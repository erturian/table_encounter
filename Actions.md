## Move Action (1 AP)
The active model can move up to twice the value of its Agility score. Obstacles up to 1" in height (excluding other characters) can be ignored during movement. 
Regardless of the ranges mentioned below for partial steps while climbing or jumping, the character can never move more than the aforementioned double value of their Agility with one Move Action.

### Climbing 
A character may climb a vertical distance up to the value of its Agility value, to climb obstacles higher than that (and without any support like ladders or so), perform an Agility test.
For each success, add 2" of vertical movement to climb the obstacle. If the character's total movement range is insufficient or they do not achieve enough successes on the climbing roll, they fall. 

> [!Note]
> An obstacle is considered climbed once the character reaches the top edge, even if their movement range is not enough to place the base on the obstacle. In this case, simply place them at the nearest possible location.

### Jumping
The active character can jump a horizontal distance up to half of their Agility score. For longer jumps, perform an Agility test. 
For each success, the character crosses the distance of 1". If the successes or the total movement range are not enough to jump the desired distance, the character falls. 
Place the model where it currently is (and possibly at a lower level).

### Falling
If climbing or a jump fails, a character may fall. In this case, determine the target height of the obstacle to be climbed or the vertical distance the character has unintentionally fallen. 
For every 3", the character receives one point of stress.

## Close Combat Action (2 AP)

### Engage
The active model can move up to its Agility value. During this movement, opposing models are not taken into account, and the movement can also pass through or into threat ranges. The movement must end with at least one opposing model within the threat range of the active model.
The attacker now selects an opponent within their threat range as the target of their attack.

> [!Note]
> The vertical threat range is 3" + the threat range of a given melee weapon.

### Clash 
The players secretly divide dice equal to their Melee value into attack and defense dice and perform a critical attribute test.
Compare the successes: Successes from defense rolls negate opposing successes from attacks, while critical successes from defense rolls can negate up to two normal successes or one critical success from opposing attacks.

> [!Note]
> A character may only deal damage with melee attacks, while the opponent is in range of at least one of their melee weapons.

### Example Melee Weapons
| Name    | Threat Range | Damage        | Critical                                                                | Points |
|---------|--------------|---------------|-------------------------------------------------------------------------|--------| 
| Sword   | 1"           | 1             | 2                                                                       | 4      |
| Spear   | 2"           | 1             | 1 and shove the defender 1" directly back (1 time per activation)       | 4      |

## Shooting Action (2 AP)

### 1. Calculate Difficulty
First, the difficulty of the shot is determined. 

1. Measure the distance between the shooter and the target to set the base difficulty. 
2. This is increased by 1 for each obstacle in the line of fire. (An obstacle is defined as any object [including models] that is larger than 1".)
3. Include the difficulty modifier of the weapon being used
4. The opponent can now decide whether the targeted model
    - a) takes cover (target must spend 1 AP), which increases the difficulty of the shot by half of the targets agility value
    - b) returns fire (target must spend 2 AP)
    - c) does nothing

### 2. Shot
The shooting model now rolls a number of dice equal to its ballistics value. If the sum of the rolled values is equal to or higher than the difficulty, inflicts stress on the target. 
If the shooter misses, the owning player rolls to see if an obstacle (including models) was hit instead, starting with the obstacle closest to the target and resolving them step by step towards the shooter. Once a roll of 4 or higher is achieved, determine whether an obstacle was hit and which one it is.

> [!Note]
> This rule is designed to allow interaction with the terrain. If an obstacle (and not a model) is hit, you can make something explode (dealing damage to all models within a 1"-3" radius), kick up dust (creating an opaque obstacle with a 2" circular template), or similar effects. Be creative!

### 3. Reaction
Now, the opposing model's reaction is taken into account. 
If it has gone to cover, its owner can now move it up to half its agility skill. During this movement, they must try to obscure the line of sight between the target and the shooter further.
If it returns fire, the model may immediatly take a shooting action (without spending additional Action Points). The Action Points required for this action have already been spent during the 'Calculate Difficulty' phase.

### Example Shooting Weapons
| Name    | Difficulty Modifier | Damage        | Critical                                                     | Points |
|---------|---------------------|---------------|--------------------------------------------------------------|--------| 
| Pistol  | -1                  | 1             | 2                                                            | 3      |
| Rifle   | 0                   | 1             | D3                                                           | 4      |
| Sniper  | 2                   | 1             | no reactive shooting allowed, take cover move reduced by 1"  | 5      |

