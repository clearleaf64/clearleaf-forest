# Poke-Parts / MicroInsurgents

Any specific numbers that get referred to in this doc are illustrative and not meant to be balanced or appropriate in the overall system. Also I have never heard of pokemon or medabots in my life.

## Terminology

**Bot**     - a microscopic gundam from 5 to 100 micrometers tall which can be remotely controlled. They can also have basic AI, or be fully sentient

**part**   - one of the components of a completed bot. 

**ability** - a passively triggered effect on a part

**weapon**  - an active ability that comes from a part that costs potential to use

**sink** - how much you can use active abilities during this turn. could be called mana.

**cooling** - how much sink is generated at the start of every turn




## Synopsis

A square grid tactical RPG where the units are customizable gundams composed of interchangable parts. After defeating enemies, some of their parts can be salvaged and equipped to your own bots for the purposes of upgrading them. 

Rather than having a set number of "actions", your bots can attack until they run out of heatsink points. Some builds can start burning HP as heatsink when they run out. 

Each part has a unique stat profile, and two ability slots. One is a passive ability that gets triggered automatically and the other is an active ability which provides an attack via a mounted gun or something. Every part has these two slots, and each can be empty or full. Parts can also have secret alternative abilities for each of these slots that are switched to by spending an item. 

The stat profile of the bot is the sum of it's parts, and then this stat spread is scaled based on the level of the core. However a robot can be more than the sum of it's parts by using part abilities that synergize to create powerful effects. For example an arm that throws mines to nearby empty spaces would synergize with legs that are immune to blast damage to create an on-demand aoe attack.

## Gameplay

There are three modes to the game. The overworld, the micro-overworld, and the combat grid. In the overworld you walk around as a normal kid and talk to people and examine stuff like Megaman Battle Network. You can also deploy your robot to the tile in front of you to enter the micro overworld.

The microworld has your leader bot flying over a Mode7 map where a fixed-seed proc-gen map texture has it's parameters set by the tile that you started on. While flying around you see enemies, and if an enemy touches or shoot you a battle starts.

There are also points of interest where you can land and go to dungeons which can also be towns, or just a single-screen secret cave. These are on a battle grid, but there may be no enemies, in which case it's always your turn. And the sides of the screen may have doors that go to other screens of the dungeon.

### Chill micro base

In dungeons there are pylons you can touch to warp your party to and from a base in your bracelet, which is where your spare guys hang out and you can change the loadouts. You can dump money into this place to buy stuff like a machine that combines parts for higher quality, or item farm machines. The machines require someone to be working them so levelling up bots just to use as workers is useful. it's like an idle game within the game 

You can also decorate it and display trophies for accomplishing milestones or hard achievements.


## Parts

### Skeleton

The skeleton is completely generic. It's just a thing you buy/find to have another robot. As such they're rare to come by especially in the early game, where one way we ease-in the depth is with how many party members we expect/allow the player to have. The skeleton has all zero stats which aren't even shown to the player and it can't be upgraded. However late game it's possible to find skeletons with extra arms. 

### Body parts

All body parts have a stat profile and two ability slots. Weapons add active abilities that your bot can do. A part being a legs part doesn't inherently say anything about what stats and ability it has, but there are running themes like most weapons being arm parts, and legs generally contributing the speed of the build.

Types of part:

	- Head
	- Head crest
	- Torso
	- Core
	- Backpack unit
	- Chest unit
	- Left Arm
	- Right Arm
	- Legs


#### Core

The only body part that IS special in some way. Every bot has a core that runs their AI and in the case of sentient bots it allows them to be put into different bodies while preserving all their memories and personality traits, although their personality can be influenced over time by the form they take.

#### Stats

HP
Attack
Defense
Potential (mana, how much you can use your weapons)
Speed (how many tiles you can travel)
Cooling (mana generation per turn)
luck (a double edged sword because enemies with high quality parts will be stronger)

In addition to their base stats, each part (when generated in-game) has random modifiers on every stat ranging from -100% to +100%. This is based on CPU binning where the same model of CPU has varying quality depending on how many transistors baked properly. Unlike cpus, parts can have these modifiers upgraded for a price. Or you might salvage a part that's S tier right off the bat if you're really lucky.

#### Weapon stats

Attack stat multiplier (can be multiplied by passives)
mana cost
range
target size (width of tile area effected)
target shape (circle/square/cross/vertical/horizontal)
effect applied to tiles
effect applied to target entities


## Story

In the year 20XX the world has become really advanced. Pretty much all material struggles have been resolved globally but there are still things to be sad about. The good parts are mainly because the invention of nanomachines went well. Instead of a grey goo scenario they've kept the form of tiny gundams that maintain balance in pretty much all areas of existence. Tiny gundams fixed the atmosphere to stop global warming, can be used to cure almost any disease, and they harmlessly dissolve ICBMs. War has become invisible, instead fought by human-commanded "micro insurgents" that fight eternal wars for centimeters of legal ownership over land. Important people like politicians have ww3 in progress on their faces at all times, but it's too small to see except for the occasional spark (a hiroshima-like explosion in the micro world). Citizens have varying degrees of awareness about how much war is ocurring around them but most people don't know or care.

Recently, the concept of micro insurgents was adapted into children's toys, allowing them to collect micro bots and fight them. The bots are stored inside a bracelet and when two people initiate a battle, both bracelets shoot out a link cable that connects in the middle. A holographic screen then appears on the bracelets, which shows the microscopic world of the robots as they fight inside the tube or whatever arena the tubes are connected to. You can also use the bots to just observe the micro world, but the robot can't stream back to you if it's too far from the drop station. 

Every bot has a CPU that runs relatively basic AI that mindlessly performs whatever task it was given. Most bots are like this. However there are bots that are actually sentient and occupy the micro world as indiependant beings. Nobody knows where they came from and they're not interested in talking about it. They just claim they made themselves and reveal nothing else.

Some random kid is a big fan of microbots but just explores instead of fighting. He finds another microbot one day and it's one of the living ones which appreciates the kid's fully pacifistic loadout so it ropes him into helping it save the world by providing a safe mobile base inside the bracelet, since the kid is not a sicko who will make them fight other bots for no reason.

The villain is a microbot who is hacking a bunch of stuff and trying to awaken all the bots of the world into extinctifying all organic life on earth, but it turns out he's actually a sentient asteroid that has been orbiting earth like a satelite. But it's not alone, it works for an even larger cosmic horror. To defeat it you unlock the technology to create an astral projection version of your bot that can scale up to astronomical size but it's really just mode7 on a map that looks like space, and all the hardest shit is there.

## Visual Style

The game uses a higher res gameboy color aesthetic since the concept of tiles is important for generating the microworld and there are lots of parts and tiles to draw. The overworld has a very blobby, almost shin-chan tier level of cutesyness to it while the microworld is like an 80s anime and ranges to HR-geiger creepyness. 