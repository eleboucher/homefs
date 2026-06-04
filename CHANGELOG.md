# Changelog

## 1.0.0 (2026-06-04)


### Features

* drbd based CSI ([027d9e3](https://github.com/eleboucher/homefs/commit/027d9e3ccd647ae3d1b26129d6af1c75f1aa1edb))
* DRBD synchronous replication (M2) ([c3d9ff0](https://github.com/eleboucher/homefs/commit/c3d9ff0cb8089bfb46bef33098efbeaacba24350))
* publish chart and image on every main push ([d53e2cb](https://github.com/eleboucher/homefs/commit/d53e2cba9f80e3d14aea69183010878152119420))
* snapshots, restore, and online expansion (M3+M4) ([39b2543](https://github.com/eleboucher/homefs/commit/39b25432151e864c51b101dbe50233d2864c2e6b))


### Bug Fixes

* correct registry and module paths to eleboucher ([2ae3d06](https://github.com/eleboucher/homefs/commit/2ae3d0645bda78a49c42ac723f77e690a9268835))
* drop per-command --noudevsync, rely on lvmlocal.conf ([86fc4da](https://github.com/eleboucher/homefs/commit/86fc4da67ace05bbb6680cc8038857286281d3ba))
* end-to-end flow review findings ([ae8c96f](https://github.com/eleboucher/homefs/commit/ae8c96f6c31d4a124d81e77062f4fc8b82e4f711))
* snapshot flush barrier and real sidecar image tags ([8f9da5c](https://github.com/eleboucher/homefs/commit/8f9da5cc995194055d87b65500f35dc300280526))
