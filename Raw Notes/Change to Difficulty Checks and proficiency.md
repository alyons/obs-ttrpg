# Difficulty Checks & Proficiency
So, the question being asked is how we can make character choices more impactful on the outcomes of random rolls in Dungeons and Dragons 5e. First, we need to establish the Difficulty Classes (DCs) of tasks.

| Task Difficulty | Difficulty Class |
| --------------- | ---------------- |
| Trivial         | 5                |
| Easy            | 10               |
| Moderate        | 15               |
| Taxing          | 20               |
| Extraordinary   | 25               |
| Nigh Impossible | 30               |

If we want to keep the task difficulties as they are, how can we push for players to have impact on their tasks? Well, we know die have different maximum values, and the less die you roll, the more random the result (2d4 more likely rolls towards the median over 1d8).

| Value | Die       | Value | Die                 |
| ----- | --------- | ----- | ------------------- |
| 4     | 1d4       | 20    | 1d20, 2d10, 5d4     |
| 6     | 1d6       | 24    | 2d12, 3d8, 4d6, 6d4 |
| 8     | 1d8, 2d4  | 28    | 7d4                 |
| 10    | 1d10      | 30    | 3d10, 5d6           |
| 12    | 1d12, 2d6 | 32    | 4d8, 8d4            |
| 16    | 2d8, 4d4  | 36    | 3d12, 6d6, 9d4      |
| 18    | 3d6       | 40    | 2d20, 4d8, 10d4     | 

So, what do we have from this:
	- There are multiple ways to hit certain value thresholds
	- The more die you roll, the higher your floor and the more predictable your outcome will be

So, what if we tried to leverage these ranges and work proficiency as follows, pulling some from D&D 3.5:

- Proficiency will have ranks, from zero to eight, with names as follows: Untrained, Novice, Apprentice, Journeyman, Inspector, Educator, Master, Legendary, Demi-God
- As part of leveling, players will earn a certain amount of proficiency points which they can add ranks to any skill.
- Backgrounds, Classes, Lineages, and Magic Items might increase a base proficiency:
	- Fighters have +1 proficiency with weapons, and perhaps that goes up to +3 as they level up, where as Wizards might always have a +0 proficiency
- A character can only assign 5 points to any skill rank, so it would be impossible for certain classes to be on the same tier as others (excluding other factors).
- If a DC is less than or equal to the minimum a player could roll, the check automatically succeeds:
	- E.G. A rogue with a +5 Dex Mod who is a Demi-God at Sleight of Hand and is proficient with theives tools wouldn't have to roll to lock pick any lock with a DC of 15 or less.
- If a DC is greater than the maximum a character could achieve, they automatically will fail the attempt... whether or not they know that going into it would be up to the DM, though for a general rule, I would say if their max is close to the DC, they have enough knowledge that they aren't skilled enough to take on the task.
- Expertise would add an additional rank, outside of the 5 from leveling up
- Jack of All Trades
	- At a low level, any skill attempted is always attempted as though you are at least a Novice
	- At a mid level, any skill attempted is always attempted as though you are at least an Apprentice
	- At a high level, and perhaps only a certain Bardic College, any skill attempted is always attempted as though you are at least a Journeyman

## Proficieny Die

| Proficiency Tier | Die  | Modifier   | Critical Range | Percent  |
| ---------------- | ---- | ---------- | -------------- | -------- |
| Untrained*       | 1d10 | 0x or 1/2x | N/A            | 0%       |
| Novice           | 1d12 | 1/2x       | N/A            | 0%       |
| Apprentice       | 2d6  | 1/2x       | N/A            | 0%       |
| Journeyman       | 1d20 | 1x         | 20             | 5%       |
| Inspector        | 2d8  | 1x         | 15-16          | 4.6875%  |
| Educator         | 3d6  | 1x         | 16-18          | 4.6296%  |
| Master           | 4d4  | 3/2x       | 13-16          | 11.3281% |
| Legendary        | 2d10 | 3/2x       | 17-20          | 10%      |
| Demi-God         | 5d4  | 2x         | 16-20          | 11.8164% |

### Notes
- The die are not finialize on this list, as these were my gut feelings when creating this idea.
- As the numbers change, imagine that your character is mastering new techniques which can yeild better outcomes, but are more risky to use.
- For critical ranges:
	- **3d6:** 15-18 => 9.2593%
	- **5d4:** 15-20 => 21.6797%
-  Untrained skills would be marked by a flag stating if an attempt can be made without proficiency.
	-  Athletics such as jumping would net you your half modifier
	-  Lockpicking would afford you no such bonus.
