# Banque de questions — Chapitre 09
# Thermochimie 2 — entropie et enthalpie libre
# Slug : thermochimie-2

_Projet-Balmer / Balmer-Cloud — Généré le 2026-11-08_
_Validée par LUM le 2026-11-08 après relecture de l'échantillon (statut validated)._

---

<!-- LÉGENDE
Niveau R1 : macro = macroscopique | parti = particulaire | symbo = symbolique
Niveau    : sou = se souvenir | com = comprendre | app = appliquer | ana = analyser | eva = évaluer (Anderson & Krathwohl, 2001)
Statut    : validated | rejected | to_fix
Niveau    : OS (chapitre entier, voir toc.yaml)
-->

---

---
id: q-energie-activation-symbo-sou-001
concept: energie-activation
sous-partie: 9F
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
misconception: second-principe--spontane-egal-rapide
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle grandeur contrôle la vitesse d'une réaction, à la différence de $\Delta_rG^\circ$ qui renseigne sur le caractère favorable et sur $K$ ?

**Options**
- A. L'énergie d'activation $E_a$ (hauteur de la barrière)
- B. L'enthalpie de réaction $\Delta_rH^\circ$
- C. La constante d'équilibre $K$
- D. L'entropie standard de réaction $\Delta_rS^\circ$

**Réponse correcte** : A

**Feedback correct**
$E_a$ mesure la barrière à franchir ; elle fixe la vitesse (via la loi d'Arrhenius $k=A\,e^{-E_a/(RT)}$, étudiée au chapitre *Vitesse de réaction*), alors que $\Delta_rG^\circ$ et $K$ décrivent l'équilibre.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $\Delta_rH^\circ$ est un bilan énergétique entre réactifs et produits, pas une barrière : une réaction très exothermique peut être très lente.
- Si C : $K$ décrit la composition à l'équilibre, pas le temps nécessaire pour l'atteindre.
- Si D : $\Delta_rS^\circ$ intervient dans $\Delta_rG^\circ$, donc dans le caractère favorable, pas dans la vitesse.

**Référence manuel** : thermochimie-2-energie-activation

---

---
id: q-energie-activation-macro-com-002
concept: energie-activation
sous-partie: 9F
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
misconception: second-principe--spontane-egal-rapide
date_validation: 2026-11-07
statut: validated
---

**Question**
Un mélange de $\ce{H2}$ et de $\ce{O2}$ reste inerte à $25\,^\circ$C, alors que $\Delta_rG^\circ=-237$ kJ·mol⁻¹. Quelle explication est correcte ?

**Options**
- A. La réaction est favorable mais sa barrière est élevée : à $25\,^\circ$C presque aucune collision n'est assez énergétique
- B. La réaction est en réalité défavorable à $25\,^\circ$C, malgré la valeur de $\Delta_rG^\circ$ indiquée
- C. $\Delta_rG^\circ$ ne s'applique qu'à haute température, donc il n'y a aucune réaction à $25\,^\circ$C
- D. Le mélange est déjà à l'équilibre à $25\,^\circ$C, donc plus aucune réaction n'est possible

**Réponse correcte** : A

**Feedback correct**
Favorable ne veut pas dire rapide. Une étincelle ou un catalyseur de platine permettent de franchir la barrière : la réaction se déroule alors presque totalement.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Avec $\Delta_rG^\circ=-237$ kJ·mol⁻¹, la réaction est très favorable ($K\approx10^{41}$).
- Si C : $\Delta_rG^\circ$ est défini à $298$ K : il décrit bien la situation à $25\,^\circ$C.
- Si D : À l'équilibre il ne resterait pratiquement que de l'eau, pas un mélange $\ce{H2}$/$\ce{O2}$.

**Référence manuel** : thermochimie-2-energie-activation

---

---
id: q-energie-activation-symbo-app-003
concept: energie-activation
sous-partie: 9F
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
À $298$ K, le facteur $e^{-E_a/(RT)}$ mesure la fraction des collisions assez énergétiques. De quel facteur est-il plus petit pour $E_a=150$ kJ·mol⁻¹ que pour $E_a=50$ kJ·mol⁻¹ ?

**Options**
- A. Environ $3\times10^{17}$
- B. Environ $3$ (rapport $150/50$)
- C. Environ $4\times10^{8}$ (la racine du bon facteur)
- D. Environ $1\times10^{-18}$ (facteur inversé)

**Réponse correcte** : A

**Feedback correct**
$e^{-50\,000/(8{,}314\times298)}\approx2\times10^{-9}$ et $e^{-150\,000/(8{,}314\times298)}\approx5\times10^{-27}$ : le rapport vaut $e^{100\,000/(8{,}314\times298)}=e^{40{,}4}\approx3\times10^{17}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $E_a$ est dans l'exposant : un rapport de $3$ sur $E_a$ donne un facteur exponentiel.
- Si C : On a divisé l'exposant par deux (par exemple en prenant $n=2$ ou en oubliant un facteur $2$) : le résultat est la racine du bon facteur.
- Si D : Le facteur est plus petit pour la plus haute barrière : le rapport demandé est supérieur à $1$.

**Référence manuel** : thermochimie-2-energie-activation

---

---
id: q-energie-activation-symbo-ana-301
concept: energie-activation
sous-partie: 9F
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--spontane-egal-rapide
date_validation: 2026-11-07
statut: validated
---

**Question**
À $298$ K : réaction A, $\Delta_rG^\circ=-50$ kJ·mol⁻¹ et $E_a=30$ kJ·mol⁻¹ ; réaction B, $\Delta_rG^\circ=-200$ kJ·mol⁻¹ et $E_a=180$ kJ·mol⁻¹ (même facteur $A$). Quelles affirmations sont correctes ?

**Options**
- A. B est plus favorable thermodynamiquement que A ($K$ plus grande)
- B. A est plus rapide que B à $298$ K ; le facteur $e^{-E_a/(RT)}$ vaut environ $5{,}5\times10^{-6}$ pour A et $3\times10^{-32}$ pour B
- C. B est plus rapide que A, car son $\Delta_rG^\circ$ est plus négatif
- D. A est moins favorable que B, donc A ne se produit pas

**Réponse correcte** : A, B

**Feedback correct**
$K$ se lit sur $\Delta_rG^\circ$ ; la vitesse se lit sur $E_a$. A a $e^{-30\,000/(8{,}314\times298)}=e^{-12{,}1}\approx5{,}5\times10^{-6}$, B a $e^{-180\,000/(8{,}314\times298)}=e^{-72{,}7}\approx3\times10^{-32}$ : B est extrêmement lente à $298$ K malgré son $\Delta_rG^\circ$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : La vitesse n'est pas contrôlée par $\Delta_rG^\circ$ mais par la barrière.
- Si D : A est favorable ($\Delta_rG^\circ<0$) : « moins favorable » ne veut pas dire « défavorable », et sa barrière est basse.

**Référence manuel** : thermochimie-2-energie-activation

---

---
id: q-energie-activation-symbo-ana-302
concept: energie-activation
sous-partie: 9F
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--spontane-egal-rapide
date_validation: 2026-11-07
statut: validated
---

**Question**
La synthèse de l'ammoniac est exothermique ; $K$ diminue quand $T$ augmente, mais la réaction est trop lente à basse température. Quelles affirmations sont correctes ?

**Options**
- A. Chauffer défavorise les produits à l'équilibre ($K$ diminue) tout en accélérant la réaction
- B. On choisit une température intermédiaire (avec un catalyseur et une pression élevée) comme compromis entre thermodynamique et vitesse
- C. Il suffit de refroidir au maximum, car $\Delta_rG^\circ$ plus négatif rend la réaction plus rapide
- D. Chauffer augmente $K$ et la vitesse : on travaille à la température la plus haute possible

**Réponse correcte** : A, B

**Feedback correct**
La thermodynamique ($K$) demande de refroidir ; la cinétique demande de chauffer. Le procédé industriel (environ $450\,^\circ$C) est un compromis ; un catalyseur et la pression compensent.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Un $\Delta_rG^\circ$ plus négatif ne rend pas la réaction plus rapide : à basse température, la barrière n'est presque jamais franchie.
- Si D : Pour une réaction exothermique, chauffer fait diminuer $K$ : le rendement à l'équilibre baisse.

**Référence manuel** : thermochimie-2-energie-activation

---

---
id: q-energie-activation-symbo-eva-303
concept: energie-activation
sous-partie: 9F
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: energie-activation--exothermique-egale-barriere-basse
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « Cette réaction est très exothermique ($\Delta_rH^\circ=-800$ kJ·mol⁻¹), donc sa barrière d'activation est faible et elle sera rapide. » Comment juger cette phrase ?

**Options**
- A. Fausse : la barrière et $\Delta_rH^\circ$ sont indépendantes ; une combustion très exothermique peut avoir une barrière élevée
- B. Correcte : plus une réaction libère d'énergie, plus sa barrière est basse
- C. Correcte : l'énergie libérée est utilisée pour franchir la barrière, donc elle ne peut pas être élevée
- D. Fausse : une réaction exothermique a toujours une barrière plus haute qu'une réaction endothermique

**Réponse correcte** : A

**Feedback correct**
La barrière se mesure des réactifs au sommet ; l'exothermie compare réactifs et produits. Le méthane brûle avec $\Delta_rH^\circ=-891$ kJ·mol⁻¹, mais il ne s'enflamme pas seul : il faut une amorce.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Aucune loi générale ne relie les deux : ce sont deux lectures différentes du même profil.
- Si C : L'énergie libérée à la fin du chemin ne réduit pas la hauteur de la barrière à gravir au début.
- Si D : Il n'existe pas non plus de lien inverse : les deux grandeurs sont indépendantes.

**Référence manuel** : thermochimie-2-energie-activation

---

---
id: q-energie-activation-symbo-eva-304
concept: energie-activation
sous-partie: 9F
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: second-principe--spontane-egal-rapide
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « $\Delta_rG^\circ=-500$ kJ·mol⁻¹ : cette réaction est tellement favorable qu'elle sera instantanée. » Comment juger cette phrase ?

**Options**
- A. Fausse : $\Delta_rG^\circ$ indique le sens et l'ampleur, pas la vitesse ; la barrière d'activation peut rendre la réaction très lente
- B. Correcte : plus $\Delta_rG^\circ$ est négatif, plus la réaction est rapide
- C. Correcte : $K$ est énorme, donc l'équilibre est atteint immédiatement
- D. Fausse : une réaction aussi favorable n'a jamais besoin d'être amorcée, mais elle n'est pas instantanée pour autant

**Réponse correcte** : A

**Feedback correct**
Le propane ($-2077$ kJ·mol⁻¹), le mélange $\ce{H2}$/$\ce{O2}$ ($-237$ kJ·mol⁻¹) et le diamant se transformant en graphite montrent que « très favorable » peut rimer avec « très lent » à température ambiante.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Aucune relation ne lie la valeur de $\Delta_rG^\circ$ à la vitesse : cette dernière dépend de $E_a$.
- Si C : Une grande valeur de $K$ dit où va l'équilibre, pas en combien de temps on l'atteint.
- Si D : Beaucoup de réactions très favorables ont besoin d'une amorce (étincelle, flamme, catalyseur).

**Référence manuel** : thermochimie-2-energie-activation

---

---
id: q-entropie-reaction-qualitative-macro-com-001
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Quel est le signe attendu de $\Delta_rS$ pour $\ce{CaCO3(s) -> CaO(s) + CO2(g)}$ ?

**Options**
- A. Positif : la réaction libère un gaz à partir d'un solide, la matière se disperse
- B. Négatif : un solide se transforme en deux espèces, ce qui rend le système plus ordonné
- C. Nul : le nombre d'atomes de chaque élément est conservé dans l'équation
- D. Impossible à prévoir sans connaître les valeurs de $\Delta_rH$ et de la température

**Réponse correcte** : A

**Feedback correct**
Apparition d'un gaz ($\ce{CO2}$) : $\Delta_rS^\circ = 38 + 214 - 92 = +160\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Deux espèces ne sont pas « plus ordonnées » : le gaz formé disperse bien plus la matière que le solide initial.
- Si C : La conservation des atomes ne dit rien sur la dispersion : l'entropie ne se conserve pas.
- Si D : Le signe de $\Delta_rS$ se prévoit par les états physiques, sans $\Delta_rH$ ni $T$.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-macro-com-002
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Quel est le signe attendu de $\Delta_rS$ pour $\ce{2H2(g) + O2(g) -> 2H2O(l)}$ ?

**Options**
- A. Négatif : trois moles de gaz donnent un liquide, la matière se concentre fortement
- B. Positif : deux produits remplacent trois réactifs, donc le système gagne en désordre
- C. Nul : la réaction est exothermique, elle n'a donc pas d'effet sur l'entropie
- D. Positif : toute réaction exothermique crée de l'entropie dans le système lui-même

**Réponse correcte** : A

**Feedback correct**
Trois moles de gaz disparaissent au profit d'un liquide : $\Delta_rS^\circ = 2\times70 - 2\times131 - 205 = -327\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Les réactifs sont gazeux et les produits liquides : l'entropie baisse, quel que soit le nombre d'espèces.
- Si C : L'exothermicité fixe $\Delta S_{\text{ext}}$, pas $\Delta_rS$ du système.
- Si D : Une réaction exothermique augmente l'entropie du milieu, pas forcément celle du système (ici elle baisse).

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-com-003
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: com
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi $\ce{N2O4(g) -> 2NO2(g)}$ a-t-elle un $\Delta_rS$ positif ?

**Options**
- A. Le nombre de moles de gaz double : les particules disposent de plus de façons de se répartir
- B. Le nombre d'atomes augmente au cours de la réaction, ce qui accroît le nombre de microétats
- C. La réaction est endothermique, et toute réaction endothermique a un $\Delta S$ positif
- D. Les molécules $\ce{NO2}$ sont plus lourdes que $\ce{N2O4}$, d'où une entropie plus grande

**Réponse correcte** : A

**Feedback correct**
$\Delta_rS^\circ = 2\times240 - 304 = +176\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ (avec $S^\circ(\ce{N2O4}) = 304$ donnée de l'énoncé) : une mole de gaz devient deux.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le nombre d'atomes est conservé dans toute équation.
- Si C : L'endothermicité n'est pas la cause : c'est le nombre de particules gazeuses qui compte.
- Si D : $\ce{NO2}$ est plus léger par molécule ($46 < 92$ g·mol⁻¹) ; la masse n'est pas l'argument.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-com-004
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: com
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Dans $\ce{2H2(g) + O2(g) -> 2H2O(l)}$, quelle justification de $\Delta_rS < 0$ est la bonne ?

**Options**
- A. Les trois moles de gaz disparaissent : les particules passent d'un grand volume accessible à une phase condensée
- B. Le nombre de molécules passe de 3 à 2, donc il y en a moins, quel que soit leur état physique
- C. Le système perd de l'énergie sous forme de chaleur, ce qui diminue sa dispersion d'énergie interne
- D. L'eau liquide est plus dense que les gaz de départ, donc elle est plus « en désordre »

**Réponse correcte** : A

**Feedback correct**
Ce qui compte, c'est le nombre de moles **de gaz** : ici de 3 à 0. Un résultat correct avec un mauvais argument (3 → 2 molécules) ne tient plus pour $\ce{N2O4 -> 2NO2}$ (1 → 2 molécules, états identiques).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Compter les molécules sans distinguer les états conduit à des erreurs, par exemple pour $\ce{CaCO3 -> CaO + CO2}$.
- Si C : La perte d'énergie du système est une affaire d'enthalpie ; l'argument entropique porte sur le nombre de microétats.
- Si D : Densité plus élevée = moins de volume accessible = moins de microétats : l'argument du désordre est inversé.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-com-005
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: com
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{CO(g) + H2O(g) -> CO2(g) + H2(g)}$, le nombre de moles de gaz est inchangé (2 → 2). Que prévoit-on pour $|\Delta_rS|$ ?

**Options**
- A. Une valeur faible : sans changement du nombre de particules gazeuses, la dispersion varie peu
- B. Une valeur très élevée, car il y a quatre gaz différents au total dans la réaction
- C. Une valeur très élevée et négative, car les produits sont plus petits que les réactifs
- D. Une valeur rigoureusement nulle, puisque le nombre de moles de gaz ne change pas du tout

**Réponse correcte** : A

**Feedback correct**
$\Delta_rS^\circ = 214 + 131 - 198 - 189 = -42\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : petite par rapport aux changements de plus de $100\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ observés quand le nombre de moles de gaz varie.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le nombre de gaz différents n'est pas ce qui compte, mais la variation du nombre de moles de gaz.
- Si C : La taille des molécules joue peu, la variation du nombre de particules domine.
- Si D : La valeur n'est pas rigoureusement nulle : la règle donne un ordre de grandeur, pas une valeur exacte.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-app-006
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: app
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Quel est le signe de $\Delta_rS$ pour $\ce{N2(g) + 3H2(g) -> 2NH3(g)}$ ?

**Options**
- A. Négatif : 4 mol de gaz donnent 2 mol de gaz
- B. Positif : la réaction produit un composé hydrogéné à partir de corps simples
- C. Positif : la synthèse est exothermique, donc elle augmente le désordre
- D. Nul : les deux membres de l'équation sont gazeux, donc l'état physique n'a pas changé

**Réponse correcte** : A

**Feedback correct**
$\Delta n_{\text{gaz}} = 2 - 4 = -2$ : $\Delta_rS^\circ = 2\times193 - 192 - 3\times131 = -199\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le fait de produire un composé n'indique pas le signe : seul le nombre de moles de gaz compte.
- Si C : L'exothermicité n'est pas l'argument pour $\Delta_rS$ du système.
- Si D : Même état physique ne veut pas dire même entropie : le nombre de moles de gaz a changé.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-app-007
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: app
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Laquelle de ces réactions a un $\Delta_rS$ négatif ?

**Options**
- A. $\ce{2NO2(g) -> N2O4(g)}$
- B. $\ce{CaCO3(s) -> CaO(s) + CO2(g)}$
- C. $\ce{NH4Cl(s) -> NH3(g) + HCl(g)}$
- D. $\ce{H2O2(l) -> H2O(l) + 1/2 O2(g)}$

**Réponse correcte** : A

**Feedback correct**
Dans $\ce{2NO2 -> N2O4}$, le nombre de moles de gaz passe de 2 à 1 : $\Delta_rS < 0$. Les trois autres produisent du gaz à partir de phases condensées.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La libération de $\ce{CO2}$ gazeux augmente l'entropie.
- Si C : La formation de deux gaz à partir d'un solide augmente l'entropie.
- Si D : La libération de dioxygène à partir d'un liquide augmente l'entropie.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-app-008
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: app
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Quel est le signe attendu de $\Delta_rS$ pour la dissolution $\ce{NaCl(s) -> Na^+(aq) + Cl^-(aq)}$ ?

**Options**
- A. Positif : les ions du cristal, ordonné, se dispersent dans la solution
- B. Négatif : les ions sont entourés de molécules d'eau, donc plus ordonnés que dans le cristal
- C. Nul : le nombre d'atomes est le même avant et après la dissolution
- D. Négatif : toute dissolution endothermique diminue l'entropie du système

**Réponse correcte** : A

**Feedback correct**
Un cristal passe en ions mobiles dans l'eau : la dispersion de la matière l'emporte sur l'organisation locale de l'eau autour des ions pour NaCl.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : L'hydratation ordonne un peu l'eau mais la dispersion des ions est le terme dominant ici (NaCl, cation et anion à faible charge).
- Si C : Le nombre d'atomes ne dit rien du signe de $\Delta_rS$.
- Si D : Une dissolution endothermique peut avoir $\Delta S>0$ (c'est même la condition pour être thermodynamiquement favorable (spontanée)).

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-ana-301
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: ana
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Deux réactions sans variation du nombre de moles de gaz sont étudiées : $\ce{Zn(s) + Cu^{2+}(aq) -> Zn^{2+}(aq) + Cu(s)}$ (aucun gaz) et $\ce{Fe2O3(s) + 3H2(g) -> 2Fe(s) + 3H2O(g)}$ (3 mol gaz → 3 mol gaz). Quelles affirmations sont correctes ?

**Options**
- A. La règle du nombre de moles de gaz ne donne qu'un ordre de grandeur « faible » ; seul un calcul avec les $S^\circ$ du tableau tranche
- B. Pour $\ce{Fe2O3}$ / $\ce{H2}$, $\Delta_rS^\circ = +141\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ n'est pas négligeable : $S^\circ(\ce{H2O,g}) = 189$ est supérieur à $S^\circ(\ce{H2,g}) = 131$
- C. Quand le nombre de moles de gaz est inchangé, $\Delta_rS$ est toujours exactement nul
- D. La réaction avec Zn et Cu²⁺ a un $\Delta_rS^\circ$ fortement positif (supérieur à $+100\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$)

**Réponse correcte** : A, B

**Feedback correct**
Zn/Cu²⁺ : $\Delta_rS^\circ = -110 + 33 - 42 - (-99) = -20\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ (faible). Fe₂O₃/H₂ : $2\times27 + 3\times189 - 87 - 3\times131 = +141\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : la règle du gaz ne suffit pas quand les molécules gazeuses diffèrent beaucoup par leur structure.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Le nombre de moles de gaz inchangé n'implique pas $\Delta_rS = 0$.
- Si D : Avec les données du tableau, $\Delta_rS^\circ(\ce{Zn/Cu^{2+}}) = -20$ : valeur faible et négative.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-ana-302
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: ana
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Classer, du plus négatif au plus positif, les trois $\Delta_rS^\circ$ : (1) $\ce{2H2(g) + O2(g) -> 2H2O(g)}$ ; (2) $\ce{2H2(g) + O2(g) -> 2H2O(l)}$ ; (3) $\ce{H2(g) + Cl2(g) -> 2HCl(g)}$.

**Options**
- A. (2) < (1) < (3)
- B. (1) < (2) < (3)
- C. (3) < (1) < (2)
- D. (2) < (3) < (1)

**Réponse correcte** : A

**Feedback correct**
(2) : 3 mol de gaz disparaissent ($-327\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$) ; (1) : 3 mol de gaz donnent 2 mol ($-89$) ; (3) : le nombre de moles de gaz est inchangé ($+20$).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Former un liquide diminue davantage l'entropie que former une vapeur : (2) est plus négatif que (1).
- Si C : (3) a le $\Delta n_{\text{gaz}}$ le plus favorable, donc la valeur la plus élevée.
- Si D : (3) n'est pas le plus négatif : c'est la seule sans diminution du nombre de moles de gaz.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-eva-303
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: eva
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève prévoit pour $\ce{Fe2O3(s) + 3H2(g) -> 2Fe(s) + 3H2O(g)}$ : « Le nombre de moles de gaz est inchangé (3 → 3), donc $\Delta_rS = 0$. » Quelle évaluation est correcte ?

**Options**
- A. Trop catégorique : la règle ne donne qu'un ordre de grandeur ; le tableau donne $+141\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. Correcte : à nombre de moles de gaz égal, $\Delta_rS$ est toujours rigoureusement nul
- C. Fausse : le signe attendu est négatif, car les solides sont produits en plus petite quantité
- D. Correcte, et le calcul avec le tableau confirme $\Delta_rS^\circ = 0$

**Réponse correcte** : A

**Feedback correct**
$\Delta_rS^\circ = 2\times27 + 3\times189 - 87 - 3\times131 = +141\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : $\ce{H2O}$ est plus complexe que $\ce{H2}$, donc plus riche en niveaux d'énergie accessibles.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La règle est une prévision qualitative ; elle ne garantit pas une valeur nulle.
- Si C : Le raisonnement sur les solides est faux : un solide a peu d'entropie, mais deux solides remplacent un solide.
- Si D : Le tableau donne $+141$, pas 0.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-qualitative-parti-eva-304
concept: entropie-reaction-qualitative
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: parti
type: eva
misconception: entropie-reaction-qualitative--compter-molecules-sans-distinguer-les-etats
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « Une réaction endothermique a toujours un $\Delta_rS$ négatif, car elle absorbe de l'énergie et se « range ». » Comment juger cette phrase ?

**Options**
- A. Fausse : la décomposition de $\ce{CaCO3}$ est endothermique ($+178$ kJ·mol⁻¹) et son $\Delta_rS$ est positif ($+160$)
- B. Vraie : absorber de l'énergie rend un système plus ordonné, ce qui fait baisser son entropie
- C. Vraie, mais seulement pour les réactions où tous les constituants sont gazeux
- D. Fausse : une réaction endothermique n'a jamais de $\Delta_rS$ défini, car elle absorbe la chaleur

**Réponse correcte** : A

**Feedback correct**
$\Delta_rH = -635 - 394 + 1207 = +178$ kJ·mol⁻¹ et $\Delta_rS^\circ = +160\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : le signe de $\Delta_rH$ et celui de $\Delta_rS$ sont indépendants.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Absorber de l'énergie augmente en général le nombre de microétats accessibles, il ne « range » pas le système.
- Si C : Même pour des réactions entre gaz, $\Delta_rH$ et $\Delta_rS$ restent indépendants (ex. $\ce{N2O4 -> 2NO2}$ : $\Delta H>0$, $\Delta S>0$).
- Si D : $\Delta_rS$ est défini pour toute réaction écrite avec des états physiques précisés.

**Référence manuel** : thermochimie-2-entropie-reaction-qualitative

---

---
id: q-entropie-reaction-symbo-sou-001
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
misconception: entropie-reaction--somme-sans-coefficients-stoechiometriques
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle expression donne l'entropie standard de réaction ?

**Options**
- A. $\Delta_rS^\circ = \sum \nu_{\text{produits}}\,S^\circ - \sum \nu_{\text{réactifs}}\,S^\circ$
- B. $\Delta_rS^\circ = \sum \nu_{\text{réactifs}}\,S^\circ - \sum \nu_{\text{produits}}\,S^\circ$
- C. $\Delta_rS^\circ = \sum S^\circ_{\text{produits}} - \sum S^\circ_{\text{réactifs}}$, sans les coefficients $\nu$
- D. $\Delta_rS^\circ = \sum \nu\,\Delta_fH^\circ_{\text{produits}} - \sum \nu\,\Delta_fH^\circ_{\text{réactifs}}$

**Réponse correcte** : A

**Feedback correct**
Comme pour $\Delta_rH^\circ$ : on retranche aux produits (pondérés par leurs coefficients) les réactifs (pondérés eux aussi).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : L'ordre est inversé : le résultat aurait le signe opposé.
- Si C : Sans pondérer par les coefficients, on ne décrit plus l'équation écrite.
- Si D : Cette expression donne $\Delta_rH^\circ$, pas $\Delta_rS^\circ$.

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-com-002
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: entropie-reaction--somme-sans-coefficients-stoechiometriques
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi multiplie-t-on chaque $S^\circ$ par le coefficient stœchiométrique dans $\Delta_rS^\circ$ ?

**Options**
- A. Parce que $\Delta_rS^\circ$ se rapporte à l'équation telle qu'elle est écrite : elle met en jeu $\nu$ moles de chaque espèce
- B. Parce que les coefficients sont des corrections liées à la température standard de 298 K
- C. Parce que l'entropie d'une espèce augmente proportionnellement à la racine de son coefficient
- D. Parce qu'il faut tenir compte du nombre d'atomes qui changent de place, pas du nombre de moles

**Réponse correcte** : A

**Feedback correct**
$S^\circ$ est une grandeur molaire : deux moles de produit contribuent deux fois plus. Écrire l'équation avec des coefficients doublés double aussi $\Delta_rS^\circ$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La température standard n'a rien à voir avec les coefficients stœchiométriques.
- Si C : Il n'y a pas de racine : la contribution est strictement proportionnelle à la quantité.
- Si D : L'entropie molaire se rapporte à des moles d'espèces, pas à des atomes isolés.

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-app-003
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: entropie-reaction--signe-produits-moins-reactifs-inverse
date_validation: 2026-11-07
statut: validated
---

**Question**
Calculer $\Delta_rS^\circ$ pour $\ce{2H2(g) + O2(g) -> 2H2O(l)}$ ($S^\circ$ : $\ce{H2}$ 131, $\ce{O2}$ 205, $\ce{H2O,l}$ 70 \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}).

**Options**
- A. $-327\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $-163{,}5\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $+327\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $-89\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_rS^\circ = 2\times70 - (2\times131 + 205) = 140 - 467 = -327\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Ce résultat correspond à une seule mole d'eau : l'équation écrite en comporte deux.
- Si C : Le signe est inversé : on retranche les réactifs aux produits.
- Si D : Ce résultat est celui de la vapeur d'eau ($S^\circ = 189$) et non du liquide.

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-app-004
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
Calculer $\Delta_rS^\circ$ pour $\ce{N2(g) + 3H2(g) -> 2NH3(g)}$ ($S^\circ$ : $\ce{N2}$ 192, $\ce{H2}$ 131, $\ce{NH3}$ 193 \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}).

**Options**
- A. $-199\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $+63\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $+199\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $+193\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_rS^\circ = 2\times193 - (192 + 3\times131) = 386 - 585 = -199\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Ce résultat vient d'un coefficient oublié : $\ce{H2}$ a été compté une fois au lieu de trois, et $\ce{NH3}$ deux fois.
- Si C : Le signe est inversé : produits − réactifs.
- Si D : On a pris uniquement $S^\circ(\ce{NH3})$ comme si les corps simples avaient $S^\circ=0$.

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-app-005
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: entropie-reaction--somme-sans-coefficients-stoechiometriques
date_validation: 2026-11-07
statut: validated
---

**Question**
Calculer $\Delta_rS^\circ$ pour la thermite $\ce{2Al(s) + Fe2O3(s) -> Al2O3(s) + 2Fe(s)}$ ($S^\circ$ : Al 28, $\ce{Fe2O3}$ 87, $\ce{Al2O3}$ 51, Fe 27 \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}).

