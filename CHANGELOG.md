# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [0.6.0](https://github.com/yifan-ca/tournament-manager/compare/v0.5.0...v0.6.0) (2021-06-12)


### Features

* adds log level by node env ([54ed044](https://github.com/yifan-ca/tournament-manager/commits/54ed04494bffeb97be14c0bac0e59130bf75f01c))
* use a consistent timestamp to slug field based in created_at ([34f7fd7](https://github.com/yifan-ca/tournament-manager/commits/34f7fd706c8c1df3a652b4e877bfdd5629862126))


### Bug Fixes

* add port to deploy with same port in Dokku ([7866a2e](https://github.com/yifan-ca/tournament-manager/commits/7866a2e89ab4b1fb77a462d5f8661d09d53ccb9e))
* undefined task payload in consumer ([e741ba3](https://github.com/yifan-ca/tournament-manager/commits/e741ba3a790f60325baf7ddb6e87579f77c549f1))

## [0.5.0](https://github.com/yifan-ca/tournament-manager/compare/v0.4.0...v0.5.0) (2021-06-11)


### Features

* adds scheduler task based in time ([e5b5ec5](https://github.com/yifan-ca/tournament-manager/commits/e5b5ec5dc9b72d73135c2809faf4c76d14592f04))
* modify patch method, return 204 always ([db8e372](https://github.com/yifan-ca/tournament-manager/commits/db8e3721d4c30b37c952d9a5c7c44abc87d9ff4b))
* uses slug to query tournaments ([c0ef84e](https://github.com/yifan-ca/tournament-manager/commits/c0ef84ed5c5705a4ae074114c692f2df7beb00e6))

## [0.4.0](https://github.com/yifan-ca/tournament-manager/compare/v0.2.0...v0.4.0) (2021-06-11)


### Features

* adds tournament resource with validation and doc ([62a308d](https://github.com/yifan-ca/tournament-manager/commits/62a308d3a9de61179c297b089afdfee33a71884e))
* adds validation in POST /tournaments and auto-swagger ([89711a7](https://github.com/yifan-ca/tournament-manager/commits/89711a72cad2aceef3dcd6006966e7d5d4f46f57))
* exclude healthcheck from openapi documentation ([37eaa25](https://github.com/yifan-ca/tournament-manager/commits/37eaa250bb46b455c6fb689ad14af4816e827a19))
* move tournament model for tournaments module ([a4fbdca](https://github.com/yifan-ca/tournament-manager/commits/a4fbdcadb5ee4d4379c69f92315a4874769ddb20))
* put all endpoints under /api resource ([e377509](https://github.com/yifan-ca/tournament-manager/commits/e37750933f5646e6c288f503b0e9f024c8cb8710))
* use nest crud generator to scafold tornauments resource ([9e01ae8](https://github.com/yifan-ca/tournament-manager/commits/9e01ae871811d40496b2cac270959be67ebe34f6))

## [0.3.0](https://github.com/yifan-ca/tournament-manager/compare/v0.2.0...v0.3.0) (2021-06-11)


### Features

* use nest crud generator to scafold tornauments resource ([9e01ae8](https://github.com/yifan-ca/tournament-manager/commits/9e01ae871811d40496b2cac270959be67ebe34f6))

## 0.2.0 (2021-06-11)


### Features

* add controllers services and interfaces ([510e35c](https://github.com/yifan-ca/tournament-manager/commits/510e35cba924c2500fbc6990a31e993c2b9c5361))
* adds bull to handle tournament start event ([afb06f5](https://github.com/yifan-ca/tournament-manager/commits/afb06f569977ec7bec4aa584ff58072fac8811c1))
* adds controller, interface and service ([22067d0](https://github.com/yifan-ca/tournament-manager/commits/22067d0819e7e6acfd3c1bd8c80025a12f7bdc33))
* adds mysql to gitpod base image ([a2889a2](https://github.com/yifan-ca/tournament-manager/commits/a2889a2ca65321d7698ee671d33d77d6a9b86d9c))
* adds mysql with sequlize as project datastore ([a370684](https://github.com/yifan-ca/tournament-manager/commits/a3706845d08cd30510ab2cb75ad9adb74f10dcd4))
* adds redis healthcheck ([8561527](https://github.com/yifan-ca/tournament-manager/commits/8561527390bce96b806594e69f425f222679f659))


### Bug Fixes

* identation ([5748be7](https://github.com/yifan-ca/tournament-manager/commits/5748be72a109149646e448283909619c757c9262))
* removing database implementation for games ([13ae57d](https://github.com/yifan-ca/tournament-manager/commits/13ae57d2ffd63e728858b2c95b3a409a6137bca1))
* Removing unnecessary interfaces ([f4f1974](https://github.com/yifan-ca/tournament-manager/commits/f4f19746ec0de88f19442ce0a35400d3ef145b72))

## 0.1.0 (2021-06-10)


### Features

* adds mysql to gitpod base image ([a2889a2](https://github.com/yifan-ca/tournament-manager/commits/a2889a2ca65321d7698ee671d33d77d6a9b86d9c))
* adds mysql with sequlize as project datastore ([a370684](https://github.com/yifan-ca/tournament-manager/commits/a3706845d08cd30510ab2cb75ad9adb74f10dcd4))
