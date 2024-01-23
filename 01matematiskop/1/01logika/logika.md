# 1. LOGIKA

*Iskaz* je rečenica koja može biti samo *tačna* ili samo *netačna*.

*Logičke konstante* su $\top$ i $\top$ (te i nete) - tačno i netačno.

*Istinitosna vrednost* iskaza p označava se sa $\tau(p)$. Moguće je $\tau(p) = \top$ ili
$\tau(p) = \bot$.

*Negacija iskaza* p je iskaz koji je tačan ako i samo ako (akko) je netačan iskaz p. Koristimo oznaku $\lnot p$ ili $\overline{p}$. (Čitamo: nije p).

*Konjunkcija* iskaza p i q je iskaz koji je tačan akko su tačna oba iskaza p i q. Oznaka je $p \land q$. (Čitamo: p i q.).

*Disjunkcija* iskaza p i q je iskaz koji je netačan akko su netačna oba iskaza p i q. Oznaka je $p \lor q$. (Čitamo: p ili q).

*Implikacija* iskaza p i q je iskaz koji je netačan akko je iskaz p tačan, a iskaz q netačan. Oznaka je $p \implies q$ ili $p \rightarrow q$. (Ako p, onda q).

*Ekvivalencija* iskaza p i q je iskaz koji je tačan ako i samo ako p i q imaju jednake istinitosne vrednosti. Oznaka je $p \iff q$ ili $p \leftrightarrow q$. (p ekvivalentno sa q).

$\lor$, $\land$, $\lnot$, $\implies$, $\iff$, $\oplus$, ... su **logički operatori**. 

Ovo su osnovne logičke operacije i njima odgovaraju sledeće istinitosne tablice

negacija

| $p$ |$\lnot p$ |
| :-: | :-: |
| $\top$ | $\bot$ |
| $\bot$ | $\top$ |

konjunkcija

| $\land$ | $\top$ | $\bot$ |
| :-: | :-: | :-: |
| $\top$ | $\top$ | $\bot$ |
| $\bot$ | $\bot$ | $\bot$ |

disjunkcija

| $\lor$ | $\top$ | $\bot$ |
| :-: | :-: | :-: |
| $\top$ | $\top$ | $\top$ |
| $\bot$ | $\top$ | $\bot$ |

implikacija

| $\rightarrow$ | $\top$ | $\bot$ |
| :-: | :-: | :-: |
| $\top$ | $\top$ | $\bot$ |
| $\bot$ | $\top$ | $\top$ |

ekvivalencija

| $\rightarrow$ | $\top$ | $\bot$ |
| :-: | :-: | :-: |
| $\top$ | $\top$ | $\bot$ |
| $\bot$ | $\bot$ | $\top$ |



Potreban i dovoljan uslov.

1) Iskazu $p \rightarrow q$ odgovaraju sledeće rečenice:
* p povlači q
* Iz p sledi q
* Ako p, onda q
* q, ako p
* p je dovoljan uslov za q
* q je potreban uslov za p.

2) Iskazu $p \leftrightarrow q$ odgovaraju rečenice:
* p povlači q i q povlači p
* p je ekvivalentno sa q
* Iz p sledi q i iz q sledi p
* q ako p i p ako q
* p ako i samo ako q
* p je potreban i dovoljan uslov za q.

Ako su p i q iskazi, onda su iskazi takođe $\lnot p$, $\lnot q$, $p \land q$, $p \lor q$, $p \rightarrow q$, $p \leftrightarrow q$.

*Tautologija* je iskaz t koji je uvek tačan, nezavisno od istinitosnih vrednosti iskaza p, q, ..., r, koji obrazuju t.

Tautologije su zakoni logičkog zaključivanja i često se zapisuju kao: $\displaystyle \frac{p, q}{r}$, što znači $(p \land q) \rightarrow r$, ili na primer: $\displaystyle \frac{p \rightarrow q, q \rightarrow p}{p \rightarrow q}$, što znači $(p \rightarrow q)∧(q \rightarrow r) ⇒ (p \rightarrow r)$.

De Morganovi zakoni za konjunkciju i disjunkciju: 

$\lnot (p \land q) \leftrightarrow (\lnot p \lor \lnot q)$ i $\lnot (p \lor q) \leftrightarrow (\lnot p \land \lnot q)$

Kvantori:

1. Univerzalni kvantor je $\forall$ – čita se: svaki, bilo koji, proizvoljan. (Na primer: $(\forall x)t$, čita se: Za svaki x vredi t).

2. Egzistencijalni kvantor je $\exists$ – čita se: postoji, neki, ima bar jedan. (Na primer: $(\exists x)t$, znači: Za neki x vredi t).

3. Koristimo i kvantor $\exists_1$ – čita se: postoji tačno jedan, ili postoji jedan i samo jedan.

Negacije kvantora su: $\lnot(\forall x) A ⇔ (\exists x) \lnot A$ i $\lnot(\exists x) A ⇔ (\forall x) \lnot A$.

Elementi iskazne algebre

U rešavanju logičkih zadataka koristi se i izvesna analogija disjunkcije sa sabiranjem brojeva i analogija konjunkcije sa množenjem brojeva, kao i distributivnost konjunkcije prema disjunkciji (analogno distributivnosti množenja u odnosu
na sabiranje brojeva). U iskaznoj algebri (Bulovoj algebri iskaza) koristimo tablice:

disjunkcija

| $A$ | $B$ | $A+B$ |
| :-: | :-: | :-: |
| 1 | 1 | 1 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 0 |

konjunkcija

| $A$ | $B$ | $A \cdot B$ |
| :-: | :-: | :-: |
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 0 |
| 0 | 0 | 0 |

negacija



| $A$ | $\overline{A}$ |
| :-: | :-: |
| 1 | 0 |
| 0 | 1 |


Za disjunkciju koristimo znak $+$, za konjukciju znak $\cdot$ i za negaciju nadvučenu crtu. Za istinitosnu vrednost iskaza tačan oznaka je 1, a za netačan oznaka je 0. Tablica konjunkcije potpuno je identična običnoj tablici množenja, a tablica disjunkcije razlikuje se od obične tablice sabiranja samo u slučaju: 1 + 1 = 1. (Kod
običnog sabiranja je 1 + 1 = 2)