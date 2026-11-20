Praktični vodič za rješavanje tipičnih zadataka s prvog kolokvija.
Koristi se kada tražimo prosječnu vrijednost podataka.

Formula:

[
\bar{x}=\frac{x_1+x_2+\cdots+x_n}{n}
=\frac{1}{n}\sum_{i=1}^{n}x_i
]

Postupak:
1. Zbroji sve vrijednosti.
2. Podijeli zbroj s brojem vrijednosti.
Primjer:

Podaci: 2, 4, 4, 6, 9

[
\bar{x}=\frac{2+4+4+6+9}{5}=\frac{25}{5}=5
]
Medijan je srednja vrijednost uređenog niza.

Postupak:
1. Poredaj podatke uzlazno.
2. Prebroji koliko ima vrijednosti (n).
3. Ako je n neparan, uzmi srednju vrijednost.
4. Ako je n paran, izračunaj prosjek dviju srednjih vrijednosti.
Formule:

Za neparan broj podataka:

[
Me=x_{\frac{n+1}{2}}
]

Za paran broj podataka:

[
Me=\frac{x_{\frac n2}+x_{\frac n2+1}}{2}
]

Primjer:
- 2, 4, 5, 7, 9 → medijan je 5.
- 2, 4, 5, 7 → medijan je (4 + 5) / 2 = 4.5.
Mod je vrijednost koja se pojavljuje najviše puta.

Primjer:

Podaci: 2, 4, 4, 5, 7, 7, 7, 9

[
Mo=7
]

Moguće je da:
- postoji jedan mod;
- postoji više modova;
- sve vrijednosti imaju jednaku frekvenciju.
Percentil (P_p) označava vrijednost ispod koje se nalazi određeni dio uređenih podataka.

Postupak:
1. Poredaj podatke uzlazno.
2. Izračunaj poziciju:
[
k=\frac{p}{100}\cdot n
]
3. Odredi percentil prema pravilu koje se koristi na kolegiju.
Konvencija iz primjera u ovim zadacima:

Ako je (k) cijeli broj:

[
P_p=\frac{x_k+x_{k+1}}{2}
]

Primjer:

Podaci: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10

Tražimo (P_{30}):

[
k=0.30\cdot10=3
]

[
P_{30}=\frac{x_3+x_4}{2}
=\frac{3+4}{2}=3.5
]

PAŽNJA: Ovo je konvencija korištena u dostavljenim primjerima. Različiti udžbenici i alati mogu koristiti druge metode računanja percentila. Za ne-cjelobrojnu poziciju slijedi pravilo koje je definirao nastavnik.
Varijanca mjeri raspršenost podataka oko aritmetičke sredine.

Varijanca populacije:

[
\sigma^2=\frac{1}{n}\sum_{i=1}^{n}(x_i-\bar{x})^2
]

Varijanca uzorka:

[
s^2=\frac{1}{n-1}\sum_{i=1}^{n}(x_i-\bar{x})^2
]

Postupak:
1. Izračunaj aritmetičku sredinu.
2. Od svake vrijednosti oduzmi sredinu.
3. Kvadriraj dobivene razlike.
4. Zbroji kvadrate.
5. Podijeli s n ili n − 1, ovisno o tome računaš li varijancu populacije ili uzorka.
Važno:

Ako su sve vrijednosti transformirane formulom:

[
Y=aX+b
]

onda vrijedi:

[
Var(Y)=a^2Var(X)
]

Dodavanje konstante ne mijenja varijancu, a množenje s a množi varijancu s (a^2).
Koriste se kada treba analizirati koliko se puta pojavljuje pojedina vrijednost ili kategorija.
Označava broj pojavljivanja određene vrijednosti.

[
f_i=\text{broj pojavljivanja vrijednosti }x_i
]
Označava udio pojavljivanja određene vrijednosti u ukupnom skupu.

[
h_i=\frac{f_i}{n}
]

Za postotak:

[
h_i(%)=\frac{f_i}{n}\cdot100
]
Označava ukupan broj pojavljivanja do određene vrijednosti.