**Options**
- A. $-38\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $+38\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $-10\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $-65\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_rS^\circ = (51 + 2\times27) - (2\times28 + 87) = 105 - 143 = -38\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Aucun gaz : variation faible.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : on retranche l'entropie des réactifs.
- Si C : Le coefficient 2 de Al a été oublié dans la somme des réactifs.
- Si D : Le coefficient 2 de Fe a été oublié dans la somme des produits.

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-app-006
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: entropie-reaction--signe-produits-moins-reactifs-inverse
date_validation: 2026-11-07
statut: validated
---

**Question**
Calculer $\Delta_rS^\circ$ pour $\ce{C3H8(g) + 5O2(g) -> 3CO2(g) + 4H2O(g)}$ ($S^\circ$ : $\ce{C3H8}$ 270, $\ce{O2}$ 205, $\ce{CO2}$ 214, $\ce{H2O,g}$ 189 \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}).

**Options**
- A. $+103\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $-103\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $+923\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $-373\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_rS^\circ = (3\times214 + 4\times189) - (270 + 5\times205) = 1398 - 1295 = +103\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : 6 mol de gaz → 7 mol de gaz.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : produits − réactifs.
- Si C : Le coefficient 5 de $\ce{O2}$ a été oublié : 1398 − 475 = 923.
- Si D : C'est le résultat avec de l'eau **liquide** ($S^\circ = 70$), non gazeuse.

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-app-007
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: entropie-reaction--signe-produits-moins-reactifs-inverse
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{2H2(g) + O2(g) -> 2H2O(l)}$ à 298 K, $\Delta_rH^\circ = -572$ kJ et $\Delta_rS^\circ = -327\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelle est l'entropie créée ?

**Options**
- A. $S_{\text{créée}} \approx +1{,}59 \times 10^{3}\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $S_{\text{créée}} = -327\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $S_{\text{créée}} \approx -2{,}25 \times 10^{3}\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $S_{\text{créée}} \approx +1{,}92 \times 10^{3}\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$\Delta S_{\text{ext}} = +572\,000/298 \approx +1{,}92 \times 10^{3}$ ; $S_{\text{créée}} = -327 + 1\,919 \approx +1{,}59 \times 10^{3}\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : la formation de l'eau est très favorable thermodynamiquement (spontanée).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est $\Delta_rS^\circ$ du système seul : il faut ajouter $\Delta S_{\text{ext}} = -\Delta H/T$.
- Si C : Le signe de $\Delta S_{\text{ext}}$ est inversé : le milieu reçoit de la chaleur, son entropie augmente.
- Si D : C'est $\Delta S_{\text{ext}}$ seul : il faut ajouter $\Delta_rS^\circ$ du système (négatif).

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-ana-301
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--entropie-du-systeme-seule-decide
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la thermite à 298 K, $\Delta_rH^\circ = -852$ kJ et $\Delta_rS^\circ = -38\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelles affirmations sont correctes ?

**Options**
- A. Le milieu gagne environ $2\,859\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ d'entropie : $\Delta S_{\text{ext}} = 852\,000/298$
- B. L'entropie créée vaut environ $+2\,821\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : la réaction est thermodynamiquement favorable (spontanée) malgré $\Delta_rS^\circ < 0$
- C. Comme $\Delta_rS^\circ < 0$, la réaction ne peut pas être favorable à 298 K
- D. L'entropie du milieu diminue, puisque la réaction libère de l'énergie

**Réponse correcte** : A, B

**Feedback correct**
$S_{\text{créée}} = -38 + 2\,859 \approx +2\,821\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : le terme du milieu domine très largement ; la thermite démarre difficilement (cinétique) mais est très favorable (thermodynamique).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : $\Delta_rS^\circ$ seul ne décide pas : le milieu compense largement.
- Si D : Une réaction exothermique fournit de la chaleur au milieu : son entropie augmente ($\Delta S_{\text{ext}} = -\Delta H/T > 0$).

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-ana-302
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--entropie-du-systeme-seule-decide
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{N2 + 3H2 -> 2NH3}$ ($\Delta_rH^\circ = -92$ kJ ; $\Delta_rS^\circ = -199\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$, supposés constants), comparer 298 K et 500 K. Quelles affirmations sont correctes ?

**Options**
- A. À 500 K, $\Delta S_{\text{ext}} = +184\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : le milieu gagne moins d'entropie qu'à 298 K
- B. À 500 K, $S_{\text{créée}} \approx -15\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : la synthèse n'est plus thermodynamiquement favorable dans les conditions standard
- C. $S_{\text{créée}}$ ne dépend pas de la température, car $\Delta_rH$ et $\Delta_rS$ sont des valeurs tabulées
- D. Quand la température augmente, $\Delta S_{\text{ext}}$ augmente aussi, ce qui rend la réaction plus favorable

**Réponse correcte** : A, B

**Feedback correct**
$S_{\text{créée}}(T) = -199 + 92\,000/T$ : $+110$ à 298 K, $-15$ à 500 K ; elle s'annule vers 462 K.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Seuls $\Delta_rH$ et $\Delta_rS$ sont (à peu près) constants ; $\Delta S_{\text{ext}} = -\Delta H/T$ dépend de $T$.
- Si D : $\Delta S_{\text{ext}} = 92\,000/T$ **diminue** quand $T$ augmente : un même transfert de chaleur crée moins d'entropie dans un milieu plus chaud.

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-eva-303
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: entropie-reaction--signe-produits-moins-reactifs-inverse
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève calcule, pour $\ce{CaCO3(s) -> CaO(s) + CO2(g)}$ : « $\Delta_rS^\circ = 92 - (38 + 214) = -160\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$, donc la décomposition diminue l'entropie ». Quelle évaluation est correcte ?

**Options**
- A. Produits et réactifs sont inversés : $\Delta_rS^\circ = +160\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ (un gaz apparaît)
- B. Le calcul est correct : la décomposition d'un solide en deux espèces rend le système plus ordonné
- C. Le calcul est correct mais $\Delta_rS^\circ$ doit être positive car la réaction est endothermique
- D. Le calcul est faux parce qu'il ne tient pas compte de la température, qui fixe le signe de $\Delta_rS^\circ$

**Réponse correcte** : A

