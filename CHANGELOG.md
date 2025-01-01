# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

<!-- Format restrictions - see https://common-changelog.org and https://keepachangelog.com/ for details -->
<!-- Each Release must start with a line for the release version of exactly this format: ## [version] -->
<!-- The subsequent comment lines start with a space - not to irritate the release scripts parser!
 ## [major.minor.micro]
 <empty line> - optional sub sections may follow like:
 ### Added:
 - This feature was added
 <empty line>
 ### Changed:
 - This feature was changed
 <empty line>
 ### Removed:
 - This feature was removed
 <empty line>
 ### Fixed:
 - This issue was fixed
 <empty line>
 <empty line> - next line is the starting of the previous release
 ## [major.minor.micro]
 <empty line>
 <...>
 !!! In addition the compare URL links are to be maintained at the end of this CHANGELOG.md as follows.
     These links provide direct access to the GitHub compare vs. the previous release.
     The particular link of a released version will be copied to the release notes of a release accordingly.
     At the end of this file appropriate compare links have to be maintained for each release version in format:
 
  +-current release version
  |
  |                   +-URL to this repo              previous release version tag-+       +-current release version tag
  |                   |                                                            |       |
 [major.minor.micro]: https://github.com/mavenplugins/parent-maven-plugins/compare/vM.N.u..vM.N.u
-->
<!--
## [Unreleased]

### 🚨 Removed
- TBD

### 💥 Breaking
- TBD

### 📢 Deprecated
- TBD

### 🚀 New Features
- TBD

### 🐛 Fixes
- TBD

### ✨ Improvements
- TBD

### 🔧 Internal Changes
- TBD

### 🚦 Tests
- TBD

### 📦 Updates
- TBD

### 🔒 Security
- TBD

### 📝 Documentation Updates
- TBD
-->

## [Unreleased]
<!-- !!! Align version in badge URLs as well !!! -->
[![6 Badge](https://img.shields.io/nexus/r/io.github.mavenplugins/parent-maven-plugins?server=https://s01.oss.sonatype.org&label=Maven%20Central&queryOpt=:v=6)](https://central.sonatype.com/artifact/io.github.mavenplugins/parent-maven-plugins/6)

### Summary
- TBD

### 📦 Updates
- TBD

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>parent-maven-plugins</artifactId>
    <version>6</version>
  </parent>
  ```


## [5]
<!-- !!! Align version in badge URLs as well !!! -->
[![5 Badge](https://img.shields.io/nexus/r/io.github.mavenplugins/parent-maven-plugins?server=https://s01.oss.sonatype.org&label=Maven%20Central&queryOpt=:v=5)](https://central.sonatype.com/artifact/io.github.mavenplugins/parent-maven-plugins/5)

### Summary
- Refer to parent pom version `io.github.mavenplugins:parent-base-maven-plugins:3`

### 📦 Updates
- pom.xml:
  - bump `<version.base-maven-plugins>1.0.2</version.base-maven-plugins>`

### 🔒 Security
- Update reference to parent pom version `io.github.mavenplugins:parent-base-maven-plugins:3`

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>parent-maven-plugins</artifactId>
    <version>5</version>
  </parent>
  ```


## [4]
<!-- !!! Align version in badge URLs as well !!! -->
[![4 Badge](https://img.shields.io/nexus/r/io.github.mavenplugins/parent-maven-plugins?server=https://s01.oss.sonatype.org&label=Maven%20Central&queryOpt=:v=4)](https://central.sonatype.com/artifact/io.github.mavenplugins/parent-maven-plugins/4)

### Summary
- Initial release maintained within GitHub mavenplugins organization
- Moved and updated from `de.mhoffrogge.maven:parent-maven-plugins:3` at [parent-maven-plugins on GitLab](https://gitlab.com/mhopen/maven-plugins/-/tree/master/parent-maven-plugins?ref_type=heads)

### 📦 Updates
- pom.xml:
  - groupId changed to `io.github.mavenplugins`
  - bump version to 4
  - remove obsolete property `<version.plexus-component-metadata>1.7.1</version.plexus-component-metadata>`
  - remove obsolete dependency managements
  - add dependency management for io.github.mavenplugins:base-maven-plugins

### 📝 Usage
- For details on usage please have a look to the comments in [pom.xml](pom.xml)
- Use as parent pom:
  ```
  <parent>
    <groupId>io.github.mavenplugins</groupId>
    <artifactId>parent-maven-plugins</artifactId>
    <version>4</version>
  </parent>
  ```


<!--
## []

### NeverReleased
- This is just a dummy placeholder to make the parser of GHCICD/release-notes-from-changelog@v1 happy!
-->

[Unreleased]: https://github.com/mavenplugins/parent-maven-plugins/compare/v5..HEAD
[5]: https://github.com/mavenplugins/parent-maven-plugins/compare/v4..v5
[4]: https://github.com/mavenplugins/parent-maven-plugins/releases/tag/v4
