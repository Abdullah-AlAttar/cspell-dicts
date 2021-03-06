# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [1.0.19](https://github.com/streetsidesoftware/cspell-dicts/compare/cspell-dict-java@1.0.18...cspell-dict-java@1.0.19) (2020-11-21)

**Note:** Version bump only for package cspell-dict-java

## [1.0.18](https://github.com/streetsidesoftware/cspell-dicts/compare/cspell-dict-java@1.0.17...cspell-dict-java@1.0.18) (2020-11-08)

### Bug Fixes

- do not include Configstore if not necessary ([#270](https://github.com/streetsidesoftware/cspell-dicts/issues/270)) ([d8b625f](https://github.com/streetsidesoftware/cspell-dicts/commit/d8b625f2f42d5cc6c4a9390216ac1e5037886e44))

## [1.0.17](https://github.com/streetsidesoftware/cspell-dicts/compare/cspell-dict-java@1.0.16...cspell-dict-java@1.0.17) (2020-10-21)

**Note:** Version bump only for package cspell-dict-java

# Change Log

## 1.0.6

- Provide an updated wordlist for JDK12 (previously JDK8) generated by
  traversing all public accessible symbols of OpenJDK 12 using a new
  [script](https://github.com/bentolor/jdk9-module-enumerator)
  leveraging [classgraph project](https://github.com/classgraph/classgraph)
- Manually add Java reserved words copied fromt he official [Java Tutorials](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/_keywords.html)
- Add `true`, `false` and `null` literals to dictionary

## 1.0.0

- Initial Release
