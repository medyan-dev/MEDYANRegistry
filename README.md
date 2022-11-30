# MEDYANRegistry
Julia package registry for medyan-dev

See https://github.com/HolyLab/HolyLabRegistry for more details on how to use and update this registry.

# Usage

If you're using at least Julia 1.1, then you can add this registry with

```
]registry add git@github.com:medyan-dev/MEDYANRegistry.git
```

(The `]` enters Pkg mode when you type it at the REPL prompt, see https://docs.julialang.org/en/v1/stdlib/Pkg/.)

For earlier Julia versions, manually `git clone` this repository under `DEPOT_PATH/registries`. (Usually, `DEPOT_PATH = /home/username/.julia`)

Then, we can use lab private packages (or unregistered public ones) as if they are registered ones.