**Feedback correct**
On retranche toujours les réactifs aux produits : $38 + 214 - 92 = +160\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$, en accord avec la règle qualitative (production d'un gaz).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Un gaz apparaît : c'est l'inverse du « rangement ».
- Si C : L'endothermicité ne fixe pas le signe de $\Delta_rS^\circ$ ; le calcul correct donne +160.
- Si D : $\Delta_rS^\circ$ est ici un résultat de tableau à 298 K ; la température n'en change pas le signe.

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-eva-304
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: second-principe--entropie-du-systeme-seule-decide
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève dit : « L'évaporation de l'eau a $\Delta_rS^\circ = +119\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$, positive, donc elle est thermodynamiquement favorable (spontanée) à 25 °C sous 1 bar. » Quelle évaluation est correcte ?

**Options**
- A. Insuffisant : $\Delta_rH^\circ = +44$ kJ donne $\Delta S_{\text{ext}} = -148$, donc $S_{\text{créée}} \approx -29\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ sous 1 bar de vapeur
- B. Correct : un $\Delta_rS^\circ$ positif suffit à garantir le caractère favorable à toute température
- C. Correct : l'enthalpie de vaporisation n'intervient pas dans le critère thermodynamique
- D. Insuffisant : il faudrait aussi connaître la vitesse d'évaporation avant de conclure sur le caractère favorable

**Réponse correcte** : A

**Feedback correct**
$S_{\text{créée}} = \Delta_rS^\circ - \Delta_rH^\circ/T = 119 - 44\,000/298 \approx -29\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : négative sous les conditions standard (pression de vapeur de 1 bar). L'eau s'évapore tout de même dans l'air non saturé, où la pression partielle est bien plus faible.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de $\Delta_rS^\circ$ seul ne garantit rien : il faut y ajouter $\Delta S_{\text{ext}}$.
- Si C : $\Delta_rH$ intervient via $\Delta S_{\text{ext}} = -\Delta H/T$.
- Si D : Le caractère favorable thermodynamique ne dépend pas de la vitesse : c'est la confusion « favorable = rapide ».

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-reaction-symbo-eva-305
concept: entropie-reaction
sous-partie: 9B
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: entropie-reaction--somme-sans-coefficients-stoechiometriques
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « $\Delta_rS^\circ$ est une propriété de la réaction : elle vaut la même chose pour $\ce{H2 + 1/2 O2 -> H2O(l)}$ et pour $\ce{2H2 + O2 -> 2H2O(l)}$. » Comment juger cette phrase ?

**Options**
- A. Fausse : $\Delta_rS^\circ$ vaut $-163{,}5\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ pour la première équation et $-327\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ pour la seconde
- B. Vraie : l'entropie standard de réaction ne dépend pas des coefficients stœchiométriques, seulement des espèces
- C. Vraie : on exprime toujours $\Delta_rS^\circ$ par mole de dihydrogène consommé, quel que soit le coefficient
- D. Fausse, mais le facteur est $\sqrt 2$ et non 2, car les entropies ne s'additionnent pas simplement

**Réponse correcte** : A

**Feedback correct**
Une équation doublée double $\Delta_rS^\circ$ (comme $\Delta_rH^\circ$). L'unité $\text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ signifie « par mole d'avancement de l'équation telle qu'écrite ».

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Les coefficients interviennent dans la somme : ils changent le résultat.
- Si C : Il n'y a pas de normalisation implicite : on rapporte à l'équation écrite.
- Si D : Les entropies sont additives : le facteur est exactement 2.

**Référence manuel** : thermochimie-2-entropie-reaction-quantitative

---

---
id: q-entropie-symbo-sou-001
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle relation de Boltzmann relie l'entropie $S$ au nombre de microétats $W$ ?

**Options**
- A. $S = k_B \ln W$
- B. $S = k_B \cdot W$
- C. $S = \ln(k_B \cdot W)$
- D. $S = k_B / W$

**Réponse correcte** : A

**Feedback correct**
Boltzmann relie l'entropie au logarithme du nombre de microétats accessibles : $S = k_B \ln W$, avec $k_B = 1{,}38 \times 10^{-23}$ J·K⁻¹.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le lien est logarithmique : doubler $W$ ajoute $k_B\ln 2$ et non une proportionnalité.
- Si C : Le logarithme porte sur $W$ seul, multiplié ensuite par $k_B$.
- Si D : $S$ augmente avec $W$ : une division donnerait l'effet inverse.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-symbo-sou-002
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle est l'unité usuelle de l'entropie molaire standard $S^\circ$ ?

**Options**
- A. J·K⁻¹·mol⁻¹
- B. kJ·mol⁻¹
- C. J·mol⁻¹
- D. K·J⁻¹·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
L'entropie est une énergie par kelvin ($Q/T$) ; rapportée à une mole, elle s'exprime en J·K⁻¹·mol⁻¹.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est l'unité d'une enthalpie molaire : il manque la division par la température.
- Si C : Il manque la division par le kelvin : $S$ est une énergie divisée par $T$.
- Si D : L'unité est inversée : $S = Q/T$ s'exprime en J·K⁻¹.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-macro-com-003
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
date_validation: 2026-11-07
statut: validated
---

**Question**
Dans lequel de ces processus l'entropie du système augmente-t-elle ?

**Options**
- A. L'évaporation de l'eau liquide en vapeur d'eau
- B. La congélation de l'eau liquide en glace
- C. La condensation de la vapeur d'eau en gouttelettes
- D. La cristallisation de $\ce{NaCl}$ dans une solution saturée

**Réponse correcte** : A

**Feedback correct**
En passant du liquide au gaz, la matière et l'énergie se dispersent sur un volume bien plus grand : le nombre de microétats accessibles augmente fortement.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Un solide cristallin est plus ordonné que le liquide : l'entropie du système diminue.
- Si C : La condensation resserre les molécules en phase liquide : l'entropie du système diminue.
- Si D : Les ions quittent la solution pour former un cristal régulier : l'entropie du système diminue.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-parti-com-004
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: parti
type: com
misconception: entropie--entropie-egale-desordre
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi l'entropie molaire d'un gaz est-elle bien supérieure à celle du liquide correspondant ?

**Options**
- A. Les molécules et leur énergie se répartissent sur un très grand nombre de microétats, car elles occupent un volume bien plus grand
- B. Les molécules d'un gaz ont une masse plus grande que celles du liquide, donc elles portent davantage d'énergie à température égale
- C. Les gaz sont toujours plus chauds que les liquides correspondants, et l'entropie ne dépend que de la température du corps
- D. Les molécules d'un gaz ne sont pas du tout en interaction entre elles, donc leur énergie interne est nulle

**Réponse correcte** : A

**Feedback correct**
Plus de microétats accessibles ($W$ grand) signifie une entropie plus grande ($S = k_B \ln W$) : c'est la dispersion de la matière et de l'énergie qui compte.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La masse d'une molécule ne change pas à l'évaporation ; c'est la répartition spatiale et énergétique qui change.
- Si C : À une température donnée, un gaz et son liquide (à l'équilibre) ont même $T$ : l'écart d'entropie vient de la dispersion, pas de $T$.
- Si D : Les molécules d'un gaz ont de l'énergie cinétique ; ce qui compte est le nombre de façons de la répartir.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-parti-com-005
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: parti
type: com
misconception: entropie--entropie-egale-desordre
date_validation: 2026-11-07
statut: validated
---

**Question**
Un bloc de cuivre chaud touche un bloc de cuivre froid. Dans le modèle des microétats, pourquoi l'énergie passe-t-elle du chaud au froid ?

**Options**
- A. Répartie entre les deux blocs, l'énergie peut occuper bien plus de microétats que si elle restait concentrée dans le bloc chaud
- B. Parce que le bloc chaud est trop désordonné et que son énergie cherche à se ranger dans le bloc froid pour retrouver l'ordre
- C. Parce que l'énergie du bloc chaud diminue toujours quand il touche un corps froid, sans qu'il y ait d'autre raison à invoquer
- D. Parce que le bloc froid attire l'énergie du bloc chaud par une force d'attraction analogue à la gravité

**Réponse correcte** : A

**Feedback correct**
Le transfert est thermodynamiquement favorable (spontané) parce que le nombre total de microétats (donc l'entropie de l'ensemble) augmente quand l'énergie se disperse entre les deux blocs.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Ce n'est pas une question de désordre intrinsèque au bloc chaud, mais de dispersion de l'énergie sur l'ensemble.
- Si C : L'énoncé décrit le phénomène sans l'expliquer ; l'explication est entropique.
- Si D : Il n'y a pas de force d'attraction : le sens du transfert vient du comptage des microétats.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-symbo-app-006
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Une mole de gaz parfait double son volume à température constante (détente isotherme). Quelle est la variation d'entropie du gaz ?

**Options**
- A. $\Delta S = R\ln 2 \approx +5{,}76\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $\Delta S = R\ln\frac12 \approx -5{,}76\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $\Delta S = 2R \approx +16{,}6\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $\Delta S = R \approx +8{,}31\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
Pour un gaz parfait : $\Delta S = nR\ln(V_2/V_1) = 1 \times 8{,}314 \times \ln 2 = +5{,}76\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le volume augmente : la dispersion augmente, donc $\Delta S > 0$ ; le rapport $V_2/V_1$ vaut 2 et non 1/2.
- Si C : La dépendance en volume est logarithmique : le facteur est $\ln 2$ et non 2.
- Si D : Il faut multiplier par $\ln(V_2/V_1) = \ln 2$, pas seulement par $R$.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-symbo-app-007
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
La fusion de la glace à 0 °C (273,15 K) absorbe $6{,}01$ kJ·mol⁻¹. Quelle est la variation d'entropie de fusion ?

**Options**
- A. $\Delta S_{\text{fus}} \approx +22{,}0\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $\Delta S_{\text{fus}} \approx +20{,}2\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $\Delta S_{\text{fus}} \approx +1\,640\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $\Delta S_{\text{fus}} \approx +0{,}0220\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
À l'équilibre de changement d'état, $\Delta S = \Delta H/T = 6\,010/273{,}15 = +22{,}0\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La fusion à 0 °C se fait à 273,15 K, pas à 298 K (25 °C).
- Si C : On divise $\Delta H$ par $T$ ; on ne les multiplie pas.
- Si D : Il faut convertir les kJ en J : 6,01 kJ = 6 010 J.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-symbo-app-008
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
La vaporisation de l'eau à 100 °C absorbe $40{,}7$ kJ·mol⁻¹. Quelle est la variation d'entropie de vaporisation ?

**Options**
- A. $\Delta S_{\text{vap}} \approx +109\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $\Delta S_{\text{vap}} \approx +407\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $\Delta S_{\text{vap}} \approx +15\,200\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $\Delta S_{\text{vap}} \approx +0{,}109\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$T = 373{,}15$ K ; $\Delta S = 40\,700/373{,}15 \approx +109\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La température doit être en kelvin : 100 °C = 373 K (et non 100).
- Si C : On divise par $T$ ; une multiplication donne un résultat sans sens physique.
- Si D : Il faut convertir : 40,7 kJ = 40 700 J.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-symbo-ana-301
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: entropie--entropie-egale-desordre
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour l'eau, $\Delta S_{\text{fus}} \approx 22\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ et $\Delta S_{\text{vap}} \approx 109\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelles affirmations sont correctes ?

**Options**
- A. La vaporisation disperse la matière beaucoup plus que la fusion : son $\Delta S$ est environ cinq fois plus grand
- B. Le passage liquide → gaz multiplie fortement le volume accessible, alors que le passage solide → liquide le modifie peu
- C. $\Delta S_{\text{fus}} > \Delta S_{\text{vap}}$ car $\Delta H_{\text{fus}}$ est plus petit
- D. Les deux valeurs sont égales, puisque $\Delta S = \Delta H/T$ pour les deux changements d'état

**Réponse correcte** : A, B

**Feedback correct**
Le rapport $109/22 \approx 5$ traduit la différence de dispersion : la vapeur occupe un volume environ 1 600 fois plus grand que le liquide, la glace et le liquide ont des volumes voisins.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Un $\Delta H$ plus petit donne un $\Delta S$ plus petit (à $T$ comparable) : l'inégalité est inversée.
- Si D : Les deux formules sont les mêmes mais les valeurs de $\Delta H$ et $T$ diffèrent : $\Delta S$ n'est pas le même.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-parti-eva-302
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: parti
type: eva
misconception: entropie--entropie-egale-desordre
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « L'entropie mesure le désordre : une chambre en désordre a une entropie plus grande qu'une chambre rangée. » Quelles affirmations permettent d'évaluer cette phrase ?

**Options**
- A. L'aspect visuel n'est pas la grandeur mesurée : $S$ dépend du nombre de microétats accessibles à l'énergie et à la matière
- B. Réarranger des objets macroscopiques (les ranger) change l'entropie thermodynamique de façon négligeable devant celle liée à l'énergie thermique
- C. Plus un système paraît désordonné à l'œil, plus son entropie est grande
- D. L'entropie ne dépend que de la température, jamais du nombre de microétats

**Réponse correcte** : A, B

**Feedback correct**
L'image du « désordre » est utile pour les gaz mais trompeuse en général (Lambert, 2002) : c'est la dispersion de l'énergie sur les microétats, comptés par $W$, qui définit $S$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : L'apparence ne se mesure pas : elle ne détermine pas $W$.
- Si D : La température intervient, mais l'entropie est définie par $W$ ($S = k_B\ln W$).

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-symbo-eva-303
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: entropie--entropie-systeme-ne-diminue-jamais
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « L'entropie d'un système ne peut jamais diminuer. » Comment juger cette phrase ?

**Options**
- A. Fausse pour un système non isolé (ex. : la congélation) ; seule l'entropie de l'Univers ne peut pas diminuer
- B. Vraie pour tout système, qu'il soit isolé ou qu'il échange de la chaleur avec le milieu
- C. Vraie dans tous les cas, sauf pour les processus qui se déroulent en dessous de 0 °C
- D. Fausse, car l'entropie d'un système diminue toujours lorsqu'on chauffe ce système

**Réponse correcte** : A

**Feedback correct**
Le deuxième principe impose $S_{\text{créée}} \ge 0$ pour l'ensemble système + milieu. La congélation baisse $S_{\text{sys}}$ de 22,0 J·K⁻¹·mol⁻¹ tout en créant de l'entropie au total.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Un système en contact avec un milieu peut échanger de l'entropie : sa propre entropie peut décroître.
- Si C : La température de congélation n'est pas une limite de validité de la règle ; la restriction vient de l'isolement du système.
- Si D : Chauffer un corps augmente son entropie ($\int C_p\,dT/T > 0$), il ne la diminue pas.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-symbo-ana-304
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: entropie--entropie-egale-desordre
date_validation: 2026-11-07
statut: validated
---

**Question**
Deux compartiments égaux contiennent chacun 1 mol d'un gaz parfait différent, à même température et pression. On retire la paroi ; les gaz se mélangent. Quelles affirmations sont correctes ?

**Options**
- A. Chaque gaz voit son volume doubler : $\Delta S = R\ln 2 \approx 5{,}76$ J·K⁻¹ pour chacun
- B. L'entropie totale augmente d'environ $11{,}5\ \text{J}\cdot\text{K}^{-1}$
- C. L'entropie ne change pas, car la température reste constante et il n'y a pas d'échange de chaleur
- D. L'entropie totale augmente de $R\ln 2 \approx 5{,}76$ J·K⁻¹ seulement, car on ne compte le mélange qu'une fois

**Réponse correcte** : A, B

**Feedback correct**
Pour chaque gaz parfait, $\Delta S = nR\ln(V_2/V_1) = R\ln 2$. Les deux effets s'additionnent : $2R\ln 2 \approx 11{,}5$ J·K⁻¹.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : L'absence d'échange de chaleur n'implique pas $\Delta S = 0$ : l'entropie est créée par le mélange irréversible.
- Si D : Chaque gaz double son volume séparément : il faut compter les deux contributions.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-entropie-macro-com-013
concept: entropie
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Le chlorure de sodium se dissout dans l'eau de façon endothermique ($\Delta H = +4$ kJ·mol⁻¹) et pourtant elle est thermodynamiquement favorable (spontanée) à 25 °C. Quelle explication est correcte ?

**Options**
- A. La dispersion des ions dans l'eau augmente fortement l'entropie du système, ce qui l'emporte sur la baisse d'entropie du milieu ($\approx -13$ J·K⁻¹·mol⁻¹)
- B. La dissolution est en fait exothermique à 25 °C, malgré la valeur positive de $\Delta H$ qui est donnée
- C. Une enthalpie positive favorise la dissolution : plus le sel absorbe de chaleur, plus la dissolution est favorable
- D. Toute dissolution d'un composé ionique est thermodynamiquement favorable (spontanée), quelles que soient les valeurs des entropies en jeu

**Réponse correcte** : A

**Feedback correct**
Le milieu fournit 4 kJ/mol : $\Delta S_{\text{ext}} = -4\,000/298 \approx -13{,}4$ J·K⁻¹·mol⁻¹. L'entropie du système augmente plus, d'où $S_{\text{créée}} > 0$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $\Delta H > 0$ signifie sans ambiguïté une absorption de chaleur.
- Si C : Absorber de la chaleur diminue l'entropie du milieu : c'est défavorable, et c'est la hausse de $\Delta S_{\text{sys}}$ qui compense.
- Si D : Beaucoup de sels ioniques sont peu solubles (ex. $\ce{CaCO3}$) : il n'y a pas de règle générale.

**Référence manuel** : thermochimie-2-entropie

---

---
id: q-enthalpie-libre-gibbs-symbo-sou-001
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle est l'expression de l'enthalpie libre de Gibbs d'une transformation à $T$ et $P$ constantes ?

**Options**
- A. $\Delta G = \Delta H - T\,\Delta S$
- B. $\Delta G = \Delta H + T\,\Delta S$
- C. $\Delta G = \Delta S - T\,\Delta H$
- D. $\Delta G = T\,\Delta H - \Delta S$

**Réponse correcte** : A

**Feedback correct**
$\Delta G = \Delta H - T\,\Delta S$, où $\Delta H$ et $\Delta S$ sont ceux du système ; elle combine le terme énergétique et le terme entropique.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de $T\Delta S$ est négatif : une hausse d'entropie du système rend $\Delta G$ plus négative.
- Si C : Les rôles sont inversés : $\Delta H$ est le premier terme et $T\Delta S$ le second.
- Si D : L'expression est mal dimensionnée : $T\Delta H$ et $\Delta S$ n'ont pas les mêmes unités.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-sou-002
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle relation lie $\Delta G$ à l'entropie créée, à $T$ et $P$ constantes ?

**Options**
- A. $\Delta G = -T\,S_{\text{créée}}$
- B. $\Delta G = +T\,S_{\text{créée}}$
- C. $\Delta G = S_{\text{créée}}/T$
- D. $\Delta G = -S_{\text{créée}}/T$

**Réponse correcte** : A

**Feedback correct**
En multipliant $S_{\text{créée}} = \Delta S - \Delta H/T$ par $-T$, on retrouve $\Delta G = \Delta H - T\Delta S = -T\,S_{\text{créée}}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : $\Delta G < 0$ doit correspondre à $S_{\text{créée}} > 0$.
- Si C : $T$ multiplie $S_{\text{créée}}$ ; il ne la divise pas.
- Si D : Même erreur : $T$ est un facteur, pas un diviseur.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-com-003
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: enthalpie-libre-gibbs--delta-g-negatif-egal-rapide-ou-totale
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi la condition $\Delta G < 0$ équivaut-elle à une transformation thermodynamiquement favorable (spontanée) ?

**Options**
- A. Car $\Delta G = -T\,S_{\text{créée}}$ : $\Delta G < 0$ revient à $S_{\text{créée}} > 0$
- B. Parce que $\Delta G$ mesure l'énergie chimique libérée, et toute transformation favorable libère de l'énergie vers le milieu
- C. Parce que $\Delta G$ est la variation d'énergie totale de l'Univers, qui doit baisser lors d'une transformation
- D. Parce que $\Delta G < 0$ garantit que la vitesse de réaction est élevée à la température choisie

**Réponse correcte** : A

**Feedback correct**
$\Delta G$ n'est pas une nouvelle loi : c'est le critère d'entropie créée, ré-exprimé avec les seules grandeurs du système, à $T$ et $P$ constantes.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Une transformation favorable n'a pas à libérer d'énergie : la fusion de la glace en absorbe.
- Si C : L'énergie de l'Univers est conservée (premier principe) ; c'est l'entropie qui augmente.
- Si D : $\Delta G$ ne renseigne pas sur la vitesse.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-com-004
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: enthalpie-libre-gibbs--delta-g-egal-delta-g-standard
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève dit : « $\Delta_rG^\circ < 0$ signifie que la réaction est thermodynamiquement favorable (spontanée) quelle que soit la composition du mélange. » Pourquoi est-ce incorrect ?

**Options**
- A. $\Delta_rG^\circ$ vaut pour l'état standard (1 bar, corps purs) ; le critère général est $\Delta_rG$, fonction de la composition
- B. $\Delta_rG^\circ$ ne dépend pas de la température, alors que le critère thermodynamique en dépend toujours et partout
- C. $\Delta_rG^\circ$ est toujours positive, car l'état standard est précisément un état d'équilibre chimique
- D. $\Delta_rG^\circ$ a la dimension d'une entropie et ne peut donc pas servir de critère thermodynamique

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ$ est la valeur au point de départ « tout standard ». Pendant la réaction, la composition change et $\Delta_rG$ varie jusqu'à s'annuler à l'équilibre.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $\Delta_rG^\circ$ dépend de la température (par $\Delta H^\circ - T\Delta S^\circ$) ; l'erreur n'est pas là.
- Si C : L'état standard n'est pas un équilibre : $\Delta_rG^\circ$ peut être de n'importe quel signe.
- Si D : $\Delta G$ est une énergie (J ou kJ), pas une entropie.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-macro-com-005
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi la fusion de la glace est-elle thermodynamiquement favorable (spontanée) à $+10$ °C mais pas à $-10$ °C, alors que la fusion est toujours endothermique ?

**Options**
- A. Le terme $-T\,\Delta S$ ($\Delta S_{\text{fus}} > 0$) l'emporte sur $\Delta H > 0$ au-dessus de 0 °C, et plus au-dessous
- B. Parce que la fusion devient exothermique dès que la température dépasse 0 °C, ce qui la rend thermodynamiquement favorable (spontanée)
- C. Parce que l'eau liquide est plus dense que la glace, donc elle est plus stable à toute température
- D. Parce que la fusion est beaucoup plus rapide à $+10$ °C qu'à $-10$ °C, donc elle a lieu à cette température

**Réponse correcte** : A

**Feedback correct**
$\Delta G = 6\,010 - T\times22{,}0$ : à 283 K, $\Delta G \approx -219\ \text{J}\cdot\text{mol}^{-1}$ ; à 263 K, $\Delta G \approx +221\ \text{J}\cdot\text{mol}^{-1}$. Le terme entropique grandit avec $T$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La fusion absorbe de la chaleur à toute température.
- Si C : La densité n'est pas le critère de stabilité thermodynamique ; c'est $\Delta G$.
- Si D : La vitesse n'est pas le critère du sens d'évolution.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-app-006
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-de-reaction--kj-et-j-melanges
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{2H2O2(l) -> 2H2O(l) + O2(g)}$, $\Delta_rH^\circ = -196$ kJ et $\Delta_rS^\circ = +125\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelle est la valeur de $\Delta_rG^\circ$ à 298 K ?

**Options**
- A. $-233$ kJ
- B. $-159$ kJ
- C. $-196$ kJ
- D. $-37\,446$ kJ

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = -196 - 298\times0{,}125 = -196 - 37{,}3 = -233$ kJ : très favorable thermodynamiquement (spontanée) (exothermique et $\Delta S>0$, cas 1).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de $-T\Delta S$ a été inversé : $-196 + 37 = -159$.
- Si C : Le terme entropique a été oublié.
- Si D : Il faut convertir $\Delta S$ en kJ·K⁻¹ (0,125) avant de multiplier.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-app-007
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{3O2(g) -> 2O3(g)}$, $\Delta_rH^\circ = +285{,}4$ kJ et $\Delta_rS^\circ = -137\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelle est la valeur de $\Delta_rG^\circ$ à 298 K ?

**Options**
- A. $+326$ kJ
- B. $+245$ kJ
- C. $+285$ kJ
- D. $-326$ kJ

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = 285{,}4 - 298\times(-0{,}137) = 285{,}4 + 40{,}8 = +326$ kJ : la formation de l'ozone à partir de $\ce{O2}$ est très défavorable (cas 2).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de $-T\Delta S$ a été inversé.
- Si C : Le terme entropique a été oublié.
- Si D : Le signe global est inversé : réaction défavorable, $\Delta G > 0$.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-app-008
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la fusion de la glace, $\Delta H = +6\,010\ \text{J}\cdot\text{mol}^{-1}$ et $\Delta S = +22{,}0\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelle est la valeur de $\Delta G$ à $+10$ °C ?

**Options**
- A. $\approx -219\ \text{J}\cdot\text{mol}^{-1}$
- B. $\approx +219\ \text{J}\cdot\text{mol}^{-1}$
- C. $\approx +5\,790\ \text{J}\cdot\text{mol}^{-1}$
- D. $\approx -219\ \text{kJ}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$T = 283{,}15$ K : $\Delta G = 6\,010 - 283{,}15\times22{,}0 = 6\,010 - 6\,229 \approx -219\ \text{J}\cdot\text{mol}^{-1}$ : fusion thermodynamiquement favorable (spontanée).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : $T\Delta S$ dépasse $\Delta H$, donc $\Delta G < 0$.
- Si C : La température doit être en kelvin : avec $10$ au lieu de $283{,}15$, on trouverait $6\,010 - 220 = 5\,790$.
- Si D : L'ordre de grandeur est en joules, pas en kilojoules.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-ana-301
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la synthèse de l'ammoniac, $\Delta H = -92$ kJ et $\Delta S = -199\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ (supposés constants). Quelles affirmations sont correctes ?

**Options**
- A. À basse température, le terme $\Delta H$ domine : $\Delta G < 0$, la synthèse est thermodynamiquement favorable (spontanée)
- B. $\Delta G$ s'annule vers $T = 92\,000/199 \approx 462$ K ; au-dessus, la synthèse n'est plus favorable
- C. La synthèse est favorable à toute température, car elle est exothermique
- D. La synthèse n'est favorable à aucune température, car $\Delta S < 0$

**Réponse correcte** : A, B

**Feedback correct**
C'est le cas 3 du tableau ($\Delta H<0$, $\Delta S<0$) : favorable à basse température seulement. Dans l'industrie, on chauffe quand même pour la vitesse (400-500 °C), au prix d'une pression élevée.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Un terme $\Delta H<0$ ne suffit pas : $-T\Delta S = +T\times0{,}199$ grandit avec $T$.
- Si D : Un $\Delta S<0$ ne suffit pas non plus : à basse température le terme $\Delta H$ domine.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-ana-302
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
La décomposition $\ce{CaCO3(s) -> CaO(s) + CO2(g)}$ a $\Delta H = +178$ kJ et $\Delta S = +160\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ (supposés constants). Quelles affirmations sont correctes ?

**Options**
- A. À 298 K, $\Delta G \approx +130$ kJ : la décomposition est thermodynamiquement défavorable (non spontanée)
- B. Elle le devient au-dessus de $T = 178\,000/160 \approx 1\,112$ K
- C. Elle est favorable à toute température, car elle libère un gaz
- D. Elle n'est favorable à aucune température, car elle est endothermique

**Réponse correcte** : A, B

**Feedback correct**
C'est le cas 4 ($\Delta H>0$, $\Delta S>0$) : le terme $-T\Delta S$ ne compense $\Delta H$ qu'à haute température. C'est le principe du four à chaux (≈ 840 °C).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Le terme entropique favorable ne suffit pas à basse température : $\Delta H$ domine.
- Si D : L'endothermicité n'interdit pas le caractère favorable : à haute température, $-T\Delta S$ la compense.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-eva-303
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: enthalpie-libre-gibbs--delta-g-negatif-egal-rapide-ou-totale
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « $\Delta G < 0$, donc la réaction est rapide, et elle est totale. » Quelles affirmations permettent de juger cette phrase ?

**Options**
- A. $\Delta G < 0$ indique seulement que $S_{\text{créée}} > 0$ (sens d'évolution) : rien sur la vitesse
- B. Une réaction avec $\Delta G < 0$ évolue jusqu'à un équilibre où $\Delta G = 0$ ; elle n'est « totale » que si l'équilibre est très déplacé
- C. $\Delta G$ négative signifie que la réaction est instantanée
- D. $\Delta G < 0$ garantit que la réaction se poursuit jusqu'à disparition complète des réactifs

**Réponse correcte** : A, B

**Feedback correct**
Le critère $\Delta G<0$ est thermodynamique : il ne dit rien de la cinétique. À l'équilibre, $\Delta G = 0$ et les réactifs ne sont pas nécessairement épuisés.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : La vitesse relève de la cinétique (énergie d'activation).
- Si D : $\Delta G$ tend vers 0 au fil de la réaction : l'état final est un équilibre.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-gibbs-symbo-eva-304
concept: enthalpie-libre-gibbs
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « Comme $\Delta G = \Delta H - T\Delta S$, augmenter la température rend toujours $\Delta G$ plus négative. » Comment juger cette phrase ?

**Options**
- A. Fausse : seulement si $\Delta S > 0$ ; si $\Delta S < 0$ (ex. synthèse de $\ce{NH3}$), chauffer rend $\Delta G$ plus positive
- B. Vraie : $T$ multiplie toujours $\Delta S$ avec un signe moins, donc $\Delta G$ baisse avec $T$
- C. Vraie pour les réactions exothermiques seulement, quelle que soit la valeur de $\Delta S$
- D. Fausse : $\Delta G$ ne dépend pas de $T$, seuls $\Delta H$ et $\Delta S$ en dépendent

**Réponse correcte** : A

**Feedback correct**
La pente de $\Delta G(T)$ vaut $-\Delta S$ : positive si $\Delta S<0$ (NH₃ : $\Delta G$ passe de $-33$ kJ à 298 K à $+7{,}5$ kJ à 500 K), négative si $\Delta S>0$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de la variation dépend du signe de $\Delta S$ : c'est le point que l'énoncé néglige.
- Si C : L'exothermicité n'est pas le critère pour la pente de $\Delta G(T)$.
- Si D : $\Delta G = \Delta H - T\Delta S$ dépend explicitement de $T$.

**Référence manuel** : thermochimie-2-enthalpie-libre

---

---
id: q-enthalpie-libre-de-reaction-symbo-sou-001
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
misconception: enthalpie-libre-de-reaction--coefficients-oublies-dans-la-somme
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle expression donne l'enthalpie libre standard de réaction à partir des enthalpies libres de formation ?

**Options**
- A. $\Delta_rG^\circ = \sum \nu_{\text{produits}}\,\Delta_fG^\circ - \sum \nu_{\text{réactifs}}\,\Delta_fG^\circ$
- B. $\Delta_rG^\circ = \sum \nu_{\text{réactifs}}\,\Delta_fG^\circ - \sum \nu_{\text{produits}}\,\Delta_fG^\circ$
- C. $\Delta_rG^\circ = \sum \Delta_fG^\circ_{\text{produits}} - \sum \Delta_fG^\circ_{\text{réactifs}}$, sans pondérer par $\nu$
- D. $\Delta_rG^\circ = \sum \nu\,\Delta_fG^\circ_{\text{produits}} + \sum \nu\,\Delta_fG^\circ_{\text{réactifs}}$

**Réponse correcte** : A

**Feedback correct**
Même structure que pour $\Delta_rH^\circ$ : produits moins réactifs, chaque terme pondéré par son coefficient stœchiométrique.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : L'ordre est inversé : le résultat aurait le signe opposé.
- Si C : Sans les coefficients, on ne décrit plus l'équation écrite.
- Si D : On retranche les réactifs, on ne les additionne pas.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-sou-002
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle est la valeur de $\Delta_fG^\circ$ d'un corps simple dans son état de référence, par exemple $\ce{O2(g)}$ ou $\ce{Fe(s)}$ ?

**Options**
- A. 0 kJ·mol⁻¹, par convention
- B. Une valeur positive, égale à $T\,S^\circ$
- C. Une valeur négative, égale à $-T\,S^\circ$
- D. La valeur de son enthalpie de fusion

**Réponse correcte** : A

**Feedback correct**
Comme pour $\Delta_fH^\circ$, la référence est choisie sur les corps simples dans leur état stable : leur enthalpie libre de formation est nulle par définition.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le terme $T\,S^\circ$ n'intervient pas : la formation d'un corps simple à partir de lui-même ne change rien.
- Si C : Même remarque : aucun terme entropique ne s'ajoute à la définition.
- Si D : L'enthalpie de fusion n'a pas de rapport avec la définition de $\Delta_fG^\circ$.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-com-003
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la combustion de l'éthane, les deux voies de calcul (par $\Delta_fG^\circ$ ou par $\Delta H - T\Delta S$) donnent $-1\,467$ et $-1\,470$ kJ·mol⁻¹. Comment interpréter cet écart ?

**Options**
- A. Il reflète les arrondis des deux tables de données ; les deux voies décrivent la même grandeur
- B. L'une des deux voies est erronée et il faut recommencer le calcul avec soin
- C. Il montre que $\Delta G$ n'est pas une fonction d'état, donc dépend de la voie
- D. Il vient de la température, qui n'est pas la même dans les deux calculs

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ$ est une fonction d'état : les deux voies doivent coïncider ; l'écart de 3 kJ sur 1 470 (0,2 %) vient des valeurs arrondies du tableau.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Les deux calculs sont corrects ; la différence vient des données.
- Si C : $G$ est bien une fonction d'état : l'écart n'est pas physique.
- Si D : Les deux calculs sont faits à 298 K.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-com-004
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: enthalpie-libre-de-reaction--kj-et-j-melanges
date_validation: 2026-11-07
statut: validated
---

**Question**
Dans la voie $\Delta_rG^\circ = \Delta_rH^\circ - T\Delta_rS^\circ$, pourquoi faut-il convertir $\Delta_rS^\circ$ de J·K⁻¹ en kJ·K⁻¹ ?

**Options**
- A. Parce que $\Delta_rH^\circ$ est en kJ : les deux termes doivent avoir la même unité avant d'être soustraits
- B. Parce que le kelvin n'est pas une unité du système international pour l'entropie
- C. Parce que $\Delta_rS^\circ$ est toujours négatif et doit être exprimé en kJ pour le montrer
- D. Parce que la constante $R$ impose une conversion systématique en kJ

**Réponse correcte** : A

**Feedback correct**
Exemple : $\Delta_rH^\circ = -196$ kJ et $T\Delta_rS^\circ = 298\times125 = 37250\ \text{J} = 37{,}3\ \text{kJ}$ ; sans conversion, on retrancherait 37250 à −196.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le kelvin est bien l'unité SI ; l'enjeu est la cohérence kJ / J.
- Si C : Le signe de $\Delta_rS^\circ$ n'a rien à voir avec l'unité.
- Si D : $R$ n'intervient pas dans cette voie.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-app-005
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-de-reaction--coefficients-oublies-dans-la-somme
date_validation: 2026-11-07
statut: validated
---

**Question**
Calculer $\Delta_rG^\circ$ de $\ce{C2H6(g) + 7/2 O2(g) -> 2CO2(g) + 3H2O(l)}$ avec $\Delta_fG^\circ$ : $\ce{C2H6}$ −32,9 ; $\ce{CO2}$ −394,4 ; $\ce{H2O,l}$ −237,1 kJ·mol⁻¹.

**Options**
- A. $-1\,467{,}2$ kJ·mol⁻¹
- B. $+1\,467{,}2$ kJ·mol⁻¹
- C. $-598{,}6$ kJ·mol⁻¹
- D. $-1\,441{,}7$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = 2\times(-394{,}4) + 3\times(-237{,}1) - (-32{,}9) = -788{,}8 - 711{,}3 + 32{,}9 = -1\,467{,}2$ kJ·mol⁻¹.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : produits − réactifs.
- Si C : Les coefficients ont été oubliés : $-394{,}4 - 237{,}1 + 32{,}9$.
- Si D : C'est la valeur obtenue avec l'eau gazeuse ($-228{,}6$) au lieu de l'eau liquide.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-app-006
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-de-reaction--coefficients-oublies-dans-la-somme
date_validation: 2026-11-07
statut: validated
---

**Question**
Calculer $\Delta_rG^\circ$ de $\ce{Zn(s) + Cu^{2+}(aq) -> Zn^{2+}(aq) + Cu(s)}$ avec $\Delta_fG^\circ(\ce{Zn^{2+}}) = -147{,}1$ et $\Delta_fG^\circ(\ce{Cu^{2+}}) = +65{,}5$ kJ·mol⁻¹.

**Options**
- A. $-212{,}6$ kJ·mol⁻¹
- B. $+212{,}6$ kJ·mol⁻¹
- C. $-81{,}6$ kJ·mol⁻¹
- D. $-147{,}1$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = \Delta_fG^\circ(\ce{Zn^{2+}}) - \Delta_fG^\circ(\ce{Cu^{2+}}) = -147{,}1 - 65{,}5 = -212{,}6$ kJ·mol⁻¹ (les métaux solides valent 0).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : produits − réactifs.
- Si C : Le signe de $\Delta_fG^\circ(\ce{Cu^{2+}})$ a été mal traité : on a ajouté 65,5 au lieu de le retrancher.
- Si D : Le terme $\ce{Cu^{2+}}$ du côté des réactifs a été oublié.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-app-007
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-de-reaction--kj-et-j-melanges
date_validation: 2026-11-07
statut: validated
---

**Question**
Calculer $\Delta_rG^\circ$ (298 K) de $\ce{C3H8(g) + 5O2(g) -> 3CO2(g) + 4H2O(g)}$ avec $\Delta_rH^\circ = -2\,046$ kJ et $\Delta_rS^\circ = +103\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Options**
- A. $-2\,077$ kJ·mol⁻¹
- B. $-2\,046$ kJ·mol⁻¹
- C. $-2\,015$ kJ·mol⁻¹
- D. $-32\,740$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = -2\,046 - 298\times0{,}103 = -2\,046 - 30{,}7 = -2\,077$ kJ·mol⁻¹.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le terme entropique a été oublié.
- Si C : Le signe de $-T\Delta_rS^\circ$ est inversé.
- Si D : $\Delta_rS^\circ$ n'a pas été converti en kJ·K⁻¹ : $-2\,046 - 298\times103$.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-app-008
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Calculer $\Delta_rG^\circ$ à 500 K pour $\ce{SOCl2 + H2O -> SO2(g) + 2HCl(g)}$ ($\Delta_rH^\circ = +49{,}5$ kJ ; $\Delta_rS^\circ = +336{,}1\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$, constants).

**Options**
- A. $-118{,}6$ kJ·mol⁻¹
- B. $-50{,}7$ kJ·mol⁻¹
- C. $+217{,}6$ kJ·mol⁻¹
- D. $-168{,}1$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ(500) = 49{,}5 - 500\times0{,}3361 = 49{,}5 - 168{,}1 = -118{,}6$ kJ·mol⁻¹ : plus négative qu'à 298 K ($-50{,}7$), car $\Delta_rS^\circ > 0$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est la valeur à 298 K : la température n'a pas été changée.
- Si C : Le signe de $-T\Delta_rS^\circ$ a été inversé.
- Si D : Le terme $\Delta_rH^\circ$ a été oublié.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-ana-301
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour l'éthane, la voie 2 donne $-1\,467{,}2$ kJ·mol⁻¹ et la voie 1 ($\Delta H = -1\,562$ kJ ; $\Delta S = -308{,}5$ J·K⁻¹) donne $-1\,470$ kJ·mol⁻¹. Quelles affirmations sont correctes ?

**Options**
- A. L'écart (≈ 3 kJ·mol⁻¹, soit 0,2 %) est dû aux arrondis des tables ; il n'affecte pas la conclusion
- B. Dans les deux cas $\Delta_rG^\circ$ est très fortement négative : la combustion est thermodynamiquement favorable (spontanée)
- C. L'un des deux résultats est faux, car deux voies correctes donnent exactement la même valeur
- D. L'écart prouve que $\Delta_rG^\circ$ dépend du chemin suivi pour calculer la réaction

**Réponse correcte** : A, B

**Feedback correct**
Le terme $-T\Delta_rS^\circ = +92$ kJ est petit devant $\Delta_rH^\circ$ ; les écarts d'arrondi (tables CRM en entiers, $\Delta_fG^\circ$ à 0,1) expliquent 3 kJ.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Des données arrondies différemment ne reproduisent jamais exactement le même résultat.
- Si D : $G$ est une fonction d'état : le chemin de calcul n'a pas d'importance, seul l'état initial et final comptent.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-ana-302
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la réaction de Daniell, voie 1 : $\Delta_rH^\circ = -218$ kJ et $\Delta_rS^\circ = -20\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ ; voie 2 : $-212{,}6$ kJ. Quelles affirmations sont correctes ?

**Options**
- A. Voie 1 : $\Delta_rG^\circ = -218 + 298\times0{,}020 \approx -212$ kJ·mol⁻¹, en accord à 1 kJ près avec la voie 2
- B. Malgré $\Delta_rS^\circ<0$, la réaction est très favorable thermodynamiquement (spontanée) : le terme $\Delta_rH^\circ$ domine
- C. Comme $\Delta_rS^\circ<0$, la réaction ne peut pas être favorable à 298 K
- D. Le terme entropique ($+6$ kJ) domine, et c'est lui qui rend la réaction favorable

**Réponse correcte** : A, B

**Feedback correct**
Le terme $-T\Delta_rS^\circ = +6$ kJ est faible devant $\Delta_rH^\circ = -218$ kJ : l'entropie, ici défavorable, ne suffit pas à inverser le signe.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Un $\Delta S<0$ ne suffit pas : l'enthalpie très négative compense largement.
- Si D : Le terme entropique est défavorable ($+6$ kJ), pas favorable.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-eva-303
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: enthalpie-libre-de-reaction--kj-et-j-melanges
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève calcule pour la combustion du propane : « $\Delta_rG^\circ = -2\,046 - 298\times103 = -32\,740$ kJ·mol⁻¹, c'est donc une réaction extraordinairement thermodynamiquement favorable (spontanée). » Quelle évaluation est correcte ?

**Options**
- A. Calcul faux : $\Delta_rS^\circ$ est en J·K⁻¹ et doit être converti en kJ·K⁻¹ ; la bonne valeur est $-2\,077$ kJ·mol⁻¹
- B. Calcul correct : le terme entropique est énorme pour une réaction qui produit des gaz
- C. Calcul faux : il faudrait ajouter les deux termes, soit $-2\,046 + 30\,694$
- D. Calcul correct, mais le résultat doit être exprimé en joules

**Réponse correcte** : A

**Feedback correct**
$298\times103 = 30694\ \text{J} = 30{,}7\ \text{kJ}$ : ce terme est petit devant $\Delta_rH^\circ$. Valeur correcte : $-2\,046 - 30{,}7 = -2\,077$ kJ·mol⁻¹.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Un terme entropique de 30,7 kJ est faible devant 2 046 kJ ; il est numériquement exagéré par une erreur d'unité.
- Si C : Le signe est bien $-T\Delta S$ ; le problème est l'unité, pas le signe.
- Si D : Un résultat en joules vaudrait $-2{,}077\times10^6$ J, pas $-32\,740$.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-de-reaction-symbo-eva-304
concept: enthalpie-libre-de-reaction
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: enthalpie-libre-de-reaction--coefficients-oublies-dans-la-somme
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève dit : « $\Delta_rG^\circ$ de la combustion est de $-1\,467$ kJ·mol⁻¹ pour l'éthane, donc elle vaut aussi $-1\,467$ kJ pour l'équation $\ce{2C2H6 + 7O2 -> 4CO2 + 6H2O(l)}$. » Comment juger cette phrase ?

**Options**
- A. Fausse : l'équation est doublée ; $\Delta_rG^\circ = 2\times(-1\,467{,}2) = -2\,934{,}4$ kJ·mol⁻¹ pour l'équation écrite
- B. Vraie : $\Delta_rG^\circ$ se rapporte toujours à une mole d'éthane, quelle que soit l'équation
- C. Vraie : l'énergie libre est une grandeur intensive qui ne dépend pas des coefficients
- D. Fausse : elle serait de $-1\,467/2$, car il faut diviser par le nombre d'équations

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ$ est une grandeur extensive par rapport à l'équation : en doublant les coefficients, on double la valeur (comme $\Delta_rH^\circ$ et $\Delta_rS^\circ$). L'unité kJ·mol⁻¹ signifie par mole d'avancement de l'équation écrite.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Il n'y a pas de normalisation implicite sur l'éthane : on rapporte à l'équation telle qu'elle est écrite.
- Si C : $\Delta G$ est extensive : doubler les quantités double $\Delta G$.
- Si D : Le facteur est 2 dans l'autre sens : il faut multiplier.

**Référence manuel** : thermochimie-2-enthalpie-libre-reaction

---

---
id: q-enthalpie-libre-et-k-symbo-sou-001
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle relation lie l'enthalpie libre standard de réaction à la constante d'équilibre $K$ à la température $T$ ?

**Options**
- A. $\Delta_rG^\circ = -RT\ln K$
- B. $\Delta_rG^\circ = +RT\ln K$
- C. $\Delta_rG^\circ = -RT\,K$
- D. $\Delta_rG^\circ = -\ln K / (RT)$

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = -RT\ln K$ : plus $\Delta_rG^\circ$ est négative, plus $K$ est grand.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : $\Delta_rG^\circ<0$ doit correspondre à $K>1$.
- Si C : $K$ intervient par son logarithme.
- Si D : $RT$ multiplie $\ln K$ ; il ne le divise pas.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-macro-com-002
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
misconception: enthalpie-libre-et-k--delta-g-standard-positif-reaction-impossible
date_validation: 2026-11-07
statut: validated
---

**Question**
À 298 K, trois réactions ont pour constantes d'équilibre $K_1 = 8\times10^{40}$, $K_2 = 1$ et $K_3 = 2\times10^{-11}$. Quelle description de la composition à l'équilibre est correcte ?

**Options**
- A. (1) : quasi seulement des produits ; (2) : réactifs et produits en quantités comparables ; (3) : quasi seulement des réactifs
- B. (1) : quasi seulement des réactifs ; (2) : un mélange ; (3) : quasi seulement des produits, car $K$ est petit
- C. (1) : un mélange ; (2) : seulement des produits, puisque $K$ vaut 1 ; (3) : seulement des réactifs
- D. (1), (2) et (3) : toujours un mélange identique, car $K$ ne dit rien de la composition d'équilibre

**Réponse correcte** : A

**Feedback correct**
$K = \dfrac{[\text{produits}]^{\nu}}{[\text{réactifs}]^{\nu}}$ à l'équilibre : $K\gg1$ favorise les produits, $K\ll1$ les réactifs, $K=1$ un partage comparable.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Les rôles sont inversés : $K\gg1$ signifie des produits en grande quantité.
- Si C : $K=1$ n'est pas « tout produits » : c'est un partage équilibré en activités.
- Si D : $K$ renseigne directement sur la composition de l'équilibre.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-com-003
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: enthalpie-libre-et-k--delta-g-standard-positif-reaction-impossible
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour une dissociation acide très faible, $\Delta_rG^\circ = +60{,}8$ kJ·mol⁻¹ à 298 K ($K = 2\times10^{-11}$). Que signifie ce signe positif ?

**Options**
- A. $K<1$ : l'équilibre est très en faveur des réactifs, mais une petite quantité de produits se forme tout de même
- B. La réaction n'a pas lieu du tout, car $\Delta_rG^\circ>0$ interdit toute transformation
- C. La réaction est impossible tant qu'on n'apporte pas de chaleur, puisque $\Delta_rG^\circ>0$
- D. La réaction est instantanée dans le sens inverse, car $\Delta_rG^\circ>0$ indique une grande vitesse

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = +60{,}8$ kJ donne $K = e^{-60\,800/(8{,}314\times298)} = 2\times10^{-11}$ : très faible mais non nulle. C'est ce qui permet de calculer le pH d'une solution d'acide faible.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $K$ n'est jamais nulle : la réaction a lieu dans une très faible mesure.
- Si C : Apporter de la chaleur changerait $K$ mais ne rendrait pas la réaction « possible » : elle l'est déjà, à très faible extension.
- Si D : $\Delta_rG^\circ$ ne renseigne pas sur la vitesse.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-com-004
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: enthalpie-libre-et-k--delta-g-standard-nul-egale-equilibre
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « À l'équilibre, $\Delta_rG^\circ = 0$. » Quelle correction est exacte ?

**Options**
- A. C'est $\Delta_rG$ qui s'annule à l'équilibre ; $\Delta_rG^\circ=-RT\ln K$ n'est nulle que si $K=1$
- B. Il a raison : $\Delta_rG^\circ=0$ est la condition d'équilibre dans tous les cas de figure
- C. Il a raison, mais seulement à la température de 298 K, qui est celle des tables
- D. Il a tort : à l'équilibre $\Delta_rG^\circ$ est toujours égale à $-RT$, quelle que soit la réaction

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG = \Delta_rG^\circ + RT\ln Q$ ; à l'équilibre $Q=K$ et $\Delta_rG=0$, d'où $\Delta_rG^\circ = -RT\ln K$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $\Delta_rG^\circ=0$ correspond à $K=1$, un cas particulier.
- Si C : La température n'y change rien : la condition d'équilibre porte sur $\Delta_rG$.
- Si D : $\Delta_rG^\circ = -RT\ln K$ dépend de $K$ ; il n'y a pas de valeur universelle.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-app-005
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-et-k--delta-g-standard-positif-reaction-impossible
date_validation: 2026-11-07
statut: validated
---

**Question**
À 298 K, $\Delta_rG^\circ = -10$ kJ·mol⁻¹. Quelle est la constante d'équilibre ?

**Options**
- A. $K\approx 6\times10^{1}$
- B. $K\approx 2\times10^{-2}$
- C. $K\approx 1{,}0$
- D. $K\approx 4{,}0$

**Réponse correcte** : A

**Feedback correct**
$\ln K = 10\,000/(8{,}314\times298) = 4{,}04$, d'où $K = e^{4{,}04}\approx 57$ : les produits dominent.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de l'exposant est inversé : $\Delta_rG^\circ<0$ donne $K>1$.
- Si C : Le résultat vient d'un oubli de conversion des kJ en J : $e^{-0{,}004}\approx1$.
- Si D : 4,0 est $\ln K$, pas $K$.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-app-006
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-gibbs--delta-g-egal-delta-g-standard
date_validation: 2026-11-07
statut: validated
---

**Question**
Une réaction a $K=10^{3}$ à 298 K. Quelle est la valeur de $\Delta_rG^\circ$ ?

**Options**
- A. $-17{,}1$ kJ·mol⁻¹
- B. $+17{,}1$ kJ·mol⁻¹
- C. $-6{,}9$ kJ·mol⁻¹
- D. $-7{,}4$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = -RT\ln K = -2{,}478\times\ln(10^{3}) = -2{,}478\times6{,}91 = -17{,}1$ kJ·mol⁻¹.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : $K>1$ donne $\Delta_rG^\circ<0$.
- Si C : $6{,}9$ est $\ln K$ : il faut multiplier par $RT$.
- Si D : 7,4 correspond à $RT\times\log_{10}K$ : il faut le logarithme népérien.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-app-007
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la synthèse de l'ammoniac, $\Delta_rG^\circ(298\ \text{K}) = -32{,}7$ kJ·mol⁻¹. Quelle est la valeur de $K$ ?

**Options**
- A. $K\approx 5\times10^{5}$
- B. $K\approx 2\times10^{-6}$
- C. $K\approx 2\times10^{14}$
- D. $K\approx 13$

**Réponse correcte** : A

**Feedback correct**
$\ln K = 32\,700/(8{,}314\times298) = 13{,}2$ ; $K = e^{13{,}2}\approx 5\times10^{5}$ : la synthèse est favorable à 298 K.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de l'exposant est inversé.
- Si C : Le facteur $RT$ a été oublié : $e^{32{,}7}$.
- Si D : 13 est $\ln K$, pas $K$.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-app-008
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-et-k--delta-g-standard-positif-reaction-impossible
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{3O2(g) -> 2O3(g)}$, $\Delta_rG^\circ(298\ \text{K}) = +326$ kJ. Quelle est la valeur de $K$ ?

**Options**
- A. $K\approx 6\times10^{-58}$
- B. $K\approx 2\times10^{57}$
- C. $K=0$ exactement
- D. $K\approx 3\times10^{-132}$

**Réponse correcte** : A

**Feedback correct**
$\ln K = -326\,000/(8{,}314\times298) = -131{,}6$ ; $K = e^{-131{,}6}\approx 6\times10^{-58}$ : l'ozone se forme, mais en quantité infime à partir de $\ce{O2}$ à 298 K.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de l'exposant est inversé.
- Si C : $K$ est minuscule mais jamais exactement nulle.
- Si D : 10 à la puissance −131,6 est une erreur : $\ln K$ est un logarithme népérien.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-ana-301
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: enthalpie-libre-et-k--k-independant-de-l-ecriture-de-l-equation
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{N2 + 3H2 -> 2NH3}$, $K\approx5{,}4\times10^{5}$ à 298 K. Quelles affirmations sont correctes pour les autres écritures de la même transformation ?

**Options**
- A. Pour $\ce{1/2 N2 + 3/2 H2 -> NH3}$, $K = \sqrt{5{,}4\times10^{5}}\approx 7{,}3\times10^{2}$
- B. Pour $\ce{2NH3 -> N2 + 3H2}$, $K = 1/(5{,}4\times10^{5}) \approx 1{,}9\times10^{-6}$
- C. Pour les trois écritures, $K$ est identique, puisque la transformation est la même
- D. Pour $\ce{2N2 + 6H2 -> 4NH3}$, $K = 2\times5{,}4\times10^{5}$

**Réponse correcte** : A, B

**Feedback correct**
Multiplier l'équation par $k$ élève $K$ à la puissance $k$ ; l'inverser donne $1/K$. Comme $\Delta_rG^\circ = -RT\ln K$ est extensive par rapport à l'équation, $\ln K$ l'est aussi.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : $\Delta_rG^\circ$ change avec l'écriture, donc $K$ aussi.
- Si D : Doubler l'équation élève $K$ au carré ($K^2\approx 2{,}9\times10^{11}$), il ne le double pas.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-ana-302
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: enthalpie-libre-et-k--delta-g-standard-nul-egale-equilibre
date_validation: 2026-11-07
statut: validated
---

**Question**
À 298 K, trois réactions ont respectivement $\Delta_rG^\circ = -50$, $0$ et $+50$ kJ·mol⁻¹. Quelles affirmations sont correctes ?

**Options**
- A. Pour $-50$ kJ·mol⁻¹, $K\approx6\times10^{8}$ : réaction quasi totale
- B. Pour $0$ kJ·mol⁻¹, $K=1$ ; ce n'est pas la condition d'équilibre pour un mélange quelconque
- C. Pour $+50$ kJ·mol⁻¹, $K=0$ : la réaction n'a pas lieu
- D. Pour $0$ kJ·mol⁻¹, un mélange standard est à l'équilibre dès le départ

**Réponse correcte** : A, B

**Feedback correct**
Pour $+50$ kJ·mol⁻¹, $K = e^{-20{,}2}\approx 2\times10^{-9}$ : très faible mais non nul. Pour $0$, $K=1$ ; le sens d'évolution dépend de la composition initiale ($Q$ comparé à $K$).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : $K$ est strictement positif, même très petit.
- Si D : À $\Delta_rG^\circ=0$, un mélange standard a $Q=1=K$, donc il est à l'équilibre seulement s'il est en proportions standard ; pour d'autres compositions il évolue.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-eva-303
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: enthalpie-libre-et-k--delta-g-standard-positif-reaction-impossible
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « $\Delta_rG^\circ = +50$ kJ·mol⁻¹, donc cette réaction ne se produit pas. » Quelle évaluation est correcte ?

**Options**
- A. Trop absolue : $K\approx2\times10^{-9}$ est minuscule mais non nulle ; la réaction a lieu très faiblement
- B. Correcte : $\Delta_rG^\circ>0$ signifie toujours $K=0$ et donc qu'aucune transformation n'a lieu
- C. Correcte à 298 K seulement ; à 400 K, $K$ devient forcément supérieure à 1, quelle que soit la réaction
- D. Fausse : $\Delta_rG^\circ>0$ signifie au contraire que la réaction est totale

**Réponse correcte** : A

**Feedback correct**
$K=e^{-\Delta_rG^\circ/RT}>0$ toujours. Les réactions « défavorables » comme la dissociation d'un acide faible produisent des ions mesurables (pH) malgré $\Delta_rG^\circ>0$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $K=0$ est impossible pour un équilibre.
- Si C : Chauffer ne rend pas $K>1$ automatiquement : cela dépend du signe de $\Delta_rH^\circ$.
- Si D : Une réaction totale correspond à $\Delta_rG^\circ\ll0$.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-eva-304
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: enthalpie-libre-et-k--k-independant-de-l-ecriture-de-l-equation
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « Pour $\ce{H2 + 1/2 O2 -> H2O(l)}$, $K\approx4\times10^{41}$ ; donc pour $\ce{2H2 + O2 -> 2H2O(l)}$, $K$ est le même. » Comment juger cette phrase ?

**Options**
- A. Fausse : l'équation doublée donne $K\approx(4\times10^{41})^{2}\approx1\times10^{83}$
- B. Vraie : $K$ ne dépend pas de la façon dont l'équation est écrite, mais de la réaction
- C. Fausse : $K$ est simplement multiplié par 2, soit environ $8\times10^{41}$
- D. Fausse : $K$ est simplement divisé par 2, soit environ $2\times10^{41}$

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ$ passe de $-237{,}1$ à $-474{,}2$ kJ·mol⁻¹ : $\ln K$ double, donc $K\to K^2$. D'où l'importance de toujours préciser l'équation écrite.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $K$ est lié à l'équation écrite par $\Delta_rG^\circ = -RT\ln K$.
- Si C : Doubler $\ln K$ revient à élever $K$ au carré, pas à le doubler.
- Si D : Diviser par 2 la valeur de $K$ n'a aucun sens : $K$ augmente.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-com-009
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: enthalpie-libre-et-k--delta-g-standard-positif-reaction-impossible
date_validation: 2026-11-07
statut: validated
---

**Question**
À 298 K, trois réactions ont pour enthalpie libre standard $\Delta_rG^\circ = -200$, $-5$ et $+200$ kJ·mol⁻¹. Quelle description est la plus juste ?

**Options**
- A. $-200$ : quasi totale ; $-5$ : mélange à dominante de produits ; $+200$ : pratiquement aucun produit
- B. $-200$ : quasi totale ; $-5$ : quasi totale aussi, puisque $\Delta_rG^\circ<0$ ; $+200$ : aucun produit, $K=0$
- C. $-200$ : favorable mais incomplète ; $-5$ : très rapide ; $+200$ : impossible dans tous les cas
- D. $-200$ et $-5$ donnent le même résultat, car seul le signe de $\Delta_rG^\circ$ compte ; $+200$ : réaction impossible

**Réponse correcte** : A

**Feedback correct**
$K=e^{-\Delta_rG^\circ/RT}$ : $-200$ kJ donne $K\approx10^{35}$ (quasi totale), $-5$ kJ donne $K\approx7{,}5$ (un mélange), $+200$ kJ donne $K\approx10^{-35}$ (pratiquement aucun produit, mais non nul).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe seul ne suffit pas : l'ampleur de $\Delta_rG^\circ$ fixe l'avancement à l'équilibre.
- Si C : Le signe seul ne suffit pas : $-5$ kJ donne $K\approx7{,}5$, loin d'une réaction totale.
- Si D : $\Delta_rG^\circ$ renseigne sur le sens et l'ampleur, jamais sur la vitesse ; et $K$ n'est jamais exactement nul.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-app-010
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-et-k--delta-g-standard-positif-reaction-impossible
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour une réaction à 298 K avec $\Delta_rG^\circ = -200$ kJ·mol⁻¹, quel ordre de grandeur a $K$ ?

**Options**
- A. $K\approx10^{35}$
- B. $K\approx10^{-35}$
- C. $K\approx10^{-2}$
- D. $K\approx 8\times10^{-1}$

**Réponse correcte** : A

**Feedback correct**
$\ln K = 200\,000/(8{,}314\times298)\approx80{,}7$, donc $K\approx1{,}1\times10^{35}$ : la réaction est quasi totale.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de l'exposant est inversé : $\Delta_rG^\circ<0$ donne $K>1$.
- Si C : Une conversion kJ vers J oubliée ferait trouver $e^{0{,}08}\approx1$, pas $10^{-2}$.
- Si D : L'exponentielle de $-\Delta_rG^\circ/RT$ n'est pas proche de 1 pour une valeur aussi grande.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-ana-305
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: enthalpie-libre-et-k--delta-g-standard-positif-reaction-impossible
date_validation: 2026-11-07
statut: validated
---

**Question**
On compare $\Delta_rG^\circ = -5$, $-20$ et $-200$ kJ·mol⁻¹ à 298 K ($K\approx7{,}5$ ; $3\times10^{3}$ ; $10^{35}$). Quelles conclusions sont correctes ?

**Options**
- A. Les trois sont thermodynamiquement favorables (spontanées), mais seule la dernière est quasi totale
- B. Quand $|\Delta_rG^\circ|$ n'excède que quelques kJ·mol⁻¹, l'équilibre contient réactifs et produits en quantités comparables
- C. Les trois sont quasi totales, car $\Delta_rG^\circ<0$ dans chaque cas
- D. Plus $\Delta_rG^\circ$ est négative, plus la réaction est rapide

**Réponse correcte** : A, B

**Feedback correct**
Le signe donne le sens ; l'ampleur de $\Delta_rG^\circ$ donne la position de l'équilibre (via $K$). D'après le tableau du cours, $-10$ kJ·mol⁻¹ donne $K\approx6\times10^{1}$ (les produits dominent) et $-50$ kJ·mol⁻¹ donne $K\approx6\times10^{8}$ (quasi totale).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Avec $K\approx7{,}5$, une part notable des réactifs subsiste.
- Si D : $\Delta_rG^\circ$ ne dit rien de la vitesse.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-enthalpie-libre-et-k-symbo-eva-306
concept: enthalpie-libre-et-k
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: enthalpie-libre-et-k--delta-g-standard-positif-reaction-impossible
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève dit : « $\Delta_rG^\circ = -5$ kJ·mol⁻¹ est négative, donc la réaction est totale. » Comment juger cette phrase ?

**Options**
- A. Inexacte : $K\approx7{,}5$ laisse un mélange de réactifs et de produits
- B. Exacte : toute valeur négative de $\Delta_rG^\circ$ donne une réaction totale
- C. Inexacte : une valeur négative de $\Delta_rG^\circ$ signifie que la réaction est impossible
- D. Exacte, car $-5$ kJ·mol⁻¹ correspond à $K\approx10^{35}$

**Réponse correcte** : A

**Feedback correct**
$K=e^{5\,000/(8{,}314\times298)}\approx7{,}5$ : les produits dominent un peu, mais l'équilibre contient encore une part importante de réactifs. Une réaction est quasi totale seulement si $\Delta_rG^\circ$ est très négative (d'après le tableau du cours, de l'ordre de $-50$ kJ·mol⁻¹ ou moins).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe ne suffit pas : il faut comparer l'ampleur à $RT\approx2{,}5$ kJ·mol⁻¹.
- Si C : Le signe négatif correspond au contraire à une réaction thermodynamiquement favorable.
- Si D : $10^{35}$ correspond à $-200$ kJ·mol⁻¹, pas à $-5$.

**Référence manuel** : thermochimie-2-enthalpie-libre-k

---

---
id: q-k-et-temperature-symbo-com-001
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: k-et-temperature--chauffer-favorise-toujours-les-produits
date_validation: 2026-11-07
statut: validated
---

**Question**
Une réaction est exothermique ($\Delta_rH^\circ<0$). Comment varie sa constante d'équilibre $K$ quand la température augmente ?

**Options**
- A. $K$ diminue : l'équilibre se déplace vers les réactifs
- B. $K$ augmente : chauffer favorise toujours les produits
- C. $K$ ne change pas, car elle ne dépend que de la nature de la réaction
- D. $K$ augmente puis diminue, avec un maximum à 298 K

**Réponse correcte** : A

**Feedback correct**
La loi de van't Hoff donne $\dfrac{d\ln K}{dT} = \dfrac{\Delta_rH^\circ}{RT^2}$ : négative si $\Delta_rH^\circ<0$. Exemple : synthèse de l'ammoniac, $K=5\times10^5$ à 298 K et $0{,}17$ à 500 K.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Chauffer favorise le sens endothermique, pas toujours les produits.
- Si C : $K$ dépend de la température (par $\Delta_rG^\circ = \Delta_rH^\circ - T\Delta_rS^\circ$).
- Si D : Il n'existe pas de maximum à 298 K : la variation est monotone si $\Delta H$ est constant.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-symbo-com-002
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: k-et-temperature--k-independant-de-la-temperature
date_validation: 2026-11-07
statut: validated
---

**Question**
Une réaction est endothermique ($\Delta_rH^\circ>0$). Que devient $K$ quand la température augmente ?

**Options**
- A. $K$ augmente : l'équilibre se déplace vers les produits
- B. $K$ diminue, car toute élévation de température déstabilise les produits
- C. $K$ reste constante, puisque la quantité de chaleur absorbée est fixe
- D. $K$ devient égale à 1, quelle que soit la réaction

**Réponse correcte** : A

**Feedback correct**
$d\ln K/dT = \Delta_rH^\circ/(RT^2)>0$ : $K$ augmente. Exemple : décomposition de $\ce{CaCO3}$, $K=1$ à 1 112 K et $K\gg1$ au-delà.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Pour une réaction endothermique, chauffer favorise les produits.
- Si C : $K$ ne reste pas constante : sa dépendance en $T$ est exponentielle.
- Si D : $K=1$ seulement à la température où $\Delta_rG^\circ=0$.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-symbo-com-003
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi trace-t-on $\ln K$ en fonction de $1/T$ ?

**Options**
- A. Car $\ln K = -\dfrac{\Delta_rH^\circ}{R}\dfrac1T + \dfrac{\Delta_rS^\circ}{R}$ est affine en $1/T$
- B. Parce que $\ln K$ est proportionnel à $T$, ce qui donne une droite passant par l'origine
- C. Parce que la pente de cette droite vaut $\Delta_rS^\circ$ et que son ordonnée à l'origine vaut $\Delta_rH^\circ$
- D. Parce que $1/T$ est directement la constante d'équilibre à 298 K

**Réponse correcte** : A

**Feedback correct**
En combinant $\Delta_rG^\circ=-RT\ln K$ et $\Delta_rG^\circ=\Delta_rH^\circ-T\Delta_rS^\circ$, on obtient une relation affine en $1/T$ : la pente donne $\Delta_rH^\circ$, l'ordonnée à l'origine $\Delta_rS^\circ$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $\ln K$ n'est pas proportionnel à $T$ mais affine en $1/T$.
- Si C : Les rôles sont inversés : la pente est $-\Delta_rH^\circ/R$ et l'ordonnée à l'origine $\Delta_rS^\circ/R$.
- Si D : $1/T$ est l'inverse de la température, sans lien direct avec $K$.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-symbo-app-004
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{1/2 N2 + 3/2 H2 -> NH3}$, $K(298)=7{,}3\times10^{2}$ et $\Delta_rH^\circ=-46$ kJ·mol⁻¹. Quelle est $K$ à 270 K ($\Delta_rH^\circ$ constant) ?

**Options**
- A. $K(270)\approx5{,}0\times10^{3}$
- B. $K(270)\approx1{,}1\times10^{2}$
- C. $K(270)\approx7{,}4\times10^{2}$
- D. $K(270)\approx3{,}5\times10^{4}$

**Réponse correcte** : A

**Feedback correct**
$\ln K(270) = \ln K(298) - \dfrac{\Delta_rH^\circ}{R}\left(\dfrac1{270}-\dfrac1{298}\right) = 6{,}60 + 1{,}93 = 8{,}52$ ; $K(270)\approx5{,}0\times10^3$ : réaction exothermique, $K$ augmente quand on refroidit.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de la correction est inversé ($6{,}60-1{,}93=4{,}67$).
- Si C : Les kJ n'ont pas été convertis en J : la correction est négligeable.
- Si D : On a utilisé $\Delta_rH^\circ=-92$ kJ (équation doublée) au lieu de $-46$ kJ.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-symbo-app-005
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la synthèse du méthanol ($\Delta_rH^\circ=-90$ kJ·mol⁻¹), $K(298)=2\times10^{4}$. Quelle est $K$ à 500 K ($\Delta_rH^\circ$ constant) ?

**Options**
- A. $K(500)\approx8\times10^{-3}$
- B. $K(500)\approx5\times10^{10}$
- C. $K(500)\approx2\times10^{4}$
- D. $K(500)\approx9{,}9$

**Réponse correcte** : A

**Feedback correct**
$\ln K(500) = 9{,}90 + \dfrac{90\,000}{8{,}314}\left(\dfrac1{500}-\dfrac1{298}\right) = 9{,}90 - 14{,}68 = -4{,}78$ ; $K\approx8\times10^{-3}$ : défavorable à 500 K (on compense par la pression et un catalyseur).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de la correction est inversé : pour une réaction exothermique, $K$ diminue quand $T$ augmente.
- Si C : Les kJ n'ont pas été convertis en J : la correction est négligeable et $K$ semble inchangée.
- Si D : 9,9 est $\ln K(298)$, pas $K(500)$.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-symbo-app-006
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{SOCl2 + H2O -> SO2(g) + 2HCl(g)}$, $\Delta_rH^\circ=+49{,}5$ kJ et $\Delta_rS^\circ=+336{,}1\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelle est $K$ à 500 K (valeurs constantes, calcul illustratif) ?

**Options**
- A. $K\approx2\times10^{12}$
- B. $K\approx4\times10^{-13}$
- C. $K\approx8\times10^{8}$
- D. $K\approx28{,}5$

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ(500)=49{,}5-500\times0{,}3361=-118{,}6$ kJ ; $\ln K=118\,600/(8{,}314\times500)=28{,}5$ ; $K\approx2\times10^{12}$ (réaction endothermique : $K$ augmente avec $T$).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de l'exposant est inversé.
- Si C : C'est $K$ à 298 K ($\Delta_rG^\circ=-50{,}7$ kJ) : la température n'a pas été changée.
- Si D : 28,5 est $\ln K$, pas $K$.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-macro-ana-301
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: macro
type: ana
misconception: k-et-temperature--chauffer-favorise-toujours-les-produits
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{1/2 N2 + 3/2 H2 -> NH3}$, on lit $\ln K=6{,}60$ à 298 K ($1/T=3{,}36\times10^{-3}$ K⁻¹) et $\ln K=8{,}52$ à 270 K ($1/T=3{,}70\times10^{-3}$ K⁻¹). Quelles affirmations sont correctes ?

**Options**
- A. La droite $\ln K = f(1/T)$ est croissante : la pente vaut environ $+5{,}5\times10^{3}$ K
- B. On en déduit $\Delta_rH^\circ = -R\times\text{pente}\approx-46$ kJ·mol⁻¹ : réaction exothermique
- C. La pente vaut $\Delta_rS^\circ$ et est donc positive
- D. La droite est croissante, donc la réaction est endothermique

**Réponse correcte** : A, B

**Feedback correct**
Pente $=(8{,}52-6{,}60)/(3{,}70\times10^{-3}-3{,}36\times10^{-3})\approx5{,}5\times10^{3}$ K $=-\Delta_rH^\circ/R$, d'où $\Delta_rH^\circ\approx-46$ kJ·mol⁻¹.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : La pente vaut $-\Delta_rH^\circ/R$ ; c'est l'ordonnée à l'origine qui vaut $\Delta_rS^\circ/R$.
- Si D : Une droite croissante en $1/T$ signifie que $K$ augmente quand $T$ diminue : réaction exothermique.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-symbo-ana-302
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: k-et-temperature--chauffer-favorise-toujours-les-produits
date_validation: 2026-11-07
statut: validated
---

**Question**
Une réaction a $K=1\,000$ à 300 K et $K=10$ à 400 K (on suppose $\Delta_rH^\circ$ et $\Delta_rS^\circ$ constants). Quelles affirmations sont correctes ?

**Options**
- A. $\Delta_rH^\circ\approx-46$ kJ·mol⁻¹ : la réaction est exothermique
- B. $\Delta_rS^\circ\approx-96$ J·K⁻¹·mol⁻¹ : elle diminue l'entropie du système
- C. La réaction est endothermique, puisque $K$ varie avec la température
- D. $\Delta_rS^\circ$ est positive, puisque $\Delta_rG^\circ<0$ à 300 K

**Réponse correcte** : A, B

**Feedback correct**
$\ln(K_2/K_1)=-\dfrac{\Delta_rH^\circ}{R}\left(\dfrac1{T_2}-\dfrac1{T_1}\right)$ donne $\Delta_rH^\circ\approx-46$ kJ. Puis $\Delta_rG^\circ(300)=-RT\ln K=-17{,}2$ kJ et $\Delta_rS^\circ=(\Delta_rH^\circ-\Delta_rG^\circ)/T\approx-96$ J·K⁻¹·mol⁻¹.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Une réaction endothermique voit $K$ augmenter avec $T$ ; ici $K$ diminue.
- Si D : $\Delta_rG^\circ<0$ peut s'obtenir avec $\Delta_rS^\circ<0$ si $\Delta_rH^\circ$ est assez négatif.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-symbo-ana-303
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: k-et-temperature--chauffer-favorise-toujours-les-produits
date_validation: 2026-11-07
statut: validated
---

**Question**
On chauffe de 298 K à 500 K deux systèmes : (a) $\ce{N2 + 3H2 -> 2NH3}$ ($\Delta_rH^\circ=-92$ kJ) ; (b) $\ce{SOCl2 + H2O -> SO2 + 2HCl}$ ($\Delta_rH^\circ=+49{,}5$ kJ). Quelles affirmations sont correctes ?

**Options**
- A. (a) : $K$ passe d'environ $5\times10^{5}$ à $0{,}17$ ; (a) est favorisée à basse température
- B. (b) : $K$ passe d'environ $8\times10^{8}$ à $2\times10^{12}$ ; (b) est favorisée à haute température
- C. Pour (a) comme pour (b), $K$ augmente avec la température, car tout équilibre se déplace vers les produits en chauffant
- D. Pour (b), $K$ diminue avec la température, car elle est endothermique

**Réponse correcte** : A, B

**Feedback correct**
Le signe de $\Delta_rH^\circ$ fixe le sens de variation de $K$ avec $T$ : négatif pour (a) ($K$ diminue), positif pour (b) ($K$ augmente).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Ce n'est vrai que pour les réactions endothermiques.
- Si D : Pour une réaction endothermique, $K$ augmente avec la température.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-symbo-eva-304
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: k-et-temperature--k-independant-de-la-temperature
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « Seul le quotient de réaction $Q$ change avec la température ; la constante d'équilibre $K$ est une constante. » Comment juger cette phrase ?

**Options**
- A. Fausse : $K$ dépend de $T$ (par $\Delta_rG^\circ=-RT\ln K$)
- B. Vraie : une constante d'équilibre ne dépend d'aucune variable, la température comprise
- C. Vraie, mais seulement pour les réactions entre gaz
- D. Fausse : $K$ dépend de la pression totale plutôt que de la température

**Réponse correcte** : A

**Feedback correct**
Exemple : $K=5\times10^{5}$ à 298 K et $0{,}17$ à 500 K pour la synthèse de $\ce{NH3}$. « Constante » veut dire indépendante de la composition, pas de la température.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Elle ne dépend pas de la composition, mais bien de la température.
- Si C : La distinction gaz / non-gaz n'intervient pas dans cette dépendance.
- Si D : $K$ standard ne dépend pas de la pression totale, mais de $T$.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-symbo-eva-305
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: k-et-temperature--chauffer-favorise-toujours-les-produits
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « Pour augmenter le rendement d'une réaction à l'équilibre, il suffit de chauffer, car la chaleur favorise les produits. » Quelle évaluation est correcte ?

**Options**
- A. Fausse : chauffer ne favorise les produits que si la réaction est endothermique
- B. Vraie : l'élévation de température augmente toujours la valeur de $K$, quelle que soit la réaction
- C. Vraie, sauf pour les réactions qui se déroulent uniquement en phase gazeuse
- D. Fausse : la température n'a jamais aucun effet sur la position de l'équilibre chimique

**Réponse correcte** : A

**Feedback correct**
Exemples : synthèse de $\ce{NH3}$ ($\Delta_rH^\circ<0$) : $K$ baisse de $5\times10^{5}$ à $0{,}17$ de 298 à 500 K ; décomposition de $\ce{CaCO3}$ ($\Delta_rH^\circ>0$) : $K$ augmente.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La règle dépend du signe de $\Delta_rH^\circ$.
- Si C : La phase n'est pas le critère : c'est le signe de $\Delta_rH^\circ$.
- Si D : La température agit directement sur $K$.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-k-et-temperature-macro-eva-306
concept: k-et-temperature
sous-partie: 9D
chapitre: thermochimie-2
niveau: OS
r1: macro
type: eva
misconception: temperature-inversion--formule-appliquee-malgre-changement-d-etat
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève calcule $K(400\ \text{K})$ pour $\ce{2H2O2(l) -> 2H2O(l) + O2(g)}$ par van't Hoff à partir de $K(298)$ et de $\Delta_rH^\circ=-196$ kJ, et conclut que le résultat est fiable. Comment juger ce calcul ?

**Options**
- A. Non fiable : à 400 K l'eau est gazeuse, donc $\Delta_rH^\circ$ n'est plus constant
- B. Fiable : la loi de van't Hoff s'applique sans aucune limite de température ni de changement d'état
- C. Fiable, tant que la valeur de $K(298)$ est connue avec une bonne précision expérimentale
- D. Non fiable parce que $\ce{H2O2}$ est instable, ce qui interdit toute mesure d'un équilibre

**Réponse correcte** : A

**Feedback correct**
La loi suppose $\Delta_rH^\circ$ constant, donc l'absence de changement d'état. L'eau bout à 373 K : au-delà, il faut recalculer avec $\ce{H2O(g)}$ ($\Delta_fH^\circ=-242$ kJ·mol⁻¹).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Elle n'est valable que dans un domaine de température sans changement d'état.
- Si C : La précision de $K(298)$ ne corrige pas l'erreur de modèle à 400 K.
- Si D : La stabilité cinétique n'est pas le critère invalidant ici.

**Référence manuel** : thermochimie-2-k-temperature

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-sou-001
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
misconception: enthalpie-libre-pile-electrolyse--delta-g-electrolyse-meme-signe-que-pile
date_validation: 2026-11-07
statut: validated
---

**Question**
Quel est le signe de $\Delta_rG^\circ$ de la réaction d'oxydo-réduction qui se produit dans une pile qui débite du courant ?

**Options**
- A. Négatif : la réaction est thermodynamiquement favorable (spontanée)
- B. Positif : la pile fournit de l'énergie, donc le système en perd moins qu'il n'en gagne
- C. Nul : une pile qui fonctionne est à l'équilibre
- D. On ne peut pas le dire : le signe dépend de la vitesse de la réaction

**Réponse correcte** : A

**Feedback correct**
Une pile utilise une réaction favorable : $\Delta_rG^\circ<0$ (pour la pile Daniell, $-212{,}6$ kJ·mol⁻¹). L'énergie libérée est récupérée en partie comme travail électrique.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : c'est l'électrolyse qui a $\Delta_rG^\circ>0$.
- Si C : À l'équilibre la pile est « à plat » : $\Delta_rG=0$, plus aucun courant ne circule.
- Si D : Le signe de $\Delta_rG^\circ$ ne dépend pas de la vitesse, il se calcule avec les $\Delta_fG^\circ$.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-sou-002
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
misconception: enthalpie-libre-pile-electrolyse--delta-g-electrolyse-meme-signe-que-pile
date_validation: 2026-11-07
statut: validated
---

**Question**
Une électrolyse impose la réaction inverse de celle d'une pile. Comment se comparent les deux valeurs de $\Delta_rG^\circ$ ?

**Options**
- A. Elles sont opposées : $\Delta_rG^\circ$(électrolyse) $= -\Delta_rG^\circ$(pile)
- B. Elles sont égales, seul le sens du courant change
- C. Elles sont inverses : $\Delta_rG^\circ$(électrolyse) $=1/\Delta_rG^\circ$(pile)
- D. Les deux sont nulles à l'équilibre

**Réponse correcte** : A

**Feedback correct**
Comme pour $\Delta_rH^\circ$ et $\Delta_rS^\circ$, inverser l'équation change le signe de $\Delta_rG^\circ$ : $-212{,}6$ kJ·mol⁻¹ pour la pile Daniell, $+212{,}6$ kJ·mol⁻¹ pour son électrolyse.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe change : une réaction favorable devient défavorable dans l'autre sens.
- Si C : Ce sont des fonctions additives, pas multiplicatives : l'inverse de l'équation donne l'opposé de $\Delta_rG^\circ$.
- Si D : $\Delta_rG^\circ$ n'est pas nul à l'équilibre, c'est $\Delta_rG$ qui s'annule.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-macro-com-003
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
misconception: enthalpie-libre-pile-electrolyse--electrolyse-spontanee-car-courant
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour décomposer l'eau en $\ce{H2}$ et $\ce{O2}$ ($\Delta_rG^\circ = +474$ kJ·mol⁻¹), un générateur est nécessaire. Quelle explication est correcte ?

**Options**
- A. La réaction est thermodynamiquement défavorable ; le générateur apporte l'énergie électrique qui manque
- B. La réaction est favorable mais très lente ; le générateur sert à l'accélérer
- C. Le générateur sert seulement à amorcer la réaction, qui se poursuit ensuite d'elle-même
- D. L'eau est un isolant : sans générateur, aucun électron ne circule, mais la réaction serait sinon favorable

**Réponse correcte** : A

**Feedback correct**
Avec $\Delta_rG^\circ>0$, la décomposition de l'eau n'est pas thermodynamiquement favorable : on doit fournir, de façon continue, au moins $474$ kJ par équation écrite sous forme de travail électrique.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Avec $\Delta_rG^\circ>0$ la réaction n'est pas « favorable mais lente » : elle est défavorable.
- Si C : Si on coupe le générateur, l'électrolyse s'arrête : l'énergie doit être fournie en continu.
- Si D : La conductivité de l'eau n'explique pas le signe de $\Delta_rG^\circ$ : même avec des ions, la réaction reste défavorable.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-com-004
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
date_validation: 2026-11-07
statut: validated
---

**Question**
La combustion de l'éthane et la pile Daniell ont toutes deux un $\Delta_rG^\circ$ négatif. Pourquoi seule la pile peut-elle fournir directement du courant électrique ?

**Options**
- A. En pile, les électrons passent par un circuit extérieur (travail électrique) ; en flamme, le transfert est direct
- B. Seule la pile est une réaction d'oxydo-réduction, la combustion est une réaction acide-base
- C. Le $\Delta_rG^\circ$ de la pile est positif, ce qui fournit de l'énergie électrique au circuit
- D. La combustion est trop exothermique : la chaleur détruit les électrons avant qu'ils ne circulent

**Réponse correcte** : A

**Feedback correct**
Le signe de $\Delta_rG^\circ$ dit seulement que la réaction est favorable. Le dispositif décide de la forme sous laquelle l'énergie est récupérée : en pile, en travail électrique ; en flamme, en chaleur.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La combustion est aussi une réaction d'oxydo-réduction (le carburant est oxydé, $\ce{O2}$ réduit).
- Si C : Le $\Delta_rG^\circ$ de la pile est négatif, comme pour toute réaction favorable.
- Si D : L'ampleur de l'exothermie n'empêche pas de récupérer l'énergie : tout dépend du montage.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-app-005
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-pile-electrolyse--delta-g-electrolyse-meme-signe-que-pile
date_validation: 2026-11-07
statut: validated
---

**Question**
À $298$ K, $\Delta_fG^\circ(\ce{Zn^{2+}}) = -147{,}1$ et $\Delta_fG^\circ(\ce{Cu^{2+}}) = +65{,}5$ kJ·mol⁻¹. Quel est $\Delta_rG^\circ$ de la pile $\ce{Zn(s) + Cu^{2+}(aq) -> Zn^{2+}(aq) + Cu(s)}$ ?

**Options**
- A. $-212{,}6$ kJ·mol⁻¹
- B. $+212{,}6$ kJ·mol⁻¹
- C. $-81{,}6$ kJ·mol⁻¹
- D. $-147{,}1$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = \Delta_fG^\circ(\ce{Zn^{2+}}) + 0 - \Delta_fG^\circ(\ce{Cu^{2+}}) - 0 = -147{,}1 - 65{,}5 = -212{,}6$ kJ·mol⁻¹ : très favorable.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : on a calculé réactifs moins produits.
- Si C : On a additionné $\Delta_fG^\circ(\ce{Cu^{2+}})$ au lieu de le soustraire : $-147{,}1 + 65{,}5 = -81{,}6$.
- Si D : Le terme du réactif $\ce{Cu^{2+}}$ a été oublié.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-app-006
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour l'électrolyse $\ce{2 H2O(l) -> 2 H2(g) + O2(g)}$, avec $\Delta_fG^\circ(\ce{H2O,l}) = -237{,}1$ kJ·mol⁻¹, quelle est la valeur de $\Delta_rG^\circ$ ?

**Options**
- A. $+474{,}2$ kJ·mol⁻¹
- B. $+237{,}1$ kJ·mol⁻¹
- C. $-474{,}2$ kJ·mol⁻¹
- D. $+948{,}4$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$\Delta_fG^\circ$ des corps simples vaut $0$ ; $\Delta_rG^\circ = 0 - 2\times(-237{,}1) = +474{,}2$ kJ·mol⁻¹ : l'opposé de la formation de $2$ mol d'eau.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le coefficient $2$ devant $\ce{H2O}$ a été oublié.
- Si C : Le signe est inversé : on a donné la valeur de la formation de l'eau (combustion du dihydrogène).
- Si D : Le coefficient a été appliqué deux fois ($2\times2$).

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-app-007
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Une pile à combustible consomme $\ce{H2 + 1/2 O2 -> H2O(l)}$ à $298$ K. Quelle est l'énergie électrique maximale récupérable par mole de $\ce{H2}$ ?

**Options**
- A. $237$ kJ
- B. $286$ kJ
- C. $474$ kJ
- D. $0$ kJ

**Réponse correcte** : A

**Feedback correct**
Le travail électrique maximal vaut $|\Delta_rG^\circ| = 237{,}1$ kJ·mol⁻¹. Il est inférieur à $|\Delta_rH^\circ| = 286$ kJ·mol⁻¹ : la différence ($T\,|\Delta_rS^\circ|\approx49$ kJ) est inévitablement cédée au milieu sous forme de chaleur.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $286$ kJ est $|\Delta_rH^\circ|$ : on a oublié le terme $T\,\Delta_rS^\circ$ ; l'énergie utile maximale est $|\Delta_rG^\circ|$.
- Si C : $474$ kJ correspond à $2$ mol d'eau (équation doublée), pas à $1$ mol de $\ce{H2}$.
- Si D : $\Delta_rG^\circ$ n'est pas nul : la réaction n'est pas à l'équilibre dans les conditions standard.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-app-008
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Une pile à combustible fonctionne avec $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$. Avec $\Delta_fG^\circ$ : $\ce{CH4}$ $-50{,}7$ ; $\ce{CO2}$ $-394{,}4$ ; $\ce{H2O,l}$ $-237{,}1$ kJ·mol⁻¹, quel est $\Delta_rG^\circ$ ?

**Options**
- A. $-817{,}9$ kJ·mol⁻¹
- B. $-800{,}9$ kJ·mol⁻¹
- C. $-919{,}3$ kJ·mol⁻¹
- D. $+817{,}9$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = (-394{,}4) + 2\times(-237{,}1) - (-50{,}7) - 0 = -817{,}9$ kJ·mol⁻¹. Le dioxygène, corps simple, ne contribue pas.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : On a utilisé $\Delta_fG^\circ(\ce{H2O,g}) = -228{,}6$ au lieu de celle de l'eau liquide : l'équation indique $\ce{H2O(l)}$.
- Si C : Le terme du réactif $\ce{CH4}$ a été additionné au lieu d'être soustrait.
- Si D : Le signe est inversé : on a calculé réactifs moins produits.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-ana-301
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--spontane-egal-rapide
date_validation: 2026-11-07
statut: validated
---

**Question**
Trois réactions à $298$ K : (a) $\ce{Zn + Cu^{2+} -> Zn^{2+} + Cu}$, $\Delta_rG^\circ = -212{,}6$ ; (b) $\ce{2 H2O -> 2 H2 + O2}$, $\Delta_rG^\circ = +474{,}2$ ; (c) combustion du propane, $\Delta_rG^\circ = -2077$ kJ·mol⁻¹. Quelles affirmations sont correctes ?

**Options**
- A. (a) peut servir de pile : elle est favorable et ses électrons peuvent passer par un circuit
- B. (b) ne se produit que si un générateur apporte l'énergie électrique : c'est une électrolyse
- C. (c) démarre toute seule dans l'air, puisque $\Delta_rG^\circ$ est très négatif
- D. (b) est impossible dans tous les cas, quel que soit le dispositif

**Réponse correcte** : A, B

**Feedback correct**
Le signe de $\Delta_rG^\circ$ distingue pile ($<0$) et électrolyse ($>0$). Le propane est très favorable thermodynamiquement mais ne s'enflamme que s'il est amorcé : la vitesse dépend de l'énergie d'activation. L'électrolyse de l'eau est réalisable en fournissant l'énergie électrique.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Très favorable ne veut pas dire rapide : il faut une étincelle pour franchir la barrière d'activation.
- Si D : « Défavorable » ne veut pas dire « impossible » : un générateur peut imposer la réaction.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-ana-302
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: enthalpie-libre-pile-electrolyse--delta-g-electrolyse-meme-signe-que-pile
date_validation: 2026-11-07
statut: validated
---

**Question**
La pile Daniell fournit $212{,}6$ kJ·mol⁻¹ de travail électrique maximal. On l'inverse en électrolyse. Quelles affirmations sont correctes ?

**Options**
- A. L'électrolyse exige au moins $212{,}6$ kJ·mol⁻¹ de travail électrique
- B. $\Delta_rG^\circ$ (électrolyse) vaut $+212{,}6$ kJ·mol⁻¹
- C. L'électrolyse fournit elle aussi $212{,}6$ kJ·mol⁻¹ au générateur
- D. La constante d'équilibre de l'électrolyse est la même que celle de la pile

**Réponse correcte** : A, B

**Feedback correct**
Les deux réactions sont inverses : $\Delta_rG^\circ$ change de signe et $K$ devient $1/K$. L'électrolyse consomme au moins l'énergie que la pile peut fournir au maximum.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Ce n'est pas une source d'énergie : une réaction défavorable demande un apport.
- Si D : $K$ devient $1/K$ quand on inverse l'équation (ici $\approx10^{-37}$).

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-macro-eva-303
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: macro
type: eva
misconception: enthalpie-libre-pile-electrolyse--electrolyse-spontanee-car-courant
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève observe des bulles dès que l'on branche un générateur sur de l'eau acidulée et affirme : « L'électrolyse de l'eau est spontanée, puisque la réaction a lieu toute seule dès que le circuit est fermé. » Comment juger cette phrase ?

**Options**
- A. Fausse : $\Delta_rG^\circ=+474$ kJ·mol⁻¹ ; la réaction est défavorable, le générateur lui apporte l'énergie
- B. Vraie : des bulles apparaissent dès que le circuit est fermé, donc la réaction est favorable
- C. Vraie : un générateur sert seulement à amorcer la réaction, qui continue ensuite d'elle-même sans apport
- D. Fausse : la réaction est impossible, les bulles viennent d'une autre source que l'eau

**Réponse correcte** : A

**Feedback correct**
Les bulles s'arrêtent dès que l'on coupe le générateur. Sans apport d'énergie électrique continu, $\Delta_rG^\circ>0$ interdit à la réaction de se poursuivre dans ce sens : l'électrolyse est imposée, pas thermodynamiquement favorable.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Observer une transformation ne prouve pas qu'elle soit favorable : elle peut être imposée de l'extérieur.
- Si C : Le générateur n'est pas une simple amorce : sans lui, rien ne se passe.
- Si D : La réaction n'est pas impossible : le générateur la réalise ; elle est seulement défavorable sans lui.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-pile-electrolyse-symbo-eva-304
concept: enthalpie-libre-pile-electrolyse
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « La combustion de $\ce{H2}$ dans une flamme libère plus d'énergie que la même réaction dans une pile à combustible, car $\Delta_rG^\circ$ est plus négatif en flamme. » Comment juger cette phrase ?

**Options**
- A. Fausse : $\Delta_rG^\circ$ ne dépend que de la réaction écrite et de $T$ ; seul le mode de récupération change
- B. Vraie : la flamme est bien plus chaude que la pile, donc $\Delta_rG^\circ$ y est plus négatif
- C. Vraie : dans une pile, une partie de $\Delta_rG^\circ$ est consommée par le circuit extérieur
- D. Fausse : la pile libère toujours plus d'énergie sous forme de chaleur que la flamme du même combustible

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ$ (comme $\Delta_rH^\circ$) est une fonction d'état : même réaction, mêmes états initial et final, même valeur ($-237$ kJ·mol⁻¹ par mole d'eau). En flamme, l'énergie part en chaleur ; en pile, jusqu'à $|\Delta_rG^\circ|$ peut être récupéré en électricité.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La température du dispositif ne modifie pas la valeur de $\Delta_rG^\circ$ à $298$ K.
- Si C : Dans la pile, le circuit récupère de l'énergie ; il n'en consomme pas.
- Si D : La flamme dissipe toute l'énergie en chaleur ; la pile peut en récupérer une part comme travail.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-sou-001
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
misconception: enthalpie-libre-et-potentiel--e-positif-delta-g-positif
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle relation lie l'enthalpie libre standard de réaction à la tension standard $E^\circ$ d'une pile ?

**Options**
- A. $\Delta_rG^\circ = -n\,F\,E^\circ$
- B. $\Delta_rG^\circ = +n\,F\,E^\circ$
- C. $\Delta_rG^\circ = -F\,E^\circ/n$
- D. $\Delta_rG^\circ = -n\,R\,T\,E^\circ$

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = -nFE^\circ$ : le travail électrique maximal fourni par la pile ($nF\,E^\circ$) est l'opposé de la variation d'enthalpie libre.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est perdu : une pile qui fonctionne a $\Delta_rG^\circ<0$ alors que $E^\circ>0$.
- Si C : $n$ multiplie : plus d'électrons échangés, plus de charge transportée.
- Si D : $R\,T$ intervient dans $\Delta_rG^\circ=-RT\ln K$, pas dans cette relation.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-sou-002
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-07
statut: validated
---

**Question**
Dans $\Delta_rG^\circ = -nFE^\circ$, que représente $n$ ?

**Options**
- A. Le nombre d'électrons échangés dans l'équation écrite
- B. Le nombre de moles de réactifs consommées par l'équation
- C. La charge de l'ion métallique le plus chargé de l'équation
- D. Le coefficient stœchiométrique du métal oxydé

**Réponse correcte** : A

**Feedback correct**
$n$ est le nombre d'électrons transférés pour l'équation écrite : $2$ pour $\ce{Zn + Cu^{2+} -> Zn^{2+} + Cu}$, $4$ pour $\ce{2 H2 + O2 -> 2 H2O}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Ce nombre ne compte pas les moles de réactifs, mais les électrons transférés.
- Si C : La charge d'un ion n'est pas toujours égale au nombre d'électrons échangés dans l'équation écrite.
- Si D : Le coefficient du métal ne donne pas nécessairement le nombre d'électrons : cf. $\ce{2 H2 + O2 -> 2 H2O}$ ($n=4$).

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-com-003
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: enthalpie-libre-et-potentiel--e-positif-delta-g-positif
date_validation: 2026-11-07
statut: validated
---

**Question**
Une pile a une tension standard $E^\circ>0$. Quelles conséquences sont correctes ?

**Options**
- A. $\Delta_rG^\circ<0$ et $K>1$ pour la réaction écrite
- B. La réaction écrite est thermodynamiquement favorable (spontanée) dans les conditions standard
- C. $\Delta_rG^\circ>0$ et $K<1$ pour la réaction écrite
- D. La réaction écrite exige un générateur pour se produire

**Réponse correcte** : A, B

**Feedback correct**
$E^\circ>0\iff\Delta_rG^\circ<0\iff K>1$. C'est le critère de la pile ; si $E^\circ<0$ pour la réaction écrite, c'est l'inverse qui est favorable et l'écrire demande un générateur.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Le signe est inversé à cause du « moins » de $\Delta_rG^\circ=-nFE^\circ$.
- Si D : C'est le cas $E^\circ<0$ qui demande un générateur (électrolyse).

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-com-004
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: enthalpie-libre-et-potentiel--e-proportionnel-a-la-quantite-de-matiere
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{H2 + 1/2 O2 -> H2O(l)}$ ($n=2$, $E^\circ = 1{,}23$ V), on double l'équation : $\ce{2 H2 + O2 -> 2 H2O(l)}$. Que deviennent $n$, $E^\circ$ et $\Delta_rG^\circ$ ?

**Options**
- A. $n$ passe à $4$, $E^\circ$ reste $1{,}23$ V et $\Delta_rG^\circ$ double
- B. $n$ passe à $4$, $E^\circ$ passe à $2{,}46$ V et $\Delta_rG^\circ$ double
- C. $n$ reste $2$, $E^\circ$ double et $\Delta_rG^\circ$ double
- D. $n$ passe à $4$, $E^\circ$ reste $1{,}23$ V et $\Delta_rG^\circ$ reste identique

**Réponse correcte** : A

**Feedback correct**
$E^\circ$ est une tension : elle ne dépend pas de la quantité de matière, donc de l'écriture de l'équation. $n$ et $\Delta_rG^\circ=-nFE^\circ$, eux, doublent ($-237\to-474$ kJ·mol⁻¹), et $K\to K^2$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Une tension n'est pas une grandeur extensive : doubler l'équation ne la double pas.
- Si C : $n$ compte les électrons de l'équation écrite : il double aussi.
- Si D : $\Delta_rG^\circ$ est extensive par rapport à l'équation : il double avec $n$ à $E^\circ$ constant.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-app-005
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-et-potentiel--e-positif-delta-g-positif
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la pile Daniell $\ce{Zn + Cu^{2+} -> Zn^{2+} + Cu}$, $n=2$ et $E^\circ = 0{,}34-(-0{,}76) = 1{,}10$ V. Quel est $\Delta_rG^\circ$ (avec $F=96\,500$ C·mol⁻¹) ?

**Options**
- A. $-212$ kJ·mol⁻¹
- B. $+212$ kJ·mol⁻¹
- C. $-106$ kJ·mol⁻¹
- D. $-212\,000$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG^\circ = -2\times96\,500\times1{,}10 = -212\,300$ J·mol⁻¹, soit $-212$ kJ·mol⁻¹, en accord avec $-212{,}6$ kJ·mol⁻¹ obtenu par les $\Delta_fG^\circ$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de $\Delta_rG^\circ$ est inversé : $E^\circ>0$ donne $\Delta_rG^\circ<0$.
- Si C : On a pris $n=1$ au lieu de $2$ : le résultat est divisé par deux.
- Si D : Le résultat est en joules : il faut diviser par $1\,000$ pour l'exprimer en kJ.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-app-006
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Quelle est la constante d'équilibre à $298$ K de la pile Daniell ($n=2$, $E^\circ=1{,}10$ V) ? On donne $\ln K = nFE^\circ/(RT)$.

**Options**
- A. $K\approx1{,}6\times10^{37}$
- B. $K\approx6\times10^{-38}$
- C. $K\approx4\times10^{18}$
- D. $K\approx1{,}1$

**Réponse correcte** : A

**Feedback correct**
$\ln K = 2\times96\,500\times1{,}10/(8{,}314\times298)=85{,}7$, d'où $K\approx1{,}6\times10^{37}$ : la réaction est quasi totale.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe de l'exposant est inversé : $E^\circ>0$ donne $K>1$.
- Si C : On a pris $n=1$ : $\ln K$ est divisé par $2$, $K$ est la racine carrée de la valeur correcte.
- Si D : On a confondu $K$ et $E^\circ$.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-app-007
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: enthalpie-libre-et-potentiel--e-positif-delta-g-positif
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{Zn(s) + Fe^{2+}(aq) -> Zn^{2+}(aq) + Fe(s)}$ ($E^\circ(\ce{Fe^{2+}/Fe}) = -0{,}41$ V ; $E^\circ(\ce{Zn^{2+}/Zn}) = -0{,}76$ V), quel est $\Delta_rG^\circ$ à $298$ K ?

**Options**
- A. $-67{,}6$ kJ·mol⁻¹
- B. $+67{,}6$ kJ·mol⁻¹
- C. $-33{,}8$ kJ·mol⁻¹
- D. $-135$ kJ·mol⁻¹

**Réponse correcte** : A

**Feedback correct**
$E^\circ = -0{,}41-(-0{,}76)=+0{,}35$ V ; $n=2$ ; $\Delta_rG^\circ = -2\times96\,500\times0{,}35 = -67\,550$ J·mol⁻¹, soit $-67{,}6$ kJ·mol⁻¹ : favorable.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : $E^\circ>0$ donne $\Delta_rG^\circ<0$.
- Si C : On a pris $n=1$ : le résultat est divisé par $2$.
- Si D : On a pris $n=4$ (somme des charges des deux ions) : le résultat est doublé.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-app-008
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
L'électrolyse $\ce{2 H2O -> 2 H2 + O2}$ a $\Delta_rG^\circ=+474{,}2$ kJ·mol⁻¹ et $n=4$. Quelle est la tension minimale à appliquer ?

**Options**
- A. $1{,}23$ V
- B. $2{,}46$ V
- C. $4{,}91$ V
- D. $0{,}61$ V

**Réponse correcte** : A

**Feedback correct**
$E^\circ = -\Delta_rG^\circ/(nF) = -474\,200/(4\times96\,500) = -1{,}23$ V : la tension minimale est $|E^\circ| = 1{,}23$ V (en pratique un peu plus à cause des surtensions).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : On a pris $n=2$ au lieu de $4$ : la tension est doublée.
- Si C : On a pris $n=1$ : la tension est multipliée par $4$.
- Si D : On a pris $n=8$ : la tension est divisée par $2$.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-ana-301
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-07
statut: validated
---

**Question**
À $298$ K : (1) $\ce{Zn + Fe^{2+} -> Zn^{2+} + Fe}$ ($E^\circ=0{,}35$ V, $n=2$) ; (2) $\ce{Fe + Cu^{2+} -> Fe^{2+} + Cu}$ ($E^\circ=0{,}75$ V, $n=2$) ; la somme (1)+(2) est la pile Daniell ($E^\circ=1{,}10$ V). Quelles affirmations sont correctes ?

**Options**
- A. Les $\Delta_rG^\circ$ s'additionnent : $-67{,}6 + (-144{,}8)\approx-212$ kJ·mol⁻¹
- B. Ici $n$ est le même ($2$) pour les trois réactions, donc les $E^\circ$ s'additionnent aussi
- C. Les $K$ s'additionnent : $K_1+K_2=K_{\text{Daniell}}$
- D. La réaction (2) est moins favorable que (1), car son $E^\circ$ est plus grand

**Réponse correcte** : A, B

**Feedback correct**
Comme pour $\Delta_rH^\circ$ (loi de Hess), ce sont les $\Delta_rG^\circ$ qui s'additionnent ; les $K$ se multiplient ($K_1K_2=K_{\text{Daniell}}$). Les $E^\circ$ ne s'additionnent que si $n$ est identique. Un $E^\circ$ plus grand signifie une réaction plus favorable.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Les constantes se multiplient quand on additionne des équations, elles ne s'additionnent pas.
- Si D : Un $E^\circ$ plus grand donne un $\Delta_rG^\circ$ plus négatif : plus favorable.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-ana-302
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
date_validation: 2026-11-07
statut: validated
---

**Question**
Une mole de $\ce{Zn}$ réagit dans la pile Daniell ($n=2$, $E^\circ=1{,}10$ V, $F=96\,500$ C·mol⁻¹). Quelles affirmations sont correctes ?

**Options**
- A. La charge qui traverse le circuit vaut $2\times96\,500=193\,000$ C
- B. Le travail électrique maximal est $193\,000\times1{,}10\approx212$ kJ
- C. La charge qui traverse le circuit vaut $96\,500$ C
- D. Le travail électrique maximal est de l'ordre de $1{,}1$ kJ

**Réponse correcte** : A, B

**Feedback correct**
Chaque mole de $\ce{Zn}$ cède $2$ mol d'électrons, soit $nF=193\,000$ C. Travail = charge × tension, soit $193000\ \text{C}\times1{,}10\ \text{V}\approx212$ kJ, qui est bien $|\Delta_rG^\circ|$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : On a oublié le facteur $n=2$ : une mole de $\ce{Zn}$ libère deux moles d'électrons.
- Si D : On a oublié la charge : un travail est le produit charge × tension.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-eva-303
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: enthalpie-libre-et-potentiel--e-positif-delta-g-positif
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « $\Delta_rG^\circ = +nFE^\circ$, donc la pile Daniell, avec $E^\circ=1{,}10$ V, a $\Delta_rG^\circ=+212$ kJ·mol⁻¹. » Comment juger cette phrase ?

**Options**
- A. Fausse : le signe est $-$ ; la pile Daniell est favorable, $\Delta_rG^\circ=-212$ kJ·mol⁻¹
- B. Correcte : une tension positive donne une enthalpie libre positive
- C. Correcte : le signe dépend de la convention choisie pour $n$, positive ou négative
- D. Fausse : la pile Daniell a $\Delta_rG^\circ=0$ puisqu'elle débite du courant

**Réponse correcte** : A

**Feedback correct**
Le travail électrique est fourni par le système (la pile) : il est compté négativement dans $\Delta_rG$. Une pile qui fonctionne a toujours $\Delta_rG^\circ<0$ pour $E^\circ>0$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Une tension positive correspond à une réaction favorable, donc à un $\Delta_rG^\circ$ négatif.
- Si C : $n$ est un nombre d'électrons, toujours positif ; le signe vient du « moins » de la formule.
- Si D : $\Delta_rG^\circ$ n'est pas nul : la pile n'est pas à l'équilibre quand elle débite du courant.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-enthalpie-libre-et-potentiel-symbo-eva-304
concept: enthalpie-libre-et-potentiel
sous-partie: 9E
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: enthalpie-libre-et-potentiel--e-proportionnel-a-la-quantite-de-matiere
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « Une pile Daniell avec dix fois plus de zinc et de solution de cuivre a une tension standard dix fois plus grande. » Comment juger cette phrase ?

**Options**
- A. Fausse : $E^\circ$ ne dépend pas de la quantité de matière ; la pile plus grosse fournit plus de charge, pas plus de tension
- B. Correcte : $E^\circ$ est proportionnelle à la quantité de réactifs engagés dans la pile
- C. Correcte : $E^\circ=-\Delta_rG^\circ/(nF)$, et $\Delta_rG^\circ$ est proportionnelle à la quantité de matière qui réagit
- D. Fausse : une pile plus grosse a une tension plus petite, car les électrons se répartissent

**Réponse correcte** : A

**Feedback correct**
$\Delta_rG$ (en kJ) est proportionnelle à la quantité qui réagit, mais $n$ l'est aussi : le rapport $\Delta_rG^\circ/(nF)$ ne change pas. La pile plus grosse débite plus longtemps ou plus de charge, avec la même tension de $1{,}10$ V.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : $E^\circ$ est une propriété des couples, pas de la quantité de matière.
- Si C : $n$ aussi croît avec la quantité qui réagit : il compense le $\Delta_rG^\circ$ plus grand.
- Si D : Les électrons ne « se répartissent » pas en diminuant la tension : la tension standard est inchangée.

**Référence manuel** : thermochimie-2-enthalpie-libre-redox

---

---
id: q-second-principe-symbo-sou-001
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
misconception: second-principe--entropie-du-systeme-seule-decide
date_validation: 2026-11-07
statut: validated
---

**Question**
Selon le deuxième principe, quelle condition caractérise un processus thermodynamiquement favorable (spontané) ?

**Options**
- A. $S_{\text{créée}} = \Delta S_{\text{sys}} + \Delta S_{\text{ext}} > 0$
- B. $\Delta S_{\text{sys}} > 0$ uniquement, sans considérer le milieu extérieur
- C. $\Delta H < 0$ uniquement, c'est-à-dire que la réaction soit exothermique
- D. $\Delta S_{\text{ext}} < 0$, c'est-à-dire que le milieu extérieur se « range »

**Réponse correcte** : A

**Feedback correct**
Un processus est favorable lorsque l'entropie créée dans l'Univers (système + milieu extérieur) est strictement positive.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le critère porte sur l'Univers : un système peut voir son entropie diminuer si le milieu extérieur compense.
- Si C : Le signe de $\Delta H$ ne suffit pas : il n'intervient que par $\Delta S_{\text{ext}} = -\Delta H/T$, à comparer à $\Delta S_{\text{sys}}$.
- Si D : Un $\Delta S_{\text{ext}}$ négatif est défavorable ; il doit être compensé par un $\Delta S_{\text{sys}}$ plus grand en valeur absolue.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-macro-com-002
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
À 25 °C, la fusion d'un glaçon dans un verre d'eau est thermodynamiquement favorable (spontanée), alors que la fusion est endothermique ($\Delta H_{\text{fus}} = +6{,}01$ kJ·mol⁻¹). Quelle explication est correcte ?

**Options**
- A. $\Delta S_{\text{sys}} = +22{,}0$ l'emporte sur $\Delta S_{\text{ext}} \approx -20{,}2$ : $S_{\text{créée}} > 0$ (J·K⁻¹·mol⁻¹)
- B. La fusion est en réalité exothermique dès que la température dépasse 0 °C, ce qui la rend thermodynamiquement favorable (spontanée)
- C. À 25 °C la fusion est rapide, et une transformation rapide est par définition une transformation favorable
- D. L'énergie est conservée lors de la fusion, donc le processus n'a pas besoin d'une entropie créée positive

**Réponse correcte** : A

**Feedback correct**
Le milieu fournit 6,01 kJ à 298 K : $\Delta S_{\text{ext}} = -6010/298 = -20{,}2\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Avec $\Delta S_{\text{sys}} = +22{,}0$, on trouve $S_{\text{créée}} \approx +1{,}8\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1} > 0$ : la fusion est favorable.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La fusion reste endothermique à toute température : elle absorbe de la chaleur du milieu.
- Si C : Favorable ne signifie pas rapide : la vitesse relève de la cinétique, le critère est $S_{\text{créée}} > 0$.
- Si D : La conservation de l'énergie (premier principe) ne dit rien du sens d'évolution ; c'est le deuxième principe qui le fixe.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-macro-com-003
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: macro
type: com
misconception: second-principe--spontane-egal-rapide
date_validation: 2026-11-07
statut: validated
---

