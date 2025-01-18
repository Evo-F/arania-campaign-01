---
draft: true
---

> [!danger] Spoilers and WIP
> This page is simultaneously a spoiler and a work-in-progress. Just ignore it for now.
# Summary
Throughout the campaign, characters may find themselves in command of one or more armies or similar units, representing collections of individuals acting with a common objective. 

These units follow different rules from individual creatures or summons that a character may command. 

Although "collective units" are not limited to armies per se, this page will use the term "army" to refer to all units of this type. If different rules are applied according to the type of unit, this will be noted. 

An army is made up of units in three categories: Infantry, Cavalry, and Artillery. 
- One unit of Infantry represents approximately one-hundred armed soldiers on foot.
- One unit of Cavalry represents approximately fifty soldiers mounted on rideable Beasts. 
- One unit of Artillery represents approximately twenty artillerists and the equipment they operate, such as cannons or trebuchets.

An army may consist of any number of units across any of the three categories, but the total number of units in the army may not exceed the Army Commander's Level plus their Charisma modifier. 

When not in combat, the army moves as a single unit. This is explained further in the "Army Movement" section. When in combat, the army's units may be controlled individually, but may be combined and split as needed or desired. This is explained further in the "Army Combat Rules" section.
# Army Command
An army has two core command roles: an Army Commander and a Ground Commander. 
## Army Commander
- The **Army Commander** is the character who controls or "owns" the army, and issues orders to it. The Army Commander does not need to physically reside or move with the army. A character may be the Army Commander of any number of armies up to their Charisma modifier. Characters with a Charisma modifier of 0 or lower, or characters incapable of communicating, may not serve as an Army Commander. 
## Ground Commander
- The **Ground Commander** is the character who is responsible for directing the army towards the completion of specific objectives, or carrying out orders issued by the Army Commander. The Ground Commander **must** reside and move with the army itself, physically leading them and receiving orders from the Army Commander. A character may only serve as Ground Commander in a single army. The Ground Commander must be capable of speech, but aside from this, there are no other requirements. 

Each of these roles has dedicated sections explaining their mechanics in more detail. Additional information to note:
- Army Commanders may serve as the Ground Commander in one of their armies, either on a temporary or permanent basis. If an Army Commander no longer wishes to serve as their army's Ground Commander, they must designate another character to serve in that role. 
- Even if an army's Ground Commander is an NPC, they will need to have a stat block, as the Ground Commander's stats are relevant in the operation of an army. 

# Army Attributes
An army has a number of attributes that should be tracked for various purposes. This section provides a very brief overview of each attribute that should be tracked. Additional explanation will be provided for each attribute in relevant sections.
## Strength
Strength is a very basic measure of the power and scale of an army. An army's overall strength is the total number of Infantry, Cavalry, and Artillery units which constitute it. 
## Morale
Morale is a representation of how willing the army is to fight for its cause and the cause of the Army Commander. Armies with high morale can receive bonuses in and out of combat, while armies with low morale can receive penalties in and out of combat. Armies with especially low morale may disband altogether, or in rare circumstances, turn renegade. An army's morale can range from +10 to -10, and a newly-formed army will have a morale of 0. 
## Speed
Speed is a measure of how much ground the army as a whole can cover over a given period of time. An army's speed is expressed in miles per hour, and is highly dependent on many factors including strength, morale, and overall composition of the army.
## Combat Readiness
Combat Readiness is a measure of how prepared the army is to engage in combat at the present time. Combat Readiness ranges from 0 to -4, and a newly-formed army will have a Combat Readiness of 0. 
- An army with a CR of 0 is as prepared as they can be for combat. You would expect to see this from armies that are about to siege a fortress, or amassing on a battlefield. 
- An army with a CR of -4 is totally disorganized and unprepared for combat. You would expect to see this from armies that have been stood down or armies with very low morale on the verge of disbandment. 
	- An army with a CR of -4 can be defeated without contest in most circumstances. See "Army Combat Rules" for more details. 
