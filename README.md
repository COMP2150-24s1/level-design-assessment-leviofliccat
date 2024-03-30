[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Felicity Nop
### Student number: 47681837

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.


discovery - scaffolding new concepts
challenge - presenting goals and obstacles
drama - controlling the pacing
exploration - inviting and rewarding curiosity
fantasy - building a world, unfolding a narrative



Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?
- The level should facilitate the player’s discovery of mechanics and dynamics without written instruction. Mechanics should be introduced safely and individually in section 1, before the player must use them under pressure and in combination (to learn new dynamics) in later sections. You can assume the player already knows the controls.

--
My level design intends to encourage the player to learn and discover through play the key verbs I wanted to highlight - 'push' boxes and 'open' doors/bridges. These two verbs are used in different ways throughout the level, each encounter developing on previous interpretations of the verb.

The box push to open bridges is introduced in section 1. The encounter was designed such that the player is "forced" to push the box forward to progress (rather than jump over), which shows them the activate button -> opens bridge mechanic. They then also jump on the box to reach the next area.
Section 2 encourages the player to combine movement verbs and 'push' to get the box from one encounter to the next (which requires the box to jump on). The gun encounter allows the discovery that shooting a switch can 'open' bridges.
Section 3 is the cumulation of sequential switch activations to 'open' and close multiple bridges as well as multi-staged box 'push'.


--


### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 
- The level should feature appropriate dramatic pacing. Each section should be divided into encounters that require the player to use their skills to complete a task. The player should have a clear idea of their goals, even if the solution is challenging to solve.

--
Throughout the level, I made sure the player was able to see their goals. The ultimate goal is visible from the start and is the central point of the level. Keys and health pickups are placed visibly, but just out of reach, to indicate where the player needs to go. Section 2 in particular presents the goal (box to be dropped) *before* any possible solutions.

Section 1 is structured so there are "safe" moments between each encounter, creating small bumps in the intensity curve. Each encounter is different, avoiding boredom by repetition.

The spitters in section 2 and the physical skill required to overcome them create a spike in intensity. Dramatic tension is created by the thinking required to strategise and solve the section.

The elevator connection between sections 2 and 3 is intentionally long and in a bigger space, to allow the player to feel the satisfaction/achievement of solving the previous puzzle, and a moment of respite before the tension of section 3.

Section 3 incorporates enemies (active threats), more acid/spikes (increased challenge) and fewer health pickups (higher stakes) to increase tension. The checkpoint is closed off from danger, creating a "saferoom" to relax and think.
--



### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?
- The level should challenge the player’s reflexes and problem-solving skills. Challenges should be presented via a dramatic arc of modulated difficulty, with moments of tension and relief, and moments of power. The first section of the level should be fairly easy. The later sections should be more demanding, but still achievable by a moderately skilled platform player.

--
The third section of my level presents an increase in both skill-based challenge and complexity.

The third section features a puzzle which combines the box 'push' and 'open' bridge verbs in a new way, with several "stages" to the solution, increasing the complexity of the section.

Physical skill - platforming, timing
intellectual skill - problem solving, complexity of puzzles

difficulty curve - 

flow - connectivity of sections, scale of level/having encounters visible and always having something to look for next
--




### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?
- The level should be non-linear, inviting and facilitating the player to explore in different directions without them getting lost or becoming uncertain as to what to do next. Your aesthetic and layout choices should aid in this goal, creating a distinct and memorable feeling of space/place. The player should never have to repeat large areas of the level that don’t present new challenges.

--

Although section 1 is mostly linear, sections 2 and 3 increase the number of ways to navigate the space. Encounters sit at different elevations and sizes, varying between being cramped (section 2's shooting encounter) to plein-air (section 3), fitting with the narrative theme of moving from undergound to the skies.

Sections 1 and 3 return the player to the start, emphasising the final door as a central landmark.

Section 3 in particular was designed to be memorable, as some backtracking is required to solve the puzzle. Areas are connected in multiple ways, inviting player curiosity and exploration of strategies (e.g., the switch can be shot from both the left and right). The multi-staged puzzle aims to challenge the player's 'hit one switch and win' mentality. The singular checkpoint placed in the distinct "saferoom" ensures the player doesn't get lost when respawning.

--



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