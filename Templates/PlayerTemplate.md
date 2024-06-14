---
Type: Player
Art: "![[frear.jpg]]"
Level: 0
AC: 0
Prof: 5
HP: 0
HitDice: d0
Speed: 0
STR: 0
DEX: 0
CONST: 0
INT: 0
WIS: 0
CHA: 0
Race: RaceName
Alignment: NONE
Gender: GenderName
Age: "0"
Location: NONE
Class: ClassName
Subclass: SubClassName
AssociatedGroup: NONE
Likes: NONE
Dislikes: NONE
Pronouns: NONE
PersonalityTrait:
  - NONE
SocialTrait:
  - NONE
MentalTrait:
  - NONE
Proficiencies:
  - NONE
Resistances:
  - NONE
Languages:
  - NONE
DmgTkn: 0
TempHP: 0
Copper: 0
Silver: 0
Electrum: 0
Gold: 0
Platinum: 0
ProfSTR: false
ProfINT: false
select: 9
CON: 0
ProfDEX: false
ProfAcrobatics: false
ProfAthletics: false
ProfHistory: false
ProfInvestigation: false
---
>[!column|flex 3]
>> [!infobox]
>> # `=this.file.name`
>> ![[frear.jpg]]
>> ###### Stats
>>  |
>> ---|---|
>> **Level** |`=this.level` |
>>  **Speed** |`=this.Speed` |
>> **Proficiency** | +`=this.Prof` |
>> **Initiative** | +`=floor((this.DEX - 10)/2)` |
>> **AC** | `=this.AC`
>> **HP** | `=this.HP - this.DmgTkn + this.TempHP` |
>> **Hit Dice** | `=this.Level + this.HitDice`  |
>> **Passive Perception** |
>>  
>> ###### Bio
>>   |
>> ---|---|
>> **Race** | `=this.race` |
>> **Sex** | `=this.gender` |
>> **Age** | `=this.age` |
>> **Sexuality** | `=this.sexuality` |
>> **Alignment** | `=this.alignment` |
>> ###### Info
>>   |
>> ---|---|
>> **Class(s)** | `=this.Class` |
>> **Sub-Class(s)** | `=this.Subclass`
>> **Group(s)** | `=this.AssociatedGroup` |
>> **Religion(s)** | `=this.AssociatedReligion` |
>> **Current Location** | `=this.Location` |
>>  ### Currency
| Copper         | Silver         | Gold         | Platinum         |
| -------------- | -------------- | ------------ | ---------------- |
| `=this.Copper` | `=this.Silver` | `=this.Gold` | `=this.Platinum` |
>
>> [!infobox] Death Saves
>> ### Death Saves
| Success | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ------- | --- | --------------------------------- | --------------------------------- |
>>
| Fails | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ----- | --- | --------------------------------- | --------------------------------- |
>>
>> ### Skills 
>> | Skill | Score | Mod | Prof | ST | a |
>> | ----- | ----------- | ----------------------- | --------------------------------- | ----------------------------------- |---- | 
>> | <font color="#ff0000">**STR**</font> |`INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15), option(16), option(17), option(18), option(19), option(20)):STR]` | `VIEW[floor(({STR}-10)/2)][math]` | `INPUT[toggle:ProfSTR]` | `VIEW[floor(({STR}-10)/2) + {Prof}*{ProfSTR}][math]` | +`=this.ST_STR` | 
>> | <font color="#ffff00">**DEX**</font> |`INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15), option(16), option(17), option(18), option(19), option(20)):DEX]` | `VIEW[floor(({DEX}-10)/2)][math]` | `INPUT[toggle:ProfDEX]` | `VIEW[floor(({DEX}-10)/2) + {Prof}*{ProfDEX}][math]` | +`=this.ST_DEX` | 
>> | <font color="#00b050">**CON**</font> |`INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15), option(16), option(17), option(18), option(19), option(20)):CON]` | `VIEW[floor(({CON}-10)/2)][math]` | `INPUT[toggle:ProfCON]` | `VIEW[floor(({CON}-10)/2) + {Prof}*{ProfCON}][math]` | +`=this.ST_CON` | 
>> | <font color="#7030a0">**INT**</font> |`INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15), option(16), option(17), option(18), option(19), option(20)):INT]` | `VIEW[floor(({INT}-10)/2)][math]` |`INPUT[toggle:ProfINT]` | `VIEW[floor(({INT}-10)/2) + {Prof}*{ProfINT}][math]` | +`=this.ST_INT` | 
>> | <font color="#245bdb">**WIS**</font> |`INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15), option(16), option(17), option(18), option(19), option(20)):WIS]` | `VIEW[floor(({WIS}-10)/2)][math]` | `INPUT[toggle:ProfWIS]`| `VIEW[floor(({WIS}-10)/2) + {Prof}*{ProfWIS}][math]` | +`=this.ST_WIS` | 
>> | <font color="#de7802">**CHA**</font> |`INPUT[inlineSelect(option(0), option(1), option(2), option(3), option(4), option(5), option(6), option(7), option(8), option(9), option(10), option(11), option(12), option(13), option(14), option(15), option(16), option(17), option(18), option(19), option(20)):CHA]` | `VIEW[floor(({CHA}-10)/2)][math]` |`INPUT[toggle:ProfCHA]` | `VIEW[floor(({CHA}-10)/2) + {Prof}*{ProfCHA}][math]` | +`=this.ST_CHA` | 
>> ### Skill Checks
| Ability               | Prof                               | Mod                                                             |
| --------------------- | ---------------------------------- | --------------------------------------------------------------- |
| Acrobatics (DEX)      | `INPUT[toggle:ProfAcrobatics]`     | `VIEW[floor(({DEX}-10)/2) + {Prof}*{ProfAcrobatics}][math]`     |
| Animal Handling (WIS) | `INPUT[toggle:ProfAnimalHandling]` | `VIEW[floor(({WIS}-10)/2) + {Prof}*{ProfAnimalHandling}][math]` |
| Arcana (INT)          | `INPUT[toggle:ProfArcana]`         | `VIEW[floor(({INT}-10)/2) + {Prof}*{ProfArcana}][math]`         |
| Athletics (STR)       | `INPUT[toggle:ProfAthletics]`      | `VIEW[floor(({STR}-10)/2) + {Prof}*{ProfAthletics}][math]`      |
| Deception (CHA)       | `INPUT[toggle:ProfDeception]`      | `VIEW[floor(({CHA}-10)/2) + {Prof}*{ProfDeception}][math]`      |
| History (INT)         | `INPUT[toggle:ProfHistory]`        | `VIEW[floor(({INT}-10)/2) + {Prof}*{ProfHistory}][math]`        |
| Insight (WIS)         | `INPUT[toggle:ProfInsight]`        | `VIEW[floor(({WIS}-10)/2) + {Prof}*{ProfInsight}][math]`        |
| Intimidation (CHA)    | `INPUT[toggle:ProfIntimidation]`   | `VIEW[floor(({CHA}-10)/2) + {Prof}*{ProfIntimidation}][math]`   |
| Investigation (INT)   | `INPUT[toggle:ProfInvestigation]`  | `VIEW[floor(({INT}-10)/2) + {Prof}*{ProfInvestigation}][math]`  |
| Medicine (WIS)        | `INPUT[toggle:ProfMedicine]`       | `VIEW[floor(({WIS}-10)/2) + {Prof}*{ProfMedicine}][math]`       |
| Nature (INT)          | `INPUT[toggle:ProfNature]`         | `VIEW[floor(({INT}-10)/2) + {Prof}*{ProfNature}][math]`         |
| Perception (WIS)      | `INPUT[toggle:ProfPerception]`     | `VIEW[floor(({WIS}-10)/2) + {Prof}*{ProfPerception}][math]`     |
| Performance (CHA)     | `INPUT[toggle:ProfPerformance]`    | `VIEW[floor(({CHA}-10)/2) + {Prof}*{ProfPerformance}][math]`    |
| Persuasion (CHA)      | `INPUT[toggle:ProfPersuasion]`     | `VIEW[floor(({CHA}-10)/2) + {Prof}*{ProfPersuasion}][math]`     |
| Religion (INT)        | `INPUT[toggle:ProfReligion]`       | `VIEW[floor(({INT}-10)/2) + {Prof}*{ProfReligion}][math]`       |
| Sleight of Hand (DEX) | `INPUT[toggle:ProfSleightofHand]`  | `VIEW[floor(({DEX}-10)/2) + {Prof}*{ProfSleightofHand}][math]`  |
| Stealth (DEX)         | `INPUT[toggle:ProfStealth]`        | `VIEW[floor(({DEX}-10)/2) + {Prof}*{ProfStealth}][math]`        |
| Survival (WIS)        | `INPUT[toggle:ProfSurvival]`       | `VIEW[floor(({WIS}-10)/2) + {Prof}*{ProfSurvival}][math]`       |
>
>>[!infobox] Background
>> ### Background
>> dhvchbdsh
>> dhb sdhkb sd
>> hb cshkbcsk




