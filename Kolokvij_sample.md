# Statistika – Kolokvij 1 (vježba)

## Varijante 1c, 1d i 1e – detaljna rješenja

Materijal obuhvaća:
- Opisnu statistiku (aritmetička sredina, mod, medijan, percentili i varijanca)
- Tablice frekvencija i relativnih frekvencija
- Princip umnoška
- Nezavisnost događaja
- Potpunu vjerojatnost i Bayesov teorem
- Osnovna svojstva vjerojatnosti

Svaka varijanta sadrži 6 zadataka po 2 boda. Rješenja uključuju formule, postupke računanja i objašnjenja.

---

# Kolokvij 1c

## Zadatak 1 – Opisna statistika

**Zadani su podaci:**

`2, 5, 4, -2, 6, 4, 1, 0, -3, 9`

Potrebno je izračunati aritmetičku sredinu, mod, medijan i 30%-tni percentil.

### 1. Aritmetička sredina

Koristimo formulu:

$$
\bar{x}=\frac{\sum_{i=1}^{n}x_i}{n}
$$

Zbrojimo sve podatke i podijelimo ih s njihovim ukupnim brojem:

$$
\bar{x}=\frac{2+5+4-2+6+4+1+0-3+9}{10}
$$

$$
\bar{x}=\frac{26}{10}=\boxed{2,6}
$$

### 2. Mod

Mod je vrijednost koja se u skupu podataka pojavljuje najviše puta.

Broj 4 pojavljuje se dva puta, dok se svi ostali brojevi pojavljuju samo jednom.

$$
\boxed{Mo=4}
$$

### 3. Medijan

Najprije sortiramo podatke uzlazno:

$$
-3,-2,0,1,2,4,4,5,6,9
$$

Imamo 10 elemenata, odnosno paran broj elemenata.

Kod parnog broja elemenata medijan je aritmetička sredina dvaju središnjih elemenata:

$$
Me=\frac{x_5+x_6}{2}
$$

$$
Me=\frac{2+4}{2}=\boxed{3}
$$

-3,-2,0,1,2,4,4,5,6,9, 11

Medijan: 4


### 4. 30%-tni percentil

Koristimo pravilo:

$$
np=10\cdot0,30=3
$$

Budući da je rezultat cijeli broj, percentil računamo kao aritmetičku sredinu 3. i 4. elementa sortiranog niza:

$$
P_{30}=\frac{x_3+x_4}{2}
$$

$$
P_{30}=\frac{0+1}{2}=\boxed{0,5}
$$

**Konačni rezultati:**

- Aritmetička sredina: 2,6
- Mod: 4
- Medijan: 3
- 30%-tni percentil: 0,5

---

## Zadatak 2 – Tablice frekvencija

**Zadani su podaci:**

Vrabac, golub, vrabac, sjenica, golub, vrabac, kos, golub, vrabac, kos, golub, sjenica, vrabac, golub, golub.

Ukupan broj opažanja:

$$
n=15
$$

### 1. Apsolutna frekvencija

Apsolutna frekvencija predstavlja broj pojavljivanja pojedine vrijednosti u skupu podataka.

Prebrojavanjem dobivamo:

- Vrabac: 5
- Golub: 6
- Sjenica: 2
- Kos: 2

### 2. Relativna frekvencija

Relativna frekvencija predstavlja udio pojedine vrijednosti u ukupnom broju opažanja.

Formula:

$$
f_i=\frac{n_i}{n}
$$

Primjer za vrapca:

$$
f_{\text{vrabac}}=\frac{5}{15}=0,3333
$$

Na isti način računamo ostale relativne frekvencije.

| Vrsta ptice | Frekvencija | Relativna frekvencija |
|---|---:|---:|
| Vrabac | 5 | 0,3333 |
| Golub | 6 | 0,4000 |
| Sjenica | 2 | 0,1333 |
| Kos | 2 | 0,1333 |
| **Ukupno** | **15** | **1,0000** |

Provjera:

$$
\sum f_i=1
$$

Zbroj relativnih frekvencija mora biti jednak 1, odnosno 100%.

---

## Zadatak 3 – Princip umnoška (faktorijel)

Biramo odjevnu kombinaciju koja uključuje:

- 4 majice
- 5 hlača
- 3 jakne

Za svaku od 4 majice možemo odabrati bilo koje od 5 hlača. Za svaku takvu kombinaciju možemo odabrati jednu od 3 jakne.

Prema principu umnoška množimo broj mogućnosti:

$$
N=4\cdot5\cdot3
$$

$$
\boxed{N=60}
$$

Moguće je složiti ukupno **60 različitih kombinacija**.

---

## Zadatak 4 – Nezavisnost događaja

Bacamo simetričnu kockicu.

Prostor elementarnih događaja:

$$
\Omega=\{1,2,3,4,5,6\}
$$

Definirani su događaji:

- A: pao je paran broj
- B: pao je broj djeljiv s 3
- C: pao je broj manji ili jednak 2

Zapisujemo ih kao skupove:

$$
A=\{2,4,6\}
$$

$$
B=\{3,6\}
$$

$$
C=\{1,2\}
$$

### 1. Jesu li A i B nezavisni?

Dva događaja su nezavisna ako vrijedi:

$$
P(A\cap B)=P(A)\cdot P(B)
$$

Izračunajmo pojedinačne vjerojatnosti.

Budući da je kockica simetrična:

$$
P(A)=\frac{3}{6}=\frac{1}{2}
$$

$$
P(B)=\frac{2}{6}=\frac{1}{3}
$$

Presjek A i B predstavlja ishode koji pripadaju objema skupinama:

$$
A\cap B=\{6\}
$$

Stoga:

$$
P(A\cap B)=\frac{1}{6}
$$

Provjeravamo uvjet nezavisnosti:

$$
P(A)\cdot P(B)=\frac{1}{2}\cdot\frac{1}{3}
$$

$$
P(A)\cdot P(B)=\frac{1}{6}
$$

Dobivamo:

$$
P(A\cap B)=P(A)\cdot P(B)
$$

**Zaključak: A i B su nezavisni događaji.**

### 2. Jesu li A, B i C međusobno nezavisni?

Za međusobnu nezavisnost triju događaja potrebno je provjeriti nezavisnost svakog para i uvjet za sva tri događaja zajedno.

Dovoljno je pronaći jedan par koji nije nezavisan da zaključimo kako događaji nisu međusobno nezavisni.

Provjerimo B i C:

$$
B\cap C=\varnothing
$$

Nemaju zajedničkih ishoda jer B sadrži 3 i 6, a C sadrži 1 i 2.

Zato:

$$
P(B\cap C)=0
$$

S druge strane:

$$
P(B)\cdot P(C)=\frac{1}{3}\cdot\frac{2}{6}
$$

$$
P(B)\cdot P(C)=\frac{1}{9}
$$

Budući da:

$$
0\neq\frac{1}{9}
$$

događaji B i C nisu nezavisni.

**Zaključak: A, B i C nisu međusobno nezavisni.**

---

## Zadatak 5 – Potpuna vjerojatnost i Bayesov teorem

Imamo dvije neprozirne vrećice:

| Vrećica | Plave kuglice | Crvene kuglice |
|---|---:|---:|
| 1 | 6 | 4 |
| 2 | 3 | 7 |

Nesimetričan novčić određuje koju vrećicu biramo:

$$
P(H_1)=0,6
$$

$$
P(H_2)=0,4
$$

Tražimo:

1. Vjerojatnost izvlačenja crvene kuglice.
2. Vjerojatnost da je kuglica iz druge vrećice ako znamo da je crvena.

### 1. Potpuna vjerojatnost

Definiramo događaj A: izvučena je crvena kuglica.

Najprije računamo vjerojatnost izvlačenja crvene kuglice iz pojedine vrećice:

$$
P(A|H_1)=\frac{4}{10}=0,4
$$

$$
P(A|H_2)=\frac{7}{10}=0,7
$$

Koristimo formulu potpune vjerojatnosti:

$$
P(A)=P(H_1)P(A|H_1)+P(H_2)P(A|H_2)
$$

Uvrštavamo:

$$
P(A)=0,6\cdot0,4+0,4\cdot0,7
$$

$$
P(A)=0,24+0,28
$$

$$
\boxed{P(A)=0,52}
$$

Vjerojatnost izvlačenja crvene kuglice iznosi 52%.

### 2. Bayesov teorem

Sada znamo da je izvučena kuglica crvena. Tražimo vjerojatnost da dolazi iz druge vrećice.

Koristimo Bayesovu formulu:

$$
P(H_2|A)=\frac{P(H_2)\cdot P(A|H_2)}{P(A)}
$$

Uvrštavamo:

$$
P(H_2|A)=\frac{0,4\cdot0,7}{0,52}
$$

$$
P(H_2|A)=\frac{0,28}{0,52}
$$

$$
\boxed{P(H_2|A)\approx0,5385}
$$

