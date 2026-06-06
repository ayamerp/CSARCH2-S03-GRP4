# CSARCH2-S03-GRP4
# Panic at the Architecture! Y2K, Global Hysteria, and Why DLSU Has 3-Digit IDs

**Course:** CSARCH2 — Virtual Exhibit Project

**Section & Theme:** S03 — Problem Solving Stories

**Topic:** Y2K Bug (Year 2000 Bug; Millennium Bug)

---

## Group 4

| Name | Role |
|------|------|
| Alcasid, Aizy Danielle | Member |
| Dimaunahan, Chelsea Jei | Member |
| Pangan, Aaliyah Maxine Rochelle | Member |
| Roa, Luis Antonio | Member |
| Sanidad, Christian Gabriel | Member |

---

## Introduction

An architectural shortcut made by programmers to save memory and storage costs led to one of the most significant technology concerns of the 20th century. The Y2K bug was created from the simplification of storing years as two digits instead of four — a practice adopted because early computer systems operated under limited and expensive memory and storage resources.

As the year 2000 approached, fears grew that computer systems would misinterpret the date and cause widespread disruptions. This prompted a massive global effort to identify and remediate vulnerable systems before the new millennium arrived. The event also left behind a local legacy that reached the hallways of De La Salle University — the student ID system was extended in response to this technical mishap.

> *"Welcome to an exhibit that explores the critical architectural decisions that either make or break the future of computing."*

---

## About the Y2K Bug

Computer engineers only stored two digits for a date's year, since data storage was expensive and took up a lot of space. As years passed, engineers realized this would become a serious problem — computers might interpret `"00"` as `1900` instead of `2000`, causing all date-dependent software to malfunction.

People feared nuclear plants would malfunction, the economy would crash, and it would be a kind of "doomsday." However, nothing catastrophic happened once the clock struck midnight on January 1, 2000. The issues that did occur were relatively minor: some records were accidentally deleted, cellphone messages were lost, and one 105-year-old man was directed to attend kindergarten. More seriously, a U.S. spy satellite lost contact with its controllers and some company security systems failed.

From a computer architecture perspective, the Y2K bug emphasizes the importance of proper data representation and storage allocation — even small savings in resource usage can create problems that affect systems decades later.

---

## Interactive Elements

### 1. Choice-Based Narrative (Simulation Game)
An interactive, narrative-driven simulation game where the player acts as a **time-traveling programmer on New Year's Eve of 1999**. The main objective is to prevent the Y2K bug from triggering before midnight.

- Three branching paths determine the story direction
- Incorrect decisions trigger time loss
- A fail message triggers once the in-site clock reaches midnight
- Users may experiment with different choices and replay

### 2. Interactive Timeline of Events
A horizontally scrollable timeline showing major events leading up to the Year 2000. Users can click on different points to view historical details, including:

- Early adoption of two-digit year formats
- Growing concerns about Y2K during the 1990s
- Efforts made to fix the problem before January 1, 2000

The currently selected period expands and becomes the focal point of the screen, with additional information and images displayed beneath it.

---

## Pages & Layout

The website is fully responsive using CSS media queries and flexible layouts. Desktop users see the full Windows 95/98-inspired interface; mobile users receive a vertically stacked layout that preserves gameplay and timeline functionality.

### Home Page
Entry point of the exhibit. Contains the exhibit title, introductory information about the Y2K bug, and navigation links to different sections. Designed to resemble an early internet webpage while remaining clean and easy to navigate.

### History, Background, and Notable Figures
Provides an overview of the Y2K bug and the technological limitations that contributed to its creation. Introduces notable individuals and groups who played important roles in raising awareness and coordinating remediation efforts. Images and supporting information are presented throughout.

At the end of this section, visitors can scroll directly into the interactive simulation game.

### Interactive Starting Screen
A **Windows 98-inspired desktop environment** with multiple error message pop-ups that communicate the urgency and confusion of the Y2K bug. Each pop-up serves as an entry point to a specific task or scenario the visitor must investigate.

### Task-Solving Screen
Presents visitors with Y2K-related problems and multiple possible solutions. Scenarios are explained in accessible language for non-technical visitors. Users select from available choices and receive feedback on the consequences of each decision.

### Interactive Timeline
Horizontally scrollable interface presenting key Y2K events across decades. Selected periods expand to become the focal point, with additional information and historical context displayed below.

---

## Design & Visual Identity

The exhibit uses a **Windows 98-inspired** visual identity to reinforce the technological setting of the Y2K era.

| Element | Choice |
|---------|--------|
| Primary Color | Windows 98 Blue |
| Background | Light Gray |
| Accent Color | Red (Error Messages) |
| Heading Font | Tahoma |
| Body Font | Verdana |
| Retro/System Font | Courier New |

---

## References

- National Geographic. (n.d.). *Y2K bug.* National Geographic Society. https://education.nationalgeographic.org/resource/Y2K-bug/
- Uenuma, F. (2019, December 30). *20 years later, the Y2K bug seems like a joke — because those behind the scenes took it seriously.* TIME. https://time.com/5752129/y2k-bug-history/
- *Y2K "Crisis" | Computer Science | Research Starters | EBSCO Research.* (2021). EBSCO. https://www.ebsco.com/research-starters/computer-science/y2k-crisis
