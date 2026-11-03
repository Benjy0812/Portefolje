# Norsk Bokmål word lists

These are cspell word lists, not Hunspell dictionaries. cspell reads them via
`cspell.config.js`; nothing else in the project touches this directory.

- `nb_NO.txt` — 708,615 Bokmål words, one per line, UTF-8, sorted upstream

Source: `LibreOffice/dictionaries`, `no/` (`master` branch), converted from the
Hunspell `nb_NO.dic` by dropping the entry-count first line.
Upstream: https://github.com/LibreOffice/dictionaries/tree/master/no

Word list is pre-expanded: common joined words (sammensatte ord) such as
`værvarsel`, `værmelding`, `trafikkork` are listed explicitly.

License: GNU GPL v2 (see `no/COPYING` upstream, package `dict-no` v3.0,
maintainer Lars Bungum, origin spell-norwegian project). `nb_NO.txt` is
GPL-2.0, separate from the project's MIT code.
