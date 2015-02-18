# Road Networks
#############

This package supports the Road Network Defintion Format (RNDF)

[![Build Status](https://travis-ci.org/tawheeler/RoadNetworks.jl.svg?branch=master)](https://travis-ci.org/tawheeler/RoadNetworks.jl)

## Git It

You can install this package through Julia

```julia
Pkg.clone("git://github.com/tawheeler/RoadNetworks.jl.git")
```

## Use It

Load an RNDF from a file:
```julia
rndf = load_rndf("myrndf.txt")
```

The RNDF structure is captured in the next heirarchy:

* `RNDF` the root type containing all RNDF data
* `RNDF_Segment` containing a list of lanes
* `RNDF_Lane` containing lane-specific information

## Support It

For questions please contact the package creator or create an issue

Feel free to create pull requests to improve this package
