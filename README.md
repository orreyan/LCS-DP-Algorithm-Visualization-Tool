# LCS Visualizer — Longest Common Subsequence

**Live demo:** [orreyan.github.io/LCS-DP-Algorithm-Visualization-Tool](https://orreyan.github.io/LCS-DP-Algorithm-Visualization-Tool/)

An interactive learning tool for the **Longest Common Subsequence (LCS)** algorithm. It animates how the dynamic programming table is filled, traces back the optimal subsequence, and reinforces understanding with quizzes, spoken narration, and explanations of each cell's dependencies.

---

## Technology

| Area | Technology |
| --- | --- |
| Languages | HTML5, CSS3, JavaScript (ES6+) |
| Browser APIs | Web Speech API (speech synthesis), Canvas API, Clipboard API |
| Dependencies | None (a single self-contained file) |
| Hosting | GitHub Pages |

---

## Features

### Algorithm Visualisation
- Step-by-step filling of the DP table, with play, pause, step, and reset controls and adjustable speed
- **Traceback animation** that reconstructs the longest common subsequence from the finished table
- Pseudocode highlighted in sync with each step
- Hover tooltips explaining every cell's value
- Live statistics for each run

### Learning Aids
- **Dependency highlighting:** click any cell to see which cells it was computed from and which cells depend on it
- **Recurrence explanations** showing which case of the LCS recurrence was applied
- **Quiz mode:** randomly generated questions during the animation (the next cell's value, which recurrence case applies, and traceback direction), with scoring
- **Voice narration:** spoken step-by-step explanations through the Web Speech API, with a choice of voice and a queue so narration stays in sync with the animation
- A help modal, an FAQ grouped by category, and further learning resources
- A history of previous inputs

### Analysis and Sharing
- A complexity chart comparing O(m x n) DP with the exponential brute-force approach
- Copy the current problem to the clipboard
- Contact and scheduling links

---

## Concepts Demonstrated

Dynamic programming, overlapping subproblems, optimal substructure, table-based (bottom-up) computation, solution reconstruction by traceback, time and space complexity analysis, and accessible, interactive algorithm teaching.

---

## Running Locally

Open `index.html` in any modern browser. No build step or server is needed.

---

## Author

**Reyan Fethi**