**Question**
À température ambiante, le diamant se transforme spontanément en graphite, et pourtant un diamant reste intact pendant des millénaires. Que peut-on en conclure ?

**Options**
- A. Spontané indique le sens thermodynamiquement permis, pas la vitesse : la transformation est ici extrêmement lente
- B. Le diamant n'est en fait pas thermodynamiquement instable, et la transformation en graphite est impossible
- C. Le deuxième principe est violé car aucun changement n'est observé alors que la transformation est permise
- D. Une transformation spontanée se déroule toujours en quelques secondes au plus, quelles que soient les conditions

**Réponse correcte** : A

**Feedback correct**
Le deuxième principe prédit si une transformation est possible ($S_{\text{créée}} > 0$), jamais en combien de temps elle a lieu : c'est l'objet de la cinétique (barrière d'activation).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le diamant est bien métastable : le graphite est la forme stable aux conditions ambiantes.
- Si C : Le deuxième principe n'impose aucune durée : il n'y a pas de contradiction avec l'absence de changement observable.
- Si D : C'est précisément l'idée à corriger : « spontané » ne veut pas dire « rapide ».

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-symbo-app-004
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Une réaction libère 150 kJ de chaleur au milieu extérieur, maintenu à 27 °C. Quelle est la variation d'entropie du milieu extérieur ?

**Options**
- A. $\Delta S_{\text{ext}} = +500\ \text{J}\cdot\text{K}^{-1}$
- B. $\Delta S_{\text{ext}} = -500\ \text{J}\cdot\text{K}^{-1}$
- C. $\Delta S_{\text{ext}} = +5\,556\ \text{J}\cdot\text{K}^{-1}$
- D. $\Delta S_{\text{ext}} = +0{,}50\ \text{J}\cdot\text{K}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$T = 27 + 273 = 300$ K, $Q_{\text{reçue par le milieu}} = +150\,000$ J. $\Delta S_{\text{ext}} = -\Delta H/T = +150\,000/300 = +500\ \text{J}\cdot\text{K}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le milieu reçoit de la chaleur : son entropie augmente, le signe est positif ($\Delta S_{\text{ext}} = -\Delta H / T$ avec $\Delta H < 0$).
- Si C : La température doit être en kelvin : 27 °C = 300 K, et non 27.
- Si D : Il faut convertir les kJ en J avant de diviser : 150 kJ = 150 000 J.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-symbo-app-005
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: second-principe--entropie-du-systeme-seule-decide
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la synthèse de l'ammoniac, $\Delta_r H = -92$ kJ et $\Delta_r S = -199\ \text{J}\cdot\text{K}^{-1}$ à 298 K. Quelle est l'entropie créée par mole d'avancement ?

**Options**
- A. $S_{\text{créée}} \approx +110\ \text{J}\cdot\text{K}^{-1}$
- B. $S_{\text{créée}} = -199\ \text{J}\cdot\text{K}^{-1}$
- C. $S_{\text{créée}} \approx -508\ \text{J}\cdot\text{K}^{-1}$
- D. $S_{\text{créée}} \approx +309\ \text{J}\cdot\text{K}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$\Delta S_{\text{ext}} = +92\,000/298 \approx +309\ \text{J}\cdot\text{K}^{-1}$ ; $S_{\text{créée}} = -199 + 309 \approx +110\ \text{J}\cdot\text{K}^{-1}$ : la réaction est thermodynamiquement favorable (spontanée) à 298 K.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Ce n'est que $\Delta S_{\text{sys}}$ : il faut y ajouter $\Delta S_{\text{ext}} = -\Delta H/T$.
- Si C : Le signe de $\Delta S_{\text{ext}}$ est mal pris : une réaction exothermique augmente l'entropie du milieu.
- Si D : C'est $\Delta S_{\text{ext}}$ seul : il faut aussi tenir compte de $\Delta S_{\text{sys}}$ négatif.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-symbo-ana-301
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--entropie-du-systeme-seule-decide
date_validation: 2026-11-07
statut: validated
---

**Question**
Un corps chaud à 350 K cède 1 000 J de chaleur à un corps froid à 300 K ; chaque corps est assez grand pour que sa température ne change pas. Quelles affirmations sont correctes ?

**Options**
- A. L'entropie du corps chaud diminue d'environ $2{,}86\ \text{J}\cdot\text{K}^{-1}$
- B. L'entropie créée vaut environ $+0{,}48\ \text{J}\cdot\text{K}^{-1}$ : le transfert est thermodynamiquement favorable (spontané)
- C. Le transfert inverse (du froid vers le chaud) serait aussi permis, car l'énergie reste conservée
- D. L'entropie créée est nulle, puisque la chaleur perdue par l'un est exactement gagnée par l'autre

**Réponse correcte** : A, B

**Feedback correct**
$\Delta S_{\text{chaud}} = -1000/350 = -2{,}86$ et $\Delta S_{\text{froid}} = +1000/300 = +3{,}33\ \text{J}\cdot\text{K}^{-1}$, soit $S_{\text{créée}} = +0{,}48\ \text{J}\cdot\text{K}^{-1} > 0$. Le transfert inverse donnerait $-0{,}48\ \text{J}\cdot\text{K}^{-1}$ : impossible.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Le premier principe (énergie conservée) autorise les deux sens ; seul le deuxième principe impose le sens chaud → froid.
- Si D : L'énergie se conserve, pas l'entropie : les deux variations n'ont pas la même valeur absolue (1/350 ≠ 1/300), d'où $S_{\text{créée}} > 0$.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-symbo-ana-302
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--entropie-du-systeme-seule-decide
date_validation: 2026-11-07
statut: validated
---

**Question**
La congélation de l'eau libère $6{,}01$ kJ·mol⁻¹ ($\Delta S_{\text{sys}} = -22{,}0\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$). Le milieu est à $-10$ °C ($263{,}15$ K). Quelles affirmations sont correctes ?

**Options**
- A. $\Delta S_{\text{ext}} \approx +22{,}8\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $S_{\text{créée}} \approx +0{,}8\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : la congélation est thermodynamiquement favorable (spontanée) à $-10$ °C
- C. L'entropie du système diminue : la congélation viole le deuxième principe
- D. À 0 °C, $S_{\text{créée}}$ serait aussi nettement positive (environ +22)

**Réponse correcte** : A, B

**Feedback correct**
$\Delta S_{\text{ext}} = 6010/263{,}15 = +22{,}8$ ; $S_{\text{créée}} = -22{,}0 + 22{,}8 \approx +0{,}8 > 0$. À 0 °C (273,15 K) : $6010/273{,}15 = 22{,}0$, donc $S_{\text{créée}} = 0$ : c'est l'équilibre solide-liquide.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Seule l'entropie de l'Univers compte : le milieu compense la baisse du système.
- Si D : À 0 °C, $\Delta S_{\text{ext}} = +22{,}0$ compense exactement $\Delta S_{\text{sys}} = -22{,}0$ : $S_{\text{créée}} = 0$, équilibre.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-macro-eva-303
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: macro
type: eva
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « Une réaction exothermique est toujours thermodynamiquement favorable (spontanée). » Quelles affirmations permettent de l'évaluer correctement ?

**Options**
- A. Faux : la dissolution de $\ce{NH4NO3}$ est endothermique ($+26$ kJ·mol⁻¹) et pourtant favorable, car $\Delta S_{\text{sys}}$ est grande
- B. Faux : la synthèse de $\ce{NH3}$ ($\Delta_r H = -92$ kJ, $\Delta_r S = -199\ \text{J}\cdot\text{K}^{-1}$) cesse d'avoir $S_{\text{créée}} > 0$ au-dessus d'environ 462 K
- C. Vrai : un transfert de chaleur vers le milieu extérieur augmente toujours l'entropie totale
- D. Vrai : exothermique et favorable sont synonymes

**Réponse correcte** : A, B

**Feedback correct**
Le signe de $\Delta H$ ne fixe que $\Delta S_{\text{ext}} = -\Delta H/T$. Pour $\ce{NH3}$ : $S_{\text{créée}} = -199 + 92\,000/T$ s'annule à $T = 92\,000/199 \approx 462$ K, et devient négative au-delà.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : $\Delta S_{\text{ext}}$ augmente, mais $\Delta S_{\text{sys}}$ peut diminuer davantage : il faut sommer les deux.
- Si D : Ce sont deux notions distinctes : le signe de $\Delta H$ ne détermine pas le caractère favorable.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-macro-eva-304
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: macro
type: eva
misconception: second-principe--spontane-egal-rapide
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « La rouille du fer est thermodynamiquement favorable, donc un clou en fer plongé dans l'eau de mer sera complètement rouillé en quelques minutes. » Comment juger cette phrase ?

**Options**
- A. Partiellement correcte : la rouille est favorable, mais la durée dépend de la cinétique
- B. Elle est entièrement correcte : spontané veut dire rapide
- C. Elle est entièrement fausse : la rouille n'est pas spontanée
- D. La conclusion est correcte car l'eau de mer accélère toujours toute réaction spontanée

**Réponse correcte** : A

**Feedback correct**
Favorable thermodynamiquement ($S_{\text{créée}} > 0$) ne dit rien de la durée. La corrosion du fer s'étale sur des semaines à des années selon les conditions.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La rapidité relève de la cinétique (barrière d'activation, concentrations, catalyse), pas du deuxième principe.
- Si C : L'oxydation du fer à l'air et à l'eau est bien spontanée.
- Si D : Un milieu salin peut accélérer la corrosion, mais cela ne rend pas la transformation instantanée.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-symbo-com-010
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: second-principe--entropie-du-systeme-seule-decide
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi une réaction dont $\Delta S_{\text{sys}} < 0$ peut-elle quand même être thermodynamiquement favorable (spontanée) ?

