![ExpeditionMenu](https://i.imgur.com/bzV99Hn.png)
# Expedition
**[WARNING] Despite every attempt to remove bugs, some may remain.**
**Please keep this in mind as you play this initial release.**


Expedition is a new gamemode for Rain World featuring random starting locations, challenges, new abilities and permadeath. Embark on a new expedition as Monk, Survivor or Hunter with the goal of completing a list of random tasks. Earn points by taking on more and more difficult challenges to unlock new perks and abilities.

## Installation

**[Download the latest version of Expedition here](https://github.com/LeeMoriya/Expedition/releases/tag/v1.0)**


[Enum Extender](https://beestuff.pythonanywhere.com/audb/api/mods/0/1/download/latest) is required for Expeditions to function correctly, you can find this in the 'Tools' tab on RainDB.
To install Expeditions, simply place the Expedition.dll file into your 'Mods' folder and apply both it and Enum Extender with Partiality, or if using BepInEx, place it in your Plugins folder.

## Difficulty

Expedition mode can be played as all three Slugcats, each with their own pros and cons just like in Story mode, e.g. Monk will permanently unlock gates and Hunter will have more difficult creature spawns, however their limited cycles are disabled in this mode.

There are also Easy, Normal and Hard difficulties to choose from with the following differences:

- Easy: No permadeath
- Normal: Dying at the lowest karma level will end the run
- Hard: Dying at all will end the run (not for the faint of heart)

Karma flowers act as your safety net, as permadeath will not occur if you karma is reinforced when you die. 

## Challenges

There are five types of challenges in Expedition mode:

- Pearls: Find and transport a unique pearl to Moon.
- Combat: Kill the specified amount of a certain creature.
- Echo: Encounter the specified Echo.
- Achievement: Earn the specified achievement.
- Miscellaneous: Challenges that don't fit in other categories

## Unlocks

Earned by acquiring a certain total number of points from successful expeditions you can unlock the following perks and abilities to assist with future runs:

**Perks**
- Start with reinforced karma
- Start with neuron glow
- Expand possible starting locations
- Start with higher karma
- All slugcats move faster

**Abilities**
- Slow Time (Slow down time for a limited duration)
- Spear Expert (You can carry a spear in each hand, and all slugcats can carry a spear on their back)
- Stealth form (A camouflaged form that makes you much harded to detect)
- Double jump (Jump a second time in mid-air, or launch high into the air from a crouched position)
- Mark and Recall (Place a warp marker at your current location and return to it from anywhere in the same region)

## Burdens

Burdens are additional penalties you can apply to your expedition to make it harder in return for more points. These are unlocked by completing 1-4 expeditions:

- Hunted: Predators always know where you are, and they are coming.
- Starved: You begin each cycle malnourished and prone to exhaustion.
- Blinded: All regions become shrouded in darkness.
- Doomed: Adjustable cycle limit, more points are earned for fewer cycles.

## Additional Information

The following changes have been made to certain mechanics while on a Expedition:

- Hunter has no cycle limit.
- Moon is alive and well when playing as Hunter.
- Visiting Pebbles will only raise your karma cap by two.
- Hunter must visit echoes first before they will spawn.
- Achievements are not gated behind the Survivor achievement.
- Echoes will not spawn in the first cycle.

Currently, Monk cannot take on Pearl challenges, however this may change.

With the exception of Echo and Achievement challenges, progress towards challenge completion is only saved when you rest. If you began the cycle with 3/5 creatures killed, killed two more during the cycle, but then die before making it back to a shelter, your progress will be reset to 3/5.

In the event that a challenge becomes impossible to complete, e.g. a pearl becomes lost. You can end the Expedition prematurely by entering the void sea. You will not be forced through the entire sequence, but points for incomplete challenges will not be awarded.

Save data for both your current Expedition and your global progress is stored in your UserData folder.
