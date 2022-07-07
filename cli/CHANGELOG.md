# Changelog

## [7.0.0](https://github.com/kairlec/protobuf.js/compare/v6.10.2...v7.0.0) (2022-07-07)


### ⚠ BREAKING CHANGES

* move command line tool to a new package named protobufjs-cli (#1234)

### Features

* add --no-service option for pbjs static target ([#1577](https://github.com/kairlec/protobuf.js/issues/1577)) ([d01394a](https://github.com/kairlec/protobuf.js/commit/d01394a1463062824c066b653aad53c449752202))
* add getTypeUrl method to generated code ([#1463](https://github.com/kairlec/protobuf.js/issues/1463)) ([d13d5d5](https://github.com/kairlec/protobuf.js/commit/d13d5d5688052e366aa2e9169f50dfca376b32cf))
* add null-defaults option ([#1611](https://github.com/kairlec/protobuf.js/issues/1611)) ([6e713ba](https://github.com/kairlec/protobuf.js/commit/6e713baf54bd987ae52cbf92a4f2742c70201dc0))
* add support for buffer configuration ([#1372](https://github.com/kairlec/protobuf.js/issues/1372)) ([101aa1a](https://github.com/kairlec/protobuf.js/commit/101aa1a4f148516fdc83a74f54a229f06e24a5de))
* allow message.getTypeUrl provide custom tyepUrlPrefix ([597ddc2](https://github.com/kairlec/protobuf.js/commit/597ddc283edbf22ca887e6727de48a8ce8406347))
* move command line tool to a new package named protobufjs-cli ([#1234](https://github.com/kairlec/protobuf.js/issues/1234)) ([da34f43](https://github.com/kairlec/protobuf.js/commit/da34f43ccd51ad97017e139f137521782f5ef119))
* prepare initial publication of cli ([#1752](https://github.com/kairlec/protobuf.js/issues/1752)) ([64811d5](https://github.com/kairlec/protobuf.js/commit/64811d5878c31e4a86a39da5fec6aea35da22fcd))
* proto3 optional support ([#1584](https://github.com/kairlec/protobuf.js/issues/1584)) ([6c4d307](https://github.com/kairlec/protobuf.js/commit/6c4d30716a9a756dcdc21d64f9c9d069315fc5b1))
* update dependencies / general cleanup ([#1356](https://github.com/kairlec/protobuf.js/issues/1356)) ([42f49b4](https://github.com/kairlec/protobuf.js/commit/42f49b43f692c24c2bc1ae081b4d1ad9fa173cd7))


### Bug Fixes

* **deps:** patch minimatch vulnerability ([#1704](https://github.com/kairlec/protobuf.js/issues/1704)) ([bac61b8](https://github.com/kairlec/protobuf.js/commit/bac61b8c2757804bbb9c5fa0f8bc6a7bcf0bb374))
* es6 export enum ([#1446](https://github.com/kairlec/protobuf.js/issues/1446)) ([9f33784](https://github.com/kairlec/protobuf.js/commit/9f33784350b1efc2e774bbfc087cbd2c47828748))
* fromObject should not initialize oneof members ([#1597](https://github.com/kairlec/protobuf.js/issues/1597)) ([90afe44](https://github.com/kairlec/protobuf.js/commit/90afe4412de8070b0c0681e5905a6e0213072a85))
* Import Long types ([1d98cb8](https://github.com/kairlec/protobuf.js/commit/1d98cb86fcbc69bd54fb3d3254b348da6ac0a96b))
* Import Long types ([8a85863](https://github.com/kairlec/protobuf.js/commit/8a858634f3add3a2d8567f72699b907e9f543eca))
* proper relative path to protobufjs in cli ([#1753](https://github.com/kairlec/protobuf.js/issues/1753)) ([a1d6029](https://github.com/kairlec/protobuf.js/commit/a1d60292ecb22fcf89c493c562ae07ab10ef49c9))
* typo in pbjs help text ([#1552](https://github.com/kairlec/protobuf.js/issues/1552)) ([7f46dbe](https://github.com/kairlec/protobuf.js/commit/7f46dbeb538a6277035a896e1ab5e1a070e28681))
