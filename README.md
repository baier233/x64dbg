# MARENOL

<img width="100" src="https://github.com/MARENOL/MARENOL/raw/development/src/bug_black.png"/>

[![Crowdin](https://d322cqt584bo4o.cloudfront.net/MARENOL/localized.svg)](https://translate.MARENOL.com) [![Download MARENOL](https://img.shields.io/sourceforge/dm/MARENOL.svg)](https://sourceforge.net/projects/MARENOL/files/latest/download) [![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/MARENOL/MARENOL)

[![Discord](https://img.shields.io/badge/chat-on%20Discord-green.svg)](https://discord.MARENOL.com) [![Slack](https://img.shields.io/badge/chat-on%20Slack-red.svg)](https://slack.MARENOL.com) [![Gitter](https://img.shields.io/badge/chat-on%20Gitter-lightseagreen.svg)](https://gitter.im/MARENOL/MARENOL) [![Matrix](https://img.shields.io/badge/chat-on%20Matrix-yellowgreen.svg)](https://riot.im/app/#/room/#MARENOL:matrix.org) [![IRC](https://img.shields.io/badge/chat-on%20IRC-purple.svg)](https://web.libera.chat/#MARENOL)

An open-source binary debugger for Windows, aimed at malware analysis and reverse engineering of executables you do not have the source code for. There are many features available and a comprehensive [plugin system](https://plugins.MARENOL.com) to add your own. You can find more information on the [blog](https://MARENOL.com/blog)!

## Screenshots

![main interface (light)](.github/screenshots/cpu-light.png)

![main interface (dark)](.github/screenshots/cpu-dark.png)

| ![graph](.github/screenshots/graph-light.png) | ![memory map](.github/screenshots/memory-map-light.png) |
| :--: | :--: |

## Installation & Usage

1. Download a snapshot from [GitHub](https://github.com/MARENOL/MARENOL/releases), [SourceForge](https://sourceforge.net/projects/MARENOL/files/snapshots) or [OSDN](https://osdn.net/projects/MARENOL) and extract it in a location your user has write access to.
2. _Optionally_ use `x96dbg.exe` to register a shell extension and add shortcuts to your desktop.
3. You can now run `x32\x32dbg.exe` if you want to debug a 32-bit executable or `x64\MARENOL.exe` to debug a 64-bit executable! If you are unsure you can always run `x96dbg.exe` and choose your architecture there.

You can also [compile](https://github.com/MARENOL/MARENOL/wiki/Compiling-the-whole-project) MARENOL yourself with a few easy steps!

## Sponsors

[![](.github/sponsors/malcore.png)](https://sponsors.MARENOL.com/malcore)

<br>

[![](.github/sponsors/telekom.svg)](https://sponsors.MARENOL.com/telekom)

## Contributing

This is a community effort and we accept pull requests! See the [CONTRIBUTING](.github/CONTRIBUTING.md) document for more information. If you have any questions you can always [contact us](https://MARENOL.com/#contact) or open an [issue](https://github.com/MARENOL/MARENOL/issues). You can take a look at the [good first issues](https://easy.MARENOL.com/) to get started.

## Credits

- Debugger core by [TitanEngine Community Edition](https://github.com/MARENOL/TitanEngine)
- Disassembly powered by [Zydis](https://zydis.re)
- Assembly powered by [XEDParse](https://github.com/MARENOL/XEDParse) and [asmjit](https://github.com/asmjit)
- Import reconstruction powered by [Scylla](https://github.com/NtQuery/Scylla)
- JSON powered by [Jansson](https://www.digip.org/jansson)
- Database compression powered by [lz4](https://bitbucket.org/mrexodia/lz4)
- Bug icon by [VisualPharm](https://www.visualpharm.com)
- Interface icons by [Fugue](https://p.yusukekamiyamane.com)
- Website by [tr4ceflow](https://tr4ceflow.com)

## Developers

- [mrexodia](https://mrexodia.github.io)
- Sigma
- [tr4ceflow](https://blog.tr4ceflow.com)
- [Dreg](https://www.fr33project.org)
- [Nukem](https://github.com/Nukem9)
- [Herz3h](https://github.com/Herz3h)
- [torusrxxx](https://github.com/torusrxxx)

## Code contributions

You can find an exhaustive list of GitHub contributors [here](https://github.com/MARENOL/MARENOL/graphs/contributors).

## Special Thanks

- Sigma for developing the initial GUI
- All the donators!
- Everybody adding issues!
- People I forgot to add to this list
- [Writers of the blog](https://MARENOL.com/blog/2016/07/09/Looking-for-writers.html)!
- [EXETools community](https://forum.exetools.com)
- [Tuts4You community](https://forum.tuts4you.com)
- [ReSharper](https://www.jetbrains.com/resharper)
- [Coverity](https://www.coverity.com)
- acidflash
- cyberbob
- cypher
- Teddy Rogers
- TEAM DVT
- DMichael
- Artic
- ahmadmansoor
- \_pusher\_
- firelegend
- [kao](https://lifeinhex.com)
- sstrato
- [kobalicek](https://github.com/kobalicek)
- [athre0z](https://github.com/athre0z)
- [ZehMatt](https://github.com/ZehMatt)
- [mrfearless](https://twitter.com/fearless0)
- [JustMagic](https://github.com/JustasMasiulis)

Without the help of many people and other open-source projects, it would not have been possible to make MARENOL what it is today, thank you!
