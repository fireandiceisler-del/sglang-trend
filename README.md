# SGLang Trend Brief

持续跟踪 SGLang 中与推理基础设施最相关的四条技术主线：

- **KV Cache**：Radix Cache、HiCache、分层缓存、缓存淘汰、Prefix Cache、KV Offload
- **P/D Disaggregation**：Prefill/Decode 分离、KV 传输、异构并行、传输后端
- **Scheduler**：批调度、Overlap Scheduler、CPU 调度开销、CUDA Graph
- **Speculative Decoding**：EAGLE、Spec V2、Draft/Verify、接受率与流水线优化

## 目录

```text
daily/YYYY/MM/YYYY-MM-DD.md   # 每日重要动向
weekly/YYYY/YYYY-Www.md       # 每周趋势总结
```

## 每日简报格式

1. 今日结论
2. 重要 PR / Issue / Roadmap 更新
3. 技术影响：TTFT、TPOT、吞吐、显存、复杂度
4. 值得精读的代码与讨论
5. 与 AI Infra 面试和项目实践的关联

没有重要更新时仍会保留当天记录，并明确注明“无值得关注的架构级变化”。

## 每周总结格式

1. 本周最重要的架构变化
2. 四个方向的演进情况
3. Benchmark 与性能结论
4. 正在形成的设计趋势
5. 对工程实践和面试准备的启发
6. 下周观察清单

## 筛选原则

优先收录：

- 已合入的重要 PR
- 带性能数据或默认行为变化的改动
- 架构重构、关键数据结构变化
- 活跃 Roadmap 和高价值设计讨论

默认过滤：

- 纯模型适配
- 机械性重构
- 无架构影响的小修复
- 内容重复或缺少实质信息的更新
