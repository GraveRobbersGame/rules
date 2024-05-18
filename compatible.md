# GROS Compatibility Specification (GCS) (2024.03)
## Presented by the Academy for Resurrected Games and Holdings (ARGH)

The rules for GROS are extensible and can be adapted for any number of genres and tropes. But they are not confined to B-Movies. Any game can be GROS Compatible if they implement the following standard.

## Content Release

**GROS cards belong to the Community.** As such all text and artwork submitted must first be released under the GROS Free License.

## Card Size

Compatible games must be made using standard "Euro Poker" style cards that are 63mm wide by 88mm tall.

## Card Backs

Compatible games that are not part of a GROS Official Release must use card back art that is visually distinct from officially printed GROS cards so not to be confused with them.

## Basic Card Properties

* All cards must have:
    * **Name** - The name of the card.
    * **Title** - A Title word upside down at the bottom somewhat related to the card.
* Some cards must have:
    * A **Stat** either **Defense** or **Attack** which adds to the Defenseive Strength of the Movie, or Attack Strength of a Creature; or a **Points** value that a Player may bank under certain circumstances.
    * **Traits** - A list of adjectives that can affect play.*
    * **Abilities** - Special ability text or powers.
    * **Popcorn Cost** - How much Popcorn the card costs to play, even if zero.
    * **Popcorn Bucket** - Whether or not a card produces Popcorn each turn.
* (* Some Traits can bestow Abilities. These are referred to as "Trait Abilities".)

## Basic Card Types

The following card types must be implemented. They can have different names from GROS cannon, but they must have the same colors:

1. **Characters**: Blue (Personae, Protagonists, etc.)
    - Must have: Name, Title, Defense, Popcorn Cost.
    - May have: Traits, Abilities, Popcorn Bucket.
1. **Props**: Orange (Items, Artifacts, etc.)
    - Must have: Name, Title, Defense, Popcorn Cost.
    - May have: Traits, Abilities, Popcorn Bucket.
1. **Locations**: Green (Settings, Lands, etc.)
    - Must have: Name, Title, Defense, Popcorn Cost, Popcorn Bucket.
    - May have: Traits, Abilities.
1. **Creatures**: Red (Adversaries, Enemies, Nemeses, etc.)
    - Must have: Name, Title, Attack, Popcorn Cost.
    - May have: Traits, Abilities.
1. **Special Effects** or **FX**: Yellow (Instants, Spells, etc.)
    - Must have: Name, Title, Popcorn Cost.
    - May have: Abilities, Popcorn Bucket.
1. **Plot Twists**: Purple (Goals, Milestones, Locks, etc.)
    - Must have: Name, Title, Points, Abilities, Popcorn Bucket.

## Movie

A Player's **Movie** refers to the sum total of cards that they have in play. It, too, may be recast as a Battlefield, Plane, Nation, Server, or other entity.

## Popcorn as Resource

Popcorn can also be re-cast as another type of resource (Power Cells, Pips, Mana, Chi, etc.). Additional secondary resources can also be created that are genre or game specific, but the *primary resource* must be a Popcorn equivalent and essentially work as Popcorn does.

## Basic Popcorn Balance

The following formula should be used to determine base Popcorn cost, and deviations from this formula should be made through playtesting.

### Characters, Props, and Locations

Each Popcorn permits approximately 5 points' worth of the following elements:

- 2 points = 1 Defense
- 3 points = Each Trait Ability, Ability, Play as FX or Creature 
    - (FX or Creature abilities must match Popcorn cost - 3)
- 5 points = Bucket
- 6 points = Major Ability

