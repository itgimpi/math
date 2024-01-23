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

$\lor$, $\land$, $\lnot$, $\implies$, $\iff$, $\oplus$, ... su **logički operatori**. $\rightarrow$ $\leftrightarrow$

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
1) Iskazu p ⇒ q odgovaraju slede´ce reˇcenice:
• p povlaˇci q
• Iz p sledi q
• Ako p, onda q
• q, ako p
• p je dovoljan uslov za q
• q je potreban uslov za p.
2) Iskazu p ⇔ q odgovaraju reˇcenice:
• p povlaˇci q i q povlaˇci p
• p je ekvivalentno sa q
• Iz p sledi q i iz q sledi p
1)Umesto ako i samo ako ˇcesto se skra´ceno piˇse akko.
8 PRVA GLAVA
• q ako p i p ako q
• p ako i samo ako q
• p je potreban i dovoljan uslov za q.
Ako su p i q iskazi, onda su iskazi takod-e ¬p, ¬q, p ∧ q, p ∨ q, p ⇒ q, p ⇔ q.
Tautologija je iskaz t koji je uvek taˇcan, nezavisno od istinitosnih vrednosti
iskaza p, q, . . . , r, koji obrazuju t.
Tautologije su zakoni logiˇckog zakljuˇcivanja i ˇcesto se zapisuju kao:
p, q
r
, ˇsto
znaˇci (p∧q) ⇒ r, ili na primer:
p ⇒ q, q ⇒ r
p ⇒ r
, ˇsto znaˇci (p ⇒ q)∧(q ⇒ r) ⇒ (p ⇒ r).
De Morganovi zakoni za konjunkciju i disjunkciju: ¬(p ∧ q) ⇔ (¬p ∨ ¬q) i
¬(p ∨ q) ⇔ (¬p ∧ q).
Kvantori:
1◦ Univerzalni kvantor je ∀ – ˇcita se: svaki, bilo koji, proizvoljan. (Na primer:
(∀x)t, ˇcita se: ”Za svaki x vredi t”).
2◦ Egzistencijalni kvantor je ∃ – ˇcita se: postoji, neki, ima bar jedan. (Na
primer: (∃x)t, znaˇci: ”Za neki x vredi t”).
3◦ Koristimo i kvantor ∃1 – ˇcita se: postoji taˇcno jedan, ili postoji jedan i samo
jedan.
Negacije kvantora su: ¬(∀x)A ⇔ (∃x)¬A i ¬(∃x)A ⇔ (∀x)¬A.
Elementi iskazne algebre
U reˇsavanju logiˇckih zadataka koristi se i izvesna analogija disjunkcije sa
sabiranjem brojeva i analogija konjunkcije sa mnoˇzenjem brojeva, kao i distributivnost
konjunkcije prema disjunkciji (analogno distributivnosti mnoˇzenja u odnosu
na sabiranje brojeva). U iskaznoj algebri (Bulovoj algebri iskaza) koristimo tablice:
disjunkcija
A B A + B
1 1 1
1 0 1
0 1 1
0 0 0
konjunkcija
A B A · B
1 1 1
1 0 0
0 1 0
0 0 0
negacija
A A
1 0
0 1
Za disjunkciju koristimo znak +, za konjukciju znak · i za negaciju nadvuˇcenu
crtu. Za istinitosnu vrednost iskaza ”taˇcan” oznaka je 1, a za ”netaˇcan” oznaka
je 0. Tablica konjunkcije potpuno je identiˇcna obiˇcnoj tablici mnoˇzenja, a tablica
disjunkcije razlikuje se od obiˇcne tablice sabiranja samo u sluˇcaju: 1 + 1 = 1. (Kod
obiˇcnog sabiranja je 1 + 1 = 2)