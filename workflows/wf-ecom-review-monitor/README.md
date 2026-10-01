# 评价流实时监控与分级

> 评价抓取→情感分析→分级推送

工作流 `wf-ecom-review-monitor`　·　归属 评价管理与差评拦截　·　触发 定时（每 30 分钟）　·　
复杂度 M　·　阶段 P0

## 调用链

- `评论情绪识别`（review-sentiment-tag）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 评价管理与差评拦截 的「评价流实时监控与分级」：<你的输入>
```
