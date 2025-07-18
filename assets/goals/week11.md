- Lab 8, Exercise 1
   - Run GPU code on Roar Collab
   - Accelerate linear algebra computations with GPU
   - Recognize what problem sizes and likely to result in acceleration with a GPU for linear algebra
- Lab 8, Exercise 2:
   - Learn to write a GPU kernel, using [KernelAbstractions.jl](https://juliagpu.github.io/KernelAbstractions.jl/stable/)
   - Improve performance by reducing memory transfers via GPU reductions
   - Perform custom scientific computations using high-level GPU interface, such as
      + `map` or `mapreduce` on [`CuArray`](https://cuda.juliagpu.org/stable/usage/array/) from [CUDA.jl](https://cuda.juliagpu.org/stable/) (recommended), or
      + [Folds.jl](https://juliafolds.github.io/Folds.jl/dev/) with `CUDAEx()` executor from [FoldsCUDA.jl](https://juliafolds.github.io/FoldsCUDA.jl/dev/)
   - Improve performance through reduced memory allocations
   - Recognize what types of problems and problem sizes are likely to result in acceleration with a GPU  when using a high-level programming interface or custom GPU kernel
- Project
   - Parallelize real world code
   - Achieve significant performance benefit via parallelization
