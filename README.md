# 论文导读 · Math Paper Guide

可独立安装的数学论文导读 skill。以逻辑关系图解释论文的论证、前人研究和引文用途，保留原文术语、符号与结果编号。完整导读默认生成本地交互式网站，交付入口 HTML、所需资源和可编辑源码。

Skill 位于 [`skills/math-paper-guide`](skills/math-paper-guide)，使用说明见其 [README](skills/math-paper-guide/README.md)。

调用示例：

> 使用 $math-paper-guide，为这篇论文制作中文交互式导读。以逻辑关系图解释关键论证、前人研究与引文用途，保留原文术语和编号。

网站围绕论文及其论证组织。导航、搜索、节点选择和局部展开服务于阅读；课程、学习任务和进度管理仅在用户提出需求时加入。

逻辑关系直接依据原始 statements、hypotheses 和 proof passages 建立。对于引用的外部结果，明确区分已核查的 proof dependency、背景引文与尚未核查的候选输入。来源或浏览器检查不可用时，报告实际缺口。

只有用户明确要求 Sites 私有托管，且具有相应能力时，才采用 ChatGPT Sites 的私有托管流程；仍保留本地网页和可编辑源码。制作、预览或保存网页本身不请求在线托管。