**Zaključak:** Ako znamo da je kuglica crvena, vjerojatnost da dolazi iz druge vrećice iznosi približno 53,85%.

---

## Zadatak 6 – Osnovna svojstva vjerojatnosti

Zadan je prostor elementarnih događaja:

$$
\Omega=\{1,2,3,4,5,6\}
$$

Vjerojatnosti pojedinačnih ishoda:

$$
P(1)=P(2)=P(5)=P(6)=\frac{1}{10}
$$

$$
P(3)=P(4)=\frac{3}{10}
$$

Događaji:

$$
A=\{2,3,4,6\}
$$

$$
B=\{3,4,5\}
$$

Potrebno je izračunati:

- $P(A\cup B)$
- $P(A\setminus B)$
- $P(B^c)$

### 1. Unija događaja

Unija sadrži sve elemente koji se nalaze u A ili B (ili u oba).

$$
A\cup B=\{2,3,4,5,6\}
$$

Zbrajamo vjerojatnosti pripadajućih ishoda:

$$
P(A\cup B)=P(2)+P(3)+P(4)+P(5)+P(6)
$$

$$
=\frac{1}{10}+\frac{3}{10}+\frac{3}{10}+\frac{1}{10}+\frac{1}{10}
$$

$$
\boxed{P(A\cup B)=\frac{9}{10}}
$$

### 2. Razlika skupova

Razlika $A\setminus B$ predstavlja elemente koji se nalaze u A, ali ne i u B.

Iz skupova:

$$
A=\{2,3,4,6\}
$$

$$
B=\{3,4,5\}
$$

Izbacujemo elemente A koji se nalaze i u B:

$$
A\setminus B=\{2,6\}
$$

Računamo:

$$
P(A\setminus B)=P(2)+P(6)
$$

$$
=\frac{1}{10}+\frac{1}{10}
$$

$$
\boxed{P(A\setminus B)=\frac{1}{5}}
$$

### 3. Komplement događaja

Komplement $B^c$ sadrži sve ishode koji se ne nalaze u B.

$$
B^c=\{1,2,6\}
$$

Zbrajamo pripadajuće vjerojatnosti:

$$
P(B^c)=P(1)+P(2)+P(6)
$$

$$
=\frac{1}{10}+\frac{1}{10}+\frac{1}{10}
$$

$$
\boxed{P(B^c)=\frac{3}{10}}
$$

---

# Kolokvij 1d

## Zadatak 1 – Opisna statistika

**Zadani su podaci:**

`3, 0, 5, -4, 2, 5, -1, 1, 7, -2`

Potrebno je izračunati aritmetičku sredinu, mod, medijan i 80%-tni percentil.

### 1. Aritmetička sredina

$$
\bar{x}=\frac{3+0+5-4+2+5-1+1+7-2}{10}
$$

$$
\bar{x}=\frac{16}{10}=\boxed{1,6}
$$

### 2. Mod

Broj 5 pojavljuje se dva puta, dok se svi ostali brojevi pojavljuju samo jednom.

$$
\boxed{Mo=5}
$$

### 3. Medijan

Sortiramo podatke uzlazno:

$$
-4,-2,-1,0,1,2,3,5,5,7
$$

Imamo paran broj elemenata, pa računamo prosjek 5. i 6. elementa:

$$
Me=\frac{x_5+x_6}{2}
$$

$$
Me=\frac{1+2}{2}=\boxed{1,5}
$$

### 4. 80%-tni percentil

$$
np=10\cdot0,8=8
$$

Budući da je rezultat cijeli broj, uzimamo prosjek 8. i 9. elementa sortiranog niza:

$$
P_{80}=\frac{x_8+x_9}{2}
$$

$$
P_{80}=\frac{5+5}{2}=\boxed{5}
$$

**Konačni rezultati:**

- Aritmetička sredina: 1,6
- Mod: 5
- Medijan: 1,5
- 80%-tni percentil: 5

---

## Zadatak 2 – Varijanca i transformacija podataka

Zadani su nizovi:

$$
x=(-6,-4,-2,0,2,4,6)
$$

$$
y=(-11,-7,-3,1,5,9,13)
$$

Potrebno je usporediti njihove varijance.

### 1. Varijanca niza x

Najprije računamo aritmetičku sredinu:

$$
\bar{x}=\frac{-6-4-2+0+2+4+6}{7}=0
$$

Koristimo formulu za varijancu uzorka:

$$
Var(x)=\frac{\sum_{i=1}^{n}(x_i-\bar{x})^2}{n-1}
$$

