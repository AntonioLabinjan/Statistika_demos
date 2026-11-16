# Statistika – Kolokvij 1 (vježba)

Tri dodatne varijante, isti obuhvat kao 1a/1b: opisna statistika, tablice frekvencija, princip umnoška, nezavisnost događaja, potpuna vjerojatnost + Bayes, osnovna svojstva vjerojatnosti.
Svaka varijanta: 6 zadataka po 2 boda. Rješenja su na kraju svake varijante.

---

# Kolokvij 1c

**Zadatak 1 (2 boda).** Zadani su podaci 2, 5, 4, −2, 6, 4, 1, 0, −3, 9. Nađite aritmetičku sredinu, mod, medijan i 30%-tni percentil tih podataka.

**Zadatak 2 (2 boda).** Ornitolog u parku bilježi vrste ptica: vrabac, golub, vrabac, sjenica, golub, vrabac, kos, golub, vrabac, kos, golub, sjenica, vrabac, golub, golub. Organizirajte podatke u tablice frekvencija i relativnih frekvencija.

**Zadatak 3 (2 boda).** U trgovini birate odjevnu kombinaciju koja uključuje majicu, hlače i jaknu. Na izboru je 4 majice, 5 hlača i 3 jakne. Koliko je različitih kombinacija moguće?

**Zadatak 4 (2 boda).** Na slučajan način bacate simetričnu kockicu. Neka je A događaj "pao je paran broj", B događaj "pao je broj djeljiv s 3". Jesu li A i B nezavisni? Neka je C događaj "pao je broj manji ili jednak 2". Jesu li A, B i C nezavisni?

**Zadatak 5 (2 boda).** Dvije neprozirne vrećice: u prvoj je 6 plavih i 4 crvene kuglice, u drugoj 3 plave i 7 crvenih. Bacate nesimetričan novčić: glava (vjerojatnost 0,6) znači prvu vrećicu, pismo (vjerojatnost 0,4) drugu. Iz odabrane vrećice slučajno izvlačite jednu kuglicu. Kolika je vjerojatnost da je kuglica crvena? Ako je izvučena crvena kuglica, kolika je vjerojatnost da je iz druge vrećice?

**Zadatak 6 (2 boda).** Zadan je Ω = {1, 2, 3, 4, 5, 6} i vjerojatnost P takva da je P(1) = P(2) = P(5) = P(6) = 1/10 i P(3) = P(4) = 3/10. Uzmimo A = {2, 3, 4, 6} i B = {3, 4, 5}. Izračunajte P(A ∪ B), P(A \ B) i P(Bᶜ).

## Rješenja 1c

**Z1.** Srednja vrijednost: 26/10 = 2,6. Sortirano: −3, −2, 0, 1, 2, 4, 4, 5, 6, 9. Medijan = (2 + 4)/2 = 3. Za 30%-tni percentil: n = 10, p = 0,3, np = 3 (cijeli broj), pa je percentil aritmetička sredina 3. i 4. člana: (0 + 1)/2 = 0,5. Mod = 4.

**Z2.** Frekvencije: vrabac 5, golub 6, sjenica 2, kos 2 (ukupno 15).
Relativne frekvencije: vrabac 0,3333, golub 0,4, sjenica 0,1333, kos 0,1333.

**Z3.** Princip umnoška: 4 · 5 · 3 = 60.

**Z4.** A = {2, 4, 6}, B = {3, 6}, A ∩ B = {6}. P(A) = 1/2, P(B) = 1/3, P(A ∩ B) = 1/6 = 1/2 · 1/3, pa su A i B nezavisni. C = {1, 2}, B ∩ C = ∅, pa je P(B ∩ C) = 0 ≠ P(B)P(C) = 1/3 · 1/3 = 1/9. Dakle A, B i C **nisu** nezavisni.

**Z5.** H1 = "glava", H2 = "pismo", A = "crvena kuglica".
P(A) = 0,6 · 0,4 + 0,4 · 0,7 = 0,24 + 0,28 = 0,52.
Bayes: P(H2 | A) = 0,28 / 0,52 ≈ 0,538.

**Z6.** A ∪ B = {2, 3, 4, 5, 6}, P = 1/10 + 3/10 + 3/10 + 1/10 + 1/10 = 9/10. A \ B = {2, 6}, P = 2/10 = 1/5. Bᶜ = {1, 2, 6}, P = 3/10.

---

# Kolokvij 1d

**Zadatak 1 (2 boda).** Zadani su podaci 3, 0, 5, −4, 2, 5, −1, 1, 7, −2. Nađite aritmetičku sredinu, mod, medijan i 80%-tni percentil tih podataka.

**Zadatak 2 (2 boda).** Zadana su dva niza podataka x = (−6, −4, −2, 0, 2, 4, 6) i y = (−11, −7, −3, 1, 5, 9, 13). Usporedite njihove varijance. Jesu li iste? Obrazložite/izračunajte.

**Zadatak 3 (2 boda).** Od Pule do Rijeke može se doći preko 3 različite ceste, od Rijeke do Ljubljane preko 4, a od Ljubljane do Beča preko 6 različitih cesta. Na koliko se različitih načina može doći od Pule do Beča (preko Rijeke i Ljubljane)?

**Zadatak 4 (2 boda).** U kutiji je 12 kuglica označenih brojevima od 1 do 12. Na slučajan način izvlačite jednu. Neka je A događaj "broj je paran", B događaj "broj je djeljiv s 3". Jesu li A i B nezavisni? Neka je C događaj "broj je manji ili jednak 2". Jesu li A, B i C nezavisni?

