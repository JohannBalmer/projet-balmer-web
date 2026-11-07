# Banque de questions validées — Chapitre 08
# Thermochimie 1 — enthalpie
# Slug : thermochimie-1

_Projet-Balmer / Balmer-Cloud — Généré le 2026-10-05_
_51 questions obligatoires — couverture minimale complète (10 concepts, cellules ● de `matrice-concepts-thermochimie-1.md`) — relues et validées par LUM le 2026-10-05._

---

<!-- LÉGENDE
Niveau R1 : macro = macroscopique | parti = particulaire | symbo = symbolique
Niveau    : sou = se souvenir | com = comprendre | app = appliquer | ana = analyser | eva = évaluer (Anderson & Krathwohl, 2001)
Statut    : validated | rejected | to_fix
Niveau    : OS (chapitre entier, voir toc.yaml)
-->

---

<!-- ============================================================ -->
<!-- LOT 1 — Enthalpie et réactions exo/endothermiques            -->
<!-- Concepts : enthalpie, reaction-exothermique, reaction-endothermique -->
<!-- 16 questions obligatoires (6 + 7 + 3)                         -->
<!-- ============================================================ -->

---
id: q-enthalpie-macro-com-001
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Vous posez la main sur une casserole qui chauffe au gaz et vous sentez immédiatement de la chaleur. Que représente, du point de vue de la thermochimie, cette chaleur ressentie ?

**Options**
- A. L'enthalpie totale $H$ du système chimique.
- B. La variation d'enthalpie $\Delta H$ cédée par le système chimique à l'environnement, car la réaction se déroule à pression constante.
- C. La température du système chimique, qui se propage telle quelle vers votre main.
- D. Une quantité d'énergie que la réaction de combustion a créée.

**Réponse correcte** : B

**Feedback correct**
À pression constante — le cas de toute réaction effectuée à l'air libre — la chaleur échangée $Q$ est directement égale à la variation d'enthalpie $\Delta H$ du système. C'est cette variation, et non $H$ lui-même, que vous ressentez.

**Feedback incorrect**
- Si A : L'enthalpie totale $H$ n'est jamais accessible expérimentalement — seule sa variation $\Delta H$ l'est, exactement comme on ne peut pas mesurer l'altitude absolue d'un point sans choisir un référentiel.
- Si B : C'est la bonne réponse.
- Si C : La chaleur (en joules) et la température (en kelvins) sont deux grandeurs distinctes — ce que vous ressentez est un transfert d'énergie, pas une propagation directe de température.
- Si D : Le premier principe de la thermodynamique interdit que de l'énergie soit créée ou détruite — elle est seulement convertie ou transférée entre le système chimique et l'environnement.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-com-001
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
misconception: enthalpie--deltah-egale-q-sans-restriction-pression
date_validation: 2026-10-05
statut: validated
---

**Question**
Un élève affirme : « $\Delta H = Q$ est toujours vrai, quelle que soit la façon dont la réaction est menée. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est vraie : $\Delta H$ et $Q$ sont deux noms pour la même grandeur, dans tous les cas.
- B. Elle est fausse : $\Delta H = Q$ n'est valable qu'à pression constante — c'est précisément l'hypothèse posée dans ce cours.
- C. Elle est fausse : $\Delta H$ et $Q$ ne sont jamais égaux, quelles que soient les conditions.
- D. Elle est vraie, mais seulement si la réaction est exothermique.

**Réponse correcte** : B

**Feedback correct**
$\Delta H = Q$ découle du premier principe appliqué spécifiquement au cas où la pression reste constante — c'est l'hypothèse de travail de tout ce chapitre, pas une propriété générale de l'enthalpie. À volume constant, c'est l'énergie interne $\Delta U$ qui égale $Q$, pas $\Delta H$.

**Feedback incorrect**
- Si A : C'est une confusion fréquente (Nilsson & Niedderer, 2014) — l'égalité $\Delta H=Q$ dépend des conditions expérimentales, elle n'est pas automatique.
- Si B : C'est la bonne réponse.
- Si C : L'égalité est bien vraie — mais seulement sous la condition de pression constante posée dans ce cours, pas jamais.
- Si D : Le signe de $\Delta_r H^\circ$ (exo ou endothermique) ne change rien à la condition de pression constante requise pour l'égalité.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-com-002
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Que représente exactement $\Delta_r H^\circ$ lorsqu'on l'exprime « en kJ/mol » pour une réaction donnée ?

**Options**
- A. L'énergie échangée pour une mole de chacun des réactifs, additionnée.
- B. L'énergie échangée pour une mole d'avancement de la réaction telle qu'elle est écrite.
- C. L'énergie échangée par mole du produit le plus lourd.
- D. L'énergie échangée par gramme de matière transformée.

**Réponse correcte** : B

**Feedback correct**
« Par mole » désigne une mole d'avancement de la réaction telle qu'elle est écrite — c'est-à-dire que les coefficients stœchiométriques de l'équation sont respectés tels quels, pas une mole de chaque réactif pris séparément.

**Feedback incorrect**
- Si A : Si plusieurs réactifs ont des coefficients différents de 1, cette interprétation ne correspond à aucune grandeur définie sans ambiguïté.
- Si B : C'est la bonne réponse.
- Si C : $\Delta_r H^\circ$ ne privilégie aucune espèce en particulier — il est défini pour l'équation entière, pas pour un produit choisi.
- Si D : L'enthalpie de réaction est définie par mole d'avancement, pas par unité de masse — c'est la capacité thermique massique qui utilise le gramme comme référence.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-app-001
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
La combustion d'une mole de propane dégage $2220\ \text{kJ}$. Quelle est la valeur de $\Delta_r H^\circ$ pour cette réaction ?

**Options**
- A. $\Delta_r H^\circ = +2220\ \text{kJ/mol}$
- B. $\Delta_r H^\circ = -2220\ \text{kJ/mol}$
- C. $\Delta_r H^\circ = -1110\ \text{kJ/mol}$
- D. $\Delta_r H^\circ = 2220\ \text{kJ}$ (sans signe ni unité par mole)

**Réponse correcte** : B

**Feedback correct**
La réaction **dégage** de la chaleur : le système chimique en perd, donc $\Delta_r H^\circ$ est négatif. La valeur est $-2220\ \text{kJ/mol}$, pour une mole d'avancement de la réaction (une mole de propane brûlée).

