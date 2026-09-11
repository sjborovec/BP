# Dekarbonizace v rafinérském průmyslu

**Decarbonisation in the oil refinery**

Bakalářská práce na [Českém vysokém učení technickém v Praze](https://www.cvut.cz/), Fakultě strojní, Ústavu procesní a zpracovatelské techniky.

| | |
| --- | --- |
| Autor | Štěpán Borovec |
| Vedoucí | doc. Ing. Radek Šulc, Ph.D. |
| Oponent | Ing. Vojtěch Bělohlav |
| Akademický rok | 2023/2024 |
| Studijní program | Teoretický základ strojního inženýrství |
| Jazyk | čeština |
| Klíčová slova | vodík, dekarbonizace, emise, rafinérie |

Oficiální verze v digitální knihovně ČVUT: [http://hdl.handle.net/10467/116848](http://hdl.handle.net/10467/116848)

## Abstrakt

Cílem této bakalářské práce je přispět k lepšímu pochopení potenciálu vodíku jako nosiče energie a jeho využití v rafinériích. Práce analyzuje aktuální projekty dekarbonizace rafinérií pomocí zeleného vodíku a navrhuje vlastní výpočet pro zlepšení udržitelnosti rafinérie.

První kapitola popisuje základní charakteristiky vodíku, jeho fyzikální a chemické vlastnosti a typy vodíku podle způsobu výroby. Následující kapitoly se věnují aplikacím vodíku v chemickém, metalurgickém a dopravním sektoru a procesům výroby vodíku v rafinériích. Závěrečná část se zaměřuje na aktuální dekarbonizační projekty a možnosti využití zeleného vodíku, včetně vlastní studie.

Praktická část odhaduje produkci CO₂ na kilogram vodíku z jednotky parciální oxidace těžkých topných olejů a naznačuje částečnou i úplnou náhradu šedého vodíku vodíkem z elektrolyzérů napájených lokální solární elektrárnou. Výpočet vychází z dat tuzemské rafinérie Orlen Unipetrol.

## Struktura repositáře

```
main.tex              vstupní soubor sazby
references.bib        bibliografie (BibLaTeX)
chapters/             kapitoly práce
  uvod.tex
  vodik.tex           Vodík, jeho vlastnosti a typy
  vyuziti.tex         Využití vodíku jako nosiče energie
  vyroba.tex          Výroba vodíku v rafinériích
  projekty.tex        Aktuální projekty částečné dekarbonizace rafinérií
  prakticka.tex       Analýza dekarbonizace výroby vodíku v rafinérii
  zaver.tex
preamble/             preambule, titulní strana, záhlaví
other/                anotační list, prohlášení, poděkování, seznam zkratek
figures/              obrázky a TikZ schémata
```

## Sazba

Práce je sázena v LaTeXu (`book`, A4, oboustranně). Bibliografii zpracovává Biber se stylem `iso-numeric`.

```sh
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

Případně `latexmk -pdf main.tex`. Kromě běžné TeX Live / MacTeX instalace jsou potřeba mimo jiné balíčky `biblatex-iso690`, `mhchem`, `pgfplots`, `tikz` a `pdfpages`. Oficiální zadání je v `other/zadani.pdf`.

## Licence

Vysokoškolská závěrečná práce je dílo chráněné autorským zákonem. Je možné pořizovat z něj na své náklady a pro svoji osobní potřebu výpisy, opisy a rozmnoženiny. Jeho využití musí být v souladu s autorským zákonem v platném znění.

A university thesis is a work protected by the Copyright Act of the Czech Republic. Extracts, copies and transcripts of the thesis are allowed for personal use only and at one's own expense. The use of the thesis should be in compliance with the Copyright Act.

© 2024 Štěpán Borovec. Práce podléhá zákonu č. 121/2000 Sb., o právu autorském (autorský zákon), ve znění pozdějších předpisů, včetně úpravy školních děl podle § 60.
