### 10. Dati su iskazi 

$p \equiv \left(\frac{1}{2}-\frac{1}{3}\right) \div \left(\frac{1}{4}-\frac{1}{5}\right) = \frac{10}{3}$; 

$q \equiv \frac{1}{2}-\frac{1}{3} \div \left(\frac{1}{4}-\frac{1}{5}\right) = -\frac{37}{6}$; 

$r \equiv (\frac{1}{2}-\frac{1}{3}) \div \frac{1}{4}-\frac{1}{5} = 7$; 

$s \equiv \frac{1}{2}-\frac{1}{3} \div \frac{1}{4}-\frac{1}{5} = \frac{2}{5}$;

Odredi njihovu tačnost, na osnovu nje odredi ostinitosnu vrednost iskaza:

a) $(p \land q) \lor (r \land s)$

b) $(p \lor q) \lor (p \land s)$

c) $((p \lor r) \lor q)\land (s \land r)$

d) $((p \lor r) \land q) \land (s \land r)$

e) $(q \land (r \land (s \land p))) \lor ((p \land q) \lor (q \land s))$

### Rešenje

$p \equiv (\frac{1}{2}^3-\frac{1}{3}^2) \div (\frac{1}{4}^5-\frac{1}{5}^4) = (\frac{3}{6}-\frac{2}{6}) \div (\frac{5}{20}-\frac{4}{20}) = \frac{1}{6} \div \frac{1}{20} = \frac{1}{6} \cdot \frac{20}{1} =  \frac{10}{3}$  

$p = \top$;

$q \equiv \frac{1}{2}-\frac{1}{3} \div (\frac{1}{4}-\frac{1}{5}) = \frac{1}{2}-\frac{1}{3} \div \frac{1}{20} = \frac{1}{2}-\frac{1}{3} \cdot \frac{20}{1} = \frac{1}{2}^3-\frac{20}{3}^2 = \frac{3}{6}-\frac{40}{6} = -\frac{37}{6}$

$q = \top$;

$r \equiv (\frac{1}{2}-\frac{1}{3}) \div \frac{1}{4}-\frac{1}{5} = \frac{1}{6} \div \frac{1}{4}-\frac{1}{5} = \frac{1}{6} \cdot \frac{4}{1}-\frac{1}{5} = \frac{2}{3}^5-\frac{1}{5}^3 = \frac{10}{15}-\frac{3}{15} = \frac{7}{15} \neq 7$; 

$r = \bot$;

$s \equiv \frac{1}{2}-\frac{1}{3} \div \frac{1}{4}-\frac{1}{5} = \frac{1}{2}-\frac{1}{3} \cdot \frac{4}{1}-\frac{1}{5} = \frac{1}{2}^{15}-\frac{4}{3}^{10} -\frac{1}{5}^6 = \frac{15}{30}-\frac{40}{30} -\frac{6}{30}=-\frac{31}{30} \neq \frac{2}{5}$;

$s = \bot$;

$p = q = \top, r = s = \bot$

a) $(p \land q) \lor (r \land s) = (\top \land \top) \lor (\bot \land \bot) = \top \lor \bot = \top$

b) $(p \lor q) \lor (p \land s) = (\top \lor \top) \lor (\top \land \bot)=\top \lor \bot = \top$

c) $((p \lor r) \lor q)\land (s \land r) = ((\top \lor \bot) \lor \top)\land (\bot \land \bot)= (\top \lor \top)\land \bot= \top \land \bot = \bot$

d) $((p \lor r) \land q) \land (s \land r) = ((\top \lor \bot) \land \top) \land (\bot \land \bot)= (\top \land \top) \land \bot = \top \land \bot = \bot$

e) $(q \land (r \land (s \land p))) \lor ((p \land q) \lor (q \land s)) = (\top \land (\bot \land (\bot \land \top))) \lor ((\top \land \top) \lor (\top \land \bot)) = (\top \land (\bot \land \bot)) \lor (\top \lor \bot) = (\top \land \bot) \lor (\top \lor \bot)= \bot \lor \top= \top$