**Options**
- A. Si elle est assez exothermique, $\Delta S_{\text{ext}} = -\Delta H/T$ dépasse $|\Delta S_{\text{sys}}|$ : $S_{\text{créée}} > 0$
- B. Parce que le deuxième principe ne s'applique qu'à l'énergie de l'Univers entier et jamais à l'entropie du système
- C. Parce que $\Delta S_{\text{sys}}$ n'intervient jamais dans le critère thermodynamique, seule la chaleur compte
- D. Parce que $\Delta S_{\text{ext}}$ est toujours nulle lorsque la pression reste constante pendant la réaction

**Réponse correcte** : A

**Feedback correct**
Le critère $S_{\text{créée}} = \Delta S_{\text{sys}} + \Delta S_{\text{ext}} > 0$ somme les deux termes : la chaleur cédée au milieu augmente son entropie et peut compenser la baisse du système.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : L'énoncé est confus : c'est l'entropie de l'Univers, pas de l'énergie, qui doit augmenter, et la compensation vient de $\Delta S_{\text{ext}}$.
- Si C : $\Delta S_{\text{sys}}$ intervient dans la somme ; ignorer ce terme conduit à des erreurs de signe.
- Si D : À pression constante, $\Delta S_{\text{ext}} = -\Delta H/T$ est généralement non nulle.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-symbo-ana-305
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
La dissolution de $\ce{NH4NO3}$ a $\Delta H = +26$ kJ·mol⁻¹ et $\Delta S_{\text{sys}} = +108\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ à 298 K. Quelles affirmations sont correctes ?

