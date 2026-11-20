# Banque de questions validées — Chapitre 03
# Liaisons intermoléculaires
# Slug : liaisons-intermoleculaires

_Projet-Balmer / Balmer-Cloud — Généré le 2026-09-02 — axe Type migré vers Anderson & Krathwohl (2001) le 26.09.2026 (chapitre pilote)_
_Couverture minimale : voir `./check-matrice-cloud.sh liaisons-intermoleculaires` (matrice concepts/) — jamais à jour ici, toujours calculé (32/32 min au 26.09.2026)_

---

<!-- LÉGENDE
Niveau R1 : macro = macroscopique | parti = particulaire | symbo = symbolique
Type      : sou = se souvenir | com = comprendre | app = appliquer | ana = analyser | eva = évaluer
            (Anderson & Krathwohl, 2001 — Créer exclu du format QCM ; voir Charte_Balmer-Cloud.md §4.3)
Statut    : validated | to_fix
-->

---

<!-- ============================================================ -->
<!-- CONCEPT : distinction-intra-inter — Les deux familles de liaisons : primaires et secondaires -->
<!-- 4 cellules obligatoires (7 questions) : macro·com(x2), parti·com(x2), parti·ana(x2), symbo·ana -->
<!-- ============================================================ -->

---
id: q-distinction-intra-inter-macro-com-001
concept: distinction-intra-inter
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
Après évaporation de l'eau, les molécules $\ce{H2O}$ en phase gazeuse sont-elles chimiquement différentes de celles en phase liquide ?

**Options**
- A. Non — seules des liaisons intermoléculaires (les ponts hydrogène) ont été rompues ; les molécules $\ce{H2O}$ restent intactes.
- B. Oui — les liaisons $\ce{O-H}$ à l'intérieur de chaque molécule ont été rompues lors de l'évaporation.
- C. Non — mais chaque molécule d'eau a perdu un atome d'hydrogène pendant le changement d'état.
- D. Oui — l'évaporation transforme $\ce{H2O}$ en $\ce{H2}$ et $\ce{O2}$ séparés.

**Réponse correcte** : A

**Feedback correct**
L'évaporation ne rompt que les ponts hydrogène intermoléculaires (~20 kJ/mol) — pas les liaisons $\ce{O-H}$ intramoléculaires (~460 kJ/mol), qui restent intactes. C'est une transformation physique, pas chimique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse de ce qui se passe — les liaisons $\ce{O-H}$ intramoléculaires, bien plus énergétiques (~460 kJ/mol), ne sont pas concernées par un simple changement d'état physique.
- Si C : Rien n'indique une perte d'atome — un changement d'état est une transformation physique, la formule chimique de chaque molécule reste inchangée.
- Si D : Ce serait une transformation chimique (électrolyse ou décomposition), bien plus énergétique, d'une tout autre nature qu'une simple évaporation.

**Référence manuel** : liaisons-intermoleculaires-familles-liaisons

---
id: q-distinction-intra-inter-macro-com-002
concept: distinction-intra-inter
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
misconception: distinction-intra-inter--ebullition-rompt-intramoleculaire
date_validation: 2026-09-08
statut: validated
---

**Question**
Après ébullition du méthanol liquide $\ce{CH3OH}$, les molécules en phase gazeuse sont-elles chimiquement différentes de celles en phase liquide ?

**Options**
- A. Non — seuls des ponts hydrogène intermoléculaires ont été rompus ; les liaisons $\ce{O-H}$ et $\ce{C-H}$ à l'intérieur de chaque molécule restent intactes.
- B. Oui — la liaison $\ce{O-H}$ à l'intérieur de chaque molécule a été rompue lors de l'ébullition.
- C. Non — mais chaque molécule de méthanol a perdu un atome d'hydrogène pendant le changement d'état.
- D. Oui — l'ébullition transforme $\ce{CH3OH}$ en $\ce{CH4}$ et $\ce{H2O}$ séparés.

**Réponse correcte** : A

**Feedback correct**
L'ébullition ne rompt que les ponts hydrogène intermoléculaires entre molécules de méthanol — pas la liaison $\ce{O-H}$ intramoléculaire, bien plus énergétique, qui reste intacte. C'est une transformation physique, pas chimique — exactement la conception que Col & Taylor (2002, cité dans Gültepe 2021) documentent comme erreur récurrente : croire que l'ébullition romprait les liaisons intramoléculaires.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse de ce qui se passe — la liaison $\ce{O-H}$ intramoléculaire, bien plus énergétique qu'un pont hydrogène, n'est pas concernée par un simple changement d'état physique. Cette confusion est documentée par Col & Taylor (2002).
- Si C : Rien n'indique une perte d'atome — un changement d'état est une transformation physique, la formule chimique de chaque molécule reste inchangée.
- Si D : Ce serait une transformation chimique (décomposition), bien plus énergétique, d'une tout autre nature qu'une simple ébullition.

**Référence manuel** : liaisons-intermoleculaires-familles-liaisons

---
id: q-distinction-intra-inter-parti-com-001
concept: distinction-intra-inter
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
Un pont hydrogène entre deux molécules d'eau voisines se situe-t-il à l'intérieur d'une molécule $\ce{H2O}$ ou entre deux molécules $\ce{H2O}$ distinctes ?

**Options**
- A. Entre deux molécules $\ce{H2O}$ distinctes — c'est une interaction intermoléculaire.
- B. À l'intérieur d'une seule molécule $\ce{H2O}$ — c'est une interaction intramoléculaire.
- C. Cela dépend de la température : intramoléculaire à basse température, intermoléculaire à haute température.
- D. Ni l'un ni l'autre — le pont hydrogène ne concerne que des atomes d'hydrogène isolés, hors de toute molécule.

**Réponse correcte** : A

**Feedback correct**
Toute liaison intermoléculaire, y compris le pont hydrogène, se forme entre deux molécules distinctes — jamais à l'intérieur d'une seule molécule. Ce sont les liaisons intramoléculaires (covalentes, ioniques, métalliques) qui existent à l'intérieur d'une molécule ou d'un cristal.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est une confusion fréquente et documentée en recherche — le pont hydrogène est justement défini comme une interaction *entre* deux molécules, pas une liaison interne comme $\ce{O-H}$.
- Si C : La température ne change pas la nature de l'interaction — seulement son intensité relative face à l'agitation thermique.
- Si D : Le pont hydrogène implique un atome d'hydrogène engagé dans une liaison covalente avec un atome électronégatif, pas un atome isolé.

**Référence manuel** : liaisons-intermoleculaires-familles-liaisons

---
id: q-distinction-intra-inter-parti-com-002
concept: distinction-intra-inter
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: com
misconception: distinction-intra-inter--confusion-intra-intermoleculaire
date_validation: 2026-09-08
statut: validated
---

**Question**
Une interaction de Keesom entre deux molécules de $\ce{HCl}$ voisines se situe-t-elle à l'intérieur d'une molécule $\ce{HCl}$ ou entre deux molécules $\ce{HCl}$ distinctes ?

**Options**
- A. Entre deux molécules $\ce{HCl}$ distinctes — c'est une interaction intermoléculaire.
- B. À l'intérieur d'une seule molécule $\ce{HCl}$ — c'est une interaction intramoléculaire.
- C. Cela dépend de la pression : intramoléculaire à haute pression, intermoléculaire à basse pression.
- D. Ni l'un ni l'autre — l'interaction de Keesom ne concerne que le noyau de chlore, indépendamment de la molécule.

**Réponse correcte** : A

**Feedback correct**
Toute liaison intermoléculaire, y compris l'interaction de Keesom, se forme entre deux molécules distinctes — jamais à l'intérieur d'une seule molécule. Ce sont les liaisons intramoléculaires (ici, la liaison covalente $\ce{H-Cl}$) qui existent à l'intérieur d'une molécule.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est une confusion fréquente et documentée en recherche (Cooper, Williams & Underwood, 2015 : au moins 55 % des étudiants localisent à tort chaque force intermoléculaire à l'intérieur d'une seule molécule) — l'interaction de Keesom est justement définie entre deux molécules polaires distinctes, pas une liaison interne comme $\ce{H-Cl}$.
- Si C : La pression ne change pas la nature de l'interaction — seulement la distance moyenne entre les molécules et donc son intensité relative.
- Si D : L'interaction de Keesom résulte de l'orientation de dipôles moléculaires entiers ($\delta^+$ face à $\delta^-$), pas d'une interaction limitée aux seuls noyaux.

**Référence manuel** : liaisons-intermoleculaires-familles-liaisons

---
id: q-distinction-intra-inter-parti-ana-001
concept: distinction-intra-inter
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: ana
date_validation: 2026-09-02
statut: validated
---

**Question**
Quelle(s) interaction(s) intermoléculaire(s) peuvent exister entre deux molécules d'ammoniac $\ce{NH3}$ (molécule polaire, avec des hydrogènes liés à l'azote) ?

**Options**
- A. London, Keesom et pont hydrogène simultanément.
- B. Pont hydrogène uniquement.
- C. London uniquement.
- D. Keesom uniquement.

**Réponse correcte** : A

**Feedback correct**
$\ce{NH3}$ est polaire (Keesom), possède des hydrogènes liés à $\ce{N}$ — l'un des trois éléments qui autorisent le pont hydrogène — et, comme toute molécule, elle est aussi soumise à London. Les trois interactions coexistent ; le principe de superposition impose de toutes les identifier, même si l'une d'elles domine ici (le pont hydrogène).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le pont hydrogène domine, mais Keesom et London sont aussi présentes — une molécule ne "choisit" pas son interaction, elle les subit toutes simultanément.
- Si C : London seule ignorerait le caractère polaire de $\ce{NH3}$ (Keesom) et sa capacité à former des ponts hydrogène.
- Si D : Keesom seule ignorerait le pont hydrogène, plus intense ici, et la force de London, toujours présente.

**Référence manuel** : liaisons-intermoleculaires-familles-liaisons

---
id: q-distinction-intra-inter-parti-ana-002
concept: distinction-intra-inter
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: ana
date_validation: 2026-09-08
statut: validated
---

**Question**
Quelle(s) interaction(s) intermoléculaire(s) peuvent exister entre un ion $\ce{Cl-}$ et une molécule d'eau $\ce{H2O}$ voisine ?

**Options**
- A. Ion–dipôle uniquement — Keesom et pont hydrogène exigent deux molécules neutres, pas un ion.
- B. Ion–dipôle, Keesom et pont hydrogène simultanément, comme pour deux molécules neutres.
- C. London uniquement, car $\ce{Cl-}$ est un ion monoatomique sans dipôle propre.
- D. Keesom uniquement, car $\ce{H2O}$ est polaire.

**Réponse correcte** : A

**Feedback correct**
Le pont hydrogène et l'interaction de Keesom se définissent tous deux entre deux molécules neutres — dès qu'un des deux partenaires est un ion, c'est la catégorie ion–dipôle (permanent, ici, car $\ce{H2O}$ est polaire) qui s'applique, remplaçant les catégories propres aux paires de molécules neutres. Reconnaître quelles catégories s'appliquent selon la nature des partenaires est le cœur du principe de superposition.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Keesom et pont hydrogène exigent deux molécules neutres polaires — $\ce{Cl-}$ est un ion, pas une molécule neutre : ces deux catégories ne s'appliquent pas ici, seule l'interaction ion–dipôle le fait.
- Si C : London seule ignorerait la polarité de $\ce{H2O}$ et la charge de $\ce{Cl-}$ — l'interaction ion–dipôle, bien plus intense, domine cette paire.
- Si D : Keesom exige deux molécules neutres polaires — $\ce{Cl-}$ étant un ion, c'est l'interaction ion–dipôle (permanent) qui s'applique, pas Keesom.

**Référence manuel** : liaisons-intermoleculaires-familles-liaisons

