Good and Great Practices for Coders
===================================

> *Empowering practices for happy coders about Git, Unit tests, C++, Python, Java, Gradle, CMake, Agile, GNU/LInux installation, pandoc... &nbsp; Not the best or the greatest because any one can propose improvements :-)*

This documentation is maintained with faireness in mind and shared in [Public Domain](#public-domain-dedication).

View this Markdown file [in presentation format](http://olibre.github.io/GreatPractices/pres.html#/) (reveal.js).


Internal documentation
======================

* [GNU/Linux installation for coders](./install)
* [Git](./git)
* [Java/Groovy/Gradle/Ant](./java)
* [C++](./cpp)
    * [Rules](cpp/rules.md)
    * [Metrics](cpp/lint.md)
    * [C++ Core Guidelines](cpp/cpp_core_guidelines.md)
* [CMake](./cmake)
* [Empoworing team members](./team)
* [Great Unit Tests](./unit-test)
* [Logging](./log)
* [Diagrams within Markdown](./markdown)


External documentation
======================


Web
---

* Respect [internaut](https://en.wikipedia.org/wiki/Internaut) privacy => Drop all tracking, Disallow anyone to collect any data at all  https://marmelab.com/blog/2020/01/28/about-privacy.html


Security
--------

* [OWASP](https://en.wikipedia.org/wiki/OWASP) Cheat Sheet https://github.com/OWASP/CheatSheetSeries
* [Tools, resources and references to practice ethical hacking](https://github.com/sundowndev/hacker-roadmap)
* [The Hacker's Choice](https://github.com/hackerschoice) (IT Security Research Group) [Tips, Tricks & Hacks](https://github.com/hackerschoice/thc-tips-tricks-hacks-cheat-sheet)
* [hackerEnv](https://github.com/abdulr7mann/hackerEnv), automation tool that sweep IPs and scan ports, vulnerabilities and exploit them
* SpiderFoot as penetration test or to gather information about what your organisation might have exposed over the Internet https://github.com/smicallef/spiderfoot
* Spy GitHub users https://github.com/eth0izzle/shhgit


Programming languages
---------------------

|Features                            | Programming languages |
|----------------------------------- | --------------------- |
|Fast compilation                    | V, D, Go, Delphi|
|Simplicity & maintainability        | V, Go, [Nim](https://nim-lang.org/), Python, [Julia](https://en.wikipedia.org/wiki/Julia_(programming_language)), Jupyter, Elm, Kotlin, Dart, Elixir   |
|Great perf. and zero cost C interop | V, C, C++, D, Delphi, Erlang, Rust|
|Safety (immutability, no null, option types, free from data races) | V, Rust|
|Easy concurrency                    | V, Go|
|Easy cross compilation              | V, Go|
|Compile time code generation        | V, D |
|Small compiler with no dependency   | V    |
|No global state                     | V    |
|Hot code reloading                  | [V](https://vlang.io)    |

* Python Cheatsheet https://github.com/gto76/python-cheatsheet
* Python-based algorithms https://github.com/TheAlgorithms/Python
* Python debugger/profiler (program flow visualizations) useful for algo learning https://github.com/CCExtractor/vardbg ([Y combinator](https://news.ycombinator.com/item?id=22170206))
* Python coloured output https://github.com/willmcgugan/rich
* Rust intruduction (2020) https://www.softax.pl/blog/rust-lang-in-a-nutshell-1-introduction/ ([Y combinator](https://news.ycombinator.com/item?id=22176968))
* GoFiber = Go web framework easy to learn by Node-developsers https://github.com/gofiber/fiber
* GoFrame (not a good idea to be locked with some libraries if cannot use others)  https://github.com/gogf/gf
* GetFlutter = 1000 open-source pre-build widgets library to develop both Flutter mobile app and web app https://github.com/ionicfirebaseapp/getflutter
* Playwright est une lib Node pour tester automatiquement l'UI sur différents navigateurs Chromium (dont MS-Edge), WebKit et Firefox en mode Headless (pas besoin d'un serveur graphique) sur Linux, macOS et Win https://github.com/microsoft/playwrigh
* Ant Design https://pro.ant.design/

Les résultats du sondage JavaScript https://2019.stateofjs.com/overview/  
(belle représentation des technos sur deux axes connaissance et opinion positive/négative)

* TypeScript a le vent en poupe
* Angular est de moins en moins apprécié : énormément de réponses I've USED it before, and would NOT use it again
* React (et Vue) sont de plus en plus utilisés
* Aux côtés de React et Vue, un troisième arrive en force : https://svelte.dev/
* GraphQL est de plus en plus utilisé et apprécié (notamment, avec Apollo comme client)
* Par contre, plus Redux est utilisé, moins il est apprécié 


DevOps
------

* Pour progresser en DevOps (et pas seulement Ops) https://github.com/bregman-arie/devops-exercises
* Un outil très complet (en Java) pour builder les images docker, config K8S, tracking des issues… https://github.com/theonedev/onedev
* Permission Manager is an easy RBAC management for Kubernetes (create users, assign namespaces/permissions, and distribute Kubeconfig YAML files) https://github.com/sighupio/permission-manager


Artificial Intelligeance
------------------------

* Introduction to Deep Learning https://github.com/aamini/introtodeeplearning


Hardware
--------

* eBook-like open hardware project  https://github.com/joeycastillo/The-Open-Book



Health & Work efficiency
------------------------

* Long cold shower https://news.ycombinator.com/item?id=22167687 (Netherlands study 2016) 


Linux
-----

* Linux screen sharing https://news.ycombinator.com/item?id=22178011
* Awesome Linux software https://github.com/luong-komorebi/Awesome-Linux-Software


Other
-----

* [The Book of Secret Knowledge](https://github.com/trimstray/the-book-of-secret-knowledge/blob/master/README.md#anger-table-of-contents), various materials and tools, manuals, cheatsheets, blogs, hacks, one-liners, cli/web tools…
* Interactive kill https://github.com/sindresorhus/fkill-cli

Public Domain Dedication
========================
CC0 1.0 Universal
-----------------

[Creative Commons Zero] &emsp; *No Rights Reserved*  &emsp; ![(CC) ZERO] &nbsp; ![(0) PUBLIC DOMAIN]

[Creative Commons Zero]: https://creativecommons.org/publicdomain/zero/1.0/deed "CC0 summary for non-lawyers" 
[(CC) ZERO]:             https://licensebuttons.net/l/zero/1.0/80x15.png "Logo Creative Commons Zero (CC0) 1.0"
[(0) PUBLIC DOMAIN]:     https://licensebuttons.net/p/zero/1.0/80x15.png "Logo CC0 1.0 Public Domain"

To the extent possible under law, [olibre](mailto:olibre@Lmap.org) 
has waived all copyright and related or neighboring rights to [GreatPractices]. 
This work is published from France since 2015.
Refer to [CC0 Legal Code] or a copy in file [`COPYING`].

[CC0 Legal Code]: https://creativecommons.org/publicdomain/zero/1.0/legalcode "CC0 full legal text for lawyers"
[GreatPractices]: https://github.com/olibre/GreatPractices "GreatPractices project hosted on GitHub" 
[`COPYING`]:      ./COPYING
