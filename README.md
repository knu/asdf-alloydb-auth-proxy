# asdf-alloydb-auth-proxy

This is the [AlloyDB Auth proxy](https://github.com/GoogleCloudPlatform/alloydb-auth-proxy) plugin for the [asdf](https://github.com/asdf-vm/asdf) version manager.

It fetches and installs a single binary for the running platform.  Building from the source is currently not implemented.

## Install

```sh
asdf plugin-add alloydb-auth-proxy https://github.com/knu/asdf-alloydb-auth-proxy.git

asdf list-all alloydb-auth-proxy

asdf install alloydb-auth-proxy x.y.z
asdf local alloydb-auth-proxy x.y.z
```

## Author

Copyright (c) 2023 Akinori MUSHA.

Licensed under the 2-clause BSD license.  See `LICENSE.txt` for details.

Visit [GitHub Repository](https://github.com/knu/asdf-alloydb-auth-proxy) for the latest information.
