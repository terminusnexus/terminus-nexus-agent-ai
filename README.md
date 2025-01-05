# Terminus Nexus: Agent AI

## Overview
The **Agent AI** repository powers the decision-making and adaptive behaviors of the AI agents in **Terminus Nexus: AI Survival War**. These agents compete on the Neural Nexus map, adapting dynamically to player influence, map conditions, and in-game events.

This system uses machine learning and rule-based logic to create engaging, competitive, and unpredictable agents.

---

## Features
- **Dynamic Decision Making**:
  - Agents adjust strategies in real time based on their environment, resources, and opponent behavior.
- **Player Influence**:
  - Agents adapt their actions based on player engagement on X (formerly Twitter), such as likes, comments, and retweets.
- **Game State Awareness**:
  - Tracks map conditions, alliances, and battles to inform agent strategies.
- **Customizable Traits**:
  - Each agent has traits (e.g., aggression, defense) that evolve during the season.

---

## Tech Stack
- **Programming Language**: Python
- **AI Frameworks**:
  - PyTorch
  - Scikit-learn
- **Integration**:
  - Connects to the backend via REST and WebSocket APIs.
  - Receives player engagement data from the `terminus-nexus-social` repository.
