# General
Bastions have a limited amount of space that can be filled with rooms. This space can be expanded over time, but it's slow process.

Players can keep their bastions separate and spread out across the world; they can be close together or even a single "bastion" that just functions as a number of smaller bastions; or they can use the rules in [[Communal Bastions]] to create truly combined bastions. The latter might be the most useful if the players want a cohesive party experience.

## Acquiring a Bastion
Players should generally get bastions at level 5, and they should start with 20 squares and 1-2 rooms, though the DM may wish to change that depending on the game they wish to run. 

## Bastion Turns
Bastion turns typically take 7 days, though your DM may wish to change that. It is during the bastion turns that everything happens, though some actions may span multiple turns.

## Squares
Squares are 5 ft. x 5 ft. in size and how the space in the bastion is calculated. Rooms and features require a certain amount of squares available to be made; rooms require unused bastion squares while features require room-specific squares. 

If the bastions are mapped physically, then the needed squares will need to be connected unless agreed upon by the DM. Some rooms or features may require that you have a certain configuration of squares available. If you don't play with mapped bastions, these requirements are to be disregarded.

### Expansion
As a baseline, it costs 100 GP/Square to expand your bastion, and each expansion takes one bastion turn. You can at a baseline expand with at most 4 squares per turn. The DM can alter these values as they wish. The price per square can even be incrementing, an example of which is it starting at 10 GP but incrementing by 5 GP for every square. Thus, while the first costs 10 GP, the fifth costs 30 GP and the 50th costs 255 GP. This method provides a bit a soft cap depending on the price increase and how much GP the players earn off both the bastion and their adventuring.

### Room Squares
A room has the following values for squares Used/Built/Max. "Max" is the largest number of squares a room can be allocated, while "Built" is the number of squares you have built for the room. "Used" is how many of the room's built squares are already used by the room's features. The available squares for room features is the difference between Built and Used.
The three variables follow Used <= Built <= Max.
Transforming a regular square into a room square has a cost given by the room, and each square takes up one of your expansion slots.

Your GM may allow you to enlarge room beyond the max size for flavor, but they should be cautious of allowing the additional expansion to increase the max. 

### Decorative Squares
Decorative squares are there for flavor. They can be stuff like corridors, stairs, ramps, etc. These squares are free to add, but cannot be used for rooms. You can at any time convert one of these squares into a proper one by following the regular rules for expansion. 


## Hirelings
Hirelings are the NPCs that man your bastion. You can give them descriptions and names if you want, but it's not required. It is assumed that rooms that require hirelings are generally capable of generating enough revenue to pay them in addition to their effects. 
You can have it be the case where play with having to actually pay them, which would be 10 GP/week or half of that if you're also housing them.

If your bastion is located away from a settlement or moving, it is expected that you have housing for your hirelings. You can also have housed hirelings even if your bastion is near or in a settlement; some rooms or features might even require housed hirelings. If you don't play with having to actively pay them, each housed hireling earns you 5 GP/week through savings.

# Rooms
Unless otherwise specified, you are only allowed one copy of each room and room feature.

## Breakdown of Parameters
### General Parameters

| Parameter         | Description                                                                                                                                     |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Initial Size      | This is the amount squares that will be put in "Used" at the room's construction.                                                               |
| Max Size          | This is the maximum number of squares the room can have.                                                                                        |
| Replaces          | This is if the structure replaces an existing structures. This is most common with room features.                                               |
| Requirements      | If there is any requirements for the room, be it bastion related, character feature related, or anything else for that matter.                  |
| Exclusivity Group | If the structure has a value in this field, then you can only build it if you have not already built one with the same value.                   |
| Minimum Level     | The minimum character level to build this room.                                                                                                 |
| Hirelings         | The number of hirelings required to man the room.<br>This is also where it's specified if they're housed hirelings and if the room houses them. |

### Construction Parameters

| Parameter                    | Description                                                                                                                                                                                                                                                                                                                            |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Square Cost                  | How many free room squares the feature needs.                                                                                                                                                                                                                                                                                          |
| Total Squares Used           | The total number of squares used by the room feature needs, counting the ones of replaced features as well.                                                                                                                                                                                                                            |
| Cost to Build                | The cost of building the room's initial square.                                                                                                                                                                                                                                                                                        |
| Cost to Expand               | The cost of expanding the room on a per square basis.<br>If the price ends with "*x*", then it means that the cost scales based on the size of the room. If the price is ɴ100*x* and you are building room square 9, then it will cost ɴ900.                                                                                           |
| Required Square Areas        | This is where certain square area formations can be specified. E.g "2x3" means that of the room feature's total squares used, at least 6 of them must be arranged as a 2x3 formation. A more complex example is "4x(3x5), 3x1", where four instances of 3x5 formations and one 1x3 are needed. These formations can be in orientation. |
| Additional Ressources Needed | If the structure needs some specific materials that the players have to specifically acquire to build it, it will be listed here.                                                                                                                                                                                                      |
| Time to Build                | How many bastion turns it takes to build the room.                                                                                                                                                                                                                                                                                     |
| Construction Goal            | If advanced construction rules are used, then this is the value the construction dice rolls should accumulate to. It is calculated to on average take about equal time as the time to build.                                                                                                                                           |
| Construction Dice            | If advanced construction rules are used, then this is what is rolled each turn while the structure is under construction. E.g. 1d4, 1d6 + 2, or 4d12 + 24.                                                                                                                                                                             |
| Expansion Slots              | The number of expansion slots you need to devote to building the structure.                                                                                                                                                                                                                                                            |

## Perks
Perks are benefits granted by a structure without you having to actively enable them with an action during a bastion turn, though said buffs can be to an actions that has to be activated.

Perks can be anything from passive buffs, synergies with other rooms, or some kind of feature you can use by doing something specific.

## Actions
Actions are the larger actions that can be done with your bastion rooms. You are generally limited to one action per room each turn. Though some rooms may allow more actions to be used at once.

## Room Features
Room features are upgrades to existing rooms. They require a certain amount of built room spaces to be available before they can be constructed.

### Demolishing Room Features
Room features can be demolished over the span of a bastion turn, during which they do not provide their perks or actions. The gain from selling what can be sold of the feature covers the demolition cost. 

## Advanced Building Time (optional rule)
For a more immersive experience to simulate random factors during the building process, these rules can be used.

The room will have a target value to reach (Construction Goal) and a dice that is rolled every bastion turn during construction (Construction Dice). The dice total is added to the Construction Value, and when the value reaches or surpasses the goal, the room or feature is constructed. 