**Zadatak 5 (2 boda).** Bacate simetričnu kockicu. Ako padne 1 ili 2, iz kutije izvlačite jednu kuglu; ako padne 3 ili 4, izvlačite dvije kugle (bez vraćanja); ako padne 5 ili 6, izvlačite tri kugle (bez vraćanja). U kutiji je 5 bijelih i 5 crnih kugli. Kolika je vjerojatnost da će među izvučenim kuglama biti barem jedna bijela?

**Zadatak 6 (2 boda).** Zadan je Ω = {1, 2, 3, 4, 5, 6} i vjerojatnost P takva da je P(1) = P(6) = 1/5, P(2) = P(5) = 1/10 i P(3) = P(4) = 1/5. Uzmimo A = {1, 2, 3} i B = {3, 4, 5}. Izračunajte P(A ∪ B), P(A \ B) i P(Bᶜ).

## Rješenja 1d

**Z1.** Srednja vrijednost: 16/10 = 1,6. Sortirano: −4, −2, −1, 0, 1, 2, 3, 5, 5, 7. Medijan = (1 + 2)/2 = 1,5. 80%-tni percentil: np = 8 (cijeli broj), pa je to (5 + 5)/2 = 5. Mod = 5.

**Z2.** x̄ = 0, Σ(xᵢ − x̄)² = 36 + 16 + 4 + 0 + 4 + 16 + 36 = 112, Var(x) = 112/6 ≈ 18,667. Vrijedi yᵢ = 2xᵢ + 1, pa je Var(y) = 2² · Var(x) = 4 · 18,667 ≈ 74,667. Varijance **nisu** iste (pomak b ne utječe na varijancu, ali faktor a = 2 je množi s a² = 4).

**Z3.** 3 · 4 · 6 = 72.

**Z4.** A = {2, 4, 6, 8, 10, 12}, B = {3, 6, 9, 12}, A ∩ B = {6, 12}. P(A) = 1/2, P(B) = 1/3, P(A ∩ B) = 2/12 = 1/6 = P(A)P(B), pa su A i B nezavisni. C = {1, 2}, B ∩ C = ∅, pa je 0 ≠ P(B)P(C) = 1/3 · 1/6 = 1/18. Dakle A, B i C **nisu** nezavisni.

**Z5.** H1 = "1 ili 2", H2 = "3 ili 4", H3 = "5 ili 6", svaki vjerojatnosti 1/3. A = "barem jedna bijela", Aᶜ = "sve su crne".
P(Aᶜ | H1) = 5/10 = 1/2, P(Aᶜ | H2) = C(5,2)/C(10,2) = 10/45 = 2/9, P(Aᶜ | H3) = C(5,3)/C(10,3) = 10/120 = 1/12.
P(Aᶜ) = 1/3 · (1/2 + 2/9 + 1/12) = 1/3 · 29/36 = 29/108 ≈ 0,2685.
P(A) = 1 − 29/108 = 79/108 ≈ 0,7315.

**Z6.** A ∪ B = {1, 2, 3, 4, 5}, P = 1 − P(6) = 4/5. A \ B = {1, 2}, P = 1/5 + 1/10 = 3/10. Bᶜ = {1, 2, 6}, P = 1/5 + 1/10 + 1/5 = 1/2.

---

# Kolokvij 1e

**Zadatak 1 (2 boda).** Zadani su podaci 6, 2, −1, 3, 2, 0, −5, 4, 2, 1. Nađite aritmetičku sredinu, mod, medijan i 40%-tni percentil tih podataka.

**Zadatak 2 (2 boda).** Na ispitu su zabilježene ocjene: 3, 4, 5, 4, 3, 2, 4, 5, 4, 3, 5, 4, 3, 4, 2. Organizirajte podatke u tablice frekvencija i relativnih frekvencija.

**Zadatak 3 (2 boda).** Pekarnica nudi sendvič: birate jednu od 4 vrste kruha, jedan od 6 nadjeva i jedan od 3 umaka. Koliko je različitih sendviča moguće složiti?

**Zadatak 4 (2 boda).** Na stolu je 8 karata (okrenutih licem prema dolje) označenih brojevima od 1 do 8. Na slučajan način odabirete jednu. Neka je A događaj "broj je neparan", B događaj "broj je manji ili jednak 4". Jesu li A i B nezavisni? Neka je C događaj "broj je veći od 6". Jesu li A, B i C nezavisni?

**Zadatak 5 (2 boda).** Tvornica ima tri stroja: S1 proizvodi 50%, S2 30%, a S3 20% svih proizvoda. Udio neispravnih proizvoda je 1% kod S1, 2% kod S2 i 5% kod S3. Kolika je vjerojatnost da slučajno odabrani proizvod bude neispravan? Ako je neispravan, kolika je vjerojatnost da ga je proizveo stroj S3?

**Zadatak 6 (2 boda).** Zadan je Ω = {1, 2, 3, 4, 5, 6} i vjerojatnost P takva da je P(1) = P(6) = 1/4 i P(2) = P(3) = P(4) = P(5) = 1/8. Uzmimo A = {1, 2, 3} i B = {3, 4, 6}. Izračunajte P(A ∪ B), P(A \ B) i P(Bᶜ).

## Rješenja 1e

**Z1.** Srednja vrijednost: 14/10 = 1,4. Sortirano: −5, −1, 0, 1, 2, 2, 2, 3, 4, 6. Medijan = (2 + 2)/2 = 2. 40%-tni percentil: np = 4 (cijeli broj), pa je to (1 + 2)/2 = 1,5. Mod = 2.

