---
nodes:
  - name: "Phase 1: Singleplayer"
    color: rgb(227, 244, 248)
    nodes:
      - name: Design Language
        nodes:
          - name: Object Definition
            description: Cards, stacks (hand, deck, etc), turns, phases etc will share a common definition.

          - name: Action Definition
            description: Card and stack manipulation.

          - name: Event Definition
            description: Triggers that occur at the start, during, end or on events.

      - name: User Interface
        nodes:
          - name: Drag & Drop
            nodes:
              - name: HTML Drag & Drop API
                nodes:
                  - name: Drag Card to Stack
                    done: true
                    description: Add card to end of stack list.
          - name: Window Layout
            nodes:
                - name: Grid Layout
          - name: Stack Layout
            nodes:
              - name: Horizontal Layout
              - name: Vertical Layout
          - name: Card Layout


  - name: "Phase 2: Multiplayer"
    color: rgb(255, 229, 199)

  - name: "Phase 3: Steam"
    color: rgb(241, 224, 253)

  - name: "Phase 4: Services"
    color: rgb(253, 224, 224)

---

# TurnTime Project

I'm splitting TurnTime development into four phases. See the [Roadmap Overview](#roadmap-overview) for high-level tasks in each phase.

## Phase 1: Singleplayer

In Phase 1 I'm solving the most challenging aspects of the project: the design language for card game design and the user interface.

Games will be limited to singleplayer (solo or AI), but the engine is being designed with multiplayer in mind.

Lastly, I'll prototype artificial intelligence which can learn to play any game from the rules and trial and error.

TurnTime will be distributed as a free Electron app.

## Phase 2: Multiplayer

In Phase 2 I'll implement a UDP multiplayer architecture for the Electron client and prototype a REST multiplayer architecture for Phase 4.

People will be able to connect to multiplayer games via port and socket (no NAT punchthrough).

TurnTime will distributed as a premium early access Electron app.

## Phase 3: Steam

In Phase 3 I'll implement Steam Peer-to-peer Networking, Steam Workshop and prepare for a full Steam release.

TurnTime will distributed off and on Steam as a premium Electron app.

## Phase 4: Services

In Phase 4 I'll implement online services: cloud saving, game design analytics, play testing analytics and more.

TurnTime will distributed off and on Steam as a premium Electron app and as a SaaS web application.

# Roadmap Overview
