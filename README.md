# TechDesignDocument
## What is a Tech Design Document?
A Tech Design Document (TDD) is a document that contains all technical specifications and features a game software is planned to be launched with. It also contains a major technical breakdown of said features in instructions about how to implement them in order to save time when doing the actual program. It borrows from the most relevant parts of the GDD in order to develop further about the game development plan. It contains several parts:
### Purpose
A brief explanation of what the software is being programmed to cover. Why do people need it?
### Background
The context that has brought the team to develop the app itself. 
### Game Engine Choice (Video Game Software specific)
Are you sticking to Unity? Unreal Engine? Did you make it on your own? Whatever you picked, it goes here, along with why you picked it. Maybe the engine is one that is renowned for having amazing 3D graphics, or maybe you just wanted one that aids with AI coding. Whatever the needs, they also go here.
### Feature List & Risks
What will the program have that makes it not a "Hello World" type of code. Do you have interactive GUI? Turn-based or action-based combat? Does the game have open world exploration? Recruiting? Affinity systems? What risks do the features carry? Everything goes here.
### Detailed Design
The complete list of features exist, but what about implementing them? What specifics will you use? Is the physics engine a specific one or is it being built from scratch? Does mapping happen manually or does it borrow imformation from files? How do you code the combat system? All of it goes in here.
### UML Diagram
It is a diagram of how the system will be defined and how all the objects within it are and how they will behave. 
### Implementation Plan
A major breakdown of tasks, sort of a checklist of what to do to have the complete game finished and ready for release. Things like "adding assets", "creating UI", etc.
### Schedule
A complete task breakdown exists, but when will they be done? Do they happen simultaneously? Does one go after the other? How long do they take? It's up for the schedule to fill up these gaps. 
### Tests
All the new features one adds to the app are all fine and nice, but testing to check if they work is needed. This section covers how that is done in detail, to prevent game breaking bugs from happening... hopefully. 
### Runbook (optional)
How will the game be monitored and launched? Troubleshooting, bug discovery and fixing, how is it all covered? It's all part of the runbook, to ensure the product remains optimal. 

## Why make a TDD?
While small features and other code things might be not optimal for the usage of this, the scope of an entire application broken down into smaller parts will aid make development quicker and more efficient, as everyone will be aware of how much needs to be researched before implementing a specific feature, since this document is shared by the entire team. 

## Things to take into account
When making a TDD a team is establishing a common document to help develop the software in detail, as such common guidelines should be established when writing in it to prevent inconsistencies and confusing code. This includes:
- Definition of variables and macros' naming scheme and hierarchy
- Organization of the functions and code

## References
- Dev.to: [https://dev.to/mage_ai/how-to-write-technical-design-docs-c02](https://dev.to/mage_ai/how-to-write-technical-design-docs-c02)
- TDDdoc.io: [https://tddoc.io/](tddoc.io)
- UIT Stanford: [https://uit.stanford.edu/pmo/technical-design](https://uit.stanford.edu/pmo/technical-design)