# Assembling an Army
Characters are eligible to assemble an army starting at Level 12, provided they meet the qualifications to become an Army Commander. Players should work with the DM to determine how best to recruit forces into the army. By default, the character assembling an army is designated as both the Army Commander and Ground Commander; the role of Ground Commander may be delegated to a friendly character or Party member who is willing. 
- Characters may not be *compelled* to serve as Ground Commander. 
# Army Maintenance
Armies require periodic maintenance and attention in order to keep their combat effectiveness and readiness. This is handled through an "Army Maintenance Turn", which by default occurs at the start of every in-game month, or on a different interval as determined by the DM. 

During an Army Maintenance Turn, the following actions are resolved:
1. The Army Commander must pay for **provisions** for each army not currently stood down. The cost of provisions for an army is calculated as `Total Army Size x 100 GP`. The cost must be paid in full and can only be paid in coin, but the money may come from any combination of sources under the Army Commander's control. 
	- When an army receives their provisions, they receive +1 morale if their morale is below 0. If their morale is greater than or equal to 0, it does not change upon receiving provisions.
	- When an army does not receive their provisions, they lose -1 morale immediately. 
2. The Army Commander may give out **bonuses** to each army at their discretion. Bonuses increase an army's morale, but there is no penalty for not giving out bonuses. An army that receives `Total Army Size x 25 GP` in bonus pay will receive +1 morale; this amount can be stacked with the appropriate amount of money.
3. The Army Commander may grant **leave time** to each army at their discretion. Leave time is measured in intervals between Army Maintenance Turns (typically one in-game month). If an army is granted leave, they immediately stand down and have their combat readiness set to -4. As long as the army is on leave, they cannot perform any actions or respond to any commands. The army can be instructed to regroup at a specific accessible location on the map once their leave expires; if no location is assigned, they will regroup at the Army Commander's bastion if they have one, or the nearest friendly bastion if they do not. Upon regrouping, an army receives +2 morale for each interval that they were on leave, and their combat readiness is set at 0. 
	- An army may be recalled from leave early during an Army Maintenance Turn, in which case they will immediately begin regrouping at the specified location. This regrouping will take 7 days. At the end of the seventh day, the army will be ready to receive commands and take actions.
	- If an army is recalled from leave early, their morale bonus is halved and they regroup with a combat readiness of -1. 
4. All armies receive the following effects based on their morale after processing all previous adjustments:
	- +8 or higher - The Army Commander rolls once on the Army Inspiration table (located under "Tables") for the relevant army.
	- +5 or higher - The army receives +1 to combat readiness. 
	- -5 or lower - The army loses -1 to combat readiness. 
	- -8 or lower - The Army Commander rolls once on the Army Dilemma table (located under "Tables") for the relevant army.
	- -10 - The army is disbanded. 
## Disbandment
An Army Commander may disband an army they control at any time, or an army may disband itself if its morale is low enough. When an army disbands, the Army Commander rolls a d20 to determine its fate; if the roll is a 1, the army goes renegade, otherwise it disbands without issue.
- If the army is disbanded directly by the Army Commander, they may roll the d20 with advantage. 
- If an army disbands due to low morale, and the army's Ground Commander was a bastion hireling (Lieutenant), the hireling is lost. 

# Army Commander Mechanics
The Army Commander is the character in charge of one or more armies, and is responsible for issuing orders and directives to those armies in order to control their actions. Typically, this means directing the army to a different location, directing the army to attack or defend an objective, or directing the army to hold its current position (and optionally fortify it). 

The Army Commander issues these orders by communicating directly with each army's Ground Commander, who is physically with the army at all times. Any method of communication between characters is acceptable for this task; however, Army Commanders should be aware that conventional communication methods are subject to delays due to delivery time. 
- It is recommended that Army Commanders set up fast lines of communication with their various Ground Commanders through the strategic use of Sending Stones or spells that perform a similar function.  
- Alternatively, Army Commanders may allow their armies to act semi-autonomously at the discretion of the Ground Commander, in pursuit of a larger goal. 
# Ground Commander Mechanics
# Army Combat Rules


