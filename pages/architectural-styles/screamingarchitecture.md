---
title: Screaming Architecture
permalink: /architectural-patterns/screaming-architecture
layout: pagelayout
---
![Screaming Architecture"](../../pictures/Screaming%20architecture1.png)

"Screaming architecture" is a term coined by software architect Robert C. Martin, also known as Uncle Bob, to emphasize the importance of clear, explicit, and highly visible architectural decisions in software development. The concept is rooted in the idea that the architecture of a software system should "scream" its intent and key design principles, making it immediately obvious to developers and maintainers. The term is used to encourage software developers to prioritize architectural decisions that are evident and straightforward, rather than hiding important architectural aspects beneath layers of complexity or indirection. The goal is to make it easy for developers to understand the system's structure, design, and behavior just by looking at the code or the architecture.

## Benefits

- **Improved Maintainability:** It makes it easier to maintain software over time. When the key architectural decisions are evident, developers can more easily identify and modify components, leading to quicker and safer updates.
- **Enhanced Readability:** Clear naming conventions and explicit architectural choices make the codebase more readable. Developers can understand the purpose and functionality of various parts of the system without needing to spend excessive time deciphering complex or ambiguous code.
- **Reduced Cognitive Load:** Developers don't need to keep as much in their heads when working with a system that follows a screaming architecture.
- **Faster Onboarding:** New team members can quickly get up to speed with the system, as they can readily grasp the architectural decisions and the organization of the codebase.
- **Improved Collaboration:** A system that uses screaming architecture fosters better collaboration among team members. When everyone understands the system's design and principles, it's easier to work together and make consistent contributions.

## Tangible Things to Do for Adoption

1. **Naming Conventions:** Use clear and meaningful names for variables, functions, classes, modules, and components. Avoid cryptic or abbreviated names.
2. **Explicit Design Patterns:** Use recognized design patterns like Model-View-Controller (MVC) or microservices and make sure their roles and responsibilities are explicitly defined.
3. **Avoid Over-Engineering:** Refrain from adding unnecessary layers of complexity or abstraction. Ensure that each component has a clear and justifiable purpose.
4. **Modularization:** Break down your software into well-defined and loosely coupled modules or components, each with a specific responsibility.
