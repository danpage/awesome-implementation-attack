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

- E. Oswald, S. Mangard, and T. Popp: ["*Power Analysis Attacks: Revealing the Secrets of Smart Cards*"](https://link.springer.com/book/10.1007/978-0-387-38162-6)
- M. Joye and M. Tunstall: ["*Fault Analysis in Cryptography*"](https://link.springer.com/book/10.1007/978-3-642-29656-7)
- J. Breier and X. Hou: ["*Cryptography and Embedded Systems Security*"](https://link.springer.com/book/10.1007/978-3-031-62205-2)
- F. Farahmandi, M. Tehranipoor, and N.N. Anandakumar: ["*Hardware Security Training, Hands-on!*"](https://link.springer.com/book/10.1007/978-3-031-31034-8)
- C. Rebeiro, D. Mukhopadhyay, and S. Bhattacharya: ["*Timing Channels in Cryptography*"](https://link.springer.com/book/10.1007/978-3-319-12370-7)

#### Online, including, e.g., lecture notes etc.

- F.-X. Standaert: ["*Side-Channel Analysis and Leakage-Resistance*"](https://perso.uclouvain.be/fstandae/book.html)
- D. Page: ["*Cryptographic Engineering*"](https://www.phoo.org/book/ceng/index.html)

<!--- -------------------------------------------------------------------- --->

### Surveys

- S. Picek, G. Perin, L. Mariot, L. Wu, and L. Batina: ["*SoK: Deep Learning-based Physical Side-channel Analysis*"](https://dblp.org/rec/journals/csur/PicekPMWB23.html)
- L. Batina, L. Chmielewski, B. Haase, N. Samwel, and P. Schwabe: ["*SoK: SCA-secure ECC in software - mission impossible?*"](https://dblp.org/rec/journals/tches/BatinaCHSS23.html)
- I. Buhan, L. Batina, Y. Yarom, and P. Schaumont: ["*SoK: Design Tools for Side-Channel-Aware Implementations*"](https://dblp.org/rec/conf/asiaccs/BuhanBYS22.html)
- J. Szefer: ["*Survey of Microarchitectural Side and Covert Channels, Attacks, and Defenses*"](https://dblp.org/rec/journals/jhss/Szefer19.html)
- Q. Ge, Y. Yarom, D.A. Cock, and G. Heiser: ["*A survey of microarchitectural timing attacks and countermeasures on contemporary hardware*"](https://dblp.org/rec/journals/jce/GeYCH18.html)
- B. Yuce, P. Schaumont, and M. Witteman: ["*Fault Attacks on Secure Embedded Software: Threats, Design, and Evaluation*"](https://dblp.org/rec/journals/jhss/YuceSW18.html)
- M. Mayhew and R. Muresan: ["*An overview of hardware-level statistical power analysis attack countermeasures*"](https://dblp.org/rec/journals/jce/MayhewM17.html)
- D. Karaklajić, J.-M. Schmidt, and I. Verbauwhede: ["*Hardware Designer’s Guide to Fault Attacks*"](https://dblp.org/rec/journals/tvlsi/KaraklajicSV13.html)
- A. Barenghi, L. Breveglieri, I. Koren, and D. Naccache: ["*Fault Injection Attacks on Cryptographic Devices: Theory, Practice, and Countermeasures*"](https://dblp.org/rec/journals/pieee/BarenghiBKN12.html)

<!--- -------------------------------------------------------------------- --->

### Datasets

- [DPA contest](https://dpacontest.telecom-paris.fr)
- [ANSSI SCA Database (ASCAD)](https://github.com/ANSSI-FR/ASCAD)

<!--- -------------------------------------------------------------------- --->

### Hardware

- [SASEBO](https://www.risec.aist.go.jp/project/sasebo)
- [ChipWhisperer](https://www.newae.com/chipwhisperer) [[paper](https://dblp.org/rec/conf/cosade/OFlynnC14.html)]
- [ChipShouter](https://www.newae.com/chipshouter)
- [Flexible Opensource workBench fOr Side-channel analysis (FOBOS)](https://cryptography.gmu.edu/documentation/fobos3)
- [SCALE](https://github.com/danpage/scale-hw)

<!--- -------------------------------------------------------------------- --->

### Software

#### Frameworks/libraries for analysis

- [SCALib](https://github.com/simple-crypto/SCALib) [[paper](https://dblp.org/rec/journals/jossw/CassiersB23.html)]
- [Lascar](https://github.com/Ledger-Donjon/lascar)
- [Side-Channel Marvels](https://github.com/SideChannelMarvels)
- [Jlsca](https://github.com/Riscure/Jlsca)
- [Pysca](https://github.com/ikizhvatov/pysca)
- [Scared](https://gitlab.com/eshard/scared)

### Frameworks/libraries for attacks

- [Mastik](https://github.com/0xADE1A1DE/Mastik)

#### Frameworks/libraries with security-enhancing properties

- [Constant-Time Toolkit (CTTK)](https://github.com/pornin/CTTK)

#### Tools for leakage simulation (see [related](https://ileanabuhan.github.io/Tools) list)

- [ELMO](https://github.com/sca-research/ELMO) [[paper](https://dblp.org/rec/conf/uss/McCannOW17.html)]
- [GILES](https://github.com/sca-research/GILES)
- ABBY [[paper](https://dblp.org/rec/conf/asiaccs/BazanganiIBB24)]

#### Tools for efficiency- and/or security-enhancing translation, compilation, etc.

- [Jasmin](https://github.com/jasmin-lang/jasmin) [[paper](https://dblp.org/rec/conf/ccs/AlmeidaBBBGLOPS17.html)]
- [PoMMES](https://github.com/ChairImpSec/PoMMES) [[paper](https://dblp.org/rec/journals/tches/ZeitschnerM24.html)]
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
