---
STR: 11
DEX: 20
CON: 13
INT: 9
WIS: 13
CHA: 12
Prof1: true
Prof: 2
Prof5: false
Prof6: false
Prof7: false
Prof8: true
Prof9: false
Prof10: true
Prof16: true
Prof20: false
Prof12: false
Prof2: true
Prof23: true
Prof17: false
exampleProperty: true
Prof25: true
Prof27: true
Prof26: true
CA: 11
Prof28: true
Prof24: true
Prof18: true
---
[[Wood Elf]], ranger, Female, Folk Hero, 80 anni, 180cm, 70kg, occhi grigi, capelli biondi
Lv 1


| CA                                   | CA Temp | Speed | Initiative |
| ------------------------------------ | ------- | ----- | ---------- |
| `VIEW[{CA} + {Prof}*{Prof25}][math]` | 0       | 35    | 5          |
Prof
`INPUT[number:Prof]`

| HP max | HP Temp | HP Attuali | DVmax | DV  |
| ------ | ------- | ---------- | ----- | --- |
| 11     | 0       | 11         | 1d8   | 1   |

| Saves   |                                   |                                   |                                   |
| ------- | --------------------------------- | --------------------------------- | --------------------------------- |
| Success | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> |
| Fails   | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> |

| Skill | Score                   | Prof                  | Mod                                                |
| ----- | ----------------------- | --------------------- | -------------------------------------------------- |
| STR   | `INPUT[number:STR]`<br> | `INPUT[toggle:Prof1]` | `VIEW[floor(({STR}-10)/2) + {Prof}*{Prof1}][math]` |
| DEX   | `INPUT[number:DEX]`     | `INPUT[toggle:Prof2]` | `VIEW[floor(({DEX}-10)/2) + {Prof}*{Prof2}][math]` |
| CON   | `INPUT[number:CON]`     | `INPUT[toggle:Prof3]` | `VIEW[floor(({CON}-10)/2) + {Prof}*{Prof3}][math]` |
| INT   | `INPUT[number:INT]`     | `INPUT[toggle:Prof4]` | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof4}][math]` |
| WIS   | `INPUT[number:WIS]`     | `INPUT[toggle:Prof5]` | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof5}][math]` |
| CHA   | `INPUT[number:CHA]`     | `INPUT[toggle:Prof6]` | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof6}][math]` |

| Ability               |                                | Mod                                                 |
| --------------------- | ------------------------------ | --------------------------------------------------- |
| Acrobatics (DEX)      | `INPUT[toggle:Prof7]`          | `VIEW[floor(({DEX}-10)/2) + {Prof}*{Prof7}][math]`  |
| Animal Handling (WIS) | `INPUT[toggle:Prof8]`          | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof8}][math]`  |
| Arcana (INT)          | `INPUT[toggle:Prof9]`          | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof9}][math]`  |
| Athletics (STR)       | `INPUT[toggle:Prof10]`         | `VIEW[floor(({STR}-10)/2) + {Prof}*{Prof10}][math]` |
| Deception (CHA)       | `INPUT[toggle:Prof11]`         | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof11}][math]` |
| History (INT)         | `INPUT[toggle:Prof12]`         | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof12}][math]` |
| Insight (WIS)         | `INPUT[toggle:Prof13]`         | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof13}][math]` |
| Intimidation (CHA)    | `INPUT[toggle:Prof14]`         | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof14}][math]` |
| Investigation (INT)   | `INPUT[toggle:Prof15]`         | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof15}][math]` |
| Medicine (WIS)        | `INPUT[toggle:Prof16]`<br><br> | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof16}][math]` |
| Nature (INT)          | `INPUT[toggle:Prof17]`         | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof17}][math]` |
| Perception (WIS)      | `INPUT[toggle:Prof18]`         | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof18}][math]` |
| Performance (CHA)     | `INPUT[toggle:Prof19]`         | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof19}][math]` |
| Persuasion (CHA)      | `INPUT[toggle:Prof20]`         | `VIEW[floor(({CHA}-10)/2) + {Prof}*{Prof20}][math]` |
| Religion (INT)        | `INPUT[toggle:Prof21]`         | `VIEW[floor(({INT}-10)/2) + {Prof}*{Prof21}][math]` |
| Sleight of Hand (DEX) | `INPUT[toggle:Prof22]`         | `VIEW[floor(({DEX}-10)/2) + {Prof}*{Prof22}][math]` |
| Stealth (DEX)         | `INPUT[toggle:Prof23]`         | `VIEW[floor(({DEX}-10)/2) + {Prof}*{Prof23}][math]` |
| Survival (WIS)        | `INPUT[toggle:Prof24]`         | `VIEW[floor(({WIS}-10)/2) + {Prof}*{Prof24}][math]` |

| Arma        | Bonus Attacco | Prof                   | Danni/Tipo   | Note                                     | gp  |
| ----------- | ------------- | ---------------------- | ------------ | ---------------------------------------- | --- |
| spada corta | +5            | `INPUT[toggle:Prof27]` | 1d6 Piercing | Finesse, light, Thrown (20/60)           | 2   |
| spada corta | +5            | `INPUT[toggle:Prof26]` | 1d6 Piercing | Finesse, light, Thrown (20/60)           | 2   |
| arco lungo  | +5            | `INPUT[toggle:Prof28]` | 1d8 Piercing | Ammunition (150/600), heavy, two heanded | 50  |
| frecce      |               |                        |              | 20                                       |     |

