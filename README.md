# Awesome implementation attack resources [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

<!--- ==================================================================== --->

*This is
a curated list of awesome resources related to the topic of (cryptographic) implementation attacks:
not that resource is loosely defined, but the aim is **not** to simply list
every related research paper (since there are too many).
The principle of such attacks is a focus on concrete implementation versus 
abstract specification of a cryptographic construction.  Concrete instances 
include
side-channel 
and
fault injection 
attacks, where the attacker can
passively observe
or
 actively influence
behaviour by a target device respectively; a rich classification of related
concepts and techniques is possible, including, for example the potential
for both
local  (e.g., contact-based)
or 
remote (e.g., contact-less)
attack instances.*

<!--- ==================================================================== --->

## Table of Contents (ToC)

- [Events](#events)
- [Books](#books)
- [Datasets](#datasets)
- [Surveys](#surveys)
- [Hardware](#hardware)
- [Software](#software)
- [Exercises](#exercises)

<!--- ==================================================================== --->

## Content

<!--- -------------------------------------------------------------------- --->

### Events

- [Cryptographic Hardware and Embedded Systems (CHES)](https://ches.iacr.org)
- [CASCADE](https://cascade-conference.org), i.e., [Constructive Side-Channel Analysis and Secure Design (COSADE)](https://www.cosade.org) plus [CARDIS](https://cardis.org)
- [Fault Diagnosis and Tolerance in Cryptography (FDTC)](https://www.fdtc-workshop.eu)

<!--- -------------------------------------------------------------------- --->

### Books

#### Hard-copy

- [Power Analysis Attacks: Revealing the Secrets of Smart Cards](https://link.springer.com/book/10.1007/978-0-387-38162-6)
- [Fault Analysis in Cryptography](https://link.springer.com/book/10.1007/978-3-642-29656-7)
- [Cryptography and Embedded Systems Security](https://link.springer.com/book/10.1007/978-3-031-62205-2)
- [Hardware Security Training, Hands-on!](https://link.springer.com/book/10.1007/978-3-031-31034-8)
- [Timing Channels in Cryptography](https://link.springer.com/book/10.1007/978-3-319-12370-7)

#### Online, including, e.g., lecture notes etc.

- [Side-Channel Analysis and Leakage-Resistance](https://perso.uclouvain.be/fstandae/book.html)
- [Cryptographic Engineering](https://www.phoo.org/book/ceng/index.html)

<!--- -------------------------------------------------------------------- --->

### Surveys

- 

<!--- -------------------------------------------------------------------- --->

### Datasets

- [DPA contest](https://dpacontest.telecom-paris.fr)
- [ASCAD](https://github.com/ANSSI-FR/ASCAD)

<!--- -------------------------------------------------------------------- --->

### Hardware

- [SASEBO](https://www.risec.aist.go.jp/project/sasebo)
- [ChipWhisperer](https://www.newae.com/chipwhisperer) [[paper](https://dblp.org/rec/conf/cosade/OFlynnC14.html)]
- [ChipShouter](https://www.newae.com/chipshouter)
- [FOBOS](https://cryptography.gmu.edu/documentation/fobos3)
- [SCALE](https://github.com/danpage/scale-hw)

<!--- -------------------------------------------------------------------- --->

### Software

#### Libraries for analysis

- [SCALib](https://github.com/simple-crypto/SCALib) [[paper](https://dblp.org/rec/journals/jossw/CassiersB23.html)]
- [Lascar](https://github.com/Ledger-Donjon/lascar)
- [Side-Channel Marvels](https://github.com/SideChannelMarvels)
- [Jlsca](https://github.com/Riscure/Jlsca)
- [Pysca](https://github.com/ikizhvatov/pysca)
- [Scared](https://gitlab.com/eshard/scared)

#### Simulation tools

- [ELMO](https://github.com/sca-research/ELMO) [[paper](https://dblp.org/rec/conf/uss/McCannOW17.html)]
- [GILES](https://github.com/sca-research/GILES)
- [ROSITA](https://github.com/0xADE1A1DE/Rosita) [[paper](https://dblp.org/rec/conf/ndss/SheltonSB00Y21.html)]
- [ROSITA++](https://github.com/0xADE1A1DE/Rositaplusplus) [[paper](https://dblp.org/rec/conf/ccs/SheltonCS0BY21.html)]

<!--- -------------------------------------------------------------------- --->

### Exercises

- [SCALE](https://github.com/danpage/scale-sw)

<!--- ==================================================================== --->

## Contributing

Contributions and/or corrections are welcome: familiarise yourself with 
the style and format used (given no strict guidelines for either exist), 
then submit a pull request which captures your update.

<!--- ==================================================================== --->

## Related

There is an awesome meta-list (i.e., an awesome list of awesome lists)
available, e.g., at 
[`sindresorhus/awesome`](https://github.com/sindresorhus/awesome);
there's also some similar (or at least related) lists, such as
[`phonchi/awesome-side-channel-attack`](https://github.com/phonchi/awesome-side-channel-attack).

<!--- ==================================================================== --->

## License 

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0)

<!--- ==================================================================== --->
