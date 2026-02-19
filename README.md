# Voronoi-triangulation-example

## Installation

### Juliagebra
Download JuliaGLM https://github.com/Csabix/JuliaGLM and Juliagebra https://github.com/Csabix/Juliagebra if not merged download Juliagebra from this branch https://github.com/Csabix/Juliagebra/tree/segment_sequence

Navigate into the JuliaGLM folder
```
julia
julia> ]
(@v1.12) pkg> dev .
```

In Juliagebra folder
```
julia
julia> ]
(@v1.12) pkg> activate .
(Juliagebra) pkg> add ..\JuliaGLM <--- path to JuliaGLM folder
(@v1.12) pkg> dev .
```

Additionally you need DelaunayTriangulation.jl dependency for this specific example
```
julia
julia> ]
(@v1.12) pkg> add DelaunayTriangulation
```

Finally you can run the file ``` julia .\voronoi.jl ```
