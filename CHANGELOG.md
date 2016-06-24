# Node.js ChangeLog

## 2016-06-28, Version 4.4.7 'Argon' (LTS), @thealphanerd

### Notable Changes

- Coming Soon

### Commits

* [[`87cdb83a96`](https://github.com/nodejs/node/commit/87cdb83a96)] - **benchmark**: merge url.js with url-resolve.js (Andreas Madsen) [#5177](https://github.com/nodejs/node/pull/5177)
* [[`921e8568d5`](https://github.com/nodejs/node/commit/921e8568d5)] - **benchmark**: move misc to categorized directories (Andreas Madsen) [#5177](https://github.com/nodejs/node/pull/5177)
* [[`c189eec14e`](https://github.com/nodejs/node/commit/c189eec14e)] - **benchmark**: fix configuation parameters (Andreas Madsen) [#5177](https://github.com/nodejs/node/pull/5177)
* [[`58ad451f0b`](https://github.com/nodejs/node/commit/58ad451f0b)] - **benchmark**: move string-decoder to its own category (Andreas Madsen) [#5177](https://github.com/nodejs/node/pull/5177)
* [[`a01caa3166`](https://github.com/nodejs/node/commit/a01caa3166)] - **build**: don't compile with -B, redux (Ben Noordhuis) [#6650](https://github.com/nodejs/node/pull/6650)
* [[`37606caeaf`](https://github.com/nodejs/node/commit/37606caeaf)] - **build**: don't compile with -B (Ben Noordhuis) [#6393](https://github.com/nodejs/node/pull/6393)
* [[`64fb7a1929`](https://github.com/nodejs/node/commit/64fb7a1929)] - **build**: update android-configure script for npm (Robert Chiras) [#6349](https://github.com/nodejs/node/pull/6349)
* [[`43ce6fc8d2`](https://github.com/nodejs/node/commit/43ce6fc8d2)] - **build**: fix DESTCPU detection for binary target (Richard Lau) [#6310](https://github.com/nodejs/node/pull/6310)
* [[`6dfe7aeed5`](https://github.com/nodejs/node/commit/6dfe7aeed5)] - **cares**: Support malloc(0) scenarios for AIX (Gireesh Punathil) [#6305](https://github.com/nodejs/node/pull/6305)
* [[`2389006720`](https://github.com/nodejs/node/commit/2389006720)] - **debugger**: display array contents in repl (cjihrig) [#6448](https://github.com/nodejs/node/pull/6448)
* [[`1c6809ce75`](https://github.com/nodejs/node/commit/1c6809ce75)] - **debugger**: introduce exec method for debugger (Jackson Tian)
* [[`de00f91041`](https://github.com/nodejs/node/commit/de00f91041)] - **deps**: backport bc2e393 from v8 upstream (evan.lucas) [#3792](https://github.com/nodejs/node/pull/3792)
* [[`1549899531`](https://github.com/nodejs/node/commit/1549899531)] - **dgram,test**: add addMembership/dropMembership tests (Rich Trott) [#6753](https://github.com/nodejs/node/pull/6753)
* [[`6c146818e8`](https://github.com/nodejs/node/commit/6c146818e8)] - **doc**: fix layout problem in v4 changelog (Myles Borins) [#7394](https://github.com/nodejs/node/pull/7394)
* [[`98469ad84d`](https://github.com/nodejs/node/commit/98469ad84d)] - **doc**: correct args for cluster message event (Colin Ihrig) [#7297](https://github.com/nodejs/node/pull/7297)
* [[`67863f110b`](https://github.com/nodejs/node/commit/67863f110b)] - **doc**: update licenses (Myles Borins) [#7127](https://github.com/nodejs/node/pull/7127)
* [[`c31eaad42d`](https://github.com/nodejs/node/commit/c31eaad42d)] - **doc**: clarify buffer class (Steve Mao) [#6914](https://github.com/nodejs/node/pull/6914)
* [[`e0dd476fe5`](https://github.com/nodejs/node/commit/e0dd476fe5)] - **doc**: fix typos in timers topic to aid readability (Kevin Donahue) [#6916](https://github.com/nodejs/node/pull/6916)
* [[`a8391bc9fc`](https://github.com/nodejs/node/commit/a8391bc9fc)] - **doc**: add jhamhader to collaborators (Yuval Brik) [#6946](https://github.com/nodejs/node/pull/6946)
* [[`22ca7b877b`](https://github.com/nodejs/node/commit/22ca7b877b)] - **doc**: add @othiym23 to list of collaborators (Forrest L Norvell) [#6945](https://github.com/nodejs/node/pull/6945)
* [[`2c3c4e5819`](https://github.com/nodejs/node/commit/2c3c4e5819)] - **doc**: reference list of language-specific globals (Anna Henningsen) [#6900](https://github.com/nodejs/node/pull/6900)
* [[`5a1a0b5ed1`](https://github.com/nodejs/node/commit/5a1a0b5ed1)] - **doc**: make the api doc print-friendly (Marian) [#6748](https://github.com/nodejs/node/pull/6748)
* [[`03db88e012`](https://github.com/nodejs/node/commit/03db88e012)] - **doc**: add bengl to collaborators (Bryan English) [#6921](https://github.com/nodejs/node/pull/6921)
* [[`fbf95dde94`](https://github.com/nodejs/node/commit/fbf95dde94)] - **doc**: Update DCO to v1.1 (William Kapke) [#6353](https://github.com/nodejs/node/pull/6353)
* [[`f23a9c39c0`](https://github.com/nodejs/node/commit/f23a9c39c0)] - **doc**: fix typo in Error.captureStackTrace (Mohsen) [#6811](https://github.com/nodejs/node/pull/6811)
* [[`30ab6a890c`](https://github.com/nodejs/node/commit/30ab6a890c)] - **doc**: fix name to match git log (Robert Jefe Lindstaedt) [#6880](https://github.com/nodejs/node/pull/6880)
* [[`2b0f40ca16`](https://github.com/nodejs/node/commit/2b0f40ca16)] - **doc**: add note for fs.watch virtualized env (Robert Jefe Lindstaedt) [#6809](https://github.com/nodejs/node/pull/6809)
* [[`3b461870be`](https://github.com/nodejs/node/commit/3b461870be)] - **doc**: Backport ee.once doc clarifications to 4.x. (Lance Ball) [#7103](https://github.com/nodejs/node/pull/7103)
* [[`eadb7e5b20`](https://github.com/nodejs/node/commit/eadb7e5b20)] - **doc**: subdivide TOC, add auxiliary links (Jeremiah Senkpiel) [#6167](https://github.com/nodejs/node/pull/6167)
* [[`107839c5dd`](https://github.com/nodejs/node/commit/107839c5dd)] - **doc**: no Node.js(1) (Jeremiah Senkpiel) [#6167](https://github.com/nodejs/node/pull/6167)
* [[`401325f9e2`](https://github.com/nodejs/node/commit/401325f9e2)] - **doc**: better example & synopsis (Jeremiah Senkpiel) [#6167](https://github.com/nodejs/node/pull/6167)
* [[`c654184f28`](https://github.com/nodejs/node/commit/c654184f28)] - **doc**: remove link to Sign in crypto.md (Kirill Fomichev) [#6812](https://github.com/nodejs/node/pull/6812)
* [[`3e9288e466`](https://github.com/nodejs/node/commit/3e9288e466)] - **doc**: fix exec example in child_process (Evan Lucas) [#6660](https://github.com/nodejs/node/pull/6660)
* [[`3d820e45b4`](https://github.com/nodejs/node/commit/3d820e45b4)] - **doc**: "a" -> "an" in api/documentation.md (Anchika Agarwal) [#6689](https://github.com/nodejs/node/pull/6689)
* [[`352496daa2`](https://github.com/nodejs/node/commit/352496daa2)] - **doc**: move the readme newcomers section (Jeremiah Senkpiel) [#6681](https://github.com/nodejs/node/pull/6681)
* [[`ac6b921ce5`](https://github.com/nodejs/node/commit/ac6b921ce5)] - **doc**: mention existence/purpose of module wrapper (Matt Harrison) [#6433](https://github.com/nodejs/node/pull/6433)
* [[`97d1fc0fc6`](https://github.com/nodejs/node/commit/97d1fc0fc6)] - **doc**: improve onboarding-extras.md formatting (Jeremiah Senkpiel) [#6548](https://github.com/nodejs/node/pull/6548)
* [[`c9b144ddd4`](https://github.com/nodejs/node/commit/c9b144ddd4)] - **doc**: linkify remaining references to fs.Stats object (Kevin Donahue) [#6485](https://github.com/nodejs/node/pull/6485)
* [[`d909c25a33`](https://github.com/nodejs/node/commit/d909c25a33)] - **doc**: fix the lint of an example in cluster.md (yorkie) [#6516](https://github.com/nodejs/node/pull/6516)
* [[`21d02f460f`](https://github.com/nodejs/node/commit/21d02f460f)] - **doc**: add missing underscore for markdown italics (Kevin Donahue) [#6529](https://github.com/nodejs/node/pull/6529)
* [[`18ecc779bb`](https://github.com/nodejs/node/commit/18ecc779bb)] - **doc**: ensure consistent grammar in node.1 file (justshiv) [#6426](https://github.com/nodejs/node/pull/6426)
* [[`52d9e7b61d`](https://github.com/nodejs/node/commit/52d9e7b61d)] - **doc**: fix a typo in __dirname section (William Luo) [#6473](https://github.com/nodejs/node/pull/6473)
* [[`de20235235`](https://github.com/nodejs/node/commit/de20235235)] - **doc**: remove all scrollbar styling (Claudio Rodriguez) [#6479](https://github.com/nodejs/node/pull/6479)
* [[`a6f45b4eda`](https://github.com/nodejs/node/commit/a6f45b4eda)] - **doc**: Remove extra space in REPL example (Juan) [#6447](https://github.com/nodejs/node/pull/6447)
* [[`feda15b2b8`](https://github.com/nodejs/node/commit/feda15b2b8)] - **doc**: update build instructions for OS X (Rich Trott) [#6309](https://github.com/nodejs/node/pull/6309)
* [[`3d1a3e4a30`](https://github.com/nodejs/node/commit/3d1a3e4a30)] - **doc**: change references to Stable to Current (Myles Borins) [#6318](https://github.com/nodejs/node/pull/6318)
* [[`e28598b1ef`](https://github.com/nodejs/node/commit/e28598b1ef)] - **doc**: update authors (James M Snell) [#6373](https://github.com/nodejs/node/pull/6373)
* [[`0f3a94acbd`](https://github.com/nodejs/node/commit/0f3a94acbd)] - **doc**: add JacksonTian to collaborators (Jackson Tian) [#6388](https://github.com/nodejs/node/pull/6388)
* [[`d7d54c8fd2`](https://github.com/nodejs/node/commit/d7d54c8fd2)] - **doc**: add Minqi Pan to collaborators (Minqi Pan) [#6387](https://github.com/nodejs/node/pull/6387)
* [[`83721c6fd2`](https://github.com/nodejs/node/commit/83721c6fd2)] - **doc**: add eljefedelrodeodeljefe to collaborators (Robert Jefe Lindstaedt) [#6389](https://github.com/nodejs/node/pull/6389)
* [[`b112fd1b4e`](https://github.com/nodejs/node/commit/b112fd1b4e)] - **doc**: add ronkorving to collaborators (ronkorving) [#6385](https://github.com/nodejs/node/pull/6385)
* [[`ac60d9cc86`](https://github.com/nodejs/node/commit/ac60d9cc86)] - **doc**: add estliberitas to collaborators (Alexander Makarenko) [#6386](https://github.com/nodejs/node/pull/6386)
* [[`435cd56de5`](https://github.com/nodejs/node/commit/435cd56de5)] - **doc**: DCO anchor that doesn't change (William Kapke) [#6257](https://github.com/nodejs/node/pull/6257)
* [[`7d8141dd1b`](https://github.com/nodejs/node/commit/7d8141dd1b)] - **doc**: add stefanmb to collaborators (Stefan Budeanu) [#6227](https://github.com/nodejs/node/pull/6227)
* [[`6dfc96326d`](https://github.com/nodejs/node/commit/6dfc96326d)] - **doc**: add iWuzHere to collaborators (Imran Iqbal) [#6226](https://github.com/nodejs/node/pull/6226)
* [[`3dbcc73159`](https://github.com/nodejs/node/commit/3dbcc73159)] - **doc**: add santigimeno to collaborators (Santiago Gimeno) [#6225](https://github.com/nodejs/node/pull/6225)
* [[`ae3eb24a3d`](https://github.com/nodejs/node/commit/ae3eb24a3d)] - **doc**: add addaleax to collaborators (Anna Henningsen) [#6224](https://github.com/nodejs/node/pull/6224)
* [[`46ee7bb4ba`](https://github.com/nodejs/node/commit/46ee7bb4ba)] - **doc**: fix incorrect references in buffer docs (Amery) [#6194](https://github.com/nodejs/node/pull/6194)
* [[`e3f78eb7c1`](https://github.com/nodejs/node/commit/e3f78eb7c1)] - **doc**: improve rendering of v4.4.5 changelog entry (Myles Borins) [#6958](https://github.com/nodejs/node/pull/6958)
* [[`bac87d01d9`](https://github.com/nodejs/node/commit/bac87d01d9)] - **gitignore**: adding .vs/ directory to .gitignore (Mike Kaufman) [#6070](https://github.com/nodejs/node/pull/6070)
* [[`93f2314dc2`](https://github.com/nodejs/node/commit/93f2314dc2)] - **gitignore**: ignore VS 2015 *.VC.opendb files (Mike Kaufman) [#6070](https://github.com/nodejs/node/pull/6070)
* [[`c98aaf59bf`](https://github.com/nodejs/node/commit/c98aaf59bf)] - **http**: speed up checkIsHttpToken (Jackson Tian) [#4790](https://github.com/nodejs/node/pull/4790)
* [[`552e25cb6b`](https://github.com/nodejs/node/commit/552e25cb6b)] - **lib,test**: update in preparation for linter update (Rich Trott) [#6498](https://github.com/nodejs/node/pull/6498)
* [[`aaeeec4765`](https://github.com/nodejs/node/commit/aaeeec4765)] - **lib,test,tools**: alignment on variable assignments (Rich Trott) [#6869](https://github.com/nodejs/node/pull/6869)
* [[`b3acbc5648`](https://github.com/nodejs/node/commit/b3acbc5648)] - **net**: replace __defineGetter__ with defineProperty (Fedor Indutny) [#6284](https://github.com/nodejs/node/pull/6284)
* [[`4c1eb5bf03`](https://github.com/nodejs/node/commit/4c1eb5bf03)] - **repl**: create history file with mode 0600 (Carl Lei) [#3394](https://github.com/nodejs/node/pull/3394)
* [[`90306bb81d`](https://github.com/nodejs/node/commit/90306bb81d)] - **src**: use size_t for http parser array size fields (Ben Noordhuis) [#5969](https://github.com/nodejs/node/pull/5969)
* [[`af41a63d0f`](https://github.com/nodejs/node/commit/af41a63d0f)] - **src**: replace ARRAY_SIZE with typesafe arraysize (Ben Noordhuis) [#5969](https://github.com/nodejs/node/pull/5969)
* [[`037291e31f`](https://github.com/nodejs/node/commit/037291e31f)] - **src**: make sure Utf8Value always zero-terminates (Anna Henningsen) [#7101](https://github.com/nodejs/node/pull/7101)
* [[`a08a0179e9`](https://github.com/nodejs/node/commit/a08a0179e9)] - **stream**: ensure awaitDrain is increased once (David Halls) [#7292](https://github.com/nodejs/node/pull/7292)
* [[`b73ec46dcb`](https://github.com/nodejs/node/commit/b73ec46dcb)] - **stream**: reset awaitDrain after manual .resume() (Anna Henningsen) [#7160](https://github.com/nodejs/node/pull/7160)
* [[`55319fe798`](https://github.com/nodejs/node/commit/55319fe798)] - **stream_base**: expose `bytesRead` getter (Fedor Indutny) [#6284](https://github.com/nodejs/node/pull/6284)
* [[`0414d882ce`](https://github.com/nodejs/node/commit/0414d882ce)] - **test**: fix test-net-* error code check for getaddrinfo(3) (Natanael Copa) [#5099](https://github.com/nodejs/node/pull/5099)
* [[`be0bb5f5fc`](https://github.com/nodejs/node/commit/be0bb5f5fc)] - **test**: fix unreliable known_issues test (Rich Trott) [#6555](https://github.com/nodejs/node/pull/6555)
* [[`ab50e82f42`](https://github.com/nodejs/node/commit/ab50e82f42)] - **test**: fix test-process-exec-argv flakiness (Santiago Gimeno) [#7128](https://github.com/nodejs/node/pull/7128)
* [[`4e38655d5f`](https://github.com/nodejs/node/commit/4e38655d5f)] - **test**: refactor test-tls-reuse-host-from-socket (Rich Trott) [#6756](https://github.com/nodejs/node/pull/6756)
* [[`1c4549a31e`](https://github.com/nodejs/node/commit/1c4549a31e)] - **test**: fix flaky test-stdout-close-catch (Santiago Gimeno) [#6808](https://github.com/nodejs/node/pull/6808)
* [[`3b94e31245`](https://github.com/nodejs/node/commit/3b94e31245)] - **test**: robust handling of env for npm-test-install (Myles Borins) [#6797](https://github.com/nodejs/node/pull/6797)
* [[`4067cde7ee`](https://github.com/nodejs/node/commit/4067cde7ee)] - **test**: abstract skip functionality to common (Jeremiah Senkpiel) [#7114](https://github.com/nodejs/node/pull/7114)
* [[`8b396e3d71`](https://github.com/nodejs/node/commit/8b396e3d71)] - **test**: fix test-debugger-repl-break-in-module (Rich Trott) [#6686](https://github.com/nodejs/node/pull/6686)
* [[`847b29c050`](https://github.com/nodejs/node/commit/847b29c050)] - **test**: fix test-debugger-repl-term (Rich Trott) [#6682](https://github.com/nodejs/node/pull/6682)
* [[`1d68bdbe3f`](https://github.com/nodejs/node/commit/1d68bdbe3f)] - **test**: fix error message checks in test-module-loading (James M Snell) [#5986](https://github.com/nodejs/node/pull/5986)
* [[`7e739ae159`](https://github.com/nodejs/node/commit/7e739ae159)] - **test,tools**: adjust function argument alignment (Rich Trott) [#7100](https://github.com/nodejs/node/pull/7100)
* [[`216486c2b6`](https://github.com/nodejs/node/commit/216486c2b6)] - **tools**: lint for function argument alignment (Rich Trott) [#7100](https://github.com/nodejs/node/pull/7100)
* [[`6a76485ad7`](https://github.com/nodejs/node/commit/6a76485ad7)] - **tools**: update ESLint to 2.9.0 (Rich Trott) [#6498](https://github.com/nodejs/node/pull/6498)
* [[`a31153c02c`](https://github.com/nodejs/node/commit/a31153c02c)] - **tools**: remove the minifying logic (Sakthipriyan Vairamani) [#6636](https://github.com/nodejs/node/pull/6636)
* [[`10bd1a73fd`](https://github.com/nodejs/node/commit/10bd1a73fd)] - **tools**: fix license-builder.sh again for ICU (Steven R. Loomis) [#6068](https://github.com/nodejs/node/pull/6068)
* [[`0f6146c6c0`](https://github.com/nodejs/node/commit/0f6146c6c0)] - **tools**: add tests for the doctool (Ian Kronquist) [#6031](https://github.com/nodejs/node/pull/6031)
* [[`cc3645cff3`](https://github.com/nodejs/node/commit/cc3645cff3)] - **tools**: lint for alignment of variable assignments (Rich Trott) [#6869](https://github.com/nodejs/node/pull/6869)

## 2016-06-22, Version 4.4.6 'Argon' (LTS), @thealphanerd

### Notable Changes

This is an important security release. All Node.js users should consult the security release summary at nodejs.org for details on patched vulnerabilities.

This release is specifically related to a Buffer overflow vulnerability discovered in v8, more details can be found [in the CVE](https://www.cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-1669)

### Commits

* [[`134c3b3977`](https://github.com/nodejs/node/commit/134c3b3977)] - **deps**: backport 3a9bfec from v8 upstream (Ben Noordhuis) [nodejs/node-private#38](https://github.com/nodejs/node-private/pull/38)

## 2016-05-24, Version 4.4.5 'Argon' (LTS), @thealphanerd

### Notable Changes

- **buffer**:
  - Buffer.indexOf now returns correct values for all UTF-16 input (Anna Henningsen) [#6511](https://github.com/nodejs/node/pull/6511)
- **contextify**:
  - Context objects are now properly garbage collected, this solves a problem some individuals were experiencing with extreme memory growth (Ali Ijaz Sheikh) [#6871](https://github.com/nodejs/node/pull/6871)
- **deps**:
  - update npm to 2.15.5 (Rebecca Turner) [#6663](https://github.com/nodejs/node/pull/6663)
- **http**:
  - Invalid status codes can no longer be sent. Limited to 3 digit numbers between 100 - 999 (Brian White) [#6291](https://github.com/nodejs/node/pull/6291)

### Commits

* [[`8b077faa82`](https://github.com/nodejs/node/commit/8b077faa82)] - **buffer**: fix UCS2 indexOf for odd buffer length (Anna Henningsen) [#6511](https://github.com/nodejs/node/pull/6511)
* [[`12a9699fcf`](https://github.com/nodejs/node/commit/12a9699fcf)] - **buffer**: fix needle length misestimation for UCS2 (Anna Henningsen) [#6511](https://github.com/nodejs/node/pull/6511)
* [[`292b1b733e`](https://github.com/nodejs/node/commit/292b1b733e)] - **build**: fix make tar-headers for Linux (Gibson Fahnestock) [#5978](https://github.com/nodejs/node/pull/5978)
* [[`918d33ad4b`](https://github.com/nodejs/node/commit/918d33ad4b)] - **build**: add script to create Android .mk files (Robert Chiras) [#5544](https://github.com/nodejs/node/pull/5544)
* [[`4ad71847bc`](https://github.com/nodejs/node/commit/4ad71847bc)] - **build**: add suport for x86 architecture (Robert Chiras) [#5544](https://github.com/nodejs/node/pull/5544)
* [[`6ad85914b1`](https://github.com/nodejs/node/commit/6ad85914b1)] - **child_process**: add nullptr checks after allocs (Anna Henningsen) [#6256](https://github.com/nodejs/node/pull/6256)
* [[`823f726f66`](https://github.com/nodejs/node/commit/823f726f66)] - **contextify**: tie lifetimes of context & sandbox (Ali Ijaz Sheikh) [#5800](https://github.com/nodejs/node/pull/5800)
* [[`9ddb44ba61`](https://github.com/nodejs/node/commit/9ddb44ba61)] - **contextify**: cache sandbox and context in locals (Ali Ijaz Sheikh) [#5392](https://github.com/nodejs/node/pull/5392)
* [[`8ebdcd65b0`](https://github.com/nodejs/node/commit/8ebdcd65b0)] - **contextify**: replace deprecated SetWeak usage (Ali Ijaz Sheikh) [#5392](https://github.com/nodejs/node/pull/5392)
* [[`9e6d8170f7`](https://github.com/nodejs/node/commit/9e6d8170f7)] - **contextify**: cleanup weak ref for sandbox (Ali Ijaz Sheikh) [#5392](https://github.com/nodejs/node/pull/5392)
* [[`b6fc15347d`](https://github.com/nodejs/node/commit/b6fc15347d)] - **contextify**: cleanup weak ref for global proxy (Ali Ijaz Sheikh) [#5392](https://github.com/nodejs/node/pull/5392)
* [[`0dc875e2c7`](https://github.com/nodejs/node/commit/0dc875e2c7)] - **deps**: upgrade npm in LTS to 2.15.5 (Rebecca Turner)
* [[`3c50350f41`](https://github.com/nodejs/node/commit/3c50350f41)] - **deps**: fix null pointer checks in v8 (Michaël Zasso) [#6669](https://github.com/nodejs/node/pull/6669)
* [[`a40730b4b4`](https://github.com/nodejs/node/commit/a40730b4b4)] - **deps**: backport IsValid changes from 4e8736d in V8 (Michaël Zasso) [#6669](https://github.com/nodejs/node/pull/6669)
* [[`855604c53a`](https://github.com/nodejs/node/commit/855604c53a)] - **deps**: upgrade npm in LTS to 2.15.4 (Rebecca Turner) [#6663](https://github.com/nodejs/node/pull/6663)
* [[`433fb9a968`](https://github.com/nodejs/node/commit/433fb9a968)] - **deps**: cherry-pick 1383d00 from v8 upstream (Fedor Indutny) [#6179](https://github.com/nodejs/node/pull/6179)
* [[`d1fca27ef8`](https://github.com/nodejs/node/commit/d1fca27ef8)] - **deps**: backport 125ac66 from v8 upstream (Myles Borins) [#6086](https://github.com/nodejs/node/pull/6086)
* [[`df299019a0`](https://github.com/nodejs/node/commit/df299019a0)] - **deps**: upgrade npm in LTS to 2.15.2 (Kat Marchán)
* [[`50f02bd8d6`](https://github.com/nodejs/node/commit/50f02bd8d6)] - **doc**: update vm.runInDebugContext() example (Ben Noordhuis) [#6757](https://github.com/nodejs/node/pull/6757)
* [[`b872feade3`](https://github.com/nodejs/node/commit/b872feade3)] - **doc**: replace functions with arrow functions (abouthiroppy) [#6203](https://github.com/nodejs/node/pull/6203)
* [[`7160229be4`](https://github.com/nodejs/node/commit/7160229be4)] - **doc**: note that zlib.flush acts after pending writes (Anna Henningsen) [#6172](https://github.com/nodejs/node/pull/6172)
* [[`d069f2de8c`](https://github.com/nodejs/node/commit/d069f2de8c)] - **doc**: add full example for zlib.flush() (Anna Henningsen) [#6172](https://github.com/nodejs/node/pull/6172)
* [[`59814acfef`](https://github.com/nodejs/node/commit/59814acfef)] - **doc**: describe child.kill() pitfalls on linux (Robert Jefe Lindstaedt) [#2098](https://github.com/nodejs/node/issues/2098)
* [[`840c09492d`](https://github.com/nodejs/node/commit/840c09492d)] - **doc**: update openssl.org hash links (silverwind) [#6817](https://github.com/nodejs/node/pull/6817)
* [[`126fdc3171`](https://github.com/nodejs/node/commit/126fdc3171)] - **doc**: fix issues related to page scrolling (Roman Reiss)
* [[`29e25d8489`](https://github.com/nodejs/node/commit/29e25d8489)] - **doc**: add steps for running addons + npm tests (Myles Borins) [#6231](https://github.com/nodejs/node/pull/6231)
* [[`fcc6a347f7`](https://github.com/nodejs/node/commit/fcc6a347f7)] - **doc**: get rid of sneaky hard tabs in CHANGELOG (Myles Borins) [#6608](https://github.com/nodejs/node/pull/6608)
* [[`369569018e`](https://github.com/nodejs/node/commit/369569018e)] - **doc**: revert backported commits (Myles Borins) [#6530](https://github.com/nodejs/node/pull/6530)
* [[`4ec9ae8a1c`](https://github.com/nodejs/node/commit/4ec9ae8a1c)] - **doc**: explain differences in console.assert between node and browsers (James M Snell) [#6169](https://github.com/nodejs/node/pull/6169)
* [[`df5ce6fad4`](https://github.com/nodejs/node/commit/df5ce6fad4)] - **doc**: native module reloading is not supported (Bryan English) [#6168](https://github.com/nodejs/node/pull/6168)
* [[`30f354f72b`](https://github.com/nodejs/node/commit/30f354f72b)] - **doc**: clarify fs.watch() and inodes on linux, os x (Joran Dirk Greef) [#6099](https://github.com/nodejs/node/pull/6099)
* [[`29f821b73d`](https://github.com/nodejs/node/commit/29f821b73d)] - **doc**: clarifies http.serverResponse implementation (Allen Hernandez) [#6072](https://github.com/nodejs/node/pull/6072)
* [[`6d560094f4`](https://github.com/nodejs/node/commit/6d560094f4)] - **doc**: minor argument formatting in stream.markdown (James M Snell) [#6016](https://github.com/nodejs/node/pull/6016)
* [[`6a197ec617`](https://github.com/nodejs/node/commit/6a197ec617)] - **doc**: fix http response event, Agent#getName (Matthew Douglass) [#5993](https://github.com/nodejs/node/pull/5993)
* [[`620a261240`](https://github.com/nodejs/node/commit/620a261240)] - **http**: disallow sending obviously invalid status codes (Brian White) [#6291](https://github.com/nodejs/node/pull/6291)
* [[`9a8b53124d`](https://github.com/nodejs/node/commit/9a8b53124d)] - **http**: unref socket timer on parser execute (Fedor Indutny) [#6286](https://github.com/nodejs/node/pull/6286)
* [[`b28e44deb2`](https://github.com/nodejs/node/commit/b28e44deb2)] - **http**: Corrects IPv6 address in Host header (Mihai Potra) [#5314](https://github.com/nodejs/node/pull/5314)
* [[`2fac15ba94`](https://github.com/nodejs/node/commit/2fac15ba94)] - **src**: fix FindFirstCharacter argument alignment (Anna Henningsen) [#6511](https://github.com/nodejs/node/pull/6511)
* [[`2942cff069`](https://github.com/nodejs/node/commit/2942cff069)] - **src**: add missing 'inline' keywords (Ben Noordhuis) [#6056](https://github.com/nodejs/node/pull/6056)
* [[`e0eebf412e`](https://github.com/nodejs/node/commit/e0eebf412e)] - **src,tools**: remove null sentinel from source array (Ben Noordhuis) [#5418](https://github.com/nodejs/node/pull/5418)
* [[`8f18414cd5`](https://github.com/nodejs/node/commit/8f18414cd5)] - **src,tools**: drop nul byte from built-in source code (Ben Noordhuis) [#5418](https://github.com/nodejs/node/pull/5418)
* [[`d7a3ea457b`](https://github.com/nodejs/node/commit/d7a3ea457b)] - **src,tools**: allow utf-8 in built-in js source code (Ben Noordhuis) [#5418](https://github.com/nodejs/node/pull/5418)
* [[`51c0808b55`](https://github.com/nodejs/node/commit/51c0808b55)] - **stream**: Fix readableState.awaitDrain mechanism (Anna Henningsen) [#6023](https://github.com/nodejs/node/pull/6023)
* [[`49a5941d30`](https://github.com/nodejs/node/commit/49a5941d30)] - **test**: fix test-debug-port-cluster flakiness (Rich Trott) [#6769](https://github.com/nodejs/node/pull/6769)
* [[`f8144e4c4a`](https://github.com/nodejs/node/commit/f8144e4c4a)] - **test**: add logging for test-debug-port-cluster (Rich Trott) [#6769](https://github.com/nodejs/node/pull/6769)
* [[`773ea20d0e`](https://github.com/nodejs/node/commit/773ea20d0e)] - **test**: include component in tap output (Ben Noordhuis) [#6653](https://github.com/nodejs/node/pull/6653)
* [[`333369e1ff`](https://github.com/nodejs/node/commit/333369e1ff)] - **test**: increase the platform timeout for AIX (Michael Dawson) [#6342](https://github.com/nodejs/node/pull/6342)
* [[`06e5fafe84`](https://github.com/nodejs/node/commit/06e5fafe84)] - **test**: add tests for console.assert (Evan Lucas) [#6302](https://github.com/nodejs/node/pull/6302)
* [[`f60ba54811`](https://github.com/nodejs/node/commit/f60ba54811)] - **test**: add zlib close-after-error regression test (Anna Henningsen) [#6270](https://github.com/nodejs/node/pull/6270)
* [[`24ac16f4be`](https://github.com/nodejs/node/commit/24ac16f4be)] - **test**: fix flaky test-http-set-timeout-server (Santiago Gimeno) [#6248](https://github.com/nodejs/node/pull/6248)
* [[`5002a71357`](https://github.com/nodejs/node/commit/5002a71357)] - **test**: assert - fixed error messages to match the tests (surya panikkal) [#6241](https://github.com/nodejs/node/pull/6241)
* [[`0f9405dd33`](https://github.com/nodejs/node/commit/0f9405dd33)] - **test**: move more tests from sequential to parallel (Santiago Gimeno) [#6187](https://github.com/nodejs/node/pull/6187)
* [[`37cc249218`](https://github.com/nodejs/node/commit/37cc249218)] - **test**: fix test-net-settimeout flakiness (Santiago Gimeno) [#6166](https://github.com/nodejs/node/pull/6166)
* [[`69dcbb642f`](https://github.com/nodejs/node/commit/69dcbb642f)] - **test**: fix flaky test-child-process-fork-net (Rich Trott) [#6138](https://github.com/nodejs/node/pull/6138)
* [[`a97a6a9d69`](https://github.com/nodejs/node/commit/a97a6a9d69)] - **test**: fix issues for ESLint 2.7.0 (silverwind) [#6132](https://github.com/nodejs/node/pull/6132)
* [[`a865975909`](https://github.com/nodejs/node/commit/a865975909)] - **test**: fix flaky test-http-client-abort (Rich Trott) [#6124](https://github.com/nodejs/node/pull/6124)
* [[`25d4b5b1e9`](https://github.com/nodejs/node/commit/25d4b5b1e9)] - **test**: move some test from sequential to parallel (Santiago Gimeno) [#6087](https://github.com/nodejs/node/pull/6087)
* [[`28040ccf49`](https://github.com/nodejs/node/commit/28040ccf49)] - **test**: refactor test-file-write-stream3 (Rich Trott) [#6050](https://github.com/nodejs/node/pull/6050)
* [[`3a67a05ed4`](https://github.com/nodejs/node/commit/3a67a05ed4)] - **test**: enforce strict mode for test-domain-crypto (Rich Trott) [#6047](https://github.com/nodejs/node/pull/6047)
* [[`0b376cb3f9`](https://github.com/nodejs/node/commit/0b376cb3f9)] - **test**: fix pummel test failures (Rich Trott) [#6012](https://github.com/nodejs/node/pull/6012)
* [[`7b60b8f8e9`](https://github.com/nodejs/node/commit/7b60b8f8e9)] - **test**: fix flakiness of stringbytes-external (Ali Ijaz Sheikh) [#6705](https://github.com/nodejs/node/pull/6705)
* [[`cc4c5187ed`](https://github.com/nodejs/node/commit/cc4c5187ed)] - **test**: ensure test-npm-install uses correct node (Myles Borins) [#6658](https://github.com/nodejs/node/pull/6658)
* [[`3d4d5777bc`](https://github.com/nodejs/node/commit/3d4d5777bc)] - **test**: refactor http-end-throw-socket-handling (Santiago Gimeno) [#5676](https://github.com/nodejs/node/pull/5676)
* [[`c76f214b90`](https://github.com/nodejs/node/commit/c76f214b90)] - **test,tools**: enable linting for undefined vars (Rich Trott) [#6255](https://github.com/nodejs/node/pull/6255)
* [[`9222689215`](https://github.com/nodejs/node/commit/9222689215)] - **test,vm**: enable strict mode for vm tests (Rich Trott) [#6209](https://github.com/nodejs/node/pull/6209)
* [[`b8c9d6b64e`](https://github.com/nodejs/node/commit/b8c9d6b64e)] - **tools**: enable linting for v8_prof_processor.js (Rich Trott) [#6262](https://github.com/nodejs/node/pull/6262)
* [[`8fa202947d`](https://github.com/nodejs/node/commit/8fa202947d)] - **tools**: lint rule for assert.fail() (Rich Trott) [#6261](https://github.com/nodejs/node/pull/6261)
* [[`1aa6c5b7a9`](https://github.com/nodejs/node/commit/1aa6c5b7a9)] - **tools**: update ESLint to 2.7.0 (silverwind) [#6132](https://github.com/nodejs/node/pull/6132)
* [[`68c7de4372`](https://github.com/nodejs/node/commit/68c7de4372)] - **tools**: remove simplejson dependency (Sakthipriyan Vairamani) [#6101](https://github.com/nodejs/node/pull/6101)
* [[`4fb4ba98a8`](https://github.com/nodejs/node/commit/4fb4ba98a8)] - **tools**: remove disabling of already-disabled rule (Rich Trott) [#6013](https://github.com/nodejs/node/pull/6013)
* [[`4e6ea7f01a`](https://github.com/nodejs/node/commit/4e6ea7f01a)] - **tools**: remove obsolete npm test-legacy command (Kat Marchán)
* [[`4c73ab4302`](https://github.com/nodejs/node/commit/4c73ab4302)] - **tools,doc**: fix json for grouped optional params (firedfox) [#5977](https://github.com/nodejs/node/pull/5977)
* [[`c893cd33d1`](https://github.com/nodejs/node/commit/c893cd33d1)] - **tools,doc**: parse types in braces everywhere (Alexander Makarenko) [#5329](https://github.com/nodejs/node/pull/5329)
* [[`48684af55f`](https://github.com/nodejs/node/commit/48684af55f)] - **zlib**: fix use after null when calling .close (James Lal) [#5982](https://github.com/nodejs/node/pull/5982)

## 2016-05-05, Version 4.4.4 'Argon' (LTS), @thealphanerd

### Notable changes

* **deps**:
  * update openssl to 1.0.2h. (Shigeki Ohtsu) [#6551](https://github.com/nodejs/node/pull/6551)
    - Please see our [blog post](https://nodejs.org/en/blog/vulnerability/openssl-may-2016/) for more info on the security contents of this release.

### Commits

* [[`f46952e727`](https://github.com/nodejs/node/commit/f46952e727)] - **buffer**: safeguard against accidental kNoZeroFill (Сковорода Никита Андреевич) [nodejs/node-private#30](https://github.com/nodejs/node-private/pull/30)
* [[`4f1c82f995`](https://github.com/nodejs/node/commit/4f1c82f995)] - **streams**: support unlimited synchronous cork/uncork cycles (Matteo Collina) [#6164](https://github.com/nodejs/node/pull/6164)
* [[`1efd96c767`](https://github.com/nodejs/node/commit/1efd96c767)] - **deps**: update openssl asm and asm_obsolete files (Shigeki Ohtsu) [#6551](https://github.com/nodejs/node/pull/6551)
* [[`c450f4a293`](https://github.com/nodejs/node/commit/c450f4a293)] - **deps**: add -no_rand_screen to openssl s_client (Shigeki Ohtsu) [nodejs/io.js#1836](https://github.com/nodejs/io.js/pull/1836)
* [[`baedfbae6a`](https://github.com/nodejs/node/commit/baedfbae6a)] - **op