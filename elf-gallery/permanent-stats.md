# General Abilities

General Abilities are the various parameters of an elf in a battle. Each elf has 15 ability values, including HP, ATK, SPE, ADF, CRE, CRI, DAM, ARM, HIT, AGI, INT, STA, STR, POT, and EAV.

**HP（Hit Points）**

Represents a character's health. Combatants are K.O.ed if their HP reaches 0.

#### ATK（Attack Power）

Attack is a type of elf ability. The high-attack elf uses moves that cause high damage.

ATK=DAM\*1+ADF\*1+ARM\*1+HP\*0.1+SPE+HIT\*2+EVA\*2.4+CRI\*2+CRE\*2

**SPE（Speed）**

Decreses the time between a character's turms, allowing them to act more frequently.

**ADF（Magic Defense）**

Decreases the damage received from magic attacks.

**CRE（Critical Resistance）**

......

**CRI（Critical）**

Represents deal critical damage.

**DAM（Damage）**

......

**ARM（Armor）**

......

**HIT**

......

**AGI（Agility）**

Increases the likelihood of evading physical attacks.

**INT（Intelligence）**

......

**STA（Stamina）**

Increases the damage dealt by attacks and physical crafts.

**STR（Strength）**

Increases the damage dealt by attacks and physical crafts.

**POT（Potential）**

......

**EVA（vasion）**

|   |   |
| - | - |
|   |   |
|   |   |
|   |   |

Represents the chance to evade attacks an crafts without fail.

x=level, i=evolution times, N=(STA/STR/AGI/INT), n=( +sta/ +str/ +agi/ +int )

$$
f(x) =n (x -1)* 1.17^{ 4i}+N
$$

