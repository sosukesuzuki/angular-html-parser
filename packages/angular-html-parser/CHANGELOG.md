# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [5.0.0](https://github.com/prettier/angular-html-parser/compare/v4.0.0...v5.0.0) (2023-10-29)


### Features

* **core:** add ng generate schematic to convert declarations to standalone ([#48790](https://github.com/prettier/angular-html-parser/issues/48790)) ([a154db8](https://github.com/prettier/angular-html-parser/commit/a154db8a81cbdfed8c3d0db1e2a5bf43aa3e0bbf))
* **core:** add ng generate schematic to convert to standalone bootstrapping APIs ([#48848](https://github.com/prettier/angular-html-parser/issues/48848)) ([345e737](https://github.com/prettier/angular-html-parser/commit/345e737daa7b9f635a4c2923358e5e765f716434))
* **core:** add ng generate schematic to remove unnecessary modules ([#48832](https://github.com/prettier/angular-html-parser/issues/48832)) ([e7318fc](https://github.com/prettier/angular-html-parser/commit/e7318fc758d9e64d1a7f60a2c7071a769b73e7d8))
* **language-service:** Allow auto-imports of a pipe via quick fix when its selector is used, both directly and via reexports. ([#48354](https://github.com/prettier/angular-html-parser/issues/48354)) ([4ae384f](https://github.com/prettier/angular-html-parser/commit/4ae384fd619a13eaadf737d08a97f07e1f6b273c))
* **language-service:** Introduce a new NgModuleIndex, and use it to suggest re-exports. ([#48354](https://github.com/prettier/angular-html-parser/issues/48354)) ([1413334](https://github.com/prettier/angular-html-parser/commit/141333411e67769d752c7162e4cb03376022f5e1))
* **router:** Add a withNavigationErrorHandler feature to provideRouter ([#48551](https://github.com/prettier/angular-html-parser/issues/48551)) ([31b94c7](https://github.com/prettier/angular-html-parser/commit/31b94c762fc91ab6cabe08ea6812780fdcf92a64))
* **router:** Add test helper for trigger navigations in tests ([#48552](https://github.com/prettier/angular-html-parser/issues/48552)) ([dedac8d](https://github.com/prettier/angular-html-parser/commit/dedac8d3f73ebf4f05b773454e2a22ab5fa4bf7c)), closes [#18967](https://github.com/prettier/angular-html-parser/issues/18967) [#15779](https://github.com/prettier/angular-html-parser/issues/15779) [#48608](https://github.com/prettier/angular-html-parser/issues/48608)


### Bug Fixes

* **animations:** fix non-animatable warnings for easing ([#48583](https://github.com/prettier/angular-html-parser/issues/48583)) ([b418754](https://github.com/prettier/angular-html-parser/commit/b4187548cae42f25624bf7ab7ad0cca121242de7)), closes [#48571](https://github.com/prettier/angular-html-parser/issues/48571)
* **common:** Update `Location` to get a normalized URL valid in case a represented URL starts with the substring equals `APP_BASE_HREF` ([#48489](https://github.com/prettier/angular-html-parser/issues/48489)) ([8802b4a](https://github.com/prettier/angular-html-parser/commit/8802b4aab9600870f3e09f198c993845587e9622)), closes [#45744](https://github.com/prettier/angular-html-parser/issues/45744)
* **common:** warn if using ngSrcset without a configured image loader ([#48804](https://github.com/prettier/angular-html-parser/issues/48804)) ([a055196](https://github.com/prettier/angular-html-parser/commit/a055196c55c57de281ff7167cd4dfb3df783c337))
* **compiler-cli:** resolve deprecation warning ([#48812](https://github.com/prettier/angular-html-parser/issues/48812)) ([4da1f29](https://github.com/prettier/angular-html-parser/commit/4da1f2948cc67b68527a91579ee14bb1a22b0c58))
* **compiler:** handle css selectors with space after an escaped character. ([#48558](https://github.com/prettier/angular-html-parser/issues/48558)) ([bc8cfa2](https://github.com/prettier/angular-html-parser/commit/bc8cfa25520c3b8b0a506c69a269e42a63f097d6)), closes [#48524](https://github.com/prettier/angular-html-parser/issues/48524)
* **compiler:** incorrect code when non-null assertion is used after a safe access ([#48801](https://github.com/prettier/angular-html-parser/issues/48801)) ([06e161f](https://github.com/prettier/angular-html-parser/commit/06e161f2dd78b42ad1938578f4d730a41404a24f)), closes [#48742](https://github.com/prettier/angular-html-parser/issues/48742)
* **compiler:** resolve deprecation warning ([#48652](https://github.com/prettier/angular-html-parser/issues/48652)) ([7243ae6](https://github.com/prettier/angular-html-parser/commit/7243ae64a6f6d7a78693a70520cc032c57c91991))
* **core:** makeEnvironmentProviders should accept EnvironmentProviders ([#48720](https://github.com/prettier/angular-html-parser/issues/48720)) ([f00bf71](https://github.com/prettier/angular-html-parser/commit/f00bf714110100549111bd27345943ab8830128c))
* **docs-infra:** consistent table width with min-width:100% ([#48815](https://github.com/prettier/angular-html-parser/issues/48815)) ([c2cd0c5](https://github.com/prettier/angular-html-parser/commit/c2cd0c548d95c9cb0c7ce03d35ddd58999bbd69f)), closes [#43840](https://github.com/prettier/angular-html-parser/issues/43840)
* **docs-infra:** correctly read example type ([#48665](https://github.com/prettier/angular-html-parser/issues/48665)) ([d4eaaef](https://github.com/prettier/angular-html-parser/commit/d4eaaefe306f8714ed1059eb24483590e992dea1)), closes [#48664](https://github.com/prettier/angular-html-parser/issues/48664)
* **forms:** Form provider FormsModule.withConfig return a FormsModule ([#48526](https://github.com/prettier/angular-html-parser/issues/48526)) ([bdf288d](https://github.com/prettier/angular-html-parser/commit/bdf288dcbfd1d680f17c04111926ff49e5e450dd)), closes [#48519](https://github.com/prettier/angular-html-parser/issues/48519)
* **language-service:** expose `package.json` for vscode extension resolution ([#48678](https://github.com/prettier/angular-html-parser/issues/48678)) ([489243b](https://github.com/prettier/angular-html-parser/commit/489243bbb80e4510f33861e4e05852d98367c9b5))
* **language-service:** ship `/api` entry-point ([#48670](https://github.com/prettier/angular-html-parser/issues/48670)) ([9fc950d](https://github.com/prettier/angular-html-parser/commit/9fc950daaffb690852a9e6801328e6a0e8e9535e))
* **language-service:** update packages/language-service/build.sh script to work with vscode-ng-language-service's new Bazel build ([#48663](https://github.com/prettier/angular-html-parser/issues/48663)) ([db8b3b7](https://github.com/prettier/angular-html-parser/commit/db8b3b7ffa3d8f01f33ad632b5b1bea04109e78e))
* **migrations:** add `enum` in `mode` option in `standalone` schema ([#48851](https://github.com/prettier/angular-html-parser/issues/48851)) ([2796230](https://github.com/prettier/angular-html-parser/commit/2796230e953eb8c29d6227a1a3858f5f08a8f200))
* **migrations:** don't delete classes that may provide dependencies transitively ([#48866](https://github.com/prettier/angular-html-parser/issues/48866)) ([f82bdc4](https://github.com/prettier/angular-html-parser/commit/f82bdc4b01f93a7103870449d37da61cc4c4f179)), closes [/github.com/angular/angular/pull/48832#discussion_r1086623514](https://github.com/prettier//github.com/angular/angular/pull/48832/issues/discussion_r1086623514)
* **migrations:** migration host incorrectly reading empty files ([#48849](https://github.com/prettier/angular-html-parser/issues/48849)) ([04e0ac3](https://github.com/prettier/angular-html-parser/commit/04e0ac3d7ca89bf38d4d2a38b7ca120d9b7b96ae)), closes [#48846](https://github.com/prettier/angular-html-parser/issues/48846)
* **migrations:** normalize paths to posix ([#48850](https://github.com/prettier/angular-html-parser/issues/48850)) ([65c74ed](https://github.com/prettier/angular-html-parser/commit/65c74ed93e04cb560c27838d440c6aa7a9859a4e))
* **router:** 'createUrlTreeFromSnapshot' with empty paths and named outlets ([#48734](https://github.com/prettier/angular-html-parser/issues/48734)) ([4dcab33](https://github.com/prettier/angular-html-parser/commit/4dcab333ae009f923cf3864e20ee47e43d32dfe6))
* **router:** page refresh should not destroy history state ([#48540](https://github.com/prettier/angular-html-parser/issues/48540)) ([cb6d73a](https://github.com/prettier/angular-html-parser/commit/cb6d73a84ef060a013d022b7696c68d343f62103))

<a name="4.0.0"></a>
## [4.0.0](https://github.com/prettier/angular-html-parser/compare/v3.0.0...v4.0.0) (2023-01-05)

Sync with upstream.

<a name="3.0.0"></a>
## [3.0.0](https://github.com/prettier/angular-html-parser/compare/v2.1.0...v3.0.0) (2022-11-20)

Sync with upstream.

<a name="2.1.0"></a>
## [2.1.0](https://github.com/prettier/angular-html-parser/compare/v2.0.0...v2.1.0) (2022-10-18)


### Features

* expose utils and classes ([#26](https://github.com/prettier/angular-html-parser/issues/26)) ([aacfa00](https://github.com/prettier/angular-html-parser/commit/aacfa00bd92006bb4abb26adda1fabb69fca3800))

<a name="2.0.0"></a>
## [2.0.0](https://github.com/prettier/angular-html-parser/compare/v1.8.0...v2.0.0) (2022-10-02)


### ⚠ BREAKING CHANGES

* switch to ESM



<a name="1.8.0"></a>
## [1.8.0](https://github.com/ikatyang/angular-html-parser/compare/v1.7.1...v1.8.0) (2021-04-05)


### Features

* add `type` field to nodes and use enumerable node type ([#21](https://github.com/ikatyang/angular-html-parser/issues/21)) ([5823440](https://github.com/ikatyang/angular-html-parser/commit/5823440))



<a name="1.7.1"></a>
## [1.7.1](https://github.com/ikatyang/angular-html-parser/compare/v1.7.0...v1.7.1) (2020-06-26)


### Bug Fixes

* add missing endSourceSpan for element with void element as its last child ([#20](https://github.com/ikatyang/angular-html-parser/issues/20)) ([f7e8c18](https://github.com/ikatyang/angular-html-parser/commit/f7e8c18))



<a name="1.7.0"></a>
## [1.7.0](https://github.com/ikatyang/angular-html-parser/compare/v1.6.0...v1.7.0) (2020-05-09)


### Features

* **getTagContentType:** add `attrs` parameter ([#17](https://github.com/ikatyang/angular-html-parser/issues/17)) ([6443800](https://github.com/ikatyang/angular-html-parser/commit/6443800))



<a name="1.6.0"></a>
## [1.6.0](https://github.com/ikatyang/angular-html-parser/compare/v1.5.0...v1.6.0) (2020-05-03)


### Features

* **getTagContentType:** add `prefix` and `hasParent` parameters ([#13](https://github.com/ikatyang/angular-html-parser/issues/13)) ([aae23df](https://github.com/ikatyang/angular-html-parser/commit/aae23df))



<a name="1.5.0"></a>
## [1.5.0](https://github.com/ikatyang/angular-html-parser/compare/v1.4.0...v1.5.0) (2020-04-21)


### Features

* add an option to customize tag content type ([#12](https://github.com/ikatyang/angular-html-parser/issues/12)) ([b327e1a](https://github.com/ikatyang/angular-html-parser/commit/b327e1a))



<a name="1.4.0"></a>
## [1.4.0](https://github.com/ikatyang/angular-html-parser/blob/master/packages/angular-html-parser/compare/v1.3.0...v1.4.0) (2020-01-28)


### Bug Fixes

* do not wrap `<tr>` into pseudo `<tbody>` ([b63f8a1](https://github.com/ikatyang/angular-html-parser/commit/b63f8a1))



<a name="1.3.0"></a>
## [1.3.0](https://github.com/ikatyang/angular-html-parser/blob/master/packages/angular-html-parser/compare/v1.2.0...v1.3.0) (2019-11-02)


### Features

* support full named entities ([#9](https://github.com/ikatyang/angular-html-parser/issues/9)) ([7eaec57](https://github.com/ikatyang/angular-html-parser/blob/master/packages/angular-html-parser/commit/7eaec57))



<a name="1.2.0"></a>
## [1.2.0](https://github.com/ikatyang/angular-html-parser/blob/master/packages/angular-html-parser/compare/v1.1.0...v1.2.0) (2018-12-07)


### Features

* add an option to specify case-sensitivity for tag names ([#7](https://github.com/ikatyang/angular-html-parser/issues/7)) ([a76b450](https://github.com/ikatyang/angular-html-parser/blob/master/packages/angular-html-parser/commit/a76b450))



<a name="1.1.0"></a>
## [1.1.0](https://github.com/ikatyang/angular-html-parser/blob/master/packages/angular-html-parser/compare/v1.0.0...v1.1.0) (2018-11-27)


### Features

* add an option to allow `htm` component closing tags ([#6](https://github.com/ikatyang/angular-html-parser/issues/6)) ([b505c16](https://github.com/ikatyang/angular-html-parser/blob/master/packages/angular-html-parser/commit/b505c16))
* support bogus comments ([#5](https://github.com/ikatyang/angular-html-parser/issues/5)) ([75042e9](https://github.com/ikatyang/angular-html-parser/blob/master/packages/angular-html-parser/commit/75042e9))



<a name="1.0.0"></a>
## 1.0.0 (2018-10-24)

### Features

* initial implementation ([#1](https://github.com/ikatyang/angular-html-parser/issues/1)) ([0e8b9a5](https://github.com/ikatyang/angular-html-parser/blob/master/packages/angular-html-parser/commit/0e8b9a5))