| Armatura | CA                 | DEX mod                | gp  |
| -------- | ------------------ | ---------------------- | --- |
| Leather  | `INPUT[number:CA]` | `INPUT[toggle:Prof25]` | 10  |
Vantaggio su tiri vs psiche. Resistente a incantesimi sul sonno. Medito 4h. Bene archi (s-l) e spade (s-l). Ok tiri x hide anche ev. naturali lievi. 

Natural explorer
You are particularly familiar with one type o f natural
environment and are adept at traveling and surviving in
such regions. Choose one type o f favored terrain: arctic,
coast, desert, forest, grassland, mountain, swamp,
or the Underdark. When you make an Intelligence or
Wisdom check related to your favored terrain, your
proficiency bonus is doubled if you are using a skill that
you’re proficient in.
While traveling for an hour or m ore in your favored
terrain, you gain the following benefits:
• Difficult terrain doesn’t slow your group’s travel.
• Your group can’t become lost except by magical
means.
• Even when you are engaged in another activity while
traveling (such as foraging, navigating, or tracking),
you remain alert to danger.
• If you are traveling alone, you can move stealthily at
a normal pace.
• When you forage, you find twice as much food as you
normally would.
• While tracking other creatures, you also learn their
exact number, their sizes, and how long ago they
passed through the area.
You choose additional favored terrain types at 6th
and 10th level.

Fa v o r e d E n e m y
Beginning at 1st level, you have significant experience
studying, tracking, hunting, and even talking to a certain
type o f enemy.
Choose a type o f favored enemy: aberrations,
beasts, celestials, constructs, dragons, elementals, fey,
fiends, giants, monstrosities, oozes, plants, or undead.
Alternatively, you can select two races o f humanoid
(such as gnolls and orc s) as favored enemies.
You have advantage on W isdom (Survival) checks to
track your favored enemies, as w ell as on Intelligence
checks to recall information about them.
When you gain this feature, you also learn one
language o f your choice that is spoken by your favored
enemies, if they speak one at all.
You choose one additional favored enemy, as well as
an associated language, at 6th and 14th level. As you
gain levels, your choices should reflect the types of
monsters you have encountered on your adventures.

competenze: armature leggere/medie + scudi, armi semplici/marziali.
Parlo goblin, vantaggio su tiri per track miei nemici.
Vantaggio intelligenza x ricordare cose su miei nemici.   
Esperta foresta, se viaggio +1h ottengo: terreno difficile non rallenta gruppo, no perdersi eccetto magia, allerta, se sola nascosta, cibo 2x, se track creature capisco n, size,when.
nemici goblin e orchi
One type o f artisan’s tools,
vehicles (land)
A set of artisan’s tools (one of your choice),
a shovel, an iron pot, a set of common clothes, and a
belt pouch containing 

10 gp -2sp -2sp

| Equipaggiamento | Q.ta | Descrizione | Valore |
| --------------- | ---- | ----------- | ------ |
| backpack        | 1    |             | 2 gp   |
| tinderbox       | 1    |             | 5 sp   |
| torches         | 10   |             | 1 cp   |
| razioni         | 10   | 1/day       | 5 sp   |
| waterskin       | 1    |             | 2 sp   |
| hempen rope     | 1    | 50 ft       | 1 gp   |
| crowbar         | 1    |             | 2 gp   |
| hammer          | 1    |             | 1 gp   |
| pitons          | 10   |             | 5 cp   |


Mi chiamo Frear Scheggia di Rovo e sono figlia di [[Mirta]], mia mamma, morta di parto e [[Folto Scheggia di rovo]], mio padre. Non ho fratelli, sono cresciuta in una foresta a nord e mio padre alleva cervi, anche i cervi bianchi del signore della foresta (nostro Re) ed è molto conosciuto. Quando sono diventata maggiorenne mio padre mi ha donato un cervo con le corna dorate che ho chiamato [[Ombra di Rovo]] e con cui ho un legame particolare, ci parliamo anche telepaticamente. Il mio ruolo era quello di cacciatrice e sentinella, grazie a questo ho sviluppato le caratteristiche da ranger, in particolare conto molto sui miei occhi e sul mio udito. Purtroppo mio padre è morto da poco durante un’imboscata dei goblin+orchi che in sella ai mannari hanno distrutto il suo ranch (che si trovava al limitare della foresta per motivi di spazio ovviamente) e ucciso qualsiasi essere vivente tranne Ombra di rovo, che mi ha avvisata ed è scappato in preda al terrore. Ho quindi lasciato il regno da pochissimo e mi sono incamminata per cercare vendetta. Sono molto buona e dolce con le creature umane e gli animali anche i mannari perché non credo che nascano cattivi, altro discorso riguarda invece orchi/goblin e in generale creature di natura malvagia. Verso di essi non ho pietà! Porto con me un piccolo ramo di rovo di biancospino, che cresceva rigoglioso a casa mia e che mi ricorda casa e la vita che non ho più.