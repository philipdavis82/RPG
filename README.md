# -WIP-
# {name} Overview
## Abstract
{name} Is meant to be a completely open source table top game that prioritizes modularity and ease of access while not reducing character building depth. The following are the key points of this game.
* There are no defined classes
    * The perceived role of the character should be defined by the items, abilities and traits that the character has obtained
* Building a character initially should be simple
    * A new player should be able to get up and begin playing with minimal reading. *(Assuming there is a semi-experienced GM)*
* Skill rolls should able to be made with a single stat or combination of stats
* The character defining attributes should be simple to generate on the fly
    * This could mean there are simple rules that rank general power of an Item,Trait, or Ability

---

## Character
* Characters are defined by the their main stats while there role in the party is defined by the Items,Traits,and Abilities of the character. 
* A character has experience and gaines levels where each level allows the player to advance their stats. 
    * Each level a character will gain a specified amount of stat points to use to increase their stats 

### **Stats**
* 4 Main Stats
    * Body
    * Mind
    * Spirit
    * Presence
* Each stat at level 1 start at 0
    * Stats Can Go to negative amounts
* Stats Give bonuses based on half the stat rounded up
* Skill Roles take 2 stat bonuses and combines them
    * A Skill that required 1 stat uses the level instead of the bonus as a modifier

### **Leveling Paradigms**
Linear Design
* Leveling a stat takes 1 stat point
    * The max a stat can reach is 20
* each level gives 2 stat points
* Stat gives a bonus of $1/2$ the level

### **Point Pools**
Character have point pools that determine the current state of the character. These include the physical health of the character, physical energy, and mental energy.
* Endurance Pool (EP):
  * This is pseudo health pool that denotes the non-permanent damage taken by a character 
  * Determined by a Combination of Body, Mind, and Level
* Health Pool (HP):
  * This is a representation of permanent physical damage
  * Determined by Body and Level (*Maybe Only Level*)
* Stamina (SP):
  * This is the representation of physical energy and is used for physical abilities and effects
  * Determined by Body, Spirit and Level
* Mental Focus (MP):
  * This is the mental energy to use magic
  * Determined by Mind, Spirit, and Level


---

## Traits
* Traits are character modifiers 
* Can have both Positive or Negative effects
* Traits are gained at character creation optionally but are also givin out during a game by the GM based on actions or events per character

*Example Trait*

    Spider Phobia
     - Modifier: -2 to Mind Rolls 
     - Effect: When the character is interacting with or near a spider it will be difficult to focus reducing action results using Mind. 
     - Description: This character has a immense fear of spiders
     - Cost: -1

---

## Abilities
* Abilities are special effects for characters.
  * They are synonymous to class abilities in other RPGs
* They will be able to be gained in a similar fashion to items.
  * For example a player may find a scroll detailing a new sword technique.
* Abilities will be categorized in levels that correspond to the power of the ability
* They will have specific stat requirements to be able to use.
  * These stat requirements should correspond to the level of the ability
  * There will be a method for determining the stat distribution of the ability
* They can have the following effects
  * Passive Effect:
    * This is an effect that is now natively available to the character
  * Active Effect:
    * This is where a player must actively use the ability to make use of it
    * This may cost points or may not
    * This could have an inherent Cooldown ie. "once per day" or "5 times per day"

*Example Ability*
    
    Wide Sweep:
     - Level : 3
     - Requirements: [ Body: 6 | Presence: 2 ]
     - Actions : 2 
     - Type : Attack
     - Cost : 4 Stamina
     - Items : Two-Handed Melee Weapon
     - Effect : "This character may spend stamina to attack multiple enemies within reach. Roll and attack against each enemy. within reach. 
     - Description : The combatant swigs their weapon in a large arc cutting down any foe how is unlucky enough to be caught in its path
     - Tags : Figher,Melee,Two-Handed,Stamina

---

## Items

* Items are similar to Abilities in terms of how a character plays
* Items should be more powerfull than abilities due to only having limited equipment slots

*Example Ability* 

    Rusty Longsowrd
    - Level : 1
    - Requirments: [ Body: 1(2) ]
    - Accracy : d20 + Body - 1d4 ( d20 + Body )
    - Damage  : 1d4 + Body/2 ( 1d4 + Body )
    - Damage Type : Physical
    - Range : Immediate
    - Effect : Fragile: Dealing 6 or more damage breaks the sword giving a point of disadvantage. At 3 points completly destory the sword.
    - Description : A layer of rust covers this sword. It was probably left out in the rain for much too long. The weight
    - Tags: Fighter,Melee,Negitive,Mundane,Damage,Immediate
>
    Minor Potion of Healing
    - Level : 1
    - Requirments: [ None (Spirit: 4) ]
    - Range : Immediate
    - Healing : 1d8 EP + 1d4 HP (1d8 + Spirit EP + 1d8 HP)
    - Effect : Drinking this potion heals ones wounds and reinvigorates 
    - Description : A translucent light green liquid that carries a strong almond scent. 
    - Tags: Potion,Healing,Immediate,Magic

---

## Enemies

---

## Encounters

---