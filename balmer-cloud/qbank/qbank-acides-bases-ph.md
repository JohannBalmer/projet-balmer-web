# Banque de questions — Chapitre 13
# Acides, bases et pH

# Slug : acides-bases-ph

_Projet-Balmer / Balmer-Cloud — Généré le 2026-11-10_
_Statut : lots en cours de rédaction, toutes les questions sont `to_fix` tant que LUM n'a pas relu l'échantillon._

---

<!-- LÉGENDE
Niveau R1 : macro = macroscopique | parti = particulaire | symbo = symbolique
Niveau    : sou = se souvenir | com = comprendre | app = appliquer | ana = analyser | eva = évaluer (Anderson & Krathwohl, 2001)
Statut    : validated | rejected | to_fix
Niveau    : OS (chapitre entier, voir toc.yaml)
-->

---
id: q-produit-ionique-eau-macro-com-001
concept: produit-ionique-eau
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
misconception: produit-ionique-eau--neutre-egal-ph-7
date_validation: 2026-11-10
statut: validated
---

**Question**
À 60 °C, le produit ionique de l'eau vaut $K_e = 9{,}6 \times 10^{-14}$. On mesure le pH d'un échantillon d'eau pure à cette température : on obtient 6,51. Que peut-on conclure ?

**Options**
- A. L'eau est acide, car son pH est inférieur à 7.
- B. L'eau est neutre : $[\ce{H3O+}] = [\ce{OH-}]$.
- C. L'eau est basique, car $K_e$ est supérieur à sa valeur à 25 °C.
- D. L'eau est contaminée, car l'eau pure a toujours un pH de 7.

**Réponse correcte** : B

**Feedback correct**
Une solution est neutre quand $[\ce{H3O+}] = [\ce{OH-}]$. À 60 °C, chacune vaut $\sqrt{9{,}6 \times 10^{-14}} \approx 3{,}1 \times 10^{-7}$ mol/L, ce qui correspond à un pH de 6,51 : l'eau est bien neutre, même si son pH n'est pas 7.

**Feedback incorrect**
- Si A : Le pH 7 n'est la valeur de neutralité qu'à 25 °C. À 60 °C, l'eau pure neutre a un pH de 6,51 ; on ne juge pas l'acidité en comparant simplement le pH à 7.
- Si B : C'est une bonne réponse.
- Si C : Une valeur plus grande de $K_e$ signifie que l'autoprotolyse est plus avancée, avec davantage d'ions des deux sortes en quantités égales. L'eau reste neutre.
- Si D : La valeur 7 vient de $K_e = 1{,}0 \times 10^{-14}$, valable à 25 °C seulement. $K_e$ augmente avec la température, donc le pH de l'eau pure neutre diminue.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-produit-ionique-eau-parti-com-001
concept: produit-ionique-eau
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: parti
type: com
date_validation: 2026-11-10
statut: validated
---

**Question**
Dans de l'eau pure à 25 °C, quelle description au niveau particulaire est correcte ?

**Options**
- A. Aucune molécule d'eau ne réagit : les ions $\ce{H3O+}$ et $\ce{OH-}$ n'apparaissent que si l'on ajoute un acide ou une base.
- B. Les molécules d'eau échangent sans cesse des protons ; les ions se forment et se recombinent aussi vite.
- C. Une fois formés, les ions $\ce{H3O+}$ et $\ce{OH-}$ restent à l'état d'ions et ne se recombinent plus.
- D. Il y a toujours davantage d'ions $\ce{H3O+}$ que d'ions $\ce{OH-}$, car l'eau est légèrement acide.

**Réponse correcte** : B

**Feedback correct**
L'autoprotolyse $\ce{2 H2O <=> H3O+ + OH-}$ est un équilibre dynamique : la formation et la recombinaison des ions se compensent, ce qui maintient $[\ce{H3O+}] = [\ce{OH-}] = 1{,}0 \times 10^{-7}$ mol/L à 25 °C.

**Feedback incorrect**
- Si A : Même l'eau la plus pure contient des ions : les molécules d'eau échangent des protons spontanément et en permanence, sans rien ajouter.
- Si B : C'est une bonne réponse.
- Si C : La réaction est réversible : les ions se recombinent aussi vite qu'ils se forment, c'est ce qui définit l'équilibre.
- Si D : Chaque autoprotolyse produit un ion $\ce{H3O+}$ et un ion $\ce{OH-}$ ; leurs quantités sont donc égales dans l'eau pure, qui est neutre.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-produit-ionique-eau-symbo-sou-001
concept: produit-ionique-eau
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelle est l'expression du produit ionique de l'eau, avec sa valeur à 25 °C ?

**Options**
- A. $K_e = [\ce{H3O+}][\ce{OH-}] = 1{,}0 \times 10^{-14}$
- B. $K_e = [\ce{H3O+}]/[\ce{OH-}] = 1{,}0 \times 10^{-14}$
- C. $K_e = [\ce{H3O+}][\ce{OH-}]/[\ce{H2O}]^2 = 1{,}0 \times 10^{-14}$
- D. $K_e = [\ce{H3O+}][\ce{OH-}] = 1{,}0 \times 10^{-7}$

**Réponse correcte** : A

**Feedback correct**
Le produit ionique de l'eau est le produit des concentrations en ions $\ce{H3O+}$ et $\ce{OH-}$, égal à $1{,}0 \times 10^{-14}$ à 25 °C.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $K_e$ est un produit, pas un quotient : c'est le produit $[\ce{H3O+}][\ce{OH-}]$ qui est constant.
- Si C : Le solvant n'apparaît pas dans l'expression de la constante (son activité vaut 1) ; $K_e$ s'écrit sans $[\ce{H2O}]$.
- Si D : $1{,}0 \times 10^{-7}$ mol/L est la valeur de chaque concentration dans l'eau pure ; $K_e$ est leur produit, soit $1{,}0 \times 10^{-14}$.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-produit-ionique-eau-symbo-app-001
concept: produit-ionique-eau
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
À 25 °C, une solution aqueuse a un pH de 3,00. Quelle est sa concentration en ions hydroxyde ?

**Options**
- A. $1{,}0 \times 10^{-3}$ mol/L
- B. $1{,}0 \times 10^{-11}$ mol/L
- C. $1{,}0 \times 10^{-7}$ mol/L
- D. 11 mol/L

**Réponse correcte** : B

**Feedback correct**
$[\ce{H3O+}] = 10^{-3}$ mol/L, donc $[\ce{OH-}] = K_e/[\ce{H3O+}] = 10^{-14}/10^{-3} = 1{,}0 \times 10^{-11}$ mol/L.

**Feedback incorrect**
- Si A : C'est la concentration en ions $\ce{H3O+}$. Les ions $\ce{OH-}$ sont beaucoup moins nombreux dans une solution acide.
- Si B : C'est une bonne réponse.
- Si C : $1{,}0 \times 10^{-7}$ mol/L est la concentration de chaque ion dans l'eau pure, pas dans une solution acide.
- Si D : 11 est le pOH, une valeur sans unité ; la concentration s'obtient par $10^{-\text{pOH}}$.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-produit-ionique-eau-symbo-app-002
concept: produit-ionique-eau
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
À 25 °C, une solution aqueuse a une concentration en ions hydroxyde $[\ce{OH-}] = 2{,}5 \times 10^{-4}$ mol/L. Quel est son pH ?

**Options**
- A. 3,60
- B. 10,40
- C. 10,00
- D. 4,40

**Réponse correcte** : B

**Feedback correct**
$\text{pOH} = -\log(2{,}5 \times 10^{-4}) = 3{,}60$, donc $\text{pH} = 14{,}00 - 3{,}60 = 10{,}40$.

**Feedback incorrect**
- Si A : 3,60 est le pOH. Le pH s'en déduit par $\text{pH} = 14 - \text{pOH}$.
- Si B : C'est une bonne réponse.
- Si C : Il ne faut pas tronquer à l'exposant : le facteur 2,5 compte dans le logarithme ($-\log 2{,}5 \approx -0{,}40$).
- Si D : Le facteur 2,5 est supérieur à 1 : $-\log 2{,}5 = -0{,}40$ se retranche de 4 ($4 - 0{,}40 = 3{,}60$) au lieu de s'y ajouter.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-produit-ionique-eau-symbo-ana-001
concept: produit-ionique-eau
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: produit-ionique-eau--ke-varie-avec-ajout
date_validation: 2026-11-10
statut: validated
---

**Question**
On ajoute de l'acide chlorhydrique à de l'eau pure à 25 °C. Quelle description de l'évolution des grandeurs de la solution est correcte ?

**Options**
- A. $[\ce{H3O+}]$ augmente, $[\ce{OH-}]$ ne change pas, donc $K_e$ augmente.
- B. $[\ce{H3O+}]$ augmente, $[\ce{OH-}]$ diminue, donc $K_e$ diminue.
- C. $[\ce{H3O+}]$ augmente, $[\ce{OH-}]$ diminue, et $K_e$ garde la valeur $1{,}0 \times 10^{-14}$.
- D. $[\ce{H3O+}]$ augmente et $[\ce{OH-}]$ devient nulle, car l'acide consomme tous les ions hydroxyde.

**Réponse correcte** : C

**Feedback correct**
L'équilibre d'autoprotolyse se déplace vers la gauche : $[\ce{OH-}]$ diminue autant que $[\ce{H3O+}]$ augmente, de sorte que le produit reste égal à $K_e$. $K_e$ ne dépend que de la température.

**Feedback incorrect**
- Si A : $[\ce{OH-}]$ diminue : l'excès d'ions $\ce{H3O+}$ déplace l'équilibre d'autoprotolyse vers la gauche. De plus, $K_e$ est une constante d'équilibre : elle ne varie pas avec la composition.
- Si B : La diminution de $[\ce{OH-}]$ compense exactement l'augmentation de $[\ce{H3O+}]$. Le produit, c'est-à-dire $K_e$, ne change pas.
- Si C : C'est une bonne réponse.
- Si D : Il reste toujours des ions $\ce{OH-}$, même en milieu très acide ; leur concentration est simplement très faible, imposée par $[\ce{OH-}] = K_e/[\ce{H3O+}]$.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-produit-ionique-eau-symbo-eva-001
concept: produit-ionique-eau
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: produit-ionique-eau--neutre-egal-ph-7
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « À 0 °C, le produit ionique de l'eau vaut $K_e = 1{,}1 \times 10^{-15}$, donc l'eau pure y a un pH supérieur à 7 : elle est basique. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte : un pH supérieur à 7 indique toujours une solution basique.
- B. Elle est fausse : l'eau reste neutre ; seul son pH de neutralité (environ 7,48) change.
- C. Elle est fausse : l'eau pure est neutre à toute température et son pH vaut donc toujours exactement 7.
- D. Elle est correcte : une baisse de température diminue $[\ce{H3O+}]$ sans changer $[\ce{OH-}]$.

**Réponse correcte** : B

**Feedback correct**
À 0 °C, $[\ce{H3O+}] = [\ce{OH-}] = \sqrt{1{,}1 \times 10^{-15}} \approx 3{,}3 \times 10^{-8}$ mol/L, soit un pH d'environ 7,48. L'eau est neutre parce que les deux concentrations sont égales, pas parce que son pH vaut 7.