**Feedback incorrect**
- Si A : Une réaction qui dégage de la chaleur est exothermique — le signe doit être négatif, pas positif.
- Si B : C'est la bonne réponse.
- Si C : Diviser par deux n'a pas de justification ici — l'énoncé donne déjà la chaleur dégagée pour une mole de propane, soit directement une mole d'avancement.
- Si D : $\Delta_r H^\circ$ doit toujours porter un signe (le sens de l'échange) et une unité par mole — ce ne sont pas des détails accessoires.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-app-002
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
La formation de $2\ \text{mol}$ d'eau liquide dégage $572\ \text{kJ}$. Quelle est la valeur de $\Delta_r H^\circ$ exprimée par mole d'eau formée ?

**Options**
- A. $-572\ \text{kJ/mol}$
- B. $-286\ \text{kJ/mol}$
- C. $+286\ \text{kJ/mol}$
- D. $-1144\ \text{kJ/mol}$

**Réponse correcte** : B

**Feedback correct**
$572\ \text{kJ}$ sont dégagés pour 2 moles d'eau formée, soit $572/2 = 286\ \text{kJ}$ par mole d'eau — et le signe est négatif car la chaleur est dégagée (exothermique).

**Feedback incorrect**
- Si A : C'est la valeur pour 2 moles, pas la valeur ramenée à une mole d'eau comme demandé.
- Si B : C'est la bonne réponse.
- Si C : Le signe doit être négatif — la réaction dégage de la chaleur, elle ne l'absorbe pas.
- Si D : Multiplier au lieu de diviser inverse l'opération demandée pour ramener la valeur à une mole d'eau.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-eva-001
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
misconception: enthalpie--energie-creee-ou-detruite
date_validation: 2026-10-05
statut: validated
---

**Question**
Un élève écrit, à propos d'une réaction exothermique : « La réaction produit de l'énergie. » Cette formulation est-elle correcte du point de vue du premier principe de la thermodynamique ?

**Options**
- A. Oui : une réaction exothermique produit effectivement de l'énergie nouvelle.
- B. Non : la réaction convertit de l'enthalpie chimique en chaleur transférée à l'environnement — rien n'est créé.
- C. Non : aucune énergie n'est échangée dans une réaction exothermique.
- D. Oui, mais seulement si la réaction est une combustion.

**Réponse correcte** : B

**Feedback correct**
Le premier principe interdit toute création ou destruction d'énergie : le système chimique perd de l'enthalpie, que l'environnement reçoit sous forme de chaleur. Parler de « production » d'énergie masque cette conversion et suggère, à tort, une création nette.

**Feedback incorrect**
- Si A : Cette formulation, répandue, contredit directement le premier principe — rien n'est produit, l'énergie est transférée du système vers l'environnement.
- Si B : C'est la bonne réponse.
- Si C : Une réaction exothermique échange bel et bien de l'énergie — c'est précisément ce que mesure $\Delta_r H^\circ$.
- Si D : Le premier principe s'applique à toute réaction chimique, pas seulement aux combustions — ce biais vient souvent du fait que les premiers exemples enseignés sont presque toujours des combustions.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-reaction-exothermique-macro-com-001
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
La combustion du méthane $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$ a $\Delta_r H^\circ = -890\ \text{kJ/mol}$. Que se passe-t-il, au niveau macroscopique, pour l'environnement proche de cette réaction ?

**Options**
- A. L'environnement se réchauffe, car le système chimique lui cède de la chaleur.
- B. L'environnement se refroidit, car le système chimique lui prend de la chaleur.
- C. L'environnement ne subit aucun changement thermique mesurable.
- D. La température de l'environnement dépend uniquement de la masse de méthane brûlée, pas du signe de $\Delta_r H^\circ$.

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ < 0$ signifie que le système chimique perd de l'enthalpie — cette énergie est cédée à l'environnement sous forme de chaleur, qui se réchauffe.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse d'une réaction exothermique — le refroidissement de l'environnement caractérise une réaction endothermique.
- Si C : Une réaction exothermique s'accompagne toujours d'un transfert de chaleur réel vers l'environnement, pas d'une absence de changement.
- Si D : La masse de méthane brûlée influence l'ampleur du changement, mais le signe (réchauffement ou refroidissement) est déterminé par le signe de $\Delta_r H^\circ$, pas par la masse.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-macro-eva-001
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: eva
misconception: reaction-exothermique--classification-exige-changement-temperature-observable
date_validation: 2026-10-05
statut: validated
---

**Question**
Un élève affirme : « On ne peut parler de réaction exothermique ou endothermique que si on observe effectivement un changement de température. » Que pensez-vous de cette affirmation, sachant qu'il existe des réactions dites **athermiques** ($\Delta_r H^\circ = 0$) ?

**Options**
- A. Elle est correcte : sans changement de température observable, la réaction est forcément athermique, jamais exo ou endothermique.
- B. Elle est incorrecte : le signe de $\Delta_r H^\circ$ définit la classification, indépendamment de l'ampleur du changement de température réellement observé.
- C. Elle est correcte, car la réaction athermique est justement la seule à exister sans changement de température.
- D. Elle est incorrecte, car les réactions athermiques n'existent pas réellement.

**Réponse correcte** : B

**Feedback correct**
Une réaction est classée exo/endo/athermique selon le **signe de $\Delta_r H^\circ$**, une grandeur théorique — un changement de température très faible (par exemple si la masse d'eau environnante est très grande) ne signifie pas que la réaction est athermique : elle reste exo ou endothermique, seulement difficile à observer.

**Feedback incorrect**
- Si A : C'est confondre la classification théorique (signe de $\Delta_r H^\circ$) avec son observabilité pratique — une réaction peut être exothermique sans que le changement de température soit perceptible (grande masse d'eau, par exemple).
- Si B : C'est la bonne réponse.
- Si C : La réaction athermique ($\Delta_r H^\circ=0$) est définie par l'absence d'échange net, pas par l'absence d'observation — mais une réaction exo/endo très diluée peut, elle aussi, sembler ne rien changer en pratique.
- Si D : Les réactions athermiques existent bel et bien : leurs deux bilans énergétiques (rupture et formation de liaisons) s'annulent exactement.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-macro-eva-002
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: eva
misconception: reaction-exothermique--vitesse-confondue-avec-thermodynamique
date_validation: 2026-10-05
statut: validated
---

**Question**
Un élève affirme : « Les réactions exothermiques sont plus rapides que les réactions endothermiques, car elles dégagent de l'énergie. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte : le signe de $\Delta_r H^\circ$ détermine directement la vitesse de la réaction.
- B. Elle est incorrecte : la vitesse d'une réaction (cinétique) et son caractère exo/endothermique (thermodynamique) sont deux propriétés indépendantes.
- C. Elle est correcte, mais seulement pour les réactions de combustion.
- D. Elle est incorrecte, car toutes les réactions chimiques ont exactement la même vitesse.

**Réponse correcte** : B

**Feedback correct**
La vitesse d'une réaction dépend de son énergie d'activation (un concept cinétique, vu au chapitre Vitesse de réaction) — pas du signe ni de la valeur de $\Delta_r H^\circ$, qui ne renseigne que sur le bilan énergétique global. Une réaction très exothermique peut être extrêmement lente (ex. l'oxydation du fer), et une réaction endothermique peut être rapide.

**Feedback incorrect**
- Si A : C'est confondre deux axes indépendants de la chimie — la thermodynamique (bilan énergétique, $\Delta_r H^\circ$) et la cinétique (vitesse, énergie d'activation).
- Si B : C'est la bonne réponse.
- Si C : Même restreinte aux combustions, cette affirmation resterait incorrecte — le signe de $\Delta_r H^\circ$ ne détermine jamais la vitesse d'une réaction.
- Si D : Les réactions chimiques ont des vitesses très différentes les unes des autres — mais cette variabilité n'est pas déterminée par le signe de $\Delta_r H^\circ$.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-parti-com-001
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
misconception: energie-de-liaison--rupture-exothermique-inversee
date_validation: 2026-10-05
statut: validated
---

**Question**
Au niveau particulaire, pourquoi une réaction est-elle exothermique lorsque les liaisons formées dans les produits sont plus fortes que les liaisons rompues dans les réactifs ?

**Options**
- A. Parce que rompre les liaisons des réactifs libère plus d'énergie que n'en demande la formation des nouvelles liaisons.
- B. Parce que former les nouvelles liaisons libère plus d'énergie que n'en a coûté la rupture des liaisons des réactifs.
- C. Parce que le nombre d'atomes présents dans les produits est plus grand que dans les réactifs.
- D. Parce que la température initiale des réactifs était déjà élevée.

**Réponse correcte** : B

**Feedback correct**
Rompre une liaison coûte toujours de l'énergie (processus endothermique) ; former une liaison en libère toujours (processus exothermique). Si l'énergie libérée par la formation des liaisons des produits dépasse l'énergie qu'a coûté la rupture des liaisons des réactifs, le bilan net est négatif : la réaction est exothermique.

**Feedback incorrect**
- Si A : C'est l'inversion classique — rompre une liaison **coûte** de l'énergie, elle ne peut jamais en « libérer » de façon à rendre la réaction exothermique de ce côté-là.
- Si B : C'est la bonne réponse.
- Si C : Le nombre d'atomes ne change jamais au cours d'une réaction chimique (conservation des éléments) — ce n'est pas un facteur du bilan énergétique.
- Si D : Le caractère exo/endothermique dépend du bilan énergétique des liaisons, pas de la température initiale des réactifs.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-parti-com-002
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
misconception: energie-de-liaison--rupture-exothermique-inversee
date_validation: 2026-10-05
statut: validated
---

**Question**
Un comprimé effervescent plongé dans l'eau refroidit légèrement la solution. Qu'est-ce que cela révèle sur le bilan énergétique des liaisons, au niveau particulaire ?

**Options**
- A. Les liaisons rompues dans les réactifs consomment plus d'énergie que les liaisons formées dans les produits n'en libèrent.
- B. Les liaisons rompues dans les réactifs libèrent plus d'énergie que les liaisons formées dans les produits n'en consomment.
- C. Aucune liaison n'est rompue ni formée — seule la température de l'eau change.
- D. Le comprimé absorbe la chaleur de l'eau simplement parce qu'il est solide et froid au contact.

**Réponse correcte** : A

**Feedback correct**
Le refroidissement de la solution signale une réaction endothermique : le système chimique absorbe de la chaleur de l'environnement. Au niveau particulaire, cela signifie que rompre les liaisons des réactifs coûte plus d'énergie que n'en libère la formation des liaisons des produits.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse — si la rupture des liaisons « libérait » plus d'énergie que la formation n'en consomme, le bilan serait exothermique et la solution se réchaufferait, pas l'inverse.
- Si C : Une réaction chimique implique toujours la rupture et la formation de liaisons — c'est précisément ce bilan qui explique le changement de température observé.
- Si D : Le refroidissement n'est pas dû à la simple présence d'un solide froid, mais au bilan énergétique de la réaction chimique qui se produit (une dissolution/réaction endothermique).

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-symbo-com-001
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Classez les réactions suivantes selon le signe de $\Delta_r H^\circ$ : (a) $\Delta_r H^\circ = -46\ \text{kJ/mol}$ ; (b) $\Delta_r H^\circ = +180\ \text{kJ/mol}$ ; (c) $\Delta_r H^\circ = 0$.

**Options**
- A. (a) exothermique ; (b) endothermique ; (c) athermique.
- B. (a) endothermique ; (b) exothermique ; (c) athermique.
- C. (a) exothermique ; (b) athermique ; (c) endothermique.
- D. (a) athermique ; (b) endothermique ; (c) exothermique.

**Réponse correcte** : A

**Feedback correct**
Un $\Delta_r H^\circ$ négatif (a) correspond à une réaction exothermique (le système perd de l'enthalpie), un $\Delta_r H^\circ$ positif (b) à une réaction endothermique (le système en gagne), et $\Delta_r H^\circ=0$ (c) à une réaction athermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les signes sont inversés — négatif signifie exothermique, positif signifie endothermique, pas l'inverse.
- Si C : $\Delta_r H^\circ=0$ correspond à une réaction athermique, pas endothermique — et (b), positif, est endothermique, pas athermique.
- Si D : Aucune des trois associations n'est correcte — revoir la définition du signe de $\Delta_r H^\circ$ pour chaque cas.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-symbo-ana-001
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-10-05
statut: validated
---

**Question**
La combustion du méthane $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$ a $\Delta_r H^\circ = -890\ \text{kJ/mol}$. Si l'on produit $\ce{H2O(g)}$ au lieu de $\ce{H2O(l)}$, sans faire aucun calcul, le $\Delta_r H^\circ$ sera-t-il plus ou moins négatif ?

**Options**
- A. Moins négatif, car la vaporisation de l'eau absorbe de l'énergie, réduisant la chaleur nette dégagée par le système.
- B. Plus négatif, car produire un gaz libère toujours davantage d'énergie qu'un liquide.
- C. Exactement identique, car l'état physique d'un produit n'affecte jamais $\Delta_r H^\circ$.
- D. Impossible à déterminer sans connaître les enthalpies de formation exactes.

**Réponse correcte** : A

**Feedback correct**
Former de l'eau gazeuse au lieu de liquide revient à « ne pas libérer » l'énergie de condensation — la réaction dégage donc moins de chaleur nette : $\Delta_r H^\circ$ devient moins négatif (en valeur absolue plus petite). C'est un raisonnement qualitatif, sans qu'il soit nécessaire de connaître les valeurs numériques exactes.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse — produire un gaz plutôt qu'un liquide demande de l'énergie supplémentaire (vaporisation), ce qui rend la réaction globale moins exothermique, pas plus.
- Si C : L'état physique de chaque espèce doit toujours être précisé dans une équation thermochimique, précisément parce qu'il influence directement la valeur de $\Delta_r H^\circ$.
- Si D : Le sens de la variation (plus ou moins négatif) se déduit qualitativement, sans calcul — l'énoncé demande justement ce raisonnement, pas un résultat numérique.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-endothermique-macro-com-001
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
La formation de $\ce{NO2(g)}$ à partir de $\ce{N2(g)}$ et $\ce{O2(g)}$ a $\Delta_r H^\circ = +34\ \text{kJ/mol}$. Que se passe-t-il, au niveau macroscopique, pour l'environnement de cette réaction ?

**Options**
- A. L'environnement se refroidit, car le système chimique lui prend de la chaleur.
- B. L'environnement se réchauffe, car le système chimique lui cède de la chaleur.
- C. L'environnement ne subit aucun changement thermique, car $\Delta_r H^\circ$ est faible.
- D. Le signe positif de $\Delta_r H^\circ$ n'a pas d'implication macroscopique directe.

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ > 0$ signifie que le système chimique gagne de l'enthalpie — il la puise dans l'environnement, qui se refroidit en conséquence.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse d'une réaction endothermique — le réchauffement de l'environnement caractérise une réaction exothermique.
- Si C : Même une valeur de $\Delta_r H^\circ$ relativement faible correspond à un échange de chaleur réel — sa faiblesse numérique n'annule pas le phénomène, elle peut seulement le rendre peu perceptible selon les quantités en jeu.
- Si D : Le signe de $\Delta_r H^\circ$ détermine précisément le sens de l'échange thermique avec l'environnement — c'est son implication macroscopique directe.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-endothermique-parti-com-001
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Pour la réaction endothermique de formation de $\ce{NO2(g)}$ ($\Delta_r H^\circ=+34\ \text{kJ/mol}$), que peut-on dire du bilan rupture/formation de liaisons au niveau particulaire ?

**Options**
- A. Les liaisons rompues dans les réactifs consomment plus d'énergie que les liaisons formées dans les produits n'en libèrent.
- B. Les liaisons rompues dans les réactifs consomment moins d'énergie que les liaisons formées dans les produits n'en libèrent.
- C. Aucune liaison n'est rompue dans cette réaction, seulement formée.
- D. Le bilan rupture/formation ne s'applique qu'aux réactions exothermiques.

**Réponse correcte** : A

**Feedback correct**
Un $\Delta_r H^\circ$ positif signifie que le bilan net est défavorable au système : rompre les liaisons des réactifs ($\ce{N2}$, $\ce{O2}$) coûte plus d'énergie que n'en libère la formation des liaisons dans $\ce{NO2}$ — le système doit donc puiser la différence dans l'environnement.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Ce bilan correspondrait à une réaction exothermique, pas endothermique — l'inverse de ce qui est observé ici.
- Si C : Toute réaction chimique implique la rupture de liaisons dans les réactifs et la formation de nouvelles liaisons dans les produits — $\ce{N2}$ et $\ce{O2}$ doivent bien voir leurs liaisons rompues.
- Si D : Le bilan rupture/formation s'applique à toute réaction chimique, exothermique ou endothermique — seul le signe du résultat net diffère.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-endothermique-symbo-app-001
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
La formation de $\ce{NO2(g)}$ à partir de $\frac{1}{2}\ \text{mol}$ de $\ce{N2(g)}$ et $1\ \text{mol}$ de $\ce{O2(g)}$ a $\Delta_r H^\circ = +34\ \text{kJ/mol}$. Quelle est la valeur de $\Delta_r H^\circ$ pour la formation de **2 moles** de $\ce{NO2}$ ?

**Options**
- A. $+34\ \text{kJ/mol}$
- B. $+17\ \text{kJ/mol}$
- C. $+68\ \text{kJ/mol}$
- D. $+136\ \text{kJ/mol}$

**Réponse correcte** : C

**Feedback correct**
L'équation donnée produit 1 mole de $\ce{NO2}$. Pour 2 moles, on multiplie tous les coefficients — et donc $\Delta_r H^\circ$ — par 2 : $2\times34=+68\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la valeur pour 1 mole de $\ce{NO2}$ formée, pas pour 2 moles comme demandé.
- Si B : Diviser par deux va dans le mauvais sens — on cherche la formation d'une quantité **plus grande**, donc il faut multiplier, pas diviser.
- Si C : C'est la bonne réponse.
- Si D : Multiplier par 4 au lieu de 2 ne correspond pas au rapport entre 1 mole et 2 moles de $\ce{NO2}$.

**Référence manuel** : thermochimie-1-exo-endo

---

<!-- ============================================================ -->
<!-- LOT 2 — Énergie de liaison et énergie de cohésion            -->
<!-- Concept : energie-de-liaison (cohésion fusionnée le 04.11.2026)  -->
<!-- 9 questions obligatoires (7 + 2)                              -->
<!-- ============================================================ -->

---
id: q-reaction-endothermique-macro-com-002
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-11-01
statut: validated
---

**Question**
En dissolvant un comprimé effervescent dans l'eau, un élève constate que le verre devient froid au toucher. Que peut-on en conclure ?

**Options**
- A. La transformation est exothermique : elle libère de la chaleur vers son environnement
- B. La transformation est endothermique : le système prend de la chaleur à son environnement
- C. Aucune énergie n'est échangée entre la transformation et son environnement
- D. Le refroidissement montre que la transformation n'a pas réellement lieu

**Réponse correcte** : B

**Feedback correct**
Le verre se refroidit : la chaleur passe de l'environnement (eau, verre, main) vers le système chimique. La transformation est endothermique ($\Delta_r H > 0$).

**Feedback incorrect**
- Si A : Une transformation exothermique cède de la chaleur et réchauffe l'environnement. Ici, il se refroidit.
- Si B : C'est la bonne réponse.
- Si C : Un refroidissement constaté est la preuve d'un échange de chaleur avec l'environnement.
- Si D : L'effervescence montre que la transformation a lieu. Le refroidissement vient de la chaleur qu'elle absorbe.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-endothermique-parti-com-002
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
date_validation: 2026-11-01
statut: validated
---

**Question**
Après une réaction endothermique, comment se situe l'énergie du système chimique par rapport à celle d'avant la réaction ?

**Options**
- A. Elle est plus basse : le système a cédé de l'énergie à l'environnement
- B. Elle est plus élevée : le système a absorbé de l'énergie de l'environnement
- C. Elle est strictement identique, car l'énergie se conserve
- D. On ne peut pas la comparer sans connaître la masse du système

**Réponse correcte** : B

**Feedback correct**
Dans une réaction endothermique ($\Delta_r H > 0$), les liaisons rompues coûtent plus d'énergie que les liaisons formées n'en libèrent : le système absorbe de l'énergie, qui reste stockée dans les produits.

**Feedback incorrect**
- Si A : C'est le cas d'une réaction exothermique. Ici le système absorbe de l'énergie.
- Si B : C'est la bonne réponse.
- Si C : L'énergie totale se conserve, mais celle du système chimique augmente aux dépens de l'environnement.
- Si D : Le signe de $\Delta_r H$ suffit pour comparer : il est positif, l'énergie du système augmente.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-endothermique-symbo-app-002
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-01
statut: validated
---

**Question**
La formation de $\ce{NO2(g)}$ a pour enthalpie $\Delta_r H^\circ = +34\ \text{kJ/mol}$. Quelle énergie est absorbée lors de la formation de $3{,}00$ mol de $\ce{NO2}$ ?

**Options**
- A. $11{,}3$ kJ
- B. $34$ kJ
- C. $-102$ kJ
- D. $102$ kJ

**Réponse correcte** : D

**Feedback correct**
$3{,}00 \times 34 = 102\ \text{kJ}$ sont absorbés, soit $\Delta H = +102\ \text{kJ}$ pour $3{,}00$ mol.

**Feedback incorrect**
- Si A : $11{,}3$ vient d'une division de 34 par 3. L'énergie est proportionnelle à la quantité formée : on multiplie.
- Si B : $34$ kJ correspond à une seule mole de $\ce{NO2}$.
- Si C : Le signe est faux : la réaction est endothermique, elle absorbe de l'énergie, donc $\Delta H > 0$.
- Si D : C'est la bonne réponse.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-endothermique-symbo-app-003
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-01
statut: validated
---

**Question**
La formation de $\ce{NO2(g)}$ à partir de ses éléments a pour enthalpie $+34\ \text{kJ/mol}$. Quelle est l'enthalpie de la réaction inverse, la décomposition d'une mole de $\ce{NO2}$ en ses éléments ?

**Options**
- A. $-34\ \text{kJ/mol}$
- B. $+34\ \text{kJ/mol}$
- C. $-68\ \text{kJ/mol}$
- D. $0\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
La réaction inverse met en jeu la même énergie, de signe opposé : $-34\ \text{kJ/mol}$. Elle est exothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La réaction inverse est de signe opposé : si l'aller absorbe de l'énergie, le retour en libère.
- Si C : Aucun facteur 2 n'intervient : on décompose une seule mole de $\ce{NO2}$.
- Si D : L'énergie échangée est la même qu'à l'aller, avec le signe opposé : elle n'est pas nulle.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-energie-de-liaison-parti-com-001
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
misconception: energie-de-liaison--rupture-exothermique-inversee
date_validation: 2026-10-05
statut: validated
---

**Question**
Pourquoi l'énergie de liaison $D_{A-B}$ est-elle, par définition, **toujours positive** ?

**Options**
- A. Parce que rompre une liaison demande de l'énergie — une liaison existe précisément parce qu'elle stabilise le système, donc la défaire lui restitue cette instabilité.
- B. Parce que former une liaison demande toujours de l'énergie, exactement comme la rompre.
- C. Parce que $D_{A-B}$ mesure l'énergie libérée par la rupture de la liaison.
- D. Parce que les valeurs négatives n'ont pas de sens physique en thermochimie.

**Réponse correcte** : A

**Feedback correct**
Une liaison se forme parce qu'elle abaisse l'énergie du système — la rompre revient donc à lui restituer cette énergie, ce qui coûte toujours de l'énergie. $D_{A-B}$ désigne précisément cette énergie de rupture, toujours positive, en phase gazeuse et de façon homolytique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Former une liaison est au contraire toujours **exothermique** ($\Delta H=-D_{A-B}<0$) — c'est l'inverse exact de la rupture.
- Si C : C'est l'inversion la plus fréquente sur ce concept (Galley, 2004) — rompre une liaison **coûte** de l'énergie, elle n'en libère jamais.
- Si D : Les variations d'enthalpie négatives existent bel et bien en thermochimie (toute réaction exothermique en est une) — ce n'est pas un problème de validité du signe négatif en général, mais une propriété spécifique de la rupture de liaison.

**Référence manuel** : thermochimie-1-energie-liaison-definition

---
id: q-energie-de-liaison-parti-com-002
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
misconception: energie-de-liaison--rupture-exothermique-inversee
date_validation: 2026-10-05
statut: validated
---

**Question**
Lors de la rupture homolytique d'une liaison $\ce{H-H}$ en phase gazeuse, chaque atome d'hydrogène récupère un électron de la liaison, formant deux radicaux $\ce{H^.}$. Que peut-on affirmer sur l'énergie de ce processus ?

**Options**
- A. Le processus est endothermique : il faut fournir $436\ \text{kJ/mol}$ pour séparer les deux atomes.
- B. Le processus est exothermique : séparer les deux atomes libère $436\ \text{kJ/mol}$.
- C. Le processus n'échange aucune énergie, car aucune nouvelle liaison n'est formée.
- D. Le signe dépend de la température à laquelle la rupture a lieu.

**Réponse correcte** : A

**Feedback correct**
La rupture d'une liaison est toujours endothermique : il faut fournir l'énergie de liaison ($D_{\ce{H-H}}=436\ \text{kJ/mol}$) pour vaincre l'attraction qui maintenait les deux atomes liés.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inversion classique — la rupture d'une liaison ne libère jamais d'énergie, elle en coûte toujours.
- Si C : L'absence de nouvelle liaison ne signifie pas l'absence d'échange énergétique — rompre une liaison existante demande de l'énergie, même sans en former de nouvelle.
- Si D : Le signe (endothermique) est une propriété structurelle de la rupture de liaison, pas une conséquence de la température.

**Référence manuel** : thermochimie-1-energie-liaison-definition

---
id: q-energie-de-liaison-symbo-app-001
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Estimez $\Delta_r H^\circ$ de la réaction $\ce{H2(g) + Cl2(g) -> 2 HCl(g)}$ par les énergies de liaison, sachant $D_{\ce{H-H}}=436\ \text{kJ/mol}$, $D_{\ce{Cl-Cl}}=243\ \text{kJ/mol}$, $D_{\ce{H-Cl}}=431\ \text{kJ/mol}$.

**Options**
- A. $+1110\ \text{kJ/mol}$
- B. $-183\ \text{kJ/mol}$
- C. $+183\ \text{kJ/mol}$
- D. $-862\ \text{kJ/mol}$

**Réponse correcte** : B

**Feedback correct**
$E_\text{endo} = D_{\ce{H-H}}+D_{\ce{Cl-Cl}} = 436+243=679\ \text{kJ/mol}$ (rupture des réactifs) ; $E_\text{exo} = 2\times431=862\ \text{kJ/mol}$ (formation des 2 liaisons $\ce{H-Cl}$) ; $\Delta_r H^\circ = 679-862=-183\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la somme des trois énergies de liaison sans soustraction — le cycle $E_\text{endo}-E_\text{exo}$ exige bien une soustraction, pas une addition.
- Si B : C'est la bonne réponse.
- Si C : Le signe est inversé — $E_\text{exo}$ (862) est plus grand que $E_\text{endo}$ (679), donc le bilan net est négatif (exothermique), pas positif.
- Si D : C'est $E_\text{exo}$ seul, sans soustraire $E_\text{endo}$.

**Référence manuel** : thermochimie-1-calcul-energie-liaison

---
id: q-energie-de-liaison-symbo-app-002
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
L'énergie de cohésion de l'acétone $\ce{(CH3)2CO}$ vaut $3928\ \text{kJ/mol}$. Sa structure comporte 6 liaisons $\ce{C-H}$ ($D=414$), 2 liaisons $\ce{C-C}$ ($D=348$) et 1 liaison $\ce{C=O}$. Quelle est la valeur de $D_{\ce{C=O}}$ ?

**Options**
- A. $748\ \text{kJ/mol}$
- B. $3928\ \text{kJ/mol}$
- C. $803\ \text{kJ/mol}$
- D. $3180\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$6\times414+2\times348 = 3180\ \text{kJ/mol}$ (contribution des liaisons C-H et C-C). Par différence avec la cohésion totale : $D_{\ce{C=O}} = 3928-3180=748\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'énergie de cohésion totale de la molécule, pas l'énergie de la seule liaison $\ce{C=O}$ recherchée.
- Si C : C'est la valeur de $D_{\ce{C=O}}$ dans $\ce{CO2}$ — ici, on cherche la valeur propre à l'acétone, déduite de la cohésion, car cette énergie dépend de l'environnement de la liaison.
- Si D : C'est la somme des liaisons $\ce{C-H}$ et $\ce{C-C}$ ($3180$) — il reste à la soustraire de la cohésion totale, pas à la donner comme résultat final.

**Référence manuel** : thermochimie-1-calcul-energie-liaison

---
id: q-energie-de-liaison-symbo-ana-001
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
misconception: energie-de-liaison--rupture-exothermique-inversee
date_validation: 2026-11-04
statut: validated
---

**Question**
La rupture d'une liaison $\ce{C=C}$ coûte $610\ \text{kJ/mol}$ et la formation d'une liaison $\ce{C-C}$ libère $348\ \text{kJ/mol}$. Quel est le bilan enthalpique de ce processus (rupture de la double liaison, formation de la simple liaison) ?

**Options**
- A. $+262\ \text{kJ/mol}$ (endothermique)
- B. $-262\ \text{kJ/mol}$ (exothermique)
- C. $+958\ \text{kJ/mol}$ (endothermique)
- D. $-958\ \text{kJ/mol}$ (exothermique)

**Réponse correcte** : A

**Feedback correct**
Bilan : $+610$ (rupture, coûte de l'énergie) $-348$ (formation, en libère) $=+262\ \text{kJ/mol}$, donc endothermique. C'est cohérent : une double liaison étant plus stable qu'une simple, sa rupture coûte davantage que ce que libère la formation d'une simple liaison.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Inverser le signe revient à traiter la rupture comme exothermique — c'est exactement l'inversion classique à éviter (rompre coûte toujours de l'énergie).
- Si C : $610+348=958$ additionne les deux valeurs au lieu de les soustraire — le bilan d'un processus rupture+formation se calcule par différence, pas par somme.
- Si D : Même erreur d'addition que C, avec en plus le signe inversé.

**Référence manuel** : thermochimie-1-calcul-energie-liaison

---
id: q-energie-de-liaison-symbo-ana-002
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
misconception: energie-de-liaison--rupture-exothermique-inversee
date_validation: 2026-11-04
statut: validated
---

**Question**
La rupture d'une liaison $\ce{O-H}$ coûte $464\ \text{kJ/mol}$ et la formation d'une liaison $\ce{C-O}$ libère $360\ \text{kJ/mol}$. Quel est le bilan enthalpique de ce processus seul ?

**Options**
- A. $+104\ \text{kJ/mol}$ (endothermique)
- B. $-104\ \text{kJ/mol}$ (exothermique)
- C. $+824\ \text{kJ/mol}$ (endothermique)
- D. $-824\ \text{kJ/mol}$ (exothermique)

**Réponse correcte** : A

**Feedback correct**
Bilan : $+464$ (rupture, coûte de l'énergie) $-360$ (formation, en libère) $=+104\ \text{kJ/mol}$, donc endothermique — ici, la liaison rompue est plus forte que la liaison formée, le bilan est donc positif.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Inverser le signe traite à tort la rupture comme exothermique.
- Si C : $464+360=824$ additionne au lieu de soustraire les deux contributions.
- Si D : Même erreur d'addition que C, avec en plus le signe inversé.

**Référence manuel** : thermochimie-1-calcul-energie-liaison

---
id: q-energie-de-liaison-symbo-eva-001
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Pour la combustion du propane $\ce{C3H8(g) + 5 O2(g) -> 3 CO2(g) + 4 H2O(g)}$, la méthode des énergies de liaison donne $\Delta_r H^\circ\approx-2032\ \text{kJ/mol}$, alors que les enthalpies de formation donnent $-2046\ \text{kJ/mol}$. Pourquoi cette méthode est-elle structurellement moins précise que celle des enthalpies de formation ?

**Options**
- A. Parce que les énergies de liaison tabulées sont des valeurs moyennes établies sur de nombreuses molécules différentes, qui ne reflètent pas l'environnement électronique exact de chaque liaison dans une molécule donnée.
- B. Parce que la méthode des énergies de liaison ne s'applique qu'aux réactions endothermiques.
- C. Parce que les calculs par énergies de liaison contiennent nécessairement une erreur d'arrondi plus grande.
- D. Parce que les énergies de liaison ne sont valables qu'à très basse température.

**Réponse correcte** : A

**Feedback correct**
Les valeurs de $D_{A-B}$ du tableau sont des moyennes statistiques sur de nombreuses molécules — l'énergie réelle d'une liaison $\ce{C-H}$ dans le propane diffère légèrement de cette moyenne. Les enthalpies de formation, elles, sont mesurées pour chaque corps pur spécifique, sans cette approximation.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La méthode s'applique aussi bien aux réactions exothermiques (comme ici) qu'endothermiques — ce n'est pas une limite de portée.
- Si C : L'écart vient d'une approximation physique (moyennes statistiques), pas d'un simple arrondi numérique dans le calcul.
- Si D : Les énergies de liaison tabulées ne dépendent pas de la température d'utilisation — le problème est la généralisation entre molécules différentes, pas la température.

**Référence manuel** : thermochimie-1-calcul-energie-liaison

---
id: q-energie-de-liaison-parti-com-003
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
Le $\ce{CO2}$ a une énergie de cohésion de $1606\ \text{kJ/mol}$ (2 liaisons $\ce{C=O}$) et l'eau $\ce{H2O}$ de $928\ \text{kJ/mol}$ (2 liaisons $\ce{O-H}$). Que signifie cette différence, au niveau particulaire ?

**Options**
- A. Il faut davantage d'énergie pour dissocier complètement une molécule de $\ce{CO2}$ en atomes isolés que pour dissocier une molécule de $\ce{H2O}$ — le $\ce{CO2}$ est globalement plus stable.
- B. Le $\ce{CO2}$ contient plus d'atomes que $\ce{H2O}$, ce qui explique entièrement l'écart.
- C. L'énergie de cohésion ne renseigne pas sur la stabilité d'une molécule, seulement sur sa masse.
- D. Le $\ce{H2O}$ est plus stable, car sa cohésion est une valeur plus petite donc plus facile à atteindre.

**Réponse correcte** : A

**Feedback correct**
L'énergie de cohésion mesure l'énergie totale nécessaire pour dissocier complètement une molécule en atomes isolés à l'état gazeux — plus elle est grande, plus la molécule est stable globalement. Le $\ce{CO2}$, avec $1606$ kJ/mol, est donc plus stable que $\ce{H2O}$, avec $928$ kJ/mol.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{CO2}$ (3 atomes) et $\ce{H2O}$ (3 atomes) ont le même nombre d'atomes — ce n'est pas le nombre d'atomes qui explique l'écart, mais la force des liaisons $\ce{C=O}$ par rapport aux liaisons $\ce{O-H}$.
- Si C : L'énergie de cohésion est précisément définie comme une mesure de la stabilité globale d'une molécule — pas de sa masse.
- Si D : Une cohésion plus petite signifie, au contraire, qu'il faut moins d'énergie pour dissocier la molécule — elle est donc moins stable, pas plus.

**Référence manuel** : thermochimie-1-energie-cohesion

---
id: q-energie-de-liaison-symbo-app-003
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Calculez l'énergie de cohésion du méthane $\ce{CH4}$, qui comporte 4 liaisons $\ce{C-H}$ ($D_{\ce{C-H}}=414\ \text{kJ/mol}$).

**Options**
- A. $414\ \text{kJ/mol}$
- B. $1656\ \text{kJ/mol}$
- C. $104\ \text{kJ/mol}$
- D. $828\ \text{kJ/mol}$

**Réponse correcte** : B

**Feedback correct**
L'énergie de cohésion est la somme de toutes les énergies de liaison de la molécule : $4\times414=1656\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est l'énergie d'une seule liaison $\ce{C-H}$, pas la somme des 4 liaisons de la molécule entière.
- Si B : C'est la bonne réponse.
- Si C : $414/4\approx104$ divise au lieu de multiplier — la cohésion est une somme, pas une moyenne par liaison divisée par leur nombre.
- Si D : $414\times2=828$ ne compte que 2 liaisons sur les 4 réellement présentes dans $\ce{CH4}$.

**Référence manuel** : thermochimie-1-energie-cohesion

---

<!-- ============================================================ -->
<!-- LOT 3 — Enthalpie de formation standard                      -->
<!-- Concept : enthalpie-de-formation                              -->
<!-- 4 questions obligatoires (macro·com, symbo·com, symbo·app ×2) -->
<!-- ============================================================ -->

---
id: q-energie-de-liaison-symbo-app-004
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Calculez l'énergie de cohésion de l'ammoniac $\ce{NH3}$, qui comporte 3 liaisons $\ce{N-H}$ ($D_{\ce{N-H}} = 389\ \text{kJ/mol}$).

**Options**
- A. $389\ \text{kJ/mol}$
- B. $130\ \text{kJ/mol}$
- C. $1556\ \text{kJ/mol}$
- D. $1167\ \text{kJ/mol}$

**Réponse correcte** : D

**Feedback correct**
L'énergie de cohésion est la somme des énergies de toutes les liaisons de la molécule : $3 \times 389 = 1167\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : $389\ \text{kJ/mol}$ ne tient compte que d'une liaison $\ce{N-H}$ : $\ce{NH3}$ en compte trois.
- Si B : $130\ \text{kJ/mol}$ résulte d'une division par 3. On additionne les énergies des liaisons, on ne les divise pas.
- Si C : $1556\ \text{kJ/mol}$ correspond à 4 liaisons $\ce{N-H}$ : $\ce{NH3}$ n'en compte que 3.
- Si D : C'est la bonne réponse.

**Référence manuel** : thermochimie-1-energie-cohesion

---
id: q-energie-de-liaison-symbo-app-005
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Calculez l'énergie de cohésion de l'éthane $\ce{CH3-CH3}$, qui comporte 6 liaisons $\ce{C-H}$ ($414\ \text{kJ/mol}$) et 1 liaison $\ce{C-C}$ ($348\ \text{kJ/mol}$).

**Options**
- A. $2484\ \text{kJ/mol}$
- B. $2832\ \text{kJ/mol}$
- C. $762\ \text{kJ/mol}$
- D. $3180\ \text{kJ/mol}$

**Réponse correcte** : B

**Feedback correct**
$E_\text{cohésion} = 6 \times 414 + 1 \times 348 = 2484 + 348 = 2832\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : $2484\ \text{kJ/mol}$ ne compte que les 6 liaisons $\ce{C-H}$ : il manque la liaison $\ce{C-C}$.
- Si B : C'est la bonne réponse.
- Si C : $762\ \text{kJ/mol}$ additionne une seule liaison de chaque sorte. Il faut compter 6 liaisons $\ce{C-H}$.
- Si D : $3180\ \text{kJ/mol}$ compte la liaison $\ce{C-C}$ deux fois. L'éthane n'en contient qu'une.

**Référence manuel** : thermochimie-1-energie-cohesion

---
id: q-energie-de-liaison-symbo-app-006
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Calculez l'énergie de cohésion du méthanol $\ce{CH3OH}$, qui comporte 3 liaisons $\ce{C-H}$ ($414\ \text{kJ/mol}$), 1 liaison $\ce{C-O}$ ($360\ \text{kJ/mol}$) et 1 liaison $\ce{O-H}$ ($464\ \text{kJ/mol}$).

**Options**
- A. $1242\ \text{kJ/mol}$
- B. $2480\ \text{kJ/mol}$
- C. $2066\ \text{kJ/mol}$
- D. $824\ \text{kJ/mol}$

**Réponse correcte** : C

**Feedback correct**
$E_\text{cohésion} = 3 \times 414 + 360 + 464 = 1242 + 360 + 464 = 2066\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : $1242\ \text{kJ/mol}$ ne compte que les trois liaisons $\ce{C-H}$ : il manque les liaisons $\ce{C-O}$ et $\ce{O-H}$.
- Si B : $2480\ \text{kJ/mol}$ compte quatre liaisons $\ce{C-H}$. Le méthanol n'en contient que trois (le quatrième hydrogène est lié à $\ce{O}$).
- Si C : C'est la bonne réponse.
- Si D : $824\ \text{kJ/mol}$ additionne $\ce{C-O}$ et $\ce{O-H}$ ($360 + 464$) et oublie les trois liaisons $\ce{C-H}$.

**Référence manuel** : thermochimie-1-energie-cohesion

---
id: q-energie-de-liaison-parti-com-004
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
date_validation: 2026-11-01
statut: validated
---

**Question**
Quelle est la différence entre l'énergie de liaison et l'énergie de cohésion d'une molécule polyatomique ?

**Options**
- A. Ce sont deux noms pour la même grandeur
- B. L'énergie de cohésion est l'énergie libérée lorsque la molécule se forme à partir de ses éléments
- C. L'énergie de cohésion mesure l'énergie nécessaire pour faire passer la substance de l'état solide à l'état liquide
- D. L'énergie de liaison concerne une liaison ; la cohésion les additionne toutes

**Réponse correcte** : D

**Feedback correct**
L'énergie de cohésion additionne les énergies de toutes les liaisons : c'est l'énergie à fournir pour dissocier complètement la molécule en atomes isolés à l'état gazeux. L'énergie de liaison ne concerne qu'une liaison donnée.

**Feedback incorrect**
- Si A : Les deux grandeurs coïncident seulement pour une molécule diatomique, qui n'a qu'une liaison. Pour une molécule polyatomique, la cohésion additionne toutes les liaisons.
- Si B : L'énergie libérée à la formation à partir des éléments est une autre grandeur (enthalpie de formation). La cohésion concerne la dissociation en atomes isolés.
- Si C : Les changements d'état font intervenir les forces intermoléculaires. La cohésion dont il s'agit ici concerne les liaisons à l'intérieur de la molécule.
- Si D : C'est la bonne réponse.

**Référence manuel** : thermochimie-1-energie-cohesion

---
id: q-enthalpie-de-formation-macro-com-001
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Dans les conditions standards ($298\ \text{K}$, $1\ \text{bar}$), l'enthalpie standard de formation du diazote gazeux $\ce{N2(g)}$ vaut $0\ \text{kJ/mol}$. Quelle est la raison de cette valeur nulle ?

**Options**
- A. $\ce{N2(g)}$ est un corps pur simple dans son état le plus stable : sa « formation » à partir de lui-même ne correspond à aucune transformation chimique.
- B. La molécule de $\ce{N2}$ ne contient aucune liaison chimique, donc aucune énergie n'est échangée.
- C. L'azote est un gaz inerte qui ne réagit avec rien, donc son enthalpie est toujours nulle.
- D. La valeur a été mesurée expérimentalement et s'est révélée être exactement zéro par coïncidence.

**Réponse correcte** : A

**Feedback correct**
Par convention, l'enthalpie standard de formation d'un corps pur simple dans son état de référence le plus stable est fixée à zéro : le former « à partir de lui-même » ne correspond à aucune réaction chimique, donc il n'y a aucune variation d'enthalpie à mesurer.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{N2}$ possède au contraire une liaison triple $\ce{N#N}$ très forte — ce n'est pas l'absence de liaison qui explique la valeur nulle, mais la convention de référence.
- Si C : La réactivité chimique n'a aucun rapport avec cette convention : $\Delta_f H^\circ = 0$ est une définition, pas une observation expérimentale de réactivité.
- Si D : Ce n'est pas une coïncidence expérimentale mais une convention fixée par définition — un référentiel arbitraire mais pratique.

**Référence manuel** : thermochimie-1-formation-definition

---
id: q-enthalpie-de-formation-symbo-com-001
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Laquelle des équations suivantes est une réaction standard de formation à $298\ \text{K}$, $1\ \text{bar}$ ?

**Options**
- A. $\ce{C(graphite) + O2(g) -> CO2(g)}$
- B. $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$
- C. $\ce{CO2(g) + H2O(g) -> H2CO3(l)}$
- D. $\ce{C(diamant) + O2(g) -> CO2(g)}$

**Réponse correcte** : A

**Feedback correct**
$\ce{C(graphite)}$ et $\ce{O2(g)}$ sont tous deux des corps purs simples dans leur état le plus stable, et ils forment une mole d'un unique composé ($\ce{CO2}$) : les trois critères d'une réaction de formation sont respectés.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Deux produits sont formés simultanément ($\ce{CO2}$ et $\ce{H2O}$) — une réaction de formation ne forme qu'un seul composé, à raison d'une mole.
- Si C : Les réactifs $\ce{CO2(g)}$ et $\ce{H2O(g)}$ ne sont pas des corps purs simples, ce sont déjà des composés.
- Si D : Le diamant n'est pas la forme la plus stable du carbone dans les conditions standards (c'est le graphite) — seule la forme la plus stable sert de référence.

**Référence manuel** : thermochimie-1-formation-criteres

---
id: q-enthalpie-de-formation-symbo-app-001
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
On donne : $\Delta_f H^\circ(\ce{CH4,g}) = -75\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{CO2,g}) = -394\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{H2O,l}) = -286\ \text{kJ/mol}$. Calculez $\Delta_r H^\circ$ de la réaction $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$.

**Options**
- A. $-891\ \text{kJ/mol}$
- B. $-966\ \text{kJ/mol}$
- C. $-605\ \text{kJ/mol}$
- D. $+891\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ = [\Delta_f H^\circ(\ce{CO2}) + 2\times\Delta_f H^\circ(\ce{H2O,l})] - [\Delta_f H^\circ(\ce{CH4}) + 2\times 0] = [-394 + 2\times(-286)] - (-75) = -966-(-75) = -891\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-966\ \text{kJ/mol}$ correspond à la somme des produits seule, sans soustraire le terme des réactifs — n'oubliez pas de soustraire $\Delta_f H^\circ(\ce{CH4})$.
- Si C : $-605\ \text{kJ/mol}$ correspond à un oubli du coefficient stœchiométrique $2$ devant $\ce{H2O(l)}$ dans le calcul.
- Si D : $+891\ \text{kJ/mol}$ correspond à une inversion de signe — vérifiez l'ordre (produits moins réactifs, et non l'inverse).

**Référence manuel** : thermochimie-1-enthalpie-formation

---
id: q-enthalpie-de-formation-symbo-app-002
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
On donne $\Delta_f H^\circ(\ce{H2O,g}) = -242\ \text{kJ/mol}$. Calculez $\Delta_r H^\circ$ de la réaction $\ce{2 H2(g) + O2(g) -> 2 H2O(g)}$.

**Options**
- A. $-484\ \text{kJ/mol}$
- B. $-242\ \text{kJ/mol}$
- C. $-572\ \text{kJ/mol}$
- D. $+484\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ = 2\times\Delta_f H^\circ(\ce{H2O,g}) - [2\times 0 + 0] = 2\times(-242) = -484\ \text{kJ/mol}$ (les réactifs $\ce{H2}$ et $\ce{O2}$ sont des corps purs simples, donc leur enthalpie de formation est nulle).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-242\ \text{kJ/mol}$ oublie le coefficient stœchiométrique $2$ devant $\ce{H2O(g)}$ dans le bilan.
- Si C : $-572\ \text{kJ/mol}$ utilise par erreur la valeur de l'eau liquide ($\Delta_f H^\circ(\ce{H2O,l}) = -286\ \text{kJ/mol}$) — ici le produit formé est $\ce{H2O(g)}$, pas $\ce{H2O(l)}$.
- Si D : $+484\ \text{kJ/mol}$ inverse le signe du résultat.

**Référence manuel** : thermochimie-1-formation-definition

<!-- ============================================================ -->
<!-- LOT 4 — Loi de Hess                                            -->
<!-- Concepts : loi-de-hess, loi-de-hess-generalisee (scindé le 04.11.2026) -->
<!-- 6 questions obligatoires (symbo·com ×2, symbo·app ×2, symbo·ana, symbo·eva) -->
<!-- ============================================================ -->

---
id: q-loi-de-hess-symbo-com-001
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
La loi de Hess permet de combiner (additionner, soustraire, multiplier) des équations de réactions dont les $\Delta_r H^\circ$ sont connus pour obtenir le $\Delta_r H^\circ$ d'une réaction cible. Quelle propriété de l'enthalpie justifie cette méthode ?

**Options**
- A. L'enthalpie est une fonction d'état : sa variation ne dépend que des états initial et final, pas du chemin suivi.
- B. L'enthalpie est une grandeur extensive, donc elle s'additionne toujours entre réactions.
- C. Les réactions chimiques respectent toujours la conservation de la masse, ce qui permet de les combiner.
- D. L'enthalpie est toujours négative pour les réactions exothermiques, ce qui facilite les additions.

**Réponse correcte** : A

**Feedback correct**
Parce que $H$ est une fonction d'état, deux chemins chimiques reliant le même état initial au même état final ont exactement le même $\Delta_r H^\circ$ — on peut donc remplacer un chemin direct par une combinaison de réactions intermédiaires sans changer le résultat.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'extensivité (le fait que $H$ dépende de la quantité de matière) permet de multiplier par des coefficients, mais ce n'est pas elle qui justifie que deux chemins différents donnent le même résultat — c'est le caractère de fonction d'état.
- Si C : La conservation de la masse est nécessaire pour équilibrer les équations, mais elle ne dit rien sur le fait que $\Delta_r H^\circ$ ne dépend pas du chemin suivi.
- Si D : Le signe de $\Delta_r H^\circ$ n'a aucun rapport avec la possibilité de combiner les réactions — la loi de Hess s'applique aussi bien aux réactions endothermiques.

**Référence manuel** : thermochimie-1-hess-fonction-etat

---
id: q-loi-de-hess-generalisee-symbo-com-001
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Une réaction a pour enthalpie $\Delta_r H^\circ = -120\ \text{kJ/mol}$. Si l'on multiplie tous les coefficients stœchiométriques de cette réaction par $3$, que devient $\Delta_r H^\circ$ ?

**Options**
- A. $-360\ \text{kJ/mol}$
- B. $-120\ \text{kJ/mol}$
- C. $-40\ \text{kJ/mol}$
- D. $+360\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
Lorsqu'on multiplie les coefficients stœchiométriques par un facteur $\lambda$, on multiplie $\Delta_r H^\circ$ par ce même facteur : $\Delta_r H^\circ = 3\times(-120) = -360\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-120\ \text{kJ/mol}$ suppose à tort que $\Delta_r H^\circ$ resterait identique — or multiplier les coefficients, c'est faire réagir 3 fois plus de matière, donc échanger 3 fois plus d'énergie.
- Si C : $-40\ \text{kJ/mol}$ divise au lieu de multiplier — c'est l'opération inverse de celle demandée.
- Si D : $+360\ \text{kJ/mol}$ inverse le signe alors que seule la quantité de matière change, pas le sens de la réaction.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-generalisee-symbo-app-001
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
On dispose de : (a) $\ce{C(graphite) + O2(g) -> CO2(g)}$, $\Delta_r H^\circ_{(a)} = -394\ \text{kJ/mol}$ ; (b) $\ce{H2(g) + \frac{1}{2} O2(g) -> H2O(l)}$, $\Delta_r H^\circ_{(b)} = -286\ \text{kJ/mol}$ ; (c) $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$, $\Delta_r H^\circ_{(c)} = -890\ \text{kJ/mol}$. Calculez $\Delta_f H^\circ(\ce{CH4,g})$.

**Options**
- A. $-76\ \text{kJ/mol}$
- B. $+76\ \text{kJ/mol}$
- C. $+210\ \text{kJ/mol}$
- D. $-1856\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_f H^\circ(\ce{CH4,g}) = \Delta_r H^\circ_{(a)} + 2\times\Delta_r H^\circ_{(b)} - \Delta_r H^\circ_{(c)} = -394 + 2\times(-286) - (-890) = -966 + 890 = -76\ \text{kJ/mol}$. La réaction cible $\ce{C(graphite) + 2 H2(g) -> CH4(g)}$ s'obtient en additionnant (a), deux fois (b), et en soustrayant (c) — ce qui revient à additionner son inverse.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+76\ \text{kJ/mol}$ inverse le signe — vérifiez le sens de la combinaison : c'est bien (a) + 2(b) − (c), pas l'inverse.
- Si C : $+210\ \text{kJ/mol}$ oublie le coefficient stœchiométrique $2$ devant la réaction (b) — il faut 2 mol de $\ce{H2}$ pour former $\ce{CH4}$.
- Si D : $-1856\ \text{kJ/mol}$ additionne (c) au lieu de la soustraire — (c) doit être inversée puisque $\ce{CH4}$ y est un réactif alors qu'il est le produit recherché dans la cible.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-generalisee-symbo-app-002
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
On dispose de : (1) $\ce{X(s) + Y2(g) -> XY2(s)}$, $\Delta_r H^\circ_{(1)} = -200\ \text{kJ/mol}$ ; (2) $\ce{2 XY2(s) + Y2(g) -> 2 XY3(s)}$, $\Delta_r H^\circ_{(2)} = -150\ \text{kJ/mol}$. Calculez $\Delta_r H^\circ$ de la réaction cible $\ce{X(s) + \frac{3}{2} Y2(g) -> XY3(s)}$.

**Options**
- A. $-275\ \text{kJ/mol}$
- B. $-350\ \text{kJ/mol}$
- C. $-125\ \text{kJ/mol}$
- D. $-500\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
La réaction cible ne forme qu'**une mole** de $\ce{XY3}$ : il faut donc prendre (1) entière, plus la **moitié** de (2) (pour ramener son coefficient de $2\ \ce{XY3}$ à $1\ \ce{XY3}$) : $\Delta_r H^\circ = \Delta_r H^\circ_{(1)} + \frac{1}{2}\times\Delta_r H^\circ_{(2)} = -200 + \frac{1}{2}\times(-150) = -200-75 = -275\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-350\ \text{kJ/mol}$ additionne (2) en entier au lieu de sa moitié — vérifiez les coefficients stœchiométriques de la réaction cible (1 mol de $\ce{XY3}$, pas 2).
- Si C : $-125\ \text{kJ/mol}$ soustrait la moitié de (2) au lieu de l'additionner.
- Si D : $-500\ \text{kJ/mol}$ multiplie (2) par $2$ au lieu de le diviser par $2$ — l'opération inverse de celle nécessaire.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-generalisee-symbo-ana-001
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-10-05
statut: validated
---

**Question**
On dispose de trois réactions connues : (1) $\ce{C2H6(g) + \frac{7}{2} O2(g) -> 2 CO2(g) + 3 H2O(l)}$ ; (2) $\ce{C(graphite) + O2(g) -> CO2(g)}$ ; (3) $\ce{H2(g) + \frac{1}{2} O2(g) -> H2O(l)}$. On cherche $\Delta_f H^\circ$ de la réaction cible $\ce{2 C(graphite) + 3 H2(g) -> C2H6(g)}$. Quelle combinaison des réactions (1), (2) et (3) permet d'obtenir exactement cette cible ?

**Options**
- A. $2\times(2) + 3\times(3) - (1)$
- B. $(1) + 2\times(2) + 3\times(3)$
- C. $(2) + (3) - (1)$
- D. $2\times(1) - (2) - (3)$

**Réponse correcte** : A

**Feedback correct**
La cible forme $\ce{C2H6}$ à partir des éléments — $\ce{C2H6}$ est un **réactif** dans (1), donc (1) doit être **inversée** (soustraite) pour qu'il devienne produit. Il faut $2$ mol de $\ce{CO2}$, donc $2\times(2)$, et $3$ mol de $\ce{H2O}$, donc $3\times(3)$, pour que ces espèces s'annulent avec celles produites par (1) inversée.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : additionner (1) au lieu de la soustraire reviendrait à consommer du $\ce{C2H6}$ en plus d'en former — incohérent avec une cible où $\ce{C2H6}$ n'apparaît que comme produit.
- Si C : (2) et (3) seuls, sans coefficients ni (1), ne permettent ni d'obtenir la bonne stœchiométrie ni d'éliminer le $\ce{CO2}$ et le $\ce{H2O}$, qui n'apparaissent pas dans la cible.
- Si D : multiplier (1) par $2$ introduit des coefficients incompatibles avec la cible (1 mol de $\ce{C2H6}$ seulement) et ne permet pas d'éliminer $\ce{CO2}$/$\ce{H2O}$ avec les bons coefficients.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-symbo-eva-001
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
misconception: loi-de-hess--independance-chemin-sans-restriction-conditions
date_validation: 2026-10-05
statut: validated
---

**Question**
Un élève affirme : « Puisque l'enthalpie est une fonction d'état, le $\Delta_r H^\circ$ d'une réaction est rigoureusement le même quel que soit le chemin réactionnel emprunté, même si les conditions de température ou de pression diffèrent d'un chemin à l'autre. » Cette affirmation est-elle correcte ?

**Options**
- A. Non — la loi de Hess garantit l'indépendance au chemin seulement si tous les chemins relient le même état initial et le même état final dans les mêmes conditions ($T$, $P$) ; changer les conditions change l'état thermodynamique du système.
- B. Oui — l'enthalpie étant une fonction d'état, sa variation ne dépend jamais des conditions expérimentales.
- C. Non — la loi de Hess ne s'applique qu'aux réactions exothermiques, jamais aux réactions endothermiques.
- D. Oui, mais seulement si la réaction est réalisée en phase gazeuse.

**Réponse correcte** : A

**Feedback correct**
La propriété de fonction d'état garantit l'indépendance au chemin pour des états initial et final **donnés** — or un « état » thermodynamique inclut la température et la pression. Deux chemins effectués à des conditions $(T, P)$ différentes ne relient pas rigoureusement le même état initial ni le même état final : la comparaison n'est valide que si l'on travaille à conditions constantes (ici, les conditions standards $298\ \text{K}$, $1\ \text{bar}$).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : c'est une généralisation abusive — le caractère « fonction d'état » ne dispense pas de fixer les mêmes conditions $(T, P)$ pour que la comparaison entre chemins soit valide.
- Si C : la loi de Hess s'applique aussi bien aux réactions endothermiques qu'exothermiques — le signe de $\Delta_r H^\circ$ n'intervient pas dans sa validité.
- Si D : la loi de Hess n'est pas restreinte à la phase gazeuse — elle s'applique à toutes les phases, tant que les conditions ($T$, $P$, état physique) sont cohérentes entre les chemins comparés.

**Référence manuel** : thermochimie-1-hess-fonction-etat

<!-- ============================================================ -->
<!-- LOT 5 — Enthalpies de dissolution                             -->
<!-- Concept : enthalpie-de-dissolution                             -->
<!-- 8 questions obligatoires (macro·com, parti·com ×2, symbo·com, symbo·app ×2, symbo·eva ×2) -->
<!-- ============================================================ -->

---
id: q-enthalpie-de-dissolution-macro-com-001
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Une compresse froide instantanée contient un sachet de $\ce{NH4NO3(s)}$ qui se dissout dans l'eau lorsqu'on presse l'emballage. Pourquoi la compresse devient-elle froide au toucher ?

**Options**
- A. La dissolution de $\ce{NH4NO3}$ est endothermique : elle absorbe de la chaleur du milieu environnant, ce qui abaisse la température de la solution.
- B. L'eau se solidifie partiellement au contact du sel, ce qui refroidit la compresse.
- C. Le sachet contient un gaz comprimé qui se détend et refroidit l'ensemble.
- D. La dissolution libère du froid directement, comme un produit de la réaction.

**Réponse correcte** : A

**Feedback correct**
La dissociation des ions du cristal (étape endothermique) l'emporte ici sur la solvatation (étape exothermique) : le bilan $\Delta H^\circ_\text{diss}$ est positif, donc la solution absorbe de la chaleur de son environnement — d'où la sensation de froid.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : rien ne se solidifie ici — au contraire, un solide ($\ce{NH4NO3}$) se dissout, il ne se forme pas de glace.
- Si C : aucun gaz comprimé n'est impliqué dans ce dispositif — c'est purement un phénomène de dissolution en solution aqueuse.
- Si D : « le froid » n'est pas une substance qui se libère — c'est l'absence de chaleur produite (voire son absorption) qui abaisse la température ; on ne peut pas « produire » du froid comme un produit chimique.

**Référence manuel** : thermochimie-1-dissolution-etapes

---
id: q-enthalpie-de-dissolution-parti-com-001
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Au niveau particulaire, que se passe-t-il durant l'étape de **dissociation** lors de la dissolution d'un sel ionique dans l'eau ?

**Options**
- A. Les ions du cristal s'éloignent les uns des autres, ce qui rompt les interactions électrostatiques attractives entre cations et anions — une étape qui coûte de l'énergie.
- B. Les molécules d'eau se brisent en ions $\ce{H+}$ et $\ce{OH-}$ pour réagir avec le sel.
- C. Les ions se combinent entre eux pour former de nouvelles liaisons covalentes avec l'eau.
- D. Les électrons de valence du sel sont transférés aux molécules d'eau, créant un courant électrique.

**Réponse correcte** : A

**Feedback correct**
Séparer des charges opposées qui s'attirent demande de l'énergie — par définition, cette étape (rompre le réseau cristallin ionique) est toujours endothermique, quelle que soit la nature du sel.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : l'eau ne se dissocie pas en ions $\ce{H+}$/$\ce{OH-}$ pendant une dissolution ordinaire — ce phénomène (autoprotolyse) est indépendant et nettement plus rare.
- Si C : il ne se forme pas de liaisons covalentes entre les ions et l'eau — les interactions ion-dipôle de la solvatation sont de nature électrostatique, non covalente.
- Si D : aucun transfert d'électrons ni courant électrique n'est impliqué — la dissolution est un phénomène physique de séparation de charges déjà existantes, pas une réaction redox.

**Référence manuel** : thermochimie-1-dissolution-etapes

---
id: q-enthalpie-de-dissolution-parti-com-002
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Pourquoi l'étape de **solvatation** (hydratation) des ions est-elle toujours exothermique ?

**Options**
- A. Les molécules d'eau s'orientent autour des ions (dipôles pointant vers les charges opposées), créant de nouvelles interactions ion-dipôle attractives qui libèrent de l'énergie.
- B. L'eau s'évapore autour des ions, ce qui libère de la chaleur latente de vaporisation.
- C. Les ions perdent leur charge électrique au contact de l'eau, ce qui libère de l'énergie.
- D. La solvatation forme de nouvelles liaisons covalentes entre les ions et l'oxygène de l'eau.

**Réponse correcte** : A

**Feedback correct**
Former de nouvelles interactions attractives (ion-dipôle) entre les ions et les molécules d'eau libère de l'énergie — comme toute formation d'interaction stabilisante, c'est un processus exothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : au contraire, l'eau s'organise autour des ions — elle ne s'évapore pas ; l'énergie vient de la formation d'interactions, pas d'un changement de phase de l'eau.
- Si C : les ions conservent leur charge en solution (ce sont toujours des ions solvatés, pas des atomes neutres) — ce n'est pas une perte de charge qui explique l'exothermicité.
- Si D : les interactions ion-dipôle sont électrostatiques, pas covalentes — aucune liaison covalente nouvelle ne se forme entre l'ion et l'eau.

**Référence manuel** : thermochimie-1-dissolution-etapes

---
id: q-enthalpie-de-dissolution-symbo-com-001
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Laquelle de ces relations exprime correctement l'enthalpie de dissolution d'un sel ionique en fonction des deux étapes conceptuelles ?

**Options**
- A. $\Delta H^\circ_\text{dissolution} = \Delta H^\circ_\text{dissociation} + \Delta H^\circ_\text{solvatation}$
- B. $\Delta H^\circ_\text{dissolution} = \Delta H^\circ_\text{dissociation} - \Delta H^\circ_\text{solvatation}$
- C. $\Delta H^\circ_\text{dissolution} = \Delta H^\circ_\text{dissociation} \times \Delta H^\circ_\text{solvatation}$
- D. $\Delta H^\circ_\text{dissolution} = -(\Delta H^\circ_\text{dissociation} + \Delta H^\circ_\text{solvatation})$

**Réponse correcte** : A

**Feedback correct**
L'enthalpie de dissolution étant une fonction d'état (loi de Hess), elle est simplement la somme des deux contributions, quels que soient leurs signes respectifs (dissociation toujours positive, solvatation toujours négative).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : soustraire reviendrait à ignorer que les deux étapes sont des contributions indépendantes qui s'additionnent — pas un bilan différentiel.
- Si C : les enthalpies ne se multiplient jamais entre elles — ce sont des grandeurs qui s'additionnent (en kJ/mol), pas des facteurs sans dimension.
- Si D : inverser le signe de la somme ne correspond à aucune justification physique — l'enthalpie de dissolution garde le signe du bilan réel des deux étapes.

**Référence manuel** : thermochimie-1-dissolution-etapes

---
id: q-enthalpie-de-dissolution-symbo-app-001
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
On donne : $\Delta_f H^\circ(\ce{KBr,s}) = -394\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{K+,aq}) = -252\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{Br-,aq}) = -121\ \text{kJ/mol}$. Calculez $\Delta H^\circ_\text{diss}$ de $\ce{KBr(s) -> K+(aq) + Br-(aq)}$.