**Z2.** Frekvencije: ocjena 2 → 2, ocjena 3 → 4, ocjena 4 → 6, ocjena 5 → 3 (ukupno 15).
Relativne frekvencije: 2 → 0,1333, 3 → 0,2667, 4 → 0,4, 5 → 0,2.

**Z3.** 4 · 6 · 3 = 72.

**Z4.** A = {1, 3, 5, 7}, B = {1, 2, 3, 4}, A ∩ B = {1, 3}. P(A) = 1/2, P(B) = 1/2, P(A ∩ B) = 2/8 = 1/4 = P(A)P(B), pa su A i B nezavisni. C = {7, 8}, B ∩ C = ∅, pa je 0 ≠ P(B)P(C) = 1/2 · 1/4 = 1/8. Dakle A, B i C **nisu** nezavisni.

**Z5.** H1, H2, H3 = "proizvod je od S1, S2, S3" (potpun sustav), D = "neispravan".
P(D) = 0,5 · 0,01 + 0,3 · 0,02 + 0,2 · 0,05 = 0,005 + 0,006 + 0,010 = 0,021.
Bayes: P(H3 | D) = 0,010 / 0,021 ≈ 0,476.

**Z6.** A ∪ B = {1, 2, 3, 4, 6}, P = 1 − P(5) = 7/8. A \ B = {1, 2}, P = 1/4 + 1/8 = 3/8. Bᶜ = {1, 2, 5}, P = 1/4 + 1/8 + 1/8 = 1/2.


General rules by GPT:
Ajmooo! Hahaha. Napravit ćemo ovo kao malu skriptu za učenje, tako da možeš pratiti postupak i razumjeti **zašto nešto računamo**, a ne samo prepisati rezultat.

Zadržat ću sve zadatke i njihove rezultate, ali ću svaki razraditi korak po korak. Posebno ću paziti na:

- formule koje trebaš znati;
- uvrštavanje podataka;
- međukorake računanja;
- kratko objašnjenje kako prepoznati koju metodu koristiti.

# **Kolokvij 1c – detaljna rješenja**

## **Zadatak 1 – Opisna statistika**

**Podaci:** 2, 5, 4, −2, 6, 4, 1, 0, −3, 9.

Tražimo aritmetičku sredinu, mod, medijan i 30%-tni percentil.

**1. Aritmetička sredina**

Formula:

\\[ \bar{x}=\frac{\sum\_{i=1}^{n}x_i}{n} \\]

Zbrojimo sve podatke:

\\[ \bar{x}=\frac{2+5+4-2+6+4+1+0-3+9}{10} \\]

\\[ \bar{x}=\frac{26}{10}=\boxed{2,6} \\]

**2. Mod**

Mod je vrijednost koja se pojavljuje najviše puta.

Pogledajmo koliko se puta pojavljuje svaki broj:

- 2 → 1 put
- 5 → 1 put
- 4 → 2 puta
- −2 → 1 put
- 6 → 1 put
- 1 → 1 put
- 0 → 1 put
- −3 → 1 put
- 9 → 1 put

Broj 4 pojavljuje se najviše puta.

\\[ \boxed{Mo=4} \\]

**3. Medijan**

Prvo sortiramo podatke uzlazno:

\\[ -3,-2,0,1,2,4,4,5,6,9 \\]

Imamo 10 podataka, odnosno paran broj elemenata.

Kod parnog broja elemenata medijan je aritmetička sredina dvaju središnjih elemenata.

\\[ Me=\frac{x_5+x_6}{2} \\]

\\[ Me=\frac{2+4}{2}=\boxed{3} \\]

**4. 30%-tni percentil**

Koristimo pravilo:

\\[ np=10\cdot0,30=3 \\]

Budući da je rezultat cijeli broj, percentil računamo kao aritmetičku sredinu 3. i 4. elementa sortiranog niza.

\\[ P\_{30}=\frac{x_3+x_4}{2} \\]

\\[ P\_{30}=\frac{0+1}{2}=\boxed{0,5} \\]

Konačni rezultati

- Aritmetička sredina: **2,6**
- Mod: **4**
- Medijan: **3**
- 30%-tni percentil: **0,5**

## **Zadatak 2 – Tablice frekvencija**

**Podaci:**

vrabac, golub, vrabac, sjenica, golub, vrabac, kos, golub, vrabac, kos, golub, sjenica, vrabac, golub, golub.

Ukupno imamo:

\\[ n=15 \\]

**1. Apsolutna frekvencija**

Apsolutna frekvencija govori koliko se puta neka vrijednost pojavljuje u skupu podataka.

Prebrojavanjem dobivamo:

- Vrabac: 5
- Golub: 6
- Sjenica: 2
- Kos: 2

**2. Relativna frekvencija**

Relativna frekvencija predstavlja udio pojedine vrijednosti u ukupnom broju podataka.

Formula:

\\[ f_i=\frac{n_i}{n} \\]

Primjer za vrapca:

\\[ f\_{\text{vrabac}}=\frac{5}{15}=0,3333 \\]

Na isti način računamo ostale vrijednosti.

| Vrsta      | Frekvencija | Relativna frekvencija |
| ---------- | ----------- | --------------------- |
| Vrabac     | 5           | 0,3333                |
| Golub      | 6           | 0,4000                |
| Sjenica    | 2           | 0,1333                |
| Kos        | 2           | 0,1333                |
| **Ukupno** | **15**      | **1,0000**            |

Važno: zbroj svih relativnih frekvencija mora biti 1 (odnosno 100%).

\\[ \sum f_i=1 \\]

## **Zadatak 3 – Princip umnoška**

