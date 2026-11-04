# Process
- Process = program in execution (code, data, heap, stack + CPU state)
- States: new -> ready -> running -> waiting -> terminated
- PCB: pid, state, PC, registers, scheduling info, memory info, open files
- Context switch: save PCB of old process, load PCB of new one (pure overhead)
- fork(): child is a copy of parent, returns 0 to child, child's pid to parent
- exec(): replaces the process image; wait(): parent waits for child exit
- Zombie: exited but not yet waited; Orphan: parent exited first (adopted by init)
