# CPU Scheduling
- Criteria: CPU utilization, throughput, turnaround, waiting, response time
- FCFS: simple, convoy effect
- SJF / SRTF: optimal average waiting time, needs burst prediction (exponential averaging)
- Priority: starvation -> aging
- Round Robin: time quantum q; large q ~ FCFS, small q -> many context switches
- Multilevel (feedback) queue: move processes between queues by behavior
- Linux CFS: picks task with smallest virtual runtime (red-black tree)
