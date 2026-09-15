# Banque de questions validées — Chapitre 06
# Oxydoréduction, piles et électrolyse
# Slug : oxydo-reduction

_Projet-Balmer / Balmer-Cloud — Généré le 2026-09-14_
_En cours de rédaction — voir `matrice-concepts-oxydo-reduction.md` pour la cible complète (88 questions obligatoires minimum sur 17 concepts)_

---

<!-- LÉGENDE
Niveau R1 : macro = macroscopique | parti = particulaire | symbo = symbolique
Type      : 1 = identification | 2 = application directe | 3 = transfert
Statut    : validated | to_fix
-->

---

<!-- ============================================================ -->
<!-- CONCEPT : degre-oxydation — Degré d'oxydation                -->
<!-- 7 questions obligatoires : macro·T1, parti·T1, parti·T2,     -->
<!-- symbo·T2×2 (●², misconception confusion-charge-reelle),      -->
<!-- symbo·T3×2 (●², misconception moyenne-atomes-non-equivalents)-->
<!-- ============================================================ -->

---
id: q-degre-oxydation-macro-t1-001
concept: degre-oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Le degré d'oxydation du chlore dans l'hypochlorite de sodium ($\ce{NaClO}$, principe actif de l'eau de Javel) vaut +1. En quoi cela explique-t-il le pouvoir décolorant et désinfectant de l'eau de Javel ?

**Options**
- A. Un d.o. de +1 est un état intermédiaire entre −1 (l'état le plus courant du chlore) et des états plus oxydés — le chlore peut donc être réduit, ce qui en fait une substance oxydante capable d'arracher des électrons aux pigments et aux micro-organismes
- B. Un d.o. de +1 signifie que le chlore porte une charge réelle positive, ce qui lui permet d'attirer électrostatiquement les pigments et de les neutraliser
- C. Un d.o. de +1 indique que le chlore est dans son état le plus stable, ce qui le rend chimiquement inerte et donc sans danger à manipuler
- D. Un d.o. de +1 est identique au d.o. de l'hydrogène — le chlore se comporte donc comme un réducteur, cédant facilement un électron

**Réponse correcte** : A

**Feedback correct**
Exactement — d.o.(Cl) = +1 dans $\ce{NaClO}$ est un état intermédiaire entre −1 (le plus courant) et des états plus oxydés (+3, +5, +7). Le chlore peut donc gagner des électrons (être réduit) en redescendant vers −1 : c'est une substance demandeuse d'électrons (oxydante), capable de dégrader les pigments et les structures cellulaires des micro-organismes.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le d.o. est une charge fictive, pas une charge réelle — les confondre est une erreur classique. Ce n'est pas une attraction électrostatique qui explique le pouvoir oxydant, mais la capacité du chlore à accepter des électrons.
- Si C : Un d.o. de +1 n'est pas l'état le plus stable du chlore (c'est −1, l'ion chlorure) — c'est justement parce que ce n'est pas l'état stable que le chlore « cherche » à redescendre vers −1 en captant des électrons, ce qui le rend réactif et oxydant, pas inerte.
- Si D : Le d.o. de l'hydrogène est +1 dans la plupart des composés, mais cela ne fait pas du chlore un réducteur — un d.o. positif signifie au contraire que l'atome a fictivement perdu des électrons et peut en regagner (être réduit), comportement typique d'un oxydant.

**Référence manuel** : oxydo-reduction-degre-oxydation

---
id: q-degre-oxydation-parti-t1-001
concept: degre-oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
À l'échelle particulaire, comment attribue-t-on fictivement les électrons d'une liaison pour calculer le degré d'oxydation des deux atomes liés ?

**Options**
- A. Tous les électrons de la liaison sont attribués fictivement à l'atome le plus électronégatif ; si les deux atomes sont identiques, la liaison ne contribue à aucun des deux
- B. Les électrons de la liaison sont répartis à parts égales entre les deux atomes, quelle que soit leur électronégativité
- C. Tous les électrons de la liaison sont attribués fictivement à l'atome le moins électronégatif, qui les retient plus fortement
- D. Les électrons de la liaison restent partagés réellement entre les deux atomes ; le degré d'oxydation ne concerne que les électrons non liants

**Réponse correcte** : A

**Feedback correct**
C'est la convention du degré d'oxydation : on attribue fictivement tous les électrons d'une liaison à l'atome le plus électronégatif, comme si la liaison était totalement ionique. Si les deux atomes liés sont identiques (même électronégativité), aucun n'est favorisé — la liaison ne contribue au d.o. d'aucun des deux (cas des corps simples, d.o. = 0).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est la répartition réelle approximative d'une liaison covalente pure entre atomes identiques, mais ce n'est pas la convention du d.o. — celui-ci exagère volontairement la polarité en l'assimilant à une liaison 100 % ionique.
- Si C : C'est l'inverse de la convention réelle — c'est l'atome le plus électronégatif, pas le moins, qui « prend » fictivement tous les électrons de la liaison.
- Si D : Le d.o. porte justement sur les électrons de liaison (attribués fictivement à un seul atome), pas sur les électrons non liants — c'est l'inverse de la définition.

**Référence manuel** : oxydo-reduction-degre-oxydation

---
id: q-degre-oxydation-parti-t2-001
concept: degre-oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans la molécule $\ce{SO2}$, l'oxygène est plus électronégatif que le soufre et chaque atome d'oxygène forme une liaison double avec le soufre central. En raisonnant liaison par liaison (sans utiliser les règles pratiques), quel est le degré d'oxydation du soufre ?

**Options**
- A. +4, car le soufre perd fictivement 2 électrons pour chacune des deux doubles liaisons S=O
- B. −4, car le soufre est entouré de deux atomes plus électronégatifs qui lui cèdent leurs électrons
- C. +2, car le soufre ne perd fictivement qu'un électron par liaison double, comme dans une liaison simple
- D. 0, car le soufre est un non-métal comme l'oxygène, la liaison ne contribue donc à aucun des deux

**Réponse correcte** : A

**Feedback correct**
L'oxygène étant plus électronégatif, il « prend » fictivement tous les électrons de chaque liaison S=O. Une liaison double correspond à 2 électrons fictivement perdus par le soufre (et gagnés par l'oxygène correspondant). Avec deux doubles liaisons, le soufre perd fictivement 2 + 2 = 4 électrons, donc d.o.(S) = +4.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse : c'est l'atome le plus électronégatif (l'oxygène) qui gagne fictivement des électrons, pas le soufre — le soufre, moins électronégatif, en perd.
- Si C : Une liaison double compte pour 2 électrons perdus, pas 1 — chaque liaison (simple ou double) contribue selon son nombre réel d'électrons partagés, pas selon un forfait par liaison.
- Si D : Le soufre et l'oxygène sont bien deux non-métaux, mais ils n'ont pas la même électronégativité (l'oxygène est plus électronégatif) — la règle « la liaison ne contribue pas » ne s'applique qu'entre atomes identiques (même électronégativité), pas entre deux non-métaux différents.

**Référence manuel** : oxydo-reduction-degre-oxydation

---
id: q-degre-oxydation-symbo-t2-001
concept: degre-oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
misconception: degre-oxydation--confusion-charge-reelle
date_validation: 2026-09-14
statut: validated
---

**Question**
Quel est le degré d'oxydation du soufre dans l'ion sulfate $\ce{SO4^{2-}}$ ?

**Options**
- A. +6 — obtenu par la règle 5 (somme des d.o. = charge de l'ion) avec O = −2 (règle 2) : d.o.(S) + 4×(−2) = −2
- B. −2 — car c'est la charge globale de l'ion, qui doit s'appliquer au soufre puisqu'il en est l'atome central
- C. +2 — car le soufre a formé quatre liaisons avec l'oxygène, une charge −2 par liaison rapportée à ses deux électrons de valence disponibles
- D. −6 — car le soufre, moins électronégatif que l'oxygène, doit avoir un d.o. négatif dans ce composé

**Réponse correcte** : A

**Feedback correct**
Avec O = −2 (règle 2) et la somme des d.o. égale à la charge de l'ion (règle 5, ici −2) : d.o.(S) + 4×(−2) = −2, donc d.o.(S) = −2 + 8 = +6.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est une confusion fréquente et bien documentée entre le degré d'oxydation (une charge fictive, répartie atome par atome selon les règles) et la charge réelle de l'ion (une propriété globale de l'ensemble $\ce{SO4^{2-}}$). La charge −2 de l'ion n'est pas « portée » par un seul atome — elle résulte de la somme des d.o. de tous les atomes (règle 5), et le soufre a lui-même un d.o. bien différent (+6) de la charge de l'ion.
- Si C : Le raisonnement en « charge par liaison rapportée aux électrons de valence » n'est pas la méthode du d.o. — on applique les règles pratiques (ici la règle 5) sur l'ensemble du groupe, pas un décompte liaison par liaison des électrons de valence disponibles.
- Si D : Le d.o. d'un atome moins électronégatif dans un groupe n'est pas nécessairement négatif — il dépend du bilan de toutes ses liaisons. Ici, entouré de quatre oxygènes très électronégatifs, le soufre perd fictivement des électrons pour chacune, d'où un d.o. positif élevé (+6).

**Référence manuel** : oxydo-reduction-degre-oxydation

---
id: q-degre-oxydation-symbo-t2-002
concept: degre-oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
misconception: degre-oxydation--confusion-charge-reelle
date_validation: 2026-09-14
statut: validated
---

**Question**
Quel est le degré d'oxydation de l'azote dans l'ion nitrate $\ce{NO3^{-}}$ ?

**Options**
- A. +5 — obtenu par la règle 5 (somme des d.o. = charge de l'ion) avec O = −2 (règle 2) : d.o.(N) + 3×(−2) = −1
- B. −1 — car c'est la charge globale de l'ion, directement attribuée à l'azote qui en est l'atome central
- C. +3 — car l'azote forme trois liaisons avec l'oxygène, une charge +1 par liaison
- D. −5 — car l'azote, moins électronégatif que l'oxygène, prend nécessairement un d.o. négatif dans ce composé

**Réponse correcte** : A

**Feedback correct**
Avec O = −2 (règle 2) et la somme des d.o. égale à la charge de l'ion (règle 5, ici −1) : d.o.(N) + 3×(−2) = −1, donc d.o.(N) = −1 + 6 = +5.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Même confusion que pour $\ce{SO4^{2-}}$ : la charge −1 de l'ion nitrate est une propriété de l'ensemble de l'ion (résultat de la règle 5 appliquée à tous les atomes), pas une valeur directement transférable à l'azote seul. L'azote a ici un d.o. de +5, très différent de la charge −1 de l'ion.
- Si C : Le d.o. ne se calcule pas comme un forfait « +1 par liaison » — il faut appliquer les règles pratiques (ici la règle 5, somme des d.o. = charge de l'ion) sur l'ensemble du groupe.
- Si D : Comme pour le soufre dans $\ce{SO4^{2-}}$, être moins électronégatif que l'oxygène qui l'entoure donne à l'azote un d.o. positif élevé (+5), pas négatif — chaque liaison avec un oxygène plus électronégatif lui fait fictivement perdre des électrons.

**Référence manuel** : oxydo-reduction-degre-oxydation

---
id: q-degre-oxydation-symbo-t3-001
concept: degre-oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
misconception: degre-oxydation--moyenne-atomes-non-equivalents
date_validation: 2026-09-14
statut: validated
---

**Question**
L'ion thiosulfate $\ce{S2O3^{2-}}$ contient deux atomes de soufre qui n'occupent pas le même environnement chimique (un soufre central lié à trois oxygènes, un soufre terminal lié uniquement au premier soufre). En appliquant la règle 5 (somme des d.o. = charge de l'ion) à partir de la seule formule brute, quel degré d'oxydation obtient-on pour le soufre — et que représente cette valeur ?

**Options**
- A. +2 — mais c'est une moyenne : les deux atomes de soufre ont en réalité des d.o. différents (structure réelle : environ +5 pour le soufre central, −1 pour le soufre terminal), que la formule brute seule ne permet pas de distinguer
- B. +2, qui est bien le d.o. réel identique de chacun des deux atomes de soufre, puisqu'ils appartiennent au même élément
- C. −2, obtenu en répartissant directement la charge de l'ion entre les deux atomes de soufre
- D. Impossible à calculer sans connaître la structure développée — la règle 5 ne s'applique pas à un ion contenant deux atomes identiques

**Réponse correcte** : A

**Feedback correct**
Avec O = −2 (règle 2) : 2×d.o.(S) + 3×(−2) = −2, donc d.o.(S) = +2 en moyenne. Mais les deux atomes de soufre du thiosulfate n'ont pas le même environnement (l'un est entouré d'oxygènes comme dans un sulfate, l'autre est lié uniquement à l'autre soufre) — leurs d.o. réels diffèrent (+5 et −1 typiquement), et +2 n'est que leur moyenne arithmétique, pas la valeur individuelle de chacun.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est exactement l'erreur documentée dans la littérature : croire qu'une formule brute donne le d.o. réel de chaque atome identique, alors qu'elle ne donne qu'une moyenne quand ces atomes occupent des environnements différents (comme le glucose et l'acide stéarique déjà vus, où le d.o. moyen n'est même pas entier). Ici, la valeur moyenne +2 est entière, ce qui peut faussement rassurer sur son exactitude atome par atome.
- Si C : La charge de l'ion (−2) n'est pas répartie directement sur un seul type d'atome — la règle 5 fait intervenir tous les atomes de la formule (ici aussi les trois oxygènes à −2 chacun), pas seulement le soufre.
- Si D : La règle 5 s'applique très bien à partir de la formule brute, même avec des atomes identiques — elle donne cependant une moyenne, pas le détail par atome, qui nécessiterait effectivement la structure développée.

**Référence manuel** : oxydo-reduction-degre-oxydation

---
id: q-degre-oxydation-symbo-t3-002
concept: degre-oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
misconception: degre-oxydation--moyenne-atomes-non-equivalents
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans l'acide acétique ($\ce{CH3COOH}$, formule brute $\ce{C2H4O2}$), les deux atomes de carbone occupent des environnements très différents (l'un est lié à deux oxygènes dans le groupe $\ce{-COOH}$, l'autre n'est lié qu'à des hydrogènes et à l'autre carbone dans le groupe $\ce{-CH3}$). Que donne le calcul du d.o. du carbone à partir de la seule formule brute, et comment l'interpréter ?

**Options**
- A. 0 en moyenne (règle 5) — mais les deux carbones ont des d.o. réels différents (+3 pour le carbone du groupe −COOH, −3 pour celui du groupe −CH3), qui se compensent exactement
- B. 0, qui est le d.o. réel de chacun des deux atomes de carbone, puisque la molécule est globalement neutre
- C. +2, en répartissant la contribution des deux oxygènes uniquement sur le carbone qui leur est directement lié
- D. La règle 5 échoue ici car les deux carbones ne sont pas équivalents — il faut une méthode différente pour une molécule organique

**Réponse correcte** : A

**Feedback correct**
Avec H = +1 (×4 = +4) et O = −2 (×2 = −4), et la molécule neutre : 2×d.o.(C) + 4 − 4 = 0, donc d.o.(C) = 0 en moyenne. Comme pour le thiosulfate, cette moyenne masque deux valeurs réelles différentes : le carbone du groupe $\ce{-COOH}$ (lié à deux oxygènes très électronégatifs) a un d.o. de +3, tandis que celui du groupe $\ce{-CH3}$ (lié uniquement à des hydrogènes moins électronégatifs) a un d.o. de −3 — leur somme donne bien 0, la moyenne calculée.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Même erreur que pour le thiosulfate : une moyenne nulle ne signifie pas que chaque atome a individuellement un d.o. nul — ici, aucun des deux carbones n'a réellement un d.o. de 0 ; ils sont respectivement à +3 et −3.
- Si C : La règle 5 s'applique à la somme de tous les atomes de la formule, pas à une répartition ad hoc de certains atomes vers d'autres — ce raisonnement ne correspond à aucune des cinq règles pratiques.
- Si D : La règle 5 fonctionne parfaitement à partir de la formule brute, y compris pour des molécules organiques — elle donne toujours une moyenne quand plusieurs atomes identiques ont des environnements différents, ce qui n'est pas un échec de la méthode mais une limite inhérente à l'information contenue dans une formule brute.

**Référence manuel** : oxydo-reduction-degre-oxydation

---
<!-- ============================================================ -->
<!-- CONCEPT : oxydation — Oxydation                              -->
<!-- 7 questions obligatoires : macro·T1, parti·T1×2 (●², misc.   -->
<!-- reaction-redox--transfert-electrons-vs-liaison), parti·T2,   -->
<!-- symbo·T2, symbo·T3×2 (●², misc. oxydation--sans-reduction-   -->
<!-- couplee)                                                     -->
<!-- ============================================================ -->

---
id: q-oxydation-macro-t1-001
concept: oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Lorsqu'on plonge une lame de cuivre métallique dans une solution de nitrate d'argent $\ce{AgNO3}$ (aq), la solution prend progressivement une teinte bleutée. Que peut-on en déduire concernant le cuivre ?

**Options**
- A. Le cuivre métallique a subi une oxydation — la teinte bleue signale l'apparition d'ions $\ce{Cu^{2+}}$ en solution, donc une perte d'électrons du cuivre
- B. Le cuivre métallique a subi une réduction — la teinte bleue signale que le cuivre a capté des électrons de la solution
- C. Le cuivre n'a subi aucune transformation chimique — la teinte bleue provient uniquement de l'argent métallique qui se dépose
- D. Le cuivre a subi une oxydation, mais cela ne peut être confirmé qu'en mesurant directement le nombre d'électrons perdus, jamais par une simple observation macroscopique

**Réponse correcte** : A

**Feedback correct**
La teinte bleue caractéristique de la solution est due à l'apparition d'ions $\ce{Cu^{2+}}$ (aq). Pour passer de $\ce{Cu^0}$ (métal) à $\ce{Cu^{2+}}$ (ion), le cuivre a perdu 2 électrons — c'est la définition même d'une oxydation. L'observation macroscopique (couleur) suffit donc ici à conclure qu'une oxydation a eu lieu.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Une réduction est un gain d'électrons, ce qui ferait diminuer le d.o. du cuivre — or $\ce{Cu^{2+}}$ a un d.o. plus élevé (+2) que $\ce{Cu^0}$ (0) : c'est donc bien une oxydation, pas une réduction.
- Si C : La teinte bleue est justement la signature d'une transformation chimique du cuivre (formation de $\ce{Cu^{2+}}$) — ce n'est pas un phénomène sans lien avec le cuivre lui-même.
- Si D : Une observation macroscopique fiable (ici, une couleur caractéristique et bien connue d'un ion) permet bien de conclure qualitativement qu'une oxydation a eu lieu, sans nécessiter une mesure directe du nombre d'électrons — c'est précisément l'intérêt de relier l'échelle macroscopique à l'échelle particulaire.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydation-parti-t1-001
concept: oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
Lors de la réaction entre le zinc métallique $\ce{Zn^0}$ et une solution de sulfate de cuivre $\ce{CuSO4}$ (aq), que se passe-t-il réellement à l'échelle particulaire lorsque le zinc s'oxyde ?

**Options**
- A. Le zinc cède directement 2 électrons au cation $\ce{Cu^{2+}}$, qui les capte — un vrai transfert d'électrons entre $\ce{Zn^0}$ et $\ce{Cu^{2+}}$, sans que l'ion spectateur $\ce{SO4^{2-}}$ n'intervienne dans ce transfert
- B. La liaison ionique entre $\ce{Cu^{2+}}$ et $\ce{SO4^{2-}}$ se rompt, et c'est cette rupture qui « libère » les électrons captés ensuite par le zinc
- C. Le zinc se lie directement à l'ion $\ce{SO4^{2-}}$ pour former $\ce{ZnSO4}$, et c'est cette nouvelle liaison qui explique le changement d'état d'oxydation du zinc
- D. Les électrons passent d'abord par l'ion $\ce{SO4^{2-}}$, qui les redistribue ensuite au cation $\ce{Cu^{2+}}$, avant que le zinc ne soit oxydé

**Réponse correcte** : A

**Feedback correct**
$\ce{SO4^{2-}}$ est un ion spectateur : il ne participe à aucun transfert d'électrons, il assure seulement la neutralité électrique de la solution. Le vrai transfert a lieu directement entre les deux acteurs redox : le zinc cède 2 électrons que le cation $\ce{Cu^{2+}}$ capte directement, sans passer par une rupture ou une formation de liaison avec l'ion spectateur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est une erreur très documentée dans la littérature (57 à 70 % des étudiants selon les études) : imaginer le transfert d'électrons comme une rupture de liaison ionique avec l'ion spectateur, à la manière d'une réaction de précipitation ou d'échange, plutôt qu'un vrai transfert d'électrons entre le réducteur et l'oxydant réels.
- Si C : $\ce{SO4^{2-}}$ reste un ion spectateur tout au long de la réaction — il ne se lie pas au zinc pour « expliquer » l'oxydation. Le changement de d.o. du zinc résulte directement de la perte de 2 électrons au profit du cuivre, pas d'une nouvelle liaison avec le sulfate.
- Si D : Les électrons ne « passent » jamais par un ion spectateur — le transfert est direct entre le réducteur ($\ce{Zn^0}$) et l'oxydant ($\ce{Cu^{2+}}$), sans intermédiaire.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydation-parti-t1-002
concept: oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
Lors de la réaction entre le zinc métallique $\ce{Zn^0}$ et l'acide chlorhydrique $\ce{HCl}$ (aq), le zinc s'oxyde et de l'hydrogène gazeux $\ce{H2}$ se dégage. Que représente réellement cette oxydation à l'échelle particulaire ?

**Options**
- A. Le zinc cède directement 2 électrons aux ions $\ce{H^+}$, qui les captent pour former $\ce{H2}$ — l'ion spectateur $\ce{Cl^-}$ n'intervient dans aucun transfert d'électrons
- B. Le zinc se lie à l'ion $\ce{Cl^-}$ pour former $\ce{ZnCl2}$, et c'est cette nouvelle liaison qui provoque le dégagement de $\ce{H2}$
- C. Les électrons perdus par le zinc transitent d'abord par l'ion $\ce{Cl^-}$, qui les cède ensuite aux ions $\ce{H^+}$
- D. Le zinc capte des électrons de l'ion $\ce{Cl^-}$, ce qui libère indirectement des ions $\ce{H^+}$ sous forme de gaz $\ce{H2}$

**Réponse correcte** : A

**Feedback correct**
L'ion $\ce{Cl^-}$ est spectateur dans cette réaction : il assure seulement l'électroneutralité, sans participer au transfert d'électrons. Le transfert réel a lieu directement entre le zinc (qui cède 2 électrons) et les ions $\ce{H^+}$ (qui les captent, deux par deux, pour former $\ce{H2}$).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{Cl^-}$ reste spectateur — il ne se lie pas au zinc pour expliquer le dégagement de $\ce{H2}$. Ce dégagement résulte directement du transfert d'électrons du zinc vers $\ce{H^+}$, indépendamment de la présence de $\ce{Cl^-}$.
- Si C : Comme pour tout ion spectateur, $\ce{Cl^-}$ ne sert jamais d'intermédiaire dans un transfert d'électrons — le zinc cède ses électrons directement aux ions $\ce{H^+}$.
- Si D : C'est l'inverse du mécanisme réel : c'est le zinc qui cède des électrons (il s'oxyde), pas qui en capte — et ce sont les ions $\ce{H^+}$, pas $\ce{Cl^-}$, qui les captent pour former $\ce{H2}$.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydation-parti-t2-001
concept: oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans la réaction entre le cuivre métallique et une solution de nitrate d'argent ($\ce{Cu^0 + 2AgNO3 (aq) -> Cu(NO3)2 (aq) + 2Ag^0}$), quelle espèce s'oxyde ?

**Options**
- A. Le cuivre $\ce{Cu^0}$, qui passe de l'état $\ce{Cu^0}$ (d.o. = 0) à l'état $\ce{Cu^{2+}}$ (d.o. = +2) en cédant 2 électrons
- B. L'argent $\ce{Ag^+}$, qui passe de l'état $\ce{Ag^+}$ à l'état $\ce{Ag^0}$ en cédant un électron
- C. L'ion nitrate $\ce{NO3^-}$, qui participe activement au transfert d'électrons malgré son rôle apparent de spectateur
- D. Le cuivre $\ce{Cu^0}$, qui capte des électrons pour former $\ce{Cu^{2+}}$

**Réponse correcte** : A

**Feedback correct**
Le cuivre passe de $\ce{Cu^0}$ (d.o. = 0) à $\ce{Cu^{2+}}$ (d.o. = +2) : son d.o. augmente, ce qui signale une perte d'électrons — donc une oxydation. C'est le cuivre qui s'oxyde dans cette réaction, en cédant 2 électrons aux deux ions $\ce{Ag^+}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'argent passe de $\ce{Ag^+}$ à $\ce{Ag^0}$ : son d.o. diminue — c'est une réduction, pas une oxydation. C'est l'argent qui capte des électrons, pas qui en cède.
- Si C : $\ce{NO3^-}$ reste identique des deux côtés de l'équation (spectateur) — il ne participe à aucun transfert d'électrons ici.
- Si D : C'est l'inverse : une oxydation correspond à une perte d'électrons (augmentation du d.o.), pas à un gain. Le cuivre cède des électrons, il ne les capte pas.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydation-symbo-t2-001
concept: oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Quelle est la demi-réaction d'oxydation correcte du zinc métallique lorsqu'il réagit avec une solution de sulfate de cuivre ?

**Options**
- A. $\ce{Zn^0 -> Zn^{2+} + 2e^-}$
- B. $\ce{Zn^0 + 2e^- -> Zn^{2+}}$
- C. $\ce{Zn^{2+} -> Zn^0 + 2e^-}$
- D. $\ce{Zn^0 -> Zn^{2+} - 2e^-}$

**Réponse correcte** : A

**Feedback correct**
Une oxydation est une perte d'électrons : les électrons doivent apparaître du côté des produits, jamais des réactifs. $\ce{Zn^0 -> Zn^{2+} + 2e^-}$ exprime correctement que le zinc perd 2 électrons en passant de l'état $\ce{Zn^0}$ à l'état $\ce{Zn^{2+}}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les électrons sont ici du côté des réactifs, ce qui décrirait un gain d'électrons (une réduction), pas une oxydation.
- Si C : Cette équation part de $\ce{Zn^{2+}}$ pour aboutir à $\ce{Zn^0}$ — c'est la demi-réaction de réduction du zinc (sens inverse), pas son oxydation.
- Si D : Le signe « moins » devant les électrons n'a pas de sens dans une demi-réaction équilibrée — les électrons perdus s'ajoutent du côté des produits avec un signe +, jamais soustraits.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydation-symbo-t3-001
concept: oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
misconception: oxydation--sans-reduction-couplee
date_validation: 2026-09-14
statut: validated
---

**Question**
Un élève propose l'équation suivante comme équation globale complète de la réaction entre le zinc métallique et une solution acide : $\ce{Zn^0 -> Zn^{2+} + 2e^-}$. Que peut-on dire de cette proposition ?

**Options**
- A. Elle est incomplète : une oxydation ne peut jamais survenir seule — les 2 électrons libérés doivent obligatoirement être captés par une réduction couplée (ici, celle des ions $\ce{H^+}$ en $\ce{H2}$), qui doit apparaître dans l'équation globale
- B. Elle est correcte : une demi-réaction d'oxydation suffit à elle seule à décrire complètement une réaction rédox, la réduction étant implicite
- C. Elle est incorrecte, mais seulement parce que le zinc devrait être noté $\ce{Zn(s)}$ plutôt que $\ce{Zn^0}$ — le reste de l'équation est complet
- D. Elle est incomplète, mais uniquement parce qu'il manque les espèces spectatrices (ions $\ce{Cl^-}$) — la partie redox elle-même est déjà complète

**Réponse correcte** : A

**Feedback correct**
Une demi-réaction seule ne peut jamais constituer une équation globale valide : les électrons libérés par une oxydation doivent obligatoirement être captés par une réduction couplée. Ici, il manque la demi-réaction de réduction (par exemple $\ce{2H+ + 2e- -> H2}$) — sans elle, l'équation « perd » des électrons qui ne sont captés nulle part, ce qui est physiquement impossible.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est précisément l'erreur documentée dans la littérature (39,6 % des futurs enseignants interrogés) : croire qu'une oxydation peut se produire indépendamment d'une réduction. Le couplage oxydant/réducteur est obligatoire — une équation globale doit toujours faire apparaître les deux demi-réactions combinées, jamais une seule isolée.
- Si C : La notation de l'état physique n'est pas le problème ici — le problème de fond est qu'aucune réduction couplée n'apparaît dans l'équation, ce qui la rend physiquement incomplète, indépendamment de la notation.
- Si D : Le problème n'est pas l'absence d'espèces spectatrices (qui n'affecte pas la validité de l'équation ionique) mais l'absence de la demi-réaction de réduction elle-même — sans elle, l'équation ne respecte pas la conservation des électrons.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydation-symbo-t3-002
concept: oxydation
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
misconception: oxydation--sans-reduction-couplee
date_validation: 2026-09-14
statut: validated
---

**Question**
Un élève affirme que l'équation $\ce{Cu^0 -> Cu^{2+} + 2e^-}$ décrit à elle seule, de façon complète, la réaction entre le cuivre métallique et une solution de nitrate d'argent. Qu'en pensez-vous ?

**Options**
- A. C'est incomplet : cette seule demi-réaction ne peut pas exister seule — il manque la demi-réaction de réduction couplée ($\ce{2Ag+ + 2e- -> 2Ag^0}$), qui doit être combinée à celle-ci pour former l'équation globale réelle
- B. C'est correct : dans une réaction spontanée, seule la demi-réaction d'oxydation détermine ce qui se passe, la réduction n'ayant pas besoin d'être explicitée
- C. C'est incomplet, mais seulement parce qu'il faudrait préciser l'état physique (aq) des ions — la logique redox de l'équation est déjà correcte et complète
- D. C'est correct dans le cas particulier du cuivre, car il s'agit d'un métal — la règle du couplage obligatoire oxydant/réducteur ne s'applique qu'aux non-métaux

**Réponse correcte** : A

**Feedback correct**
Comme pour toute oxydation, celle du cuivre ne peut pas se produire seule : les 2 électrons cédés doivent être captés par une réduction couplée. Ici, il s'agit de la réduction de deux ions $\ce{Ag^+}$ en deux $\ce{Ag^0}$ ($\ce{2Ag+ + 2e- -> 2Ag^0}$). L'équation globale réelle résulte de la combinaison des deux demi-réactions : $\ce{Cu^0 + 2Ag+ -> Cu^{2+} + 2Ag^0}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Même erreur que pour le zinc : croire qu'une seule demi-réaction (ici l'oxydation) suffit à décrire la réaction complète. Le couplage oxydant/réducteur est toujours obligatoire, quelle que soit la réaction — la réduction doit toujours être explicitée et combinée.
- Si C : Le problème n'est pas une question de notation d'état physique — c'est l'absence totale de la demi-réaction de réduction qui rend cette équation incomplète, quel que soit le soin apporté à la notation.
- Si D : Le couplage obligatoire oxydant/réducteur s'applique à toute réaction rédox, sans exception liée à la nature métal/non-métal des espèces en jeu — le cuivre n'échappe pas à cette règle.

**Référence manuel** : oxydo-reduction-reaction-redox

---

<!-- ============================================================ -->
<!-- CONCEPT : reduction — Réduction (symétrique à oxydation)     -->
<!-- 7 questions obligatoires : macro·T1, parti·T1×2 (●², misc.   -->
<!-- reaction-redox--transfert-electrons-vs-liaison), parti·T2,   -->
<!-- symbo·T2, symbo·T3×2 (●², misc. oxydation--sans-reduction-   -->
<!-- couplee)                                                     -->
<!-- ============================================================ -->

---
id: q-reduction-macro-t1-001
concept: reduction
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Lorsqu'une lame de zinc est plongée dans une solution de sulfate de cuivre $\ce{CuSO4}$ (aq), la couleur bleue de la solution pâlit progressivement et un dépôt rougeâtre apparaît sur le zinc. Que peut-on en déduire concernant le cuivre ?

**Options**
- A. Les ions $\ce{Cu^{2+}}$ ont subi une réduction — ils ont capté des électrons pour former du cuivre métallique $\ce{Cu^0}$, ce qui explique à la fois la décoloration de la solution et le dépôt rougeâtre
- B. Les ions $\ce{Cu^{2+}}$ ont subi une oxydation — ils ont cédé des électrons, ce qui explique le dépôt métallique observé
- C. Aucune transformation du cuivre n'a eu lieu — le dépôt rougeâtre provient uniquement du zinc qui change d'apparence
- D. Les ions $\ce{Cu^{2+}}$ ont subi une réduction, mais cela ne peut être confirmé qu'en mesurant directement le courant électrique généré, jamais par une simple observation de couleur

**Réponse correcte** : A

**Feedback correct**
La disparition progressive de la couleur bleue signale la disparition des ions $\ce{Cu^{2+}}$ en solution, tandis que le dépôt rougeâtre est du cuivre métallique $\ce{Cu^0}$. Passer de $\ce{Cu^{2+}}$ à $\ce{Cu^0}$ correspond à un gain de 2 électrons — c'est une réduction. Les deux observations macroscopiques (décoloration + dépôt) confirment ensemble cette réduction.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Une oxydation correspondrait à une perte d'électrons, donc à une augmentation du d.o. — or $\ce{Cu^{2+}}$ (d.o. +2) devient $\ce{Cu^0}$ (d.o. 0) : le d.o. diminue, ce qui signale une réduction, pas une oxydation.
- Si C : Le dépôt rougeâtre est précisément la signature de la formation de cuivre métallique à partir des ions $\ce{Cu^{2+}}$ — une vraie transformation chimique du cuivre a bien eu lieu.
- Si D : Les observations macroscopiques qualitatives (couleur, dépôt) suffisent ici à conclure de façon fiable qu'une réduction a eu lieu, sans nécessiter une mesure de courant — c'est justement l'intérêt de relier ces trois échelles (macro/particulaire/symbolique).

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reduction-parti-t1-001
concept: reduction
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
Lors de la réaction entre le cuivre métallique et une solution de nitrate d'argent, l'ion $\ce{Ag+}$ est réduit en argent métallique $\ce{Ag^0}$. Que se passe-t-il réellement à l'échelle particulaire lors de cette réduction ?

**Options**
- A. Chaque ion $\ce{Ag+}$ capte directement un électron cédé par le cuivre $\ce{Cu^0}$ — un vrai transfert d'électrons, sans que l'ion spectateur $\ce{NO3^-}$ n'intervienne
- B. La liaison entre $\ce{Ag+}$ et $\ce{NO3^-}$ se rompt, libérant l'ion $\ce{Ag+}$ qui se transforme alors spontanément en $\ce{Ag^0}$ sans transfert d'électrons réel
- C. L'ion $\ce{NO3^-}$ cède d'abord un électron à $\ce{Ag+}$, qui le retransmet ensuite au cuivre
- D. $\ce{Ag+}$ se lie directement au cuivre pour former un composé intermédiaire, qui se décompose ensuite en $\ce{Ag^0}$ et $\ce{Cu^{2+}}$

**Réponse correcte** : A

**Feedback correct**
$\ce{NO3^-}$ est spectateur : il n'intervient dans aucun transfert d'électrons. Le transfert réel a lieu directement entre le cuivre (qui cède des électrons) et les ions $\ce{Ag+}$ (qui les captent directement, un par un) pour former $\ce{Ag^0}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur documentée : imaginer que la réduction résulte d'une rupture de liaison avec l'ion spectateur plutôt que d'un vrai transfert d'électrons depuis le réducteur (ici le cuivre). Sans transfert d'électrons reçu, $\ce{Ag+}$ ne peut pas devenir $\ce{Ag^0}$.
- Si C : $\ce{NO3^-}$ ne cède ni ne transmet jamais d'électrons — il reste spectateur du début à la fin de la réaction.
- Si D : Il n'y a pas de composé intermédiaire Ag-Cu — le transfert d'électrons se fait directement du réducteur à l'oxydant, sans étape de liaison covalente ou ionique entre les deux espèces redox elles-mêmes.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reduction-parti-t1-002
concept: reduction
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
Lors de la réaction entre le zinc métallique et l'acide chlorhydrique, les ions $\ce{H+}$ sont réduits en gaz $\ce{H2}$. Que se passe-t-il réellement à l'échelle particulaire lors de cette réduction ?

**Options**
- A. Chaque paire d'ions $\ce{H+}$ capte directement les 2 électrons cédés par le zinc $\ce{Zn^0}$ — un vrai transfert d'électrons, sans que l'ion spectateur $\ce{Cl^-}$ n'intervienne
- B. La liaison entre $\ce{H+}$ et $\ce{Cl^-}$ se rompt, ce qui libère spontanément $\ce{H2}$ sans qu'un transfert d'électrons réel n'ait lieu
- C. L'ion $\ce{Cl^-}$ capte d'abord les électrons du zinc, puis les retransmet aux ions $\ce{H+}$
- D. $\ce{H+}$ se lie directement au zinc pour former un composé intermédiaire Zn-H, qui se décompose ensuite en $\ce{H2}$ et $\ce{Zn^{2+}}$

**Réponse correcte** : A

**Feedback correct**
$\ce{Cl^-}$ est spectateur : il n'intervient dans aucun transfert d'électrons. Le transfert réel a lieu directement entre le zinc (qui cède 2 électrons) et deux ions $\ce{H+}$ (qui les captent directement) pour former $\ce{H2}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{HCl}$ (aq) existe déjà sous forme d'ions $\ce{H+}$ et $\ce{Cl^-}$ dissociés — il n'y a pas de « liaison H-Cl » à rompre en solution aqueuse, et surtout ce n'est pas cette dissociation qui explique la formation de $\ce{H2}$, mais bien le transfert d'électrons du zinc vers $\ce{H+}$.
- Si C : $\ce{Cl^-}$ ne capte ni ne retransmet jamais d'électrons — il reste spectateur, assurant seulement l'électroneutralité de la solution.
- Si D : Il n'y a pas de composé intermédiaire Zn-H — le transfert d'électrons se fait directement du réducteur (zinc) à l'oxydant ($\ce{H+}$), sans étape de liaison entre les deux espèces redox elles-mêmes.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reduction-parti-t2-001
concept: reduction
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans la réaction entre le zinc métallique et l'acide chlorhydrique ($\ce{Zn^0 + 2HCl (aq) -> ZnCl2 (aq) + H2}$), quelle espèce est réduite ?

**Options**
- A. Les ions $\ce{H+}$, qui passent de l'état $\ce{H+}$ (d.o. = +1) à l'état $\ce{H2}$ (d.o. = 0) en captant des électrons
- B. Le zinc $\ce{Zn^0}$, qui passe de l'état $\ce{Zn^0}$ à l'état $\ce{Zn^{2+}}$ en captant des électrons
- C. L'ion $\ce{Cl^-}$, qui participe activement au transfert d'électrons malgré son rôle apparent de spectateur
- D. Les ions $\ce{H+}$, qui cèdent des électrons pour former $\ce{H2}$

**Réponse correcte** : A

**Feedback correct**
Les ions $\ce{H+}$ passent de d.o. = +1 à d.o. = 0 dans $\ce{H2}$ : leur d.o. diminue, ce qui signale un gain d'électrons — donc une réduction. Ce sont les ions $\ce{H+}$ qui sont réduits, captant les 2 électrons cédés par le zinc.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le zinc passe de $\ce{Zn^0}$ à $\ce{Zn^{2+}}$ : son d.o. augmente — c'est une oxydation, pas une réduction. Le zinc cède des électrons, il ne les capte pas.
- Si C : $\ce{Cl^-}$ reste identique des deux côtés de l'équation (spectateur) — il ne participe à aucun transfert d'électrons ici.
- Si D : C'est l'inverse : une réduction correspond à un gain d'électrons (diminution du d.o.), pas à une perte. Les ions $\ce{H+}$ captent des électrons, ils n'en cèdent pas.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reduction-symbo-t2-001
concept: reduction
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Quelle est la demi-réaction de réduction correcte des ions cuivre(II) lorsqu'une lame de zinc est plongée dans une solution de sulfate de cuivre ?

**Options**
- A. $\ce{Cu^{2+} + 2e^- -> Cu^0}$
- B. $\ce{Cu^{2+} -> Cu^0 + 2e^-}$
- C. $\ce{Cu^0 + 2e^- -> Cu^{2+}}$
- D. $\ce{Cu^{2+} - 2e^- -> Cu^0}$

**Réponse correcte** : A

**Feedback correct**
Une réduction est un gain d'électrons : les électrons doivent apparaître du côté des réactifs. $\ce{Cu^{2+} + 2e^- -> Cu^0}$ exprime correctement que l'ion cuivre(II) capte 2 électrons pour former du cuivre métallique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les électrons sont ici du côté des produits, ce qui décrirait une perte d'électrons (une oxydation), pas une réduction.
- Si C : Cette équation part de $\ce{Cu^0}$ pour aboutir à $\ce{Cu^{2+}}$ en captant des électrons, ce qui est chimiquement incohérent (un atome neutre qui capte des électrons pour former un cation, plutôt que d'en perdre) — ce n'est ni l'oxydation ni la réduction correctes du couple $\ce{Cu^{2+}}$/$\ce{Cu^0}$.
- Si D : Le signe « moins » devant les électrons n'a pas de sens dans une demi-réaction équilibrée — les électrons gagnés s'ajoutent du côté des réactifs avec un signe +, jamais soustraits du côté des produits.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reduction-symbo-t3-001
concept: reduction
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
misconception: oxydation--sans-reduction-couplee
date_validation: 2026-09-14
statut: validated
---

**Question**
Un élève affirme que l'équation $\ce{Cu^{2+} + 2e^- -> Cu^0}$ décrit à elle seule, de façon complète, la réaction entre le zinc métallique et une solution de sulfate de cuivre. Qu'en pensez-vous ?

**Options**
- A. C'est incomplet : une réduction ne peut jamais survenir seule — les 2 électrons captés par $\ce{Cu^{2+}}$ doivent obligatoirement provenir d'une oxydation couplée (ici, celle du zinc $\ce{Zn^0 -> Zn^{2+} + 2e^-}$), qui doit apparaître dans l'équation globale
- B. C'est correct : la demi-réaction de réduction suffit à elle seule à décrire complètement une réaction rédox, l'oxydation étant implicite
- C. C'est incomplet, mais seulement parce qu'il faudrait préciser l'état physique (aq) de l'ion $\ce{Cu^{2+}}$ — le reste de l'équation est complet
- D. C'est correct, car dans une pile ou une réaction spontanée, seule la demi-réaction de réduction détermine si la réaction a lieu

**Réponse correcte** : A

**Feedback correct**
Une demi-réaction seule ne peut jamais constituer une équation globale valide : les électrons captés par une réduction doivent obligatoirement provenir d'une oxydation couplée. Ici, il manque la demi-réaction d'oxydation du zinc ($\ce{Zn^0 -> Zn^{2+} + 2e^-}$) — sans elle, les électrons captés par $\ce{Cu^{2+}}$ n'ont aucune origine, ce qui est physiquement impossible.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est la même erreur, en miroir, que pour l'oxydation seule : croire qu'une seule demi-réaction suffit. Le couplage oxydant/réducteur est toujours obligatoire dans les deux sens — une réduction a toujours besoin d'une oxydation couplée qui lui fournit ses électrons.
- Si C : Le problème n'est pas la notation d'état physique, mais l'absence totale de la demi-réaction d'oxydation, qui rend l'équation physiquement incomplète quelle que soit la notation utilisée.
- Si D : Même dans une réaction spontanée ou une pile, les deux demi-réactions sont toujours nécessaires et couplées — aucune des deux ne « suffit seule » à décrire la réaction, quel que soit le contexte.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reduction-symbo-t3-002
concept: reduction
sous-partie: 6A
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
misconception: oxydation--sans-reduction-couplee
date_validation: 2026-09-14
statut: validated
---

**Question**
Un élève affirme que l'équation $\ce{Ag+ + e^- -> Ag^0}$ décrit à elle seule, de façon complète, la réaction entre le cuivre métallique et une solution de nitrate d'argent. Qu'en pensez-vous ?

**Options**
- A. C'est incomplet : cette seule demi-réaction ne peut pas exister seule — il manque la demi-réaction d'oxydation couplée du cuivre ($\ce{Cu^0 -> Cu^{2+} + 2e^-}$), qui doit être combinée à celle-ci (multipliée par 2) pour former l'équation globale réelle
- B. C'est correct : dans une réaction où un métal se dépose, seule la demi-réaction de réduction du métal qui se dépose détermine ce qui se passe
- C. C'est incomplet, mais seulement parce qu'il faudrait préciser l'état physique (aq) des ions — la logique redox de l'équation est déjà correcte et complète
- D. C'est correct, car l'électron $\ce{e^-}$ présent dans l'équation prouve déjà qu'un couplage a eu lieu, sans qu'il soit nécessaire de l'expliciter

**Réponse correcte** : A

**Feedback correct**
Comme pour toute réduction, celle de l'argent ne peut pas se produire seule : l'électron capté doit provenir d'une oxydation couplée. Ici, il s'agit de l'oxydation du cuivre ($\ce{Cu^0 -> Cu^{2+} + 2e^-}$), dont la demi-réaction de réduction de l'argent doit être doublée ($\ce{2Ag+ + 2e- -> 2Ag^0}$) pour équilibrer les électrons avant combinaison : $\ce{Cu^0 + 2Ag+ -> Cu^{2+} + 2Ag^0}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Même erreur que pour le cuivre seul : croire qu'une seule demi-réaction (ici la réduction) suffit à décrire la réaction complète. L'oxydation couplée doit toujours être explicitée et combinée, avec les électrons équilibrés entre les deux demi-réactions.
- Si C : Le problème n'est pas une question de notation d'état physique — c'est l'absence totale de la demi-réaction d'oxydation qui rend cette équation incomplète.
- Si D : La présence du symbole $\ce{e^-}$ dans une demi-réaction isolée ne prouve rien sur le couplage réel — elle indique seulement un échange d'électrons localisé à cette demi-réaction ; le couplage n'est établi que lorsque les deux demi-réactions sont explicitement combinées avec leurs électrons équilibrés.

**Référence manuel** : oxydo-reduction-reaction-redox

---

<!-- ============================================================ -->
<!-- CONCEPT : oxydant — Oxydant                                  -->
<!-- 5 questions obligatoires : macro·T1, parti·T1, parti·T2×2    -->
<!-- (●², misc. reaction-redox--transfert-electrons-vs-liaison),  -->
<!-- symbo·T2                                                     -->
<!-- ============================================================ -->

---
id: q-oxydant-macro-t1-001
concept: oxydant
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Le manuel rappelle que le dioxygène de l'air $\ce{O2}$ est « l'oxydant par excellence » — c'est notamment lui qui permet à un feu de brûler (comburant). Quel usage macroscopique courant illustre le mieux le caractère oxydant d'une substance ?

**Options**
- A. L'eau de Javel ($\ce{NaClO}$), utilisée comme désinfectant et décolorant — son pouvoir oxydant lui permet de dégrader pigments et micro-organismes en captant leurs électrons
- B. Le sel de cuisine ($\ce{NaCl}$), utilisé pour conserver les aliments — son pouvoir oxydant empêche la prolifération bactérienne
- C. Le sucre (saccharose), utilisé comme conservateur dans les confitures — son pouvoir oxydant stabilise les fruits
- D. L'eau ($\ce{H2O}$), utilisée comme solvant universel — son pouvoir oxydant dissout la plupart des substances

**Réponse correcte** : A

**Feedback correct**
L'eau de Javel est un exemple courant et bien connu de substance oxydante à usage macroscopique : le chlore qu'elle contient (d.o. +1) capte des électrons (est réduit) en dégradant pigments et micro-organismes, ce qui explique son pouvoir désinfectant et décolorant — exactement le même principe que le dioxygène comburant.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le sel de cuisine conserve les aliments principalement en réduisant l'activité de l'eau disponible pour les micro-organismes (effet osmotique), pas par un mécanisme oxydant.
- Si C : Le sucre agit en confiture par un effet similaire au sel (réduction de l'eau disponible), pas par un pouvoir oxydant.
- Si D : L'eau est un solvant, pas un oxydant usuel — dissoudre une substance n'implique pas de transfert d'électrons.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydant-parti-t1-001
concept: oxydant
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans la réaction $\ce{Zn^0 + Cu^{2+} -> Zn^{2+} + Cu^0}$, quelle espèce joue le rôle d'oxydant ?

**Options**
- A. $\ce{Cu^{2+}}$, car il capte les électrons cédés par le zinc
- B. $\ce{Zn^0}$, car il cède des électrons à l'ion cuivre
- C. $\ce{Zn^{2+}}$, car c'est le produit obtenu après la réaction
- D. $\ce{Cu^0}$, car c'est le métal qui se dépose visiblement

**Réponse correcte** : A

**Feedback correct**
L'oxydant est, par définition, l'espèce qui capte des électrons (et qui, ce faisant, subit elle-même une réduction). Ici, $\ce{Cu^{2+}}$ capte les 2 électrons cédés par le zinc pour former $\ce{Cu^0}$ : c'est donc l'oxydant de cette réaction.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{Zn^0}$ cède des électrons — c'est la définition du réducteur, pas de l'oxydant.
- Si C : $\ce{Zn^{2+}}$ est le produit de l'oxydation du zinc (« l'oxydé »), pas l'oxydant lui-même — l'oxydant est l'espèce de départ qui capte les électrons, pas le résultat de l'espèce qui les a cédés.
- Si D : $\ce{Cu^0}$ est le produit de la réduction de $\ce{Cu^{2+}}$ (« le réduit »), pas l'oxydant — l'oxydant est $\ce{Cu^{2+}}$, avant qu'il ne capte les électrons.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydant-parti-t2-001
concept: oxydant
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans l'expérience où une lame de cuivre est plongée dans une solution de nitrate d'argent $\ce{AgNO3}$ (aq), quatre espèces sont présentes : $\ce{Cu^0}$, $\ce{Ag+}$, $\ce{NO3^-}$ et $\ce{H2O}$. Laquelle joue le rôle d'oxydant ?

**Options**
- A. $\ce{Ag+}$, qui capte un électron cédé par le cuivre pour former $\ce{Ag^0}$ — $\ce{NO3^-}$ et $\ce{H2O}$ restent spectateurs, sans rôle redox
- B. $\ce{NO3^-}$, car c'est l'espèce qui semble accompagner $\ce{Ag+}$ et pourrait donc, par analogie, jouer un rôle actif dans le transfert d'électrons
- C. $\ce{Cu^0}$, car c'est l'espèce métallique, et les métaux sont par nature des oxydants
- D. $\ce{H2O}$, car le solvant participe toujours activement à toute réaction rédox en solution aqueuse

**Réponse correcte** : A

**Feedback correct**
Parmi les quatre espèces en présence, seuls $\ce{Cu^0}$ et $\ce{Ag+}$ échangent réellement des électrons. $\ce{Ag+}$ capte un électron cédé par le cuivre pour former $\ce{Ag^0}$ : c'est donc l'oxydant. $\ce{NO3^-}$ et $\ce{H2O}$ restent spectateurs — ne pas se laisser distraire par leur simple présence dans le mélange.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur documentée d'attribuer un rôle redox à un ion spectateur simplement parce qu'il est présent dans la solution — $\ce{NO3^-}$ ne capte ni ne cède d'électrons ici, il assure seulement l'électroneutralité.
- Si C : Être un métal ne fait pas automatiquement de $\ce{Cu^0}$ un oxydant — au contraire, les métaux à l'état élémentaire sont généralement des réducteurs (ils ont tendance à céder des électrons), comme c'est le cas ici.
- Si D : $\ce{H2O}$ n'est pas systématiquement active dans une réaction rédox — ici, elle reste spectatrice ; sa participation dépend de la réaction précise (elle intervient activement dans d'autres contextes, mais pas celui-ci).

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydant-parti-t2-002
concept: oxydant
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans l'expérience où une lame de zinc est plongée dans l'acide chlorhydrique $\ce{HCl}$ (aq), quatre espèces sont présentes : $\ce{Zn^0}$, $\ce{H+}$, $\ce{Cl^-}$ et $\ce{H2O}$. Laquelle joue le rôle d'oxydant ?

**Options**
- A. $\ce{H+}$, qui capte des électrons cédés par le zinc pour former $\ce{H2}$ — $\ce{Cl^-}$ et $\ce{H2O}$ restent spectateurs, sans rôle redox
- B. $\ce{Cl^-}$, car il accompagne $\ce{H+}$ dans la formule $\ce{HCl}$ et devrait donc partager le même rôle redox
- C. $\ce{Zn^0}$, car c'est l'espèce qui disparaît visiblement, donc l'espèce « active » de la réaction
- D. $\ce{H2O}$, car c'est le solvant, donc l'espèce qui pilote nécessairement le transfert d'électrons

**Réponse correcte** : A

**Feedback correct**
Parmi les quatre espèces en présence, seuls $\ce{Zn^0}$ et $\ce{H+}$ échangent réellement des électrons. $\ce{H+}$ capte des électrons cédés par le zinc pour former $\ce{H2}$ : c'est donc l'oxydant. $\ce{Cl^-}$ et $\ce{H2O}$ restent spectateurs.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur documentée d'attribuer un rôle redox à un ion spectateur simplement parce qu'il apparaît dans la même formule (HCl) que l'espèce réellement active — $\ce{Cl^-}$ ne capte ni ne cède d'électrons ici.
- Si C : « Être visiblement actif » (le zinc qui se dissout) ne signifie pas « être l'oxydant » — le zinc est au contraire le réducteur : c'est lui qui cède des électrons, pas qui en capte.
- Si D : Le solvant n'est pas automatiquement l'espèce qui « pilote » le transfert d'électrons — ici, $\ce{H2O}$ reste spectatrice ; le rôle d'oxydant revient à $\ce{H+}$, l'espèce qui capte réellement les électrons.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-oxydant-symbo-t2-001
concept: oxydant
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Quelle demi-réaction décrit correctement le comportement de l'oxydant $\ce{Ag+}$ lorsqu'il réagit avec le cuivre métallique ?

**Options**
- A. $\ce{Ag+ + e^- -> Ag^0}$
- B. $\ce{Ag+ -> Ag^0 + e^-}$
- C. $\ce{Ag^0 + e^- -> Ag+}$
- D. $\ce{2Ag+ + e^- -> 2Ag^0}$

**Réponse correcte** : A

**Feedback correct**
L'oxydant $\ce{Ag+}$ capte un électron pour former $\ce{Ag^0}$ : $\ce{Ag+ + e^- -> Ag^0}$. Les électrons apparaissent du côté des réactifs, ce qui correspond bien à une réduction (le comportement de l'oxydant).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les électrons sont ici du côté des produits, ce qui décrirait une oxydation (une perte d'électrons) — or l'oxydant $\ce{Ag+}$ capte des électrons, il n'en cède pas.
- Si C : Cette équation part de $\ce{Ag^0}$ pour aboutir à $\ce{Ag+}$, ce qui est l'inverse du comportement de l'oxydant (qui part de la forme oxydée $\ce{Ag+}$ pour capter un électron).
- Si D : Les coefficients stœchiométriques ne sont pas équilibrés : 2 ions $\ce{Ag+}$ nécessiteraient 2 électrons, pas 1, pour former 2 $\ce{Ag^0}$.

**Référence manuel** : oxydo-reduction-reaction-redox

---

<!-- ============================================================ -->
<!-- CONCEPT : reducteur — Réducteur (symétrique à oxydant)       -->
<!-- 5 questions obligatoires : macro·T1, parti·T1, parti·T2×2    -->
<!-- (●², misc. reaction-redox--transfert-electrons-vs-liaison),  -->
<!-- symbo·T2                                                     -->
<!-- ============================================================ -->

---
id: q-reducteur-macro-t1-001
concept: reducteur
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Le magnésium métallique $\ce{Mg^0}$ est un réducteur bien connu, capable de céder facilement ses électrons — c'est pourquoi il brûle vivement au contact du dioxygène de l'air, avec un éclat lumineux caractéristique. Quel usage macroscopique courant illustre le mieux le caractère réducteur d'une substance ?

**Options**
- A. Les combustibles (bois, charbon, essence), qui cèdent facilement leurs électrons au dioxygène de l'air lors de la combustion, dégageant chaleur et lumière
- B. Les gaz nobles (hélium, néon), utilisés dans les ampoules — leur caractère réducteur empêche toute réaction avec le filament
- C. Le sel de table ($\ce{NaCl}$), utilisé en cuisine — son caractère réducteur préserve la fraîcheur des aliments
- D. Le verre, utilisé pour fabriquer des récipients — son caractère réducteur le rend résistant aux chocs thermiques

**Réponse correcte** : A

**Feedback correct**
Les combustibles usuels sont de bons réducteurs : ils cèdent facilement des électrons au dioxygène de l'air (qui joue le rôle d'oxydant) lors de la combustion — exactement comme le magnésium qui brûle vivement dans $\ce{O2}$. C'est ce transfert d'électrons, très exothermique, qui dégage la chaleur et la lumière observées.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les gaz nobles sont au contraire chimiquement très peu réactifs — leur configuration électronique stable les empêche de céder facilement des électrons ; ce n'est pas un caractère réducteur qui explique leur usage dans les ampoules, mais leur quasi-inertie chimique.
- Si C : Le sel de table n'a pas de caractère réducteur particulier expliquant la conservation alimentaire — cet effet est plutôt lié à la réduction de l'eau disponible pour les micro-organismes (effet osmotique).
- Si D : La résistance thermique du verre n'a aucun lien avec un caractère réducteur — elle tient à sa structure atomique (réseau covalent) et à son faible coefficient de dilatation, pas à un transfert d'électrons.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reducteur-parti-t1-001
concept: reducteur
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans la réaction $\ce{Zn^0 + Cu^{2+} -> Zn^{2+} + Cu^0}$, quelle espèce joue le rôle de réducteur ?

**Options**
- A. $\ce{Zn^0}$, car il cède des électrons à l'ion cuivre
- B. $\ce{Cu^{2+}}$, car il capte les électrons cédés par le zinc
- C. $\ce{Cu^0}$, car c'est le métal qui se dépose visiblement
- D. $\ce{Zn^{2+}}$, car c'est le produit obtenu après la réaction

**Réponse correcte** : A

**Feedback correct**
Le réducteur est, par définition, l'espèce qui cède des électrons (et qui, ce faisant, subit elle-même une oxydation). Ici, $\ce{Zn^0}$ cède 2 électrons à l'ion cuivre : c'est donc le réducteur de cette réaction.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{Cu^{2+}}$ capte des électrons — c'est la définition de l'oxydant, pas du réducteur.
- Si C : $\ce{Cu^0}$ est le produit de la réduction de $\ce{Cu^{2+}}$ (« le réduit »), pas le réducteur lui-même.
- Si D : $\ce{Zn^{2+}}$ est le produit de l'oxydation du zinc (« l'oxydé »), pas le réducteur — le réducteur est l'espèce de départ ($\ce{Zn^0}$) qui cède les électrons, pas le résultat de cette perte.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reducteur-parti-t2-001
concept: reducteur
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans l'expérience où une lame de cuivre est plongée dans une solution de nitrate d'argent $\ce{AgNO3}$ (aq), quatre espèces sont présentes : $\ce{Cu^0}$, $\ce{Ag+}$, $\ce{NO3^-}$ et $\ce{H2O}$. Laquelle joue le rôle de réducteur ?

**Options**
- A. $\ce{Cu^0}$, qui cède des électrons captés par $\ce{Ag+}$ — $\ce{NO3^-}$ et $\ce{H2O}$ restent spectateurs, sans rôle redox
- B. $\ce{NO3^-}$, car il est présent dans la même solution qu'$\ce{Ag+}$ et pourrait donc, par analogie, jouer un rôle actif
- C. $\ce{Ag+}$, car c'est l'espèce qui subit une transformation visible (dépôt métallique)
- D. $\ce{H2O}$, car le solvant fournit nécessairement les électrons échangés dans toute réaction en solution aqueuse

**Réponse correcte** : A

**Feedback correct**
Parmi les quatre espèces en présence, seuls $\ce{Cu^0}$ et $\ce{Ag+}$ échangent réellement des électrons. $\ce{Cu^0}$ cède 2 électrons captés par les ions $\ce{Ag+}$ : c'est donc le réducteur. $\ce{NO3^-}$ et $\ce{H2O}$ restent spectateurs.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur documentée d'attribuer un rôle redox à un ion spectateur simplement parce qu'il partage la solution avec une espèce active — $\ce{NO3^-}$ ne cède ni ne capte d'électrons ici.
- Si C : $\ce{Ag+}$ subit effectivement une transformation (il devient $\ce{Ag^0}$), mais c'est en captant des électrons : c'est donc l'oxydant, pas le réducteur — le réducteur est l'espèce qui cède les électrons ($\ce{Cu^0}$).
- Si D : L'eau n'est pas systématiquement la source des électrons échangés — ici, elle reste spectatrice ; les électrons proviennent directement du cuivre.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reducteur-parti-t2-002
concept: reducteur
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans l'expérience où une lame de zinc est plongée dans l'acide chlorhydrique $\ce{HCl}$ (aq), quatre espèces sont présentes : $\ce{Zn^0}$, $\ce{H+}$, $\ce{Cl^-}$ et $\ce{H2O}$. Laquelle joue le rôle de réducteur ?

**Options**
- A. $\ce{Zn^0}$, qui cède des électrons captés par les ions $\ce{H+}$ — $\ce{Cl^-}$ et $\ce{H2O}$ restent spectateurs, sans rôle redox
- B. $\ce{Cl^-}$, car il accompagne $\ce{H+}$ dans la formule $\ce{HCl}$ et devrait donc partager le même rôle redox
- C. $\ce{H+}$, car c'est l'espèce qui se transforme en un gaz visible ($\ce{H2}$)
- D. $\ce{H2O}$, car le solvant fournit nécessairement les électrons échangés dans toute réaction acide

**Réponse correcte** : A

**Feedback correct**
Parmi les quatre espèces en présence, seuls $\ce{Zn^0}$ et $\ce{H+}$ échangent réellement des électrons. $\ce{Zn^0}$ cède 2 électrons captés par deux ions $\ce{H+}$ : c'est donc le réducteur. $\ce{Cl^-}$ et $\ce{H2O}$ restent spectateurs.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur documentée d'attribuer un rôle redox à un ion spectateur simplement parce qu'il apparaît dans la même formule que l'espèce active — $\ce{Cl^-}$ ne cède ni ne capte d'électrons ici.
- Si C : $\ce{H+}$ subit effectivement une transformation (il devient $\ce{H2}$), mais c'est en captant des électrons : c'est donc l'oxydant, pas le réducteur — le réducteur est l'espèce qui cède les électrons ($\ce{Zn^0}$).
- Si D : L'eau n'est pas systématiquement la source des électrons échangés — ici, elle reste spectatrice ; les électrons proviennent directement du zinc.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-reducteur-symbo-t2-001
concept: reducteur
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Quelle demi-réaction décrit correctement le comportement du réducteur $\ce{Cu^0}$ lorsqu'il réagit avec une solution de nitrate d'argent ?

**Options**
- A. $\ce{Cu^0 -> Cu^{2+} + 2e^-}$
- B. $\ce{Cu^0 + 2e^- -> Cu^{2+}}$
- C. $\ce{Cu^{2+} -> Cu^0 + 2e^-}$
- D. $\ce{Cu^0 -> Cu^{2+} - 2e^-}$

**Réponse correcte** : A

**Feedback correct**
Le réducteur $\ce{Cu^0}$ cède 2 électrons pour former $\ce{Cu^{2+}}$ : $\ce{Cu^0 -> Cu^{2+} + 2e^-}$. Les électrons apparaissent du côté des produits, ce qui correspond bien à une oxydation (le comportement du réducteur).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les électrons sont ici du côté des réactifs, ce qui décrirait une réduction (un gain d'électrons) — or le réducteur $\ce{Cu^0}$ cède des électrons, il n'en capte pas.
- Si C : Cette équation part de $\ce{Cu^{2+}}$ pour aboutir à $\ce{Cu^0}$, ce qui est l'inverse du comportement du réducteur (qui part de la forme réduite $\ce{Cu^0}$ pour céder des électrons).
- Si D : Le signe « moins » devant les électrons n'a pas de sens dans une demi-réaction équilibrée — les électrons cédés s'ajoutent du côté des produits avec un signe +, jamais soustraits.

**Référence manuel** : oxydo-reduction-reaction-redox

---

<!-- ============================================================ -->
<!-- CONCEPT : demi-reaction — Demi-réaction                       -->
<!-- 6 questions obligatoires : parti·T1×2 (●², misc. oxydation-- -->
<!-- sans-reduction-couplee), parti·T2×2 (●², misc. reaction-     -->
<!-- redox--transfert-electrons-vs-liaison), symbo·T2, symbo·T3   -->
<!-- ============================================================ -->

---
id: q-demi-reaction-parti-t1-001
concept: demi-reaction
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
misconception: oxydation--sans-reduction-couplee
date_validation: 2026-09-14
statut: validated
---

**Question**
Peut-on observer expérimentalement, en pratique, une demi-réaction d'oxydation se produire seule, sans qu'aucune réduction ne se produise simultanément quelque part dans le système ?

**Options**
- A. Non — les deux demi-réactions sont toujours couplées : les électrons libérés par une oxydation doivent immédiatement être captés par une réduction, sinon la charge ne serait pas conservée
- B. Oui — une oxydation peut se produire isolément si le milieu est suffisamment riche en énergie pour « libérer » les électrons sans qu'ils soient captés ailleurs
- C. Oui, mais uniquement dans le cas de métaux très réactifs comme le zinc ou le magnésium, qui peuvent céder leurs électrons sans réduction couplée
- D. Non, sauf dans les piles électriques, où l'oxydation et la réduction sont physiquement séparées et peuvent donc se produire indépendamment l'une de l'autre

**Réponse correcte** : A

**Feedback correct**
Les deux demi-réactions sont toujours couplées, sans exception : les électrons libérés par une oxydation doivent être immédiatement captés par une réduction quelque part dans le système, faute de quoi la charge électrique ne serait pas conservée — un électron ne peut pas exister « libre » indéfiniment dans une solution ou sur une électrode.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est exactement l'erreur documentée : croire qu'une oxydation peut « libérer » des électrons sans qu'ils soient captés ailleurs. Ce n'est physiquement pas possible — la conservation de la charge l'exige.
- Si C : Le couplage obligatoire n'a rien à voir avec la réactivité du métal — même les métaux les plus réactifs (zinc, magnésium, sodium) ont besoin d'un oxydant pour capter les électrons qu'ils cèdent.
- Si D : Même dans une pile, où oxydation et réduction sont séparées spatialement (sur deux électrodes différentes), les deux demi-réactions restent couplées — les électrons cédés à l'anode doivent circuler jusqu'à la cathode où ils sont captés ; elles ne se produisent jamais indépendamment l'une de l'autre.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-demi-reaction-parti-t1-002
concept: demi-reaction
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
misconception: oxydation--sans-reduction-couplee
date_validation: 2026-09-14
statut: validated
---

**Question**
Un élève affirme qu'une lame de zinc plongée dans l'eau pure devrait se dissoudre progressivement, le zinc cédant ses électrons directement à l'eau du récipient, même en l'absence de tout oxydant identifiable. Que peut-on répondre à cette affirmation, du point de vue du couplage des demi-réactions ?

**Options**
- A. Si le zinc cède réellement des électrons (s'oxyde), il faut nécessairement qu'une espèce présente les capte (soit réduite) — l'affirmation n'est donc physiquement valide que si l'on identifie précisément quelle espèce de l'eau ($\ce{H+}$ ou $\ce{H2O}$ elle-même) joue ce rôle d'oxydant couplé
- B. C'est possible tel quel : le zinc peut céder ses électrons directement dans le milieu sans qu'aucune réduction couplée ne soit nécessaire, les électrons se dispersant simplement dans le liquide
- C. C'est impossible, car le zinc ne peut jamais s'oxyder en l'absence d'un métal moins réactif que lui à proximité
- D. C'est possible, mais uniquement parce que l'eau est un solvant polaire — cette polarité suffit à elle seule à capter les électrons cédés, sans qu'il s'agisse d'une véritable réduction

**Réponse correcte** : A

**Feedback correct**
Le principe du couplage obligatoire s'applique ici aussi : si le zinc s'oxyde réellement, une réduction couplée doit avoir lieu quelque part — typiquement la réduction de traces de $\ce{H+}$ (issues de l'auto-ionisation de l'eau) en $\ce{H2}$, un processus lent mais bien réel. On ne peut jamais affirmer qu'une oxydation se produit « seule » ; il faut toujours identifier l'espèce réduite en contrepartie.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est exactement l'erreur documentée : imaginer que des électrons peuvent simplement « se disperser » dans un liquide sans être captés par une espèce précise qui se réduit. Un électron libre n'existe pas durablement en solution.
- Si C : Le couplage obligatoire ne dépend pas de la présence d'un métal moins réactif — il exige seulement une espèce capable de capter les électrons, ce qui peut être un ion $\ce{H+}$ ou même l'eau elle-même dans certaines conditions, pas nécessairement un autre métal.
- Si D : La polarité d'un solvant n'a rien à voir avec sa capacité à capter des électrons (être réduit) — ce sont deux phénomènes distincts (polarité électrostatique vs transfert réel d'électrons).

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-demi-reaction-parti-t2-001
concept: demi-reaction
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
On souhaite décomposer la réaction $\ce{Zn^0 + CuSO4 (aq) -> ZnSO4 (aq) + Cu^0}$ en ses deux demi-réactions. Laquelle des décompositions suivantes est correcte ?

**Options**
- A. Oxydation : $\ce{Zn^0 -> Zn^{2+} + 2e^-}$ ; Réduction : $\ce{Cu^{2+} + 2e^- -> Cu^0}$ (le sulfate $\ce{SO4^{2-}}$ reste spectateur, il n'apparaît dans aucune des deux demi-réactions)
- B. Oxydation : $\ce{Zn^0 + SO4^{2-} -> ZnSO4}$ (la liaison Cu-SO4 se rompt, libérant $\ce{Cu^{2+}}$, qui capte ensuite les électrons du zinc)
- C. Réduction : $\ce{Zn^0 -> Zn^{2+} + 2e^-}$ ; Oxydation : $\ce{Cu^{2+} + 2e^- -> Cu^0}$
- D. Oxydation : $\ce{SO4^{2-} -> SO4^{0} + 2e^-}$ ; Réduction : $\ce{Cu^{2+} + 2e^- -> Cu^0}$

**Réponse correcte** : A

**Feedback correct**
La bonne décomposition isole les deux vrais acteurs redox ($\ce{Zn^0}$ et $\ce{Cu^{2+}}$) et laisse le sulfate, spectateur, en dehors des deux demi-réactions : $\ce{Zn^0 -> Zn^{2+} + 2e^-}$ (oxydation) et $\ce{Cu^{2+} + 2e^- -> Cu^0}$ (réduction).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur documentée de modéliser la réaction comme une rupture de liaison ionique (« Cu-SO4 ») libérant l'espèce active, plutôt que de décomposer directement en deux demi-réactions de transfert d'électrons entre les vrais acteurs redox — le sulfate n'est jamais « lié » au cuivre de cette manière dans le mécanisme réel, et surtout il ne doit apparaître dans aucune demi-réaction puisqu'il est spectateur.
- Si C : Les labels sont inversés : $\ce{Zn^0 -> Zn^{2+} + 2e^-}$ est une oxydation (perte d'électrons, électrons en produits), pas une réduction ; et inversement pour le cuivre.
- Si D : Le soufre du sulfate ne change pas de d.o. dans cette réaction ($\ce{SO4^{2-}}$ reste spectateur) — lui attribuer une demi-réaction d'oxydation est incorrect, il n'y a ici que deux acteurs redox réels (Zn et Cu).

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-demi-reaction-parti-t2-002
concept: demi-reaction
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: reaction-redox--transfert-electrons-vs-liaison
date_validation: 2026-09-14
statut: validated
---

**Question**
On souhaite décomposer la réaction $\ce{Zn^0 + 2HCl (aq) -> ZnCl2 (aq) + H2}$ en ses deux demi-réactions, en partant de la demi-réaction de réduction $\ce{2H+ + 2e- -> H2}$ donnée dans la série électrochimique, qu'il faut lire en sens inverse pour obtenir l'oxydation du zinc. Laquelle des décompositions suivantes est correcte ?

**Options**
- A. Oxydation (lecture inversée de la réduction du zinc) : $\ce{Zn^0 -> Zn^{2+} + 2e^-}$ ; Réduction (telle quelle) : $\ce{2H+ + 2e- -> H2}$ (le chlorure $\ce{Cl^-}$ reste spectateur, il n'apparaît dans aucune des deux demi-réactions)
- B. Oxydation : $\ce{Zn^0 + 2Cl^- -> ZnCl2}$ (la liaison entre $\ce{H+}$ et $\ce{Cl^-}$ se rompt, libérant $\ce{H+}$ qui capte ensuite les électrons du zinc)
- C. Oxydation : $\ce{2H+ + 2e- -> H2}$ ; Réduction : $\ce{Zn^0 -> Zn^{2+} + 2e^-}$
- D. Oxydation : $\ce{Zn^0 -> Zn^{2+} + 2e^-}$ ; Réduction : $\ce{2Cl^- -> Cl2 + 2e^-}$

**Réponse correcte** : A

**Feedback correct**
On isole les deux vrais acteurs redox ($\ce{Zn^0}$ et $\ce{H+}$) et on laisse le chlorure, spectateur, en dehors des deux demi-réactions : $\ce{Zn^0 -> Zn^{2+} + 2e^-}$ (oxydation, obtenue en lisant en sens inverse la demi-réaction de réduction du zinc) et $\ce{2H+ + 2e- -> H2}$ (réduction, telle qu'elle apparaît dans la série électrochimique).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Même erreur que pour le sulfate : imaginer une rupture de liaison HCl libérant l'espèce active plutôt qu'un transfert d'électrons direct entre les vrais acteurs redox — et le chlorure ne doit apparaître dans aucune des deux demi-réactions puisqu'il est spectateur.
- Si C : Les labels sont inversés : $\ce{2H+ + 2e- -> H2}$ (électrons en réactifs) est une réduction, pas une oxydation ; et inversement pour le zinc.
- Si D : Le chlore de $\ce{Cl^-}$ ne change pas de d.o. dans cette réaction ($\ce{Cl^-}$ reste spectateur, il ne devient pas $\ce{Cl2}$) — lui attribuer une demi-réaction d'oxydation est incorrect ; il n'y a ici que deux acteurs redox réels (Zn et $\ce{H+}$).

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-demi-reaction-symbo-t2-001
concept: demi-reaction
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Écrivez la demi-réaction équilibrée (atomes et charge) correspondant à la réduction de l'ion fer(III) en ion fer(II).

**Options**
- A. $\ce{Fe^{3+} + e^- -> Fe^{2+}}$
- B. $\ce{Fe^{3+} -> Fe^{2+} + e^-}$
- C. $\ce{Fe^{2+} + e^- -> Fe^{3+}}$
- D. $\ce{Fe^{3+} + 2e^- -> Fe^{2+}}$

**Réponse correcte** : A

**Feedback correct**
$\ce{Fe^{3+}}$ (d.o. +3) devient $\ce{Fe^{2+}}$ (d.o. +2) : c'est un gain d'un seul électron. La demi-réaction équilibrée en atomes (un Fe de chaque côté) et en charge (+3 sur les réactifs avec l'électron = +2, soit +2 des deux côtés) est : $\ce{Fe^{3+} + e^- -> Fe^{2+}}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les électrons sont ici du côté des produits, ce qui décrirait une oxydation ($\ce{Fe^{2+} -> Fe^{3+}}$), pas la réduction demandée.
- Si C : Cette équation part de $\ce{Fe^{2+}}$ pour aboutir à $\ce{Fe^{3+}}$ en captant un électron, ce qui est chimiquement incohérent (un cation qui capte un électron devrait voir sa charge diminuer, pas augmenter) — c'est l'inverse de ce qui est demandé.
- Si D : Le bilan de charge n'est pas respecté : $\ce{Fe^{3+} + 2e^-}$ donnerait une charge de +1 côté réactifs, ce qui ne correspond pas à la charge +2 de $\ce{Fe^{2+}}$ côté produits — un seul électron est nécessaire, pas deux.

**Référence manuel** : oxydo-reduction-reaction-redox

---
id: q-demi-reaction-symbo-t3-001
concept: demi-reaction
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
date_validation: 2026-09-14
statut: validated
---

**Question**
En vous appuyant sur le couple $\ce{MnO4^-}$/$\ce{Mn^{2+}}$ utilisé dans l'exemple d'équilibrage du manuel (d.o. du manganèse : +7 → +2), complétez et équilibrez la demi-réaction de réduction de l'ion permanganate $\ce{MnO4^-}$ en $\ce{Mn^{2+}}$, en milieu acide (ions $\ce{H+}$ disponibles).

**Options**
- A. $\ce{MnO4^- + 8H+ + 5e^- -> Mn^{2+} + 4H2O}$
- B. $\ce{MnO4^- + 5e^- -> Mn^{2+} + 4O^{2-}}$
- C. $\ce{MnO4^- + 4H+ + 5e^- -> Mn^{2+} + 2H2O}$
- D. $\ce{MnO4^- + 8H+ -> Mn^{2+} + 4H2O + 5e^-}$

**Réponse correcte** : A

**Feedback correct**
Le manganèse gagne 5 électrons (+7 → +2). Les 4 atomes d'oxygène de $\ce{MnO4^-}$ doivent être équilibrés en 4 $\ce{H2O}$ du côté des produits, ce qui nécessite 8 $\ce{H+}$ du côté des réactifs pour équilibrer les 8 atomes d'hydrogène ainsi introduits. Le bilan de charge se vérifie : à gauche, −1 ($\ce{MnO4^-}$) + 8×(+1) ($\ce{H+}$) + 5×(−1) ($\ce{e^-}$) = +2 ; à droite, $\ce{Mn^{2+}}$ = +2. L'équation est équilibrée en atomes et en charge.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'oxygène ne se retrouve pas sous forme d'ion oxyde libre $\ce{O^{2-}}$ en solution aqueuse — il doit être équilibré avec des ions $\ce{H+}$ pour former des molécules d'eau $\ce{H2O}$, comme le fait toute réaction en milieu acide.
- Si C : Le nombre de molécules d'eau (2) ne correspond pas aux 4 atomes d'oxygène de $\ce{MnO4^-}$ — il en faut 4, ce qui exige 8 $\ce{H+}$ (et non 4) pour équilibrer les hydrogènes.
- Si D : Les électrons gagnés par une réduction doivent apparaître du côté des réactifs, pas des produits — cette équation, telle qu'écrite, décrirait plutôt une oxydation.

**Référence manuel** : oxydo-reduction-equilibrage

---
<!-- ============================================================ -->
<!-- CONCEPT : serie-electrochimique — Série électrochimique       -->
<!-- 5 questions obligatoires : parti·T1, symbo·T2×2 (●², concept -->
<!-- central), symbo·T3×2 (●², concept culminant)                 -->
<!-- ============================================================ -->

---
id: q-serie-electrochimique-parti-t1-001
concept: serie-electrochimique
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Que représente le potentiel standard de réduction $E^\circ$ d'un couple oxydant/réducteur dans la série électrochimique ?

**Options**
- A. Une mesure de la tendance de l'espèce oxydante du couple à gagner des électrons (à être réduite) — plus $E^\circ$ est élevé, meilleur est l'oxydant
- B. Une mesure de la vitesse à laquelle la réaction d'électrode se produit — plus $E^\circ$ est élevé, plus la réaction est rapide
- C. Une mesure de la quantité d'électrons disponibles dans le couple, exprimée en volts
- D. Une mesure de la charge réelle portée par l'espèce oxydante du couple

**Réponse correcte** : A

**Feedback correct**
$E^\circ$ mesure la tendance d'une espèce à gagner des électrons (à se réduire). Plus $E^\circ$ est élevé, plus l'espèce oxydante du couple est un bon oxydant (elle se réduit facilement) ; plus $E^\circ$ est bas, plus l'espèce réductrice du couple est un bon réducteur (elle s'oxyde facilement).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $E^\circ$ est une grandeur thermodynamique (liée à la tendance à échanger des électrons), pas cinétique — il ne renseigne pas sur la vitesse de la réaction.
- Si C : Le volt n'est pas une unité de quantité d'électrons (ce serait le coulomb ou la mole) — $E^\circ$ mesure une tendance, pas une quantité.
- Si D : $E^\circ$ est une propriété du couple oxydant/réducteur dans son ensemble, pas une charge portée par une espèce isolée — ce n'est pas non plus une charge réelle au sens électrostatique.

**Référence manuel** : oxydo-reduction-serie-electrochimique

---
id: q-serie-electrochimique-symbo-t2-001
concept: serie-electrochimique
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
On met en présence de l'aluminium métallique $\ce{Al^0}$ ($E^\circ(\ce{Al^{3+}/Al}) = −1{,}70$ V) et des ions cuivre(II) $\ce{Cu^{2+}}$ ($E^\circ(\ce{Cu^{2+}/Cu}) = +0{,}34$ V). La réaction est-elle spontanée, et si oui, quelle est l'espèce qui s'oxyde ?

**Options**
- A. Oui, spontanée ($\Delta V^\circ = +0{,}34 − (−1{,}70) = +2{,}04$ V $> 0$) — l'aluminium s'oxyde (il a le $E^\circ$ le plus bas, c'est le meilleur réducteur)
- B. Oui, spontanée, mais c'est le cuivre $\ce{Cu^{2+}}$ qui s'oxyde, car il a le potentiel le plus élevé
- C. Non, la réaction n'est pas spontanée car $\Delta V^\circ = −1{,}70 − 0{,}34 = −2{,}04$ V $< 0$
- D. Oui, spontanée ($\Delta V^\circ = +2{,}04$ V), mais aucune des deux espèces ne s'oxyde réellement — seuls les électrons se déplacent sans changer l'état d'oxydation des espèces

**Réponse correcte** : A

**Feedback correct**
Le meilleur réducteur ($E^\circ$ le plus bas, ici Al à −1,70 V) s'oxyde, tandis que le meilleur oxydant ($E^\circ$ le plus élevé, ici $\ce{Cu^{2+}}$ à +0,34 V) se réduit. $\Delta V^\circ = E^\circ_{\text{cathode}} − E^\circ_{\text{anode}} = 0{,}34 − (−1{,}70) = +2{,}04$ V $> 0$ : la réaction est spontanée. L'équation globale équilibrée est $\ce{2Al + 3Cu^{2+} -> 2Al^{3+} + 3Cu}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse : l'espèce au potentiel le plus élevé ($\ce{Cu^{2+}}$) est le meilleur oxydant — elle se réduit, elle ne s'oxyde pas. C'est l'espèce au potentiel le plus bas (Al) qui s'oxyde.
- Si C : Le calcul de $\Delta V^\circ$ suit toujours $E^\circ_{\text{cathode}}$ (l'oxydant, qui se réduit) moins $E^\circ_{\text{anode}}$ (le réducteur, qui s'oxyde) — ici $\ce{Cu^{2+}}$ est l'oxydant ($E^\circ$ le plus élevé) et Al le réducteur ($E^\circ$ le plus bas), donnant $\Delta V^\circ = 0{,}34 − (−1{,}70) = +2{,}04$ V, pas l'inverse.
- Si D : Une réaction rédox spontanée implique toujours un changement réel d'état d'oxydation des deux espèces impliquées — $\Delta V^\circ$ positif signale justement qu'un transfert d'électrons a bien lieu, avec oxydation d'une espèce et réduction de l'autre.

**Référence manuel** : oxydo-reduction-serie-electrochimique

---
id: q-serie-electrochimique-symbo-t2-002
concept: serie-electrochimique
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
On met en présence du zinc métallique $\ce{Zn^0}$ ($E^\circ(\ce{Zn^{2+}/Zn}) = −0{,}76$ V) et des ions nickel(II) $\ce{Ni^{2+}}$ ($E^\circ(\ce{Ni^{2+}/Ni}) = −0{,}23$ V). La réaction est-elle spontanée, et si oui, quelle est l'espèce qui se réduit ?

**Options**
- A. Oui, spontanée ($\Delta V^\circ = −0{,}23 − (−0{,}76) = +0{,}53$ V $> 0$) — $\ce{Ni^{2+}}$ se réduit (il a le $E^\circ$ le plus élevé, c'est le meilleur oxydant)
- B. Oui, spontanée, mais c'est le zinc $\ce{Zn^{2+}}$ qui se réduit, car il a le potentiel le plus bas
- C. Non, la réaction n'est pas spontanée car $\Delta V^\circ = −0{,}76 − (−0{,}23) = −0{,}53$ V $< 0$
- D. Oui, spontanée ($\Delta V^\circ = +0{,}53$ V), mais aucune réduction n'a lieu — seule une oxydation du zinc se produit, sans transfert d'électrons vers une autre espèce

**Réponse correcte** : A

**Feedback correct**
Le meilleur oxydant ($E^\circ$ le plus élevé, ici $\ce{Ni^{2+}}$ à −0,23 V) se réduit, tandis que le meilleur réducteur ($E^\circ$ le plus bas, ici Zn à −0,76 V) s'oxyde. $\Delta V^\circ = E^\circ_{\text{cathode}} − E^\circ_{\text{anode}} = −0{,}23 − (−0{,}76) = +0{,}53$ V $> 0$ : la réaction est spontanée. L'équation globale équilibrée est $\ce{Zn + Ni^{2+} -> Zn^{2+} + Ni}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse : l'espèce au potentiel le plus bas (Zn) est le meilleur réducteur — elle s'oxyde, elle ne se réduit pas. C'est l'espèce au potentiel le plus élevé ($\ce{Ni^{2+}}$) qui se réduit.
- Si C : Le calcul de $\Delta V^\circ$ suit toujours $E^\circ_{\text{cathode}}$ (l'oxydant, ici $\ce{Ni^{2+}}$, le potentiel le plus élevé) moins $E^\circ_{\text{anode}}$ (le réducteur, ici Zn, le potentiel le plus bas), donnant +0,53 V, pas l'inverse.
- Si D : Une oxydation ne peut jamais se produire sans réduction couplée — ici, la réduction de $\ce{Ni^{2+}}$ en Ni accompagne nécessairement l'oxydation du zinc.

**Référence manuel** : oxydo-reduction-serie-electrochimique

---
id: q-serie-electrochimique-symbo-t3-001
concept: serie-electrochimique
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
date_validation: 2026-09-14
statut: validated
---

**Question**
On plonge de la poudre de zinc $\ce{Zn^0}$ dans une solution contenant à la fois des ions $\ce{Fe^{2+}}$ ($E^\circ(\ce{Fe^{2+}/Fe}) = −0{,}41$ V) et des ions $\ce{Cu^{2+}}$ ($E^\circ(\ce{Cu^{2+}/Cu}) = +0{,}34$ V), en présence des ions spectateurs $\ce{SO4^{2-}}$ et de $\ce{H2O}$. Le zinc étant un très bon réducteur ($E^\circ(\ce{Zn^{2+}/Zn}) = −0{,}76$ V), avec quelle espèce réagit-il préférentiellement ?

**Options**
- A. Avec $\ce{Cu^{2+}}$, car c'est le meilleur oxydant du mélange ($E^\circ$ le plus élevé parmi les espèces réellement oxydantes présentes) — $\ce{Fe^{2+}}$ restant, pour l'instant, un oxydant moins favorable
- B. Avec $\ce{Fe^{2+}}$, car le fer est chimiquement plus proche du zinc dans le tableau périodique que le cuivre
- C. Avec les deux simultanément et dans les mêmes proportions, puisque les deux sont thermodynamiquement favorables face au zinc
- D. Avec $\ce{SO4^{2-}}$, car c'est l'espèce la plus abondante dans la solution (contre-ion des deux sels)

**Réponse correcte** : A

**Feedback correct**
Parmi les oxydants réellement présents ($\ce{Fe^{2+}}$ à −0,41 V et $\ce{Cu^{2+}}$ à +0,34 V), c'est $\ce{Cu^{2+}}$ qui a le potentiel le plus élevé : c'est donc le meilleur oxydant du mélange, celui qui réagit préférentiellement avec le meilleur réducteur disponible ($\ce{Zn^0}$). $\ce{SO4^{2-}}$ et $\ce{H2O}$ restent spectateurs.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La proximité dans le tableau périodique n'a aucun rapport avec la réactivité redox — seule la comparaison des potentiels standard $E^\circ$ détermine quelle espèce réagit préférentiellement.
- Si C : La règle « le meilleur oxydant réagit avec le meilleur réducteur » désigne une préférence thermodynamique claire, pas une réaction simultanée à parts égales — $\ce{Cu^{2+}}$, ayant le potentiel le plus élevé, réagit préférentiellement avant $\ce{Fe^{2+}}$ (qui pourrait ensuite réagir aussi, dans un second temps, une fois le meilleur oxydant consommé).
- Si D : $\ce{SO4^{2-}}$ reste spectateur quelle que soit sa concentration — l'abondance d'une espèce ne lui confère aucun rôle redox si son propre potentiel ne la rend pas compétitive.

**Référence manuel** : oxydo-reduction-serie-electrochimique

---
id: q-serie-electrochimique-symbo-t3-002
concept: serie-electrochimique
sous-partie: 6B
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
date_validation: 2026-09-14
statut: validated
---

**Question**
On plonge un fil de cuivre $\ce{Cu^0}$ dans une solution contenant à la fois des ions $\ce{Ag+}$ ($E^\circ(\ce{Ag+/Ag}) = +0{,}80$ V) et des ions $\ce{Fe^{3+}}$ ($E^\circ(\ce{Fe^{3+}/Fe^{2+}}) = +0{,}77$ V), en présence de l'ion spectateur $\ce{NO3^-}$ et de $\ce{H2O}$. Le cuivre étant un réducteur modéré ($E^\circ(\ce{Cu^{2+}/Cu}) = +0{,}34$ V), avec quelle espèce réagit-il préférentiellement ?

**Options**
- A. Avec $\ce{Ag+}$, car c'est le meilleur oxydant du mélange ($E^\circ$ le plus élevé parmi les espèces réellement oxydantes présentes), même si $\ce{Fe^{3+}}$ est également un bon oxydant face au cuivre
- B. Avec $\ce{Fe^{3+}}$, car le fer est un métal de transition plus réactif que l'argent, un métal noble peu réactif
- C. Avec les deux simultanément et dans les mêmes proportions, puisque les deux potentiels sont très proches
- D. Avec $\ce{NO3^-}$, car il accompagne les deux oxydants dans la solution et joue donc nécessairement un rôle actif

**Réponse correcte** : A

**Feedback correct**
Parmi les oxydants réellement présents ($\ce{Ag+}$ à +0,80 V et $\ce{Fe^{3+}}$ à +0,77 V), c'est $\ce{Ag+}$ qui a le potentiel le plus élevé, même si l'écart est faible : c'est donc le meilleur oxydant du mélange, celui qui réagit préférentiellement avec le meilleur réducteur disponible ($\ce{Cu^0}$). $\ce{NO3^-}$ et $\ce{H2O}$ restent spectateurs.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La réactivité intuitive d'un métal (l'argent est effectivement peu réactif à l'état métallique) ne détermine pas quel est le meilleur oxydant parmi deux espèces déjà sous forme ionique oxydée — seule la comparaison des potentiels standard $E^\circ$ des couples $\ce{Ag+/Ag}$ et $\ce{Fe^{3+}/Fe^{2+}}$ le détermine, et c'est $\ce{Ag+}$ qui l'emporte ici.
- Si C : Même avec un écart de potentiel faible (0,03 V), la règle désigne une préférence claire — $\ce{Ag+}$, ayant le potentiel le plus élevé, réagit préférentiellement avant $\ce{Fe^{3+}}$.
- Si D : $\ce{NO3^-}$ reste spectateur quelle que soit sa proximité apparente avec les espèces actives — son propre potentiel ne le rend compétitif dans aucune des deux demi-réactions en jeu ici.

**Référence manuel** : oxydo-reduction-serie-electrochimique

---
<!-- ============================================================ -->
<!-- CONCEPT : pile-galvanique — Pile galvanique                   -->
<!-- 5 questions obligatoires : macro·T1, parti·T1, parti·T2×2    -->
<!-- (●², misc. pont-salin--electrons-traversent-solution),       -->
<!-- symbo·T2                                                     -->
<!-- ============================================================ -->

---
id: q-pile-galvanique-macro-t1-001
concept: pile-galvanique
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Une pile galvanique est un dispositif qui convertit de l'énergie chimique en énergie électrique grâce à une réaction d'oxydoréduction spontanée. Dans la pile Daniell « classique » (deux béchers séparés reliés par un pont salin en papier), un voltmètre indique bien une tension, mais une ampoule branchée à la place ne s'allume pas. Comment expliquer cette observation macroscopique ?

**Options**
- A. Le voltmètre mesure une différence de potentiel sans nécessiter de courant important, tandis que l'ampoule a besoin d'un courant réel — or la résistance très élevée du pont salin en papier (trajet long, section étroite) limite le courant à une valeur quasi nulle, insuffisante pour allumer l'ampoule
- B. La pile ne produit en réalité aucune énergie électrique — la tension indiquée par le voltmètre est un artefact de mesure sans lien avec une vraie réaction chimique
- C. L'ampoule nécessite une tension alternative pour s'allumer, alors qu'une pile ne peut produire qu'une tension continue
- D. Le pont salin bloque complètement le passage de tout courant électrique, y compris celui mesuré par le voltmètre — la tension affichée est donc également nulle en réalité

**Réponse correcte** : A

**Feedback correct**
Un voltmètre a une résistance interne très élevée et ne consomme presque aucun courant — il peut donc indiquer une tension même si le courant réel disponible est minuscule. L'ampoule, elle, a besoin d'un courant conséquent pour chauffer son filament. Ici, la résistance énorme du pont salin en papier (R ∝ L/A, avec un trajet long et une section étroite) limite le courant à une valeur quasi nulle : la pile produit bien une tension réelle, mais ne peut débiter suffisamment de courant pour allumer l'ampoule.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La pile produit bel et bien de l'énergie électrique via une réaction chimique réelle (le zinc s'oxyde, le cuivre se dépose) — la tension mesurée par le voltmètre reflète une vraie f.e.m., pas un artefact.
- Si C : Une pile galvanique produit naturellement une tension continue, et une ampoule à incandescence classique fonctionne très bien en courant continu — ce n'est pas le type de courant qui pose problème ici, mais son intensité insuffisante.
- Si D : Le pont salin laisse bien passer un peu de courant (sinon même le voltmètre n'indiquerait rien) — c'est sa résistance très élevée qui limite ce courant à une valeur trop faible pour l'ampoule, pas un blocage total.

**Référence manuel** : oxydo-reduction-pile-daniell

---
id: q-pile-galvanique-parti-t1-001
concept: pile-galvanique
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Quel principe permet à une pile galvanique de capter, sous forme électrique, l'énergie d'une réaction rédox spontanée, plutôt que de la dissiper entièrement en chaleur ?

**Options**
- A. Séparer spatialement les deux demi-réactions (oxydation et réduction) dans deux compartiments distincts, en forçant les électrons à emprunter un fil métallique extérieur pour aller de l'un à l'autre
- B. Refroidir la réaction à basse température pour ralentir le transfert d'électrons et permettre sa mesure
- C. Utiliser des électrodes en métaux précieux, qui empêchent toute perte d'énergie sous forme de chaleur
- D. Augmenter la concentration des réactifs pour que davantage d'électrons soient transférés simultanément

**Réponse correcte** : A

**Feedback correct**
Lorsque le réducteur et l'oxydant sont en contact direct (par exemple une lame de zinc plongée directement dans une solution de sulfate de cuivre), toute l'énergie de la réaction se dissipe en chaleur. En séparant spatialement les deux demi-réactions dans deux compartiments reliés par un fil extérieur, les électrons sont forcés de circuler dans ce fil — ce flux d'électrons est le courant électrique récupérable.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La température n'est pas le levier qui permet de capter l'énergie sous forme électrique — c'est la séparation spatiale des deux demi-réactions qui force les électrons à emprunter un circuit extérieur.
- Si C : Le choix du métal des électrodes n'élimine pas les pertes thermiques (résistance du circuit, du pont salin) — ce n'est pas ce qui permet fondamentalement de capter l'énergie électriquement.
- Si D : Augmenter la concentration peut influencer la vitesse ou la durée de la réaction, mais ce n'est pas le principe qui permet de convertir l'énergie chimique en énergie électrique — c'est la séparation spatiale des demi-réactions.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-pile-galvanique-parti-t2-001
concept: pile-galvanique
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: pont-salin--electrons-traversent-solution
date_validation: 2026-09-14
statut: validated
---

**Question**
On construit une pile galvanique à partir des couples $\ce{Sn^{2+}/Sn}$ (E° = −0,14 V, électrode de Sn) et $\ce{Br2/Br^-}$ (E° = +1,06 V, électrode de platine inerte). Dans quel sens circulent les électrons dans le circuit extérieur, et quelle électrode est l'anode ?

**Options**
- A. Les électrons circulent de l'électrode de Sn (anode, potentiel le plus bas, siège de l'oxydation) vers l'électrode de platine (cathode, potentiel le plus élevé, siège de la réduction)
- B. Les électrons circulent de l'électrode de platine (anode) vers l'électrode de Sn (cathode) — l'électrode au potentiel le plus élevé cède toujours ses électrons en premier
- C. Aucun électron ne circule dans le circuit extérieur — tout le courant de cette pile provient exclusivement de la migration des ions dans le pont salin
- D. Les électrons circulent dans les deux sens simultanément, s'équilibrant entre les deux électrodes jusqu'à ce que les deux potentiels deviennent égaux

**Réponse correcte** : A

**Feedback correct**
L'étain, au potentiel le plus bas (−0,14 V), est le meilleur réducteur : il s'oxyde à l'anode, libérant des électrons qui circulent dans le fil extérieur vers l'électrode de platine, où le dibrome (potentiel le plus élevé, +1,06 V) les capte en se réduisant — c'est la cathode.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse : c'est l'électrode au potentiel le plus bas (Sn) qui cède ses électrons (anode) ; l'électrode au potentiel le plus élevé (Pt/Br2) les capte (cathode) — elle ne les cède jamais en premier.
- Si C : Dans le circuit extérieur, ce sont bien les électrons qui circulent (via le fil métallique) ; ce sont les ions qui migrent dans le pont salin, pas l'inverse — les deux mouvements sont complémentaires, pas substituables l'un à l'autre.
- Si D : Le courant électrique d'une pile spontanée a un sens net et déterminé par la différence de potentiel entre les deux couples — il ne s'agit pas d'un équilibrage symétrique dans les deux sens.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-pile-galvanique-parti-t2-002
concept: pile-galvanique
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: pont-salin--electrons-traversent-solution
date_validation: 2026-09-14
statut: validated
---

**Question**
On construit une pile galvanique à partir des couples $\ce{Pb^{2+}/Pb}$ (E° = −0,13 V, électrode de plomb) et $\ce{I2/I^-}$ (E° = +0,53 V, électrode de platine inerte). Dans quel sens circulent les électrons dans le circuit extérieur, et quelle électrode est la cathode ?

**Options**
- A. Les électrons circulent de l'électrode de plomb (anode, potentiel le plus bas) vers l'électrode de platine (cathode, potentiel le plus élevé, siège de la réduction du diiode)
- B. Les électrons circulent de l'électrode de platine (cathode) vers l'électrode de plomb (anode) — c'est la cathode qui « pousse » les électrons vers l'anode dans le circuit extérieur
- C. Le diiode migre directement à travers le pont salin jusqu'à l'électrode de plomb, où il capte les électrons libérés par l'oxydation
- D. Les électrons circulent uniquement à l'intérieur de chaque demi-pile, sans jamais emprunter le circuit extérieur — le pont salin assure à lui seul la totalité du transfert d'électrons

**Réponse correcte** : A

**Feedback correct**
Le plomb, au potentiel le plus bas (−0,13 V), est le meilleur réducteur : il s'oxyde à l'anode, libérant des électrons qui circulent dans le fil extérieur vers l'électrode de platine, où le diiode (potentiel le plus élevé, +0,53 V) les capte en se réduisant — c'est la cathode.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les électrons circulent toujours de l'anode (où ils sont libérés par l'oxydation) vers la cathode (où ils sont captés par la réduction) — jamais dans le sens inverse ; ce n'est pas la cathode qui « pousse » les électrons.
- Si C : Le diiode ne migre pas à travers le pont salin pour aller capter des électrons à l'électrode de plomb — la réduction du diiode a lieu à sa propre électrode (cathode) ; seuls des ions assurant l'électroneutralité migrent dans le pont salin.
- Si D : Le circuit extérieur (le fil métallique) est précisément le chemin emprunté par les électrons — c'est le pont salin qui n'est jamais parcouru par des électrons, mais par des ions.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-pile-galvanique-symbo-t2-001
concept: pile-galvanique
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Une pile est construite avec une lame de fer plongée dans $\ce{FeSO4}$ (aq) (E°($\ce{Fe^{2+}/Fe}$) = −0,41 V) et une lame d'argent plongée dans $\ce{AgNO3}$ (aq) (E°($\ce{Ag+/Ag}$) = +0,80 V). Quelle est l'équation globale équilibrée de cette pile ?

**Options**
- A. $\ce{Fe^0 + 2Ag+ -> Fe^{2+} + 2Ag^0}$
- B. $\ce{Fe^0 + Ag+ -> Fe^{2+} + Ag^0}$
- C. $\ce{Fe^{2+} + 2Ag^0 -> Fe^0 + 2Ag+}$
- D. $\ce{2Fe^0 + Ag+ -> 2Fe^{2+} + Ag^0}$

**Réponse correcte** : A

**Feedback correct**
Le fer (E° plus bas) s'oxyde : $\ce{Fe^0 -> Fe^{2+} + 2e-}$. L'argent (E° plus élevé) se réduit : $\ce{Ag+ + e- -> Ag^0}$. Pour égaliser les 2 électrons échangés, on multiplie la demi-réaction de l'argent par 2 : $\ce{2Ag+ + 2e- -> 2Ag^0}$. L'équation globale est donc $\ce{Fe^0 + 2Ag+ -> Fe^{2+} + 2Ag^0}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les électrons ne sont pas équilibrés : le fer cède 2 électrons, mais un seul ion $\ce{Ag+}$ n'en capte qu'un — il faut 2 $\ce{Ag+}$ pour absorber les 2 électrons cédés par chaque atome de fer.
- Si C : Cette équation part des produits ($\ce{Fe^{2+}}$, $\ce{Ag^0}$) pour revenir aux réactifs ($\ce{Fe^0}$, $\ce{Ag+}$) — c'est l'inverse de la réaction spontanée.
- Si D : Les coefficients sont inversés par rapport au bon équilibrage : c'est l'argent (pas le fer) qui doit être doublé pour égaliser les 2 électrons cédés par un seul atome de fer.

**Référence manuel** : oxydo-reduction-pile-galvanique

---

<!-- ============================================================ -->
<!-- CONCEPT : anode — Anode                                       -->
<!-- 5 questions obligatoires : parti·T1, parti·T2×2 (●², misc.   -->
<!-- anode-cathode--inversion-polarite-galvanique-electrolyse),   -->
<!-- symbo·T1, symbo·T2                                            -->
<!-- ============================================================ -->

---
id: q-anode-parti-t1-001
concept: anode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Comment définit-on l'anode d'un dispositif électrochimique (pile ou électrolyse) ?

**Options**
- A. L'électrode où se produit l'oxydation
- B. L'électrode où se produit la réduction
- C. L'électrode reliée au pôle positif du générateur, quel que soit le dispositif
- D. L'électrode la plus grande en surface, quel que soit le dispositif

**Réponse correcte** : A

**Feedback correct**
Par définition, l'anode est l'électrode où se produit l'oxydation — c'est-à-dire la perte d'électrons — que ce soit dans une pile (où elle est le pôle négatif) ou dans une cellule d'électrolyse (où elle est le pôle positif).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est la définition de la cathode, pas de l'anode — le moyen mnémotechnique « CaRé » (Cathode = Réduction) permet de s'en souvenir.
- Si C : Le signe de l'anode dépend du dispositif (négatif en pile, positif en électrolyse) — ce n'est donc pas sa relation au générateur qui la définit, mais le type de réaction (oxydation) qui s'y produit.
- Si D : La taille des électrodes n'a aucun rapport avec la définition de l'anode — seule la nature de la réaction qui s'y produit (oxydation) compte.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-anode-parti-t2-001
concept: anode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: anode-cathode--inversion-polarite-galvanique-electrolyse
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans une pile construite à partir des couples $\ce{Mg^{2+}/Mg}$ (E° = −2,37 V) et $\ce{Ag+/Ag}$ (E° = +0,80 V), quelle électrode est l'anode, et quel est son signe ?

**Options**
- A. Le magnésium est l'anode (il s'oxyde, potentiel le plus bas) ; dans une pile, l'anode est chargée négativement
- B. Le magnésium est l'anode ; dans une pile, l'anode est chargée positivement, comme dans une cellule d'électrolyse
- C. L'argent est l'anode (il a le potentiel le plus élevé) ; l'anode est chargée négativement
- D. Le magnésium est l'anode, mais son signe dépend du sens dans lequel on choisit d'écrire l'équation de la réaction

**Réponse correcte** : A

**Feedback correct**
Le magnésium, au potentiel le plus bas, s'oxyde : c'est l'anode. Dans une pile (contrairement à une cellule d'électrolyse), l'anode est le pôle négatif — c'est de là que partent les électrons vers le circuit extérieur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est précisément l'erreur d'inversion documentée dans la littérature : appliquer la polarité de l'électrolyse (anode positive) à une pile. Dans une pile, l'anode est négative — c'est en électrolyse qu'elle devient positive.
- Si C : L'argent, au potentiel le plus élevé, se réduit — c'est la cathode, pas l'anode. C'est le magnésium (potentiel le plus bas) qui s'oxyde et constitue l'anode.
- Si D : Le signe de l'anode ne dépend pas d'un choix arbitraire d'écriture — il dépend uniquement du type de dispositif (pile ou électrolyse), la réaction se produisant physiquement dans un sens déterminé par les potentiels standard.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-anode-parti-t2-002
concept: anode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: anode-cathode--inversion-polarite-galvanique-electrolyse
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans une cellule d'électrolyse (contrairement à une pile), quel est le signe de l'anode ?

**Options**
- A. Positif — dans une cellule d'électrolyse, l'anode (où se produit toujours l'oxydation) est reliée au pôle positif du générateur externe
- B. Négatif — la polarité de l'anode reste la même que dans une pile, quel que soit le dispositif
- C. Cela dépend uniquement de la nature du métal utilisé comme électrode, pas du type de dispositif
- D. Positif dans certains cas, négatif dans d'autres, selon le sens dans lequel on fait circuler le courant du générateur

**Réponse correcte** : A

**Feedback correct**
L'anode reste, par définition, l'électrode où se produit l'oxydation — mais son signe change selon le dispositif : positif en cellule d'électrolyse (reliée au pôle + du générateur externe qui force la réaction), négatif dans une pile (où l'oxydation se produit spontanément et libère des électrons).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est précisément l'erreur d'inversion documentée : généraliser abusivement la polarité d'un type de dispositif à l'autre. La polarité de l'anode s'inverse bel et bien entre pile (négative) et électrolyse (positive).
- Si C : Le signe de l'anode ne dépend pas de la nature du métal — c'est le type de dispositif (pile ou électrolyse) qui détermine sa polarité, la définition « où se produit l'oxydation » restant, elle, invariante.
- Si D : Le signe de l'anode en électrolyse est toujours positif, de façon fixe — il ne varie pas selon un choix arbitraire de sens de courant ; c'est justement le générateur externe qui impose ce sens et cette polarité positive à l'anode.

**Référence manuel** : oxydo-reduction-electrolyse

---
id: q-anode-symbo-t1-001
concept: anode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans un schéma de pile galvanique, quel symbole doit-on associer à l'électrode où se produit l'oxydation (l'anode) ?

**Options**
- A. Le signe « − » (moins)
- B. Le signe « + » (plus)
- C. Le symbole « e⁻ » directement sur l'électrode, quel que soit le signe
- D. Aucun symbole n'est nécessaire — l'anode se reconnaît uniquement par sa position sur le schéma

**Réponse correcte** : A

**Feedback correct**
Dans une pile galvanique, l'anode (siège de l'oxydation) est le pôle négatif : c'est de là que partent les électrons vers le circuit extérieur. On lui associe donc le signe « − ».

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le signe « + » correspond à la cathode dans une pile, pas à l'anode — attention à ne pas confondre les deux polarités.
- Si C : Le symbole « e⁻ » représente un électron, pas un signe de polarité d'électrode — bien que des électrons soient effectivement libérés à l'anode, ce n'est pas la notation conventionnelle de sa polarité.
- Si D : La position sur un schéma n'est pas une convention universelle (elle varie selon qui dessine le schéma) — le signe (+/−) est la convention standard et sans ambiguïté pour indiquer la polarité d'une électrode.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-anode-symbo-t2-001
concept: anode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Quelle demi-réaction se produit à l'anode de la pile Daniell (électrode de zinc plongée dans $\ce{ZnSO4}$ (aq)) ?

**Options**
- A. $\ce{Zn^0 -> Zn^{2+} + 2e-}$
- B. $\ce{Zn^{2+} + 2e- -> Zn^0}$
- C. $\ce{Cu^{2+} + 2e- -> Cu^0}$
- D. $\ce{SO4^{2-} -> SO4^0 + 2e-}$

**Réponse correcte** : A

**Feedback correct**
L'anode de la pile Daniell est l'électrode de zinc, siège de l'oxydation : $\ce{Zn^0 -> Zn^{2+} + 2e-}$. Les électrons libérés circulent ensuite vers la cathode de cuivre via le circuit extérieur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Cette équation décrit une réduction du zinc (gain d'électrons), pas l'oxydation qui se produit réellement à l'anode de cette pile.
- Si C : C'est la demi-réaction de la cathode (réduction du cuivre), pas de l'anode.
- Si D : Le sulfate $\ce{SO4^{2-}}$ reste spectateur dans la pile Daniell — il ne subit aucune oxydation, son soufre conservant son d.o. tout au long du fonctionnement de la pile.

**Référence manuel** : oxydo-reduction-pile-daniell

---

<!-- ============================================================ -->
<!-- CONCEPT : cathode — Cathode (symétrique à anode)              -->
<!-- 5 questions obligatoires : parti·T1, parti·T2×2 (●², misc.   -->
<!-- anode-cathode--inversion-polarite-galvanique-electrolyse),   -->
<!-- symbo·T1, symbo·T2                                            -->
<!-- ============================================================ -->

---
id: q-cathode-parti-t1-001
concept: cathode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Comment définit-on la cathode d'un dispositif électrochimique (pile ou électrolyse) ?

**Options**
- A. L'électrode où se produit la réduction
- B. L'électrode où se produit l'oxydation
- C. L'électrode reliée au pôle négatif du générateur, quel que soit le dispositif
- D. L'électrode la plus petite en surface, quel que soit le dispositif

**Réponse correcte** : A

**Feedback correct**
Par définition, la cathode est l'électrode où se produit la réduction — c'est-à-dire le gain d'électrons — que ce soit dans une pile (où elle est le pôle positif) ou dans une cellule d'électrolyse (où elle est le pôle négatif). Le moyen mnémotechnique « CaRé » (Cathode = Réduction) permet de s'en souvenir.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est la définition de l'anode, pas de la cathode.
- Si C : Le signe de la cathode dépend du dispositif (positif en pile, négatif en électrolyse) — ce n'est donc pas sa relation au générateur qui la définit, mais le type de réaction (réduction) qui s'y produit.
- Si D : La taille des électrodes n'a aucun rapport avec la définition de la cathode — seule la nature de la réaction qui s'y produit (réduction) compte.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-cathode-parti-t2-001
concept: cathode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: anode-cathode--inversion-polarite-galvanique-electrolyse
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans une pile construite à partir des couples $\ce{Mg^{2+}/Mg}$ (E° = −2,37 V) et $\ce{Ag+/Ag}$ (E° = +0,80 V), quelle électrode est la cathode, et quel est son signe ?

**Options**
- A. L'argent est la cathode (il se réduit, potentiel le plus élevé) ; dans une pile, la cathode est chargée positivement
- B. L'argent est la cathode ; dans une pile, la cathode est chargée négativement, comme dans une cellule d'électrolyse
- C. Le magnésium est la cathode (il a le potentiel le plus bas) ; la cathode est chargée positivement
- D. L'argent est la cathode, mais son signe dépend du sens dans lequel on choisit d'écrire l'équation de la réaction

**Réponse correcte** : A

**Feedback correct**
L'argent, au potentiel le plus élevé, se réduit : c'est la cathode. Dans une pile (contrairement à une cellule d'électrolyse), la cathode est le pôle positif — c'est là qu'arrivent les électrons venus du circuit extérieur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur d'inversion documentée : appliquer la polarité de l'électrolyse (cathode négative) à une pile. Dans une pile, la cathode est positive — c'est en électrolyse qu'elle devient négative.
- Si C : Le magnésium, au potentiel le plus bas, s'oxyde — c'est l'anode, pas la cathode. C'est l'argent (potentiel le plus élevé) qui se réduit et constitue la cathode.
- Si D : Le signe de la cathode ne dépend pas d'un choix arbitraire d'écriture — il dépend uniquement du type de dispositif (pile ou électrolyse).

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-cathode-parti-t2-002
concept: cathode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: anode-cathode--inversion-polarite-galvanique-electrolyse
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans une cellule d'électrolyse (contrairement à une pile), quel est le signe de la cathode ?

**Options**
- A. Négatif — dans une cellule d'électrolyse, la cathode (où se produit toujours la réduction) est reliée au pôle négatif du générateur externe
- B. Positif — la polarité de la cathode reste la même que dans une pile, quel que soit le dispositif
- C. Cela dépend uniquement de la nature du métal utilisé comme électrode, pas du type de dispositif
- D. Négatif dans certains cas, positif dans d'autres, selon le sens dans lequel on fait circuler le courant du générateur

**Réponse correcte** : A

**Feedback correct**
La cathode reste, par définition, l'électrode où se produit la réduction — mais son signe change selon le dispositif : négatif en cellule d'électrolyse (reliée au pôle − du générateur externe), positif dans une pile (où la réduction se produit spontanément en captant les électrons venus du circuit extérieur).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur d'inversion documentée : généraliser abusivement la polarité d'un type de dispositif à l'autre. La polarité de la cathode s'inverse bel et bien entre pile (positive) et électrolyse (négative).
- Si C : Le signe de la cathode ne dépend pas de la nature du métal — c'est le type de dispositif qui détermine sa polarité.
- Si D : Le signe de la cathode en électrolyse est toujours négatif, de façon fixe, imposé par le générateur externe — il ne varie pas selon un choix arbitraire.

**Référence manuel** : oxydo-reduction-electrolyse

---
id: q-cathode-symbo-t1-001
concept: cathode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans un schéma de pile galvanique, quel symbole doit-on associer à l'électrode où se produit la réduction (la cathode) ?

**Options**
- A. Le signe « + » (plus)
- B. Le signe « − » (moins)
- C. Le symbole « e⁻ » directement sur l'électrode, quel que soit le signe
- D. Aucun symbole n'est nécessaire — la cathode se reconnaît uniquement par sa position sur le schéma

**Réponse correcte** : A

**Feedback correct**
Dans une pile galvanique, la cathode (siège de la réduction) est le pôle positif : c'est là qu'arrivent les électrons venus du circuit extérieur. On lui associe donc le signe « + ».

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le signe « − » correspond à l'anode dans une pile, pas à la cathode.
- Si C : Le symbole « e⁻ » représente un électron, pas un signe de polarité d'électrode.
- Si D : La position sur un schéma n'est pas une convention universelle — le signe (+/−) est la convention standard pour indiquer la polarité d'une électrode.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-cathode-symbo-t2-001
concept: cathode
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Quelle demi-réaction se produit à la cathode de la pile Daniell (électrode de cuivre plongée dans $\ce{CuSO4}$ (aq)) ?

**Options**
- A. $\ce{Cu^{2+} + 2e- -> Cu^0}$
- B. $\ce{Cu^0 -> Cu^{2+} + 2e-}$
- C. $\ce{Zn^0 -> Zn^{2+} + 2e-}$
- D. $\ce{SO4^{2-} + 2e- -> SO4^{4-}}$

**Réponse correcte** : A

**Feedback correct**
La cathode de la pile Daniell est l'électrode de cuivre, siège de la réduction : $\ce{Cu^{2+} + 2e- -> Cu^0}$. Les électrons arrivés par le circuit extérieur (depuis l'anode de zinc) sont captés ici par les ions $\ce{Cu^{2+}}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Cette équation décrit une oxydation du cuivre (perte d'électrons), pas la réduction qui se produit réellement à la cathode de cette pile.
- Si C : C'est la demi-réaction de l'anode (oxydation du zinc), pas de la cathode.
- Si D : Le sulfate $\ce{SO4^{2-}}$ reste spectateur dans la pile Daniell — il ne subit aucune réduction ; cette équation ne correspond d'ailleurs à aucune transformation chimique réelle du soufre dans ce contexte.

**Référence manuel** : oxydo-reduction-pile-daniell

---

<!-- ============================================================ -->
<!-- CONCEPT : pont-salin — Pont salin                              -->
<!-- 4 questions obligatoires : macro·T1, parti·T1×2 (●², misc.   -->
<!-- pont-salin--electrons-traversent-solution), parti·T2         -->
<!-- ============================================================ -->

---
id: q-pont-salin-macro-t1-001
concept: pont-salin
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans la pile Daniell « classique » (deux béchers séparés par un long pont salin en papier), le courant disponible est quasi nul, alors que dans la version « concentrique » (électrodes rapprochées, pont salin remplacé par un récipient poreux court et large), le courant atteint environ 0,3 A pour une f.e.m. inchangée d'environ 1,1 V. Comment expliquer cette différence macroscopique ?

**Options**
- A. La résistance du pont salin suit R ∝ L/A : un trajet ionique long et une section étroite (version classique) donnent une résistance énorme, tandis qu'un trajet court et une section large (version concentrique) réduisent fortement cette résistance, permettant un courant bien plus élevé pour la même tension
- B. La f.e.m. elle-même augmente dans la version concentrique, ce qui explique le courant plus élevé
- C. Le pont salin en papier ne conduit aucun ion, contrairement au récipient poreux concentrique — seul ce dernier permet un vrai passage d'ions
- D. La différence provient uniquement de la nature chimique différente du sel utilisé dans les deux versions, pas de leur géométrie

**Réponse correcte** : A

**Feedback correct**
La résistance d'un conducteur ionique suit R ∝ L/A (L = longueur du trajet, A = section disponible). Le pont salin en papier de la version classique impose un trajet long et étroit (résistance de l'ordre du kΩ, voire du MΩ), tandis que la version concentrique rapproche les électrodes et élargit la surface d'échange, réduisant drastiquement cette résistance. La f.e.m. (environ 1,1 V, une grandeur intensive liée aux couples chimiques) reste la même dans les deux cas — c'est la résistance, donc le courant disponible, qui change radicalement.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La f.e.m. est une grandeur intensive qui ne dépend que des couples chimiques en jeu (ici Zn²⁺/Zn et Cu²⁺/Cu dans les deux versions) — elle reste inchangée (≈1,1 V) ; c'est la résistance interne, pas la f.e.m., qui explique la différence de courant.
- Si C : Le pont salin en papier conduit bien des ions — c'est justement pour cela que le voltmètre indique une tension dans la version classique. Le problème est la résistance très élevée de ce trajet, pas une absence totale de conduction.
- Si D : La différence vient de la géométrie (longueur et section du trajet ionique), pas de la nature chimique du sel — les deux versions peuvent utiliser un électrolyte similaire.

**Référence manuel** : oxydo-reduction-pile-daniell

---
id: q-pont-salin-parti-t1-001
concept: pont-salin
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
misconception: pont-salin--electrons-traversent-solution
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans la pile Daniell (anode de zinc, cathode de cuivre), que se passe-t-il réellement dans le pont salin pendant le fonctionnement de la pile ?

**Options**
- A. Des ions (anions vers la demi-pile de zinc, cations vers la demi-pile de cuivre) migrent pour maintenir l'électroneutralité des deux solutions — aucun électron ne traverse le pont salin
- B. Les électrons libérés par l'oxydation du zinc traversent directement le pont salin pour atteindre la demi-pile de cuivre, où ils réduisent les ions $\ce{Cu^{2+}}$
- C. Le pont salin reste totalement inactif tant que le circuit extérieur n'est pas fermé — aucun mouvement d'ions ni d'électrons ne s'y produit jamais
- D. Des atomes de cuivre migrent à travers le pont salin depuis la demi-pile de cuivre vers la demi-pile de zinc, où ils se déposent sur l'électrode

**Réponse correcte** : A

**Feedback correct**
Le pont salin n'est jamais traversé par des électrons — ceux-ci circulent exclusivement dans le fil métallique extérieur. Ce sont des ions qui migrent dans le pont salin : les anions vers la demi-pile de zinc (pour compenser l'excès de $\ce{Zn^{2+}}$ produit par l'oxydation) et les cations vers la demi-pile de cuivre (pour compenser l'appauvrissement en $\ce{Cu^{2+}}$ consommé par la réduction), afin de maintenir l'électroneutralité des deux solutions.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est exactement l'erreur documentée par Sanger & Greenbowe, le nœud de recherche fondateur du domaine : croire que les électrons traversent directement la solution ou le pont salin. Les électrons ne circulent que dans le fil métallique extérieur — jamais en solution.
- Si C : Dès que le circuit extérieur est fermé et que la réaction démarre, la migration ionique dans le pont salin est immédiate et continue — c'est elle qui permet à la pile de fonctionner durablement.
- Si D : Aucun atome métallique ne migre à travers le pont salin — seuls des ions simples (assurant l'électroneutralité, comme K+ et NO3- ou Cl-, présents dans le sel du pont salin lui-même) y circulent.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-pont-salin-parti-t1-002
concept: pont-salin
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
misconception: pont-salin--electrons-traversent-solution
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans une pile construite avec une lame de fer dans $\ce{FeSO4}$ (aq) et une lame d'argent dans $\ce{AgNO3}$ (aq), que se passe-t-il réellement dans le pont salin reliant les deux demi-piles ?

**Options**
- A. Des ions migrent pour maintenir l'électroneutralité des deux solutions (anions vers la demi-pile de fer, qui s'enrichit en $\ce{Fe^{2+}}$ ; cations vers la demi-pile d'argent, qui s'appauvrit en $\ce{Ag+}$) — aucun électron ne traverse le pont salin
- B. Les électrons libérés par l'oxydation du fer traversent directement le pont salin pour atteindre les ions $\ce{Ag+}$ et les réduire
- C. Le pont salin ne joue aucun rôle tant que la pile débite du courant — il ne sert qu'à l'équilibre initial, avant la fermeture du circuit
- D. Des ions $\ce{Ag+}$ migrent à travers le pont salin jusqu'à la demi-pile de fer, où ils se déposent directement sur l'électrode de fer

**Réponse correcte** : A

**Feedback correct**
Comme dans toute pile, le pont salin n'est jamais traversé par des électrons. Ici, des ions migrent pour maintenir l'électroneutralité : des anions vers la demi-pile de fer (qui s'enrichit en $\ce{Fe^{2+}}$ du fait de l'oxydation) et des cations vers la demi-pile d'argent (qui s'appauvrit en $\ce{Ag+}$ du fait de la réduction). Les électrons, eux, circulent exclusivement dans le fil extérieur, du fer vers l'argent.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur documentée : les électrons ne traversent jamais le pont salin ni aucune solution — ils circulent uniquement dans le circuit métallique extérieur, de l'anode (fer) vers la cathode (argent).
- Si C : Le pont salin est actif en continu pendant tout le fonctionnement de la pile, pas seulement à l'équilibre initial — sans sa migration ionique continue, la pile s'arrêterait rapidement (accumulation de charge).
- Si D : Les ions $\ce{Ag+}$ ne migrent pas à travers le pont salin vers l'électrode de fer — ils sont réduits directement à leur propre électrode (la cathode d'argent), où ils captent les électrons arrivés par le fil.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-pont-salin-parti-t2-001
concept: pont-salin
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans une pile construite avec les couples $\ce{Mg^{2+}/Mg}$ (anode) et $\ce{Ag+/Ag}$ (cathode), dans quel sens migrent les cations du pont salin ?

**Options**
- A. Vers la demi-pile d'argent, pour compenser l'appauvrissement en ions $\ce{Ag+}$ consommés par la réduction
- B. Vers la demi-pile de magnésium, pour compenser l'appauvrissement en ions $\ce{Mg^{2+}}$ à cette électrode
- C. Les cations ne migrent jamais dans un pont salin — seuls les anions y circulent, dans les deux sens
- D. Vers la demi-pile d'argent, pour remplacer directement les atomes d'argent métallique qui se déposent sur l'électrode

**Réponse correcte** : A

**Feedback correct**
À la cathode d'argent, la réduction des ions $\ce{Ag+}$ en $\ce{Ag^0}$ appauvrit la solution en cations — les cations du pont salin migrent donc vers cette demi-pile pour compenser ce déficit et maintenir l'électroneutralité. À l'inverse, les anions du pont salin migrent vers la demi-pile de magnésium, où l'oxydation produit un excès de $\ce{Mg^{2+}}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse : à l'anode de magnésium, c'est un excès de cations ($\ce{Mg^{2+}}$) qui est produit par l'oxydation — ce sont donc des anions du pont salin qui migrent vers cette demi-pile pour compenser, pas des cations.
- Si C : Un pont salin permet la migration des deux types d'ions, anions et cations, chacun vers la demi-pile où il est nécessaire pour maintenir l'électroneutralité — jamais un seul type dans les deux sens.
- Si D : Les cations du pont salin (typiquement un cation du sel inerte utilisé) ne se déposent pas sur l'électrode d'argent — seuls les ions $\ce{Ag+}$ de la solution se déposent en captant des électrons ; les cations du pont salin restent en solution, assurant seulement l'électroneutralité.

**Référence manuel** : oxydo-reduction-pile-galvanique

---

<!-- ============================================================ -->
<!-- CONCEPT : force-electromotrice — Force électromotrice (f.e.m.)-->
<!-- 4 questions obligatoires : macro·T1, symbo·T2×2 (●², concept -->
<!-- central), symbo·T3                                            -->
<!-- ============================================================ -->

---
id: q-force-electromotrice-macro-t1-001
concept: force-electromotrice
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
La pile alcaline et la pile Leclanché ont toutes deux une tension (f.e.m.) d'environ 1,5 V, mais des durées de vie très différentes. Comment expliquer que la f.e.m. soit identique alors que la durée de vie diffère ?

**Options**
- A. La f.e.m. est une grandeur intensive, qui ne dépend que des couples chimiques utilisés (mêmes couples dans les deux piles) — la durée de vie dépend en revanche de la quantité de réactifs disponibles (grandeur extensive), qui peut différer entre les deux piles
- B. La f.e.m. dépend de la quantité de réactifs disponibles — les deux piles ont donc nécessairement la même quantité de réactifs, ce qui explique leur tension identique
- C. La durée de vie et la f.e.m. sont en réalité la même grandeur mesurée différemment — leur écart révèle une erreur de mesure sur l'une des deux piles
- D. La f.e.m. identique est une coïncidence sans lien avec les couples chimiques utilisés dans chaque pile

**Réponse correcte** : A

**Feedback correct**
La f.e.m. est une grandeur intensive : elle ne dépend que des couples chimiques en présence (ici, les mêmes couples zinc/dioxyde de manganèse dans les deux piles), pas de leur quantité. La durée de vie, elle, dépend de la quantité de réactifs disponibles (grandeur extensive) — une pile qui contient davantage de réactifs dure plus longtemps, même à tension identique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse : c'est justement parce que la f.e.m. NE dépend PAS de la quantité de réactifs (grandeur intensive) qu'elle peut être identique entre deux piles contenant des quantités différentes de réactifs.
- Si C : La f.e.m. (une tension, en volts) et la durée de vie (un temps, en heures) sont deux grandeurs physiquement différentes, mesurées avec des unités différentes — il ne s'agit pas de la même grandeur ni d'une erreur de mesure.
- Si D : La f.e.m. n'est pas une coïncidence — elle est directement déterminée par les couples chimiques utilisés (E° de chaque électrode) ; deux piles utilisant les mêmes couples ont nécessairement la même f.e.m.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-force-electromotrice-symbo-t2-001
concept: force-electromotrice
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Calculez la force électromotrice standard $\Delta V^\circ$ d'une pile construite à partir des couples $\ce{Pb^{2+}/Pb}$ (E° = −0,13 V) et $\ce{I2/I^-}$ (E° = +0,53 V).

**Options**
- A. $\Delta V^\circ = +0{,}53 − (−0{,}13) = +0{,}66$ V
- B. $\Delta V^\circ = −0{,}13 − (+0{,}53) = −0{,}66$ V
- C. $\Delta V^\circ = +0{,}53 + (−0{,}13) = +0{,}40$ V
- D. $\Delta V^\circ = +0{,}13 − 0{,}53 = −0{,}40$ V

**Réponse correcte** : A

**Feedback correct**
$\Delta V^\circ = E^\circ_{\text{cathode}} − E^\circ_{\text{anode}}$. Le diiode a le potentiel le plus élevé (+0,53 V) : il se réduit, c'est la cathode. Le plomb a le potentiel le plus bas (−0,13 V) : il s'oxyde, c'est l'anode. $\Delta V^\circ = 0{,}53 − (−0{,}13) = +0{,}66$ V.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les rôles cathode/anode sont inversés : c'est le diiode (potentiel le plus élevé) qui est la cathode, pas le plomb — le calcul doit toujours soustraire le potentiel de l'anode (le plus bas) à celui de la cathode (le plus élevé).
- Si C : La formule $\Delta V^\circ = E^\circ_{\text{cathode}} − E^\circ_{\text{anode}}$ est une soustraction, pas une addition — appliquer une addition donne un résultat numériquement erroné.
- Si D : Les deux potentiels sont inversés dans le calcul, et le signe du potentiel du plomb (−0,13 V) n'est pas correctement pris en compte.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-force-electromotrice-symbo-t2-002
concept: force-electromotrice
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Calculez la force électromotrice standard $\Delta V^\circ$ d'une pile construite à partir des couples $\ce{Sn^{2+}/Sn}$ (E° = −0,14 V) et $\ce{Cl2/Cl^-}$ (E° = +1,36 V).

**Options**
- A. $\Delta V^\circ = +1{,}36 − (−0{,}14) = +1{,}50$ V
- B. $\Delta V^\circ = −0{,}14 − (+1{,}36) = −1{,}50$ V
- C. $\Delta V^\circ = +1{,}36 + (−0{,}14) = +1{,}22$ V
- D. $\Delta V^\circ = +0{,}14 − 1{,}36 = −1{,}22$ V

**Réponse correcte** : A

**Feedback correct**
$\Delta V^\circ = E^\circ_{\text{cathode}} − E^\circ_{\text{anode}}$. Le dichlore a le potentiel le plus élevé (+1,36 V) : il se réduit, c'est la cathode. L'étain a le potentiel le plus bas (−0,14 V) : il s'oxyde, c'est l'anode. $\Delta V^\circ = 1{,}36 − (−0{,}14) = +1{,}50$ V.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les rôles cathode/anode sont inversés : c'est le dichlore (potentiel le plus élevé) qui est la cathode, pas l'étain.
- Si C : La formule $\Delta V^\circ = E^\circ_{\text{cathode}} − E^\circ_{\text{anode}}$ est une soustraction, pas une addition.
- Si D : Les deux potentiels sont inversés dans le calcul, et le signe du potentiel de l'étain (−0,14 V) n'est pas correctement pris en compte.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
id: q-force-electromotrice-symbo-t3-001
concept: force-electromotrice
sous-partie: 6C
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
date_validation: 2026-09-14
statut: validated
---

**Question**
Une pile a une force électromotrice standard de +1,56 V. L'une des électrodes est le couple $\ce{Al^{3+}/Al}$ (E° = −1,70 V), qui joue le rôle d'anode. Quel est le potentiel standard de l'autre couple (la cathode) ?

**Options**
- A. $E^\circ_{\text{cathode}} = \Delta V^\circ + E^\circ_{\text{anode}} = 1{,}56 + (−1{,}70) = −0{,}14$ V
- B. $E^\circ_{\text{cathode}} = \Delta V^\circ − E^\circ_{\text{anode}} = 1{,}56 − (−1{,}70) = +3{,}26$ V
- C. $E^\circ_{\text{cathode}} = E^\circ_{\text{anode}} − \Delta V^\circ = −1{,}70 − 1{,}56 = −3{,}26$ V
- D. $E^\circ_{\text{cathode}} = \Delta V^\circ = +1{,}56$ V, indépendamment du potentiel de l'anode

**Réponse correcte** : A

**Feedback correct**
À partir de $\Delta V^\circ = E^\circ_{\text{cathode}} − E^\circ_{\text{anode}}$, on isole $E^\circ_{\text{cathode}} = \Delta V^\circ + E^\circ_{\text{anode}} = 1{,}56 + (−1{,}70) = −0{,}14$ V. C'est le potentiel du couple $\ce{Sn^{2+}/Sn}$ — cohérent avec son rôle de cathode, puisque −0,14 V est bien supérieur à −1,70 V (l'anode).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La formule isolée à partir de $\Delta V^\circ = E^\circ_{\text{cathode}} − E^\circ_{\text{anode}}$ est $E^\circ_{\text{cathode}} = \Delta V^\circ + E^\circ_{\text{anode}}$, pas $\Delta V^\circ − E^\circ_{\text{anode}}$ — cette erreur de signe donne un résultat bien trop élevé et chimiquement peu plausible.
- Si C : Cette formule inverse incorrectement la relation — elle ne correspond à aucune réorganisation valide de $\Delta V^\circ = E^\circ_{\text{cathode}} − E^\circ_{\text{anode}}$.
- Si D : Le potentiel de la cathode dépend à la fois de la f.e.m. mesurée ET du potentiel de l'anode — il ne peut pas être égal à $\Delta V^\circ$ seul, sauf dans le cas particulier où $E^\circ_{\text{anode}} = 0$.

**Référence manuel** : oxydo-reduction-pile-galvanique

---
<!-- ============================================================ -->
<!-- CONCEPT : electrolyse — Électrolyse                            -->
<!-- 5 questions obligatoires : macro·T1, parti·T1, parti·T2×2      -->
<!-- (●², misc. anode-cathode--inversion-polarite-galvanique-       -->
<!-- electrolyse), symbo·T2                                         -->
<!-- ============================================================ -->

---
id: q-electrolyse-macro-t1-001
concept: electrolyse
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
On observe, au cours d'une électrolyse, un dépôt métallique se former sur une électrode pendant qu'un gaz se dégage sur l'autre — deux transformations qui, livrées à elles-mêmes (sans le générateur branché), ne se produiraient pas spontanément entre les espèces en présence. Quel principe fondamental explique cette observation macroscopique ?

**Options**
- A. Le générateur électrique impose un courant qui force une réaction non spontanée à se produire — contrairement à une pile, où c'est au contraire la réaction spontanée qui produit le courant.
- B. Le générateur agit comme un catalyseur qui accélère une réaction qui se produirait de toute façon, mais beaucoup plus lentement, sans lui.
- C. Le dépôt et le dégagement gazeux prouvent que la réaction est spontanée, comme dans une pile galvanique — le générateur ne fait que fournir la différence de potentiel nécessaire pour démarrer une réaction qui, de toute façon, se produirait.
- D. Le générateur ne fait que chauffer localement la solution, ce qui accélère une réaction déjà thermodynamiquement favorable entre les espèces en présence.

**Réponse correcte** : A

**Feedback correct**
L'électrolyse est le processus inverse de la pile galvanique : au lieu de laisser une réaction spontanée produire du courant, on impose un courant pour forcer une réaction qui ne se produirait pas d'elle-même. Le dépôt métallique et le dégagement gazeux observés sont la signature macroscopique de cette transformation forcée par l'apport d'énergie électrique du générateur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Un catalyseur accélère une réaction déjà thermodynamiquement favorable sans changer si elle se produit ou non — ici, au contraire, la réaction ne se produirait pas du tout sans l'apport d'énergie du générateur : ce n'est pas une question de vitesse, mais de spontanéité.
- Si C : Si la réaction était spontanée, elle produirait elle-même un courant en fonctionnant comme une pile, sans qu'il faille lui imposer continuellement de l'énergie électrique pour qu'elle se poursuive — c'est justement l'inverse qui est observé en électrolyse.
- Si D : Le mécanisme n'est pas thermique : le générateur pompe et injecte des électrons aux électrodes, forçant un transfert électronique dans un sens donné — il ne s'agit pas d'un simple effet de chauffage accélérant une réaction déjà favorable.

**Référence manuel** : oxydo-reduction-electrolyse

---
id: q-electrolyse-parti-t1-001
concept: electrolyse
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Au niveau particulaire, comment un générateur électrique parvient-il à inverser le sens naturel des réactions lors d'une électrolyse ?

**Options**
- A. Il pompe des électrons hors d'une électrode (l'anode) et les injecte dans l'autre (la cathode), forçant ainsi l'oxydation à l'anode et la réduction à la cathode, même si ce sens n'est pas celui que suivrait la réaction spontanément.
- B. Il chauffe les deux électrodes de façon asymétrique, ce qui favorise l'oxydation du côté le plus chaud et la réduction du côté le plus froid.
- C. Il modifie directement les degrés d'oxydation des espèces en solution par contact électrique, sans qu'aucun électron ne soit réellement transféré d'une espèce à une autre.
- D. Il augmente uniformément la concentration de tous les ions en solution, ce qui déplace l'équilibre chimique global vers la formation des produits.

**Réponse correcte** : A

**Feedback correct**
Le générateur pompe les électrons hors de l'anode et les injecte à la cathode, inversant le sens naturel des réactions : cela force les anions à céder des électrons (s'oxyder) à l'anode et les cations à en capter (se réduire) à la cathode, même lorsque ce sens ne correspond pas à la réaction spontanée entre ces espèces.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Aucun gradient thermique n'est en jeu dans le mécanisme de l'électrolyse — c'est un mécanisme électrique (pompage/injection d'électrons via la différence de potentiel imposée), pas thermique.
- Si C : Un transfert d'électrons a bel et bien lieu — c'est exactement le mécanisme de l'électrolyse (électrons pompés à l'anode, injectés à la cathode), pas un contournement de ce transfert.
- Si D : Le générateur ne modifie pas uniformément la concentration de toutes les espèces — il force sélectivement un transfert d'électrons à des électrodes précises, ce qui est un mécanisme très différent d'un déplacement d'équilibre par concentration.

**Référence manuel** : oxydo-reduction-electrolyse

---
id: q-electrolyse-parti-t2-001
concept: electrolyse
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: anode-cathode--inversion-polarite-galvanique-electrolyse
date_validation: 2026-09-14
statut: validated
---

**Question**
Lors de l'électrolyse d'une solution aqueuse de $\ce{ZnBr2}$ entre deux électrodes inertes, on observe un dépôt de zinc métallique sur l'une des électrodes et un dégagement de dibrome ($\ce{Br2}$) sur l'autre. Quel est le signe de l'électrode où se forme le dibrome ?

**Options**
- A. Cette électrode est l'anode (siège de l'oxydation des ions $\ce{Br^-}$) ; dans une cellule d'électrolyse, l'anode est reliée au pôle positif (+) du générateur.
- B. Cette électrode est l'anode, mais comme dans une pile galvanique, l'anode est toujours le pôle négatif (−), quel que soit le dispositif utilisé.
- C. Cette électrode est la cathode (siège de la réduction), reliée au pôle négatif (−) du générateur.
- D. Cette électrode est la cathode, reliée au pôle positif (+) du générateur, car en électrolyse tous les signes sont inversés, y compris la nature de la réaction qui s'y produit.

**Réponse correcte** : A

**Feedback correct**
La formation de $\ce{Br2}$ à partir de $\ce{Br^-}$ correspond à une perte d'électrons ($\ce{2Br^- -> Br2 + 2e^-}$) : c'est une oxydation, qui définit l'anode, quel que soit le dispositif. Mais dans une cellule d'électrolyse (contrairement à une pile), le générateur pompe les électrons hors de cette électrode, ce qui la relie au pôle positif (+) du générateur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur classique d'inversion de polarité anode/cathode : dans une pile galvanique, l'anode est bien négative, mais en cellule d'électrolyse, c'est l'inverse — l'anode est positive. Appliquer la convention de signe de la pile à une cellule d'électrolyse donne le mauvais résultat.
- Si C : La formation de $\ce{Br2}$ est une oxydation (perte d'électrons par $\ce{Br^-}$), ce qui définit une anode, pas une cathode (siège de la réduction).
- Si D : Seule la définition anode = oxydation / cathode = réduction reste fixe entre les deux dispositifs — ce sont les signes (+/−) associés à chacune qui s'inversent, pas la nature électrochimique de la réaction elle-même.

**Référence manuel** : oxydo-reduction-electrolyse

---
id: q-electrolyse-parti-t2-002
concept: electrolyse
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
misconception: anode-cathode--inversion-polarite-galvanique-electrolyse
date_validation: 2026-09-14
statut: validated
---

**Question**
Lors de l'électrolyse d'une solution aqueuse de $\ce{NiCl2}$ entre deux électrodes de graphite, un dépôt de nickel métallique gris apparaît sur l'une des électrodes pendant qu'un dégagement de dichlore gazeux se produit sur l'autre. Quel est le signe de l'électrode où se dépose le nickel métallique ?

**Options**
- A. Cette électrode est la cathode (siège de la réduction de $\ce{Ni^{2+}}$ en $\ce{Ni^0}$) ; en cellule d'électrolyse, la cathode est reliée au pôle négatif (−) du générateur.
- B. Cette électrode est la cathode, reliée au pôle positif (+) du générateur — comme dans une pile galvanique, où la cathode est toujours positive.
- C. Cette électrode est l'anode, reliée au pôle positif (+) du générateur, car c'est là que se produit le dépôt métallique, la transformation la plus visible.
- D. Cette électrode est la cathode, reliée au pôle négatif (−), mais uniquement parce que le nickel est un métal réducteur — un non-métal se déposerait plutôt à l'anode.

**Réponse correcte** : A

**Feedback correct**
Le dépôt de nickel métallique correspond à un gain d'électrons ($\ce{Ni^{2+} + 2e^- -> Ni^0}$) : c'est une réduction, qui définit la cathode. Dans une cellule d'électrolyse (contrairement à une pile, où la cathode est positive), le générateur injecte les électrons à cette électrode, ce qui la relie au pôle négatif (−).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'erreur classique d'inversion de polarité : la cathode est bien positive dans une pile galvanique, mais le signe s'inverse en électrolyse — ici la cathode est négative. Appliquer la convention de signe de la pile à une cellule d'électrolyse donne le mauvais résultat.
- Si C : Le dépôt d'un métal à partir de son cation est toujours une réduction (gain d'électrons), ce qui définit par nature la cathode, pas l'anode — quelle que soit la visibilité de la transformation.
- Si D : L'attribution anode/cathode dépend uniquement du type de réaction (oxydation ou réduction) qui s'y produit, pas de la nature métallique ou non de l'espèce déposée ; le signe (+/−) est fixé par le type de cellule (pile ou électrolyse), pas par les propriétés de la substance formée.

**Référence manuel** : oxydo-reduction-electrolyse

---
id: q-electrolyse-symbo-t2-001
concept: electrolyse
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
On réalise l'électrolyse d'une solution aqueuse de $\ce{SnBr2}$ à l'aide de deux électrodes inertes. Les espèces en présence sont $\ce{Sn^{2+}}$, $\ce{Br^-}$ et $\ce{H2O}$ ; la série électrochimique indique que $\ce{Sn^{2+}}$ et $\ce{Br^-}$ sont plus facilement déchargés que l'eau dans ce système. Quelles sont les deux demi-réactions aux électrodes et l'équation globale de cette électrolyse ?

**Options**
- A. Cathode : $\ce{Sn^{2+} + 2e^- -> Sn^0}$ ; Anode : $\ce{2Br^- -> Br2 + 2e^-}$ ; Globale : $\ce{Sn^{2+} + 2Br^- -> Sn^0 + Br2}$
- B. Cathode : $\ce{2Br^- -> Br2 + 2e^-}$ ; Anode : $\ce{Sn^{2+} + 2e^- -> Sn^0}$ ; Globale : $\ce{Sn^{2+} + 2Br^- -> Sn^0 + Br2}$
- C. Cathode : $\ce{2H2O + 2e^- -> H2 + 2OH^-}$ ; Anode : $\ce{2H2O -> O2 + 4H^+ + 4e^-}$ ; Globale : $\ce{2H2O -> 2H2 + O2}$
- D. Cathode : $\ce{Sn^{2+} + 2e^- -> Sn^0}$ ; Anode : $\ce{2Br^- -> Br2 + 2e^-}$ ; Globale : $\ce{Sn^{2+} + Br^- -> Sn^0 + Br2}$

**Réponse correcte** : A

**Feedback correct**
$\ce{Sn^{2+}}$ capte 2 électrons et se réduit à la cathode ($\ce{Sn^{2+} + 2e^- -> Sn^0}$) ; $\ce{Br^-}$ cède des électrons et s'oxyde à l'anode ($\ce{2Br^- -> Br2 + 2e^-}$). Les deux demi-réactions échangent le même nombre d'électrons (2), ce qui permet de les additionner directement pour obtenir l'équation globale équilibrée.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'attribution anode/cathode est inversée — une réduction (gain d'électrons) a toujours lieu à la cathode, pas à l'anode. Ici, c'est $\ce{Sn^{2+}}$ qui gagne des électrons : il doit donc figurer à la cathode, pas $\ce{Br^-}$.
- Si C : $\ce{Sn^{2+}}$ et $\ce{Br^-}$ sont ici plus facilement déchargés que l'eau (d'après la série électrochimique) : ce sont donc eux qui réagissent aux électrodes, pas l'eau. Retomber par défaut sur l'électrolyse de l'eau ignore les espèces réellement présentes et privilégiées dans ce système précis.
- Si D : Les demi-réactions sont correctes, mais l'équation globale n'est pas équilibrée : 2 électrons sont échangés par ion $\ce{Sn^{2+}}$, ce qui nécessite d'oxyder 2 ions $\ce{Br^-}$ (coefficient 2), pas un seul — sinon la charge et le nombre d'électrons ne s'équilibrent pas entre les deux demi-réactions.

**Référence manuel** : oxydo-reduction-electrolyse

---

<!-- ============================================================ -->
<!-- CONCEPT : accumulateur — Accumulateur                         -->
<!-- 4 questions obligatoires : macro·T1, parti·T1, parti·T2,      -->
<!-- symbo·T2                                                       -->
<!-- ============================================================ -->

---
id: q-accumulateur-macro-t1-001
concept: accumulateur
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Un élève affirme qu'une batterie de voiture « se recharge en électricité » — c'est-à-dire que l'énergie électrique fournie par l'alternateur serait stockée telle quelle dans la batterie, prête à être restituée plus tard. Quelle est l'explication correcte du principe de réversibilité d'un accumulateur ?

**Options**
- A. L'énergie électrique reçue lors de la charge est convertie en énergie chimique : le courant force la réaction inverse de la décharge, régénérant les réactifs de départ ($\ce{Pb^0}$ et $\ce{PbO2}$) — l'accumulateur stocke des substances chimiques, pas des électrons.
- B. L'élève a raison : la batterie accumule littéralement des électrons supplémentaires sur ses électrodes pendant la charge, qu'elle relâche ensuite pendant la décharge.
- C. La charge et la décharge sont deux réactions chimiques indépendantes, sans lien entre elles — la charge ne fait que remplacer l'électrolyte usé par de l'acide neuf.
- D. La charge fonctionne comme une pile galvanique ordinaire, avec les mêmes réactions spontanées que la décharge, mais simplement accélérées par le courant du générateur.

**Réponse correcte** : A

**Feedback correct**
La batterie ne stocke pas des électrons, elle stocke des substances chimiques. Lors de la charge, l'énergie électrique reçue est convertie en énergie chimique : le générateur force la réaction inverse de la décharge, reconstituant les réactifs de départ ($\ce{PbSO4}$ redevient $\ce{Pb^0}$ à une électrode et $\ce{PbO2}$ à l'autre).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est exactement la conception naïve que le manuel met en garde : une batterie n'accumule pas d'électrons supplémentaires sur ses électrodes — elle stocke des substances chimiques (les réactifs de la décharge), régénérées par la réaction inverse lors de la charge.
- Si C : La charge n'est pas une réaction indépendante ni un simple remplacement d'électrolyte : c'est précisément la réaction inverse de la décharge (une électrolyse forcée), qui régénère chimiquement les réactifs sur les électrodes elles-mêmes.
- Si D : Lors de la charge, les réactions sont forcées (non spontanées, par électrolyse) — c'est précisément pour cela qu'un générateur est nécessaire : si la réaction de charge était spontanée comme en décharge, elle se produirait d'elle-même sans apport d'énergie externe.

**Référence manuel** : oxydo-reduction-electrolyse

---
id: q-accumulateur-parti-t1-001
concept: accumulateur
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans un accumulateur, pourquoi est-il indispensable que les produits formés lors de la décharge (comme le $\ce{PbSO4}$ dans une batterie au plomb) restent insolubles et adhèrent aux électrodes ?

**Options**
- A. Parce que s'ils se dissolvaient et diffusaient loin des électrodes, le générateur ne pourrait plus les réduire ou les oxyder sur place lors de la charge — les réactifs de départ ne seraient pas régénérés, et l'accumulateur serait détruit après un seul cycle.
- B. Parce qu'un produit soluble conduirait le courant électrique différemment, ce qui empêcherait simplement de mesurer la tension de la batterie.
- C. Parce que la solubilité des produits de décharge n'a aucun lien avec la rechargeabilité — seule la nature du métal des électrodes détermine si un accumulateur est rechargeable.
- D. Parce qu'un produit soluble réagirait spontanément avec l'électrolyte pour former un gaz toxique, rendant la batterie dangereuse plutôt que simplement non rechargeable.

**Réponse correcte** : A

**Feedback correct**
Si $\ce{PbSO4}$ se dissolvait, il diffuserait loin de l'électrode où il s'est formé. Lors de la charge, le générateur ne pourrait alors plus le réduire ou l'oxyder sur place pour régénérer $\ce{Pb^0}$ et $\ce{PbO2}$ : les réactifs ne seraient pas reconstitués, et l'accumulateur serait détruit après un seul cycle de décharge.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'insolubilité n'est pas une question de mesure de tension, mais de position physique des réactifs : c'est le maintien des produits sur l'électrode qui permet leur régénération lors de la charge.
- Si C : La solubilité du produit de décharge est justement le facteur déterminant de la rechargeabilité (c'est pour cette raison que certaines piles sont rechargeables et d'autres non), pas seulement la nature du métal des électrodes.
- Si D : Aucun mécanisme de formation de gaz toxique n'est en jeu ici ; la conséquence réelle de la solubilité est l'impossibilité de régénérer les réactifs sur place, pas un danger chimique de ce type.

**Référence manuel** : oxydo-reduction-electrolyse

---
id: q-accumulateur-parti-t2-001
concept: accumulateur
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans une batterie au plomb, l'électrode de $\ce{PbO2}$ est la cathode (siège de la réduction) lors de la décharge. Que devient cette même électrode lorsqu'on branche un chargeur pour recharger la batterie ?

**Options**
- A. Elle devient l'anode : le chargeur inverse le sens du courant, ce qui inverse aussi le sens de la réaction à cette électrode — le $\ce{PbSO4}$ qui s'y était déposé pendant la décharge est réoxydé en $\ce{PbO2}$.
- B. Elle reste la cathode : l'identité anode/cathode d'une électrode est fixe et ne dépend jamais du sens du courant imposé.
- C. Elle devient l'anode, mais uniquement parce que le $\ce{PbO2}$ est physiquement remplacé par une nouvelle électrode lors de la charge — ce n'est pas la même électrode qui change de rôle.
- D. Elle reste la cathode, car la charge et la décharge produisent toujours les mêmes réactions, dans le même sens, à chaque électrode.

**Réponse correcte** : A

**Feedback correct**
La charge force la réaction inverse de la décharge : à cette électrode, le $\ce{PbSO4}$ formé pendant la décharge (par réduction de $\ce{PbO2}$) est réoxydé en $\ce{PbO2}$ pendant la charge. Cette électrode, cathode (réduction) en décharge, devient donc anode (oxydation) en charge — c'est la même électrode physique, mais son rôle électrochimique s'inverse avec le sens du courant.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'identité anode/cathode d'une électrode est définie par le type de réaction (oxydation ou réduction) qui s'y produit à un instant donné, pas fixée une fois pour toutes — elle s'inverse nécessairement quand le sens du courant s'inverse entre charge et décharge.
- Si C : C'est bien la même électrode physique de $\ce{PbO2}$/$\ce{PbSO4}$ qui change de rôle ; aucun remplacement matériel n'a lieu entre la décharge et la charge.
- Si D : C'est exactement ce que contredit le principe de réversibilité : charge et décharge font fonctionner les réactions dans des sens opposés, ce qui échange nécessairement les rôles anode/cathode des deux électrodes.

**Référence manuel** : oxydo-reduction-electrolyse

---
id: q-accumulateur-symbo-t2-001
concept: accumulateur
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Pour la décharge d'une batterie au plomb, on donne : $E^\circ(\ce{PbO2/PbSO4}) = +1{,}68\ \text{V}$ (en présence de $\ce{SO4^{2-}}$ et $\ce{H^+}$) et $E^\circ(\ce{PbSO4/Pb^0}) = -0{,}36\ \text{V}$ (en présence de $\ce{SO4^{2-}}$). Quelles sont les deux demi-réactions de décharge, avec leurs électrodes ?

**Options**
- A. Anode (oxydation) : $\ce{Pb^0 + SO4^{2-} -> PbSO4 + 2e^-}$ ; Cathode (réduction) : $\ce{PbO2 + SO4^{2-} + 4H^+ + 2e^- -> PbSO4 + 2H2O}$
- B. Anode (oxydation) : $\ce{PbO2 + SO4^{2-} + 4H^+ + 2e^- -> PbSO4 + 2H2O}$ ; Cathode (réduction) : $\ce{Pb^0 + SO4^{2-} -> PbSO4 + 2e^-}$
- C. Anode (oxydation) : $\ce{Pb^0 -> Pb^{2+} + 2e^-}$ ; Cathode (réduction) : $\ce{PbO2 + 4H^+ + 2e^- -> Pb^{2+} + 2H2O}$
- D. Anode (oxydation) : $\ce{Pb^0 + SO4^{2-} -> PbSO4 + 2e^-}$ ; Cathode (réduction) : $\ce{PbO2 + SO4^{2-} + 2H^+ + 2e^- -> PbSO4 + H2O}$

**Réponse correcte** : A

**Feedback correct**
Le couple $E^\circ(\ce{PbSO4/Pb^0}) = -0{,}36\ \text{V}$, le plus faible, est oxydé à l'anode ($\ce{Pb^0}$ cède ses électrons) ; le couple $E^\circ(\ce{PbO2/PbSO4}) = +1{,}68\ \text{V}$, le plus élevé, est réduit à la cathode. Les deux demi-réactions consomment $\ce{SO4^{2-}}$ et forment $\ce{PbSO4}$ (insoluble) aux deux électrodes — la condition nécessaire à la rechargeabilité de l'accumulateur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'attribution est inversée — le couple ayant le potentiel standard le plus élevé (ici $\ce{PbO2/PbSO4}$, +1,68 V) est toujours celui qui se réduit à la cathode ; celui de potentiel le plus faible ($\ce{PbSO4/Pb^0}$, −0,36 V) s'oxyde à l'anode.
- Si C : Cette option ignore le rôle de $\ce{SO4^{2-}}$, pourtant essentiel : la décharge réelle forme du $\ce{PbSO4}$ insoluble aux deux électrodes (condition de réversibilité), pas des ions $\ce{Pb^{2+}}$ solubles.
- Si D : Les demi-réactions ne sont pas équilibrées : réduire $\ce{PbO2}$ (Pb au degré +IV) en $\ce{PbSO4}$ (Pb au degré +II) par un transfert de 2 électrons nécessite 4 $\ce{H^+}$ et forme 2 $\ce{H2O}$, pas 2 $\ce{H^+}$ et 1 $\ce{H2O}$ — sinon l'oxygène et l'hydrogène ne s'équilibrent pas.

**Référence manuel** : oxydo-reduction-electrolyse

---
<!-- ============================================================ -->
<!-- CONCEPT : constante-faraday — Constante de Faraday             -->
<!-- 3 questions obligatoires : macro·T1, parti·T1, symbo·T2        -->
<!-- ============================================================ -->

---
id: q-constante-faraday-macro-t1-001
concept: constante-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Que représente physiquement la constante de Faraday $F \approx 96\ 500\ \text{C/mol}$ ?

**Options**
- A. La charge électrique portée par une mole d'électrons.
- B. La charge électrique portée par un seul électron.
- C. Le nombre d'électrons contenus dans une mole de substance.
- D. L'énergie nécessaire pour déposer une mole de métal par électrolyse.

**Réponse correcte** : A

**Feedback correct**
La constante de Faraday n'est rien d'autre qu'une charge par mole — mais une mole d'électrons : $F = N_A \times e \approx 96\ 500\ \text{C/mol}$, où $N_A$ est le nombre d'Avogadro et $e$ la charge élémentaire d'un électron.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est la charge d'un seul électron ($1{,}602 \times 10^{-19}\ \text{C}$), pas celle d'une mole entière — $F$ est exactement $N_A$ fois cette valeur.
- Si C : Cela confond $F$ avec le nombre d'Avogadro lui-même ; $F$ est une charge (en coulombs), pas un simple dénombrement d'entités.
- Si D : $F$ est une charge (en C/mol), pas une énergie — elle ne représente pas, à elle seule, une quantité d'énergie nécessaire au dépôt.

**Référence manuel** : oxydo-reduction-loi-faraday

---
id: q-constante-faraday-parti-t1-001
concept: constante-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
La constante de Faraday se calcule à partir de deux constantes déjà connues : $F = N_A \times e$. Que représentent ces deux grandeurs ?

**Options**
- A. $N_A$ est le nombre d'Avogadro (nombre d'entités par mole, $6{,}022 \times 10^{23}\ \text{mol}^{-1}$) et $e$ est la charge élémentaire portée par un électron ($1{,}602 \times 10^{-19}\ \text{C}$).
- B. $N_A$ est le nombre d'Avogadro et $e$ est l'énergie de liaison d'un électron dans un atome.
- C. $N_A$ est la masse molaire d'un électron et $e$ est le nombre de moles d'électrons échangées.
- D. $N_A$ est le nombre d'électrons échangés par ion dans une demi-réaction donnée, et $e$ est la charge élémentaire.

