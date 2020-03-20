---
title: "Project: Flow"

nodes:
  - name: "<strong>Phase 1: Horizontal Tree</strong>"
    description: "Goal: Edit and visualise a horizontal tree of project dependencies."
    color: rgb(227, 244, 248)
    nodes:
      - name: Visualise
        done: true
        nodes:
          - name: Nested List Layout
            nodes:
              - name: Nodes
              - name: Edges
          - name: Colors
            done: ture
      - name: YAML Schema
        description: Node name, descripton, color and done flag.
        done: true
      - name: Jekyll Integration
        description: Usable as a custom Jekyll type, Projects, or as an template include.
        done: true


  - name: "<strong>Phase 2: Directed Graph</strong>"
    color: rgb(255, 229, 199)

  - name: "<strong>Phase 3: ...</strong>"
    color: rgb(241, 224, 253)

---

*Flow* captures a set of ideas about cognition that I've been thinking about for around 7 years. An exploratory project to structurally and visually represent knowlege, understanding and thought to increases the rate of inforamtion exchange between humans and humans and computers.

## Phase 1: Horizontal Tree

In Phase 1 I built the first prototype of Flow to represent, edit and visualise a tree of project dependecies as a horizontal flow chart. Primarly built for [Project: TurnTime](/projects/turntime) and now being used for Flow project management too.

Information is represented as a tree of nodes with properties and meta information and stored as YAML. The tree is [marked-up][includes/flow]{:target="_blank"} as HTML nested lists and [styled][sass/flow]{:target="_blank"} as a horizontal tree with visible node edges.

No JavaScript is used for the presentation. It's just simple and clean HTML and CSS which also works great on mobile.

Next I'll add the ability to edit trees locally in the browser. I'll use this as an opportunity to create my own frontend JavaScript framework.

## Phase 2: Directed Graph

In Phase 2 I'll step up the complexity and work with digraphs. I'm not sure what specific problem I'll tackle, maybe game AI for [Project: TurnTime](/projects/turntime) or decomposting a subset of English into hierachies.

## Phase 3: ...

There will be many more phases, things I'd like to explore: artithmetic and set-like operations, knowlege comparison and exchange, inheritence and evolution, and much more.


[includes/flow]: https://github.com/seanpackham/seanpackham.github.io/blob/master/_includes/flow.html
[sass/flow]: https://github.com/seanpackham/seanpackham.github.io/blob/master/_sass/flow.scss
