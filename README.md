﻿# Webová aplikace pro trénink anglické slovní zásoby v React Native
## O aplikace
- Jedná se o mobilní aplikaci pro trénování anglické slovní zásoby.
- Aplikace je navržena pro tvorbu ve frameworku React Native.
- Celá aplikace muže být generována z jednoho JSON souboru viz words.json

## Hlavní stránka
- Karty pro výběr procvičované lekce a nastavení obtížnosti slovíček
- Každá karta nabízí možnost začít trénování, možnost prohlédnout slovíčka která obsahuje a odkaz na stránku se sttistikami uživatele. 
- Karta je samostatným React komponentem.

![Hlavní stránka](./imgs/mainpage.jpg)

## Stránka se slovíčky
- vypíše všechna slovíčka vybraná pro procvičování.
- obsahuje tlačítka pro zahájení procvičování a návrat na hlavní stránku.

![Stránka se slovíčky](./imgs/words.jpg)

## Stránka procvičování
- uživateli je předvedeno anglické slovíčko a výběr možností českého překladu.
- uživatel se snaží vybrat správný překlad.
- po výběru se zobrazí pop-up okno informující uživatele o správnosti výsledku.
- po dokončení všech slov v lekci se zobrazí pop-up okno se stistikou uspěšnosti.

![Stránka procvičování](./imgs/training.jpg)
![Pop-up okno](./imgs/popup.jpg)

## Stránka se statistikami
- ukazuje udaje o uspěšnosti uživatele v dané lekci

![Stránka se statistikami](./imgs/stats2.jpg)

## Návrhy na rozšíření
- Rozšíření aplikaci o backend
- Vytvořit uživatelské učty, na kterých budou uloženy statistiky.
- Nahrazení nebo rozšíření JSON souboru databází.