---
id: q-distinction-intra-inter-symbo-ana-001
concept: distinction-intra-inter
chapitre: liaisons-intermoleculaires
niveau: DF
r1: symbo
type: ana
date_validation: 2026-09-17
statut: validated
---

**Question**
Dans un échantillon d'éthanol liquide $\ce{CH3CH2OH}$, lesquelles des interactions suivantes sont intermoléculaires (entre deux molécules distinctes) ?

**Options**
- A. La liaison covalente $\ce{C-C}$ au sein d'une molécule.
- B. Le pont hydrogène entre le $\ce{H}$ du groupe $\ce{-OH}$ d'une molécule et le doublet non-liant de l'oxygène d'une molécule voisine.
- C. La force de London entre les chaînes carbonées de deux molécules voisines.
- D. La liaison covalente polarisée $\ce{O-H}$ au sein d'une molécule.

**Réponse correcte** : B, C

**Feedback correct**
Une interaction est intermoléculaire seulement si elle relie deux molécules distinctes. Le pont hydrogène (B) et la force de London (C) s'exercent toujours entre molécules voisines, jamais à l'intérieur d'une seule molécule — contrairement aux liaisons covalentes $\ce{C-C}$ et $\ce{O-H}$ (A, D), qui structurent la molécule elle-même.

**Feedback incorrect**
- Si A : La liaison $\ce{C-C}$ est une liaison covalente intramoléculaire — elle assure la cohésion interne de la molécule, elle ne relie pas deux molécules entre elles.
- Si B : C'est la bonne réponse.
- Si C : C'est la bonne réponse.
- Si D : Comme la liaison $\ce{C-C}$, la liaison $\ce{O-H}$ est covalente et intramoléculaire — c'est elle qui rend possible le pont hydrogène (en polarisant l'hydrogène), mais elle n'est pas elle-même ce pont hydrogène intermoléculaire.

**Référence manuel** : liaisons-intermoleculaires-familles-liaisons

---

<!-- ============================================================ -->
<!-- CONCEPT : ion-dipole — Interaction ion–dipôle permanent et induit, solvatation -->
<!-- 4 cellules obligatoires (5 questions) : macro·com, parti·com(x2), parti·app, symbo·sou -->
<!-- ============================================================ -->

---
id: q-ion-dipole-macro-com-001
concept: ion-dipole
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
Pourquoi le chlorure de sodium $\ce{NaCl}$ se dissout-il dans l'eau mais reste-t-il pratiquement insoluble dans l'hexane (solvant apolaire) ?

**Options**
- A. Dans l'eau, les interactions ion–dipôle permanent sont assez fortes pour arracher les ions au cristal ; dans l'hexane, seules de faibles interactions ion–dipôle induit sont possibles.
- B. $\ce{NaCl}$ ne se dissout dans aucun solvant, quelle que soit sa polarité.
- C. L'hexane dissout mieux $\ce{NaCl}$ que l'eau, car les solvants apolaires dissolvent toujours mieux les sels.
- D. La solubilité de $\ce{NaCl}$ ne dépend pas de la polarité du solvant, seulement de sa température.

**Réponse correcte** : A

**Feedback correct**
L'eau, polaire, développe des interactions ion–dipôle permanent intenses (40–600 kJ/mol) qui compensent l'énergie de réseau du cristal ionique. L'hexane, apolaire, ne peut établir que de très faibles interactions ion–dipôle induit — insuffisantes pour arracher les ions.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{NaCl}$ se dissout très bien dans l'eau (35,9 g/100 mL) — l'affirmation est fausse.
- Si C : C'est l'inverse : $\ce{NaCl}$ affiche une solubilité inférieure à 0,001 g/100 mL dans l'hexane, contre 35,9 g/100 mL dans l'eau.
- Si D : La polarité du solvant est le facteur déterminant démontré par le manuel — la température joue un rôle secondaire.

**Référence manuel** : liaisons-intermoleculaires-ion-dipole

---
id: q-ion-dipole-parti-com-001
concept: ion-dipole
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
Dans la sphère de solvatation d'un ion $\ce{Cl-}$ dissous dans l'eau, comment les molécules d'eau s'orientent-elles ?

**Options**
- A. Les hydrogènes ($\delta+$) des molécules d'eau pointent vers l'ion $\ce{Cl-}$.
- B. L'oxygène ($\delta-$) de chaque molécule d'eau pointe vers l'ion $\ce{Cl-}$.
- C. Les molécules d'eau s'orientent aléatoirement, sans lien avec la charge de l'ion.
- D. Les molécules d'eau perdent leur polarité au contact de l'ion $\ce{Cl-}$.

**Réponse correcte** : A

**Feedback correct**
$\ce{Cl-}$ est un anion, chargé négativement : il attire la partie $\delta+$ de la molécule d'eau, c'est-à-dire les hydrogènes — c'est l'interaction ion–dipôle qui gouverne cette orientation.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse — l'oxygène ($\delta-$) s'oriente vers un cation comme $\ce{Na+}$, pas vers un anion comme $\ce{Cl-}$.
- Si C : L'orientation n'est pas aléatoire : c'est précisément l'attraction électrostatique ion–dipôle qui impose une orientation systématique.
- Si D : Les molécules d'eau restent polaires — c'est justement leur polarité qui permet l'interaction ion–dipôle et la solvatation.

**Référence manuel** : liaisons-intermoleculaires-ion-dipole

---
id: q-ion-dipole-parti-com-002
concept: ion-dipole
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: com
misconception: ion-dipole--ions-conservent-proprietes-element-neutre
date_validation: 2026-09-08
statut: validated
---

**Question**
Une solution aqueuse de chlorure de lithium $\ce{LiCl}$ conduit le courant électrique. Quelle est la meilleure explication à l'échelle particulaire ?

**Options**
- A. Les ions $\ce{Li+(aq)}$ et $\ce{Cl-(aq)}$, mobiles et chargés, transportent le courant — ils n'ont plus les propriétés du lithium métallique ni du dichlore gazeux dont ils dérivent.
- B. Du lithium métallique, dissous sous forme de petits fragments, conduit le courant comme un fil métallique.
- C. Les ions se recombinent en molécules neutres $\ce{LiCl}$ dissoutes, qui conduisent le courant par elles-mêmes.
- D. L'eau seule conduit le courant ; la présence de $\ce{LiCl}$ n'y change rien.

**Réponse correcte** : A

**Feedback correct**
La dissolution sépare $\ce{LiCl}$ en ions $\ce{Li+}$ et $\ce{Cl-}$ indépendants, solvatés par les molécules d'eau. Ce sont ces ions mobiles et chargés — pas du métal, pas des molécules neutres — qui transportent le courant électrique en solution.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est exactement la conception documentée par Naah & Sanger (2012) : 16 à 35 % des élèves interrogés attribuent aux ions dissous les propriétés de l'élément métallique neutre dont ils dérivent. Or $\ce{Li+(aq)}$ n'est pas du lithium métallique — c'est un ion, chargé et solvaté, aux propriétés très différentes du métal.
- Si C : Les ions restent indépendants et libres en solution — ils ne se recombinent pas en une molécule neutre $\ce{LiCl}$ dissoute (ce serait revenir au cadre « moléculaire » déjà documenté par Taber pour le solide, appliqué ici à tort à la solution).
- Si D : L'eau pure est un très mauvais conducteur — ce sont les ions mobiles apportés par $\ce{LiCl}$ qui rendent la solution conductrice.

**Référence manuel** : liaisons-intermoleculaires-ion-dipole

---
id: q-ion-dipole-parti-app-001
concept: ion-dipole
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: app
date_validation: 2026-09-02
statut: validated
---

**Question**
Les ions $\ce{Ca^{2+}}$ et $\ce{Na+}$ sont tous deux solvatés par l'eau. Lequel interagit le plus fortement avec les molécules d'eau environnantes, et pourquoi ?

**Options**
- A. $\ce{Ca^{2+}}$, car sa charge double génère un champ électrique local plus intense.
- B. $\ce{Na+}$, car il est plus petit que $\ce{Ca^{2+}}$.
- C. Les deux interagissent avec la même intensité, la charge ne jouant aucun rôle.
- D. $\ce{Ca^{2+}}$, car il est moins électronégatif que $\ce{Na+}$.

**Réponse correcte** : A

**Feedback correct**
À taille comparable, une charge plus élevée génère un champ électrique local plus intense, donc une interaction ion–dipôle plus forte — c'est ce qui explique, par exemple, que $\ce{CaCl2}$ soit bien plus soluble que $\ce{NaCl}$ dans l'éthanol (facteur ~400).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La taille joue un rôle via la distance, mais ce n'est pas le facteur invoqué ici — $\ce{Ca^{2+}}$ est en réalité plus petit que $\ce{Na+}$, ce n'est pas ce qui explique l'écart de solubilité observé.
- Si C : La charge de l'ion est justement le facteur déterminant démontré par le manuel (comparaison $\ce{NaCl}$/$\ce{CaCl2}$ dans l'éthanol).
- Si D : L'électronégativité concerne la répartition des électrons dans une liaison covalente — elle n'est pas le facteur pertinent pour comparer l'intensité d'une interaction ion–dipôle entre deux ions.

**Référence manuel** : liaisons-intermoleculaires-ion-dipole

---
id: q-ion-dipole-symbo-sou-001
concept: ion-dipole
chapitre: liaisons-intermoleculaires
niveau: DF
r1: symbo
type: sou
date_validation: 2026-09-02
statut: validated
---

**Question**
Comment note-t-on symboliquement un ion sodium dissous (solvaté) dans l'eau ?

**Options**
- A. $\ce{Na+(aq)}$
- B. $\ce{Na+(s)}$
- C. $\ce{Na(aq)}$
- D. $\ce{Na+(l)}$

**Réponse correcte** : A

**Feedback correct**
La notation $\text{(aq)}$ indique une espèce dissoute en solution aqueuse — $\ce{Na+(aq)}$ désigne l'ion sodium entouré de sa sphère de solvatation, distinct du sodium métallique solide $\ce{Na(s)}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\text{(s)}$ désigne un solide — $\ce{Na+}$ dissous n'est pas à l'état solide.
- Si C : La charge $+$ doit être précisée — $\ce{Na}$ sans charge désignerait un atome neutre, pas l'ion réellement présent en solution.
- Si D : $\text{(l)}$ désigne un liquide pur, pas une espèce dissoute en solution.

**Référence manuel** : liaisons-intermoleculaires-ion-dipole

---

<!-- ============================================================ -->
<!-- CONCEPT : pont-hydrogene — Le pont hydrogène                 -->
<!-- 6 cellules obligatoires (8 questions) : macro·com(x2), parti·com, parti·app, parti·ana, symbo·sou(x2), symbo·ana -->
<!-- ============================================================ -->

---
id: q-pont-hydrogene-macro-com-001
concept: pont-hydrogene
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
L'acide fluorhydrique $\ce{HF}$ ($T_\text{éb} = 19{,}5\ ^\circ\text{C}$) bout à une température bien plus élevée que $\ce{HCl}$ ($T_\text{éb} = -85\ ^\circ\text{C}$), alors que $\ce{HF}$ a une masse molaire plus faible. Quelle est la meilleure explication ?

**Options**
- A. $\ce{HF}$ forme des ponts hydrogène entre ses molécules, contrairement à $\ce{HCl}$ — cette interaction supplémentaire augmente fortement la cohésion intermoléculaire.
- B. $\ce{HF}$ est plus lourd que $\ce{HCl}$, ce qui explique sa température d'ébullition plus élevée.
- C. $\ce{HF}$ est un solide à température ambiante, contrairement à $\ce{HCl}$.
- D. La température d'ébullition ne dépend pas du type de liaison intermoléculaire.

**Réponse correcte** : A

