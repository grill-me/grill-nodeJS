# 01 · 事件循环（Event Loop）

Node.js 的运行时基石。所有"异步"最终都在这里被调度。

## 学习目标

- 说出 event loop 的 phase 顺序，以及每个 phase 处理什么
- 解释 `setTimeout(fn, 0)` 为什么不真的 0ms，以及 minimum delay
- 说清 microtask queue 与 macrotask queue 的边界（Promise.then 属于哪边）
- 解释 `setImmediate` vs `process.nextTick` vs `Promise.then` 谁先跑
- 给出一个真实代码的调度顺序预测，并能自证

---

## Grill 01.1 · 启动

**Q1**：Node.js 为什么不是每个请求一个线程？

不要只答"因为轻"。说出**具体机制**：libuv + V8 的线程模型是怎么分工的。
