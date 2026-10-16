# grill-nodeJS

Node.js 系统学习路径。grill-me 模式：苏格拉底式追问，锚定主题本身（语言语义、运行时、标准库、协议层、生态模式），不牵涉用户已有项目。

## 学习方法

- 一次一个概念，追问到底层机制
- 每轮结论落到"我以后会怎么决定"，不是"我记住了"
- 遇到自己答不出的，诚实标注 ❓，后续章节回填

## 文件索引

| 文件 | 主题 |
|---|---|
| `01-event-loop.md` | 事件循环：宏任务/微任务、phases、setImmediate 陷阱 |
| `02-modules.md` | CommonJS vs ESM：加载机制、循环依赖、__dirname 消失 |
| `03-streams.md` | Streams 与 backpressure：四种类型、pipeline 替代 pipe |
| `04-async.md` | 异步：Promise、async/await、错误传播、并发控制 |
| `05-buffers.md` | Buffer 与编码：Uint8Array、字符串边界、性能陷阱 |
| `06-http.md` | HTTP 层：http/https、keep-alive、代理、chunked |
| `07-process.md` | process 与 worker：cluster、worker_threads、V8 isolate |
| `08-packages.md` | 包管理：node 24+ 的 node:sqlite、test runner、perf_hooks |

## 当前进度

- [ ] 01-event-loop
- [ ] 02-modules
- [ ] 03-streams
- [ ] 04-async
- [ ] 05-buffers
- [ ] 06-http
- [ ] 07-process
- [ ] 08-packages