**Feedback correct**
Le fluor, très électronégatif, permet à $\ce{HF}$ de former des ponts hydrogène ($\ce{F-H\cdots F}$) — une interaction bien plus intense que les seules forces de London présentes dans $\ce{HCl}$, ce qui explique l'écart malgré une masse molaire inférieure.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est faux — $\ce{HF}$ ($20\ \text{g/mol}$) est plus léger que $\ce{HCl}$ ($36{,}5\ \text{g/mol}$), donc l'argument de la masse va dans le sens contraire de l'observation.
- Si C : Les deux substances bouillent à basse température ($\ce{HF}$ à $19{,}5\ ^\circ\text{C}$) — $\ce{HF}$ n'est pas solide à température ambiante.
- Si D : Le type de liaison intermoléculaire est justement le facteur déterminant illustré par cette comparaison.

**Référence manuel** : liaisons-intermoleculaires-pont-hydrogene

---
id: q-pont-hydrogene-macro-com-002
concept: pont-hydrogene
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-09-08
statut: validated
---

**Question**
L'ammoniac $\ce{NH3}$ ($T_\text{éb} = -33\ ^\circ\text{C}$) bout à une température bien plus élevée que la phosphine $\ce{PH3}$ ($T_\text{éb} = -87{,}7\ ^\circ\text{C}$), alors que $\ce{NH3}$ a une masse molaire plus faible. Quelle est la meilleure explication ?

**Options**
- A. $\ce{NH3}$ forme des ponts hydrogène entre ses molécules (hydrogène lié à l'azote, très électronégatif), contrairement à $\ce{PH3}$ (hydrogène lié au phosphore, pas assez électronégatif) — cette interaction supplémentaire augmente fortement la cohésion intermoléculaire.
- B. $\ce{NH3}$ est plus lourd que $\ce{PH3}$, ce qui explique sa température d'ébullition plus élevée.
- C. $\ce{NH3}$ est un solide à température ambiante, contrairement à $\ce{PH3}$.
- D. La température d'ébullition ne dépend pas du type de liaison intermoléculaire.

**Réponse correcte** : A

**Feedback correct**
L'azote, très électronégatif, permet à $\ce{NH3}$ de former des ponts hydrogène ($\ce{N-H\cdots N}$) — une interaction bien plus intense que les seules forces de London et de Keesom présentes dans $\ce{PH3}$ (le phosphore n'est pas assez électronégatif pour autoriser le pont hydrogène), ce qui explique l'écart malgré une masse molaire inférieure. Henderleiter et al. (2001) documentent que même des étudiants avancés échouent à mobiliser correctement ce raisonnement pour prédire une propriété physique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est faux — $\ce{NH3}$ ($17{,}0\ \text{g/mol}$) est plus léger que $\ce{PH3}$ ($34{,}0\ \text{g/mol}$), donc l'argument de la masse va dans le sens contraire de l'observation.
- Si C : Les deux substances bouillent à basse température ($\ce{NH3}$ à $-33\ ^\circ\text{C}$) — $\ce{NH3}$ n'est pas solide à température ambiante.
- Si D : Le type de liaison intermoléculaire est justement le facteur déterminant illustré par cette comparaison.

**Référence manuel** : liaisons-intermoleculaires-pont-hydrogene

---
id: q-pont-hydrogene-parti-com-001
concept: pont-hydrogene
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
Pourquoi le méthane $\ce{CH4}$ ne forme-t-il aucun pont hydrogène, alors que ses quatre liaisons $\ce{C-H}$ pourraient sembler s'y prêter ?

**Options**
- A. Le carbone n'est pas assez électronégatif pour rendre l'hydrogène suffisamment $\delta+$ — seuls $\ce{N}$, $\ce{O}$ et $\ce{F}$ le permettent.
- B. Le méthane ne possède pas d'atomes d'hydrogène.
- C. Le méthane est une molécule trop grosse pour former des ponts hydrogène.
- D. Le méthane ne possède aucun doublet non-liant, ce qui empêche tout pont hydrogène.

**Réponse correcte** : A

**Feedback correct**
Un pont hydrogène exige un hydrogène lié à un atome très électronégatif et de petite taille — exclusivement $\ce{N}$, $\ce{O}$ ou $\ce{F}$. Le carbone, bien moins électronégatif, ne polarise pas assez la liaison $\ce{C-H}$ pour générer la charge $\delta+$ nécessaire.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{CH4}$ possède quatre atomes d'hydrogène — ce n'est pas leur absence qui est en cause, mais leur liaison à un atome ($\ce{C}$) pas assez électronégatif.
- Si C : La taille de la molécule n'est pas le critère — c'est la nature de l'atome auquel l'hydrogène est lié ($\ce{N}$, $\ce{O}$ ou $\ce{F}$) qui détermine la possibilité d'un pont hydrogène.
- Si D : Le carbone dans $\ce{CH4}$ n'a en effet pas de doublet non-liant à offrir comme accepteur, mais la raison première reste que l'hydrogène lié au carbone n'est pas assez $\delta+$ pour être un bon donneur non plus.

**Référence manuel** : liaisons-intermoleculaires-pont-hydrogene

---
id: q-pont-hydrogene-parti-ana-001
concept: pont-hydrogene
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: ana
misconception: pont-hydrogene--regle-nof-appliquee-rigidement
date_validation: 2026-09-08
statut: validated
---

**Question**
Le fluorométhane $\ce{CH3F}$ contient un atome de fluor, très électronégatif. Peut-il donner un pont hydrogène à une molécule d'eau voisine ?

**Options**
- A. Non — ses hydrogènes sont tous liés au carbone, pas au fluor ; seul un hydrogène directement lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ peut être donneur de pont hydrogène.
- B. Oui — la seule présence d'un atome de fluor dans la molécule suffit à autoriser un pont hydrogène, quel que soit l'atome auquel les hydrogènes sont liés.
- C. Non, car le fluor ne peut jamais participer à un pont hydrogène, ni comme donneur ni comme accepteur.
- D. Oui, car le carbone est indirectement assez électronégatif via sa liaison avec le fluor pour rendre les hydrogènes donneurs.

**Réponse correcte** : A

**Feedback correct**
Un pont hydrogène donneur exige un hydrogène *directement* lié par covalence à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ — pas seulement la présence de l'un de ces atomes quelque part dans la molécule. Dans $\ce{CH3F}$, les trois hydrogènes sont liés au carbone : aucun n'est assez $\delta^+$ pour donner un pont hydrogène. Le fluor, lui, porte des doublets non liants et peut accepter un pont hydrogène d'une autre molécule.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Ce n'est pas la simple présence d'un atome $\ce{N}$, $\ce{O}$ ou $\ce{F}$ dans la molécule qui compte, mais bien la liaison directe $\ce{H-N}$, $\ce{H-O}$ ou $\ce{H-F}$. Ici, les hydrogènes de $\ce{CH3F}$ sont liés au carbone, pas au fluor — une application trop rigide de la règle NOF, à l'envers, documentée par Nahum et al. (2006).
- Si C : Le fluor de $\ce{CH3F}$ porte des doublets non liants et peut donc accepter un pont hydrogène d'une autre molécule (par exemple d'une molécule d'eau) — seule sa fonction de donneur est exclue ici, pas sa fonction d'accepteur.
- Si D : L'électronégativité ne se transmet pas indirectement à travers une liaison $\ce{C-F}$ jusqu'aux hydrogènes portés par le même carbone — seule une liaison directe $\ce{H-N}$/$\ce{O}$/$\ce{F}$ rend l'hydrogène suffisamment $\delta^+$ pour être donneur.

**Référence manuel** : liaisons-intermoleculaires-pont-hydrogene

---
id: q-pont-hydrogene-parti-app-001
concept: pont-hydrogene
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: app
date_validation: 2026-09-02
statut: validated
---

**Question**
L'éther diméthylique $\ce{CH3OCH3}$ peut-il former des ponts hydrogène avec l'eau ?

**Options**
- A. Oui, mais seulement comme accepteur — il n'a pas d'hydrogène lié à $\ce{O}$, $\ce{N}$ ou $\ce{F}$ pour être donneur.
- B. Non, il ne peut ni donner ni accepter de pont hydrogène.
- C. Oui, il peut à la fois donner et accepter des ponts hydrogène, comme l'eau.
- D. Cela dépend uniquement de la température de la solution.

**Réponse correcte** : A

**Feedback correct**
L'oxygène de $\ce{CH3OCH3}$ porte des doublets non-liants et peut donc accepter un pont hydrogène — par exemple avec un $\ce{H}$ de l'eau. Mais tous ses hydrogènes sont liés à des atomes de carbone, donc aucun n'est assez $\delta+$ pour être donneur.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'oxygène de l'éther peut bien accepter un pont hydrogène — l'affirmation est trop catégorique dans le sens négatif.
- Si C : Contrairement à l'eau ou au méthanol, l'éther ne peut pas donner de pont hydrogène — il n'a pas de $\ce{H}$ lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$.
- Si D : La température module l'agitation thermique, pas la capacité structurelle d'une molécule à donner ou accepter un pont hydrogène.

**Référence manuel** : liaisons-intermoleculaires-pont-hydrogene

---
id: q-pont-hydrogene-symbo-sou-001
concept: pont-hydrogene
chapitre: liaisons-intermoleculaires
niveau: DF
r1: symbo
type: sou
date_validation: 2026-09-02
statut: validated
---

**Question**
Que représente la notation pointillée dans $\ce{O-H\cdots O}$ ?

**Options**
- A. Un pont hydrogène entre l'hydrogène d'une molécule et un doublet non-liant d'un atome d'oxygène d'une autre molécule.
- B. Une liaison covalente double entre deux atomes d'oxygène.
- C. Une liaison ionique entre un ion $\ce{H+}$ et un ion $\ce{O^{2-}}$.
- D. Une interaction de van der Waals entre deux atomes d'oxygène, sans participation de l'hydrogène.

**Réponse correcte** : A

**Feedback correct**
Les pointillés notent une interaction électrostatique (le pont hydrogène) entre un $\ce{H}$ covalent fortement $\delta+$ et un doublet non-liant $\delta-$ porté par un atome électronégatif voisin — une interaction distincte des liaisons covalentes (trait plein) et ioniques.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Un trait plein noterait une liaison covalente — les pointillés notent au contraire une interaction plus faible, non covalente.
- Si C : Le pont hydrogène n'implique pas un transfert complet d'électron comme une liaison ionique — l'hydrogène reste covalemment lié à son atome d'origine.
- Si D : L'hydrogène est au contraire l'élément central du pont hydrogène — c'est lui qui est intercalé entre les deux atomes électronégatifs.

**Référence manuel** : liaisons-intermoleculaires-pont-hydrogene

---
id: q-pont-hydrogene-symbo-sou-002
concept: pont-hydrogene
chapitre: liaisons-intermoleculaires
niveau: DF
r1: symbo
type: sou
misconception: pont-hydrogene--confondu-avec-liaison-covalente
date_validation: 2026-09-08
statut: validated
---

**Question**
Que représente la notation pointillée dans $\ce{N-H\cdots O}$ ?

