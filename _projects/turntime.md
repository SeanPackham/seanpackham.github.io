---
title: "Project: TurnTime"

nodes:
  - name: "<strong>Phase 1: Singleplayer</strong>"
    color: rgb(227, 244, 248)
    nodes:
      - name: Layout
        description: Window, stacks and cards.
        nodes:
        - name: Interaction
          description: Drag and drop stacks and cards.
      - name: Design Language
        description: Objects, actions and events.


  - name: "<strong>Phase 2: Multiplayer</strong>"
    color: rgb(255, 229, 199)

  - name: "<strong>Phase 3: Steam</strong>"
    color: rgb(241, 224, 253)

  - name: "<strong>Phase 4: Services</strong>"
    color: rgb(253, 224, 224)

---

I'm splitting TurnTime development into four phases. See the [Roadmap](#roadmap-overview) for high-level tasks in each phase.

## Phase 1: Singleplayer

In Phase 1 I'm solving the most challenging aspects of the project: the design language and user interface.

Games will be limited to singleplayer (solo or AI), but the engine is being designed for multiplayer.

Lastly, I'll prototype artificial intelligence which can learn to play from the rules, observation and trial and error.

TurnTime will be distributed as a free Electron app.

## Phase 2: Multiplayer

In Phase 2 I'll implement a UDP multiplayer architecture for the Electron client and prototype a REST multiplayer architecture for Phase 4.

People will be able to connect to multiplayer games via port and socket (no NAT punchthrough).

TurnTime will be distributed as a premium early access Electron app.

## Phase 3: Steam

In Phase 3 I'll implement Steam Peer-to-peer Networking, Steam Workshop and prepare for a full Steam release.

TurnTime will distributed off and on Steam as a premium Electron app.

## Phase 4: Services

In Phase 4 I'll implement online services: cloud saving, game design analytics, play testing analytics and more.

TurnTime will distributed off and on Steam as a premium Electron app and as a SaaS web application.