**Options**
- A. $+21\ \text{kJ/mol}$
- B. $-21\ \text{kJ/mol}$
- C. $-767\ \text{kJ/mol}$
- D. $+767\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta H^\circ_\text{diss} = \Delta_f H^\circ(\ce{K+,aq}) + \Delta_f H^\circ(\ce{Br-,aq}) - \Delta_f H^\circ(\ce{KBr,s}) = (-252) + (-121) - (-394) = -373 + 394 = +21\ \text{kJ/mol}$ — légèrement endothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-21\ \text{kJ/mol}$ inverse le signe — vérifiez l'ordre (produits moins réactif, pas l'inverse).
- Si C : $-767\ \text{kJ/mol}$ additionne les trois termes avec le même signe au lieu de soustraire $\Delta_f H^\circ(\ce{KBr,s})$ — n'oubliez pas qu'il s'agit du réactif, donc à soustraire.
- Si D : $+767\ \text{kJ/mol}$ commet la même erreur d'addition que l'option C, avec en plus une inversion de signe supplémentaire.

**Référence manuel** : thermochimie-1-dissolution-calcul

---
id: q-enthalpie-de-dissolution-symbo-app-002
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La dissolution du sulfate de cuivre ($\ce{CuSO4(s) -> Cu^2+(aq) + SO4^2-(aq)}$) a pour enthalpie $\Delta H^\circ_\text{diss} = -68\ \text{kJ/mol}$ (exothermique). Quelle est l'enthalpie de la cristallisation inverse $\ce{Cu^2+(aq) + SO4^2-(aq) -> CuSO4(s)}$ ?

**Options**
- A. $+68\ \text{kJ/mol}$
- B. $-68\ \text{kJ/mol}$
- C. $-34\ \text{kJ/mol}$
- D. $0\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
Inverser une réaction change le signe de son enthalpie (loi de Hess) : si la dissolution est exothermique ($-68\ \text{kJ/mol}$), la cristallisation inverse est endothermique de même ampleur ($+68\ \text{kJ/mol}$) — c'est exactement ce mécanisme qu'exploitent les chaufferettes réutilisables, où l'inverse d'une dissolution endothermique est une cristallisation qui libère de la chaleur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-68\ \text{kJ/mol}$ suppose à tort qu'inverser une réaction ne change rien — or le signe doit être inversé.
- Si C : $-34\ \text{kJ/mol}$ divise par erreur l'enthalpie par 2, alors qu'aucune opération d'échelle n'est demandée ici (seulement une inversion).
- Si D : $0\ \text{kJ/mol}$ supposerait que les deux processus s'annulent, ce qui n'a pas de sens physique — ce sont deux processus opposés, pas simultanés.

**Référence manuel** : thermochimie-1-chaufferettes

---
id: q-enthalpie-de-dissolution-symbo-eva-001
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
misconception: enthalpie-de-dissolution--spontaneite-sans-entropie
date_validation: 2026-10-05
statut: validated
---

**Question**
La dissolution de $\ce{NaCl}$ dans l'eau est légèrement endothermique ($\Delta H^\circ_\text{diss} = +4\ \text{kJ/mol}$), et pourtant ce sel se dissout spontanément à température ambiante. Un élève en conclut : « Puisque la réaction est spontanée, son $\Delta H^\circ$ doit forcément être négatif — il doit y avoir une erreur dans ce calcul. » Cette conclusion est-elle correcte ?

**Options**
- A. Non — la spontanéité d'une transformation dépend à la fois de l'enthalpie ET de l'entropie ; une réaction endothermique peut être spontanée si l'augmentation de désordre (entropie) du système compense le coût enthalpique.
- B. Oui — une réaction spontanée a toujours un $\Delta H^\circ$ négatif, donc il y a bien une erreur dans le calcul de $+4\ \text{kJ/mol}$.
- C. Non — la spontanéité ne dépend que de la température, pas de l'enthalpie ni de l'entropie.
- D. Oui, mais seulement parce que $\ce{NaCl}$ est un sel ionique particulier ; pour les autres sels, un $\Delta H^\circ$ positif empêcherait toujours la dissolution.

**Réponse correcte** : A

**Feedback correct**
La spontanéité d'une transformation est déterminée par l'enthalpie libre $\Delta G^\circ = \Delta H^\circ - T\Delta S^\circ$, qui combine l'effet enthalpique ET l'effet entropique (formalisé au chapitre suivant). Ici, la forte augmentation de désordre lorsque les ions se dispersent dans l'eau (entropie positive) compense largement le léger coût enthalpique ($+4\ \text{kJ/mol}$), rendant la dissolution spontanée malgré son caractère endothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : c'est précisément la conception erronée à éviter — de nombreuses transformations spontanées sont endothermiques (la fonte de la glace au-dessus de $0\ ^\circ\text{C}$, par exemple) ; le $\Delta H^\circ$ seul ne détermine pas la spontanéité.
- Si C : la température intervient (via le terme $T\Delta S^\circ$), mais l'enthalpie ET l'entropie jouent toutes deux un rôle — ce n'est pas la température seule qui décide.
- Si D : il n'y a rien de « particulier » à $\ce{NaCl}$ ici — le même principe ($\Delta G^\circ = \Delta H^\circ - T\Delta S^\circ$) s'applique à tous les sels ; certains sels très endothermiques à dissoudre ne se dissolvent effectivement pas spontanément, précisément quand l'entropie ne compense pas suffisamment.

**Référence manuel** : thermochimie-1-dissolution-calcul

---
id: q-enthalpie-de-dissolution-symbo-eva-002
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-10-05
statut: validated
---

**Question**
Un élève affirme : « $\ce{NaCl}$ et $\ce{CaCl2}$ contiennent tous deux des ions $\ce{Cl-}$, donc leurs enthalpies de dissolution devraient être très proches. » Or, la dissolution de $\ce{CaCl2}$ est nettement plus exothermique que celle de $\ce{NaCl}$. Quelle explication évalue correctement cette différence ?

**Options**
- A. Le cation $\ce{Ca^2+}$ porte une double charge, ce qui crée des interactions ion-dipôle bien plus fortes avec l'eau que le cation $\ce{Na+}$ (simple charge) : l'étape de solvatation est donc beaucoup plus exothermique pour $\ce{CaCl2}$, ce qui l'emporte sur l'étape de dissociation.
- B. L'affirmation de l'élève est correcte : la présence des mêmes ions $\ce{Cl-}$ garantit des enthalpies de dissolution identiques, l'écart observé est une erreur expérimentale.
- C. $\ce{CaCl2}$ contient deux fois plus d'atomes de chlore, donc son enthalpie de dissolution est automatiquement deux fois plus négative.
- D. Le calcium est un métal plus réactif que le sodium, ce qui rend toute réaction impliquant $\ce{Ca^2+}$ plus exothermique par nature.

**Réponse correcte** : A

**Feedback correct**
Comparer uniquement l'anion commun ($\ce{Cl-}$) ignore le rôle du cation : une charge plus élevée ($\ce{Ca^2+}$, charge $2+$) crée des interactions électrostatiques ion-dipôle bien plus fortes avec les molécules d'eau polaires qu'une charge simple ($\ce{Na+}$), ce qui rend l'étape de solvatation beaucoup plus exothermique et déplace le bilan global vers des valeurs plus négatives.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : l'écart observé n'est pas une erreur — il reflète une réelle différence physique entre les deux sels, liée à la charge du cation, pas seulement à la présence d'un anion commun.
- Si C : le nombre d'atomes de chlore (stœchiométrie) n'explique pas à lui seul l'intensité de l'enthalpie par mole de sel dissous — c'est la nature des interactions ion-dipôle, pas un simple facteur de comptage, qui est en cause.
- Si D : la « réactivité » d'un métal (au sens de la série d'activité) n'est pas le facteur pertinent ici — c'est la charge ionique du cation en solution qui détermine la force de ses interactions avec l'eau, indépendamment de la réactivité du métal à l'état solide.

**Référence manuel** : thermochimie-1-dissolution-calcul

<!-- ============================================================ -->
<!-- LOT 6 — Capacité thermique massique et calorimétrie           -->
<!-- Concepts : capacite-thermique-massique, calorimetrie           -->
<!-- 8 questions obligatoires (2 + 6)                               -->
<!-- ============================================================ -->

---
id: q-capacite-thermique-massique-macro-com-001
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
L'eau possède une capacité thermique massique élevée ($C_p = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$). Quelle conséquence macroscopique cela a-t-il pour un lac en été ?

**Options**
- A. Le lac se réchauffe et se refroidit lentement, atténuant les variations de température de l'air environnant — il agit comme un régulateur thermique.
- B. Le lac bout plus facilement que d'autres liquides car il absorbe beaucoup d'énergie.
- C. Le lac gèle plus rapidement en hiver car il retient mal la chaleur.
- D. La capacité thermique élevée signifie que l'eau conduit très bien l'électricité.

**Réponse correcte** : A

