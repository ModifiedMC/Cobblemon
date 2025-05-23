- [[#Towns & Guilds]]
- [[#Player Skills]]
- [[#PokéDungeons]]
- [[#Dungeons]]
- [[#NPC Quests]]
- [[#FTB Quests]]
- [[#Seasonal Pokémon League]]
- [[#Custom Mods & Content]]
- [[#Dynamic Events]]

# Towns & Guilds

**Towns & Guilds** is the part of the project focused on fostering player communities and driving the in-game economy. It introduces a guild-based skill system, where players join specific guilds—similar to RPG job classes—to access unique skill trees and role-specific abilities. Each guild supports a distinct gameplay style or profession, encouraging cooperation and specialization within the player community.

## Concept Overview

While the system is designed to encourage collaboration and group specialization, **nothing prevents a solo player** from founding a guild and acting as its sole member and Guild Master. This solo GM can undertake Guild Quests (GQs) and Guild Skill Quests (GSQs) alone, earn Guild Tokens, and even obtain Guild Gems through meaningful server participation.

That said, this path is **deliberately challenging**, as the effort and resource demands of progressing a guild are balanced around group-scale activity. Completing high-tier quests and unlocking powerful abilities solo is possible—but intentionally challenging.

With that in mind, guild progression systems are designed to scale based on member commitment and activity, with special consideration given to solo players and small guilds through built-in token scaling.

The core goal of this system is to encourage players to **form towns** and **establish guilds** as persistent, meaningful structures within the server's world.

- **Towns** act as the foundation for player governance and community building. Each town is expected to function as a semi-autonomous entity, complete with leadership, infrastructure, and a sustainable economy.
    
- **Guilds** are professional organizations that specialize in a particular trade, such as farming, blacksmithing, enchanting, exploration, or construction. They provide structure, role identity, and skill progression for players who join them.
    

## Town-Guild Relationship

- A guild must have a **physical presence (guild building)** in at least one town to be officially recognized.
    
- While a guild may originate in a specific town, it is **not limited to that town** and can **freely expand to others**.
    
- **Towns do not have jurisdiction** over a guild's expansion decisions. A founding town may serve as the symbolic origin or cultural hub of a guild, but it **holds no formal control** over where the guild operates next.
    
- The one exception is when a **host town financially or materially contributes** to the deployment of a new guild branch. In such cases, **terms can be negotiated** between all parties involved.
    
- This system encourages **player-driven diplomacy**, where inter-town and guild relations are shaped by mutual benefit rather than strict hierarchy.
    

## Guild-Player Interaction & the GP System

Each guild offers players access to two unique **skill trees**, which reflect the guild's thematic identity and core functions. These trees define the perks, abilities, and enhancements that guild members can unlock over time.

### Skill Tree Design

A guild’s skill trees are chosen at the time of its founding and are tied closely to its focus. For example:

- The **Risky Miners Guild** may offer:
    
    - A **Mining Tree** with skills related to efficiency, rare ore detection, and safety bypass tools.
        
    - An **Adventuring Tree** that enhances mobility, hazard resistance, or underground combat bonuses.
        
- The **Tech Builders Guild** might include:
    
    - A **Tech Tree** for automation, redstone logic, or power systems.
        
    - A **Builder Tree** for improved construction tools, blueprint systems, or block manipulation perks.
        

This dual-tree structure facilitates each guild maintaining a **unique identity** while allowing flexibility for members to engage with multiple playstyles.

### Guild Points (GP)

**Guild Points (GP)** represent a player's availability and willingness to commit to guild activities. This soft cap system regulates how many guilds a player can meaningfully participate in.

- Players begin with **5 GP**, which can increase up to **9 GP** as they progress.
    
- Joining a guild requires spending **1 to 3 GP**, set in the initial contract.
    
- GP spent determines the _maximum_ amount of **Tree Skill Points (TSP)** the player can actively use, which limits how many skills they can select within the unlocked skill tree. All members can see the full unlocked tree, but TSP determines how much of it they can actively utilize:
    

|GP Spent|SP Allocation Rate|
|---|---|
|1 GP|50% of total TSP|
|2 GP|75% of total TSP|
|3 GP|100% of total TSP|

This encourages meaningful specialization while still allowing players to join multiple guilds.

## Guild Roles & Hierarchy

Guilds have a structured hierarchy with defined responsibilities and GP requirements. Each role corresponds to a Guild Token rank and determines access to specific Guild Quests (GQs).

- **Guild Master (GM)** – 3 GP required. Can create and manage the guild, promote and demote any role, sign off Guild Skill Quests (GSQ), and manage high-level contracts. Token: **Guild Token S**. Only one GM per guild.
    
- **Guild Captain (GC)** – 3 GP required. Can invite and demote members, promote Specialists and Officers, manage contracts, and eject inactive or disruptive members. Token: **Guild Token A** (occasionally **S**). Max of 4 per guild.
    
- **Guild Officer** – 3 GP required. Mid-level leader with organizational responsibility. While Officers cannot issue Guild Contracts by default, specific Officers may be granted permission by a GC or GM to issue contracts for the Rookie role only. Token: **Guild Token B** (occasionally **A**).
    
- **Guild Specialist** – 2 GP required. Trusted contributor with access to higher-tier GQs and guild projects. Token: **Guild Token C** (occasionally **B**).
    
- **Guild Rookie** – 1 GP required. Entry-level member, limited privileges, mostly introductory tasks and GQs. Token: **Guild Token D** (occasionally **C**).
    
-  **Initiate** – 0 GP required. Temporary onboarding role with access to tutorial-level GQs and minimal TSP (33%). Token: **Guild Token D** only.
    

Contracts define the terms of a player’s commitment. While there may be organic negotiation between the applicant and the Captain during the onboarding process, the final decision on how much GP is allocated is solely up to the Captain. The applicant cannot choose their own GP investment—this prevents players from claiming high contribution without following through.

The only unilateral action a member can take is to leave the guild altogether.

Captains can demote 2 GP members to 1 GP, just as they can demote Specialists to Rookies. Similarly, GMs have full authority to demote Captains or Officers to any lower role.

GP and guild roles are separate: a player may be assigned 3 GP but still hold the rank of Rookie. Conversely, GMs and GCs can eject any lower role at any time in response to inactivity, disruption, or lack of contribution.

## Guild Rank (GR)

**Guild Rank (GR)** represents the overall activity, history, and impact of a guild. GR is largely symbolic and serves as a visible indicator of a guild’s maturity and involvement in the world. Server admins may reference GR when considering guild privileges or recognition.  
It also plays a role in **progression scaling**, particularly for small or solo guilds.

GR is advanced by completing **Guild Skill Quests (GSQ)**. To reach higher ranks, a guild must complete a required number of GSQs across various difficulty tiers:

- Example (for Rank A):
    
    - X Rank A GSQs
        
    - Y Rank B GSQs
        
    - Z Rank C GSQs
        
    - W Rank D GSQs
        

These thresholds ensure that a guild’s growth is not just vertical (power-focused), but holistic across all types of contributions.

## Guild Quests (GQ), Guild Skill Quests (GSQ), and Tree Progression

Guild Quests (GQ) refresh periodically—typically daily or weekly—providing an ongoing source of objectives and engagement for members at every rank. Each guild's two skill trees directly determine the available GQ pools. For every rank, there are two quest pools—one for each tree—ensuring that GQ content aligns with the guild's identity and specialization. As ranks increase, the quests also become more demanding. In practice, high-ranking players are often expected to coordinate with or receive assistance from lower-ranking guildmates to complete their GQs.

The quest system is divided into two layers:

- **Guild Quests (GQ)** – Repeatable, role-based quests that grant **Guild Tokens (GT)** and **Tree Experience (TXP)**.
    
- **Guild Skill Quests (GSQ)** – One-time, skill-tree-specific quests that unlock new abilities for the guild. Only the GM can complete and submit these.
    

### Tree Experience (TXP) and Tree Level (TL)

Each player tracks their own **Tree Level (TL)** independently for each of the guild’s two skill trees. Completing GQs grants **Tree Experience (TXP)** toward the tree associated with that specific quest. As TL increases, players are rewarded with **Tree Skill Points (TSP)**.

- TL is capped at 30 per tree.
    
- TSP is capped at 120 per tree.
    
- TL progression is permanent and remains with the player even if they leave a guild. If a player joins a new guild with the same tree, but the new guild has not unlocked certain skills they previously allocated TSP to, those skills will remain **allocated but inactive**. This design prevents players from using guild switching as a means to freely respec their TSP. To reallocate these inactive points, the player must use a **Tome of Reverie** to respec their skill selections.
    
- When joining a new guild with the same tree, the player retains their TL, but available skills and usable TSP are based on current GP investment and the guild's unlocked GSQs.
    

### TSP and GP Influence

Although TL determines the amount of TSP a player earns, the **maximum usable TSP** is gated by their **GP investment**:

|GP Spent|TSP Usability Cap (at TL 30)|
|---|---|
|1 GP|60 TSP (50%)|
|2 GP|90 TSP (75%)|
|3 GP|120 TSP (100%)|

Different skills consume different amounts of TSP based on their power. If a player spends more TSP than their GP allows (due to being demoted or reassigned), the system will **deactivate the most recently allocated skills** until their TSP usage falls within the new limit.

Players can use a special item called the **Tome of Reverie** to respec their TSP allocation if they wish to reprioritize their skill build.

### Guild Tokens (GT)

Guild Tokens come in five ranked tiers and are awarded through Guild Quests (GQs). Each guild role has a typical token tier associated with it, reflecting their access and influence:

-  **Initiate** → Typically earns Guild Token D
    
- **Guild Rookie** → Typically earns Guild Token D, occasionally C
    
- **Guild Specialist** → Typically earns Guild Token C, occasionally B
    
- **Guild Officer** → Typically earns Guild Token B, occasionally A
    
- **Guild Captain** → Typically earns Guild Token A, occasionally S
    
- **Guild Master** → Typically earns Guild Token S
    

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
    

**Guild Gems**: Rare rewards granted by staff for **participation, leadership, and contribution**. They are part of some high-tier GSQs, usually those unlocking powerful or infrastructure-related abilities (e.g., teleporters, dimension access).

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
    

## Contracts & Trade Agreements

Contracts are tangible items representing **formal agreements** between players or guilds. These documents define terms, responsibilities, and expectations for activities such as trades, services, or membership.

### Guild Contract

The **Guild Contract** is a special item used to onboard a player into a guild and define their initial role and GP investment. It serves as a binding agreement between the player and the guild leadership (GC or GM).

By default, only Captains and the Guild Master can issue Guild Contracts. However, specific Officers may be granted permission by a GC or GM to issue Guild Contracts for the **Rookie** role only. This enables designated roles such as guild receptionists to onboard new members while maintaining role-based authority.

If a new recruit demonstrates exceptional capabilities (e.g., high Tree Level), the Officer may escalate the case to a Captain for a higher-rank assignment.

- Only Captains or the Guild Master can issue a Guild Contract.
    
- No player can edit their own contract. Any changes, including a request to reduce GP, must be authorized and applied by a higher-ranking role.
    
- The contract defines:
    
    - Player name
        
    - Assigned role
        
    - GP investment (1–3 GP)
        
    - Contract date
        
    - Signatures of authorizing party
        
- A new contract can be issued at any time to **update a member’s terms**, including role or GP investment, pending Captain or GM approval. Only one GM may exist per guild at any time. To designate a new GM, the current GM must switch roles with a GC, thereby promoting the GC to GM and demoting themselves to Captain. If a GM leaves the guild, a new GM is automatically chosen from the Captains, based on order of joining. If there are no Captains, then it will be chosen from the Officers, then the Specialists, then the Rookies. If no valid member is found, that means the guild has no remaining members, and the guild will be disbanded.
    
- The only action a player can take unilaterally is to **leave the guild**, voiding their current contract.
    

This system ensures that GP commitments are carefully managed and only assigned when warranted by activity or trust.

### Trade and Task Contracts

Other contract types include:

- **Delivery Contracts** – A player or guild agrees to provide specific items by a deadline.
    
- **Service Contracts** – Agreements for completing tasks like building, automation, or redstone commissions.
    
- **Trade Deals** – Agreements between towns and guilds for recurring resource exchanges or services.
    

### Technical Function

All contracts are represented in-game as custom items (e.g., written books, tagged papers, or custom-textured items) and may include metadata:

- Contract type
    
- Involved parties
    
- Quantities or terms
    
- Deadlines
    
- Signatures or authorizations
    

When used (typically through right-click interaction), contracts may open a **custom UI** where both parties complete their portion of the agreement. Once all conditions are met:

- The contract item is consumed.
    
- The agreement is recorded in a list of **active contracts** associated with the involved players.
    
- In the case of **Guild Contracts**, the record is added to the guild’s contract registry, accessible through a modded UI menu for guild management.
    

Even though the original contract item is consumed, players can access a **copy of the signed contract** from their contract history menu. This copy serves as proof of agreement and may be used for follow-up interactions, such as validating a delivery or completing a turn-in by right-clicking it on an entity or container.

Certain containers, such as **contract-locked chests**, can only be accessed by using a valid copy of the corresponding contract. When used, access to the chest shifts from the contractor to the client, completing the transaction and locking out the contractor. These chests verify that the contents match the original contract terms before allowing access, acting as a one-time verification gate.

This system requires **custom mods** to function and is designed to support high-immersion roleplay and secure multi-party agreements.

## Addressing Potential Concerns

As part of the intended design philosophy behind the Towns & Guilds system, the following points are addressed to preemptively account for scalability, balance, and fairness in diverse gameplay contexts:

---

### New Player Onboarding & the Initiate Role

To help new and casual players smoothly enter the Towns & Guilds ecosystem, the **Initiate** role serves as a low-commitment, tutorial-oriented entry point. Initiates function as provisional guild members, allowing players to explore the basics of guild life without immediately investing Guild Points (GP) or assuming formal responsibilities.

Initiates may be introduced to a guild through a **server-driven tutorial questline** or invited directly by guild Officers and higher roles, who have the authority to issue Initiate Contracts. These contracts assign the player to the Initiate role with 0 GP investment and grant them limited access to guild functions.

While in this role, players may complete **Initiate-grade Guild Quests (GQs)**—a curated subset of beginner-friendly tasks intended to teach the fundamentals of guild gameplay. These quests are simpler than those available to Rookies and always reward **Guild Token D**, reinforcing early participation and contribution.

Initiates have access to **33% of their available Tree Skill Points (TSP)**, allowing limited interaction with unlocked skills based on their Tree Level (TL). The full skill tree is always visible to all guild members, though unselectable skills remain greyed out when beyond a player's current GP tier.

Initiate Contracts are **temporary** and expire after a set duration (e.g., 7 real-world days). Players nearing the expiration of their contract will receive automated reminders through the mod’s UI. Upon expiration, an Officer or higher may choose to promote the player to Rookie, renew the Initiate contract, or release them from the guild. This approach ensures that trial members must demonstrate engagement to remain within the organization.

This structure empowers guilds to onboard new players in a low-risk, low-pressure way while preserving the integrity and standards of the broader guild progression system.

---

### GM Inactivity & Power Bottlenecks

Guild Masters (GMs) play a vital role in advancing their guild's growth by approving high-level decisions and submitting Guild Skill Quests (GSQs). However, when a GM becomes inactive, it can lead to organizational stagnation. To prevent this, the system includes a clear protocol for detecting inactivity and resolving leadership deadlock.

A GM is automatically flagged as inactive after a period of **3 real-world weeks** without logging in. Once flagged, any active **Guild Captain (GC)** may initiate a **Vote of No Confidence**.

For the vote to succeed:

- **All currently active Captains must unanimously agree** to the ejection.
    
- The vote is finalized through a 48-hour decision window.
    

If the vote passes, the inactive GM is demoted to the rank of Captain, and the standard **guild succession system** takes immediate effect—typically promoting the longest-standing Captain to GM. This approach ensures that no single Captain can unilaterally seize power while still providing a structured way to respond to prolonged leadership absence.

In cases where the GM is inactive and there are **no active Captains**, lower-ranking members such as Officers or Specialists cannot trigger an ejection vote. Instead, these members are considered **orphaned**. They are encouraged to **leave the guild** voluntarily and seek new opportunities elsewhere. Once all remaining members have left, the guild is marked as **dissolved** by the system.

If a GM attempts to **evade inactivity detection** by briefly logging in without meaningfully contributing—such as avoiding GSQs or guild decisions—this is considered a **bad-faith loophole**. In such cases, server staff may be petitioned to review the situation and, if appropriate, forcibly remove the GM.

Likewise, if a guild lacks a GM and any active Captains, but lower-ranking members are **committed to preserving the guild**, the **highest-ranked active member** may submit a request to server administration for manual promotion to GM. This is intended to preserve player-built communities when they are otherwise at risk of collapse due to absent leadership.

This system maintains the balance of authority while avoiding bureaucratic stagnation, preserving the importance of strong leadership without risking indefinite deadlock.

---

### Solo and Small Guild Viability

In the early phases of a server's life, or in quieter player populations, it is essential that **solo Guild Masters (GMs)** and **small guilds** remain viable. While large guilds will naturally achieve faster throughput and collaboration, smaller groups must be capable of fully participating in the core systems of Towns & Guilds without undue disadvantage.

To support this, the system introduces a **scaling modifier system** that dynamically adjusts GSQ token requirements based on the guild's size and maturity. These modifiers ensure that early-stage and low-commitment guilds enjoy a smoother progression curve, while still maintaining the long-term prestige of organized, high-investment groups.

Two inputs determine the scaling:

- **Total GP Investment**: The sum of GP committed across all guild members.
    
- **Guild Rank (GR)**: The current level of the guild, based on cumulative GSQ completions.
    

The **GP-based modifier** serves as the primary discount factor, while the **GR-based modifier acts as a multiplier** on that discount. The lower the guild’s GP and GR, the more generous the combined effect.

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

| Guild Rank | Multiplier |
|------------|------------|
| Rank D     | ×2.0       |
| Rank C     | ×1.7       |
| Rank B     | ×1.5       |
| Rank A     | ×1.2       |
| Rank S     | ×1.0       |

**Example:** A guild with 9 total GP and Guild Rank D receives a 20% base reduction × 2.0 = **40% total discount** on a GSQ's token requirements. The overall maximum discount achievable is capped at **70%**, ensuring that even small or early-stage guilds contribute meaningfully to progression. 

Once a GSQ is submitted, the cost is locked in based on the guild’s current GP and GR. Future GSQs will adjust accordingly if the guild’s status changes.

**High-tier GSQs**, particularly those related to infrastructure or server-wide capabilities, are **not eligible for scaling**. These are intended to be late-game collaborative milestones that reward larger, more coordinated organizations.  
That said, **solo players may still complete these over time**, though doing so will be a considerable long-term undertaking.

This system ensures that early and independent guild efforts are rewarded fairly, while preserving the aspirational scale and complexity of high-level guild operations.

---

### Large Guild Behavior and Scaling Implications

In a highly active server environment, it is possible—though not guaranteed—that some guilds may grow to include 30 or more members. The Towns & Guilds system is intentionally designed to **reward organized collaboration**, but not passive membership. Even at this hypothetical scale, progression is still dictated by meaningful contribution.

Large guilds receive **no systemic bonuses** from their size alone. In fact, once their total GP investment exceeds the scaling thresholds, **they receive no GSQ token discounts whatsoever**. To progress, they must rely entirely on member activity—particularly the generation of Guild Tokens through GQs—and strategic coordination to turn those tokens into GSQ completions.

This means that a large guild that is inactive or uncoordinated is effectively weaker than a small or solo guild that is fully engaged. Guild Tokens are:

- **Bound to the issuing guild**, meaning only internal contribution counts.
    
- **Non-transferable between guilds**, ensuring tokens cannot be externally farmed.
    
- **Only generated through active player participation in quests**, making them an accurate reflection of engagement.
    

As such, **large guilds must be genuinely active** to achieve and maintain their advantages. The social prestige, economic impact, and strategic positioning of a large guild are earned—not assumed—through the collective output of its members.

This design encourages the formation of large communities while still requiring internal commitment, making social growth both viable and balanced. It ensures that the system scales effectively across all stages of server development, and that **strong organization—not mere headcount—is the primary vector for power**. As a result, the server naturally promotes and elevates groups that demonstrate genuine coordination and contribution.

---

### Foundational Guild Growth & Leadership Legacy

It is fully possible—and entirely intended—that a solo player or a small group could develop a guild's early GSQs, unlock valuable skill trees, and later open the guild to new recruits. This raises the question of whether new members are gaining access to perks they didn’t help earn.

The answer lies in the system’s balance of effort and accessibility. Founders who develop guilds solo are putting in significant effort and are forgoing the benefits of group collaboration. Any new member joining after the fact still has to:

- **Earn their own Tree Level (TL)** through GQs
    
- **Invest GP to access skill trees**, with all associated tradeoffs
    
- **Contribute Guild Tokens** to access or unlock future GSQs
    

There is no free power handed to newcomers. They join a well-founded organization and must contribute meaningfully to continue its progression. Conversely, founders receive social prestige and leadership position as a reward for early commitment.

This is not a loophole, but a healthy gameplay loop that mimics how real organizations grow. Successful guilds naturally attract others, and their leadership legacy becomes part of the world’s evolving history.

---
### Tree Access in Multi-Guild Membership

When a player belongs to multiple guilds that share the same skill tree, a consistent rule is needed to determine what perks and progression that player can access. Since players only have one Tree Level (TL) and one Tree Skill Point (TSP) pool per skill tree, overlapping guilds must not enable duplication or exploitation.

This section defines how **TSP usability** and **skill unlocks** are governed when multiple guilds share a tree.

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

- **Guild A** — 3 GP invested, Rank A
    
- **Guild B** — 1 GP invested, Rank A
    

Guild A determines the TSP cap due to higher GP investment.

If later:

- **Guild A** remains at Rank A
    
- **Guild B** increases to Rank S
    

Then Guild B becomes the controlling guild. The player's usable TSP will be based on the **1 GP invested in Guild B**, potentially deactivating some previously used skills. These skills remain allocated but become **inactive**, similar to what happens when a player is demoted and their TSP exceeds the new GP limit.

This dynamic encourages players to remain meaningfully invested in the guilds they wish to benefit from.


---
### Addressing Contract Abuse & Transparency

The Guild Contract system introduces formal agreements for membership, rank, and GP investment, creating a strong roleplay and structure layer. However, any such system involving human decisions must anticipate misuse—not necessarily through bugs or exploits, but through misaligned intent or social conflict.

Some potential abuse scenarios include coercive onboarding, arbitrary demotion, or using contracts as a tool for social control. However, these are not design flaws—they are **social dynamics** best resolved through transparency and player autonomy.

#### Why the System Holds

- **Tree Level (TL) is permanent**: A demoted or ejected player retains their TL, meaning their progress isn't lost and can be leveraged in future guilds.
    
- **Contracts are transparent**: Public logs and preview windows ensure players know what they’re agreeing to.
    
- **Leaving is always an option**: No contract can trap a player; they can walk away with their TL intact.
    
- **Guilds gain nothing from power abuse**: There is no mechanical benefit to demoting a player arbitrarily. Doing so hurts the guild’s progression and damages its reputation.
    

If leadership is toxic or petty, it will naturally **burn talent and decay**—not due to punitive mechanics, but because the system **rewards contribution and discourages passivity**. Guilds that don’t foster fairness or loyalty will falter over time.

The only cases where intervention may be necessary are when:

- **Bad-faith actors mislead new players** through deceptive onboarding.
    
- **Repetitive social abuse patterns** emerge from the same leadership group.
    

In such cases, server staff can intervene through a **formal arbitration process** to mediate disputes or impose corrective measures.

This approach helps keep guild life immersive and meaningful, while safeguarding players from predatory practices—without diminishing the depth and agency of emergent social structures.

---

### Addressing Alt Account Concerns

A commonly raised concern in multiplayer systems is the potential for alt account abuse—particularly scenarios where a single player might create multiple low-GP characters to generate Guild Tokens through easy quests.

However, the Towns & Guilds system is inherently resilient to this type of abuse by design. Guild Tokens are:

- **Bound to the issuing guild**, meaning they cannot be used to progress another guild.
    
- **Only meaningful within the originating guild’s GSQ system**, which requires substantial, structured contribution.
    
- **Produced through real quest activity**, meaning any alt must actually perform work to generate tokens.
    

Furthermore, by creating alts to simulate a multi-member guild, the player loses access to the powerful **GP-based scaling bonuses** designed for solo and small guild play. In practice:

- A solo guild can access up to a 70% GSQ token reduction.
    
- A multi-alt guild immediately invalidates that bonus and must pay full cost.
    

This makes multi-account farming **less efficient** than simply playing actively on one account. Real guildmates generate more varied and useful token types (e.g., B or A), progress higher-scope quests, and can fulfill collaborative goals more effectively.

The **structure and scaling of the game itself reward authentic participation** and make any attempt at gaming the system through alts a suboptimal strategy.

---

### Cross-Guild Interaction and Land Agreements

While cross-guild collaboration is not a formalized mechanic, the system is intentionally designed to support organic interactions between guilds through towns, shared infrastructure, trade, and diplomacy. Most collaboration will naturally occur within the town environment where guilds coexist, participate in events, or align their interests around construction, commerce, and influence.

Rather than hardcoding alliance systems, Towns & Guilds encourages these relationships to emerge **organically through the existing contract framework**. Guilds, towns, or players can establish their own treaties, agreements, and collaborations using customized contract types.

To support this, a new category of contracts—**Land Agreements**—may be issued to represent property claims, rentals, leases, or co-ownership deals. These contracts would include metadata specifying:

- **Land zone or coordinates**
    
- **Type of agreement** (purchase, rental, shared usage)
    
- **Recurrence terms**, such as rent payment cycles
    
- **Contractor and client permissions**
    

If a land contract involves a **recurring payment**, it becomes the contractor's responsibility to ensure payments are made. The contract UI will track overdue payments and, after a defined grace period, enable the contractor to **rescind the agreement**. When this happens, ownership of the land is unclaimed and transferred back to the contractor.

This approach supports a broad variety of real-world scenarios:

- Renting a house or workshop from a merchant guild
    
- Selling territory between towns
    
- Managing tenant agreements in a shared guild compound
    
- Diplomatic land swaps or protectorate arrangements
    

These land contracts make it possible for **guilds and players to simulate real, meaningful economic and territorial relationships** without the need for extra mechanical layers. The immersion comes from the social structure, while the system simply enforces the agreed-upon terms.

## **Glossary**

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

---
# Player Skills

**Player Skills** are part of a standalone skill system that exists independently from the Towns & Guilds specialization system. It allows players to unlock a broad set of general-purpose convenience skills—such as QoL improvements—without encroaching on the more focused, role-defining abilities provided by guilds.

# PokéDungeons

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
    

### Encounter Synchronization & Quest Target Handling

To maintain fairness while avoiding instancing, PokéDungeon encounters—including bosses and quest-specific targets—use a **shared-world conditional spawn and interaction system**.

### Shared Target and Boss Logic

- When a player who meets the encounter or quest condition enters a relevant area, the target (boss, NPC, or special Pokémon) is **spawned**.
    
- These targets are **not exclusive** to the player who triggered the spawn but can only be meaningfully interacted with by **eligible players**.
    
- Combat or interaction is validated against the player's **active objective state**, preventing unqualified players from hijacking progression.
    
- Targets despawn after being defeated, and a **brief cooldown phase** begins.
    
- Once the cooldown ends, the system checks if any other qualified players are still nearby and **spawns the target again** for the next eligible player.
    
- Additionally, the system should **periodically check** whether any eligible players are still present in the area. If no qualifying players remain—for example, if a player enters and then leaves without completing the objective—the spawned target should **despawn** to prevent lingering, unused encounters.
    

### Synchronization Safeguards

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

# Dungeons

**Dungeons** are similar to PokéDungeons, but instead of a Pokémon theme, they follow a fantasy adventure style, featuring monsters, bosses, and traditional dungeon-crawling challenges.
# NPC Quests

**NPC Quests** are questlines designed to engage players through immersive storytelling and interactions with the world and its characters.
# FTB Quests

**FTB Quests** are UI-based quests organized into categories (chapters), each containing specific goals for players to complete. They are primarily used to guide players through the mechanics of various gameplay niches, mods, and server systems, ensuring a smooth and informative experience without reliance on external resources.

### Overall Goals of FTB Quests:

- **Comprehensive Onboarding:** Provide a clear and structured introduction for new players to Minecraft, the Cobblemon Pokémon experience, core modpack mechanics, and essential server features.

- **Self-Contained Guidance:** Design quests with detailed descriptions, clear objectives, and all necessary information embedded within the quest book UI. The aim is for players to understand and complete tasks **without needing to consult external wikis or websites.**

- **Feature Introduction:** Systematically introduce players to all major gameplay elements, including Pokémon catching and battling, crafting systems, Level Caps, custom mods (like Enhanced Pokémon Backpacks and Additional Pokémon Items), the Towns & Guilds system, specific mods like Create, Farmers Delight and Refined/Sophisticated Storage, dimensional exploration (Aether, The Otherside, Mining Dimension), and more.

- **Skill Development:** Gradually teach players the skills and knowledge required to thrive, from basic survival and Cobblemon training to complex automation and interdimensional travel.

- **Promote Engagement:** Encourage exploration, experimentation, and interaction with the server's unique content through rewarding questlines.

- **Accessibility:** **All quest text will be translated into the most popular languages of our player base** to ensure the content is accessible and understandable to a wider audience.

### Proposed FTB Quest Chapter Themes:

The quest book will be divided into thematic chapters, allowing players to focus on areas of interest or follow a natural progression:

1. **Getting Started! (Cobblemon & Modpack Basics)**
    - Covers basic movement, controls, UI navigation.
    - First steps in the world: gathering basic resources, simple crafting.
    - Understanding foundational mods like our Currency System.
    - Introduction to Cobblemon: your first Pokémon, how to catch, basic battling mechanics, using the Pokédex.

2. **Your Trainer Journey Begins (Cobblemon Fundamentals)**
    - Cobblemon typing, strengths, and weaknesses.
    - Leveling up Pokémon, understanding stats, and evolution.
    - Crafting basic Pokémon items (e.g., Potions, standard Poké Balls).
    - Using your first Pokémon-specific tools (e.g., Basic Trainer's Pouch).

3. **Surviving and Thriving (World Interaction & Vanilla Progression)**
    - Food and hunger management. (**introduce Farmers Delight, Spice of Life,** etc.)
    - Building a basic shelter and understanding base security.
    - Introduction to Player Skills (if applicable early on).
    - Navigating different Overworld biomes and their unique Cobblemon.

4. **The World of Pokémon Gear (Custom Items & Tools)**
    - Crafting and using the tiered **Enhanced Pokémon Backpacks**.
    - Introduction to **Additional Pokémon Items & Resources** (new held items, consumables, etc.).
    - Utilizing specific item functionalities (e.g., Repel Sprays, Encounter Lures).

5. **Automated Ingenuity (The Create Mod)**
    - **Kinetic Foundations:** Introduction to Create's rotational power: Water Wheels, Windmills, Cogwheels, Shafts.
    - **Basic Processing:** Crafting and using the Mechanical Press, Millstone, and Mixer for automated resource processing.
    - **Item Transportation:** Utilizing Encased Fans, Chutes, Belts, and Funnels for basic item logistics.
    - **Advanced Mechanisms (Overview):** Brief introduction to more complex Create concepts like Mechanical Crafters, trains, and logic circuits, pointing towards player experimentation.
    - **Create Addons**: Dive into some of the other create sidemods included such as; Integrated Kitchen, Enchantment Industry, etc.

6. **Digital Order (Storage Solutions & Refined Storage)**
    - **Vanilla Organization:** Mastering chests, barrels, hoppers, and simple item sorters.
    - **Introduction to Digital Storage:** Setting up a basic `Refined Storage` system: Controller, Grid, Disk Drive (with small storage disks), and Crafting Grid.
    - **Basic Autocrafting:** Learning to teach the system recipes using the Crafting Grid and Pattern Grid.
    - **Network Expansion (Overview):** Introduction to cables, Importers/Exporters, and wireless access, encouraging further exploration.

7. **Community and Collaboration (Towns & Guilds Primer)**

    - Introduction to the concept of Towns and their importance.
    - How to join or found a Guild (covering the basics of Guild Contracts and the Initiate role).
    - Understanding Guild Points (GP), Tree Skill Points (TSP), and introductory Guild Quests (GQs).
    - The role of Guild Tokens (GT) at an entry-level.


8. **The Aspiring Artisan (Crafting Professions via Guilds - Examples)**
    
    - _This chapter might have sub-chapters or be one of several, depending on guild focuses._
    - Focuses on a specific Guild's crafting-related skill trees (e.g., a Guild specializing in Poké Ball crafting, technical item creation, or potion brewing).
    - Guides players through relevant GQs and GSQs for that profession.


9. **The Dedicated Breeder (Cobblemon Breeding)**

    - Detailed guide on Cobblemon breeding mechanics available on the server.
    - Quests on achieving specific breeding outcomes (IVs, Natures, Egg Moves, Hidden Abilities).
    - Crafting and using breeding-assisting items.


10. **Mastering the Battle (Advanced Cobblemon Combat)**

    - Strategies for more challenging battles.
    - Understanding EV training, Natures, and advanced team composition.
    - Utilizing status moves, entry hazards, and weather effects.
    - Introduction to competitive battling concepts.


11. **Dimensional Explorer (Venturing Beyond)**

    - **The Nether Depths:** Surviving the Nether, finding Nether Fortresses, gathering unique resources (Nether Wart, Blaze Rods, Ancient Debris). Nether-native Cobblemon.
    - **The End's Expanse:** Reaching The End, defeating the Ender Dragon, exploring End Cities, obtaining Elytra. End-native Cobblemon.
    - **The Aetherial Skies (The Aether Mod):**
        - Crafting the Aether Portal and first steps into the Aether.
        - Exploring Aether biomes (e.g., Highlands, Holystone Caves, Skyroot Forests).
        - Encountering Aether mobs (Moas, Aerwhales, Cockatrices, Swets) and Aether-adapted Cobblemon.
        - Introduction to Aether Dungeons (Bronze, Silver, Gold) and their unique loot/Pokémon.
    - **The Otherside (Deeper Dark Expansion):**
        - Preparing for and braving the Deep Dark biome ("The Otherside").
        - Strategies for dealing with Sculk Shriekers, Sensors, and the Warden.
        - Exploring Ancient Cities and their treasures.
        - Discovering Cobblemon adapted to the extreme darkness or unique to this dimension.
    - **The Mining Dimension (AllTheModium Mod):**
        - Crafting the portal or method to access the Mining Dimension.
        - Introduction to mining for AllTheModium, Vibranium, and Unobtainium.
        - Navigating unique geological features and potential hazards.
        - Quests for finding specific ore veins or quantities.
        - Potential for unique Cobblemon adapted to this resource-rich dimension.

12. **Adventurer's Compendium (Collection & Discovery)**
    
    - **Flora of the Worlds:**
        - Overworld Saplings & Crops: Collect one of every type of sapling and successfully cultivate every crop from Overworld biomes.
        - Nether Flora: Collect unique Nether fungi and plants.
        - End Flora: Collect Chorus Fruit and other End-specific plants.
        - Aetherial Botany: Collect Aether saplings (e.g., Skyroot, Golden Oak) and Aether-specific crops/plants.
        - Otherside Organisms: Collect any unique flora found in The Otherside.
        - Mining Dimension Minerals: (state changed ore rates and locations)
    - **Biome Atlas:**
        - Visit and document (perhaps via a screenshot quest, specific block interaction, or an "Atlas" item) every biome in:
            - The Overworld
            - The Nether
            - The End
            - The Aether
            - The Otherside (Deep Dark and its sub-biomes if any)
            - The Mining Dimension
    - **Structural Cartographer:**
        - Discover and explore key generated structures in each dimension (e.g., Overworld Villages/Temples/Ocean Monuments, Nether Fortresses/Bastions, End Cities, Aether Dungeons/Villages, Ancient Cities, etc.)

13. **Monster Hunter's Manual (Mob Eradication & Farming)**
    
    - **Vanilla Hostiles:** Defeat X number of each common Overworld, Nether, and End hostile mob (Zombies, Skeletons, Creepers, Spiders, Endermen, Blazes, Ghasts, etc.).
        - **Reward:** Upon completing a quota for a specific mob, award the player with that mob's **MobCard from the Easy Mob Farms mod**, blocks/nuggets of experience.
        
    - **Aetherial Foes:** Defeat X number of each Aether-specific hostile mob (e.g., Hostile Moas, Cockatrices, Valkyries, Sentries).
        - **Reward:** Relevant Aether MobCards, blocks/nuggets of experience.
        
    - **Dimensional Threats:** Defeat X number of any unique hostile mobs in The Otherside (e.g., Warden - though this might be a special challenge rather than a quota) or the Mining Dimension.
        - **Reward:** Relevant MobCards, blocks/nuggets of experience.
        
    - **Farming Fundamentals:** Quests guiding players to set up basic mob farms (perhaps using vanilla mechanics or simple `Easy Mob Farms` setups if the mod allows for guided creation), explaining spawning mechanics and collection.

14. **Dungeon Delver (PokéDungeons & Other Dungeons)**
    
    - Preparing for your first **PokéDungeon** or other modded/custom **Dungeon** run.
    - Understanding the mechanics (floor progression, blackout, boss battles).
    - Tips for survival and Cobblemon team strategies for dungeons.
    - Rewards and unique Pokémon/items found within.

15. **The Path to Champion (Seasonal Pokémon League Intro)**
    
    - Explaining the **Seasonal Pokémon League** structure.
    - How to challenge player-operated Gyms.
    - Earning badges and qualifying for the League Tournament.

16. **Advanced Mod Systems (Deep Dives)**
    
    - This chapter provides in-depth questlines for mastering complex mods that offer significant new gameplay systems. Quests will guide players from initial setup to advanced functionalities and automation.
    - **Examples of mods to be covered:**
        - **Ars Nouveau:** Spellcrafting, magical automation, enchanting, ritual systems.
        - **Apotheosis:** Advanced enchanting mechanics, mob spawner modification, boss enhancements, unique affix gear.
        - **MineColonies:** Building and managing your own thriving colony, citizen management, research, and town development.
        
        - _(Other mods of similar complexity present in the modpack would also be featured here.)_

Each quest will clearly state its objectives, provide hints or context if necessary (e.g., "To power your first Create contraptions, try building a Water Wheel next to a flowing water source and connect it with Shafts."), and offer appropriate rewards that aid progression (e.g., items, currency, experience, Cobblemon encounters, or even unlocking the next set of quests). This detailed, in-game guidance system will be pivotal in making the modpack accessible and enjoyable for everyone.



# Dynamic Events

**Dynamic Events** are limited-time activities designed to inject excitement, foster community interaction, and offer unique challenges and rewards in parallel with regular content updates and major features like new PokéDungeon releases. These events are typically short-lived (ranging from a few hours to a full week) to encourage active participation and make their exclusive rewards feel valuable. The core philosophy is to provide engaging content that breaks the routine and gives players memorable experiences and distinct goals.

### Key Features & Mechanics:

- **Variety of Event Types:**
    
    - **Cobblemon Community Focus Days:**
        - **Featured Pokémon:** Each event will spotlight a single, specific Pokémon species.
        - **Massively Increased Spawns:** The featured Pokémon will appear much more frequently in the wild globally, or in designated, widespread biomes, for a dedicated block of hours (e.g., 3-6 hours on a weekend day).
        - **Increased Shiny Chance:** During the event hours, there will be a significantly increased probability of encountering a shiny version of the featured Pokémon.
        - **Event Bonuses:** Additional potential bonuses during these hours could include increased Pokémon XP, reduced egg hatching distance (if applicable), changes to the fishing spawn pools, or special Field Research-style tasks focused on the featured Pokémon.
        - **Advance Announcement:** These Community Focus Days will be announced well in advance to allow players to prepare (e.g., stock up on Poké Balls, clear Pokémon storage).
    - **World Boss Encounters:** A formidable, custom-designed "World Boss" (could be a giant, uniquely powerful Pokémon variant or a completely custom creature) spawns at a predetermined time and location. Defeating it requires a server-wide collaborative effort, with rewards scaled by participation, damage contribution, and successful takedown.
    - **Themed Treasure Hunts:** Server-wide hunts involving riddles, parkour, exploration clues scattered across multiple dimensions, leading to hidden stashes of valuable loot, event tokens, or unique collectibles.
    - **Limited-Time Dungeons:** Special, non-PokéDungeon instances appear for the event's duration. These dungeons would feature custom layouts, unique mobs (potentially event-themed reskins of existing mobs or new custom ones), challenging bosses, and exclusive loot tables (e.g., event currency, rare crafting materials, specific event-themed Pokémon).
    - **Community Challenge Events:** Server-wide objectives are set (e.g., "Collect 1,000,000 Cobblestone," "Catch 5,000 Pokemon," "Plant 10,000 Saplings across all towns"). Upon completion by the community, a global reward, a temporary server-wide buff (e.g., increased Pokémon XP, better loot from PokéStops), or a new temporary feature is unlocked for everyone.
    - **Holiday & Seasonal Celebrations:** Special events themed around real-world holidays or significant seasonal changes (distinct from the Seasonal Pokémon League). Examples:
        - **Halloween Haunt:** Ghost-type Pokémon focus, spooky-themed areas with temporary quests, and cosmetic costume rewards.
        - **Winter Festival:** Ice-type Pokémon focus, gift-exchanging systems, decorative town contests, and chances to find rare winter-themed items.
    - **Town-Hosted Mini-Festivals:** The server may provide support (e.g., kits with decorative blocks, temporary NPC vendors, minor prize support) for player towns to organize their own local events like fishing contests, building competitions, or small-scale Pokémon tournaments, fostering town identity and community spirit.
    - **Fishing Derbies & Bug Catching Contests:** Timed competitions to catch the largest, rarest, or most of a specific type of fish or bug-themed Pokémon, with leaderboards and prizes.
    - **Themed Building Contests:** Server-announced themes (e.g., "Best Pokémon Gym Design," "Most Innovative Redstone Contraption"), with designated areas or plot worlds for building, judged by staff or community vote.


- **Reward Structures:**
    
    - **Event Currency/Tokens:** Earned by participating in event activities, redeemable at a special event vendor for exclusive items.
    - **Exclusive Collectibles:** Time-limited items such as custom-textured tools/weapons (cosmetic), event-specific trophies (placeable furniture), unique banner patterns, titles, or collectible coins/medallions with high in-game trade value.
    - **Event-Themed Pokémon:** As detailed in Custom Mods, Pokémon with unique event-specific textures, minor cosmetic accessories (e.g., a party hat), or occasionally a special non-advantageous move (like "Celebrate"). These would not be breedable with their special textures/accessories to maintain rarity. This is especially relevant for Community Focus Day Pokémon.
    - **Cosmetic Gear:** Unique armor sets (cosmetic only, perhaps using armor stand mods or similar), hats, particle effects, or custom-designed non-PokéBag backpacks.
    - **Rare Resources & Items:** Enhanced chances to obtain rare crafting materials (e.g., AllTheModium ores), high-tier enchantment books, Ability Patches/Fragments, or even Guild Gems.
    - **Guild & Town Incentives:** Bonus Guild Points for collective guild participation, resources for Guild HQ development, or special recognition/trophies for towns that excel in community events or festivals.


- **Engagement & Accessibility:**
    
    - **Event-Specific Questlines:** Short FTB Quest lines will be available to guide players through the event's activities, explain its mechanics, and offer baseline participation rewards.
    - **Announcements & In-Game Calendar:** Clear communication about upcoming and active events via in-game broadcasts, a visible event calendar/bulletin board UI, and Discord announcements.
    - **Leaderboards & Recognition:** For competitive events, visible leaderboards will track top performers, who will be publicly recognized and rewarded.
    - **Translation:** Key event information and questlines will be translated to ensure accessibility for the diverse player base.

- **Frequency & Duration:** A general cadence might involve one major weekend event (like a Limited-Time Dungeon or World Boss) per month, with one **Cobblemon Community Focus Day** also occurring monthly on a different weekend. Smaller, more frequent occurrences could happen for a few hours on different days to cater to various time zones.
    

# Seasonal Pokémon League

The **Seasonal Pokémon League** is a premier, recurring competitive structure designed to test the mettle of Pokémon trainers and foster a dynamic, player-driven competitive scene. Tied to real-world seasons (Spring, Summer, Autumn, Winter), each League season offers a fresh start, new challenges, and the ultimate goal of crowning a server Champion.

### Core Structure & Progression:

1. **Seasonal Reset & Theme:**
    
    - At the start of each season, League progress (badges, rankings from the previous season) is reset, offering a level playing field.
    - Each season may feature a subtle thematic twist. This could involve encouraging Gym Leaders to incorporate specific Pokémon types or battle styles relevant to the season, or introducing minor, lore-friendly environmental effects in official League battle arenas. For example, a "Summer Scorcher" season might see more Sun-based teams.

2. **Player-Operated Gyms:**
    
    - **Authorization & Application:** Players can apply to become official Gym Leaders for a town. Requirements typically include a strong understanding of Pokémon battling, a commitment to a specific type or theme for their gym, an established presence/building within a recognized Town, and passing a qualification trial by League officials (staff or designated players).
    - **Gym Leader Responsibilities:** Maintain their designated gym, be available for challenges during set "Gym Hours" or by appointment, adhere to official League rules, and represent their Town and the League with sportsmanship.
    - **Gym Rules & Regulations:** A standardized set of rules will govern all official Gym battles, including Pokémon level caps (which may scale slightly as the season progresses), limitations on certain items or legendary Pokémon, and the number of Pokémon allowed per battle (e.g., 6v6 singles, 3v3 singles, doubles, etc.).
    - **Badge System:** Successful challengers earn custom-designed, physical (or digital via Trainer Card) Badge items specific to that Gym and season. These are required to qualify for the end-of-season tournament.

3. **Earning Badges & Qualification:**
    
    - Players travel the world, challenging the 8 (or a set number) authorized player-operated Gyms located in various Towns.
    - Collecting the required number of unique badges by the season's deadline qualifies a trainer for the Championship Tournament.

4. **Seasonal Championship Tournament:**
    
    - **Format:** A multi-stage tournament, typically single or double elimination, with matches being best-of-three (or best-of-five for finals).
    - **Seeding:** May be based on the order of qualification, a League Points system (see below), or random draw.
    - **Battle Arenas:** Tournament matches will be held in specially designed, impressive arenas. This could be a central "League HQ" complex, or arenas could rotate between prominent, well-developed Towns that meet certain criteria.
    - **Live Spectating & Casting (Optional):** Important matches might be streamed or spectated in-game by the community, potentially with player "casters" providing commentary.

### Advanced Features & Engagement:

- **League Points & Ranking System:**
    - Beyond just badges, players could earn "League Points" (LP) for defeating Gym Leaders, with bonus points for overcoming higher-ranked or more challenging gyms.
    - A visible seasonal leaderboard would track trainers by LP, fostering ongoing competition even before the final tournament and potentially influencing tournament seeding.
    - Minor rewards or titles could be distributed at mid-season milestones based on LP rankings.

- **Gym Leader Gauntlets & Special Challenges:**
    - Periodically, "Gym Leader Gauntlet" events could allow qualified trainers to challenge multiple Gym Leaders consecutively for bonus rewards or prestige.
    - "Elite Four" style challenges could be implemented as a precursor to the Champion battle, where top tournament players face a series of extremely skilled NPC or designated player teams.

- **Off-Season Activities:**
    - A designated period between seasons for Gym Leader applications, evaluations, and re-authorizations.
    - Pre-season exhibition tournaments or "Rookie Cups" for newer players.
    - Workshops or training sessions hosted by experienced players or former champions.

### Rewards & Recognition:

- **Champion:**
    - The coveted title of "Server Champion" for the season (with a unique chat prefix/color).
    - A physical trophy/statue erected in a Hall of Fame or the Champion's Town.
    - An extremely rare Pokémon (e.g., a pseudo-legendary with a guaranteed custom Champion's texture, perfect IVs, or unique cosmetic move).
    - A significant sum of in-game currency, Guild Gems, and other high-value items.
    - The Champion's input might be sought for minor thematic elements of the next season.

- **Tournament Finalists & Top Ranks (e.g., Top 4, 8, 16):**
    - Generous prizes including currency, rare items (Ability Patches, unique TMs, Master Balls), custom-textured Pokémon (non-Champion exclusive), and cosmetic gear.
    - Lesser titles or public recognition.

- **Gym Leaders:**
    - Successful and active Gym Leaders receive stipends of in-game currency or resources, unique cosmetic items identifying their role, and prestige within the community.
    - Top-performing or most innovative gyms might receive special commendations.

- **Participation Rewards:**
    - All trainers who qualify for and participate in the Championship Tournament will receive a seasonal participation memento (e.g., a unique banner, a small amount of event currency, a participation badge for their Trainer Card).
- **Seasonal Cosmetic Trophies:** Placeable trophy items for winners and high-ranking participants, unique to each season, to display in their homes or guild halls.

The Seasonal Pokémon League aims to be the pinnacle of competitive Pokémon play on the server, encouraging continuous improvement, strategic team building, and active community involvement across multiple towns and player groups.


# Custom Mods & Content

**Custom Mods** are developed in-house to address specific gameplay needs, enhance the player experience, and add an additional layer of polish and depth to the overall modpack. These bespoke modifications are designed to seamlessly integrate with each other and existing Cobblemon-centric gameplay, creating a unique and cohesive adventure.

### 1. The Modified Experience (Core Integration & GUI Mod)

This central mod acts as the primary interface and integration hub for many of the modpack's unique features and custom systems. Its main purpose is to provide players with a streamlined way to access critical information and interact with various gameplay elements through a custom, user-friendly GUI.

- **Custom Main GUI Features:**
    
    - **Information Hub:** A unified interface to access:
        - **Dungeon Information:** Details on available PokéDungeons and other dungeons, including types, recommended levels, and potential unique loot.
        - **Event Information:** A calendar and description for current and upcoming server events (from the `#Running Events` system), including objectives and special rewards.
        - **Trainer & Gym Information:** Displays player's current Pokémon team level caps, personal trainer stats (like PokéDollar balance), and detailed information on recognized Gyms (player-operated from the `#Seasonal Pokémon League`), their types, leaders, if they are accepting battles, active hours, or if there are any specific challenge rules.
        - **Server & Modpack Info:** Quick access to server rules, links to important community platforms, and basic guides or version info for key mods.
        
    - **Player Interaction:**
        - **Trainer Battle Interface:** A system for players to easily find and initiate battles with other trainers, potentially including a challenge list, elo/ranking display, or quick battle options.
        
    - **Quick Access & Utility:**
        - **PokéBag Hotkey Integration:** Provides the functionality for a dedicated hotkey to directly open the player's PokéBag (from the separate PokéBag Mod).
        - **PokéDollar Balance Display:** Clearly shows the player's current in-game currency.

- **System Integration & Compatibility:**
    - This mod will be crucial for ensuring seamless interaction between different complex systems:
    
        - **Towns & Guilds System:** "The Modified Experience" will house the UI elements and integration logic necessary for players to interact with the custom Guild system, its skill trees, and the Guild Quest (GQ) and Guild Skill Quest (GSQ) framework detailed in the `#Towns & Guilds` section.
        - **Contract System:** The interface for creating, viewing, and managing player-to-player and guild-related contracts (as defined in `#Towns & Guilds`) will be managed through this mod.

- **Pokémon Item Additions & Reimplementations:**
    - "The Modified Experience" will also be the vehicle for introducing a variety of Pokémon items not yet implemented in Cobblemon or new custom items to enrich gameplay. These will be designed to integrate with other systems like Guilds, crafting, and exploration. Examples include:
    
        - **New Held Items:** Items that offer unique passive effects in battle or during training.
        - **New Consumables & Craftables:** Utility items for trainers in the field (e.g., "Portable Pokémon Healer Kit," stronger "Repel Sprays/Incense," type-specific "Encounter Lures," "Ability Patch Fragments" for crafting).
        - **Specialized Crafting Ingredients:** Unique materials needed for high-tier items, guild upgrades, or module crafting for the PokéBag, encouraging engagement with various aspects of the modpack.
        - **PokeStops, Lures, Etc**: Reimplementing various items from other games such as PokemonGo

### 2. Dungeon System 

 These systems and resources will be crucial for our gameplay, housing many of the systems for the features discussed in this document to come to fruition.

- **Custom Blocks & Items**
	- Includes the dungeon keys, portal blocks, and any other blocks required for the dungeons to function 

- **Portal Resources**
	-  Dynamic portal textures, and sounds depending on the dungeon its used to travel to.

- **Showdown Changes**
	 - Possible changes and additions to the Cobblemon Showdown system, possibly required for the boss tier of mon in development

### 3. Custom Pokémon Textures

This mod (or integrated feature set) aims to introduce a wider variety of visual appearances for Pokémon beyond their standard and shiny forms, enhancing the collectability and visual diversity of Cobblemon.

- **Purpose:**
    - **Enhanced Collectibility:** Provide players with more unique Pokémon to find, train, and show off.
    - **Visual Diversity:** Make the Pokémon world feel richer and more varied.
    - **Event Rewards:** Offer special textured Pokémon as prizes for participating in Running Events or Seasonal Pokémon League tournaments.
    - **Rare Variants:** Introduce textures that are exceptionally rare, like "Albino," "Melanistic," biome-specific camouflage patterns (e.g., "Desert Rattata," "Arctic Pikachu"), or even "Retro" pixel-art inspired textures, found in the wild or through specific, challenging breeding achievements.
    - **Non-Intrusive:** These textures would be purely cosmetic and offer no gameplay advantages, preserving competitive balance. They would be an additional layer for collectors and those who appreciate visual flair. Integration with "The Modified Experience" GUI could allow players to see a "Texture Dex" or similar.

### 4. Event-Themed Pokémon

This mod or feature set allows for the introduction of Pokémon with special themes tied to server events (as detailed in `#Dynamic Events`), holidays, or ongoing server story arcs.

- **Features:**
    - **Unique Appearances:** Pokémon might receive temporary or permanent custom textures fitting the event (e.g., a pumpkin-themed Pikachu for Halloween, a flower-crowned Eevee for a Spring festival). They might also feature minor, non-obtrusive cosmetic accessories (if technically feasible) or unique particle effects.
    - **Special Moves (Cosmetic/Thematic):** Rarely, an event Pokémon might know a specific, thematically named move. If it has a unique battle effect, it would be a balanced, existing move re-skinned for the event, or a purely cosmetic move like "Celebrate" or "Happy Hour."
    - **Limited Availability:** These Pokémon would primarily be obtainable only during the specific event they are tied to, increasing their rarity and value as collectibles.
    - **Story & Quest Integration:** Event-themed Pokémon could play a role in temporary `#NPC Quests` or the narrative of a running event, making their appearance feel more integrated into the world.
    - **Collection Challenges:** Events could feature short-term collection challenges or Pokédex-style objectives centered around finding and cataloging these event-themed Pokémon, with rewards for completion. These would also be visible through "The Modified Experience" event UI.

### 5. PokéBag Mod (Standalone Utility Mod)

This mod introduces a dedicated inventory solution for Pokémon trainers, designed with thematic accuracy and ease of use in mind. It is intended to be a focused mod that can be utilized by the broader Cobblemon community in other modpacks as well.

- **Single Tier, Modular Design:**
    - There will be one primary "PokéBag" item. Its functionality is expanded not through tiered crafting of new bags, but by acquiring and installing distinct **Modules**.
- **Pokémon Game Inspired Interface:**
    - The bag's GUI will closely mimic the interface seen in the mainline Pokémon games.
    - Items will be automatically sorted into logical categories within the bag, each accessible via clear tabs or sections:
        - **Medicine Pocket:** For Potions, Status Healers, Revives, etc.
        - **Poké Balls Pocket:** Organizes all types of Poké Balls.
        - **TMs/HMs Pocket:** Stores Technical and Hidden Machines.
        - **Berries Pocket:** Dedicated space for all collected Berries.
        - **Key Items Pocket:** For important progression-related items, ensuring they are not accidentally discarded. 
        - **Battle Items Pocket:** For X-items, Dire Hits, Guards Specs etc.
        - **Treasures/Valuables Pocket:** For items primarily meant to be sold (Nuggets, Stardust, etc.) or rare collectibles.
        - **Held Items Compartment:** A section specifically for managing Pokémon Held Items.
- **Module Acquisition & Progression:**
    - While the base PokéBag might be relatively easy to obtain or craft, many of its specialized **Modules** (which unlock or expand specific pockets/features, or add new functionality like an integrated Egg Incubator slot or a Bait & Lure Satchel) will be locked during initial gameplay.
    - These modules will primarily be obtained as rewards from completing specific NPC quests, storyline milestones, or challenging dungeons, providing a clear progression path for enhancing the bag's utility.
- **Standalone & Sharable:**
    - Developed as an independent mod, allowing other Cobblemon modpack creators to easily incorporate it if they wish, promoting a common, high-quality utility for the community.