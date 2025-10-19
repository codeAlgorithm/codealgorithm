 # codeAlgorithm — Algorithms ● Visualizations ● Mind Maps

[![GitHub followers](https://img.shields.io/github/followers/codeAlgorithm?label=Follow&style=flat-square)](https://github.com/codeAlgorithm)
[![Website](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=flat-square)](https://codeAlgorithm.github.io)
[![License](https://img.shields.io/github/license/codeAlgorithm/codeAlgorithm?style=flat-square)](LICENSE)
[![Repo Size](https://img.shields.io/github/repo-size/codeAlgorithm/codeAlgorithm?style=flat-square)](https://github.com/codeAlgorithm)

---

<p align="center">
  <img alt="animated demo" src="https://raw.githubusercontent.com/codeAlgorithm/assets/main/header-animated.gif" width="820" />
</p>

> **A curated playground for learning algorithms** — interactive visualizers, clear implementations (C++ / Python / Java), and a structured mind map for interview & contest prep.

---

## 🔥 Quick links
- 🔗 Profile: https://github.com/codeAlgorithm  
- 🌐 Live demo: https://codeAlgorithm.github.io  
- 📚 Repos: `algorithms-visualized`, `ds-and-algos`, `interview-prep`

---

## 🚀 Highlights
- Interactive sorting & graph visualizers (play, pause, step).
- Algorithm mind map (Mermaid) for quick revision paths.
- Multi-language reference implementations with tests.
- Short, annotated solutions ideal for interviews and contests.

---

## 🧭 Algorithm Mind Map (Mermaid)
> Paste this block into any GitHub README page — GitHub supports Mermaid diagrams.

```mermaid
flowchart LR
  ALGO[Algorithms]
  SORT[Sorting<br/>Quick • Merge • Heap • Radix]
  GRAPH[Graphs<br/>BFS • DFS • Dijkstra • MST]
  DP[Dynamic Programming<br/>Knapsack • LIS • Tree DP]
  STR[Strings<br/>KMP • Rolling Hash • Suffix]
  GREEDY[Greedy<br/>Interval • Huffman]

  ALGO --> SORT
  ALGO --> GRAPH
  ALGO --> DP
  ALGO --> STR
  SORT --> GREEDY
  GRAPH --> DP
