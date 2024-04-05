[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Felicity Nop
### Student number: 47681837

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.





Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)

### 1.1. Discovery
My level design scaffolds discovery of the key concepts and verbs I wanted to highlight - 'push' boxes and 'open' doors/bridges - through effective use of space to indirectly guide the player, and through teaching simple solutions then problematising them.

The main verbs are introduced in section 1. The encounter space was designed such that the player must ‘push’ the box forward to progress (cannot jump over), teaching them the activate button -> open bridge mechanic. 
Section 3 is the cumulation of sequential switch activations to 'open' and 'close' multiple doors as well as a multi-staged box 'push'. The arrangement of encounters in that part of the level creates a memorable space, with the “next” objective/door visible on the player’s screen. The more challenging scenario using previously-taught verbs forces discovery and mastery of switch mechanics, and facilitates the development of problem solving dynamics.
Originally, the plan was to use bridges instead of doors, as I believe the toggle state doors conflict with the idea that "doors will close if the button isn't held down", but mechanics limitations changed this.

Additionally, the player’s initial confusion about the column blocking the right of the starting area is resolved after completing section 1 and discovering the ‘attack to break column’ mechanic, providing them with an “I know how to get through now!” moment as a reward for completing section 1 and an incentive to continue.


pic: pushbox1 pushbox2
swtich1 switch2 switch3


### 1.2. Drama
The overall intensity curve holds section 1 as the hook, as the player learns different mechanics and dynamics through interesting encounter design. Section 2 represents the rising action, as there is a specific sequence of actions required to complete the smaller section, and figuring out each encounter contributes towards moments of achievement. Section 3 represents the climax, as it is the most challenging part of the level and has the most complexity.

Every encounter in the level is different, introducing some novel mechanic or dynamic, avoiding boredom by repetition. Higher intensity encounters in sections 1 and 2 are connected to “safe” areas, allowing for dips and bumps in the experiential intensity curve.

The transition between sections 2 and 3 is a shift from tight underground space to a more open floating space to emphasise the shift between sections. This connecting space is intentionally long and simple to create resonance, allowing the player to feel the satisfaction of completing the last puzzle, and facilitating a moment of respite before the upcoming tension.

The forked path and spike drop at the entrance of section 3 were designed so the player has incomplete knowledge of what lies ahead (cannot see what is below the drop or above the high path), stimulating their curiosity to explore and discover despite the possibility of danger. This, along with some randomness of the spitter attacks and the moving platform timings, creates uncertainty and tension. Tension is also created through the scarcity of health pickups and checkpoints (rewards) compared to the many threats (penalties), forcing the player to consider the risks of their actions.

Pic: paths (can’t see below or above)



### 1.3. Challenge
The main challenges of my level are around discovering the different applications of boxes and switches, particularly in section 2 and the final part of section 3. Each encounter in the level contributes towards moments of tension and relief as the player solves puzzles or overcomes enemies/obstacles, with complexity of encounters increasing through sections, thus increasing difficulty.

Section 3 presents an increase in both skill-based challenge and complexity. Complexity is achieved as a combination of the simple mechanics and verbs used in previous sections is required to solve the final box push/doors puzzle. Physical skill is engaged particularly in the S-shaped path (spikes were placed to drive fine-tuning of jumps) and acid/moving platform parkour (challenging reflexes and precision platforming). Intellectual problem-solving and analytical skills are required to understand and solve the doors puzzle.

The level aims to maintain the player’s state of flow by balancing intense threat encounters with minimally dangerous spaces (e.g. the tunnels in section 2) to modulate the level of difficulty. The player is able to see their objectives clearly (often a switch or a door) due to the close proximity or order of encounters and receives immediate feedback to actions (e.g. doors opening/closing loudly). Minimal red herrings/distractions also contribute towards maintaining flow.