**Options**
- A. Un pont hydrogène entre l'hydrogène d'une molécule (lié à l'azote) et un doublet non-liant d'un atome d'oxygène d'une autre molécule.
- B. Une liaison covalente simple entre l'azote et l'oxygène, l'hydrogène servant seulement d'intermédiaire.
- C. Une liaison ionique entre un ion $\ce{H+}$ et un ion $\ce{O^{2-}}$.
- D. Une interaction de London entre les atomes d'azote et d'oxygène, sans participation de l'hydrogène.

**Réponse correcte** : A

**Feedback correct**
Les pointillés notent une interaction électrostatique (le pont hydrogène) entre un $\ce{H}$ covalent, lié à l'azote et fortement $\delta^+$, et un doublet non-liant $\delta^-$ porté par un atome d'oxygène voisin — une interaction distincte des liaisons covalentes (trait plein) et ioniques.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Un trait plein noterait une liaison covalente — les pointillés notent au contraire une interaction plus faible, non covalente, entre deux molécules distinctes. Cette confusion pont hydrogène/liaison covalente est documentée par Henderleiter et al. (2001) et par Gültepe (2021, 31 élèves sur 52 en prétest).
- Si C : Le pont hydrogène n'implique pas un transfert complet d'électron comme une liaison ionique — l'hydrogène reste covalemment lié à l'azote, il n'est pas un ion $\ce{H+}$ isolé.
- Si D : L'hydrogène est au contraire l'élément central du pont hydrogène — c'est lui qui est intercalé entre les deux atomes électronégatifs, pas absent de l'interaction.

**Référence manuel** : liaisons-intermoleculaires-pont-hydrogene

---
id: q-pont-hydrogene-symbo-ana-001
concept: pont-hydrogene
chapitre: liaisons-intermoleculaires
niveau: DF
r1: symbo
type: ana
date_validation: 2026-09-17
statut: validated
---

**Question**
Parmi les paires suivantes (une molécule avec une autre de son espèce), pour lesquelles un pont hydrogène est-il possible ?

**Options**
- A. Deux molécules $\ce{H2O}$
- B. Deux molécules $\ce{CH4}$
- C. Deux molécules $\ce{NH3}$
- D. Deux molécules $\ce{CH3F}$

**Réponse correcte** : A, C

**Feedback correct**
Le pont hydrogène exige un $\ce{H}$ covalemment lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ (donneur) face à un doublet non-liant porté par l'un de ces mêmes trois atomes (accepteur), sur une molécule voisine. $\ce{H2O}$ (H lié à O) et $\ce{NH3}$ (H lié à N) remplissent cette condition des deux côtés de chaque paire.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Dans $\ce{CH4}$, les $\ce{H}$ sont liés au carbone, pas à N/O/F — aucun doublet non-liant n'est disponible sur le carbone non plus : ni donneur, ni accepteur.
- Si C : C'est la bonne réponse.
- Si D : Piège — $\ce{CH3F}$ contient bien du fluor, mais ses hydrogènes sont liés au carbone, pas au fluor : ce ne sont pas des donneurs de pont hydrogène. Le fluor porte des doublets non-liants (accepteur potentiel), mais sans donneur en face, aucun pont hydrogène ne se forme entre deux molécules de $\ce{CH3F}$.

**Référence manuel** : liaisons-intermoleculaires-pont-hydrogene

---

<!-- ============================================================ -->
<!-- CONCEPT : keesom — Interaction dipôle permanent–dipôle permanent -->
<!-- 2 cellules obligatoires (2 questions) : macro·com, parti·sou -->
<!-- ============================================================ -->

---
id: q-keesom-macro-com-001
concept: keesom
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
À masse molaire comparable, $\ce{HCl}$ ($36{,}5\ \text{g/mol}$, polaire) bout à $-85\ ^\circ\text{C}$ tandis que $\ce{Ar}$ ($40{,}0\ \text{g/mol}$, apolaire) bout à $-186\ ^\circ\text{C}$. Quelle interaction explique cet écart de $101\ ^\circ\text{C}$ ?

**Options**
- A. Les forces de Keesom, présentes dans $\ce{HCl}$ (polaire) mais absentes dans $\ce{Ar}$ (apolaire).
- B. Les forces de London, plus intenses dans $\ce{Ar}$ que dans $\ce{HCl}$.
- C. Un pont hydrogène présent dans $\ce{HCl}$.
- D. La masse molaire, légèrement différente entre les deux substances.

**Réponse correcte** : A

**Feedback correct**
À masse comparable, les forces de London sont similaires d'une substance à l'autre. La différence s'explique par les forces de Keesom (dipôle–dipôle permanent), présentes dans $\ce{HCl}$ (polaire) mais absentes dans $\ce{Ar}$ (apolaire, sans dipôle permanent).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : C'est l'inverse de ce qui compte ici — à masse comparable, les forces de London ne diffèrent pas significativement ; ce n'est pas le facteur discriminant.
- Si C : $\ce{HCl}$ n'a pas d'hydrogène lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ (il est lié à $\ce{Cl}$) — aucun pont hydrogène ne se forme.
- Si D : L'écart de masse molaire ($36{,}5$ vs $40{,}0\ \text{g/mol}$) est mineur et ne peut expliquer une différence de $101\ ^\circ\text{C}$.

**Référence manuel** : liaisons-intermoleculaires-keesom

---
id: q-keesom-parti-sou-001
concept: keesom
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: sou
date_validation: 2026-09-02
statut: validated
---

**Question**
Quelle condition est nécessaire pour qu'une interaction de Keesom s'établisse entre deux molécules ?

**Options**
- A. Les deux molécules doivent être polaires (porter chacune un dipôle permanent).
- B. Une seule des deux molécules doit être polaire, l'autre apolaire.
- C. Les deux molécules doivent être ioniques.
- D. Les deux molécules doivent contenir un hydrogène lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$.

**Réponse correcte** : A

**Feedback correct**
L'interaction de Keesom est une attraction électrostatique entre deux dipôles permanents — elle exige donc que les deux molécules impliquées soient polaires, s'orientant $\delta+$ face à $\delta-$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le cas d'une molécule polaire et d'une molécule apolaire décrit une interaction de Debye, pas de Keesom.
- Si C : Keesom concerne des molécules neutres portant des dipôles permanents, pas des espèces chargées comme des ions.
- Si D : C'est la condition du pont hydrogène — un cas particulier et plus intense de dipôle-dipôle — pas de Keesom en général.

**Référence manuel** : liaisons-intermoleculaires-keesom

---

<!-- ============================================================ -->
<!-- CONCEPT : debye — Interaction dipôle permanent–dipôle induit  -->
<!-- 2 cellules obligatoires (2 questions) : macro·com, parti·sou -->
<!-- ============================================================ -->

---
id: q-keesom-macro-app-001
concept: keesom
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: app
date_validation: 2026-11-01
statut: validated
---

**Question**
Le dioxyde de soufre $\ce{SO2}$ ($M = 64{,}1\ \text{g/mol}$, molécule polaire) et le tétrafluorure de silicium $\ce{SiF4}$ ($M = 104{,}1\ \text{g/mol}$, molécule apolaire) sont deux gaz à température ambiante. Lequel bout à la température la plus élevée ?

**Options**
- A. $\ce{SiF4}$, car sa masse molaire plus grande renforce ses interactions bien plus que la polarité
- B. $\ce{SO2}$, car ses molécules polaires s'attirent aussi par des forces de Keesom
- C. $\ce{SiF4}$, car il possède davantage de liaisons polaires que $\ce{SO2}$
- D. $\ce{SO2}$, car ses molécules forment des ponts hydrogène entre elles

**Réponse correcte** : B

**Feedback correct**
$\ce{SO2}$ bout à $-10\ ^\circ\text{C}$ et $\ce{SiF4}$ à $-86\ ^\circ\text{C}$ (valeurs du manuel). Les molécules polaires de $\ce{SO2}$ s'attirent par des forces de Keesom, en plus des forces de London : l'écart de masse ne suffit pas à compenser.

**Feedback incorrect**
- Si A : La masse molaire plus élevée augmente les forces de London, mais ici l'effet de la polarité l'emporte : $\ce{SO2}$ bout plus haut que $\ce{SiF4}$ malgré sa masse plus faible.
- Si B : C'est la bonne réponse.
- Si C : Le nombre de liaisons polaires ne rend pas la molécule polaire : la géométrie symétrique de $\ce{SiF4}$ annule les dipôles, la molécule est apolaire.
- Si D : Un pont hydrogène exige un hydrogène lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$. $\ce{SO2}$ ne contient pas d'hydrogène.

**Référence manuel** : liaisons-intermoleculaires-keesom

---
id: q-keesom-macro-app-002
concept: keesom
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: app
date_validation: 2026-11-01
statut: validated
---

**Question**
L'acétone $\ce{(CH3)2CO}$ ($M = 58{,}1\ \text{g/mol}$, polaire) est liquide à 20 °C alors que le propane $\ce{C3H8}$ ($M = 44{,}1\ \text{g/mol}$, apolaire) est un gaz. Quelle interaction explique principalement cette différence ?

**Options**
- A. Les forces de London, car la molécule la plus lourde est toujours liquide
- B. Des ponts hydrogène entre les molécules d'acétone
- C. Des interactions ion–dipôle entre les molécules d'acétone
- D. Les forces de Keesom, présentes entre les molécules polaires d'acétone

**Réponse correcte** : D

**Feedback correct**
L'acétone bout à $+56\ ^\circ\text{C}$ et le propane à $-42\ ^\circ\text{C}$. À masse comparable, la différence vient surtout des forces de Keesom entre les molécules polaires d'acétone.

**Feedback incorrect**
- Si A : Les forces de London dépendent de la taille des molécules, mais l'écart de masse est faible ici (14 g/mol). Une molécule plus lourde n'est pas « toujours » liquide.
- Si B : Les molécules d'acétone n'ont pas d'hydrogène lié à $\ce{O}$, $\ce{N}$ ou $\ce{F}$ : elles ne peuvent pas former de ponts hydrogène entre elles.
- Si C : L'acétone est une molécule neutre, sans ion : aucune interaction ion–dipôle n'est possible entre ses molécules.
- Si D : C'est la bonne réponse.

**Référence manuel** : liaisons-intermoleculaires-keesom

---
id: q-keesom-parti-sou-002
concept: keesom
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: sou
date_validation: 2026-11-01
statut: validated
---

**Question**
Parmi ces paires de molécules, laquelle peut s'attirer par des forces de Keesom ?

**Options**
- A. $\ce{CH4}$ et $\ce{CH4}$
- B. $\ce{CO2}$ et $\ce{CO2}$
- C. $\ce{HCl}$ et $\ce{HCl}$
- D. $\ce{Ar}$ et $\ce{Ar}$

**Réponse correcte** : C

**Feedback correct**
Les forces de Keesom s'exercent entre deux molécules polaires. $\ce{HCl}$ est polaire ($\delta^+$ sur $\ce{H}$, $\delta^-$ sur $\ce{Cl}$) : deux molécules de $\ce{HCl}$ s'orientent $\delta^+$ face à $\delta^-$.

**Feedback incorrect**
- Si A : $\ce{CH4}$ est apolaire : il n'a pas de dipôle permanent, donc pas de forces de Keesom.
- Si B : $\ce{CO2}$ possède des liaisons polaires, mais sa géométrie linéaire symétrique annule les dipôles : la molécule est apolaire.
- Si C : C'est la bonne réponse.
- Si D : $\ce{Ar}$ est un atome isolé, apolaire : seules les forces de London s'exercent entre atomes d'argon.

**Référence manuel** : liaisons-intermoleculaires-keesom

---
id: q-keesom-parti-app-001
concept: keesom
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: app
date_validation: 2026-11-01
statut: validated
---

**Question**
Les liquides $\ce{HCl}$ et $\ce{HI}$ sont constitués de molécules polaires. Données : $\chi(\ce{H}) = 2{,}1$, $\chi(\ce{Cl}) = 3{,}0$, $\chi(\ce{I}) = 2{,}5$ ; l'atome de chlore est plus petit que celui d'iode. Dans lequel les forces de Keesom entre molécules identiques sont-elles les plus intenses ?

**Options**
- A. Dans $\ce{HI}$, car l'iode est un gros atome très polarisable
- B. Dans $\ce{HCl}$, charges partielles plus grandes, atomes plus proches
- C. Dans $\ce{HI}$, car sa masse molaire est plus élevée
- D. Elles sont identiques, car les deux molécules sont polaires

**Réponse correcte** : B

**Feedback correct**
La différence d'électronégativité est plus grande dans $\ce{HCl}$ ($0{,}9$) que dans $\ce{HI}$ ($0{,}4$) : les charges partielles sont plus grandes. Le petit atome de chlore permet en plus des distances plus courtes. Les deux facteurs renforcent Keesom dans $\ce{HCl}$.

**Feedback incorrect**
- Si A : La polarisabilité élevée de l'iode renforce les forces de London, pas celles de Keesom. Keesom dépend des charges partielles et de la distance.
- Si B : C'est la bonne réponse.
- Si C : La masse molaire joue sur les forces de London, pas sur celles de Keesom.
- Si D : Être polaire ne suffit pas : l'intensité de Keesom dépend de l'amplitude des charges partielles et de la distance, qui diffèrent ici.

**Référence manuel** : liaisons-intermoleculaires-keesom

---
id: q-debye-macro-com-001
concept: debye
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
Le diiode $\ce{I2}$, apolaire, se dissout légèrement dans l'eau. Quelle force intermoléculaire permet cette dissolution partielle ?

**Options**
- A. La force de Debye — le dipôle permanent de l'eau induit un dipôle temporaire dans $\ce{I2}$.
- B. La force de Keesom — $\ce{I2}$ possède un dipôle permanent.
- C. Un pont hydrogène entre $\ce{I2}$ et l'eau.
- D. Aucune force ne permet cette dissolution ; elle est purement due à l'agitation thermique.

**Réponse correcte** : A

**Feedback correct**
Le dipôle permanent de l'eau déforme le nuage électronique de $\ce{I2}$ (apolaire) et y induit un dipôle temporaire — c'est la force de Debye. Elle reste faible, d'où une dissolution limitée.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{I2}$ est une molécule diatomique symétrique et apolaire — elle n'a pas de dipôle permanent, donc pas d'interaction de Keesom possible.
- Si C : $\ce{I2}$ ne possède aucun atome d'hydrogène lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ — aucun pont hydrogène n'est possible.
- Si D : Une interaction électrostatique réelle (Debye) est bien à l'œuvre — ce n'est pas un effet purement thermique.

**Référence manuel** : liaisons-intermoleculaires-debye

---
id: q-debye-parti-sou-001
concept: debye
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: sou
date_validation: 2026-09-02
statut: validated
---

**Question**
Quelle combinaison de partenaires caractérise une interaction de Debye ?

**Options**
- A. Une molécule polaire (dipôle permanent) et une molécule apolaire (polarisable).
- B. Deux molécules polaires.
- C. Deux molécules apolaires.
- D. Un ion et une molécule polaire.

**Réponse correcte** : A

**Feedback correct**
La force de Debye naît quand le dipôle permanent d'une molécule polaire déforme le nuage électronique d'une molécule apolaire voisine et y induit un dipôle temporaire — elle nécessite donc un partenaire polaire et un partenaire apolaire.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Deux molécules polaires interagissent par force de Keesom, pas de Debye.
- Si C : Deux molécules apolaires interagissent uniquement par force de London.
- Si D : Un ion et une molécule polaire interagissent par interaction ion–dipôle, un type de force distinct et plus intense que Debye.

**Référence manuel** : liaisons-intermoleculaires-debye

---

<!-- ============================================================ -->
<!-- CONCEPT : london — Force de London (dispersion), polarisabilité -->
<!-- 4 cellules obligatoires (6 questions) : macro·com, parti·com(x2), parti·app, parti·eva(x2) -->
<!-- ============================================================ -->

---
id: q-debye-parti-sou-002
concept: debye
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: sou
date_validation: 2026-11-01
statut: validated
---

**Question**
Parmi ces paires, laquelle peut s'attirer par une force de Debye ?

**Options**
- A. $\ce{HCl}$ et $\ce{HCl}$
- B. $\ce{Cl2}$ et $\ce{Cl2}$
- C. $\ce{Na+}$ et $\ce{Cl-}$
- D. $\ce{HCl}$ et $\ce{Cl2}$

**Réponse correcte** : D

**Feedback correct**
La force de Debye associe une molécule polaire ($\ce{HCl}$, dipôle permanent) et une molécule apolaire polarisable ($\ce{Cl2}$) : le dipôle permanent déforme le nuage électronique de $\ce{Cl2}$ et y induit un dipôle.

**Feedback incorrect**
- Si A : Deux molécules polaires s'attirent par des forces de Keesom, pas de Debye.
- Si B : Deux molécules apolaires s'attirent uniquement par des forces de London.
- Si C : Il s'agit de deux ions de charges opposées : l'attraction est une liaison ionique, pas une force de Debye.
- Si D : C'est la bonne réponse.

**Référence manuel** : liaisons-intermoleculaires-debye

---
id: q-debye-macro-com-002
concept: debye
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-11-01
statut: validated
---

**Question**
Les poissons respirent le dioxygène dissous dans l'eau, alors que $\ce{O2}$ est apolaire et l'eau polaire. Quelle interaction rend cette dissolution partielle possible ?

**Options**
- A. La force de Debye : le dipôle permanent de l'eau induit un dipôle dans $\ce{O2}$
- B. Un pont hydrogène entre $\ce{O2}$ et l'eau
- C. La force de Keesom, parce que les deux atomes d'oxygène sont très électronégatifs
- D. Une interaction ion–dipôle, parce que $\ce{O2}$ se dissout sous forme d'ions

**Réponse correcte** : A

**Feedback correct**
Le dipôle permanent d'une molécule d'eau déforme le nuage électronique de $\ce{O2}$ et induit un dipôle : c'est la force de Debye. Elle est faible, ce qui explique que la solubilité de $\ce{O2}$ reste modeste ($1{,}70\ \text{mmol/L}$ à $10\ ^\circ\text{C}$).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Un pont hydrogène exige un hydrogène lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ sur l'une des molécules : $\ce{O2}$ n'en contient pas.
- Si C : $\ce{O2}$ est formé de deux atomes identiques : les électrons sont partagés équitablement, la molécule est apolaire, quelle que soit l'électronégativité de $\ce{O}$.
- Si D : $\ce{O2}$ se dissout sous forme de molécules, sans former d'ions : aucune interaction ion–dipôle n'intervient.

**Référence manuel** : liaisons-intermoleculaires-debye

---
id: q-debye-macro-app-001
concept: debye
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: app
date_validation: 2026-11-01
statut: validated
---

**Question**
À $10\ ^\circ\text{C}$, trois gaz apolaires se dissolvent dans l'eau à raison de : $\ce{H2}$ $0{,}80\ \text{mmol/L}$, $\ce{N2}$ $0{,}83\ \text{mmol/L}$, $\ce{CH4}$ $2{,}03\ \text{mmol/L}$. Quelle explication est cohérente avec ces valeurs ?

**Options**
- A. Plus un gaz est léger, plus il se dissout dans l'eau
- B. Ces gaz forment des ponts hydrogène avec l'eau, d'autant plus nombreux que la molécule contient d'hydrogène
- C. Ces gaz ne devraient pas se dissoudre du tout : les valeurs mesurées sont des erreurs de mesure
- D. Une interaction de Debye avec l'eau, plus forte pour le gaz le plus polarisable ($\ce{CH4}$)

**Réponse correcte** : D

**Feedback correct**
Le dipôle permanent de l'eau induit un dipôle dans chaque gaz (force de Debye). L'effet est d'autant plus marqué que la molécule est polarisable : $\ce{CH4}$, plus polarisable que $\ce{N2}$ et $\ce{H2}$, se dissout davantage.

**Feedback incorrect**
- Si A : Les valeurs contredisent cette règle : $\ce{H2}$, le plus léger, est le moins soluble.
- Si B : Ces molécules ne peuvent pas former de ponts hydrogène (il faut un $\ce{H}$ lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$). De plus, $\ce{N2}$, sans hydrogène, est plus soluble que $\ce{H2}$.
- Si C : Une molécule apolaire peut tout de même interagir avec l'eau : la force de Debye est faible mais non nulle, ce qui explique une dissolution modeste.
- Si D : C'est la bonne réponse.

**Référence manuel** : liaisons-intermoleculaires-debye

---
id: q-debye-parti-app-001
concept: debye
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: app
date_validation: 2026-11-01
statut: validated
---

**Question**
On mélange du chlorure d'hydrogène $\ce{HCl}$ (gaz polaire) et de l'argon $\ce{Ar}$ (gaz apolaire). Lesquelles de ces interactions s'exercent dans ce mélange ?

**Options**
- A. Des forces de Keesom entre deux molécules de $\ce{HCl}$
- B. Des forces de Debye entre une molécule de $\ce{HCl}$ et un atome d'argon
- C. Des forces de Keesom entre une molécule de $\ce{HCl}$ et un atome d'argon
- D. Des ponts hydrogène entre une molécule de $\ce{HCl}$ et un atome d'argon

**Réponse correcte** : A,B

**Feedback correct**
Deux molécules polaires de $\ce{HCl}$ s'attirent par Keesom. Le dipôle permanent de $\ce{HCl}$ induit un dipôle dans l'atome d'argon, polarisable : c'est la force de Debye. Les interactions autorisées coexistent.

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : C'est une des réponses correctes.
- Si C : Keesom exige deux dipôles permanents. L'argon est un atome apolaire : il n'en possède pas.
- Si D : Un pont hydrogène exige un hydrogène lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ : le $\ce{H}$ de $\ce{HCl}$ est lié à $\ce{Cl}$, et l'argon n'a aucun doublet à accepter.

**Référence manuel** : liaisons-intermoleculaires-debye

---
id: q-london-macro-com-001
concept: london
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
Pourquoi les températures d'ébullition des gaz nobles augmentent-elles régulièrement de $\ce{He}$ ($4\ \text{K}$) à $\ce{Xe}$ ($165\ \text{K}$) ?

**Options**
- A. Le nombre d'électrons (et donc la polarisabilité) augmente avec la taille de l'atome, renforçant les forces de London.
- B. Les gaz nobles forment des liaisons covalentes de plus en plus fortes en descendant dans le groupe.
- C. Les gaz nobles deviennent de plus en plus polaires en descendant dans le groupe.
- D. La masse atomique n'a aucune influence sur la température d'ébullition des gaz nobles.

**Réponse correcte** : A

**Feedback correct**
Plus un atome contient d'électrons, plus son nuage électronique est étendu et facilement déformable (polarisabilité élevée) — les forces de London, seules interactions possibles entre atomes apolaires, s'intensifient donc, ce qui élève la température d'ébullition.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Les gaz nobles n'établissent pas de liaisons covalentes entre eux — seules des interactions intermoléculaires (London) sont en jeu.
- Si C : Les gaz nobles restent des atomes isolés, toujours apolaires — ils ne développent pas de dipôle permanent.
- Si D : C'est au contraire un facteur central : plus la masse et le nombre d'électrons augmentent, plus la polarisabilité et les forces de London sont grandes.

**Référence manuel** : liaisons-intermoleculaires-london

---
id: q-london-parti-com-001
concept: london
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
Comment se forme une force de London entre deux atomes apolaires voisins ?

**Options**
- A. Une fluctuation instantanée du nuage électronique d'un atome crée un dipôle temporaire, qui induit à son tour un dipôle dans l'atome voisin ; les deux s'attirent brièvement.
- B. Les deux atomes échangent en permanence un électron de valence.
- C. Les noyaux des deux atomes s'attirent directement, indépendamment des électrons.
- D. Chaque atome porte une charge partielle permanente qui attire l'autre.

**Réponse correcte** : A

**Feedback correct**
À un instant donné, la répartition des électrons n'est jamais parfaitement symétrique : un dipôle instantané apparaît, déforme le nuage électronique du voisin et y induit un dipôle induit. Ces deux dipôles s'attirent brièvement — un phénomène permanent et incessant en moyenne sur l'ensemble des molécules.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Il ne s'agit pas d'un échange d'électron, ce qui décrirait une liaison covalente ou une réaction chimique, mais d'une simple fluctuation de répartition de charge.
- Si C : Ce sont les nuages électroniques, pas les noyaux seuls, qui sont à l'origine du dipôle instantané et de l'attraction qui en résulte.
- Si D : Par définition, un atome apolaire n'a pas de charge partielle *permanente* — c'est justement l'absence de permanence, une fluctuation, qui caractérise London.

**Référence manuel** : liaisons-intermoleculaires-london

---
id: q-london-parti-com-002
concept: london
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: com
misconception: london--mecanisme-non-electrostatique-boite-noire
date_validation: 2026-09-08
statut: validated
---

**Question**
Deux molécules apolaires de $\ce{Cl2}$ s'attirent brièvement par une force de London. Quelle est l'origine physique de cette attraction ?

**Options**
- A. Une fluctuation instantanée de la répartition des électrons dans une molécule crée un dipôle temporaire, qui induit un dipôle dans la molécule voisine ; les deux dipôles s'attirent brièvement.
- B. Chaque molécule de $\ce{Cl2}$ cherche à atteindre une configuration plus stable en s'associant temporairement à sa voisine, indépendamment de toute répartition de charge.
- C. Les molécules complètent mutuellement leur octet en se rapprochant, ce qui crée une attraction.
- D. Les deux molécules échangent brièvement un doublet d'électrons, comme dans une liaison covalente temporaire.

**Réponse correcte** : A

**Feedback correct**
À un instant donné, la répartition des électrons n'est jamais parfaitement symétrique : un dipôle instantané apparaît, déforme le nuage électronique de la molécule voisine et y induit un dipôle induit. Ces deux dipôles s'attirent brièvement — un phénomène permanent et incessant en moyenne sur l'ensemble des molécules.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : « Chercher la stabilité » n'est pas un mécanisme physique — c'est une explication non électrostatique documentée par Becker, Noyes & Cooper (2016) comme boîte noire : elle nomme un résultat sans expliquer le mécanisme réel (fluctuation de charge → dipôle instantané → dipôle induit).
- Si C : La règle de l'octet régit la formation de liaisons covalentes, pas les interactions intermoléculaires de London — cette confusion (transposer la règle de l'octet hors de son domaine) est également documentée par Becker et al. (2016) parmi les explications non électrostatiques mobilisées par les élèves.
- Si D : Un échange d'électrons décrirait une liaison covalente, une interaction bien plus forte et permanente — la force de London résulte d'une fluctuation de répartition de charge, sans échange d'électrons entre les deux molécules.

