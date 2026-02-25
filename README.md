# -Vaja11-LCD2x16-STM32F0







ODGOVORI:
2.

b)   RS= PB11 , E= PB12

PB13= D4

PA11= D5

PC7= D6

PC6= D7


e)

Nova frekvenca je 24 MHz.

f)

Hitrost podatkov na vodilih je nastavljena na Low.


3.

h)

x (stolpci): min = 0, max = 15 (za 16-znakovni zaslon).

y (vrstice): min = 0, max = 1 (za 2-vrstični zaslon).

Funkcija itoa pretvori celo število v znakovni niz ki se zaključi z ničelnim znakom.

LCD zaslon ne zna neposredno prikazati številske vrednosti. Sprejme lahko le ASCII kode znakov. Zato moramo število 5 pretvoriti v znak '5', da ga lahko funkcija Puts pravilno pošlje na zaslon.

Tretji argument določa številski sistem  za pretvorbo (10 pomeni decimalni sistem).