Biramo:

- 4 majice;
- 5 hlača;
- 3 jakne.

Kod ovakvih zadataka koristimo princip umnoška.

Ideja je jednostavna: za svaki izbor majice imamo 5 mogućnosti izbora hlača, a za svaku takvu kombinaciju još 3 mogućnosti izbora jakne.

Zato množimo broj mogućnosti:

\\[ N=4\cdot5\cdot3 \\]

\\[ \boxed{N=60} \\]

Moguće je složiti **60 različitih kombinacija**.

## **Zadatak 4 – Nezavisnost događaja**

Bacamo simetričnu kockicu.

Prostor elementarnih događaja:

\\[ \Omega=\\{1,2,3,4,5,6\\} \\]

Definirani su događaji:

- A: pao je paran broj;
- B: pao je broj djeljiv s 3;
- C: pao je broj manji ili jednak 2.

Prvo ih zapišimo kao skupove:

\\[ A=\\{2,4,6\\} \\]

\\[ B=\\{3,6\\} \\]

\\[ C=\\{1,2\\} \\]

**1. Jesu li A i B nezavisni?**

Dva događaja su nezavisna ako vrijedi:

\\[ P(A\cap B)=P(A)\cdot P(B) \\]

Izračunajmo pojedinačne vjerojatnosti.

Budući da je kockica simetrična:

\\[ P(A)=\frac{3}{6}=\frac12 \\]

\\[ P(B)=\frac{2}{6}=\frac13 \\]

Presjek A i B predstavlja ishode koji pripadaju objema skupinama.

\\[ A\cap B=\\{6\\} \\]

Dakle:

\\[ P(A\cap B)=\frac16 \\]

Provjeravamo uvjet nezavisnosti:

\\[ P(A)\cdot P(B)=\frac12\cdot\frac13 =\frac16 \\]

Dobivamo:

\\[ P(A\cap B)=P(A)P(B) \\]

**A i B su nezavisni događaji.**

**2. Jesu li A, B i C međusobno nezavisni?**

Za međusobnu nezavisnost triju događaja potrebno je provjeriti:

- nezavisnost svakog para;
- uvjet za sva tri događaja zajedno.

Dovoljno je pronaći jedan uvjet koji nije zadovoljen da zaključimo kako nisu međusobno nezavisni.

Pogledajmo B i C:

\\[ B\cap C=\varnothing \\]

Nema zajedničkih ishoda jer B sadrži 3 i 6, a C sadrži 1 i 2.

Zato:

\\[ P(B\cap C)=0 \\]

S druge strane:

\\[ P(B)P(C)=\frac13\cdot\frac26 =\frac19 \\]

Dakle:

\\[ 0\neq\frac19 \\]

**A, B i C nisu međusobno nezavisni.**

## **Zadatak 5 – Potpuna vjerojatnost i Bayesov teorem**

Imamo dvije vrećice:

| Vrećica | Plave kuglice | Crvene kuglice |
| ------- | ------------- | -------------- |
| 1       | 6             | 4              |
| 2       | 3             | 7              |

Novčić određuje koju vrećicu biramo:

\\[ P(H_1)=0,6 \\]

\\[ P(H_2)=0,4 \\]

Tražimo:

1. Vjerojatnost izvlačenja crvene kuglice.
2. Vjerojatnost da je kuglica iz druge vrećice ako znamo da je crvena.

**1. Potpuna vjerojatnost**

Definirajmo događaj A: izvučena je crvena kuglica.

Vjerojatnosti crvene kuglice iz pojedinih vrećica:

\\[ P(A|H_1)=\frac4{10}=0,4 \\]

\\[ P(A|H_2)=\frac7{10}=0,7 \\]

Koristimo formulu potpune vjerojatnosti:

\\[ P(A)=P(H_1)P(A|H_1)+ P(H_2)P(A|H_2) \\]

Uvrštavamo:

\\[ P(A)=0,6\cdot0,4+0,4\cdot0,7 \\]

\\[ P(A)=0,24+0,28 \\]

\\[ \boxed{P(A)=0,52} \\]

Vjerojatnost izvlačenja crvene kuglice iznosi 52%.

**2. Bayesov teorem**

Sada znamo da je izvučena kuglica crvena. Tražimo vjerojatnost da je došla iz druge vrećice.

Koristimo Bayesovu formulu:

\\[ P(H_2|A)=\frac{P(H_2)P(A|H_2)}{P(A)} \\]

Uvrštavamo:

\\[ P(H_2|A)=\frac{0,4\cdot0,7}{0,52} \\]

\\[ =\frac{0,28}{0,52} \\]

\\[ \boxed{P(H_2|A)\approx0,5385} \\]

Dakle, ako znamo da je kuglica crvena, vjerojatnost da dolazi iz druge vrećice iznosi približno **53,85%**.

## **Zadatak 6 – Svojstva vjerojatnosti**

Zadan je prostor:

\\[ \Omega=\\{1,2,3,4,5,6\\} \\]

Vjerojatnosti pojedinačnih ishoda:

\\[ P(1)=P(2)=P(5)=P(6)=0,1 \\]

\\[ P(3)=P(4)=0,3 \\]

Događaji:

\\[ A=\\{2,3,4,6\\} \\]

\\[ B=\\{3,4,5\\} \\]

Tražimo:

- \\(P(A\cup B)\\)
- \\(P(A\setminus B)\\)
- \\(P(B^c)\\)

**1. Unija događaja**

Unija sadrži sve elemente koji se nalaze u A ili B (ili u oba).

\\[ A\cup B=\\{2,3,4,5,6\\} \\]