**Feedback correct**
Une capacité thermique massique élevée signifie qu'il faut beaucoup d'énergie pour faire varier la température de l'eau d'un seul kelvin — un grand volume d'eau absorbe ou restitue donc beaucoup de chaleur sans que sa température change énormément, ce qui stabilise le climat environnant.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : au contraire, une $C_p$ élevée signifie qu'il faut PLUS d'énergie pour élever la température (donc pour la faire bouillir), pas moins — l'eau ne bout pas plus facilement.
- Si C : c'est l'inverse : une $C_p$ élevée signifie que l'eau retient bien la chaleur et se refroidit lentement, donc elle gèle plus difficilement (plus lentement), pas plus rapidement.
- Si D : la capacité thermique massique est une grandeur thermodynamique (liée à la chaleur), sans rapport avec la conductivité électrique.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-capacite-thermique-massique-symbo-app-001
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
On chauffe $250\ \text{g}$ d'eau de $18\ ^\circ\text{C}$ à $41\ ^\circ\text{C}$. Quelle quantité de chaleur a été absorbée par l'eau ? ($C_p(\ce{H2O,l}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$)

**Options**
- A. $+24{,}0\ \text{kJ}$
- B. $+42{,}8\ \text{kJ}$
- C. $+24\ 035\ \text{kJ}$
- D. $-24{,}0\ \text{kJ}$

**Réponse correcte** : A

**Feedback correct**
$Q = m\cdot C_p\cdot\Delta T = 250 \times 4{,}18 \times (41-18) = 250 \times 4{,}18 \times 23$. Le résultat est $Q = 24035\ \text{J}$, soit $Q \approx +24{,}0\ \text{kJ}$ (l'eau absorbe de la chaleur, donc $Q$ est positif).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+42{,}8\ \text{kJ}$ utilise $\Delta T = 41\ ^\circ\text{C}$ au lieu de la variation réelle $\Delta T = T_\text{final} - T_\text{initial} = 41-18 = 23\ ^\circ\text{C}$.
- Si C : $+24\ 035\ \text{kJ}$ oublie de convertir les joules en kilojoules (facteur $1000$) — relisez les unités de $C_p$.
- Si D : $-24{,}0\ \text{kJ}$ inverse le signe : l'eau se réchauffe, elle absorbe donc de la chaleur ($Q$ positif), elle n'en cède pas.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-capacite-thermique-massique-macro-com-002
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-11-01
statut: validated
---

**Question**
Deux calorimètres contiennent respectivement $100\ \text{g}$ et $10\ \text{kg}$ d'eau. Une même réaction dégageant $1\ \text{kJ}$ s'y déroule dans chacun. Que peut-on dire des variations de température ?

**Options**
- A. La température augmente autant dans les deux, puisque la chaleur dégagée est la même
- B. La température augmente davantage dans le calorimètre de $10\ \text{kg}$, car il contient plus d'eau
- C. Elle augmente beaucoup moins dans celui de $10\ \text{kg}$, où la chaleur est répartie sur plus de masse
- D. On ne peut rien dire sans connaître la nature de la réaction

**Réponse correcte** : C

**Feedback correct**
Pour une même chaleur, $\Delta T = Q/(m \cdot C_p)$ est inversement proportionnelle à la masse : environ $2{,}4\ ^\circ\text{C}$ pour $100\ \text{g}$ contre $0{,}024\ ^\circ\text{C}$ pour $10\ \text{kg}$. La chaleur échangée est identique, la variation de température non.

**Feedback incorrect**
- Si A : La chaleur échangée est identique, mais la variation de température dépend aussi de la masse chauffée : à chaleur égale, plus la masse est grande, moins la température varie.
- Si B : C'est le contraire : plus la masse d'eau est grande, plus la même chaleur se répartit, et moins la température augmente.
- Si C : C'est la bonne réponse.
- Si D : La nature de la réaction n'importe pas ici : la chaleur dégagée est donnée ($1\ \text{kJ}$). Seules la masse et la capacité thermique de l'eau déterminent $\Delta T$.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-capacite-thermique-massique-symbo-sou-001
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-01
statut: validated
---

**Question**
Quelle est la capacité thermique massique de l'eau liquide ?

**Options**
- A. $418\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$
- B. $4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$
- C. $4{,}18\ \text{kJ}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$
- D. $1{,}00\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$

**Réponse correcte** : B

**Feedback correct**
$C_p(\ce{H2O,l}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ : il faut $4{,}18\ \text{J}$ pour élever de $1\ \text{K}$ la température de $1\ \text{g}$ d'eau.

**Feedback incorrect**
- Si A : Cette valeur est cent fois trop grande : il s'agit de $4{,}18$ joules, pas $418$ joules, par gramme et par kelvin.
- Si B : C'est la bonne réponse.
- Si C : Cette valeur est mille fois trop grande : l'unité est le joule, pas le kilojoule.
- Si D : La valeur $1{,}00$ est celle de la calorie, d'une autre unité d'énergie : en joules, $C_p$ de l'eau vaut $4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-capacite-thermique-massique-symbo-app-002
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-01
statut: validated
---

**Question**
Quelle chaleur faut-il fournir pour chauffer $500\ \text{g}$ d'eau de $20\ ^\circ\text{C}$ à $60\ ^\circ\text{C}$ ? ($C_p(\ce{H2O,l}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$)

**Options**
- A. $+2{,}09\ \text{kJ}$
- B. $+125\ \text{kJ}$
- C. $+83{,}6\ \text{kJ}$
- D. $+0{,}0836\ \text{kJ}$

**Réponse correcte** : C

**Feedback correct**
$Q = m \cdot C_p \cdot \Delta T = 500 \times 4{,}18 \times (60 - 20) = 83600\ \text{J} = +83{,}6\ \text{kJ}$.

**Feedback incorrect**
- Si A : Cette valeur ($500 \times 4{,}18$) oublie le facteur $\Delta T = 40\ \text{K}$.
- Si B : Cette valeur utilise $60$ au lieu de $\Delta T = 60 - 20 = 40$ : on prend la variation de température, pas la température finale.
- Si C : C'est la bonne réponse.
- Si D : Cette valeur est mille fois trop petite : $83600\ \text{J}$ valent $83{,}6\ \text{kJ}$, pas $0{,}0836\ \text{kJ}$.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-capacite-thermique-massique-symbo-app-003
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-01
statut: validated
---

**Question**
Une chaleur de $12{,}5\ \text{kJ}$ est absorbée par $300\ \text{g}$ d'eau liquide. Quelle est la variation de température de l'eau ? ($C_p(\ce{H2O,l}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$)

**Options**
- A. $\Delta T \approx 0{,}10\ ^\circ\text{C}$
- B. $\Delta T \approx 10{,}0\ ^\circ\text{C}$
- C. $\Delta T \approx 52{,}3\ ^\circ\text{C}$
- D. $\Delta T \approx 2990\ ^\circ\text{C}$

**Réponse correcte** : B

**Feedback correct**
$\Delta T = Q/(m \cdot C_p) = 12500/(300 \times 4{,}18) \approx 10{,}0\ ^\circ\text{C}$. Il faut convertir la chaleur en joules avant d'appliquer la formule.

**Feedback incorrect**
- Si A : Cette valeur provient d'un oubli de conversion en joules : $12{,}5\ \text{kJ}$ valent $12500\ \text{J}$.
- Si B : C'est la bonne réponse.
- Si C : Cette valeur multiplie $Q$ par $C_p$ ($12{,}5 \times 4{,}18$). Pour trouver $\Delta T$, on divise $Q$ par $m \cdot C_p$.
- Si D : Cette valeur oublie de diviser par la masse : $12500/4{,}18 \approx 2990$. Il faut aussi diviser par $m = 300\ \text{g}$.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-calorimetrie-macro-com-001
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Dans un calorimètre bien isolé, pourquoi peut-on affirmer que « la chaleur perdue par la réaction est intégralement gagnée par le système (eau + parois) » ?

**Options**
- A. Parce que le calorimètre est thermiquement isolé de l'extérieur : aucune énergie ne s'échappe vers l'environnement, donc le bilan énergétique total de ce système isolé est nul (premier principe).
- B. Parce que la réaction chimique et l'eau ont toujours la même capacité thermique massique.
- C. Parce que la chaleur se propage instantanément et uniformément dans tout l'univers.
- D. Parce que les réactions chimiques produisent toujours exactement la quantité de chaleur que l'eau peut absorber.

**Réponse correcte** : A

**Feedback correct**
L'isolation thermique empêche tout échange avec l'extérieur — à l'intérieur de ce système fermé et isolé, l'énergie ne peut ni apparaître ni disparaître (premier principe), donc la chaleur cédée par l'un des sous-systèmes est nécessairement gagnée par l'autre : $Q_\text{réaction} + Q_\text{système} = 0$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : les capacités thermiques massiques des réactifs/produits et de l'eau n'ont aucune raison d'être égales — ce n'est pas cette égalité qui justifie le bilan, mais l'isolation thermique.
- Si C : la propagation de la chaleur n'est ni instantanée ni automatiquement uniforme — ce qui compte ici est la conservation de l'énergie dans un système isolé, pas la vitesse de propagation.
- Si D : ce n'est pas une coïncidence entre quantités « produites » et « absorbables » — c'est la conservation de l'énergie qui impose l'égalité des échanges, quelle que soit leur ampleur.

**Référence manuel** : thermochimie-1-calorimetrie-principe

---
id: q-calorimetrie-symbo-com-001
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Quelle relation représente le bilan calorimétrique complet, tenant compte de la constante calorimétrique $C_\text{cal}$ ?

**Options**
- A. $Q_\text{réaction} + \bigl(m_\text{eau}\cdot C_p + C_\text{cal}\bigr)\cdot \Delta T = 0$
- B. $Q_\text{réaction} = m_\text{eau}\cdot C_p\cdot \Delta T + C_\text{cal}$
- C. $Q_\text{réaction} \cdot \bigl(m_\text{eau}\cdot C_p + C_\text{cal}\bigr) = \Delta T$
- D. $Q_\text{réaction} = C_\text{cal} - m_\text{eau}\cdot C_p\cdot \Delta T$

**Réponse correcte** : A

**Feedback correct**
Le bilan calorimétrique complet additionne la chaleur absorbée par l'eau ET par l'appareillage (la constante calorimétrique), et ce total doit être égal et opposé à la chaleur cédée par la réaction, puisque le système global est isolé.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $C_\text{cal}$ n'est pas un terme additif indépendant de $\Delta T$ — la constante calorimétrique doit elle aussi être multipliée par $\Delta T$, car c'est une capacité thermique (en J/K), pas une quantité de chaleur fixe.
- Si C : la multiplication n'a pas de sens physique ici — chaleur et capacité thermique s'additionnent, elles ne se multiplient pas entre elles pour donner une variation de température.
- Si D : cette relation inverse le rôle des termes — $C_\text{cal}$ doit être multiplié par $\Delta T$, et $Q_\text{réaction}$ n'est pas une simple différence entre $C_\text{cal}$ et le terme en eau.

**Référence manuel** : thermochimie-1-bilan-calorimetrique

---
id: q-calorimetrie-symbo-app-001
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
On dissout $2{,}675\ \text{g}$ de $\ce{NH4Cl}$ ($M = 53{,}5\ \text{g/mol}$) dans $50\ \text{g}$ d'eau. La température passe de $22{,}0\ ^\circ\text{C}$ à $18{,}4\ ^\circ\text{C}$ ($C_\text{cal}$ négligée). Calculez $\Delta H^\circ_\text{diss}$ de $\ce{NH4Cl}$.

**Options**
- A. $+15{,}0\ \text{kJ/mol}$
- B. $-15{,}0\ \text{kJ/mol}$
- C. $+0{,}28\ \text{kJ/mol}$
- D. $+15048\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$n(\ce{NH4Cl}) = 2{,}675/53{,}5 = 0{,}0500\ \text{mol}$ ; $Q_\text{eau} = 50\times4{,}18\times(-3{,}6) = -752{,}4\ \text{J} = -0{,}7524\ \text{kJ}$ ; $Q_\text{réaction} = +0{,}7524\ \text{kJ}$ (la solution se refroidit, donc la dissolution absorbe de la chaleur) ; $\Delta H^\circ_\text{diss} = 0{,}7524/0{,}0500 \approx +15{,}0\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : inversion de signe — la température de l'eau diminue, donc la réaction absorbe de la chaleur ($Q_\text{réaction}>0$), pas l'inverse.
- Si C : confond la masse ($2{,}675\ \text{g}$) et la quantité de matière ($0{,}0500\ \text{mol}$) au dénominateur — il faut diviser par $n$ en moles, pas par $m$ en grammes.
- Si D : oublie de convertir les joules en kilojoules — relisez les unités de $Q$.

**Référence manuel** : thermochimie-1-bilan-calorimetrique

---
id: q-calorimetrie-symbo-app-002
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
La combustion de $1{,}20\ \text{g}$ de graphite dans une bombe calorimétrique contenant $600\ \text{g}$ d'eau élève la température de $10{,}0\ ^\circ\text{C}$ ($C_\text{cal}$ négligée). Calculez $\Delta_r H^\circ$ de la combustion du graphite, par mole.

**Options**
- A. $-251\ \text{kJ/mol}$
- B. $+251\ \text{kJ/mol}$
- C. $-20{,}9\ \text{kJ/mol}$
- D. $-25{,}1\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$n(\text{graphite}) = 1{,}20/12{,}0 = 0{,}100\ \text{mol}$ ; $Q_\text{eau} = 600\times4{,}18\times10{,}0 = 25080\ \text{J}$, soit $25{,}08\ \text{kJ}$. Donc $Q_\text{réaction} = -25{,}08\ \text{kJ}$, et $\Delta_r H^\circ = -25{,}08/0{,}100 \approx -251\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+251\ \text{kJ/mol}$ inverse le signe — l'eau se réchauffe donc la réaction est exothermique, $\Delta_r H^\circ$ est négatif.
- Si C : $-20{,}9\ \text{kJ/mol}$ divise par la masse en grammes ($1{,}20\ \text{g}$) au lieu de la quantité de matière en moles ($0{,}100\ \text{mol}$).
- Si D : $-25{,}1\ \text{kJ/mol}$ oublie de diviser par $n$ — ce chiffre est $Q_\text{réaction}$ en kJ, pas l'enthalpie molaire de réaction.

**Référence manuel** : thermochimie-1-bombe-calorimetrique

---
id: q-calorimetrie-symbo-ana-001
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
misconception: capacite-thermique-massique--chaleur-dependrait-seulement-temperature
date_validation: 2026-10-05
statut: validated
---

**Question**
Deux calorimètres reçoivent chacun exactement la même quantité de chaleur, $Q = 1{,}0\ \text{kJ}$, provenant de deux réactions identiques. Le premier contient $100\ \text{g}$ d'eau, le second $10\ \text{kg}$ d'eau. Un élève observe que le second calorimètre ne chauffe presque pas et en conclut : « La réaction dans le second calorimètre a dû dégager beaucoup moins de chaleur. » Que révèle l'analyse de la relation $Q = m\cdot C_p\cdot\Delta T$ sur cette conclusion ?

**Options**
- A. La conclusion est fausse : $Q$ est identique dans les deux cas ($1{,}0\ \text{kJ}$) ; c'est la masse d'eau $m$, bien plus grande dans le second calorimètre, qui dilue le même $Q$ sur une variation de température $\Delta T$ beaucoup plus petite.
- B. La conclusion est juste : une faible variation de température indique toujours une faible quantité de chaleur échangée.
- C. La conclusion est fausse : en réalité, c'est le premier calorimètre qui a reçu moins de chaleur, car sa masse d'eau est plus petite.
- D. La conclusion est fausse, mais seulement parce que les deux calorimètres ont des capacités thermiques massiques différentes.

**Réponse correcte** : A

**Feedback correct**
En isolant $\Delta T$ dans $Q = m\cdot C_p\cdot\Delta T$, on obtient $\Delta T = Q/(m\cdot C_p)$ : pour un même $Q$, $\Delta T$ est inversement proportionnel à $m$. Avec $100$ fois plus d'eau, le second calorimètre subit une variation de température $100$ fois plus petite — alors que la chaleur dégagée est rigoureusement identique. La variation de température seule ne permet donc pas de juger la quantité de chaleur échangée sans connaître la masse (et la capacité thermique) du système.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : c'est exactement la confusion à éviter — $\Delta T$ dépend aussi de la masse du système, pas seulement de $Q$ ; un grand volume d'eau peut absorber beaucoup de chaleur sans que sa température varie beaucoup.
- Si C : l'énoncé précise que $Q$ est identique ($1{,}0\ \text{kJ}$) dans les deux calorimètres — ce n'est donc ni l'un ni l'autre qui a reçu « moins » de chaleur.
- Si D : l'eau est utilisée dans les deux calorimètres, donc $C_p$ est le même ($4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$) — c'est la masse $m$, et non $C_p$, qui diffère et explique l'écart de $\Delta T$.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-calorimetrie-symbo-ana-002
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-10-05
statut: validated
---

**Question**
Dans une bombe calorimétrique contenant $m_1$ g d'eau à $T_1$, on ajoute $m_2$ g d'eau à $T_2$ (avec $T_2 > T_1$). Le mélange atteint une température d'équilibre $T_f$. Quelle équation de bilan permet de déterminer la constante calorimétrique $C_\text{cal}$ de l'appareil ?

**Options**
- A. $\bigl(m_1\cdot C_p + C_\text{cal}\bigr)\cdot(T_f-T_1) + m_2\cdot C_p\cdot(T_f-T_2) = 0$
- B. $m_1\cdot C_p\cdot(T_f-T_1) + \bigl(m_2\cdot C_p + C_\text{cal}\bigr)\cdot(T_f-T_2) = 0$
- C. $\bigl(m_1+m_2\bigr)\cdot C_p\cdot(T_f - T_1) = C_\text{cal}$
- D. $m_1\cdot C_p\cdot(T_f-T_1) = m_2\cdot C_p\cdot(T_f-T_2)$

**Réponse correcte** : A

**Feedback correct**
Avant l'ajout, le calorimètre (parois, thermomètre, agitateur) est en équilibre thermique avec les $m_1$ g d'eau à $T_1$ — ils se réchauffent donc ensemble jusqu'à $T_f$, ce qui justifie d'associer $C_\text{cal}$ au terme en $m_1$. L'eau ajoutée ($m_2$ g à $T_2$) se refroidit de son côté jusqu'à $T_f$. Le bilan du système isolé impose que la somme algébrique des deux chaleurs échangées soit nulle.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : associe à tort $C_\text{cal}$ à l'eau ajoutée ($m_2$) plutôt qu'à l'eau et aux parois déjà en équilibre thermique avant l'ajout ($m_1$) — c'est l'inverse de la configuration physique décrite.
- Si C : cette expression n'est pas un bilan de chaleur valide — elle mélange les masses sans respecter le bilan thermique d'un système isolé (somme des deux chaleurs échangées nulle), et isole $C_\text{cal}$ de façon incohérente dimensionnellement.
- Si D : cette équation omet complètement $C_\text{cal}$ — c'est justement l'erreur qui conduirait à sous-estimer (ou ignorer) l'énergie absorbée par l'appareillage lui-même.

**Référence manuel** : thermochimie-1-bilan-calorimetrique

<!-- LOT QUESTIONS DIFFICILES (lot-thermo.tmp.md, 02.11.2026) — statut to_fix -->

---
id: q-capacite-thermique-massique-symbo-ana-301
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-02
statut: validated
---

**Question**
Un morceau de métal de 100 g, chauffé à 100,0 °C, est plongé dans 200 g d'eau à 20,0 °C. La température d'équilibre est de 24,0 °C. On néglige les pertes de chaleur et la capacité du récipient. ($C_p(\ce{H2O}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ ; $C_p(\ce{Fe}) = 0{,}449$, $C_p(\ce{Cu}) = 0{,}385$, $C_p(\ce{Al}) = 0{,}897$, tous en $\text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$.) Quelles affirmations sont correctes ?

**Options**
- A. Le métal cède autant de chaleur que l'eau en absorbe : sa capacité thermique massique est donc égale à celle de l'eau
- B. L'eau absorbe environ 3,3 kJ
- C. Le métal pourrait être de l'aluminium
- D. La capacité thermique massique du métal vaut environ 0,44 J·g⁻¹·K⁻¹, ce qui est compatible avec du fer

**Réponse correcte** : B, D

**Feedback correct**
La chaleur absorbée par l'eau vaut $Q = 200 \times 4{,}18 \times 4{,}0 = 3344$ J, soit environ 3,3 kJ. Le métal cède cette même chaleur en se refroidissant de 76,0 °C : $C_p = 3344 / (100 \times 76{,}0) = 0{,}44$ J·g⁻¹·K⁻¹. Cette valeur est proche de celle du fer (0,449), loin de celles du cuivre (0,385) et surtout de l'aluminium (0,897).

**Feedback incorrect**
- Si A : Les chaleurs échangées sont égales, mais pas les capacités thermiques : le métal, de masse moindre, subit une variation de température bien plus grande (76 °C contre 4 °C). Sa capacité thermique massique est environ dix fois plus faible que celle de l'eau.
- Si B : C'est une bonne réponse.
- Si C : Avec l'aluminium ($C_p = 0{,}897$), le métal aurait cédé deux fois plus de chaleur pour la même baisse de température : l'eau se serait réchauffée d'environ 7,7 °C (équilibre vers 27,7 °C) au lieu de 4,0 °C.
- Si D : C'est une bonne réponse.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-capacite-thermique-massique-symbo-eva-302
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-02
statut: validated
---

**Question**
Dans un calorimètre de constante calorimétrique $C_\text{cal} = 60\ \text{J/K}$ contenant 100 g d'eau, une réaction fait monter la température de 5,0 °C. Un élève calcule la chaleur dégagée par la réaction en ne considérant que l'eau, sans tenir compte de $C_\text{cal}$. ($C_p(\ce{H2O}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$.) Quelles évaluations de son calcul sont correctes ?

**Options**
- A. Il surestime la chaleur dégagée, car il oublie que le calorimètre en a absorbé une partie
- B. L'erreur relative, rapportée à la valeur correcte, est de l'ordre de 13 %
- C. Il sous-estime la chaleur dégagée : il trouve environ 2090 J alors que la valeur correcte est environ 2390 J
- D. L'erreur est négligeable, de l'ordre de 1 %

**Réponse correcte** : B, C

**Feedback correct**
Le calorimètre absorbe lui aussi de la chaleur : $Q = (m \cdot C_p + C_\text{cal}) \times \Delta T = (418 + 60) \times 5{,}0 = 2390$ J. En ne comptant que l'eau, l'élève trouve $418 \times 5{,}0 = 2090$ J. L'écart de 300 J représente environ 13 % de 2390 J.

**Feedback incorrect**
- Si A : C'est l'inverse : en oubliant la part de chaleur absorbée par le calorimètre, l'élève trouve une valeur trop faible, pas trop forte.
- Si B : C'est une bonne réponse.
- Si C : C'est une bonne réponse.
- Si D : $C_\text{cal}$ vaut 60 J/K contre 418 J/K pour l'eau : le calorimètre absorbe environ 13 % de la chaleur de la réaction. Ce n'est pas négligeable.

**Référence manuel** : thermochimie-1-bilan-calorimetrique

---
id: q-energie-de-liaison-symbo-ana-003
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
On estime $\Delta_r H^\circ$ de la combustion du méthane, $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(g)}$, à partir des énergies de cohésion : $\ce{CH4}$ 1656 kJ/mol ; $\ce{O2}$ 498 kJ/mol ; $\ce{CO2}$ 1606 kJ/mol ; $\ce{H2O}$ 928 kJ/mol. La valeur expérimentale est de $-802\ \text{kJ/mol}$. Quelles affirmations sont correctes ?

**Options**
- A. $\Delta_r H^\circ = \sum E_\text{cohésion}(\text{réactifs}) - \sum E_\text{cohésion}(\text{produits}) = -810\ \text{kJ/mol}$
- B. L'écart prouve que la valeur expérimentale de $-802\ \text{kJ/mol}$ est erronée
- C. L'écart avec la valeur expérimentale s'explique par le fait que les énergies de liaison utilisées sont des valeurs moyennes, établies sur de nombreuses molécules
- D. Le calcul correct est $\sum E_\text{cohésion}(\text{produits}) - \sum E_\text{cohésion}(\text{réactifs}) = +810\ \text{kJ/mol}$

**Réponse correcte** : A, C

**Feedback correct**
On passe des réactifs aux atomes isolés (énergie à fournir : $1656 + 2 \times 498 = 2652$ kJ), puis on forme les produits (énergie libérée : $1606 + 2 \times 928 = 3462$ kJ). Bilan : $2652 - 3462 = -810$ kJ/mol. Les énergies de liaison tabulées sont des moyennes : le résultat est une estimation, pas une valeur exacte, d'où l'écart d'environ 8 kJ/mol avec la valeur expérimentale.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La valeur expérimentale est mesurée ; c'est l'estimation par les énergies de liaison qui est approchée, parce qu'elle utilise des valeurs moyennes.
- Si C : C'est une bonne réponse.
- Si D : Le signe est inversé : on additionne ce qu'il faut fournir pour casser les réactifs, puis on retranche l'énergie libérée par la formation des produits. Le résultat est négatif : la réaction est exothermique.

**Référence manuel** : thermochimie-1-calcul-energie-liaison

---
id: q-energie-de-liaison-symbo-eva-002
concept: energie-de-liaison
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
On donne les énergies de cohésion de quatre molécules : $\ce{CH4}$ 1656 kJ/mol (5 atomes) ; $\ce{CO2}$ 1606 kJ/mol (3 atomes) ; $\ce{N2}$ 949 kJ/mol (2 atomes) ; $\ce{H2O}$ 928 kJ/mol (3 atomes). Quelles affirmations sont correctes ?

**Options**
- A. Par atome, $\ce{CO2}$ (environ 535 kJ/mol par atome) est plus fortement lié que $\ce{CH4}$ (environ 331 kJ/mol par atome)
- B. $\ce{N2}$ a la plus faible énergie de cohésion des quatre molécules : c'est donc la moins stable
- C. $\ce{CH4}$ est la molécule qui demande le plus d'énergie pour être entièrement dissociée en atomes
- D. $\ce{CH4}$ est aussi celle dont les atomes sont, en moyenne, le plus fortement liés

**Réponse correcte** : A, C

**Feedback correct**
L'énergie de cohésion totale dépend du nombre de liaisons : $\ce{CH4}$ (1656) vient en tête. Rapportée au nombre d'atomes, elle donne : $\ce{CO2}$ environ 535, $\ce{N2}$ environ 475, $\ce{CH4}$ environ 331 et $\ce{H2O}$ environ 309 kJ/mol par atome. Pour comparer la solidité de l'assemblage atome par atome, il faut donc diviser par le nombre d'atomes.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La plus faible énergie de cohésion est celle de $\ce{H2O}$ (928 kJ/mol), pas celle de $\ce{N2}$ (949 kJ/mol). De plus, $\ce{N2}$ est très stable : sa liaison triple est très difficile à rompre.
- Si C : C'est une bonne réponse.
- Si D : Par atome, $\ce{CH4}$ n'arrive qu'en troisième position (environ 331 kJ/mol) : $\ce{CO2}$ et $\ce{N2}$ ont des atomes plus fortement liés.

**Référence manuel** : thermochimie-1-energie-cohesion

---
id: q-enthalpie-de-formation-symbo-ana-301
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
On calcule $\Delta_r H^\circ$ de la synthèse de l'ammoniac, $\ce{N2(g) + 3 H2(g) -> 2 NH3(g)}$, de deux façons. Données : $\Delta_f H^\circ(\ce{NH3,g}) = -46\ \text{kJ/mol}$ ; énergies de liaison : $\ce{N#N}$ 949, $\ce{H-H}$ 436, $\ce{N-H}$ 389 kJ/mol. Quelles affirmations sont correctes ?

**Options**
- A. L'écart de 15 kJ provient surtout de ce que les énergies de liaison sont des valeurs moyennes, alors que les enthalpies de formation sont mesurées pour la substance considérée
- B. Les deux méthodes devraient donner exactement la même valeur : l'écart révèle une erreur de calcul
- C. Par les énergies de liaison, on obtient $-77\ \text{kJ}$ pour la même équation
- D. Par les enthalpies de formation, on obtient $-92\ \text{kJ}$ pour l'équation telle qu'elle est écrite

**Réponse correcte** : A, C, D

**Feedback correct**
Enthalpies de formation : $\Delta_r H^\circ = 2 \times (-46) - 0 - 3 \times 0 = -92$ kJ (les corps simples $\ce{N2}$ et $\ce{H2}$ valent 0 par définition). Énergies de liaison : on rompt $949 + 3 \times 436 = 2257$ kJ et l'on forme $6 \times 389 = 2334$ kJ, soit $2257 - 2334 = -77$ kJ. Les deux résultats diffèrent, car l'énergie de liaison $\ce{N-H}$ est une moyenne établie sur plusieurs molécules.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Il n'y a pas d'erreur : la méthode des énergies de liaison utilise des valeurs moyennes et donne une estimation. Seul le calcul par les enthalpies de formation repose sur des mesures propres à chaque substance.
- Si C : C'est une bonne réponse.
- Si D : C'est une bonne réponse.

**Référence manuel** : thermochimie-1-enthalpie-formation

---
id: q-enthalpie-de-formation-macro-eva-302
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: macro
type: eva
date_validation: 2026-11-02
statut: validated
---

**Question**
Un élève constate que la formation de l'eau à partir de ses éléments ne dégage pas la même énergie selon l'état de l'eau obtenue : $\Delta_f H^\circ(\ce{H2O,l}) = -286\ \text{kJ/mol}$ et $\Delta_f H^\circ(\ce{H2O,g}) = -242\ \text{kJ/mol}$. Il écrit : « Les deux valeurs devraient être identiques, puisque c'est toujours $\ce{H2O}$ ». Quelles évaluations de son raisonnement sont correctes ?

**Options**
- A. $\ce{H2O,g}$ est un corps pur simple : son enthalpie de formation devrait donc être nulle
- B. L'état physique compte : à pression constante, former du liquide libère plus d'énergie que former du gaz, car les interactions entre molécules de liquide libèrent de l'énergie
- C. Les deux valeurs sont identiques ; l'écart provient d'une erreur de mesure
- D. L'écart de 44 kJ/mol correspond à l'énergie à fournir, à 25 °C, pour vaporiser une mole d'eau liquide

**Réponse correcte** : B, D

**Feedback correct**
La formule chimique ne suffit pas : l'état physique fait partie de la définition de la substance. Passer de l'eau liquide à l'eau gazeuse exige $-242 - (-286) = +44$ kJ/mol : c'est l'enthalpie de vaporisation. Le liquide est plus stable car ses molécules interagissent entre elles (ponts hydrogène), ce qui libère de l'énergie lors de sa formation.

**Feedback incorrect**
- Si A : L'eau est un corps composé ($\ce{H}$ et $\ce{O}$). Seuls les corps simples dans leur état de référence (comme $\ce{H2(g)}$, $\ce{O2(g)}$) ont une enthalpie de formation nulle.
- Si B : C'est une bonne réponse.
- Si C : Les deux valeurs sont bien différentes : elles décrivent deux substances d'état physique différent, et leur écart a une signification physique (la vaporisation).
- Si D : C'est une bonne réponse.

**Référence manuel** : thermochimie-1-formation-criteres

---
id: q-enthalpie-macro-eva-301
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: eva
date_validation: 2026-11-02
statut: validated
---

**Question**
La paille de fer exposée à l'humidité rouille en quelques jours. Enflammée, elle brûle en quelques secondes. On suppose que, dans les deux cas, le fer est transformé en le même produit ($\ce{Fe2O3}$), et on néglige l'eau de la rouille. Quelles affirmations sont correctes ?

**Options**
- A. L'énergie totale libérée est la même dans les deux cas ; seule la puissance (énergie par seconde) diffère
- B. La variation d'enthalpie ne dépend que de l'état initial et de l'état final, pas de la durée de la transformation
- C. La combustion rapide dégage davantage d'énergie, car elle est plus intense
- D. Si l'on double la quantité de paille de fer, $\Delta_r H^\circ$ exprimée par mole d'avancement double aussi

**Réponse correcte** : A, B

**Feedback correct**
L'enthalpie est une fonction d'état : $\Delta H$ ne dépend que des états initial et final. La rouille et la combustion transforment le même fer en le même oxyde : l'énergie totale est la même. La combustion paraît plus intense seulement parce que cette énergie est libérée en quelques secondes au lieu de quelques jours, ce qui élève fortement la température.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : L'énergie totale ne dépend pas de la vitesse. La combustion paraît plus intense parce que la même énergie est libérée beaucoup plus vite.
- Si D : $\Delta_r H^\circ$ en kJ/mol est une valeur par mole d'avancement de la réaction écrite : elle ne change pas avec la quantité de matière. C'est la chaleur totale échangée qui double.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-reaction-endothermique-symbo-ana-301
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
On étudie la décomposition de la vapeur d'eau : $\ce{2 H2O(g) -> 2 H2(g) + O2(g)}$. Énergies de liaison : $\ce{O-H}$ 464, $\ce{H-H}$ 436, $\ce{O=O}$ 498 kJ/mol. Quelles affirmations sont correctes ?

**Options**
- A. Pour la réaction $\ce{H2O(g) -> H2(g) + \frac{1}{2} O2(g)}$, $\Delta_r H^\circ$ vaut environ $+243\ \text{kJ}$
- B. La réaction est exothermique, car elle forme trois molécules à partir de deux ; $\Delta_r H^\circ$ vaut environ $-486\ \text{kJ}$
- C. La réaction est endothermique : les liaisons formées libèrent moins d'énergie que les liaisons rompues n'en ont consommé
- D. Pour l'équation telle qu'elle est écrite, $\Delta_r H^\circ$ vaut environ $+486\ \text{kJ}$

**Réponse correcte** : A, C, D

**Feedback correct**
On rompt 4 liaisons $\ce{O-H}$ : $4 \times 464 = 1856$ kJ. On forme 2 liaisons $\ce{H-H}$ et 1 liaison $\ce{O=O}$ : $2 \times 436 + 498 = 1370$ kJ. Bilan : $1856 - 1370 = +486$ kJ pour deux moles d'eau, soit $+243$ kJ par mole d'eau décomposée, valeur très proche de l'inverse de la formation de la vapeur d'eau ($-242$ kJ/mol).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le nombre de molécules ne détermine pas le signe : ce qui compte est le bilan entre l'énergie consommée pour rompre les liaisons (1856 kJ) et celle libérée en en formant (1370 kJ). Ici, la rupture l'emporte.
- Si C : C'est une bonne réponse.
- Si D : C'est une bonne réponse.

**Référence manuel** : thermochimie-1-methode-energie-liaison

---
id: q-reaction-endothermique-macro-eva-302
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: eva
date_validation: 2026-11-02
statut: validated
---

**Question**
On veut fabriquer un sachet réfrigérant instantané : un sel solide qu'on mélange à 100 g d'eau et qui doit la refroidir de 10 °C. Enthalpies de dissolution : $\ce{NH4NO3}$ $+26$ kJ/mol ; $\ce{KBr}$ $+20$ kJ/mol ; $\ce{CaCl2}$ et $\ce{NaOH}$ : dissolutions exothermiques. ($C_p(\ce{H2O}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ ; $M(\ce{NH4NO3}) = 80{,}04$ g/mol ; on néglige les pertes et la capacité thermique du sel.) Quelles évaluations sont correctes ?

**Options**
- A. $\ce{CaCl2}$ convient aussi : sa dissolution implique de grands échanges d'énergie, donc un fort refroidissement
- B. Environ 13 g de $\ce{NH4NO3}$ suffisent pour refroidir les 100 g d'eau de 10 °C
- C. $\ce{KBr}$ ne convient pas, car sa dissolution est endothermique
- D. $\ce{NH4NO3}$ convient : sa dissolution est endothermique, elle prélève de la chaleur à l'eau

**Réponse correcte** : B, D

**Feedback correct**
Pour refroidir, il faut une dissolution endothermique. Chaleur à extraire : $Q = 100 \times 4{,}18 \times 10 = 4180$ J. Avec $\Delta H_\text{diss} = +26\,000$ J/mol, il faut $n = 4180 / 26000 \approx 0{,}16$ mol, soit $0{,}16 \times 80{,}04 \approx 13$ g de $\ce{NH4NO3}$. $\ce{KBr}$ conviendrait aussi (dissolution endothermique) : $n = 4180 / 20000 \approx 0{,}21$ mol, soit environ 25 g ($M = 119{,}0$ g/mol).

**Feedback incorrect**
- Si A : La dissolution de $\ce{CaCl2}$ est exothermique : elle réchaufferait l'eau. Un fort échange d'énergie ne suffit pas : ce qui compte est son signe.
- Si B : C'est une bonne réponse.
- Si C : Au contraire, une dissolution endothermique absorbe de la chaleur : $\ce{KBr}$ refroidit l'eau comme $\ce{NH4NO3}$.
- Si D : C'est une bonne réponse.

**Référence manuel** : thermochimie-1-enthalpie-dissolution

<!-- LOT QUESTIONS DIFFICILES (lot-thermo.tmp.md, 02.11.2026) — statut to_fix -->

---
id: q-enthalpie-de-formation-symbo-ana-401
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-02
statut: validated
---

**Question**
Les enthalpies standard de combustion du carbone en $\ce{CO2(g)}$ valent $-394$ kJ/mol pour le graphite et $-396$ kJ/mol pour le diamant. Quelles affirmations sont correctes ?

**Options**
- A. $\Delta_f H^\circ(\ce{C, diamant})$ vaut environ $-2$ kJ/mol, car la combustion du diamant dégage 2 kJ de plus
- B. $\Delta_f H^\circ(\ce{C, diamant})$ vaut environ $+2$ kJ/mol
- C. $\Delta_f H^\circ(\ce{C, diamant})$ vaut 0 par convention, comme celle de tout corps simple
- D. La combustion du diamant dégage un peu plus de chaleur que celle du graphite, car le diamant est légèrement moins stable

**Réponse correcte** : B, D

**Feedback correct**
La convention $\Delta_f H^\circ = 0$ s'applique à la forme la plus stable du corps simple, ici le graphite. Par la loi de Hess, $\ce{C(diamant) -> C(graphite)}$ vaut $-396 - (-394) = -2$ kJ/mol, donc $\Delta_f H^\circ(\ce{C, diamant}) = +2$ kJ/mol : le diamant est un peu moins stable, et sa combustion libère un peu plus d'énergie.

**Feedback incorrect**
- Si A : Le signe est inversé : la formation du diamant à partir du graphite demande de l'énergie ($\ce{C(graphite) -> C(diamant)}$ vaut $+2$ kJ/mol), donc $\Delta_f H^\circ(\ce{C, diamant}) = +2$ kJ/mol. La chaleur supplémentaire dégagée à la combustion est cette énergie stockée dans le diamant.
- Si B : Cette option est correcte parce que $\Delta_f H^\circ(\ce{C, diamant}) = -394 - (-396) = +2$ kJ/mol, le graphite étant la référence à 0.
- Si C : La convention ne vaut que pour la forme la plus stable du corps simple dans les conditions standards (ici le graphite). Pour le diamant, un peu moins stable, $\Delta_f H^\circ$ n'est pas nulle.
- Si D : Cette option est correcte parce que le diamant, un peu moins stable ($+2$ kJ/mol), libère $2$ kJ de plus à la combustion ($-396$ contre $-394$ kJ/mol).

**Référence manuel** : thermochimie-1-formation-definition
<!-- LOT PILOTE (génération par script, 04.11.2026) — loi-de-hess-generalisee — statut to_fix -->
<!-- Valeurs calculées par generateur-variantes/hess_generalisee.py depuis donnees_crm.py ; bilan d'espèces vérifié -->

---
id: q-loi-de-hess-generalisee-symbo-app-003
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
On dispose des enthalpies de combustion suivantes : (1) $\ce{C2H2(g) + \frac{5}{2} O2(g) -> 2 CO2(g) + H2O(l)}$, $\Delta_r H^\circ_{(1)} = -1301\ \text{kJ/mol}$ ; (2) $\ce{H2(g) + \frac{1}{2} O2(g) -> H2O(l)}$, $\Delta_r H^\circ_{(2)} = -286\ \text{kJ/mol}$ ; (3) $\ce{C2H6(g) + \frac{7}{2} O2(g) -> 2 CO2(g) + 3 H2O(l)}$, $\Delta_r H^\circ_{(3)} = -1561\ \text{kJ/mol}$. Cette réaction est l'hydrogénation de l'éthyne en éthane. Calculez $\Delta_r H^\circ$ de la réaction cible $\ce{C2H2(g) + 2 H2(g) -> C2H6(g)}$.

**Options**
- A. $-312\ \text{kJ/mol}$
- B. $+312\ \text{kJ/mol}$
- C. $-26\ \text{kJ/mol}$
- D. $+260\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
L'éthyne et le dihydrogène sont réactifs de la cible : on garde leur équation de combustion (multipliée par le coefficient de la cible) ; l'éthane est produit de la cible : on inverse son équation. Soit $\Delta_r H^\circ = (-1301) + 2\times(-286) - (-1561) = -312\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+312\ \text{kJ/mol}$ combine toutes les équations à l'envers (équations des réactifs inversées, équations des produits conservées) : le résultat obtenu est exactement l'opposé du bon.
- Si C : $-26\ \text{kJ/mol}$ oublie le coefficient 2 du dihydrogène dans la cible : son équation de combustion doit être multipliée par 2.
- Si D : $+260\ \text{kJ/mol}$ oublie l'équation de combustion du dihydrogène, pourtant indispensable : elle intervient dans la cible avec un coefficient 2.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-generalisee-symbo-app-004
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
On dispose des enthalpies de combustion suivantes : (1) $\ce{C2H5OH(l) + 3 O2(g) -> 2 CO2(g) + 3 H2O(l)}$, $\Delta_r H^\circ_{(1)} = -1367\ \text{kJ/mol}$ ; (2) $\ce{CH3CHO(g) + \frac{5}{2} O2(g) -> 2 CO2(g) + 2 H2O(l)}$, $\Delta_r H^\circ_{(2)} = -1167\ \text{kJ/mol}$ ; (3) $\ce{H2(g) + \frac{1}{2} O2(g) -> H2O(l)}$, $\Delta_r H^\circ_{(3)} = -286\ \text{kJ/mol}$. Cette réaction est la déshydrogénation de l'éthanol en éthanal. Calculez $\Delta_r H^\circ$ de la réaction cible $\ce{C2H5OH(l) -> CH3CHO(g) + H2(g)}$.

**Options**
- A. $+86\ \text{kJ/mol}$
- B. $-86\ \text{kJ/mol}$
- C. $-200\ \text{kJ/mol}$
- D. $-2820\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
L'éthanol est réactif de la cible : on garde son équation de combustion (multipliée par le coefficient de la cible) ; l'éthanal et le dihydrogène sont produits de la cible : on inverse leur équation. Soit $\Delta_r H^\circ = (-1367) - (-1167) - (-286) = +86\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-86\ \text{kJ/mol}$ combine toutes les équations à l'envers (équations des réactifs inversées, équations des produits conservées) : le résultat obtenu est exactement l'opposé du bon.
- Si C : $-200\ \text{kJ/mol}$ oublie l'équation de combustion du dihydrogène, pourtant indispensable : elle intervient dans la cible avec un coefficient 1.
- Si D : $-2820\ \text{kJ/mol}$ additionne toutes les équations de combustion sans en inverser aucune : or l'éthanal et le dihydrogène sont produits de la cible, alors que leur combustion les consomme — leurs équations doivent être inversées.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-generalisee-symbo-ana-002
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
On dispose des enthalpies de combustion suivantes : (1) $\ce{C2H2(g) + \frac{5}{2} O2(g) -> 2 CO2(g) + H2O(l)}$, $\Delta_r H^\circ_{(1)} = -1301\ \text{kJ/mol}$ ; (2) $\ce{H2(g) + \frac{1}{2} O2(g) -> H2O(l)}$, $\Delta_r H^\circ_{(2)} = -286\ \text{kJ/mol}$ ; (3) $\ce{C2H4(g) + 3 O2(g) -> 2 CO2(g) + 2 H2O(l)}$, $\Delta_r H^\circ_{(3)} = -1411\ \text{kJ/mol}$. Cette réaction est l'hydrogénation partielle de l'éthyne en éthène. Quelle combinaison de ces équations conduit à la réaction cible $\ce{C2H2(g) + H2(g) -> C2H4(g)}$ ?

**Options**
- A. $(1) + (2) - (3)$
- B. $-(1) - (2) + (3)$
- C. $(1) + (2) + (3)$
- D. $(1) - (3)$

**Réponse correcte** : A

**Feedback correct**
L'éthyne et le dihydrogène sont réactifs de la cible : on garde leur équation de combustion (multipliée par le coefficient de la cible) ; l'éthène est produit de la cible : on inverse son équation. La combinaison est donc $(1) + (2) - (3)$, soit $\Delta_r H^\circ = (-1301) + (-286) - (-1411) = -176\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-(1) - (2) + (3)$ combine toutes les équations à l'envers (équations des réactifs inversées, équations des produits conservées) : le résultat obtenu est exactement l'opposé du bon.
- Si C : $(1) + (2) + (3)$ additionne toutes les équations de combustion sans en inverser aucune : or l'éthène est produit de la cible, alors que sa combustion le consomme — son équation doit être inversée.
- Si D : $(1) - (3)$ oublie l'équation de combustion du dihydrogène, pourtant indispensable : elle intervient dans la cible avec un coefficient 1.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-generalisee-symbo-ana-003
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
On dispose des enthalpies de combustion suivantes : (1) $\ce{C(graphite) + O2(g) -> CO2(g)}$, $\Delta_r H^\circ_{(1)} = -394\ \text{kJ/mol}$ ; (2) $\ce{H2(g) + \frac{1}{2} O2(g) -> H2O(l)}$, $\Delta_r H^\circ_{(2)} = -286\ \text{kJ/mol}$ ; (3) $\ce{C2H5OH(l) + 3 O2(g) -> 2 CO2(g) + 3 H2O(l)}$, $\Delta_r H^\circ_{(3)} = -1367\ \text{kJ/mol}$. Cette réaction est la formation de l'éthanol à partir de ses éléments ; le dioxygène est un corps pur simple, il n'a pas d'équation de combustion. Quelle combinaison de ces équations conduit à la réaction cible $\ce{2 C(graphite) + 3 H2(g) + \frac{1}{2} O2(g) -> C2H5OH(l)}$ ?

**Options**
- A. $2\times(1) + 3\times(2) - (3)$
- B. $-2\times(1) - 3\times(2) + (3)$
- C. $(1) + 3\times(2) - (3)$
- D. $2\times(1) - (3)$

**Réponse correcte** : A

**Feedback correct**
Le carbone graphite et le dihydrogène sont réactifs de la cible : on garde leur équation de combustion (multipliée par le coefficient de la cible) ; l'éthanol est produit de la cible : on inverse son équation. La combinaison est donc $2\times(1) + 3\times(2) - (3)$, soit $\Delta_r H^\circ = 2\times(-394) + 3\times(-286) - (-1367) = -279\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-2\times(1) - 3\times(2) + (3)$ combine toutes les équations à l'envers (équations des réactifs inversées, équations des produits conservées) : le résultat obtenu est exactement l'opposé du bon.
- Si C : $(1) + 3\times(2) - (3)$ oublie le coefficient 2 du carbone graphite dans la cible : son équation de combustion doit être multipliée par 2.
- Si D : $2\times(1) - (3)$ oublie l'équation de combustion du dihydrogène, pourtant indispensable : elle intervient dans la cible avec un coefficient 3.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-generalisee-symbo-eva-001
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
On dispose des enthalpies de combustion suivantes : (1) $\ce{C(graphite) + O2(g) -> CO2(g)}$, $\Delta_r H^\circ_{(1)} = -394\ \text{kJ/mol}$ ; (2) $\ce{H2(g) + \frac{1}{2} O2(g) -> H2O(l)}$, $\Delta_r H^\circ_{(2)} = -286\ \text{kJ/mol}$ ; (3) $\ce{C2H4(g) + 3 O2(g) -> 2 CO2(g) + 2 H2O(l)}$, $\Delta_r H^\circ_{(3)} = -1411\ \text{kJ/mol}$. Une élève veut calculer $\Delta_r H^\circ$ de la réaction de formation de l'éthène $\ce{2 C(graphite) + 2 H2(g) -> C2H4(g)}$ et écrit : $\Delta_r H^\circ = 2\times(-394) + 2\times(-286) + (-1411) = -2771\ \text{kJ/mol}$. Que pensez-vous de son calcul ?

**Options**
- A. Il est faux : l'éthène est un produit de la cible, donc son équation de combustion doit être inversée ; on obtient $\Delta_r H^\circ = +51\ \text{kJ/mol}$.
- B. Il est correct : les trois données étant des enthalpies de combustion, on les additionne toutes avec les coefficients de la cible ; on obtient bien $\Delta_r H^\circ = -2771\ \text{kJ/mol}$.
- C. Il est faux : ce sont les équations des réactifs (carbone et dihydrogène) qu'il faut inverser, pas celle du produit ; on obtient $\Delta_r H^\circ = -51\ \text{kJ/mol}$.
- D. Il est faux : il manque seulement le facteur $2$ sur la combustion de l'éthène, sans rien inverser ; on obtient $\Delta_r H^\circ = -4182\ \text{kJ/mol}$.

**Réponse correcte** : A

**Feedback correct**
Dans la cible, l'éthène est produit : l'équation de combustion qui le consomme doit être inversée, donc son $\Delta_r H^\circ$ change de signe. Soit $\Delta_r H^\circ = 2\times(-394) + 2\times(-286) - (-1411) = +51\ \text{kJ/mol}$ : la formation de l'éthène est endothermique, ce que le résultat de l'élève ($-2771\ \text{kJ/mol}$, très exothermique) ne pouvait pas refléter.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Additionner les trois enthalpies sans inverser celle de l'éthène revient à traiter l'éthène comme un réactif de la cible : le résultat ($-2771\ \text{kJ/mol}$) est faux d'un ordre de grandeur.
- Si C : Inverser les équations des réactifs et conserver celle du produit combine tout à l'envers : le résultat ($-51\ \text{kJ/mol}$) est l'opposé du bon.
- Si D : La cible ne forme qu'une mole d'éthène : l'équation de combustion de l'éthène est prise avec le coefficient $1$, pas $2$ ; le vrai défaut est son signe (équation non inversée), pas son coefficient.

**Référence manuel** : thermochimie-1-hess-combinaison

<!-- LOT PILOTE (génération par script, 04.11.2026) — capacite-thermique-massique — statut to_fix -->

---
id: q-capacite-thermique-massique-symbo-app-004
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Un bloc de $200\ \text{g}$ d'un métal inconnu reçoit une chaleur de $5{,}39\ \text{kJ}$ : sa température passe de $20\ ^\circ\text{C}$ à $80\ ^\circ\text{C}$. Quelle est sa capacité thermique massique ?

**Options**
- A. $0{,}449\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$
- B. $1{,}35\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$
- C. $0{,}337\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$
- D. $2{,}23\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$C_p = \dfrac{Q}{m\,\Delta T} = \dfrac{5390}{200\times60} = 0{,}449\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$, valeur proche de celle du fer. Attention : la chaleur est donnée en kJ, il faut la convertir en J ($5{,}39\ \text{kJ} = 5390\ \text{J}$) pour obtenir des $\text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $1{,}35\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ divise par la température initiale ($20\ ^\circ\text{C}$) au lieu de la variation $\Delta T = \theta_f - \theta_i = 60\ \text{K}$.
- Si C : $0{,}337\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ divise par la température finale ($80\ ^\circ\text{C}$) au lieu de la variation $\Delta T = 60\ \text{K}$.
- Si D : $2{,}23\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ inverse la relation : $C_p = Q/(m\,\Delta T)$, pas $m\,\Delta T/Q$ (on le voit à l'unité : des joules au numérateur).

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-capacite-thermique-massique-symbo-app-005
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
On chauffe $2{,}5\ \text{kg}$ d'eau de $15\ ^\circ\text{C}$ à $35\ ^\circ\text{C}$. Quelle quantité de chaleur l'eau absorbe-t-elle ? ($C_p(\ce{H2O,l}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$)

**Options**
- A. $209\ \text{kJ}$
- B. $0{,}209\ \text{kJ}$
- C. $366\ \text{kJ}$
- D. $157\ \text{kJ}$

**Réponse correcte** : A

**Feedback correct**
La capacité thermique est en $\text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ : la masse doit être en grammes ($2500\ \text{g}$). $Q = m\,C_p\,\Delta T = 2500\times4{,}18\times20 = 209000\ \text{J} = 209\ \text{kJ}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $0{,}209\ kJ$ utilise la masse en kg directement avec un $C_p$ en $\text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ (résultat $209\ \text{J}$, soit $0{,}209\ \text{kJ}$) : il faut convertir $2{,}5\ \text{kg}$ en $2500\ \text{g}$.
- Si C : $366\ kJ$ prend la température finale ($35\ ^\circ\text{C}$) à la place de la variation $\Delta T = 20\ \text{K}$.
- Si D : $157\ kJ$ prend la température initiale ($15\ ^\circ\text{C}$) à la place de la variation $\Delta T = 20\ \text{K}$.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-capacite-thermique-massique-symbo-ana-002
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
Un récipient contient $200\ \text{g}$ d'eau et un autre $50\ \text{g}$ de cuivre, tous deux à la même température initiale. Chacun reçoit exactement la même chaleur $Q$. ($C_p(\ce{H2O}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ ; $C_p(\ce{Cu}) = 0{,}385\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$.) Quel est le rapport $\Delta T_\text{Cu} / \Delta T_\text{eau}$ ?

**Options**
- A. environ $43{,}4$
- B. environ $10{,}9$
- C. $4$
- D. environ $0{,}023$

**Réponse correcte** : A

**Feedback correct**
Pour une même chaleur, $Q = m\,C_p\,\Delta T$ est identique : $\Delta T = Q/(m\,C_p)$. Le rapport vaut $\dfrac{m_\text{eau}\,C_{p,\text{eau}}}{m_\text{Cu}\,C_{p,\text{Cu}}} = \dfrac{200\times4{,}18}{50\times0{,}385} \approx 43{,}4$ : le cuivre s'échauffe plus de quarante fois plus que l'eau.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Environ $10{,}9$ ne compare que les capacités thermiques massiques ($4{,}18/0{,}385$) et oublie que les masses diffèrent (200 g contre 50 g).
- Si C : $4$ ne compare que les masses ($200/50$) et oublie que le cuivre a une capacité thermique massique bien plus faible que l'eau.
- Si D : Environ $0{,}023$ est l'inverse du bon rapport : c'est le matériau à plus faible $m\,C_p$ (le cuivre) qui s'échauffe le plus, donc $\Delta T_\text{Cu}$ est au numérateur et plus grand.

**Référence manuel** : thermochimie-1-capacite-thermique

---
id: q-capacite-thermique-massique-symbo-eva-001
concept: capacite-thermique-massique
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
misconception: capacite-thermique-massique--chaleur-dependrait-seulement-temperature
date_validation: 2026-11-04
statut: validated
---

**Question**
Une élève chauffe de $20\ \text{K}$ $100\ \text{g}$ d'eau d'une part, $100\ \text{g}$ de cuivre d'autre part. Elle affirme : « La chaleur absorbée ne dépend que de la variation de température : les deux échantillons ont absorbé la même chaleur, $Q = m\,\Delta T$ à une constante près. » ($C_p(\ce{H2O}) = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$ ; $C_p(\ce{Cu}) = 0{,}385\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$.) Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est fausse : $Q = m\,C_p\,\Delta T$ dépend aussi de la substance par son $C_p$ ; l'eau absorbe $8{,}36\ \text{kJ}$ et le cuivre seulement $0{,}77\ \text{kJ}$.
- B. Elle est juste : à masse et variation de température égales, la chaleur absorbée est la même quelle que soit la substance.
- C. Elle est fausse : c'est le cuivre qui absorbe le plus de chaleur, car son faible $C_p$ le rend plus sensible à la chaleur reçue.
- D. Elle est fausse : les deux échantillons absorbent des chaleurs différentes, mais seulement à cause de leurs masses volumiques différentes, pas de leur $C_p$.

**Réponse correcte** : A

**Feedback correct**
$Q = m\,C_p\,\Delta T$ : à $m$ et $\Delta T$ égaux, $Q$ est proportionnel à $C_p$. Eau : $100\times4{,}18\times20 = 8360\ \text{J}$ ; cuivre : $100\times0{,}385\times20 = 770\ \text{J}$, soit environ onze fois moins. La chaleur dépend de la variation de température, de la masse et de la substance.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La chaleur dépend de la substance par son $C_p$ : à masse et $\Delta T$ égaux, deux substances n'absorbent pas la même chaleur.
- Si C : C'est l'inverse : un $C_p$ faible signifie qu'il faut peu de chaleur pour élever la température d'un gramme de 1 K ; à $\Delta T$ égal, le cuivre absorbe donc moins de chaleur que l'eau.
- Si D : Les masses sont égales : la masse volumique n'intervient pas dans $Q = m\,C_p\,\Delta T$ ; ce qui diffère entre les deux substances est leur $C_p$.

**Référence manuel** : thermochimie-1-capacite-thermique

<!-- LOT PILOTE (génération par script, 04.11.2026) — reaction-exothermique (défis) — statut to_fix -->

---
id: q-reaction-exothermique-symbo-ana-002
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
La synthèse de l'ammoniac s'écrit $\ce{N2(g) + 3 H2(g) -> 2 NH3(g)}$, avec $\Delta_r H^\circ = -92\ \text{kJ/mol}$ (par mole de réaction telle qu'écrite). Quelle chaleur est dégagée lorsque $0{,}50\ \text{mol}$ de dihydrogène réagit ?

**Options**
- A. environ $15{,}3\ \text{kJ}$
- B. $46\ \text{kJ}$
- C. $92\ \text{kJ}$
- D. $23\ \text{kJ}$

**Réponse correcte** : A

**Feedback correct**
La réaction telle qu'écrite consomme $3\ \text{mol}$ de $\ce{H2}$ pour dégager $92\ \text{kJ}$ (réaction exothermique, $\Delta_r H^\circ < 0$). Pour $0{,}50\ \text{mol}$ de $\ce{H2}$ : $\dfrac{0{,}50}{3}\times 92 = 15{,}3\ \text{kJ}$ dégagés.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $46\ \text{kJ}$ prend $0{,}50\times92$ : c'est oublier que $92\ \text{kJ}$ correspondent à $3\ \text{mol}$ de $\ce{H2}$ et non à $1\ \text{mol}$.
- Si C : $92\ \text{kJ}$ est la chaleur dégagée pour la réaction complète telle qu'écrite ($3\ \text{mol}$ de $\ce{H2}$), pas pour $0{,}50\ \text{mol}$.
- Si D : $23\ \text{kJ}$ divise par $2$, le coefficient de $\ce{NH3}$, alors que la quantité donnée est celle de $\ce{H2}$ (coefficient $3$).

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-symbo-ana-003
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
La combustion de l'éthanol liquide a pour enthalpie $\Delta_r H^\circ = -1367\ \text{kJ/mol}$ ; sa masse molaire vaut $M = 46{,}0\ \text{g/mol}$. Quelle masse d'éthanol faut-il brûler pour dégager $500\ \text{kJ}$ de chaleur ?

**Options**
- A. environ $16{,}8\ \text{g}$
- B. environ $126\ \text{g}$
- C. environ $0{,}366\ \text{g}$
- D. $46{,}0\ \text{g}$

**Réponse correcte** : A

**Feedback correct**
Chaque mole d'éthanol brûlée dégage $1367\ \text{kJ}$ ($\Delta_r H^\circ < 0$ : réaction exothermique). Pour $500\ \text{kJ}$ : $n = \dfrac{500}{1367} = 0{,}366\ \text{mol}$, soit $m = n\,M = 0{,}366\times46{,}0 = 16{,}8\ \text{g}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Environ $126\ \text{g}$ inverse le rapport ($\frac{1367}{500}\times46{,}0$) : la chaleur dégagée est proportionnelle à la masse brûlée, donc plus de chaleur voulue exige plus d'éthanol, pas moins.
- Si C : Environ $0{,}366\ \text{g}$ est la quantité de matière en mol ($0{,}366\ \text{mol}$) prise pour une masse : il manque la multiplication par $M$.
- Si D : $46{,}0\ \text{g}$ est la masse d'une mole d'éthanol : une mole dégagerait $1367\ \text{kJ}$, bien plus que les $500\ \text{kJ}$ voulus.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-macro-eva-003
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Une bouillotte chimique contient une solution sursaturée d'acétate de sodium. Quand on déclenche la cristallisation, le sachet devient chaud dans la main. Un élève affirme : « Le sachet gagne de la chaleur, donc la cristallisation est endothermique et $\Delta H > 0$. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est fausse : le sachet et la main sont l'environnement, qui reçoit de la chaleur ; c'est le système chimique qui en cède, donc $\Delta H < 0$ et la cristallisation est exothermique.
- B. Elle est juste : si de la chaleur apparaît dans le sachet, l'enthalpie du système augmente, donc $\Delta H > 0$.
- C. Elle est juste : la cristallisation forme des liaisons entre les ions, et la formation de liaisons absorbe de l'énergie, donc $\Delta H > 0$.
- D. Elle est fausse, mais on ne peut pas dire si la cristallisation est exothermique ou endothermique : la température du sachet ne renseigne pas sur le signe de $\Delta H$.

**Réponse correcte** : A

**Feedback correct**
Le signe de $\Delta H$ se lit du point de vue du système chimique : si l'environnement (le sachet, la main) s'échauffe, c'est que le système lui cède de la chaleur, donc $\Delta H < 0$ — réaction exothermique. Ce que l'on ressent est la chaleur reçue par l'environnement, de signe opposé à la variation d'enthalpie du système.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La chaleur gagnée par le sachet est de la chaleur perdue par le système chimique : l'enthalpie du système diminue, $\Delta H < 0$.
- Si C : C'est la rupture de liaisons qui absorbe de l'énergie ; la formation de liaisons en libère. Ici, la cristallisation libère de l'énergie, ce que confirme l'échauffement.
- Si D : Un environnement qui s'échauffe renseigne bien sur le signe : il reçoit de la chaleur du système, donc $\Delta H < 0$ (seules les réactions athermiques ou trop faibles pour être perçues échappent à cette lecture).

**Référence manuel** : thermochimie-1-exo-endo

<!-- LOT PILOTE (génération par script, 04.11.2026) — loi-de-hess (formule et fonction d'état) — statut to_fix -->

---
id: q-loi-de-hess-symbo-app-001
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La fermentation alcoolique du glucose s'écrit $\ce{C6H12O6(s) -> 2 C2H5OH(l) + 2 CO2(g)}$. On donne : $\Delta_f H^\circ(\ce{C6H12O6(s)}) = -1273\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{C2H5OH(l)}) = -278\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{CO2(g)}) = -394\ \text{kJ/mol}$. Calculez $\Delta_r H^\circ$ de cette réaction.

**Options**
- A. $-71\ \text{kJ/mol}$
- B. $+71\ \text{kJ/mol}$
- C. $+601\ \text{kJ/mol}$
- D. $-1344\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ = \sum\nu\,\Delta_f H^\circ(\text{produits}) - \sum\nu\,\Delta_f H^\circ(\text{réactifs}) = [2\times(-278) + 2\times(-394)] - [(-1273)] = -71\ \text{kJ/mol}$ : la fermentation est légèrement exothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+71\ \text{kJ/mol}$ calcule réactifs moins produits : la formule est produits moins réactifs, le résultat obtenu est l'opposé du bon.
- Si C : $+601\ \text{kJ/mol}$ oublie les coefficients $2$ de l'éthanol et du dioxyde de carbone : chaque $\Delta_f H^\circ$ est pondéré par son coefficient stœchiométrique.
- Si D : $-1344\ \text{kJ/mol}$ ne retient que les produits : il faut soustraire la somme des enthalpies de formation des réactifs (ici le glucose).

**Référence manuel** : thermochimie-1-hess-fonction-etat

---
id: q-loi-de-hess-symbo-app-002
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
L'hydratation de l'éthène s'écrit $\ce{C2H4(g) + H2O(l) -> C2H5OH(l)}$. On donne : $\Delta_f H^\circ(\ce{C2H4(g)}) = +52\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{H2O(l)}) = -286\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{C2H5OH(l)}) = -278\ \text{kJ/mol}$. Calculez $\Delta_r H^\circ$ de cette réaction.

**Options**
- A. $-44\ \text{kJ/mol}$
- B. $+44\ \text{kJ/mol}$
- C. $-330\ \text{kJ/mol}$
- D. $-616\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ = (-278) - [(52) + (-286)] = -44\ \text{kJ/mol}$ : l'éthène, de $\Delta_f H^\circ$ positive, est un réactif ; l'eau liquide doit figurer parmi les réactifs.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+44\ \text{kJ/mol}$ calcule réactifs moins produits : le signe obtenu est l'opposé du bon.
- Si C : $-330\ \text{kJ/mol}$ oublie l'eau parmi les réactifs : $\ce{H2O(l)}$ réagit et son $\Delta_f H^\circ$ ($-286\ \text{kJ/mol}$) doit être soustrait avec ceux des réactifs.
- Si D : $-616\ \text{kJ/mol}$ compte l'eau avec le mauvais signe : la somme des réactifs s'additionne, $\Delta_f H^\circ(\ce{C2H4}) + \Delta_f H^\circ(\ce{H2O}) = -234\ \text{kJ/mol}$, puis elle est soustraite.

**Référence manuel** : thermochimie-1-hess-fonction-etat

---
id: q-loi-de-hess-symbo-com-002
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
Le glucose peut être oxydé en $\ce{CO2(g)}$ et $\ce{H2O(l)}$ de deux façons : (1) par combustion directe, $\Delta_r H^\circ = -2803\ \text{kJ/mol}$ ; (2) par fermentation en éthanol ($\Delta_r H^\circ = -71\ \text{kJ/mol}$), suivie de la combustion des $2\ \text{mol}$ d'éthanol formées ($\Delta_r H^\circ = -1367\ \text{kJ/mol}$ d'éthanol). La voie (2) donne $-71 + 2\times(-1367) = -2805\ \text{kJ}$. Que peut-on conclure de la comparaison des deux voies ?

**Options**
- A. Les deux voies relient les mêmes états initial et final : la loi de Hess impose le même $\Delta H$ ; le petit écart vient des arrondis des valeurs tabulées.
- B. La voie (2) dégage un peu moins de chaleur car elle passe par un intermédiaire (l'éthanol) qui « retient » de l'énergie.
- C. La voie (1) est la seule à être exothermique ; la voie (2) ne l'est que si l'on tient compte de la combustion de l'éthanol.
- D. Les deux voies ne peuvent pas être comparées, car elles n'ont pas les mêmes étapes intermédiaires.

**Réponse correcte** : A

**Feedback correct**
L'enthalpie est une fonction d'état : seul compte le bilan entre l'état initial (glucose et dioxygène) et l'état final ($\ce{CO2}$ et $\ce{H2O}$), pas le chemin. L'écart de $2\ \text{kJ}$ sur $2803\ \text{kJ}$ n'est dû qu'aux arrondis des tables.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Un intermédiaire ne « retient » pas d'énergie : l'éthanol formé à l'étape 1 est entièrement consommé à l'étape 2, et son $\Delta_f H^\circ$ disparaît du bilan global.
- Si C : Les deux voies sont exothermiques au total ; ce qui compte est le bilan entre état initial et état final.
- Si D : C'est justement l'intérêt de la loi de Hess : deux chemins reliant les mêmes états initial et final se comparent directement, quelles que soient leurs étapes.

**Référence manuel** : thermochimie-1-hess-fonction-etat

---
id: q-loi-de-hess-symbo-eva-002
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
L'oxydation du méthanol s'écrit $\ce{CH3OH(l) + \frac{1}{2} O2(g) -> HCHO(g) + H2O(l)}$. On donne : $\Delta_f H^\circ(\ce{CH3OH(l)}) = -239\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{HCHO(g)}) = -109\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{H2O(l)}) = -286\ \text{kJ/mol}$. Une élève calcule $\Delta_r H^\circ = [(-239) + 0] - [(-109) + (-286)] = +156\ \text{kJ/mol}$ et conclut que la réaction est endothermique. Que pensez-vous de son calcul ?

**Options**
- A. Il est faux : elle a calculé réactifs moins produits ; avec produits moins réactifs, $\Delta_r H^\circ = -156\ \text{kJ/mol}$ et la réaction est exothermique.
- B. Il est juste : le dioxygène étant un réactif, son $\Delta_f H^\circ$ doit être compté et rend la réaction endothermique.
- C. Il est faux : le terme du dioxygène manque, car son $\Delta_f H^\circ$ n'est pas nul ; avec ce terme, la réaction reste endothermique.
- D. Il est juste : une oxydation consomme du dioxygène et absorbe donc de la chaleur.

**Réponse correcte** : A

**Feedback correct**
La formule est $\Delta_r H^\circ = \sum\nu\,\Delta_f H^\circ(\text{produits}) - \sum\nu\,\Delta_f H^\circ(\text{réactifs})$ : l'élève a inversé les deux sommes et obtient le signe opposé. Correct : $[(-109) + (-286)] - [(-239) + 0] = -156\ \text{kJ/mol}$ ; réaction exothermique. Le dioxygène, corps pur simple, a un $\Delta_f H^\circ$ nul.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le dioxygène est un corps pur simple dans son état le plus stable : son $\Delta_f H^\circ$ est nul, il ne change donc pas le résultat ; le vrai défaut est l'inversion des deux sommes.
- Si C : Le terme du dioxygène est bien présent dans le calcul (il vaut $0$) ; $\Delta_f H^\circ(\ce{O2,g}) = 0$ car c'est un corps pur simple stable.
- Si D : Consommer du dioxygène n'impose pas le signe de $\Delta_r H^\circ$ : c'est le bilan des enthalpies de formation qui le détermine (ici, exothermique).

**Référence manuel** : thermochimie-1-hess-fonction-etat

<!-- LOT PILOTE (génération par script, 04.11.2026) — enthalpie-de-formation — statut to_fix -->

---
id: q-enthalpie-de-formation-symbo-com-002
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
Laquelle de ces équations correspond à l'enthalpie standard de formation de l'éthanol liquide, $\Delta_f H^\circ(\ce{C2H5OH,l})$ ?

**Options**
- A. $\ce{2 C(graphite) + 3 H2(g) + \frac{1}{2} O2(g) -> C2H5OH(l)}$
- B. $\ce{2 C(g) + 6 H(g) + O(g) -> C2H5OH(l)}$
- C. $\ce{C2H4(g) + H2O(l) -> C2H5OH(l)}$
- D. $\ce{2 CO2(g) + 3 H2O(l) -> C2H5OH(l) + 3 O2(g)}$

**Réponse correcte** : A

**Feedback correct**
Une réaction de formation part des **corps purs simples** dans leur état standard le plus stable (carbone graphite, dihydrogène, dioxygène) et forme **une seule mole** du composé : c'est le cas de la première équation.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Cette équation part d'atomes isolés en phase gazeuse : elle correspond à l'énergie de cohésion (au signe près), pas à la formation à partir des corps purs simples.
- Si C : Cette équation part de composés ($\ce{C2H4}$, $\ce{H2O}$), pas de corps purs simples : c'est l'hydratation de l'éthène, dont $\Delta_r H^\circ$ n'est pas $\Delta_f H^\circ$.
- Si D : Cette équation est l'inverse de la combustion de l'éthanol : elle part de $\ce{CO2}$ et $\ce{H2O}$ et non des corps purs simples.

**Référence manuel** : thermochimie-1-formation-criteres

---
id: q-enthalpie-de-formation-symbo-app-003
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La combustion de l'éthyne s'écrit $\ce{C2H2(g) + \frac{5}{2} O2(g) -> 2 CO2(g) + H2O(l)}$ et dégage $1301\ \text{kJ}$ par mole d'éthyne ($\Delta_r H^\circ = -1301\ \text{kJ/mol}$). On donne $\Delta_f H^\circ(\ce{CO2,g}) = -394\ \text{kJ/mol}$ et $\Delta_f H^\circ(\ce{H2O,l}) = -286\ \text{kJ/mol}$. Quelle est $\Delta_f H^\circ(\ce{C2H2,g})$ ?

**Options**
- A. $+227\ \text{kJ/mol}$
- B. $-227\ \text{kJ/mol}$
- C. $+621\ \text{kJ/mol}$
- D. $-1074\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ = 2\,\Delta_f H^\circ(\ce{CO2}) + \Delta_f H^\circ(\ce{H2O}) - \Delta_f H^\circ(\ce{C2H2})$ (le dioxygène, corps pur simple, vaut $0$), d'où $\Delta_f H^\circ(\ce{C2H2}) = 2\times(-394) + (-286) - (-1301) = +227\ \text{kJ/mol}$ : la formation de l'éthyne est endothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-227\ \text{kJ/mol}$ résulte d'une erreur de signe sur l'isolement de $\Delta_f H^\circ(\ce{C2H2})$ : il faut soustraire $\Delta_r H^\circ$ à la somme des produits, pas l'ajouter.
- Si C : $+621\ \text{kJ/mol}$ oublie le coefficient $2$ devant $\ce{CO2}$ : deux moles de $\ce{CO2}$ se forment par mole d'éthyne.
- Si D : $-1074\ \text{kJ/mol}$ oublie le terme $-\Delta_r H^\circ$ : il faut en tenir compte pour remonter à $\Delta_f H^\circ(\ce{C2H2})$.

**Référence manuel** : thermochimie-1-formation-criteres

---
id: q-enthalpie-de-formation-symbo-app-004
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La formation du glucose solide à partir de ses éléments a pour enthalpie $\Delta_f H^\circ(\ce{C6H12O6,s}) = -1273\ \text{kJ/mol}$ ; sa masse molaire vaut $180\ \text{g/mol}$. Quelle chaleur est échangée lors de la formation de $90{,}0\ \text{g}$ de glucose, dans les conditions standard ?

**Options**
- A. $-636{,}5\ \text{kJ}$
- B. $-1273\ \text{kJ}$
- C. $-114570\ \text{kJ}$
- D. $-2546\ \text{kJ}$

**Réponse correcte** : A

**Feedback correct**
$90{,}0\ \text{g}$ correspondent à $n = 90{,}0/180 = 0{,}500\ \text{mol}$ de glucose, donc $Q = n\,\Delta_f H^\circ = 0{,}500\times(-1273) = -636{,}5\ \text{kJ}$ : la formation dégage de la chaleur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-1273\ \text{kJ}$ est la chaleur pour une mole de glucose ($180\ \text{g}$), pas pour $90{,}0\ \text{g}$ : il faut multiplier par $n = 0{,}500\ \text{mol}$.
- Si C : $-114570\ \text{kJ}$ multiplie $\Delta_f H^\circ$ par la masse en grammes au lieu de la quantité de matière : il faut diviser par $M$ pour obtenir $n$.
- Si D : $-2546\ \text{kJ}$ utilise le rapport $M/m$ au lieu de $m/M$ : $n = m/M = 0{,}500\ \text{mol}$, pas $2{,}00\ \text{mol}$.

**Référence manuel** : thermochimie-1-formation-criteres

---
id: q-enthalpie-de-formation-symbo-eva-001
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
L'éthyne a une enthalpie standard de formation $\Delta_f H^\circ(\ce{C2H2,g}) = +227\ \text{kJ/mol}$. Une élève en conclut : « Une enthalpie de formation positive signifie que l'éthyne est instable : il se décompose immédiatement en carbone et en dihydrogène. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est abusive : $\Delta_f H^\circ > 0$ signifie seulement que sa formation à partir des éléments absorbe de la chaleur (la décomposition en libère) ; cela ne dit rien de la vitesse de décomposition, que l'enthalpie seule ne détermine pas.
- B. Elle est juste : un composé de $\Delta_f H^\circ > 0$ est toujours instable et se décompose aussitôt.
- C. Elle est fausse : une enthalpie de formation ne peut pas être positive pour un composé stable.
- D. Elle est fausse : la décomposition de l'éthyne est endothermique, donc elle ne peut pas se produire.

**Réponse correcte** : A

**Feedback correct**
$\Delta_f H^\circ > 0$ décrit un bilan d'énergie : l'éthyne est plus « riche en enthalpie » que ses éléments, sa décomposition libérerait $227\ \text{kJ/mol}$. Mais l'enthalpie ne renseigne pas sur la vitesse : l'éthyne se conserve en bouteille (stabilité cinétique), alors que sa décomposition reste exothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Un signe positif de $\Delta_f H^\circ$ ne fixe pas la vitesse de décomposition : beaucoup de composés à $\Delta_f H^\circ > 0$ sont conservés sans difficulté, la décomposition étant très lente sans activation.
- Si C : Des composés stables, comme l'éthyne ou le $\ce{NO2}$, ont une enthalpie de formation positive : c'est fréquent et sans contradiction.
- Si D : Si la formation est endothermique, la décomposition (réaction inverse) est exothermique ($-227\ \text{kJ/mol}$) : le signe n'interdit pas la décomposition, il ne dit simplement rien sur sa vitesse.

**Référence manuel** : thermochimie-1-formation-criteres


<!-- LOT loi-de-hess (formule des ΔfH), 04.11.2026 — généré par script, statut to_fix -->

---
id: q-loi-de-hess-symbo-sou-001
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-04
statut: validated
---

**Question**
Quelle expression donne $\Delta_r H^\circ$ à partir des enthalpies standard de formation, $\nu$ désignant les coefficients stœchiométriques ?

**Options**
- A. $\Delta_r H^\circ = \sum \nu\,\Delta_f H^\circ(\text{produits}) - \sum \nu\,\Delta_f H^\circ(\text{réactifs})$
- B. $\Delta_r H^\circ = \sum \nu\,\Delta_f H^\circ(\text{réactifs}) - \sum \nu\,\Delta_f H^\circ(\text{produits})$
- C. $\Delta_r H^\circ = \sum \nu\,\Delta_f H^\circ(\text{produits}) + \sum \nu\,\Delta_f H^\circ(\text{réactifs})$
- D. $\Delta_r H^\circ = \sum \Delta_f H^\circ(\text{produits}) - \sum \Delta_f H^\circ(\text{réactifs})$, sans tenir compte des coefficients

**Réponse correcte** : A

**Feedback correct**
On part des corps purs simples, on forme les produits ($+\sum\nu\,\Delta_f H^\circ$ produits) et l'on retire ce qu'il a fallu pour former les réactifs ($-\sum\nu\,\Delta_f H^\circ$ réactifs).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Cette expression est inversée (réactifs moins produits) : elle donne le signe opposé de $\Delta_r H^\circ$.
- Si C : Une somme des deux termes n'a pas de sens physique : les réactifs sont consommés, leur contribution se soustrait.
- Si D : Les coefficients stœchiométriques sont indispensables : deux moles de produit contribuent deux fois plus qu'une.

**Référence manuel** : thermochimie-1-hess-fonction-etat

---
id: q-loi-de-hess-symbo-com-003
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
La formule $\Delta_r H^\circ = \sum \nu\,\Delta_f H^\circ(\text{produits}) - \sum \nu\,\Delta_f H^\circ(\text{réactifs})$ peut se lire comme un chemin fictif entre réactifs et produits. Lequel ?

**Options**
- A. Décomposer les réactifs en corps purs simples, puis former les produits à partir de ces corps purs simples
- B. Dissocier les réactifs en atomes isolés à l'état gazeux, puis former les produits à partir de ces atomes
- C. Brûler complètement les réactifs, puis reformer les produits à partir du dioxyde de carbone et de l'eau obtenus
- D. Porter les réactifs à ébullition, puis les refroidir jusqu'à la température des produits

**Réponse correcte** : A

**Feedback correct**
Passer des réactifs aux corps purs simples coûte $-\sum\nu\,\Delta_f H^\circ(\text{réactifs})$ ; en former les produits apporte $+\sum\nu\,\Delta_f H^\circ(\text{produits})$. Le chemin est fictif, mais l'enthalpie étant une fonction d'état, le bilan est le même que par la voie réelle.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Ce chemin passe par les atomes isolés : c'est celui de la méthode des énergies de liaison, non celui des enthalpies de formation, définies à partir des corps purs simples.
- Si C : Un chemin par la combustion relie les composés à $\ce{CO2}$ et $\ce{H2O}$ : c'est la logique des enthalpies de combustion, non celle des enthalpies de formation.
- Si D : Un simple changement de température ne transforme pas les réactifs en produits : le chemin doit décrire la transformation chimique elle-même, ici via les corps purs simples.

**Référence manuel** : thermochimie-1-hess-fonction-etat

---
id: q-loi-de-hess-symbo-app-003
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La réaction de la thermite, utilisée pour souder des rails, s'écrit $\ce{Fe2O3(s) + 2 Al(s) -> Al2O3(s) + 2 Fe(s)}$. On donne : $\Delta_f H^\circ(\ce{Fe2O3,s}) = -824\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{Al2O3,s}) = -1676\ \text{kJ/mol}$. Les métaux $\ce{Al(s)}$ et $\ce{Fe(s)}$ sont des corps purs simples. Calculez $\Delta_r H^\circ$ de cette réaction.

**Options**
- A. $-852\ \text{kJ/mol}$
- B. $+852\ \text{kJ/mol}$
- C. $-1676\ \text{kJ/mol}$
- D. $-2500\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ = \Delta_f H^\circ(\ce{Al2O3}) + 2\,\Delta_f H^\circ(\ce{Fe}) - \Delta_f H^\circ(\ce{Fe2O3}) - 2\,\Delta_f H^\circ(\ce{Al}) = (-1676) + 0 - (-824) - 0 = -852\ \text{kJ/mol}$ (les corps purs simples valent $0$). La réaction est fortement exothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+852\ \text{kJ/mol}$ inverse le sens du calcul : il faut faire produits moins réactifs, pas réactifs moins produits.
- Si C : $-1676\ \text{kJ/mol}$ ne retient que $\Delta_f H^\circ(\ce{Al2O3})$ : il manque la soustraction de $\Delta_f H^\circ(\ce{Fe2O3})$, un réactif non nul.
- Si D : $-2500\ \text{kJ/mol}$ additionne les enthalpies de formation du réactif et du produit : le réactif doit être soustrait.

**Référence manuel** : thermochimie-1-loi-hess

---
id: q-loi-de-hess-symbo-app-004
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Dans un four à chaux, le calcaire se décompose selon $\ce{CaCO3(s) -> CaO(s) + CO2(g)}$. On donne : $\Delta_f H^\circ(\ce{CaCO3,s}) = -1207\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{CaO,s}) = -635\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{CO2,g}) = -394\ \text{kJ/mol}$. Calculez $\Delta_r H^\circ$ de cette réaction.

**Options**
- A. $+178\ \text{kJ/mol}$
- B. $-178\ \text{kJ/mol}$
- C. $+572\ \text{kJ/mol}$
- D. $-2236\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ = \Delta_f H^\circ(\ce{CaO}) + \Delta_f H^\circ(\ce{CO2}) - \Delta_f H^\circ(\ce{CaCO3}) = (-635) + (-394) - (-1207) = +178\ \text{kJ/mol}$ : la décomposition est endothermique, ce qui explique qu'il faille chauffer le four en continu.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-178\ \text{kJ/mol}$ résulte d'une inversion du sens du calcul (réactifs moins produits) : la décomposition absorbe de la chaleur, elle n'en libère pas.
- Si C : $+572\ \text{kJ/mol}$ oublie le $\ce{CO2(g)}$ parmi les produits : il compte, car son $\Delta_f H^\circ$ n'est pas nul.
- Si D : $-2236\ \text{kJ/mol}$ additionne les trois enthalpies de formation : le réactif doit être soustrait, non ajouté.

**Référence manuel** : thermochimie-1-loi-hess

---
id: q-loi-de-hess-symbo-app-005
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Première étape de la fabrication de l'acide nitrique (procédé Ostwald) : $\ce{4 NH3(g) + 5 O2(g) -> 4 NO(g) + 6 H2O(g)}$. On donne : $\Delta_f H^\circ(\ce{NH3,g}) = -46\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{NO,g}) = 91\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{H2O,g}) = -242\ \text{kJ/mol}$. Calculez $\Delta_r H^\circ$ de cette réaction.

**Options**
- A. $-904\ \text{kJ/mol}$
- B. $+904\ \text{kJ/mol}$
- C. $-105\ \text{kJ/mol}$
- D. $-1168\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ = 4\,\Delta_f H^\circ(\ce{NO}) + 6\,\Delta_f H^\circ(\ce{H2O,g}) - 4\,\Delta_f H^\circ(\ce{NH3}) - 5\,\Delta_f H^\circ(\ce{O2}) = 364 - 1452 + 184 - 0 = -904\ \text{kJ/mol}$ pour l'équation telle qu'écrite.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+904\ \text{kJ/mol}$ inverse le sens du calcul : la réaction est exothermique, avec produits moins réactifs.
- Si C : $-105\ \text{kJ/mol}$ ignore les coefficients stœchiométriques ($4$, $6$, $4$) : chaque $\Delta_f H^\circ$ doit être multiplié par son coefficient.
- Si D : $-1168\ \text{kJ/mol}$ utilise $\Delta_f H^\circ(\ce{H2O,l}) = -286\ \text{kJ/mol}$ alors que l'équation écrit de l'eau gazeuse : l'état physique doit correspondre.

**Référence manuel** : thermochimie-1-loi-hess

---
id: q-loi-de-hess-symbo-app-006
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
En métallurgie, l'oxyde de cuivre est réduit par le monoxyde de carbone : $\ce{CuO(s) + CO(g) -> Cu(s) + CO2(g)}$. On donne : $\Delta_f H^\circ(\ce{CuO,s}) = -157\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{CO,g}) = -111\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{CO2,g}) = -394\ \text{kJ/mol}$. Le cuivre métallique est un corps pur simple. Calculez $\Delta_r H^\circ$ de cette réaction.

**Options**
- A. $-126\ \text{kJ/mol}$
- B. $+126\ \text{kJ/mol}$
- C. $-237\ \text{kJ/mol}$
- D. $-662\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ = \Delta_f H^\circ(\ce{CO2}) + \Delta_f H^\circ(\ce{Cu}) - \Delta_f H^\circ(\ce{CuO}) - \Delta_f H^\circ(\ce{CO}) = (-394) + 0 - (-157) - (-111) = -126\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+126\ \text{kJ/mol}$ inverse le sens du calcul : réactifs moins produits donne le signe opposé.
- Si C : $-237\ \text{kJ/mol}$ oublie $\Delta_f H^\circ(\ce{CO})$ parmi les réactifs : $\ce{CO}$ n'est pas un corps pur simple, sa valeur n'est pas nulle.
- Si D : $-662\ \text{kJ/mol}$ additionne les enthalpies de formation de $\ce{CO2}$, $\ce{CuO}$ et $\ce{CO}$ : les réactifs doivent être soustraits.

**Référence manuel** : thermochimie-1-loi-hess

---
id: q-loi-de-hess-symbo-eva-003
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Pour la combustion du méthane $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$, une élève écrit $\Delta_r H^\circ = [(-394) + 2\times(-242)] - [(-75) + 0] = -803\ \text{kJ/mol}$. On donne $\Delta_f H^\circ(\ce{H2O,l}) = -286\ \text{kJ/mol}$ et $\Delta_f H^\circ(\ce{H2O,g}) = -242\ \text{kJ/mol}$. Que penser de son calcul ?

**Options**
- A. Il est faux : elle a pris l'enthalpie de formation de l'eau gazeuse alors que l'équation produit de l'eau liquide ; avec $-286\ \text{kJ/mol}$, $\Delta_r H^\circ = -891\ \text{kJ/mol}$.
- B. Il est juste : l'enthalpie de formation de l'eau est la même quel que soit son état physique.
- C. Il est faux : la formule devrait faire réactifs moins produits, ce qui donnerait $+803\ \text{kJ/mol}$.
- D. Il est faux : le dioxygène devrait être compté avec $\Delta_f H^\circ(\ce{O2}) = -242\ \text{kJ/mol}$ ; la valeur correcte est alors $-1287\ \text{kJ/mol}$.

**Réponse correcte** : A

**Feedback correct**
L'état physique doit correspondre à celui de l'équation : l'eau liquide a $\Delta_f H^\circ = -286\ \text{kJ/mol}$ ; $\Delta_r H^\circ = [(-394) + 2\times(-286)] - [(-75) + 0] = -891\ \text{kJ/mol}$. Le calcul de l'élève correspond à la combustion avec de l'eau gazeuse ($-803\ \text{kJ/mol}$) : la différence $88 = 2\times44$ est l'enthalpie de vaporisation de deux moles d'eau.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les enthalpies de formation de $\ce{H2O(l)}$ ($-286$) et de $\ce{H2O(g)}$ ($-242$) diffèrent de $44\ \text{kJ/mol}$ : c'est l'enthalpie de vaporisation, l'état physique ne peut donc pas être ignoré.
- Si C : La formule est bien produits moins réactifs : le signe de son résultat est correct ; c'est le choix de la valeur pour l'eau qui est en cause.
- Si D : Le dioxygène est un corps pur simple dans son état le plus stable : son $\Delta_f H^\circ$ vaut $0$ par définition, jamais $-242\ \text{kJ/mol}$.

**Référence manuel** : thermochimie-1-loi-hess

---
id: q-loi-de-hess-symbo-eva-004
concept: loi-de-hess
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Une élève calcule l'enthalpie de combustion du diamant, $\ce{C(diamant) + O2(g) -> CO2(g)}$, en posant $\Delta_f H^\circ(\ce{C,diamant}) = 0$ comme pour tout corps pur simple, et trouve $-394\ \text{kJ/mol}$. On donne $\Delta_f H^\circ(\ce{C,diamant}) = +1{,}9\ \text{kJ/mol}$ et $\Delta_f H^\circ(\ce{CO2,g}) = -394\ \text{kJ/mol}$. Que penser de son raisonnement ?

**Options**
- A. Il est faux : seule la forme la plus stable du corps simple (ici le graphite) a $\Delta_f H^\circ = 0$ ; pour le diamant, $\Delta_r H^\circ = -394 - 1{,}9 = -395{,}9\ \text{kJ/mol}$.
- B. Il est juste : tout corps pur simple a une enthalpie de formation nulle, quelle que soit sa forme.
- C. Il est faux : il faut ajouter $+1{,}9$ aux produits, ce qui donne $\Delta_r H^\circ = -392{,}1\ \text{kJ/mol}$.
- D. Il est juste : le diamant et le graphite sont le même élément, donc leur combustion dégage exactement la même chaleur.

**Réponse correcte** : A

**Feedback correct**
La convention $\Delta_f H^\circ = 0$ ne s'applique qu'à l'état de référence (graphite). Le diamant est un peu moins stable ($+1{,}9\ \text{kJ/mol}$) : $\Delta_r H^\circ = (-394) - (+1{,}9) = -395{,}9\ \text{kJ/mol}$, valeur un peu plus négative que celle du graphite, puisque le diamant part d'un niveau d'enthalpie plus élevé.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La convention ne vaut que pour la forme la plus stable : le diamant, moins stable que le graphite, a une enthalpie de formation non nulle.
- Si C : $\Delta_f H^\circ(\ce{C,diamant})$ est celle d'un réactif : elle se soustrait, produisant $-395{,}9$ ; ajouter $1{,}9$ aux produits n'a pas de sens ici.
- Si D : Deux formes d'un même élément n'ont pas la même enthalpie : leur combustion ne dégage pas exactement la même chaleur (écart ici de $1{,}9\ \text{kJ/mol}$).

**Référence manuel** : thermochimie-1-formation-definition


<!-- LOT calorimetrie + enthalpie-de-dissolution, 04.11.2026 — généré par script, statut to_fix -->

---
id: q-calorimetrie-symbo-app-003
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
On dissout $11{,}1\ \text{g}$ de $\ce{CaCl2}$ ($M = 111{,}0\ \text{g/mol}$, $\Delta H^\circ_\text{diss} = -75\ \text{kJ/mol}$) dans $150\ \text{g}$ d'eau à $18{,}0\ ^\circ\text{C}$ (on assimile la solution à $150\ \text{g}$ d'eau ; $C_\text{cal}$ négligée ; $C_p = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$). Quelle est la température finale ?

**Options**
- A. $30{,}0\ ^\circ\text{C}$
- B. $6{,}0\ ^\circ\text{C}$
- C. $12{,}0\ ^\circ\text{C}$
- D. $18{,}0\ ^\circ\text{C}$

**Réponse correcte** : A

**Feedback correct**
$n = 11{,}1/111{,}0 = 0{,}100\ \text{mol}$ ; la dissolution libère $Q = 75 \times 0{,}100 = 7{,}50\ \text{kJ}$, absorbés par l'eau : $\Delta T = 7500/(150 \times 4{,}18) = 11{,}96\ \text{K}$, d'où $T_f = 18{,}0 + 11{,}96 \approx 30{,}0\ ^\circ\text{C}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $6{,}0\ ^\circ\text{C}$ soustrait $\Delta T$ de la température initiale : la dissolution est exothermique, la solution se réchauffe.
- Si C : $12{,}0\ ^\circ\text{C}$ est la variation $\Delta T$, pas la température finale : il faut l'ajouter à $18{,}0\ ^\circ\text{C}$.
- Si D : $18{,}0\ ^\circ\text{C}$ oublie de convertir les kJ en J dans $Q = m\,C_p\,\Delta T$ : la variation de température obtenue est mille fois trop faible.

**Référence manuel** : thermochimie-1-bilan-calorimetrique

---
id: q-calorimetrie-symbo-app-004
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Une compresse froide de laboratoire : on dissout $8{,}0\ \text{g}$ de $\ce{NH4NO3}$ ($M = 80{,}04\ \text{g/mol}$, $\Delta H^\circ_\text{diss} = +26\ \text{kJ/mol}$) dans $100\ \text{g}$ d'eau à $22{,}0\ ^\circ\text{C}$, dans un calorimètre de constante $C_\text{cal} = 0{,}14\ \text{kJ/K}$ (solution assimilée à $100\ \text{g}$ d'eau). Quelle est la température finale ?

**Options**
- A. $17{,}3\ ^\circ\text{C}$
- B. $26{,}7\ ^\circ\text{C}$
- C. $15{,}8\ ^\circ\text{C}$
- D. $4{,}7\ ^\circ\text{C}$

**Réponse correcte** : A

**Feedback correct**
$n = 8{,}0/80{,}04 = 0{,}100\ \text{mol}$ ; la dissolution absorbe $Q = 26 \times 0{,}100 = 2{,}60\ \text{kJ}$ à l'ensemble eau + calorimètre : $\Delta T = 2600/(100 \times 4{,}18 + 140) = 4{,}66\ \text{K}$, d'où $T_f = 22{,}0 - 4{,}66 \approx 17{,}3\ ^\circ\text{C}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $26{,}7\ ^\circ\text{C}$ ajoute $\Delta T$ : la dissolution est endothermique, la solution se refroidit.
- Si C : $15{,}8\ ^\circ\text{C}$ oublie la constante calorimétrique : le calorimètre absorbe aussi de la chaleur, ce qui limite le refroidissement.
- Si D : $4{,}7\ ^\circ\text{C}$ est la variation de température $\Delta T$ prise pour la température finale : il faut la retrancher de $22{,}0\ ^\circ\text{C}$.

**Référence manuel** : thermochimie-1-bilan-calorimetrique

---
id: q-calorimetrie-symbo-app-005
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
On brûle du méthanol $\ce{CH3OH(l)}$ ($M = 32{,}04\ \text{g/mol}$, $\Delta_r H^\circ_c = -726\ \text{kJ/mol}$) pour chauffer un calorimètre contenant $230{,}0\ \text{g}$ d'eau ($C_\text{cal}$ négligée). La température de l'eau s'élève de $12{,}0\ ^\circ\text{C}$. Quelle masse de méthanol a été brûlée ?

**Options**
- A. $0{,}509\ \text{g}$
- B. $0{,}0159\ \text{g}$
- C. $509\ \text{g}$
- D. $4{,}96\times10^{-4}\ \text{g}$

**Réponse correcte** : A

**Feedback correct**
$Q = 230{,}0 \times 4{,}18 \times 12{,}0 = 11537\ \text{J} = 11{,}54\ \text{kJ}$ ; $n = 11{,}54/726 = 0{,}0159\ \text{mol}$ ; $m = n\,M = 0{,}0159 \times 32{,}04 \approx 0{,}509\ \text{g}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $0{,}0159\ \text{g}$ est la quantité de matière en mol, pas la masse : il reste à multiplier par $M = 32{,}04\ \text{g/mol}$.
- Si C : $509\ \text{g}$ confond joules et kilojoules : $Q$ vaut $11{,}5\ \text{kJ}$ et non $11537\ \text{kJ}$.
- Si D : $4{,}96\times10^{-4}\ \text{g}$ divise $n$ par $M$ au lieu de la multiplier : on passe des moles aux grammes en multipliant par la masse molaire.

**Référence manuel** : thermochimie-1-bilan-calorimetrique

---
id: q-calorimetrie-symbo-ana-003
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
Pour étalonner une bombe calorimétrique, on y brûle $0{,}500\ \text{g}$ d'acide benzoïque ($M = 122{,}1\ \text{g/mol}$, $\Delta_r H^\circ_c = -3228\ \text{kJ/mol}$) ; la bombe est plongée dans $800\ \text{g}$ d'eau, dont la température s'élève de $3{,}14\ ^\circ\text{C}$. Quelle est la constante calorimétrique $C_\text{cal}$ de la bombe ?

**Options**
- A. $0{,}87\ \text{kJ/K}$
- B. $4{,}21\ \text{kJ/K}$
- C. $7{,}55\ \text{kJ/K}$
- D. $866\ \text{kJ/K}$

**Réponse correcte** : A

**Feedback correct**
La combustion dégage $Q_r = 3228 \times 0{,}500/122{,}1 = 13{,}22\ \text{kJ}$ ; l'eau en absorbe $800 \times 4{,}18 \times 3{,}14/1000 = 10{,}50\ \text{kJ}$ ; la bombe absorbe le reste : $C_\text{cal} \times 3{,}14 = 13{,}22 - 10{,}50$, d'où $C_\text{cal} \approx 0{,}87\ \text{kJ/K}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $4{,}21\ \text{kJ/K}$ attribue toute la chaleur à la bombe : l'eau en absorbe aussi une part, qu'il faut retrancher.
- Si C : $7{,}55\ \text{kJ/K}$ ajoute la chaleur de l'eau au lieu de la soustraire : $C_\text{cal}$ correspond à la part de chaleur que l'eau n'a pas absorbée.
- Si D : $866\ \text{kJ/K}$ confond $\text{kJ/K}$ et $\text{J/K}$ : la valeur trouvée est en $\text{J/K}$ (soit $0{,}87\ \text{kJ/K}$).

**Référence manuel** : thermochimie-1-bilan-calorimetrique

---
id: q-calorimetrie-symbo-ana-004
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
Un calorimètre de constante $C_\text{cal} = 0{,}50\ \text{kJ/K}$ contient $300\ \text{g}$ d'eau à $20{,}0\ ^\circ\text{C}$. On y verse $100\ \text{g}$ d'eau à $60{,}0\ ^\circ\text{C}$. Quelle est la température d'équilibre (aucune perte de chaleur) ?

**Options**
- A. $27{,}7\ ^\circ\text{C}$
- B. $30{,}0\ ^\circ\text{C}$
- C. $40{,}0\ ^\circ\text{C}$
- D. $50{,}0\ ^\circ\text{C}$

**Réponse correcte** : A

**Feedback correct**
$100 \times 4{,}18 \times (60{,}0 - T_f) = (300 \times 4{,}18 + 500)(T_f - 20{,}0)$, soit $418\,(60{,}0 - T_f) = 1754\,(T_f - 20{,}0)$, d'où $T_f \approx 27{,}7\ ^\circ\text{C}$ : le calorimètre, qui monte aussi en température, retient une partie de la chaleur de l'eau chaude.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $30{,}0\ ^\circ\text{C}$ ignore la constante calorimétrique : le calorimètre absorbe aussi de la chaleur, donc la température d'équilibre est plus basse.
- Si C : $40{,}0\ ^\circ\text{C}$ est la moyenne simple des deux températures : elle supposerait des masses égales et un calorimètre sans capacité thermique.
- Si D : $50{,}0\ ^\circ\text{C}$ permute les masses : la plus grande masse (l'eau froide) pèse le plus dans l'équilibre, qui reste donc plus proche de $20\ ^\circ\text{C}$.

**Référence manuel** : thermochimie-1-bilan-calorimetrique

---
id: q-calorimetrie-symbo-eva-003
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Dans un calorimètre contenant $500\ \text{g}$ d'eau ($C_\text{cal}$ négligée), la combustion de $1{,}0\ \text{g}$ de graphite élève la température de $15\ ^\circ\text{C}$ ; l'élève trouve $\Delta_r H^\circ \approx -376\ \text{kJ/mol}$, alors que la valeur tabulée est $-394\ \text{kJ/mol}$. Quelle évaluation de cet écart est la plus pertinente ?

**Options**
- A. L'écart d'environ $5\ \%$ est cohérent avec une constante calorimétrique négligée : le calorimètre absorbe lui aussi de la chaleur, donc l'eau seule en reçoit moins que la réaction n'en dégage.
- B. La mesure fait foi : la valeur tabulée de $-394\ \text{kJ/mol}$ doit être corrigée à $-376\ \text{kJ/mol}$.
- C. L'élève s'est trompé de signe : la valeur correcte de sa mesure serait $+376\ \text{kJ/mol}$.
- D. La combustion d'un solide dans une bombe donne toujours une valeur inférieure de $5\ \%$ à la valeur tabulée : c'est un facteur de correction systématique.

**Réponse correcte** : A

**Feedback correct**
La chaleur reçue par l'eau est $500 \times 4{,}18 \times 15 = 31350\ \text{J}$, soit $\Delta_r H^\circ \approx -376\ \text{kJ/mol}$ pour $n = 0{,}083\ \text{mol}$ ; la valeur tabulée correspondrait à $\approx 32{,}8\ \text{kJ}$ : il manque $\approx 1{,}5\ \text{kJ}$, qu'absorberait le calorimètre avec $C_\text{cal} \approx 0{,}10\ \text{kJ/K}$. L'écart est un biais de la mesure, pas une erreur des tables.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Une valeur tabulée est établie par de nombreuses mesures soignées, avec $C_\text{cal}$ étalonnée : une mesure d'élève simplifiée ne la remet pas en cause.
- Si C : Le signe est correct : la réaction est exothermique, donc $\Delta_r H^\circ < 0$. C'est l'ampleur qui s'écarte de la table, pas le signe.
- Si D : Aucun facteur systématique de $5\ \%$ n'existe : l'écart dépend du calorimètre utilisé (sa constante calorimétrique) et des pertes de chaleur, propres à chaque montage.

**Référence manuel** : thermochimie-1-bombe-calorimetrique

---
id: q-calorimetrie-symbo-eva-004
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Dans un calorimètre isolé, une élève fait réagir $0{,}010\ \text{mol}$ de réactif dans $50\ \text{g}$ d'eau ($C_\text{cal}$ négligée) : la température de l'eau monte de $5{,}0\ ^\circ\text{C}$. Elle calcule $Q = 50 \times 4{,}18 \times 5{,}0 = +1045\ \text{J}$, puis $\Delta_r H^\circ = +1{,}045/0{,}010 = +104{,}5\ \text{kJ/mol}$, et conclut que la réaction est endothermique. Que penser de ce raisonnement ?

**Options**
- A. Il est faux : $+1045\ \text{J}$ est la chaleur reçue par l'eau ; celle de la réaction est son opposée ($-1045\ \text{J}$), d'où $\Delta_r H^\circ = -104{,}5\ \text{kJ/mol}$ et une réaction exothermique.
- B. Il est juste : l'eau a reçu de la chaleur, donc la réaction a absorbé de la chaleur.
- C. Il est faux : il fallait diviser par la masse d'eau et non par la quantité de matière de réactif ; la réaction reste endothermique.
- D. Il est juste : une température qui augmente est le signe d'une réaction endothermique.

**Réponse correcte** : A

**Feedback correct**
Le système isolé impose $Q_\text{réaction} + Q_\text{eau} = 0$ : l'eau se réchauffe parce que la réaction lui cède de la chaleur. $Q_\text{réaction} = -1045\ \text{J}$ et $\Delta_r H^\circ = -1{,}045/0{,}010 = -104{,}5\ \text{kJ/mol}$ : réaction exothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Que l'eau reçoive de la chaleur ne signifie pas que la réaction en absorbe : c'est elle qui la lui a cédée ; le bilan s'écrit $Q_\text{réaction} = -Q_\text{eau}$.
- Si C : Le calcul par mole de réactif est correct ($\Delta_r H^\circ$ s'exprime en kJ par mole) ; l'erreur porte sur le signe de $Q_\text{réaction}$.
- Si D : Une température qui monte dans le calorimètre indique au contraire que la réaction dégage de la chaleur : elle est exothermique.

**Référence manuel** : thermochimie-1-calorimetrie-principe

---
id: q-calorimetrie-symbo-com-002
concept: calorimetrie
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
Pour dissoudre $5\ \text{g}$ de sel dans $100\ \text{g}$ d'eau, on calcule la chaleur absorbée par la solution avec $m = 100\ \text{g}$ (et non $105\ \text{g}$) et $C_p = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$. Comment justifier cette convention ?

**Options**
- A. La solution est constituée essentiellement d'eau : on l'assimile à l'eau pure, ce qui introduit une erreur de quelques pour cent, faible devant les autres incertitudes de la mesure.
- B. Le sel dissous n'absorbe jamais de chaleur, car sa température ne change pas.
- C. Seule l'eau participe à la réaction de dissolution, le sel étant un simple spectateur.
- D. Pour une solution, la masse à prendre en compte est toujours celle du solvant seul, quelle que soit la concentration.

**Réponse correcte** : A

**Feedback correct**
Une solution diluée a une capacité thermique massique très voisine de celle de l'eau : assimiler la solution à la masse d'eau est une approximation raisonnable, dont l'effet reste petit pour des solutions diluées. La convention doit simplement être annoncée dans l'énoncé.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le soluté dissous est à la même température que l'eau : il absorbe donc de la chaleur ; son effet est seulement petit devant celui de l'eau.
- Si C : Le sel participe bien à la dissolution : c'est la rupture et la formation d'interactions qui échange la chaleur ; ce sont ces échanges que l'on mesure.
- Si D : Aucune règle générale n'impose de ne prendre que le solvant : pour une solution concentrée, l'approximation devient mauvaise ; la convention vaut pour les solutions diluées.

**Référence manuel** : thermochimie-1-bilan-calorimetrique

---
id: q-enthalpie-de-dissolution-symbo-app-003
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
On donne $\Delta_f H^\circ(\ce{NH4+,aq}) = -133\ \text{kJ/mol}$, $\Delta_f H^\circ(\ce{NO3-,aq}) = -207\ \text{kJ/mol}$ et $\Delta_f H^\circ(\ce{NH4NO3,s}) = -366\ \text{kJ/mol}$. Calculez $\Delta H^\circ_\text{diss}$ de $\ce{NH4NO3(s) -> NH4+(aq) + NO3-(aq)}$.

**Options**
- A. $+26\ \text{kJ/mol}$
- B. $-26\ \text{kJ/mol}$
- C. $-706\ \text{kJ/mol}$
- D. $+233\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta H^\circ_\text{diss} = (-133) + (-207) - (-366) = +26\ \text{kJ/mol}$ : dissolution endothermique, d'où l'usage du sel dans les compresses froides.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-26\ \text{kJ/mol}$ inverse le sens du calcul (réactifs moins produits) : la dissolution de $\ce{NH4NO3}$ absorbe de la chaleur.
- Si C : $-706\ \text{kJ/mol}$ additionne les trois enthalpies de formation : le sel solide, réactif, doit être soustrait.
- Si D : $+233\ \text{kJ/mol}$ oublie l'ion $\ce{NO3-}$ : les deux ions solvatés comptent parmi les produits.

**Référence manuel** : thermochimie-1-dissolution-calcul

---
id: q-enthalpie-de-dissolution-symbo-app-004
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Le chlorure d'hydrogène gazeux se dissout dans l'eau : $\ce{HCl(g) -> H+(aq) + Cl-(aq)}$. On donne $\Delta_f H^\circ(\ce{HCl,g}) = -92\ \text{kJ/mol}$ et $\Delta_f H^\circ(\ce{Cl-,aq}) = -167\ \text{kJ/mol}$. Calculez $\Delta H^\circ_\text{diss}$ (on rappelle la valeur conventionnelle de $\Delta_f H^\circ(\ce{H+,aq})$).

**Options**
- A. $-75\ \text{kJ/mol}$
- B. $+75\ \text{kJ/mol}$
- C. $-259\ \text{kJ/mol}$
- D. $-167\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
Par convention $\Delta_f H^\circ(\ce{H+,aq}) = 0$ : $\Delta H^\circ_\text{diss} = 0 + (-167) - (-92) = -75\ \text{kJ/mol}$ (dissolution exothermique).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $+75\ \text{kJ/mol}$ inverse le sens du calcul : produits moins réactifs donne ici un résultat négatif.
- Si C : $-259\ \text{kJ/mol}$ additionne $\Delta_f H^\circ(\ce{Cl-})$ et $\Delta_f H^\circ(\ce{HCl})$ : le réactif doit être soustrait.
- Si D : $-167\ \text{kJ/mol}$ oublie de soustraire $\Delta_f H^\circ(\ce{HCl,g})$ : le réactif compte, même si $\ce{H+}$ vaut $0$.

**Référence manuel** : thermochimie-1-dissolution-calcul

---
id: q-enthalpie-de-dissolution-symbo-com-002
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
Pourquoi attribue-t-on la valeur $\Delta_f H^\circ(\ce{H+,aq}) = 0$ dans les calculs d'enthalpies de dissolution ?

**Options**
- A. C'est une convention : on choisit l'ion $\ce{H+(aq)}$ comme origine de l'échelle, et les enthalpies de formation des autres ions en solution sont exprimées par rapport à lui.
- B. Parce que $\ce{H+}$ est un corps pur simple dans son état le plus stable, comme $\ce{H2(g)}$.
- C. Parce que la formation de $\ce{H+(aq)}$ à partir de $\ce{H2(g)}$ a été mesurée et ne libère aucune chaleur.
- D. Parce que le proton ne peut pas interagir avec les molécules d'eau, qui sont neutres.

**Réponse correcte** : A

**Feedback correct**
On ne peut pas former un ion isolé et mesurer son enthalpie de formation : on fixe arbitrairement $\Delta_f H^\circ(\ce{H+,aq}) = 0$, et l'on rapporte à cette référence celles de tous les autres ions solvatés. Cette convention est indépendante de la définition des corps purs simples.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{H+(aq)}$ est un ion solvaté, pas un corps pur simple : la nullité de son enthalpie de formation ne vient pas de la définition des corps simples, mais d'un choix de référence.
- Si C : Une enthalpie de formation d'un ion seul n'est pas mesurable, car une solution reste globalement neutre : la valeur zéro ne résulte donc pas d'une mesure.
- Si D : Le proton interagit très fortement avec l'eau (il forme l'ion hydronium $\ce{H3O+}$) : ce n'est pas l'absence d'interaction qui justifie le zéro.

**Référence manuel** : thermochimie-1-dissolution-calcul

---
id: q-enthalpie-de-dissolution-macro-com-002
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
Une chaufferette réutilisable contient une solution d'acétate de sodium qui reste liquide à température ambiante. Lorsqu'on déclenche la pastille, la poche se solidifie et chauffe. Que traduit cet échauffement ?

**Options**
- A. La cristallisation du sel, processus inverse d'une dissolution endothermique, libère de la chaleur dans la poche.
- B. L'eau de la poche s'évapore et libère de la chaleur en passant à l'état gazeux.
- C. Le frottement de la pastille métallique sur les parois de la poche produit de la chaleur.
- D. La dissolution de la pastille dans la solution libère de la chaleur, comme celle de $\ce{CaCl2}$.

**Réponse correcte** : A

**Feedback correct**
La solution est en surfusion : le sel est dissous au-delà de sa solubilité normale. La pastille amorce la cristallisation, qui est l'inverse d'une dissolution endothermique, donc exothermique : la poche chauffe jusqu'à environ $55\ ^\circ\text{C}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'évaporation absorbe de la chaleur et la poche reste fermée : elle ne peut pas expliquer l'échauffement.
- Si C : Le geste de déclenchement ne fournit qu'une impulsion minuscule : l'énergie dégagée provient de la cristallisation, pas du frottement.
- Si D : La pastille ne se dissout pas : elle sert de germe de cristallisation ; c'est la solidification du sel qui libère la chaleur.

**Référence manuel** : thermochimie-1-chaufferettes

---
id: q-enthalpie-de-dissolution-symbo-eva-003
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Pour concevoir une compresse froide, un élève compare trois sels : $\ce{NaCl}$ ($\Delta H^\circ_\text{diss} = +4\ \text{kJ/mol}$), $\ce{NH4NO3}$ ($+26\ \text{kJ/mol}$) et $\ce{CaCl2}$ ($-75\ \text{kJ/mol}$). Il retient $\ce{CaCl2}$, « parce que son enthalpie de dissolution est de loin la plus grande en valeur absolue ». Que penser de ce choix ?

**Options**
- A. Il est faux : le signe compte autant que la valeur absolue ; $\ce{CaCl2}$ libère de la chaleur et réchaufferait la poche, alors que $\ce{NH4NO3}$, endothermique, la refroidit.
- B. Il est juste : une dissolution très énergétique refroidit d'autant plus la solution.
- C. Il est faux : $\ce{NaCl}$ est meilleur, car la dissolution d'un sel est toujours d'autant plus endothermique que $\Delta H^\circ_\text{diss}$ est petit en valeur absolue.
- D. Il est juste, car la dissolution de $\ce{CaCl2}$ absorbe $75\ \text{kJ}$ par mole de sel dissous.

**Réponse correcte** : A

**Feedback correct**
Pour refroidir, il faut une dissolution **endothermique** ($\Delta H^\circ_\text{diss} > 0$). $\ce{CaCl2}$ ($-75\ \text{kJ/mol}$) est exothermique : il convient aux chaufferettes à usage unique. Parmi les deux sels endothermiques, $\ce{NH4NO3}$ ($+26$) absorbe environ $6$ fois plus de chaleur par mole que $\ce{NaCl}$ ($+4$) : c'est le bon choix.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La grandeur importante est le signe : une valeur négative signifie que la dissolution libère de la chaleur ; la valeur absolue ne dit que l'ampleur de cet échange.
- Si C : Pour refroidir, il faut que $\Delta H^\circ_\text{diss}$ soit positif et le plus grand possible : une valeur proche de zéro (comme $+4$) donne un faible refroidissement.
- Si D : Un $\Delta H^\circ_\text{diss}$ négatif signifie que la dissolution **libère** $75\ \text{kJ}$ par mole de sel : la solution se réchauffe.

**Référence manuel** : thermochimie-1-chaufferettes


<!-- LOT enthalpie, 04.11.2026 — généré par script, statut to_fix -->

---
id: q-enthalpie-symbo-sou-001
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-04
statut: validated
---

**Question**
Quelle expression définit l'enthalpie $H$ d'un système, en fonction de son énergie interne $U$, de sa pression $P$ et de son volume $V$ ?

**Options**
- A. $H = U + P \cdot V$
- B. $H = U - P \cdot V$
- C. $H = U + \dfrac{P}{V}$
- D. $H = P \cdot V - U$

**Réponse correcte** : A

**Feedback correct**
L'enthalpie est définie par $H = U + P\cdot V$ : elle ajoute à l'énergie interne le terme $P\cdot V$, lié au travail de volume nécessaire pour « faire de la place » au système dans l'atmosphère.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le terme $P\cdot V$ s'ajoute à $U$ : la soustraction correspond au travail de volume reçu par le système ($W=-P\Delta V$), pas à la définition de $H$.
- Si C : Le produit $P\cdot V$ a la dimension d'une énergie, pas le quotient $P/V$ : la somme avec $U$ n'aurait aucun sens dimensionnel.
- Si D : Le signe de $U$ est inversé : $H$ est la somme $U + P\cdot V$, pas la différence $P\cdot V - U$.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-com-003
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
On brûle un combustible dans une bombe calorimétrique : le récipient est fermé et rigide, son volume reste constant. La chaleur $Q$ échangée avec l'environnement est alors égale à :

**Options**
- A. la variation d'énergie interne $\Delta U$ du système, car aucun travail de volume n'est échangé
- B. la variation d'enthalpie $\Delta H$, comme pour toute réaction chimique
- C. zéro, car le volume du système ne varie pas
- D. la variation d'enthalpie $\Delta H$ changée de signe, car le récipient est fermé

**Réponse correcte** : A

**Feedback correct**
À volume constant, il n'y a pas de travail de volume ($W = -P\Delta V = 0$), donc $Q_V = \Delta U$. L'égalité $Q = \Delta H$ n'est valable qu'à **pression** constante : pour une réaction qui modifie la quantité de gaz, $\Delta H$ et $\Delta U$ diffèrent de $\Delta(P\cdot V)$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $Q=\Delta H$ suppose une pression constante, ce qui n'est pas le cas dans un récipient rigide fermé où la pression peut varier fortement.
- Si C : Un volume constant supprime seulement le travail de volume : la chaleur échangée reste non nulle, elle vaut $\Delta U$.
- Si D : Un changement de signe n'a aucune raison d'apparaître : le récipient fermé n'impose pas $Q=-\Delta H$, il impose l'absence de travail de volume.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-macro-com-002
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: macro
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
Dans un bécher ouvert à l'air libre, on ajoute du zinc dans une solution d'acide chlorhydrique. La solution se réchauffe de quelques degrés. Que peut-on en déduire sur la réaction, menée à pression atmosphérique constante ?

**Options**
- A. La chaleur est cédée à l'environnement : $Q = \Delta H < 0$, la réaction est exothermique.
- B. La chaleur est absorbée par le système : $Q = \Delta H > 0$, la réaction est endothermique.
- C. Comme la pression est constante, $\Delta H = 0$ et la réaction est athermique.
- D. On ne peut rien dire du signe de $\Delta H$ sans connaître la masse de zinc.

**Réponse correcte** : A

**Feedback correct**
À pression constante, $Q = \Delta H$. La solution (l'environnement de la réaction) se réchauffe : elle reçoit de la chaleur, que le système chimique a cédée. La réaction est donc exothermique et $\Delta H < 0$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La température de la solution monte : l'environnement gagne de la chaleur, ce que le système a perdu. Une réaction endothermique refroidirait la solution.
- Si C : Une pression constante ne rend pas $\Delta H$ nul : elle permet seulement d'identifier $\Delta H$ à la chaleur échangée, qui ici est non nulle.
- Si D : Le **signe** de $\Delta H$ se lit directement sur l'échange de chaleur observé ; la masse de zinc ne fait varier que son ampleur.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-app-003
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La combustion de $0{,}50\ \text{mol}$ de méthane dans un excès de dioxygène, selon $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$, dégage $445\ \text{kJ}$ à pression constante. Quelle est la valeur de $\Delta_r H^\circ$ pour cette réaction, écrite avec ces coefficients ?

**Options**
- A. $-890\ \text{kJ/mol}$
- B. $-445\ \text{kJ/mol}$
- C. $-222{,}5\ \text{kJ/mol}$
- D. $+890\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_r H^\circ$ se rapporte à **une mole de réaction** telle qu'écrite, soit ici $1\ \text{mol}$ de $\ce{CH4}$ brûlé. Pour $0{,}50\ \text{mol}$, $445\ \text{kJ}$ sont dégagés : pour $1\ \text{mol}$, $445/0{,}50 = 890\ \text{kJ}$ ; la chaleur est cédée, donc $\Delta_r H^\circ = -890\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-445\ \text{kJ/mol}$ est la chaleur mesurée pour $0{,}50\ \text{mol}$ : elle n'a pas été ramenée à une mole de réaction.
- Si C : $-222{,}5\ \text{kJ/mol}$ multiplie la chaleur par $0{,}50$ au lieu de la diviser : la valeur par mole doit être **plus grande** que celle mesurée pour une demi-mole.
- Si D : Le signe est inversé : la réaction dégage de la chaleur, donc $\Delta_r H^\circ$ est négatif.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-app-004
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La synthèse de l'ammoniac $\ce{N2(g) + 3 H2(g) -> 2 NH3(g)}$ est menée à pression constante : la formation de $0{,}40\ \text{mol}$ de $\ce{NH3}$ dégage $18{,}4\ \text{kJ}$. Quelle est la valeur de $\Delta_r H^\circ$ pour l'équation telle qu'elle est écrite ?

**Options**
- A. $-92\ \text{kJ/mol}$
- B. $-46\ \text{kJ/mol}$
- C. $-18{,}4\ \text{kJ/mol}$
- D. $-7{,}4\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
Par mole de $\ce{NH3}$ formé : $18{,}4/0{,}40 = 46\ \text{kJ}$ dégagés. L'équation écrite forme $2\ \text{mol}$ de $\ce{NH3}$ par mole de réaction, d'où $\Delta_r H^\circ = 2 \times (-46) = -92\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-46\ \text{kJ/mol}$ est la valeur par mole de $\ce{NH3}$ : l'équation écrite en forme deux moles, il faut multiplier par $2$.
- Si C : $-18{,}4\ \text{kJ/mol}$ est la chaleur mesurée pour $0{,}40\ \text{mol}$ : elle n'est ramenée ni à une mole de $\ce{NH3}$, ni à une mole de réaction.
- Si D : $-7{,}4\ \text{kJ/mol}$ multiplie la chaleur par la quantité de matière ($18{,}4\times0{,}40$) au lieu de la diviser.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-eva-002
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Un élève affirme : « À pression constante, $\Delta H = Q$, donc le système n'échange aucun travail avec l'extérieur. » Que penser de cette affirmation ?

**Options**
- A. Elle est fausse : le système peut fournir ou recevoir un travail de volume ; l'égalité $\Delta H = Q$ tient parce que ce travail est pris en compte dans la définition de $H$.
- B. Elle est juste : si $Q$ et $\Delta H$ sont égaux, aucune autre forme d'énergie n'est échangée.
- C. Elle est fausse : à pression constante, $\Delta H = Q$ n'est valable que si le volume reste aussi constant.
- D. Elle est juste : le travail n'existe qu'à volume constant.

**Réponse correcte** : A

**Feedback correct**
À pression constante, $\Delta U = Q - P\Delta V$, soit $\Delta U + P\Delta V = Q$, c'est-à-dire $\Delta H = Q$. Le travail de volume $-P\Delta V$ existe bien (par exemple lorsqu'un gaz se forme et repousse l'atmosphère) ; il est simplement « absorbé » dans la définition $H = U + P\cdot V$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'égalité $Q=\Delta H$ ne dit pas que le travail est nul : elle dit que la chaleur échangée mesure la variation de $H$, qui inclut le travail de volume.
- Si C : Pression **et** volume constants sont deux conditions différentes : l'égalité $Q=\Delta H$ ne requiert que la pression constante, et à volume constant c'est $\Delta U$ qui est égal à $Q$.
- Si D : C'est l'inverse : le travail de volume $-P\Delta V$ est nul à volume constant, et existe dès que le volume varie.

**Référence manuel** : thermochimie-1-premier-principe

---
id: q-enthalpie-symbo-eva-003
concept: enthalpie
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Un élève mesure la chaleur dégagée par une réaction en bombe calorimétrique (volume constant), puis écrit : « J'ai mesuré $Q$, donc j'ai directement $\Delta_r H^\circ$ de la réaction. » Que penser de cette conclusion ?

**Options**
- A. Elle est discutable : à volume constant, $Q=\Delta U$ ; passer à $\Delta H$ exige de corriger de $\Delta(P\cdot V)$, non négligeable si la quantité de gaz change.
- B. Elle est correcte : la chaleur mesurée est toujours égale à $\Delta H$, quel que soit le dispositif.
- C. Elle est fausse : une bombe calorimétrique ne permet de mesurer que des variations de température, jamais de chaleur.
- D. Elle est correcte : à volume constant, $\Delta U$ et $\Delta H$ sont toujours égaux.

**Réponse correcte** : A

**Feedback correct**
La chaleur mesurée à volume constant est $Q_V = \Delta U$. Comme $\Delta H = \Delta U + \Delta(P\cdot V)$, les deux ne coïncident que si $\Delta(P\cdot V)$ est négligeable, ce qui n'est pas le cas quand la réaction change la quantité de gaz (par exemple une combustion produisant ou consommant du gaz).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $Q=\Delta H$ n'est vraie qu'à pression constante : la bombe calorimétrique opère à volume constant, la chaleur qu'elle mesure vaut $\Delta U$.
- Si C : La température mesurée sert justement à calculer la chaleur échangée, via $Q = C\,\Delta T$ : la bombe permet bien d'en déduire une chaleur.
- Si D : $\Delta H$ et $\Delta U$ diffèrent de $\Delta(P\cdot V)$ : ils ne sont égaux que si cette quantité est négligeable, par exemple sans variation de la quantité de gaz.

**Référence manuel** : thermochimie-1-premier-principe


<!-- LOT hess-généralisée / endo / exo / formation, 04.11.2026 — généré par script, statut to_fix -->

---
id: q-loi-de-hess-generalisee-symbo-app-005
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
On dispose des enthalpies de combustion suivantes : (1) $\ce{C2H4(g) + 3 O2(g) -> 2 CO2(g) + 2 H2O(l)}$, $\Delta_r H^\circ_{(1)} = -1411\ \text{kJ/mol}$ ; (2) $\ce{H2(g) + \frac{1}{2} O2(g) -> H2O(l)}$, $\Delta_r H^\circ_{(2)} = -286\ \text{kJ/mol}$ ; (3) $\ce{C2H6(g) + \frac{7}{2} O2(g) -> 2 CO2(g) + 3 H2O(l)}$, $\Delta_r H^\circ_{(3)} = -1561\ \text{kJ/mol}$. Calculez $\Delta_r H^\circ$ de l'hydrogénation de l'éthène : $\ce{C2H4(g) + H2(g) -> C2H6(g)}$.

**Options**
- A. $-136\ \text{kJ/mol}$
- B. $+136\ \text{kJ/mol}$
- C. $+150\ \text{kJ/mol}$
- D. $-3258\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
L'éthène et le dihydrogène sont consommés : on garde (1) et (2) ; l'éthane est produit : on **inverse** (3). $\Delta_r H^\circ = (-1411) + (-286) - (-1561) = -136\ \text{kJ/mol}$ (on retrouve $\Delta_f H^\circ(\ce{C2H6}) - \Delta_f H^\circ(\ce{C2H4}) = -84 - 52$).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le signe est inversé : l'hydrogénation d'une double liaison est exothermique ; la valeur positive viendrait d'un mauvais sens des équations.
- Si C : $+150$ oublie l'équation (2) : le dihydrogène consommé doit apparaître dans la combinaison, avec son enthalpie de combustion $-286$.
- Si D : $-3258$ additionne les trois équations sans inverser (3) : l'éthane est un produit de la cible, pas un réactif.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-generalisee-symbo-com-002
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
La synthèse de l'ammoniac $\ce{N2(g) + 3 H2(g) -> 2 NH3(g)}$ a pour enthalpie $\Delta_r H^\circ = -92\ \text{kJ/mol}$. Quelle est l'enthalpie de la réaction $\ce{NH3(g) -> \frac{1}{2} N2(g) + \frac{3}{2} H2(g)}$ ?

**Options**
- A. $+46\ \text{kJ/mol}$
- B. $-46\ \text{kJ/mol}$
- C. $+92\ \text{kJ/mol}$
- D. $-92\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
La réaction demandée est l'inverse de la synthèse (changement de signe) et correspond à la moitié des quantités de matière (division par $2$, pour passer de $2\ \text{mol}$ à $1\ \text{mol}$ de $\ce{NH3}$) : $\Delta_r H^\circ = +92/2 = +46\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le signe doit changer : la décomposition de l'ammoniac absorbe la chaleur que sa synthèse dégage.
- Si C : $+92$ inverse bien l'équation mais oublie de diviser par $2$ : l'équation demandée ne met en jeu qu'une mole de $\ce{NH3}$.
- Si D : $-92$ est la valeur de la synthèse telle qu'écrite : l'équation n'a été ni inversée ni ramenée à une mole de $\ce{NH3}$.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-loi-de-hess-generalisee-symbo-eva-002
concept: loi-de-hess-generalisee
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
On dispose des enthalpies de combustion : $\ce{C2H2(g)}$ $-1301$ ; $\ce{H2(g)}$ $-286$ ; $\ce{C2H4(g)}$ $-1411$ (en $\text{kJ/mol}$). Pour calculer $\Delta_r H^\circ$ de $\ce{C2H2(g) + H2(g) -> C2H4(g)}$, une élève applique « produits moins réactifs » aux enthalpies de combustion : $\Delta_r H^\circ = (-1411) - [(-1301) + (-286)] = +176\ \text{kJ/mol}$. Que penser de son calcul ?

**Options**
- A. Il est faux : avec des enthalpies de **combustion**, la règle s'inverse (« réactifs moins produits »), car chaque combustion part des composés de départ : $\Delta_r H^\circ = -176\ \text{kJ/mol}$.
- B. Il est correct : « produits moins réactifs » s'applique à toute table d'enthalpies, quelle qu'elle soit.
- C. Il est faux : il faut additionner les trois enthalpies, ce qui donne $-2998\ \text{kJ/mol}$.
- D. Il est correct, car l'hydrogénation d'une triple liaison est endothermique.

**Réponse correcte** : A

**Feedback correct**
« Produits moins réactifs » vaut pour les enthalpies de **formation**. Les enthalpies de combustion se combinent à l'envers : $\Delta_r H^\circ = \sum \Delta_c H^\circ(\text{réactifs}) - \sum \Delta_c H^\circ(\text{produits}) = (-1301 - 286) - (-1411) = -176\ \text{kJ/mol}$. Le signe positif est aussi incohérent avec la chimie : l'hydrogénation d'une triple liaison est exothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La règle « produits moins réactifs » n'est valable que pour les enthalpies de formation ; pour des combustions, les composés brûlés sont ceux de départ.
- Si C : Additionner les trois valeurs revient à ne pas inverser l'équation de combustion de l'éthène, produit de la cible : le résultat $-2998$ n'a pas de sens.
- Si D : L'hydrogénation d'une liaison multiple est exothermique : on forme des liaisons C–H plus fortes, ce qui dégage de la chaleur.

**Référence manuel** : thermochimie-1-hess-combinaison

---
id: q-reaction-endothermique-symbo-app-004
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
Estimez $\Delta_r H^\circ$ de la décomposition $\ce{2 HCl(g) -> H2(g) + Cl2(g)}$ à partir des énergies de liaison : $D(\ce{H-Cl}) = 431$, $D(\ce{H-H}) = 436$, $D(\ce{Cl-Cl}) = 243$ (en $\text{kJ/mol}$).

**Options**
- A. $+183\ \text{kJ/mol}$
- B. $-183\ \text{kJ/mol}$
- C. $-248\ \text{kJ/mol}$
- D. $+1541\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
On rompt $2$ liaisons $\ce{H-Cl}$ ($+862$) et l'on forme une liaison $\ce{H-H}$ ($-436$) et une liaison $\ce{Cl-Cl}$ ($-243$) : $\Delta_r H^\circ = 862 - 436 - 243 = +183\ \text{kJ/mol}$. La réaction est endothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le signe est inversé : on a calculé « formées moins rompues ». Les liaisons rompues sont ici les plus fortes, la réaction absorbe de la chaleur.
- Si C : $-248$ ne compte qu'une seule liaison $\ce{H-Cl}$ rompue : l'équation en met en jeu deux.
- Si D : $+1541$ additionne toutes les énergies : les liaisons formées doivent être soustraites des liaisons rompues.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-endothermique-symbo-app-005
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La formation de l'éthène à partir de ses éléments, $\ce{2 C(graphite) + 2 H2(g) -> C2H4(g)}$, a pour enthalpie $\Delta_r H^\circ = +52\ \text{kJ/mol}$. Quelle énergie est absorbée lors de la formation de $7{,}0\ \text{g}$ d'éthène ($M = 28{,}0\ \text{g/mol}$) ?

**Options**
- A. $13{,}0\ \text{kJ}$
- B. $52\ \text{kJ}$
- C. $208\ \text{kJ}$
- D. $364\ \text{kJ}$

**Réponse correcte** : A

**Feedback correct**
$n = 7{,}0/28{,}0 = 0{,}25\ \text{mol}$ d'éthène, soit $0{,}25$ mole de réaction : $Q = 0{,}25 \times 52 = 13{,}0\ \text{kJ}$, absorbés puisque la réaction est endothermique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $52\ \text{kJ}$ est l'énergie absorbée pour **une mole** d'éthène : $7{,}0\ \text{g}$ n'en représentent qu'un quart.
- Si C : $208\ \text{kJ}$ divise par la quantité de matière au lieu de multiplier : une quantité plus petite qu'une mole absorbe moins que $52\ \text{kJ}$.
- Si D : $364\ \text{kJ}$ multiplie l'enthalpie molaire par la masse en grammes : il faut d'abord convertir la masse en quantité de matière.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-endothermique-symbo-app-006
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La formation de l'éthyne, $\ce{2 C(graphite) + H2(g) -> C2H2(g)}$, est endothermique : $\Delta_r H^\circ = +227\ \text{kJ/mol}$. Quelle masse d'éthyne ($M = 26{,}0\ \text{g/mol}$) peut-on former en absorbant $454\ \text{kJ}$ ?

**Options**
- A. $52{,}0\ \text{g}$
- B. $2{,}00\ \text{g}$
- C. $13{,}0\ \text{g}$
- D. $11804\ \text{g}$

**Réponse correcte** : A

**Feedback correct**
$n = 454/227 = 2{,}00\ \text{mol}$ d'éthyne, soit $m = 2{,}00 \times 26{,}0 = 52{,}0\ \text{g}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $2{,}00$ est la quantité de matière en moles : il reste à la convertir en masse avec $M = 26{,}0\ \text{g/mol}$.
- Si C : $13{,}0\ \text{g}$ résulte de l'inverse du rapport des énergies ($227/454$) : plus on absorbe d'énergie, plus on forme d'éthyne.
- Si D : $11804\ \text{g}$ multiplie l'énergie par la masse molaire au lieu de diviser d'abord par l'enthalpie molaire.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-symbo-app-004
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-04
statut: validated
---

**Question**
La réaction $\ce{H2(g) + Cl2(g) -> 2 HCl(g)}$ a pour enthalpie $\Delta_r H^\circ = -183\ \text{kJ/mol}$ (bilan des énergies de liaison : $436 + 243 - 2\times431$). Quelle chaleur est dégagée lorsque $7{,}09\ \text{g}$ de $\ce{Cl2}$ ($M = 70{,}9\ \text{g/mol}$) réagissent entièrement ?

**Options**
- A. $18{,}3\ \text{kJ}$
- B. $183\ \text{kJ}$
- C. $9{,}15\ \text{kJ}$
- D. $1297\ \text{kJ}$

**Réponse correcte** : A

**Feedback correct**
$n(\ce{Cl2}) = 7{,}09/70{,}9 = 0{,}100\ \text{mol}$ ; une mole de réaction consomme une mole de $\ce{Cl2}$ : $Q = 0{,}100 \times 183 = 18{,}3\ \text{kJ}$, dégagés.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $183\ \text{kJ}$ correspond à une mole de $\ce{Cl2}$ : $7{,}09\ \text{g}$ n'en représentent qu'un dixième.
- Si C : $9{,}15\ \text{kJ}$ ramène la chaleur à une mole de $\ce{HCl}$ ou divise par $2$ à tort : une mole de réaction consomme une mole de $\ce{Cl2}$.
- Si D : $1297\ \text{kJ}$ multiplie l'enthalpie par la masse en grammes : il faut d'abord calculer la quantité de matière.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-exothermique-symbo-ana-004
concept: reaction-exothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
Pour chauffer un échantillon, on hésite entre le méthanol ($\Delta_c H^\circ = -726\ \text{kJ/mol}$, $M = 32{,}0\ \text{g/mol}$) et l'éthanol ($\Delta_c H^\circ = -1367\ \text{kJ/mol}$, $M = 46{,}0\ \text{g/mol}$). Lequel dégage le plus de chaleur par **gramme** brûlé ?

**Options**
- A. L'éthanol : environ $29{,}7\ \text{kJ/g}$ contre $22{,}7\ \text{kJ/g}$ pour le méthanol.
- B. Le méthanol : environ $29{,}7\ \text{kJ/g}$ contre $22{,}7\ \text{kJ/g}$ pour l'éthanol.
- C. Le méthanol, car sa plus petite molécule fournit plus de moles par gramme, donc plus de chaleur.
- D. Aucun des deux : deux alcools dégagent la même chaleur par gramme.

**Réponse correcte** : A

**Feedback correct**
Par gramme : $726/32{,}0 \approx 22{,}7\ \text{kJ/g}$ pour le méthanol et $1367/46{,}0 \approx 29{,}7\ \text{kJ/g}$ pour l'éthanol. Le méthanol a certes plus de moles par gramme, mais chaque mole d'éthanol dégage presque deux fois plus de chaleur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les deux valeurs sont attribuées au mauvais alcool : $726/32{,}0$ donne le méthanol ($22{,}7$), $1367/46{,}0$ l'éthanol ($29{,}7$).
- Si C : Le nombre de moles par gramme n'est qu'un des deux facteurs : il faut le multiplier par la chaleur dégagée **par mole**, bien plus grande pour l'éthanol.
- Si D : Deux composés de même famille ont des $\Delta_c H^\circ$ et des masses molaires différentes : la chaleur par gramme n'a aucune raison d'être identique.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-enthalpie-de-formation-parti-com-001
concept: enthalpie-de-formation
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
date_validation: 2026-11-04
statut: validated
---

**Question**
L'éthène a une enthalpie de formation positive, $\Delta_f H^\circ(\ce{C2H4,g}) = +52\ \text{kJ/mol}$. Que traduit ce signe au niveau particulaire ?

**Options**
- A. Les liaisons à rompre dans les corps simples (graphite, $\ce{H2}$) coûtent plus d'énergie que n'en libère la formation des liaisons de l'éthène.
- B. Les liaisons formées dans l'éthène libèrent plus d'énergie que n'en coûte la rupture des liaisons des corps simples.
- C. La formation d'un composé gazeux absorbe toujours de la chaleur, quelles que soient les liaisons mises en jeu.
- D. Les corps simples ne contiennent aucune liaison : le signe vient seulement de la formation de l'éthène.

**Réponse correcte** : A

**Feedback correct**
$\Delta_f H^\circ > 0$ signifie que le bilan rupture/formation est défavorable : rompre le graphite (réseau de liaisons $\ce{C-C}$) et $\ce{H2}$ coûte plus que ce que libèrent les liaisons $\ce{C-H}$ et $\ce{C=C}$ de l'éthène. L'éthène est moins stable que ses éléments, au sens enthalpique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Ce raisonnement décrit le cas $\Delta_f H^\circ < 0$ (formation exothermique), pas celui d'un signe positif.
- Si C : L'état gazeux ne fixe pas le signe : le méthane gazeux a un $\Delta_f H^\circ$ négatif ($-75$).
- Si D : Le graphite et $\ce{H2}$ possèdent bien des liaisons (réseau covalent, liaison $\ce{H-H}$) : c'est leur rupture qui entre dans le bilan.

**Référence manuel** : thermochimie-1-formation-definition


<!-- LOT défis complémentaires, 04.11.2026 — to_fix -->

---
id: q-reaction-endothermique-symbo-eva-301
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-04
statut: validated
---

**Question**
Un élève lit $\Delta_f H^\circ(\ce{C2H2,g}) = +227\ \text{kJ/mol}$ et conclut : « Le signe positif prouve que l'éthyne est plus stable que le graphite et le dihydrogène dont il est issu, puisqu'il a fallu lui fournir de l'énergie. » Que penser de cette conclusion ?

**Options**
- A. Elle est fausse : l'énergie fournie est stockée dans l'éthyne, dont l'enthalpie est plus **élevée** que celle de ses éléments ; il est moins stable, enthalpiquement.
- B. Elle est correcte : plus on fournit d'énergie, plus le composé formé est stable.
- C. Elle est fausse : le signe positif indique que la réaction dégage de la chaleur.
- D. Elle est correcte, car une réaction endothermique est toujours spontanée.

**Réponse correcte** : A

**Feedback correct**
Une formation endothermique ($\Delta_f H^\circ > 0$) absorbe de l'énergie qui se retrouve dans le composé : son enthalpie est supérieure à celle des corps simples. Enthalpiquement, l'éthyne est donc **moins** stable que ses éléments, ce qui explique sa grande énergie de combustion.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'énergie fournie reste emmagasinée dans le composé formé, qui se retrouve plus riche en énergie, donc moins stable que ses éléments.
- Si C : Un $\Delta H^\circ$ positif correspond à une chaleur absorbée, pas dégagée : c'est la définition d'une réaction endothermique.
- Si D : Le caractère endothermique ne dit rien sur la spontanéité d'une réaction ; l'enthalpie seule ne permet pas de la prédire.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-reaction-endothermique-symbo-ana-302
concept: reaction-endothermique
sous-partie: 8A
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
On compare deux formations à partir des corps simples : $\ce{C2H4(g)}$ ($\Delta_f H^\circ = +52\ \text{kJ/mol}$, $M = 28{,}0\ \text{g/mol}$) et $\ce{C2H2(g)}$ ($\Delta_f H^\circ = +227\ \text{kJ/mol}$, $M = 26{,}0\ \text{g/mol}$). Laquelle absorbe le plus d'énergie par gramme de produit formé ?

**Options**
- A. La formation de l'éthyne : environ $8{,}7\ \text{kJ/g}$ contre $1{,}9\ \text{kJ/g}$ pour l'éthène.
- B. La formation de l'éthène : environ $8{,}7\ \text{kJ/g}$ contre $1{,}9\ \text{kJ/g}$ pour l'éthyne.
- C. La formation de l'éthène, car sa masse molaire plus grande lui fait absorber plus d'énergie.
- D. Les deux absorbent autant par gramme, car elles sont toutes deux endothermiques.

**Réponse correcte** : A

**Feedback correct**
Par gramme : $227/26{,}0 \approx 8{,}7\ \text{kJ/g}$ pour l'éthyne et $52/28{,}0 \approx 1{,}9\ \text{kJ/g}$ pour l'éthène. L'éthyne absorbe environ $4{,}7$ fois plus d'énergie par gramme.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les deux valeurs sont attribuées au mauvais composé : $227/26{,}0$ concerne l'éthyne, $52/28{,}0$ l'éthène.
- Si C : Une masse molaire plus grande répartit la même énergie sur plus de grammes : elle diminue l'énergie absorbée par gramme, elle ne l'augmente pas.
- Si D : Être endothermique ne fixe que le signe : l'énergie absorbée par mole ($52$ contre $227$) et la masse molaire diffèrent.

**Référence manuel** : thermochimie-1-exo-endo

---
id: q-enthalpie-de-dissolution-symbo-ana-301
concept: enthalpie-de-dissolution
sous-partie: 8C
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-04
statut: validated
---

**Question**
On dissout $0{,}10\ \text{mol}$ de sel dans $100\ \text{g}$ d'eau ($C_p = 4{,}18\ \text{J}\cdot\text{g}^{-1}\cdot\text{K}^{-1}$, solution assimilée à $100\ \text{g}$ d'eau, pertes négligées), au choix : $\ce{NH4NO3}$ ($+26\ \text{kJ/mol}$), $\ce{NH4Cl}$ ($+15\ \text{kJ/mol}$) ou $\ce{NaOH}$ ($-45\ \text{kJ/mol}$). Quel sel refroidit le plus l'eau, et de combien environ ?

**Options**
- A. $\ce{NH4NO3}$ : $\Delta T \approx -6{,}2\ \text{K}$ (contre $-3{,}6\ \text{K}$ pour $\ce{NH4Cl}$).
- B. $\ce{NaOH}$, car c'est lui qui a la plus grande valeur absolue d'enthalpie de dissolution.
- C. $\ce{NH4Cl}$ : $\Delta T \approx -6{,}2\ \text{K}$ (contre $-3{,}6\ \text{K}$ pour $\ce{NH4NO3}$).
- D. Aucune différence : $\ce{NH4NO3}$ et $\ce{NH4Cl}$ refroidissent autant, car les deux dissolutions sont endothermiques.

**Réponse correcte** : A

**Feedback correct**
Seules les dissolutions endothermiques refroidissent. $Q = 0{,}10 \times 26 = 2{,}6\ \text{kJ}$ pour $\ce{NH4NO3}$, soit $\Delta T = -2600/(100 \times 4{,}18) \approx -6{,}2\ \text{K}$ ; pour $\ce{NH4Cl}$, $1{,}5\ \text{kJ}$ donnent $\approx -3{,}6\ \text{K}$. $\ce{NaOH}$, exothermique, réchauffe l'eau.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La dissolution de $\ce{NaOH}$ est exothermique ($-45$) : elle réchauffe l'eau. Le signe compte autant que la valeur absolue.
- Si C : Les deux valeurs sont attribuées au mauvais sel : la plus grande enthalpie de dissolution ($+26$) donne le plus grand refroidissement.
- Si D : À même quantité de matière, l'énergie absorbée est proportionnelle à $\Delta H^\circ_\text{diss}$ : les deux sels n'ont pas le même effet.

**Référence manuel** : thermochimie-1-dissolution-calcul

