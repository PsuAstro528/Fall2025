- Lab 6:  Shared Memory Computing Patterns
   - Choose an appropriate number of worker processors for your compute node & problem
   - Parallelize code using shared memory model & multiple threads, using tools such as:
      + [OhMyThreads.jl](https://juliafolds2.github.io/OhMyThreads.jl/stable/)
      + [ThreadsX.jl](https://tkf.github.io/ThreadsX.jl/dev/)
      + [Polyester.jl](https://github.com/juliasimd/Polyester.jl)
      + [FLoops.jl](https://juliafolds.github.io/FLoops.jl/dev/)
      + [Threads](https://docs.julialang.org/en/v1/manual/multi-threading/)

   - Parallelize code using shared memory model & multiple processes, using tools such as:
      + [pmap](https://docs.julialang.org/en/v1/stdlib/Distributed/#Distributed.pmap)
      + [SharedArray](https://docs.julialang.org/en/v1/stdlib/SharedArrays/)s
      + [DistributedArrays.jl](https://juliaparallel.github.io/DistributedArrays.jl/stable/) w/ using map and mapreduce
      + [@distributed for loop](https://docs.julialang.org/en/v1/stdlib/Distributed/#Distributed.@distributed)    
      + [FLoops.jl](https://juliafolds.github.io/FLoops.jl/dev/) and `DistributedEx` (recommended)
- Readings / Discussions
   - Evaluating the suitability of a problem for different parallel architectures
