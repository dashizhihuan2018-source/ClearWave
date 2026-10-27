# 澄音音乐 / ClearWave

[产品介绍与三端状态](https://dashizhihuan2018-source.github.io/ClearWave/) · [使用导览](https://dashizhihuan2018-source.github.io/ClearWave/guide.html) · [隐私与权利](https://dashizhihuan2018-source.github.io/ClearWave/rights.html)

从本地音乐出发，连接更多有权播放的声音。Rust 共享核心，原生平台薄层；不是网易云官方客户端，不承诺全网商业音乐永久免费无损。

## 本次公开范围

2026-10-28：本仓库首批仅包含独立产品网站、宣传海报视觉草案、字体许可及公众发布状态，**不包含完整 App 源码或最终安装器**，不能据此称软件最终发布已经完成。网站图片不是 App 实拍或最终 Logo，暂无最终实操视频。

| 平台 | 当前状态 | 公开安装包 |
|---|---|---|
| macOS | arm64 / macOS 14 起的 Mac Catalyst 本机技术预览已安装启动；ad-hoc 非 Developer ID、未公证，完整 GUI 验收与最终发行候选仍待交接 | 无 |
| Windows | 尚未交付目标平台 App 与运行证据 | 无 |
| iOS / iPadOS | Rust + SwiftUI / AVFoundation 开发候选；既有设备构建未签名，真机验收未完成 | 无 |

历史模拟器通过记录不等于三端交付。iPad XCTest 间歇性动画 idle 超时仍未闭合。没有发布软件 Release 或最终版本标签；没有模拟器包冒充手机安装器。

## 后续成对发布

最终候选冻结后，按允许清单同步完整原创产品源、测试、资源与构建脚本，保留必要第三方 LICENSE / NOTICE 与编译契约，不保留自有开发注释。安装包、源提交/标签、源码归档、系统/架构、签名、字节数和最终 SHA-256 分别固定并回读。

不会把内部研究提取物、第三方原 App、用户音乐、账号设置、访问票据、系统诊断、内部交接或凭据加入公开镜像。源码公开不自动授予开源许可；应用使用/修改/再分发条款尚待明确。见 [版权范围](COPYRIGHT.md)。

## 网站源码

静态网页在 `docs/`，无构建、登录、付款、统计或上传服务。可用静态 HTTP 服务预览。所有资源采用相对路径；GitHub Pages 发布来源为 `main:/docs`。现有机器可读状态在 [release-status.json](docs/release-status.json)，其中 App 产物与源码提交为空是实际未发布状态，不是占位下载。

网站标题字形来自 Adobe Source Han Serif Bold；派生子集重命名为 ClearWaveTitle Bold，依 OFL-1.1，详见 [字体来源](docs/fonts/provenance.json) 与 [完整许可](docs/fonts/OFL.txt)。海报由内置 ImageGen 生成，仅是候选构图，不是真实字体排版、最终 Logo 或应用截图。见 [媒体来源](MEDIA.md)。

© 2026 Nankong。各第三方权利独立适用。