**Options**
- A. $\Delta S_{\text{ext}} \approx -87\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : le milieu perd de la chaleur
- B. $S_{\text{créée}} \approx +21\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : la dissolution est thermodynamiquement favorable (spontanée) malgré son caractère endothermique
- C. $\Delta S_{\text{ext}} \approx +87$ car la dissolution absorbe de la chaleur
- D. La dissolution est favorable parce qu'elle est exothermique

**Réponse correcte** : A, B

**Feedback correct**
Le milieu fournit 26 kJ : $\Delta S_{\text{ext}} = -26\,000/298 = -87{,}2$ ; $S_{\text{créée}} = 108 - 87{,}2 \approx +21$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Le système absorbe la chaleur, le milieu en perd : son entropie diminue, $\Delta S_{\text{ext}} = -\Delta H/T < 0$.
- Si D : La dissolution est endothermique ($\Delta H > 0$) : c'est la dispersion des ions, donc $\Delta S_{\text{sys}} > 0$, qui la rend favorable.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-symbo-app-012
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
Une réaction a $\Delta H = +40$ kJ et $\Delta S_{\text{sys}} = +110\ \text{J}\cdot\text{K}^{-1}$. Quelle est l'entropie créée à 400 K (en supposant $\Delta H$ et $\Delta S_{\text{sys}}$ constants) ?