**Référence manuel** : liaisons-intermoleculaires-london

---
id: q-london-parti-app-001
concept: london
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: app
date_validation: 2026-09-02
statut: validated
---

**Question**
Le fluor $\ce{F2}$ ($18$ électrons, $T_\text{éb} = -188\ ^\circ\text{C}$) et le chlore $\ce{Cl2}$ ($34$ électrons, $T_\text{éb} = -34\ ^\circ\text{C}$) sont tous deux apolaires. Comment expliquer l'écart de $154\ ^\circ\text{C}$ entre leurs températures d'ébullition ?

**Options**
- A. $\ce{Cl2}$ possède plus d'électrons que $\ce{F2}$, ce qui le rend plus polarisable — les forces de London y sont donc plus intenses.
- B. $\ce{Cl2}$ est polaire, contrairement à $\ce{F2}$.
- C. $\ce{F2}$ forme des ponts hydrogène, contrairement à $\ce{Cl2}$.
- D. Le nombre d'électrons n'a aucun effet sur l'intensité des forces de London.

**Réponse correcte** : A

**Feedback correct**
Un nuage électronique plus étendu ($34$ électrons contre $18$) est plus facilement déformable — la polarisabilité, et donc l'intensité des forces de London, augmente avec le nombre d'électrons.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{F2}$ et $\ce{Cl2}$ sont tous deux des molécules diatomiques homonucléaires, donc apolaires — aucune des deux ne porte de dipôle permanent.
- Si C : Aucune des deux molécules ne contient d'hydrogène — un pont hydrogène est impossible dans les deux cas.
- Si D : C'est au contraire le facteur déterminant : plus le nombre d'électrons augmente, plus la polarisabilité et les forces de London sont grandes.

