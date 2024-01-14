# Gimnazijska snov matematike

Gimnazijska snov matematike štirih let, rahlo dopolnjena pred vsakim testom, tako da
nisem naredil vsega naenkrat. Se bo dopolnjevala vsaj do mature in naj bi odgovorila
na vsa maturitetna vprašanja.

Vse sem naredil samo jaz, kar pomeni da nobena nova verzija ni preverjena in ni
nujno pravilna (čeprav se seveda trudim, da je napak čim manj). Prosim, da mi
odkrite napake sporočite (najbolje da kar odprete issue). Z veseljem sprejemam tudi pull requeste,
pa ni treba dodajat pdfja, ker so potem samo težave z mergi.

Narejena v LaTeX-u, `teorija.tex` je koda, `teorija.pdf` je glavni dokument za gledat.

Za popravke in dodatke se zahvaljujem Žigi Gosarju, Roku Kosu in @hunter1749.

## Prevajanje iz izvorne kode
Jaz prevajam kodo s pomočjo orodja `pdflatex`. Zaženete samo
```
pdflatex -synctex=1 -interaction=nonstopmode -shell-escape teorija.tex
```
počakate nekaj časa in ven pride pdf. Opcija `-shell-escape` dovoli LaTeXu zaganjanje programov iz
ukazne vrstice, in je lahko potencialno nevarna, vendar potrebna za avtomatsko risanje slik.

Jure Slak