Zbrajamo vjerojatnosti tih ishoda:

\\[ P(A\cup B)=P(2)+P(3)+P(4)+P(5)+P(6) \\]

\\[ =0,1+0,3+0,3+0,1+0,1 \\]

\\[ \boxed{P(A\cup B)=0,9} \\]

**2. Razlika skupova**

\\(A\setminus B\\) predstavlja elemente koji se nalaze u A, ali ne i u B.

Imamo:

\\[ A=\\{2,3,4,6\\} \\]

\\[ B=\\{3,4,5\\} \\]

Iz A izbacujemo elemente koji se nalaze u B:

\\[ A\setminus B=\\{2,6\\} \\]

Zato:

\\[ P(A\setminus B)=P(2)+P(6) \\]

\\[ =0,1+0,1 \\]

\\[ \boxed{P(A\setminus B)=0,2} \\]

**3. Komplement događaja**

Komplement \\(B^c\\) sadrži sve ishode koji se ne nalaze u B.

\\[ B=\\{3,4,5\\} \\]

Prema tome:

\\[ B^c=\\{1,2,6\\} \\]

Zbrajamo:

\\[ P(B^c)=P(1)+P(2)+P(6) \\]

\\[ =0,1+0,1+0,1 \\]

\\[ \boxed{P(B^c)=0,3} \\]

# **Kolokvij 1d – detaljna rješenja**

## **Zadatak 1 – Opisna statistika**

Podaci:

\\[ 3,0,5,-4,2,5,-1,1,7,-2 \\]

**1. Aritmetička sredina**

\\[ \bar{x}=\frac{3+0+5-4+2+5-1+1+7-2}{10} \\]

\\[ \bar{x}=\frac{16}{10}=\boxed{1,6} \\]

**2. Mod**

Najčešće se pojavljuje broj 5, i to dva puta.

\\[ \boxed{Mo=5} \\]

**3. Medijan**

Sortiramo podatke:

\\[ -4,-2,-1,0,1,2,3,5,5,7 \\]

Imamo 10 elemenata, pa uzimamo prosjek 5. i 6. elementa:

\\[ Me=\frac{1+2}{2} \\]

\\[ \boxed{Me=1,5} \\]

**4. 80%-tni percentil**

\\[ np=10\cdot0,8=8 \\]

Budući da je rezultat cijeli broj, uzimamo prosjek 8. i 9. elementa:

\\[ P\_{80}=\frac{x_8+x_9}{2} \\]

\\[ P\_{80}=\frac{5+5}{2} \\]

\\[ \boxed{P\_{80}=5} \\]

## **Zadatak 2 – Varijanca i transformacija podataka**

Zadano je:

\\[ x=(-6,-4,-2,0,2,4,6) \\]

\\[ y=(-11,-7,-3,1,5,9,13) \\]

Tražimo usporedbu varijanci.

**1. Varijanca niza x**

Prvo računamo aritmetičku sredinu:

\\[ \bar{x}=\frac{-6-4-2+0+2+4+6}{7}=0 \\]

Formula za varijancu:

\\[ Var(x)=\frac{\sum\_{i=1}^{n}(x_i-\bar{x})^2}{n-1} \\]

Ovdje koristimo varijancu uzorka, odnosno nazivnik \\(n-1\\).

Uvrštavamo:

\\[ Var(x)=\frac{ (-6)^2+(-4)^2+(-2)^2+0^2+ 2^2+4^2+6^2 }{6} \\]

\\[ =\frac{36+16+4+0+4+16+36}{6} \\]

\\[ =\frac{112}{6} \\]

\\[ \boxed{Var(x)\approx18,667} \\]

**2. Varijanca niza y**

Primijetimo zanimljivu stvar:

\\[ y_i=2x_i+1 \\]

Drugim riječima, svaki element niza x pomnožili smo s 2 i dodali 1.

Vrijedi svojstvo varijance:

\\[ Var(aX+b)=a^2Var(X) \\]

Dodavanje konstante ne mijenja varijancu, dok množenje s konstantom množi varijancu s njezinim kvadratom.

Ovdje je:

\\[ a=2,\quad b=1 \\]

Zato:

\\[ Var(y)=2^2Var(x) \\]

\\[ Var(y)=4\cdot18,667 \\]

\\[ \boxed{Var(y)\approx74,667} \\]

**Zaključak:** Varijance nisu jednake. Varijanca niza y četiri je puta veća od varijance niza x.

## **Zadatak 3 – Princip umnoška**

Imamo tri dionice puta:

- Pula → Rijeka: 3 mogućnosti;
- Rijeka → Ljubljana: 4 mogućnosti;
- Ljubljana → Beč: 6 mogućnosti.

Za svaku od 3 mogućnosti prve dionice postoje 4 mogućnosti druge, a za svaku od njih 6 mogućnosti treće dionice.

Prema principu umnoška:

\\[ N=3\cdot4\cdot6 \\]

\\[ \boxed{N=72} \\]

Postoje 72 različita načina putovanja.

## **Zadatak 4 – Nezavisnost događaja**

Imamo kuglicu s brojevima od 1 do 12.

\\[ \Omega=\\{1,2,\ldots,12\\} \\]

Događaji:

- A: broj je paran;
- B: broj je djeljiv s 3;
- C: broj je manji ili jednak 2.

Zapisujemo skupove:

\\[ A=\\{2,4,6,8,10,12\\} \\]

\\[ B=\\{3,6,9,12\\} \\]

\\[ C=\\{1,2\\} \\]

**1. Nezavisnost A i B**

Formula:

