# Project Overview

This project is an interactive simulator of a creature world with a Web UI written in OCaml. The goal of the project is to help creatures stay away from a polluted river and to bring the sick ones to a hospital.

The project is a simulation game where creatures move randomly in a rectangular space. The top of the space is a toxic river, and the bottom is a hospital. Creatures that touch the river get sick, change color, and become contagious. The game ends when all creatures are contaminated.

The user can interact with the simulation by grabbing and moving creatures with the mouse.

# Building and Running

TODO: Add instructions on how to build and run the project.

# Development Conventions

*   The project is written in OCaml using the Js_of_ocaml compiler and the Eliom library.
*   Each creature is managed by a Lwt thread.
*   Creatures are displayed as DOM elements.
*   Mouse events are handled with the `Lwt_js_event` module.
*   The game should be graphically pleasant.
*   The simulation parameters should be controllable with various forms, cursors or checkboxes on the page.
*   Collision detection between the creatures should be optimized, for instance by using a quadtree.
