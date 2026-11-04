# Virtual Memory
- Demand paging: load page only on page fault
- Copy-on-write makes fork() cheap
- Page replacement: FIFO (Belady's anomaly), OPT, LRU, clock (second chance)
- Thrashing: too little memory per process; working-set model / PFF to control