Uvrštavamo podatke:

$$
Var(x)=\frac{(-6)^2+(-4)^2+(-2)^2+0^2+2^2+4^2+6^2}{6}
$$

$$
Var(x)=\frac{36+16+4+0+4+16+36}{6}
$$

$$
Var(x)=\frac{112}{6}
$$

$$
\boxed{Var(x)\approx18,667}
$$

### 2. Varijanca niza y

Primijetimo da vrijedi:

$$
y_i=2x_i+1
$$

Svaki element niza x pomnožen je s 2, a zatim mu je dodana 1.

Koristimo svojstvo varijance:

$$
Var(aX+b)=a^2Var(X)
$$

Dodavanje konstante ne mijenja varijancu, dok množenje s konstantom a množi varijancu s kvadratom te konstante.

U našem slučaju:

$$
a=2,\qquad b=1
$$

Stoga:

$$
Var(y)=2^2Var(x)
$$

$$
Var(y)=4\cdot18,667
$$

$$
\boxed{Var(y)\approx74,667}
$$

**Zaključak:** Varijance nisu jednake. Varijanca niza y četiri je puta veća od varijance niza x.

---

## Zadatak 3 – Princip umnoška (faktorijel)

Od Pule do Beča putujemo preko Rijeke i Ljubljane.

Broj mogućnosti za pojedine dionice:

- Pula – Rijeka: 3 ceste
- Rijeka – Ljubljana: 4 ceste
- Ljubljana – Beč: 6 cesta

Za svaku od 3 mogućnosti prve dionice postoje 4 mogućnosti druge dionice, a za svaku od njih 6 mogućnosti treće dionice.

Prema principu umnoška:

$$
N=3\cdot4\cdot6
$$

$$
\boxed{N=72}
$$

Postoje ukupno 72 različita načina putovanja.

---

## Zadatak 4 – Nezavisnost događaja

Imamo kutiju s kuglicama označenima brojevima od 1 do 12.

Prostor elementarnih događaja:

$$
\Omega=\{1,2,\ldots,12\}
$$

Definirani događaji:

- A: broj je paran
- B: broj je djeljiv s 3
- C: broj je manji ili jednak 2

Zapisujemo skupove:

$$
A=\{2,4,6,8,10,12\}
$$

$$
B=\{3,6,9,12\}
$$

$$
C=\{1,2\}
$$

### 1. Nezavisnost A i B

Događaji su nezavisni ako vrijedi:

$$
P(A\cap B)=P(A)\cdot P(B)
$$

Računamo:

$$
P(A)=\frac{6}{12}=\frac{1}{2}
$$

$$
P(B)=\frac{4}{12}=\frac{1}{3}
$$

Presjek događaja:

$$
A\cap B=\{6,12\}
$$

Stoga:

$$
P(A\cap B)=\frac{2}{12}=\frac{1}{6}
$$

Provjeravamo uvjet nezavisnosti:

$$
P(A)\cdot P(B)=\frac{1}{2}\cdot\frac{1}{3}
$$

$$
P(A)\cdot P(B)=\frac{1}{6}
$$

Uvjet je zadovoljen.

**A i B su nezavisni događaji.**

### 2. Nezavisnost A, B i C

Provjerimo događaje B i C:

$$
B\cap C=\varnothing
$$

Prema tome:

$$
P(B\cap C)=0
$$

Međutim:

$$
P(B)\cdot P(C)=\frac{4}{12}\cdot\frac{2}{12}
$$

$$
=\frac{1}{3}\cdot\frac{1}{6}
$$

$$
=\frac{1}{18}
$$

Budući da:

$$
0\neq\frac{1}{18}
$$

događaji B i C nisu nezavisni.

**Zaključak: A, B i C nisu međusobno nezavisni.**

---

## Zadatak 5 – Potpuna vjerojatnost i komplement događaja

U kutiji imamo:

- 5 bijelih kugli
- 5 crnih kugli

Broj izvlačenja ovisi o rezultatu bacanja simetrične kockice:

| Ishod kockice | Broj kugli koje izvlačimo | Vjerojatnost |
|---|---:|---:|
| 1 ili 2 | 1 | 1/3 |
| 3 ili 4 | 2 | 1/3 |
| 5 ili 6 | 3 | 1/3 |

Tražimo vjerojatnost da među izvučenim kuglama bude barem jedna bijela.

### 1. Koristimo komplement događaja

Umjesto da računamo vjerojatnost barem jedne bijele kugle, lakše je računati suprotan događaj:

$$
A^c=\text{sve izvučene kugle su crne}
$$

Vrijedi:

$$
P(A)=1-P(A^c)
$$

### 2. Računamo vjerojatnost da su sve kugle crne

Razlikujemo tri slučaja.

**Prvi slučaj: izvlačimo jednu kuglu.**

Od ukupno 10 kugli, njih 5 je crno.

$$
P(A^c|H_1)=\frac{5}{10}=\frac{1}{2}
$$

**Drugi slučaj: izvlačimo dvije kugle bez vraćanja.**

Prva kugla mora biti crna, a zatim i druga.

$$
P(A^c|H_2)=\frac{5}{10}\cdot\frac{4}{9}
$$

$$
=\frac{20}{90}=\frac{2}{9}
$$

Isti rezultat dobivamo pomoću kombinacija:

$$
P(A^c|H_2)=\frac{\binom{5}{2}}{\binom{10}{2}}
$$

$$
=\frac{10}{45}=\frac{2}{9}
$$

**Treći slučaj: izvlačimo tri kugle bez vraćanja.**

Sve tri moraju biti crne:

$$
P(A^c|H_3)=\frac{5}{10}\cdot\frac{4}{9}\cdot\frac{3}{8}
$$

$$
=\frac{60}{720}=\frac{1}{12}
$$

### 3. Primjenjujemo potpunu vjerojatnost

Svaki od tri slučaja ima vjerojatnost 1/3.

$$
P(A^c)=
\frac{1}{3}\cdot\frac{1}{2}
+\frac{1}{3}\cdot\frac{2}{9}
+\frac{1}{3}\cdot\frac{1}{12}
$$

Izlučimo 1/3:

$$
P(A^c)=\frac{1}{3}
\left(\frac{1}{2}+\frac{2}{9}+\frac{1}{12}\right)
$$

Zajednički nazivnik je 36:

$$
P(A^c)=\frac{1}{3}
\left(\frac{18+8+3}{36}\right)
$$

$$
P(A^c)=\frac{1}{3}\cdot\frac{29}{36}
$$

$$
P(A^c)=\frac{29}{108}
$$

### 4. Izračunavamo traženu vjerojatnost

$$
P(A)=1-\frac{29}{108}
$$

$$
\boxed{P(A)=\frac{79}{108}\approx0,7315}
$$

**Zaključak:** Vjerojatnost da ćemo izvući barem jednu bijelu kuglu iznosi približno 73,15%.

---

## Zadatak 6 – Osnovna svojstva vjerojatnosti

Zadan je prostor:

$$
\Omega=\{1,2,3,4,5,6\}
$$

Vjerojatnosti pojedinačnih ishoda:

$$
P(1)=P(6)=\frac{1}{5}
$$

$$
P(2)=P(5)=\frac{1}{10}
$$

$$
P(3)=P(4)=\frac{1}{5}
$$

Događaji:

$$
A=\{1,2,3\}
$$

$$
B=\{3,4,5\}
$$

Potrebno je izračunati uniju, razliku i komplement događaja.

### 1. Unija događaja

Unija sadrži sve elemente koji pripadaju barem jednom od događaja.

$$
A\cup B=\{1,2,3,4,5\}
$$

Zbrajamo vjerojatnosti pripadajućih ishoda:

$$
P(A\cup B)=P(1)+P(2)+P(3)+P(4)+P(5)
$$

$$
=\frac{1}{5}+\frac{1}{10}+\frac{1}{5}+\frac{1}{5}+\frac{1}{10}
$$

$$
\boxed{P(A\cup B)=\frac{4}{5}}
$$

### 2. Razlika skupova

Razlika $A\setminus B$ predstavlja elemente koji se nalaze u A, ali ne i u B.

$$
A\setminus B=\{1,2\}
$$

Zbrajamo pripadajuće vjerojatnosti:

$$
P(A\setminus B)=P(1)+P(2)
$$

$$
=\frac{1}{5}+\frac{1}{10}
$$

$$
\boxed{P(A\setminus B)=\frac{3}{10}}
$$

### 3. Komplement događaja

Komplement B sadrži sve ishode koji se ne nalaze u B.

$$
B^c=\{1,2,6\}
$$

Zbrajamo pripadajuće vjerojatnosti:

$$
P(B^c)=P(1)+P(2)+P(6)
$$

$$
=\frac{1}{5}+\frac{1}{10}+\frac{1}{5}
$$

