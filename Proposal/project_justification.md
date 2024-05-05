# Justification
[//]: # (This section is an example of justifying your design and development decisions.)

## Overview

### Brief
The client is seeking a sidescrolling retro 2D platformer game (like the original Mario) where they can add their own art. The game needs to be organised in a way that they can develop the:
* Levels
* Enemies
* Player 
* Pickups

The player character should be able to:
* Walk
* Run
* Jump
* Be damaged

### Project Name
Velvet Thunder

### Description
The player plays as Mario-like character that can run and jump. 
They navigate a 2D sidescrolling environment from left to right, completing levels that get harder and harder.
The player can collect powerups to more effectively complete levels and defeat enemies by jumping on them.

### Begin Date
**Tuesday 23rd of April 2024** (first email contact with client accepting the project)
### End Date
**Friday 31st of May, 2024 at 11:59pm** (handover of the finished project to the client)

### Communication with Client
* Would you like an animation controller set-up on the player? (Differing jump, sprint, damage taken sprites?)
> For the scope of this project I'm fine with a box or capsule moving around without an animation controller.

* Should the enemies patrol between two points as well as be stationary? Would you like an animation que in their movement/death?
> I would love to have a patrolling system! I would just like to be able to use it easily and change the points.

* We're looking to add a speed/jump-boost so that you can modify it later. Would this be acceptable?
> A speed and jump boost sounds perfect! Thank you.

* In your job posting, you say that you'd like the game to be similar to old-school Mario games. Do you mean that in just the gameplay sense, or also the aesthetic and graphical sense (e.g. low resolution pixel art)?
> Mario is the inspiration in gameplay and it's simple aesthetic. Although I would like to put my own art in and I'm probably not going down a pixel art path. 

* Is a start-screen and some in-game UI required?
> I wouldn't need any start-screen or in-game UI for the scope of this project.

* Would there be a way for players to damage enemies? Such as landing on them like in Mario?
> At this point there doesn't need to be a way to damage enemies. 

* Would there be any movement mechanics other than simple running and jumping? Like double jumping, dashing, etc.
> I don't need any double jumping or dashing at this point!

* Would there be different enemy variants? would they all hurt the player though contact damage or would some have ranged attacks?
> Right now all I need is a stationary hazard and I think an enemy that can patrol between two points as suggested by another team-member.

* Would players have a value for health or would they die from a single enemy hit?
> Player death would be a great addition if it can be done. Resetting them back to the start on damage would be fine enough.

* Seeing as you are handling the whole aesthetic and artistic side of the game, what is the working name for the game that you have considered?
> I'd like to call the WIP project name "Velvet Thunder". Thanks for asking!

* Should the player be centered in the middle of the camera or offset to the left a bit to let the player see further to the right?
> I'd like it to replicate the same camera from the retro Mario platformer games. I think it's a little to the right.

* Do you expect any complications outside of our team's control to arise midway through the project? Let me know if there are any that come to mind.
> There's no complications here! I'm not really at any crucial position to effect the projects progress. 

---

## Project Understanding After Communication (Statement of Works)

### Requirements
[//]: # (What are the requirements of the finished project?)
* **Needs** the product inside the deadline.
* Game art **needs** to be modular and easily editable by the client
* **Needs** level changing functionality
* **Needs** to control extremely similarly to retro 2D mario games

### Expectations
[//]: # (What are the client's expectations?)
* Project delivered on time
* Professional communication between the team and the client to establish expectations and requirements.
* Prompt communication with the client when design issues encountered
* Does **not** require audio
* Does **not** require any UI or home screen
    * The game can boot into the first level
* Does **not** require high quality art
    * Use placeholder basic shapes in Unity
* Does **not** require any animation for the player
* Does **not** require the player to be able to kill enemies
* One stationary hazard and one patrolling enemy the moves between two editable points
* Player death functionality and reseting position on damage
* Replicate Mario Bros camera lookahead (offset to the right)

### Assumptions
[//]: # (What are you assuming based on client responses)
* The client will not interfere during development unless we engage them with further questions
* Multiple fully completed levels are not needed as the client wants to build them themselves - at least 2 basic levels are needed to get level progression working however.
---

## Milestones
[//]: # (Breakdown of phases of development, with estimated delivery times)
[//]: # (In practice, if you were working on fixed price phases, you would also list expected payment after each phase.)
| Phase | Completion Date |
| --- | --- |
| Prototype | Week 13 |
---

## Risks

### Risks
[//]: # (What are the risks of this project)
* Unity and C# are excellent prototyping tools, but working quickly often means less than perfect code
    * Project may not be fit for use in further development
    * Bugs may be present in prototype due to the short turn-around
    * Working quickly is error-prone

### Risk Management
[//]: # (How are you managing the mentioned risks)
* All coding will aim to be designed in an extensible manner
* Testing will be undertaken throughout prototype development
* Using source control we will ensure our code is safe and usable at all times

---

## Constraints

### Constraints
[//]: # (What are the constraints of this project)
* We have a tight timeframe, so we will need to make fast decisions, which may be less than perfect

---

## Justification
We really like the mention of "silly games catch people's eyes". So we took your suggestion of dragons and built on it with alliteration as a starting point. We went through many ideas, but finally came up with a title called "Donuts, Daggers & Dragons.

The name along was enough to get conversation happening, and we soon found ourselves thinking of countless, comical and enjoyable scenarios stemming from the title.

etc. Explain your design decisions in regards to the client's requirements.

## Agreement
[//]: # (List out the arrangement)
Work will be completed to fit the provided Statement of Works, any work outside of this arrangement will be billed at our hourly rate, or quoted separately.

## Signatures

| Client Name | Date | Signature |
| --- | --- | --- |
| Llhiza Eamont |xx-xx-2024 | ________ |

| Team Rep. | Date | Signature |
| --- | --- | --- |
| James Warren | xx-xx-2024 | ________ |
