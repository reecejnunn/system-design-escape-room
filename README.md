# 🧩 System Design Escape Room

<p align="center">
	<img src="assets/system-design-escape-room-header.png" alt="System Design Escape Room: Diagnose, Decide, Defend, Unlock" width="100%" />
</p>

> A team-based system design challenge built around realistic production
> incidents, sharp constraints, and decisions made under pressure.

Teams investigate four incidents, defend their choices, and collect the clues
needed to unlock the final meta challenge.

This repository is the public, participant-facing pack. It contains the room
introduction and scenario sheets needed for teams to understand the incidents,
but it does not contain the hidden evidence, clues, or answer sheets.

The full facilitator pack, including question sheets, clue/evidence files,
answer sheets, and private delivery notes, is kept in a separate private
repository.

## 🗺️ Public participant materials

This repository contains the public room heading and scenario sheets. It is
designed to be reviewable and shareable without exposing the hidden evidence,
clue ladders, or answer key.

The room is run using this participant pack alongside the private facilitator
pack. Participants should read the [room heading](room/room-heading.docx)
and the relevant scenario before working with the facilitator-provided questions
and evidence.

| Station | Incident | Scenario |
| --- | --- | --- |
| 1 | Double-Charge Disaster | [Open scenario](scenarios/station-1-scenario.docx) |
| 2 | Poisoned Queue | [Open scenario](scenarios/station-2-scenario.docx) |
| 3 | Cache of Old Memories | [Open scenario](scenarios/station-3-scenario.docx) |
| 4 | The Scream at p95 | [Open scenario](scenarios/station-4-scenario.docx) |

## ⏱️ The room loop

Each station takes **30 minutes**. Teams should:

1. **Investigate** the scenario, clues, and constraints.
2. **Decide** on answers and record the reasoning.
3. **Defend** the choices to a facilitator.
4. **Unlock** that station's code word when all answers are correct.

After all four stations, the team uses the four code words to complete the
final meta challenge

## 🔍 How to use the files

For each station:

1. Read the scenario to understand the system, failure mode, and constraints.
2. Review the complete question and evidence set supplied by the facilitator at
	the start of the station.
3. Complete the private question sheet as a team, recording the reasoning behind each
   decision.
4. Be prepared to explain which constraints ruled out the alternatives.

## 📏 Rules of the room

- Use only the information in the scenario and evidence materials.
- Do not rely on assumptions or facts that are not provided as evidence.
- Prefer the smallest change that meets the goal and all stated constraints.
- Write down the team's answers and show them to the facilitator.

The room is designed to be solved by reasoning from the scenario and evidence,
with facilitator guidance used to keep the team moving when needed. The private
facilitator repository contains the full evidence packs, clues, answer
sheets, scoring guidance, and private delivery notes. Anyone who might
who want to run the exercise can message the repository owner to request access.

## 📁 Repository structure

```text
assets/
├── system-design-escape-room-header.png
room/
└── room-heading.docx
scenarios/
├── station-1-scenario.docx
├── station-2-scenario.docx
├── station-3-scenario.docx
└── station-4-scenario.docx
README.md
```

The question sheets, clue packs, metrics, traces, and answer keys are kept in the
private facilitator repository.

## 🔒 Scope of this repository

This is the public participant pack. Facilitator guidance, question sheets,
hidden clues, evidence packs, and answer sheets are handled separately in the
private facilitator repository.