$$
\boxed{P(B^c)=\frac{1}{2}}
$$

---

# Kolokvij 1e

## Zadatak 1 – Opisna statistika

**Zadani su podaci:**

`6, 2, -1, 3, 2, 0, -5, 4, 2, 1`

Potrebno je izračunati aritmetičku sredinu, mod, medijan i 40%-tni percentil.

### 1. Aritmetička sredina

$$
\bar{x}=\frac{6+2-1+3+2+0-5+4+2+1}{10}
$$

$$
\bar{x}=\frac{14}{10}
$$

$$
\boxed{\bar{x}=1,4}
$$

### 2. Mod

Broj 2 pojavljuje se tri puta, više od svih ostalih vrijednosti.

$$
\boxed{Mo=2}
$$

### 3. Medijan

Sortiramo podatke uzlazno:

$$
-5,-1,0,1,2,2,2,3,4,6
$$

Imamo paran broj elemenata:

$$
Me=\frac{x_5+x_6}{2}
$$

$$
Me=\frac{2+2}{2}
$$

$$
\boxed{Me=2}
$$

### 4. 40%-tni percentil

$$
np=10\cdot0,4=4
$$

Budući da je rezultat cijeli broj, uzimamo prosjek 4. i 5. elementa sortiranog niza:

$$
P_{40}=\frac{x_4+x_5}{2}
$$

$$
P_{40}=\frac{1+2}{2}
$$

$$
\boxed{P_{40}=1,5}
$$

---

## Zadatak 2 – Tablice frekvencija

**Zadani su podaci:**

`3, 4, 5, 4, 3, 2, 4, 5, 4, 3, 5, 4, 3, 4, 2`

Ukupan broj opažanja:

$$
n=15
$$

### 1. Apsolutna frekvencija

Prebrojavanjem pojedinih ocjena dobivamo:

- Ocjena 2 pojavljuje se 2 puta.
- Ocjena 3 pojavljuje se 4 puta.
- Ocjena 4 pojavljuje se 6 puta.
- Ocjena 5 pojavljuje se 3 puta.

### 2. Relativna frekvencija

Koristimo formulu:

$$
f_i=\frac{n_i}{n}
$$

Primjer za ocjenu 4:

$$
f_4=\frac{6}{15}=0,4
$$

Ostale relativne frekvencije:

$$
f_2=\frac{2}{15}\approx0,1333
$$

$$
f_3=\frac{4}{15}\approx0,2667
$$

$$
f_5=\frac{3}{15}=0,2
$$

Tablica frekvencija:

| Ocjena | Frekvencija | Relativna frekvencija |
|---|---:|---:|
| 2 | 2 | 0,1333 |
| 3 | 4 | 0,2667 |
| 4 | 6 | 0,4000 |
| 5 | 3 | 0,2000 |
| **Ukupno** | **15** | **1,0000** |

Provjera:

$$
0,1333+0,2667+0,4+0,2=1
$$

---

## Zadatak 3 – Princip umnoška (faktorijel)

Pekarnica nudi sendviče kod kojih biramo:

- 4 vrste kruha
- 6 vrsta nadjeva
- 3 vrste umaka

Za svaku vrstu kruha možemo odabrati bilo koji od 6 nadjeva, a za svaku takvu kombinaciju bilo koji od 3 umaka.

Prema principu umnoška:

$$
N=4\cdot6\cdot3
$$

$$
\boxed{N=72}
$$

Moguće je složiti ukupno 72 različita sendviča.

---

## Zadatak 4 – Nezavisnost događaja

Na stolu se nalazi 8 karata označenih brojevima od 1 do 8.

Prostor elementarnih događaja:

$$
\Omega=\{1,2,3,4,5,6,7,8\}
$$

Definirani događaji:

- A: broj je neparan
- B: broj je manji ili jednak 4
- C: broj je veći od 6

Zapisujemo ih kao skupove:

$$
A=\{1,3,5,7\}
$$

$$
B=\{1,2,3,4\}
$$

$$
C=\{7,8\}
$$

### 1. Provjera nezavisnosti A i B

Dva događaja su nezavisna ako vrijedi:

$$
P(A\cap B)=P(A)\cdot P(B)
$$

Računamo pojedinačne vjerojatnosti:

$$
P(A)=\frac{4}{8}=\frac{1}{2}
$$

$$
P(B)=\frac{4}{8}=\frac{1}{2}
$$

Presjek događaja:

$$
A\cap B=\{1,3\}
$$

$$
P(A\cap B)=\frac{2}{8}=\frac{1}{4}
$$