**Options**
- A. $S_{\text{créée}} = +10\ \text{J}\cdot\text{K}^{-1}$ (thermodynamiquement favorable (spontanée) à 400 K)
- B. $S_{\text{créée}} = +210\ \text{J}\cdot\text{K}^{-1}$
- C. $S_{\text{créée}} = +110\ \text{J}\cdot\text{K}^{-1}$
- D. $S_{\text{créée}} = -10\ \text{J}\cdot\text{K}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$\Delta S_{\text{ext}} = -40\,000/400 = -100\ \text{J}\cdot\text{K}^{-1}$ ; $S_{\text{créée}} = 110 - 100 = +10\ \text{J}\cdot\text{K}^{-1}$. À 298 K elle serait de $110 - 134 = -24\ \text{J}\cdot\text{K}^{-1}$ : défavorable. Chauffer a rendu la réaction favorable.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le milieu fournit de la chaleur : $\Delta S_{\text{ext}}$ est négative.
- Si C : Il faut ajouter $\Delta S_{\text{ext}}$ (ici $-100$) : $\Delta S_{\text{sys}}$ seul ne décide pas.
- Si D : Le signe est inversé : $\Delta S_{\text{sys}}$ domine ($+110 > |-100|$).

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-second-principe-symbo-eva-306
concept: second-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: second-principe--entropie-du-systeme-seule-decide
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève dit : « Le réfrigérateur diminue l'entropie des aliments, ce qui contredit le deuxième principe. » Quelle réponse est correcte ?

**Options**
- A. Le raisonnement oublie le milieu : la cuisine gagne plus d'entropie que les aliments n'en perdent
- B. Le raisonnement est correct : un réfrigérateur est un contre-exemple au deuxième principe de la thermodynamique
- C. Le deuxième principe ne s'applique pas aux machines thermiques fonctionnant à l'électricité
- D. L'entropie des aliments ne diminue pas, car la température seule fixe la valeur de l'entropie d'un corps

**Réponse correcte** : A

**Feedback correct**
Le deuxième principe porte sur le système isolé « aliments + réfrigérateur + cuisine » : le moteur du frigo consomme de l'énergie électrique et rejette plus de chaleur à l'extérieur qu'il n'en retire à l'intérieur, de sorte que $S_{\text{créée}} > 0$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Une baisse locale d'entropie est permise si une hausse plus grande se produit ailleurs.
- Si C : Le deuxième principe s'applique à tous les processus, machines comprises.
- Si D : L'entropie dépend de l'état (T, quantité de matière, état physique…) : refroidir des aliments la diminue bien.

**Référence manuel** : thermochimie-2-spontaneite

---

---
id: q-temperature-inversion-symbo-com-001
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Que représente la température d'inversion $T_{\text{inv}} = \Delta H/\Delta S$ ?

**Options**
- A. La température où $\Delta G$ s'annule et change de signe (si $\Delta H$ et $\Delta S$ sont constants)
- B. La température à laquelle la réaction atteint sa vitesse maximale en conditions standard
- C. La température où $\Delta H$ s'annule, ce qui inverse le sens de l'échange de chaleur avec le milieu
- D. La température où l'entropie du système devient égale à celle du milieu extérieur dans tous les cas

**Réponse correcte** : A

**Feedback correct**
$\Delta G = \Delta H - T\Delta S = 0$ donne $T = \Delta H/\Delta S$ : de part et d'autre, le caractère favorable s'inverse.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La vitesse relève de la cinétique, pas de $T_{\text{inv}}$.
- Si C : $\Delta H$ ne s'annule pas avec la température dans ce modèle (il est supposé constant).
- Si D : $T_{\text{inv}}$ annule $S_{\text{créée}}$, pas la différence des entropies système/milieu.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-com-002
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour une réaction avec $\Delta H < 0$ et $\Delta S < 0$, de quel côté de $T_{\text{inv}}$ est-elle thermodynamiquement favorable (spontanée) ?

**Options**
- A. En dessous de $T_{\text{inv}}$ : à basse température, le terme $\Delta H$ domine
- B. Au-dessus de $T_{\text{inv}}$ : le terme $-T\Delta S$ domine à haute température
- C. À toute température, car l'enthalpie est négative
- D. À aucune température, car l'entropie diminue lors de la réaction

**Réponse correcte** : A

**Feedback correct**
$\Delta G = \Delta H - T\Delta S$ : à basse $T$ on a $\Delta G\approx\Delta H<0$ ; à haute $T$, $-T\Delta S>0$ l'emporte. Exemple : $\ce{N2 + 3H2 -> 2NH3}$ ($T_{\text{inv}} = 462$ K).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Avec $\Delta S<0$, le terme $-T\Delta S$ est positif et défavorable à haute température.
- Si C : Un $\Delta H<0$ ne suffit pas : à haute $T$, $-T\Delta S$ le dépasse.
- Si D : Un $\Delta S<0$ ne suffit pas à interdire la réaction : à basse $T$, $\Delta H$ domine.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-com-003
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi une réaction avec $\Delta H = -196$ kJ et $\Delta S = +125\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ n'a-t-elle pas de température d'inversion physique ?

**Options**
- A. Le calcul donne $T = \Delta H/\Delta S < 0$ : $\Delta G$ reste négative à toute température positive
- B. Le calcul donne $T = 0$ K, car l'enthalpie est négative
- C. Elle a une température d'inversion, mais très élevée, que le tableau ne permet pas de calculer
- D. Elle n'en a pas parce qu'elle est exothermique, ce qui l'empêche de s'inverser

**Réponse correcte** : A

**Feedback correct**
Les deux termes agissent dans le même sens ($\Delta H<0$ et $-T\Delta S<0$) : $\Delta G<0$ pour tout $T>0$. Le rapport $-196\,000/125 = -1\,568$ K n'a aucun sens physique.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le rapport n'est pas nul ; il est négatif.
- Si C : Le quotient se calcule avec les valeurs données : il vaut $-1\,568$ K, inaccessible.
- Si D : L'exothermicité seule ne détermine pas l'existence de $T_{\text{inv}}$ : c'est le signe commun de $\Delta H$ et $\Delta S$ qui compte.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-app-004
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: temperature-inversion--celsius-au-lieu-de-kelvin
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{N2O4(g) -> 2NO2(g)}$, $\Delta_rH^\circ = +57{,}2$ kJ et $\Delta_rS^\circ = +175{,}8\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelle est la température d'inversion ?

**Options**
- A. $T_{\text{inv}} \approx 325$ K
- B. $T_{\text{inv}} \approx 0{,}325$ K
- C. $T_{\text{inv}} \approx 598$ K
- D. $T_{\text{inv}} \approx 3{,}07$ K

**Réponse correcte** : A

**Feedback correct**
$T_{\text{inv}} = 57\,200/175{,}8 \approx 325$ K (52 °C) : au-dessus, la dissociation en $\ce{NO2}$ est thermodynamiquement favorable (spontanée).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Les kJ n'ont pas été convertis en J : $57{,}2/175{,}8 = 0{,}325$.
- Si C : On a ajouté 273 à une valeur déjà en kelvin.
- Si D : Le quotient est inversé : $\Delta S/\Delta H$ au lieu de $\Delta H/\Delta S$.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-app-005
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: temperature-inversion--celsius-au-lieu-de-kelvin
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{CaCO3(s) -> CaO(s) + CO2(g)}$, $\Delta_rH^\circ = +178$ kJ et $\Delta_rS^\circ = +160\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelle est la température d'inversion en °C ?

