# Aurelia PPT Studio

**制作没有AI味的PPT：根据研究材料组织论点，用可编辑图表和图解讲清重点。**

## 下载 v2.1.0

[下载完整 skill 便携包](https://github.com/tianxiangzhang732-del/aurelia-ppt-studio/raw/refs/heads/main/Aurelia-PPT-Studio-v2.1.0-portable.zip)。解压后得到 `aurelia-ppt-studio/`，其中的 `SKILL.md` 是入口。仓库是便携包分发页；直接下载仓库源码 ZIP 会多一层压缩，优先用前面的链接。

## 它怎样做 PPT

- 从研究材料中提炼结论，保留关键数字、时间、统计口径和原文页码。
- 根据内容关系选图：用对比图解释差异，用流程图解释机制，用原生图表呈现数据，不让每页都变成一排文字卡片。
- 新建整稿时，先展示 6–7 个方向的封面和实质内容页；选择方向后再扩展全稿。
- 交付前渲染并逐页复查，区分可编辑的文字、图表、图解和仅作为配图的图片。

## 使用

在 Codex 中，将解压后的 `aurelia-ppt-studio` 文件夹放入个人 skills 目录，再开启新任务。示例：

> 使用 Aurelia PPT Studio，把附件研究报告做成 15 页可编辑 PPTX，含封面。保留关键证据与风险；先展示风格样张供我选择。

核心检查脚本需要 Python 3.10+；PPTX 生成、渲染还需要宿主提供兼容的演示文稿引擎。包内不附带专有运行时、原始 PPT 模板、原图、客户文档或私有学习记录。其他宿主可参考方法，但 Grok Bot 的完整制作与验收链路尚未实测。

便携包 SHA-256：`9593ae6664daad6db76085331a3e05ad2e76c0d0b8ff2934fe33e3f2d7f8c61b`。
