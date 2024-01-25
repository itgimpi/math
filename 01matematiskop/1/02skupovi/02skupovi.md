## 2. SKUPOVI

$S = \{x| S(x)\}$, znači isto čto i: $S = \{x| x$ ima svojstvo $S(x)\}$ tj. S je skup svih elemenata koji imaju svojstvo S(x).

Za skupove prirodnih, celih, racionalnih, realnih brojeva koristimo oznake redom: N, Z, Q, R.

Podskup A skupa S je skup koji zadovoljava uslov: (∀x) (x ∈ A ⇒ x ∈ S).
Oznaka je A ⊂ S ili S ⊃ A.
Jednakost dva skupa definiˇse se na slede´ci naˇcin
A = B ⇐⇒ (∀x) (x ∈ A ⇐⇒ x ∈ B) ili (A = B ⇐⇒ (A ⊂ B ∧ B ⊂ A).
Postoji jedan i samo jedan prazan skup. To je skup koji nema elemenata.
Prazan skup je matematiˇcka konstanta. Oznaˇcavamo ga sa ∅.
Unija dva skupa A i B je skup koji oznaˇcavamo sa A ∪ B i to je:
A ∪ B = {x| x ∈ A ∨ x ∈ B}.
Presek dva skupa A i B je skup koji oznaˇcavamo sa A ∩ B i to je:
A ∩ B = {x| x ∈ A ∧ x ∈ B}.
Ako je A ∩ B = ∅, tada kaˇzemo da su A i B disjunktni (razdvojeni).
Razlika skupa A i skupa B je skup koji oznaˇcavamo sa A\B i to je:
A\B = {x| x ∈ A ∧ x ∈ B}.
Grafiˇcka interpretacija pomo´cu tzv. Ojler-Venovih dijagrama (ˇsrafirani delovi
su redom: unija, presek, razlika) data je na slikama 6, 7 i 8.
Sl. 6 Sl. 7 Sl. 8
Komplement skupa A, skup oznaˇcen sa A, definiˇsemo kao: A={x| x∈A}.
Komplement skupa A u odnosu na skup B, ako A ⊂ B, je: CB(A) = B\A.
Ured-en par (ured-ena dvojka) je skup od dva elementa, recimo a i b, koji
oznaˇcavamo sa (a, b) i definiˇsemo kao: (a, b) = {{a}, {a, b}}.
Jednakost dva ured-ena para karakteriˇse prirodu ovih skupova:
(a, b) = (c, d) ⇐⇒ (a = c ∧ b = d).
22 DRUGA GLAVA
Dekartov proizvod dva skupa A i B, u oznaci A × B je
A × B = {(a, b)| a ∈ A ∧ b ∈ B}.
Dekartov kvadrat skupa A je: A2 = A × A = {(a, b)| a, b ∈ A}.
Relacija izmed-u dva elementa a i b, a ∈ A, b ∈ B, je skup ρ, takav da je
ρ ⊂ A × B ∧ (a, b) ∈ ρ. Tada piˇsemo: aρb, ˇsto znaˇci: a je u relaciji ρ sa b.
Od mogu´cih osobina relacije ρ definisanih na skupu A, ρ ⊂ A × A, istiˇcemo:
(R) refleksivnost (∀x ∈ A)(xρx)
(S) simetriˇcnost (∀x, y ∈ A)(xρy ⇒ yρx)
(AS) antisimetriˇcnost (∀x, y ∈ A)(xρy ∧ yρx ⇒ x = y)
(T) tranzitivnost (∀x, y, z ∈ A)(xρy ∧ yρz ⇒ xρz)
Relacija ekvivalencije je svaka relacija koja ima osobine R, S, T . Ona deli skup
na disjunktne klase, a elementi jedne klase su svi jedni s drugim u relaciji. Oznaka
za relaciju ekvivalencije je ∼ (tilda), a za klasu ekvivalencije: Cx = {y| x ∼ y}.
Relacija poretka je svaka relacija koja se odlikuje osobinama R, AS, T .
Funkcija (preslikavanje) skupa A u skup B, A
f
−→ B, je podskup f Dekartovog
proizvoda A×B, koji se odlikuje osobinama: svakom elementu a skupa A odgovara
taˇcno jedna ured-ena dvojka (a, b), b ∈ B, takva da (a, b) ∈ f, sl. 9. Koriste se
oznaˇcavanja: f =
m
1
n
5
p
5

i f = {(m, 1), (n, 5), (p, 5)}. Skup A je domen, a skup
B je kodomen funkcije f.
Sl. 9 Sl. 10
Elemenat a ∈ A je original (lik), a elemenat b ∈ B je slika. ˇCinjenicu da je
(a, b) ∈ f oznaˇcavamo sa f(a) = b. Skup slika oznaˇcavamo sa f(A).
Ako je f(A) = B, tada je f preslikavanje skupa A na skup B (sirjekcija), sl. 10.
Ako vaˇzi implikacija: a1 = a2 ⇒ f(a1) = f(a2), tada je f preslikavanje jedanjedan,
odnosno 1-1 (injekcija), sl. 11.
Sl. 11 Sl. 12
Ako je f preslikavanje na i jedan-jedan, sl. 12, onda je to bijekcija i postoji inverzno
(obratno) preslikavanje skupa B na skup A. To oznaˇcavamo sa B = f−1(A).
2.1. Operacije sa skupovima 23
Ako je f(A) = B i g(B) = C, tada se skup A preslikava na skup C kompozicijom
preslikavanja: g ◦ f(A) = C (ˇcita se: ”gof od A jednako C”). Vaˇzi zakon
asocijativnosti: h ◦ (g ◦ f) = (h ◦ g) ◦ f.
Svako preslikavanje skupa A×A u skup A naziva se binarna operacija. Dakle,
ako za svaki x, y ∈ A postoji z ∈ A, tako da (x, y) −∗→ z, kaˇzemo da je z rezultat
primene operacije ∗ redom na x i y. Piˇsemo: x ∗ y = z.
Operacija je komutativna ako za ∀x, y ∈ A vaˇzi: x ∗ y = y ∗ x.
Operacija je asocijativna ako za ∀x, y ∈ A vaˇzi: x ∗ (y ∗ z) = (x ∗ y) ∗ z.
Ako postoji e ∈ A, tako da za ∀x ∈ A, vaˇzi: e∗x = x∗e = x, tada je e jediniˇcni
element (jedinica) operacije ∗.
Ako za ∀x ∈ A postoji y ∈ A, tako da je x ∗ y = y ∗ x = e, tada je y inverzni
elemenat (obrat ) eementa x u odnosu na jedinicu e. Inverzni elemenat oznaˇcavamo
i sa x−1.
Skup snabdeven operacijom ˇcini algebarsku strukturu, na primer: (A, ∗)
Algebarska struktura (A, ∗) je grupa, ako se operacija ∗ odlikuje osobinama:
1◦ Asocijativna je, tj. vaˇzi jednakost: x ∗ (y ∗ z) = (x ∗ y) ∗ z, za bilo koju trojku
elemenata x, y, z ∈ A.
2◦ U skupu A postoji jediniˇcni elemenat e, tj. za svaki elemenat x ∈ A vaˇze
jednakosti: e ∗ x = x ∗ e = x.
3◦ Za svaki elemenat x ∈ A postoji obrat x−1 ∈ A, tj. za svaki elemenat x ∈ A
moˇze se na´ci elemenat x−1 ∈ A, takav da vaˇze jednakosti: x∗x−1 = x−1∗x = e.
Ako je ∗ joˇs i komutativna operacija, onda se (A, ∗) naziva komutativna (Abelova)
grupa.
Algebarska struktura (R,+, ·) je polje realnih brojeva jer se odlikuje osobinama:
1◦ a + b = b + a (komutativnost sabiranja)
2◦ a + (b + c) = (a + b) + c (asocijativnost sabiranja)
3◦ a + 0 = 0 + a = a (0 je neutralni (jediniˇcni) elemenat sabiranja)
4◦ a + (−a) = (−a) + a = 0 (postojanje suprotnog (inverznog) elementa za
sabiranje)
5◦ a · b = b · a (komutativnost mnoˇzenja)
6◦ a · (b · c) = (a · b) · c (asocijativnost mnoˇzenja)
7◦ 1 · a = a · 1 = a (postoji jediniˇcni elemenat za mnoˇzenje)
8◦ a · a−1 = a−1 · a = 1, a = 0 (postojanje inverznog elementa za mnoˇzenje)
9◦ a · (b+c) = a · b+a · c (distributivnost mnoˇzenja u odnosu na sabiranje), gde
su a, b, c, (−a), a−1, 1 i 0 realni brojevi, a R skup svih realnih brojeva.