# Changelog

## [3.2.1](https://github.com/znarfm/bing-rewards/compare/v3.2.1...v3.2.1) (2025-07-06)


### chore

* release 3.2.1 ([e8b73bd](https://github.com/znarfm/bing-rewards/commit/e8b73bd22a6281d25b701e215909bc5f725ea371))


### Features

* enable color argparse help on python &gt;= 3.14 ([98ad897](https://github.com/znarfm/bing-rewards/commit/98ad897e4d3121d0fe1b3fb306f453de68a2afdf))
* enhance browser subprocess termination ([#61](https://github.com/znarfm/bing-rewards/issues/61)) ([d902ecd](https://github.com/znarfm/bing-rewards/commit/d902ecd81b68d47e8000ad814b56b5929fe771b0))
* removed some potentially objectionable random search terms ([#87](https://github.com/znarfm/bing-rewards/issues/87)) ([2f08693](https://github.com/znarfm/bing-rewards/commit/2f08693666c1b6d4ca5e5dcfa064c7a8d8278cb8))
* search-delay option can specify a random range to delay ([#63](https://github.com/znarfm/bing-rewards/issues/63)) ([fc82c11](https://github.com/znarfm/bing-rewards/commit/fc82c1116f58dc372994bba52eea93546ac6aa88))
* skip verifying browser path when --no-window flag is used ([8e98011](https://github.com/znarfm/bing-rewards/commit/8e9801102b484442e247435bf8b5e36c1096ed30))
* support and test on Python 3.14 ([b018261](https://github.com/znarfm/bing-rewards/commit/b018261690fe6ec41f9957e8835f8a9410024373))
* support multiple Chrome profiles for sequential runs ([#55](https://github.com/znarfm/bing-rewards/issues/55)) ([bba536e](https://github.com/znarfm/bing-rewards/commit/bba536eb57735c393feaedb9b6cc90247b0ce920))
* validate that the browser path exists on a dryrun ([b656340](https://github.com/znarfm/bing-rewards/commit/b6563400c4e21a6657bd0133702136d206ae30f0))


### Bug Fixes

* absolute path to script in help output on python &gt;= 3.14 ([98ad897](https://github.com/znarfm/bing-rewards/commit/98ad897e4d3121d0fe1b3fb306f453de68a2afdf))
* **ci:** remove $schema from release-please-manifest ([f3decf5](https://github.com/znarfm/bing-rewards/commit/f3decf5f051b570bde3de1fde80d315fc2c34027))
* improve word generation cyclic file reading ([#54](https://github.com/znarfm/bing-rewards/issues/54)) ([4f018ca](https://github.com/znarfm/bing-rewards/commit/4f018ca618f0f6d87bd3ebc3de90eb923144805c))
* refactor config and args into options module ([f2da5db](https://github.com/znarfm/bing-rewards/commit/f2da5db5efb19e5aa3e4b420457d428107610810))
* refactor open/close browser in search() function ([5a44749](https://github.com/znarfm/bing-rewards/commit/5a447492f457c73edf5c1b7d102776faeb5248f4))
* workaround for pyinput browser interactions on Wayland ([#59](https://github.com/znarfm/bing-rewards/issues/59)) ([56d92c8](https://github.com/znarfm/bing-rewards/commit/56d92c84ce2b476c4e1b05f1c51718162a033a51)), closes [#58](https://github.com/znarfm/bing-rewards/issues/58)


### Documentation

* add disclaimer in README ([678f98e](https://github.com/znarfm/bing-rewards/commit/678f98e025e2072ac43f8ecdabf46076fa7ff576))
* add UV to install instructions ([64ec334](https://github.com/znarfm/bing-rewards/commit/64ec33447c34733505fcb1418c0e2700fdcc046f))


### Build System

* ditch dynamic vcs versioning ([6a4af97](https://github.com/znarfm/bing-rewards/commit/6a4af97cfabca11c6c34696f74a09606dfe38736))
* make releaseplease also bump version in uv.lock ([008a9e2](https://github.com/znarfm/bing-rewards/commit/008a9e2b3522eb572504ee72526b6ab9f65229bd))
* switch to the new uv_build backend for wheels and sdist ([35b6bd7](https://github.com/znarfm/bing-rewards/commit/35b6bd7905acd5f81b6a8fe5a62e225279d2ee82))
* use UV for project & dep management ([9d65882](https://github.com/znarfm/bing-rewards/commit/9d658825c4c4fe617b8d224221cbbfc24a4515ec))


### Continuous Integration

* add release-please workflow ([2fe5143](https://github.com/znarfm/bing-rewards/commit/2fe514376fab3dbfa34ce4cafc049955320b5f67))
* Use the ruff action for linting ([e288ec7](https://github.com/znarfm/bing-rewards/commit/e288ec75df2290e206b97b379153b79c25da99ae))

## [3.2.1](https://github.com/jack-mil/bing-rewards/compare/v3.2.0...v3.2.1) (2025-06-20)


### Changes

* removed some potentially objectionable random search terms ([#87](https://github.com/jack-mil/bing-rewards/issues/87)) ([2f08693](https://github.com/jack-mil/bing-rewards/commit/2f08693666c1b6d4ca5e5dcfa064c7a8d8278cb8))

## [3.2.0](https://github.com/jack-mil/bing-rewards/compare/v3.1.0...v3.2.0) (2025-06-01)


### Features

* enhance browser subprocess termination ([#61](https://github.com/jack-mil/bing-rewards/issues/61)) ([d902ecd](https://github.com/jack-mil/bing-rewards/commit/d902ecd81b68d47e8000ad814b56b5929fe771b0))
* search-delay option can specify a random range to delay ([#63](https://github.com/jack-mil/bing-rewards/issues/63)) ([fc82c11](https://github.com/jack-mil/bing-rewards/commit/fc82c1116f58dc372994bba52eea93546ac6aa88))
* skip verifying browser path when --no-window flag is used ([8e98011](https://github.com/jack-mil/bing-rewards/commit/8e9801102b484442e247435bf8b5e36c1096ed30))
* support and test on Python 3.14 ([b018261](https://github.com/jack-mil/bing-rewards/commit/b018261690fe6ec41f9957e8835f8a9410024373))


### Bug Fixes

* **ci:** remove $schema from release-please-manifest ([f3decf5](https://github.com/jack-mil/bing-rewards/commit/f3decf5f051b570bde3de1fde80d315fc2c34027))


### Documentation

* add UV to install instructions ([64ec334](https://github.com/jack-mil/bing-rewards/commit/64ec33447c34733505fcb1418c0e2700fdcc046f))


### Build System

* ditch dynamic vcs versioning ([6a4af97](https://github.com/jack-mil/bing-rewards/commit/6a4af97cfabca11c6c34696f74a09606dfe38736))
* make releaseplease also bump version in uv.lock ([008a9e2](https://github.com/jack-mil/bing-rewards/commit/008a9e2b3522eb572504ee72526b6ab9f65229bd))
* use UV for project & dep management ([9d65882](https://github.com/jack-mil/bing-rewards/commit/9d658825c4c4fe617b8d224221cbbfc24a4515ec))


### Continuous Integration

* add release-please workflow ([2fe5143](https://github.com/jack-mil/bing-rewards/commit/2fe514376fab3dbfa34ce4cafc049955320b5f67))
* Use the ruff action for linting ([e288ec7](https://github.com/jack-mil/bing-rewards/commit/e288ec75df2290e206b97b379153b79c25da99ae))
