---
title: Nejprve něco o jazyce Archimate
layout: page
nav_order: 2
date: 2020-04-09
parent: Poznáváme jazyk Archimate (česky)
---

# O jazyce Archimate

Obsah tohoto dokumentu


- TOC
{:toc}


## Co je vlastně Archimate?

## Jak se poprat s jazykem Archimate?

Archimate® jako každý jiný jazyk má svoje pravidla a postupy, které je nutné dodržovat, abychom mu dobře rozuměli. Můžeme ho z části považovat za jazyk komunikační (čili takový, kterým se mluví či vyjadřuje), ale také za jazyk programátorský, (tedy, kterým se dá exaktně znázornit hierarchie a vazba jedné věci na druhou). 

Má svoji sémantiku a svoje pravidla pro zapisování jednotlivých elementů a vazeb a určité podmínky pro to, co lze s jeho pomocí vyjádřit. Má ale také jasně definované grafické znázornění, tedy diagramy zpracované v jazyce archimate je schopen číst každý, kdo ví, co jednotlivý obdélník či obrázek znamená.

Pro architekty je nepochybně nutné znát tento jazyk velice podrobně a být schopni v tomto jazyce také zpracovávat jednotlivé modely architektury. Pro běžného uživatele ale úplně postačí, když dostane do rukou seznam všech elementů s jejich popisy a to, jak dané elementy vypadají. Tím se dokáže kdokoliv naučit číst diagramy zpracovávané v tomto architektonickém jazyce, aniž by nutně musel ovládat veškeré jeho záludnosti.

## Základy archimate 

V jazyce jsou tři důležité věci:

* Prvky (elementy): To jsou jednotlivé architektonické objekty
* Vazby: To jsou vazby mezi elementy
* Vrstvy: To jsou jakési filozofické části architektury

Kromě toho se můžete ještě v Archimate setkat také s pohledy, ty si představte jako jakési standardizované náhledy na určité kusy architektury, ale pro běžného čtenáře jsou vlastně nezajímavé, protože je vytváří architekt a architektonický nástroj.

### Elementy

Elementy jsou základní stavební prvky jazyka. Vyjádřené jsou zpravidla pomocí „krabiček“ s ikonkami. Ty nejčastěji popisují něco, co existuje, činnosti, které někdo nebo něco vykonává, motivaci nebo další témata.

Archimate rozlišuje elementy na Aktivní, Behaviorální a Pasivní, čímž se dost blíží větnému pojetí jazyka. Aktivní element se chová (behaviorálně) vůči pasivnímu elementu.

> Příklad: Já právě píšu učební text o Archimate. Já je aktivní element (aktér Já), píšu je vykonávaná činnost chování (behaviorální) a výsledek je učební texty pro Archimate, což je tedy prvek pasivní.

Obyčejný člověk v roli čtenáře a prostého uživatele obrázků v Archimate se ale tímhle členěním nemusí moc trápit.


### Vazby

Vazby vyjadřují vztahy mezi elementy a jsou zpravidla znázorněné pomocí různých čar se značkami na koncích.

### Pohledy / Viewpointy

S elementy a vazbami to ale nekončí, na rozdíl od jiných jazyků definuje Archimate i hlediska, kterým se ale i u nás nejčastěji říká anglickým viewpoint.

Viewpoint představuje perspektivu, ze které se na něco dívám a to, co vidím je pohled (view). Nebudeme se zatím příliš trápit teorií, tak si pro zjednodušení můžeme představit viewpoint jako šablonu, která nám říká, jak máme vybrané téma zachytit. Viewpointy jsou jedna z nejdůležitějších věcí v Archimatu, přesto je hodně lidí ignoruje. Částečně je to dané nepochopením, hlavním důvodem je ale absence podpory viewpointů v nejvíce rozšířených nástrojích Sparx Systems Enterprise Architect a MS Visio.

> Zdroj: https://www.modelovaci-jazyky.cz/archimate-obsah/

## Popis a význam jednotlivých vrstev

Architektura se dělí do vrstev a stejně i jazyk Archimate. Každá vrstva má svoji barvu a svůj daný set elementů, kterými se vyjadřují objekty na dané vrstvě. To samo pro pochopení Archimate pro laiky není tak podstatné. Podstatné ale je, aby rozuměli tomu, co znamená která vrstva a co v ní tedy přibližně najdou.

### Strategická vrstva architektury

Od strategie se vše odvíjí. Strategie je základ pro jakékoliv konání, včetně popisu a změn v architektuře. Pro strategii jsou důležité schopnosti a zdroje, nicméně samotná strategie je základem pro další vrstvy. Proto je také vždy na prvním místě.


### Byznysová vrstva architektury

V této vrstvě se popisuje vše, co děláme, protože vše, co činíme, je součástí našeho byznysu. Ať už se opravdu jedná o byznys jako obchod, nebo o naplnění našeho poslání, na této vrstvě musíme vyjádřit, co vlastně děláme, kdo to dělá, jak to dělá a s kým, či pro koho to dělá. Byznys je uváděn hned pod strategií, protože je to prostě náš byznys.


### Aplikační vrstva architektury

Na této vrstvě popisujeme aplikace, programy, data, výměnu dat, a vše co zajistí, že byznys budeme schopni s pomocí ICT opravdu dělat. A to včetně technických dat a databází a systémů, které pro nás zajišťují fungování onoho byznysu v praxi.

### Technologická vrstva architektury

Někdy označovaná i jako infrastrukturní. Jedná se o vrstvu všech technologických prostředků a zařízení, které potřebujeme k tomu, aby nám fungovaly aplikace a systémy a data, a tedy, abychom s technickou pomocí mohli dělat byznys a plnit naši strategii. Místy je dost problematické odlišovat aplikační a technologickou vrstvu a jednotlivé elementy (zejména softwarové) se často zaměňují.

### Motivační vrstva architektury

Motivační vrstva ukazuje to, co motivuje či donucuje ke změnám v byznysu a v architektuře. Tedy motivací může být nějaký požadavek, externí vliv, zvýšení poptávky či cíl zvýšení kvality, nebo nějaké nové omezení způsobené změnou legislativy apod. V motivační vrstvě najdeme také trochu nelogicky reprezentaci požadavků, včetně požadavků na byznys a aplikace a technologie.

### Implementační vrstva architektury

Na této vrstvě se řeší změna určitého stavu ze současného (as-is) do budoucího chtěného (to-be) a to, co se musí pro tuto změnu udělat. Tedy implementace nového byznysu, implementace nových aplikací či jejich změn apod. 