[
F_i=\sum_{j=1}^{i}f_j
]
[
H_i=\sum_{j=1}^{i}h_j
]

Primjer:

Podaci: 2, 3, 3, 4, 4, 4, 5, 5
Vrijednost	Aps. frekvencija	Rel. frekvencija	Kumulativna frekvencija
2	1	12.5%	1
3	2	25%	3
4	3	37.5%	6
5	2	25%	8
Ukupno	8	100%	
Provjera:

[
\sum f_i=n
]

[
\sum h_i=1
]
Koristi se kada se postupak sastoji od više uzastopnih izbora.

Ako prvi korak ima (n_1) mogućnosti, drugi (n_2), a treći (n_3), ukupan broj mogućnosti je:

[
N=n_1\cdot n_2\cdot n_3
]

Primjer 1 — PIN:

PIN ima 4 znamenke. Svaka znamenka može biti od 0 do 9, a ponavljanje je dopušteno.

[
N=10\cdot10\cdot10\cdot10=10^4=10000
]

Primjer 2 — odjeća:

Na raspolaganju su:
- 3 majice;
- 4 hlače;
- 2 para cipela.
[
N=3\cdot4\cdot2=24
]

Kako prepoznati zadatak?

Ako zadatak pita koliko se različitih kombinacija može složiti kroz nekoliko uzastopnih izbora, najčešće koristiš princip množenja.

PAŽNJA: Ako je izbor bez ponavljanja, broj mogućnosti u sljedećem koraku može se smanjiti.
Događaji (A) i (B) su neovisni ako ostvarenje jednog ne utječe na vjerojatnost ostvarenja drugog.

Uvjet neovisnosti:

[
P(A\cap B)=P(A)\cdot P(B)
]

Postupak:
1. Izračunaj (P(A)).
2. Izračunaj (P(B)).
3. Izračunaj (P(A\cap B)).
4. Provjeri vrijedi li jednakost.
Ako vrijedi, događaji su neovisni. Ako ne vrijedi, događaji su ovisni.
Tri događaja (A), (B) i (C) međusobno su neovisna ako vrijedi:

[
P(A\cap B)=P(A)P(B)
]

[
P(A\cap C)=P(A)P(C)
]

[
P(B\cap C)=P(B)P(C)
]

i dodatno:

[
P(A\cap B\cap C)=P(A)P(B)P(C)
]

Važno: Provjera samo parova nije dovoljna za dokaz međusobne neovisnosti triju događaja.

Za dokaz da događaji NISU međusobno neovisni dovoljno je pronaći samo jednu jednakost koja ne vrijedi.
Vjerojatnost događaja (A) pod uvjetom da se dogodio događaj (B):

[
P(A|B)=\frac{P(A\cap B)}{P(B)}
]

Uvjet je:

[
P(B)>0
]

Kako prepoznati zadatak?

Izrazi poput:
- „ako znamo da se dogodio...”;
- „pod uvjetom da...”;
- „ako je poznato da...”.
Obično upućuju na uvjetnu vjerojatnost.
Iz definicije uvjetne vjerojatnosti:

[
P(A\cap B)=P(A|B)\cdot P(B)
]

Također:

[
P(A\cap B)=P(B|A)\cdot P(A)
]

Koristi se kada poznajemo vjerojatnost jednog događaja i uvjetnu vjerojatnost drugog.
Ako događaji (A_1,A_2,\ldots,A_n) čine potpunu particiju prostora uzorka, vrijedi:

[
P(B)=\sum_{i=1}^{n}P(B|A_i)P(A_i)
]

Za dva događaja:

[
P(B)=P(B|A)P(A)+P(B|\overline A)P(\overline A)
]

Kako prepoznati zadatak?
- Proizvodi dolaze iz više tvornica.
- Dijelovi dolaze s više proizvodnih linija.
- Kupci dolaze iz više skupina.
- Svaka skupina ima svoju vjerojatnost pogreške ili nekog ishoda.
Postupak:
1. Razdvoji moguće izvore ili skupine.
2. Zapiši vjerojatnost odabira svake skupine.
3. Zapiši uvjetnu vjerojatnost traženog događaja za svaku skupinu.
4. Pomnoži odgovarajuće vjerojatnosti.
5. Zbroji rezultate.
Koristi se kada znamo da se dogodio neki rezultat, a želimo odrediti iz kojeg izvora ili skupine potječe.

