# Requirement Engineering and Design Project (Software Engineering for HPC)

This repository contains the relation developed during the Software Engineering for HPC course. I wrote the relation in LaTeX, and I've worked alone.

The document can be found in the [doc](doc/) folder and the file name is _Valentini_ because it was a requirement of the professor (used for submission).

## Project details

### Goal and approach

The objective of this project is to apply in practice what have you learnt during the first part of the course about requirement engineering and design.

The exercise consists in analyzing the problem presented in the following section and in writing a document including the following elements:
- **Requirement analysis aspects**: Derive from the goals the problem description the use cases, requirements (both functional and non-functional), and domain assumptions. For brevity, you do not need to describe in detail each individual use case. One or mose use case diagrams and the detailed description of the use case you feel is the most critical/important will be enough. Don't forget to take into account all relevant actors in the considered domain. Remember that actors are not only human beings, but all relevant devices/legacy software that interact with your system and play a role in some use case.
- **Architectural design**: Define the architecture for your system. Use component diagrams and sequence diagrams to present the architecture. Describe the purpose of each component. Highlight in the sequence diagrams how components interact with each other. Discuss about the criticalities behind your system and how you plan to address them.


### The problem

Two urgent global concerns are environmental sustainability and climate change; because of air pollution and greenhouse gas emission, transportation - especially urban commuting - contributes to worsening those issues.

Even today, urban areas are characterized by a heavy reliance on personal vehicles, which are seen as the most comfortable and efficient way of commuting, despite several studies showing that better alternatives exist in most cases.

Improving public transportation systems' efficiency can make them more appealing to daily commuters and is, therefore, a promising way to lessen environmental impact and, at the same time, to increase the overall quality of citizens' life ([article](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0223650)).

The project "Eco-City Commute" (ECC) aims to create a comprehensive software system that makes public transportation within an urban area as easy and efficient as possible, promoting its adoption.

ECC receives data from sensors, deployed on public transport means, that provide information about their respective occupancy rates. Moreover, it can acquire real-time information about public transit timetables, as well as information about bike and ride sharing, from specific services (think at ATM in Milano, bikemi, mobike, blablacar, ...).

Based on these pieces of information, ECC offers services to two types of stakeholders:
- **Citizens**: ECC offers a mobile app that allows citizens to input the origin and the destination of their trips within the urban area, together with any constraint they have (e.g., they do not want to use a bike, or they must arrive at destination within a certain timeframe). The app will compute for them environmentally friendly routes, possibly combining different transportation means.
- **Urban area managers**: ECC offers to managers a dashboard through which they can visualize reports concerning the daily usage of the various available transportation means, their occupation rates and delays (if any).