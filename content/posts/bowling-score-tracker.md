---
weight: 6
title: "Bowling Score Tracker"
github: https://github.com/hungcq/bowling-score-tracker
technologies: Go, Unit Testing
#cover:
#  image: /images/bowling-score-tracker.png
summary: >
  This backend, built in Golang, tracks and calculates ten-pin bowling scores.
  The project is defined by a rigorous, maintainable test suite that emphasizes not just coverage, but clarity and reliability.
---

This project is a backend application for tracking and calculating scores in ten-pin bowling, implemented in **Golang**.
It emphasizes modularity through a clear separation of concerns,
using a port-adapter architecture that keeps game logic independent from APIs and storage,
ensuring long-term maintainability and flexibility for future improvements.

A cornerstone of this project is its **rigorous, sustainable test suite**.
I hold myself to exceptionally high standards for unit testing-not just achieving broad coverage
but prioritizing **clarity, reliability, and maintainability**. Tests focus on public API behaviors,
employ real implementations and fakes where practical, and avoid brittle coupling to implementation details.
Each test is named for the behavior it verifies, structured for readability with clear "given-when-then" patterns,
and written to read naturally so intent and outcomes are always explicit.
This principled approach enables fast,
safe evolution of the codebase and gives developers complete confidence in the system's correctness.

![Unit tests](/images/bowling-score-tracker.png)