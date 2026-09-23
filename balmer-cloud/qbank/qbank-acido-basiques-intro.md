# Banque de questions validées — Chapitre 07
# Introduction aux équilibres acido-basiques
# Slug : acido-basiques-intro

_Projet-Balmer / Balmer-Cloud — Généré le 2026-09-20_
_Sous-parties 7A (Arrhenius, Brønsted-Lowry, couple, autoprotolyse : 23 questions), 7B (force, pH, pOH, milieu : 26), 7C (neutralisation, conductivité, indicateurs : 19) et 7D (métaux, carbonates, oxydes : 12), soit 80 questions obligatoires minimum, relues et validées par l'enseignant le 2026-09-21. Six « super questions » (champ `outils:`, Charte §6.2bis) suivent en fin de fichier, validées le 2026-09-21 (86 questions au total). Voir `matrice-concepts-acido-basiques-intro.md` pour la cible complète._

---

<!-- LÉGENDE
Niveau R1 : macro = macroscopique | parti = particulaire | symbo = symbolique
Type      : 1 = identification | 2 = application directe | 3 = transfert
Statut    : validated | to_fix
-->

---

<!-- ============================================================ -->
<!-- SOUS-PARTIE 7A                                               -->
<!-- ============================================================ -->

---

<!-- ============================================================ -->
<!-- CONCEPT : acide-base-arrhenius — Acide et base (Arrhenius)   -->
<!-- 6 questions obligatoires : macro·T1, parti·T1, parti·T2×2    -->
<!-- (●², misconception h-dans-la-formule-egal-acide), symbo·T1,  -->
<!-- symbo·T2                                                     -->
<!-- ============================================================ -->

---
id: q-acide-base-arrhenius-macro-t1-001
concept: acide-base-arrhenius
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Un élève affirme : « un acide est une substance qui pique, et une base est une substance au toucher savonneux ». Parmi les affirmations suivantes, lesquelles sont correctes ?

**Options**
- A. Toute substance qui pique est un acide d'Arrhenius, qu'elle libère ou non des ions $\ce{H+}$ en solution aqueuse
- B. Ce sont des impressions sensorielles réelles, mais elles ne constituent pas une définition chimique
- C. Une définition chimique peut se limiter à une sensation perçue au contact, à condition que tout le monde la ressente de la même façon
- D. Une définition chimique décrit ce qui est libéré ou échangé entre les espèces, par exemple des ions $\ce{H+}$ ou $\ce{OH-}$ chez Arrhenius

**Réponse correcte** : B,D

**Feedback correct**
Le caractère piquant et le toucher savonneux sont des observations sensorielles réelles, mais pas une définition chimique (B). Une définition chimique décrit ce qui est libéré ou échangé entre les espèces : des ions $\ce{H+}$ ou $\ce{OH-}$ selon Arrhenius, des protons selon Brønsted-Lowry (D).

**Feedback incorrect**
- Si A : Le caractère piquant est une sensation, pas ce qui définit un acide. Un acide d'Arrhenius se définit par la libération d'ions $\ce{H+}$ en solution aqueuse, pas par l'effet ressenti au contact.
- Si B : C'est une des réponses correctes.
- Si C : Même partagée par tous, une sensation ne dit rien de ce qui se passe entre les espèces chimiques. Une définition chimique porte sur ce qui est libéré ou échangé, pas sur l'impression ressentie.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-acides-bases

---
id: q-acide-base-arrhenius-parti-t1-001
concept: acide-base-arrhenius
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, que se passe-t-il lorsque le chlorure d'hydrogène $\ce{HCl}$ est dissous dans l'eau, selon la définition d'Arrhenius ?

**Options**
- A. Chaque molécule $\ce{HCl}$ libère un ion $\ce{OH-}$, ce qui rend la solution acide
- B. Les molécules $\ce{HCl}$ restent intactes et se dispersent simplement entre les molécules d'eau
- C. Chaque molécule $\ce{HCl}$ libère un ion $\ce{H+}$ et un ion $\ce{Cl-}$ ; l'ion $\ce{H+}$ se lie aussitôt à une molécule d'eau pour former $\ce{H3O+}$
- D. Chaque molécule $\ce{HCl}$ cède un électron à une molécule d'eau

**Réponse correcte** : C

**Feedback correct**
Un acide d'Arrhenius libère des ions $\ce{H+}$ en solution aqueuse : $\ce{HCl -> H+ + Cl-}$. Comme les ions $\ce{H+}$ ne restent jamais libres en solution, ils se lient immédiatement à une molécule d'eau pour former l'ion hydronium $\ce{H3O+}$.

**Feedback incorrect**
- Si A : Ce sont les bases d'Arrhenius qui libèrent des ions $\ce{OH-}$. $\ce{HCl}$ est un acide : il libère un ion $\ce{H+}$, pas un ion $\ce{OH-}$.
- Si B : Selon Arrhenius, un acide libère des ions $\ce{H+}$ en solution aqueuse : les molécules $\ce{HCl}$ ne restent donc pas intactes. Elles se séparent en $\ce{H+}$ et $\ce{Cl-}$.
- Si C : C'est la bonne réponse.
- Si D : Ce qui est libéré est un ion $\ce{H+}$, le noyau de l'atome d'hydrogène, et non un électron. Les échanges d'électrons caractérisent les réactions d'oxydo-réduction.

**Référence manuel** : acido-basiques-intro-arrhenius

---
id: q-acide-base-arrhenius-parti-t2-001
concept: acide-base-arrhenius
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
misconception: arrhenius--h-dans-la-formule-egal-acide
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, lesquelles de ces espèces libèrent, lorsqu'elles sont dissoutes dans l'eau, des ions $\ce{H+}$ ou des ions $\ce{OH-}$ (c'est-à-dire sont des acides ou des bases d'Arrhenius) ?

**Options**
- A. $\ce{Ca(OH)2}$
- B. $\ce{CH4}$
- C. $\ce{HBr}$
- D. $\ce{NaCl}$

**Réponse correcte** : A,C

**Feedback correct**
$\ce{HBr}$ libère des ions $\ce{H+}$ ($\ce{HBr -> H+ + Br-}$) et $\ce{Ca(OH)2}$ des ions $\ce{OH-}$ ($\ce{Ca(OH)2 -> Ca^{2+} + 2 OH-}$) : ce sont respectivement un acide et une base d'Arrhenius. Ce qui compte est ce que l'espèce libère dans l'eau, pas les atomes qui figurent dans sa formule.

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : $\ce{CH4}$ contient des atomes d'hydrogène, mais ne libère aucun ion $\ce{H+}$ dans l'eau. Avoir des atomes $\ce{H}$ dans sa formule ne suffit pas à faire un acide d'Arrhenius.
- Si C : C'est une des réponses correctes.
- Si D : $\ce{NaCl}$ se dissocie dans l'eau en ions $\ce{Na+}$ et $\ce{Cl-}$, mais ne libère ni $\ce{H+}$ ni $\ce{OH-}$ : ce n'est ni un acide ni une base d'Arrhenius.

**Référence manuel** : acido-basiques-intro-arrhenius

---
id: q-acide-base-arrhenius-parti-t2-002
concept: acide-base-arrhenius
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
misconception: arrhenius--h-dans-la-formule-egal-acide
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, lesquelles de ces espèces libèrent, lorsqu'elles sont dissoutes dans l'eau, des ions $\ce{H+}$ ou des ions $\ce{OH-}$ (c'est-à-dire sont des acides ou des bases d'Arrhenius) ?

**Options**
- A. $\ce{HNO3}$
- B. $\ce{C6H12O6}$ (glucose)
- C. $\ce{CH3OH}$ (méthanol)
- D. $\ce{KOH}$

**Réponse correcte** : A,D

**Feedback correct**
$\ce{HNO3}$ libère des ions $\ce{H+}$ ($\ce{HNO3 -> H+ + NO3-}$) et $\ce{KOH}$ des ions $\ce{OH-}$ ($\ce{KOH -> K+ + OH-}$) : ce sont un acide et une base d'Arrhenius. Ni le nombre d'atomes d'hydrogène ni la présence d'un groupe $\ce{OH}$ dans la formule ne suffisent : c'est la libération d'ions en solution aqueuse qui définit un acide ou une base d'Arrhenius.

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Le glucose contient de nombreux atomes d'hydrogène, mais ne libère aucun ion $\ce{H+}$ dans l'eau. Des atomes $\ce{H}$ dans la formule ne font pas un acide d'Arrhenius.
- Si C : Dans $\ce{CH3OH}$, le groupe $\ce{OH}$ est lié au carbone et n'est pas libéré sous forme d'ion $\ce{OH-}$ dans l'eau. Ce n'est pas un hydroxyde comme $\ce{KOH}$, donc pas une base d'Arrhenius.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-arrhenius

---
id: q-acide-base-arrhenius-symbo-t1-001
concept: acide-base-arrhenius
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Lesquelles de ces équations représentent correctement la libération d'ions par une base d'Arrhenius en solution aqueuse ?

**Options**
- A. $\ce{HBr (aq) -> H+ (aq) + Br- (aq)}$
- B. $\ce{Ca(OH)2 (aq) -> Ca^{2+} (aq) + 2 OH- (aq)}$
- C. $\ce{KOH (aq) -> K+ (aq) + OH- (aq)}$
- D. $\ce{Ca(OH)2 (aq) -> Ca^{2+} (aq) + OH- (aq)}$

**Réponse correcte** : B,C

**Feedback correct**
Une base d'Arrhenius libère des ions $\ce{OH-}$ en solution aqueuse. Dans $\ce{KOH}$ et $\ce{Ca(OH)2}$, ces ions sont déjà présents dans le composé ionique : un par ion $\ce{K+}$, deux par ion $\ce{Ca^{2+}}$, de sorte que les charges sont conservées dans chaque équation.

**Feedback incorrect**
- Si A : Cette équation représente la libération d'un ion $\ce{H+}$ : c'est celle d'un acide d'Arrhenius, pas d'une base.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : La charge n'est pas conservée : le membre de gauche est neutre, alors que celui de droite porte une charge totale de +1. Pour compenser les deux charges positives de $\ce{Ca^{2+}}$, il faut deux ions $\ce{OH-}$.

**Référence manuel** : acido-basiques-intro-arrhenius

---
id: q-acide-base-arrhenius-symbo-t2-001
concept: acide-base-arrhenius
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Selon Arrhenius, l'acide sulfurique $\ce{H2SO4}$ libère ses protons en deux étapes. Lesquelles de ces équations décrivent correctement ces étapes ?

**Options**
- A. $\ce{H2SO4 -> H+ + HSO4-}$
- B. $\ce{H2SO4 -> H+ + SO4^{2-}}$
- C. $\ce{HSO4- <=> H+ + SO4^{2-}}$
- D. $\ce{HSO4- <=> 2 H+ + SO4^{2-}}$

**Réponse correcte** : A,C

**Feedback correct**
Une molécule $\ce{H2SO4}$ libère d'abord un proton pour donner $\ce{HSO4-}$ (A). L'ion $\ce{HSO4-}$ peut ensuite en libérer un second, pour donner $\ce{SO4^{2-}}$ (C) : c'est pourquoi $\ce{H2SO4}$ est un acide diprotique. Dans chaque équation, les atomes et les charges sont conservés.

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : La charge n'est pas conservée : elle est nulle à gauche, mais vaut −1 à droite (+1 pour $\ce{H+}$, −2 pour $\ce{SO4^{2-}}$). Un seul proton est libéré à chaque étape : il faut passer par $\ce{HSO4-}$.
- Si C : C'est une des réponses correctes.
- Si D : $\ce{HSO4-}$ ne contient qu'un seul atome d'hydrogène : il ne peut libérer qu'un proton, pas deux. Cette équation ne conserve ni les atomes ni les charges.

**Référence manuel** : acido-basiques-intro-arrhenius

---

<!-- ============================================================ -->
<!-- CONCEPT : acide-base-bronsted-lowry — Acide et base (B-L)    -->
<!-- 8 questions obligatoires : parti·T1×2 (●², misconception     -->
<!-- proton-confondu-electron), parti·T2×2 (●², base-prise-pour-  -->
<!-- acide), parti·T3×2 (●², melange-modeles), symbo·T1, symbo·T2-->
<!-- ============================================================ -->

---
id: q-acide-base-bronsted-lowry-parti-t1-001
concept: acide-base-bronsted-lowry
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: bronsted-lowry--proton-confondu-electron
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, lesquelles de ces affirmations décrivent correctement ce qui se passe lors d'une réaction acido-basique selon Brønsted-Lowry ?

**Options**
- A. Un proton $\ce{H+}$ passe de l'acide vers la base
- B. Un électron passe de l'acide vers la base, comme dans une réaction d'oxydo-réduction
- C. L'espèce transférée est le noyau de l'atome d'hydrogène, sans aucun électron
- D. Un ion $\ce{OH-}$ passe de la base vers l'acide

**Réponse correcte** : A,C

