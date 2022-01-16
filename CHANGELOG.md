# Change Log

## [1.8.4-0.9.8](https://github.com/chros73/rtorrent-ps-ch/tree/1.8.4-0.9.8) (2021-09-21)
**Fixed bugs:**

- Fix getting xmlrpc-c in build.sh due to shutdown of Bintray [\#170](https://github.com/chros73/rtorrent-ps-ch/issues/170)

## [1.8.3-0.9.8](https://github.com/chros73/rtorrent-ps-ch/tree/1.8.3-0.9.8) (2019-07-27)
**Implemented enhancements:**

- Upgrade to official rtorrent/libtorrent 0.9.8/0.13.8 releases [\#164](https://github.com/chros73/rtorrent-ps-ch/issues/164)

## [1.8.3-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.8.3-0.9.7) (2018-10-05)
**Fixed bugs:**

- Fix position of 'up\_rate' and 'down\_rate' values in their column on canvas [\#156](https://github.com/chros73/rtorrent-ps-ch/issues/156)

## [1.8.2-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.8.2-0.9.7) (2018-10-02)
**Implemented enhancements:**

- Add rtorrent config syntax highlighting for mcedit [\#153](https://github.com/chros73/rtorrent-ps-ch/issues/153)
- Add 'event.system.startup\_done/shutdown' commands/events [\#152](https://github.com/chros73/rtorrent-ps-ch/issues/152)

**Fixed bugs:**

- Fix 'list' method type and add 'array.size' command [\#154](https://github.com/chros73/rtorrent-ps-ch/issues/154)

## [1.8.1-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.8.1-0.9.7) (2018-09-22)
**Implemented enhancements:**

- Upgrade the used external libraries [\#149](https://github.com/chros73/rtorrent-ps-ch/issues/149)
- Update bintray script with upstream changes [\#148](https://github.com/chros73/rtorrent-ps-ch/issues/148)
- Backport integration tests from upstream [\#147](https://github.com/chros73/rtorrent-ps-ch/issues/147)
- Backport 'try' command [\#146](https://github.com/chros73/rtorrent-ps-ch/issues/146)
- Add 'd.eta.\*' commands [\#145](https://github.com/chros73/rtorrent-ps-ch/issues/145)
- Backport and modify canvas v2 from rtorrent-ps [\#144](https://github.com/chros73/rtorrent-ps-ch/issues/144)

## [1.8.0-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.8.0-0.9.7) (2018-06-09)
**Implemented enhancements:**

- Modify build script a bit [\#140](https://github.com/chros73/rtorrent-ps-ch/issues/140)
- Upgrade to official rtorrent/libtorrent 0.9.7/0.13.7 releases [\#139](https://github.com/chros73/rtorrent-ps-ch/issues/139)

## [1.7.4-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.7.4-0.9.7) (2018-06-05)
**Implemented enhancements:**

- Add binary tarballs and packages on Debian flavours [\#138](https://github.com/chros73/rtorrent-ps-ch/issues/138)
- Add pkg2tgz functionality into build script [\#136](https://github.com/chros73/rtorrent-ps-ch/issues/136)

**Fixed bugs:**

- Fix bugs in 'math.\*' commands [\#135](https://github.com/chros73/rtorrent-ps-ch/issues/135)

## [1.7.3-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.7.3-0.9.7) (2018-05-26)
**Implemented enhancements:**

- Upgrade the used external libraries [\#133](https://github.com/chros73/rtorrent-ps-ch/issues/133)
- Refactor build script a bit [\#132](https://github.com/chros73/rtorrent-ps-ch/issues/132)
- Move changing 'rpath' in binaries to the end of compilation in build script [\#131](https://github.com/chros73/rtorrent-ps-ch/issues/131)

## [1.7.2-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.7.2-0.9.7) (2018-05-19)
**Implemented enhancements:**

- Make '\*' key a built-in keyboard shortcut [\#129](https://github.com/chros73/rtorrent-ps-ch/issues/129)
- Make Info View default on download details [\#128](https://github.com/chros73/rtorrent-ps-ch/issues/128)

## [1.7.1-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.7.1-0.9.7) (2018-05-13)
**Fixed bugs:**

- Fix honoring "throttle.min\_peers\*" settings in rtorrent [\#126](https://github.com/chros73/rtorrent-ps-ch/issues/126)

## [1.7.0-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.7.0-0.9.7) (2018-05-06)
**Implemented enhancements:**

- Get relevant changes from upstream repo [\#124](https://github.com/chros73/rtorrent-ps-ch/issues/124)
- Add 'chars.\*' command group [\#123](https://github.com/chros73/rtorrent-ps-ch/issues/123)
- Include tm\_completed and last\_active custom fields into rtorrent [\#120](https://github.com/chros73/rtorrent-ps-ch/issues/120)
- Backport and modify canvas customization from rtorrent-ps [\#119](https://github.com/chros73/rtorrent-ps-ch/issues/119)

**Fixed bugs:**

- Fix log.messages command in rtorrent-ps [\#122](https://github.com/chros73/rtorrent-ps-ch/issues/122)
- Fix bug with allocatable\_size\_bytes [\#118](https://github.com/chros73/rtorrent-ps-ch/issues/118)

## [1.6.2-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.6.2-0.9.7) (2018-03-10)
**Implemented enhancements:**

- Small input history enhancement [\#114](https://github.com/chros73/rtorrent-ps-ch/issues/114)

**Fixed bugs:**

- Fix bug with selected\_size\_bytes and save it into session [\#116](https://github.com/chros73/rtorrent-ps-ch/issues/116)
- Fix error message in as\_vector method [\#115](https://github.com/chros73/rtorrent-ps-ch/issues/115)

## [1.6.1-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.6.1-0.9.7) (2017-12-10)
**Implemented enhancements:**

- IPv4 filter enhancement [\#112](https://github.com/chros73/rtorrent-ps-ch/issues/112)

## [1.6.0-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.6.0-0.9.7) (2017-08-20)
**Implemented enhancements:**

- Update building instructions [\#111](https://github.com/chros73/rtorrent-ps-ch/issues/111)
- Add proper relative rpath link support [\#110](https://github.com/chros73/rtorrent-ps-ch/issues/110)
- Create optimized gcc build by default on Linux as well [\#109](https://github.com/chros73/rtorrent-ps-ch/issues/109)
- Add hash checking for downloaded packages in build script [\#108](https://github.com/chros73/rtorrent-ps-ch/issues/108)
- Fix compiling issues with gcc v6.x and libtool properly [\#106](https://github.com/chros73/rtorrent-ps-ch/issues/106)
- Upgrade xmlrpc-c external library [\#104](https://github.com/chros73/rtorrent-ps-ch/issues/104)
- Terminate building process any time when the previous step is failed [\#103](https://github.com/chros73/rtorrent-ps-ch/issues/103)
- Refactor build script completely [\#102](https://github.com/chros73/rtorrent-ps-ch/issues/102)
- Rename repo and main directories [\#101](https://github.com/chros73/rtorrent-ps-ch/issues/101)
- Backport relevant upstream build script changes [\#100](https://github.com/chros73/rtorrent-ps-ch/issues/100)
- Separate vanilla build of rtorrent completely [\#99](https://github.com/chros73/rtorrent-ps-ch/issues/99)
- Use tar.gz packages instead of zip with GitHub [\#98](https://github.com/chros73/rtorrent-ps-ch/issues/98)

## [1.5.3-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.5.3-0.9.7) (2017-07-23)
**Implemented enhancements:**

- Add version info to user build as well [\#96](https://github.com/chros73/rtorrent-ps-ch/issues/96)
- Update package dependencies [\#95](https://github.com/chros73/rtorrent-ps-ch/issues/95)
- Don't download packages if they are already available [\#94](https://github.com/chros73/rtorrent-ps-ch/issues/94)
- Upgrade the used external libraries [\#92](https://github.com/chros73/rtorrent-ps-ch/issues/92)
- Backport support for OpenSSL 1.1 [\#91](https://github.com/chros73/rtorrent-ps-ch/issues/91)

**Fixed bugs:**

- Fix rpath linking on newer distros by using relative rpath linking [\#93](https://github.com/chros73/rtorrent-ps-ch/issues/93)
- Fix compiling issues with gcc v6.x [\#89](https://github.com/chros73/rtorrent-ps-ch/issues/89)

## [1.5.2-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.5.2-0.9.7) (2017-07-11)
**Implemented enhancements:**

- Modify directory.watch.added and add directory.watch.removed command [\#87](https://github.com/chros73/rtorrent-ps-ch/issues/87)

**Fixed bugs:**

- Fix race condition between CommandScheduler insert & call\_item [\#88](https://github.com/chros73/rtorrent-ps-ch/issues/88)

## [1.5.1-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.5.1-0.9.7) (2017-06-05)
**Implemented enhancements:**

- Modify postfixes on Info and Peer List pane [\#85](https://github.com/chros73/rtorrent-ps-ch/issues/85)
- Make global throttle steps adjustable [\#84](https://github.com/chros73/rtorrent-ps-ch/issues/84)
- Implement input \(command\) history with categories [\#83](https://github.com/chros73/rtorrent-ps-ch/issues/83)

## [1.5.0-0.9.7](https://github.com/chros73/rtorrent-ps-ch/tree/1.5.0-0.9.7) (2017-05-15)
**Implemented enhancements:**

- Modify bencode parse info patch to sanitize output [\#80](https://github.com/chros73/rtorrent-ps-ch/issues/80)
- Update docs [\#79](https://github.com/chros73/rtorrent-ps-ch/issues/79)
- Support only git version \(not old versions\) [\#78](https://github.com/chros73/rtorrent-ps-ch/issues/78)
- Update build.sh [\#77](https://github.com/chros73/rtorrent-ps-ch/issues/77)
- Update to current head fork [\#75](https://github.com/chros73/rtorrent-ps-ch/issues/75)
- Modify throttle status bar mod to be able to display multiple values [\#74](https://github.com/chros73/rtorrent-ps-ch/issues/74)
- Add support for multiple local rtorrent-ps versions in build script [\#73](https://github.com/chros73/rtorrent-ps-ch/issues/73)
- Add support for basic arithmetic operators to git version [\#71](https://github.com/chros73/rtorrent-ps-ch/issues/71)
- Modify ui\_pyroscope.cc to handle partially done downloads in git version [\#70](https://github.com/chros73/rtorrent-ps-ch/issues/70)
- Fix partially done downloads and choke groups in git version [\#69](https://github.com/chros73/rtorrent-ps-ch/issues/69)
- Modify fixing honoring system.file.allocate.set=1 patch in git version [\#68](https://github.com/chros73/rtorrent-ps-ch/issues/68)
- Bump rtorrent commit backwards in build script for git version [\#67](https://github.com/chros73/rtorrent-ps-ch/issues/67)
- Small color config changes [\#65](https://github.com/chros73/rtorrent-ps-ch/issues/65)
- Get relevant changes from upstream repo [\#64](https://github.com/chros73/rtorrent-ps-ch/issues/64)
- Backport temp filter patch only for git version [\#63](https://github.com/chros73/rtorrent-ps-ch/issues/63)
- Bump libtorrent/rtorrent commit in build script for git version [\#62](https://github.com/chros73/rtorrent-ps-ch/issues/62)

**Fixed bugs:**

- rtorrent become to unusable when set out rang ui color [\#76](https://github.com/chros73/rtorrent-ps-ch/issues/76)
- self url in build.sh [\#60](https://github.com/chros73/rtorrent-ps-ch/issues/60)

**Merged pull requests:**

- Update to current head fork [\#61](https://github.com/chros73/rtorrent-ps-ch/pull/61) ([chros73](https://github.com/chros73))

## [1.4.6-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.4.6-0.9.6) (2016-10-12)
**Implemented enhancements:**

- Bump libtorrent/rtorrent commit in build script and remove IPv6 patches for git version [\#57](https://github.com/chros73/rtorrent-ps-ch/issues/57)

## [1.4.5-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.4.5-0.9.6) (2016-09-20)
**Implemented enhancements:**

- Add IPv6 support to git build [\#55](https://github.com/chros73/rtorrent-ps-ch/issues/55)
- Bump libtorrent/rtorrent commit in build script for git version [\#54](https://github.com/chros73/rtorrent-ps-ch/issues/54)

## [1.4.4-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.4.4-0.9.6) (2016-08-30)
**Implemented enhancements:**

- Bump rtorrent commit in build script for git version [\#52](https://github.com/chros73/rtorrent-ps-ch/issues/52)

**Fixed bugs:**

- Fix broken full list redraw in git version [\#51](https://github.com/chros73/rtorrent-ps-ch/issues/51)

## [1.4.3-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.4.3-0.9.6) (2016-08-29)
**Implemented enhancements:**

- Modify git section main readme file [\#50](https://github.com/chros73/rtorrent-ps-ch/issues/50)
- Refactor all the patches thanks to git support [\#48](https://github.com/chros73/rtorrent-ps-ch/issues/48)
- Add proper support for building from git versions in build script [\#47](https://github.com/chros73/rtorrent-ps-ch/issues/47)
- Add ability in build script to use multiple versions in name of patches [\#46](https://github.com/chros73/rtorrent-ps-ch/issues/46)
- Add ability to build only extended when building for user [\#45](https://github.com/chros73/rtorrent-ps-ch/issues/45)

## [1.4.2-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.4.2-0.9.6) (2016-08-24)
**Implemented enhancements:**

- Backport rpc unit conversion fix patch [\#43](https://github.com/chros73/rtorrent-ps-ch/issues/43)
- Backport increased max file size patch [\#42](https://github.com/chros73/rtorrent-ps-ch/issues/42)
- Rename DHT segfault fix patch [\#41](https://github.com/chros73/rtorrent-ps-ch/issues/41)
- Modify status bar mod to be able to display 1 throttle.down as well [\#37](https://github.com/chros73/rtorrent-ps-ch/issues/37)

**Fixed bugs:**

- Fix honoring system.file.allocate.set=1 rtorrent config setting [\#39](https://github.com/chros73/rtorrent-ps-ch/issues/39)
- Fix honoring system.file.allocate.set=0 rtorrent config setting [\#38](https://github.com/chros73/rtorrent-ps-ch/issues/38)

**Merged pull requests:**

- Update to current head fork [\#40](https://github.com/chros73/rtorrent-ps-ch/pull/40) ([chros73](https://github.com/chros73))

## [1.4.1-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.4.1-0.9.6) (2016-07-31)
**Implemented enhancements:**

- Add DHT segfault fix patch [\#35](https://github.com/chros73/rtorrent-ps-ch/issues/35)
- Add bencode parse info patch [\#34](https://github.com/chros73/rtorrent-ps-ch/issues/34)
- Backport use xb with peer list patch [\#33](https://github.com/chros73/rtorrent-ps-ch/issues/33)
- Backport show non-preloaded pieces stat patch [\#32](https://github.com/chros73/rtorrent-ps-ch/issues/32)
- Backport save downloaded stat per torrent patch [\#31](https://github.com/chros73/rtorrent-ps-ch/issues/31)
- Backport context for internal\_error patch [\#30](https://github.com/chros73/rtorrent-ps-ch/issues/30)
- Backport bencode fixes patch [\#29](https://github.com/chros73/rtorrent-ps-ch/issues/29)
- Backport adding 2 more torrent clients patch [\#28](https://github.com/chros73/rtorrent-ps-ch/issues/28)
- Add ability in build script to use 'all' in librottent patches [\#27](https://github.com/chros73/rtorrent-ps-ch/issues/27)
- Docs: Add up-to-date compiling instructions [\#26](https://github.com/chros73/rtorrent-ps-ch/issues/26)

## [1.4-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.4-0.9.6) (2016-07-20)
**Implemented enhancements:**

- Add magnet property to downloads in rtorrent [\#23](https://github.com/chros73/rtorrent-ps-ch/issues/23)
- Add separate change log file [\#22](https://github.com/chros73/rtorrent-ps-ch/issues/22)

## [1.3-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.3-0.9.6) (2016-07-07)
**Fixed bugs:**

- Fix scheduled sorting/filtering bug on started and stopped views in rtorrent [\#19](https://github.com/chros73/rtorrent-ps-ch/issues/19)

## [1.2-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.2-0.9.6) (2016-06-27)
**Implemented enhancements:**

- Modify Data-directory column under the hood [\#17](https://github.com/chros73/rtorrent-ps-ch/issues/17)
- Add modified screenshot [\#12](https://github.com/chros73/rtorrent-ps-ch/issues/12)

## [1.1-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.1-0.9.6) (2016-06-24)
**Implemented enhancements:**

- Modify Unsafe-data column under the hood [\#15](https://github.com/chros73/rtorrent-ps-ch/issues/15)
- Add more 256 color themes [\#13](https://github.com/chros73/rtorrent-ps-ch/issues/13)

**Fixed bugs:**

- Fix displaying last\_active time in upload rate column when peers are connected [\#14](https://github.com/chros73/rtorrent-ps-ch/issues/14)

## [1.0-0.9.6](https://github.com/chros73/rtorrent-ps-ch/tree/1.0-0.9.6) (2016-05-21)
**Implemented enhancements:**

- Add version number [\#11](https://github.com/chros73/rtorrent-ps-ch/issues/11)
- Add fork notes to readme file [\#10](https://github.com/chros73/rtorrent-ps-ch/issues/10)
- Change name in title and in package name [\#9](https://github.com/chros73/rtorrent-ps-ch/issues/9)
- Modify build script [\#8](https://github.com/chros73/rtorrent-ps-ch/issues/8)
- Replace fix path of install directory in build script [\#5](https://github.com/chros73/rtorrent-ps-ch/issues/5)
- Display values of 1 throttle.up in the first part of status bar [\#4](https://github.com/chros73/rtorrent-ps-ch/issues/4)
- Add 2 more columns on collapsed view [\#3](https://github.com/chros73/rtorrent-ps-ch/issues/3)
- Change character in header of newly added Throttle column [\#2](https://github.com/chros73/rtorrent-ps-ch/issues/2)
- Include more columns on collapsed view [\#1](https://github.com/chros73/rtorrent-ps-ch/issues/1)



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*