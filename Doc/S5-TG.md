# S5 TG


## TS1
Permanent:
 * 293 Slovenija (Slovenija)
 * 293112 ARON (Slovenija)


## TS2


* 2930 Tehnika (Slovenija)
* 2931 Ljubljana (Osrednja Slovenija)
* 2932 Maribor (Vzhodna Stajerska) 
* 2933 Celje (Zahodna štajerska)
* 2934 Kranj (Gorenjska)
* 2935 Nova Gorica (Primorska)
* 29351 ?
* 2936 Koper (Obala)
* 2937 Novo mesto (Dolenjska)
* 2938 Murska Sobota (Pomurje)
* 2939 Ptuj (Podravje)
* 29310 Postojna (Notranjska)
* 29311 Krsko, Sevnica (Posavje)
* 29312 Slovenj Gradec (Koroska)
* 29313 Trbovlje, Zagorje, Hrastnik (Zasavje)
* 29314 RPT link 1
* 29315 RPT link 2
* 293112 ARON (Slovenija)
* 9 Local/Reflektor (Lokalno)
* 91 World Wide [hose](https://hose.brandmeister.network/group/91/) - [LH](https://brandmeister.network/?page=lh&jsonquery=%7B%22condition%22%3A%22AND%22%2C%22rules%22%3A%5B%7B%22id%22%3A%22DestinationID%22%2C%22field%22%3A%22DestinationID%22%2C%22type%22%3A%22integer%22%2C%22input%22%3A%22text%22%2C%22operator%22%3A%22equal%22%2C%22value%22%3A%2291%22%7D%5D%7D)

**Tilen Cestnik** via Facebook: V S5 DMR omrežju se uporabljata dva time slota (dve časovni okni) in sicer :

TS1, na katerem statično deluje slovenska govorna skupina 293 in skupina 293112 - ARON ter
TS2, na katerem statično delujejo slovenske regijske skupine 2931, 2932, 2933 itd.

TG293 je vpisana na vseh slovenskih repetitorjih kot statična, kar pomeni, da, ko na repetitorju oddajamo na skupini 293 nas slišijo na vseh slovenskih DMR repetitorjih. Povezovanje po drugih državah je zato potrebno opraviti na TS2. Dolgi pogovori postaj v lokalu ne sodijo na TG293 ampak na TG9 na TS 2, če sta uporabnika na istem repetitorju ali na katero izmed regijskih skupin.

Na TS2 lahko z ukazom dinamično povežemo na poljubnem repetitorju katerokoli regijsko skupino. Npr. na mariborskem repetitorju S55DMX lahko povežemo skupino 2935 in se pogovarjamo s Primorci. Po določenem času neaktivnosti se povezava z dinamično skupino samodejno podre.

Ker se število repetitorjev v omrežju povečuje moramo vsi paziti na HAM SPIRIT. Novim uporabnikom omrežja svetujem, da si pred uporabo in oddajo v omrežju DMR preberejo pravila, kako sistem uporabljati in tudi nekaj časa poslušajo kako poteka promet.