**Référence manuel** : liaisons-intermoleculaires-london

---
id: q-london-parti-eva-001
concept: london
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: eva
date_validation: 2026-09-02
statut: validated
---

**Question**
Un élève affirme : "La force de London est tellement plus faible que les forces de Keesom ou les ponts hydrogène qu'on peut la négliger dès qu'une molécule est polaire." Que répondre à partir de la série $\ce{HCl} \to \ce{HBr} \to \ce{HI}$, où la polarité diminue mais où la température d'ébullition remonte ?

**Options**
- A. C'est faux : London est présente dans toutes les molécules, et pour des molécules suffisamment grosses (nombreux électrons), elle peut dominer même une interaction de Keesom.
- B. C'est vrai : dans une molécule polaire, seules les forces de Keesom comptent.
- C. C'est faux, mais uniquement parce que $\ce{HCl}$, $\ce{HBr}$ et $\ce{HI}$ forment des ponts hydrogène.
- D. C'est vrai : la série $\ce{HCl} \to \ce{HBr} \to \ce{HI}$ illustre que la polarité est le seul facteur qui compte.

**Réponse correcte** : A

**Feedback correct**
De $\ce{HCl}$ à $\ce{HI}$, la polarité — donc Keesom — diminue, mais la masse molaire et le nombre d'électrons augmentent fortement : les forces de London s'intensifient au point de dominer, et la température d'ébullition remonte malgré la polarité décroissante. C'est la preuve que London ne peut jamais être ignorée par principe, même dans une molécule polaire.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'exemple $\ce{HCl} \to \ce{HI}$ réfute directement cette affirmation : c'est London, pas Keesom, qui explique la remontée de température d'ébullition.
- Si C : Aucun de ces trois halogénures d'hydrogène ne contient de $\ce{H}$ lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ — aucun pont hydrogène n'est possible ici, contrairement à $\ce{HF}$.
- Si D : C'est l'inverse : cette série montre justement que la polarité seule ne suffit pas à prédire la température d'ébullition — London peut prendre le dessus.

**Référence manuel** : liaisons-intermoleculaires-london

---
id: q-london-parti-eva-002
concept: london
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: eva
date_validation: 2026-09-08
statut: validated
---

**Question**
Un élève affirme : « La force de London est tellement plus faible que les forces de Keesom qu'on peut la négliger dès qu'une molécule est polaire. » Que répondre à partir de la série $\ce{H2S} \to \ce{H2Se} \to \ce{H2Te}$, où la polarité diminue mais où la température d'ébullition remonte ($-60\ ^\circ\text{C} \to -41\ ^\circ\text{C} \to -2\ ^\circ\text{C}$) ?

**Options**
- A. C'est faux : London est présente dans toutes les molécules, et pour des molécules suffisamment grosses (nombreux électrons), elle peut dominer même une interaction de Keesom.
- B. C'est vrai : dans une molécule polaire, seules les forces de Keesom comptent.
- C. C'est faux, mais uniquement parce que $\ce{H2S}$, $\ce{H2Se}$ et $\ce{H2Te}$ forment des ponts hydrogène.
- D. C'est vrai : la série $\ce{H2S} \to \ce{H2Te}$ illustre que la polarité est le seul facteur qui compte.

**Réponse correcte** : A

