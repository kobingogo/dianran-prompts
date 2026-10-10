# 点染提示词资源

点染公开提示词快照。JSON、清单及 WebP 封面位于 prompt-sources/；维护状态位于 data/，报告位于 reports/。

采集与发布脚本保留在 [点染主仓库](https://github.com/kobingogo/dianran/tree/main/brand/pipeline)。维护者设置 DIANRAN_PROMPT_PIPELINE_ROOT 指向本仓库，在主仓库运行脚本。临时采集文件与日志位于忽略的 candidates/。

Vercel 仅发布 prompt-sources/，主站通过 /prompt-sources/* 访问。条目和封面权利归原作者，来源与授权见 [LICENSES.md](prompt-sources/LICENSES.md)。
