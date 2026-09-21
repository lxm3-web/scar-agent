# scar-agent — 品保 SCAR 專員（Agent 版）

claude.ai/code 選這個 repo（或本機 `claude`）→ 說「品保主管的指示在 inbox，該開的 SCAR 開一開」→ 供應商統計、每家一份 SCAR、寄件信、回覆追蹤表、內部月報寫到 `outbox/` → 看完說「好，發下去」。

公司與供應商皆為課堂虛構。**demo 完歸零**：`inbox/*.done` 改回 `.txt`、清 `outbox/`、log 只留表頭。
