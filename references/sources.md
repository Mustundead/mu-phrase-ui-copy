# 资料与取舍

本技能以 MU LABS 的产品写作选择为主，相关平台资料用于校对具体问题。没有转载第三方技能正文、Apple 演讲逐字稿、图像或示例代码。外部页面保持各自权利与条款，MIT 仅适用于本仓库新写的内容。

| 资料 | 解决的问题 | 采用和保留的边界 |
| --- | --- | --- |
| [Writing for interfaces · WWDC22](https://developer.apple.com/videos/play/wwdc2022/10037/) | 文本何时出现、服务什么目的 | 采用使用者场景、品牌声音、情境语气和多语言空间的判断；不要求产品模仿 Apple 的声音或照搬弹窗按钮顺序。 |
| [Apple HIG](https://developer.apple.com/design/human-interface-guidelines/) | 原生控件与系统约定 | 改动涉及的平台/系统术语才定向查询；不把本技能偏好称为系统要求。 |
| [Apple Localization](https://developer.apple.com/localization/) | 多语言资源与交付 | 根据项目实际工具链查询；不为了文字修改迁移资源系统。 |
| [W3C WAI: Accessible Names and Descriptions](https://www.w3.org/WAI/ARIA/apg/practices/names-and-descriptions/) | Web 控件的名称与描述 | 检查可见名称和可访问名称；不盲目给所有原生控件覆盖 aria-label。 |
| [WCAG 2.2 Reflow](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html) | Web 文字放大与重排时关键事实是否仍可见 | 用于相关 Web 页的重排验证；320 CSS px 及例外属于 Web 准则，不换算为原生 point，也不凭单例宣称整体符合。 |

首版资料核对：2026-09-22（WWDC22 演讲页面）。2026-10-01 的增补依据定向研究记录，覆盖 WWDC22、W3C 名称与重排正文；其他链接为定向查阅入口，不代表逐条平台认证。

旧的个人工作流名称 `apple-interface-copy` 仅作为迁移说明。本项目重新组织了指令、场景和示例，没有把来源未注明许可的旧文件原样收入发行包。Apple、Codex 等名称用于识别平台，不表示关联、授权或背书。
