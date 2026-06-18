# Changelog

## 1.0.0 (2026-06-18)


### Features

* add loopfile backend storing volumes as loop-backed sparse files ([0c8bd92](https://github.com/eleboucher/homefs/commit/0c8bd9232f158382b64b99bfa55c68fb78deb9da))
* drbd based CSI ([1002809](https://github.com/eleboucher/homefs/commit/1002809fa94ab54dcb7e442229503f23e757f885))
* DRBD synchronous replication ([52ceb00](https://github.com/eleboucher/homefs/commit/52ceb00c20683043e09124e820d1c858aeb60cb8))
* name the metrics ports for scrape discovery ([f1a0390](https://github.com/eleboucher/homefs/commit/f1a039037d8747d26a0978866a8a169e10a20902))
* publish chart and image on every main push ([c5cb86c](https://github.com/eleboucher/homefs/commit/c5cb86cd0544d39230bcf437a8176fc02ed1bcc9))
* reconcile replica membership edits on live volumes ([3b46b1e](https://github.com/eleboucher/homefs/commit/3b46b1e412cea09a3925fe33d07b70dc2f52248e))
* snapshots, restore, and online expansion ([3b520d9](https://github.com/eleboucher/homefs/commit/3b520d974d3aff3db0e252c07cbdb5e3caa18d53))


### Bug Fixes

* correct registry and module paths to eleboucher ([b676cba](https://github.com/eleboucher/homefs/commit/b676cbad4c1b1d42245555aa2e4b6c643533d2f8))
* crash-safe GI seeding and well-defined drbdmeta addressing ([3ec244d](https://github.com/eleboucher/homefs/commit/3ec244d0daa6aeb16ea5fba90b5a1f6a7802045f))
* drop per-command --noudevsync, rely on lvmlocal.conf ([80084cb](https://github.com/eleboucher/homefs/commit/80084cb6112363dcc45e5d1cf63a40274095b3e0))
* echo ContentSource on snapshot-restore CreateVolume ([b48da8a](https://github.com/eleboucher/homefs/commit/b48da8a39b0c7c6de7c58faed9c566c747c4eeac))
* end-to-end flow review findings ([3d072e9](https://github.com/eleboucher/homefs/commit/3d072e981a709edf55c0283db52fdc8af746ac08))
* goconst findings from the pinned linter version ([8b3d6bf](https://github.com/eleboucher/homefs/commit/8b3d6bfb8bfd0b9cfce93a971d7f48cb3b123eff))
* keep snapshot LV names out of LVM's reserved namespace ([ca3183e](https://github.com/eleboucher/homefs/commit/ca3183ee75eabec4adb3025b50c882cbdc7832d7))
* raise controller provision timeout to match csi-provisioner sidecar ([cd26cc9](https://github.com/eleboucher/homefs/commit/cd26cc93a0a521961c9af8031820fad82ed9910e))
* replay the activity log before probing cloned metadata ([61d5f3f](https://github.com/eleboucher/homefs/commit/61d5f3fa47133809f756bf3c79bfde0fabab513c))
* resolve ZFS clone dependencies and reactivate restored LVs ([636e784](https://github.com/eleboucher/homefs/commit/636e78472b58f09411b7147a4b9dfaebb78a2434))
* route the snapshot write barrier through drbdadm ([39bc85a](https://github.com/eleboucher/homefs/commit/39bc85a948ae3924992d67a69178eab82ac920f3))
* setup mode exits after pool ready, clear managedFields for SSA ([b68e848](https://github.com/eleboucher/homefs/commit/b68e8482717f42b19cc8f857879d6e6686ce4f1c))
* snapshot flush barrier and real sidecar image tags ([b8bd894](https://github.com/eleboucher/homefs/commit/b8bd89406ca2ce9b0fa82c331f5b2f02ce031dec))
