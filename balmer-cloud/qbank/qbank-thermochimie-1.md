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
<!-- Concepts : energie-de-liaison, energie-de-cohesion            -->
<!-- 9 questions obligatoires (7 + 2)                              -->
<!-- ============================================================ -->

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
date_validation: 2026-10-05
statut: validated
---

**Question**
Estimez $\Delta_r H^\circ$ de la réaction $\ce{H2(g) + Cl2(g) -> 2 HCl(g)}$ par les énergies de liaison, sachant $D_{\ce{H-H}}=436\ \text{kJ/mol}$, $D_{\ce{Cl-Cl}}=242\ \text{kJ/mol}$, $D_{\ce{H-Cl}}=431\ \text{kJ/mol}$.

**Options**
- A. $+1109\ \text{kJ/mol}$
- B. $-184\ \text{kJ/mol}$
- C. $+184\ \text{kJ/mol}$
- D. $-862\ \text{kJ/mol}$

**Réponse correcte** : B

**Feedback correct**
$E_\text{endo} = D_{\ce{H-H}}+D_{\ce{Cl-Cl}} = 436+242=678\ \text{kJ/mol}$ (rupture des réactifs) ; $E_\text{exo} = 2\times431=862\ \text{kJ/mol}$ (formation des 2 liaisons $\ce{H-Cl}$) ; $\Delta_r H^\circ = 678-862=-184\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la somme des trois énergies de liaison sans soustraction — le cycle $E_\text{endo}-E_\text{exo}$ exige bien une soustraction, pas une addition.
- Si B : C'est la bonne réponse.
- Si C : Le signe est inversé — $E_\text{exo}$ (862) est plus grand que $E_\text{endo}$ (678), donc le bilan net est négatif (exothermique), pas positif.
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
date_validation: 2026-10-05
statut: validated
---

**Question**
L'énergie de cohésion de l'acétone $\ce{(CH3)2CO}$ vaut $3923\ \text{kJ/mol}$. Sa structure comporte 6 liaisons $\ce{C-H}$ ($D=412$), 2 liaisons $\ce{C-C}$ ($D=348$) et 1 liaison $\ce{C=O}$. Quelle est la valeur de $D_{\ce{C=O}}$ ?

**Options**
- A. $755\ \text{kJ/mol}$
- B. $3923\ \text{kJ/mol}$
- C. $743\ \text{kJ/mol}$
- D. $3168\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$6\times412+2\times348 = 3168\ \text{kJ/mol}$ (contribution des liaisons C-H et C-C). Par différence avec la cohésion totale : $D_{\ce{C=O}} = 3923-3168=755\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'énergie de cohésion totale de la molécule, pas l'énergie de la seule liaison $\ce{C=O}$ recherchée.
- Si C : C'est la valeur moyenne tabulée pour $\ce{C=O}$ — ici, on cherche la valeur de $D_{\ce{C=O}}$ propre à l'acétone, déduite de la cohésion réelle, pas la moyenne du tableau.
- Si D : C'est la somme des liaisons $\ce{C-H}$ et $\ce{C-C}$ ($3168$) — il reste à la soustraire de la cohésion totale, pas à la donner comme résultat final.

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
date_validation: 2026-10-05
statut: validated
---

**Question**
La rupture d'une liaison $\ce{C=C}$ coûte $612\ \text{kJ/mol}$ et la formation d'une liaison $\ce{C-C}$ libère $348\ \text{kJ/mol}$. Quel est le bilan enthalpique de ce processus (rupture de la double liaison, formation de la simple liaison) ?

**Options**
- A. $+264\ \text{kJ/mol}$ (endothermique)
- B. $-264\ \text{kJ/mol}$ (exothermique)
- C. $+960\ \text{kJ/mol}$ (endothermique)
- D. $-960\ \text{kJ/mol}$ (exothermique)

**Réponse correcte** : A

