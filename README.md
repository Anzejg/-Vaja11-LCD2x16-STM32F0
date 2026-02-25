# -Vaja11-LCD2x16-STM32F0

Slikovni izrezek pinout:
<img width="694" height="551" alt="image" src="https://github.com/user-attachments/assets/ccb1962d-05b5-49b3-854a-451b0d5ea647" />

fotografija vezave
![Image](https://github.com/user-attachments/assets/4a078e49-c313-4e10-82ac-5e3ccedaee73)





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

KOMENTAR:LCD deluje in prikazuje pravilno.Učitelj bi nama moral pri 3.g nalogi dati znak ampak ker ga žal ni bilo sva uporabila znak pravokotnika kot je v navodilih, če bi želela uporabiti drug znak bi samo del kode iz 3.g naloge x se drugače razporedila oziroma jih postavila v obliki znaka ki bi nama ga učitelj dal.
