# CommitHabit

A lightweight, terminal-based habit and daily task tracker built for developers who prefer living in the command line.

## What Problem Does It Solve?
Switching between a code editor and heavy, browser-based productivity apps breaks focus. CommitHabit lets developers log daily habits, check off tasks, and view their consistency streaks without ever leaving their terminal.

## How It Works
- **Local-First Storage:** Saves all tasks and streak data locally in a clean JSON file so it works offline and can be version-controlled.
- **Simple CLI Commands:** Add, complete, and list tasks using straightforward terminal flags (e.g., `habit add "Review PRs"`, `habit done 1`).
- **Streak Tracking:** Automatically calculates consecutive days a habit has been completed.