**Feedback correct**
Bilan : $+612$ (rupture, coûte de l'énergie) $-348$ (formation, en libère) $=+264\ \text{kJ/mol}$, donc endothermique. C'est cohérent : une double liaison étant plus stable qu'une simple, sa rupture coûte davantage que ce que libère la formation d'une simple liaison.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Inverser le signe revient à traiter la rupture comme exothermique — c'est exactement l'inversion classique à éviter (rompre coûte toujours de l'énergie).
- Si C : $612+348=960$ additionne les deux valeurs au lieu de les soustraire — le bilan d'un processus rupture+formation se calcule par différence, pas par somme.
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
date_validation: 2026-10-05
statut: validated
---

**Question**
La rupture d'une liaison $\ce{O-H}$ coûte $463\ \text{kJ/mol}$ et la formation d'une liaison $\ce{C-O}$ libère $360\ \text{kJ/mol}$. Quel est le bilan enthalpique de ce processus seul ?

**Options**
- A. $+103\ \text{kJ/mol}$ (endothermique)
- B. $-103\ \text{kJ/mol}$ (exothermique)
- C. $+823\ \text{kJ/mol}$ (endothermique)
- D. $-823\ \text{kJ/mol}$ (exothermique)

**Réponse correcte** : A

**Feedback correct**
Bilan : $+463$ (rupture, coûte de l'énergie) $-360$ (formation, en libère) $=+103\ \text{kJ/mol}$, donc endothermique — ici, la liaison rompue est plus forte que la liaison formée, le bilan est donc positif.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Inverser le signe traite à tort la rupture comme exothermique.
- Si C : $463+360=823$ additionne au lieu de soustraire les deux contributions.
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
date_validation: 2026-10-05
statut: validated
---

**Question**
La méthode des énergies de liaison donne pour la combustion du propane $\Delta_r H^\circ\approx-1690\ \text{kJ/mol}$, alors que la valeur expérimentale est $-2220\ \text{kJ/mol}$. Pourquoi cette méthode est-elle structurellement moins précise que celle des enthalpies de formation ?

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
id: q-energie-de-cohesion-parti-com-001
concept: energie-de-cohesion
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: parti
type: com
date_validation: 2026-10-05
statut: validated
---

**Question**
Le $\ce{CO2}$ a une énergie de cohésion de $1486\ \text{kJ/mol}$ (2 liaisons $\ce{C=O}$) et l'eau $\ce{H2O}$ de $926\ \text{kJ/mol}$ (2 liaisons $\ce{O-H}$). Que signifie cette différence, au niveau particulaire ?

**Options**
- A. Il faut davantage d'énergie pour dissocier complètement une molécule de $\ce{CO2}$ en atomes isolés que pour dissocier une molécule de $\ce{H2O}$ — le $\ce{CO2}$ est globalement plus stable.
- B. Le $\ce{CO2}$ contient plus d'atomes que $\ce{H2O}$, ce qui explique entièrement l'écart.
- C. L'énergie de cohésion ne renseigne pas sur la stabilité d'une molécule, seulement sur sa masse.
- D. Le $\ce{H2O}$ est plus stable, car sa cohésion est une valeur plus petite donc plus facile à atteindre.

**Réponse correcte** : A

**Feedback correct**
L'énergie de cohésion mesure l'énergie totale nécessaire pour dissocier complètement une molécule en atomes isolés à l'état gazeux — plus elle est grande, plus la molécule est stable globalement. Le $\ce{CO2}$, avec $1486$ kJ/mol, est donc plus stable que $\ce{H2O}$, avec $926$ kJ/mol.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{CO2}$ (3 atomes) et $\ce{H2O}$ (3 atomes) ont le même nombre d'atomes — ce n'est pas le nombre d'atomes qui explique l'écart, mais la force des liaisons $\ce{C=O}$ par rapport aux liaisons $\ce{O-H}$.
- Si C : L'énergie de cohésion est précisément définie comme une mesure de la stabilité globale d'une molécule — pas de sa masse.
- Si D : Une cohésion plus petite signifie, au contraire, qu'il faut moins d'énergie pour dissocier la molécule — elle est donc moins stable, pas plus.

**Référence manuel** : thermochimie-1-energie-cohesion

---
id: q-energie-de-cohesion-symbo-app-001
concept: energie-de-cohesion
sous-partie: 8B
chapitre: thermochimie-1
niveau: OS
r1: symbo
type: app
date_validation: 2026-10-05
statut: validated
---

**Question**
Calculez l'énergie de cohésion du méthane $\ce{CH4}$, qui comporte 4 liaisons $\ce{C-H}$ ($D_{\ce{C-H}}=412\ \text{kJ/mol}$).

**Options**
- A. $412\ \text{kJ/mol}$
- B. $1648\ \text{kJ/mol}$
- C. $103\ \text{kJ/mol}$
- D. $824\ \text{kJ/mol}$

**Réponse correcte** : B

**Feedback correct**
L'énergie de cohésion est la somme de toutes les énergies de liaison de la molécule : $4\times412=1648\ \text{kJ/mol}$.

**Feedback incorrect**
- Si A : C'est l'énergie d'une seule liaison $\ce{C-H}$, pas la somme des 4 liaisons de la molécule entière.
- Si B : C'est la bonne réponse.
- Si C : $412/4=103$ divise au lieu de multiplier — la cohésion est une somme, pas une moyenne par liaison divisée par leur nombre.
- Si D : $412\times2=824$ ne compte que 2 liaisons sur les 4 réellement présentes dans $\ce{CH4}$.

**Référence manuel** : thermochimie-1-energie-cohesion

---

<!-- ============================================================ -->
<!-- LOT 3 — Enthalpie de formation standard                      -->
<!-- Concept : enthalpie-de-formation                              -->
<!-- 4 questions obligatoires (macro·com, symbo·com, symbo·app ×2) -->
<!-- ============================================================ -->

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
<!-- Concept : loi-de-hess                                          -->
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
id: q-loi-de-hess-symbo-com-002
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
id: q-loi-de-hess-symbo-app-001
concept: loi-de-hess
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
id: q-loi-de-hess-symbo-app-002
concept: loi-de-hess
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
id: q-loi-de-hess-symbo-ana-001
concept: loi-de-hess
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
date_validation: 2026-10-05
statut: validated
---

**Question**
La dissolution du sulfate de cuivre ($\ce{CuSO4(s) -> Cu^2+(aq) + SO4^2-(aq)}$) a pour enthalpie $\Delta H^\circ_\text{diss} = -66\ \text{kJ/mol}$ (exothermique). Quelle est l'enthalpie de la cristallisation inverse $\ce{Cu^2+(aq) + SO4^2-(aq) -> CuSO4(s)}$ ?

**Options**
- A. $+66\ \text{kJ/mol}$
- B. $-66\ \text{kJ/mol}$
- C. $-33\ \text{kJ/mol}$
- D. $0\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
Inverser une réaction change le signe de son enthalpie (loi de Hess) : si la dissolution est exothermique ($-66\ \text{kJ/mol}$), la cristallisation inverse est endothermique de même ampleur ($+66\ \text{kJ/mol}$) — c'est exactement ce mécanisme qu'exploitent les chaufferettes réutilisables, où l'inverse d'une dissolution endothermique est une cristallisation qui libère de la chaleur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $-66\ \text{kJ/mol}$ suppose à tort qu'inverser une réaction ne change rien — or le signe doit être inversé.
- Si C : $-33\ \text{kJ/mol}$ divise par erreur l'enthalpie par 2, alors qu'aucune opération d'échelle n'est demandée ici (seulement une inversion).
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
date_validation: 2026-10-05
statut: validated
---

**Question**
On dissout $2{,}675\ \text{g}$ de $\ce{NH4Cl}$ ($M = 53{,}5\ \text{g/mol}$) dans $50\ \text{g}$ d'eau. La température passe de $22{,}0\ ^\circ\text{C}$ à $17{,}2\ ^\circ\text{C}$ ($C_\text{cal}$ négligée). Calculez $\Delta H^\circ_\text{diss}$ de $\ce{NH4Cl}$.

**Options**
- A. $+20{,}1\ \text{kJ/mol}$
- B. $-20{,}1\ \text{kJ/mol}$
- C. $+0{,}4\ \text{kJ/mol}$
- D. $+20\ 064\ \text{kJ/mol}$

**Réponse correcte** : A

**Feedback correct**
$n(\ce{NH4Cl}) = 2{,}675/53{,}5 = 0{,}0500\ \text{mol}$ ; $Q_\text{eau} = 50\times4{,}18\times(-4{,}8) = -1003{,}2\ \text{J} = -1{,}0032\ \text{kJ}$ ; $Q_\text{réaction} = +1{,}0032\ \text{kJ}$ (la solution se refroidit, donc la dissolution absorbe de la chaleur) ; $\Delta H^\circ_\text{diss} = 1{,}0032/0{,}0500 \approx +20{,}1\ \text{kJ/mol}$.

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
