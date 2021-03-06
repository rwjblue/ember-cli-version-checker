# Changelog

## v5.1.2 (2021-01-19)

#### :rocket: Enhancement
* [#242](https://github.com/ember-cli/ember-cli-version-checker/pull/242) Remove extraneous file I/O when checking the same package version ([@davecombs](https://github.com/davecombs))

#### Committers: 2
- Dave Combs ([@davecombs](https://github.com/davecombs))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)


## v5.1.1 (2020-05-13)

#### :bug: Bug Fix
* [#207](https://github.com/ember-cli/ember-cli-version-checker/pull/207) fix: Semver constraint matching should allow prereleases ([@runspired](https://github.com/runspired))

#### Committers: 1
- Chris Thoburn ([@runspired](https://github.com/runspired))

## v5.1.0 (2020-05-13)

#### :bug: Bug Fix
* [#207](https://github.com/ember-cli/ember-cli-version-checker/pull/207) fix: Semver constraint matching should allow prereleases ([@runspired](https://github.com/runspired))

#### Committers: 1
- Chris Thoburn ([@runspired](https://github.com/runspired))

## v5.1.0 (2020-05-11)

* [#206](https://github.com/ember-cli/ember-cli-version-checker/pull/206) Add ProjectWideDependencyChecker `check` API([@stefanpenner](https://github.com/stefanpenner))

## v5.0.2 (2020-03-23)

#### :bug: Bug Fix
* [#178](https://github.com/ember-cli/ember-cli-version-checker/pull/178) Fix hasSingleImplementation ([@xg-wang](https://github.com/xg-wang))

#### :house: Internal
* [#179](https://github.com/ember-cli/ember-cli-version-checker/pull/179) Add automated release setup. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 2
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- Thomas Wang ([@xg-wang](https://github.com/xg-wang))


##  v5.0.1 (2020-02-14)

* correct URLs to point to the correct GH organization

##  v5.0.0 (2020-02-14)

#### :boom: Breaking Change
* [#165](https://github.com/ember-cli/ember-cli-version-checker/pull/165) Remove Un-needed features ([@stefanpenner](https://github.com/stefanpenner))
* [#170](https://github.com/ember-cli/ember-cli-version-checker/pull/170) Drop node 8 support ([@stefanpenner](https://github.com/stefanpenner))

#### :rocket: Enhancement
* [#173](https://github.com/ember-cli/ember-cli-version-checker/pull/173) Add partial windows coverage ([@stefanpenner](https://github.com/stefanpenner))
* [#172](https://github.com/ember-cli/ember-cli-version-checker/pull/172) use GH Actions ([@stefanpenner](https://github.com/stefanpenner))
* [#171](https://github.com/ember-cli/ember-cli-version-checker/pull/171) Improve error message ([@stefanpenner](https://github.com/stefanpenner))

#### Committers: 2
- Stefan Penner ([@stefanpenner](https://github.com/stefanpenner))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)


##  v4.1.0 (2020-01-17)

#### :rocket: Enhancement
* [#156](https://github.com/ember-cli/ember-cli-version-checker/pull/156) Add hasSingleImplementation, assertHasSingleImplementation (highlander) ([@xg-wang](https://github.com/xg-wang))

#### Committers: 1
- Thomas Wang ([@xg-wang](https://github.com/xg-wang))

## v4.0.1 (2020-01-16)

#### :rocket: Enhancement
* [#164](https://github.com/ember-cli/ember-cli-version-checker/pull/164) Restore node 8 for a cycle, to ease some upgrades. ([@stefanpenner](https://github.com/stefanpenner))

#### Committers: 1
- Stefan Penner ([@stefanpenner](https://github.com/stefanpenner))


## v4.0.0 (2020-01-16)

#### :boom: Breaking Change & :rocket: Enhancement
* [#163](https://github.com/ember-cli/ember-cli-version-checker/pull/163) drop unsupported node versions and upgrade all dependencies ([@stefanpenner](https://github.com/stefanpenner))

#### Committers: 3
- Stefan Penner ([@stefanpenner](https://github.com/stefanpenner))
- Thomas Wang ([@xg-wang](https://github.com/xg-wang))
- [@dependabot-preview[bot]](https://github.com/apps/dependabot-preview)

## v3.1.3 (2019-03-26)

#### :bug: Bug Fix
* [#106](https://github.com/ember-cli/ember-cli-version-checker/pull/106) Fix issue with PnP + missing packages ([@stefanpenner](https://github.com/stefanpenner))

#### Committers: 1
- Stefan Penner ([@stefanpenner](https://github.com/stefanpenner))

## v3.1.0 (2019-02-28)

#### :rocket: Enhancement
* [#97](https://github.com/ember-cli/ember-cli-version-checker/pull/97) Perf fix: cache the resolutions identically to how require does. ([@stefanpenner](https://github.com/stefanpenner))

#### Committers: 1
- Stefan Penner ([@stefanpenner](https://github.com/stefanpenner))

## v3.0.1 (2019-01-09)

#### :bug: Bug Fix
* [#71](https://github.com/ember-cli/ember-cli-version-checker/pull/71) fix: fallback to project if addon has no root ([@buschtoens](https://github.com/buschtoens))

#### Committers: 1
- Jan Buschtöns ([@buschtoens](https://github.com/buschtoens))


## v2.2.0 (2019-01-07)

#### :rocket: Enhancement
* [#83](https://github.com/ember-cli/ember-cli-version-checker/pull/83) Backport Yarn PnP Support to 2.x ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))


## v3.0.0 (2019-01-07)

#### :boom: Breaking Change
* [#76](https://github.com/ember-cli/ember-cli-version-checker/pull/76) Drop Node 4 support ([@Turbo87](https://github.com/Turbo87))

#### :rocket: Enhancement
* [#80](https://github.com/ember-cli/ember-cli-version-checker/pull/80) Support resolution with Yarn PnP. ([@rwjblue](https://github.com/rwjblue))

#### :memo: Documentation
* [#64](https://github.com/ember-cli/ember-cli-version-checker/pull/64) Fix code example ([@SergeAstapov](https://github.com/SergeAstapov))

#### :house: Internal
* [#82](https://github.com/ember-cli/ember-cli-version-checker/pull/82) chore(ci): install yarn via curl :weary: ([@rwjblue](https://github.com/rwjblue))
* [#81](https://github.com/ember-cli/ember-cli-version-checker/pull/81) chore(ci): Install latest yarn via apt-get ([@rwjblue](https://github.com/rwjblue))

#### Committers: 3
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))
- Tobias Bieniek ([@Turbo87](https://github.com/Turbo87))


## v2.1.2 (2018-04-27)

#### :bug: Bug Fix
* [#53](https://github.com/ember-cli/ember-cli-version-checker/pull/53) Ensure `forEmber` _always_ uses the project. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))


## v2.1.1 (2018-04-27)

#### :bug: Bug Fix
* [#51](https://github.com/ember-cli/ember-cli-version-checker/pull/51) [bugfix] Allow VersionChecker to work with Projects ([@pzuraq](https://github.com/pzuraq))

#### :memo: Documentation
* [#49](https://github.com/ember-cli/ember-cli-version-checker/pull/49) [DOCS]: Document semver methods in README ([@alexander-alvarez](https://github.com/alexander-alvarez))

#### :house: Internal
* [#44](https://github.com/ember-cli/ember-cli-version-checker/pull/44) Linting + Prettier ([@rwjblue](https://github.com/rwjblue))

#### Committers: 3
- Alex Alvarez ([@alexander-alvarez](https://github.com/alexander-alvarez))
- Chris Garrett ([@pzuraq](https://github.com/pzuraq))
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))


## v2.1.0 (2017-10-08)

#### :rocket: Enhancement
* [#43](https://github.com/ember-cli/ember-cli-version-checker/pull/43) Add `.exists()` and document `.version`. ([@rwjblue](https://github.com/rwjblue))

#### :memo: Documentation
* [#42](https://github.com/ember-cli/ember-cli-version-checker/pull/42) Updates to newer JS syntax ([@twokul](https://github.com/twokul))

#### Committers: 2
- Alex Navasardyan ([@twokul](https://github.com/twokul))
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))


## v2.0.0 (2017-05-08)

#### :boom: Breaking Change
* [#41](https://github.com/ember-cli/ember-cli-version-checker/pull/41) Properly handle nested package resolution. ([@rwjblue](https://github.com/rwjblue))
* [#37](https://github.com/ember-cli/ember-cli-version-checker/pull/37) Refactor to Node 4 supported ES2015 syntax. ([@rwjblue](https://github.com/rwjblue))

#### :rocket: Enhancement
* [#39](https://github.com/ember-cli/ember-cli-version-checker/pull/39) Default to `npm` as type. ([@rwjblue](https://github.com/rwjblue))
* [#36](https://github.com/ember-cli/ember-cli-version-checker/pull/36)  CI: Use "auto-dist-tag" for deployment ([@Turbo87](https://github.com/Turbo87))

#### Committers: 2
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- Tobias Bieniek ([@Turbo87](https://github.com/Turbo87))


## v1.3.0 (2017-04-23)

#### :rocket: Enhancement
* [#32](https://github.com/ember-cli/ember-cli-version-checker/pull/32) Add support for gte(), lte(), eq() and neq() ([@Turbo87](https://github.com/Turbo87))

#### :memo: Documentation
* [#26](https://github.com/ember-cli/ember-cli-version-checker/pull/26) Add forEmber section in readme ([@josemarluedke](https://github.com/josemarluedke))

#### :house: Internal
* [#33](https://github.com/ember-cli/ember-cli-version-checker/pull/33) CI: Enable automatic NPM deployment for tags ([@Turbo87](https://github.com/Turbo87))
* [#31](https://github.com/ember-cli/ember-cli-version-checker/pull/31) Extract classes into seperate files ([@Turbo87](https://github.com/Turbo87))

#### Committers: 3
- Jared ([@coderatchet](https://github.com/coderatchet))
- Josemar Luedke ([@josemarluedke](https://github.com/josemarluedke))
- Tobias Bieniek ([@Turbo87](https://github.com/Turbo87))


## v1.2.0 (2016-12-04)

#### :rocket: Enhancement
* [#21](https://github.com/ember-cli/ember-cli-version-checker/pull/21) Add #forEmber helper method to get ember version from bower or npm ([@josemarluedke](https://github.com/josemarluedke))

#### :bug: Bug Fix
* [#23](https://github.com/ember-cli/ember-cli-version-checker/pull/23) All operations like `gt`, `lt`, `isAbove`, etc must return false if the dependency is not present ([@cibernox](https://github.com/cibernox))

#### Committers: 4
- Jacob Jewell ([@jakesjews](https://github.com/jakesjews))
- Josemar Luedke ([@josemarluedke](https://github.com/josemarluedke))
- Miguel Camba ([@cibernox](https://github.com/cibernox))
- Tobias Bieniek ([@Turbo87](https://github.com/Turbo87))


## v1.1.7 (2016-10-07)

#### :bug: Bug Fix
* [#18](https://github.com/ember-cli/ember-cli-version-checker/pull/18) Include only necessary files in the npm package ([@locks](https://github.com/locks))

#### Committers: 1
- Ricardo Mendes ([@locks](https://github.com/locks))


## v1.1.6 (2016-01-20)

#### :bug: Bug Fix
* [#14](https://github.com/ember-cli/ember-cli-version-checker/pull/14) Fix bower dependency path when in child directory ([@HeroicEric](https://github.com/HeroicEric))

#### Committers: 1
- Eric Kelly ([@HeroicEric](https://github.com/HeroicEric))


## v1.1.5 (2015-12-15)

#### :bug: Bug Fix
* [#12](https://github.com/ember-cli/ember-cli-version-checker/pull/12) Support beta/canary version number format ([@minichate](https://github.com/minichate))

#### Committers: 1
- Christopher Troup ([@minichate](https://github.com/minichate))


## 1.1.0 (2015-06-18)

#### :rocket: Enhancement
* [#3](https://github.com/ember-cli/ember-cli-version-checker/pull/3) Allow testing of other packages. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 1
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