\\[ P(A\cap B)=P(A)P(B) \\]

Računamo:

\\[ P(A)=\frac6{12}=\frac12 \\]

\\[ P(B)=\frac4{12}=\frac13 \\]

Presjek:

\\[ A\cap B=\\{6,12\\} \\]

\\[ P(A\cap B)=\frac2{12}=\frac16 \\]

Provjera:

\\[ P(A)P(B)=\frac12\cdot\frac13=\frac16 \\]

Uvjet je zadovoljen.

**A i B su nezavisni.**

**2. Nezavisnost A, B i C**

Provjerimo događaje B i C:

\\[ B\cap C=\varnothing \\]

Dakle:

\\[ P(B\cap C)=0 \\]

Ali:

\\[ P(B)P(C)=\frac4{12}\cdot\frac2{12} \\]

\\[ =\frac13\cdot\frac16=\frac1{18} \\]

Budući da:

\\[ 0\neq\frac1{18} \\]

B i C nisu nezavisni.

Prema tome, A, B i C nisu međusobno nezavisni.

## **Zadatak 5 – Potpuna vjerojatnost**

U kutiji imamo:

- 5 bijelih kugli;
- 5 crnih kugli.

Broj izvlačenja ovisi o rezultatu bacanja kockice:

| Ishod kockice | Broj kugli koje izvlačimo | Vjerojatnost |
| ------------- | ------------------------- | ------------ |
| 1 ili 2       | 1                         | 1/3          |
| 3 ili 4       | 2                         | 1/3          |
| 5 ili 6       | 3                         | 1/3          |

Tražimo vjerojatnost da među izvučenim kuglama bude barem jedna bijela.

**1. Koristimo komplement događaja**

Umjesto da računamo vjerojatnost barem jedne bijele kugle, lakše je računati suprotan događaj:

\\[ A^c=\text{sve izvučene kugle su crne} \\]

Tada vrijedi:

\\[ P(A)=1-P(A^c) \\]

**2. Računamo vjerojatnost da su sve kugle crne**

Razlikujemo tri slučaja.

*Prvi slučaj: izvlačimo jednu kuglu.*

Od 10 kugli, njih 5 je crno.

\\[ P(A^c|H_1)=\frac5{10}=\frac12 \\]

*Drugi slučaj: izvlačimo dvije kugle bez vraćanja.*

Prva kugla mora biti crna, a zatim i druga.

\\[ P(A^c|H_2)=\frac5{10}\cdot\frac4{9} \\]

\\[ =\frac{20}{90}=\frac29 \\]

Isti rezultat dobivamo pomoću kombinacija:

\\[ P(A^c|H_2)=\frac{\binom52}{\binom{10}2} =\frac{10}{45}=\frac29 \\]

*Treći slučaj: izvlačimo tri kugle bez vraćanja.*

Sve tri moraju biti crne:

\\[ P(A^c|H_3)= \frac5{10}\cdot\frac49\cdot\frac38 \\]

\\[ =\frac{60}{720}=\frac1{12} \\]

**3. Primjenjujemo potpunu vjerojatnost**

Svaki slučaj ima vjerojatnost 1/3.

\\[ P(A^c)= \frac13\cdot\frac12+ \frac13\cdot\frac29+ \frac13\cdot\frac1{12} \\]

Izlučimo 1/3:

\\[ P(A^c)=\frac13 \left(\frac12+\frac29+\frac1{12}\right) \\]

Zajednički nazivnik je 36:

\\[ P(A^c)=\frac13 \left(\frac{18+8+3}{36}\right) \\]

\\[ P(A^c)=\frac13\cdot\frac{29}{36} \\]

\\[ P(A^c)=\frac{29}{108} \\]

**4. Izračunamo traženu vjerojatnost**

\\[ P(A)=1-\frac{29}{108} \\]

\\[ \boxed{P(A)=\frac{79}{108}\approx0,7315} \\]

Vjerojatnost da ćemo izvući barem jednu bijelu kuglu iznosi približno **73,15%**.

## **Zadatak 6 – Svojstva vjerojatnosti**

Zadano:

\\[ \Omega=\\{1,2,3,4,5,6\\} \\]

\\[ P(1)=P(6)=\frac15 \\]

\\[ P(2)=P(5)=\frac1{10} \\]

\\[ P(3)=P(4)=\frac15 \\]

Događaji:

\\[ A=\\{1,2,3\\} \\]

\\[ B=\\{3,4,5\\} \\]

**1. Unija**

\\[ A\cup B=\\{1,2,3,4,5\\} \\]

Zbrajamo pripadajuće vjerojatnosti:

\\[ P(A\cup B)= \frac15+\frac1{10}+\frac15+\frac15+\frac1{10} \\]

\\[ =\frac2{10}+\frac1{10}+\frac2{10}+\frac2{10}+\frac1{10} \\]

\\[ \boxed{P(A\cup B)=\frac45} \\]

**2. Razlika skupova**

\\[ A\setminus B=\\{1,2\\} \\]

\\[ P(A\setminus B)=P(1)+P(2) \\]

\\[ =\frac15+\frac1{10} \\]

\\[ \boxed{P(A\setminus B)=\frac3{10}} \\]

**3. Komplement**

\\[ B^c=\\{1,2,6\\} \\]

\\[ P(B^c)=P(1)+P(2)+P(6) \\]

\\[ =\frac15+\frac1{10}+\frac15 \\]

\\[ \boxed{P(B^c)=\frac12} \\]

# **Kolokvij 1e – detaljna rješenja**

## **Zadatak 1 – Opisna statistika**

