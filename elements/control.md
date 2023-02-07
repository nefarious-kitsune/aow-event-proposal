# Control

[The AoW Ideas project](https://github.com/nefarious-kitsune/aow.ideas):
*Ideas from AoW players on changes & improvements to help make the game more interesting.*

## Problem

- Some skill elements have no weakness
- Players often *stack* skill elements by using a large number of the *same* troops
- The game sometimes feels like a monotonous war of *resource* rather than a war of *strategy*

## Suggested Solution

- Redesign control such that players need to use **a variety of troops** to maximize their skills
- Split "control" into three distinct types: Disruptive, Stalling, and Transformation
- Design controls such that each type has both **strength** and **weakness**
- Design controls such that controls of same type cannot stack
- Design controls such that controls of different type can **enhance** one another

-----

## Mechanics

There are 3 types of Control
- Disruptive
- Stalling
- Transformation

Each unit has one clock for Disruptive and one or more clocks for stalling

<table style="border-collapse: collapse; border: 1px solid">
  <thead>
    <tr>
      <th>Type</th>
      <th>Sub-Type</th>
      <th>Primary Effect</th>
      <th>Secondary Effect</th>
      <th>Removable</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan=3>Disruptive</td>
      <td>Stun</td>
      <td>Stop attack or moving</td>
      <td>Skill and targeting reset</td>
      <td>Yes</td>
    </tr>
    <tr>
      <td>Fear</td>
      <td>Forced escape</td>
      <td>Skill and targeting reset</td>
      <td>Yes</td>
    </tr>
    <tr>
      <td>Taunt</td>
      <td>Forced targeting</td>
      <td>Skill reset</td>
      <td>Yes</td>
    </tr>
    <tr>
      <td rowspan=3>Stalling</td>
      <td>Binding</td>
      <td>Stop attack or moving</td>
      <td>n/a</td>
      <td>No</td>
    </tr>
    <tr>
      <td>Silencing</td>
      <td>Suppress skill release</td>
      <td>n/a</td>
      <td>No</td>
    </tr>
    <tr>
      <td>Slowing</td>
      <td>Slow down attack or moving</td>
      <td>n/a</td>
      <td>No</td>
    </tr>
    <tr>
      <td rowspan=3>Transformation</td>
      <td>Knock-back</td>
      <td>Pushing back</td>
      <td>Stun</td>
      <td>Yes</td>
    </tr>
    <tr>
      <td>Snatching</td>
      <td>Pulling in</td>
      <td>Stun</td>
      <td>Yes</td>
    </tr>
    <tr>
      <td>Conversion</td>
      <td>Conversion</td>
      <td>Binding</td>
      <td>Yes</td>
    </tr>
  </tbody>
</table>

------

## Disruptive

Disruptive is interruption *with* some secondary effect. It can be either Physical (Stun) or 
Psychic (Fear, Taunt, Spook, Mind Control)

### Characteristics of Disruptive
- Disruptive has one or more secondary effects
  - Target reset: effected unit will reselect a target
  - Skill reset: reset effected unit's trigger number (for example, effected Peltasts would drop their "Fighting spirit" effect) and *cause Aly to drop the bomb*
- Disruptive skill cannot affect existing Disruptive effect`
  - For example: if a troops is stunned for 3 seconds, the troops cannot be affected by fear, taunt, transformation, or another stun until the 3 seconds has lapsed
- Disruptive effect can be **removed**
  - Example 1: if Aly is stunned for 3 seconds, and the cooldown of her skill ended within the 3 seconds, Aly can break free from the stun effect and release her skill
  - Example 2: if a unit is stunned, the effect can be removed by a Nun or another support unit
  - Example 3: when a unit is protected by Control Immunity skill, the unit cannot be affected by any Disruptive skill
- Disruptive does not affect cooldown clock
  - Example: if Orc Hunters is stun for 3 seconds, they can escape from the stun when their  cooldown clock resets.
### Stun

Stun cause effected unit to stop attacking or moving.

### Fear

Fear cause effected unit to flee from the enemy. The fleeing speed is 1/2 of movement speed (e.g. the faster the troops is, the further away the troops flee.)

### Taunt

Taunt cause effected unit to change target to a specific enemy.

------

## Stalling

Stalling is interruption *without* any secondary effect.ect.

There are 4 sub-types: Binding, Silencing, and Slowing.

### Characteristics of Stalling

- Stalling has no secondary effects
- Stalling skills have some stacking ability
  - For example: if a unit is under 3-second Binding, and then it is affected by a 4-second Binding, the maximum Binding time is 5 seconds
  - For example: if a unit is under 3-second Binding, and then it is affected by a 2-second Silencing, the unit is under both Binding and Silencing control
- Stalling effect can NOT be removed
  - Example 1: if Aly is bound for 5 seconds, and the cooldown of her skill ended within the 5 seconds, Aly can NOT break free and release her skill
  - Example 2: if a unit is frozen, the effect can NOT be removed by a Nun or another support unit
  - Example 3: when a unit is protected by Control Immunity skill, the unit can still be frozen by Chione's blizzard
- Stalling does not affect cooldown clock
  - Example: if Orc Hunters is frozen for 5 seconds, they cannot escape from the freeze with their skill, but they can use their skill immediately after the freeze.

### Binding

Binding (binding and freezing) cause effected unit to stop attacking or moving.

### Silencing

Silencing (such as Ivan and Harrison's skills) cause effected unit to delay skill release.

### Slowing

Slowing (such as Ice Mage's slowing skill) cause effected unit to slow down.

------

## Using Disruptive and Stalling

Disruptive and Stalling each have their own strength and weakness.

<table style="border-collapse: collapse; border: 1px solid">
  <thead>
    <tr>
      <th>Type</th>
      <th>Strength</th>
      <th>Weakness</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Disruptive</td>
      <td>Useful secondary effect (such as skill reset)</td>
      <td>Can be removed. Cannot stack.</td>
    </tr>
    <tr>
      <td>Stalling</td>
      <td>Cannot be removed. Some stacking is possible.</td>
      <td>No useful secondary effect</td>
    </tr>
  </tbody>
</table>

The two types are designed such that
- overusing one type of control can be counter productive
- proper mixing of the two types can help maximizing the control effect

When a unit is under a Stalling effect, and the unit is affected by a Disruptive skill, the *primary* effect of the Disruptive skill would not apply, but the *secondary* effect of the Disruptive skill would apply.

Example 1: If Aly is stun by Pirate Ship, and during the stun period Aly is affected by the Primal Fear skill of the Witchcraft Totem, Aly will not flee and the stun time will not be extended.

Example 2: If Aly is frozen whiling charing her bomb, and during the frozen period Aly is affected by the Primal Fear skill of the Witchcraft Totem, Aly will not flee but she will drop her bomb due to the secondary effects (skill and targeting reset).

Example 3: If Aly is under protection of Control Immunity, Aly can still be prevented from using her skill with Binding or Silencing, and Aly could be effected by Stun when the time period of Control Immunity expires.

------

## Transformation

### Knock Back

### Conversion

Conversion cause effected unit to momentarily change into something else.