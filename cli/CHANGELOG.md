# Changelog

### [0.3.1](https://www.github.com/grain-lang/grain/compare/cli-v0.3.0...cli-v0.3.1) (2021-04-29)


### Bug Fixes

* **cli:** Correct typo in lsp catch block ([#618](https://www.github.com/grain-lang/grain/issues/618)) ([b903ced](https://www.github.com/grain-lang/grain/commit/b903ced32ad7a6a2055a73473921e791adfd6ae4))

## [0.3.0](https://www.github.com/grain-lang/grain/compare/cli-v0.2.0...cli-v0.3.0) (2021-04-21)


### ⚠ BREAKING CHANGES

* **cli:** Remove `-f` CLI option
* **compiler:** Remove --principal-types and --recursive-types compiler flags
* **compiler:** Rename --cdebug to --verbose
* **cli:** Pass compiler flags from the CLI to grainc directly (#613)
* Rework memory management (#461)

### Features

* allow setting the initial memory via CLI option ([#448](https://www.github.com/grain-lang/grain/issues/448)) ([213ee5a](https://www.github.com/grain-lang/grain/commit/213ee5a2736a71eb6a62a28bd60f338e196ea265))
* **cli:** Pass compiler flags from the CLI to grainc directly ([#613](https://www.github.com/grain-lang/grain/issues/613)) ([8f40383](https://www.github.com/grain-lang/grain/commit/8f40383af23b236b0333032bba193c39757d2569))
* Compile grainc to JS & create binaries with pkg ([#570](https://www.github.com/grain-lang/grain/issues/570)) ([f4919bd](https://www.github.com/grain-lang/grain/commit/f4919bdbab7dddd433b3f53bf8a8536a7efd5b03))
* Grain implementation of memory manager ([#534](https://www.github.com/grain-lang/grain/issues/534)) ([cea6dcc](https://www.github.com/grain-lang/grain/commit/cea6dccaf45e8bdd07eb6c674f30c53a50f37a19))
* Grain implementation of toString/print ([#540](https://www.github.com/grain-lang/grain/issues/540)) ([8c77905](https://www.github.com/grain-lang/grain/commit/8c779059c4a2a71d0ccacc51d946dde2d48d6623))
* Use real wasm tail call instruction ([#510](https://www.github.com/grain-lang/grain/issues/510)) ([9c9ffe4](https://www.github.com/grain-lang/grain/commit/9c9ffe48d78ed315f0a406d704c7a0fdbb116f1f))


### Bug Fixes

* replace shebang trick with flagged-respawn to support Windows ([#430](https://www.github.com/grain-lang/grain/issues/430)) ([4ea2602](https://www.github.com/grain-lang/grain/commit/4ea26021d270adc542736efa90093d2f2cdbef5b))
* Rework memory management ([#461](https://www.github.com/grain-lang/grain/issues/461)) ([84318b0](https://www.github.com/grain-lang/grain/commit/84318b01a21137492e9728f346680225f1d1ea9a))


### Miscellaneous Chores

* **cli:** Remove `-f` CLI option ([8f40383](https://www.github.com/grain-lang/grain/commit/8f40383af23b236b0333032bba193c39757d2569))
* **compiler:** Remove --principal-types and --recursive-types compiler flags ([8f40383](https://www.github.com/grain-lang/grain/commit/8f40383af23b236b0333032bba193c39757d2569))
* **compiler:** Rename --cdebug to --verbose ([8f40383](https://www.github.com/grain-lang/grain/commit/8f40383af23b236b0333032bba193c39757d2569))
