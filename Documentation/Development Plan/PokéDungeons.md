---
sticker: emoji//1f48e
---
#### **Section Index**

- [[#Concept Overview|Concept Overview]]
- [[#World Integration & Access|World Integration & Access]]
- [[#Dungeon Layout & Environmental Mechanics|Dungeon Layout & Environmental Mechanics]]
	- [[#Dungeon Layout & Environmental Mechanics#Floor Portals & Objective Clarity|Floor Portals & Objective Clarity]]
	- [[#Dungeon Layout & Environmental Mechanics#Final Floor Exit Portal|Final Floor Exit Portal]]
	- [[#Dungeon Layout & Environmental Mechanics#Quest System|Quest System]]
	- [[#Dungeon Layout & Environmental Mechanics#Blackout & Failure Conditions|Blackout & Failure Conditions]]
	- [[#Dungeon Layout & Environmental Mechanics#NPC Quests & Objective Handling|NPC Quests & Objective Handling]]
	- [[#Dungeon Layout & Environmental Mechanics#Shared Target and Boss Logic|Shared Target and Boss Logic]]
	- [[#Dungeon Layout & Environmental Mechanics#Conditional Behavior|Conditional Behavior]]
	- [[#Dungeon Layout & Environmental Mechanics#Floor Layouts & Randomization|Floor Layouts & Randomization]]
	- [[#Dungeon Layout & Environmental Mechanics#Fixed Floors|Fixed Floors]]
	- [[#Dungeon Layout & Environmental Mechanics#Floor Variants|Floor Variants]]
		- [[#Floor Variants#Purpose|Purpose]]
		- [[#Floor Variants#Use Cases|Use Cases]]
		- [[#Floor Variants#Implementation Notes|Implementation Notes]]
	- [[#Dungeon Layout & Environmental Mechanics#Displayed vs. Internal Floor Numbers|Displayed vs. Internal Floor Numbers]]
	- [[#Dungeon Layout & Environmental Mechanics#Annex Sub-Dungeons|Annex Sub-Dungeons]]
	- [[#Dungeon Layout & Environmental Mechanics#Cross-Dungeon Unlocks & Recontextualization|Cross-Dungeon Unlocks & Recontextualization]]
	- [[#Dungeon Layout & Environmental Mechanics#Level Scaling Constraints|Level Scaling Constraints]]
- [[#Advanced Dungeon Features & Living Systems|Advanced Dungeon Features & Living Systems]]
	- [[#Advanced Dungeon Features & Living Systems#Dungeon Token Economy|Dungeon Token Economy]]
		- [[#Dungeon Token Economy#Earning Tokens|Earning Tokens]]
		- [[#Dungeon Token Economy#Spending Tokens|Spending Tokens]]
		- [[#Dungeon Token Economy#Integration with Towns & Guilds|Integration with Towns & Guilds]]
	- [[#Advanced Dungeon Features & Living Systems#Optional Challenges & Branching Paths|Optional Challenges & Branching Paths]]
	- [[#Advanced Dungeon Features & Living Systems#Multiplayer-Activated Routes|Multiplayer-Activated Routes]]
	- [[#Advanced Dungeon Features & Living Systems#Dungeon-Bound Key Items|Dungeon-Bound Key Items]]
	- [[#Advanced Dungeon Features & Living Systems#Secret Loops & Thematic Sub-Dungeons|Secret Loops & Thematic Sub-Dungeons]]
	- [[#Advanced Dungeon Features & Living Systems#High-Value Secrets & Legendary Encounters|High-Value Secrets & Legendary Encounters]]
	- [[#Advanced Dungeon Features & Living Systems#Optional Portal Keys & Access Clues|Optional Portal Keys & Access Clues]]
	- [[#Advanced Dungeon Features & Living Systems#Exploration Signposting & Clue Design|Exploration Signposting & Clue Design]]
	- [[#Advanced Dungeon Features & Living Systems#Wild Pokémon Behavior|Wild Pokémon Behavior]]
	- [[#Advanced Dungeon Features & Living Systems#NPC Variety & Interactions|NPC Variety & Interactions]]
	- [[#Advanced Dungeon Features & Living Systems#Roaming Pokémon|Roaming Pokémon]]
	- [[#Advanced Dungeon Features & Living Systems#Early Exits & Incomplete Runs|Early Exits & Incomplete Runs]]
	- [[#Advanced Dungeon Features & Living Systems#Competitive Chest Mechanics & Contested Objectives|Competitive Chest Mechanics & Contested Objectives]]
	- [[#Advanced Dungeon Features & Living Systems#Lore Collectibles & Exploration Achievements|Lore Collectibles & Exploration Achievements]]
		- [[#Lore Collectibles & Exploration Achievements#Lorebooks & Optional Discoveries|Lorebooks & Optional Discoveries]]
		- [[#Lore Collectibles & Exploration Achievements#Exploration-Based Achievements|Exploration-Based Achievements]]
	- [[#Advanced Dungeon Features & Living Systems#Dungeon Persistence & Logout Recovery|Dungeon Persistence & Logout Recovery]]
	- [[#Advanced Dungeon Features & Living Systems#Special Rules for Competitive or Timed Dungeons|Special Rules for Competitive or Timed Dungeons]]
	- [[#Advanced Dungeon Features & Living Systems#Floor Boundaries & Out-of-Bounds Protection|Floor Boundaries & Out-of-Bounds Protection]]
	- [[#Advanced Dungeon Features & Living Systems#Custom Bulletin Boards in Player Towns|Custom Bulletin Boards in Player Towns]]
	- [[#Advanced Dungeon Features & Living Systems#Mini-Floor Templates & Transitional Encounters|Mini-Floor Templates & Transitional Encounters]]
	- [[#Advanced Dungeon Features & Living Systems#Biome Mechanics & Environmental Effects|Biome Mechanics & Environmental Effects]]
	- [[#Advanced Dungeon Features & Living Systems#Dungeon Prestige & Seasonal Progression|Dungeon Prestige & Seasonal Progression]]
		- [[#Dungeon Prestige & Seasonal Progression#Leaderboards, Seasonality & Titles|Leaderboards, Seasonality & Titles]]
		- [[#Dungeon Prestige & Seasonal Progression#Seasonal Titles & Town Contributions|Seasonal Titles & Town Contributions]]
		- [[#Dungeon Prestige & Seasonal Progression#Prestige Shops|Prestige Shops]]
		- [[#Dungeon Prestige & Seasonal Progression#Community Incentives|Community Incentives]]

## Concept Overview

**PokéDungeons** are Pokémon-themed, floor-based dungeons focused on exploration, battling wild Pokémon, and surviving a blackout mechanic that resets progress upon defeat. They are designed to challenge players through increasingly difficult encounters, encourage strategic preparation, and reward teamwork and perseverance.

Each PokéDungeon features a unique biome, theme, or elemental alignment, influencing the type of Pokémon and environmental hazards players will encounter. Dungeons are structured into multiple floors, with each floor offering a variety of challenges such as puzzles and resource scarcity. While the levels of opponents are kept relatively consistent across a dungeon to accommodate randomization, Fixed Floors may be used to introduce spikes in difficulty through boss battles or scripted encounters.

## World Integration & Access

PokéDungeons appear as **portals in the world**, serving as gateways to distinct dimensions. These dungeons are **not instanced**, meaning multiple players entering the same portal will meet and interact within the same dungeon environment. This enables cooperative exploration and shared challenges, but also requires fair mechanics for individual progression.

PokéDungeons **regenerate daily**, including all their resources, making them valuable for regular farming and exploration. Players can enter most dungeons simply by **right-clicking on the portal**, with no special access requirements.

However, access to some PokéDungeons may be **gated behind quest progression**. Entry conditions can include:

- Completing specific story or side quests
    
- Achieving certain milestones in prior dungeons
    
- Possessing unique quest items or flags
    

This allows dungeon access to be tied into broader world progression and narrative systems, offering another layer of challenge and long-term goals for players.

In some cases, however, players may encounter **special PokéDungeon portals** that require a **PokéDungeon Key** to enter:

- **PokéDungeon Keys** are standard Minecraft items (unlike Floor Keys)
    
- They are **consumed** on use
    
- They allow access to dungeons that often contain **rarer Pokémon**, **unique encounters**, or **valuable rewards**
    

These dungeons may take many forms:

- Some are **limited-time event dungeons** with time-gated availability
    
- Others are **permanent expansions**, introduced as live updates to the ongoing world
    

As server staff, these portals can be placed **strategically**, especially in or near **prominent player-run towns** from the Towns & Guilds system. Doing so rewards those towns by:

- Drawing in travelers and adventurers
    
- Creating economic opportunities for hosting services and trading
    
- Encouraging interaction, event hosting, and inter-guild travel
    

Because **fast travel is limited**, players seeking these dungeons often stay in the nearby town for extended periods, strengthening the local player economy and reinforcing the value of town-based infrastructure and discovery.

Rewarding towns in this way is likely to inspire healthy competition among them—towns that improve their visual design, accessibility, services, and social presence may attract more portals over time. The better a town performs and the more it stands out, the more likely it is to be chosen for portal placement. This acts as a natural incentive structure that fuels creativity, town development, and regional prestige.

Additionally, portals may be placed near towns as a **reward for participation in server-wide events**, such as serving as the host for seasonal festivals, tournaments, or collaborative quests. This further reinforces the idea that player involvement and contribution can shape the world in meaningful ways.

## Dungeon Layout & Environmental Mechanics

Dungeon navigation is shaped by limited utility and surprise-focused design. Most teleportation options are disabled within PokéDungeons, but some key exceptions exist:

- **Floor portals**, present on every floor, transport players to the next level when activated using a key or upon meeting certain conditions
    
- **Abra statues**, occasionally found at the start of some floors, allow players to exit the dungeon and send a limited number of items outside
    

### Floor Portals & Objective Clarity

Each floor contains a **portal to the next level**, which typically requires a **floor-specific key**. Keys are obtained through various means:

- Hidden in chests
    
- Dropped by defeating trainers or a number of Pokémon
    
- Guarded by powerful wild Pokémon
    
- Occasionally placed near the portal with the main challenge being locating the portal itself
    

Some floors may subvert expectations:

- Occasionally, the key may be **placed right beside** the portal, even though the HUD shows the objective as “Find the key.”
    
- In other cases, the floor may genuinely have **no key requirement**, with the HUD showing “Find the portal” and no key slot appearing.
    

These occasional twists serve as examples of the dungeon’s unpredictable structure, helping keep exploration engaging and varied without overwhelming the player with surprises.

### Final Floor Exit Portal

The **final floor** of a dungeon always contains a **special exit portal**, visually distinct from standard floor portals. Its design closely resembles the **entrance portal**, clearly indicating to players that this portal will **end the dungeon run** and return them to the overworld.

These portals are placed consistently at **Fixed Floors** and are used as definitive completion markers. Crossing through this portal should send a back-end signal to validate that the dungeon has been completed by the player, which can be integrated with the quest system.

### Quest System

Every player must **acquire their own key**. Keys are consumed by **right-clicking on the floor portal**, which then transports the player to the next level. To prevent issues of item transfer or loss, keys will be implemented as **HUD-based key items** managed programmatically. This ensures that:

- Keys are **non-transferable**
    
- Keys cannot be dropped or lost accidentally
    
- If a player **faints or exits** the dungeon after acquiring a key, the key is removed and must be reacquired
    

This quest system is powered by a **custom mod** that provides:

- A **quest-related inventory** for managing floor keys and special items
    
- Custom **UI elements**
    
- A **HUD overlay** that displays:
    
    - The name of the current PokéDungeon
        
    - The current floor
        
    - The active **floor objective** (e.g., "Defeat 1/5 wild Pokémon")
        
    - Any **tracked overworld or global quest objectives**
        
    - A **key slot icon** that appears only if the current floor requires a key:
        
        - If the key has not been acquired, the slot shows a transparent **key silhouette**
            
        - When the player acquires the key, the slot is filled with a glowing key icon
            
        - If no key is required, the slot does not appear at all
            
- Real-time progress tracking for both dungeon objectives and external quests
    
- A UI menu for players to select and prioritize quest tracking
    

Floor completion objectives can include:

- Defeating a set number of Pokémon
    
- Finding the portal (no key required)
    
- Defeating a number of trainers
    
- Defeating a specific Pokémon
    
- Defeating specific trainer(s)
    
- Finding the key (e.g., hidden or chest-contained)
    

This custom mod may also introduce **special dungeon chests**, which can contain:

- Floor keys
    
- Quest items
    
- Regular dungeon rewards and loot
    
- Dungeon Tokens (explored in a later section)
    

These chests can be implemented in two forms:

- **Instanced chests**, where each player receives individual loot
    
- **Non-instanced chests**, where only the first player to find it after a daily reset receives the reward
    

### Blackout & Failure Conditions

A player will experience a **blackout** if all their Pokémon faint or if they die (e.g., from traps or fall damage). In both cases, their inventory remains intact, but progress is reset.

To add flavor and immersion to this mechanic, a **black screen** can be shown upon blackout, acting as a thematic game-over moment. This screen might include an illustration or visual design element along with a message, such as:

> “You’ve blacked out... but the guardian of the dungeon has found you. You are carried to safety...”

This reinforces the atmosphere and narrative cohesion of the dungeon world while softening the punitive nature of failure with a touch of mystery or lore.

### NPC Quests & Objective Handling

Some PokéDungeon floors may feature **NPC quests** requiring:

- Defeating a specific trainer
    
- Finding and battling/capturing a target Pokémon
    
- Locating a quest item
    

These quests are part of the **general quest system**, meaning they can be started from various sources:

- Directly within a PokéDungeon
    
- In the overworld or other dungeons, with the objective residing inside a specific PokéDungeon
    

### Shared Target and Boss Logic

To maintain fairness while avoiding instancing, PokéDungeon encounters—including bosses and quest-specific targets—use a **shared-world conditional spawn and interaction system**.

- When a player who meets the encounter or quest condition enters a relevant area, the target (boss, NPC, or special Pokémon) is **spawned**.
    
- These targets are **not exclusive** to the player who triggered the spawn but can only be meaningfully interacted with by **eligible players**.
    
- Combat or interaction is validated against the player's **active objective state**, preventing unqualified players from hijacking progression.
    
- Targets despawn after being defeated, and a **brief cooldown phase** begins.
    
- Once the cooldown ends, the system checks if any other qualified players are still nearby and **spawns the target again** for the next eligible player.
    
- Additionally, the system should **periodically check** whether any eligible players are still present in the area. If no qualifying players remain—for example, if a player enters and then leaves without completing the objective—the spawned target should **despawn** to prevent lingering, unused encounters.
    

This system ensures that:

- Progression is **not blocked** by AFK or slow players
    
- Encounters are **not duplicated or hoarded**
    
- Players interact with content based on **eligibility and sequence**, not spawn ownership
    

To prevent confusion or abuse:

- A visible indicator (e.g., glyph, or particle effect) appears when the encounter is **currently active**, signaling that others must wait
    
- Players who **already completed the objective** will not trigger additional spawns or be eligible to interact
    

### Conditional Behavior

This system also includes a **conditional interaction framework**:

- Checks player progress, flags, or state to dynamically adjust encounter behavior or access
    
- Modifies NPC dialogue and quest logic to reflect the player's current status
    
- Prevents re-triggers of objectives already completed
    

This unified system supports both **boss battles** and **quest-related encounters**, allowing them to coexist fairly in a non-instanced, persistent environment.

### Floor Layouts & Randomization

To make dungeons feel **replayable**, PokéDungeons use a **pseudo-randomized floor layout system**:

- Every dungeon has a **larger pool of designed floors** than it uses in any single run.
    
- On each daily reset, the dungeon selects a subset of these floors and shuffles their order to create a fresh path.
    
- This gives every dungeon reset a slightly different layout while preserving design intent.
    

### Fixed Floors

While most floors are randomized, **Fixed Floors** are pre-defined and always appear at the same position in the dungeon's sequence. They serve as stable landmarks and design anchors within the experience:

- Ideal for placing important encounters, quest objectives, narrative events, or lore triggers
    
- Can guarantee the appearance of healing stations or teleport statues at key milestones
    
- Useful for progression pacing or tutorializing mechanics
    
- As a rule, the **first floor** of both main dungeons and annex sub-dungeons should always be a **Fixed Floor** to ensure stable entry, consistent environment setup, and safe spawn handling .
    

### Floor Variants

**Floor Variants** are alternate versions of specific PokéDungeon floors that can be dynamically swapped in or out based on world events, quests, or developer triggers. They enable the dungeon system to respond to player achievements, seasonal changes, or server-wide milestones.

#### Purpose

The Floor Variant system allows dungeons to feel alive and mutable, offering new content, visual changes, or functional shifts without requiring an entirely new dungeon instance. This can:

- Reflect world-state changes from completed NPC Quests (e.g., sealed paths after legendary encounters)
    
- Support seasonal or event-based alterations (e.g., spooky Halloween floor variant)
    
- Provide challenge scaling or timed access (e.g., tougher layout active only during full moons or after server milestones)
    

#### Use Cases

- **Legendary Encounter Lockout**: After a server-wide quest where a player captures a mythical Pokémon hidden in a secret path, the original floor is swapped for a crumbled variant that seals the path for a number of days or weeks.
    
- **Story Branching Response**: A floor may present different layouts depending on how a player's previous quests flagged certain world or narrative events.
    
- **Community Events**: A floor temporarily becomes themed (e.g., elemental storm or festival decor) as a response to player contributions or server initiatives.
    

#### Implementation Notes

- Every dungeon floor, whether fixed or randomized, should have a unique identifier (**UID**) to allow precise targeting.
    
- Floor Variants are pre-authored and mapped to these base floor UIDs as alternate versions.
    
- Swaps can be time-based, event-driven, or permanently triggered.
    
- Multiple variants may exist for a single floor, creating layers of change potential.
    
- Variant activation may be global or player-specific, depending on context and technical feasibility.
    
- Swaps can be time-based, event-driven, or permanently triggered.
    
- Multiple variants may exist for a single floor, creating layers of change potential.
    
- Variant activation may be global or player-specific, depending on context and technical feasibility.
    

This system reinforces the core PokéDungeons goal of persistent, non-instanced evolution, while granting developers powerful tools for environmental storytelling and adaptive design.
### Displayed vs. Internal Floor Numbers

There is a distinction between a floor’s **internal ID** and the **number shown to the player**:

- Internally, floors are always tracked sequentially by the system.
    
- Visually, floor numbers may reflect thematic direction (e.g., descending into a cave: Floor -1 to -20; climbing a mountain: Floor 1 to 20).
    
- This provides narrative immersion without affecting mechanical logic.
    

### Annex Sub-Dungeons

Some floors may act as **gateways to annexed sub-dungeons**:

- Upon reaching a specific floor (e.g., Floor 20), the player transitions to a separate dungeon entirely.
    
- This new dungeon has its own set of randomized or fixed floors and can scale differently.
    
- It allows for dramatic environmental shifts, theme changes, difficulty escalations, and even storytelling opportunities.
    

### Cross-Dungeon Unlocks & Recontextualization

In some cases, annex sub-dungeons may not be unique to the parent dungeon—they may instead be **pre-existing full dungeons** temporarily treated as annexes. This allows for **cross-dungeon storytelling and progression mechanics**.

For example:

- A player may find a mysterious sealed gate in **Sunlight Forest Floor 4**, a low-level dungeon. Despite multiple runs, the method to unlock it remains unknown.
    
- Much later, while exploring **Dark Cave**—a higher-level dungeon—the player acquires a **dark gem** with no apparent use.
    
- Following obscure clues and completing puzzles, the player finds a hidden portal leading back into **Sunlight Forest Floor 1**, but this time as part of an annexed sub-dungeon.
    
- Because they now carry the dark gem, the sealed gate in Sunlight Forest Floor 4 can be opened—leading to a **new high-level challenge** hidden inside a familiar low-level zone.
    

This mechanic turns the dungeon world into a **web of interlinked mysteries**, where progress in one dungeon may unlock content in another, and revisiting earlier areas with new tools or knowledge leads to discovery and reward.

### Level Scaling Constraints

To avoid inconsistencies when floors are shuffled:

- **Pokémon levels must remain consistent** across all floors within a given dungeon.
    
- This prevents progression issues due to reordered challenge tiers.
    
- Annex Sub-Dungeons, being treated as separate entities, can safely scale difficulty upward.
    

This floor system creates a balance of **freshness and familiarity**, supporting repeat runs, flexible design, and meaningful pacing.

## Advanced Dungeon Features & Living Systems

### Dungeon Token Economy

Dungeon Tokens are a special currency earned through high-engagement dungeon activities. They serve as a versatile reward system designed to be valuable without encouraging grind-based behavior.

#### Earning Tokens

Tokens may be awarded through:

- **Daily-reset chests**, especially rare or hidden ones
    
- **Boss completions**, particularly on first completion of the day
    
- **Optional or secret objectives** during runs
    
- **Event or bounty-based quests** specific to dungeons
    

These sources are naturally limited by the dungeon reset system, preventing repetitive farming while still offering tokens frequently enough to feel meaningful.

#### Spending Tokens

Tokens can be used at special NPC vendors, often located in towns or within dungeons. These vendors may offer:

- **Exclusive PokéBalls** (some purely cosmetic, others mechanically useful)
    
- **Dungeon-themed decorative furniture** (via custom mods)
    
- **Temporary buffs** or single-use dungeon items
    
- **Dungeon-themed cosmetic overlays or visual effects** for gear
    

This separation of power-based and vanity rewards allows all types of players to engage with the system meaningfully.

#### Integration with Towns & Guilds

Towns that host dungeon token vendors benefit from increased traffic and prestige. This ties the token economy directly into the server's wider systems and encourages player collaboration in maintaining and upgrading their local economy.

### Optional Challenges & Branching Paths

Beyond core combat and traversal, certain dungeon floors will feature **secondary challenges** that introduce layers of complexity and replay value:

- Some floors include **puzzles**, **platforming sequences**, or **non-combat objectives** that offer alternate ways to progress or earn rewards.
    
- Other floors may include **branching paths**, some of which are only accessible under specific conditions—like bringing a friend, solving a puzzle, or unlocking a secret gate.
    
- These optional routes can sometimes lead to **secret annex sub-dungeons**, further enhancing the roguelike depth of exploration.
    
- Sub-dungeons may be obvious, hidden, or cleverly disguised as part of the critical path.
    

### Multiplayer-Activated Routes

- Some floors contain mechanisms that require **multiple players** to operate (e.g., weight plates, timed switches, multi-person pressure puzzles).
    
- These challenges encourage cooperative play and reward group effort with rare spawns, loot, or shortcuts.
    
- In some cases, these multiplayer gates may be the only way to access certain powerful encounters or hidden paths.
    

### Dungeon-Bound Key Items

- Occasionally, players may find **special key items** during dungeon runs.
    
- These items are **bound to the dungeon session**—they disappear upon leaving the dungeon, though they may carry through into annex sub-dungeons.
    
- These items can be used to solve puzzles, open locked gates, or activate hidden mechanisms later in the same run.
    
- Unlike floor keys, these are not shown in the key slot, but may be displayed as a **separate HUD overlay** grouped as “dungeon tools.”
    

### Secret Loops & Thematic Sub-Dungeons

- Some paths may loop back to earlier parts of the main dungeon, creating **nonlinear progression**. For example:
    
    - A player exits from Mountain Floor 20 into a cave-like annex
        
    - After reaching Cavern Floor -4, they re-enter the Mountain Dungeon at Floor 5
        
- These loops create a sense of unpredictability and tension—players never know exactly where a portal may lead.
    
- Other branches may lead to entirely different dungeon sets with new themes (e.g., from mountain to rising waterfalls) and then return to the original dungeon at a higher floor.
    

### High-Value Secrets & Legendary Encounters

- The rarest sub-dungeons or secret branches may contain **legendary or mythical Pokémon**, **guaranteed shiny encounters**, or **exceptionally rare loot**.
    
- These encounters reward players who explore thoroughly, collaborate, or decipher long-hidden secrets—strengthening the feeling that **each run could reveal something entirely new**.
    

### Optional Portal Keys & Access Clues

- Some **optional branching portals** may require their own unique keys, while others may use the same floor key as the main progression.
    
- Optional keys will appear in the **Dungeon Tool HUD** rather than the primary key slot, maintaining UI simplicity and avoiding spoilers about their presence.
    
- If a player attempts to use an optional portal without the necessary key or having triggered a required mechanism, the game will display a contextual message:
    
    - Literal (e.g., “You don’t have the key for this portal”) or
        
    - Thematic (e.g., “The gears of time are not turning”, “The runes remain dormant”).
        
- This preserves the mystery around portal requirements and makes each interaction feel like a potential discovery.
    
- In many cases, the requirement may not be a key but instead a **mechanism that must be activated** elsewhere on the floor or earlier in the dungeon.
    

Whether through found items or conditional triggers, these alternate routes enhance the dungeon's roguelike unpredictability and deepen the sense of discovery. This layered progression and optionality fosters an experience where every run becomes an opportunity for surprise, mastery, and community-driven exploration.

### Exploration Signposting & Clue Design

As dungeon branching, looping, and annex transitions become more complex, subtle **exploration signposting** is essential to maintain clarity and immersion without diminishing mystery.

Clues can take many forms:

- **Visual Cues:** Unique block textures, colored lighting, or faint particle effects to highlight nearby secrets or interactive elements
    
- **NPC Dialogue Hints:** Rumors and in-world tips like “I heard a lever was hidden behind the waterfall...”
    
- **Ambient Audio:** Subtle sounds such as echoes, humming, or trickling water that change near hidden chambers or events
    
- **Environmental Composition:** Inaccessible doors or conspicuous layouts that subconsciously nudge the player to question what they’re seeing
    

These hints should never hand-hold but instead create “aha!” moments when secrets are uncovered. This approach increases satisfaction and encourages deeper attention to the dungeon’s layout, environment, and lore.

### Wild Pokémon Behavior

- Many wild Pokémon within PokéDungeons will **aggressively pursue and engage** the player in battle upon detection.
    
- This is essential to maintain pressure on the player’s team and resources.
    
- Depending on implementation flexibility, some Pokémon may behave differently:
    
    - **Neutral:** Do not engage unless provoked
        
    - **Skittish:** Attempt to flee when approached
        
- These behavioral differences could reflect species traits or floor themes.
    

### NPC Variety & Interactions

Dungeon NPCs serve many roles beyond traditional trainers:

- **Trainer NPCs:**
    
    - Some will initiate combat on sight
        
    - Others require the player to speak with them to trigger a battle
        
- **Supportive/Interactive NPCs:**
    
    - May offer quests, dialogue hints, or lore
        
    - May gift items once per player or per reset
        
    - Could ask for dungeon-bound key items and provide rewards or open hidden paths in return
        
- **Traders and Tricksters:**
    
    - Certain rare NPCs act as shopkeepers, offering trades for:
        
        - **Regular Pokédollars**
            
        - A planned **Dungeon Token** currency
            
        - Special dungeon items
            
    - These shopkeepers may appear randomly and could sell valuable or exclusive items
        
    - Some deceptive NPCs might offer bad deals—like purchasing a valuable key item only for the player to later realize it was critical to accessing a rare encounter
        

### Roaming Pokémon

- Occasionally, rare Pokémon may spawn on a **random floor** within a dungeon as part of a **roaming mechanic**.
    
- These rare encounters are meant to drive repeat runs and speculation.
    
- Roamers may include shiny-locked species, rare forms, or themed event Pokémon tied to the dungeon's identity.
    

Together, these systems bring the dungeon world to life—filling it with emergent stories, active threats, and opportunities for players to build memories through both success and regret.

### Early Exits & Incomplete Runs

Not all dungeon paths lead to deep progression—some may **end** after only a few floors, returning the player to the entrance instead of advancing further. This applies to both main dungeons and annex sub-dungeons.

For example:

- A player attempting to reach Mountain Dungeon Floor 20 might instead take a path at Floor 15 that leads into Cavern B, which **ends at Floor -10**, ejecting the player.
    
- This results in an incomplete run, and the player will need to retry another day or follow a different path to meet their objective.
    

These endings are **intentional** and provide:

- A way to increase tension and risk in path decisions
    
- Controlled gating of content or quest progress
    
- A means of rewarding repeat runs and map mastery
    

Portals leading to annex sub-dungeons can be placed at **Fixed Floors** to ensure predictable placement, but signaling does not require the floor to be fixed:

- Some paths may be clearly marked or foreshadowed with environmental clues
    
- Others might remain obscure or mysterious, keeping players guessing
    

Rare looping paths may even guide players **backward** through the dungeon unexpectedly—or act as shortcuts in disguise.

This system emphasizes the theme that **you haven’t seen everything yet**, and every branch can offer surprises, setbacks, or breakthroughs that enrich the sense of exploration.

### Competitive Chest Mechanics & Contested Objectives

Beyond standard loot and quest rewards, PokéDungeons may occasionally feature **competitive mechanics** tied to specific dungeon chests or item-based objectives:

- While most dungeon-bound key items and loot are **instanced per player**, select **non-instanced chests** may be introduced as rare, limited-access features.
    
- These chests offer special rewards to the **first player who reaches them after a reset**, creating a sense of race and urgency.
    
- To avoid abuse, these non-instanced chests should be used sparingly and reset infrequently.
    

In special competitive or timed dungeon formats:

- Some chests may contain **progress-critical items**, such as a rare key, puzzle trigger, or unique treasure.
    
- These items can unlock **exclusive paths, puzzles, or boss encounters** only accessible to the player who claimed the item first.
    
- If the claiming player **successfully completes** the associated objective, the dungeon may reset as part of a new competitive round.
    
- If the claiming player **fails** (e.g., blacks out or leaves the dungeon) and the item was **singular or essential**, the following may occur:
    
    - All other players are ejected
        
    - The dungeon **resets and reshuffles** the item’s location
        
    - The challenge is reopened for a new attempt
        

This behavior depends on the nature of the event or run. For example:

- **Per-run events** may reset the dungeon immediately after each completion or failure
    
- **Hourly or time-gated events** may allow the dungeon to remain open and reset on a global timer
    

Not all progression items must be strictly singular:

- In some cases, multiple keys or components may exist in a run
    
- The system can track whether **all instances have been claimed** and whether **any holders remain** in the dungeon before resetting
    

Competitive objectives may take many forms:

- Rare loot hidden behind limited chests
    
- Keys required to access powerful Pokémon
    
- Event-limited items needed to complete puzzles or bypass obstacles
    

Additionally, **PvP may be disabled** in these dungeons, but players could be allowed to **challenge each other to normalized Pokémon battles**, adding an extra layer of free-for-all interaction without griefing.

### Lore Collectibles & Exploration Achievements

> **Note:** This system is conceptual and would likely require additional custom modding. It is included here as a design suggestion rather than a fully committed feature.

To encourage long-term engagement and reward in-depth exploration, PokéDungeons may feature collectible lore elements and trackable achievement systems.

#### Lorebooks & Optional Discoveries

- Some hidden or optional areas may contain **lorebooks**—collectible items or entries tied to the story of the dungeon, its region, or its Pokémon inhabitants.
    
- These could be found in instanced chests, behind puzzles, or by interacting with specific environmental triggers.
    
- When discovered, lorebooks could be stored in a personal **Lore Compendium** UI panel, giving players a record of their discoveries.
    

#### Exploration-Based Achievements

Players may receive progress or achievements for actions such as:

- Fully completing a dungeon (reaching the final floor and exiting)
    
- Finding all lore entries in a dungeon
    
- Completing a dungeon without blacking out
    
- Completing a dungeon solo or without using healing stations
    

These achievements could unlock:

- **Titles** (e.g., “Cavern Archivist”, “Sunlight Explorer”)
    
- **Cosmetic gear overlays**
    
- **Small token rewards**
    
- **Quest unlocks** or hidden content for lore completionists
    

This system supports completionists, encourages repeat exploration, and reinforces the idea that PokéDungeons are not just combat spaces—but living, mysterious environments worth investigating fully.

### Dungeon Persistence & Logout Recovery

Players who log out while inside a PokéDungeon may face special handling depending on whether the dungeon has reset during their absence.

- If the player had previously reached a checkpoint floor, they resume from that point upon logging back in—regardless of floor reshuffling. If the dungeon is no longer accessible, they are safely **ejected from the dungeon** with appropriate messaging.
    
- Checkpoints are defined as **Fixed Floors containing Abra statues**, and act as stable respawn points. The first floor of every dungeon and sub-dungeon is always a checkpoint floor.
    

> “The dungeon’s shape has shifted while you were away. You are guided out by a faint familiar force.”

This system ensures players are never trapped inside invalid terrain while preserving their sense of progression when possible.

### Special Rules for Competitive or Timed Dungeons

Certain dungeons—especially **event-based or competitive formats**—may disable checkpoint persistence to prevent exploitation:

- These dungeons **may not contain checkpoints** at all
    
- Alternatively, if technical flexibility allows, **checkpoint recovery can be selectively disabled** for specific dungeons
    
- Upon entering such dungeons, players will see a clear warning:
    

> “Note: This dungeon must be completed in a single session. Logging out will forfeit your current progress.”

This helps maintain competitive fairness and encourages full attention during high-stakes runs, without confusing players or undermining expectations in standard dungeon content.

### Floor Boundaries & Out-of-Bounds Protection

Each dungeon floor is encased in **invisible barrier blocks** (or **bedrock layers** for cave-style floors) to preserve intended movement and exploration. This containment allows players to mine and interact with the environment without leaving the playable space.

To ensure game integrity and prevent players from exploiting or bypassing floor progression:

- Every floor must have a **robust level boundary** defined
    
- If a player breaches these boundaries (e.g., reaching a separate floor, accessing unintended geometry, or skipping content), an **automatic blackout** will be triggered
    
- This blackout forcibly ends the run, returning the player to safety while preserving fairness
    

A **message can be displayed** to inform the player of what happened:

> “You’ve strayed too far from the dungeon path... A mysterious force pulls you into darkness.”

This system protects against unintended progression and helps maintain challenge, immersion, and balance throughout dungeon exploration.

### Custom Bulletin Boards in Player Towns

Towns with nearby PokéDungeons or dungeon vendors can feature **custom modded bulletin boards**, placed by server staff in collaboration with the town’s leadership. These bulletin boards act as public hubs of information and may include:

- A list of **nearby PokéDungeons** and their themes or entry details
    
- **Dungeon event notices** such as loot rotations or time-limited content
    
- **Special dungeon leaderboards**, focused on players from that town or region
    

This integration reinforces town identity, encourages exploration from nearby towns, and creates a strong sense of server-wide presence and prestige.

### Mini-Floor Templates & Transitional Encounters

To enhance pacing and provide design variety, PokéDungeons may occasionally insert **micro-scale floors** or **mini encounters** that span only a few rooms or screens. These can include:

- **Single-solution puzzle floors** (e.g., push-block challenges or light manipulation)
    
- **Short story vignettes** or atmospheric encounters
    
- **Gauntlet corridors** of back-to-back battles or hazards
    

These lightweight floors serve as breathing room or tension ramps, letting designers fine-tune flow and pacing.

### Biome Mechanics & Environmental Effects

Each dungeon biome can introduce **environmental mechanics** that thematically and mechanically distinguish floors. If feasible via datapack or mod implementation, effects might include:

- **Ice floors:** Slippery movement or hailing during combat
    
- **Fire zones:** Gradual burn damage unless a resistance item is held, sunny-day during combat
    
- **Psychic-themed areas:** Periodic camera distortion, illusion floors, or temporary disorientation effects
    

These biome traits encourage players to adapt their strategies and gear, adding another layer of planning, mastery, and immersion to dungeon exploration.

As developers, these effects also create opportunities to introduce **dungeon-specific gear** tailored to mitigating or interacting with these hazards—further reinforcing the identity and mechanical depth of each biome.

### Dungeon Prestige & Seasonal Progression

To support long-term engagement and competitive progression, a **Dungeon Prestige** system may be implemented:

- Players earn **Dungeon Prestige** by opening dungeon chests, completing dungeons, solving secret puzzles, and participating in certain repeatable activities.
    
- Prestige is a score system that accumulates **over time** and is designed to stretch across long-term server play, ensuring gradual, satisfying growth.
    

#### Leaderboards, Seasonality & Titles

- Dungeon Prestige contributes to **seasonal leaderboards**, visible both globally and per town.
    
- At the end of each season, server staff may reward **top-ranking players** with special rewards.
    
- Prestige may **reset between seasons**, giving newcomers a chance to compete.
    

#### Seasonal Titles & Town Contributions

There are two types of leaderboards where **titles** can be awarded as part of the seasonal rewards:

1. **Dungeon Prestige Leaderboard** (Server-wide):
    
    - These leaderboards track overall Dungeon Prestige across all dungeons.
        
    - The server may poll or select from a pool of **title suggestions** (some proposed by players) for each season.
        
    - The **top three ranking players** are awarded unique seasonal titles based on the highest-voted options.
        
2. **Town Dungeon Leaderboard** (Town-local):
    
    - These leaderboards track **Dungeon Prestige earned specifically within PokéDungeons near a given town**.
        
    - Town leadership is encouraged to propose **custom title rewards** for their local leaderboard.
        
    - Towns may provide **optional rewards** for their top three ranking players, and the server will also contribute with **additional seasonal prizes**.
        

These titles are added on a **per-season basis**, but once earned, they are **kept permanently** by the players as a lasting mark of distinction. This helps reinforce both player accomplishment and town-based identity in the long term.

- Player towns with nearby dungeons are encouraged to **suggest title ideas** to server staff at the start of each season.
    
- Approved titles may be granted to the top players of that dungeon, reinforcing both **individual prestige** and **town-based identity**.
    

#### Prestige Shops

- Prestige can also unlock access to **Prestige Shops**, which deal primarily in **Dungeon Tokens**.
    
- These shops offer **exclusive items** that cannot be acquired through other means.
    
- Once a player reaches a certain Prestige threshold, they unlock access to all shop tiers; further leveling becomes purely **cosmetic and competitive**.
    

#### Community Incentives

- Player towns are encouraged to contribute to seasonal rewards, creating a shared interest in **supporting dungeon runners**.
    
- This can also incentivize players to prioritize dungeons located **near or within active towns**, boosting traffic and local economy.
    

This system offers players both individual recognition and a shared competitive goal—balancing long-term mastery with seasonal freshness.
