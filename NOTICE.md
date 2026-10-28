# 署名、来源与许可

本仓库分别发行 **Mac 应用与网页广告过滤器**。适配者：hclchcl；适配及独立发行日期：2026-10-28。

规则整理者：blackmatrix7。原项目：[blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)。适用许可为该项目的 GNU GPL v2。所选原文和不可变来源链接随 `sources/` 提供。

上游说明列出的来源包括 [ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)、[NobyDa/ND-AD](https://github.com/NobyDa/ND-AD)、[NobyDa/Script](https://github.com/NobyDa/Script)、[yjqiang/surge_scripts](https://github.com/yjqiang/surge_scripts)、[GeQ1an/Rules](https://github.com/GeQ1an/Rules)、[GFBG-IT/QuantumultX](https://github.com/GFBG-IT/QuantumultX)，以及 blackmatrix7 仓库内的原始规则。感谢原作者；本项目不把规则选集宣称为全部原创。

适配内容：选取专用广告域名和按服务的广告路径，收窄路径匹配，转为原生 Rewrite 并精确列出 MitM 主机；没有完整复制 iOS 插件、猜测 JSON 结构或修改会员/账号权限。逐条原文与修改见 [rewrite-selection.json](sources/rewrite-selection.json)。

上游的提交、文件 Git blob SHA、原始更新时间及链接见 [manifest.json](sources/manifest.json)。本次发行日期不代表每条上游规则均更新到该日期。

本项目参考可莉插件展示的功能方向，没有复制、解密或再分发可莉的 `.lpx` 文件，不是原作者的官方 Mac 移植。

插件以可编辑明文发行，按 [GPL-2.0](LICENSE) 许可。重新分发修改版时请保留适用署名、许可及修改说明。本仓库不适用原 DNS 项目的 MIT 许可。

Loon 语法依据：[插件](https://nsloon.app/docs/Plugin/)、[逻辑规则](https://nsloon.app/docs/Rule/logic_rule/)、[原生 Rewrite](https://nsloon.app/docs/Rewrite/rewrite_v2/)。

未进行实机效果测试，不提供覆盖全部应用的效果保证。
