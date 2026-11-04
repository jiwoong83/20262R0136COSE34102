# OS Overview
- OS = resource manager + control program between user programs and hardware
- Dual mode: user mode / kernel mode, switched by system calls, interrupts, exceptions
- System call: user program's interface to request kernel services (e.g. read, write, fork)
- Interrupt-driven: hardware raises interrupt -> CPU saves state -> ISR runs -> resume
