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