**Options**
- A. $\approx 839$ °C
- B. $\approx 1\,112$ °C
- C. $\approx 1\,385$ °C
- D. $\approx -272$ °C

**Réponse correcte** : A

**Feedback correct**
$T_{\text{inv}} = 178\,000/160 \approx 1\,112$ K, soit $1\,112 - 273 \approx 839$ °C : température du four à chaux.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La valeur de 1 112 est en kelvin ; il reste à convertir en degrés Celsius.
- Si C : On a ajouté 273 au lieu de le retrancher.
- Si D : Les kJ n'ont pas été convertis en J : $178/160 = 1{,}1$ K.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-app-006
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: temperature-inversion--celsius-au-lieu-de-kelvin
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{Fe2O3(s) + 3H2(g) -> 2Fe(s) + 3H2O(g)}$, $\Delta_rH^\circ = +98$ kJ et $\Delta_rS^\circ = +141\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. À partir de quelle température la réaction devient-elle thermodynamiquement favorable (spontanée) ?

**Options**
- A. Environ 695 K (≈ 420 °C)
- B. Environ 422 K
- C. Environ 1,44 K
- D. Elle n'est favorable à aucune température

**Réponse correcte** : A

**Feedback correct**
$T_{\text{inv}} = 98\,000/141 \approx 695$ K ; à 298 K, $\Delta G = 98 - 298\times0{,}141 = +56$ kJ (défavorable), à 800 K $\Delta G \approx -15$ kJ.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : 422 est la valeur en °C : l'unité a été confondue.
- Si C : Le quotient est inversé et les unités mal converties.
- Si D : $\Delta G>0$ à 298 K n'implique pas $\Delta G>0$ à toute $T$ : avec $\Delta S>0$, le terme $-T\Delta S$ finit par l'emporter.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-app-007
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: temperature-inversion--celsius-au-lieu-de-kelvin
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour $\ce{H2O(l) -> H2O(g)}$, $\Delta H = +40{,}7$ kJ et $\Delta S = +109\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelle température d'ébullition ($\Delta G = 0$) prévoit-on ?

**Options**
- A. $T \approx 373$ K (100 °C)
- B. $T \approx 298$ K (25 °C)
- C. $T \approx 0{,}373$ K
- D. $T \approx 646$ K

**Réponse correcte** : A

**Feedback correct**
$T = 40\,700/109 \approx 373$ K : à cette température, liquide et vapeur sont en équilibre sous 1 bar.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : 298 K est la température de référence des tables, pas la solution de $\Delta G=0$.
- Si C : Les kJ n'ont pas été convertis en J.
- Si D : On a ajouté 273 à une valeur déjà en kelvin.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-ana-301
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Quatre réactions : (A) $\Delta H = -92$ kJ, $\Delta S = -199\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ ; (B) $\Delta H = +178$ kJ, $\Delta S = +160\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ ; (C) $\Delta H = -196$ kJ, $\Delta S = +125\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ ; (D) $\Delta H = +285$ kJ, $\Delta S = -137\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. Quelles affirmations sont correctes ?

**Options**
- A. (A) et (B) ont une température d'inversion positive (462 K et 1 112 K)
- B. (C) est thermodynamiquement favorable (spontanée) à toute température et (D) n'est favorable à aucune
- C. (C) a une température d'inversion de $-1\,568$ K, donc elle devient favorable sous 0 K
- D. (A) est favorable au-dessus de 462 K et (B) au-dessous de 1 112 K

**Réponse correcte** : A, B

**Feedback correct**
(A) : $\Delta H<0,\Delta S<0$, favorable en dessous de 462 K. (B) : $\Delta H>0,\Delta S>0$, favorable au-dessus de 1 112 K. (C) : $\Delta H<0,\Delta S>0$, toujours. (D) : $\Delta H>0,\Delta S<0$, jamais.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : Une température négative en kelvin n'existe pas : il n'y a simplement pas d'inversion.
- Si D : Les deux sens sont inversés : (A) est favorable en dessous et (B) au-dessus de leur $T_{\text{inv}}$.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-ana-302
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: ana
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour la réduction $\ce{Fe2O3(s) + 3H2(g) -> 2Fe(s) + 3H2O(g)}$ ($\Delta H = +98$ kJ ; $\Delta S = +141\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$, constants), quelles affirmations sont correctes ?

**Options**
- A. À 298 K, $\Delta G \approx +56$ kJ : la réduction est thermodynamiquement défavorable (non spontanée)
- B. À 800 K, $\Delta G \approx -15$ kJ : la réduction est favorable
- C. La réaction est favorable à toute température, car $\Delta S>0$
- D. À 800 K, $\Delta G \approx +113$ kJ : la réaction est encore moins favorable qu'à 298 K

**Réponse correcte** : A, B

**Feedback correct**
$\Delta G(T) = 98 - 0{,}141\,T$ (kJ) : positive en dessous de 695 K, négative au-dessus. L'entropie favorable ne prend le dessus qu'à haute température.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : À 298 K le terme $\Delta H = +98$ domine : $\Delta G>0$.
- Si D : À 800 K, $\Delta G = 98 - 112{,}8 = -14{,}8$ kJ et non $+113$ (le terme $T\Delta S$ vaut 113 kJ, il est soustrait).

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-macro-eva-303
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: macro
type: eva
misconception: temperature-inversion--formule-appliquee-malgre-changement-d-etat
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève calcule $\Delta G$ à 400 K pour $\ce{2H2O2(l) -> 2H2O(l) + O2(g)}$ avec $\Delta H = -196$ kJ et $\Delta S = +125\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ (valeurs à 298 K, eau liquide). Comment juger ce calcul ?

**Options**
- A. Invalide : à 400 K l'eau est gazeuse ; $\Delta H$ et $\Delta S$ ne sont plus ceux de l'eau liquide
- B. Valide : $\Delta H$ et $\Delta S$ sont toujours constants, quelle que soit la température
- C. Valide, car on peut utiliser ces données jusqu'à la température de décomposition de $\ce{H2O2}$
- D. Invalide, car il faut toujours utiliser les valeurs de $\Delta H$ et $\Delta S$ à 0 K

**Réponse correcte** : A

**Feedback correct**
Le modèle ($\Delta H$, $\Delta S$ constants) suppose qu'aucune espèce ne change d'état. L'eau bout à 373 K : à 400 K, il faut recalculer avec $\ce{H2O(g)}$ ($\Delta_fH^\circ = -242$, $S^\circ = 189$).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Ils ne sont constants que tant qu'aucune espèce ne change d'état.
- Si C : Le critère est le changement d'état de l'eau (373 K) et non la décomposition de $\ce{H2O2}$.
- Si D : Le troisième principe donne le zéro de $S$, pas les conditions d'application de ce modèle.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-eva-304
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: second-principe--exothermique-egale-spontane
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève trouve $T_{\text{inv}} = 325$ K pour $\ce{N2O4(g) -> 2NO2(g)}$ ($\Delta H = +57{,}2$ kJ ; $\Delta S = +175{,}8\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$) et conclut : « la dissociation est thermodynamiquement favorable (spontanée) en dessous de 325 K. » Quelle est la bonne évaluation ?

**Options**
- A. Fausse : avec $\Delta H>0$ et $\Delta S>0$, la dissociation est favorable **au-dessus** de 325 K
- B. Correcte : une réaction endothermique est défavorisée à haute température
- C. Correcte, car l'entropie augmente donc elle est favorable à basse température
- D. Fausse : la dissociation est favorable à toutes les températures, puisque $\Delta S>0$

**Réponse correcte** : A

**Feedback correct**
Au-dessus de 325 K, $-T\Delta S$ l'emporte sur $\Delta H$ et $\Delta G<0$. En dessous, c'est la dimérisation $\ce{2NO2 -> N2O4}$ qui est favorable.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Pour $\Delta S>0$, chauffer renforce le terme entropique : c'est l'inverse.
- Si C : Le terme entropique grandit avec $T$ : c'est à haute température qu'il domine.
- Si D : À basse température, $\Delta H>0$ domine et $\Delta G>0$.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-temperature-inversion-symbo-eva-305
concept: temperature-inversion
sous-partie: 9C
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: temperature-inversion--celsius-au-lieu-de-kelvin
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « La synthèse de l'ammoniac cesse d'être thermodynamiquement favorable (spontanée) au-dessus de $T_{\text{inv}} = 462$ °C. » Comment juger cette phrase ?

**Options**
- A. Erreur d'unité : $T_{\text{inv}} = 462$ K, soit environ 189 °C
- B. Correcte : $T_{\text{inv}}$ se calcule en degrés Celsius
- C. Correcte : l'unité n'a pas d'importance, car $\Delta G$ s'annule dans les deux échelles
- D. Fausse : la synthèse est favorable à toute température

**Réponse correcte** : A

**Feedback correct**
Le quotient $\Delta H/\Delta S$ est une température absolue (kelvin). 462 K $= 462 - 273 \approx 189$ °C.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le calcul en kelvin donne 462 K ; la conversion en Celsius est une étape distincte.
- Si C : Les échelles diffèrent d'un décalage de 273 : 462 °C est une tout autre température (735 K).
- Si D : La synthèse n'est pas favorable à toute $T$ (cas 3) ; elle l'est en dessous de 462 K.

**Référence manuel** : thermochimie-2-temperature-inversion

---

---
id: q-troisieme-principe-symbo-sou-001
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
Quel énoncé correspond au troisième principe de la thermodynamique ?

**Options**
- A. L'entropie d'un cristal parfait à 0 K est nulle
- B. L'entropie de tout corps pur dans son état standard à 298 K est nulle, par convention
- C. L'entropie d'un corps simple dans son état de référence est nulle, à toute température
- D. L'entropie d'un gaz parfait est nulle à 0 °C

**Réponse correcte** : A

**Feedback correct**
Le troisième principe (Nernst, Planck) fixe le zéro de l'échelle d'entropie : $S = 0$ pour un cristal parfait à 0 K, car un seul microétat est accessible ($W = 1$).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : À 298 K, l'énergie thermique peuple de nombreux microétats : $S^\circ > 0$ pour toute substance.
- Si C : Ce zéro de convention est celui de $\Delta_fH^\circ$ (corps simples), pas celui de $S$.
- Si D : 0 °C n'est pas 0 K : le zéro de l'entropie n'a rien à voir avec la température de congélation.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-symbo-sou-002
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: sou
date_validation: 2026-11-07
statut: validated
---

**Question**
Qui a énoncé en 1906 le principe selon lequel l'entropie s'annule au zéro absolu pour un cristal parfait ?

**Options**
- A. Walther Nernst
- B. Rudolf Clausius
- C. Ludwig Boltzmann
- D. Josiah Willard Gibbs

**Réponse correcte** : A

**Feedback correct**
Nernst a posé en 1906 le « théorème de la chaleur » qui deviendra le troisième principe ; Planck lui a ensuite donné la forme $S(0\,\text{K}) = 0$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Clausius a introduit le mot et le concept d'entropie (1865), pas son zéro.
- Si C : Boltzmann a relié $S$ au nombre de microétats ($S = k_B\ln W$).
- Si D : Gibbs est l'auteur de l'enthalpie libre ($G = H - TS$).

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-parti-com-003
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: parti
type: com
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi l'entropie d'un cristal parfait à 0 K est-elle nulle ?

**Options**
- A. Un seul arrangement des particules est possible : $W = 1$, donc $S = k_B\ln 1 = 0$
- B. Les particules s'arrêtent de se déplacer, donc leur énergie disparaît et il ne reste plus d'état possible
- C. À 0 K, la chaleur échangée est toujours nulle, et $S = Q/T$ s'annule
- D. Par convention, comme pour l'enthalpie de formation des corps simples

**Réponse correcte** : A

**Feedback correct**
À 0 K, le cristal parfait n'a qu'un microétat accessible ; avec $S = k_B\ln W$ et $W = 1$, on obtient $S = 0$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : L'énergie ne disparaît pas ; c'est le nombre de microétats qui tombe à 1.
- Si C : $S = Q/T$ ne définit pas $S$ à 0 K : le zéro découle du comptage $W = 1$.
- Si D : Contrairement à $\Delta_fH^\circ$, ce zéro n'est pas arbitraire : il résulte de la physique statistique.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-symbo-com-004
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
On lit $S^\circ(\ce{O2}) = 205\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ et $\Delta_fH^\circ(\ce{O2}) = 0$ kJ·mol⁻¹. Quelle interprétation est correcte ?

**Options**
- A. $\Delta_fH^\circ = 0$ est une convention ; $S^\circ > 0$ est une valeur absolue (agitation thermique à 298 K)
- B. Les deux zéros ont la même origine, une convention pour les corps simples : $S^\circ(\ce{O2})$ devrait aussi valoir 0
- C. $S^\circ(\ce{O2})$ est positive uniquement parce que $\ce{O2}$ est un gaz, et le troisième principe ne s'y applique pas
- D. Le tableau est faux : un corps simple a toujours une entropie nulle dans son état standard

**Réponse correcte** : A

**Feedback correct**
L'enthalpie n'a pas de zéro naturel (on choisit la référence des corps simples) ; l'entropie en a un grâce au troisième principe, donc $S^\circ$ est une valeur absolue, strictement positive à 298 K.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La convention ne concerne que $\Delta_fH^\circ$ (et $\Delta_fG^\circ$) ; $S^\circ$ est absolue.
- Si C : Même les solides ont $S^\circ > 0$ à 298 K ($S^\circ(\ce{Fe}) = 27$) : le troisième principe s'applique à tous.
- Si D : La table est correcte : tous les $S^\circ$ tabulés sont positifs, y compris pour les corps simples.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-symbo-com-005
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: com
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
Pourquoi peut-on tabuler des entropies absolues $S^\circ$, alors qu'on ne tabule que des variations d'enthalpie $\Delta_fH^\circ$ ?

**Options**
- A. Le troisième principe fournit un zéro naturel à l'entropie, alors que l'énergie et l'enthalpie n'ont pas de zéro absolu
- B. Parce que l'entropie est toujours plus facile à mesurer que l'enthalpie, quel que soit le système étudié
- C. Parce que l'entropie est une fonction d'état alors que l'enthalpie est une grandeur qui dépend du chemin suivi
- D. Parce que l'entropie d'un corps vaut toujours exactement $k_B$ par mole de matière, quelle que soit la substance

**Réponse correcte** : A

**Feedback correct**
L'entropie se mesure à partir de $S(0\,\text{K}) = 0$ en intégrant $C_p/T$, sans référence arbitraire ; pour l'enthalpie, on doit choisir une référence (les corps simples).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La difficulté de la mesure n'est pas le critère : c'est l'existence d'un zéro physique.
- Si C : $H$ et $S$ sont toutes deux des fonctions d'état.
- Si D : $S$ dépend de la substance, de l'état et de la température.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-symbo-app-006
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
Calculer $\Delta_rS^\circ$ pour $\ce{H2(g) + 1/2 O2(g) -> H2O(l)}$ avec $S^\circ(\ce{H2}) = 131$, $S^\circ(\ce{O2}) = 205$, $S^\circ(\ce{H2O,l}) = 70\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Options**
- A. $\Delta_rS^\circ = -163{,}5\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $\Delta_rS^\circ = +70\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ (on suppose nulles les entropies des corps simples)
- C. $\Delta_rS^\circ = +163{,}5\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ (réactifs − produits)
- D. $\Delta_rS^\circ = -266\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ (coefficient 1 pour $\ce{O2}$)

**Réponse correcte** : A

**Feedback correct**
$\Delta_rS^\circ = 70 - 131 - \tfrac12\times205 = -163{,}5\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$. L'entropie diminue : trois entités gazeuses donnent un liquide.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Les corps simples n'ont pas $S^\circ = 0$ : il faut soustraire $S^\circ(\ce{H2})$ et $S^\circ(\ce{O2})$.
- Si C : Le calcul est « produits − réactifs » ; l'inverse change le signe.
- Si D : Le coefficient stœchiométrique de $\ce{O2}$ vaut $\tfrac12$, pas 1.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-symbo-app-007
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
On chauffe 1 mol d'eau liquide de 298 K à 350 K ($C_p = 75{,}3\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$, constante). Quelle est la variation d'entropie ?

**Options**
- A. $\Delta S = C_p\ln(350/298) \approx +12{,}1\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $\Delta S = C_p\,\Delta T/350 \approx +11{,}2\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $\Delta S = C_p\,\Delta T/298 \approx +13{,}1\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $\Delta S = C_p\,\Delta T \approx +3\,916\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
Pour $C_p$ constante : $\Delta S = \int C_p\,dT/T = C_p\ln(T_2/T_1) = 75{,}3\times0{,}1609 \approx +12{,}1\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Diviser par la température finale sous-estime : $T$ varie pendant le chauffage, il faut intégrer.
- Si C : Diviser par la température initiale surestime : l'intégrale $\int dT/T$ vaut $\ln(T_2/T_1)$.
- Si D : Sans division par $T$, on obtient une chaleur échangée ($Q = C_p\Delta T$), pas une entropie.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-symbo-app-008
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: app
date_validation: 2026-11-07
statut: validated
---

**Question**
D'après la table ($S^\circ(\ce{H2O,l}) = 70$ et $S^\circ(\ce{H2O,g}) = 189\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$), quelle est $\Delta S^\circ$ de $\ce{H2O(l) -> H2O(g)}$ à 298 K ?

**Options**
- A. $+119\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. $-119\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- C. $+259\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. $+0{,}119\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$

**Réponse correcte** : A

**Feedback correct**
$\Delta S^\circ = S^\circ(\text{gaz}) - S^\circ(\text{liquide}) = 189 - 70 = +119\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ : le gaz est bien plus dispersé que le liquide.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le signe est inversé : on retranche l'entropie de l'état initial (liquide).
- Si C : On soustrait, on n'additionne pas les deux entropies.
- Si D : Il s'agit de J, pas de kJ : l'ordre de grandeur est une centaine de J·K⁻¹·mol⁻¹.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-macro-ana-301
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: macro
type: ana
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
Pour l'eau chauffée à pression constante de 0 K à plus de 373 K, la courbe $S(T)$ croît avec des sauts. Quelles affirmations sont correctes ?

**Options**
- A. Dans chaque phase, $S$ augmente avec $T$ (car $C_p > 0$)
- B. À la fusion et à la vaporisation, $S$ saute (de $\Delta H/T$), le saut étant bien plus grand pour la vaporisation
- C. Pendant la vaporisation, $S$ diminue car l'eau absorbe de la chaleur
- D. Quand $T \to 0$ K, $S$ tend vers une valeur positive non nulle pour le cristal parfait

**Réponse correcte** : A, B

**Feedback correct**
Entre deux changements d'état, $dS = C_p\,dT/T > 0$. Aux changements d'état, $\Delta S = \Delta H/T$ : 22 J·K⁻¹·mol⁻¹ à la fusion, 109 à la vaporisation.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : L'absorption de chaleur à $T$ constante augmente l'entropie ($\Delta S = Q/T > 0$).
- Si D : Le troisième principe impose $S \to 0$ quand $T \to 0$ K pour un cristal parfait.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-symbo-eva-302
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève écrit : « L'entropie d'un corps pur est nulle à 298 K. » Quelles affirmations permettent de juger cette phrase ?

**Options**
- A. Elle est fausse : les $S^\circ$ tabulés à 298 K sont strictement positifs (ex. $S^\circ(\ce{Fe}) = 27$, $S^\circ(\text{graphite}) = 5{,}7\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$)
- B. Le zéro de l'entropie est atteint seulement à 0 K, pour un cristal parfait
- C. Elle est vraie pour les corps simples dans leur état standard, comme pour $\Delta_fH^\circ$ qui est nulle par convention
- D. L'entropie n'est définie qu'à une constante près, choisie par convention comme l'énergie potentielle

**Réponse correcte** : A, B

**Feedback correct**
Le troisième principe donne un zéro absolu à 0 K ; à 298 K tout corps a une entropie positive. Le zéro conventionnel de 298 K ne concerne que $\Delta_fH^\circ$ et $\Delta_fG^\circ$.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : C'est une bonne réponse.
- Si C : C'est justement la confusion à éviter : $S^\circ(\ce{O2}) = 205$, $S^\circ(\ce{H2}) = 131$.
- Si D : L'entropie n'est pas définie à une constante près : le troisième principe fixe son zéro.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-symbo-eva-303
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève calcule $\Delta_rS^\circ$ pour $\ce{N2 + 3H2 -> 2NH3}$ ainsi : « les corps simples ont une entropie nulle, donc $\Delta_rS^\circ = 2\times193 = +386\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ ». Quelle évaluation est correcte ?

**Options**
- A. Erreur : $S^\circ(\ce{N2}) = 192$ et $S^\circ(\ce{H2}) = 131$ ne sont pas nulles ; le bon résultat est $386 - 192 - 3\times131 = -199\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- B. Calcul correct : le troisième principe annule l'entropie des corps simples dans leur état standard à 298 K
- C. Calcul correct sur le fond, mais le résultat doit être exprimé en kJ·mol⁻¹ : $+0{,}386\ \text{kJ}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$
- D. Erreur de signe seulement : le résultat correct est $-386\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$, car le gaz se resserre

**Réponse correcte** : A

**Feedback correct**
Le raisonnement transpose à $S^\circ$ la convention valable pour $\Delta_fH^\circ$. Avec les valeurs de la table : $\Delta_rS^\circ = 386 - (192 + 393) = -199\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ ; la réaction diminue l'entropie (4 mol de gaz → 2 mol).

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : Le troisième principe annule $S$ à 0 K, pas à 298 K.
- Si C : Le problème est de fond, pas d'unité.
- Si D : Le signe n'est pas le seul problème : il manque les entropies des réactifs.

**Référence manuel** : thermochimie-2-troisieme-principe

---

---
id: q-troisieme-principe-symbo-eva-304
concept: troisieme-principe
sous-partie: 9A
chapitre: thermochimie-2
niveau: OS
r1: symbo
type: eva
misconception: troisieme-principe--entropie-element-nulle-comme-enthalpie-formation
date_validation: 2026-11-07
statut: validated
---

**Question**
Un élève affirme : « $S^\circ$ augmente avec la masse molaire : $\ce{I2(s)}$ (254 g·mol⁻¹) a donc plus d'entropie que $\ce{H2O(g)}$ (18 g·mol⁻¹). » Comment juger cette phrase ?

**Options**
- A. Fausse : $S^\circ(\ce{H2O,g}) = 189$ est supérieure à $S^\circ(\ce{I2,s}) = 116\ \text{J}\cdot\text{K}^{-1}\cdot\text{mol}^{-1}$ ; l'état physique pèse plus que la masse
- B. Vraie : plus une molécule est lourde, plus elle a de microétats accessibles, quel que soit son état physique
- C. Vraie, car les solides, plus compacts, ont des entropies plus élevées que les gaz
- D. Fausse, car $S^\circ$ ne dépend ni de la masse ni de l'état physique, seulement de la température

**Réponse correcte** : A

**Feedback correct**
Les gaz, où la matière est très dispersée, ont des entropies bien supérieures à celles des solides. La masse joue un rôle secondaire par rapport à l'état physique.

**Feedback incorrect**
- Si A : C'est une bonne réponse.
- Si B : La table montre le contraire : un gaz léger dépasse un solide lourd.
- Si C : Les solides, plus ordonnés, ont les plus faibles entropies : $S^\circ(\ce{Fe}) = 27$, $S^\circ(\ce{O2,g}) = 205$.
- Si D : $S^\circ$ dépend de la substance, de son état et de sa structure (ici tabulée à 298 K).

**Référence manuel** : thermochimie-2-troisieme-principe

