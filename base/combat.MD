@Author: Brad Arnett
@Note: Donate if you like this project:

# Combat

## Rules of Engagement

### Turns and Duration

A combat scenario is divided into turns during which each participant gets to act once.  A turn is 5 seconds long in the game world.  When combat begins, the first turn happens, and turns continue until combat ends.

These rules are intended for use in "combat", though they can also be used in other situations.  If there is a situation where your game would benefit from the granularity of a turn-based game, then use these until it makes sense not to.

When a duration is measured in turns, assume that the duration begins the first turn after it was started.  For example, if a character used a stim that gave a bonus for a single turn, then it would give that bonus for the next turn. 

### Actions

An Action is a deliberate activity that a character performs within their part of a combat turn.  This activity could be anything that a person could reasonably do in less than five seconds.  Some common examples are below:

- Walk 20 feet
- Run 40 feet
- Climb a 3 meter ladder
- Make a running jump
- Attack someone
- Pick up an object from the ground
- Retrieve an item from a container

Some actions can be combined.  A character can walk 10 feet and perform most actions still, and it's possible to drop something while running.  All actions listed in the Interrupted Actions section can happen while performing another action.

The GM should have each player declare their actions.  This doesn't need to be done in any particular order, and players can be skipped and come back to if they need more time to decide.

After each player has declared their actions, the GM should then describe the outcome, asking players to roll skill tests or attacks as needed.  Situations where two characters are trying to do something mutually exclusive should be resolved with opposed skill tests.

Generally each action is assumed to happen at the same time, however, this might not always make sense as some actions are generally going to happen faster than others.  The GM should decide if any actions might preempt others.

### Interrupted actions

If your action is interrupted, you can still perform Quick Actions.  These are simple actions that can be done in a second.  Some examples of Quick Actions include:

- Drawing a weapon or other item from a dedicated storage location (i.e. holster)
- Letting go of an object held in hand.
- Communicating with others.
- Going prone.  This allows dodge rolls against any other attacks made this round.


<div class="sidebar" markdown="1">
### Example Encounter

Zeven rounds a corner in a hallway and comes face to face with a security guard.  Combat begins, and then Zeven shoots at the guard while the guard attempts to run over to hit an alarm button on the wall.  The GM decides that Zeven's shot could stop the guard before he got to the alarm, so the GM asks Zeven to roll her attack.  

Zeven rolls 2d6 and gets 7.  Then she adds her Dexterity (3) along with her Firearms (1) and gets a 11.  She's trying to aim for his leg, so that's a -2 penalty, but the guard is within 20 ft, so that's a +1 bonus.  She adds a total modifier of -1 to the hit and tells the GM she has a 10.  The guard was moving in another direction, so he's going to try to dodge while moving.  He rolls 2d6 and gets a 5.  he adds his Dexterity (3) and his Dodge (1) for a total of 9.  Zeven hits, so she rolls on the chart to make sure she hit him where she wanted to.  She was aiming for his left leg, and rolls 2d6 and gets an 8.  Just enough to pass!

Zeven rolls and shoots the guard in the leg, dropping him to the ground.  The GM decides that the guard can't hit the button, but he's not dead.  Instead, he lets out a loud yell for help and draws his pistol, preparing to take aim at the intruder next turn.

On the next turn, Zeven fires at the guard's head while he takes two shots back at Zeven.  The GM says that both actions occur at the same time, so Zeven rolls 2d6 for her shot and gets 8.  Adding her Dexterity (3) with Firearms (1), she gets a 12.  She's making a called shot again, so she takes a -2 penalty, and an extra -1 for the target being prone, but she still gets the +1 from the target being within a 20 feet, for a total of -2.  The guard cannot dodge since he is already on the floor, and so her total of 10 hits, and the guard takes a bullet to the head.  

