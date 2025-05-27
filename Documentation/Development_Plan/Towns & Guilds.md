---
sticker: emoji//1f3f0
---
**Towns & Guilds** is the part of the project focused on fostering player communities and driving the in-game economy. It introduces a guild-based skill system, where players join specific guilds—similar to RPG job classes—to access unique skill trees and role-specific abilities. Each guild supports a distinct gameplay style or profession, encouraging cooperation and specialization within the player community.

#### **Section Index**

- [[#Concept Overview|Concept Overview]]
- [[#Town-Guild Relationship|Town-Guild Relationship]]
- [[#Guild-Player Interaction & the GP System|Guild-Player Interaction & the GP System]]
	- [[#Guild-Player Interaction & the GP System#Skill Tree Design|Skill Tree Design]]
	- [[#Guild-Player Interaction & the GP System#Guild Points (GP)|Guild Points (GP)]]
- [[#Guild Roles & Hierarchy|Guild Roles & Hierarchy]]
- [[#Acting GM Mechanics|Acting GM Mechanics]]
	- [[#Acting GM Mechanics#Purpose|Purpose]]
	- [[#Acting GM Mechanics#Assignment and Revocation|Assignment and Revocation]]
	- [[#Acting GM Mechanics#Automatic Activation|Automatic Activation]]
	- [[#Acting GM Mechanics#Permissions|Permissions]]
	- [[#Acting GM Mechanics#Transparency and Oversight|Transparency and Oversight]]
	- [[#Acting GM Mechanics#Role Expiry|Role Expiry]]
- [[#Guild Rank (GR)|Guild Rank (GR)]]
- [[#Guild Quests (GQ), Guild Skill Quests (GSQ), and Tree Progression|Guild Quests (GQ), Guild Skill Quests (GSQ), and Tree Progression]]
	- [[#Guild Quests (GQ), Guild Skill Quests (GSQ), and Tree Progression#Guild Skill Quests (GSQs)|Guild Skill Quests (GSQs)]]
		- [[#Guild Skill Quests (GSQs)#1. Skill Unlock GSQs|1. Skill Unlock GSQs]]
		- [[#Guild Skill Quests (GSQs)#2. Tool Redeemable GSQs|2. Tool Redeemable GSQs]]
			- [[#2. Tool Redeemable GSQs#Tool GSQ Characteristics:|Tool GSQ Characteristics:]]
		- [[#Guild Skill Quests (GSQs)#Guild Tool Mechanics|Guild Tool Mechanics]]
			- [[#Guild Tool Mechanics#A. Guild-Exclusive Items|A. Guild-Exclusive Items]]
			- [[#Guild Tool Mechanics#B. Guild-Bound Items|B. Guild-Bound Items]]
			- [[#Guild Tool Mechanics#C. Placement & Management Authority|C. Placement & Management Authority]]
			- [[#Guild Tool Mechanics#D. Active Tracking for GMs|D. Active Tracking for GMs]]
		- [[#Guild Skill Quests (GSQs)#GSQ Submission Delegation|GSQ Submission Delegation]]
		- [[#Guild Skill Quests (GSQs)#Tool GSQ Access Structure|Tool GSQ Access Structure]]
		- [[#Guild Skill Quests (GSQs)#Example Tool GSQ Chain: Courier Infrastructure|Example Tool GSQ Chain: Courier Infrastructure]]
		- [[#Guild Skill Quests (GSQs)#Quality of Life Features|Quality of Life Features]]
	- [[#Guild Quests (GQ), Guild Skill Quests (GSQ), and Tree Progression#Tree Experience (TXP) and Tree Level (TL)|Tree Experience (TXP) and Tree Level (TL)]]
	- [[#Guild Quests (GQ), Guild Skill Quests (GSQ), and Tree Progression#TSP and GP Influence|TSP and GP Influence]]
	- [[#Guild Quests (GQ), Guild Skill Quests (GSQ), and Tree Progression#Guild Tokens (GT)|Guild Tokens (GT)]]
	- [[#Guild Quests (GQ), Guild Skill Quests (GSQ), and Tree Progression#Example GSQ: Unlock “Mining Dimension Portal” Skill|Example GSQ: Unlock “Mining Dimension Portal” Skill]]
		- [[#Example GSQ: Unlock “Mining Dimension Portal” Skill#Design Note: Emergent Use of Guild Tokens|Design Note: Emergent Use of Guild Tokens]]
- [[#Contracts & Trade Agreements|Contracts & Trade Agreements]]
	- [[#Contracts & Trade Agreements#Guild Contract|Guild Contract]]
	- [[#Contracts & Trade Agreements#Trade and Task Contracts|Trade and Task Contracts]]
	- [[#Contracts & Trade Agreements#Technical Function|Technical Function]]
- [[#Addressing Potential Concerns|Addressing Potential Concerns]]
	- [[#Addressing Potential Concerns#New Player Onboarding & the Initiate Role|New Player Onboarding & the Initiate Role]]
	- [[#Addressing Potential Concerns#GM Inactivity & Power Bottlenecks|GM Inactivity & Power Bottlenecks]]
		- [[#GM Inactivity & Power Bottlenecks#Chain of Succession|Chain of Succession]]
		- [[#GM Inactivity & Power Bottlenecks#Orphaned Guilds|Orphaned Guilds]]
		- [[#GM Inactivity & Power Bottlenecks#Bad-Faith Loopholes|Bad-Faith Loopholes]]
		- [[#GM Inactivity & Power Bottlenecks#Staff Intervention|Staff Intervention]]
	- [[#Addressing Potential Concerns#Solo and Small Guild Viability|Solo and Small Guild Viability]]
		- [[#Solo and Small Guild Viability#GP-Based Modifier (Base Discount)|GP-Based Modifier (Base Discount)]]
		- [[#Solo and Small Guild Viability#GR-Based Modifier (Multiplier on Base Discount)|GR-Based Modifier (Multiplier on Base Discount)]]
	- [[#Addressing Potential Concerns#Large Guild Behavior and Scaling Implications|Large Guild Behavior and Scaling Implications]]
	- [[#Addressing Potential Concerns#Foundational Guild Growth & Leadership Legacy|Foundational Guild Growth & Leadership Legacy]]
	- [[#Addressing Potential Concerns#Tree Access in Multi-Guild Membership|Tree Access in Multi-Guild Membership]]
		- [[#Tree Access in Multi-Guild Membership#Rule Summary|Rule Summary]]
		- [[#Tree Access in Multi-Guild Membership#Example: How It Works|Example: How It Works]]
	- [[#Addressing Potential Concerns#Addressing Contract Abuse & Transparency|Addressing Contract Abuse & Transparency]]
		- [[#Addressing Contract Abuse & Transparency#Why the System Holds|Why the System Holds]]
	- [[#Addressing Potential Concerns#Addressing Alt Account Concerns|Addressing Alt Account Concerns]]
	- [[#Addressing Potential Concerns#Cross-Guild Interaction and Land Agreements|Cross-Guild Interaction and Land Agreements]]
- [[#Glossary|Glossary]]

## Concept Overview

While the system is designed to encourage collaboration and group specialization, **nothing prevents a solo player** from founding a guild and acting as its sole member and Guild Master. This solo GM can undertake Guild Quests (GQs) and Guild Skill Quests (GSQs) alone, earn Guild Tokens, and even obtain Guild Gems through meaningful server participation.

That said, this path is **deliberately challenging**, as the effort and resource demands of progressing a guild are balanced around group-scale activity. Completing high-tier quests and unlocking powerful abilities solo is possible—but intentionally challenging.

With that in mind, guild progression systems are designed to scale based on member commitment and activity, with special consideration given to solo players and small guilds through built-in token scaling.

The core goal of this system is to encourage players to **form towns** and **establish guilds** as persistent, meaningful structures within the server's world.

- **Towns** act as the foundation for player governance and community building. Each town is expected to function as a semi-autonomous entity, complete with leadership, infrastructure, and a sustainable economy.  
    
- **Guilds** are professional organizations that specialize in a particular trade, such as farming, blacksmithing, enchanting, exploration, or construction. They provide structure, role identity, and skill progression for players who join them.  
    

## Town-Guild Relationship

- A guild must have a **physical presence (guild building)** in at least one town to be officially recognized.  
    
- While a guild may originate in a specific town, it is **not limited to that town** and can **freely expand to others**.  
    
- **Towns do not have jurisdiction** over a guild's expansion decisions. A founding town may serve as the symbolic origin or cultural hub of a guild, but it **holds no formal control** over where the guild operates next.  
    
- The one exception is when a **host town financially or materially contributes** to the deployment of a new guild branch. In such cases, **terms can be negotiated** between all parties involved.  
    
- This system encourages **player-driven diplomacy**, where inter-town and guild relations are shaped by mutual benefit rather than strict hierarchy.  
    

## Guild-Player Interaction & the GP System

Each guild offers players access to two unique **skill trees**, which reflect the guild's thematic identity and core functions. These trees define the perks, abilities, and enhancements that guild members can unlock over time.

### Skill Tree Design

A guild’s skill trees are chosen at the time of its founding and are tied closely to its focus. For example:

- The **Risky Miners Guild** may offer:
    - A **Mining Tree** with skills related to efficiency, rare ore detection, and safety bypass tools.  
        
    - An **Adventuring Tree** that enhances mobility, hazard resistance, or underground combat bonuses.  
        
- The **Tech Builders Guild** might include:
    - A **Tech Tree** for automation, redstone logic, or power systems.  
        
    - A **Builder Tree** for improved construction tools, blueprint systems, or block manipulation perks.  
        

This dual-tree structure facilitates each guild maintaining a **unique identity** while allowing flexibility for members to engage with multiple playstyles.

### Guild Points (GP)

**Guild Points (GP)** represent a player's availability and willingness to commit to guild activities. This soft cap system regulates how many guilds a player can meaningfully participate in.

- Players begin with **5 GP**, which can increase up to **9 GP** as they progress.  
    
- Joining a guild requires spending **1 to 3 GP**, set in the initial contract.  
    
- GP spent determines the _maximum_ amount of **Tree Skill Points (TSP)** the player can actively use, which limits how many skills they can select within the unlocked skill tree. All members can see the full unlocked tree, but TSP determines how much of it they can actively utilize:  
    

|GP Spent|SP Allocation Rate|
|---|---|
|1 GP|50% of total TSP|
|2 GP|75% of total TSP|
|3 GP|100% of total TSP|

This encourages meaningful specialization while still allowing players to join multiple guilds.

## Guild Roles & Hierarchy

Guilds have a structured hierarchy with defined responsibilities and GP requirements. Each role corresponds to a Guild Token rank and determines access to specific Guild Quests (GQs).

- **Guild Master (GM)** – 3 GP required. Can create and manage the guild, promote and demote any role, sign off Guild Skill Quests (GSQ), and manage high-level contracts. Token: **Guild Token S**. Only one GM per guild.  
    
- **Guild Captain (GC)** – 3 GP required. Can invite and demote members, promote Specialists and Officers, manage contracts, and eject inactive or disruptive members. Token: **Guild Token A** (occasionally **S**). Max of 4 per guild.  
    
- **Guild Officer** – 3 GP required. Mid-level leader with organizational responsibility. While Officers cannot issue Guild Contracts by default, specific Officers may be granted permission by a GC or GM to issue contracts for the Rookie role only. Token: **Guild Token B** (occasionally **A**).  
    
- **Guild Specialist** – 2 GP required. Trusted contributor with access to higher-tier GQs and guild projects. Token: **Guild Token C** (occasionally **B**).  
    
- **Guild Rookie** – 1 GP required. Entry-level member, limited privileges, mostly introductory tasks and GQs. Token: **Guild Token D** (occasionally **C**).  
    
- **Initiate** – 0 GP required. Temporary onboarding role with access to tutorial-level GQs and minimal TSP (33%). Token: **Guild Token D** only.  
    

Contracts define the terms of a player’s commitment. While there may be organic negotiation between the applicant and the Captain during the onboarding process, the final decision on how much GP is allocated is solely up to the Captain. The applicant cannot choose their own GP investment—this prevents players from claiming high contribution without following through.

The only unilateral action a member can take is to leave the guild altogether.

Captains can demote 2 GP members to 1 GP, just as they can demote Specialists to Rookies. Similarly, GMs have full authority to demote Captains or Officers to any lower role.

GP and guild roles are separate: a player may be assigned 3 GP but still hold the rank of Rookie. Conversely, GMs and GCs can eject any lower role at any time in response to inactivity, disruption, or lack of contribution.

## Acting GM Mechanics

The **Acting GM** is a role that exists to ensure the continuity of guild leadership responsibilities when the Guild Master (GM) is unavailable or chooses to delegate specific authority. This role is scoped deliberately and does not assume full control of the guild, but rather temporary authority over limited guild systems.

### Purpose

The Acting GM is primarily empowered to:

- Submit and finalize **Guild Skill Quests (GSQs)** on behalf of the guild  
    
- Act as a temporary executor for specific guild actions as authorized by the GM  
    

This ensures that progression, particularly in GSQs, is not halted due to GM unavailability.

### Assignment and Revocation

- Only the GM may assign the Acting GM.  
    
- Only one Captain may be assigned as Acting GM at a time.  
    
- The GM may change the Acting GM designation at any time, with no cooldown.  
    
- When a Guild Captain is assigned as Acting GM, their visible title in the guild interface is updated from **Guild Captain** to **Acting GM**.  
    
- This title can be used by the GM and others as an indicator for delegating additional social or operational responsibilities beyond GSQs, depending on the guild's internal structure.  
    
- The assignment is visible in the guild interface as: **"Acting GM: [Name]"**  
    

### Automatic Activation

- If the GM is inactive for more than **24 hours (configurable)**, the currently assigned Acting GM automatically gains permission to submit GSQs (if not already active).  
    
- This automatic access lasts until the GM returns or assigns a new delegate.  
    

### Permissions

The Acting GM may:

- Submit and finalize both **Skill GSQs** and **Tool GSQs**  
    
- Access the **GSQ interface** with full permissions identical to the GM for submission  
    

The Acting GM may **not**:

- Promote/demote Captains or Officers  
    
- Disband or rename the guild  
    
- Reassign the Acting GM role  
    

### Transparency and Oversight

- All GSQ submissions by the Acting GM are logged in the **Guild Activity Log**  
    
- The GM retains full visibility into the actions taken while they were absent  
    

### Role Expiry

- The Acting GM designation remains in effect until manually changed by the GM.  
    
- The role does not expire automatically unless the guild structure or rank permissions are altered.  
    

This system ensures that guilds can maintain forward progress without requiring the GM’s constant presence, while still upholding a clear chain of command and transparent oversight.

## Guild Rank (GR)

**Guild Rank (GR)** represents the overall activity, history, and impact of a guild. GR is largely symbolic and serves as a visible indicator of a guild’s maturity and involvement in the world. Server admins may reference GR when considering guild privileges or recognition.  
It also plays a role in **progression scaling**, particularly for small or solo guilds.

GR is advanced by completing **Guild Skill Quests (GSQ)**. To reach higher ranks, a guild must complete a required number of GSQs across various difficulty tiers:

- Example (for Rank A):
    - X Rank A GSQs  
        
    - Y Rank B GSQs  
        
    - Z Rank C GSQs  
        
    - W Rank D GSQs  
        

These thresholds ensure that a guild’s growth is not just vertical (power-focused), but holistic across all types of contributions.

## Guild Quests (GQ), Guild Skill Quests (GSQ), and Tree Progression

Guild Quests (GQ) refresh periodically—typically daily or weekly—providing an ongoing source of objectives and engagement for members at every rank. Each guild's two skill trees directly determine the available GQ pools. For every rank, there are two quest pools—one for each tree—ensuring that GQ content aligns with the guild's identity and specialization. As ranks increase, the quests also become more demanding. In practice, high-ranking players are often expected to coordinate with or receive assistance from lower-ranking guildmates to complete their GQs.

The quest system is divided into two layers:

- **Guild Quests (GQ)** – Repeatable, role-based quests that grant **Guild Tokens (GT)** and **Tree Experience (TXP)**.  
    
- **Guild Skill Quests (GSQ)** – One-time, skill-tree-specific quests that unlock new abilities for the guild. Only the GM can complete and submit these.  
    

### Guild Skill Quests (GSQs)

**Guild Skill Quests (GSQs)** are critical milestones that drive a guild’s growth, identity, and power. They are submitted by the **Guild Master (GM)** and come in two main categories:

#### 1. Skill Unlock GSQs

These quests permanently unlock **new skills** within a guild’s two thematic trees. Once completed, these skills become available for members to allocate **Tree Skill Points (TSP)** into, depending on their Tree Level (TL), GP investment, and skill prerequisites.

- **One-time only**: Skill GSQs cannot be repeated.  
    
- **Contribute to Guild Rank (GR)** upon completion.  
    
- May be gated behind:
    - Previous skill unlocks (progression tree logic)  
        
    - Tool GSQs (e.g., must have crafted a tool before unlocking passive synergy skills)  
        

#### 2. Tool Redeemable GSQs

Tool GSQs reward the guild with powerful, tangible infrastructure or equipment—called **Guild Tools**—rather than unlocking skills. These tools range from utility stations and portals to world-interactive assets.

##### Tool GSQ Characteristics:

- **Repeatable**: Tool GSQs can be completed multiple times to receive additional copies of the associated tool.  
    
- **GR Contribution**: Only the **first successful completion** contributes to the guild’s GR. Subsequent completions are utility-only.  
    
- **Cost Scaling**: High-tier Tool GSQs typically **do not benefit from small/solo guild discounts**. If they do, the **discount is applied based on the guild’s active rate at the time of each redemption**, not when it was first unlocked.  
    

#### Guild Tool Mechanics

##### A. Guild-Exclusive Items

Guild Tools are **exclusive** to the guild that unlocked them. Only current guild members may:

- Interact with the item  
    
- Use its functions  
    
- Benefit from its effects  
    

If a player leaves the guild, any Guild Tool access is revoked.

##### B. Guild-Bound Items

Some Guild Tools are additionally **bound to the guild** and **tracked server-side**. These are limited in number due to their high power level or world impact.

- Each **guild has a cap** on how many active units of that tool may exist.  
    
- For example, **Guild Waystones** may be capped at **5 per guild**.  
    
- Once the cap is reached, neither the **GM nor GCs** can place more until an active one is removed.  
    
- Completion of the GSQ will still grant the item, but placement is **denied until space is available**.  
    

This ensures powerful items like teleporters, duplicators, or access hubs cannot overwhelm the world balance.

##### C. Placement & Management Authority

- Only **Guild Masters** and **Guild Captains** may **place**, **remove**, or **reclaim** Guild-Bound items.  
    
- Attempting to place a tool beyond the active cap results in a rejection message and no placement.  
    

##### D. Active Tracking for GMs

The GSQ interface includes a **live tracker** showing the current count of **active Guild-Bound tools** by type (e.g., "Waystone: 4/5 Active").

This allows the GM to monitor deployment and plan future tool placements strategically.

#### GSQ Submission Delegation

By default, only the **Guild Master (GM)** may submit and finalize Guild Skill Quests (GSQs). However, to ensure operational continuity, the GM may designate **one Guild Captain (GC)** at a time as the **Acting GM** for GSQ purposes.

The Acting GM is granted the following permissions:

- Submit and finalize both **Skill GSQs** and **Tool GSQs**  
    

A visible status indicator appears in the guild interface: **"Acting GM (GSQs): [Name]"**

The Acting GM designation is not time-limited and may be changed at any time by the GM using the **GSQ Delegation Panel**.

Additionally, if the GM becomes inactive for more than **24 hours**, the currently designated Acting GM automatically gains submission rights until the GM returns or assigns a new delegate.

All GSQ submissions—whether by the GM or the Acting GM—are **logged in the Guild Activity Log** for transparency.

#### Tool GSQ Access Structure

- Some Tool GSQs are **gated** behind:
    - Prior **Skill GSQs**  
        
    - Previous **Tool GSQs** (forming a **tech tree**)  
        
- Others are **standalone**—they are not tied to any unlock tree and may be completed at any time. These typically offer utility rather than progression.  
    

To support this, **Tool GSQs feature a distinctive icon** in the GSQ interface, visually separating them from Skill GSQs for easier navigation by the GM.

#### Example Tool GSQ Chain: Courier Infrastructure

1. **Skill GSQ**: _Courier Endurance Training_  
    _Unlocks a passive Adventuring Tree skill that increases mount movement speed for designated courier roles within the guild._
2. **Tool GSQ**: _Lesser Waystone Deployment_  
    _Grants a limited-use, Guild-Bound Lesser Waystone. Requires scrolls (also crafted or acquired) to activate teleportation. Counts toward the shared "Waystone" cap._
3. **Tool GSQ**: _Scrollwork Assembly_  
    _Provides a one-time batch of Guild Scrolls used to activate Lesser Waystones. Includes blueprint for continued production by guild crafters._
4. **Tool GSQ**: _Standard Waystone Access_  
    _Repeatable. Grants full-function Guild Waystones. Unlocked only after completing both "Lesser Waystone Deployment" and "Scrollwork Assembly" at least once. Shares cap with Lesser Waystones (total 5 active)._

#### Quality of Life Features

- Tool GSQs that unlock **Guild-Bound items** now add a permanent **completion checkmark** upon first completion, even if repeatable. This serves both as a tech tree reference and an audit trail. The GSQ does not become grayed out and may be repeated for utility.  
    
- Certain items (e.g., Lesser Waystones and Standard Waystones) **share a common placement cap**. For example, the total number of deployed Waystones, regardless of tier, may not exceed 5.  
    
- A **top-right interface menu** provides the GM with a list of all **limited-use Guild-Bound items** and their current active counts, streamlining management and avoiding over-deployment.  
    

---

This system ensures that:

- **Guilds earn real, functional power** through their progression.  
    
- **High-impact tools are tracked, gated, and bounded**, preserving game balance.  
    
- **GMs retain full visibility and control** over their infrastructure ecosystem.  
    
- **Visual and mechanical clarity** distinguishes between skill and tool progression paths.

### Tree Experience (TXP) and Tree Level (TL)

Each player tracks their own **Tree Level (TL)** independently for each of the guild’s two skill trees. Completing GQs grants **Tree Experience (TXP)** toward the tree associated with that specific quest. As TL increases, players are rewarded with **Tree Skill Points (TSP)**.

- TL is capped at 30 per tree.  
    
- TSP is capped at 120 per tree.  
    
- TL progression is permanent and remains with the player even if they leave a guild. If a player joins a new guild with the same tree, but the new guild has not unlocked certain skills they previously allocated TSP to, those skills will remain **allocated but inactive**. This design prevents players from using guild switching as a means to freely respec their TSP. To reallocate these inactive points, the player must use a **Tome of Reverie** to respec their skill selections.  
    
- When joining a new guild with the same tree, the player retains their TL, but available skills and usable TSP are based on current GP investment and the guild's unlocked GSQs.  
    

### TSP and GP Influence

Although TL determines the amount of TSP a player earns, the **maximum usable TSP** is gated by their **GP investment**:

|GP Spent|TSP Usability Cap (at TL 30)|
|---|---|
|1 GP|60 TSP (50%)|
|2 GP|90 TSP (75%)|
|3 GP|120 TSP (100%)|

Different skills consume different amounts of TSP based on their power. If a player spends more TSP than their GP allows (due to being demoted or reassigned), the system will **deactivate the most recently allocated skills** until their TSP usage falls within the new limit.

Players can use a special item called the **Tome of Reverie** to respec their TSP allocation if they wish to reprioritize their skill build.

### Guild Tokens (GT)

Guild Tokens come in five ranked tiers and are awarded through Guild Quests (GQs). Each guild role has a typical token tier associated with it, reflecting their access and influence:

- **Initiate** → Typically earns Guild Token D  
    
- **Guild Rookie** → Typically earns Guild Token D, occasionally C  
    
- **Guild Specialist** → Typically earns Guild Token C, occasionally B  
    
- **Guild Officer** → Typically earns Guild Token B, occasionally A  
    
- **Guild Captain** → Typically earns Guild Token A, occasionally S  
    
- **Guild Master** → Typically earns Guild Token S  
    

Players can complete GQs appropriate to their role, but they also retain access to lower-tier quest pools. Higher ranks unlock broader quest sets.

Guild Tokens earned from GQs can be turned in to higher-ranked members and ultimately delivered to the GM, who uses them (along with other resources) to fulfill GSQ requirements.

All Guild Tokens are permanently bound to the guild that issued them and cannot be used by or transferred to other guilds.

### Example GSQ: Unlock “Mining Dimension Portal” Skill

- 48x Guild Token D  
    
- 24x Guild Token C  
    
- 16x Guild Token B  
    
- 8x Guild Token A  
    
- 2x Guild Token S  
    
- 1x Guild Gem (staff-awarded)  
    
- 270x Diamonds  
    
- 200 Master Token  
    

**Guild Gems**: Rare rewards granted by staff for **participation, leadership, and contribution**. They are part of some high-tier GSQs, usually those unlocking powerful or infrastructure-related abilities (e.g., teleporters, dimension access).

With this system:

- Every member has a clear role in progressing the guild.  
    
- Contribution is both visible and valuable.  
    
- GM-directed progression is supported by the whole guild.  
    

Each role has access to a unique quest pool appropriate to their responsibility:

- **Initiates**: Going through the tutorial, learning the ropes, basic assignments  
    
- **Rookies**: Gathering, participation, supply delivery  
    
- **Specialists**: Coordination, construction projects, task management  
    
- **Officers**: Oversight, logistics, and support  
    
- **Captains**: Diplomacy, events, high-value orders  
    
- **GM**: Strategic submissions, rank milestones, promotions  
    

#### Design Note: Emergent Use of Guild Tokens

While Guild Tokens (GT) are primarily intended for GSQ progression, some guilds may choose to build **internal economies** around them. These may include informal **guild shops**, **reward structures**, or **promotion incentives** based on GT contributions.

This behavior is **not hard-coded**, but rather an emergent use of the systems in place. The GSQ framework is deliberately designed to support flexible leadership styles and player-driven organization.

## Contracts & Trade Agreements

Contracts are tangible items representing **formal agreements** between players or guilds. These documents define terms, responsibilities, and expectations for activities such as trades, services, or membership.

### Guild Contract

The **Guild Contract** is a special item used to onboard a player into a guild and define their initial role and GP investment. It serves as a binding agreement between the player and the guild leadership (GC or GM).

By default, only Captains and the Guild Master can issue Guild Contracts. However, specific Officers may be granted permission by a GC or GM to issue Guild Contracts for the **Rookie** role only. This enables designated roles such as guild receptionists to onboard new members while maintaining role-based authority.

If a new recruit demonstrates exceptional capabilities (e.g., high Tree Level), the Officer may escalate the case to a Captain for a higher-rank assignment.

- Only Captains or the Guild Master can issue a Guild Contract.  
    
- No player can edit their own contract. Any changes, including a request to reduce GP, must be authorized and applied by a higher-ranking role.  
    
- The contract defines:
    - Player name  
        
    - Assigned role  
        
    - GP investment (1–3 GP)  
        
    - Contract date  
        
    - Signatures of authorizing party  
        
- A new contract can be issued at any time to **update a member’s terms**, including role or GP investment, pending Captain or GM approval. Only one GM may exist per guild at any time. To designate a new GM, the current GM must switch roles with a GC, thereby promoting the GC to GM and demoting themselves to Captain. If a GM leaves the guild, a new GM is automatically chosen from the Captains, based on order of joining. If there are no Captains, then it will be chosen from the Officers, then the Specialists, then the Rookies. If no valid member is found, that means the guild has no remaining members, and the guild will be disbanded.  
    
- The only action a player can take unilaterally is to **leave the guild**, voiding their current contract.  
    

This system ensures that GP commitments are carefully managed and only assigned when warranted by activity or trust.

### Trade and Task Contracts

Other contract types include:

- **Delivery Contracts** – A player or guild agrees to provide specific items by a deadline.  
    
- **Service Contracts** – Agreements for completing tasks like building, automation, or redstone commissions.  
    
- **Trade Deals** – Agreements between towns and guilds for recurring resource exchanges or services.  
    

### Technical Function

All contracts are represented in-game as custom items (e.g., written books, tagged papers, or custom-textured items) and may include metadata:

- Contract type  
    
- Involved parties  
    
- Quantities or terms  
    
- Deadlines  
    
- Signatures or authorizations  
    

When used (typically through right-click interaction), contracts may open a **custom UI** where both parties complete their portion of the agreement. Once all conditions are met:

- The contract item is consumed.  
    
- The agreement is recorded in a list of **active contracts** associated with the involved players.  
    
- In the case of **Guild Contracts**, the record is added to the guild’s contract registry, accessible through a modded UI menu for guild management.  
    

Even though the original contract item is consumed, players can access a **copy of the signed contract** from their contract history menu. This copy serves as proof of agreement and may be used for follow-up interactions, such as validating a delivery or completing a turn-in by right-clicking it on an entity or container.

Certain containers, such as **contract-locked chests**, can only be accessed by using a valid copy of the corresponding contract. When used, access to the chest shifts from the contractor to the client, completing the transaction and locking out the contractor. These chests verify that the contents match the original contract terms before allowing access, acting as a one-time verification gate.

This system requires **custom mods** to function and is designed to support high-immersion roleplay and secure multi-party agreements.

## Addressing Potential Concerns

As part of the intended design philosophy behind the Towns & Guilds system, the following points are addressed to preemptively account for scalability, balance, and fairness in diverse gameplay contexts:

---

### New Player Onboarding & the Initiate Role

To help new and casual players smoothly enter the Towns & Guilds ecosystem, the **Initiate** role serves as a low-commitment, tutorial-oriented entry point. Initiates function as provisional guild members, allowing players to explore the basics of guild life without immediately investing Guild Points (GP) or assuming formal responsibilities.

Initiates may be introduced to a guild through a **server-driven tutorial questline** or invited directly by guild Officers and higher roles, who have the authority to issue Initiate Contracts. These contracts assign the player to the Initiate role with 0 GP investment and grant them limited access to guild functions.

While in this role, players may complete **Initiate-grade Guild Quests (GQs)**—a curated subset of beginner-friendly tasks intended to teach the fundamentals of guild gameplay. These quests are simpler than those available to Rookies and always reward **Guild Token D**, reinforcing early participation and contribution.

Initiates have access to **33% of their available Tree Skill Points (TSP)**, allowing limited interaction with unlocked skills based on their Tree Level (TL). The full skill tree is always visible to all guild members, though unselectable skills remain greyed out when beyond a player's current GP tier.

Initiate Contracts are **temporary** and expire after a set duration (e.g., 7 real-world days). Players nearing the expiration of their contract will receive automated reminders through the mod’s UI. Upon expiration, an Officer or higher may choose to promote the player to Rookie, renew the Initiate contract, or release them from the guild. This approach ensures that trial members must demonstrate engagement to remain within the organization.

This structure empowers guilds to onboard new players in a low-risk, low-pressure way while preserving the integrity and standards of the broader guild progression system.

---

### GM Inactivity & Power Bottlenecks

Guild Masters (GMs) play a vital role in advancing their guild's growth by approving high-level decisions and submitting Guild Skill Quests (GSQs). However, when a GM becomes inactive, it can lead to organizational stagnation. To prevent this, the system includes a clear protocol for detecting inactivity and resolving leadership deadlock.

A GM is automatically flagged as inactive after a period of **3 real-world weeks** without logging in. Once flagged, any active **Guild Captain (GC)** may initiate a **Vote of No Confidence**.

For the vote to succeed:

- **All currently active Captains must unanimously agree** to the ejection.  
    
- The vote is finalized through a 48-hour decision window.  
    

If the vote passes, the inactive GM is demoted to the rank of Captain, and the standard **guild succession system** takes immediate effect.

#### Chain of Succession

When the GM role is vacated, the **chain of succession** is as follows:

1. If an **Acting GM** has been designated and is currently active, they are automatically promoted to full GM.
2. If there is no Acting GM, the **longest-standing active Guild Captain** is promoted instead.

This ensures that succession reflects the original GM's intentions, preserving leadership continuity and honoring delegated trust.

#### Orphaned Guilds

If the GM is inactive and there are **no active Captains**, lower-ranking members such as Officers or Specialists cannot trigger an ejection vote. Instead, these members are considered **orphaned**. They are encouraged to **leave the guild** voluntarily and seek new opportunities elsewhere. Once all remaining members have left, the guild is marked as **dissolved** by the system.

#### Bad-Faith Loopholes

If a GM attempts to **evade inactivity detection** by briefly logging in without meaningfully contributing—such as avoiding GSQs or guild decisions—this is considered a **bad-faith loophole**. In such cases, server staff may be petitioned to review the situation and, if appropriate, forcibly remove the GM.

#### Staff Intervention

If a guild lacks a GM and any active Captains, but lower-ranking members are **committed to preserving the guild**, the **highest-ranked active member** may submit a request to server administration for manual promotion to GM. This is intended to preserve player-built communities when they are otherwise at risk of collapse due to absent leadership.

This system maintains the balance of authority while avoiding bureaucratic stagnation, preserving the importance of strong leadership without risking indefinite deadlock.

---

### Solo and Small Guild Viability

In the early phases of a server's life, or in quieter player populations, it is essential that **solo Guild Masters (GMs)** and **small guilds** remain viable. While large guilds will naturally achieve faster throughput and collaboration, smaller groups must be capable of fully participating in the core systems of Towns & Guilds without undue disadvantage.

To support this, the system introduces a **scaling modifier system** that dynamically adjusts GSQ token requirements based on the guild's size and maturity. These modifiers ensure that early-stage and low-commitment guilds enjoy a smoother progression curve, while still maintaining the long-term prestige of organized, high-investment groups.

Two inputs determine the scaling:

- **Total GP Investment**: The sum of GP committed across all guild members.  
    
- **Guild Rank (GR)**: The current level of the guild, based on cumulative GSQ completions.  
    

The **GP-based modifier** serves as the primary discount factor, while the **GR-based modifier acts as a multiplier** on that discount. The lower the guild’s GP and GR, the more generous the combined effect.

#### GP-Based Modifier (Base Discount)

|Total GP|Base Token Reduction|
|---|---|
|1–3|35%|
|4–6|25%|
|7–9|20%|
|10–12|15%|
|13–15|10%|
|16+|No reduction|

#### GR-Based Modifier (Multiplier on Base Discount)

|Guild Rank|Multiplier|
|---|---|
|Rank D|×2.0|
|Rank C|×1.7|
|Rank B|×1.5|
|Rank A|×1.2|
|Rank S|×1.0|

**Example:** A guild with 9 total GP and Guild Rank D receives a 20% base reduction × 2.0 = **40% total discount** on a GSQ's token requirements. The overall maximum discount achievable is capped at **70%**, ensuring that even small or early-stage guilds contribute meaningfully to progression.

Once a GSQ is submitted, the cost is locked in based on the guild’s current GP and GR. Future GSQs will adjust accordingly if the guild’s status changes.

**High-tier GSQs**, particularly those related to infrastructure or server-wide capabilities, are **not eligible for scaling**. These are intended to be late-game collaborative milestones that reward larger, more coordinated organizations.  
That said, **solo players may still complete these over time**, though doing so will be a considerable long-term undertaking.

This system ensures that early and independent guild efforts are rewarded fairly, while preserving the aspirational scale and complexity of high-level guild operations.

---

### Large Guild Behavior and Scaling Implications

In a highly active server environment, it is possible—though not guaranteed—that some guilds may grow to include 30 or more members. The Towns & Guilds system is intentionally designed to **reward organized collaboration**, but not passive membership. Even at this hypothetical scale, progression is still dictated by meaningful contribution.

Large guilds receive **no systemic bonuses** from their size alone. In fact, once their total GP investment exceeds the scaling thresholds, **they receive no GSQ token discounts whatsoever**. To progress, they must rely entirely on member activity—particularly the generation of Guild Tokens through GQs—and strategic coordination to turn those tokens into GSQ completions.

This means that a large guild that is inactive or uncoordinated is effectively weaker than a small or solo guild that is fully engaged. Guild Tokens are:

- **Bound to the issuing guild**, meaning only internal contribution counts.  
    
- **Non-transferable between guilds**, ensuring tokens cannot be externally farmed.  
    
- **Only generated through active player participation in quests**, making them an accurate reflection of engagement.  
    

As such, **large guilds must be genuinely active** to achieve and maintain their advantages. The social prestige, economic impact, and strategic positioning of a large guild are earned—not assumed—through the collective output of its members.

This design encourages the formation of large communities while still requiring internal commitment, making social growth both viable and balanced. It ensures that the system scales effectively across all stages of server development, and that **strong organization—not mere headcount—is the primary vector for power**. As a result, the server naturally promotes and elevates groups that demonstrate genuine coordination and contribution.

---

### Foundational Guild Growth & Leadership Legacy

It is fully possible—and entirely intended—that a solo player or a small group could develop a guild's early GSQs, unlock valuable skill trees, and later open the guild to new recruits. This raises the question of whether new members are gaining access to perks they didn’t help earn.

The answer lies in the system’s balance of effort and accessibility. Founders who develop guilds solo are putting in significant effort and are forgoing the benefits of group collaboration. Any new member joining after the fact still has to:

- **Earn their own Tree Level (TL)** through GQs  
    
- **Invest GP to access skill trees**, with all associated tradeoffs  
    
- **Contribute Guild Tokens** to access or unlock future GSQs  
    

There is no free power handed to newcomers. They join a well-founded organization and must contribute meaningfully to continue its progression. Conversely, founders receive social prestige and leadership position as a reward for early commitment.

This is not a loophole, but a healthy gameplay loop that mimics how real organizations grow. Successful guilds naturally attract others, and their leadership legacy becomes part of the world’s evolving history.

---

### Tree Access in Multi-Guild Membership

When a player belongs to multiple guilds that share the same skill tree, a consistent rule is needed to determine what perks and progression that player can access. Since players only have one Tree Level (TL) and one Tree Skill Point (TSP) pool per skill tree, overlapping guilds must not enable duplication or exploitation.

This section defines how **TSP usability** and **skill unlocks** are governed when multiple guilds share a tree.

---

#### Rule Summary

1. **Each player has only one version of each skill tree.**
2. **Access to a tree requires membership in at least one guild that offers it.**
3. **The TSP cap for a shared tree is determined by the player's GP investment in the guild with the highest Guild Rank (GR) among those that offer it.**
4. **If multiple guilds have the same GR, the one with the highest GP investment determines the TSP cap.**
5. **Skills unlocked through GSQs are combined additively across all guilds the player is part of that share the tree.**

These checks are re-evaluated each time a player logs in or opens the skill tree UI. If the controlling guild changes (e.g., due to GR updates), the player's TSP cap may change accordingly.

---

#### Example: How It Works

A player is in:

- **Guild A** — 3 GP invested, Rank A  
    
- **Guild B** — 1 GP invested, Rank A  
    

Guild A determines the TSP cap due to higher GP investment.

If later:

- **Guild A** remains at Rank A  
    
- **Guild B** increases to Rank S  
    

Then Guild B becomes the controlling guild. The player's usable TSP will be based on the **1 GP invested in Guild B**, potentially deactivating some previously used skills. These skills remain allocated but become **inactive**, similar to what happens when a player is demoted and their TSP exceeds the new GP limit.

This dynamic encourages players to remain meaningfully invested in the guilds they wish to benefit from.

---

### Addressing Contract Abuse & Transparency

The Guild Contract system introduces formal agreements for membership, rank, and GP investment, creating a strong roleplay and structure layer. However, any such system involving human decisions must anticipate misuse—not necessarily through bugs or exploits, but through misaligned intent or social conflict.

Some potential abuse scenarios include coercive onboarding, arbitrary demotion, or using contracts as a tool for social control. However, these are not design flaws—they are **social dynamics** best resolved through transparency and player autonomy.

#### Why the System Holds

- **Tree Level (TL) is permanent**: A demoted or ejected player retains their TL, meaning their progress isn't lost and can be leveraged in future guilds.  
    
- **Contracts are transparent**: Public logs and preview windows ensure players know what they’re agreeing to.  
    
- **Leaving is always an option**: No contract can trap a player; they can walk away with their TL intact.  
    
- **Guilds gain nothing from power abuse**: There is no mechanical benefit to demoting a player arbitrarily. Doing so hurts the guild’s progression and damages its reputation.  
    

If leadership is toxic or petty, it will naturally **burn talent and decay**—not due to punitive mechanics, but because the system **rewards contribution and discourages passivity**. Guilds that don’t foster fairness or loyalty will falter over time.

The only cases where intervention may be necessary are when:

- **Bad-faith actors mislead new players** through deceptive onboarding.  
    
- **Repetitive social abuse patterns** emerge from the same leadership group.  
    

In such cases, server staff can intervene through a **formal arbitration process** to mediate disputes or impose corrective measures.

This approach helps keep guild life immersive and meaningful, while safeguarding players from predatory practices—without diminishing the depth and agency of emergent social structures.

---

### Addressing Alt Account Concerns

A commonly raised concern in multiplayer systems is the potential for alt account abuse—particularly scenarios where a single player might create multiple low-GP characters to generate Guild Tokens through easy quests.

However, the Towns & Guilds system is inherently resilient to this type of abuse by design. Guild Tokens are:

- **Bound to the issuing guild**, meaning they cannot be used to progress another guild.  
    
- **Only meaningful within the originating guild’s GSQ system**, which requires substantial, structured contribution.  
    
- **Produced through real quest activity**, meaning any alt must actually perform work to generate tokens.  
    

Furthermore, by creating alts to simulate a multi-member guild, the player loses access to the powerful **GP-based scaling bonuses** designed for solo and small guild play. In practice:

- A solo guild can access up to a 70% GSQ token reduction.  
    
- A multi-alt guild immediately invalidates that bonus and must pay full cost.  
    

This makes multi-account farming **less efficient** than simply playing actively on one account. Real guildmates generate more varied and useful token types (e.g., B or A), progress higher-scope quests, and can fulfill collaborative goals more effectively.

The **structure and scaling of the game itself reward authentic participation** and make any attempt at gaming the system through alts a suboptimal strategy.

---

### Cross-Guild Interaction and Land Agreements

While cross-guild collaboration is not a formalized mechanic, the system is intentionally designed to support organic interactions between guilds through towns, shared infrastructure, trade, and diplomacy. Most collaboration will naturally occur within the town environment where guilds coexist, participate in events, or align their interests around construction, commerce, and influence.

Rather than hardcoding alliance systems, Towns & Guilds encourages these relationships to emerge **organically through the existing contract framework**. Guilds, towns, or players can establish their own treaties, agreements, and collaborations using customized contract types.

To support this, a new category of contracts—**Land Agreements**—may be issued to represent property claims, rentals, leases, or co-ownership deals. These contracts would include metadata specifying:

- **Land zone or coordinates**  
    
- **Type of agreement** (purchase, rental, shared usage)  
    
- **Recurrence terms**, such as rent payment cycles  
    
- **Contractor and client permissions**  
    

If a land contract involves a **recurring payment**, it becomes the contractor's responsibility to ensure payments are made. The contract UI will track overdue payments and, after a defined grace period, enable the contractor to **rescind the agreement**. When this happens, ownership of the land is unclaimed and transferred back to the contractor.

This approach supports a broad variety of real-world scenarios:

- Renting a house or workshop from a merchant guild  
    
- Selling territory between towns  
    
- Managing tenant agreements in a shared guild compound  
    
- Diplomatic land swaps or protectorate arrangements  
    

These land contracts make it possible for **guilds and players to simulate real, meaningful economic and territorial relationships** without the need for extra mechanical layers. The immersion comes from the social structure, while the system simply enforces the agreed-upon terms.

## Glossary

**GP (Guild Points)**  
Represents a player's commitment to a guild. Determines their rank eligibility, TSP usability, and role privileges. Players start with 5 GP (max 9).

**TSP (Tree Skill Points)**  
Points used to unlock and activate abilities within a guild's skill tree. TSP earned via leveling up (TL) but capped by GP investment.

**TL (Tree Level)**  
A player's experience level in a specific guild skill tree. Capped at 30. TL increases through completing Guild Quests (GQs).

**TXP (Tree Experience)**  
Experience earned from Guild Quests (GQs), used to increase Tree Level (TL).

**GR (Guild Rank)**  
Represents a guild’s maturity and accomplishments. Advanced by completing Guild Skill Quests (GSQs). Affects progression scaling for small guilds.

**GQ (Guild Quest)**  
Repeatable quests that generate Guild Tokens and TXP. Aligned with guild skill trees and member roles.

**GSQ (Guild Skill Quest)**  
One-time quests that unlock new guild abilities or infrastructure. Completed only by the Guild Master.

**GT (Guild Token)**  
Currency earned through GQs, ranked from D to S. Used to fulfill GSQ requirements. Bound to the guild that issued them.

**Guild Contract**  
A formal item-based agreement defining a member’s role and GP investment. Managed by Captains or the GM.

**Initiate Contract**  
A temporary, 0-GP contract used to onboard new players in a trial capacity.

**Tome of Reverie**  
Item used to respec (reallocate) a player's TSP within a skill tree.

**Contract-Locked Chest**  
Special container tied to a contract; requires a valid signed contract to access or finalize a delivery.

**Guild Gem**  
Rare, staff-awarded item used in high-tier GSQs, representing leadership, community contribution, or strategic milestones.