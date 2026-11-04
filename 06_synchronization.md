# Synchronization
- Race condition: result depends on execution order of shared data access
- Critical section requirements: mutual exclusion, progress, bounded waiting
- Peterson's solution (2 processes), hardware: test_and_set, compare_and_swap
- Mutex lock (busy wait = spinlock), semaphore (wait/signal, counting/binary)
- Monitor + condition variables (wait/signal)
