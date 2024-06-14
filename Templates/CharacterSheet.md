---
STR: 10
DEX: 10
CON: 10
INT: 10
WIS: 10
CHA: 10
Prof1: false
Prof: 2
Prof5: false
Prof6: false
Prof7: false
Prof8: false
Prof9: false
Prof10: false
Prof16: false
Prof20: false
Prof12: false
Prof2: false
Prof23: false
Prof24: false
Prof18: false
Prof17: false
Prof11: false
Prof21: false
CA: 0
Prof25: false
---
[[Mountain Dwarf]], paladin, Male, Noble
Lv 1

>[!column|flex 2]
>
>



| CA                                   | CA Temp | Speed | Initiative |
| ------------------------------------ | ------- | ----- | ---------- |
| `VIEW[{CA} + {Prof}*{Prof25}][math]` | 0       | 25    | 0          |
Prof
`INPUT[number:Prof]`

| HP max | HP Temp | HP Attuali | DVmax | DV  |
| ------ | ------- | ---------- | ----- | --- |
| 12     | 0       | 12         | 1d10  | 1   |

| Saves   |                                   |                                   |                                   |
| ------- | --------------------------------- | --------------------------------- | --------------------------------- |
| Success | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> |
| Fails   | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> |

| Skill | Score                   | Prof                  | Mod                                                |     |
| ----- | ----------------------- | --------------------- | -------------------------------------------------- | --- |
| STR   | `INPUT[number:STR]`<br> | `INPUT[toggle:Prof1]` | `VIEW[floor(({STR}-10)/2) + {Prof}*{Prof1}][math]` |     |
| DEX   | `INPUT[number:DEX]`     | `INPUT[toggle:Prof2]` | `VIEW[floor(({DEX}-10)/2) + {Prof}*{Prof2}][math]` |     |
| CON   | `INPUT[number:CON]`     | `INPUT[toggle:Prof3]` | `VIEW[floor(({CON}-10)/2) + {Prof}*{Prof3}][math]` |     |
| INT   | `INPUT[number:INT]`     | `INPUT[toggle:Prof4]` | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof4}][math]` |     |
| WIS   | `INPUT[number:WIS]`     | `INPUT[toggle:Prof5]` | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof5}][math]` |     |
| CHA   | `INPUT[number:CHA]`     | `INPUT[toggle:Prof6]` | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof6}][math]` |     |

| Ability               |                        | Mod                                                 |
| --------------------- | ---------------------- | --------------------------------------------------- |
| Acrobatics (DEX)      | `INPUT[toggle:Prof7]`  | `VIEW[floor(({DEX}-10)/2) + {Prof}*{Prof7}][math]`  |
| Animal Handling (WIS) | `INPUT[toggle:Prof8]`  | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof8}][math]`  |
| Arcana (INT)          | `INPUT[toggle:Prof9]`  | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof9}][math]`  |
| Athletics (STR)       | `INPUT[toggle:Prof10]` | `VIEW[floor(({STR}-10)/2) + {Prof}*{Prof10}][math]` |
| Deception (CHA)       | `INPUT[toggle:Prof11]` | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof11}][math]` |
| History (INT)         | `INPUT[toggle:Prof12]` | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof12}][math]` |
| Insight (WIS)         | `INPUT[toggle:Prof13]` | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof13}][math]` |
| Intimidation (CHA)    | `INPUT[toggle:Prof14]` | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof14}][math]` |
| Investigation (INT)   | `INPUT[toggle:Prof15]` | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof15}][math]` |
| Medicine (WIS)        | `INPUT[toggle:Prof16]` | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof16}][math]` |
| Nature (INT)          | `INPUT[toggle:Prof17]` | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof17}][math]` |
| Perception (WIS)      | `INPUT[toggle:Prof18]` | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof18}][math]` |
| Performance (CHA)     | `INPUT[toggle:Prof19]` | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof19}][math]` |
| Persuasion (CHA)      | `INPUT[toggle:Prof20]` | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof20}][math]` |
| Religion (INT)        | `INPUT[toggle:Prof21]` | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof21}][math]` |
| Sleight of Hand (DEX) | `INPUT[toggle:Prof22]` | `VIEW[floor(({DEX}-10)/2) + {Prof}*{Prof22}][math]` |
| Stealth (DEX)         | `INPUT[toggle:Prof23]` | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof23}][math]` |
| Survival (WIS)        | `INPUT[toggle:Prof24]` | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof24}][math]` |

| Arma               | Bonus Attacco | Danni/Tipo   | Note                  | gp  |
| ------------------ | ------------- | ------------ | --------------------- | --- |
| Maglio             | +5            | 2d6 Bludgeon | heavy, two heanded    | 10  |
| Martello da guerra | +5            | 1d8 Bludgeon | versatile (1d10)      | 15  |
| Ascia              | +5            | 1d6 Slashing | light, thrown (20/60) | 5   |

| Armatura   | CA                 | DEX mod                | gp  |
| ---------- | ------------------ | ---------------------- | --- |
| Chain Mail | `INPUT[number:CA]` | `INPUT[toggle:Prof25]` | 75  |
Devoto ad Hanseath
Taglia Media
Visione Notturna
Vantaggio Veleno
Proficiency birraio
Stonecunning
Armatura tutte, martelli, Asce, asce da lancio, scudi, simple and martial weapons
Passive perception 2

Divine Sense
The presence o f strong evil registers on your senses like
a noxious odor, and powerful good rings like heavenly
music in your ears. As an action, you can open your
awareness to detect such forces. Until the end o f your
next turn, you know the location o f any celestial, fiend,
or undead within 60 feet o f you that is not behind total
cover. You know the type (celestial, fiend, or undead) o f
any being w hose presence you sense, but not its identity
(the vampire Count Strahd von Zarovich, for instance).
Within the same radius, you also detect the presence
o f any place or object that has been consecrated or
desecrated, as with the hallow spell.
You can use this feature a number of times equal to
1 + your Charisma modifier. When you finish a long rest,
you regain all expended uses.

Lay on Hands
Your blessed touch can heal wounds. You have a pool
o f healing power that replenishes when you take a long
rest. With that pool, you can restore a total number of
hit points equal to your paladin level x 5.
As an action, you can touch a creature and draw
power from the pool to restore a number o f hit points
to that creature, up to the maximum amount remaining
in your pool.
Alternatively, you can expend 5 hit points from your
pool o f healing to cure the target o f one disease or
neutralize one poison affecting it. You can cure multiple
diseases and neutralize multiple poisons with a single
use o f Lay on Hands, expending hit points separately
for each one.
This feature has no effect on undead and constructs.

Gioca a scacchi nanici

25 gp -3sp -10sp -15sp

| Equipaggiamento         | Q.ta | Descrizione | Valore |
| ----------------------- | ---- | ----------- | ------ |
| backpack                | 1    |             | 2 gp   |
| bedroll                 | 1    |             | 1 gp   |
| mess kit                | 1    |             | 2 sp   |
| tinderbox               | 1    |             | 5 sp   |
| torches                 | 10   |             | 1 cp   |
| razioni                 | 10   | 1/day       | 5 sp   |
| waterskin               | 1    |             | 2 sp   |
| hempen rope             | 1    | 50 ft       | 1 gp   |
| Boccale (simbolo sacro) | 1    |             | 5 gp   |
| Anello di Famiglia      | 1    |             |        |
| Vestiti eleganti        | 1    |             |        |
| Pedigree                | 1    |             |        |

### Background
