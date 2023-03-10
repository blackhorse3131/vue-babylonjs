# [1.0.0-beta.7](https://github.com/Beg-in/vue-babylonjs/compare/1.0.0-beta.5...1.0.0-beta.7) (2019-06-02)


### Bug Fixes

* **asset:** set root mesh to single mesh if possible ([f6bc9cf](https://github.com/Beg-in/vue-babylonjs/commit/f6bc9cf))
* **docs:** template highlighting issues ([16f666c](https://github.com/Beg-in/vue-babylonjs/commit/16f666c))
* **observable:** fix for onentity emit ([51b7745](https://github.com/Beg-in/vue-babylonjs/commit/51b7745))
* **package:** audit cleanup and peer dependencies ([266e52c](https://github.com/Beg-in/vue-babylonjs/commit/266e52c)), closes [#21](https://github.com/Beg-in/vue-babylonjs/issues/21)
* **scene:** race condition with detecting a camera for exclusion of the default environment ([207df91](https://github.com/Beg-in/vue-babylonjs/commit/207df91))


### Features

* **asset:** add asset component ([78116b3](https://github.com/Beg-in/vue-babylonjs/commit/78116b3))
* **observable:** add support with vue custom events ([bd8dac0](https://github.com/Beg-in/vue-babylonjs/commit/bd8dac0))
* **Observable:** observable events emitted by entity and scene components ([5e016cd](https://github.com/Beg-in/vue-babylonjs/commit/5e016cd)), closes [#5](https://github.com/Beg-in/vue-babylonjs/issues/5)


### BREAKING CHANGES

* **package:** Babylon.js and loaders are now peer dependencies. Add `@babylonjs/core` and
`@babylonjs/loaders` when using this package from npm.



# [1.0.0-beta.5](https://github.com/Beg-in/vue-babylonjs/compare/1.0.0-beta.4...1.0.0-beta.5) (2018-06-13)


### Bug Fixes

* **site:** fix webpack build for local development ([3e62158](https://github.com/Beg-in/vue-babylonjs/commit/3e62158))



# [1.0.0-beta.4](https://github.com/Beg-in/vue-babylonjs/compare/1.0.0-beta.3...1.0.0-beta.4) (2018-05-24)


### Bug Fixes

* **esm:** support environments with esm Vue ([a2a921f](https://github.com/Beg-in/vue-babylonjs/commit/a2a921f))



# [1.0.0-beta.3](https://github.com/Beg-in/vue-babylonjs/compare/1.0.0-beta.2...1.0.0-beta.3) (2018-04-21)


### Bug Fixes

* **controls:** add margin bottom to controls example ([e121220](https://github.com/Beg-in/vue-babylonjs/commit/e121220))



# [1.0.0-beta.2](https://github.com/Beg-in/vue-babylonjs/compare/1.0.0-beta.1...1.0.0-beta.2) (2018-03-30)


### Bug Fixes

* **scene:** default environment now activates properly ([ac79e6a](https://github.com/Beg-in/vue-babylonjs/commit/ac79e6a))



# [1.0.0-beta.1](https://github.com/Beg-in/vue-babylonjs/compare/0.9.0...1.0.0-beta.1) (2018-03-30)



# [0.9.0](https://github.com/Beg-in/vue-babylonjs/compare/0.8.0...0.9.0) (2018-03-25)


### Features

* **physics:** add physics impostor support ([cbc547a](https://github.com/Beg-in/vue-babylonjs/commit/cbc547a))



# [0.8.0](https://github.com/Beg-in/vue-babylonjs/compare/0.7.1...0.8.0) (2018-03-22)


### Features

* **material:** add material with pbr support ([9261b6c](https://github.com/Beg-in/vue-babylonjs/commit/9261b6c))



## [0.7.1](https://github.com/Beg-in/vue-babylonjs/compare/0.7.0...0.7.1) (2018-02-24)



# [0.7.0](https://github.com/Beg-in/vue-babylonjs/compare/0.6.0...0.7.0) (2018-02-08)


### Features

* **camera:** add camera component ([6829d85](https://github.com/Beg-in/vue-babylonjs/commit/6829d85))
* **entity:** add propreties system ([10124f1](https://github.com/Beg-in/vue-babylonjs/commit/10124f1))



# [0.6.0](https://github.com/Beg-in/vue-babylonjs/compare/0.5.0...0.6.0) (2018-02-05)


### Features

* **material:** add shader uniform and attribute components ([4c17b62](https://github.com/Beg-in/vue-babylonjs/commit/4c17b62))
* **material:** add shaders ([c7bd5cb](https://github.com/Beg-in/vue-babylonjs/commit/c7bd5cb))
* **material:** add vertex and fragment components ([93d2959](https://github.com/Beg-in/vue-babylonjs/commit/93d2959))



# [0.5.0](https://github.com/Beg-in/vue-babylonjs/compare/0.4.0...0.5.0) (2018-01-31)


### Features

* **animations:** add animations ([cb8297b](https://github.com/Beg-in/vue-babylonjs/commit/cb8297b))
* **animations:** add animations ([1f3482d](https://github.com/Beg-in/vue-babylonjs/commit/1f3482d))



# [0.4.0](https://github.com/Beg-in/vue-babylonjs/compare/0.3.0...0.4.0) (2018-01-30)


### Features

* **entity:** add entity lifecycle hooks ([4705ea4](https://github.com/Beg-in/vue-babylonjs/commit/4705ea4))
* **entity:** add entity lifecycle hooks ([1072f52](https://github.com/Beg-in/vue-babylonjs/commit/1072f52))



# [0.3.0](https://github.com/Beg-in/vue-babylonjs/compare/0.2.0...0.3.0) (2018-01-30)


### Features

* **light:** add lights ([297622f](https://github.com/Beg-in/vue-babylonjs/commit/297622f))


# [0.2.0](https://github.com/Beg-in/vue-babylonjs/compare/1c8615b...0.2.0) (2018-01-29)


### Features

* **entity:** add entity and some basic meshes ([2cc7c33](https://github.com/Beg-in/vue-babylonjs/commit/2cc7c33))
* **entity:** add entity and some basic meshes ([ebb4a76](https://github.com/Beg-in/vue-babylonjs/commit/ebb4a76))
* **plugin:** create Vue and Vuex plugins ([1c8615b](https://github.com/Beg-in/vue-babylonjs/commit/1c8615b))



