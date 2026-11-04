# Deadlock
- Necessary conditions: mutual exclusion, hold and wait, no preemption, circular wait
- Resource allocation graph: cycle -> possible deadlock (certain if single instance)
- Prevention: break one of the four conditions (e.g. resource ordering)
- Avoidance: Banker's algorithm, keep the system in a safe state
- Detection & recovery: kill processes or preempt resources
