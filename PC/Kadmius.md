---
STR: 4
DEX: 12
CON: 17
INT: 16
WIS: 11
CHA: 19
Prof1: false
Prof: 2
Prof5: true
Prof6: true
Prof7: false
Prof8: false
Prof9: true
Prof10: true
Prof16: false
Prof20: true
Prof12: true
Prof2: false
Prof23: false
Prof17: true
exampleProperty: true
Prof25: true
Prof27: true
Prof26: true
CA: 11
Prof24: true
Prof28: true
Prof3: false
---
[[Half Elf]], warlock, Male, Outlander, 25 anni, 190cm, 75kg, occhi verdi rossi, carnagione rosa, capelli castano chiaro
Ragazzo, adulto da 5 anni, orfano, caratteri misti dalla razza, alto magro.

Lv 1


| CA                                   | CA Temp | Speed | Initiative |
| ------------------------------------ | ------- | ----- | ---------- |
| `VIEW[{CA} + {Prof}*{Prof25}][math]` | 0       | 30    | 0          |
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

| Arma    | Bonus Attacco | Prof                   | Danni/Tipo   | Note                                           | gp  |
| ------- | ------------- | ---------------------- | ------------ | ---------------------------------------------- | --- |
| pugnale | +3            | `INPUT[toggle:Prof27]` | 1d4 Piercing | Finesse, light, Thrown (20/60)                 | 2   |
| pugnale | +3            | `INPUT[toggle:Prof26]` | 1d4 Piercing | Finesse, light, Thrown (20/60)                 | 2   |
| staff   |               |                        |              |                                                |     |
|         | -1            | `INPUT[toggle:Prof28]` | 1d8 Piercing | Ammunition (range 80/320), loading, two-handed | 25  |
|         |               |                        |              |                                                |     |

| Armatura | CA                 | DEX mod                | gp  |
| -------- | ------------------ | ---------------------- | --- |
| Leather  | `INPUT[number:CA]` | `INPUT[toggle:Prof25]` | 10  |
Passive perception 2


Ammaliante, resisto alle manip. psichiche, non mi addormentano e dormo 8h.
Elfico, comune, altre 2, proficiency con uno strumento, + una lingua, hunting trap, animal trophy, wanderer clothes, 10 gp -4sp
Arcane Focus: Occhi rossi

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


PATRON : the Great Old One,features at 1st level and again at 6th, 10th, and 14th level.

Awakened Mind
Starting at 1st level, your alien knowledge gives you
the ability to touch the minds of other creatures. You
can communicate telepathically with any creature you
can see within 30 feet o f you. You don’t need to share
a language with the creature for it to understand your
telepathic utterances, but the creature must be able to
understand at least one language.

Pa c t M a g i c
Your arcane research and the magic bestowed on you
by your patron have given you facility with spells. See
chapter 10 for the general rules o f spellcasting and
chapter 11 for the w arlock spell list.
C a n t r i p s
You know two cantrips o f your choice from the w arlock
spell list. You learn additional warlock cantrips of your
choice at higher levels, as shown in the Cantrips Known
column o f the Warlock table.
Sp e l l Sl o t s
The Warlock table shows how many spell slots you have.
The table also shows what the level of those slots is; all
o f your spell slots are the same level. To cast one o f your
warlock spells o f 1st level or higher, you must expend a
spell slot. You regain all expended spell slots when you
finish a short or long rest.
For example, when you are 5th level, you have
two 3rd-level spell slots. To cast the 1st-level spell
thunderwave, you must spend one o f those slots, and
you cast it as a 3rd-level spell.


| Cantrips           |     |
| ------------------ | --- |
| [[Eldritch Blast]] |     |
| [[Blade Ward]]     |     |

| Lv 1 Spells        | 1 slot |
| ------------------ | ------ |
| [[Witch Bolt]]     |        |
| [[Hellish Rebuke]] |        |

Confort armature leggere e armi semplici.

The DC to resist one of your spells equals 8 + your spellcasting ability modifier + your proficiency bonus + any special modifiers.

Sono un mezz’elfo che vive ai confini di un bosco enorme e rigoglioso in cui dimorano gli elfi delle foreste ed è da quel luogo che mia madre ([[Madre di Kadmius]]) proviene. Mio Padre ([[Padre di Kadmius]]) invece è un uomo che proviene da una famiglia di commercianti della città appena fuori dal bosco abitato dagli elfi.
I miei genitori si sono incontrati grazie alle attività commerciali intraprese dalla famiglia di mio padre con gli elfi, mio padre rimase folgorato la prima volta che vide mia madre. I due iniziarono a frequentarsi, nonostante l’opposizione delle rispettive famiglie, ma loro si amavano. Quando io nacqui fu chiaro fin da subito che non fossi ne un uomo ne un elfo, a metà.. un mezz’elfo.. la mia famiglia fu emarginata dai rispettivi mondi ma eravamo felici. 

Lo eravamo, finché mia madre si ammalò di un male incurabile… il [[Morbo blu]] lo chiamavano…sia per gli uomini che per gli elfi… e quando morì… da quel giorno non fu più lo stesso.

Sono passati 5 anni da quel giorno, ormai sono adulto sono piu alto di mio padre, ho i capelli lunghi lisci e neri, li porto raccolti amo la natura e sono socievole ma solitario. 

Aiuto mio padre nell’attività di famiglia e i rapporti con le razze da cui provengo sono difficili, distanti e mi sento giudicato per il mio aspetto…

Un giorno mi sono incamminato per una delle mie passeggiate lungo il confine nord-est del bosco degli elfi, era una zona che non avevo mai esplorato, intrapresi una via piena di salici piangenti circondati da ruscelli silenziosi fino a quando vidi una grotta.
Grazie al sangue di mia madre riesco a percepire la presenza di animali pericolosi e quella grotta ne era priva.
Dopo il primo passo il pavimento cedette sotto i miei piedi e mi ritrovai in un altra stanza, c’era un podio/ un altare non capivo realmente di cosa si trattasse e mi avvicinai per capirlo. 

Sembrava antico, non visto da secoli,  mi avvicinai e toccandolo mi graffiai… ([[Patrono di Kadmius]])
Ho dei ricordi confusi di quel momento, una luce crescente mi avvolse ma sentivo il freddo dell’ oscurità dentro di me, un rumore assordante e monotono, e poi mi svegliai in mezzo ai salici piangenti.
Da quel giorno sento dentro di me un potere, qualcosa di diverso da prima, mi sento legato a qualcosa o qualcuno un filo invisibile.
Ora il mio scopo nella vita è capire cosa mi è successo e so chiaramente che la natura, dove mi sono sempre rifugiato, è connessa con il mio muovo potere e  mi guiderà nella comprensione del nuovo legame che sento dentro.