# Inter-Process Communication
- Shared memory: fast, but processes must synchronize themselves
- Message passing: send/receive via kernel, easier but slower
- Blocking (synchronous) vs non-blocking (asynchronous) send/receive
- Pipes: ordinary pipe (parent-child, unidirectional), named pipe (FIFO)
- Producer-consumer with bounded buffer as the classic example
