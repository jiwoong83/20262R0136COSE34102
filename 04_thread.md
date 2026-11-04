# Thread
- Thread = unit of CPU execution; shares code/data/files, has own stack, registers, PC
- Benefits: responsiveness, resource sharing, economy, scalability on multicore
- Concurrency (interleaving) vs parallelism (truly simultaneous)
- Models: many-to-one, one-to-one (Linux), many-to-many
- Pthreads: pthread_create, pthread_join
- Amdahl's law: speedup <= 1 / (S + (1-S)/N), S = serial portion
