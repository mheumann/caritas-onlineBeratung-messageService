# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [2.0.0](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/compare/v1.3.1...v2.0.0) (2020-11-23)


### ⚠ BREAKING CHANGES

* creating a new database for messageservice is required

### Features

* adapt new database for messageservice ([e60c87a](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/e60c87af3607a61f92b673cea2646f2f827ee21e))
* define new api andpoints for draft messages ([fb39ee2](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/fb39ee2cc664dfdd79f7269b3fab1bbc657319ca))
* delete draft when message has been send ([0195342](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/01953428eed44088be61d40b34667d01bbbd228f))
* prevent live event trigger for rocket chat system user ([55ae8d8](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/55ae8d87fddd96613ad5f21c3810cd8f525e3000))
* provide controller endpoint to retrieve saved draft message ([fa3820e](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/fa3820ee39822fedde35def34084566700109d3e))
* provide controller endpoint to save draft messages ([2668490](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/266849009490b35d2580455ab0da84e132c23dab))
* provide service method to search for draft message ([524d916](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/524d9161e00428aa40b839c043d8fb12944c7bb6))
* provide service to save, overwrite and delete draft messages ([f8f7988](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/f8f79887d38fe7239bbd52a5fb2c9c906de3e433))
* restrict release action to relase starting branches ([47925c6](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/47925c6bfe75897e19c0026001fb155826d93308))
* seperate changelog configurations ([4a2fcee](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/4a2fcee56d60b354a431f0e4acd9a742b98e5474))
* update keycloak to 11.0.2 ([8d9aa25](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/8d9aa257768c9fd11dbd4fcb605b299c5ade2768))
* update spring boot and dependencies ([ea09118](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/ea09118bbdd8624c20775b079339904a90e9096e))


### Bug Fixes

* add property values to fix integration tests ([a92a6d3](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/a92a6d32ac6ad5f6ef1b468f47cb320246f45f04))
* update deprecated logging property ([fbf6143](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/fbf614388b342ee4932c87b7de22507734c853b8))

### [1.3.1](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/compare/v1.3.0...v1.3.1) (2020-10-28)

## [1.3.0](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/compare/v1.2.3...v1.3.0) (2020-10-28)


### Features

* add authorization headers for api client ([b88eb89](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/b88eb896aaeb1546e410e3852a9706f370177f2c))
* generate user service api client ([04486e0](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/04486e0d586825d05c337c8645e5ca0eb0d427dd))
* integrate live event trigger ([ef5b276](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/ef5b276ff2ebf968baf539f63b970ba91e4c78b6))
* remove unnecessary content declarations ([936735d](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/936735d4a8d43cba47b2ab8e6470b6bbc7f82a63))
* update swagger to openapi and define api models ([9cb3290](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/9cb3290e6b9d11b401b1219aabeae1ee96fc5f38))


### Bug Fixes

* check boolean against null ([c7a4d29](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/c7a4d29e445ab571722f93256bc2846a37139987))

### [1.2.3](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/compare/v1.2.2...v1.2.3) (2020-10-12)

### [1.2.2](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/compare/v1.2.1...v1.2.2) (2020-10-12)

### [1.2.1](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/compare/v1.2.0...v1.2.1) (2020-08-26)

## [1.1.0](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/compare/e094b600cc4512e2f107094be174f5fa84cbf581...v1.1.0) (2020-07-29)


### Bug Fixes

* added npm install for github release action ([e094b60](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/e094b600cc4512e2f107094be174f5fa84cbf581))

## 1.2.0 (2020-08-26)


### Features

* check on writing to a feedback chat if provided group id is valid ([8291bb2](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/8291bb2e8596e4490f674ed7b4a6aded52f0141d))
* Initial Commit ([9083810](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/90838106445c029f43afc05307b8816888b0be7f))


### Bug Fixes

* logservice tests to be independent of logback rule ([87905bc](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/87905bc837c35828b69c8b4bc93a75e35aa230d9))
* removed unused field setter ([f98594b](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/f98594bfede8b50e0404c44edc6a8a015caa4ea1))


## 1.1.0 (2020-07-29)


### Features

* Initial Commit ([9083810](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/90838106445c029f43afc05307b8816888b0be7f))


### Bug Fixes

* added npm install for github release action ([e094b60](https://github.com/CaritasDeutschland/caritas-onlineBeratung-messageService/commit/e094b600cc4512e2f107094be174f5fa84cbf581))
