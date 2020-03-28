---
title: "Project: Flow"

nodes:
  - name: "<strong>Phase 1: Horizontal Tree</strong>"
    description: "Visualise and edit horizontal trees."
    color: rgb(227, 244, 248)
    nodes:
      - name: Schema
        description: Name, descripton and color.
        done: true
        nodes:
        - name: Layout
          description: Nested unordered lists.
          nodes:
            - name: Styling
              description: Nodes and edges.
      - name: Server
        description: Write changes to YAML.
        nodes:
        - name: JavaScript Client
          description: Add, edit, delete and move nodes.


  - name: "<strong>Phase 2: Directed Graph</strong>"
    color: rgb(255, 229, 199)

  - name: "<strong>Phase 3: ...</strong>"
    color: rgb(241, 224, 253)

---

*Flow* captures a set of ideas about cognition that I've been thinking about for around 7 years. An exploratory project to structurally and visually represent knowlege, understanding and thought to increases the rate of information exchange between people and people and computers.

## Phase 1: Horizontal Tree

In Phase 1 I built the first prototype of Flow to represent, edit and visualise a tree of project dependecies as a horizontal flow chart. Primarly built for [Project: TurnTime](/projects/turntime) and now being used for Flow project management too.

Information is represented as a tree of nodes with properties and meta information and stored as YAML. The tree is [marked-up][includes/flow]{:target="_blank"} as HTML nested lists and [styled][sass/flow]{:target="_blank"} as a horizontal tree with visible node edges.

No JavaScript is used for the presentation. It's just simple and clean HTML and CSS which also works great on mobile.

Next I'll add the ability to edit trees locally in the browser. I'll use this as an opportunity to create my own frontend JavaScript framework.

## Phase 2: Directed Graph

In Phase 2 I'll step up the complexity and work with digraphs. I'm not sure what specific problem I'll tackle, maybe game AI for [Project: TurnTime](/projects/turntime) or decomposting a subset of English into hierachies.

## Phase 3: ...

There will be many more phases, things I'd like to explore: artithmetic and set-like operations, knowlege comparison and exchange, inheritence and evolution.


[includes/flow]: https://github.com/seanpackham/seanpackham.github.io/blob/master/_includes/flow.html
[sass/flow]: https://github.com/seanpackham/seanpackham.github.io/blob/master/_sass/flow.scss
