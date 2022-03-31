# General Abilities

General Abilities are the various parameters of an elf in a battle. Each elf has 15 ability values, including HP, ATK, SPE, ADF, CRE, CRI, DAM, ARM, HIT, AGI, INT, STA, STR, POT, and EAV.

| Short name | Complete name       |
| ---------- | ------------------- |
| ATK        | Attack Power        |
| HP         | Hit Points          |
| POT        | Potential           |
| STA        | Stamina             |
| _+sta_     | Stamina Growth      |
| STR        | Strength            |
| _+str_     | Strength Growth     |
| AGI        | Agility             |
| _+agi_     | Agility Growth      |
| INT        | Intelligence        |
| _+int_     | Intelligence Growth |
| DAM        | Damage              |
| ADF        | Magic Defense       |
| ARM        | Armor               |
| CRE        | Critical Resistance |
| CRI        | Critical            |
| EVA        | Vasion              |
| HIT        | Hit                 |
| SPE        | Speed               |

HP = STA\*10

_ATK = DAM\*1 + ADF\*1 + ARM\*1 +HP\*0.1 + SPE\*1 + HIT\*2 + EVA\*2.4 +CRI\*2 + CRE\*2_

#### Growth formula，about STA ， STR ， AGI ， INT  :&#x20;

$$
f(x) =n (x -1)* 1.17^{ i*4}+N
$$

x=Level

i=Number of Evolution

N=( STA / STR / AGI / INT )

n=( _+sta / +str / +agi / +int_ )
