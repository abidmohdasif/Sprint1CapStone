# Sprint1CapStone
https://github.com/abidmohdasif/GroupSprint

SDLC Capstone — Sprint 1 Process Analysis
Course: Software Quality Assurance

Sprint: Sprint 1

Model Selected: Agile/Scrum

Submission Type: Solo

Due: End of class Thursday

## Section 1 — Model Selection and Rationale
<!-- Choose one SDLC model: Waterfall, Agile/Scrum, or V-Model. Argue that it best describes how Sprint 1 actually ran. Your rationale must connect specific model characteristics to specific evidence from your project — your spec, your GitHub Issues, your swap structure, your retrospective. If you choose Waterfall: address why Sprint 1's feedback loops and iterative fixes do not disqualify it. If you choose V-Model: identify the specific parallel between your dev phases and your test phases. -->

Selected Model: My team ran the agile/scrum framework during our sprint 1.

Rationale: We didn't have a set of requirements that we had to follow, we had a basic layout and we built upon that during the sprint. This closley follows the agile framework as it doesn't need a structed design at the begening and allows for revisions during the sprint. Even though there was mutliple testing portion in 1 sprint if you split the sprint in 3 parts(weeks) it would be the same as three sprints and is very similar to the agile framework. We always had a playable product, it wasn't until the end of the sprint that we finally had a product.

## Section 2 — Phase Analysis
<!-- Walk through every phase of your chosen model. For each phase, address two things: 1. What element of Sprint 1 corresponds to this phase, even loosely? 2. What would this phase have looked like under strict model adherence? Every phase must be addressed. Phases that don't map cleanly are not a reason to skip — they are the most valuable part of the analysis. -->

Phase: <!-- Requirements -->
What Sprint 1 produced: We created a planning document which talks about the game specifications, player action and how you will win or lose. We included all the requirements of the game and all our ideas for the game.

What strict adherence would have looked like: We would have writted a clear basic story and the explanation of the featuers being included in the game. We would have also ranked all the features by importance so that we would know which ones to implement first.

Phase: <!-- Planning -->
What Sprint 1 produced: We divided up what each person was going to do and starting building the base of the game. We didn't really document this part it was more of telling each person what they were going to do that day.

What strict adherence would have looked like: We would have chosen a specific thing that we would have wanted to be finished by the end of the day. Everyone would have their roles and know what part they are responsible for.

Phase:<!-- Implementation -->
What Sprint 1 produced: We got the game working added all the features together. You could play the game right now, it was in its MVP stages.

What strict adherence would have looked like: We would meet daily to have a standup and code will only be marked complete if it met the guidelines and if it was tested and reviewd.

Phase:<!-- Testing -->
What Sprint 1 produced: This was the end of week one we were finished with the MVP of our game and we had to test the other classes game, becuase of that we mostly found the errors after the game was developed. We logged the issues into github for the devteam to check.

What strict adherence would have looked like: Testing should have happend during the code was being built so that bugs can be reported immediatly and also fixed during the sprint. We would have done all the testing such as edge cases and black box and etc.

Phase:<!-- Review -->
What Sprint 1 produced: We got together as a class and the game was presented to all the students and questions were asked. It was also evalueated by a different team to make sure all the bugs were fixed.

What strict adherence would have looked like: Presentation of the game occurs and there would be feedback given to the team that should be implemented as new updates. Figure what should be done for the next sprint because the cycle never ends :)


<!-- Add additional phase sections as needed for your chosen model -->
## Section 3 — Defect Case Studies
<!-- Select two bugs from your GitHub Issues filed during the Week 6 swap. For each bug provide: 1. A description of the bug and what it caused 2. The phase that introduced the defect (requirements / design / implementation) 3. The phase that caught it — and whether your model would have caught it earlier 4. The cost of catching it late Link directly to each GitHub Issue. -->

Bug 1
GitHub Issue: <!-- https://github.com/Gcc07/GroupSprint-QA/issues/7 -->

Description: The logic of the game dosen't allow the game to end even when the pets stats reach zero, the game just keeps going as nothing happens. t

Phase that introduced the defect: This was one of the errors that we introduced ourselfs but I think implementation is where it is most likly to show up, for example < 0 instead of <= 0

Phase that caught it: Testing, when the QA testers were playing the game they couldn't lose

Would your chosen model have caught it earlier? yes if we had implemented testing as we were coding it would have been easily catchable

Cost of catching it late: You have run throught the code and figure out where the code was wrong, if it had been published it would be bad PR for the company

Bug 2
GitHub Issue: <!-- https://github.com/Gcc07/GroupSprint-QA/issues/6 -->

Description: The game doesn't check weather or not the user input is valid or in this case if it is to long 

Phase that introduced the defect: Implementation, during the coding phase the dev team lacked or forgot to put error handling into the user input.

Phase that caught it: Testing the QA team figured out that when you entered in a name that was crazy long the game started to lag/crash

Would your chosen model have caught it earlier? : Yes if we had test cases set up for this and we implemented testing through the processs 

Cost of catching it late: It affects the user experience a little and we had to go back to the code and implent error handling for not only this but a a bunch more imputs.

## Section 4 — QA Assessment
<!-- Address three things: 1. How did QA actually operate during Sprint 1? (Gate / continuous / in between?) 2. How does that compare to what your chosen model prescribes? 3. What would QA have looked like under strict model adherence? Your answer must be specific to your team's Sprint 1 experience. -->

How QA actually operated: QA was continuous between week 1 and week 3 We finished the game gave it to QA and then we got the game back to do revisions

How that compares to your chosen model: This differs from agile becuase of the fact the agile says testing occurs alonside development, we had finished the mvp before testing ever got to touch it.

What QA would have looked like under strict adherence: 
QA would have been invloved during the planning
There would have been some test cases that were written before code(the basics suchs as error handling for user intput)
Run validation testing before mergin together all the features(implementation)

## Section 5 — Team Retrospective on Process
<!-- Identify the single most significant gap between how Sprint 1 ran and how it would have run under strict adherence to your chosen model. Answer three things: 1. What was the gap? 2. What did it cost your team in practice? 3. If you ran Sprint 2 under strict model adherence, what one change would have the most impact? -->

The gap: I believe the biggest gap was the fact testing didnt work alongside the development. The testing part was kind of run as waterfall as the testing team was brought in at the end to check for errors in the game.

What it cost the team: There wasn't to much cost for the team as we already knew most of the errors but if we didn't know the erros we would have to rework the logic and have to spend time working on fixing the errors

The one change for Sprint 2: I would start of the sprint choosing one of the models of SDLC. I would also ask the QA team for ideas as they may have ideas that will help the game or they will figure out potential errors that could happen, so that we could take them into account before we even start the game building process.

## Contributors
Abid Asif - all
