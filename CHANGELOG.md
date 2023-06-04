# 1.0.0 (2023-06-04)


### Bug Fixes

* add missing xAPI object unique field identifier ([209ae81](https://github.com/philipp8101/h5p-standalone/commit/209ae812356ae9803f96b0a27ba91e1d6e3ac236))
* async task should return a promise that resolves to a val ([277b07e](https://github.com/philipp8101/h5p-standalone/commit/277b07e576dcbcb9d7b7c7ed116fec61b3f792b7))
* auto-commit changelog file via semantic release package ([6bea820](https://github.com/philipp8101/h5p-standalone/commit/6bea820dd99d83144cdf0a178a7009dde537195f))
* every step must define a `uses` or `run` key ([#69](https://github.com/philipp8101/h5p-standalone/issues/69)) ([9909179](https://github.com/philipp8101/h5p-standalone/commit/9909179b51b2f3c95a4b6ad812ecea502fae8e83))
* h5p integration postuserstatistics  is always false ([a5b8e9f](https://github.com/philipp8101/h5p-standalone/commit/a5b8e9f71d3d0edb936c48b46e4677d8967bea12))
* inject jQuery property into Iframe window [#74](https://github.com/philipp8101/h5p-standalone/issues/74) ([#75](https://github.com/philipp8101/h5p-standalone/issues/75)) ([1ec9101](https://github.com/philipp8101/h5p-standalone/commit/1ec910102d352270d2d4dda262399ba6dd57a29d))
* interactive videos causes the player to flicker  ([#68](https://github.com/philipp8101/h5p-standalone/issues/68)) ([43635c6](https://github.com/philipp8101/h5p-standalone/commit/43635c615b2a5d97f2b78c3127f2c0166c449cdf))
* Jquery empty object causing fatal error on arithmetic quiz content ([c3c0992](https://github.com/philipp8101/h5p-standalone/commit/c3c09921664d245c8d31d1a2d0f4caf76e372b64))
* merge conflict ([f5f3a29](https://github.com/philipp8101/h5p-standalone/commit/f5f3a29cb1d3ceae75bc482b1817846bb4cb5f00))
* missing metadata title while loading interactive book ([721d038](https://github.com/philipp8101/h5p-standalone/commit/721d038cb1ac49391363f5e80b6413c661d75a40))
* Node release matrix doesn't exist. Fix it to version 14 ([3cdea3c](https://github.com/philipp8101/h5p-standalone/commit/3cdea3cc2aad2de2795bd0246e622dff99650ff9))
* path parameter(s) should resolve correctly ([#73](https://github.com/philipp8101/h5p-standalone/issues/73)) ([7db44f2](https://github.com/philipp8101/h5p-standalone/commit/7db44f2975664aa5cc9a36fe350228c43d230fb8))
* properly cache the Cypress binary - Github action ([#71](https://github.com/philipp8101/h5p-standalone/issues/71)) ([c6ec1ce](https://github.com/philipp8101/h5p-standalone/commit/c6ec1ce2059988e576a7e0f5aed6926bae705ac0))
* remove duplicates loading of main library assets ([08c44e9](https://github.com/philipp8101/h5p-standalone/commit/08c44e922d6c3a7d02a87f3cbe092846d25922da))
* remove github release archive from npm release files ([f6e0b03](https://github.com/philipp8101/h5p-standalone/commit/f6e0b035042858f3c12a6dc5c9d52cbefb9918a0))
* remove github release archive from npm release files ([63ac845](https://github.com/philipp8101/h5p-standalone/commit/63ac84590f39ac23c1232e574d5536b5599055c4))
* remove Jquery dependency ([601177e](https://github.com/philipp8101/h5p-standalone/commit/601177e684f3e69ef58d09ab49c89fd823cbf74e))
* restore mistakenly deleted content id ([#72](https://github.com/philipp8101/h5p-standalone/issues/72)) ([e172cf8](https://github.com/philipp8101/h5p-standalone/commit/e172cf8a4ae0083c4770a911007ffa0c0798ddd3))
* save frequency should default to false ([3e9f329](https://github.com/philipp8101/h5p-standalone/commit/3e9f3290d85b14e24114f122a2b817c4bafe8a81))


### Code Refactoring

* H5P player constructor to accept object as second argument ([#70](https://github.com/philipp8101/h5p-standalone/issues/70)) ([7dd6503](https://github.com/philipp8101/h5p-standalone/commit/7dd6503c5878d608949e52b97b1ad20f22189f0d))


### Features

* accept override of assets fetch function ([f9ca0be](https://github.com/philipp8101/h5p-standalone/commit/f9ca0be48cc31809dbee436d738ab47895968927))
* add default fallback metadata options for interactive book type ([e4037b9](https://github.com/philipp8101/h5p-standalone/commit/e4037b98c2f7cc39ecb9d9f9a615152dd387ae90))
* add option to add embed code and/or embed resizer code ([217d093](https://github.com/philipp8101/h5p-standalone/commit/217d0936e2c53000c8776f78d7ff9aa21cc2f8aa))
* add options for custom stylesheets and scripts ([b2f3d29](https://github.com/philipp8101/h5p-standalone/commit/b2f3d299b042eca914005f437bb801cdc6835479))
* add tests for embed button option ([09e8070](https://github.com/philipp8101/h5p-standalone/commit/09e8070edd6378c356de5ded6082e56825be36d4))
* allow provision of xAPI actor statement user data ([6e05abc](https://github.com/philipp8101/h5p-standalone/commit/6e05abc3d5c3f0752003f6a55455575f7678fdf4))
* allow setting endpoint to manage current user state ([4d6d626](https://github.com/philipp8101/h5p-standalone/commit/4d6d6263093774e49ee92bd19de01ad1db843e18))
* allow user to set if to post user results ([c60456a](https://github.com/philipp8101/h5p-standalone/commit/c60456ac7b396e99cc700c4ae49e2b431b820195))
* allow user to set where post the results on finish event ([b247c46](https://github.com/philipp8101/h5p-standalone/commit/b247c460af8beb2350c50aaaf2c5c1fb87191fc3))
* allow user to specify the embed code  ([db4fcbf](https://github.com/philipp8101/h5p-standalone/commit/db4fcbf228943d048573115d1332201f8cfe3e65)), closes [#96](https://github.com/philipp8101/h5p-standalone/issues/96)
* disable npm release ([4e69712](https://github.com/philipp8101/h5p-standalone/commit/4e69712f7f2e861cfd789e8889433ba132ca9d6b))
* don't overwrite existing window h5p integration..override only ([bc5c49d](https://github.com/philipp8101/h5p-standalone/commit/bc5c49d070004a2d71130cddc7dff683b06bafc5))
* enable user to provide user previous state data ([b1d83fd](https://github.com/philipp8101/h5p-standalone/commit/b1d83fd93c750eef15169609ef11b35169a55755))
* expose full ([68b92b4](https://github.com/philipp8101/h5p-standalone/commit/68b92b402d694c0e8058c9b2bd0c3f911edee0e5))
* initial semantic-release ([e8bb0ae](https://github.com/philipp8101/h5p-standalone/commit/e8bb0ae1a16a07172caeb9979d5a7554c43b6869))
* sample jsdocs ([f2d2771](https://github.com/philipp8101/h5p-standalone/commit/f2d2771364ffcf076f20ea209888830e5aa70f4c))
* sample jsdocs ([0b39636](https://github.com/philipp8101/h5p-standalone/commit/0b39636e6a8e41fcddcefe7f299beab8e62218cd))


### BREAKING CHANGES

* Cypress binary is now cached during release action
* constructor now only accepts two arguments

* docs: specify that a user requires an extracted H5P on their workspace

* docs: update the changelog

# [3.6.0](https://github.com/tunapanda/h5p-standalone/compare/v3.5.1...v3.6.0) (2023-05-12)


### Bug Fixes

* h5p integration postuserstatistics  is always false ([a5b8e9f](https://github.com/tunapanda/h5p-standalone/commit/a5b8e9f71d3d0edb936c48b46e4677d8967bea12))


### Features

* accept override of assets fetch function ([f9ca0be](https://github.com/tunapanda/h5p-standalone/commit/f9ca0be48cc31809dbee436d738ab47895968927))
* add default fallback metadata options for interactive book type ([e4037b9](https://github.com/tunapanda/h5p-standalone/commit/e4037b98c2f7cc39ecb9d9f9a615152dd387ae90))

## [3.5.1](https://github.com/tunapanda/h5p-standalone/compare/v3.5.0...v3.5.1) (2022-05-12)


### Bug Fixes

* auto-commit changelog file via semantic release package ([6bea820](https://github.com/tunapanda/h5p-standalone/commit/6bea820dd99d83144cdf0a178a7009dde537195f))
* Node release matrix doesn't exist. Fix it to version 14 ([3cdea3c](https://github.com/tunapanda/h5p-standalone/commit/3cdea3cc2aad2de2795bd0246e622dff99650ff9))

## [3.0.3](https://github.com/tunapanda/h5p-standalone/compare/v3.0.2...v3.0.3) (2021-04-19)


### Bug Fixes

* inject jQuery property into Iframe window [#74](https://github.com/tunapanda/h5p-standalone/issues/74) ([#75](https://github.com/tunapanda/h5p-standalone/issues/75)) ([1ec9101](https://github.com/tunapanda/h5p-standalone/commit/1ec910102d352270d2d4dda262399ba6dd57a29d))


## [3.0.2](https://github.com/tunapanda/h5p-standalone/compare/v3.0.1...v3.0.2) (2021-04-19)


### Bug Fixes

* path parameter(s) should resolve correctly ([#73](https://github.com/tunapanda/h5p-standalone/issues/73)) ([7db44f2](https://github.com/tunapanda/h5p-standalone/commit/7db44f2975664aa5cc9a36fe350228c43d230fb8))

## [3.0.1](https://github.com/tunapanda/h5p-standalone/compare/v3.0.0...v3.0.1) (2021-04-17)


### Bug Fixes

* restore mistakenly deleted content id ([#72](https://github.com/tunapanda/h5p-standalone/issues/72)) ([e172cf8](https://github.com/tunapanda/h5p-standalone/commit/e172cf8a4ae0083c4770a911007ffa0c0798ddd3))

# [3.0.0](https://github.com/tunapanda/h5p-standalone/compare/v2.2.2...v3.0.0) (2021-04-17)

### Bug Fixes

* properly cache the Cypress binary

# 2.2.2
* Update all project dependencies
* Update H5P core libraries to latest version
* Fix: Interactive videos causes the player to flicker #62

# 2.2.1
* Remove jQuery as project dependency on package.json
* Fixes failing CircleCi  Github action

# 2.1.3
* Remove H5P overrides, found a better solution
* Should fix #43

# 2.1.2
* Strike that, librariesPath update didn't even work? Tests were not run...

# 2.1.1
* Bugfix last version didn't inclde an updated built version

# 2.1.0
* Add optional libraryPath option for serving libraries from another source, thanks @tdxdave

# 2.0.2
* Check if main library has dependencies before loading them

# 2.0.1
* fix paths for h5p assets

# 2.0.0
* Switched to Webpack
* Using module system, can be imported via ES6, CommonJS, AMD or Globals
* Hide H5P frame by default
* Move away from being a jQuery plugin
* Include H5P JS files directly in this project
* Remove bower
* Add tests