Meanwhile, the GM rolls 2d6 for each of the guard's shots and gets 11 and 10.  Each one of those gets a +1 modifier from range and a -2 modifier for rapid firing for totals of 10 and 9.  Zeven will drop to the ground as she's firing so she can dodge.  She rolls 5 on 2d6 and adds her Dexterity (3) along with Dodge (1) for a total of 9.  She dodged one bullet, but got hit by the other one.  The GM rolls 2d6 and determines that the guard shot her in her left arm.

She marks a point of damage down on her arm.  Any skills she has to perform with that arm will now be at half their normal bonus until she can heal the damage or find some painkillers.  The guard is much worse off and must now make a ```Blackout (Fortitude) 12``` Test.  He gets 5 on 2d6 and adds his Fortitude (3) along with his Blackout skill (2).  He only gets a 10, and so the pain is too much for him, and he goes into shock.  He is now in critical condition and at risk of death.

Zeven looks at her mangled arm and curses.  After a brief glance down the corridor, she picks her pace up to a hustle, concerned that the gunshots wouldn't go unnoticed.  A handful of moments later, her hustle shifts into a sprint as the alarms start going off.

</div>

## Attacking

There are a few basic steps to any combat turn:

  1. Declare target and whether the attack is a 'called shot'.
  2. Roll an attack test with the chosen weapon
  3. Target can choose to dodge or parry
  4. Apply modifiers and check if test passed difficulty
  5. Determine where the hit lands

### Determining if you hit
To see if a character hits with a weapon, first declare whether you are making a regular shot or a called shot (as well the location you are aiming for).  Next, roll a test using the corresponding ability and weapon skill.  The base difficulty for this test is 9, and is modified by the rules below.

### Artful dodging
The targeted character can actively attempt to avoid getting hit.  They can do this by rolling dice as a Parry (Strength) test (requires an object held to parry with) or a Dodge (Dexterity) test (requires nearby cover, or to drop to the ground).  Use the outcome of this roll as the base difficulty for the attackers.  If the attacker rolls it or higher, it’s a hit!

<div class="sidebar" markdown="1">
### Never saw it coming

If a target is both, not threatened and also completely unaware of the attacker's presence, then the attacker will do two points of damage on a successful hit instead of one.  This damage can still be reduced by armor or other effects.

</div>

### Other bonuses and penalties


|Circumstance  | modifier|
|----------------|----|
|More than 50 feet away|-1 (per 50 ft)
|Less than 20 feet away|+1
|At least 50% of the target is not visible|-1
|Target is in darkness or dim light|-1
|Target is lying prone|-1
|Firing a called shot|-2|
|Firing multiple shots per round| -2 (per shot) |

### Determining where you hit
To determine what hitbox is damaged, roll 2d6 and compare the chart for your attack type:

<div class="sidebar" markdown="1">

### Called Shot

A called shot is different than a regular shot.  Hitting even in spite of the penalty means the character hit <i>somewhere</i> on the target.  It may not have been where you intended, but it's more likely that it was.

Roll 2d6 and consult the chart below.  If your roll matches the called location, then you hit that hitbox.  If the roll doesn't match, then it becomes a torso shot.

</div>

<div class="flex" markdown="1">
<div markdown="1">
**Regular Attack:**

| 2d6 roll |Hitbox location |
|-----|----------------|
|2-3  | Head 
|4    | Left Arm
|5-6 | Left Leg
|7-8 | Torso
|9-10| Right Leg
|11  | Right Arm
|12  | Groin
</div>
<div markdown="1">
**Called Shot:**

| 2d6 roll |Hitbox location* |
|-----|----------------|
|9-12  | Head 
|8-12 | Any Arm
|8-12 | Any Leg
|11-12 | Groin

\* If roll doesn’t match the called location, the torso is hit instead.
</div>
</div>
That location is then hit by the weapon and does whatever damage is listed in the weapons profile, first to whatever armor the targeted character is wearing in that location, and then to the character itself.  Most weapons deal a single point of damage, though certain weapons may do more damage under certain circumstances.