[
P(A_i|B)=\frac{P(B|A_i)P(A_i)}{P(B)}
]

Nazivnik se često računa formulom totalne vjerojatnosti.

Za dvije skupine:

[
P(A|B)=
\frac{P(B|A)P(A)}
{P(B|A)P(A)+P(B|\overline A)P(\overline A)}
]

Primjer — proizvodnja:

Tri stroja proizvode dijelove:
- (P(A_1)=0.5), stopa greške 1%;
- (P(A_2)=0.3), stopa greške 2%;
- (P(A_3)=0.2), stopa greške 5%.
Tražimo vjerojatnost da neispravan dio dolazi sa stroja 3.

Prvo računamo ukupnu vjerojatnost neispravnog dijela:

[
P(D)=0.5\cdot0.01+0.3\cdot0.02+0.2\cdot0.05
]

[
P(D)=0.005+0.006+0.010=0.021
]

Zatim primjenjujemo Bayesov teorem:

[
P(A_3|D)=\frac{0.05\cdot0.2}{0.021}
]

[
P(A_3|D)=\frac{0.01}{0.021}\approx0.4762
]

Odgovor: približno 47.62%.

Najčešća pogreška: Zamjena (P(A|B)) i (P(B|A)). To nisu iste vjerojatnosti!
Događa se (A) ILI (B), odnosno barem jedan od događaja.

[
A\cup B
]

Formula:

[
P(A\cup B)=P(A)+P(B)-P(A\cap B)
]

Ako su događaji disjunktni:

[
P(A\cup B)=P(A)+P(B)
]
Događaju se (A) I (B).

[
A\cap B
]

Ako su događaji neovisni:

[
P(A\cap B)=P(A)P(B)
]

PAŽNJA: Ova formula vrijedi za neovisne događaje. Za općenite događaje koristi se uvjetna vjerojatnost ili druga poznata informacija.
Događa se sve osim događaja (A).

[
A^c \quad \text{ili} \quad \overline A
]

Formula:

[
P(A^c)=1-P(A)
]

Trik za zadatke:

Izraz „barem jedan” često je jednostavnije riješiti preko komplementa:

[
P(\text{barem jedan})=1-P(\text{nijedan})
]

Primjer:

Vjerojatnost da se pogodi meta u jednom pokušaju je 0.8. Izvedena su dva neovisna pokušaja.

[
P(\text{barem jedan pogodak})
=1-P(\text{nijedan pogodak})
]

[
=1-(0.2\cdot0.2)=0.96
]
Događa se (A), ali ne i (B).

[
A\setminus B=A\cap B^c
]

Formula:

[
P(A\setminus B)=P(A)-P(A\cap B)
]
Događaji su disjunktni ako se ne mogu dogoditi istovremeno.

[
A\cap B=\varnothing
]

[
P(A\cap B)=0
]

Za disjunktne događaje:

[
P(A\cup B)=P(A)+P(B)
]

VAŽNO: Disjunktnost i neovisnost nisu isto. Ako su dva događaja disjunktna i oba imaju pozitivnu vjerojatnost, nisu neovisna.
Ako zadatak daje skup mogućih ishoda, prvo definiraj prostor uzorka:

[
\Omega={\omega_1,\omega_2,\ldots,\omega_n}
]

Događaj je podskup prostora uzorka:

[
A\subseteq\Omega
]

Vjerojatnost događaja računa se zbrajanjem vjerojatnosti njegovih elementarnih ishoda:

[
P(A)=\sum_{\omega_i\in A}P(\omega_i)
]

Ako su svi ishodi jednako vjerojatni:

[
P(A)=\frac{|A|}{|\Omega|}
]

Ako ishodi nisu jednako vjerojatni:

Ne smiješ koristiti omjer broja povoljnih i ukupnih ishoda. Moraš zbrojiti zadane vjerojatnosti.

Provjera raspodjele:

[
\sum_{\omega_i\in\Omega}P(\omega_i)=1
]

Ako zbroj nije 1, negdje postoji pogreška ili nedostaje informacija.
Kod izvlačenja bez vraćanja broj dostupnih elemenata mijenja se nakon svakog izvlačenja.

Ako imamo (B) crnih i (W) bijelih kuglica:

[
N=B+W
]

Vjerojatnost izvlačenja crne kuglice u prvom izvlačenju:

[
P(C_1)=\frac{B}{N}
]

Ako se kuglica ne vraća, vjerojatnost crne kuglice u drugom izvlačenju, pod uvjetom da je prva bila crna:

[
P(C_2|C_1)=\frac{B-1}{N-1}
]

Vjerojatnost da su obje crne:

[
P(C_1\cap C_2)=\frac{B}{N}\cdot\frac{B-1}{N-1}
]

Za tri uzastopne crne kuglice:

\frac{B}{N}\cdot
\frac{B-1}{N-1}\cdot
\frac{B-2}{N-2}
]

PAŽNJA: Bez vraćanja izvlačenja nisu neovisna!
Ako zadatak traži...	Koristi...
Prosječnu vrijednost	Aritmetičku sredinu
Srednju vrijednost uređenog niza	Medijan
Najčešću vrijednost	Mod
Vrijednost ispod koje je određeni postotak podataka	Percentil
Raspršenost podataka	Varijancu
Broj pojavljivanja	Apsolutnu frekvenciju
Udio pojavljivanja	Relativnu frekvenciju
Ukupan broj uzastopnih kombinacija	Princip množenja
Provjeru neovisnosti	(P(A\cap B)=P(A)P(B))
Vjerojatnost uz poznat uvjet	Uvjetnu vjerojatnost
Ukupnu vjerojatnost kroz više skupina	Totalnu vjerojatnost
Izvor događaja nakon poznatog rezultata	Bayesov teorem
A ili B	Uniju
A i B	Presjek
Sve osim A	Komplement
A, ali ne B	Razliku događaja
Barem jedan	Komplement događaja „nijedan”
Izvlačenje bez vraćanja	Uvjetne vjerojatnosti i princip množenja
1. Medijan bez sortiranja: Podatke uvijek prvo poredaj uzlazno.
2. Pogrešan broj elemenata: Provjeri n prije računanja sredine, medijana ili percentila.
3. Miješanje varijance populacije i uzorka: Provjeri dijeliš li s n ili n − 1.
4. Pretpostavka da su ishodi jednako vjerojatni: To vrijedi samo ako je zadano ili opravdano.
5. Miješanje neovisnosti i disjunktnosti: To su različita svojstva.
6. Zaboravljanje presjeka u uniji: Oduzmi (P(A\cap B)).
7. Zamjena Bayesovih vjerojatnosti: (P(A|B)\neq P(B|A)) općenito.
8. Vraćanje kuglica u računu bez vraćanja: Nakon svakog izvlačenja promijeni broj preostalih kuglica.
9. Zaboravljanje komplementa: „Barem jedan” često je lakše riješiti kao (1-P(\text{nijedan})).
10. Neprovjeravanje zbroja vjerojatnosti: Sve elementarne vjerojatnosti zajedno moraju dati 1.
- Jesam li pravilno prepisao/la podatke?
- Jesam li odabrao/la odgovarajuću formulu?
- Jesam li provjerio/la pretpostavke formule?
- Jesam li pravilno izračunao/la presjek, uniju ili komplement?
- Jesu li vjerojatnosti u dopuštenom rasponu od 0 do 1?
- Zbrajaju li se vjerojatnosti svih elementarnih ishoda u 1?
- Jesam li napisao/la konačan odgovor i odgovarajuću mjernu jedinicu, ako je potrebna?
Sretno na kolokviju!

Ovaj šalabahter služi kao pregled metoda i formula. Uvijek slijedi definicije i konvencije koje se koriste na kolegiju.

