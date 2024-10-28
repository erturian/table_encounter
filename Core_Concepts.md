# Core Concepts 

## Characters and Abilities
Each model has a character card with four abilities: Melee, Ballistics, Toughness, and Agility.
* Melee primarily influences the ability to engage in direct combat. A high melee value allows for harder strikes and better parries.
* Ballistics allows the character to hit more accurately in ranged combat and increases the chance of critical hits.
* Toughness makes the character more resilient. They can endure more wounds and stay on their feet longer after taking hits.
* Agility affects the character's speed. Additionally, a nimble character can dodge, climb, and jump more effectively.

The attribute values typically range from 2 to 5. When creating your own characters, pay attention to the total sum of the attribute points. Here’s a quick overview:

| Sum    | Description        | Sum    | Description        |
|-------:|--------------------|-------:|--------------------|
| 8      | Worm               | 16     | Hero               |
| 10     | Minion             | 18     | Monster            |
| 12     | Ordinary Mortal    | 20     | Legendary Being    |
| 14     | Leader             |        |                    |

## Action Points
All models start each combat round with 3 action points. These can be spent during the round, especially when they are activated, to perform actions.

## Move (1 AP)
The active model can move up to twice the value of its Agility score. Obstacles up to 1" in height (excluding other models) can be ignored during movement. Regardless of the ranges mentioned below for partial steps while climbing or jumping, the character can never move more than the aforementioned double value of their Agility.

Obstacles up to 3" in height can be easily climbed. The vertical movement simply counts toward the movement distance. This also applies to using ladders of any height.

> [!Note]
> An obstacle is considered climbed once the character reaches the top edge, even if their movement range is not enough to place their base on the obstacle. In this case, simply place them at the nearest possible location.

### Climbing 
To climb obstacles higher than 3", roll a number of dice equal to the active character's Agility score. For each roll of 4 or higher, add 2" of vertical movement to the current distance to climb the obstacle. If the character's movement range is insufficient or they do not achieve enough successes on the climbing roll, they fall. 

### Jumping
The active character can jump up to half of their Agility score. The character may also jump multiple times as long as a single jump is not longer than half its Agility Score. Add the jump distance normally to the movement already performed. For longer jumps, make an Agility test: for each roll of 4 or higher, the character moves 1". If the successes or movement range are not enough to clear the desired distance, place the character where they currently are.

### Falling

If climbing or a jump fails, a character may fall. In this case, determine the target height of the obstacle to be climbed or the vertical distance the character has unintentionally fallen. For every 3", the character receives one point of stress.

## Close Combat Action (2 AP)

### Pounce on
The active model can move up to its Agility value. During this movement, opposing models are not taken into account, and the movement can also pass through or into threat ranges. The movement must end with at least one opposing model within the threat range of the active model.
The attacker now selects an opponent within their threat range as the target of their attack.

### Clash 
The players secretly divide dice equal to their Melee value into attack and defense dice. It is important to note that the defender can only allocate dice for the attack if the attacker is within the threat range of their melee weapon.
Then, they roll their dice simultaneously and compare their successes. A result of 4 or higher counts as a normal success, while a roll of 6 counts as a critical success.

Normal successes from defense rolls negate opposing successes from attacks, while critical successes from defense rolls can negate up to two normal successes or one critical success from opposing attacks.

### Example Melee Weapons
| Name    | Threat Range | Damage        | Critical                                                                | Points |
|---------|--------------|---------------|-------------------------------------------------------------------------|--------| 
| Sword   | 1"           | 1             | 2                                                                       | 4      |
| Spear   | 2"           | 1             | 1 and shove the defender 1" directly back (1 time per activation)       | 4      |

## Shooting Action (2 AP)

### Calculate Difficulty
First, the difficulty of the shot is determined: The distance between the shooter and the target sets the base difficulty. This difficulty is then increased by 1 for each obstacle in the line of fire. An obstacle is defined as any object (including models) that is larger than 1".

The opponent can now decide whether the targeted model does nothing, takes cover (for 1 AP) or returns fire (for 2 AP). If it takes cover, increase the difficulty of the shot by half its agility skill.

### Shot
The shooting model now rolls a number of dice equal to its ballistics ability. If the sum of the rolled values is equal to or higher than the difficulty, it has hit its target and inflicts damage.
If the shooter misses their target, the owner rolls to see if an obstacle (including models!) was hit instead. They start with the obstacle closest to the target and resolve the obstacles step by step towards the shooter. Once a 4 or higher is rolled, it is determined whether an obstacle was hit and which one it is.

> [!Note]
> This rule is designed to allow interaction with the terrain. If an obstacle (and not a model) is hit, you can make something explode (dealing damage to all models within a 1"-3" radius), kick up dust (creating an opaque obstacle with a 2" circular template), or similar effects. Be creative!

### Reaction
If the opposing model has not been taken out and has gone to cover, its owner can now move it up to half its agility skill in inch. During this movement, they must try to obscure the line of sight between the target and the shooter further.
Regardless of whether the targeted model has been taken out, it can now return fire if it did not take cover. This action costs 2 action points and is resolved immediately.

### Example Shooting Weapons
| Name    | Difficulty Mod | Damage        | Critical                                                     | Points |
|---------|----------------|---------------|--------------------------------------------------------------|--------| 
| Pistol  | 1              | 1             | 2                                                            | 3      |
| Rifle   | 0              | 1             | D3                                                           | 4      |
| Sniper  | -2             | 1             | no reactive shooting allowed, take cover move reduced by 1"  | 5      |

## Stress and incapability
The toughness value of a character determines how well they can withstand wounds or stress situations in combat. Each time the character takes damage, their stress level increases by the same amount. Once the stress level equals or exceeds the character's toughness value, they must perform a stress test:

Roll a number of dice equal to the character's toughness value. A roll of 4 or higher counts as a success. For each failed roll, decrease the character's toughness value by 1.

If the toughness value falls to 0, the character's nerves break, or they are so severely injured that they can no longer continue the fight. Remove them from the game.
