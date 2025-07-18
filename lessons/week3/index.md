+++
title = "Week 3: Software Design"
course_inst = "Penn State"
course_number = "Astro 528"
course_name = "High-Performance Scientific Computing for Astrophysics"
weight = 03101  #wwdpp

chapter= true

creatordisplayname = "Eric Ford"
creatoremail = "ebf11 at psu dot edu"
lastmodifierdisplayname = "Eric Ford"
lastmodifieremail = "ebf11 at psu dot edu"
tags = ["weekly",]
+++

# Week 3
## Goals
\textinput{goals/week3}

## Lessons along the way
- Big-O notation
- File formats: CSV, FITS, HDF5, JLD2
- Calling Python from Julia

## Readings
\textinput{reading/week3}

## Lab
\textinput{labs/lab3}

## Additional Resources
- [Monday Discussion](https://psuastro528.github.io/Notes-Fall2023/week3/week3_discuss.html):  Priorities for Scientific Computing: Correctness, Documentation
- [Wednesday Q&A](https://psuastro528.github.io/Notes-Fall2023/week3/week3_qa.html): Two-language Problem, Expert vs Non-Expert Interfaces

- File Formats
   - [FITSIO library written in C](https://heasarc.gsfc.nasa.gov/fitsio/)
   - [HDF5](https://www.hdfgroup.org/solutions/hdf5/)
   - [Apache Arrow](https://arrow.apache.org/)
- Julia packages for reading files
   - Julia's [FileIO.jl](https://github.com/JuliaIO/FileIO.jl) high-level API
   - Julia's [JLD2.jl package](https://github.com/JuliaIO/JLD2.jl)
   - Julia's [HDF5.jl package](https://github.com/JuliaIO/HDF5.jl)
   - Julia's [FITSIO.jl package](https://github.com/JuliaAstro/FITSIO.jl)
   - Julia's Apache [Arrow.jl](https://github.com/JuliaData/Arrow.jl) implementation
   - [Feather.jl](http://juliadata.github.io/Feather.jl/stable/)
   - [PyCall.jl documentation](https://github.com/JuliaPy/PyCall.jl#types).
- [Querying DataFrames](https://dataframes.juliadata.org/stable/man/querying_frameworks/)
   - [Query.jl](http://www.queryverse.org/Query.jl/stable/gettingstarted/)
   - [DataFramesMeta.jl](https://github.com/JuliaData/DataFramesMeta.jl))
   - [JuliaDB.jl](https://github.com/JuliaData/JuliaDB.jl)
- Miscelaneous
   - [Regular expressions in julia](https://docs.julialang.org/en/v1/manual/strings/index.html#Regular-Expressions-1)
   - [Astropy](http://docs.astropy.org)
- Julia
   - [Julia Manual](http://docs.julialang.org/en/v1/)
   - [Think Julia: How to Think Like a Computer Scientist](https://benlauwens.github.io/ThinkJulia.jl/latest/book.html)
   - [Learn Julia in Y Minutes](https://learnxinyminutes.com/docs/julia/)
