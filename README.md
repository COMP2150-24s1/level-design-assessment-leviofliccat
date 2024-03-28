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
My level design intends to encourage the player to learn and discover the facets?? of the key set of verbs - jump, attack, push.
Section 1 facilitates the learning of the key mechanics to be used in future strategies by structuring them in a mostly linear fashion. The ability to control jump heights is introduced in encounter 1, the melee attack function and switch activation in encounter 2, and most importantly, the box push mechanic in encounter 3. The tight layout of encounter 3 forces the player to learn the push mechanic, which is key strategy required in later sections.


--


### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 
- The level should feature appropriate dramatic pacing. Each section should be divided into encounters that require the player to use their skills to complete a task. The player should have a clear idea of their goals, even if the solution is challenging to solve.

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?
- The level should challenge the player’s reflexes and problem-solving skills. Challenges should be presented via a dramatic arc of modulated difficulty, with moments of tension and relief, and moments of power. The first section of the level should be fairly easy. The later sections should be more demanding, but still achievable by a moderately skilled platform player.

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?
- The level should be non-linear, inviting and facilitating the player to explore in different directions without them getting lost or becoming uncertain as to what to do next. Your aesthetic and layout choices should aid in this goal, creating a distinct and memorable feeling of space/place. The player should never have to repeat large areas of the level that don’t present new challenges.

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid

### 2.2. Checkpoints

### 2.3. Chompers

### 2.4. Health Pickups

### 2.5. Keys

### 2.6. Moving Platforms

### 2.7. Passthrough Platforms

### 2.8. Spikes

### 2.9. Spitters

### 2.10. Weapon Pickup (Gun)

### 2.11. Weapon Pickup (Staff)

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
2. personal in-engine playtesting revealed issues with section 2 - the initial arrangement of encounters meant that the player would likely complete the shooting puzzle to drop the block before actually seeing the block, as the solution was the first thing presented in the section. so, the order of encounters was modified, and a new goal was consequently added - the player now has to push the block to the goal. additionally, a small platform was added to draw attention/indicate to the player that there is something of interest above them (the box drop).
3. in-engine playtesting revealed section 3 to feel too boring and disconnected to previous sections. initially, i attempted to fix this by increasing the skill-based challenge through the section with tricky platforming and navigation, however, after those changes, I still felt like it wasn't cohesive with the rest of the level because it didn't challenge the player to apply many of the key mechanics learned in previous sections. so, i implemented a slightly more complex (combination and expansion of known systems) box?mechanic? update this

Evaluate:
1. the level flows as intended, and the path through is quite clear without being overly linear.
2. the rearrangement of the goal and solution worked well - the player is now encouraged to examine the whole area and can see the goals before solving the puzzle.



e.g. greyboxing the basic geometry of the level; discovered the jump height is very high (6 units) so adjusted the beginning encounter/s to achieve the desired effet (e.g. cant skip sections or backtracking whatever)
- the chomper encounter in section 1 was initially too spaced out - wasn't obvious that the switch was connected to the platform. now the goal and target are on the same screen for clarity.
- section 2 layout was changed after in-engine testing - need to see the box drop mechanism and the end goal before completing the shooting puzzle. but then the acid made it so that if they failed the box timing, they would get softlocked. so added a little platform to catch the block and help the player push it across the acid... was gonna put a wait at the end of the platform movement but decided against it to add challenge. add more challenge by making them figure out how to start the platform moving
- early playtesting by brother - identified some issues - can still softlock by pushing block into acid. not clear enough visually where the block should go

--

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