### 1.4. Exploration
Although section 1 is mostly linear, sections 2 and 3 increase the number of ways to navigate the space, with different paths having different purposes. Encounters sit at different elevations and aesthetic settings, varying between being cramped (section 2's shooting encounter) to plein-air (section 3), fitting with the narrative theme of moving from underground to the skies.

Sections 1 and 3 return the player to the start, establishing the final key door as a central landmark and allowing the player to mentally connect each section together as they drop down to the start after collecting all three keys. Keys are placed throughout the level in visible locations to mark the final objective for each section.

Section 3 in particular was designed to be memorable, as some backtracking is required to solve the puzzle. Areas are connected in multiple ways and passages are opened/blocked depending on the player’s interaction with the switch, inviting player curiosity and exploration of strategies (e.g., the switch can be shot from both the left and right). The multi-staged puzzle aims to challenge any existing 'hit one switch to succeed' mentality. The singular checkpoint placed in the small, distinct "safe room" acts as a landmark and ensures the player doesn't get disoriented when respawning.

Pics: switch left/right, section3


## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.8. Spikes
Three pits of spikes are sequenced in increasing size, requiring the player to adjust the magnitude of their jumps, teaching them both the jump mechanic and the spike damage/knockback mechanic if they fail. Starts easy then increases pressure to scaffold mastery.
### 2.2. Checkpoints
The first checkpoint is placed after the first source of damage (spikes) and before the next (chomper), in a safe area enclosed by a door and column. Generally placed to mark each area/encounter.
### 2.11. Weapon Pickup (Staff)
The staff pickup is directly followed by columns blocking the path forward, facilitating discovery of the 'attack to break column' mechanic. 
### 2.4. Health Pickups
Health pickups are placed after potential damage encounters (more frequently in section 1) to reduce stress of dying.
### 2.3. Chompers
The chomper is placed behind a column so when the player approaches, it gets angry but can't reach them. When the player attacks the column, they also hit the chomper, teaching them that enemies have 1 hit point.
### 2.10. Weapon Pickup (Gun) and Spitters
One spitter is placed in a tunnel, unreachable by the melee attack, teaching the player to combine crouch and shoot.
Two spitters are placed on raised terrain to demonstrate how they can spit through walls, and additionally allows the player to combine jump and shoot.
### 2.6. Moving Platforms and Acid
Moving platforms provide a safe path over the acid if the player can time their jumps correctly, requiring a low level of skill and accuracy which is developed upon in later sections.
### 2.5. Keys
The key is the last objective achieved in each section, indicating the end of the section.
### 2.7. Passthrough Platforms
The player must learn to pass through certain platforms in order to progress and complete the section. Ideally facilitated by the platforms' visual difference to terrain.






## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3



## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

--
Identify the unknown:
1. does the level feel cohesive, with a strong sense of space and without feeling repetitive or linear?
2. are the goals (both big and small) clear throughout each encounter?
3. is the player continuously being pushed to test their knowledge and learning over the whole level? are there any dips in the hill of strategy/performance?

Prototype:
1. level map sketches were drawn as 3 separate screens, intending to loop back to the central start point. then greyboxing the geometry of the level to see how it all fits together and testing whether the player path works as intended.
2. gameplay prototypes - lo-fi implementation of assets to test how encounters would play out according to my level map/storyboards
- 

Playtest:
1. with personal in-engine greyboxing, I discovered the jump height was a lot higher than I imagined (6 units), so some parts of the level map were adjusted to achieve the desired effect; e.g., the first spike encounter was meant to introduce controlling jump height and distance, but the size of one unit to jump was a bit too easy and felt too out of control with the scale of Ellen's jump, so the encounter was adjusted to better facilitate learning the jump mechanic in a smoother way. additionally, the connecting section that loops section 1 back to the start was slightly modified to feel more familiar (the passthrough platform and key are visible at the start of the level) and to provide a goal from the start of the level (as you can see the key).
2. personal in-engine playtesting revealed issues with section 2 - the initial arrangement of encounters meant that the player would likely complete the shooting puzzle to drop the block before actually seeing the block, as the solution was the first thing presented in the section. so, the order of encounters was modified, and a new goal was consequently added - the player now has to push the block to the goal. additionally, a small platform was added to draw attention/indicate to the player that there is something of interest above them (the box drop). the rearrangement of the goal and solution worked well - the player is now encouraged to examine the whole area and can see the goals before solving the puzzle. but still the softlock.
3. in-engine playtesting revealed section 3 to feel too boring and disconnected to previous sections. initially, i attempted to fix this by increasing the skill-based challenge through the section with tricky platforming and navigation, however, after those changes, I still felt like it wasn't cohesive with the rest of the level because it didn't challenge the player to apply many of the key mechanics learned in previous sections. so, i expanded on the box push and open bridge verbs used previously to create an interesting puzzle that requires strategy, understanding of learned mechanics, and memory of the area. 

Evaluate:
1. the level flows as intended, and the path through is quite clear without being overly linear.




greyboxing the basic geometry of the level; discovered the jump height is very high (6 units) so adjusted the beginning encounter/s to achieve the desired effet (e.g. cant skip sections or backtracking whatever)


- early playtesting and feedback by brother - identified some issues - can softlock by pushing block into acid (section 2 ver 4). not clear enough visually where the block should go/need it to jump for key.
- iterated over one of the main encounters in that section - the moving platform pushing. i wanted to keep the verb of 'push' the block to solve the next puzzle/encounter, but with the acid there was too much possibility of softlocking. so, we considered a path where the box could go, but the player couldn't. level map sketches and storyboards resulted in the labyrinth-like/tunnel design. now it is a bit more clear where the box should go, and that it needs to be pushed in a certain direction. the elements of the section are a bit closer together now too, so it's a bit easier to navigate encounters.

--

## Generative AI Use Acknowledgement

Generative AI was not used throughout the development of this project.