**Feedback correct**
Selon Brønsted-Lowry, une réaction acido-basique est un transfert de proton de l'acide vers la base (A). Ce proton est le noyau de l'atome d'hydrogène : ce qui reste de l'atome quand il a perdu son électron (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Ce sont les réactions d'oxydo-réduction qui échangent des électrons. Dans une réaction acido-basique, l'espèce échangée est un proton, qui ne porte aucun électron.
- Si C : C'est une des réponses correctes.
- Si D : Ce qui est transféré est un proton $\ce{H+}$, non un ion $\ce{OH-}$. Il va de plus de l'acide vers la base, et non de la base vers l'acide.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-acide-base-bronsted-lowry-parti-t1-002
concept: acide-base-bronsted-lowry
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: bronsted-lowry--proton-confondu-electron
date_validation: 2026-09-21
statut: validated
---

**Question**
Lors de la réaction $\ce{HCl + H2O -> Cl- + H3O+}$, lesquelles de ces descriptions à l'échelle particulaire sont correctes ?

**Options**
- A. La molécule $\ce{HCl}$ cède un proton à une molécule d'eau
- B. La molécule $\ce{HCl}$ cède un électron à une molécule d'eau
- C. La molécule d'eau cède un ion $\ce{OH-}$ à la molécule $\ce{HCl}$
- D. Le proton est accepté par un doublet non liant de l'atome d'oxygène de l'eau

**Réponse correcte** : A,D

**Feedback correct**
La molécule $\ce{HCl}$ cède un proton (A) : c'est l'acide. L'eau, qui joue le rôle de base, accepte ce proton sur un doublet non liant de son atome d'oxygène (D), ce qui forme $\ce{H3O+}$ et laisse $\ce{Cl-}$.

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Aucun électron n'est transféré à l'eau : $\ce{HCl}$ cède un proton, c'est-à-dire un $\ce{H+}$ sans électron. Les échanges d'électrons caractérisent l'oxydo-réduction.
- Si C : L'eau ne cède pas d'ion $\ce{OH-}$ : la formule $\ce{H3O+}$ montre qu'elle a gagné un $\ce{H+}$, et non qu'elle a perdu un groupe.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-acide-base-bronsted-lowry-parti-t2-001
concept: acide-base-bronsted-lowry
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
misconception: bronsted-lowry--base-prise-pour-acide
date_validation: 2026-09-21
statut: validated
---

**Question**
Dans le sens direct de la réaction $\ce{NH3 + H2O <=> NH4+ + OH-}$, lesquelles de ces affirmations sont correctes selon Brønsted-Lowry ?

**Options**
- A. $\ce{NH3}$ est un acide, car sa formule contient de l'hydrogène
- B. $\ce{NH3}$ est une base : il accepte un proton
- C. $\ce{H2O}$ est un acide : elle cède un proton
- D. $\ce{H2O}$ est une base : elle accepte un proton

**Réponse correcte** : B,C

**Feedback correct**
$\ce{NH3}$ devient $\ce{NH4+}$ : il gagne un $\ce{H+}$, donc il accepte un proton et se comporte comme une base (B). L'eau devient $\ce{OH-}$ : elle perd un $\ce{H+}$, donc elle cède un proton et se comporte comme un acide (C).

**Feedback incorrect**
- Si A : Ce n'est pas la présence d'hydrogène qui fait un acide, mais la capacité à céder un proton. Ici $\ce{NH3}$ en accepte un pour former $\ce{NH4+}$ : c'est une base.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : Les rôles sont inversés : l'eau devient $\ce{OH-}$, elle a donc perdu un $\ce{H+}$. Une espèce qui cède un proton est un acide.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-acide-base-bronsted-lowry-parti-t2-002
concept: acide-base-bronsted-lowry
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
misconception: bronsted-lowry--base-prise-pour-acide
date_validation: 2026-09-21
statut: validated
---

**Question**
Dans le sens direct de la réaction $\ce{CO3^{2-} + H2O <=> HCO3- + OH-}$, lesquelles de ces affirmations sont correctes selon Brønsted-Lowry ?

**Options**
- A. $\ce{CO3^{2-}}$ est un acide : il cède un proton à l'eau
- B. $\ce{CO3^{2-}}$ est une base : il accepte un proton
- C. $\ce{H2O}$ est une base : elle accepte un proton de $\ce{CO3^{2-}}$
- D. $\ce{H2O}$ est un acide : elle cède un proton

**Réponse correcte** : B,D

**Feedback correct**
$\ce{CO3^{2-}}$ devient $\ce{HCO3-}$ : il gagne un $\ce{H+}$, donc il accepte un proton et se comporte comme une base (B). L'eau devient $\ce{OH-}$ : elle perd un $\ce{H+}$, donc elle cède un proton et se comporte comme un acide (D).

**Feedback incorrect**
- Si A : $\ce{CO3^{2-}}$ ne contient aucun atome d'hydrogène : il n'a aucun proton à céder. Il en gagne au contraire un pour donner $\ce{HCO3-}$, ce qui en fait une base.
- Si B : C'est une des réponses correctes.
- Si C : L'eau ne peut pas accepter de proton ici : elle se transforme en $\ce{OH-}$, ce qui signifie qu'elle en perd un. C'est $\ce{CO3^{2-}}$ qui en gagne un.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-acide-base-bronsted-lowry-parti-t3-001
concept: acide-base-bronsted-lowry
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 3
misconception: bronsted-lowry--melange-modeles
date_validation: 2026-09-21
statut: validated
---

**Question**
L'ammoniac $\ce{NH3}$ ne contient aucun ion $\ce{OH-}$, mais son atome d'azote porte un doublet non liant. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. $\ce{NH3}$ est une base de Brønsted-Lowry : son doublet non liant peut accepter un proton
- B. $\ce{NH3}$ n'est pas une base, car une base doit contenir des ions $\ce{OH-}$
- C. $\ce{NH3}$ est une base d'Arrhenius, car il rend la solution basique
- D. Toute base d'Arrhenius est aussi une base de Brønsted-Lowry, car la première théorie est un cas particulier de la seconde

**Réponse correcte** : A,D

**Feedback correct**
$\ce{NH3}$ peut accepter un proton grâce à son doublet non liant : c'est une base de Brønsted-Lowry (A), sans contenir d'ion $\ce{OH-}$. La théorie d'Arrhenius étant un cas particulier de celle de Brønsted-Lowry, toute base d'Arrhenius (comme $\ce{OH-}$) est aussi une base de Brønsted-Lowry (D) ; l'inverse est faux.

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Exiger la présence d'ions $\ce{OH-}$ est la contrainte de la définition d'Arrhenius. Dans la théorie de Brønsted-Lowry, toute espèce capable d'accepter un proton est une base, ce que permet un doublet non liant.
- Si C : Une base d'Arrhenius libère des ions $\ce{OH-}$ en solution aqueuse, ce que $\ce{NH3}$ ne fait pas directement. Que la solution soit basique ne suffit pas : $\ce{NH3}$ est une base de Brønsted-Lowry, pas d'Arrhenius.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-acide-base-bronsted-lowry-parti-t3-002
concept: acide-base-bronsted-lowry
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 3
misconception: bronsted-lowry--melange-modeles
date_validation: 2026-09-21
statut: validated
---

**Question**
L'ion phosphate $\ce{PO4^{3-}}$ ne contient aucun ion $\ce{OH-}$, mais ses atomes d'oxygène portent des doublets non liants. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. $\ce{PO4^{3-}}$ n'est pas une base de Brønsted-Lowry, car cette théorie exige aussi la libération d'ions $\ce{OH-}$
- B. $\ce{PO4^{3-}}$ n'est pas une base d'Arrhenius, car il ne libère pas d'ions $\ce{OH-}$
- C. $\ce{PO4^{3-}}$ est une base de Brønsted-Lowry, car il peut accepter un proton
- D. Les deux théories désignent toujours les mêmes espèces comme des bases

**Réponse correcte** : B,C

**Feedback correct**
Ne libérant pas d'ion $\ce{OH-}$, $\ce{PO4^{3-}}$ n'est pas une base d'Arrhenius (B). Il peut en revanche accepter un proton sur un doublet non liant : c'est une base de Brønsted-Lowry (C), théorie plus générale que celle d'Arrhenius.

**Feedback incorrect**
- Si A : La théorie de Brønsted-Lowry n'exige pas la libération d'ions $\ce{OH-}$ : elle demande seulement de pouvoir accepter un proton. C'est la définition d'Arrhenius qui exige des ions $\ce{OH-}$.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : Les deux théories ne désignent pas les mêmes bases : celle de Brønsted-Lowry est plus large. Des espèces comme $\ce{NH3}$ ou $\ce{PO4^{3-}}$ sont des bases de Brønsted-Lowry sans être des bases d'Arrhenius.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-acide-base-bronsted-lowry-symbo-t1-001
concept: acide-base-bronsted-lowry
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Dans l'équation générale $\ce{AH + B- -> A- + BH}$ d'une réaction acido-basique de Brønsted-Lowry, laquelle de ces descriptions est correcte ?

**Options**
- A. $\ce{B-}$ cède un proton à $\ce{AH}$ : $\ce{B-}$ est l'acide et $\ce{AH}$ est la base
- B. $\ce{A-}$ est l'acide et $\ce{BH}$ est la base, car ce sont les produits de la réaction
- C. $\ce{AH}$ cède un proton à $\ce{B-}$ : $\ce{AH}$ est l'acide et $\ce{B-}$ est la base
- D. $\ce{AH}$ cède un électron à $\ce{B-}$, comme dans une réaction d'oxydo-réduction

**Réponse correcte** : C

**Feedback correct**
Dans $\ce{AH + B- -> A- + BH}$, l'espèce $\ce{AH}$ perd un $\ce{H+}$ pour devenir $\ce{A-}$, tandis que $\ce{B-}$ en gagne un pour devenir $\ce{BH}$. $\ce{AH}$, qui cède un proton, est donc l'acide ; $\ce{B-}$, qui l'accepte, est la base.

**Feedback incorrect**
- Si A : Les rôles sont inversés : $\ce{AH}$ se transforme en $\ce{A-}$, donc il perd un $\ce{H+}$. L'espèce qui cède le proton est l'acide.
- Si B : L'acide et la base qui réagissent sont les réactifs. Les espèces $\ce{A-}$ et $\ce{BH}$ sont les espèces conjuguées qui se forment à partir d'eux.
- Si C : C'est la bonne réponse.
- Si D : Ce qui passe de $\ce{AH}$ à $\ce{B-}$ est un proton $\ce{H+}$, pas un électron : une réaction acido-basique n'est pas une réaction d'oxydo-réduction.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-acide-base-bronsted-lowry-symbo-t2-001
concept: acide-base-bronsted-lowry
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Laquelle de ces équations représente la réaction de l'ion fluorure $\ce{F-}$, agissant comme base de Brønsted-Lowry, avec l'eau ?

**Options**
- A. $\ce{F- + H2O <=> HF + H3O+}$
- B. $\ce{HF + OH- <=> F- + H2O}$
- C. $\ce{F- -> F + e-}$
- D. $\ce{F- + H2O <=> HF + OH-}$

**Réponse correcte** : D

**Feedback correct**
En tant que base, $\ce{F-}$ accepte un proton de l'eau et devient $\ce{HF}$ ; l'eau, qui cède ce proton, devient $\ce{OH-}$ : $\ce{F- + H2O <=> HF + OH-}$. Les atomes et les charges sont conservés de part et d'autre.

**Feedback incorrect**
- Si A : La charge n'est pas conservée : elle vaut −1 à gauche et +1 à droite. Si $\ce{F-}$ gagne un $\ce{H+}$, l'eau qui le perd devient $\ce{OH-}$, et non $\ce{H3O+}$.
- Si B : Dans cette équation, $\ce{F-}$ est un produit et non un réactif : elle décrit la réaction inverse, où $\ce{HF}$ cède un proton à $\ce{OH-}$. Elle ne représente pas l'action de $\ce{F-}$ sur l'eau.
- Si C : Cette équation représente la perte d'un électron, c'est-à-dire une oxydation. Une base de Brønsted-Lowry accepte un proton, elle ne cède pas d'électron.
- Si D : C'est la bonne réponse.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---

<!-- ============================================================ -->
<!-- CONCEPT : couple-acide-base — Couple acide/base conjugué     -->
<!-- 7 questions obligatoires : parti·T1×2 (●², misconception     -->
<!-- paire-ion-positif-negatif), parti·T2, symbo·T1, symbo·T2×2   -->
<!-- (●², conjugue-ecart-plus-dun-proton), symbo·T3               -->
<!-- ============================================================ -->

---
id: q-couple-acide-base-parti-t1-001
concept: couple-acide-base
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: couple-acide-base--paire-ion-positif-negatif
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, laquelle de ces descriptions caractérise le couple acide/base conjugué $\ce{CH3COOH}/\ce{CH3COO-}$ ?

**Options**
- A. Ce sont un cation et un anion, associés par une liaison ionique
- B. Les deux espèces ont la même structure, à un proton près : l'acide possède un $\ce{H+}$ de plus que sa base conjuguée
- C. Les deux espèces diffèrent d'un électron : l'acide en possède un de plus
- D. La base est formée à partir de l'acide par perte d'un ion $\ce{OH-}$

**Réponse correcte** : B

**Feedback correct**
Les deux espèces d'un couple conjugué ont la même structure, à un proton près : $\ce{CH3COOH}$ possède un $\ce{H+}$ de plus que $\ce{CH3COO-}$. Ici l'acide est une molécule neutre et sa base conjuguée un anion, ce qui montre qu'un couple n'est pas une paire d'ions.

**Feedback incorrect**
- Si A : Un couple acide/base n'est pas une paire cation/anion : $\ce{CH3COOH}$ est une molécule neutre. Ce qui relie les deux espèces est un proton, non une liaison ionique.
- Si B : C'est la bonne réponse.
- Si C : L'acide et sa base conjuguée diffèrent d'un proton $\ce{H+}$, pas d'un électron. Le lien entre les deux espèces est un transfert de proton.
- Si D : Passer de l'acide à sa base conjuguée, c'est perdre un proton $\ce{H+}$, et non un ion $\ce{OH-}$.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-couple-acide-base-parti-t1-002
concept: couple-acide-base
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: couple-acide-base--paire-ion-positif-negatif
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, laquelle de ces affirmations sur le couple $\ce{NH4+}/\ce{NH3}$ est correcte ?

**Options**
- A. $\ce{NH4+}$ et $\ce{NH3}$ ne diffèrent que par un proton : $\ce{NH3}$ possède un doublet non liant qui peut accepter un $\ce{H+}$ pour redonner $\ce{NH4+}$
- B. Un couple acide/base est toujours formé d'un ion positif et d'un ion négatif, comme $\ce{NH4+}$ et $\ce{Cl-}$
- C. $\ce{NH4+}$ et $\ce{NH3}$ diffèrent d'un électron : $\ce{NH4+}$ en possède un de moins
- D. $\ce{NH4+}$ et $\ce{NH3}$ forment un couple parce qu'elles contiennent toutes deux de l'azote et de l'hydrogène

**Réponse correcte** : A

**Feedback correct**
$\ce{NH4+}$ possède un $\ce{H+}$ de plus que $\ce{NH3}$. En cédant ce proton, l'acide $\ce{NH4+}$ donne sa base conjuguée $\ce{NH3}$, dont le doublet non liant peut le réaccepter. Ici l'acide est un cation et la base une molécule neutre : un couple n'est pas une paire ion positif/ion négatif.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Un couple n'est pas formé d'un ion positif et d'un ion négatif : $\ce{NH4+}$ et $\ce{Cl-}$ n'échangent aucun proton entre eux et ne forment pas de couple. Dans $\ce{NH4+}/\ce{NH3}$, la base est une molécule neutre.
- Si C : L'acide et sa base conjuguée diffèrent d'un proton $\ce{H+}$, pas d'un électron.
- Si D : Partager les mêmes éléments ne suffit pas : deux espèces forment un couple conjugué lorsqu'elles ne diffèrent que d'un proton $\ce{H+}$.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-couple-acide-base-parti-t2-001
concept: couple-acide-base
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Lors du transfert d'un proton entre $\ce{HCl}$ et $\ce{H2O}$ ($\ce{HCl + H2O -> Cl- + H3O+}$), lesquelles de ces associations sont correctes ?

**Options**
- A. $\ce{H3O+}$ est la base conjuguée de $\ce{H2O}$
- B. $\ce{Cl-}$ est l'acide conjugué de $\ce{H2O}$
- C. $\ce{Cl-}$ est la base conjuguée de $\ce{HCl}$
- D. $\ce{H3O+}$ est l'acide conjugué de $\ce{H2O}$

**Réponse correcte** : C,D

**Feedback correct**
$\ce{HCl}$ a cédé un proton : $\ce{Cl-}$ est sa base conjuguée (C), ce qui forme le couple $\ce{HCl}/\ce{Cl-}$. $\ce{H2O}$ a accepté un proton : $\ce{H3O+}$ est son acide conjugué (D), ce qui forme le couple $\ce{H3O+}/\ce{H2O}$.

**Feedback incorrect**
- Si A : $\ce{H3O+}$ possède un $\ce{H+}$ de plus que $\ce{H2O}$ : c'est son acide conjugué, pas sa base conjuguée. Une base conjuguée se forme par perte d'un proton.
- Si B : $\ce{Cl-}$ et $\ce{H2O}$ ne diffèrent pas d'un simple proton : ils ne forment pas un couple. $\ce{Cl-}$ est la base conjuguée de $\ce{HCl}$.
- Si C : C'est une des réponses correctes.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-couple-acide-base-symbo-t1-001
concept: couple-acide-base
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Lesquelles de ces paires sont des couples acide/base conjugué, notés dans l'ordre acide/base ?

**Options**
- A. $\ce{NH4+}/\ce{NH3}$
- B. $\ce{H3O+}/\ce{H2O}$
- C. $\ce{HCl}/\ce{H2O}$
- D. $\ce{NH3}/\ce{OH-}$

**Réponse correcte** : A,B

**Feedback correct**
Un couple associe un acide et sa base conjuguée, qui ne diffèrent que d'un proton, avec l'acide noté en premier. C'est le cas de $\ce{NH4+}/\ce{NH3}$ et de $\ce{H3O+}/\ce{H2O}$.

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : C'est une des réponses correctes.
- Si C : $\ce{HCl}$ et $\ce{H2O}$ sont deux réactifs qui échangent un proton : ce ne sont pas deux espèces conjuguées. Le couple de $\ce{HCl}$ est $\ce{HCl}/\ce{Cl-}$.
- Si D : $\ce{NH3}$ et $\ce{OH-}$ sont deux bases, et non un acide et sa base conjuguée : elles ne diffèrent pas d'un simple proton. Les couples respectifs sont $\ce{NH4+}/\ce{NH3}$ et $\ce{H2O}/\ce{OH-}$.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-couple-acide-base-symbo-t2-001
concept: couple-acide-base
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
misconception: couple-acide-base--conjugue-ecart-plus-dun-proton
date_validation: 2026-09-21
statut: validated
---

**Question**
Quel est l'acide conjugué de l'ion sulfate $\ce{SO4^{2-}}$ ?

**Options**
- A. $\ce{HSO4-}$
- B. $\ce{H2SO4}$
- C. $\ce{HSO3-}$
- D. $\ce{SO4^{3-}}$

**Réponse correcte** : A

**Feedback correct**
L'acide conjugué d'une base est l'espèce formée lorsque cette base accepte un proton : $\ce{SO4^{2-} + H+ -> HSO4-}$. Le couple est $\ce{HSO4-}/\ce{SO4^{2-}}$, avec un seul $\ce{H+}$ d'écart.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : $\ce{H2SO4}$ possède deux $\ce{H+}$ de plus que $\ce{SO4^{2-}}$ : c'est l'acide conjugué de $\ce{HSO4-}$, pas de $\ce{SO4^{2-}}$. Deux espèces conjuguées ne diffèrent que d'un seul proton.
- Si C : $\ce{HSO3-}$ contient un atome d'oxygène de moins que $\ce{SO4^{2-}}$ : ce n'est pas la même espèce plus un proton. L'acide conjugué de $\ce{SO4^{2-}}$ comporte les mêmes atomes, plus un $\ce{H+}$.
- Si D : Accepter un proton rend la charge plus positive, non plus négative : l'acide conjugué de $\ce{SO4^{2-}}$ a une charge de −1.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-couple-acide-base-symbo-t2-002
concept: couple-acide-base
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
misconception: couple-acide-base--conjugue-ecart-plus-dun-proton
date_validation: 2026-09-21
statut: validated
---

**Question**
Quelle est la base conjuguée de l'acide phosphorique $\ce{H3PO4}$ ?

**Options**
- A. $\ce{PO4^{3-}}$
- B. $\ce{HPO4^{2-}}$
- C. $\ce{H4PO4+}$
- D. $\ce{H2PO4-}$

**Réponse correcte** : D

**Feedback correct**
La base conjuguée d'un acide est l'espèce formée lorsque cet acide cède un proton : $\ce{H3PO4 -> H2PO4- + H+}$. Le couple est $\ce{H3PO4}/\ce{H2PO4-}$, avec un seul $\ce{H+}$ d'écart.

**Feedback incorrect**
- Si A : $\ce{PO4^{3-}}$ a perdu trois protons par rapport à $\ce{H3PO4}$ : c'est la base conjuguée de $\ce{HPO4^{2-}}$. Une base conjuguée ne diffère de son acide que d'un seul proton.
- Si B : $\ce{HPO4^{2-}}$ a perdu deux protons par rapport à $\ce{H3PO4}$ : c'est la base conjuguée de $\ce{H2PO4-}$, pas de $\ce{H3PO4}$.
- Si C : $\ce{H4PO4+}$ possède un proton de plus que $\ce{H3PO4}$ : ce serait son acide conjugué, non sa base conjuguée. Une base conjuguée se forme par perte d'un proton.
- Si D : C'est la bonne réponse.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-couple-acide-base-symbo-t3-001
concept: couple-acide-base
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
L'ion hydrogénosulfure $\ce{HS-}$ peut agir à la fois comme acide et comme base. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. $\ce{H2S}$ et $\ce{S^{2-}}$ forment un couple acide/base conjugué
- B. Une espèce ne peut appartenir qu'à un seul couple acide/base
- C. Dans le couple $\ce{H2S}/\ce{HS-}$, $\ce{HS-}$ joue le rôle de base
- D. Dans le couple $\ce{HS-}/\ce{S^{2-}}$, $\ce{HS-}$ joue le rôle d'acide

**Réponse correcte** : C,D

**Feedback correct**
$\ce{HS-}$ peut accepter un proton pour donner $\ce{H2S}$ : il est alors la base du couple $\ce{H2S}/\ce{HS-}$ (C). Il peut aussi en céder un pour donner $\ce{S^{2-}}$ : il est alors l'acide du couple $\ce{HS-}/\ce{S^{2-}}$ (D). Une espèce amphotère appartient donc à deux couples.

**Feedback incorrect**
- Si A : $\ce{H2S}$ et $\ce{S^{2-}}$ diffèrent de deux protons : ils ne forment pas un couple conjugué. Ils sont reliés par $\ce{HS-}$, qui forme un couple avec chacun d'eux.
- Si B : Une espèce amphotère appartient à deux couples : elle joue le rôle de base dans l'un et d'acide dans l'autre, comme $\ce{HS-}$ ici.
- Si C : C'est une des réponses correctes.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---

<!-- ============================================================ -->
<!-- CONCEPT : autoprotolyse-eau — Autoprotolyse de l'eau         -->
<!-- 2 questions obligatoires : parti·T1, symbo·T1                -->
<!-- ============================================================ -->

---
id: q-autoprotolyse-eau-parti-t1-001
concept: autoprotolyse-eau
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, que se passe-t-il dans l'eau pure ?

**Options**
- A. Elle ne contient que des molécules $\ce{H2O}$ intactes : aucun ion n'y est présent
- B. Deux molécules d'eau échangent un proton : l'une le cède (acide), l'autre l'accepte (base), ce qui forme des ions $\ce{H3O+}$ et $\ce{OH-}$
- C. Seuls des ions $\ce{H3O+}$ se forment, ce qui rend l'eau pure légèrement acide
- D. Les molécules d'eau se décomposent en dihydrogène et en dioxygène

**Réponse correcte** : B

**Feedback correct**
Lors de l'autoprotolyse de l'eau, une molécule d'eau cède un proton à une autre : $\ce{H2O + H2O <=> H3O+ + OH-}$. L'eau agit à la fois comme acide et comme base : on dit qu'elle est amphotère.

**Feedback incorrect**
- Si A : L'eau pure contient en réalité des ions : l'autoprotolyse forme en petite quantité des ions $\ce{H3O+}$ et $\ce{OH-}$.
- Si B : C'est la bonne réponse.
- Si C : L'autoprotolyse forme des ions $\ce{OH-}$ en même temps que des ions $\ce{H3O+}$ : la réaction produit les deux, et un seul type d'ion ne peut pas se former sans l'autre.
- Si D : La décomposition de l'eau en $\ce{H2}$ et $\ce{O2}$ est celle de l'électrolyse, qui exige un apport d'énergie électrique. L'autoprotolyse est un simple échange de protons entre molécules d'eau.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---
id: q-autoprotolyse-eau-symbo-t1-001
concept: autoprotolyse-eau
sous-partie: 7A
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Laquelle de ces équations représente l'autoprotolyse de l'eau ?

**Options**
- A. $\ce{2 H2O <=> 2 H2 + O2}$
- B. $\ce{H2O + H2O <=> H3O+ + H3O+}$
- C. $\ce{H2O + H2O <=> H3O+ + OH}$
- D. $\ce{H2O + H2O <=> H3O+ + OH-}$

**Réponse correcte** : D

**Feedback correct**
Dans l'autoprotolyse, une molécule d'eau cède un proton à une autre : la première devient $\ce{OH-}$, la seconde $\ce{H3O+}$. Les atomes et les charges sont conservés, et la double flèche traduit un équilibre.

**Feedback incorrect**
- Si A : Cette équation représente la décomposition de l'eau en dihydrogène et en dioxygène, et non un échange de proton entre molécules d'eau.
- Si B : La charge n'est pas conservée : elle est nulle à gauche et vaut +2 à droite. Une molécule d'eau qui cède un proton ne forme pas $\ce{H3O+}$ : elle devient $\ce{OH-}$.
- Si C : La charge n'est pas conservée : elle est nulle à gauche et vaut +1 à droite. Une molécule d'eau qui perd un proton devient l'ion $\ce{OH-}$ (charge −1), et non un groupe $\ce{OH}$ neutre.
- Si D : C'est la bonne réponse.

**Référence manuel** : acido-basiques-intro-bronsted-lowry

---

<!-- ============================================================ -->
<!-- SOUS-PARTIE 7B                                               -->
<!-- ============================================================ -->

---

<!-- ============================================================ -->
<!-- CONCEPT : force-acide-base — Force des acides et des bases   -->
<!-- 9 questions obligatoires : macro·T1×2 (●², force-vs-         -->
<!-- concentration), parti·T1×2 (●², acide-faible-totalement-     -->
<!-- ionise), parti·T2, symbo·T1, symbo·T2, symbo·T3×2 (●²,       -->
<!-- diprotique-plus-fort / hydroxyde-pris-pour-faible)           -->
<!-- ============================================================ -->

---
id: q-force-acide-base-macro-t1-001
concept: force-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
misconception: force-acide-base--force-vs-concentration
date_validation: 2026-09-21
statut: validated
---

**Question**
On prépare deux solutions : A, de l'acide chlorhydrique $\ce{HCl}$ à 0,001 mol/L (pH mesuré : 3,0), et B, de l'acide acétique $\ce{CH3COOH}$ à 1 mol/L (pH mesuré : 2,4). Un élève affirme que « l'acide acétique est un acide plus fort que l'acide chlorhydrique, puisque le pH de B est plus bas ». Lesquelles de ces affirmations sont correctes ?

**Options**
- A. Un pH plus bas prouve toujours que l'acide dissous est plus fort
- B. Le pH de B est plus bas parce que B est beaucoup plus concentrée que A, et non parce que l'acide acétique est plus fort
- C. Pour comparer la force de deux acides, il faut comparer des solutions de même concentration
- D. $\ce{HCl}$ à 0,001 mol/L est un acide faible, car la solution est très diluée

**Réponse correcte** : B,C

**Feedback correct**
La force d'un acide est sa tendance à céder un proton à l'eau : elle ne dépend pas de la quantité d'acide dissous. Ici B est 1000 fois plus concentrée que A, ce qui explique son pH plus bas (B). Pour comparer des forces, on compare donc des solutions de même concentration (C), où l'acide fort $\ce{HCl}$ donne davantage d'ions que l'acide faible $\ce{CH3COOH}$.

**Feedback incorrect**
- Si A : Le pH dépend de la concentration de la solution autant que de la force de l'acide : une solution concentrée d'acide faible peut avoir un pH plus bas qu'une solution diluée d'acide fort. Le pH seul ne permet donc pas de comparer des forces.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : Fort et faible ne signifient pas concentré et dilué : $\ce{HCl}$ reste un acide fort à toute concentration, sa dissociation dans l'eau est totale. La dilution change la concentration en ions, pas la force de l'acide.

**Référence manuel** : acido-basiques-intro-force

---
id: q-force-acide-base-macro-t1-002
concept: force-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
misconception: force-acide-base--force-vs-concentration
date_validation: 2026-09-21
statut: validated
---

**Question**
On dispose de deux solutions : A, d'acide nitrique $\ce{HNO3}$ à 0,001 mol/L, et B, d'acide formique $\ce{HCOOH}$ à 1 mol/L. Dans un montage de conductivité, l'ampoule brille davantage avec B qu'avec A. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. B conduit mieux parce qu'elle contient davantage d'ions par litre, ce qui ne prouve pas que $\ce{HCOOH}$ soit un acide plus fort que $\ce{HNO3}$
- B. L'ampoule brille plus avec B, donc $\ce{HCOOH}$ est un acide plus fort que $\ce{HNO3}$
- C. Un acide fort conduit toujours mieux qu'un acide faible, quelles que soient les concentrations
- D. $\ce{HNO3}$ reste un acide fort à 0,001 mol/L, même si sa solution conduit moins bien que B

**Réponse correcte** : A,D

**Feedback correct**
L'ampoule renseigne sur la quantité d'ions par litre, qui dépend de la concentration autant que de la force de l'acide (A). $\ce{HNO3}$ est un acide fort : sa dissociation est totale à toute concentration, même lorsque sa solution est diluée et conduit moins bien qu'une solution concentrée d'acide faible (D).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : La conductivité mesure la quantité d'ions par litre, pas la force. B est 1000 fois plus concentrée que A : elle peut contenir plus d'ions même si $\ce{HCOOH}$ ne cède qu'une petite fraction de ses protons.
- Si C : Ce n'est vrai qu'à concentration égale : un acide fort produit alors plus d'ions qu'un acide faible. Avec des concentrations très différentes, la comparaison n'est plus valable.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-force

---
id: q-force-acide-base-parti-t1-001
concept: force-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: force-acide-base--acide-faible-totalement-ionise
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, on observe une solution d'acide acétique $\ce{CH3COOH}$ à 0,1 mol/L. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. Des molécules $\ce{CH3COOH}$ et des ions $\ce{CH3COO-}$ coexistent en solution
- B. Aucune molécule $\ce{CH3COOH}$ ne subsiste : elles ont toutes cédé leur proton à l'eau
- C. Environ 98,7 molécules sur 100 n'ont pas cédé leur proton
- D. Environ la moitié des molécules ont cédé leur proton

**Réponse correcte** : A,C

**Feedback correct**
$\ce{CH3COOH}$ est un acide faible : sa dissociation est partielle. À 0,1 mol/L, seules 1,3 % des molécules ont cédé leur proton, si bien que $\ce{CH3COOH}$ et $\ce{CH3COO-}$ coexistent (A) et qu'environ 98,7 molécules sur 100 restent intactes (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Ce serait le cas d'un acide fort, dont aucune molécule $\ce{AH}$ ne subsiste. Un acide faible ne cède pas tous ses protons : $\ce{CH3COOH}$ n'en cède que 1,3 % à cette concentration.
- Si C : C'est une des réponses correctes.
- Si D : Seules 1,3 % des molécules ont cédé leur proton, et non la moitié. Même pour un acide faible, la fraction dissociée est ici très petite.

**Référence manuel** : acido-basiques-intro-force

---
id: q-force-acide-base-parti-t1-002
concept: force-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: force-acide-base--acide-faible-totalement-ionise
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, on observe une solution d'acide formique $\ce{HCOOH}$ à 0,1 mol/L, dont le pourcentage de dissociation est de 4,1 %. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. Aucune molécule $\ce{HCOOH}$ ne subsiste : tout est sous forme d'ions $\ce{HCOO-}$ et $\ce{H3O+}$
- B. Des molécules $\ce{HCOOH}$ et des ions $\ce{HCOO-}$ coexistent en solution
- C. Environ 4 molécules sur 100 n'ont pas cédé leur proton, les autres sont dissociées
- D. Environ 96 molécules sur 100 n'ont pas cédé leur proton

**Réponse correcte** : B,D

**Feedback correct**
$\ce{HCOOH}$ est un acide faible : à 0,1 mol/L, 4,1 % seulement des molécules cèdent leur proton, si bien que $\ce{HCOOH}$ et $\ce{HCOO-}$ coexistent (B) et qu'environ 96 molécules sur 100 restent intactes (D).

**Feedback incorrect**
- Si A : Aucune molécule $\ce{AH}$ ne subsiste seulement pour un acide fort. $\ce{HCOOH}$ est un acide faible : la plupart de ses molécules gardent leur proton.
- Si B : C'est une des réponses correctes.
- Si C : C'est l'inverse : 4,1 % des molécules ont cédé leur proton, et 95,9 % restent intactes.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-force

---
id: q-force-acide-base-parti-t2-001
concept: force-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
On dispose de 20 000 particules de $\ce{CH3COOH}$ et de 20 000 particules de $\ce{HCOOH}$, chacun en solution à 0,1 mol/L. Le pourcentage de dissociation est de 1,3 % pour $\ce{CH3COOH}$ et de 4,1 % pour $\ce{HCOOH}$. Combien de particules ont cédé leur proton dans chaque cas, et quel est l'acide le plus fort ?

**Options**
- A. $\ce{CH3COOH}$ : 260 ; $\ce{HCOOH}$ : 820 ; les deux acides ont la même force, car ce sont tous deux des acides faibles
- B. $\ce{CH3COOH}$ : 19 740 ; $\ce{HCOOH}$ : 19 180 ; le plus fort est $\ce{HCOOH}$
- C. $\ce{CH3COOH}$ : 260 ; $\ce{HCOOH}$ : 820 ; le plus fort est $\ce{HCOOH}$
- D. $\ce{CH3COOH}$ : 2 600 ; $\ce{HCOOH}$ : 8 200 ; le plus fort est $\ce{HCOOH}$

**Réponse correcte** : C

**Feedback correct**
1,3 % de 20 000 particules, soit 260, ont cédé leur proton pour $\ce{CH3COOH}$ ; 4,1 % de 20 000 particules, soit 820, pour $\ce{HCOOH}$. L'acide le plus fort est celui dont la fraction de particules dissociées est la plus grande : ici $\ce{HCOOH}$.

**Feedback incorrect**
- Si A : Deux acides faibles n'ont pas forcément la même force : plus la fraction de particules ayant cédé leur proton est grande, plus l'acide est fort. Ici 4,1 % pour $\ce{HCOOH}$ contre 1,3 % pour $\ce{CH3COOH}$.
- Si B : Ces nombres sont ceux des particules qui n'ont PAS cédé leur proton (98,7 % et 95,9 %). La question porte sur celles qui l'ont cédé : 1,3 % et 4,1 %.
- Si C : C'est la bonne réponse.
- Si D : Le calcul est faux d'un facteur 10 : 1,3 % de 20 000 vaut 260, et 4,1 % de 20 000 vaut 820.

**Référence manuel** : acido-basiques-intro-force

---
id: q-force-acide-base-symbo-t1-001
concept: force-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Lesquelles de ces écritures sont cohérentes, c'est-à-dire que le type de flèche correspond à la proportion de molécules d'acide restantes indiquée ?

**Options**
- A. $\ce{HNO3 + H2O <=> NO3- + H3O+}$ — 0 % de $\ce{HNO3}$ restant
- B. $\ce{NH4+ + H2O -> NH3 + H3O+}$ — 99,992 % de $\ce{NH4+}$ restant
- C. $\ce{HCOOH + H2O <=> HCOO- + H3O+}$ — 95,9 % de $\ce{HCOOH}$ restant
- D. $\ce{HCl + H2O -> Cl- + H3O+}$ — 0 % de $\ce{HCl}$ restant

**Réponse correcte** : C,D

**Feedback correct**
La flèche simple traduit une réaction totale : aucune molécule d'acide ne subsiste (0 % restant), comme pour $\ce{HCl}$ (D). La double flèche traduit un équilibre où l'acide et sa base conjuguée coexistent, comme pour $\ce{HCOOH}$ avec 95,9 % restant (C).

**Feedback incorrect**
- Si A : Si 0 % de $\ce{HNO3}$ subsiste, la réaction est totale : elle s'écrit avec une flèche simple, car $\ce{HNO3}$ est un acide fort.
- Si B : Avec 99,992 % de $\ce{NH4+}$ restant, la réaction est très partielle : elle s'écrit avec une double flèche, car $\ce{NH4+}$ est un acide faible. Une flèche simple traduirait une réaction totale.
- Si C : C'est une des réponses correctes.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-force

---
id: q-force-acide-base-symbo-t2-001
concept: force-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
misconception: force-acide-base--acide-faible-totalement-ionise
date_validation: 2026-09-21
statut: validated
---

**Question**
Parmi ces équations, lesquelles décrivent correctement ce qui se passe dans l'eau ?

**Options**
- A. $\ce{HCl + H2O -> Cl- + H3O+}$
- B. $\ce{Cl- + H2O -> HCl + OH-}$
- C. $\ce{HCOOH + H2O <=> HCOO- + H3O+}$
- D. $\ce{CH3COOH + H2O -> CH3COO- + H3O+}$

**Réponse correcte** : A,C

**Feedback correct**
$\ce{HCl}$ est un acide fort : sa réaction avec l'eau est totale, avec une flèche simple (A). $\ce{HCOOH}$ est un acide faible : sa réaction est partielle, avec une double flèche (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : $\ce{Cl-}$ est la base conjuguée d'un acide fort : c'est une base négligeable, sans tendance à capter un proton à l'eau. Cette réaction n'a pas lieu.
- Si C : C'est une des réponses correctes.
- Si D : $\ce{CH3COOH}$ est un acide faible (1,3 % de dissociation à 0,1 mol/L) : sa réaction avec l'eau est partielle et s'écrit avec une double flèche. Une flèche simple traduirait une réaction totale.

**Référence manuel** : acido-basiques-intro-force

---
id: q-force-acide-base-symbo-t3-001
concept: force-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
misconception: force-acide-base--diprotique-plus-fort
date_validation: 2026-09-21
statut: validated
---

**Question**
Un élève affirme que $\ce{H3PO4}$ est un acide plus fort que $\ce{HNO3}$, « car il peut céder trois protons alors que $\ce{HNO3}$ n'en cède qu'un ». Lesquelles de ces affirmations sont correctes ?

**Options**
- A. Plus une molécule peut céder de protons, plus l'acide est fort
- B. La force d'un acide mesure sa tendance à céder un proton à l'eau, et non le nombre de protons qu'il peut céder
- C. La base conjuguée de $\ce{H3PO4}$ est plus faible que celle de $\ce{HNO3}$
- D. $\ce{HNO3}$ est un acide fort et $\ce{H3PO4}$ un acide faible : $\ce{HNO3}$ est le plus fort des deux

**Réponse correcte** : B,D

**Feedback correct**
La force d'un acide se mesure à sa tendance à céder un proton à l'eau, non au nombre de protons qu'il peut céder (B). $\ce{HNO3}$ cède son proton en totalité : c'est un acide fort ; $\ce{H3PO4}$, bien que triprotique, n'en cède qu'une fraction : c'est un acide faible (D).

**Feedback incorrect**
- Si A : Le nombre de protons cédables n'entre pas dans la force : $\ce{H3PO4}$ peut céder trois protons, mais chacun est cédé difficilement, alors que $\ce{HNO3}$ cède son unique proton en totalité.
- Si B : C'est une des réponses correctes.
- Si C : La force d'un acide et celle de sa base conjuguée varient en sens opposé : $\ce{HNO3}$, acide fort, a une base conjuguée négligeable, alors que $\ce{H3PO4}$, acide faible, a une base conjuguée $\ce{H2PO4-}$ très faible mais plus forte que $\ce{NO3-}$.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-force

---
id: q-force-acide-base-symbo-t3-002
concept: force-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
misconception: force-acide-base--hydroxyde-pris-pour-faible
date_validation: 2026-09-21
statut: validated
---

**Question**
Un élève affirme que « $\ce{KOH}$ et $\ce{NH3}$ sont tous deux des bases faibles ». Lesquelles de ces affirmations sont correctes ?

**Options**
- A. $\ce{KOH}$ libère en totalité ses ions $\ce{OH-}$ en solution aqueuse : c'est une base forte
- B. $\ce{KOH}$ est une base faible, car il ne contient qu'un seul ion $\ce{OH-}$ par unité formulaire
- C. $\ce{NH3}$ est une base faible : à 0,1 mol/L, seules 1,3 % des molécules captent un proton à l'eau
- D. L'acide conjugué de $\ce{NH3}$, l'ion $\ce{NH4+}$, est un acide négligeable

**Réponse correcte** : A,C

**Feedback correct**
$\ce{KOH}$ est un hydroxyde métallique : il libère en totalité l'ion $\ce{OH-}$, base forte (A). $\ce{NH3}$ ne capte qu'une petite fraction de protons à l'eau (1,3 % à 0,1 mol/L) : c'est une base faible (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Le nombre d'ions $\ce{OH-}$ par unité formulaire ne détermine pas la force : $\ce{KOH}$, comme $\ce{NaOH}$ ou $\ce{Ca(OH)2}$, libère ses ions $\ce{OH-}$ en totalité. C'est un hydroxyde, donc une base forte.
- Si C : C'est une des réponses correctes.
- Si D : $\ce{NH4+}$ est un acide faible (0,008 % de dissociation à 0,1 mol/L), et non négligeable : le conjugué d'une base faible est un acide faible.

**Référence manuel** : acido-basiques-intro-force

---

<!-- ============================================================ -->
<!-- CONCEPT : ph — pH d'une solution                             -->
<!-- 8 questions obligatoires : macro·T1, parti·T1, parti·T2×2    -->
<!-- (●², misconception echelle-lineaire), symbo·T1, symbo·T2×2   -->
<!-- (●²), symbo·T3                                               -->
<!-- ============================================================ -->

---
id: q-ph-macro-t1-001
concept: ph
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Lesquelles de ces affirmations sur le pH d'une solution aqueuse sont correctes ?

**Options**
- A. Plus le pH d'une solution est élevé, plus elle est acide
- B. Le pH d'une solution peut se mesurer avec un pH-mètre
- C. Plus le pH d'une solution est petit, plus elle est acide
- D. Le pH ne peut pas se mesurer : il ne peut que se calculer

**Réponse correcte** : B,C

**Feedback correct**
Le pH se mesure avec un pH-mètre, un papier pH ou un indicateur coloré (B). L'échelle varie en sens opposé de l'acidité : plus le pH est petit, plus la solution est acide (C).

**Feedback incorrect**
- Si A : L'échelle varie en sens opposé de l'acidité : au-dessus de 7, la solution est basique. Un pH élevé signifie une solution moins acide.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : Le pH est une grandeur mesurable : le pH-mètre, le papier pH et les indicateurs colorés le donnent directement.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-ph-parti-t1-001
concept: ph
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, que traduit le pH d'une solution aqueuse ?

**Options**
- A. La quantité d'acide dissous dans la solution, quelle que soit sa force
- B. La concentration en ions $\ce{H3O+}$ : plus le pH est bas, plus il y a d'ions $\ce{H3O+}$ par litre
- C. La concentration en ions $\ce{H3O+}$ : plus le pH est bas, moins il y a d'ions $\ce{H3O+}$ par litre
- D. Le nombre de molécules d'eau par litre de solution

**Réponse correcte** : B

**Feedback correct**
Le pH résume la concentration en ions $\ce{H3O+}$ : $\text{pH} = -\log[\ce{H3O+}]$. Comme le logarithme est précédé d'un signe moins, plus le pH est petit, plus il y a d'ions $\ce{H3O+}$ par litre.

**Feedback incorrect**
- Si A : Le pH traduit la concentration en ions $\ce{H3O+}$, non la quantité d'acide dissous : un acide faible et un acide fort de même concentration ne donnent pas le même pH.
- Si B : C'est la bonne réponse.
- Si C : Le sens est inversé : le pH varie en sens opposé de la concentration en $\ce{H3O+}$.
- Si D : Le pH ne compte pas les molécules d'eau : il traduit la concentration en ions $\ce{H3O+}$.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-ph-parti-t2-001
concept: ph
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
misconception: ph--echelle-lineaire
date_validation: 2026-09-21
statut: validated
---

**Question**
Une solution A a un pH de 2 et une solution B un pH de 6. À l'échelle des ions, laquelle de ces affirmations est correcte ?

**Options**
- A. A contient 4 fois plus d'ions $\ce{H3O+}$ que B
- B. A contient 3 fois plus d'ions $\ce{H3O+}$ que B
- C. B contient 10 000 fois plus d'ions $\ce{H3O+}$ que A
- D. A contient 10 000 fois plus d'ions $\ce{H3O+}$ que B

**Réponse correcte** : D

**Feedback correct**
Une unité de pH correspond à un facteur 10 sur la concentration en $\ce{H3O+}$ ; quatre unités d'écart donnent donc un facteur 10 000. Ici $[\ce{H3O+}]$ vaut $10^{-2}$ mol/L pour A et $10^{-6}$ mol/L pour B.

**Feedback incorrect**
- Si A : L'échelle de pH n'est pas linéaire : elle est logarithmique. Chaque unité d'écart multiplie la concentration par 10, de sorte que 4 unités d'écart donnent un facteur $10^4$ et non un facteur 4.
- Si B : Le rapport 6/2 n'a pas de sens ici : le pH est un logarithme, non une concentration. C'est l'écart de pH qui compte, avec un facteur 10 par unité.
- Si C : Le sens est inversé : le pH le plus bas correspond à la solution la plus riche en ions $\ce{H3O+}$, donc à A.
- Si D : C'est la bonne réponse.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-ph-parti-t2-002
concept: ph
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
misconception: ph--echelle-lineaire
date_validation: 2026-09-21
statut: validated
---

**Question**
On dilue 100 fois une solution d'acide nitrique $\ce{HNO3}$ de pH 1,5. Quel est le pH de la solution diluée ?

**Options**
- A. 0,015
- B. 2,5
- C. 3,5
- D. 150

**Réponse correcte** : C

**Feedback correct**
Diluer 100 fois divise la concentration en $\ce{H3O+}$ par 100, soit $10^2$. Comme une unité de pH correspond à un facteur 10, le pH augmente de 2 unités : 1,5 + 2 = 3,5.

**Feedback incorrect**
- Si A : Ce n'est pas le pH qui est divisé par 100, mais la concentration en $\ce{H3O+}$. Le pH est un logarithme : il augmente de 2 unités.
- Si B : Une augmentation d'une unité de pH correspond à une dilution par 10. Pour une dilution par 100, il faut deux unités.
- Si C : C'est la bonne réponse.
- Si D : Ce n'est pas le pH qui est multiplié par 100, mais la concentration en $\ce{H3O+}$ qui est divisée par 100. Le pH augmente de 2 unités seulement.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-ph-symbo-t1-001
concept: ph
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Lesquelles de ces relations sont correctes ?

**Options**
- A. $\text{pH} = -\log[\ce{H3O+}]$
- B. $\text{pH} = \log[\ce{H3O+}]$
- C. $[\ce{H3O+}] = 10^{\text{pH}}$
- D. $[\ce{H3O+}] = 10^{-\text{pH}}$

**Réponse correcte** : A,D

**Feedback correct**
Le pH est l'opposé du logarithme décimal de la concentration en $\ce{H3O+}$ : $\text{pH} = -\log[\ce{H3O+}]$ (A), ce qui s'écrit aussi $[\ce{H3O+}] = 10^{-\text{pH}}$ (D).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Sans le signe moins, on obtiendrait l'opposé du pH : une concentration inférieure à 1 mol/L donnerait un pH négatif.
- Si C : L'exposant doit être $-\text{pH}$ : avec $10^{\text{pH}}$, une solution de pH 3 aurait une concentration de 1000 mol/L, ce qui est absurde.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-ph-symbo-t2-001
concept: ph
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Quel est le pH d'une solution d'acide nitrique $\ce{HNO3}$ à $4{,}5 \times 10^{-3}$ mol/L ?

**Options**
- A. −2,35
- B. 5,40
- C. 2,35
- D. 11,65

**Réponse correcte** : C

**Feedback correct**
$\ce{HNO3}$ est un acide fort : sa dissociation est totale, donc $[\ce{H3O+}]$ est égale à la concentration initiale de l'acide, soit $4{,}5 \times 10^{-3}$ mol/L. Le pH vaut alors $-\log(4{,}5 \times 10^{-3})$, soit 2,35.

**Feedback incorrect**
- Si A : Un pH négatif correspondrait à une concentration supérieure à 1 mol/L. Le signe moins de la définition est déjà pris en compte : $-\log(4{,}5 \times 10^{-3})$ est positif.
- Si B : 5,40 est le résultat du logarithme népérien. Le pH utilise le logarithme décimal, celui de la touche « log » de la calculatrice.
- Si C : C'est la bonne réponse.
- Si D : 11,65 vaut 14 − 2,35 : le pH a été transformé en pOH. Pour un acide fort, $[\ce{H3O+}] = C_0$ donne directement le pH.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-ph-symbo-t2-002
concept: ph
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Quelle est la concentration en ions $\ce{H3O+}$ d'une solution de pH 4,6 ?

**Options**
- A. $3{,}98 \times 10^{4}$ mol/L
- B. $2{,}51 \times 10^{-5}$ mol/L
- C. $4{,}6 \times 10^{-5}$ mol/L
- D. $2{,}51 \times 10^{-4}$ mol/L

**Réponse correcte** : B

**Feedback correct**
$[\ce{H3O+}] = 10^{-\text{pH}} = 10^{-4{,}6} = 2{,}51 \times 10^{-5}$ mol/L. Cette valeur se situe entre $10^{-5}$ et $10^{-4}$ mol/L, plus près de $10^{-5}$, ce qui est cohérent avec un pH plus proche de 5 que de 4.

**Feedback incorrect**
- Si A : L'exposant doit être négatif : $10^{+4{,}6}$ donnerait une concentration de près de 40 000 mol/L, ce qui est absurde pour une solution acide usuelle.
- Si B : C'est la bonne réponse.
- Si C : Cette réponse recopie le pH dans la mantisse alors que le pH est l'exposant : $10^{-4{,}6}$ ne vaut pas $4{,}6 \times 10^{-5}$.
- Si D : $2{,}51 \times 10^{-4}$ mol/L correspondrait à un pH de 3,6. Un pH de 4,6 donne une concentration dix fois plus petite : $2{,}51 \times 10^{-5}$ mol/L.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-ph-symbo-t3-001
concept: ph
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
On dissout 0,112 L de chlorure d'hydrogène gazeux $\ce{HCl}$ (conditions TPN, $V_m = 22{,}4$ L/mol) dans de l'eau, de façon à obtenir 200 mL de solution. Quel est le pH de cette solution ?

**Options**
- A. −1,60
- B. 2,30
- C. 3,00
- D. 1,60

**Réponse correcte** : D

**Feedback correct**
n(HCl) = 0,112 / 22,4 = 0,00500 mol, puis C = 0,00500 / 0,200 = 0,0250 mol/L. $\ce{HCl}$ étant un acide fort, $[\ce{H3O+}] = 0{,}0250$ mol/L et $\text{pH} = -\log(0{,}0250) = 1{,}60$.

**Feedback incorrect**
- Si A : Le signe moins de la définition est déjà pris en compte : le pH d'une solution d'acide fort de concentration inférieure à 1 mol/L est positif.
- Si B : Ce résultat oublie de diviser par le volume : la concentration se calcule en mol/L, et non en mol.
- Si C : 3,00 vient du produit n × V au lieu du quotient n / V : la concentration est une quantité de matière par litre de solution.
- Si D : C'est la bonne réponse.

**Référence manuel** : acido-basiques-intro-ph

---

<!-- ============================================================ -->
<!-- CONCEPT : poh — pOH et produit ionique de l'eau              -->
<!-- 5 questions obligatoires : symbo·T1×2 (●², poh--ph-acidite-  -->
<!-- poh-basicite / poh--kw-egal-10-7), symbo·T2×2 (●²), symbo·T3 -->
<!-- ============================================================ -->

---
id: q-poh-symbo-t1-001
concept: poh
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 1
misconception: poh--ph-acidite-poh-basicite
date_validation: 2026-09-21
statut: validated
---

**Question**
Un élève affirme : « le pH mesure l'acidité d'une solution et le pOH sa basicité ; ce sont deux grandeurs indépendantes ». Lesquelles de ces affirmations sont correctes ?

**Options**
- A. Le pH et le pOH décrivent la même solution : ce sont deux expressions d'une même situation, liées par $\text{pH} + \text{pOH} = 14$ à 25 °C
- B. Une solution de pH 3 a un pOH de 11
- C. Le pOH ne se calcule que pour les bases, et le pH que pour les acides
- D. Connaître le pH d'une solution ne renseigne pas sur son pOH

**Réponse correcte** : A,B

**Feedback correct**
Le pH et le pOH sont le reflet l'un de l'autre, avec pH 7 comme axe : $\text{pH} + \text{pOH} = 14$ à 25 °C (A). Une solution de pH 3 a donc un pOH de 14 − 3 = 11 (B).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : C'est une des réponses correctes.
- Si C : Le pH et le pOH se calculent pour n'importe quelle solution aqueuse : une solution acide a un pH bas et un pOH élevé, une solution basique l'inverse.
- Si D : Les deux grandeurs sont liées par $\text{pH} + \text{pOH} = 14$ : connaître l'une donne immédiatement l'autre.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-poh-symbo-t1-002
concept: poh
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 1
misconception: poh--kw-egal-10-7
date_validation: 2026-09-21
statut: validated
---

**Question**
À 25 °C, lesquelles de ces relations sont correctes pour une solution aqueuse ?

**Options**
- A. $[\ce{H3O+}] \times [\ce{OH-}] = 1{,}0 \times 10^{-14}$
- B. $[\ce{H3O+}] \times [\ce{OH-}] = 1{,}0 \times 10^{-7}$
- C. $\text{pH} + \text{pOH} = 14$
- D. $\text{pH} + \text{pOH} = 7$

**Réponse correcte** : A,C

**Feedback correct**
Dans l'eau pure, $[\ce{H3O+}] = [\ce{OH-}] = 10^{-7}$ mol/L : leur produit vaut $10^{-14}$ (A). En prenant le $-\log$ des deux côtés, on obtient $\text{pH} + \text{pOH} = 14$ (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : $10^{-7}$ mol/L est la concentration de chacun des deux ions dans l'eau pure, et non leur produit, qui vaut $10^{-7} \times 10^{-7} = 10^{-14}$.
- Si C : C'est une des réponses correctes.
- Si D : Dans l'eau pure, le pH et le pOH valent chacun 7, donc leur somme vaut 14, et non 7.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-poh-symbo-t2-001
concept: poh
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Quel est le pH d'une solution d'hydroxyde de sodium $\ce{NaOH}$ à $5{,}0 \times 10^{-3}$ mol/L (25 °C) ?

**Options**
- A. −2,30
- B. 2,30
- C. 11,70
- D. 16,30

**Réponse correcte** : C

**Feedback correct**
$\ce{NaOH}$ est une base forte : $[\ce{OH-}]$ est égale à la concentration initiale de la base, soit $5{,}0 \times 10^{-3}$ mol/L. Le pOH vaut $-\log(5{,}0 \times 10^{-3})$, soit 2,30, puis $\text{pH} = 14 - \text{pOH}$, soit 14 − 2,30 = 11,70.

**Feedback incorrect**
- Si A : Un pOH négatif correspondrait à une concentration en $\ce{OH-}$ supérieure à 1 mol/L. Le signe moins de la définition est déjà pris en compte, et le résultat est de toute façon un pOH, pas un pH.
- Si B : 2,30 est le pOH, pas le pH : il faut « retourner l'image » avec $\text{pH} = 14 - \text{pOH}$.
- Si C : C'est la bonne réponse.
- Si D : 16,30 vient de 14 + pOH. Il faut soustraire : $\text{pH} = 14 - \text{pOH}$. Dans les solutions usuelles, le pH ne dépasse d'ailleurs pas 14.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-poh-symbo-t2-002
concept: poh
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Quel est le pH d'une solution d'hydroxyde de calcium $\ce{Ca(OH)2}$ à $5{,}0 \times 10^{-3}$ mol/L (25 °C) ?

**Options**
- A. 2,00
- B. 11,70
- C. 11,40
- D. 12,00

**Réponse correcte** : D

**Feedback correct**
$\ce{Ca(OH)2}$ libère 2 ions $\ce{OH-}$ par unité formulaire : $[\ce{OH-}]$ vaut le double de la concentration de la base, soit $1{,}0 \times 10^{-2}$ mol/L. Le pOH vaut 2,00 et le pH vaut 14 − 2,00 = 12,00.

**Feedback incorrect**
- Si A : 2,00 est le pOH, pas le pH : il faut « retourner l'image » avec $\text{pH} = 14 - \text{pOH}$.
- Si B : 11,70 est le pH d'une solution où $[\ce{OH-}] = 5{,}0 \times 10^{-3}$ mol/L : ce calcul oublie que $\ce{Ca(OH)2}$ libère deux ions $\ce{OH-}$ par unité formulaire.
- Si C : 11,40 correspond à $[\ce{OH-}] = 2{,}5 \times 10^{-3}$ mol/L : la concentration a été divisée par 2 au lieu d'être multipliée par 2.
- Si D : C'est la bonne réponse.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-poh-symbo-t3-001
concept: poh
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
Une solution aqueuse à 25 °C a un pH de 10,5. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. La solution est basique : elle ne contient plus d'ions $\ce{H3O+}$
- B. Son pOH vaut 3,5
- C. Sa concentration en ions $\ce{H3O+}$ vaut $3{,}2 \times 10^{-11}$ mol/L
- D. Sa concentration en ions $\ce{OH-}$ vaut $3{,}2 \times 10^{-11}$ mol/L

**Réponse correcte** : B,C

**Feedback correct**
Le pOH vaut 14 − 10,5 = 3,5 (B). La concentration en $\ce{H3O+}$ vaut $10^{-10{,}5} = 3{,}2 \times 10^{-11}$ mol/L (C) ; la solution est basique car $[\ce{OH-}] = 10^{-3{,}5} = 3{,}2 \times 10^{-4}$ mol/L domine.

**Feedback incorrect**
- Si A : Même dans une solution basique, il reste des ions $\ce{H3O+}$ : très peu, mais jamais zéro. Ici, $3{,}2 \times 10^{-11}$ mol/L.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : Les deux valeurs sont inversées : $[\ce{OH-}] = 10^{-\text{pOH}} = 3{,}2 \times 10^{-4}$ mol/L, tandis que $3{,}2 \times 10^{-11}$ mol/L est $[\ce{H3O+}]$.

**Référence manuel** : acido-basiques-intro-ph

---

<!-- ============================================================ -->
<!-- CONCEPT : milieu-acide-neutre-basique — Milieu acide,        -->
<!-- neutre ou basique                                            -->
<!-- 4 questions obligatoires : macro·T1, parti·T1×2 (●², ph-     -->
<!-- acide-plus-doh / ajout-acide-reste-neutre), parti·T2         -->
<!-- ============================================================ -->

---
id: q-milieu-acide-neutre-basique-macro-t1-001
concept: milieu-acide-neutre-basique
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
À 25 °C, lesquelles de ces solutions sont basiques (pH mesuré entre parenthèses) ?

**Options**
- A. L'eau distillée (pH 7,0)
- B. Une solution d'hydrogénocarbonate de sodium (pH 8,3)
- C. Le café (pH 5,0)
- D. L'eau savonneuse (pH 10,0)

**Réponse correcte** : B,D

**Feedback correct**
À 25 °C, une solution est basique lorsque son pH est supérieur à 7 : c'est le cas de la solution d'hydrogénocarbonate de sodium (8,3) et de l'eau savonneuse (10,0).

**Feedback incorrect**
- Si A : Un pH de 7,0 correspond à une solution neutre à 25 °C, ni acide ni basique.
- Si B : C'est une des réponses correctes.
- Si C : Un pH de 5,0 est inférieur à 7 : le café est légèrement acide.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-milieu-acide-neutre-basique-parti-t1-001
concept: milieu-acide-neutre-basique
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: milieu-acide-neutre-basique--ph-acide-plus-doh
date_validation: 2026-09-21
statut: validated
---

**Question**
Une solution aqueuse a un pH de 3. Lesquelles de ces affirmations sur les ions qu'elle contient sont correctes ?

**Options**
- A. Elle contient plus d'ions $\ce{H3O+}$ que d'ions $\ce{OH-}$
- B. Elle contient plus d'ions $\ce{OH-}$ que d'ions $\ce{H3O+}$
- C. Elle contient encore des ions $\ce{OH-}$, en très petite quantité
- D. Elle ne contient aucun ion $\ce{OH-}$

**Réponse correcte** : A,C

**Feedback correct**
À pH 3, $[\ce{H3O+}] = 10^{-3}$ mol/L domine largement (A). Mais le produit $[\ce{H3O+}] \times [\ce{OH-}] = 10^{-14}$ impose $[\ce{OH-}] = 10^{-11}$ mol/L : très peu, mais jamais zéro, car l'autoprotolyse en refabrique sans cesse (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : C'est l'inverse : un pH inférieur à 7 signifie $[\ce{H3O+}] > [\ce{OH-}]$. La solution est acide parce que les ions $\ce{H3O+}$ dominent.
- Si C : C'est une des réponses correctes.
- Si D : Tant qu'il y a de l'eau, l'autoprotolyse fabrique des ions $\ce{OH-}$ : ils deviennent très rares, mais jamais nuls.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-milieu-acide-neutre-basique-parti-t1-002
concept: milieu-acide-neutre-basique
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: milieu-acide-neutre-basique--ajout-acide-reste-neutre
date_validation: 2026-09-21
statut: validated
---

**Question**
On ajoute quelques gouttes d'acide chlorhydrique $\ce{HCl}$ à de l'eau pure (pH 7 à 25 °C). Lesquelles de ces affirmations, à l'échelle des ions, sont correctes ?

**Options**
- A. Le pH reste égal à 7, car l'eau pure est neutre
- B. Les ions $\ce{H3O+}$ apportés par $\ce{HCl}$ s'ajoutent à ceux de l'eau : $[\ce{H3O+}]$ augmente et le pH devient inférieur à 7
- C. Les ions $\ce{OH-}$ de l'eau deviennent très rares, mais l'autoprotolyse en refabrique un peu
- D. Les ions $\ce{OH-}$ de l'eau disparaissent complètement

**Réponse correcte** : B,C

**Feedback correct**
Les ions $\ce{H3O+}$ apportés par l'acide fort dominent : $[\ce{H3O+}] > [\ce{OH-}]$ et le pH passe sous 7 (B). Les $\ce{H3O+}$ retrouvent des ions $\ce{OH-}$ de l'eau et les transforment en eau : les $\ce{OH-}$ deviennent rares, mais jamais nuls, car l'autoprotolyse en refabrique un peu (C).

**Feedback incorrect**
- Si A : Le pH de 7 est celui de l'eau pure, sans acide ni base ajoutés. Dès qu'on ajoute $\ce{HCl}$, $[\ce{H3O+}]$ augmente et le pH baisse.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : Tant qu'il reste de l'eau, l'autoprotolyse refabrique des ions $\ce{OH-}$ : ils deviennent très rares, mais ne disparaissent jamais complètement.

**Référence manuel** : acido-basiques-intro-ph

---
id: q-milieu-acide-neutre-basique-parti-t2-001
concept: milieu-acide-neutre-basique
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
À 25 °C, une solution contient $[\ce{H3O+}] = 2{,}0 \times 10^{-9}$ mol/L et $[\ce{OH-}] = 5{,}0 \times 10^{-6}$ mol/L. Laquelle de ces descriptions est correcte ?

**Options**
- A. Elle est neutre, car les deux ions sont présents
- B. Elle est acide, car elle contient des ions $\ce{H3O+}$
- C. Elle est basique, car $[\ce{OH-}] > [\ce{H3O+}]$
- D. Elle est basique, car elle ne contient plus d'ions $\ce{H3O+}$

**Réponse correcte** : C

**Feedback correct**
Une solution est basique lorsque $[\ce{OH-}] > [\ce{H3O+}]$, ce qui correspond à un pH supérieur à 7. Ici les ions $\ce{OH-}$ sont 2500 fois plus concentrés que les ions $\ce{H3O+}$, et $\text{pH} = -\log(2{,}0 \times 10^{-9}) = 8{,}7$.

**Feedback incorrect**
- Si A : Les deux ions sont présents dans toute solution aqueuse, y compris acide ou basique : c'est le rapport de leurs concentrations qui décide. Une solution n'est neutre que si $[\ce{H3O+}] = [\ce{OH-}]$.
- Si B : La présence d'ions $\ce{H3O+}$ n'est pas un critère : ils existent dans toute solution aqueuse. Ce qui compte est l'ion qui domine, ici $\ce{OH-}$.
- Si C : C'est la bonne réponse.
- Si D : Il reste des ions $\ce{H3O+}$ ($2{,}0 \times 10^{-9}$ mol/L) : très peu, mais jamais zéro. Le caractère basique vient de la domination des ions $\ce{OH-}$, non de la disparition des ions $\ce{H3O+}$.

**Référence manuel** : acido-basiques-intro-ph

---

<!-- ============================================================ -->
<!-- SOUS-PARTIE 7C                                               -->
<!-- ============================================================ -->

---

<!-- ============================================================ -->
<!-- CONCEPT : neutralisation — Neutralisation acide fort / base  -->
<!-- forte                                                        -->
<!-- 10 questions obligatoires : macro·T1×2 (●², toujours-ph-7),  -->
<!-- parti·T1×2 (●², melange-physique-ou-destruction), parti·T2,  -->
<!-- symbo·T1, symbo·T2×2 (●²), symbo·T3×2 (●²)                   -->
<!-- ============================================================ -->

---
id: q-neutralisation-macro-t1-001
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
misconception: neutralisation--toujours-ph-7
date_validation: 2026-09-21
statut: validated
---

**Question**
On mélange 20,0 mL d'acide chlorhydrique $\ce{HCl}$ à 0,10 mol/L et 20,0 mL de soude $\ce{NaOH}$ à 0,10 mol/L. Laquelle de ces affirmations sur la solution obtenue est correcte ?

**Options**
- A. Elle est acide, car $\ce{HCl}$ est un acide
- B. Elle est neutre, car une neutralisation donne toujours une solution de pH 7, quelles que soient les quantités mélangées
- C. Elle est neutre (pH 7 à 25 °C) : l'acide et la base ont été mélangés en proportions stœchiométriques
- D. Elle est basique, car $\ce{NaOH}$ est une base

**Réponse correcte** : C

**Feedback correct**
Les quantités sont égales : $n(\ce{HCl})$ et $n(\ce{NaOH})$ valent chacune $2{,}00 \times 10^{-3}$ mol, soit des proportions stœchiométriques. La solution ne contient plus que de l'eau et du sel $\ce{NaCl}$ dissous : elle est neutre.

**Feedback incorrect**
- Si A : L'acide est entièrement neutralisé par la base : les quantités de $\ce{H3O+}$ et de $\ce{OH-}$ sont égales, aucun des deux n'est en excès. La solution n'est pas acide.
- Si B : La conclusion est juste ici, mais le raisonnement est faux : une neutralisation ne donne une solution neutre que si les quantités d'acide et de base sont dans les proportions stœchiométriques. Si l'un des deux est en excès, la solution finale est acide ou basique.
- Si C : C'est la bonne réponse.
- Si D : La base est entièrement neutralisée par l'acide : aucun des deux n'est en excès. La solution n'est pas basique.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-neutralisation-macro-t1-002
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
misconception: neutralisation--toujours-ph-7
date_validation: 2026-09-21
statut: validated
---

**Question**
On mélange 15,0 mL d'acide chlorhydrique $\ce{HCl}$ à 0,10 mol/L et 25,0 mL de soude $\ce{NaOH}$ à 0,10 mol/L. Laquelle de ces affirmations sur la solution obtenue est correcte ?

**Options**
- A. Elle est neutre, puisqu'on a mélangé un acide et une base
- B. Elle est basique : la base est en excès, il reste des ions $\ce{OH-}$ après la neutralisation
- C. Elle est acide, car $\ce{HCl}$ est un acide fort
- D. Elle est neutre : une neutralisation donne toujours du sel et de l'eau, donc un pH de 7

**Réponse correcte** : B

**Feedback correct**
$n(\ce{HCl})$ vaut $1{,}5 \times 10^{-3}$ mol et $n(\ce{NaOH})$ vaut $2{,}5 \times 10^{-3}$ mol : la base est en excès de $1{,}0 \times 10^{-3}$ mol. Une fois l'acide entièrement neutralisé, il reste des ions $\ce{OH-}$ : la solution est basique.

**Feedback incorrect**
- Si A : Mélanger un acide et une base ne suffit pas à obtenir une solution neutre : elle n'est neutre que si leurs quantités sont dans les proportions stœchiométriques. Ici la base est en excès.
- Si B : C'est la bonne réponse.
- Si C : $\ce{HCl}$ est bien un acide fort, mais c'est le réactif limitant : il est entièrement consommé. Ce qui reste en excès est de la base.
- Si D : Le mélange forme bien du sel et de l'eau, mais l'excès de $\ce{NaOH}$ laisse des ions $\ce{OH-}$ dans la solution, qui est donc basique.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-neutralisation-parti-t1-001
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: neutralisation--melange-physique-ou-destruction
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, lesquelles de ces affirmations décrivent correctement ce qui se passe lorsqu'on mélange $\ce{HCl}$ (aq) et $\ce{NaOH}$ (aq) en proportions stœchiométriques ?

**Options**
- A. L'acide est détruit par la base : les atomes de $\ce{HCl}$ disparaissent
- B. Les ions $\ce{H3O+}$ et $\ce{OH-}$ réagissent entre eux pour former des molécules d'eau
- C. Il ne reste que des molécules d'eau et des ions $\ce{Na+}$ et $\ce{Cl-}$ (le sel dissous)
- D. Les ions $\ce{H3O+}$ et $\ce{OH-}$ se mélangent sans réagir : les deux restent présents en quantités égales

**Réponse correcte** : B,C

**Feedback correct**
La neutralisation est une réaction entre particules : $\ce{H3O+ + OH- -> 2 H2O}$ (B), l'inverse de l'autoprotolyse de l'eau. Les ions $\ce{Na+}$ et $\ce{Cl-}$ ne participent pas à la réaction : il ne reste que de l'eau et du sel dissous (C).

**Feedback incorrect**
- Si A : Ce n'est pas une destruction : les atomes de $\ce{HCl}$ se retrouvent dans l'ion $\ce{Cl-}$ et dans les molécules d'eau formées. Rien ne disparaît, les particules se réorganisent.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : Si les deux ions étaient présents sans réagir, la solution ne serait pas neutralisée. Ils réagissent pour former de l'eau : il n'en reste que les traces que fournit l'autoprotolyse.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-neutralisation-parti-t1-002
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: neutralisation--melange-physique-ou-destruction
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, lesquelles de ces affirmations décrivent correctement ce qui se passe lorsqu'on mélange $\ce{HNO3}$ (aq) et $\ce{KOH}$ (aq) en proportions stœchiométriques ?

**Options**
- A. Un proton passe d'un ion $\ce{H3O+}$ à un ion $\ce{OH-}$ : il se forme deux molécules d'eau
- B. Il ne se passe aucune réaction : les deux solutions se mélangent simplement
- C. Les ions $\ce{K+}$ et $\ce{NO3-}$ ne participent pas à la réaction et restent en solution
- D. La base décompose l'acide nitrique en ses atomes

**Réponse correcte** : A,C

**Feedback correct**
La réaction est $\ce{H3O+ + OH- -> 2 H2O}$ : un proton passe de $\ce{H3O+}$ à $\ce{OH-}$ (A). Les ions $\ce{K+}$ et $\ce{NO3-}$ ne participent pas à la réaction : ils restent en solution sous forme de sel dissous (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Si rien ne se passait, la solution ne serait pas neutralisée. Les ions $\ce{H3O+}$ et $\ce{OH-}$ réagissent entre eux pour former de l'eau.
- Si C : C'est une des réponses correctes.
- Si D : La base ne décompose pas l'acide en atomes : la réaction est un transfert de proton, dans lequel les atomes se réorganisent sans disparaître.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-neutralisation-parti-t2-001
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
On mélange 20,0 mL de $\ce{HCl}$ à 0,020 mol/L et 20,0 mL de $\ce{Ca(OH)2}$ à 0,020 mol/L. En comparant les quantités d'ions $\ce{H3O+}$ et $\ce{OH-}$ apportés, laquelle de ces affirmations est correcte ?

**Options**
- A. Les ions $\ce{OH-}$ sont en excès : $n(\ce{OH-}) = 8{,}0 \times 10^{-4}$ mol contre $n(\ce{H3O+}) = 4{,}0 \times 10^{-4}$ mol ; la solution est basique
- B. Les ions $\ce{H3O+}$ et $\ce{OH-}$ sont en quantités égales ($4{,}0 \times 10^{-4}$ mol chacun) : la solution est neutre
- C. Les ions $\ce{H3O+}$ sont en excès : la solution est acide
- D. Le réactif limitant est $\ce{Ca(OH)2}$ : il reste des ions $\ce{H3O+}$ dans la solution

**Réponse correcte** : A

**Feedback correct**
$n(\ce{H3O+})$ vaut $4{,}0 \times 10^{-4}$ mol, apportées par $\ce{HCl}$. Chaque unité de $\ce{Ca(OH)2}$ libère 2 ions $\ce{OH-}$ : $n(\ce{OH-})$ vaut le double de $n(\ce{Ca(OH)2})$, soit $8{,}0 \times 10^{-4}$ mol. Les ions $\ce{OH-}$ sont en excès : la solution est basique.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Cette réponse oublie que $\ce{Ca(OH)2}$ libère 2 ions $\ce{OH-}$ par unité formulaire : $n(\ce{OH-})$ vaut $8{,}0 \times 10^{-4}$ mol, et non $4{,}0 \times 10^{-4}$ mol. Des concentrations et des volumes égaux ne suffisent pas à conclure.
- Si C : Les ions $\ce{H3O+}$ sont en quantité moindre : $4{,}0 \times 10^{-4}$ mol contre $8{,}0 \times 10^{-4}$ mol d'ions $\ce{OH-}$.
- Si D : C'est l'inverse : les ions $\ce{OH-}$ sont en excès, donc c'est l'acide qui est entièrement consommé. Il ne reste pas d'ions $\ce{H3O+}$ en quantité notable.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-neutralisation-symbo-t1-001
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Lesquelles de ces équations représentent une neutralisation d'un acide fort par une base forte ?

**Options**
- A. $\ce{AH + OH- -> A- + H2O}$
- B. $\ce{HCl + H2O -> Cl- + H3O+}$
- C. $\ce{HBr + LiOH -> LiBr + H2O}$
- D. $\ce{KOH + NaCl -> KCl + NaOH}$

**Réponse correcte** : A,C

**Feedback correct**
Une neutralisation fait réagir un acide avec une base : $\ce{AH + OH- -> A- + H2O}$ (A), ou, avec les espèces complètes, $\ce{HBr + LiOH -> LiBr + H2O}$ (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : C'est la réaction de l'acide fort avec l'eau, qui forme $\ce{H3O+}$. Aucune base forte n'intervient : ce n'est pas la neutralisation.
- Si C : C'est une des réponses correctes.
- Si D : Il n'y a aucun acide dans ce mélange : $\ce{KOH}$ est une base et $\ce{NaCl}$ un sel neutre. Aucun proton n'est échangé et il ne se forme pas d'eau.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-neutralisation-symbo-t2-001
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Quel volume de soude $\ce{NaOH}$ à 0,15 mol/L faut-il verser dans 25,0 mL de $\ce{HBr}$ à 0,12 mol/L pour neutraliser exactement l'acide ?

**Options**
- A. 20,0 mL
- B. 25,0 mL
- C. 31,3 mL
- D. 40,0 mL

**Réponse correcte** : A

**Feedback correct**
$\ce{HBr + NaOH -> NaBr + H2O}$ : 1 mol de $\ce{HBr}$ réagit avec 1 mol de $\ce{NaOH}$. $n(\ce{HBr})$ vaut $0{,}12 \text{ mol/L} \times 0{,}0250 \text{ L}$, soit $3{,}00 \times 10^{-3}$ mol, donc $V(\ce{NaOH})$ vaut $3{,}00 \times 10^{-3} \text{ mol} / 0{,}15 \text{ mol/L}$, soit 0,0200 L, c'est-à-dire 20,0 mL.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Des volumes égaux ne conviennent que si les deux solutions ont la même concentration. Ici $\ce{NaOH}$ est plus concentrée (0,15 mol/L) que $\ce{HBr}$ (0,12 mol/L) : il en faut moins.
- Si C : Le calcul est à l'envers : 31,3 mL vient de 25,0 mL × 0,15 / 0,12. Il faut diviser la quantité de matière de $\ce{HBr}$ par la concentration de $\ce{NaOH}$.
- Si D : $\ce{HBr}$ et $\ce{NaOH}$ réagissent mole à mole : il n'y a aucun facteur 2 dans cette réaction.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-neutralisation-symbo-t2-002
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Quel volume d'acide nitrique $\ce{HNO3}$ à 0,040 mol/L faut-il verser dans 20,0 mL de $\ce{Ca(OH)2}$ à 0,030 mol/L pour neutraliser exactement la base ?

**Options**
- A. 15,0 mL
- B. 30,0 mL
- C. 20,0 mL
- D. 60,0 mL

**Réponse correcte** : B

**Feedback correct**
$\ce{Ca(OH)2 + 2 HNO3 -> Ca(NO3)2 + 2 H2O}$ : 1 mol de $\ce{Ca(OH)2}$ réagit avec 2 mol de $\ce{HNO3}$. $n(\ce{Ca(OH)2})$ vaut $6{,}0 \times 10^{-4}$ mol, donc $n(\ce{HNO3})$ vaut $1{,}2 \times 10^{-3}$ mol et $V(\ce{HNO3})$ vaut $1{,}2 \times 10^{-3} \text{ mol} / 0{,}040 \text{ mol/L}$, soit 0,0300 L, c'est-à-dire 30,0 mL.

**Feedback incorrect**
- Si A : 15,0 mL oublie le facteur 2 : $\ce{Ca(OH)2}$ libère 2 ions $\ce{OH-}$ et demande donc 2 $\ce{HNO3}$ par unité formulaire.
- Si B : C'est la bonne réponse.
- Si C : Des volumes égaux ne conviendraient que si les quantités de $\ce{H3O+}$ et de $\ce{OH-}$ étaient égales. Ici 20,0 mL de $\ce{HNO3}$ apportent $8{,}0 \times 10^{-4}$ mol de $\ce{H3O+}$, contre $1{,}2 \times 10^{-3}$ mol d'ions $\ce{OH-}$.
- Si D : 60,0 mL apporte $2{,}4 \times 10^{-3}$ mol de $\ce{HNO3}$, soit le double de ce qu'il faut : le facteur 2 a été appliqué deux fois.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-neutralisation-symbo-t3-001
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
On mélange 40,0 mL d'acide chlorhydrique $\ce{HCl}$ à 0,15 mol/L et 25,0 mL de soude $\ce{NaOH}$ à 0,10 mol/L. Quel est le pH de la solution obtenue ?

**Options**
- A. 2,46
- B. 1,27
- C. 1,06
- D. 12,73

**Réponse correcte** : B

**Feedback correct**
$n(\ce{HCl})$ vaut $6{,}0 \times 10^{-3}$ mol et $n(\ce{NaOH})$ vaut $2{,}5 \times 10^{-3}$ mol : $\ce{NaOH}$ est le réactif limitant, et il reste $3{,}5 \times 10^{-3}$ mol de $\ce{H3O+}$. Le volume final est de 40,0 + 25,0 = 65,0 mL, donc $[\ce{H3O+}]$ vaut $3{,}5 \times 10^{-3} \text{ mol} / 0{,}0650 \text{ L}$, soit $5{,}4 \times 10^{-2}$ mol/L, et le pH vaut 1,27.

**Feedback incorrect**
- Si A : Cette réponse oublie de diviser par le volume final : $[\ce{H3O+}]$ est une concentration, en mol/L, et non une quantité de matière.
- Si B : C'est la bonne réponse.
- Si C : Il faut diviser par le volume total du mélange (65,0 mL), et non par le seul volume d'acide (40,0 mL) : l'ajout de la base dilue la solution.
- Si D : Un pH de 12,73 serait celui d'une solution basique. Or c'est l'acide qui est en excès : la solution est acide, son pH est inférieur à 7.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-neutralisation-symbo-t3-002
concept: neutralisation
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
On mélange 30,0 mL d'acide nitrique $\ce{HNO3}$ à 0,10 mol/L et 50,0 mL de potasse $\ce{KOH}$ à 0,10 mol/L. Quel est le pH de la solution obtenue ?

**Options**
- A. 1,43
- B. 1,60
- C. 11,30
- D. 12,40

**Réponse correcte** : D

**Feedback correct**
$n(\ce{HNO3})$ vaut $3{,}0 \times 10^{-3}$ mol et $n(\ce{KOH})$ vaut $5{,}0 \times 10^{-3}$ mol : $\ce{HNO3}$ est le réactif limitant, et il reste $2{,}0 \times 10^{-3}$ mol d'ions $\ce{OH-}$. Le volume final est de 30,0 + 50,0 = 80,0 mL, donc $[\ce{OH-}]$ vaut $2{,}0 \times 10^{-3} \text{ mol} / 0{,}0800 \text{ L}$, soit $2{,}5 \times 10^{-2}$ mol/L. Le pOH vaut 1,60 et le pH vaut 14 − 1,60 = 12,40.

**Feedback incorrect**
- Si A : 1,43 correspond à un calcul de $[\ce{H3O+}]$ avec la seule quantité d'acide, en ignorant la base. C'est la base qui est en excès : la solution est basique.
- Si B : 1,60 est le pOH : il faut encore « retourner l'image » avec $\text{pH} = 14 - \text{pOH}$.
- Si C : 11,30 oublie de diviser la quantité d'ions $\ce{OH-}$ en excès par le volume final (0,0800 L) : $[\ce{OH-}]$ est une concentration.
- Si D : C'est la bonne réponse.

**Référence manuel** : acido-basiques-intro-neutralisation

---

<!-- ============================================================ -->
<!-- CONCEPT : conductivite — Conductivité électrique des         -->
<!-- solutions                                                    -->
<!-- 5 questions obligatoires : macro·T1×2 (●², conductivite--    -->
<!-- eau-pure-conductrice), macro·T2, parti·T1, parti·T2          -->
<!-- ============================================================ -->

---
id: q-conductivite-macro-t1-001
concept: conductivite
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
misconception: conductivite--eau-pure-conductrice
date_validation: 2026-09-21
statut: validated
---

**Question**
On plonge deux électrodes, reliées à une ampoule et à un générateur, dans de l'eau distillée. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. L'ampoule reste éteinte : l'eau distillée contient trop peu d'ions pour conduire le courant
- B. L'ampoule s'allume franchement, car l'eau contient beaucoup d'ions $\ce{H3O+}$ et $\ce{OH-}$
- C. Si l'on dissout du chlorure de sodium $\ce{NaCl}$ dans l'eau, l'ampoule s'allume : les ions $\ce{Na+}$ et $\ce{Cl-}$ sont mobiles
- D. Seule une solution acide ou basique peut conduire le courant

**Réponse correcte** : A,C

**Feedback correct**
Une solution conduit l'électricité si et seulement si elle contient des ions mobiles en quantité suffisante. L'autoprotolyse de l'eau en produit trop peu pour allumer l'ampoule (A), alors que $\ce{NaCl}$ dissous libère des ions $\ce{Na+}$ et $\ce{Cl-}$ (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : L'autoprotolyse ne forme que $10^{-7}$ mol/L de chaque ion : c'est trop peu pour allumer l'ampoule. L'eau distillée est considérée comme non conductrice.
- Si C : C'est une des réponses correctes.
- Si D : Une solution peut conduire sans être ni acide ni basique : $\ce{NaCl}$ dissous en est la preuve. Ce qui compte est la présence d'ions mobiles.

**Référence manuel** : acido-basiques-intro-conductivite

---
id: q-conductivite-macro-t1-002
concept: conductivite
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
misconception: conductivite--eau-pure-conductrice
date_validation: 2026-09-21
statut: validated
---

**Question**
On compare deux béchers : l'un contient de l'eau distillée, l'autre une solution de glucose $\ce{C6H12O6}$ dans l'eau. On plonge les mêmes électrodes, reliées à une ampoule, dans chacun. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. L'eau distillée conduit bien, car elle contient des ions $\ce{H3O+}$ et $\ce{OH-}$ en abondance
- B. L'eau distillée conduit très mal : l'autoprotolyse produit très peu d'ions
- C. Une solution conduit dès qu'un composé est dissous dans l'eau
- D. La solution de glucose ne conduit pas mieux que l'eau distillée : le glucose reste sous forme de molécules neutres, sans ions mobiles

**Réponse correcte** : B,D

**Feedback correct**
Ce sont les ions mobiles qui transportent le courant. L'eau distillée en contient très peu (B), et le glucose, composé moléculaire, ne libère aucun ion : sa solution ne conduit pas mieux (D).

**Feedback incorrect**
- Si A : Les ions $\ce{H3O+}$ et $\ce{OH-}$ de l'eau distillée existent, mais à raison de $10^{-7}$ mol/L seulement : c'est bien trop peu pour conduire de façon notable.
- Si B : C'est une des réponses correctes.
- Si C : Il faut que le composé dissous libère des ions. Le glucose reste sous forme de molécules neutres : sa solution ne conduit pas.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-conductivite

---
id: q-conductivite-macro-t2-001
concept: conductivite
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
On compare trois liquides à la même concentration de 0,1 mol/L pour les solutions : soude $\ce{NaOH}$ (aq), ammoniac $\ce{NH3}$ (aq) et eau distillée. Quel classement, du moins conducteur au plus conducteur, est correct ?

**Options**
- A. $\ce{NaOH}$ < $\ce{NH3}$ < eau distillée
- B. $\ce{NH3}$ < eau distillée < $\ce{NaOH}$
- C. eau distillée < $\ce{NH3}$ < $\ce{NaOH}$
- D. eau distillée < $\ce{NaOH}$ < $\ce{NH3}$

**Réponse correcte** : C

**Feedback correct**
L'eau distillée contient très peu d'ions : elle conduit le moins. $\ce{NH3}$, base faible (protonation partielle), en forme peu ; $\ce{NaOH}$, base forte (dissociation totale), en libère le plus à cette concentration.

**Feedback incorrect**
- Si A : Ce classement est à l'envers : l'eau distillée, presque sans ions, est la moins conductrice, et $\ce{NaOH}$, dissocié en totalité, la plus conductrice.
- Si B : $\ce{NH3}$ capte des protons à l'eau et forme des ions $\ce{NH4+}$ et $\ce{OH-}$ : sa solution conduit, faiblement, mais mieux que l'eau distillée.
- Si C : C'est la bonne réponse.
- Si D : À même concentration, $\ce{NaOH}$, base forte dissociée en totalité, produit plus d'ions que $\ce{NH3}$, base faible : il conduit mieux.

**Référence manuel** : acido-basiques-intro-conductivite

---
id: q-conductivite-parti-t1-001
concept: conductivite
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, qu'est-ce qui transporte le courant électrique dans une solution aqueuse d'acide chlorhydrique ?

**Options**
- A. Des électrons libres, qui circulent entre les molécules d'eau
- B. Des ions mobiles : les ions $\ce{H3O+}$ et $\ce{Cl-}$
- C. Les molécules $\ce{HCl}$ restées intactes en solution
- D. Les molécules d'eau, qui se déplacent d'une électrode à l'autre

**Réponse correcte** : B

**Feedback correct**
Une solution conduit l'électricité grâce à des ions mobiles. $\ce{HCl}$, acide fort, libère en totalité des ions $\ce{H3O+}$ et $\ce{Cl-}$ : ce sont eux qui transportent le courant.

**Feedback incorrect**
- Si A : Dans une solution, ce ne sont pas des électrons libres qui transportent le courant, mais des ions. Les électrons circulent dans les fils et les électrodes.
- Si B : C'est la bonne réponse.
- Si C : Aucune molécule $\ce{HCl}$ ne subsiste en solution : c'est un acide fort. Une molécule neutre ne transporterait de toute façon pas le courant.
- Si D : Les molécules d'eau sont neutres : elles ne transportent pas le courant. Ce sont les ions qui le transportent.

**Référence manuel** : acido-basiques-intro-conductivite

---
id: q-conductivite-parti-t2-001
concept: conductivite
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Deux solutions ont la même concentration, 0,1 mol/L : soude $\ce{NaOH}$ et ammoniac $\ce{NH3}$. La soude conduit nettement mieux. Lesquelles de ces explications, à l'échelle particulaire, sont correctes ?

**Options**
- A. $\ce{NH3}$ conduit aussi bien que $\ce{NaOH}$, car c'est une base
- B. $\ce{NH3}$ ne conduit pas du tout, car il ne contient aucun ion $\ce{OH-}$
- C. $\ce{NaOH}$ se dissocie totalement : la solution contient beaucoup d'ions $\ce{Na+}$ et $\ce{OH-}$
- D. $\ce{NH3}$ ne capte que partiellement des protons à l'eau (1,3 % à 0,1 mol/L) : la solution contient peu d'ions $\ce{NH4+}$ et $\ce{OH-}$

**Réponse correcte** : C,D

**Feedback correct**
La conductivité augmente avec le nombre d'ions par litre. $\ce{NaOH}$, base forte, libère tous ses ions $\ce{OH-}$ (C) ; $\ce{NH3}$, base faible, n'en forme que peu (D).

**Feedback incorrect**
- Si A : Deux bases de même concentration ne produisent pas le même nombre d'ions : la force de la base intervient. $\ce{NH3}$ étant une base faible, il en produit peu.
- Si B : $\ce{NH3}$ ne contient pas d'ion $\ce{OH-}$, mais il en forme en captant un proton à l'eau : $\ce{NH3 + H2O <=> NH4+ + OH-}$. Sa solution conduit faiblement, mais elle conduit.
- Si C : C'est une des réponses correctes.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-conductivite

---

<!-- ============================================================ -->
<!-- CONCEPT : indicateur-colore — Indicateurs colorés            -->
<!-- 4 questions obligatoires : macro·T1, macro·T2, parti·T1,     -->
<!-- parti·T2                                                     -->
<!-- ============================================================ -->

---
id: q-indicateur-colore-macro-t1-001
concept: indicateur-colore
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
D'après les couleurs des indicateurs colorés, lesquelles de ces affirmations sont correctes ?

**Options**
- A. Le bleu de bromothymol (BBT) est jaune en milieu acide
- B. La phénolphtaléine est rose fuchsia en milieu acide
- C. L'extrait de chou rouge est jaune en milieu basique
- D. Le papier pH est bleu en milieu acide

**Réponse correcte** : A,C

**Feedback correct**
Le BBT est jaune en milieu acide et bleu en milieu basique (A). L'extrait de chou rouge est rouge en milieu acide et jaune en milieu basique (C).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : La phénolphtaléine est incolore en milieu acide et rose fuchsia en milieu basique.
- Si C : C'est une des réponses correctes.
- Si D : Le papier pH est rouge en milieu acide et bleu en milieu basique.

**Référence manuel** : acido-basiques-intro-indicateurs

---
id: q-indicateur-colore-macro-t2-001
concept: indicateur-colore
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Un élève dispose de deux solutions incolores. Une goutte de la première, déposée sur un papier pH, le colore en rouge. Dans la seconde, quelques gouttes de bleu de bromothymol (BBT) donnent une couleur bleue. Lesquelles de ces conclusions sont correctes ?

**Options**
- A. La première solution est basique
- B. La première solution est acide
- C. La seconde solution est basique
- D. La seconde solution est acide, car le BBT est jaune en milieu basique

**Réponse correcte** : B,C

**Feedback correct**
Le papier pH est rouge en milieu acide : la première solution est acide (B). Le BBT est bleu en milieu basique : la seconde solution est basique (C).

**Feedback incorrect**
- Si A : Le rouge du papier pH indique un milieu acide ; en milieu basique, il serait bleu.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : Le BBT est jaune en milieu acide et bleu en milieu basique : la couleur bleue indique un milieu basique.

**Référence manuel** : acido-basiques-intro-indicateurs

---
id: q-indicateur-colore-parti-t1-001
concept: indicateur-colore
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, qu'est-ce qui explique qu'un indicateur coloré change de couleur selon le milieu ?

**Options**
- A. L'indicateur est lui-même un acide faible : sa forme acide et sa forme basique ont des couleurs différentes
- B. L'indicateur réagit avec l'eau pour former une molécule d'eau colorée
- C. L'indicateur est détruit par l'acide ou la base et remplacé par une substance colorée
- D. L'indicateur est un acide fort dont la couleur dépend seulement de sa concentration

**Réponse correcte** : A

**Feedback correct**
Un indicateur coloré est un acide faible $\ce{HIn}$ : sa forme acide $\ce{HIn}$ et sa forme basique $\ce{In-}$ n'ont pas la même couleur. La couleur observée est celle de la forme dominante, donc elle renseigne sur le milieu.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : Aucune molécule d'eau colorée ne se forme : l'indicateur est un couple acide/base, $\ce{HIn}/\ce{In-}$, dont chacune des deux formes a sa propre couleur.
- Si C : L'indicateur n'est pas détruit : il passe simplement d'une forme à l'autre, $\ce{HIn}$ et $\ce{In-}$, par transfert de proton.
- Si D : Un indicateur est un acide faible, non un acide fort, et sa couleur dépend de la forme dominante (acide ou basique), donc du milieu, et non de sa seule concentration.

**Référence manuel** : acido-basiques-intro-indicateurs

---
id: q-indicateur-colore-parti-t2-001
concept: indicateur-colore
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
La phénolphtaléine est un acide faible noté $\ce{HIn}$, incolore en milieu acide et rose fuchsia en milieu basique. On en ajoute quelques gouttes à une solution de soude $\ce{NaOH}$. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. La forme dominante est $\ce{HIn}$
- B. La solution devient rose fuchsia
- C. La solution reste incolore, car $\ce{NaOH}$ n'est pas un acide
- D. La forme dominante est $\ce{In-}$, la forme basique de l'indicateur

**Réponse correcte** : B,D

**Feedback correct**
En milieu basique, la forme basique $\ce{In-}$ domine (D) : elle est rose fuchsia, et la solution prend cette couleur (B).

**Feedback incorrect**
- Si A : $\ce{HIn}$ est la forme acide, dominante en milieu acide, où elle est incolore. En milieu basique, la forme dominante est $\ce{In-}$.
- Si B : C'est une des réponses correctes.
- Si C : La couleur d'un indicateur renseigne sur le milieu, acide ou basique, et non sur la nature acide du réactif ajouté. En milieu basique, la phénolphtaléine est rose fuchsia.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-indicateurs

---

<!-- ============================================================ -->
<!-- SOUS-PARTIE 7D                                               -->
<!-- ============================================================ -->

---

<!-- ============================================================ -->
<!-- CONCEPT : acides-metaux — Réaction des acides avec les       -->
<!-- métaux                                                       -->
<!-- 5 questions obligatoires : macro·T1, parti·T1×2 (●²,         -->
<!-- acides-metaux--echange-de-partenaires), symbo·T2, symbo·T3   -->
<!-- ============================================================ -->

---
id: q-acides-metaux-macro-t1-001
concept: acides-metaux
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
On plonge un ruban de magnésium $\ce{Mg}$ dans une solution d'acide chlorhydrique $\ce{HCl}$. Des bulles se forment à la surface du métal. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. Le gaz dégagé est du dioxyde de carbone $\ce{CO2}$
- B. Le gaz dégagé est du dihydrogène $\ce{H2}$
- C. Tous les métaux, y compris l'or, se dissolvent de la même façon dans l'acide chlorhydrique
- D. Le ruban de magnésium se dissout peu à peu

**Réponse correcte** : B,D

**Feedback correct**
Un acide réagit avec un métal pour donner un sel et du dihydrogène (B) : ici $\ce{2 HCl + Mg -> MgCl2 + H2}$. Le métal est consommé, donc le ruban se dissout peu à peu (D).

**Feedback incorrect**
- Si A : Le dioxyde de carbone est produit par la réaction d'un acide avec un carbonate, non avec un métal. Ici, le gaz dégagé est du dihydrogène $\ce{H2}$.
- Si B : C'est une des réponses correctes.
- Si C : Les métaux nobles, comme l'or $\ce{Au}$ et le platine $\ce{Pt}$, ne réagissent pas avec les acides courants. Seuls certains métaux, comme $\ce{Mg}$, $\ce{Zn}$, $\ce{Fe}$ ou $\ce{Al}$, se dissolvent.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-acides-metaux

---
id: q-acides-metaux-parti-t1-001
concept: acides-metaux
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: acides-metaux--echange-de-partenaires
date_validation: 2026-09-21
statut: validated
---

**Question**
Un morceau de zinc $\ce{Zn}$ plongé dans de l'acide chlorhydrique se dissout en dégageant du dihydrogène. Lesquelles de ces descriptions, à l'échelle particulaire, sont correctes ?

**Options**
- A. Les atomes de zinc et d'hydrogène « échangent leurs partenaires », sans aucun transfert d'électrons
- B. Les ions $\ce{H3O+}$ prennent des électrons aux atomes de zinc, qui passent en solution sous forme de cations $\ce{Zn^2+}$
- C. Les électrons cédés par le zinc sont captés par des protons, qui forment des molécules $\ce{H2}$
- D. Les atomes de zinc captent des protons $\ce{H+}$ pour former le dihydrogène

**Réponse correcte** : B,C

**Feedback correct**
Les ions $\ce{H3O+}$ arrachent des électrons aux atomes de zinc (B), qui se dissolvent sous forme de cations $\ce{Zn^2+}$. Ces électrons sont captés par des protons, qui forment des molécules $\ce{H2}$ (C).

**Feedback incorrect**
- Si A : Il ne s'agit pas d'un simple échange de partenaires : la réaction est un transfert d'électrons du métal vers les ions $\ce{H3O+}$.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : C'est l'inverse : le zinc cède des électrons, il ne capte pas de protons. Ce sont les protons qui captent les électrons pour former $\ce{H2}$.

**Référence manuel** : acido-basiques-intro-acides-metaux

---
id: q-acides-metaux-parti-t1-002
concept: acides-metaux
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
misconception: acides-metaux--echange-de-partenaires
date_validation: 2026-09-21
statut: validated
---

**Question**
Un morceau d'aluminium $\ce{Al}$ plongé dans de l'acide chlorhydrique se dissout en dégageant du dihydrogène. Lesquelles de ces descriptions, à l'échelle particulaire, sont correctes ?

**Options**
- A. Les ions $\ce{H3O+}$ prennent des électrons aux atomes d'aluminium, qui passent en solution sous forme de cations $\ce{Al^3+}$
- B. Les atomes d'aluminium et d'hydrogène « changent de partenaire », sans transfert d'électrons
- C. Les atomes d'aluminium captent des protons $\ce{H+}$ pour former le dihydrogène
- D. Les électrons pris à l'aluminium sont captés par des protons, qui forment des molécules $\ce{H2}$

**Réponse correcte** : A,D

**Feedback correct**
Les ions $\ce{H3O+}$ arrachent des électrons aux atomes d'aluminium (A), qui se dissolvent sous forme de cations $\ce{Al^3+}$. Ces électrons sont captés par des protons, qui forment des molécules $\ce{H2}$ (D).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Il ne s'agit pas d'un simple changement de partenaire : la réaction est un transfert d'électrons du métal vers les ions $\ce{H3O+}$.
- Si C : C'est l'inverse : l'aluminium cède des électrons, il ne capte pas de protons. Ce sont les protons qui captent les électrons pour former $\ce{H2}$.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-acides-metaux

---
id: q-acides-metaux-symbo-t2-001
concept: acides-metaux
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Quelle équation décrit correctement la réaction de l'aluminium $\ce{Al}$ avec l'acide sulfurique $\ce{H2SO4}$ ?

**Options**
- A. $\ce{Al + H2SO4 -> AlSO4 + H2}$
- B. $\ce{2 Al + 3 H2SO4 -> Al2(SO4)3 + 3 H2O}$
- C. $\ce{2 Al + 3 H2SO4 -> Al2(SO4)3 + 3 H2}$
- D. $\ce{2 Al + H2SO4 -> Al2(SO4)3 + H2}$

**Réponse correcte** : C

**Feedback correct**
Un acide et un métal donnent un sel et du dihydrogène. Le sel est $\ce{Al2(SO4)3}$ (deux $\ce{Al^3+}$ pour trois $\ce{SO4^2-}$) et l'équation est équilibrée : 2 Al, 3 S, 12 O et 6 H de chaque côté.

**Feedback incorrect**
- Si A : La formule $\ce{AlSO4}$ est impossible : les charges $\ce{Al^3+}$ et $\ce{SO4^2-}$ imposent $\ce{Al2(SO4)3}$.
- Si B : Le second produit est du dihydrogène $\ce{H2}$, non de l'eau ; l'oxygène n'est d'ailleurs pas conservé (12 atomes à gauche, 15 à droite).
- Si C : C'est la bonne réponse.
- Si D : La formule du sel est correcte, mais l'équation n'est pas équilibrée : il y a 3 atomes de soufre à droite pour un seul à gauche.

**Référence manuel** : acido-basiques-intro-acides-metaux

---
id: q-acides-metaux-symbo-t3-001
concept: acides-metaux
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
On fait réagir 2,43 g de magnésium $\ce{Mg}$ ($M = 24{,}31$ g/mol) avec un excès d'acide chlorhydrique : $\ce{Mg + 2 HCl -> MgCl2 + H2}$. Quel volume de dihydrogène est dégagé à TPN ($V_m = 22{,}4$ L/mol) ?

**Options**
- A. 1,12 L
- B. 2,24 L
- C. 4,48 L
- D. 54,4 L

**Réponse correcte** : B

**Feedback correct**
La quantité de magnésium est n(Mg) = 2,43 / 24,31 = 0,100 mol. Le rapport est de 1 mol de $\ce{H2}$ pour 1 mol de $\ce{Mg}$, donc n(H₂) = 0,100 mol. Le volume est V = 0,100 × 22,4 = 2,24 L.

**Feedback incorrect**
- Si A : 1,12 L correspond à 0,050 mol de $\ce{H2}$, soit la moitié de la valeur attendue : le rapport est de 1 mol de $\ce{H2}$ pour 1 mol de $\ce{Mg}$, non de 1 pour 2.
- Si B : C'est la bonne réponse.
- Si C : 4,48 L correspond à 0,200 mol de $\ce{H2}$ : le coefficient 2 de $\ce{HCl}$ a été appliqué à $\ce{H2}$, dont le coefficient est 1.
- Si D : 54,4 L s'obtient en multipliant directement la masse par 22,4 : il faut d'abord convertir la masse en quantité de matière, avec $n = m / M$.

**Référence manuel** : acido-basiques-intro-acides-metaux

---

<!-- ============================================================ -->
<!-- CONCEPT : acides-carbonates — Réaction des acides avec les   -->
<!-- carbonates                                                   -->
<!-- 4 questions obligatoires : macro·T1, parti·T1, symbo·T2,     -->
<!-- symbo·T3                                                     -->
<!-- ============================================================ -->

---
id: q-acides-carbonates-macro-t1-001
concept: acides-carbonates
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
Une pastille effervescente contient de l'acide citrique et de l'hydrogénocarbonate de sodium $\ce{NaHCO3}$. Jetée dans un verre d'eau, elle produit de nombreuses bulles. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. Les bulles sont du dihydrogène $\ce{H2}$
- B. L'eau se met à bouillir sous l'effet de la réaction
- C. Les bulles sont du dioxyde de carbone $\ce{CO2}$, produit par la réaction de l'acide avec l'hydrogénocarbonate
- D. La réaction est du même type que celle d'un acide sur du calcaire $\ce{CaCO3}$

**Réponse correcte** : C,D

**Feedback correct**
Un acide qui réagit avec un carbonate ou un hydrogénocarbonate donne un sel, du dioxyde de carbone et de l'eau (C). C'est le même type de réaction que $\ce{2 HCl + CaCO3 -> CaCl2 + CO2 + H2O}$ (D).

**Feedback incorrect**
- Si A : Le dihydrogène est produit par la réaction d'un acide avec un métal, non avec un hydrogénocarbonate. Ici, le gaz est du dioxyde de carbone.
- Si B : L'eau ne bout pas : les bulles sont un gaz produit par la réaction, le dioxyde de carbone, et non de la vapeur d'eau.
- Si C : C'est une des réponses correctes.
- Si D : C'est une des réponses correctes.

**Référence manuel** : acido-basiques-intro-acides-carbonates

---
id: q-acides-carbonates-parti-t1-001
concept: acides-carbonates
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
L'acide chlorhydrique attaque le calcaire $\ce{CaCO3}$ avec dégagement de dioxyde de carbone. Lesquelles de ces descriptions, à l'échelle particulaire, sont correctes ?

**Options**
- A. Un proton passe d'un ion $\ce{H3O+}$ à un ion carbonate $\ce{CO3^2-}$, qui joue le rôle de base
- B. Les ions $\ce{H3O+}$ prennent des électrons à l'ion carbonate, ce qui forme du dihydrogène
- C. L'acide carbonique $\ce{H2CO3}$ formé est instable : il se décompose en eau et en dioxyde de carbone
- D. L'ion carbonate cède un proton à un ion $\ce{H3O+}$ : il joue le rôle d'acide

**Réponse correcte** : A,C

**Feedback correct**
L'ion carbonate est une base de Brønsted-Lowry : il capte un proton de $\ce{H3O+}$ (A) et forme $\ce{H2CO3}$. Cet acide instable se décompose en $\ce{H2O}$ et $\ce{CO2}$ (C), le gaz observé.

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : Il s'agit d'un transfert de proton, non d'un transfert d'électrons, et le gaz dégagé est du dioxyde de carbone, non du dihydrogène.
- Si C : C'est une des réponses correctes.
- Si D : C'est l'inverse : en présence d'un acide, l'ion carbonate capte un proton. C'est une base, non un acide.

**Référence manuel** : acido-basiques-intro-acides-carbonates

---
id: q-acides-carbonates-symbo-t2-001
concept: acides-carbonates
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Quelle équation décrit correctement la réaction de l'acide nitrique $\ce{HNO3}$ avec le carbonate de sodium $\ce{Na2CO3}$ ?

**Options**
- A. $\ce{HNO3 + Na2CO3 -> NaNO3 + CO2 + H2O}$
- B. $\ce{2 HNO3 + Na2CO3 -> 2 NaNO3 + H2 + CO2}$
- C. $\ce{2 HNO3 + Na2CO3 -> 2 NaNO3 + H2CO3}$
- D. $\ce{2 HNO3 + Na2CO3 -> 2 NaNO3 + CO2 + H2O}$

**Réponse correcte** : D

**Feedback correct**
Un acide et un carbonate donnent un sel, du dioxyde de carbone et de l'eau. L'équation est équilibrée : 2 Na, 2 N, 2 H, 1 C et 9 O de chaque côté.

**Feedback incorrect**
- Si A : L'équation n'est pas équilibrée : il y a 2 atomes de sodium à gauche pour un seul à droite. Il faut 2 $\ce{HNO3}$ et 2 $\ce{NaNO3}$.
- Si B : Le gaz produit n'est pas du dihydrogène, et l'oxygène n'est pas conservé (9 atomes à gauche, 8 à droite) : l'eau manque.
- Si C : L'acide carbonique $\ce{H2CO3}$ est instable : il se décompose en $\ce{H2O}$ et $\ce{CO2}$, qui doivent figurer dans l'équation bilan.
- Si D : C'est la bonne réponse.

**Référence manuel** : acido-basiques-intro-acides-carbonates

---
id: q-acides-carbonates-symbo-t3-001
concept: acides-carbonates
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
On verse 100 mL d'acide chlorhydrique $\ce{HCl}$ à 0,250 mol/L sur 3,00 g de carbonate de calcium $\ce{CaCO3}$ ($M = 100{,}09$ g/mol) : $\ce{2 HCl + CaCO3 -> CaCl2 + CO2 + H2O}$. Quel volume de dioxyde de carbone est dégagé à TPA ($V_m = 24{,}5$ L/mol) ?

**Options**
- A. 0,306 L
- B. 0,613 L
- C. 0,734 L
- D. 0,153 L

**Réponse correcte** : A

**Feedback correct**
On a n(HCl) = 0,100 × 0,250 = 0,0250 mol et n(CaCO₃) = 3,00 / 100,09 = 0,0300 mol. Consommer tout le calcaire exigerait 0,0600 mol de $\ce{HCl}$ : l'acide est le réactif limitant. Avec 2 mol de $\ce{HCl}$ pour 1 mol de $\ce{CO2}$, n(CO₂) = 0,0250 / 2 = 0,0125 mol, donc V = 0,0125 × 24,5 = 0,306 L.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : 0,613 L suppose 1 mol de $\ce{CO2}$ par mole de $\ce{HCl}$ : le coefficient 2 de $\ce{HCl}$ a été oublié.
- Si C : 0,734 L s'obtient en prenant le calcaire comme réactif limitant, alors que c'est l'acide qui est en défaut.
- Si D : 0,153 L correspond à une division par 2 appliquée deux fois : la quantité de $\ce{CO2}$ vaut 0,0125 mol, non 0,00625 mol.

**Référence manuel** : acido-basiques-intro-acides-carbonates

---

<!-- ============================================================ -->
<!-- CONCEPT : oxydes-acides-bases — Oxydes acides et oxydes      -->
<!-- basiques                                                     -->
<!-- 3 questions obligatoires : macro·T1, parti·T1, symbo·T2      -->
<!-- ============================================================ -->

---
id: q-oxydes-acides-bases-macro-t1-001
concept: oxydes-acides-bases
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: macro
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
On brûle du soufre $\ce{S}$ dans un flacon contenant un peu d'eau et du bleu de bromothymol (jaune en milieu acide, bleu en milieu basique). La solution devient jaune. On répète l'expérience avec du magnésium $\ce{Mg}$ : la solution devient bleue. Lesquelles de ces affirmations sont correctes ?

**Options**
- A. La solution jaune est basique
- B. L'oxyde de soufre formé donne, avec l'eau, une solution acide
- C. L'oxyde de magnésium formé donne, avec l'eau, une solution basique
- D. Les acides et les bases ne peuvent être fabriqués qu'en laboratoire

**Réponse correcte** : B,C

**Feedback correct**
Le soufre, un non-métal, brûle en formant un oxyde qui donne avec l'eau une solution acide : le bleu de bromothymol est jaune (B). Le magnésium, un métal, forme un oxyde qui donne une solution basique : l'indicateur est bleu (C).

**Feedback incorrect**
- Si A : Le bleu de bromothymol est jaune en milieu acide, non en milieu basique. La solution jaune est donc acide.
- Si B : C'est une des réponses correctes.
- Si C : C'est une des réponses correctes.
- Si D : Cette expérience montre le contraire : une simple combustion suivie d'un contact avec l'eau suffit à produire un acide ou une base. Les oxydes de soufre présents dans l'air sont d'ailleurs à l'origine des pluies acides.

**Référence manuel** : acido-basiques-intro-origine-acides-bases

---
id: q-oxydes-acides-bases-parti-t1-001
concept: oxydes-acides-bases
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: parti
type: 1
date_validation: 2026-09-21
statut: validated
---

**Question**
À l'échelle particulaire, comment expliquer qu'un oxyde de métal donne une solution basique et un oxyde de non-métal une solution acide ? Lesquelles de ces affirmations sont correctes ?

**Options**
- A. L'ion oxyde $\ce{O^2-}$ d'un oxyde de métal est une base forte : il arrache un proton à l'eau ($\ce{O^2- + H2O -> 2 OH-}$)
- B. Un non-métal, très électronégatif, attire les électrons des liaisons O–H de l'eau, ce qui favorise la libération d'un proton
- C. Un oxyde de métal libère des protons $\ce{H+}$ dans l'eau
- D. Un oxyde de non-métal contient des ions $\ce{O^2-}$

**Réponse correcte** : A,B

**Feedback correct**
L'ion $\ce{O^2-}$ des oxydes de métaux capte un proton de l'eau et forme des ions $\ce{OH-}$ : la solution est basique (A). Un non-métal, très électronégatif, attire les électrons des liaisons O–H de l'eau, ce qui libère un proton : la solution est acide (B).

**Feedback incorrect**
- Si A : C'est une des réponses correctes.
- Si B : C'est une des réponses correctes.
- Si C : C'est l'inverse : un oxyde de métal capte des protons de l'eau et fait apparaître des ions $\ce{OH-}$, ce qui rend la solution basique.
- Si D : Ce sont les oxydes de métaux qui contiennent l'ion $\ce{O^2-}$, non ceux de non-métaux.

**Référence manuel** : acido-basiques-intro-origine-acides-bases

---
id: q-oxydes-acides-bases-symbo-t2-001
concept: oxydes-acides-bases
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 2
date_validation: 2026-09-21
statut: validated
---

**Question**
Laquelle de ces équations décrit correctement la réaction d'un oxyde avec l'eau, ainsi que la nature de la solution obtenue ?

**Options**
- A. $\ce{SO3 + H2O -> H2SO4}$ : solution acide
- B. $\ce{MgO + H2O -> Mg(OH)2}$ : solution acide
- C. $\ce{K2O + H2O -> KOH}$ : solution basique
- D. $\ce{SO2 + H2O -> H2SO4}$ : solution acide

**Réponse correcte** : A

**Feedback correct**
$\ce{SO3}$ est un oxyde de non-métal : avec l'eau, il donne un acide, $\ce{H2SO4}$. L'équation est équilibrée (1 S, 4 O et 2 H de chaque côté) et la solution est acide.

**Feedback incorrect**
- Si A : C'est la bonne réponse.
- Si B : L'équation est équilibrée, mais $\ce{MgO}$ est un oxyde de métal : il donne une base, $\ce{Mg(OH)2}$, et une solution basique, non acide.
- Si C : La solution est bien basique, mais l'équation n'est pas équilibrée : il y a 2 atomes de potassium à gauche pour un seul à droite. L'équation correcte est $\ce{K2O + H2O -> 2 KOH}$.
- Si D : $\ce{SO2}$ donne $\ce{H2SO3}$ avec l'eau, non $\ce{H2SO4}$ : l'oxygène n'est pas conservé (3 atomes à gauche, 4 à droite).

**Référence manuel** : acido-basiques-intro-origine-acides-bases

---

<!-- ============================================================ -->
<!-- SUPER QUESTIONS (chantier 18, Charte §6.2bis) — champ outils: -->
<!-- 6 questions, une par contexte, chaque option testant son      -->
<!-- propre concept (notation tout-ou-rien par concept).           -->
<!-- Validées le 2026-09-21 (relecture Claude + contrôle indépendant). -->
<!-- Contextes inspirés d'annales du bac (labolycee.org) et du     -->
<!-- 1er tour de l'Olympiade suisse de chimie ; données changées. -->
<!-- ============================================================ -->

---
id: q-acides-carbonates-symbo-t3-002
concept: acides-carbonates
outils: A:acides-carbonates, B:acide-base-bronsted-lowry, C:force-acide-base, D:couple-acide-base
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
On verse du vinaigre blanc (une solution d'acide acétique $\ce{CH3COOH}$) sur du bicarbonate de sodium $\ce{NaHCO3}$ : une mousse se forme aussitôt, à cause d'un dégagement gazeux. La réaction met en jeu l'acide acétique et l'ion hydrogénocarbonate $\ce{HCO3-}$. Parmi les affirmations suivantes, lesquelles sont exactes ?

**Options**
- A. Le gaz dégagé est du dihydrogène $\ce{H2}$, comme lorsqu'un acide attaque un métal.
- B. L'ion $\ce{HCO3-}$ capte un proton de l'acide acétique : il se comporte comme une base de Brønsted-Lowry.
- C. Puisque cet acide réagit visiblement avec le bicarbonate, l'acide acétique est un acide fort.
- D. L'ion acétate $\ce{CH3COO-}$ est la base conjuguée de l'acide acétique : les deux espèces forment le couple $\ce{CH3COOH}/\ce{CH3COO-}$.

**Réponse correcte** : B, D

**Feedback correct**
B. Dans la réaction $\ce{CH3COOH + HCO3- -> CH3COO- + CO2 + H2O}$, l'acide acétique cède un proton à l'ion $\ce{HCO3-}$ : c'est le rôle d'une base de Brønsted-Lowry. D. L'ion acétate est ce qui reste de l'acide acétique après la perte de son proton : les deux espèces ne diffèrent que d'un proton, ce qui définit un couple acide/base conjugué.

**Feedback incorrect**
- Si A : Le dihydrogène se forme lorsqu'un acide attaque un métal. Avec un carbonate ou un hydrogénocarbonate, l'acide forme de l'acide carbonique $\ce{H2CO3}$, instable, qui se décompose en eau et en dioxyde de carbone $\ce{CO2}$ : c'est ce gaz qui fait mousser.
- Si B : C'est une bonne réponse. L'ion $\ce{HCO3-}$ reçoit le proton cédé par l'acide acétique : il joue le rôle de base de Brønsted-Lowry.
- Si C : Réagir visiblement avec un hydrogénocarbonate ne mesure pas la force d'un acide. L'acide acétique est un acide faible : à 0,1 mol/L, seules 1,3 % de ses molécules cèdent leur proton à l'eau.
- Si D : C'est une bonne réponse. $\ce{CH3COO-}$ est la base conjuguée de $\ce{CH3COOH}$ : les deux espèces ne diffèrent que d'un proton.

**Référence manuel** : acido-basiques-intro-acides-carbonates

---
id: q-oxydes-acides-bases-symbo-t3-001
concept: oxydes-acides-bases
outils: A:oxydes-acides-bases, B:ph, C:acides-carbonates, D:force-acide-base
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
La combustion de combustibles fossiles rejette du dioxyde de soufre $\ce{SO2}$ dans l'atmosphère. Dissous dans l'eau de pluie, il contribue aux pluies acides, dont le pH est nettement inférieur à celui d'une pluie normale (environ 5,6). Parmi les affirmations suivantes, lesquelles sont exactes ?

**Options**
- A. Le dioxyde de soufre est un oxyde de non-métal : avec l'eau, il forme un acide, $\ce{SO2 + H2O -> H2SO3}$.
- B. Une pluie acide de pH 3,6 est environ 2 fois plus acide qu'une pluie normale de pH 5,6, puisque son pH est inférieur de 2 unités.
- C. Lorsque l'acide de la pluie attaque un monument en calcaire $\ce{CaCO3}$, un gaz se dégage : le dioxyde de carbone $\ce{CO2}$.
- D. Une solution d'acide nitrique $\ce{HNO3}$ à 0,038 mol/L a un pH de 1,42 : cette valeur montre que $\ce{HNO3}$ est un acide fort.

**Réponse correcte** : A, C, D

**Feedback correct**
A. $\ce{SO2}$ est un oxyde de non-métal : il forme un acide avec l'eau, ici l'acide sulfureux $\ce{H2SO3}$. C. Un acide attaque un carbonate selon acide + carbonate → sel + $\ce{CO2}$ + $\ce{H2O}$ : c'est ce qui érode les monuments calcaires. D. Pour un acide fort, la dissociation est totale : $[\ce{H3O+}] = C_0$, donc pH = −log(0,038) = 1,42, exactement la valeur mesurée.

**Feedback incorrect**
- Si A : C'est une bonne réponse. Les oxydes de non-métaux donnent un acide avec l'eau (ceux des métaux donnent une base) : $\ce{SO2 + H2O -> H2SO3}$.
- Si B : Le pH est une échelle logarithmique : 2 unités d'écart correspondent à un facteur 10 × 10 = 100. Une pluie de pH 3,6 contient 100 fois plus d'ions $\ce{H3O+}$ (environ 2,5 × 10⁻⁴ mol/L contre 2,5 × 10⁻⁶ mol/L) qu'une pluie de pH 5,6.
- Si C : C'est une bonne réponse. Acide + carbonate → sel + $\ce{CO2}$ + $\ce{H2O}$ : le gaz dégagé est du dioxyde de carbone.
- Si D : C'est une bonne réponse. Si $\ce{HNO3}$ était un acide faible, $[\ce{H3O+}]$ serait nettement inférieure à 0,038 mol/L et le pH nettement supérieur à 1,42 : la valeur pH = −log(0,038) = 1,42 confirme une dissociation totale.

**Référence manuel** : acido-basiques-intro-origine-acides-bases

---
id: q-force-acide-base-symbo-t3-003
concept: force-acide-base
outils: A:poh, B:force-acide-base, C:acide-base-bronsted-lowry, D:couple-acide-base
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
Une lessive « maison » se prépare avec des cendres de bois, qui contiennent du carbonate de potassium $\ce{K2CO3}$. On dissout 3,0 g de $\ce{K2CO3}$ ($M = 138$ g/mol) dans de l'eau pour obtenir 100 mL de solution S, dont le pH mesuré est de 11,8. L'ion carbonate réagit avec l'eau selon $\ce{CO3^{2-} + H2O <=> HCO3- + OH-}$. Parmi les affirmations suivantes, lesquelles sont exactes ?

**Options**
- A. Le pOH de la solution S vaut 11,8, puisque la solution est basique.
- B. L'ion carbonate est une base faible : seule une petite partie des ions $\ce{CO3^{2-}}$ dissous a capté un proton.
- C. En se dissolvant, $\ce{K2CO3}$ libère directement des ions $\ce{OH-}$ : l'ion carbonate est donc une base d'Arrhenius.
- D. L'acide conjugué de l'ion carbonate est l'acide carbonique $\ce{H2CO3}$.

**Réponse correcte** : B

**Feedback correct**
B. À pH 11,8, le pOH vaut 14 − 11,8 = 2,2, donc $[\ce{OH-}]$ = 0,0063 mol/L. La quantité d'ions carbonate dissous est n = 3,0 / 138 = 0,0217 mol, soit c = 0,0217 / 0,100 = 0,217 mol/L. Chaque ion carbonate qui capte un proton forme un ion $\ce{OH-}$ : environ 3 % seulement des ions ont réagi. Une base forte les aurait tous protonés ($[\ce{OH-}]$ = 0,217 mol/L, pH proche de 13,3) : $\ce{CO3^{2-}}$ est une base faible.

**Feedback incorrect**
- Si A : Le pH de la solution vaut 11,8 ; le pOH s'en déduit par pH + pOH = 14, soit pOH = 14 − 11,8 = 2,2. Une solution basique a un pH élevé et un pOH faible : les deux valeurs se reflètent autour de 7.
- Si B : C'est une bonne réponse. Avec $[\ce{OH-}]$ = 0,0063 mol/L pour 0,217 mol/L d'ions carbonate dissous, environ 3 % seulement ont capté un proton : c'est le comportement d'une base faible.
- Si C : La dissolution de $\ce{K2CO3}$ libère des ions $\ce{K+}$ et $\ce{CO3^{2-}}$ : aucun ion $\ce{OH-}$ n'est libéré directement, ce n'est donc pas une base d'Arrhenius. Les ions $\ce{OH-}$ n'apparaissent que parce que $\ce{CO3^{2-}}$ capte un proton de l'eau : c'est une base de Brønsted-Lowry.
- Si D : L'acide conjugué d'une base ne diffère d'elle que d'un seul proton : pour $\ce{CO3^{2-}}$, c'est $\ce{HCO3-}$ (couple $\ce{HCO3-}/\ce{CO3^{2-}}$). $\ce{H2CO3}$ est l'acide conjugué de $\ce{HCO3-}$.

**Référence manuel** : acido-basiques-intro-force

---
id: q-neutralisation-symbo-t3-003
concept: neutralisation
outils: A:indicateur-colore, B:neutralisation, C:conductivite, D:ph
sous-partie: 7C
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
On mélange 20,0 mL d'acide chlorhydrique $\ce{HCl}$ à 0,10 mol/L avec 30,0 mL de soude $\ce{NaOH}$ à 0,10 mol/L, en présence de quelques gouttes de bleu de bromothymol (BBT). Parmi les affirmations suivantes sur la solution obtenue, lesquelles sont exactes ?

**Options**
- A. Le BBT est bleu dans la solution finale.
- B. L'acide chlorhydrique est le réactif limitant : c'est la soude qui est en excès.
- C. La solution finale ne conduit pas le courant électrique, puisque l'acide et la base se sont neutralisés.
- D. Le pH de la solution finale est voisin de 12,3.

**Réponse correcte** : A, B, D

**Feedback correct**
B. n(HCl) = 0,0200 × 0,10 = 0,0020 mol et n(NaOH) = 0,0300 × 0,10 = 0,0030 mol : la réaction $\ce{HCl + NaOH -> NaCl + H2O}$ se fait mole à mole, l'acide est donc limitant et il reste 0,0010 mol de $\ce{NaOH}$. D. Ces 0,0010 mol sont dissoutes dans 0,0500 L : $[\ce{OH-}]$ = 0,0010 / 0,0500 = 0,020 mol/L, pOH = 1,70 et pH = 14 − 1,70 = 12,30. A. La solution est basique : le BBT y est bleu (il est jaune en milieu acide).

**Feedback incorrect**
- Si A : C'est une bonne réponse. Le mélange est basique (excès de soude) : le BBT, jaune en milieu acide, y est bleu.
- Si B : C'est une bonne réponse. Il y a 0,0020 mol d'acide pour 0,0030 mol de base : l'acide est entièrement consommé, la soude en excès.
- Si C : Une neutralisation ne supprime pas tous les ions : il reste du sel dissous (ions $\ce{Na+}$ et $\ce{Cl-}$) et, ici, un excès d'ions $\ce{OH-}$. Une solution conduit le courant dès qu'elle contient des ions mobiles : celle-ci conduit bien.
- Si D : C'est une bonne réponse. L'excès de 0,0010 mol de $\ce{NaOH}$ dans 50,0 mL donne $[\ce{OH-}]$ = 0,020 mol/L, pOH = 1,70, donc pH = 12,30.

**Référence manuel** : acido-basiques-intro-neutralisation

---
id: q-ph-symbo-t3-002
concept: ph
outils: A:ph, B:autoprotolyse-eau, C:milieu-acide-neutre-basique, D:poh
sous-partie: 7B
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
Un élève prépare une solution d'acide chlorhydrique $\ce{HCl}$ à $1{,}0 \times 10^{-9}$ mol/L. Il applique la formule $\text{pH} = -\log C_0$ et obtient $\text{pH} = 9$. Parmi les affirmations suivantes, lesquelles sont exactes ?

**Options**
- A. La formule $\text{pH} = -\log C_0$ reste valable à cette concentration : le pH de la solution est bien 9.
- B. Dans l'eau pure, l'autoprotolyse fournit déjà environ $10^{-7}$ mol/L d'ions $\ce{H3O+}$, bien plus que les $10^{-9}$ mol/L apportés par l'acide : elle ne peut pas être négligée.
- C. La solution reste acide, mais son pH est à peine inférieur à 7.
- D. Comme la solution est acide, elle ne contient plus d'ions $\ce{OH-}$ : son pOH n'a pas de valeur.

**Réponse correcte** : B, C

**Feedback correct**
B. L'autoprotolyse de l'eau pure fournit 10⁻⁷ mol/L de $\ce{H3O+}$, cent fois plus que les 10⁻⁹ mol/L apportés par l'acide : ce sont eux qui dominent. C. Les $\ce{H3O+}$ de l'acide s'ajoutent à ceux de l'eau : $[\ce{H3O+}]$ vaut à peine plus de 10⁻⁷ mol/L, donc $[\ce{H3O+}] > [\ce{OH-}]$ : le milieu est acide, mais avec un pH d'environ 7,0, à peine inférieur à 7.

**Feedback incorrect**
- Si A : La formule $\text{pH} = -\log C_0$ suppose que tous les ions $\ce{H3O+}$ viennent de l'acide. Ici elle donne 9, un pH basique pour une solution d'acide : résultat absurde, signe que l'hypothèse ne tient plus, car l'eau fournit bien plus de $\ce{H3O+}$ (10⁻⁷ mol/L) que l'acide (10⁻⁹ mol/L).
- Si B : C'est une bonne réponse. L'autoprotolyse de l'eau fournit 10⁻⁷ mol/L de $\ce{H3O+}$ : c'est cent fois plus que ce que l'acide apporte ici.
- Si C : C'est une bonne réponse. Ajouter un acide ne peut pas rendre l'eau basique : les $\ce{H3O+}$ de l'acide s'ajoutent à ceux de l'eau, le pH passe à peine sous 7.
- Si D : Même dans une solution acide, l'autoprotolyse refabrique des ions $\ce{OH-}$ : ils deviennent rares, mais jamais nuls (ici environ 10⁻⁷ mol/L). La relation pH + pOH = 14 reste valable : le pOH existe toujours (ici environ 7,0).

**Référence manuel** : acido-basiques-intro-ph

---
id: q-acides-metaux-symbo-t3-002
concept: acides-metaux
outils: A:acides-metaux, B:acides-metaux, C:acide-base-bronsted-lowry, D:ph
sous-partie: 7D
chapitre: acido-basiques-intro
niveau: DF
r1: symbo
type: 3
date_validation: 2026-09-21
statut: validated
---

**Question**
On plonge un ruban de magnésium dans de l'acide chlorhydrique $\ce{HCl}$ dilué : des bulles se forment sur le métal, qui se dissout peu à peu. Le gaz recueilli explose avec un léger « pop » à l'approche d'une flamme. Parmi les affirmations suivantes, lesquelles sont exactes ?

**Options**
- A. Un métal noble comme l'or se dissoudrait de la même façon dans cette solution : tous les métaux réagissent avec un acide.
- B. Le gaz est du dihydrogène : $\ce{Mg + 2 HCl -> MgCl2 + H2}$.
- C. Cette transformation est un échange d'électrons entre le magnésium et les ions $\ce{H3O+}$ : ce n'est pas un transfert de proton d'un acide vers une base.
- D. Le pH de la solution diminue au fil de la réaction, puisque le métal libère des ions dans la solution.

**Réponse correcte** : B, C

**Feedback correct**
B. Un acide attaque un métal en formant un sel et du dihydrogène : $\ce{Mg + 2 HCl -> MgCl2 + H2}$ ; le « pop » à la flamme est la signature de $\ce{H2}$. C. Les ions $\ce{H3O+}$ arrachent des électrons au magnésium, qui se dissout sous forme d'ions $\ce{Mg^{2+}}$ : c'est un échange d'électrons, propre à l'oxydo-réduction, alors qu'une réaction acido-basique est un échange de protons.

**Feedback incorrect**
- Si A : Tous les métaux ne réagissent pas avec les acides : les métaux nobles, comme l'or ($\ce{Au}$) ou le platine ($\ce{Pt}$), résistent aux acides courants.
- Si B : C'est une bonne réponse. Acide + métal → sel + dihydrogène : le gaz qui fait « pop » à la flamme est $\ce{H2}$.
- Si C : C'est une bonne réponse. Les ions $\ce{H3O+}$ captent des électrons cédés par le métal : c'est un échange d'électrons (oxydo-réduction), non un transfert de proton.
- Si D : Les ions $\ce{H3O+}$ sont consommés par la réaction : ils captent les électrons cédés par le métal pour former du dihydrogène. $[\ce{H3O+}]$ diminue donc et le pH augmente, il ne diminue pas.

**Référence manuel** : acido-basiques-intro-acides-metaux