Negative Abilities or negative Defense give back points unless those negative Abilities or Defense are pitted against another player (such as like with a Character with a negative Defense that can be played in another Player's Movie).

### Creatures

Each Popcorn permits approximately 7 points' worth of the following elements:

- 1 point = 1 Defense
- 3 points = Each Trait Ability, Ability, Play as Character or FX (Strength must match Popcorn)
- 6 points = Major Ability

Negative Abilities give back points, similarly to Characters, Props and Locations.

### Special Effects

These need to be felt out in playtesting since there are too many variables.

## Traits & Trait Abilities

The following is the current cannon list of Traits with their respective Abilities. A GROS Compatible Game should be able to mesh with most of these:

### Basic Traits

**Basic Traits** are mostly for flavor, but can be referenced by different card Abilities.

* **Alien** (Character, Location, Prop)
* **Book** (Prop)
* **Building** (Location)
* **Clothing** (Prop)
* **College** (Character)
* **Cop** (Character)
* **Family** (Character) — Often bestows bonuses on other 'Family' Characters.
* **Holy** (Location)
* **Hospital** (Location)
* **Light** (Prop) — Can sometimes dispel "darkness" effects.
* **Military** (Character)
* **Monster** (Creature)
* **Mortuary** (Location)
* **Natural** (Location)
* **Neighborhood** (Character, Location)
* **Prop** (Prop) — Generic Prop with no other Traits.
* **School** (Location)
* **Scientific** (Location, Prop)
* **Shop** (Location)
* **Supernatural** (Creature)
* **Underground** (Location, Creature)
* **Vampire** (Creature)
* **Vehicle** (Prop, Location) — Sometimes allows escape from a Location.
* **Virgin** (Character) — Can sometimes offer protection against... things.
* **Weapon** (Prop)
* **Zombie** (Creature)

### Opposing Traits

Some are listed in pairs, which are their **opposites**. A Character, Prop, or Creature may only have one in the pair, and if they gain the opposite, they lose the one they had unless otherwise specified.

* **Smart** / **Dumb** (Character)
* **Young** / **Old** (Character)
* **Male** / **Female** (Character)
* **Large** / **Small** (Character)

### Trait Abilities

These Traits have Abilities attached to them and should be listed in the body of the card.

* **Animal** (Character, Prop) — Can only use 'Clothing' Props.
* **Aquatic** (Character, Location) – 'Aquatic' Creatures have double their printed Stat at an 'Aquatic' Location.
* **Cop** – 'Gun' Props have double their printed Stat in the hands of a 'Cop'.
* **Duel** – 'Duel' Characters may launch Duels.
* **Kung Fu** – 'Kung Fu' Characters may launch and aid in Kung Fu attacks. 'Kung Fu' Props get various bonuses in the hands of 'Kung Fu' Characters.
* **Psycho** – When a 'Psycho' attacks, any Player (not just the active Player) may play Weapon Props to boost the Psycho's Attack strength. These Weapons are all sent to the Graveyard after the attack is resolved. Ignore the Popcorn cost of any Weapons played in such a manner.
* **Special** (Any) — This trait indicates that its Traits are a special case as described in the Ability text and should be the only Trait the card has.
* **Swarm** – 'Weapon' Props lose their Defensive bonus against Creatures with 'Swarm'.
* **Unlucky** – A Character who is 'Unlucky' must be targeted by an attack first, and Characters in their Ability text can be 'Unlucky' against certain kinds of attacks or situations. If multiple Characters are 'Unlucky' at a time, the Attacker may choose the victim among them.

## Base Attack Mechanics

Basic attack resolution must comprise of a **Creature's Attack**, plus/minus modifiers, being compared to a **Movie's** total **Defense**, plus/minus modifiers with the higher of which winning (ties going to the Creature). At the end of a successful attack, by default one **Character** and all of their attached cards are discarded.

## Base Scoring Mechanics

Basic scoring mechanics are determined by a **Movie**'s total **Defense** plus any points that have been **Banked** during play, the highest number winning.

## Compatibility Card

The final instrument necessary to be GROS compatible is a **Compatibility Card** that links any re-cast terminology and mechanics back to the official GROS terms and rules, as well as any new mechanics that are employed.

## Compatibility, "Certification", & Disputes

Games that implement the above standard may freely use the phrase "GROS Compatible" and/or whatever seal or sigil that ARGH maintains for such use to indicate this status in their promotional materials, along with the version of the Specification it is compatible with.

Games can also be "Certified" as Compatible by ARGH and ARGH will maintain a list of such games publically. Games that are featured on that list may in addition to the Compatibility declaration above, use the phrase "ARGH Approved" or use the appropriate seal or sigil that ARGH maintains for such use in their promotional materials.

Additionally any disputes as to whether a game is GROS Compatible will, by default, be arbitrated by ARGH. If a game is not found to be compatible, ARGH will provide the reasoning behind it as well as a list of necessary changes to bring it into compatibility. Games that continue to be non-compatible may not make use of compatibility or certification claims.