Podaci:

\\[ 6,2,-1,3,2,0,-5,4,2,1 \\]

**1. Aritmetička sredina**

\\[ \bar{x}=\frac{6+2-1+3+2+0-5+4+2+1}{10} \\]

\\[ \bar{x}=\frac{14}{10} \\]

\\[ \boxed{\bar{x}=1,4} \\]

**2. Mod**

Broj 2 pojavljuje se tri puta, više od svih ostalih vrijednosti.

\\[ \boxed{Mo=2} \\]

**3. Medijan**

Sortiramo podatke:

\\[ -5,-1,0,1,2,2,2,3,4,6 \\]

Imamo 10 elemenata:

\\[ Me=\frac{x_5+x_6}{2} \\]

\\[ Me=\frac{2+2}{2} \\]

\\[ \boxed{Me=2} \\]

**4. 40%-tni percentil**

\\[ np=10\cdot0,4=4 \\]

Rezultat je cijeli broj, stoga računamo prosjek 4. i 5. elementa:

\\[ P\_{40}=\frac{x_4+x_5}{2} \\]

\\[ P\_{40}=\frac{1+2}{2} \\]

\\[ \boxed{P\_{40}=1,5} \\]

## **Zadatak 2 – Tablice frekvencija**

Podaci:

\\[ 3,4,5,4,3,2,4,5,4,3,5,4,3,4,2 \\]

Ukupan broj ocjena:

\\[ n=15 \\]

**1. Apsolutne frekvencije**

Prebrojimo svaku ocjenu:

- Ocjena 2 pojavljuje se 2 puta.
- Ocjena 3 pojavljuje se 4 puta.
- Ocjena 4 pojavljuje se 6 puta.
- Ocjena 5 pojavljuje se 3 puta.

**2. Relativne frekvencije**

Koristimo:

\\[ f_i=\frac{n_i}{n} \\]

Primjer za ocjenu 4:

\\[ f_4=\frac6{15}=0,4 \\]

Ostale:

\\[ f_2=\frac2{15}\approx0,1333 \\]

\\[ f_3=\frac4{15}\approx0,2667 \\]

\\[ f_5=\frac3{15}=0,2 \\]

Tablica:

| Ocjena     | Frekvencija | Relativna frekvencija |
| ---------- | ----------- | --------------------- |
| 2          | 2           | 0,1333                |
| 3          | 4           | 0,2667                |
| 4          | 6           | 0,4000                |
| 5          | 3           | 0,2000                |
| **Ukupno** | **15**      | **1,0000**            |

## **Zadatak 3 – Princip umnoška**

Biramo:

- 4 vrste kruha;
- 6 nadjeva;
- 3 umaka.

Za svaku vrstu kruha možemo izabrati bilo koji od 6 nadjeva, a za svaku takvu kombinaciju bilo koji od 3 umaka.

Prema principu umnoška:

\\[ N=4\cdot6\cdot3 \\]

\\[ \boxed{N=72} \\]

Moguće je složiti 72 različita sendviča.

## **Zadatak 4 – Nezavisnost događaja**

Imamo karte s brojevima:

\\[ \Omega=\\{1,2,3,4,5,6,7,8\\} \\]

Događaji:

- A: broj je neparan;
- B: broj je manji ili jednak 4;
- C: broj je veći od 6.

Zapisujemo skupove:

\\[ A=\\{1,3,5,7\\} \\]

\\[ B=\\{1,2,3,4\\} \\]

\\[ C=\\{7,8\\} \\]

**1. Provjera nezavisnosti A i B**

\\[ P(A)=\frac48=\frac12 \\]

\\[ P(B)=\frac48=\frac12 \\]

Presjek:

\\[ A\cap B=\\{1,3\\} \\]

\\[ P(A\cap B)=\frac28=\frac14 \\]

Provjeravamo:

\\[ P(A)P(B)=\frac12\cdot\frac12=\frac14 \\]

Uvjet je zadovoljen.

**A i B su nezavisni.**

**2. Provjera međusobne nezavisnosti A, B i C**

Pogledajmo B i C:

\\[ B\cap C=\varnothing \\]

Zato:

\\[ P(B\cap C)=0 \\]

A:

\\[ P(B)P(C)=\frac12\cdot\frac28 \\]

\\[ =\frac12\cdot\frac14=\frac18 \\]

Budući da:

\\[ 0\neq\frac18 \\]

B i C nisu nezavisni, pa ni sva tri događaja nisu međusobno nezavisna.

## **Zadatak 5 – Potpuna vjerojatnost i Bayesov teorem**

Tvornica ima tri stroja:

| Stroj | Udio proizvodnje | Udio neispravnih |
| ----- | ---------------- | ---------------- |
| S1    | 50%              | 1%               |
| S2    | 30%              | 2%               |
| S3    | 20%              | 5%               |

Tražimo:

1. Vjerojatnost da je slučajno odabrani proizvod neispravan.
2. Vjerojatnost da je neispravan proizvod proizveo stroj S3.

**1. Potpuna vjerojatnost**

Definiramo događaje:

- \\(H_1\\): proizvod je proizveo S1;
- \\(H_2\\): proizvod je proizveo S2;
- \\(H_3\\): proizvod je proizveo S3;
- \\(D\\): proizvod je neispravan.

Iz tablice imamo:

\\[ P(H_1)=0,5 \\]

\\[ P(H_2)=0,3 \\]

\\[ P(H_3)=0,2 \\]

Vjerojatnosti neispravnosti:

\\[ P(D|H_1)=0,01 \\]

\\[ P(D|H_2)=0,02 \\]