**Feedback correct**
De $\ce{H2S}$ à $\ce{H2Te}$, la polarité — donc Keesom — diminue légèrement (l'électronégativité de $\ce{S}$, $\ce{Se}$, $\ce{Te}$ décroît), mais le nombre d'électrons augmente fortement : les forces de London s'intensifient au point de dominer, et la température d'ébullition remonte malgré la polarité décroissante. C'est la preuve que London ne peut jamais être ignorée par principe, même dans une molécule polaire — exactement le résultat documenté par Becker, Noyes & Cooper (2016).

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La série $\ce{H2S} \to \ce{H2Te}$ réfute directement cette affirmation : c'est London, pas Keesom, qui explique la remontée de température d'ébullition.
- Si C : Aucun de ces trois hydrures ne contient d'hydrogène lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ ($\ce{S}$, $\ce{Se}$ et $\ce{Te}$ ne satisfont pas la règle NOF) — aucun pont hydrogène n'est possible ici, contrairement à $\ce{H2O}$.
- Si D : C'est l'inverse : cette série montre justement que la polarité seule ne suffit pas à prédire la température d'ébullition — London peut prendre le dessus.

**Référence manuel** : liaisons-intermoleculaires-london

---

<!-- ============================================================ -->
<!-- CONCEPT : hydrophile-hydrophobe-amphiphile — Synthèse transversale, molécules à parties mixtes -->
<!-- 2 cellules obligatoires (2 questions) : macro·com, parti·ana -->
<!-- ============================================================ -->

---
id: q-hydrophile-hydrophobe-amphiphile-macro-com-001
concept: hydrophile-hydrophobe-amphiphile
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-09-02
statut: validated
---

**Question**
Le savon stéarate de sodium $\ce{CH3(CH2)16COO^{-}Na^{+}}$ possède une longue chaîne carbonée et une tête ionique $\ce{COO^{-}Na^{+}}$. Laquelle de ces deux parties est hydrophile ?

**Options**
- A. La tête ionique $\ce{COO^{-}Na^{+}}$ — elle interagit fortement avec l'eau par interaction ion–dipôle.
- B. La chaîne carbonée — elle interagit fortement avec l'eau par pont hydrogène.
- C. Les deux parties sont également hydrophiles.
- D. Aucune des deux parties n'a d'affinité particulière pour l'eau.

**Réponse correcte** : A

**Feedback correct**
La tête ionique $\ce{COO^{-}Na^{+}}$, chargée, interagit fortement avec les dipôles de l'eau par interaction ion–dipôle — elle est hydrophile. La longue chaîne carbonée, apolaire, n'établit que de faibles forces de London avec l'eau — elle est hydrophobe.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : La chaîne carbonée est apolaire et ne possède aucun hydrogène lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ — elle ne peut former ni pont hydrogène, ni interaction forte avec l'eau ; c'est la partie hydrophobe.
- Si C : Les deux parties ont un comportement opposé face à l'eau — c'est précisément ce qui définit une molécule amphiphile.
- Si D : La tête ionique a au contraire une forte affinité pour l'eau, via l'interaction ion–dipôle.

**Référence manuel** : liaisons-intermoleculaires-recapitulatif

---
id: q-hydrophile-hydrophobe-amphiphile-parti-ana-001
concept: hydrophile-hydrophobe-amphiphile
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: ana
date_validation: 2026-09-02
statut: validated
---

**Question**
Le propan-1-ol $\ce{CH3CH2CH2OH}$ est miscible à l'eau en toutes proportions, mais le pentan-1-ol $\ce{CH3(CH2)4OH}$ ne l'est pas, alors que les deux possèdent un groupe $\ce{-OH}$. Pourquoi ?

**Options**
- A. Chez le pentan-1-ol, la longue chaîne carbonée apolaire (London) domine sur le groupe $\ce{-OH}$ (pont hydrogène), rendant la molécule globalement hydrophobe.
- B. Le pentan-1-ol ne possède pas de groupe $\ce{-OH}$ capable de former des ponts hydrogène.
- C. Le propan-1-ol est ionique, contrairement au pentan-1-ol.
- D. La longueur de la chaîne carbonée n'a aucune influence sur la miscibilité avec l'eau.

**Réponse correcte** : A

**Feedback correct**
Les deux alcools peuvent former des ponts hydrogène via leur groupe $\ce{-OH}$. Mais chez le pentan-1-ol, la chaîne apolaire (5 carbones) est assez longue pour que les forces de London entre chaînes carbonées dominent globalement le comportement de la molécule — elle devient hydrophobe malgré son groupe $\ce{-OH}$.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Le pentan-1-ol possède bien un groupe $\ce{-OH}$, comme son nom l'indique, et peut former des ponts hydrogène — ce n'est pas leur absence qui est en cause, mais leur insuffisance face à la chaîne apolaire.
- Si C : Aucun des deux alcools n'est ionique — tous deux sont des molécules covalentes neutres.
- Si D : C'est au contraire le facteur déterminant : plus la chaîne carbonée est longue, plus la molécule devient hydrophobe.

**Référence manuel** : liaisons-intermoleculaires-recapitulatif

---
id: q-hydrophile-hydrophobe-amphiphile-macro-com-002
concept: hydrophile-hydrophobe-amphiphile
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-11-01
statut: validated
---

**Question**
Le glucose $\ce{C6H12O6}$ se dissout très bien dans l'eau, alors que le cyclohexane $\ce{C6H12}$ ne s'y dissout pas. Comment peut-on qualifier ces deux espèces ?

**Options**
- A. Le glucose est hydrophobe et le cyclohexane est hydrophile
- B. Le glucose est hydrophile et le cyclohexane est hydrophobe
- C. Les deux sont hydrophiles, mais le cyclohexane l'est moins
- D. Le glucose est amphiphile et le cyclohexane est hydrophile

**Réponse correcte** : B

**Feedback correct**
Le glucose, polaire et riche en groupes $\ce{-OH}$, forme des ponts hydrogène avec l'eau : il est hydrophile. Le cyclohexane, apolaire, ne peut établir avec l'eau que de faibles forces de London : il est hydrophobe.

**Feedback incorrect**
- Si A : C'est l'inverse : le glucose se dissout dans l'eau (hydrophile), le cyclohexane non (hydrophobe).
- Si B : C'est la bonne réponse.
- Si C : Une espèce qui ne se dissout pas dans l'eau n'est pas hydrophile : le cyclohexane est apolaire, donc hydrophobe.
- Si D : Le glucose est hydrophile dans son ensemble, sans partie hydrophobe marquée, et le cyclohexane, apolaire, n'est pas hydrophile.

**Référence manuel** : liaisons-intermoleculaires-recapitulatif

---
id: q-hydrophile-hydrophobe-amphiphile-macro-com-003
concept: hydrophile-hydrophobe-amphiphile
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: com
date_validation: 2026-11-01
statut: validated
---

**Question**
Un phospholipide, constituant des membranes cellulaires, possède une « tête » chargée et deux longues « queues » carbonées. Pourquoi le qualifie-t-on d'amphiphile ?

**Options**
- A. Parce qu'il est soluble dans l'eau comme dans n'importe quel autre solvant
- B. Parce qu'il possède deux têtes polaires, une de chaque côté
- C. Parce qu'il comporte une partie hydrophile et une partie hydrophobe
- D. Parce qu'il est ionique dans son ensemble, donc entièrement hydrophile

**Réponse correcte** : C

**Feedback correct**
Une espèce amphiphile possède à la fois une partie hydrophile et une partie hydrophobe. La tête chargée interagit avec l'eau, tandis que les queues carbonées apolaires n'établissent avec elle que de faibles forces de London.

**Feedback incorrect**
- Si A : Amphiphile ne signifie pas « soluble partout » : le terme décrit la coexistence de deux parties aux affinités opposées pour l'eau.
- Si B : Il n'y a qu'une tête polaire. Les queues, apolaires, forment la partie hydrophobe.
- Si C : C'est la bonne réponse.
- Si D : Les longues queues carbonées sont apolaires : la molécule n'est pas entièrement hydrophile.

**Référence manuel** : liaisons-intermoleculaires-recapitulatif

---
id: q-hydrophile-hydrophobe-amphiphile-parti-ana-002
concept: hydrophile-hydrophobe-amphiphile
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: ana
date_validation: 2026-11-01
statut: validated
---

**Question**
L'éthanol $\ce{CH3CH2OH}$ est miscible à l'eau en toutes proportions, alors que l'octan-1-ol $\ce{CH3(CH2)7OH}$ y est pratiquement insoluble, bien que les deux possèdent un groupe $\ce{-OH}$. Quelle explication convient ?

**Options**
- A. La longue chaîne apolaire l'emporte sur le seul groupe $\ce{-OH}$
- B. L'octan-1-ol ne possède pas de groupe $\ce{-OH}$
- C. Plus une molécule est lourde, moins elle est miscible à l'eau, quel que soit son groupe fonctionnel
- D. L'éthanol est ionique, contrairement à l'octan-1-ol

**Réponse correcte** : A

**Feedback correct**
Le groupe $\ce{-OH}$ forme des ponts hydrogène avec l'eau, mais la chaîne carbonée apolaire n'établit que des forces de London. Quand la chaîne s'allonge, la partie hydrophobe l'emporte et la molécule devient globalement hydrophobe.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'octan-1-ol possède bien un groupe $\ce{-OH}$, comme l'éthanol : c'est la taille de la chaîne qui fait la différence.
- Si C : La masse molaire seule ne détermine pas la miscibilité : un petit alcane est insoluble, alors que de grosses molécules à nombreux groupes $\ce{-OH}$ (comme le glucose) sont très solubles.
- Si D : L'éthanol est une molécule neutre, polaire grâce à son groupe $\ce{-OH}$ : il n'est pas ionique.

**Référence manuel** : liaisons-intermoleculaires-recapitulatif

---
id: q-hydrophile-hydrophobe-amphiphile-parti-ana-003
concept: hydrophile-hydrophobe-amphiphile
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: ana
date_validation: 2026-11-01
statut: validated
---

**Question**
Lesquelles de ces espèces sont amphiphiles ?

**Options**
- A. Le palmitate de sodium $\ce{CH3(CH2)14COO^{-}Na^{+}}$
- B. L'octane $\ce{CH3(CH2)6CH3}$
- C. L'éthane-1,2-diol $\ce{HOCH2CH2OH}$
- D. Le dodécylsulfate de sodium $\ce{CH3(CH2)11OSO3^{-}Na^{+}}$

**Réponse correcte** : A,D

**Feedback correct**
Une espèce amphiphile associe une partie hydrophile (ici une tête ionique) et une partie hydrophobe (ici une longue chaîne carbonée apolaire). C'est le cas du palmitate de sodium, un savon, et du dodécylsulfate de sodium, un détergent.

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : L'octane est entièrement apolaire : il est hydrophobe, sans partie hydrophile.
- Si C : L'éthane-1,2-diol est petit et porte deux groupes $\ce{-OH}$ : il est hydrophile, sans partie hydrophobe marquée.
- Si D : C'est une des réponses correctes.

**Référence manuel** : liaisons-intermoleculaires-recapitulatif

<!-- LOT QUESTIONS DIFFICILES (lot-ch3.tmp.md, 02.11.2026) — statut to_fix -->

---
id: q-ion-dipole-parti-ana-301
concept: ion-dipole
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: ana
date_validation: 2026-11-02
statut: validated
---

**Question**
Voici des données pour quatre ions dissous dans l'eau :

| Ion | Rayon (pm) | Enthalpie d'hydratation (kJ/mol) |
|---|---|---|
| $\ce{Na+}$ | 102 | −406 |
| $\ce{K+}$ | 138 | −322 |
| $\ce{Ca^{2+}}$ | 100 | −1577 |
| $\ce{Mg^{2+}}$ | 72 | −1922 |

Plus l'enthalpie est négative, plus l'interaction ion-dipôle avec l'eau est forte. Quelles conclusions sont cohérentes avec ces données ?

**Options**
- A. L'enthalpie d'hydratation ne dépend pas de la charge de l'ion
- B. À charge égale, l'ion le plus petit interagit le plus fortement avec l'eau ($\ce{Na+}$ par rapport à $\ce{K+}$)
- C. $\ce{Mg^{2+}}$ est plus fortement hydraté que $\ce{Ca^{2+}}$ parce que sa charge est plus grande
- D. $\ce{Na+}$ et $\ce{Ca^{2+}}$ ont presque le même rayon, mais $\ce{Ca^{2+}}$ est hydraté environ quatre fois plus fortement : la charge pèse lourd dans l'interaction

**Réponse correcte** : B, D

**Feedback correct**
L'interaction ion-dipôle est d'autant plus forte que l'ion est petit (il s'approche davantage des molécules d'eau) et que sa charge est élevée. $\ce{Na+}$ ($-406$) est plus fortement hydraté que $\ce{K+}$ ($-322$). Avec des rayons presque identiques, $\ce{Ca^{2+}}$ ($-1577$) l'est environ quatre fois plus que $\ce{Na+}$ : la charge double a un effet très marqué (l'énergie d'interaction varie comme le carré de la charge divisé par le rayon : elle est multipliée par 4 quand la charge double).

**Feedback incorrect**
- Si A : Les données montrent le contraire : à rayon presque égal, $\ce{Ca^{2+}}$ ($2+$) est bien plus hydraté que $\ce{Na+}$ ($1+$).
- Si B : C'est une bonne réponse : $\ce{Na+}$ et $\ce{K+}$ ont la même charge, et le plus petit (102 pm) est le plus fortement hydraté.
- Si C : $\ce{Mg^{2+}}$ et $\ce{Ca^{2+}}$ portent la même charge (2+). La différence vient de la taille : $\ce{Mg^{2+}}$ est plus petit (72 pm contre 100 pm), donc plus proche des molécules d'eau.
- Si D : C'est une bonne réponse : à rayon quasi identique, seule la charge explique l'écart entre $\ce{Na+}$ et $\ce{Ca^{2+}}$.

**Référence manuel** : liaisons-intermoleculaires-ion-dipole

---
id: q-ion-dipole-macro-eva-302
concept: ion-dipole
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: eva
date_validation: 2026-11-02
statut: validated
---

**Question**
On prépare une solution aqueuse saturée de chlorure de sodium $\ce{NaCl}$. En ajoutant lentement de l'éthanol (solvant polaire, mais moins que l'eau), on voit apparaître un précipité de $\ce{NaCl}$. Un élève propose quatre explications. Laquelle est valable ?

**Options**
- A. L'éthanol réagit chimiquement avec $\ce{NaCl}$ et forme un nouveau solide
- B. Dans le mélange, la solvatation des ions est moins efficace que dans l'eau pure : l'énergie gagnée par les interactions ion-dipôle ne compense plus la cohésion du cristal
- C. La solubilité d'un sel ne dépend que de la température, pas de la nature du solvant
- D. L'éthanol attire les molécules d'eau et les retire aux ions, mais l'énergie de solvatation par molécule reste exactement la même

**Réponse correcte** : B

**Feedback correct**
Un sel se dissout si les interactions ion-dipôle avec le solvant compensent la cohésion du cristal. L'éthanol est polaire, mais moins que l'eau, et sa molécule porte une chaîne carbonée apolaire : la solvatation est moins efficace. L'équilibre se déplace vers le cristal et le sel précipite.

**Feedback incorrect**
- Si A : Il n'y a pas de réaction : le précipité est du $\ce{NaCl}$ solide qui se reforme, simplement parce que le solvant solvate moins bien ses ions.
- Si B : C'est la bonne réponse.
- Si C : La nature du solvant est déterminante : le même sel est très soluble dans l'eau et presque insoluble dans l'hexane ou, ici, dans un mélange riche en éthanol.
- Si D : Le raisonnement est incomplet : ce qui compte est l'efficacité globale de la solvatation. Quand la proportion d'éthanol augmente, les ions sont entourés de molécules qui les solvatent moins bien que l'eau.