**Feedback incorrect**
- Si A : Le critère « pH supérieur à 7 donc basique » n'est valable qu'à 25 °C. Le critère général compare $[\ce{H3O+}]$ et $[\ce{OH-}]$.
- Si B : C'est une bonne réponse.
- Si C : La conclusion est juste (l'eau reste neutre) mais l'explication est fausse : le pH de l'eau pure neutre varie avec la température parce que $K_e$ varie.
- Si D : L'autoprotolyse produit toujours autant d'ions $\ce{H3O+}$ que d'ions $\ce{OH-}$ ; les deux concentrations diminuent ensemble quand la température baisse.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-amphoterisme-parti-sou-001
concept: amphoterisme
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: parti
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Au niveau particulaire, qu'est-ce qui caractérise une espèce amphotère ?

**Options**
- A. Elle peut céder ou capter un proton, selon son partenaire.
- B. Elle ne réagit avec aucun acide ni aucune base.
- C. Elle porte à la fois une charge positive et une charge négative.
- D. Elle est à la fois un acide fort et une base forte.

**Réponse correcte** : A

**Feedback correct**
Une espèce amphotère appartient à deux couples acide-base : elle joue le rôle d'acide avec une base plus forte qu'elle, et le rôle de base avec un acide plus fort qu'elle. L'eau et l'ion $\ce{HCO3-}$ en sont des exemples.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Au contraire, une espèce amphotère réagit avec les acides comme avec les bases.
- Si C : La charge n'a rien à voir avec l'amphotérisme : l'eau est amphotère et neutre. C'est la capacité à céder et à capter un proton qui compte.
- Si D : Une espèce amphotère n'est en général ni un acide fort ni une base forte ; elle est le plus souvent faiblement acide et faiblement basique à la fois.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-amphoterisme-symbo-com-001
concept: amphoterisme
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-10
statut: validated
---

**Question**
À quels deux couples acide-base l'ion hydrogénocarbonate $\ce{HCO3-}$ appartient-il ?

**Options**
- A. $\ce{HCO3-/CO3^{2-}}$ et $\ce{CO3^{2-}/CO2}$
- B. $\ce{H3O+/H2O}$ et $\ce{H2O/OH-}$
- C. $\ce{H2CO3/HCO3-}$ et $\ce{HCO3-/CO3^{2-}}$
- D. $\ce{H2CO3/HCO3-}$ et $\ce{CO2/HCO3-}$

**Réponse correcte** : C

**Feedback correct**
$\ce{HCO3-}$ est la base du couple $\ce{H2CO3/HCO3-}$ (il capte un proton pour donner $\ce{H2CO3}$) et l'acide du couple $\ce{HCO3-/CO3^{2-}}$ (il cède un proton pour donner $\ce{CO3^{2-}}$). C'est ce qui le rend amphotère.

**Feedback incorrect**
- Si A : Le couple $\ce{CO3^{2-}/CO2}$ n'est pas un couple acide-base : les couples de $\ce{HCO3-}$ sont ceux dont il est acide ou base conjuguée, en échangeant un seul proton.
- Si B : Ce sont les deux couples de l'eau, elle aussi amphotère, mais ils ne font pas intervenir l'ion $\ce{HCO3-}$.
- Si C : C'est une bonne réponse.
- Si D : Le couple $\ce{CO2/HCO3-}$ désigne le même acide que $\ce{H2CO3}$ (le $\ce{CO2}$ dissous) : cette réponse omet le couple où $\ce{HCO3-}$ joue le rôle d'acide, $\ce{HCO3-/CO3^{2-}}$.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-amphoterisme-symbo-app-001
concept: amphoterisme
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le pH d'une solution d'hydrogénocarbonate de sodium, sachant que p$K_{a1}(\ce{H2CO3/HCO3-}) = 6{,}35$ et p$K_{a2}(\ce{HCO3-/CO3^{2-}}) = 10{,}25$.

**Options**
- A. 6,35
- B. 8,30
- C. 10,25
- D. 16,60

**Réponse correcte** : B

**Feedback correct**
Pour un ampholyte, $\text{pH} \approx \frac{1}{2}(\text{p}K_{a1} + \text{p}K_{a2}) = \frac{1}{2}(6{,}35 + 10{,}25) = 8{,}30$.

**Feedback incorrect**
- Si A : Ce serait le pH d'une solution contenant autant de $\ce{H2CO3}$ que de $\ce{HCO3-}$ ; l'ampholyte dépend des deux p$K_a$.
- Si B : C'est une bonne réponse.
- Si C : Ce serait le pH d'une solution contenant autant de $\ce{HCO3-}$ que de $\ce{CO3^{2-}}$ ; il faut tenir compte des deux couples.
- Si D : C'est la somme des deux p$K_a$ ; le pH est leur demi-somme.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-amphoterisme-symbo-ana-001
concept: amphoterisme
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-10
statut: validated
---

**Question**
Sans calcul détaillé, que peut-on prévoir du pH d'une solution d'hydrogénocarbonate de sodium ($\ce{HCO3-}$ : p$K_{a1} = 6{,}35$ ; p$K_{a2} = 10{,}25$) ?

**Options**
- A. Il vaut 7, car l'ion est amphotère.
- B. Il est inférieur à 6,35, car l'ion est un acide.
- C. Il est supérieur à 10,25, car l'ion est la base conjuguée d'un acide faible.
- D. Il est compris entre 6,35 et 10,25, et la solution est plutôt basique.

**Réponse correcte** : D

**Feedback correct**
Le pH d'un ampholyte se situe entre les deux p$K_a$, vers leur milieu : environ 8,3. Il est supérieur à 7, la solution est donc légèrement basique.

**Feedback incorrect**
- Si A : L'amphotérisme ne rend pas la solution neutre : le pH dépend des deux p$K_a$ et vaut ici environ 8,3.
- Si B : L'ion est aussi une base ; le pH ne descend pas sous le p$K_a$ du couple dont il est la base ($\ce{H2CO3/HCO3-}$).
- Si C : L'ion est aussi un acide ; le pH ne dépasse pas le p$K_a$ du couple dont il est l'acide ($\ce{HCO3-/CO3^{2-}}$).
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-amphoterisme-symbo-ana-002
concept: amphoterisme
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-10
statut: validated
---

**Question**
Sans calcul détaillé, que peut-on prévoir du pH d'une solution de dihydrogénophosphate de sodium ($\ce{H2PO4-}$ : p$K_{a1} = 2{,}12$ ; p$K_{a2} = 7{,}20$) ?

**Options**
- A. Il vaut 7, car l'ion est amphotère.
- B. Il est compris entre 2,12 et 7,20, et la solution est plutôt acide.
- C. Il est supérieur à 7,20, car l'ion est la base conjuguée de $\ce{H3PO4}$.
- D. Il vaut exactement 7,20.

**Réponse correcte** : B

**Feedback correct**
Le pH d'un ampholyte se situe entre les deux p$K_a$, vers leur milieu : $\frac{1}{2}(2{,}12 + 7{,}20) = 4{,}66$. Il est inférieur à 7, la solution est donc acide.

**Feedback incorrect**
- Si A : L'amphotérisme ne rend pas la solution neutre : le pH dépend des deux p$K_a$ et vaut ici environ 4,7.
- Si B : C'est une bonne réponse.
- Si C : L'ion est la base conjuguée de $\ce{H3PO4}$, mais aussi un acide ; le pH reste compris entre les deux p$K_a$.
- Si D : Le pH vaudrait 7,20 si l'ion se trouvait avec sa base conjuguée $\ce{HPO4^{2-}}$ en quantités égales, ce qui n'est pas le cas dans cette solution.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-amphoterisme-symbo-eva-001
concept: amphoterisme
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: amphoterisme--amphotere-egal-neutre
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « L'ion $\ce{HCO3-}$ est amphotère, donc sa solution aqueuse est neutre. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est vraie : les comportements d'acide et de base se compensent exactement.
- B. Elle est fausse : la solution est acide, car l'ion contient un atome d'hydrogène.
- C. Elle est fausse : le pH dépend des deux p$K_a$ et vaut environ 8,3, ce qui est légèrement basique.
- D. Elle est fausse : la solution est fortement basique (pH supérieur à 12), car l'ion est une base.

**Réponse correcte** : C

**Feedback correct**
« Amphotère » décrit une capacité (céder ou capter un proton), pas un pH. Le pH d'un ampholyte vaut $\frac{1}{2}(\text{p}K_{a1} + \text{p}K_{a2}) = \frac{1}{2}(6{,}35 + 10{,}25) = 8{,}30$ : il n'est neutre que si la demi-somme des deux p$K_a$ vaut 7.

**Feedback incorrect**
- Si A : Les deux comportements ne se compensent pas : leur importance relative dépend des constantes, et la demi-somme des p$K_a$ vaut ici 8,3.
- Si B : Présence d'hydrogène n'implique pas acidité de la solution : l'ion est aussi une base, et ici son caractère basique l'emporte.
- Si C : C'est une bonne réponse.
- Si D : Le pH ne dépasse pas le p$K_a$ du couple $\ce{HCO3-/CO3^{2-}}$ (10,25) et vaut environ 8,3.

**Référence manuel** : acides-bases-ph-ke-amphoterisme

---

---
id: q-constante-acidite-macro-com-001
concept: constante-acidite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
misconception: constante-acidite--ka-varie-avec-concentration
date_validation: 2026-11-10
statut: validated
---

**Question**
À température constante, on dilue une solution d'acide éthanoïque (acétique) en y ajoutant de l'eau. Que devient la constante d'acidité $K_a$ du couple $\ce{CH3COOH/CH3COO-}$ ?

**Options**
- A. Elle augmente, car l'acide est proportionnellement plus dissocié.
- B. Elle est divisée par le facteur de dilution.
- C. Elle ne change pas : elle ne dépend que de la température.
- D. Elle diminue, car toutes les concentrations diminuent.

**Réponse correcte** : C

**Feedback correct**
$K_a$ est une constante d'équilibre : elle ne varie qu'avec la température. En diluant, les concentrations changent mais le quotient $[\ce{A-}][\ce{H3O+}]/[\ce{HA}]$ retrouve la même valeur à l'équilibre.

**Feedback incorrect**
- Si A : C'est la proportion de molécules dissociées (le coefficient $\alpha$) qui augmente quand on dilue, pas la constante $K_a$.
- Si B : $K_a$ n'est pas une concentration : elle ne se dilue pas. Elle garde sa valeur tant que la température ne change pas.
- Si C : C'est une bonne réponse.
- Si D : Les concentrations diminuent, mais l'équilibre se réajuste de sorte que le quotient reste égal à $K_a$.

**Référence manuel** : acides-bases-ph-ka-pka

---

---
id: q-constante-acidite-symbo-sou-001
concept: constante-acidite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelle est l'expression de la constante d'acidité du couple $\ce{HF/F-}$ dans l'eau ?

**Options**
- A. $K_a = \dfrac{[\ce{HF}]}{[\ce{F-}][\ce{H3O+}]}$
- B. $K_a = \dfrac{[\ce{F-}][\ce{H3O+}]}{[\ce{HF}]}$
- C. $K_a = \dfrac{[\ce{F-}][\ce{OH-}]}{[\ce{HF}]}$
- D. $K_a = \dfrac{[\ce{F-}][\ce{H3O+}]}{[\ce{HF}][\ce{H2O}]}$

**Réponse correcte** : B

**Feedback correct**
La réaction $\ce{HF + H2O <=> F- + H3O+}$ conduit à $K_a = [\ce{F-}][\ce{H3O+}]/[\ce{HF}]$ : les produits au numérateur, l'acide au dénominateur, sans l'eau.

**Feedback incorrect**
- Si A : Cette expression est inversée : les produits de la réaction de dissociation se placent au numérateur.
- Si B : C'est une bonne réponse.
- Si C : Avec $\ce{OH-}$, on obtiendrait une constante de basicité (réaction de $\ce{F-}$ avec l'eau), pas la constante d'acidité.
- Si D : Le solvant n'apparaît pas dans l'expression de la constante (son activité vaut 1).

**Référence manuel** : acides-bases-ph-ka-pka

---

---
id: q-constante-acidite-symbo-com-001
concept: constante-acidite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: com
misconception: constante-acidite--pka-eleve-acide-fort
date_validation: 2026-11-10
statut: validated
---

**Question**
Les p$K_a$ des couples $\ce{HF/F-}$ et $\ce{HCN/CN-}$ valent respectivement 3,17 et 9,22. Quelle conclusion est correcte ?

**Options**
- A. $\ce{HCN}$ est un acide plus fort que $\ce{HF}$, car son p$K_a$ est plus grand.
- B. $\ce{HF}$ est un acide plus fort que $\ce{HCN}$ : son p$K_a$ est plus petit, donc son $K_a$ est plus grand.
- C. $\ce{HF}$ est un acide plus fort que $\ce{HCN}$ : son p$K_a$ est plus petit, donc son $K_a$ est plus petit.
- D. Les deux acides ont la même force, car ce sont tous deux des acides faibles.

**Réponse correcte** : B

**Feedback correct**
Comme $\text{p}K_a = -\log K_a$, un p$K_a$ plus petit correspond à un $K_a$ plus grand, donc à un acide plus dissocié : $\ce{HF}$ est un acide plus fort que $\ce{HCN}$.

**Feedback incorrect**
- Si A : Le signe moins de la définition inverse l'ordre : plus le p$K_a$ est grand, plus le $K_a$ est petit et plus l'acide est faible.
- Si B : C'est une bonne réponse.
- Si C : La conclusion est juste, mais la justification est erronée : un p$K_a$ plus petit correspond à un $K_a$ plus grand.
- Si D : Deux acides faibles n'ont pas la même force : leur $K_a$ peuvent différer de plusieurs puissances de dix ($7 \times 10^{-4}$ pour $\ce{HF}$, $6 \times 10^{-10}$ pour $\ce{HCN}$).

**Référence manuel** : acides-bases-ph-ka-pka

---

---
id: q-constante-acidite-symbo-app-001
concept: constante-acidite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le p$K_a$ de l'acide benzoïque $\ce{C6H5COOH}$, dont la constante d'acidité vaut $K_a = 6{,}46 \times 10^{-5}$.

**Options**
- A. 4,19
- B. 9,81
- C. 5,81
- D. $-4{,}19$

**Réponse correcte** : A

**Feedback correct**
$\text{p}K_a = -\log(6{,}46 \times 10^{-5}) = 5 - 0{,}81 = 4{,}19$, car le logarithme décimal de 6,46 vaut 0,81.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : 9,81 est le p$K_b$ de la base conjuguée ($14 - 4{,}19$), pas le p$K_a$ de l'acide.
- Si C : Le logarithme décimal de 6,46 (0,81) se retranche de 5 et ne s'y ajoute pas.
- Si D : Le p$K_a$ d'un acide faible est positif, puisque son $K_a$ est inférieur à 1.

**Référence manuel** : acides-bases-ph-ka-pka

---

---
id: q-constante-acidite-symbo-app-002
concept: constante-acidite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Le p$K_a$ du couple $\ce{HNO2/NO2-}$ vaut 3,2. Quelle est la valeur de la constante d'acidité $K_a$ ?

**Options**
- A. $3{,}2 \times 10^{-4}$
- B. $6{,}3 \times 10^{-4}$
- C. $1{,}6 \times 10^{3}$
- D. $1{,}6 \times 10^{-11}$

**Réponse correcte** : B

**Feedback correct**
$K_a = 10^{-\text{p}K_a} = 10^{-3{,}2} = 6{,}3 \times 10^{-4}$.

**Feedback incorrect**
- Si A : Il ne suffit pas de reprendre « 3,2 » avec un exposant : $10^{-3{,}2} = 10^{-4} \times 10^{0{,}8}$, soit $6{,}3 \times 10^{-4}$.
- Si B : C'est une bonne réponse.
- Si C : Le signe de l'exposant est inversé : $K_a = 10^{-\text{p}K_a}$ et non $10^{+\text{p}K_a}$.
- Si D : C'est la constante de basicité de l'ion nitrite ($K_b = 10^{-14}/K_a$), pas la constante d'acidité de l'acide nitreux.

**Référence manuel** : acides-bases-ph-ka-pka

---

---
id: q-constante-acidite-symbo-ana-001
concept: constante-acidite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-10
statut: validated
---

**Question**
On prépare deux solutions de même concentration, 0,10 mol/L : l'une d'acide fluorhydrique $\ce{HF}$ (p$K_a = 3{,}17$), l'autre d'acide éthanoïque (p$K_a = 4{,}75$). Laquelle a le pH le plus bas, et pourquoi ?

**Options**
- A. La solution d'acide éthanoïque, car son p$K_a$ est plus grand.
- B. Les deux ont le même pH, car leurs concentrations sont égales.
- C. L'acide fluorhydrique, plus dissocié car son p$K_a$ est plus petit.
- D. On ne peut pas conclure sans connaître le volume de chaque solution.

**Réponse correcte** : C

**Feedback correct**
Un p$K_a$ plus petit signifie un $K_a$ plus grand : à même concentration, $\ce{HF}$ libère davantage d'ions $\ce{H3O+}$, donc le pH de sa solution est plus bas.

**Feedback incorrect**
- Si A : Un p$K_a$ plus grand signifie un acide plus faible, donc moins d'ions $\ce{H3O+}$ et un pH plus élevé.
- Si B : À même concentration, la force de l'acide fait la différence : plus $K_a$ est grand, plus $[\ce{H3O+}]$ est grand.
- Si C : C'est une bonne réponse.
- Si D : Le pH dépend de la concentration et non de la quantité de solution : le volume n'intervient pas dans la comparaison.

**Référence manuel** : acides-bases-ph-ka-pka

---

---
id: q-constante-acidite-symbo-eva-001
concept: constante-acidite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: constante-acidite--ka-varie-avec-concentration
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Si j'ajoute de l'éthanoate de sodium à une solution d'acide éthanoïque, la concentration $[\ce{CH3COO-}]$ augmente, donc $K_a$ augmente aussi. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte : $K_a$ est proportionnelle à $[\ce{CH3COO-}]$.
- B. Elle est fausse : $K_a$ est constante ; c'est $[\ce{H3O+}]$ qui diminue.
- C. Elle est fausse : $K_a$ diminue, car $[\ce{H3O+}]$ diminue.
- D. Elle est fausse : $K_a$ diminue, car $[\ce{CH3COOH}]$ augmente.

**Réponse correcte** : B

**Feedback correct**
$K_a$ ne varie qu'avec la température. L'ajout d'ions éthanoate déplace l'équilibre vers la gauche : $[\ce{H3O+}]$ diminue, $[\ce{CH3COOH}]$ augmente, et le quotient reprend exactement la valeur de $K_a$.

**Feedback incorrect**
- Si A : $K_a$ n'est pas proportionnelle à une concentration : si $[\ce{CH3COO-}]$ augmente, l'équilibre se déplace de façon à ramener le quotient à $K_a$.
- Si B : C'est une bonne réponse.
- Si C : $[\ce{H3O+}]$ diminue bien, mais $[\ce{A-}]$ augmente en même temps : le quotient reste égal à $K_a$.
- Si D : $[\ce{CH3COOH}]$ augmente bien, mais $[\ce{H3O+}]$ diminue : le quotient reste égal à $K_a$.

**Référence manuel** : acides-bases-ph-ka-pka

---

---
id: q-constante-basicite-symbo-sou-001
concept: constante-basicite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelle équation et quelle expression correspondent à la constante de basicité de l'ammoniac $\ce{NH3}$ ?

**Options**
- A. $\ce{NH3 + H2O <=> NH4+ + OH-}$ et $K_b = \dfrac{[\ce{NH4+}][\ce{OH-}]}{[\ce{NH3}]}$
- B. $\ce{NH3 + H2O <=> NH4+ + OH-}$ et $K_b = \dfrac{[\ce{NH3}]}{[\ce{NH4+}][\ce{OH-}]}$
- C. $\ce{NH4+ + H2O <=> NH3 + H3O+}$ et $K_b = \dfrac{[\ce{NH3}][\ce{H3O+}]}{[\ce{NH4+}]}$
- D. $\ce{NH3 + H2O <=> NH4+ + OH-}$ et $K_b = \dfrac{[\ce{NH4+}][\ce{OH-}]}{[\ce{NH3}][\ce{H2O}]}$

**Réponse correcte** : A

**Feedback correct**
L'ammoniac capte un proton de l'eau : $\ce{NH3 + H2O <=> NH4+ + OH-}$. La constante est le quotient des produits sur le réactif, sans l'eau : $K_b = [\ce{NH4+}][\ce{OH-}]/[\ce{NH3}]$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : L'expression est inversée : les produits de la réaction se placent au numérateur.
- Si C : C'est la réaction de l'acide $\ce{NH4+}$ avec l'eau, dont la constante est $K_a$, pas $K_b$.
- Si D : Le solvant n'apparaît pas dans l'expression de la constante (son activité vaut 1).

**Référence manuel** : acides-bases-ph-kb

---

---
id: q-constante-basicite-symbo-com-001
concept: constante-basicite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: com
misconception: constante-basicite--base-conjuguee-sans-basicite
date_validation: 2026-11-10
statut: validated
---

**Question**
L'ion éthanoate $\ce{CH3COO-}$ est la base conjuguée de l'acide éthanoïque, qui est un acide faible. Quelle affirmation est correcte ?

**Options**
- A. Il n'a aucun caractère basique, car l'acide éthanoïque n'est pas une base.
- B. C'est une base forte, car la base conjuguée d'un acide faible est toujours forte.
- C. Son $K_b$ est égal au $K_a$ de l'acide éthanoïque.
- D. Il a un caractère basique faible, mesuré par $K_b = K_e/K_a$.

**Réponse correcte** : D

**Feedback correct**
Dans un couple, $K_a \cdot K_b = K_e$. Pour l'acide éthanoïque, $K_b(\ce{CH3COO-}) = 10^{-14}/(1{,}78 \times 10^{-5}) \approx 5{,}6 \times 10^{-10}$ : l'ion est une base faible mais bien réelle. Plus $K_a$ est petit, plus $K_b$ est grand.

**Feedback incorrect**
- Si A : Toute espèce capable de capter un proton est une base : l'ion éthanoate capte un proton de l'eau. Son caractère basique est faible mais non nul.
- Si B : Une base conjuguée n'est forte que si l'acide est très faible (négligeable dans l'eau). Ici $K_b \approx 5{,}6 \times 10^{-10}$ : la base reste faible.
- Si C : Les deux constantes sont liées par $K_a \cdot K_b = K_e$, pas égales : $K_b$ vaut ici environ $5{,}6 \times 10^{-10}$ alors que $K_a = 1{,}78 \times 10^{-5}$.
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-kb

---

---
id: q-constante-basicite-symbo-app-001
concept: constante-basicite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez la constante de basicité de l'ion éthanoate $\ce{CH3COO-}$ à 25 °C, sachant que $K_a(\ce{CH3COOH}) = 1{,}78 \times 10^{-5}$.

**Options**
- A. $5{,}6 \times 10^{-10}$
- B. $1{,}78 \times 10^{-5}$
- C. $1{,}78 \times 10^{-19}$
- D. 9,25

**Réponse correcte** : A

**Feedback correct**
$K_b = K_e/K_a = 10^{-14}/(1{,}78 \times 10^{-5}) = 5{,}6 \times 10^{-10}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est la valeur de $K_a$ de l'acide. $K_b$ de la base conjuguée s'en déduit par $K_b = K_e/K_a$.
- Si C : C'est le produit $K_e \times K_a$. La relation est $K_a \cdot K_b = K_e$, donc $K_b = K_e/K_a$.
- Si D : 9,25 est le p$K_b$ (sans unité), pas la constante $K_b$ elle-même.

**Référence manuel** : acides-bases-ph-kb

---

---
id: q-constante-basicite-symbo-app-002
concept: constante-basicite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Le p$K_a$ du couple $\ce{HF/F-}$ vaut 3,17. Quel est le p$K_b$ de l'ion fluorure $\ce{F-}$ à 25 °C ?

**Options**
- A. 3,17
- B. 10,83
- C. 17,17
- D. 3,83

**Réponse correcte** : B

**Feedback correct**
Pour un couple conjugué, $\text{p}K_a + \text{p}K_b = 14$ à 25 °C, donc $\text{p}K_b = 14 - 3{,}17 = 10{,}83$.

**Feedback incorrect**
- Si A : C'est le p$K_a$ du couple. Le p$K_b$ de la base conjuguée s'en déduit par $\text{p}K_b = 14 - \text{p}K_a$.
- Si B : C'est une bonne réponse.
- Si C : C'est la somme $14 + 3{,}17$. La relation est $\text{p}K_a + \text{p}K_b = 14$, donc une soustraction.
- Si D : Il s'agit d'une erreur de calcul : $14 - 3{,}17 = 10{,}83$ et non 3,83.

**Référence manuel** : acides-bases-ph-kb

---

---
id: q-constante-basicite-symbo-ana-001
concept: constante-basicite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-10
statut: validated
---

**Question**
Les p$K_a$ des acides conjugués valent 3,17 pour $\ce{HF}$, 4,75 pour $\ce{CH3COOH}$ et 9,22 pour $\ce{NH4+}$. Quel classement des bases $\ce{F-}$, $\ce{CH3COO-}$ et $\ce{NH3}$ est correct, de la plus faible à la plus forte ?

**Options**
- A. $\ce{F-} < \ce{CH3COO-} < \ce{NH3}$
- B. $\ce{NH3} < \ce{CH3COO-} < \ce{F-}$
- C. $\ce{CH3COO-} < \ce{F-} < \ce{NH3}$
- D. $\ce{F-} < \ce{NH3} < \ce{CH3COO-}$

**Réponse correcte** : A

**Feedback correct**
Plus le p$K_a$ de l'acide conjugué est grand, plus l'acide est faible et plus sa base conjuguée est forte ($\text{p}K_b = 14 - \text{p}K_a$) : $\ce{F-}$ (p$K_b$ 10,83) < $\ce{CH3COO-}$ (9,25) < $\ce{NH3}$ (4,78).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Ce classement est inversé : c'est l'acide le plus fort ($\ce{HF}$) qui a la base conjuguée la plus faible.
- Si C : L'ion éthanoate est une base plus forte que l'ion fluorure, car son acide conjugué est plus faible ($\text{p}K_a$ 4,75 contre 3,17).
- Si D : L'ammoniac est la base la plus forte des trois (acide conjugué le plus faible) ; l'ion éthanoate est plus faible que lui.

**Référence manuel** : acides-bases-ph-kb

---

---
id: q-constante-basicite-symbo-eva-001
concept: constante-basicite
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: constante-basicite--somme-ka-kb
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Pour un couple acide-base, $K_a + K_b = K_e$. » Vérifiez avec le couple $\ce{NH4+/NH3}$ ($K_a = 6 \times 10^{-10}$ ; $K_b = 1{,}7 \times 10^{-5}$ à 25 °C). Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte, car les deux constantes sont petites et leur somme est petite.
- B. Elle est fausse : c'est leur produit, et non leur somme, qui vaut $K_e$.
- C. Elle est fausse : c'est le quotient $K_a/K_b$ qui est égal à $K_e$.
- D. Elle est fausse : la relation correcte est $K_a = K_b$ pour tout couple conjugué.

**Réponse correcte** : B

**Feedback correct**
La relation est $K_a \cdot K_b = K_e$ : ici $6 \times 10^{-10} \times 1{,}7 \times 10^{-5} \approx 1{,}0 \times 10^{-14}$. Ce sont les p$K$ qui s'additionnent : $\text{p}K_a + \text{p}K_b = 14$.

**Feedback incorrect**
- Si A : La somme vaut environ $1{,}7 \times 10^{-5}$, très loin de $1{,}0 \times 10^{-14}$ : l'affirmation est contredite par le calcul.
- Si B : C'est une bonne réponse.
- Si C : Le quotient $K_a/K_b$ vaut environ $3{,}5 \times 10^{-5}$, très loin de $1{,}0 \times 10^{-14}$ ; seul le produit convient.
- Si D : Pour $\ce{NH4+/NH3}$, $K_a = 6 \times 10^{-10}$ et $K_b = 1{,}7 \times 10^{-5}$ sont très différents ; ils ne sont égaux que si les deux valent $10^{-7}$.

**Référence manuel** : acides-bases-ph-kb

---

---
id: q-ph-acide-base-fort-macro-com-001
concept: ph-acide-base-fort
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
misconception: ph-fort--acide-fort-ph-un
date_validation: 2026-11-10
statut: validated
---

**Question**
On mesure un pH de 2,0 pour une solution d'acide chlorhydrique, et un pH de 0,0 pour une autre solution d'acide chlorhydrique. Que peut-on en conclure ?

**Options**
- A. La première solution contient un acide qui n'est pas fort, car un acide fort a toujours un pH de 1.
- B. La seconde solution est cent fois plus concentrée que la première.
- C. La seconde solution est deux fois plus concentrée que la première, car le pH diffère de deux unités.
- D. Les deux solutions devraient avoir le même pH ; l'une des mesures est erronée.

**Réponse correcte** : B

**Feedback correct**
Un acide fort est entièrement dissocié : $[\ce{H3O+}] = c_0$, donc le pH dépend de la concentration. Un pH de 0,0 correspond à 1 mol/L et un pH de 2,0 à 0,01 mol/L : le rapport est de 100.

**Feedback incorrect**
- Si A : La valeur du pH d'un acide fort n'est pas fixée à 1 : elle vaut $-\log c_0$ et dépend donc de la concentration. Les deux solutions contiennent bien un acide fort.
- Si B : C'est une bonne réponse.
- Si C : Le pH est une échelle logarithmique : une différence de deux unités correspond à un facteur cent sur la concentration, pas à un facteur 2.
- Si D : Deux solutions du même acide fort peuvent avoir des pH très différents si leurs concentrations diffèrent.

**Référence manuel** : acides-bases-ph-ph-forts

---

---
id: q-ph-acide-base-fort-parti-app-001
concept: ph-acide-base-fort
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: parti
type: app
misconception: ph-fort--base-forte-stoechiometrie-poh
date_validation: 2026-11-10
statut: validated
---

**Question**
Une solution d'hydroxyde de calcium $\ce{Ca(OH)2}$ (base forte) de concentration $c_0 = 0{,}010$ mol/L est entièrement dissociée. Combien d'ions hydroxyde libère chaque unité de formule dissoute, et que vaut $[\ce{OH-}]$ ?

**Options**
- A. Un ion hydroxyde ; $[\ce{OH-}] = 0{,}010$ mol/L.
- B. Deux ions hydroxyde ; $[\ce{OH-}] = 0{,}010$ mol/L, car la concentration ne change pas.
- C. Deux ions hydroxyde ; $[\ce{OH-}] = 0{,}020$ mol/L.
- D. Deux ions hydroxyde ; $[\ce{OH-}] = 0{,}0050$ mol/L, car on divise par deux.

**Réponse correcte** : C

**Feedback correct**
$\ce{Ca(OH)2 -> Ca^{2+} + 2 OH-}$ : chaque unité de formule libère deux ions hydroxyde, donc $[\ce{OH-}] = 2c_0$, soit 0,020 mol/L (pH = 12,30).

**Feedback incorrect**
- Si A : La formule $\ce{Ca(OH)2}$ contient deux groupes hydroxyde : il faut en tenir compte, la concentration en ions $\ce{OH-}$ vaut $2c_0$.
- Si B : Les ions $\ce{OH-}$ sont deux fois plus nombreux que les unités de formule dissoutes : leur concentration est donc le double de $c_0$.
- Si C : C'est une bonne réponse.
- Si D : Le coefficient stœchiométrique 2 multiplie la concentration, il ne la divise pas.

**Référence manuel** : acides-bases-ph-ph-forts

---

---
id: q-ph-acide-base-fort-symbo-sou-001
concept: ph-acide-base-fort
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelle relation donne le pH d'une solution de base forte monohydroxylée (par exemple NaOH) de concentration $c_0$, à 25 °C ?

**Options**
- A. $\text{pH} = -\log c_0$
- B. $\text{pH} = 14 - \log c_0$
- C. $\text{pH} = 14 + \log c_0$
- D. $\text{pH} = \log c_0$

**Réponse correcte** : C

**Feedback correct**
$[\ce{OH-}] = c_0$, donc $\text{pOH} = -\log c_0$ et $\text{pH} = 14 - \text{pOH} = 14 + \log c_0$ (avec $\log c_0 < 0$ pour $c_0 < 1$ mol/L).

**Feedback incorrect**
- Si A : Cette relation est celle d'un acide fort : elle donne un pH inférieur à 7, ce qui est impossible pour une base.
- Si B : Le signe de $\log c_0$ est faux : $\text{pOH} = -\log c_0$ et $\text{pH} = 14 - \text{pOH}$, soit $14 + \log c_0$. Avec $c_0 = 0{,}1$ mol/L, cette formule donnerait un pH de 15.
- Si C : C'est une bonne réponse.
- Si D : Cette expression donne un nombre négatif pour $c_0 < 1$ mol/L ; ce n'est pas un pH.

**Référence manuel** : acides-bases-ph-ph-forts

---

---
id: q-ph-acide-base-fort-symbo-app-001
concept: ph-acide-base-fort
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le pH d'une solution d'acide chlorhydrique de concentration $c_0 = 0{,}025$ mol/L à 25 °C.

**Options**
- A. 0,025
- B. 1,60
- C. 2,60
- D. 12,40

**Réponse correcte** : B

**Feedback correct**
L'acide chlorhydrique est un acide fort : $[\ce{H3O+}] = c_0$, soit 0,025 mol/L, donc $\text{pH} = -\log(0{,}025) = 1{,}60$.

**Feedback incorrect**
- Si A : 0,025 est la concentration, pas le pH. Le pH est le logarithme décimal de la concentration, changé de signe.
- Si B : C'est une bonne réponse.
- Si C : 2,60 vient d'un signe inversé : le logarithme de 2,5 (0,40) se retranche de 2 au lieu de s'y ajouter, ce qui donne 1,60.
- Si D : 12,40 est le pH d'une base forte de même concentration, pas celui d'un acide.

**Référence manuel** : acides-bases-ph-ph-forts

---

---
id: q-ph-acide-base-fort-symbo-app-002
concept: ph-acide-base-fort
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le pH d'une solution d'hydroxyde de sodium de concentration $c_0 = 0{,}020$ mol/L à 25 °C.

**Options**
- A. 1,70
- B. 12,30
- C. 13,00
- D. 11,70

**Réponse correcte** : B

**Feedback correct**
NaOH est une base forte : $[\ce{OH-}] = c_0$, soit 0,020 mol/L, donc $\text{pOH} = -\log(0{,}020) = 1{,}70$ et $\text{pH} = 14 - 1{,}70 = 12{,}30$.

**Feedback incorrect**
- Si A : 1,70 est le pOH. Le pH d'une base s'obtient par $\text{pH} = 14 - \text{pOH}$.
- Si B : C'est une bonne réponse.
- Si C : 13,00 correspond à une concentration de 0,10 mol/L (pOH égal à 1,00), non à 0,020 mol/L : il ne faut pas arrondir la concentration à la puissance de dix.
- Si D : Il s'agit d'une erreur de calcul : $14 - 1{,}70 = 12{,}30$.

**Référence manuel** : acides-bases-ph-ph-forts

---

---
id: q-ph-acide-base-fort-symbo-ana-001
concept: ph-acide-base-fort
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: ph-fort--dilution-extreme-ph-sup-7
date_validation: 2026-11-10
statut: validated
---

**Question**
On dissout de l'acide chlorhydrique à la concentration $c_0 = 1{,}0 \times 10^{-8}$ mol/L dans de l'eau pure, à 25 °C. Quelle conclusion est correcte ?

**Options**
- A. Le pH vaut 8,0, car $\text{pH} = -\log c_0$.
- B. Le pH vaut 6,0, car on retranche à 14 le pH calculé de 8,0.
- C. Le pH vaut environ 7 (6,98) : l'eau fournit plus d'ions $\ce{H3O+}$ que l'acide.
- D. Le pH vaut exactement 7,00, car un acide aussi dilué n'a aucun effet sur l'eau pure à cette température.

**Réponse correcte** : C

**Feedback correct**
Dans l'eau pure, $[\ce{H3O+}] = 10^{-7}$ mol/L vient déjà de l'autoprotolyse, dix fois plus que l'apport de l'acide. La formule $-\log c_0$ n'est valable que pour $c_0 \gtrsim 10^{-6}$ mol/L ; ici $[\ce{H3O+}] \approx 1{,}05 \times 10^{-7}$ mol/L, soit un pH de 6,98.

**Feedback incorrect**
- Si A : Un pH de 8 serait basique : ajouter un acide à l'eau ne peut pas rendre la solution basique. La formule $-\log c_0$ ne s'applique plus en dessous de $10^{-6}$ mol/L.
- Si B : Cette soustraction n'a aucun fondement ici : le pH d'un acide ne s'obtient pas en retranchant à 14 le résultat d'une formule hors de son domaine de validité.
- Si C : C'est une bonne réponse.
- Si D : L'acide a un effet très faible mais non nul : il fait passer le pH de 7,00 à 6,98.

**Référence manuel** : acides-bases-ph-ph-forts

---

---
id: q-ph-acide-base-fort-symbo-eva-001
concept: ph-acide-base-fort
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève dilue 1000 fois une solution d'acide chlorhydrique à 0,010 mol/L, puis encore 1000 fois. Il prédit un pH de 5 après la première dilution et un pH de 8 après la seconde. Que pensez-vous de ces deux prédictions ?

**Options**
- A. Les deux sont correctes, car $\text{pH} = -\log c$ s'applique à toute concentration.
- B. La première est fausse, car diluer un acide fort ne change pas son pH : seule la quantité d'acide change.
- C. La première est correcte ; la seconde est impossible : un acide reste acide, son pH est proche de 7.
- D. Les deux sont fausses, car diluer 1000 fois multiplie le pH par 1000.

**Réponse correcte** : C

**Feedback correct**
Après la première dilution, $c = 1{,}0 \times 10^{-5}$ mol/L et $\text{pH} = 5$ : la formule s'applique. Après la seconde, $c = 10^{-8}$ mol/L est inférieure à la limite de validité ($10^{-6}$ mol/L) : l'autoprotolyse de l'eau domine et le pH est d'environ 6,98, jamais supérieur à 7 pour un acide.

**Feedback incorrect**
- Si A : La formule a une limite : en dessous de $10^{-6}$ mol/L environ, l'eau fournit plus d'ions $\ce{H3O+}$ que l'acide. Un acide dilué n'a jamais un pH basique.
- Si B : Diluer diminue $[\ce{H3O+}]$ et fait donc monter le pH : dilué 1000 fois, un acide fort passe de pH 2 à pH 5.
- Si C : C'est une bonne réponse.
- Si D : Le pH est un logarithme : diluer 1000 fois ajoute 3 unités au pH, il ne le multiplie pas.

**Référence manuel** : acides-bases-ph-ph-forts

---

---
id: q-melange-acide-base-forts-macro-com-001
concept: melange-acide-base-forts
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
misconception: melange-forts--volumes-egaux-neutre
date_validation: 2026-11-10
statut: validated
---

**Question**
À 25 °C, on mélange 50 mL d'acide chlorhydrique à 0,20 mol/L et 50 mL de soude (hydroxyde de sodium) à 0,10 mol/L. Que peut-on dire de la solution obtenue ?

**Options**
- A. Elle est neutre, car les deux volumes sont égaux.
- B. Elle est neutre, car l'acide et la base sont tous deux forts.
- C. Elle est acide, car il reste un excès d'acide qui n'a pas été neutralisé.
- D. Elle est basique, car la base réagit toujours plus vite que l'acide.

**Réponse correcte** : C

**Feedback correct**
La neutralisation dépend des quantités de matière : $n(\ce{H3O+}) = 10{,}0$ mmol et $n(\ce{OH-}) = 5{,}0$ mmol. Il reste 5,0 mmol d'ions $\ce{H3O+}$ en excès, la solution est acide (pH = 1,30).

**Feedback incorrect**
- Si A : Des volumes égaux ne suffisent pas : les concentrations diffèrent, donc les quantités de matière aussi.
- Si B : Un acide fort et une base forte ne donnent une solution neutre que si leurs quantités de matière sont égales.
- Si C : C'est une bonne réponse.
- Si D : La vitesse de la réaction n'a aucun rapport avec le pH final, qui est déterminé par le réactif en excès.

**Référence manuel** : acides-bases-ph-melanges-forts

---

---
id: q-melange-acide-base-forts-symbo-sou-001
concept: melange-acide-base-forts
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelle est l'équation de la réaction entre un acide fort et une base forte en solution aqueuse, et quelle est sa constante d'équilibre à 25 °C ?

**Options**
- A. $\ce{H3O+ + OH- -> 2 H2O}$ avec $K = 1/K_e = 10^{14}$, réaction quasi totale
- B. $\ce{H3O+ + OH- -> 2 H2O}$ avec $K = K_e = 10^{-14}$, réaction très limitée
- C. $\ce{H3O+ + OH- <=> 2 H2O}$ avec $K = 1$, réaction équilibrée
- D. $\ce{2 H2O -> H3O+ + OH-}$ avec $K = 10^{14}$, réaction quasi totale

**Réponse correcte** : A

**Feedback correct**
La réaction de neutralisation est l'inverse de l'autoprotolyse : $K = 1/K_e = 10^{14}$. Elle est donc quasi totale, ce qui permet de calculer le pH à partir de la quantité du réactif en excès.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $K_e$ est la constante de l'autoprotolyse (sens inverse). La neutralisation est son inverse, de constante $1/K_e$.
- Si C : La constante n'est pas égale à 1 : la neutralisation est quasi totale, avec $K = 10^{14}$.
- Si D : Cette équation décrit l'autoprotolyse, dont la constante est $K_e = 10^{-14}$, et non la neutralisation.

**Référence manuel** : acides-bases-ph-melanges-forts

---

---
id: q-melange-acide-base-forts-symbo-app-001
concept: melange-acide-base-forts
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
À 25 °C, on mélange 100 mL d'acide chlorhydrique à 0,10 mol/L avec 100 mL de soude à 0,050 mol/L. Quel est le pH du mélange ?

**Options**
- A. 1,00
- B. 1,30
- C. 1,60
- D. 7,00

**Réponse correcte** : C

**Feedback correct**
$n(\ce{H3O+}) = 10{,}0$ mmol et $n(\ce{OH-}) = 5{,}0$ mmol, d'où un excès de 5,0 mmol de $\ce{H3O+}$ dans $V = 200$ mL : $[\ce{H3O+}] = 0{,}025$ mol/L et $\text{pH} = 1{,}60$.

**Feedback incorrect**
- Si A : 1,00 correspond à l'acide seul ($c = 0{,}10$ mol/L), sans tenir compte de la soude ajoutée.
- Si B : Le volume utilisé est celui d'une seule solution (100 mL) : il faut diviser l'excès de $\ce{H3O+}$ par le volume total (200 mL).
- Si C : C'est une bonne réponse.
- Si D : Le mélange n'est pas stœchiométrique ($10{,}0$ mmol d'acide contre $5{,}0$ mmol de base) : il reste un excès d'acide et la solution n'est pas neutre.

**Référence manuel** : acides-bases-ph-melanges-forts

---

---
id: q-melange-acide-base-forts-symbo-app-002
concept: melange-acide-base-forts
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
À 25 °C, on mélange 40,0 mL de soude à 0,100 mol/L avec 60,0 mL d'acide chlorhydrique à 0,050 mol/L. Quel est le pH du mélange ?

**Options**
- A. 2,00
- B. 12,00
- C. 12,40
- D. 13,00

**Réponse correcte** : B

**Feedback correct**
$n(\ce{OH-}) = 4{,}00$ mmol et $n(\ce{H3O+}) = 3{,}00$ mmol, d'où un excès de 1,00 mmol de $\ce{OH-}$ dans $V = 100$ mL : $[\ce{OH-}] = 0{,}0100$ mol/L, $\text{pOH} = 2{,}00$ et $\text{pH} = 12{,}00$.

**Feedback incorrect**
- Si A : 2,00 est le pOH. Le pH s'obtient par $\text{pH} = 14 - \text{pOH}$.
- Si B : C'est une bonne réponse.
- Si C : L'excès de $\ce{OH-}$ est divisé par 40,0 mL (volume de la soude) au lieu du volume total (100 mL).
- Si D : 13,00 correspond à la soude seule ($c = 0{,}100$ mol/L), sans tenir compte de l'acide ajouté.

**Référence manuel** : acides-bases-ph-melanges-forts

---

---
id: q-melange-acide-base-forts-symbo-ana-001
concept: melange-acide-base-forts
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: melange-forts--volume-total-oublie
date_validation: 2026-11-10
statut: validated
---

**Question**
On mélange 25,0 mL de soude à 0,100 mol/L et 25,0 mL d'acide nitrique à 0,060 mol/L. Quel est le réactif en excès, et quelle est sa concentration dans le mélange ?

**Options**
- A. L'acide nitrique, à 0,020 mol/L.
- B. La soude, à 0,020 mol/L.
- C. La soude, à 0,040 mol/L.
- D. Aucun : les volumes sont égaux, donc le mélange est neutre.

**Réponse correcte** : B

**Feedback correct**
$n(\ce{OH-}) = 2{,}50$ mmol et $n(\ce{H3O+}) = 1{,}50$ mmol : la soude est en excès de 1,00 mmol. Le volume total est de 50,0 mL, donc $[\ce{OH-}] = 1{,}00/50{,}0 = 0{,}020$ mol/L.

**Feedback incorrect**
- Si A : C'est la soude qui est en excès : elle apporte plus de quantité de matière d'ions $\ce{OH-}$ (2,50 mmol) que l'acide d'ions $\ce{H3O+}$ (1,50 mmol).
- Si B : C'est une bonne réponse.
- Si C : L'excès (1,00 mmol) est divisé par 25,0 mL au lieu du volume total (50,0 mL).
- Si D : Des volumes égaux ne suffisent pas à neutraliser : les concentrations diffèrent, donc les quantités de matière aussi.

**Référence manuel** : acides-bases-ph-melanges-forts

---

---
id: q-melange-acide-base-forts-symbo-eva-001
concept: melange-acide-base-forts
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: melange-forts--ph-moyenne-des-ph
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Si je mélange des volumes égaux d'une solution d'acide fort de pH 2 et d'une solution de base forte de pH 13, le pH du mélange est la moyenne des deux pH, soit 7,5. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte : le pH du mélange est compris entre les deux pH de départ.
- B. Elle est fausse : le pH du mélange est celui de la base seule, soit 13, car la base est plus concentrée.
- C. Elle est fausse : le pH du mélange est de 7, car les volumes sont égaux.
- D. Elle est fausse : le pH n'est pas additif ; la base est en large excès et le pH vaut environ 12,65.

**Réponse correcte** : D

**Feedback correct**
Le pH est un logarithme : on ne peut pas faire la moyenne de deux pH. Pour un volume $V$ de chaque solution : $n(\ce{OH-}) = 0{,}10V$ et $n(\ce{H3O+}) = 0{,}010V$. L'excès, $0{,}090V$, est dilué dans $2V$ : $[\ce{OH-}] = 0{,}045$ mol/L, d'où $\text{pH} \approx 12{,}65$.

**Feedback incorrect**
- Si A : Le pH du mélange est bien compris entre les deux, mais la valeur n'est pas la moyenne : elle dépend des quantités de matière, pas des valeurs de pH.
- Si B : Le pH de la base seule (13) ne se maintient pas : l'acide consomme une partie des ions $\ce{OH-}$ et le volume total double.
- Si C : Des volumes égaux ne suffisent pas : l'acide (0,010 mol/L) et la base (0,10 mol/L) ne sont pas à la même concentration.
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-melanges-forts

---

---
id: q-melange-acide-base-forts-symbo-eva-002
concept: melange-acide-base-forts
sous-partie: 13A
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: melange-forts--ph-moyenne-des-ph
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève mélange 100 mL d'une solution d'acide fort de pH 1 et 300 mL d'une solution de base forte de pH 13. Il calcule la moyenne des pH pondérée par les volumes : $(1 \times 100 + 13 \times 300)/400 = 10$. Que pensez-vous de cette méthode ?

**Options**
- A. Elle est correcte : la pondération par les volumes tient compte de la quantité de chaque solution et donne donc une valeur réaliste.
- B. Elle est fausse : il faut comparer les quantités de matière ; l'excès de $\ce{OH-}$ donne un pH de 12,70.
- C. Elle est fausse : le pH est celui de la base seule, soit 13, puisqu'elle est en excès.
- D. Elle est fausse : le pH est de 7, car un acide fort et une base forte se neutralisent toujours.

**Réponse correcte** : B

**Feedback correct**
On ne peut pas moyenner des pH. $n(\ce{H3O+})$ vaut 10 mmol (0,10 mol/L dans 100 mL) et $n(\ce{OH-})$ vaut 30 mmol (0,10 mol/L dans 300 mL) : l'excès de 20 mmol de $\ce{OH-}$ est dilué dans 400 mL, d'où $[\ce{OH-}] = 0{,}050$ mol/L, $\text{pOH} = 1{,}30$ et $\text{pH} = 12{,}70$.

**Feedback incorrect**
- Si A : La pondération par les volumes ne corrige pas l'erreur de fond : le pH est une échelle logarithmique, on ne le moyenne pas ; le calcul se fait sur les quantités de matière.
- Si B : C'est une bonne réponse.
- Si C : L'acide consomme 10 mmol de $\ce{OH-}$ et le volume total est de 400 mL : la concentration en $\ce{OH-}$ n'est plus de 0,10 mol/L.
- Si D : La neutralisation n'est totale que si les quantités de matière sont égales ; ici la base est en excès.

**Référence manuel** : acides-bases-ph-melanges-forts

---

---
id: q-ph-acide-base-faible-macro-com-001
concept: ph-acide-base-faible
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
misconception: ph-faible--ph-mesure-la-force
date_validation: 2026-11-10
statut: validated
---

**Question**
On compare une solution d'acide chlorhydrique à 0,0010 mol/L (pH 3,00) et une solution d'acide éthanoïque à 0,10 mol/L (pH 2,88). Que peut-on en conclure ?

**Options**
- A. L'acide éthanoïque est le plus fort des deux acides, puisque sa solution a le pH le plus bas.
- B. L'acide chlorhydrique est un acide faible, puisque le pH de sa solution est plus élevé.
- C. Les deux acides ont la même force, puisque leurs pH sont presque identiques.
- D. L'acide chlorhydrique reste le plus fort ; le pH plus bas de l'autre solution vient de sa concentration, cent fois plus grande.

**Réponse correcte** : D

**Feedback correct**
Le pH dépend à la fois de la force de l'acide et de sa concentration. L'acide chlorhydrique est entièrement dissocié ; l'acide éthanoïque ne l'est que partiellement, mais sa solution est 100 fois plus concentrée, ce qui compense l'écart.

**Feedback incorrect**
- Si A : Le pH ne mesure pas la force d'un acide : il dépend aussi de la concentration. Ici, l'acide éthanoïque est plus concentré, c'est ce qui abaisse son pH.
- Si B : Un acide fort dilué peut avoir un pH plus élevé qu'un acide faible concentré. La force se lit sur la dissociation (ou le p$K_a$), pas sur le pH seul.
- Si C : Des pH voisins ne signifient pas des forces voisines : les concentrations diffèrent d'un facteur 100.
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-ph-faibles

---

---
id: q-ph-acide-base-faible-macro-app-001
concept: ph-acide-base-faible
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: app
misconception: ph-faible--ph-egal-ou-inferieur-au-fort
date_validation: 2026-11-10
statut: validated
---

**Question**
On prépare deux solutions de même concentration, 0,10 mol/L : l'une d'acide chlorhydrique, l'autre d'acide éthanoïque. Laquelle a le pH le plus élevé ?

**Options**
- A. Les deux ont le même pH, puisque leurs concentrations sont égales.
- B. L'acide chlorhydrique, puisqu'un acide fort libère davantage d'ions $\ce{H3O+}$ que l'acide éthanoïque.
- C. L'acide éthanoïque (pH d'environ 2,9 contre 1,0 pour l'acide chlorhydrique), puisqu'il est partiellement dissocié.
- D. On ne peut pas le prévoir sans connaître le volume de chaque solution.

**Réponse correcte** : C

**Feedback correct**
L'acide chlorhydrique est entièrement dissocié ($[\ce{H3O+}] = 0{,}10$ mol/L, pH 1,0) ; l'acide éthanoïque ne l'est que pour environ 1 % de ses molécules ($[\ce{H3O+}] \approx 1{,}3 \times 10^{-3}$ mol/L, pH 2,9). À concentration égale, l'acide faible donne le pH le plus élevé.

**Feedback incorrect**
- Si A : À même concentration, les pH diffèrent si les acides n'ont pas la même force : l'acide chlorhydrique se dissocie en totalité, l'acide éthanoïque très peu.
- Si B : L'acide chlorhydrique libère bien le plus d'ions $\ce{H3O+}$, mais c'est précisément ce qui donne le pH le plus bas, pas le plus élevé.
- Si C : C'est une bonne réponse.
- Si D : Le pH ne dépend que de la concentration et de la force de l'acide, pas du volume de solution.

**Référence manuel** : acides-bases-ph-ph-faibles

---

---
id: q-ph-acide-base-faible-parti-com-001
concept: ph-acide-base-faible
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: parti
type: com
date_validation: 2026-11-10
statut: validated
---

**Question**
Au niveau particulaire, comment peut-on décrire une solution d'acide éthanoïque à 0,10 mol/L ?

**Options**
- A. Presque toutes les molécules sont dissociées en ions $\ce{CH3COO-}$ et $\ce{H3O+}$.
- B. Aucune molécule n'est dissociée : tous les ions $\ce{H3O+}$ proviennent de l'eau.
- C. La moitié des molécules sont dissociées et l'autre moitié sont intactes.
- D. La grande majorité des molécules restent intactes ; environ 1 % sont dissociées en ions.

**Réponse correcte** : D

**Feedback correct**
L'acide éthanoïque est un acide faible : son équilibre de dissociation est fortement déplacé vers les molécules $\ce{CH3COOH}$. À 0,10 mol/L, environ 1 % des molécules seulement sont dissociées.

**Feedback incorrect**
- Si A : Cette description est celle d'un acide fort. Pour un acide faible, la dissociation est très partielle.
- Si B : Les ions $\ce{H3O+}$ de l'eau pure ($10^{-7}$ mol/L) sont négligeables devant ceux de l'acide ($1{,}3 \times 10^{-3}$ mol/L) : une partie des molécules est bien dissociée.
- Si C : Une dissociation à moitié correspond à un $K_a$ proche de la concentration, ce qui n'est pas le cas ici ($K_a = 1{,}78 \times 10^{-5}$).
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-ph-faibles

---

---
id: q-ph-acide-base-faible-symbo-app-001
concept: ph-acide-base-faible
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le pH d'une solution d'acide éthanoïque à 0,050 mol/L, sachant que p$K_a = 4{,}75$ (la dissociation est faible).

**Options**
- A. 1,30
- B. 3,03
- C. 4,75
- D. 6,05

**Réponse correcte** : B

**Feedback correct**
Pour un acide faible, $\text{pH} \approx \frac{1}{2}(\text{p}K_a - \log c_0) = \frac{1}{2}(4{,}75 + 1{,}30) = 3{,}03$.

**Feedback incorrect**
- Si A : 1,30 serait le pH d'un acide fort de même concentration ($-\log c_0$), ce qui suppose une dissociation totale.
- Si B : C'est une bonne réponse.
- Si C : Le pH est égal au p$K_a$ seulement lorsque $[\ce{HA}] = [\ce{A-}]$, ce qui n'est pas le cas dans une solution d'acide faible seul.
- Si D : Il manque le facteur $\frac{1}{2}$ : la formule est $\frac{1}{2}(\text{p}K_a - \log c_0)$, pas $\text{p}K_a - \log c_0$.

**Référence manuel** : acides-bases-ph-ph-faibles

---

---
id: q-ph-acide-base-faible-symbo-app-002
concept: ph-acide-base-faible
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le pH d'une solution d'ammoniac $\ce{NH3}$ à 0,10 mol/L, sachant que p$K_a(\ce{NH4+/NH3}) = 9{,}22$ (la protonation est faible).

**Options**
- A. 13,00
- B. 11,11
- C. 9,22
- D. 2,89

**Réponse correcte** : B

**Feedback correct**
Pour une base faible, $\text{pH} \approx 7 + \frac{1}{2}(\text{p}K_a + \log c_0) = 7 + \frac{1}{2}(9{,}22 - 1{,}00) = 11{,}11$.

**Feedback incorrect**
- Si A : 13,00 serait le pH d'une base forte de même concentration, qui libérerait 0,10 mol/L d'ions $\ce{OH-}$.
- Si B : C'est une bonne réponse.
- Si C : Le pH égale le p$K_a$ seulement lorsque $[\ce{NH3}] = [\ce{NH4+}]$, ce qui n'est pas le cas dans une solution d'ammoniac seul.
- Si D : 2,89 est le pOH complémentaire à 14 ; une base donne un pH supérieur à 7.

**Référence manuel** : acides-bases-ph-ph-faibles

---

---
id: q-ph-acide-base-faible-symbo-ana-001
concept: ph-acide-base-faible
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: ph-faible--approximation-sans-verification
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève calcule le pH d'une solution d'acide fluorhydrique à 0,010 mol/L (p$K_a = 3{,}17$) avec la formule $\text{pH} = \frac{1}{2}(\text{p}K_a - \log c_0)$ et obtient 2,59. Pourquoi ce résultat est-il peu fiable ?

**Options**
- A. Parce que la formule n'est valable que pour les acides organiques.
- B. Parce que $\alpha$ dépasse 5 % : la résolution complète donne 2,64.
- C. Parce que le p$K_a$ de $\ce{HF}$ est trop petit pour qu'on puisse calculer un pH.
- D. Parce qu'il fallait utiliser $\text{pH} = -\log c_0$, $\ce{HF}$ étant un acide fort.

**Réponse correcte** : B

**Feedback correct**
La formule approchée suppose $[\ce{HA}] \approx c_0$, donc un coefficient de dissociation inférieur à 5 %. Ici $\alpha$ dépasse 20 % ($\sqrt{K_a/c_0} \approx 26\ \%$ par la formule approchée, 23 % en réalité) : il faut résoudre $K_a = x^2/(c_0 - x)$, ce qui donne $x = 2{,}3 \times 10^{-3}$ mol/L et un pH de 2,64.

**Feedback incorrect**
- Si A : La formule s'applique à tout acide faible ; ce qui compte, c'est la valeur de $\alpha$, pas la nature organique ou minérale de l'acide.
- Si B : C'est une bonne réponse.
- Si C : Un p$K_a$ de 3,17 est tout à fait courant. Il est assez petit pour que la dissociation ne soit plus négligeable à 0,010 mol/L, c'est tout.
- Si D : L'acide fluorhydrique n'est pas un acide fort : son $K_a$ est de $6{,}8 \times 10^{-4}$ ; il est seulement assez dissocié ici pour que l'approximation échoue.

**Référence manuel** : acides-bases-ph-ph-faibles

---

---
id: q-ph-acide-base-faible-symbo-eva-001
concept: ph-acide-base-faible
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: ph-faible--dilution-dix-ph-plus-un
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Si je dilue 10 fois une solution d'acide éthanoïque, son pH augmente de 1 unité, comme pour un acide fort. » (On suppose que l'approximation de l'acide faible reste valable.) Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte : diluer 10 fois divise $[\ce{H3O+}]$ par 10.
- B. Elle est fausse : le pH augmente d'environ 0,5 unité seulement.
- C. Elle est fausse : le pH diminue, car l'acide devient plus dissocié.
- D. Elle est fausse : le pH ne change pas, car $K_a$ est constante.

**Réponse correcte** : B

**Feedback correct**
Pour un acide faible, $[\ce{H3O+}] \approx \sqrt{K_a c_0}$ : diluer d'un facteur 10 divise $[\ce{H3O+}]$ par $\sqrt{10} \approx 3{,}2$, soit une augmentation du pH d'environ 0,5 unité. Pour un acide fort, $[\ce{H3O+}] = c_0$ et le pH gagne bien 1 unité.

**Feedback incorrect**
- Si A : C'est vrai pour un acide fort. Pour un acide faible, la dissociation augmente avec la dilution et limite la baisse de $[\ce{H3O+}]$.
- Si B : C'est une bonne réponse.
- Si C : Même si le coefficient de dissociation augmente, le nombre d'ions $\ce{H3O+}$ par litre diminue : le pH augmente.
- Si D : $K_a$ est constante, mais $[\ce{H3O+}] = \sqrt{K_a c_0}$ dépend de $c_0$ : le pH varie bien avec la dilution.

**Référence manuel** : acides-bases-ph-ph-faibles

---

---
id: q-coefficient-dissociation-parti-com-001
concept: coefficient-dissociation
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: parti
type: com
misconception: dissociation--dilution-diminue-le-taux
date_validation: 2026-11-10
statut: validated
---

**Question**
On dilue 10 fois une solution d'acide éthanoïque. Au niveau particulaire, que devient la proportion de molécules dissociées en ions ?

**Options**
- A. Elle diminue, car il y a moins de molécules par litre.
- B. Elle ne change pas, car $K_a$ est constante.
- C. Elle augmente, même si le nombre d'ions par litre diminue.
- D. Elle devient égale à 100 % dès que la solution est diluée 10 fois.

**Réponse correcte** : C

**Feedback correct**
En diluant, l'équilibre se déplace dans le sens qui produit davantage de particules ($\ce{HA + H2O <=> A- + H3O+}$) : la proportion de molécules dissociées augmente, bien que la concentration en ions diminue.

**Feedback incorrect**
- Si A : Moins de molécules par litre ne signifie pas une proportion plus faible : l'équilibre se réajuste et la proportion dissociée augmente.
- Si B : Seul le quotient $K_a$ est constant ; la proportion de molécules dissociées $\alpha$ varie avec la concentration.
- Si C : C'est une bonne réponse.
- Si D : La dissociation n'est jamais totale pour un acide faible, même après une forte dilution : elle s'en approche seulement.

**Référence manuel** : acides-bases-ph-dissociation

---

---
id: q-coefficient-dissociation-symbo-sou-001
concept: coefficient-dissociation
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Comment définit-on le coefficient de dissociation $\alpha$ d'un acide $\ce{HA}$ de concentration initiale $c_0$ ?

**Options**
- A. $\alpha = K_a/c_0$
- B. $\alpha = [\ce{HA}]/c_0$ à l'équilibre
- C. $\alpha = [\ce{A-}]/c_0$ à l'équilibre
- D. $\alpha = [\ce{A-}][\ce{H3O+}]/[\ce{HA}]$

**Réponse correcte** : C

**Feedback correct**
$\alpha$ est la proportion de molécules dissociées à l'équilibre : $\alpha = [\ce{A-}]/c_0$ (compris entre 0 et 1, souvent donné en pourcent).

**Feedback incorrect**
- Si A : $K_a/c_0$ n'est qu'une approximation de $\alpha^2$ pour un acide faible, pas sa définition.
- Si B : C'est la proportion de molécules non dissociées, soit $1 - \alpha$.
- Si C : C'est une bonne réponse.
- Si D : C'est l'expression de $K_a$, constante d'équilibre, et non du coefficient de dissociation.

**Référence manuel** : acides-bases-ph-dissociation

---

---
id: q-coefficient-dissociation-symbo-com-001
concept: coefficient-dissociation
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-10
statut: validated
---

**Question**
Deux acides faibles sont dissous à la même concentration, 0,10 mol/L. Le coefficient de dissociation vaut 0,5 % pour le premier et 5 % pour le second. Que peut-on en conclure ?

**Options**
- A. Le second acide a un $K_a$ plus grand ; il est le plus fort des deux.
- B. Les deux acides ont le même $K_a$, puisque leurs concentrations sont égales.
- C. Le premier acide est le plus fort, puisque son coefficient de dissociation est le plus petit.
- D. Les deux acides ont le même $K_a$ ; seule la température explique l'écart de $\alpha$.

**Réponse correcte** : A

**Feedback correct**
À concentration égale, un coefficient de dissociation plus grand traduit un acide plus dissocié, donc un $K_a$ plus grand : ici $K_a \approx \alpha^2 c_0$, soit environ 100 fois plus grand pour le second acide. $\alpha$ dépend de $c_0$ et de $K_a$ ; $K_a$ ne dépend que de la température.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : À même concentration, des $\alpha$ différents signifient des $K_a$ différents : $K_a \approx \alpha^2 c_0$.
- Si C : Un coefficient plus petit indique un acide moins dissocié, donc plus faible.
- Si D : Dans cette comparaison la température est la même pour les deux solutions : l'écart de $\alpha$ traduit une différence de $K_a$.

**Référence manuel** : acides-bases-ph-dissociation

---

---
id: q-coefficient-dissociation-symbo-app-001
concept: coefficient-dissociation
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Une solution d'acide éthanoïque à 0,10 mol/L a un pH de 2,88. Quel est son coefficient de dissociation ?

**Options**
- A. 0,13 %
- B. 1,3 %
- C. 2,9 %
- D. 13 %

**Réponse correcte** : B

**Feedback correct**
$[\ce{H3O+}] = 10^{-2{,}88} = 1{,}3 \times 10^{-3}$ mol/L, égale à $[\ce{A-}]$. Donc $\alpha = 1{,}3 \times 10^{-3}/0{,}10 = 1{,}3\ \%$.

**Feedback incorrect**
- Si A : Il y a une erreur d'un facteur 10 : $1{,}3 \times 10^{-3}/0{,}10 = 0{,}013$, soit 1,3 %.
- Si B : C'est une bonne réponse.
- Si C : 2,88 est la valeur du pH, pas un pourcentage de dissociation.
- Si D : Il y a une erreur d'un facteur 10 dans l'autre sens : $0{,}013$ correspond à 1,3 %, pas à 13 %.

**Référence manuel** : acides-bases-ph-dissociation

---

---
id: q-coefficient-dissociation-symbo-app-002
concept: coefficient-dissociation
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le coefficient de dissociation d'une solution d'acide méthanoïque (formique) à 0,50 mol/L, sachant que $K_a = 1{,}78 \times 10^{-4}$.

**Options**
- A. 0,036 %
- B. 1,9 %
- C. 19 %
- D. 3,6 %

**Réponse correcte** : B

**Feedback correct**
Pour un acide faible, $\alpha \approx \sqrt{K_a/c_0} = \sqrt{1{,}78 \times 10^{-4}/0{,}50} = 0{,}019$, soit 1,9 % (inférieur à 5 % : l'approximation est valable).

**Feedback incorrect**
- Si A : 0,036 % est le quotient $K_a/c_0$ ; il manque la racine carrée : $\alpha \approx \sqrt{K_a/c_0}$.
- Si B : C'est une bonne réponse.
- Si C : Il y a une erreur d'un facteur 10 : $\sqrt{3{,}56 \times 10^{-4}} = 0{,}019$, soit 1,9 %.
- Si D : 3,6 % ne correspond à aucune formule valable ; la racine carrée de $3{,}56 \times 10^{-4}$ vaut 0,019.

**Référence manuel** : acides-bases-ph-dissociation

---

---
id: q-coefficient-dissociation-symbo-ana-001
concept: coefficient-dissociation
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-10
statut: validated
---

**Question**
On dilue 100 fois une solution d'acide éthanoïque à 0,10 mol/L. Comment évoluent environ $\alpha$, $[\ce{H3O+}]$ et $K_a$ ?

**Options**
- A. $\alpha$ est multiplié par environ 10, $[\ce{H3O+}]$ est divisée par environ 10, et $K_a$ ne change pas.
- B. $\alpha$, $[\ce{H3O+}]$ et $K_a$ sont tous divisés par 100.
- C. $\alpha$ ne change pas, $[\ce{H3O+}]$ est divisée par 100, et $K_a$ ne change pas.
- D. $\alpha$ est multiplié par 10, $[\ce{H3O+}]$ ne change pas, et $K_a$ est multiplié par 10.

**Réponse correcte** : A

**Feedback correct**
$\alpha \approx \sqrt{K_a/c_0}$ augmente d'un facteur $\sqrt{100} = 10$ (en valeur approchée) tandis que $[\ce{H3O+}] \approx \sqrt{K_a c_0}$ diminue d'un facteur 10 ; $K_a$ ne dépend que de la température.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $K_a$ ne change pas avec la dilution, et $\alpha$ augmente au lieu de diminuer.
- Si C : Si $\alpha$ restait constant, $[\ce{H3O+}] = \alpha c_0$ serait divisée par 100 ; or $\alpha$ augmente et limite la baisse à un facteur 10 environ.
- Si D : $[\ce{H3O+}]$ diminue (la solution contient moins de matière par litre), et $K_a$ est constante.

**Référence manuel** : acides-bases-ph-dissociation

---

---
id: q-coefficient-dissociation-symbo-eva-001
concept: coefficient-dissociation
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: dissociation--faible-toujours-peu-dissocie
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Un acide faible est toujours très peu dissocié, quelle que soit sa concentration. » Vous testez cette affirmation avec l'acide éthanoïque ($K_a = 1{,}78 \times 10^{-5}$) à la concentration de $1{,}0 \times 10^{-4}$ mol/L. Que concluez-vous ?

**Options**
- A. L'affirmation est correcte : par définition, un acide faible est dissocié à moins de 5 %.
- B. L'affirmation est correcte, mais seulement pour les acides organiques comme l'acide éthanoïque.
- C. L'affirmation est fausse : à cette concentration, tout acide faible est dissocié à 100 %.
- D. L'affirmation est fausse : environ 34 % des molécules sont dissociées à cette concentration.

**Réponse correcte** : D

**Feedback correct**
« Faible » signifie $K_a$ petit, pas $\alpha$ petit. En résolvant $K_a = x^2/(c_0 - x)$ on trouve $x \approx 3{,}4 \times 10^{-5}$ mol/L, soit $\alpha \approx 34\ \%$ : à forte dilution, un acide faible peut être largement dissocié.

**Feedback incorrect**
- Si A : La définition d'un acide faible porte sur sa constante $K_a$, pas sur un seuil de dissociation. Le seuil de 5 % sert seulement à valider l'approximation de calcul.
- Si B : La dilution agit de la même façon sur tous les acides faibles, organiques ou non.
- Si C : Un acide faible n'est jamais dissocié à 100 % ; ici, $\alpha$ atteint environ 34 %.
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-dissociation

---

---
id: q-hydrolyse-sel-macro-com-001
concept: hydrolyse-sel
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
misconception: hydrolyse--tous-sels-neutres
date_validation: 2026-11-10
statut: validated
---

**Question**
On mesure le pH de trois solutions de sels à 0,10 mol/L : chlorure de sodium, éthanoate de sodium et chlorure d'ammonium. Quel résultat est attendu ?

**Options**
- A. Les trois solutions sont neutres (pH 7), puisque ce sont des sels.
- B. Le chlorure de sodium est neutre, l'éthanoate de sodium est acide et le chlorure d'ammonium est basique.
- C. Le chlorure de sodium est neutre, l'éthanoate de sodium est basique et le chlorure d'ammonium est acide.
- D. Les trois solutions sont acides, puisque la dissolution libère des ions dans l'eau.

**Réponse correcte** : C

**Feedback correct**
$\ce{NaCl}$ ne contient que des ions spectateurs (neutre) ; l'ion éthanoate, base faible, rend la solution basique (pH ≈ 8,9) ; l'ion ammonium, acide faible, rend la solution acide (pH ≈ 5,1).

**Feedback incorrect**
- Si A : Seul un sel dont les deux ions sont sans effet acido-basique (comme $\ce{NaCl}$) donne une solution neutre. Les autres ions réagissent avec l'eau.
- Si B : Les rôles sont inversés : l'ion éthanoate est une base (il capte un proton) et l'ion ammonium est un acide (il en cède un).
- Si C : C'est une bonne réponse.
- Si D : La dissolution d'un sel libère des ions, mais ce sont leurs propriétés acido-basiques qui déterminent le pH ; $\ce{Na+}$ et $\ce{Cl-}$ n'en ont aucune.

**Référence manuel** : acides-bases-ph-sels

---

---
id: q-hydrolyse-sel-parti-com-001
concept: hydrolyse-sel
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: parti
type: com
misconception: hydrolyse--hydrolyse-egal-dissolution
date_validation: 2026-11-10
statut: validated
---

**Question**
Au niveau particulaire, en quoi consiste l'hydrolyse de l'ion éthanoate $\ce{CH3COO-}$ dans l'eau ?

**Options**
- A. En la séparation de l'ion sodium et de l'ion éthanoate par les molécules d'eau, lors de la dissolution du sel.
- B. En un transfert de proton d'une molécule d'eau vers l'ion éthanoate, qui forme $\ce{CH3COOH}$ et $\ce{OH-}$.
- C. En un transfert de proton de l'ion éthanoate vers une molécule d'eau, qui forme $\ce{CH3COO^{2-}}$ et $\ce{H3O+}$.
- D. En la rupture d'une molécule d'eau en atomes d'hydrogène et d'oxygène au contact de l'ion.

**Réponse correcte** : B

**Feedback correct**
L'hydrolyse est la réaction acido-basique d'un ion avec l'eau : l'ion éthanoate, base faible, capte un proton d'une molécule d'eau selon $\ce{CH3COO- + H2O <=> CH3COOH + OH-}$. Les ions $\ce{OH-}$ formés rendent la solution basique.

**Feedback incorrect**
- Si A : C'est la dissolution du sel (dissociation ionique), qui précède l'hydrolyse. L'hydrolyse est la réaction ultérieure de l'ion avec l'eau.
- Si B : C'est une bonne réponse.
- Si C : L'ion éthanoate n'a plus de proton acide à céder (il n'existe pas d'ion $\ce{CH3COO^{2-}}$) ; il se comporte en base, pas en acide.
- Si D : Les molécules d'eau ne sont pas décomposées en atomes ; l'eau échange seulement un proton avec l'ion.

**Référence manuel** : acides-bases-ph-sels

---

---
id: q-hydrolyse-sel-symbo-sou-001
concept: hydrolyse-sel
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelle équation décrit l'hydrolyse de l'ion ammonium $\ce{NH4+}$ dans l'eau ?

**Options**
- A. $\ce{NH4+ + H2O <=> NH3 + H3O+}$
- B. $\ce{NH4+ + H2O <=> NH3 + OH-}$
- C. $\ce{NH4+ + OH- -> NH3 + H2O}$
- D. $\ce{NH4Cl -> NH4+ + Cl-}$

**Réponse correcte** : A

**Feedback correct**
L'ion ammonium est l'acide du couple $\ce{NH4+/NH3}$ : il cède un proton à l'eau, ce qui forme $\ce{NH3}$ et $\ce{H3O+}$ et rend la solution acide.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Cette équation n'est pas équilibrée en charge (+1 à gauche, $-1$ à droite) ; l'ion ammonium cède un proton, il n'en capte pas.
- Si C : C'est la réaction de l'ion ammonium avec une base forte ajoutée, pas une hydrolyse dans l'eau pure.
- Si D : C'est la dissolution du sel, pas l'hydrolyse de l'ion.

**Référence manuel** : acides-bases-ph-sels

---

---
id: q-hydrolyse-sel-symbo-app-001
concept: hydrolyse-sel
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le pH d'une solution d'éthanoate de sodium à 0,10 mol/L, sachant que p$K_a(\ce{CH3COOH/CH3COO-}) = 4{,}75$.

**Options**
- A. 2,88
- B. 8,88
- C. 7,00
- D. 9,25

**Réponse correcte** : B

**Feedback correct**
L'ion éthanoate est une base faible : $\text{pH} \approx 7 + \frac{1}{2}(\text{p}K_a + \log c_0) = 7 + \frac{1}{2}(4{,}75 - 1{,}00) = 8{,}88$.

**Feedback incorrect**
- Si A : 2,88 serait le pH d'une solution d'acide éthanoïque de même concentration. L'ion éthanoate est la base conjuguée, pas l'acide.
- Si B : C'est une bonne réponse.
- Si C : Un sel dérivé d'un acide faible et d'une base forte n'est pas neutre : l'anion s'hydrolyse et produit des ions $\ce{OH-}$.
- Si D : 9,25 est le p$K_b$ de l'ion éthanoate, pas le pH de sa solution.

**Référence manuel** : acides-bases-ph-sels

---

---
id: q-hydrolyse-sel-symbo-app-002
concept: hydrolyse-sel
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le pH d'une solution de chlorure d'ammonium à 0,10 mol/L, sachant que p$K_a(\ce{NH4+/NH3}) = 9{,}22$.

**Options**
- A. 1,00
- B. 5,11
- C. 8,89
- D. 9,22

**Réponse correcte** : B

**Feedback correct**
L'ion ammonium est un acide faible : $\text{pH} \approx \frac{1}{2}(\text{p}K_a - \log c_0) = \frac{1}{2}(9{,}22 + 1{,}00) = 5{,}11$. L'ion chlorure est spectateur.

**Feedback incorrect**
- Si A : 1,00 serait le pH d'un acide fort à 0,10 mol/L ; l'ion ammonium est un acide faible, très peu dissocié.
- Si B : C'est une bonne réponse.
- Si C : 8,89 s'obtiendrait avec la formule des bases ($14 - 5{,}11$) ; or l'ion ammonium est un acide, la solution est acide.
- Si D : Le pH égale le p$K_a$ seulement si l'acide et sa base conjuguée sont en quantités égales, ce qui n'est pas le cas ici.

**Référence manuel** : acides-bases-ph-sels

---

---
id: q-hydrolyse-sel-symbo-ana-001
concept: hydrolyse-sel
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: hydrolyse--ion-spectateur-ou-kh-mal-relie
date_validation: 2026-11-10
statut: validated
---

**Question**
Dans une solution de chlorure d'ammonium $\ce{NH4Cl}$, quel(s) ion(s) s'hydrolyse(nt) de façon notable, et pourquoi ?

**Options**
- A. Les deux ions, car tout ion issu d'un sel réagit avec l'eau.
- B. L'ion chlorure seulement, car il forme de l'acide chlorhydrique $\ce{HCl}$ avec l'eau.
- C. Aucun ion, car un sel dissous donne toujours une solution neutre.
- D. L'ion ammonium seulement ; l'ion chlorure est la base conjuguée d'un acide fort.

**Réponse correcte** : D

**Feedback correct**
$\ce{Cl-}$ est la base conjuguée de $\ce{HCl}$, acide fort : sa basicité est négligeable ($K_b \approx 10^{-21}$). Seul $\ce{NH4+}$, acide faible de p$K_a$ 9,22, réagit avec l'eau et acidifie la solution.

**Feedback incorrect**
- Si A : Un ion ne s'hydrolyse que s'il est un acide ou une base faible dans l'eau ; les ions $\ce{Na+}$, $\ce{Cl-}$, $\ce{K+}$, $\ce{NO3-}$ sont spectateurs.
- Si B : L'acide chlorhydrique est un acide fort, entièrement dissocié ; l'ion chlorure ne capte pas de proton de l'eau.
- Si C : Un sel dissous ne donne une solution neutre que si ses deux ions sont spectateurs, ce qui n'est pas le cas du chlorure d'ammonium.
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-sels

---

---
id: q-hydrolyse-sel-symbo-eva-001
concept: hydrolyse-sel
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: hydrolyse--sel-ne-peut-etre-acide-ou-basique
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « L'éthanoate de sodium est un sel, pas une base. Sa solution ne peut donc pas être basique. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte : les sels et les bases sont deux familles distinctes de composés.
- B. Elle est fausse : l'ion éthanoate est une base faible ; le pH est d'environ 8,9.
- C. Elle est fausse : c'est l'ion sodium qui est une base et qui rend la solution basique.
- D. Elle est correcte : on appelle « sel » un composé dont la solution est toujours neutre.

**Réponse correcte** : B

**Feedback correct**
« Sel » décrit la nature ionique du composé, pas son comportement acido-basique. L'ion éthanoate est la base conjuguée d'un acide faible : il capte un proton de l'eau, ce qui produit des ions $\ce{OH-}$ et un pH d'environ 8,9 à 0,10 mol/L.

**Feedback incorrect**
- Si A : Les familles ne s'excluent pas : un composé ionique peut contenir un ion qui est un acide ou une base au sens de Brønsted.
- Si B : C'est une bonne réponse.
- Si C : L'ion sodium est spectateur : c'est l'ion éthanoate qui est la base.
- Si D : Un sel donne une solution neutre uniquement si ses deux ions sont spectateurs ; beaucoup de sels donnent des solutions acides ou basiques.

**Référence manuel** : acides-bases-ph-sels

---

---
id: q-courbe-titrage-macro-sou-001
concept: courbe-titrage
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelle condition caractérise le point d'équivalence d'un titrage acido-basique ?

**Options**
- A. Le pH de la solution vaut 7.
- B. L'indicateur coloré change de teinte.
- C. Les réactifs sont dans les proportions stœchiométriques de la réaction.
- D. Le volume de solution titrante versé est égal au volume de solution titrée.

**Réponse correcte** : C

**Feedback correct**
À l'équivalence, la quantité de réactif titrant introduite est exactement celle qui réagit avec la quantité de réactif titré, selon les coefficients de l'équation de titrage : il ne reste ni l'un ni l'autre en excès.

**Feedback incorrect**
- Si A : Le pH à l'équivalence dépend de la force des espèces ; il n'est de 7 que pour un acide fort titré par une base forte.
- Si B : Le virage de l'indicateur est un signal observé, qui ne coïncide que de manière approchée avec l'équivalence.
- Si C : C'est une bonne réponse.
- Si D : Les volumes sont égaux seulement si les concentrations des deux solutions et les coefficients stœchiométriques le sont aussi.

**Référence manuel** : acides-bases-ph-courbes-titrage

---

---
id: q-courbe-titrage-macro-com-001
concept: courbe-titrage
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
misconception: titrage--equivalence-egal-ph-7
date_validation: 2026-11-10
statut: validated
---

**Question**
On titre une solution d'acide éthanoïque par de la soude. Que peut-on dire du pH au point d'équivalence ?

**Options**
- A. Il vaut 7, car l'acide et la base ont réagi entièrement.
- B. Il est supérieur à 7 (de l'ordre de 8 à 9) : la solution contient la base $\ce{CH3COO-}$.
- C. Il est inférieur à 7, car il reste de l'acide éthanoïque non neutralisé.
- D. Il est d'environ 13, car la soude est une base forte.

**Réponse correcte** : B

**Feedback correct**
À l'équivalence, tout l'acide a été transformé en ion éthanoate, base faible qui s'hydrolyse : $\ce{CH3COO- + H2O <=> CH3COOH + OH-}$. Le pH est supérieur à 7.

**Feedback incorrect**
- Si A : Le pH vaut 7 à l'équivalence seulement quand les espèces formées sont sans effet acido-basique, c'est-à-dire pour un acide fort titré par une base forte.
- Si B : C'est une bonne réponse.
- Si C : À l'équivalence, il ne reste plus d'acide éthanoïque (en dehors de celui formé par l'hydrolyse, en quantité infime).
- Si D : La soude est en quantité juste suffisante à l'équivalence, pas en excès ; elle n'impose pas son pH.

**Référence manuel** : acides-bases-ph-courbes-titrage

---

---
id: q-courbe-titrage-symbo-app-001
concept: courbe-titrage
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
On titre 25,0 mL d'une solution d'acide éthanoïque à 0,100 mol/L par de la soude à 0,100 mol/L. Quel est le volume de soude versé à l'équivalence, et quel est le pH à la demi-équivalence ? (p$K_a = 4{,}75$)

**Options**
- A. 12,5 mL ; 4,75
- B. 25,0 mL ; 7,00
- C. 25,0 mL ; 4,75
- D. 50,0 mL ; 2,88

**Réponse correcte** : C

**Feedback correct**
La réaction de titrage est $\ce{CH3COOH + OH- -> CH3COO- + H2O}$, avec des coefficients 1:1 : $V_{\text{éq}} = 0{,}100 \times 25{,}0/0{,}100 = 25{,}0$ mL. À la demi-équivalence (12,5 mL), la moitié de l'acide est devenue sa base conjuguée, $[\ce{HA}] = [\ce{A-}]$ et $\text{pH} = \text{p}K_a = 4{,}75$.

**Feedback incorrect**
- Si A : 12,5 mL est le volume de la demi-équivalence, pas celui de l'équivalence.
- Si B : 7,00 n'est pas le pH de la demi-équivalence : il vaut p$K_a$. Pour un acide faible titré par une base forte, le pH à l'équivalence (environ 8,7) est lui aussi supérieur à 7.
- Si C : C'est une bonne réponse.
- Si D : Les concentrations des deux solutions étant égales et les coefficients 1:1, le volume de soude à l'équivalence est égal au volume d'acide, pas à son double.

**Référence manuel** : acides-bases-ph-courbes-titrage

---

---
id: q-courbe-titrage-symbo-app-002
concept: courbe-titrage
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
On titre 20,0 mL d'une solution d'ammoniac à 0,100 mol/L par de l'acide chlorhydrique à 0,0500 mol/L. Quel est le volume d'acide versé à l'équivalence, et quel est le pH à la demi-équivalence ? (p$K_a(\ce{NH4+/NH3}) = 9{,}22$)

**Options**
- A. 20,0 mL ; 9,22
- B. 40,0 mL ; 4,78
- C. 40,0 mL ; 9,22
- D. 40,0 mL ; 7,00

**Réponse correcte** : C

**Feedback correct**
La réaction de titrage $\ce{NH3 + H3O+ -> NH4+ + H2O}$ est 1:1 : $V_{\text{éq}} = 0{,}100 \times 20{,}0/0{,}0500 = 40{,}0$ mL. À la demi-équivalence (20,0 mL), $[\ce{NH3}] = [\ce{NH4+}]$ et $\text{pH} = \text{p}K_a = 9{,}22$.

**Feedback incorrect**
- Si A : 20,0 mL est le volume de la demi-équivalence : l'acide chlorhydrique est deux fois moins concentré que l'ammoniac, il en faut deux fois plus pour atteindre l'équivalence.
- Si B : 4,78 est le p$K_b$ ; le pH à la demi-équivalence est égal au p$K_a$ du couple.
- Si C : C'est une bonne réponse.
- Si D : Le pH à la demi-équivalence est égal au p$K_a$, pas à 7 ; ce dernier ne serait atteint que pour un couple de p$K_a$ égal à 7.

**Référence manuel** : acides-bases-ph-courbes-titrage

---

---
id: q-courbe-titrage-symbo-ana-001
concept: courbe-titrage
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-10
statut: validated
---

**Question**
Lors du titrage de 25,0 mL d'un acide par une solution de soude à 0,100 mol/L, on relève les valeurs suivantes : $V = 0$ mL, pH = 2,9 ; $V = 12{,}5$ mL, pH = 4,8 ; $V = 25{,}0$ mL, pH = 8,7 (saut de pH) ; $V = 37{,}5$ mL, pH = 12,3. De quel type de titrage s'agit-il, et que vaut le p$K_a$ du couple ?

**Options**
- A. Acide fort par base forte ; p$K_a = 2{,}9$.
- B. Acide faible par base forte ; p$K_a \approx 8{,}7$, lu au point d'équivalence.
- C. Acide faible par base forte ; p$K_a \approx 4{,}8$, lu à la demi-équivalence (12,5 mL).
- D. Base faible par acide fort ; p$K_a \approx 4{,}8$.

**Réponse correcte** : C

**Feedback correct**
Le pH initial (2,9) est supérieur à 1 et le pH à l'équivalence est supérieur à 7 : l'acide est faible. Le volume équivalent est de 25,0 mL (milieu du saut), donc la demi-équivalence est à 12,5 mL, où $\text{pH} = \text{p}K_a \approx 4{,}8$.

**Feedback incorrect**
- Si A : Pour un acide fort à cette concentration, le pH initial serait voisin de 1 et le pH à l'équivalence valdrait 7. Le pH initial n'est pas un p$K_a$.
- Si B : Le pH à l'équivalence n'est pas le p$K_a$ : c'est à la demi-équivalence que $\text{pH} = \text{p}K_a$.
- Si C : C'est une bonne réponse.
- Si D : Le pH augmente avec le volume de soude versée : on titre un acide par une base, pas une base par un acide.

**Référence manuel** : acides-bases-ph-courbes-titrage

---

---
id: q-courbe-titrage-symbo-ana-002
concept: courbe-titrage
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-10
statut: validated
---

**Question**
Lors du titrage de 20,0 mL d'une base par de l'acide chlorhydrique à 0,0500 mol/L, on relève les valeurs suivantes : $V = 0$ mL, pH = 11,1 ; $V = 20{,}0$ mL, pH = 9,2 ; $V = 40{,}0$ mL, pH = 5,3 (saut de pH) ; $V = 60{,}0$ mL, pH = 1,9. De quel type de titrage s'agit-il, et que vaut le p$K_a$ du couple ?

**Options**
- A. Base faible par acide fort ; p$K_a \approx 9{,}2$, lu à la demi-équivalence (20,0 mL).
- B. Base forte par acide fort ; p$K_a \approx 5{,}3$.
- C. Acide faible par base forte ; p$K_a \approx 9{,}2$.
- D. Base faible par acide fort ; p$K_a \approx 11{,}1$, lu au pH initial.

**Réponse correcte** : A

**Feedback correct**
Le pH diminue quand on verse l'acide : on titre une base. Le pH à l'équivalence (5,3) est inférieur à 7 : la base est faible. Le volume équivalent est de 40,0 mL (milieu du saut), donc la demi-équivalence est à 20,0 mL, où $\text{pH} = \text{p}K_a \approx 9{,}2$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Pour une base forte, le pH initial serait voisin de 13 et le pH à l'équivalence vaudrait 7.
- Si C : Le pH diminue quand on verse le titrant : la solution titrée est une base, pas un acide.
- Si D : Le pH initial dépend de la concentration de la base, pas du p$K_a$ seul ; c'est à la demi-équivalence que $\text{pH} = \text{p}K_a$.

**Référence manuel** : acides-bases-ph-courbes-titrage

---

---
id: q-courbe-titrage-symbo-eva-001
concept: courbe-titrage
sous-partie: 13B
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: titrage--demi-equivalence-egal-ph-7
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Au point de demi-équivalence du titrage de l'acide éthanoïque par la soude, le pH vaut 7, puisque la moitié de l'acide est neutralisée. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte : à moitié neutralisée, la solution est neutre.
- B. Elle est fausse : le pH vaut alors 8,72, valeur du point d'équivalence.
- C. Elle est fausse : à la demi-équivalence, le pH vaut le p$K_a$, soit 4,75.
- D. Elle est fausse : le pH vaut 2,88, le pH de la solution d'acide de départ.

**Réponse correcte** : C

**Feedback correct**
À la demi-équivalence, la moitié de l'acide a été transformée en sa base conjuguée : $[\ce{CH3COOH}] = [\ce{CH3COO-}]$, donc $\text{pH} = \text{p}K_a + \log 1 = \text{p}K_a = 4{,}75$. La solution est un tampon, pas une solution neutre.

**Feedback incorrect**
- Si A : Moitié neutralisée ne signifie pas pH neutre : les deux espèces conjuguées coexistent en quantités égales, ce qui fixe $\text{pH} = \text{p}K_a$.
- Si B : 8,72 est le pH du point d'équivalence (solution d'éthanoate), pas celui de la demi-équivalence.
- Si C : C'est une bonne réponse.
- Si D : 2,88 est le pH de la solution d'acide avant toute addition de soude.

**Référence manuel** : acides-bases-ph-courbes-titrage

---

---
id: q-solution-tampon-macro-com-001
concept: solution-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelle observation expérimentale caractérise une solution tampon ?

**Options**
- A. Son pH reste voisin de la même valeur quand on lui ajoute de petites quantités d'acide fort ou de base forte.
- B. Son pH vaut toujours 7, quelle que soit la composition de la solution.
- C. Son pH reste rigoureusement constant quelle que soit la quantité d'acide ou de base forte ajoutée.
- D. Elle ne réagit ni avec les acides forts ni avec les bases fortes, qui restent présents dans la solution sans la modifier.

**Réponse correcte** : A

**Feedback correct**
Un tampon limite les variations de pH lors d'ajouts modérés d'acide ou de base, parce qu'il contient un acide faible et sa base conjuguée en quantités comparables : l'un neutralise l'acide ajouté, l'autre la base ajoutée.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La valeur du pH d'un tampon dépend du couple choisi (p$K_a$) et du rapport des quantités ; elle n'est pas nécessairement 7.
- Si C : Un tampon a une capacité limitée : si l'on ajoute trop d'acide ou de base, l'un des deux constituants est épuisé et le pH varie brutalement.
- Si D : Le tampon réagit bien avec les acides et les bases forts, c'est justement ce qui limite la variation de pH ; il ne les laisse pas intacts dans la solution.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-solution-tampon-parti-com-001
concept: solution-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: parti
type: com
misconception: tampon--melange-quelconque-acide-base
date_validation: 2026-11-10
statut: validated
---

**Question**
Parmi les mélanges suivants, lequel donne une solution tampon ?

**Options**
- A. 100 mL d'acide chlorhydrique à 0,10 mol/L et 100 mL de soude à 0,10 mol/L, car on mélange un acide et une base.
- B. 100 mL d'acide éthanoïque à 0,10 mol/L et 100 mL d'acide chlorhydrique à 0,10 mol/L, car on mélange deux acides.
- C. 100 mL d'acide chlorhydrique à 0,10 mol/L et 100 mL de chlorure de sodium à 0,10 mol/L, car on ajoute un sel de l'acide.
- D. 100 mL d'acide éthanoïque à 0,10 mol/L et 100 mL de soude à 0,050 mol/L, car il reste autant d'acide éthanoïque que d'ion éthanoate formé.

**Réponse correcte** : D

**Feedback correct**
La soude (5,0 mmol) neutralise la moitié de l'acide éthanoïque (10 mmol) : il reste 5,0 mmol de $\ce{CH3COOH}$ et se forment 5,0 mmol de $\ce{CH3COO-}$. L'acide faible et sa base conjuguée coexistent en quantités comparables : c'est un tampon de pH 4,75.

**Feedback incorrect**
- Si A : Les quantités égales d'acide fort et de base forte se neutralisent totalement : il ne reste que $\ce{Na+}$ et $\ce{Cl-}$, des ions spectateurs. Mélanger un acide et une base ne suffit pas à fabriquer un tampon.
- Si B : Un acide faible mélangé à un acide fort ne contient pas de base conjuguée : l'ion éthanoate est absent, rien ne peut neutraliser un acide ajouté.
- Si C : $\ce{Cl-}$ est la base conjuguée d'un acide fort, trop faible pour neutraliser un acide ajouté. Il manque un couple d'acide faible.
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-solution-tampon-symbo-sou-001
concept: solution-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelle est l'équation de Henderson-Hasselbalch pour un tampon formé d'un acide faible $\ce{HA}$ et de sa base conjuguée $\ce{A-}$ ?

**Options**
- A. $\text{pH} = \text{p}K_a + \log\dfrac{[\ce{HA}]}{[\ce{A-}]}$
- B. $\text{pH} = \text{p}K_a + \log\dfrac{[\ce{A-}]}{[\ce{HA}]}$
- C. $\text{pH} = \text{p}K_a + \dfrac{[\ce{A-}]}{[\ce{HA}]}$
- D. $\text{pH} = 14 - \text{p}K_a + \log\dfrac{[\ce{A-}]}{[\ce{HA}]}$

**Réponse correcte** : B

**Feedback correct**
$\text{pH} = \text{p}K_a + \log([\ce{A-}]/[\ce{HA}])$ : la base conjuguée au numérateur. Si $[\ce{A-}] > [\ce{HA}]$, le pH est supérieur au p$K_a$.

**Feedback incorrect**
- Si A : Le rapport est inversé : cette écriture donnerait un pH inférieur au p$K_a$ quand la base est majoritaire, ce qui est faux.
- Si B : C'est une bonne réponse.
- Si C : Il manque le logarithme : le rapport des concentrations intervient par son logarithme décimal.
- Si D : Le terme $14 - \text{p}K_a$ est le p$K_b$ ; l'équation s'écrit avec le p$K_a$ du couple.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-solution-tampon-symbo-app-001
concept: solution-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
misconception: tampon--rapport-inverse-hh
date_validation: 2026-11-10
statut: validated
---

**Question**
Calculez le pH d'un tampon contenant 0,10 mol/L d'acide éthanoïque et 0,50 mol/L d'éthanoate de sodium (p$K_a = 4{,}75$).

**Options**
- A. 4,05
- B. 4,75
- C. 5,45
- D. 5,25

**Réponse correcte** : C

**Feedback correct**
Le rapport $[\ce{CH3COO-}]/[\ce{CH3COOH}]$ vaut 5 et son logarithme décimal 0,70, donc le pH est de 5,45 (soit 4,75 plus 0,70).

**Feedback incorrect**
- Si A : Le rapport a été inversé ($\log 0{,}2 = -0{,}70$). La base est majoritaire : le pH est supérieur au p$K_a$.
- Si B : Le pH égale le p$K_a$ seulement si $[\ce{HA}] = [\ce{A-}]$, ce qui n'est pas le cas ici.
- Si C : C'est une bonne réponse.
- Si D : 5,25 s'obtient en ajoutant au p$K_a$ la concentration de la base (0,50). Le terme correctif est le logarithme du rapport, soit 0,70.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-solution-tampon-symbo-app-002
concept: solution-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Un litre de tampon contient 0,20 mol d'acide éthanoïque et 0,20 mol d'éthanoate de sodium. On y ajoute 0,050 mol d'acide chlorhydrique, sans variation de volume. Quel est le pH final ? (p$K_a = 4{,}75$)

**Options**
- A. 1,30
- B. 4,53
- C. 4,75
- D. 4,97

**Réponse correcte** : B

**Feedback correct**
L'acide chlorhydrique réagit avec $\ce{CH3COO-}$ : il reste 0,15 mol de base et se forment 0,25 mol d'acide. $\text{pH} = 4{,}75 + \log(0{,}15/0{,}25) = 4{,}75 - 0{,}22 = 4{,}53$.

**Feedback incorrect**
- Si A : 1,30 serait le pH si l'acide ajouté restait libre (0,050 mol/L) ; or le tampon en neutralise la presque totalité.
- Si B : C'est une bonne réponse.
- Si C : Le pH ne reste pas égal au p$K_a$ : l'ajout d'acide modifie le rapport base/acide, donc le pH, légèrement.
- Si D : Le pH augmenterait si l'on ajoutait une base. Ici l'acide ajouté convertit la base en acide, ce qui abaisse le pH.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-solution-tampon-symbo-ana-001
concept: solution-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: tampon--ph-egal-pka-toujours
date_validation: 2026-11-10
statut: validated
---

**Question**
Un tampon est préparé avec 0,30 mol/L de chlorure d'ammonium et 0,10 mol/L d'ammoniac (p$K_a(\ce{NH4+/NH3}) = 9{,}22$). Sans calcul détaillé, où se situe son pH ?

**Options**
- A. Au-dessus de 9,22, car l'ammoniac est la base du couple.
- B. Exactement à 9,22, car le pH d'un tampon est toujours égal au p$K_a$ du couple utilisé.
- C. En dessous de 9,22 (environ 8,7), car l'acide $\ce{NH4+}$ est majoritaire.
- D. Autour de 7, car un tampon maintient le pH près de la neutralité.

**Réponse correcte** : C

**Feedback correct**
Le rapport $[\ce{NH3}]/[\ce{NH4+}] = 1/3 < 1$ donne un logarithme négatif : $\text{pH} = 9{,}22 + \log(1/3) = 8{,}74$, en dessous du p$K_a$.

**Feedback incorrect**
- Si A : Ce n'est pas la nature du couple qui compte, mais la forme majoritaire : ici l'acide $\ce{NH4+}$ est trois fois plus concentré que la base, le pH est sous le p$K_a$.
- Si B : Le pH vaut le p$K_a$ uniquement si les concentrations de l'acide et de la base sont égales.
- Si C : C'est une bonne réponse.
- Si D : Le pH d'un tampon est fixé par le p$K_a$ du couple et le rapport des concentrations, pas par la neutralité.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-solution-tampon-symbo-eva-001
concept: solution-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: tampon--dilution-change-le-ph
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Si je dilue 10 fois un tampon acétique, son pH change d'environ une unité, comme pour un acide fort dilué. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte : la concentration de l'acide est divisée par 10.
- B. Elle est fausse : le pH diminue d'une unité, car la solution devient plus acide.
- C. Elle est fausse : le pH reste quasiment le même ; seul le pouvoir tampon diminue.
- D. Elle est fausse : le pH reste identique, quelle que soit la dilution, et le pouvoir tampon aussi.

**Réponse correcte** : C

**Feedback correct**
Le pH d'un tampon dépend du p$K_a$ et du rapport $[\ce{A-}]/[\ce{HA}]$. La dilution divise les deux concentrations par 10 : le rapport, donc le pH, ne change pas (aux concentrations usuelles). En revanche les quantités de $\ce{HA}$ et de $\ce{A-}$ par litre diminuent, et avec elles la capacité à résister aux ajouts.

**Feedback incorrect**
- Si A : Les deux concentrations sont divisées par 10 en même temps : leur rapport, qui fixe le pH, reste le même.
- Si B : Il n'y a aucune raison que la solution devienne plus acide : la dilution ne modifie ni le p$K_a$ ni le rapport base/acide.
- Si C : C'est une bonne réponse.
- Si D : Le pH est conservé par la dilution, mais pas le pouvoir tampon : avec 10 fois moins de $\ce{HA}$ et de $\ce{A-}$ par litre, la capacité à neutraliser les ajouts est réduite.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-pouvoir-tampon-macro-sou-001
concept: pouvoir-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Qu'appelle-t-on pouvoir tampon d'une solution tampon ?

**Options**
- A. La valeur du pH de la solution, qui doit être égale au p$K_a$ du couple utilisé.
- B. Son aptitude à limiter la variation de pH lors de l'ajout d'acide ou de base.
- C. Le rapport entre les concentrations de la base et de l'acide du couple.
- D. La quantité de base nécessaire pour amener la solution à pH 7.

**Réponse correcte** : B

**Feedback correct**
Le pouvoir tampon mesure la capacité de la solution à résister aux variations de pH quand on y ajoute un acide ou une base ; il est d'autant plus grand que les quantités d'acide faible et de base conjuguée sont grandes et proches.

**Feedback incorrect**
- Si A : La valeur du pH est une autre grandeur, qui dépend du p$K_a$ et du rapport des concentrations ; elle ne mesure pas la capacité de résistance.
- Si B : C'est une bonne réponse.
- Si C : Ce rapport fixe le pH du tampon (équation de Henderson-Hasselbalch), pas sa capacité à résister aux ajouts.
- Si D : Il n'y a aucune raison d'amener un tampon à pH 7 ; son pH est fixé par le couple choisi.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-pouvoir-tampon-parti-com-001
concept: pouvoir-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: parti
type: com
date_validation: 2026-11-10
statut: validated
---

**Question**
Deux tampons ont le même rapport $[\ce{A-}]/[\ce{HA}] = 1$. Le premier contient 0,50 mol de chaque espèce, le second 0,050 mol. Pourquoi le premier résiste-t-il mieux à l'ajout de 0,10 mol d'acide chlorhydrique ?

**Options**
- A. Parce qu'il contient davantage d'ions $\ce{A-}$, disponibles pour capter les ions $\ce{H3O+}$ ajoutés.
- B. Parce que son pH est plus élevé que celui du second tampon.
- C. Parce que son p$K_a$ est plus grand que celui du second tampon.
- D. Parce que l'acide chlorhydrique réagit avec $\ce{HA}$, qui est plus abondant dans le premier tampon.

**Réponse correcte** : A

**Feedback correct**
Les ions $\ce{H3O+}$ ajoutés réagissent avec la base conjuguée $\ce{A-}$. Le premier tampon en contient 0,50 mol (le second, 0,050 mol, serait épuisé par 0,10 mol d'acide) : sa capacité est dix fois plus grande.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Les deux tampons ont le même rapport, donc le même pH. La différence tient aux quantités, pas à la valeur du pH.
- Si C : Le p$K_a$ dépend du couple, pas de la quantité : les deux tampons utilisent le même couple.
- Si D : L'acide chlorhydrique réagit avec la base $\ce{A-}$, pas avec l'acide $\ce{HA}$ : c'est la quantité de base conjuguée qui limite l'ajout d'acide absorbable.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-pouvoir-tampon-symbo-app-001
concept: pouvoir-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Un litre de tampon contient 0,50 mol d'acide éthanoïque et 0,50 mol d'éthanoate de sodium. On y ajoute 0,10 mol d'acide chlorhydrique, sans variation de volume. Quel est le pH final ? (p$K_a = 4{,}75$)

**Options**
- A. 4,75
- B. 4,57
- C. 4,93
- D. 1,00

**Réponse correcte** : B

**Feedback correct**
L'acide ajouté convertit 0,10 mol de base en acide : il reste 0,40 mol de $\ce{CH3COO-}$ et il y a 0,60 mol de $\ce{CH3COOH}$. $\text{pH} = 4{,}75 + \log(0{,}40/0{,}60) = 4{,}75 - 0{,}18 = 4{,}57$ : le pH n'a baissé que de 0,18 unité.

**Feedback incorrect**
- Si A : Le rapport a changé (0,40/0,60), donc le pH aussi, même si peu.
- Si B : C'est une bonne réponse.
- Si C : Le pH augmenterait si l'on ajoutait une base. Ici l'acide ajouté abaisse le pH.
- Si D : 1,00 serait le pH de l'acide ajouté, resté libre (0,10 mol/L), ce qui suppose qu'il n'est pas neutralisé par le tampon.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-pouvoir-tampon-symbo-app-002
concept: pouvoir-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Un litre de tampon dilué contient 0,050 mol d'acide éthanoïque et 0,050 mol d'éthanoate de sodium. On y ajoute 0,030 mol d'acide chlorhydrique, sans variation de volume. Quel est le pH final ? (p$K_a = 4{,}75$)

**Options**
- A. 1,52
- B. 4,15
- C. 4,75
- D. 5,35

**Réponse correcte** : B

**Feedback correct**
L'acide ajouté convertit 0,030 mol de base en acide : il reste 0,020 mol de $\ce{CH3COO-}$ et il y a 0,080 mol de $\ce{CH3COOH}$. $\text{pH} = 4{,}75 + \log(0{,}020/0{,}080) = 4{,}75 - 0{,}60 = 4{,}15$ : la baisse est ici plus importante, car le tampon est moins concentré.

**Feedback incorrect**
- Si A : 1,52 serait le pH de l'acide ajouté seul (0,030 mol/L) ; le tampon en neutralise une grande partie.
- Si B : C'est une bonne réponse.
- Si C : Le rapport $[\ce{A-}]/[\ce{HA}]$ n'est plus égal à 1 après l'ajout : le pH n'est plus égal au p$K_a$.
- Si D : Le pH monterait si l'on ajoutait une base ; l'acide ajouté abaisse le pH.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-pouvoir-tampon-symbo-ana-001
concept: pouvoir-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: pouvoir-tampon--composants-forts-meilleur-tampon
date_validation: 2026-11-10
statut: validated
---

**Question**
Tampon X : 0,10 mol d'acide éthanoïque (p$K_a = 4{,}75$) et 0,10 mol d'éthanoate de sodium. Tampon Y : 0,010 mol d'acide fluorhydrique (p$K_a = 3{,}17$) et 0,010 mol de fluorure de sodium. Même volume. Lequel résiste le mieux à l'ajout de 0,005 mol d'acide chlorhydrique ?

**Options**
- A. Le tampon Y, car l'acide fluorhydrique est un acide plus fort que l'acide éthanoïque.
- B. Les deux se valent, car les deux ont un rapport base/acide égal à 1.
- C. Aucun, car un tampon ne résiste qu'à l'ajout d'une base.
- D. Le tampon X, car il contient dix fois plus d'acide faible et de base conjuguée.

**Réponse correcte** : D

**Feedback correct**
Le pouvoir tampon dépend des quantités de $\ce{HA}$ et de $\ce{A-}$, pas de la force du couple. X contient 0,10 mol de base, Y seulement 0,010 mol : l'ajout de 0,005 mol d'acide consomme la moitié de la base de Y, contre 5 % de celle de X.

**Feedback incorrect**
- Si A : Un acide plus fort ne donne pas un meilleur tampon : c'est la quantité disponible des deux espèces conjuguées qui fixe la capacité, et le p$K_a$ le domaine de pH.
- Si B : Un même rapport donne le même pH, mais pas la même capacité : celle-ci augmente avec les quantités.
- Si C : Un tampon résiste aux deux types d'ajout : la base conjuguée neutralise l'acide, l'acide faible neutralise la base.
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-pouvoir-tampon-symbo-ana-002
concept: pouvoir-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: pouvoir-tampon--independant-de-la-concentration
date_validation: 2026-11-10
statut: validated
---

**Question**
Deux tampons acétiques ont le même pH, 4,75 : le tampon P contient 0,010 mol/L de chaque espèce, le tampon Q 0,50 mol/L de chaque espèce. On ajoute 5,0 mmol de soude à 100 mL de chacun. Que peut-on prévoir ?

**Options**
- A. Le pH de Q varie le plus, car Q est plus concentré.
- B. Les deux pH varient de la même façon, car ils ont le même pH initial et utilisent le même couple, de même p$K_a$.
- C. Le pH de P varie très fortement : sa capacité (1,0 mmol) est dépassée par 5,0 mmol de soude.
- D. Aucun des deux pH ne varie, puisque ce sont deux tampons.

**Réponse correcte** : C

**Feedback correct**
P contient 1,0 mmol de $\ce{CH3COOH}$ dans 100 mL : la soude (5,0 mmol) la consomme entièrement et il reste 4,0 mmol de $\ce{OH-}$ libres (pH proche de 12,6). Q contient 50 mmol de chaque espèce : le rapport devient 55/45 et le pH passe seulement à 4,84.

**Feedback incorrect**
- Si A : Un tampon plus concentré varie moins : il a davantage de matière pour neutraliser l'ajout.
- Si B : Le même pH et le même p$K_a$ ne suffisent pas : la capacité à résister dépend aussi des quantités présentes.
- Si C : C'est une bonne réponse.
- Si D : Un tampon n'est efficace que dans les limites de sa capacité ; P est dépassé et son pH varie fortement.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-pouvoir-tampon-symbo-eva-001
concept: pouvoir-tampon
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: pouvoir-tampon--zone-pka-ignoree
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Le couple $\ce{CH3COOH/CH3COO-}$ (p$K_a = 4{,}75$) permet de préparer un tampon efficace à pH 8, il suffit d'ajuster le rapport base/acide. » Que pensez-vous de cette affirmation ?

**Options**
- A. Elle est correcte : tout pH est accessible en choisissant le bon rapport.
- B. Elle est fausse : un tampon pour pH 8 doit être préparé avec un acide fort de p$K_a$ inférieur à 8.
- C. Elle est correcte, car l'équation de Henderson-Hasselbalch est valable à tout pH.
- D. Elle est fausse : à pH 8, l'acide est quasi absent et ne neutralise plus la base ajoutée.

**Réponse correcte** : D

**Feedback correct**
On peut calculer un rapport $[\ce{A-}]/[\ce{HA}] = 10^{8-4{,}75} \approx 1800$, mais le tampon ainsi préparé ne contient presque plus d'acide faible : il ne résiste plus à l'ajout d'une base. Un tampon est efficace pour un rapport entre 1/10 et 10, soit pour un pH compris entre p$K_a - 1$ et p$K_a + 1$. Pour pH 8, on choisit un couple de p$K_a$ voisin de 8.

**Feedback incorrect**
- Si A : L'équation donne bien un rapport pour tout pH, mais l'efficacité n'est assurée que pour des quantités comparables d'acide et de base, soit p$K_a \pm 1$.
- Si B : Il faut un couple de p$K_a$ voisin de 8 (acide faible), pas un acide fort : un acide fort n'a pas de base conjuguée utilisable.
- Si C : L'équation est valable, mais la formule ne garantit pas l'efficacité du tampon : celle-ci exige des quantités comparables des deux espèces.
- Si D : C'est une bonne réponse.

**Référence manuel** : acides-bases-ph-tampon

---

---
id: q-indicateur-colore-macro-sou-001
concept: indicateur-colore
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Qu'est-ce qu'un indicateur coloré acido-basique ?

**Options**
- A. Un couple acide-base dont les formes acide et basique ont des couleurs différentes.
- B. Un acide fort dont la couleur change quand on le neutralise par une base forte que l'on ajoute progressivement.
- C. Un réactif qui devient coloré uniquement au moment exact de l'équivalence, quel que soit le pH de la solution.
- D. Un sel coloré dont la simple présence fixe le pH de la solution à une valeur proche de 7 pour tous les titrages.

**Réponse correcte** : A

**Feedback correct**
Un indicateur coloré est un couple $\ce{HIn}/\ce{In-}$ dont les deux formes n'ont pas la même couleur. La forme majoritaire, donc la teinte observée, dépend du pH de la solution.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Un indicateur est un acide ou une base faible, présent en très petite quantité ; sa couleur dépend du pH, pas de la neutralisation d'un acide fort.
- Si C : Le changement de teinte dépend du pH et non d'un instant particulier : il se produit dans une zone de pH autour du p$K_a$ de l'indicateur.
- Si D : L'indicateur est ajouté en quantité infime : il ne fixe pas le pH, il le signale seulement par sa couleur.

**Référence manuel** : acides-bases-ph-indicateurs

---

---
id: q-indicateur-colore-macro-com-001
concept: indicateur-colore
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
misconception: indicateur--virage-en-un-point
date_validation: 2026-11-10
statut: validated
---

**Question**
On ajoute quelques gouttes de bleu de bromothymol (p$K_a = 7{,}1$, jaune en milieu acide, bleu en milieu basique) dans une solution dont on fait croître le pH de 5 à 9. Quelle observation fait-on ?

**Options**
- A. La teinte évolue progressivement du jaune vers le bleu, en passant par une teinte intermédiaire autour de pH 7,1.
- B. La solution reste jaune jusqu'à pH 7,1, puis devient brusquement bleue sans aucune teinte intermédiaire entre les deux couleurs.
- C. La solution devient bleue dès pH 6, puis ne change plus de teinte jusqu'à pH 9, car l'indicateur est alors totalement consommé.
- D. La solution reste jaune sur toute la gamme, car la couleur d'un indicateur est indépendante du pH de la solution observée.

**Réponse correcte** : A

**Feedback correct**
Les formes acide (jaune) et basique (bleue) coexistent : la teinte dépend de leur proportion, qui varie progressivement avec le pH. À pH 7,1 les deux formes sont en quantités égales, d'où la teinte intermédiaire.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le changement n'est pas instantané : il s'étend sur environ deux unités de pH autour du p$K_a$, la proportion des deux formes variant de façon continue.
- Si C : À pH 6 la forme acide reste très largement majoritaire : la solution est encore jaune. L'indicateur n'est pas consommé, il passe d'une forme à l'autre.
- Si D : La proportion des deux formes dépend du pH, c'est précisément ce qui fait varier la couleur observée.

**Référence manuel** : acides-bases-ph-indicateurs

---

---
id: q-indicateur-colore-symbo-app-001
concept: indicateur-colore
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Le bleu de bromothymol est un indicateur de p$K_a = 7{,}1$ (forme acide jaune, forme basique bleue). Quelle est la proportion de la forme basique $\ce{In-}$ à pH 6,1 ?

**Options**
- A. 9,1 %
- B. 91 %
- C. 50 %
- D. 1,0 %

**Réponse correcte** : A

**Feedback correct**
Le pH est inférieur au p$K_a$ d'une unité, donc le rapport $[\ce{In-}]/[\ce{HIn}]$ vaut $10^{-1}$, soit 0,10. La proportion de $\ce{In-}$ est 0,10 divisé par 1,10, soit 9,1 % : la solution est jaune.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Cette valeur correspond à la proportion de la forme acide $\ce{HIn}$ ; les deux proportions sont inversées. À pH inférieur au p$K_a$, la forme acide domine.
- Si C : Une proportion de 50 % ne s'obtient que si le pH est égal au p$K_a$, soit 7,1.
- Si D : Il faut passer par le rapport $10^{\text{pH} - \text{p}K_a}$, qui vaut 0,10 ici, puis le rapporter à la somme des deux formes : on obtient environ 9 %, non 1 %.

**Référence manuel** : acides-bases-ph-indicateurs

---

---
id: q-indicateur-colore-symbo-app-002
concept: indicateur-colore
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
misconception: titrage--equivalence-egal-ph-7
date_validation: 2026-11-10
statut: validated
---

**Question**
On titre 25,0 mL d'ammoniac $\ce{NH3}$ à 0,10 mol/L par de l'acide chlorhydrique à 0,10 mol/L (p$K_a(\ce{NH4+}) = 9{,}22$). Le pH à l'équivalence vaut 5,26. Quel indicateur coloré choisir ?

**Options**
- A. Le rouge de méthyle, dont la plage de virage (4,2 à 6,2) englobe 5,26.
- B. Le bleu de bromothymol (6,0 à 7,6), car l'équivalence a lieu à un pH voisin de la neutralité.
- C. La phénolphtaléine (8,0 à 9,8), car c'est l'indicateur le plus répandu pour les titrages avec une base.
- D. L'hélianthine (3,1 à 4,4), car sa plage de virage est la plus acide, comme le pH de l'équivalence de ce titrage.

**Réponse correcte** : A

**Feedback correct**
L'indicateur doit avoir une plage de virage qui englobe le pH à l'équivalence. Seul le rouge de méthyle (4,2 à 6,2) englobe 5,26. L'équivalence ne correspond pas à pH 7 ici, car le chlorure d'ammonium est un sel acide.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : L'équivalence n'a lieu à pH 7 que pour un acide fort et une base forte. Ici le pH vaut 5,26, que la plage 6,0 à 7,6 ne recouvre pas.
- Si C : Une plage de virage basique serait adaptée à un pH d'équivalence basique. Ici le pH vaut 5,26 : la phénolphtaléine ne virerait que bien après l'équivalence.
- Si D : Plus acide ne suffit pas : la plage 3,1 à 4,4 est entièrement en dessous de 5,26, le virage serait observé trop tôt, avant l'équivalence.

**Référence manuel** : acides-bases-ph-indicateurs

---

---
id: q-indicateur-colore-symbo-ana-001
concept: indicateur-colore
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: titrage--equivalence-egal-virage
date_validation: 2026-11-10
statut: validated
---

**Question**
Lors du titrage de $\ce{CH3COOH}$ à 0,10 mol/L par $\ce{NaOH}$, le pH à l'équivalence vaut 8,72. On emploie la phénolphtaléine (p$K_a = 9{,}7$, plage de virage 8,0 à 9,8). Quelle affirmation est exacte ?

**Options**
- A. Le virage a lieu près de l'équivalence car sa plage englobe 8,72, mais les deux notions restent distinctes.
- B. La couleur change exactement à l'équivalence, car le pH de virage de l'indicateur est alors égal au pH d'équivalence, soit 9,7.
- C. La phénolphtaléine ne convient pas, car son p$K_a$ de 9,7 est différent du pH de 8,72 à l'équivalence, ce qui décalerait le virage.
- D. Le virage se produit à pH 7, puisque l'équivalence d'un titrage acide-base correspond toujours à une solution neutre.

**Réponse correcte** : A

**Feedback correct**
Équivalence et virage sont deux notions distinctes : l'équivalence est définie par les quantités de matière, le virage par la plage de pH de l'indicateur. L'indicateur convient si sa plage (8,0 à 9,8) englobe le pH d'équivalence (8,72).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le p$K_a$ de l'indicateur (9,7) et le pH à l'équivalence (8,72) sont deux valeurs différentes. Le virage est observé sur une plage de pH, qui englobe l'équivalence sans coïncider avec elle.
- Si C : L'indicateur n'a pas besoin d'un p$K_a$ égal au pH d'équivalence. Il suffit que la plage de virage recouvre ce pH, ce qui est le cas ici.
- Si D : Le titrage d'un acide faible par une base forte donne une solution basique à l'équivalence (ion éthanoate), non neutre : le pH vaut 8,72.

**Référence manuel** : acides-bases-ph-indicateurs

---

---
id: q-indicateur-colore-symbo-eva-001
concept: indicateur-colore
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: indicateur--indicateur-participe-neutralisation
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Pour que la couleur change, l'indicateur coloré doit réagir avec la soude versée ; plus on en met, mieux on voit le virage. » Que penser de cette affirmation ?

**Options**
- A. Elle est fausse : on n'ajoute que quelques gouttes et l'indicateur ne consomme pas de soude de façon notable.
- B. Elle est exacte : l'indicateur est neutralisé par la soude au même titre que l'acide titré, et sa quantité doit donc être grande pour que le virage soit net.
- C. Elle est à moitié exacte : l'indicateur réagit avec la soude, mais seulement une fois que tout l'acide titré a été consommé par la soude.
- D. Elle est fausse : le virage est dû à un changement de température de la solution lors de la neutralisation, non à une réaction chimique.

**Réponse correcte** : A

**Feedback correct**
L'indicateur est un couple acide-base introduit en quantité infime : sa propre neutralisation consomme une quantité de soude négligeable et ne modifie pas le volume équivalent. Ajouter beaucoup d'indicateur fausserait le titrage.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Une grande quantité d'indicateur consommerait une quantité non négligeable de soude et fausserait le volume équivalent. On en ajoute au contraire très peu.
- Si C : L'indicateur ne réagit pas après l'acide : sa forme change en fonction du pH, qui varie progressivement. Sa quantité est trop faible pour intervenir dans le bilan de matière.
- Si D : La couleur change parce que le pH varie et déplace l'équilibre entre les deux formes de l'indicateur ; la température n'intervient pas.

**Référence manuel** : acides-bases-ph-indicateurs

---

---
id: q-indicateur-colore-symbo-eva-002
concept: indicateur-colore
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: indicateur--virage-en-un-point
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève écrit : « Le bleu de bromothymol change de couleur exactement à pH 7,1 : en dessous la solution est parfaitement jaune, au-dessus parfaitement bleue. » Que penser de cette affirmation ?

**Options**
- A. Elle est fausse : la teinte évolue sur environ deux unités de pH ; à pH 7,1 les deux formes sont en quantités égales.
- B. Elle est exacte : à pH 7,1 les deux formes sont présentes en proportions égales, ce qui donne une transition nette et instantanée entre le jaune et le bleu.
- C. Elle est exacte : un indicateur ne change de couleur qu'au point où la concentration de sa forme acide s'annule complètement.
- D. Elle est fausse : le virage a lieu à pH 7 exactement, valeur indépendante de l'indicateur choisi, car l'eau pure est neutre.

**Réponse correcte** : A

**Feedback correct**
Le virage s'étend sur une plage de l'ordre de deux unités de pH (6,0 à 7,6 pour le BBT). À pH 7,1 les deux formes sont en quantités égales, mais la teinte varie progressivement de part et d'autre.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : L'égalité des deux formes à pH 7,1 est exacte, mais la transition n'est pas instantanée : la proportion des formes varie de façon continue avec le pH.
- Si C : La forme acide ne disparaît jamais complètement : elle reste présente en proportion faible, mais non nulle, bien au-delà du p$K_a$.
- Si D : Le pH de virage dépend de l'indicateur, via son p$K_a$ : 4,2 pour l'hélianthine, 7,1 pour le BBT, 9,7 pour la phénolphtaléine.

**Référence manuel** : acides-bases-ph-indicateurs

---

---
id: q-acide-polyprotique-macro-com-001
concept: acide-polyprotique
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: macro
type: com
misconception: polyacides--deuxieme-proton-aussi-facile
date_validation: 2026-11-10
statut: validated
---

**Question**
On suit par pH-métrie le titrage de l'acide carbonique $\ce{H2CO3}$ (p$K_{a1} = 6{,}35$ ; p$K_{a2} = 10{,}25$) par la soude. Quelle est l'allure théorique de la courbe ?

**Options**
- A. Deux sauts de pH, aux volumes $V_1$ et $2V_1$, un pour chaque proton titré.
- B. Un seul saut de pH, car les deux protons de l'acide sont titrés ensemble, à un même volume équivalent unique.
- C. Deux sauts de pH, aux volumes $V_1$ et $V_1/2$, le proton le moins acide étant titré en premier.
- D. Aucun saut net, car un diacide faible ne peut pas être titré par une base forte, quelle que soit la différence des p$K_a$.

**Réponse correcte** : A

**Feedback correct**
Les deux p$K_a$ sont éloignés : les deux protons sont titrés l'un après l'autre. Le premier saut a lieu à $V_1$ et le second à $2V_1$, car le second proton consomme autant de soude que le premier.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Les deux protons n'ont pas la même acidité : le plus acide est titré avant l'autre, ce qui donne deux équivalences distinctes lorsque les p$K_a$ sont suffisamment espacés.
- Si C : Le proton le plus acide (p$K_{a1}$) est titré en premier, et le second volume équivalent est plus grand que le premier, pas plus petit.
- Si D : Un diacide faible se titre par une base forte ; l'écart des p$K_a$ détermine seulement si les deux sauts sont séparés.

**Référence manuel** : acides-bases-ph-polyacides

---

---
id: q-acide-polyprotique-symbo-sou-001
concept: acide-polyprotique
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-10
statut: validated
---

**Question**
Quelles équations décrivent les deux dissociations successives de l'acide carbonique dans l'eau ?

**Options**
- A. $\ce{H2CO3 + H2O <=> HCO3- + H3O+}$ puis $\ce{HCO3- + H2O <=> CO3^2- + H3O+}$
- B. $\ce{H2CO3 + 2 H2O <=> CO3^2- + 2 H3O+}$ en une seule étape, avec une unique constante d'acidité pour les deux protons
- C. $\ce{H2CO3 + H2O <=> HCO3- + H3O+}$ puis $\ce{HCO3- + H3O+ <=> H2CO3 + H2O}$
- D. $\ce{H2CO3 + OH- <=> HCO3- + H2O}$ puis $\ce{HCO3- + OH- <=> CO3^2- + H2O}$

**Réponse correcte** : A

**Feedback correct**
Les protons sont cédés l'un après l'autre à l'eau, avec deux constantes : $K_{a1}$ pour le couple $\ce{H2CO3}/\ce{HCO3-}$ et $K_{a2}$ pour $\ce{HCO3-}/\ce{CO3^2-}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Un diacide cède ses protons en deux étapes successives, chacune avec sa propre constante ($K_{a1}$ puis $K_{a2}$). Une équation globale unique masquerait cette différence.
- Si C : La seconde équation est la réaction inverse de la première : elle ne décrit pas la deuxième dissociation, qui forme $\ce{CO3^2-}$.
- Si D : Ces équations décrivent des réactions avec une base ajoutée, non les dissociations de l'acide dans l'eau, où l'accepteur de proton est $\ce{H2O}$.

**Référence manuel** : acides-bases-ph-polyacides

---

---
id: q-acide-polyprotique-symbo-app-001
concept: acide-polyprotique
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
On titre 20,0 mL d'acide phosphorique $\ce{H3PO4}$ à 0,10 mol/L par de la soude à 0,20 mol/L (p$K_a$ : 2,12 ; 7,20 ; 12,37). Quel volume de soude faut-il verser pour atteindre la deuxième équivalence ?

**Options**
- A. 10,0 mL
- B. 20,0 mL
- C. 30,0 mL
- D. 40,0 mL

**Réponse correcte** : B

**Feedback correct**
La prise d'essai contient 2,0 mmol d'acide. À la deuxième équivalence, chaque molécule a cédé deux protons : il faut 4,0 mmol de soude, soit 4,0 mmol divisées par 0,20 mmol/mL, c'est-à-dire 20,0 mL.

**Feedback incorrect**
- Si A : Ce volume correspond à la première équivalence (2,0 mmol de soude, un proton par molécule), non à la deuxième.
- Si B : C'est une bonne réponse.
- Si C : Ce volume correspond à une troisième équivalence (6,0 mmol de soude), qui suppose le troisième proton titré. La deuxième équivalence n'en fait pas partie.
- Si D : Ce résultat vient d'un calcul fait avec une concentration de soude de 0,10 mol/L ; la soude est à 0,20 mol/L, le volume est donc deux fois plus petit.

**Référence manuel** : acides-bases-ph-polyacides

---

---
id: q-acide-polyprotique-symbo-app-002
concept: acide-polyprotique
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-10
statut: validated
---

**Question**
Dans le même titrage (20,0 mL de $\ce{H3PO4}$ à 0,10 mol/L par la soude à 0,20 mol/L ; p$K_a$ : 2,12 ; 7,20 ; 12,37), quel est le pH après ajout de 15,0 mL de soude ?

**Options**
- A. 2,12
- B. 4,66
- C. 7,20
- D. 9,79

**Réponse correcte** : C

**Feedback correct**
La première équivalence a lieu à 10,0 mL et la deuxième à 20,0 mL : 15,0 mL est au milieu. La moitié des ions $\ce{H2PO4-}$ a été convertie en $\ce{HPO4^2-}$, les deux espèces sont en quantités égales, donc le pH vaut le p$K_{a2}$, soit 7,20.

**Feedback incorrect**
- Si A : Cette valeur est le p$K_{a1}$, atteinte à 5,0 mL de soude (moitié de la première équivalence). À 15,0 mL, c'est le couple $\ce{H2PO4-}/\ce{HPO4^2-}$ qui impose le pH.
- Si B : Cette valeur est le pH à la première équivalence (10,0 mL), demi-somme de p$K_{a1}$ et p$K_{a2}$. À 15,0 mL on a dépassé cette équivalence.
- Si C : C'est une bonne réponse.
- Si D : Cette valeur est la demi-somme de p$K_{a2}$ et p$K_{a3}$, vers la seconde équivalence (20,0 mL), non à 15,0 mL où les deux formes sont en quantités égales.

**Référence manuel** : acides-bases-ph-polyacides

---

---
id: q-acide-polyprotique-symbo-ana-001
concept: acide-polyprotique
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: polyacides--deuxieme-proton-aussi-facile
date_validation: 2026-11-10
statut: validated
---

**Question**
Le pH d'une solution contenant de l'acide phosphorique est fixé à 5,0 (p$K_a$ : 2,12 ; 7,20 ; 12,37). Quelle espèce est majoritaire ?

**Options**
- A. $\ce{H2PO4-}$, car le pH est compris entre p$K_{a1}$ et p$K_{a2}$.
- B. $\ce{H3PO4}$, car le pH est inférieur à 7 et la solution est donc acide.
- C. $\ce{PO4^3-}$, car le pH est supérieur à 2,12, valeur à partir de laquelle l'acide a perdu tous ses protons.
- D. $\ce{HPO4^2-}$, car les deux premiers protons sont cédés ensemble dès que le pH dépasse 2,12.

**Réponse correcte** : A

**Feedback correct**
Au-dessus de p$K_{a1}$ (2,12), $\ce{H3PO4}$ est devenu minoritaire par rapport à $\ce{H2PO4-}$. Au-dessous de p$K_{a2}$ (7,20), $\ce{H2PO4-}$ domine encore $\ce{HPO4^2-}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Un pH acide ne suffit pas : il faut comparer le pH au p$K_{a1}$. À pH 5,0, supérieur à 2,12, $\ce{H3PO4}$ est minoritaire.
- Si C : Chaque proton est cédé à son propre pH : l'ion $\ce{PO4^3-}$ n'est majoritaire qu'au-dessus de p$K_{a3}$ (12,37).
- Si D : Les protons ne sont pas cédés ensemble : le deuxième l'est à un pH plus élevé que le premier. $\ce{HPO4^2-}$ domine seulement au-dessus de 7,20.

**Référence manuel** : acides-bases-ph-polyacides

---

---
id: q-acide-polyprotique-symbo-ana-002
concept: acide-polyprotique
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: ana
misconception: polyacides--ampholyte-ph-depend-de-c
date_validation: 2026-11-10
statut: validated
---

**Question**
Deux élèves titrent de l'acide carbonique $\ce{H2CO3}$, l'un à 0,10 mol/L, l'autre à 0,010 mol/L (p$K_{a1} = 6{,}35$ ; p$K_{a2} = 10{,}25$). Que prévoit-on pour le pH à la première équivalence ?

**Options**
- A. Environ 8,3 dans les deux cas, car la demi-somme des p$K_a$ ne dépend pas de la concentration.
- B. Un pH plus élevé pour la solution à 0,010 mol/L, car la dilution rend le milieu plus basique.
- C. Un pH inférieur d'une unité pour la solution à 0,010 mol/L, car $[\ce{H3O+}]$ est proportionnelle à la concentration.
- D. Un pH égal à 6,35 dans les deux cas, car l'espèce présente à cet instant impose le pH du premier couple.

**Réponse correcte** : A

**Feedback correct**
À la première équivalence, l'espèce majoritaire est l'ampholyte $\ce{HCO3-}$. Son pH vaut la demi-somme des p$K_a$ des deux couples, soit 8,30, quelle que soit la concentration (tant qu'elle reste assez élevée et les p$K_a$ assez éloignés).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La dilution ne modifie pas le pH d'un ampholyte : la demi-somme des p$K_a$ ne contient pas la concentration.
- Si C : Ce raisonnement convient à un acide fort. Pour un ampholyte, $[\ce{H3O+}]$ ne dépend pas de la concentration, car le gain et la perte de protons se compensent.
- Si D : Le pH de 6,35 est le p$K_{a1}$, atteint à la demi-équivalence, non à l'équivalence. À l'équivalence, le couple $\ce{HCO3-}/\ce{CO3^2-}$ intervient aussi.

**Référence manuel** : acides-bases-ph-polyacides

---

---
id: q-acide-polyprotique-symbo-eva-001
concept: acide-polyprotique
sous-partie: 13C
chapitre: acides-bases-ph
niveau: OS
r1: symbo
type: eva
misconception: polyacides--deuxieme-proton-aussi-facile
date_validation: 2026-11-10
statut: validated
---

**Question**
Un élève affirme : « Les protons de l'acide phosphorique sont tous cédés avec la même facilité ; il n'y a donc qu'un seul p$K_a$ à connaître pour cet acide. » Que penser de cette affirmation ?

**Options**
- A. Elle est fausse : chaque proton a son propre p$K_a$, de plus en plus élevé (2,12 ; 7,20 ; 12,37).
- B. Elle est exacte : tous les protons d'un même acide ont la même aptitude à être cédés, car ils sont portés par la même molécule.
- C. Elle est fausse : le deuxième proton est plus facile à arracher que le premier, car la molécule est déjà partiellement dissociée.
- D. Elle est exacte : le p$K_a$ de l'acide est celui du premier proton, les autres protons étant toujours cédés ensuite intégralement.

**Réponse correcte** : A

**Feedback correct**
Arracher un proton à un ion déjà chargé négativement est plus difficile : $K_{a1} > K_{a2} > K_{a3}$, donc p$K_{a1} < \text{p}K_{a2} < \text{p}K_{a3}$. Chaque couple a sa propre constante.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Les protons ne sont pas équivalents : une fois un proton cédé, la charge négative de l'ion retient mieux le suivant.
- Si C : C'est l'inverse : la charge négative de l'ion formé retient le proton suivant, qui est donc plus difficile à céder (p$K_{a2}$ supérieur à p$K_{a1}$).
- Si D : Les protons suivants ne sont pas cédés intégralement : $\ce{H2PO4-}$ et $\ce{HPO4^2-}$ sont des acides faibles (p$K_a$ de 7,20 et 12,37).

**Référence manuel** : acides-bases-ph-polyacides

---