Provjeravamo:

$$
P(A)\cdot P(B)=\frac{1}{2}\cdot\frac{1}{2}
$$

$$
P(A)\cdot P(B)=\frac{1}{4}
$$

Uvjet je zadovoljen.

**A i B su nezavisni događaji.**

### 2. Provjera međusobne nezavisnosti A, B i C

Provjerimo događaje B i C:

$$
B\cap C=\varnothing
$$

Zato:

$$
P(B\cap C)=0
$$

Međutim:

$$
P(B)\cdot P(C)=\frac{1}{2}\cdot\frac{2}{8}
$$

$$
=\frac{1}{2}\cdot\frac{1}{4}
$$

$$
=\frac{1}{8}
$$

Budući da:

$$
0\neq\frac{1}{8}
$$

događaji B i C nisu nezavisni.

**Zaključak: A, B i C nisu međusobno nezavisni.**

---

## Zadatak 5 – Potpuna vjerojatnost i Bayesov teorem

Tvornica ima tri stroja:

| Stroj | Udio proizvodnje | Udio neispravnih proizvoda |
|---|---:|---:|
| S1 | 50% | 1% |
| S2 | 30% | 2% |
| S3 | 20% | 5% |

Tražimo:

1. Vjerojatnost da je slučajno odabrani proizvod neispravan.
2. Vjerojatnost da je neispravan proizvod proizveo stroj S3.

### 1. Potpuna vjerojatnost

Definiramo događaje:

- $H_1$: proizvod je proizveo S1
- $H_2$: proizvod je proizveo S2
- $H_3$: proizvod je proizveo S3
- $D$: proizvod je neispravan

Iz tablice imamo:

$$
P(H_1)=0,5
$$

$$
P(H_2)=0,3
$$

$$
P(H_3)=0,2
$$

Vjerojatnosti neispravnosti pojedinih strojeva:

$$
P(D|H_1)=0,01
$$

$$
P(D|H_2)=0,02
$$

$$
P(D|H_3)=0,05
$$

Primjenjujemo formulu potpune vjerojatnosti:

$$
P(D)=P(H_1)P(D|H_1)+P(H_2)P(D|H_2)+P(H_3)P(D|H_3)
$$

Uvrštavamo:

$$
P(D)=0,5\cdot0,01+0,3\cdot0,02+0,2\cdot0,05
$$

$$
P(D)=0,005+0,006+0,010
$$

$$
\boxed{P(D)=0,021}
$$

Dakle, vjerojatnost neispravnog proizvoda iznosi 2,1%.

### 2. Bayesov teorem

Sada znamo da je proizvod neispravan. Želimo izračunati vjerojatnost da ga je proizveo stroj S3.

Koristimo Bayesovu formulu:

$$
P(H_3|D)=\frac{P(H_3)\cdot P(D|H_3)}{P(D)}
$$

Uvrštavamo:

$$
P(H_3|D)=\frac{0,2\cdot0,05}{0,021}
$$

$$
P(H_3|D)=\frac{0,010}{0,021}
$$

$$
\boxed{P(H_3|D)\approx0,4762}
$$

**Zaključak:** Ako znamo da je proizvod neispravan, postoji približno 47,62% vjerojatnosti da ga je proizveo stroj S3.

Zanimljivo je da S3 proizvodi samo 20% svih proizvoda, ali je odgovoran za gotovo polovicu neispravnih proizvoda.

---

## Zadatak 6 – Osnovna svojstva vjerojatnosti

Zadan je prostor:

$$
\Omega=\{1,2,3,4,5,6\}
$$

Vjerojatnosti pojedinačnih ishoda:

$$
P(1)=P(6)=\frac{1}{4}
$$

$$
P(2)=P(3)=P(4)=P(5)=\frac{1}{8}
$$

Događaji:

$$
A=\{1,2,3\}
$$

$$
B=\{3,4,6\}
$$

Potrebno je izračunati uniju, razliku i komplement događaja.

### 1. Unija događaja

Unija sadrži sve elemente koji pripadaju barem jednom od događaja.

$$
A\cup B=\{1,2,3,4,6\}
$$

Zbrajamo vjerojatnosti pripadajućih ishoda:

$$
P(A\cup B)=P(1)+P(2)+P(3)+P(4)+P(6)
$$

$$
=\frac{1}{4}+\frac{1}{8}+\frac{1}{8}+\frac{1}{8}+\frac{1}{4}
$$

Svodimo na zajednički nazivnik:

$$
=\frac{2}{8}+\frac{1}{8}+\frac{1}{8}+\frac{1}{8}+\frac{2}{8}
$$

$$
\boxed{P(A\cup B)=\frac{7}{8}}
$$

### 2. Razlika skupova

Razlika $A\setminus B$ predstavlja elemente koji se nalaze u A, ali ne i u B.

$$
A\setminus B=\{1,2\}
$$

Računamo:

$$
P(A\setminus B)=P(1)+P(2)
$$

$$
=\frac{1}{4}+\frac{1}{8}
$$

$$
\boxed{P(A\setminus B)=\frac{3}{8}}
$$

### 3. Komplement događaja

Komplement B sadrži sve ishode koji se ne nalaze u B.

$$
B^c=\{1,2,5\}
$$

Zbrajamo pripadajuće vjerojatnosti:

$$
P(B^c)=P(1)+P(2)+P(5)
$$

$$
=\frac{1}{4}+\frac{1}{8}+\frac{1}{8}
$$

$$
\boxed{P(B^c)=\frac{1}{2}}
$$

---

# Mini šalabahter – formule za kolokvij

## 1. Opisna statistika

**Aritmetička sredina:**

$$
\bar{x}=\frac{\sum_{i=1}^{n}x_i}{n}
$$

**Varijanca uzorka:**

$$
s^2=\frac{\sum_{i=1}^{n}(x_i-\bar{x})^2}{n-1}
$$

**Varijanca populacije:**

$$
\sigma^2=\frac{\sum_{i=1}^{n}(x_i-\mu)^2}{n}
$$

**Transformacija varijance:**

$$
Var(aX+b)=a^2Var(X)
$$

## 2. Frekvencije

**Relativna frekvencija:**

$$
f_i=\frac{n_i}{n}
$$

**Zbroj relativnih frekvencija:**

$$
\sum_i f_i=1
$$

## 3. Princip umnoška

$$
N=n_1\cdot n_2\cdot\ldots\cdot n_k
$$

## 4. Nezavisnost događaja

**Dva nezavisna događaja:**

$$
P(A\cap B)=P(A)\cdot P(B)
$$

**Tri međusobno nezavisna događaja:**

$$
P(A\cap B\cap C)=P(A)P(B)P(C)
$$

Uz to je potrebno provjeriti nezavisnost svakog para događaja.

## 5. Potpuna vjerojatnost

$$
P(A)=\sum_{i=1}^{n}P(H_i)P(A|H_i)
$$

## 6. Bayesov teorem

$$
P(H_k|A)=\frac{P(H_k)P(A|H_k)}{P(A)}
$$

## 7. Osnovna svojstva vjerojatnosti

**Unija:**

$$
P(A\cup B)=P(A)+P(B)-P(A\cap B)
$$

**Razlika:**

$$
P(A\setminus B)=P(A)-P(A\cap B)
$$

**Komplement:**

$$
P(A^c)=1-P(A)
$$

---

# Na što posebno paziti na kolokviju?

1. **Percentili:** U ovim zadacima koristi se pravilo da se kod cjelobrojnog rezultata $np$ uzima aritmetička sredina odgovarajućeg i sljedećeg elementa sortiranog niza. Za necjelobrojni rezultat treba primijeniti konvenciju definiranu na predavanjima.

2. **Varijanca:** Provjeri računa li se varijanca populacije (dijeljenje s $n$) ili uzorka (dijeljenje s $n-1$). U zadatku 1d korištena je uzoračka varijanca.

3. **Tri nezavisna događaja:** Nezavisnost A i B ne znači automatski da su A, B i C međusobno nezavisni. Potrebno je provjeriti sve parove i zajednički presjek triju događaja.

4. **Potpuna vjerojatnost:** Kada postoji više mogućih načina na koje događaj može nastati, računamo vjerojatnost svakog načina zasebno i zbrajamo rezultate.

5. **Bayesov teorem:** Koristi se kada znamo da se neki događaj dogodio i želimo izračunati vjerojatnost njegovog mogućeg uzroka.

6. **Komplement:** Kada je lakše izračunati suprotan događaj, koristimo $P(A)=1-P(A^c)$. Ovo je posebno korisno kod zadataka s izvlačenjem kuglica i uvjetom "barem jedan".

**Preporuka za učenje:** Pokušaj svaki tip zadatka riješiti samostalno, bez gledanja u postupak. Ako možeš prepoznati koju formulu treba primijeniti i pravilno postaviti račun, imaš jako dobru bazu za kolokvij.
