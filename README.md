# DCorbinJLReg

A public registry containing Julia packages relating to my PhD research at the Univeristy of Bristol. The packages hosted here are in-development, so I
provide no guarantee that they will function as intended. Once packages are ready for release, all subsequent versions will be released via the
Julia General registry.

## Quick Start

To access all packages in this registry, simply run

```julia
using Pkg
Pkg.Registry.add(RegistrySpec(url = "https://github.com/dfcorbin/DCorbinJLReg"))
```

Once this step is completed, any hosted package can be added via

```julia
using Pkg
Pkg.add("$PKG_NAME")
```

## Expired Packages

I will list here all the packages which have transitioned to the Julia General Registry.

- Nothing yet.
