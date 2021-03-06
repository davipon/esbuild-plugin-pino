# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.2.1](https://github.com/davipon/esbuild-plugin-pino/compare/v1.2.0...v1.2.1) (2022-07-03)


### 🚚 Chores

* **deps:** add renovate.json ([#5](https://github.com/davipon/esbuild-plugin-pino/issues/5)) ([7c3d10d](https://github.com/davipon/esbuild-plugin-pino/commit/7c3d10dd358148aec298f6d9e8e86e44a687bbb2))
* **deps:** pin dependencies ([#6](https://github.com/davipon/esbuild-plugin-pino/issues/6)) ([28f0cc1](https://github.com/davipon/esbuild-plugin-pino/commit/28f0cc1100123947d42be8fa1fd22990de0bcf3c))
* **deps:** update dependency eslint-plugin-prettier to v4.1.0 ([#9](https://github.com/davipon/esbuild-plugin-pino/issues/9)) ([eab2455](https://github.com/davipon/esbuild-plugin-pino/commit/eab2455d441f4ab5360ae794c777e098069e1463))
* **deps:** update typescript-eslint monorepo to v5.30.0 ([#11](https://github.com/davipon/esbuild-plugin-pino/issues/11)) ([b72143d](https://github.com/davipon/esbuild-plugin-pino/commit/b72143dcb6290adf5721b90bda80434c82e3f7e1))
* **renovate:** update to schedule once a week ([2916c82](https://github.com/davipon/esbuild-plugin-pino/commit/2916c8283df81be4d6f2f1f83da52b32304d37d0))


### 🐛 Bug Fixes

* generate pino files reference at runtime but not build time ([#12](https://github.com/davipon/esbuild-plugin-pino/issues/12)) ([118b7c3](https://github.com/davipon/esbuild-plugin-pino/commit/118b7c3f46c442ae9f22e1e991eac87109b6b9ef))

## [1.2.0](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.11...v1.2.0) (2022-06-24)


### 🚚 Chores

* ignore "dist" in nodemon, add new scripts in package.json ([41b0f3a](https://github.com/davipon/esbuild-plugin-pino/commit/41b0f3a47946144a20243ee725f5b628ccc8068e))
* **nodemon:** add nodemon for develop ([c90b4db](https://github.com/davipon/esbuild-plugin-pino/commit/c90b4dbf9a67a4c6aa0c65cef45a7a2e786d2ad7))


### 🐛 Bug Fixes

* **bundle:** add transportsEntrypoints to pinoOverrides ([661a009](https://github.com/davipon/esbuild-plugin-pino/commit/661a00963c7bdf5531095b1edc019fdc6315fba7))

### [1.1.11](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.10...v1.1.11) (2022-06-23)


### ♻️ Code Refactoring

* replace "./" with process.cwd() in absoluteOutputPath ([a57590d](https://github.com/davipon/esbuild-plugin-pino/commit/a57590ded9fce830b599852cbc71eff880161f5e))


### 🐛 Bug Fixes

* **ci.yml:** fix paths-ignore ([1b16912](https://github.com/davipon/esbuild-plugin-pino/commit/1b16912df2e49d5c1b3cc598ef575c518d83bb72))
* **index.ts:** replace backslashes with slashes in absoluteOutputPath ([fb9222a](https://github.com/davipon/esbuild-plugin-pino/commit/fb9222ae3c20cde69738e9e2a3b06263ef3739a8))
* **index.ts:** replace backslashes with slashes in absoluteOutputPath ([3acc66b](https://github.com/davipon/esbuild-plugin-pino/commit/3acc66b8fa4c9ace0a89365f894ce0ab39687ac8))
* **windows:** fix windows user use posix separator in entryPoints ([c16ceea](https://github.com/davipon/esbuild-plugin-pino/commit/c16ceea98cfc5b2c9cb94edf0fb5cd7ff56cd10a))

### [1.1.10](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.9...v1.1.10) (2022-06-20)

### [1.1.9](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.8...v1.1.9) (2022-06-20)


### 🐛 Bug Fixes

* **dep:** fix deps ([e8c13af](https://github.com/davipon/esbuild-plugin-pino/commit/e8c13af5ebb0eb0be43ae5e6e49fe97756c78372))

### [1.1.8](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.7...v1.1.8) (2022-06-20)


### 🐛 Bug Fixes

* fix test script - add npx before pkgroll ([7a73ace](https://github.com/davipon/esbuild-plugin-pino/commit/7a73ace4e239ab13195430cff1c2e983ebf0149b))
* **package.json:** fix "test" script ([5214a52](https://github.com/davipon/esbuild-plugin-pino/commit/5214a52cd69307afbad942aaaa32052df8298ed3))

### [1.1.7](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.6...v1.1.7) (2022-06-20)


### 🚚 Chores

* **commitlint:** rename config file ([58ef953](https://github.com/davipon/esbuild-plugin-pino/commit/58ef953cf2af45750db8cbbe76af0548644f9c92))
* **deps:** bump pnpm/action-setup from 2.0.1 to 2.2.2 ([ebcfd0d](https://github.com/davipon/esbuild-plugin-pino/commit/ebcfd0dda4526e38d34d95f6c16d09814e3c9bc2))


### 📝 Documentation

* add dependencies and license badges ([452035c](https://github.com/davipon/esbuild-plugin-pino/commit/452035c61256cb00f16a31c42879121c052504a2))
* add package size badge ([f0e68ca](https://github.com/davipon/esbuild-plugin-pino/commit/f0e68ca0a8bea5b63a6cfa908f09eba60f9be684))
* **readme.md:** add Credits section ([fd512d0](https://github.com/davipon/esbuild-plugin-pino/commit/fd512d08c90a643d66b1f19091898c8911e58d9f))
* update keywords in package.json ([b4ab9b3](https://github.com/davipon/esbuild-plugin-pino/commit/b4ab9b328b7fad6dd3f35fcc66e6c1985fa8a636))


### 🔨 Build System

* **bundling:** replace tsc with pkgroll for bundling ([1d18059](https://github.com/davipon/esbuild-plugin-pino/commit/1d18059a836c55c2f6150afc6314652351c891fe))

### [1.1.6](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.5...v1.1.6) (2022-06-18)


### 📝 Documentation

* add new badge ([87f2191](https://github.com/davipon/esbuild-plugin-pino/commit/87f2191abf7c9064e859b8006ecc423e45823641))

### [1.1.5](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.4...v1.1.5) (2022-06-18)

### [1.1.4](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.3...v1.1.4) (2022-06-18)

### [1.1.3](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.2...v1.1.3) (2022-06-18)


### 📝 Documentation

* add npm & github action badges ([cdbc441](https://github.com/davipon/esbuild-plugin-pino/commit/cdbc441c405379481800d33cf3c2194a42df1977))

### [1.1.2](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.1...v1.1.2) (2022-06-18)


### ✅ Testing

* fix last expect.stringMatching ([ab93534](https://github.com/davipon/esbuild-plugin-pino/commit/ab93534301e11a1191c70f091d0fe663a7337a14))

### [1.1.1](https://github.com/davipon/esbuild-plugin-pino/compare/v1.1.0...v1.1.1) (2022-06-18)


### 🚚 Chores

* update scripts ([691f301](https://github.com/davipon/esbuild-plugin-pino/commit/691f30121b05f88e7af519c27a55c57140046cc9))

## 1.1.0 (2022-06-18)


### ✨ Features

* initial release ([5fc632d](https://github.com/davipon/esbuild-plugin-pino/commit/5fc632d4063603a55998b9d9fabc032665f50f6a))


### ♻️ Code Refactoring

* use 'export =' to build a CommonJS module that exports a function ([f3f96fd](https://github.com/davipon/esbuild-plugin-pino/commit/f3f96fd5d23f045d114a79588f64cebc65f64a34))


### ✅ Testing

* add build scripts for testing ([3e0c944](https://github.com/davipon/esbuild-plugin-pino/commit/3e0c944f09d8cc3ed4716f0a574a6ef8e5f878e8))
* use build script to simulate real build step ([b15f8b2](https://github.com/davipon/esbuild-plugin-pino/commit/b15f8b24ffadb51df53f32235880b7a340cb1d06))


### 📝 Documentation

* update README.md ([a56c484](https://github.com/davipon/esbuild-plugin-pino/commit/a56c484be902025b96363b7744c208543798585a))


### 🚚 Chores

* add eslint, prettier, commitizen, standard-version, and husky ([968e93d](https://github.com/davipon/esbuild-plugin-pino/commit/968e93dc534872f26fe36aa699678300c4800f02))
* bump deps to latest version ([50c1046](https://github.com/davipon/esbuild-plugin-pino/commit/50c1046cfb673287572d61d5e732fdb2f4d1db94))
* format codebase ([6072c98](https://github.com/davipon/esbuild-plugin-pino/commit/6072c9812c2569e8f9a0fb9276cf4a57127c46d1))
* setup esling & prettier ([8fc00d5](https://github.com/davipon/esbuild-plugin-pino/commit/8fc00d53fc82a21d913ca36a6a817ad60c677b13))
