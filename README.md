# Vývoj a realizácia systému pre automatické balansovanie guličky na naklonenej podložke

## Cieľ práce

Cieľom bakalárskej práce je navrhnúť, realizovať a experimentálne overiť automatickú balančnú podložku určenú na vycentrovanie guličky v zvolenom cieľovom bode. Systém bude na základe snímania aktuálnej polohy guličky určovať regulačnú odchýlku od požadovanej polohy. PID regulátor na základe tejto odchýlky vypočíta potrebný sklon podložky v oboch osiach a prostredníctvom aktuatorov dosiahne riadený pohyb guličky smerom do cieľového bodu.

## Úlohy

1.	Analyzovať teoretické princípy riadenia polohy guličky na nakláňanej podložke, vrátane dynamiky pohybu guličky, spätnej väzby a PID regulácie.
2.	Navrhnúť mechanickú konštrukciu balančnej podložky umožňujúcej nakláňanie v dvoch osiach, vrátane výberu vhodných aktuatorov.
3.	Navrhnúť spôsob snímania polohy guličky a elektronickú časť systému vrátane riadiacej jednotky, napájania a ovládania aktuatorov.
4.	Navrhnúť elektronické zapojenie (mikroprocesor/platňa, ovládače motorov, napájanie, senzory) a vybrať vhodné komponenty.
5.	Navrhnúť riadiaci algoritmus na základe PID regulátora pre presun guličky do zvoleného cieľového bodu.
6.	Implementovať funkčný prototyp balančnej podložky vrátane softvérovej časti riadiaceho algoritmu.
7.	Experimentálne overiť funkčnosť systému, nastaviť parametre PID regulátora a vyhodnotiť dosiahnutú presnosť a stabilitu vycentrovania guličky.
8.	Zhodnotiť výsledky, identifikovať obmedzenia navrhnutého riešenia a navrhnúť možnosti jeho ďalšieho vylepšenia. 

## Očakávané výstupy

•	Dokumentácia obsahujúca teoretický rozbor problému, návrh mechaniky, elektroniky a riadenia.
•	Funkčný prototyp systému s možnosťou naklonenia platformy v oboch osiach a stabilizácie guličky.
•	Softvér (riešený regulátor) s možnosťou zmeny parametrov.
•	Experimentálne merania a analýza výkonnosti (napr. čas stabilizácie, maximálna rýchlosť guličky, rozsah naklonenia platformy).
•	Záverečná správa bakalárskej práce so zhrnutím, diskusiou a odporúčaniami.
