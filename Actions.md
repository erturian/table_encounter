## Move (1 AP)
The movement range of a character is double its Agility value. Obstacles up to 1 inch in height can be ignored during movement. 
A character can never exceed its movement range during a single Move Action.

### Climbing 
A character may climb a vertical distance up to its Agility value. 
To climb obstacles higher than the character's Agility value and without any support (like ladders), perform an Agility test:

For each success, gain 2 inch of vertical movement to climb the obstacle. If insufficient successes are achieved, the character falls. 

> [!Note]
> An obstacle is considered climbed once the character reaches the top edge, even if their movement range does not allow them to place their base on top of the obstacle. In this case, simply place the character at the nearest possible location.

### Jumping
The active character can jump a horizontal distance up to half of their Agility value.
If the jump exceeds this distance, perform an Agility test:

For each success, the character moves horizontally by 1". If the successes are insufficient to jump the desired distance, the character falls.
Place the model at its current location, potentially at a lower level.

### Falling
If a climbing or jumping attamept fails, a character may fall. In this case, determine the height of the obstacle that was attempted to be climbed or the vertical distance the character has fallen.
For every 3 inches fallen, the character receives one point of stress.

## Close Combat (2 AP)

### Engage
1. The attacker choses one of their melee weapons as selected weapon for this attack. 
2. The active model can move up to its Agility value. During this movement, opposing models are not taken into account, and the movement can also pass through threat ranges. The movement must end with at least one opposing model within the threat range of the active model.
3. The attacker now selects an opponent within their threat range as the target of their attack.

> [!Note]
> The vertical threat range is 3" + the threat range of a given melee weapon.

### Clash 
1. Both players perform a critical Melee test.
2. Starting with the attacker, the players alternate to resolve their successes:
  - to induce stress on the target (see opression value of its melee weapon)
  - to parry (negate one opposing success, critical successes are needed to parry other critcial successes)

> [!Note]
> A character may only induce stress with melee attacks, while the opponent is in range of at least one of their melee weapons.

### Example Melee Weapons
| Name    | Threat Range | Oppression    | Critical                                                                | Points |
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
  
> [!Note]
> If the enemy character is targeted by this attack after they took an Aid action this turn, they cannot take cover but can return fire without spending AP.

### 2. Shooting
The shooting model now rolls a number of dice equal to its ballistics value. 
- If the sum of the rolled values is equal to or higher than the difficulty, inflicts stress on the target. 
- If the shooter misses, the owning player rolls to see if an obstacle (including models) was hit instead, starting with the obstacle closest to the target and resolving them step by step towards the shooter. Once a roll of 4 or higher is achieved, determine whether an obstacle was hit and which one it is.

> [!Note]
> This rule is designed to allow interaction with the terrain. If an obstacle (and not a model) is hit, you can make something explode (dealing damage to all models within a 1"-3" radius), kick up dust (creating an opaque obstacle with a 2" circular template), or similar effects. Be creative!

### 3. Reaction
Now, the opposing model's reaction is taken into account. 
- If it has gone to cover, its owner can now move it up to half its agility skill. During this movement, they must try to obscure the line of sight between the target and the shooter further.
- If it returns fire, the model may immediatly take a shooting action (without spending additional Action Points). The Action Points required for this action have already been spent during the 'Calculate Difficulty' phase.

### Example Shooting Weapons
| Name    | Difficulty Modifier | Damage        | Critical                                                     | Points |
|---------|---------------------|---------------|--------------------------------------------------------------|--------| 
| Pistol  | -1                  | 1             | 2                                                            | 3      |
| Rifle   | 0                   | 1             | D3                                                           | 4      |
| Sniper  | 2                   | 1             | no reactive shooting allowed, take cover move reduced by 1"  | 5      |

## Aid (2 AP)

This character helps another in a dire situation. 
- Choose another friendly character in base contact who has experienced a _Break Down_ this round.
- The friendly character immediately loses one stress point and then loses additional stress points for each point of stress this character has caused to an opponent during this combat round.

For this round, the following applies: 

- As long as the friendly character remains in base contact, this character can take the place of the other friendly character if an opposing character targets them with a shooting or close combat action.
  - If this effect occurs, switch the positions of the two friendly characters and resolve the enemy's action as though this character had been the intended target.
- This character cannot seek cover in response to the opponent’s shooting attack. However, no action points are required for them to return fire.