**Référence manuel** : liaisons-intermoleculaires-ion-dipole

---
id: q-keesom-macro-ana-301
concept: keesom
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: ana
date_validation: 2026-11-02
statut: validated
---

**Question**
On compare trois substances de masses molaires voisines :

| Substance | $M$ (g/mol) | Moment dipolaire (D) | $T_\text{éb}$ (°C) |
|---|---|---|---|
| Propane $\ce{CH3CH2CH3}$ | 44 | 0,08 | −42 |
| Éther diméthylique $\ce{CH3OCH3}$ | 46 | 1,30 | −25 |
| Éthanal $\ce{CH3CHO}$ | 44 | 2,75 | +20 |

Quelles affirmations sont cohérentes avec ces données ?

**Options**
- A. Dans ces trois substances, les forces de London sont négligeables devant les forces de Keesom
- B. Dans cette série, la température d'ébullition augmente avec le moment dipolaire
- C. L'éthanal forme des ponts hydrogène avec lui-même, ce qui explique son point d'ébullition élevé
- D. Le propane n'exerce pratiquement que des forces de London, alors que les deux autres molécules y ajoutent des forces de Keesom

**Réponse correcte** : B, D

**Feedback correct**
Les masses molaires étant voisines, les forces de London sont du même ordre. L'écart de température d'ébullition est donc attribuable aux forces de Keesom, d'autant plus intenses que le moment dipolaire est grand. Le propane (quasi apolaire) n'a que London.

**Feedback incorrect**
- Si A : Les forces de London existent dans les trois substances et sont du même ordre (masses molaires de 44 à 46 g/mol). Elles ne sont pas négligeables : elles se retranchent simplement de la comparaison.
- Si B : C'est une bonne réponse.
- Si C : Un pont hydrogène exige un $\ce{H}$ lié à $\ce{N}$, $\ce{O}$ ou $\ce{F}$. Dans l'éthanal, le $\ce{H}$ est lié à $\ce{C}$ : il n'y a pas de pont hydrogène entre molécules.
- Si D : C'est une bonne réponse.

**Référence manuel** : liaisons-intermoleculaires-keesom

---
id: q-keesom-parti-ana-302
concept: keesom
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: ana
date_validation: 2026-11-02
statut: validated
---

**Question**
Les deux isomères du 1,2-dichloroéthène $\ce{C2H2Cl2}$ ont la même masse molaire (96,9 g/mol). L'isomère cis, où les deux atomes de chlore sont du même côté de la double liaison, bout à 60 °C. L'isomère trans, où ils sont de part et d'autre, bout à 48 °C. Quelles affirmations sont correctes pour interpréter cette différence ?

**Options**
- A. Le trans est plus polaire, car ses deux atomes de chlore sont éloignés l'un de l'autre
- B. Dans le cis, les deux dipôles des liaisons $\ce{C-Cl}$ ne s'annulent pas : la molécule est polaire et peut établir des forces de Keesom
- C. Le cis forme des ponts hydrogène $\ce{C-H...Cl}$ qui expliquent à eux seuls l'écart de 12 °C
- D. Les forces de London sont comparables, car les deux isomères ont la même masse molaire et la même formule

**Réponse correcte** : B, D

**Feedback correct**
Même formule et même masse molaire : les forces de London sont du même ordre. Dans l'isomère cis, les dipôles $\ce{C-Cl}$ s'additionnent : la molécule est polaire et s'attire en plus par Keesom. Dans le trans, ils pointent en sens opposés et s'annulent : la molécule est apolaire.

**Feedback incorrect**
- Si A : C'est l'inverse : dans le trans, les deux dipôles $\ce{C-Cl}$ sont opposés et se compensent, la molécule est apolaire.
- Si B : C'est une bonne réponse.
- Si C : Le $\ce{H}$ est lié à $\ce{C}$, non à $\ce{N}$, $\ce{O}$ ou $\ce{F}$ : il n'y a pas de pont hydrogène au sens du cours. Des contacts $\ce{C-H...Cl}$ seraient très faibles et ne pourraient pas expliquer à eux seuls 12 °C : la polarité du cis suffit.
- Si D : C'est une bonne réponse.

**Référence manuel** : liaisons-intermoleculaires-keesom

---
id: q-debye-macro-ana-301
concept: debye
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: ana
date_validation: 2026-11-02
statut: validated
---

**Question**
La solubilité du dioxygène $\ce{O2}$ dans l'eau, sous une pression d'$\ce{O2}$ de 1 atm, diminue quand la température augmente :

| Température (°C) | 0 | 10 | 25 | 40 |
|---|---|---|---|---|
| Solubilité (mmol/L) | 2,2 | 1,7 | 1,3 | 1,0 |

Quelle interprétation est cohérente avec la nature de l'interaction entre $\ce{O2}$ et l'eau ?

**Options**
- A. La baisse de solubilité montre que $\ce{O2}$ et l'eau se repoussent
- B. À chaud, les ponts hydrogène entre molécules d'eau se renforcent et expulsent $\ce{O2}$
- C. L'eau chaude contient nettement moins de molécules d'eau par litre, d'où moins de place pour $\ce{O2}$
- D. L'interaction de Debye entre l'eau et $\ce{O2}$ est faible, du même ordre que l'énergie d'agitation thermique : quand la température monte, l'association de $\ce{O2}$ aux molécules d'eau est de plus en plus défavorisée

**Réponse correcte** : D

**Feedback correct**
Le dipôle permanent de l'eau induit un dipôle dans $\ce{O2}$ (force de Debye), mais cette interaction est faible. Quand la température monte, l'énergie d'agitation thermique devient plus importante et libère davantage de molécules d'$\ce{O2}$ : la solubilité diminue. C'est ce qui prive d'oxygène les eaux trop chaudes.

**Feedback incorrect**
- Si A : La solubilité reste positive : $\ce{O2}$ est attiré par l'eau (force de Debye), faiblement. La baisse avec la température traduit une attraction faible, pas une répulsion.
- Si B : L'agitation thermique désorganise les ponts hydrogène au lieu de les renforcer, et ils n'« expulsent » pas $\ce{O2}$.
- Si C : La masse volumique de l'eau varie de moins de 1 % entre 0 et 40 °C : le nombre de molécules d'eau par litre ne change presque pas.
- Si D : C'est la bonne réponse.

**Référence manuel** : liaisons-intermoleculaires-debye

---
id: q-debye-macro-eva-302
concept: debye
chapitre: liaisons-intermoleculaires
niveau: DF
r1: macro
type: eva
date_validation: 2026-11-02
statut: validated
---

**Question**
À 10 °C, sous 1 atm de gaz pur, le dioxyde de carbone $\ce{CO2}$ (apolaire) se dissout dans l'eau à 52,7 mmol/L, le sulfure d'hydrogène $\ce{H2S}$ (polaire) à 150 mmol/L et le dioxygène $\ce{O2}$ (apolaire) à 1,7 mmol/L. Un élève conclut : « $\ce{CO2}$ est bien plus soluble que $\ce{O2}$, donc la force de Debye est très intense, plus forte que les interactions entre molécules polaires ». Quelles affirmations évaluent correctement ce raisonnement ?

**Options**
- A. La conclusion est fondée : un gaz plus soluble qu'un autre prouve que son interaction de Debye avec l'eau est plus forte
- B. Pour $\ce{O2}$ dans l'eau, l'interaction de Debye est nettement plus faible que l'interaction entre deux molécules d'eau voisines
- C. La forte solubilité de $\ce{H2S}$ confirme que Debye est la force qui domine dans la dissolution des gaz dans l'eau
- D. La conclusion n'est pas fondée : la solubilité d'un gaz reflète l'ensemble des interactions, dont la polarisabilité de la molécule (plus grande pour $\ce{CO2}$ que pour $\ce{O2}$) et, pour $\ce{CO2}$, une réaction partielle avec l'eau, pas la seule force de Debye

**Réponse correcte** : B, D

**Feedback correct**
La solubilité d'un gaz dépend de l'ensemble des interactions avec l'eau et de la polarisabilité de la molécule ; pour $\ce{CO2}$ s'ajoute une réaction partielle avec l'eau (équilibre acido-basique). On ne peut donc pas isoler la force de Debye. Par ailleurs, pour $\ce{O2}$, la solubilité très faible montre que l'attraction avec l'eau reste faible devant la cohésion de l'eau.

**Feedback incorrect**
- Si A : La solubilité mesurée additionne plusieurs effets (polarisabilité, réaction éventuelle avec l'eau, etc.) : elle ne permet pas de conclure sur la seule intensité de Debye.
- Si B : C'est une bonne réponse.
- Si C : $\ce{H2S}$ est polaire : il s'attire avec l'eau par des interactions entre dipôles permanents en plus des forces de London. Sa forte solubilité ne dit rien de la force de Debye.
- Si D : C'est une bonne réponse.

**Référence manuel** : liaisons-intermoleculaires-debye

<!-- LOT QUESTIONS DIFFICILES (lot-inter.tmp.md, 02.11.2026) — statut to_fix -->

---
id: q-london-parti-eva-401
concept: london
chapitre: liaisons-intermoleculaires
niveau: DF
r1: parti
type: eva
date_validation: 2026-11-02
statut: validated
---

**Question**
Le propane $\ce{C3H8}$ ($M = 44$ g/mol, $T_\text{éb} = -42\ ^\circ\text{C}$) et l'éthanal $\ce{CH3CHO}$ ($M = 44$ g/mol, $T_\text{éb} = +20\ ^\circ\text{C}$) ont la même masse molaire. Un élève affirme : « Les forces de London ne dépendent que de la masse, donc ces deux liquides devraient bouillir à la même température ». Quelles évaluations de son raisonnement sont correctes ?

**Options**
- A. L'écart s'explique par la chaîne carbonée : celle du propane est plus courte, donc ses molécules s'attirent moins
- B. Son point de départ est inexact : les forces de London dépendent de la taille du nuage électronique (polarisabilité), pas de la seule masse
- C. Même si les forces de London sont voisines ici, l'éthanal est polaire : ses molécules s'attirent en plus par des forces de Keesom
- D. L'éthanal forme des ponts hydrogène entre ses propres molécules, ce qui explique l'écart

**Réponse correcte** : B, C

**Feedback correct**
Les forces de London dépendent de la polarisabilité du nuage électronique (nombre d'électrons, taille), et non de la masse seule. Ici, les deux molécules ont un nombre d'électrons voisin : leurs forces de London sont comparables. Mais l'éthanal est polaire (liaison $\ce{C=O}$) : ses molécules s'attirent en plus par des forces de Keesom, ce qui élève sa température d'ébullition. Le propane, apolaire, n'a que du London.

**Feedback incorrect**
- Si A : Les deux molécules ont un nombre d'électrons voisin (26 et 24) : la longueur de chaîne ne suffit pas à expliquer un écart de 62 °C. C'est la polarité de l'éthanal qui compte.
- Si B : Cette option est correcte parce que les forces de London dépendent de la polarisabilité du nuage électronique (nombre d'électrons, taille), pas de la masse seule : ici 26 et 24 électrons, donc des forces voisines.
- Si C : Cette option est correcte parce que l'éthanal est polaire (liaison $\ce{C=O}$) : ses molécules s'attirent en plus par des forces de Keesom, ce que le propane apolaire ne fait pas.
- Si D : Un pont hydrogène demande un $\ce{H}$ lié à $\ce{O}$, $\ce{N}$ ou $\ce{F}$. Dans $\ce{CH3CHO}$, les $\ce{H}$ sont liés à des carbones : les molécules d'éthanal n'en forment pas entre elles.

**Référence manuel** : liaisons-intermoleculaires-london
