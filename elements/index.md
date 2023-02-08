[中文版](zh.elements)

# Game Elements

Various elements in the game are to be classified by
* Domains (previously Race)
* Classes (Professions)
* Attack Types
* Skill Elements

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

## Domains

Units are grouped into [domains](domains)

<table style="border-collapse: collapse; border: 1px solid">
  <thead>
    <tr>
      <th>Domain</th>
      <th>Entities</th>
      <th>Examples</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Human</td>
      <td>Human beings and Human Tech</td>
      <td>Human, seige weapon, tower</td>
    </tr>
    <tr>
      <td>Wild*</td>
      <td>Wild beings and Wild Tech</td>
      <td>Beast, plant, fairy, goblin</td>
    </tr>
    <tr>
      <td>Divine</td>
      <td>Sacred beings</td>
      <td>God, ascended humans</td>
    </tr>
    <tr>
      <td>Chaos</td>
      <td>Dark beings and Dark Relic</td>
      <td>Demon, alien, ghost</td>
    </tr>
    <tr>
      <td>Unknown</td>
      <td>Titans</td>
      <td>Cerberus, Cyclops, Ice Dragon</td>
    </tr>
  </tbody>
</table>


## Attack Types

Attacks (and defenses) are classified by [attack types](attack-type):

<table style="border-collapse: collapse; border: 1px solid">
  <thead>
    <tr>
      <th>Type</th>
      <th>Source</th>
      <th>Weapon examples</th>
      <th>Defense examples</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan=3>Physical</td>
      <td>Physics</td>
      <td>Sword</td>
      <td>Armour</td>
    </tr>
    <tr>
      <td>Chemical</td>
      <td>Acid</td>
      <td>Medicine</td>
    </tr>
    <tr>
      <td>Biological</td>
      <td>Poison</td>
      <td>Thorns</td>
    </tr>
    <tr>
      <td rowspan=4>Magical</td>
      <td>Light Magic</td>
      <td>Refraction</td>
      <td>Force field</td>
    </tr>
    <tr>
      <td>Dark Magic</td>
      <td>Curse</td>
      <td>Cloaking</td>
    </tr>
    <tr>
      <td>Fairy Magic</td>
      <td>Enchantment</td>
      <td>Mystical mist</td>
    </tr>
    <tr>
      <td>Faith</td>
      <td>n/a</td>
      <td>Blessing</td>
    </tr>
  </tbody>
</table>

## Skill Elements

Skills are classified by [skill elements](elements)

<table style="border-collapse: collapse; border: 1px solid">
  <thead>
    <tr>
      <th>Type</th>
      <th>Concept</th>
      <th>Sub-Type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan=10><a href="control">Control</a></td>
      <td rowspan=3>Disruptive</td>
      <td>Stun</td>
    </tr>
    <tr>
      <td>Fear/Spook</td>
    </tr>
    <tr>
      <td>Taunt/Attract</td>
    </tr>
    <tr>
      <td rowspan=3>Stalling</td>
      <td>Binding</td>
    </tr>
    <tr>
      <td>Silencing</td>
    </tr>
    <tr>
      <td>Slowing</td>
    </tr>
    <tr>
      <td rowspan=4>Transformation</td>
      <td>Knock-back</td>
    </tr>
    <tr>
      <td>Pushing</td>
    </tr>
    <tr>
      <td>Pull-in</td>
    <tr>
      <td>Conversion</td>
    </tr>
    <tr>
      <td rowspan=6><a href="natural-elements">Natural Elements</a></td>
      <td rowspan=2>Power</td>
      <td>Fire</td>
    </tr>
    <tr>
      <td>Light</td>
    </tr>
    <tr>
      <td rowspan=2>Darkness</td>
      <td>Ice</td>
    </tr>
    <tr>
      <td>Shadow</td>
    </tr>
    <tr>
      <td rowspan=2>Support</td>
      <td>Air</td>
    </tr>
    <tr>
      <td>Earth</td>
    </tr>
    <tr>
      <td rowspan=8>Health</td>
      <td rowspan=3>Recovery</td>
      <td>Heal</td>
    </tr>
    <tr>
      <td>Regenerate</td>
    </tr>
    <tr>
      <td>Life Steal</td>
    </tr>
    <tr>
      <td rowspan=2>Drain</td>
      <td>Harvest</td>
    </tr>
    <tr>
      <td>Curse</td>
    </tr>
    <tr>
      <td rowspan=3>Endurance</td>
      <td>Armour</td>
    </tr>
    <tr>
      <td>Toughen</td>
    </tr>
    <tr>
      <td>Aureole</td>
    </tr>
    <tr>
      <td rowspan=4>Laws</td>
      <td rowspan=3>Law Bending</td>
      <td>Time Travel</td>
    </tr>
    <tr>
      <td>Revival</td>
    </tr>
    <tr>
      <td>Summoning</td>
    </tr>
    <tr>
      <td>Assertion</td>
      <td>Edict</td>
    </tr>
    <td rowspan=6>Other</td>
      <td rowspan=2>Creation</td>
      <td>Build</td>
    </tr>
    <tr>
      <td>Magical Forge</td>
    </tr>
    <tr>
      <td rowspan=4>Biological</td>
      <td>Mimicry</td>
    </tr>
    <tr>
      <td>Parasitism</td>
    </tr>
    <tr>
      <td>Spawn</td>
    </tr>
    <tr>
      <td>Transmutation</td>
    </tr>
  </tbody>
</table>
