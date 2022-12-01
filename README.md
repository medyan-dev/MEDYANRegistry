# MEDYANRegistry
Julia package registry for medyan-dev

See https://github.com/HolyLab/HolyLabRegistry and https://github.com/GunnarFarneback/LocalRegistry.jl for more details on how to use and update this registry.

## Installation for MEDYAN users.

```julia
using Pkg; pkg"registry add https://github.com/medyan-dev/MEDYANRegistry.git"
```

## Installation for MEDYAN package developers.

If you want to be able to update the registry with https://github.com/GunnarFarneback/LocalRegistry.jl

use the ssh version.

```julia
using Pkg; pkg"registry add git@github.com:medyan-dev/MEDYANRegistry.git"
```