\\[ P(D|H_3)=0,05 \\]

Primjenjujemo formulu potpune vjerojatnosti:

\\[ P(D)= P(H_1)P(D|H_1)+ P(H_2)P(D|H_2)+ P(H_3)P(D|H_3) \\]

Uvrštavamo:

\\[ P(D)=0,5\cdot0,01+ 0,3\cdot0,02+ 0,2\cdot0,05 \\]

\\[ P(D)=0,005+0,006+0,010 \\]

\\[ \boxed{P(D)=0,021} \\]

Dakle, vjerojatnost neispravnog proizvoda iznosi **2,1%**.

**2. Bayesov teorem**

Sada znamo da je proizvod neispravan. Želimo izračunati vjerojatnost da ga je proizveo S3.

Koristimo:

\\[ P(H_3|D)=\frac{P(H_3)P(D|H_3)}{P(D)} \\]

Uvrštavamo:

\\[ P(H_3|D)=\frac{0,2\cdot0,05}{0,021} \\]

\\[ =\frac{0,010}{0,021} \\]

\\[ \boxed{P(H_3|D)\approx0,4762} \\]

Dakle, ako znamo da je proizvod neispravan, postoji približno **47,62% vjerojatnosti** da ga je proizveo stroj S3.

Zanimljivost: S3 proizvodi samo 20% svih proizvoda, ali odgovoran je za gotovo polovicu neispravnih proizvoda. To je upravo ono što nam Bayesov teorem pomaže otkriti.

## **Zadatak 6 – Svojstva vjerojatnosti**

Zadano:

\\[ \Omega=\\{1,2,3,4,5,6\\} \\]

\\[ P(1)=P(6)=\frac14 \\]

\\[ P(2)=P(3)=P(4)=P(5)=\frac18 \\]

Događaji:

\\[ A=\\{1,2,3\\} \\]

\\[ B=\\{3,4,6\\} \\]

**1. Unija događaja**

Unija sadrži sve elemente koji pripadaju barem jednom od događaja.

\\[ A\cup B=\\{1,2,3,4,6\\} \\]

Zbrajamo vjerojatnosti:

\\[ P(A\cup B)= P(1)+P(2)+P(3)+P(4)+P(6) \\]

\\[ =\frac14+\frac18+\frac18+\frac18+\frac14 \\]

Svedemo na zajednički nazivnik:

\\[ =\frac28+\frac18+\frac18+\frac18+\frac28 \\]

\\[ \boxed{P(A\cup B)=\frac78} \\]

**2. Razlika skupova**

\\[ A\setminus B=\\{1,2\\} \\]

Element 3 izbacujemo jer pripada i skupu B.

\\[ P(A\setminus B)=P(1)+P(2) \\]

\\[ =\frac14+\frac18 \\]

\\[ \boxed{P(A\setminus B)=\frac38} \\]

**3. Komplement događaja**

\\[ B=\\{3,4,6\\} \\]

Prema tome:

\\[ B^c=\\{1,2,5\\} \\]

Zbrajamo:

\\[ P(B^c)=P(1)+P(2)+P(5) \\]

\\[ =\frac14+\frac18+\frac18 \\]

\\[ \boxed{P(B^c)=\frac12} \\]

# **Mini šalabahter – formule za kolokvij**

Ovo bih ti preporučio naučiti napamet. Pokriva praktički sve tipove zadataka iz ove tri varijante.

**1. Opisna statistika**

Aritmetička sredina:

\\[ \bar{x}=\frac{\sum x_i}{n} \\]

Varijanca uzorka:

\\[ s^2=\frac{\sum(x_i-\bar{x})^2}{n-1} \\]

Transformacija varijance:

\\[ Var(aX+b)=a^2Var(X) \\]

**2. Frekvencije**

Relativna frekvencija:

\\[ f_i=\frac{n_i}{n} \\]

Zbroj relativnih frekvencija:

\\[ \sum f_i=1 \\]

**3. Princip umnoška**

\\[ N=n_1\cdot n_2\cdot\ldots\cdot n_k \\]

**4. Nezavisnost**

Za dva događaja:

\\[ P(A\cap B)=P(A)P(B) \\]

Za tri međusobno nezavisna događaja potrebno je provjeriti i:

\\[ P(A\cap B\cap C)=P(A)P(B)P(C) \\]

uz nezavisnost svih parova.

**5. Potpuna vjerojatnost**

\\[ P(A)=\sum_i P(H_i)P(A|H_i) \\]

**6. Bayesov teorem**

\\[ P(H_k|A)= \frac{P(H_k)P(A|H_k)}{P(A)} \\]

**7. Osnovna svojstva vjerojatnosti**

Unija:

\\[ P(A\cup B)=P(A)+P(B)-P(A\cap B) \\]

Razlika:

\\[ P(A\setminus B)=P(A)-P(A\cap B) \\]

Komplement:

\\[ P(A^c)=1-P(A) \\]

## **Tri stvari na koje posebno pazi na kolokviju**

1. **Percentili:** kada je \\(np\\) cijeli broj, u ovim zadacima uzimaš prosjek odgovarajućeg i sljedećeg elementa. Kada nije cijeli broj, treba primijeniti pravilo koje je definirano na vašim predavanjima.
2. **Varijanca:** provjeri računa li se varijanca populacije (dijeljenje s \\(n\\)) ili uzorka (dijeljenje s \\(n-1\\)). U zadatku 1d koristili smo uzoračku varijancu.
3. **Tri nezavisna događaja:** nezavisnost A i B ne znači automatski da su A, B i C međusobno nezavisni.