**Réponse correcte** : A

**Feedback correct**
En multipliant le nombre d'entités par mole ($N_A$) par la charge portée par chacune d'elles ($e$), on obtient directement la charge portée par une mole d'électrons — c'est-à-dire $F$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $e$ n'est pas une énergie, c'est la charge élémentaire (en coulombs) — une grandeur physique d'une tout autre nature.
- Si C : $N_A$ n'est pas une masse — c'est un nombre pur (d'entités par mole) ; cela le confond avec une masse molaire, une grandeur différente.
- Si D : $N_A$ est une constante universelle fixe, identique quelle que soit la substance étudiée — ce n'est pas le $n_e$ propre à une demi-réaction donnée, une grandeur distincte utilisée séparément dans la loi de Faraday elle-même.

**Référence manuel** : oxydo-reduction-loi-faraday

---
id: q-constante-faraday-symbo-t2-001
concept: constante-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Une électrolyse a fait transiter $0{,}250$ mol d'électrons dans le circuit. Quelle charge électrique totale, en coulombs, cela représente-t-il ?

**Options**
- A. $Q = n(e^-) \times F = 0{,}250 \times 96\ 500 = 24\ 125\ \text{C}$
- B. $Q = n(e^-) / F = 0{,}250 / 96\ 500 = 2{,}59 \times 10^{-6}\ \text{C}$
- C. $Q = n(e^-) \times N_A = 0{,}250 \times 6{,}022 \times 10^{23} = 1{,}51 \times 10^{23}\ \text{C}$
- D. $Q = n(e^-) + F = 0{,}250 + 96\ 500 = 96\ 500{,}25\ \text{C}$

**Réponse correcte** : A

**Feedback correct**
$F$ convertit un nombre de moles d'électrons en charge par simple multiplication : $Q = n(e^-) \times F$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Diviser au lieu de multiplier inverse l'opération — $F$ sert à convertir des moles d'électrons en coulombs par multiplication, pas par division.
- Si C : Multiplier par $N_A$ (le nombre d'Avogadro) donne un nombre d'électrons, pas une charge en coulombs — cette conversion est déjà intégrée dans la valeur de $F$ elle-même.
- Si D : La charge ne s'obtient pas en additionnant $n(e^-)$ et $F$ — ce sont deux grandeurs de nature différente (un nombre de moles et une charge par mole) qui doivent être multipliées, pas sommées.

**Référence manuel** : oxydo-reduction-loi-faraday

---

<!-- ============================================================ -->
<!-- CONCEPT : loi-faraday — Loi de Faraday                         -->
<!-- 7 questions obligatoires : macro·T1, parti·T1, parti·T2,       -->
<!-- symbo·T2×2 (●², misc. loi-faraday--confusion-identite-         -->
<!-- electrode-charge-ion), symbo·T3×2 (●², même misconception)     -->
<!-- ============================================================ -->

---
id: q-loi-faraday-macro-t1-001
concept: loi-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: macro
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Lors d'une électrolyse, quel facteur détermine directement la quantité de matière déposée ou dégagée à une électrode ?

**Options**
- A. Le produit du courant et du temps ($i \times t$, la charge totale écoulée) — et non le courant seul.
- B. Le courant seul : plus le courant est intense, plus il se dépose de matière, indépendamment de la durée de l'électrolyse.
- C. Le temps seul : peu importe l'intensité du courant, seule la durée de l'électrolyse détermine la quantité de matière transformée.
- D. La tension appliquée par le générateur, indépendamment du courant et du temps.

**Réponse correcte** : A

**Feedback correct**
Un courant plus intense dépose automatiquement plus de substance, mais c'est le produit $i \times t$ — la charge totale écoulée — qui détermine la quantité de matière transformée, et non le courant seul.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le courant seul ne suffit pas : un courant intense appliqué très brièvement transfère peu de charge totale, donc dépose peu de matière — c'est le produit $i \times t$ qui compte.
- Si C : Le temps seul ne suffit pas non plus, pour la même raison : un courant très faible pendant longtemps transfère peu de charge — c'est bien le produit des deux qui détermine la quantité déposée.
- Si D : La tension détermine si l'électrolyse est possible (elle doit dépasser la f.e.m. de la réaction spontanée), mais ne détermine pas quantitativement la masse déposée — c'est la charge écoulée ($i \times t$) qui le fait.

**Référence manuel** : oxydo-reduction-loi-faraday

---
id: q-loi-faraday-parti-t1-001
concept: loi-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
Pour une même charge électrique écoulée, pourquoi une mole d'ions $\ce{Cu^{2+}}$ nécessite-t-elle deux fois plus d'électrons qu'une mole d'ions $\ce{Ag+}$ pour être entièrement réduite ?

**Options**
- A. Parce que $\ce{Cu^{2+}}$ est un ion divalent (demi-réaction à 2 électrons) alors que $\ce{Ag+}$ est monovalent (demi-réaction à 1 électron) — la charge ne se convertit pas directement en masse, elle passe par le nombre d'électrons réellement échangés par ion ($n_e$).
- B. Parce que le cuivre a une masse molaire plus élevée que l'argent, ce qui nécessite davantage d'électrons pour déposer la même masse.
- C. Parce que la constante de Faraday $F$ est différente selon l'ion considéré.
- D. Ce n'est pas vrai : pour une même charge écoulée, le nombre de moles de substance déposée est toujours identique, quel que soit l'ion.

**Réponse correcte** : A

**Feedback correct**
Un ion divalent comme $\ce{Cu^{2+}}$ nécessite deux fois plus d'électrons qu'un ion monovalent comme $\ce{Ag+}$ pour déposer la même quantité de matière : la charge ne se convertit pas directement en masse, elle passe par le nombre d'électrons échangés ($n_e$), propre à chaque demi-réaction.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La masse molaire n'a aucun lien avec le nombre d'électrons requis par ion — elle intervient seulement dans le calcul final de la masse ($m = n \times M$), pas dans la valeur de $n_e$, qui dépend uniquement de la charge/l'état d'oxydation de l'ion.
- Si C : $F$ est une constante universelle, identique pour toute substance — elle ne varie jamais selon l'ion électrolysé.
- Si D : C'est faux : le nombre de moles de substance déposée pour une charge donnée dépend directement de $n_e$ — un ion divalent comme $\ce{Cu^{2+}}$ nécessite deux fois plus de charge qu'un ion monovalent comme $\ce{Ag+}$ pour déposer le même nombre de moles.

**Référence manuel** : oxydo-reduction-loi-faraday

---
id: q-loi-faraday-parti-t2-001
concept: loi-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
On électrolyse une solution contenant des ions $\ce{Sn^{4+}}$, réduits selon la demi-réaction $\ce{Sn^{4+} + 4e^- -> Sn^0}$. Quelle valeur de $n_e$ (nombre de moles d'électrons par mole de substance déposée) faut-il utiliser dans la loi de Faraday pour ce dépôt d'étain ?

**Options**
- A. $n_e = 4$, car la demi-réaction montre que 4 moles d'électrons sont nécessaires pour réduire 1 mole d'ions $\ce{Sn^{4+}}$.
- B. $n_e = 1$, car un seul ion $\ce{Sn^{4+}}$ est réduit dans la demi-réaction.
- C. $n_e = 96\ 500$, en utilisant directement la valeur de la constante de Faraday comme valeur de $n_e$.
- D. $n_e = 2$, en supposant l'état d'oxydation +II plus courant de l'étain, sans tenir compte de la demi-réaction donnée qui montre ici l'étain au degré +IV.

**Réponse correcte** : A

**Feedback correct**
$n_e$ se lit directement dans le coefficient stœchiométrique des électrons de la demi-réaction donnée : ici, 4 électrons sont échangés par ion $\ce{Sn^{4+}}$ réduit.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Compter le nombre d'ions réduits (1) au lieu du nombre d'électrons échangés par ion (4) confond deux grandeurs différentes — $n_e$ se lit dans le coefficient des électrons de la demi-réaction, pas dans le nombre de formules de l'ion.
- Si C : Cela confond $n_e$ (un petit entier stœchiométrique, sans unité) avec $F$ (une constante physique, en C/mol) — deux grandeurs de nature complètement différente utilisées ensemble dans la même formule, mais jamais interchangeables.
- Si D : L'étain peut exister au degré +II dans d'autres composés, mais la demi-réaction donnée ici montre explicitement $\ce{Sn^{4+}}$ (degré +IV) échangeant 4 électrons — il faut toujours lire $n_e$ dans la demi-réaction fournie, pas supposer un état d'oxydation par habitude.

**Référence manuel** : oxydo-reduction-loi-faraday

---
id: q-loi-faraday-symbo-t2-001
concept: loi-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
misconception: loi-faraday--confusion-identite-electrode-charge-ion
date_validation: 2026-09-14
statut: validated
---

**Question**
On électrolyse une solution de $\ce{AgNO3}$ avec un courant de $2{,}00\ \text{A}$ pendant $15{,}0\ \text{min}$. Sachant que $M(\ce{Ag}) = 107{,}9\ \text{g/mol}$ et que la demi-réaction est $\ce{Ag+ + e^- -> Ag^0}$, quelle masse d'argent se dépose à la cathode ?

**Options**
- A. $Q = 2{,}00 \times 900 = 1\ 800\ \text{C}$ ; $n(e^-) = 1\ 800/96\ 500 = 0{,}01865\ \text{mol}$ ; $n(\ce{Ag}) = 0{,}01865\ \text{mol}$ (car $n_e = 1$) ; $m = 0{,}01865 \times 107{,}9 = 2{,}01\ \text{g}$
- B. Même $Q = 1\ 800\ \text{C}$ et $n(e^-) = 0{,}01865\ \text{mol}$, mais avec $n_e = 2$ (en supposant, par réflexe, un ion divalent) : $n(\ce{Ag}) = 0{,}01865/2 = 0{,}00933\ \text{mol}$ ; $m = 0{,}00933 \times 107{,}9 = 1{,}01\ \text{g}$
- C. $Q = 2{,}00 \times 15{,}0 = 30{,}0\ \text{C}$ (en oubliant de convertir les minutes en secondes) ; $n(\ce{Ag}) = 30{,}0/96\ 500 = 3{,}11 \times 10^{-4}\ \text{mol}$ ; $m = 3{,}11 \times 10^{-4} \times 107{,}9 = 0{,}0336\ \text{g}$
- D. $m = i \times t \times M = 2{,}00 \times 900 \times 107{,}9 = 194\ 220\ \text{g}$, sans jamais passer par $F$ ni par $n_e$

**Réponse correcte** : A

**Feedback correct**
$Q = i \times t = 1\ 800\ \text{C}$ ; $n(e^-) = Q/F = 0{,}01865\ \text{mol}$ ; comme $\ce{Ag+}$ n'échange qu'un seul électron ($n_e = 1$), $n(\ce{Ag}) = n(e^-)$ ; $m = n(\ce{Ag}) \times M = 2{,}01\ \text{g}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $n_e$ doit se lire dans la demi-réaction réellement donnée ($\ce{Ag+ + e^- -> Ag^0}$, un seul électron), pas être supposé égal à 2 par réflexe pour un ion « typique » — c'est exactement la confusion documentée entre l'identité réelle de l'espèce qui se décharge et un nombre d'électrons présumé.
- Si C : Oublier de convertir les minutes en secondes donne une charge 60 fois trop petite — le temps doit être exprimé en secondes (SI) avant de calculer $Q = i \times t$.
- Si D : Cette option court-circuite toute la chaîne physique (charge → moles d'électrons → moles de substance → masse) : la masse ne s'obtient pas en multipliant directement $i$, $t$ et $M$ — $F$ et $n_e$ doivent impérativement apparaître dans le calcul.

**Référence manuel** : oxydo-reduction-loi-faraday

---
id: q-loi-faraday-symbo-t2-002
concept: loi-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
misconception: loi-faraday--confusion-identite-electrode-charge-ion
date_validation: 2026-09-14
statut: validated
---

**Question**
On électrolyse une solution de $\ce{NiCl2}$ avec un courant de $4{,}00\ \text{A}$ pendant $20{,}0\ \text{min}$. Sachant que $M(\ce{Ni}) = 58{,}69\ \text{g/mol}$ et que la demi-réaction est $\ce{Ni^{2+} + 2e^- -> Ni^0}$, quelle masse de nickel se dépose à la cathode ?

**Options**
- A. $Q = 4{,}00 \times 1\ 200 = 4\ 800\ \text{C}$ ; $n(e^-) = 4\ 800/96\ 500 = 0{,}04974\ \text{mol}$ ; $n(\ce{Ni}) = 0{,}04974/2 = 0{,}02487\ \text{mol}$ ; $m = 0{,}02487 \times 58{,}69 = 1{,}46\ \text{g}$
- B. Même $n(e^-) = 0{,}04974\ \text{mol}$, mais avec $n_e = 1$ (en supposant, par réflexe, un seul électron échangé comme pour un ion monovalent) : $n(\ce{Ni}) = 0{,}04974\ \text{mol}$ ; $m = 0{,}04974 \times 58{,}69 = 2{,}92\ \text{g}$
- C. $Q = 4{,}00 \times 20{,}0 = 80{,}0\ \text{C}$ (en oubliant de convertir les minutes en secondes) ; $n(e^-) = 80{,}0/96\ 500 = 8{,}29 \times 10^{-4}\ \text{mol}$ ; $n(\ce{Ni}) = 4{,}15 \times 10^{-4}\ \text{mol}$ ; $m = 4{,}15 \times 10^{-4} \times 58{,}69 = 0{,}0244\ \text{g}$
- D. $n(\ce{Ni}) = 0{,}02487\ \text{mol}$ correctement calculé, mais présenté directement comme la masse en grammes, sans multiplier par $M$ : $m = 0{,}02487\ \text{g}$

**Réponse correcte** : A

**Feedback correct**
$Q = i \times t = 4\ 800\ \text{C}$ ; $n(e^-) = Q/F = 0{,}04974\ \text{mol}$ ; comme $\ce{Ni^{2+}}$ échange 2 électrons ($n_e = 2$), $n(\ce{Ni}) = n(e^-)/n_e = 0{,}02487\ \text{mol}$ ; $m = n(\ce{Ni}) \times M = 1{,}46\ \text{g}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $n_e$ doit se lire dans la demi-réaction réellement donnée ($\ce{Ni^{2+} + 2e^- -> Ni^0}$, deux électrons), pas être supposé égal à 1 par réflexe — c'est exactement la confusion documentée entre l'identité réelle de l'espèce qui se décharge et un nombre d'électrons présumé.
- Si C : Oublier de convertir les minutes en secondes donne une charge 60 fois trop petite — le temps doit être exprimé en secondes avant de calculer $Q = i \times t$.
- Si D : $n(\ce{Ni})$ est un nombre de MOLES, pas une masse en grammes — l'étape finale $m = n \times M$ est indispensable et a été oubliée ici.

**Référence manuel** : oxydo-reduction-loi-faraday

---
id: q-loi-faraday-symbo-t3-001
concept: loi-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
misconception: loi-faraday--confusion-identite-electrode-charge-ion
date_validation: 2026-09-14
statut: validated
---

**Question**
Deux cuves électrolytiques sont montées **en série** : l'une contient du $\ce{NiCl2}$ (demi-réaction $\ce{Ni^{2+} + 2e^- -> Ni^0}$), l'autre du $\ce{PtCl4}$ (demi-réaction $\ce{Pt^{4+} + 4e^- -> Pt^0}$). On obtient un dépôt de $37{,}2\ \text{g}$ de nickel à la cathode de la première cuve. Quelle masse de platine s'est déposée en même temps dans la seconde cuve ? ($M(\ce{Ni}) = 58{,}69\ \text{g/mol}$, $M(\ce{Pt}) = 195{,}08\ \text{g/mol}$)

**Options**
- A. $n(\ce{Ni}) = 37{,}2/58{,}69 = 0{,}634\ \text{mol}$ ; $Q = n(\ce{Ni}) \times 2 \times 96\ 500 \approx 122\ 400\ \text{C}$ (charge commune aux deux cuves montées en série) ; $n(\ce{Pt}) = Q/(4 \times 96\ 500) \approx 0{,}317\ \text{mol}$ ; $m(\ce{Pt}) = 0{,}317 \times 195{,}08 \approx 61{,}8\ \text{g}$
- B. Comme la charge est la même dans les deux cuves en série, on suppose qu'elle y dépose le même nombre de moles, sans tenir compte du nombre d'électrons propre à chaque ion : $n(\ce{Pt}) = n(\ce{Ni}) = 0{,}634\ \text{mol}$ ; $m(\ce{Pt}) = 0{,}634 \times 195{,}08 \approx 123{,}7\ \text{g}$
- C. $Q \approx 122\ 400\ \text{C}$ (calculé correctement), mais avec $n_e(\ce{Pt}) = 1$ (en assimilant $\ce{Pt^{4+}}$ à un ion monovalent) : $n(\ce{Pt}) = 122\ 400/96\ 500 \approx 1{,}268\ \text{mol}$ ; $m(\ce{Pt}) \approx 1{,}268 \times 195{,}08 \approx 247{,}4\ \text{g}$
- D. $n(e^-)$ pour le nickel calculé avec $n_e(\ce{Ni}) = 1$ au lieu de 2 : $n(e^-) = 0{,}634\ \text{mol}$ ; $Q = 0{,}634 \times 96\ 500 \approx 61\ 200\ \text{C}$ ; $n(\ce{Pt}) = 61\ 200/(4 \times 96\ 500) \approx 0{,}159\ \text{mol}$ ; $m(\ce{Pt}) \approx 0{,}159 \times 195{,}08 \approx 31{,}0\ \text{g}$

**Réponse correcte** : A

**Feedback correct**
Deux cuves montées en série sont traversées par la même charge $Q$ (même courant, même durée). Cette charge commune doit ensuite être convertie séparément en moles de chaque substance, en utilisant le $n_e$ propre à chaque ion ($n_e(\ce{Ni}) = 2$, $n_e(\ce{Pt}) = 4$) : $Q = n(\ce{Ni}) \times n_e(\ce{Ni}) \times F$, puis $n(\ce{Pt}) = Q/(n_e(\ce{Pt}) \times F)$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est exactement le type d'erreur que documente la confusion identité électrode/charge de l'ion : supposer qu'une même charge dépose le même nombre de moles partout ignore que $\ce{Ni^{2+}}$ et $\ce{Pt^{4+}}$ n'échangent pas le même nombre d'électrons ($n_e = 2$ contre $n_e = 4$) — le nombre de moles déposées est inversement proportionnel au $n_e$ propre à chaque ion, pas identique.
- Si C : $n_e$ pour $\ce{Pt^{4+}}$ vaut 4 (quatre électrons sont nécessaires pour réduire $\ce{Pt^{4+}}$ en $\ce{Pt^0}$), pas 1 — assumer un échange à un seul électron ignore la charge réelle de l'ion tel qu'indiqué dans sa propre demi-réaction de réduction.
- Si D : $n_e$ pour $\ce{Ni^{2+}}$ vaut 2 (d'après $\ce{Ni^{2+} + 2e^- -> Ni^0}$), pas 1 — cette erreur se propage dans tout le calcul et produit une charge (et donc une masse de platine) deux fois trop faible.

**Référence manuel** : oxydo-reduction-loi-faraday

---
id: q-loi-faraday-symbo-t3-002
concept: loi-faraday
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
misconception: loi-faraday--confusion-identite-electrode-charge-ion
date_validation: 2026-09-14
statut: validated
---

**Question**
Lors de l'électrolyse de l'eau, combien de temps faut-il, avec un courant de $3{,}00\ \text{A}$, pour dégager $0{,}750\ \text{L}$ de $\ce{O2}$ à TPA ($24{,}5\ \text{L/mol}$) à l'anode ? (Demi-réaction anodique : $\ce{2H2O -> O2 + 4H^+ + 4e^-}$)

**Options**
- A. $n(\ce{O2}) = 0{,}750/24{,}5 = 0{,}03061\ \text{mol}$ ; $n(e^-) = 0{,}03061 \times 4 = 0{,}12245\ \text{mol}$ (car $n_e = 4$ par mole de $\ce{O2}$) ; $Q = 0{,}12245 \times 96\ 500 \approx 11\ 816\ \text{C}$ ; $t = Q/i = 11\ 816/3{,}00 \approx 3\ 939\ \text{s} \approx 65{,}6\ \text{min}$
- B. Même $n(\ce{O2}) = 0{,}03061\ \text{mol}$, mais avec $n_e = 2$ (coefficient de la demi-réaction cathodique de $\ce{H2}$, appliqué par erreur à $\ce{O2}$) : $n(e^-) = 0{,}06122\ \text{mol}$ ; $Q \approx 5\ 908\ \text{C}$ ; $t \approx 1\ 969\ \text{s} \approx 32{,}8\ \text{min}$
- C. $n(\ce{O2}) = 0{,}750/22{,}4 = 0{,}03348\ \text{mol}$ (en utilisant le volume molaire à TPN au lieu de TPA) ; $n(e^-) = 0{,}13393\ \text{mol}$ ; $Q \approx 12\ 924\ \text{C}$ ; $t \approx 4\ 308\ \text{s} \approx 71{,}8\ \text{min}$
- D. $n(e^-) = 0{,}12245\ \text{mol}$ (correctement calculé), mais utilisé directement comme s'il s'agissait de $Q$ en coulombs : $t = 0{,}12245/3{,}00 \approx 0{,}0408\ \text{s}$

**Réponse correcte** : A

**Feedback correct**
La demi-réaction anodique montre que 4 électrons sont échangés par mole de $\ce{O2}$ dégagée. On convertit donc le volume en moles (via le volume molaire à TPA), les moles de $\ce{O2}$ en moles d'électrons (via $n_e = 4$), puis en charge (via $F$), et enfin en temps (via $i$).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $n_e = 2$ est le coefficient de la demi-réaction cathodique, qui produit du $\ce{H2}$ ($\ce{2H2O + 2e^- -> H2 + 2OH^-}$), pas celle de l'anode qui produit réellement le $\ce{O2}$ demandé ici (4 électrons) — confondre le $n_e$ d'une électrode avec celui de l'autre est exactement le type d'erreur documenté par cette confusion.
- Si C : Le volume molaire à TPN ($22{,}4\ \text{L/mol}$) ne correspond pas aux conditions TPA précisées dans l'énoncé ($24{,}5\ \text{L/mol}$) — il faut toujours utiliser le volume molaire correspondant aux conditions réellement données.
- Si D : $n(e^-)$ (en moles) et $Q$ (en coulombs) sont deux grandeurs différentes : $Q = n(e^-) \times F$, et non $Q = n(e^-)$ directement — l'étape de conversion par $F$ a été sautée ici.

**Référence manuel** : oxydo-reduction-loi-faraday

---
<!-- ============================================================ -->
<!-- CONCEPT : loi-nernst — Loi de Nernst                           -->
<!-- 4 questions obligatoires : parti·T1, symbo·T2, symbo·T3×2      -->
<!-- (●², culmination structurelle — principe 7, critère 2,         -->
<!-- pas de misconception externe documentée)                       -->
<!-- ============================================================ -->

---
id: q-loi-nernst-parti-t1-001
concept: loi-nernst
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: parti
type: 1
date_validation: 2026-09-14
statut: validated
---

**Question**
D'après la loi de Nernst, comment le potentiel d'une électrode évolue-t-il lorsque la concentration de l'espèce oxydante ($\text{Ox}$) diminue par rapport à celle du réducteur ($\text{Red}$) ?

**Options**
- A. Le potentiel de réduction diminue : moins concentrée, l'espèce oxydante « attire » moins facilement les électrons.
- B. Le potentiel de réduction augmente : une espèce oxydante plus diluée devient paradoxalement plus réactive.
- C. Le potentiel reste rigoureusement égal à $E^\circ$, tant que la réaction reste possible.
- D. Le potentiel devient négatif dès que la concentration s'écarte de la valeur standard de 1 mol/L, quel que soit le sens de l'écart.

**Réponse correcte** : A

**Feedback correct**
Plus la concentration en espèce oxydante est faible par rapport au réducteur, moins l'électrode « attire » facilement les électrons — son potentiel de réduction diminue. À l'inverse, une concentration en oxydant plus élevée que la référence standard augmente le potentiel.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse — diluer l'oxydant rend l'électrode moins apte à attirer des électrons, ce qui fait diminuer le potentiel, pas augmenter.
- Si C : $E^\circ$ n'est le potentiel qu'à la concentration de référence (1 mol/L) ; dès que la concentration réelle s'en écarte, le potentiel réel $E$ diffère de $E^\circ$ — c'est précisément ce que corrige le terme logarithmique de la loi de Nernst.
- Si D : Le sens de l'écart dépend de la direction du changement de concentration : un oxydant plus concentré que la référence augmente le potentiel, un oxydant plus dilué le diminue — ce n'est pas systématiquement négatif.

**Référence manuel** : oxydo-reduction-pile-volta-nernst

---
id: q-loi-nernst-symbo-t2-001
concept: loi-nernst
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 2
date_validation: 2026-09-14
statut: validated
---

**Question**
Quel est le potentiel de l'électrode $\ce{Ag+/Ag^0}$ ($E^\circ = +0{,}80\ \text{V}$, $n = 1$) plongée dans une solution où $[\ce{Ag+}] = 1{,}0 \times 10^{-3}\ \text{mol/L}$ ?

**Options**
- A. $E = 0{,}80 + 0{,}059 \log(1{,}0 \times 10^{-3}) = 0{,}80 - 0{,}18 \approx 0{,}62\ \text{V}$
- B. $E = 0{,}80 - 0{,}059 \log(1{,}0 \times 10^{-3}) = 0{,}80 + 0{,}18 \approx 0{,}98\ \text{V}$
- C. $E = 0{,}80 + \dfrac{0{,}059}{1} \times (1{,}0 \times 10^{-3}) \approx 0{,}80\ \text{V}$ (variation quasi nulle)
- D. $E = E^\circ = 0{,}80\ \text{V}$, car la loi de Nernst ne s'applique qu'aux concentrations supérieures à 1 mol/L.

**Réponse correcte** : A

**Feedback correct**
$E = E^\circ + \frac{0{,}059}{n}\log\frac{[\text{Ox}]}{[\text{Red}]}$ ; ici $n = 1$ et $\ce{Ag^0}$ (solide, activité 1) : $E = 0{,}80 + 0{,}059\log(1{,}0 \times 10^{-3}) = 0{,}80 - 0{,}177 \approx 0{,}62\ \text{V}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Soustraire le terme logarithmique au lieu de l'additionner inverse le sens de la correction — ici $[\ce{Ag+}]$ est sous la concentration standard, donc le potentiel doit diminuer, pas augmenter.
- Si C : Le terme de correction de Nernst multiplie $0{,}059/n$ par le LOGARITHME de la concentration, pas par la concentration elle-même — la correction est logarithmique, pas linéaire.
- Si D : La loi de Nernst s'applique à toute concentration, pas seulement au-dessus de 1 mol/L — elle est justement conçue pour corriger $E^\circ$ lorsque la concentration s'écarte de la référence standard, dans un sens comme dans l'autre.

**Référence manuel** : oxydo-reduction-pile-volta-nernst

---
id: q-loi-nernst-symbo-t3-001
concept: loi-nernst
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
date_validation: 2026-09-14
statut: validated
---

**Question**
Dans la pile de Volta (zinc / eau salée neutre), la précipitation de $\ce{Zn(OH)2}$ ($K_s = 1{,}8 \times 10^{-14}$) limite la concentration de $\ce{Zn^{2+}}$ à l'équilibre. Sachant que $[\ce{OH-}] = 2s$ où $s = [\ce{Zn^{2+}}]$, et que $E^\circ(\ce{Zn^{2+}/Zn^0}) = -0{,}76\ \text{V}$ ($n = 2$), quel est le potentiel corrigé de l'électrode de zinc ?

**Options**
- A. $K_s = s(2s)^2 = 4s^3 \Rightarrow s = \sqrt[3]{K_s/4} \approx 1{,}65 \times 10^{-5}\ \text{mol/L}$ ; $E = -0{,}76 + \dfrac{0{,}059}{2}\log(1{,}65 \times 10^{-5}) \approx -0{,}76 - 0{,}14 \approx -0{,}90\ \text{V}$
- B. $s = \sqrt{K_s} \approx 1{,}34 \times 10^{-7}\ \text{mol/L}$ (en ignorant le facteur 4 et l'exposant 3 propres à la stœchiométrie de précipitation) ; $E \approx -0{,}76 - 0{,}19 \approx -0{,}95\ \text{V}$
- C. $s \approx 1{,}65 \times 10^{-5}\ \text{mol/L}$ (calculé correctement), mais en oubliant de diviser par $n = 2$ dans le terme de Nernst : $E = -0{,}76 + 0{,}059\log(1{,}65 \times 10^{-5}) \approx -1{,}05\ \text{V}$
- D. $s \approx 1{,}65 \times 10^{-5}\ \text{mol/L}$ (calculé correctement), mais sans jamais appliquer de correction de Nernst, car « la précipitation ne change pas le potentiel standard » : $E = E^\circ = -0{,}76\ \text{V}$

**Réponse correcte** : A

**Feedback correct**
$\ce{Zn(OH)2}$ se dissocie en $\ce{Zn^{2+}} + \ce{2OH^-}$ : avec $[\ce{OH-}] = 2s$, on a $K_s = s \times (2s)^2$, soit $K_s = 4s^3$, d'où $s \approx 1{,}65 \times 10^{-5}\ \text{mol/L}$. En injectant cette concentration très inférieure à 1 mol/L dans la loi de Nernst, le potentiel de l'électrode de zinc chute à environ $-0{,}90\ \text{V}$ — bien plus négatif que $E^\circ$, ce qui résout le paradoxe apparent de la pile de Volta.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Cette option ignore la stœchiométrie réelle de l'équilibre de précipitation — pour $\ce{Zn(OH)2}$, on a $K_s = [\ce{Zn^{2+}}][\ce{OH^-}]^2$, ce qui donne une fois développé $K_s = 4s^3$ (le facteur 4 et l'exposant 3 viennent du fait que $[\ce{OH^-}]$ vaut le double de $[\ce{Zn^{2+}}]$) ; traiter cela comme une simple racine carrée de $K_s$ ignore cette relation.
- Si C : $n = 2$ pour le couple $\ce{Zn^{2+}/Zn^0}$ (deux électrons échangés) doit obligatoirement apparaître au dénominateur du terme de correction ($0{,}059/n$) ; l'omettre double la correction et fausse le potentiel obtenu.
- Si D : C'est exactement le point de cet exemple travaillé : la précipitation abaisse réellement la concentration de $\ce{Zn^{2+}}$ très en dessous de 1 mol/L, et la loi de Nernst doit être appliquée pour corriger $E^\circ$ en conséquence — sans cette correction, le paradoxe (la pile de Volta ne devrait pas fonctionner selon les potentiels standard seuls) n'est jamais résolu.

**Référence manuel** : oxydo-reduction-pile-volta-nernst

---
id: q-loi-nernst-symbo-t3-002
concept: loi-nernst
sous-partie: 6D
chapitre: oxydo-reduction
niveau: DF+OS
r1: symbo
type: 3
date_validation: 2026-09-14
statut: validated
---

**Question**
Si le $K_s$ de $\ce{Zn(OH)2}$ valait $1{,}8 \times 10^{-16}$ (soit 100 fois plus petit que la valeur utilisée dans l'exemple travaillé de la pile de Volta), quel serait le nouveau potentiel corrigé de l'électrode de zinc ? ($E^\circ(\ce{Zn^{2+}/Zn^0}) = -0{,}76\ \text{V}$, $n = 2$)

**Options**
- A. $s' = \sqrt[3]{K_s'/4} = \sqrt[3]{4{,}5 \times 10^{-17}} \approx 3{,}56 \times 10^{-6}\ \text{mol/L}$ ; $E = -0{,}76 + \dfrac{0{,}059}{2}\log(3{,}56 \times 10^{-6}) \approx -0{,}76 - 0{,}16 \approx -0{,}92\ \text{V}$
- B. Un $K_s$ 100 fois plus petit donnerait une concentration $s'$ également 100 fois plus petite (en ignorant que $s$ dépend de $K_s$ par une racine cubique, pas une proportion directe) : $s' \approx 1{,}65 \times 10^{-7}\ \text{mol/L}$ ; $E \approx -0{,}76 - 0{,}20 \approx -0{,}96\ \text{V}$
- C. $s' \approx 3{,}56 \times 10^{-6}\ \text{mol/L}$ (calculé correctement), mais interprété comme signifiant une précipitation moins complète, donc un potentiel corrigé moins négatif (plus proche de $E^\circ$) : $E \approx -0{,}80\ \text{V}$
- D. $s'$ calculé correctement, mais avec le terme de correction ajouté en valeur absolue au lieu d'être soustrait : $E \approx -0{,}76 + 0{,}16 \approx -0{,}60\ \text{V}$

**Réponse correcte** : A

**Feedback correct**
$s$ et $K_s$ sont reliés par une racine cubique ($s = \sqrt[3]{K_s/4}$) : un $K_s$ 100 fois plus petit donne un $s'$ environ $\sqrt[3]{100} \approx 4{,}64$ fois plus petit, soit $s' \approx 3{,}56 \times 10^{-6}\ \text{mol/L}$. Cette concentration encore plus faible abaisse davantage le potentiel corrigé, à environ $-0{,}92\ \text{V}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $K_s$ et $s$ ne sont pas directement proportionnels — leur relation passe par une racine cubique ($s = \sqrt[3]{K_s/4}$) : un $K_s$ 100 fois plus petit donne un $s'$ environ $4{,}64$ fois plus petit (racine cubique de 100), pas 100 fois plus petit.
- Si C : Un $K_s$ plus petit signifie au contraire que le solide précipite plus facilement (à une concentration ionique plus basse), ce qui abaisse encore davantage $[\ce{Zn^{2+}}]$ et rend la correction de Nernst plus importante (potentiel plus négatif), pas moins — l'inverse de ce qu'affirme cette option.
- Si D : Le signe du terme logarithmique découle directement de la loi de Nernst elle-même ; comme la concentration est très inférieure à la référence standard, $\log(s')$ est négatif, et la correction doit être soustraite de $E^\circ$, pas additionnée — inverser ce signe place le résultat du mauvais côté de $E^\circ$.

**Référence manuel** : oxydo-reduction-pile-volta-nernst

---
