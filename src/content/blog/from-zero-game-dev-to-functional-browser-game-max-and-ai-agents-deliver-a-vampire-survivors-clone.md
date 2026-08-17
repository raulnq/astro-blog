---
title: "From Zero Game Dev to Functional Browser Game: Max and AI Agents Deliver a 'Vampire Survivors' Clone"
description: "A recent live stream showcased the rapid development of a browser-based, 'Vampire Survivors-like' game, leveraging AI agents to overcome the developer's lack of prior game development experience. The session highlighted an agent-driven workflow, transitioning from initial research to a fully playable prototype in under two hours."
date: 2026-07-27
tags: ["ai-development","game-dev","phaser","typescript","agentic-ai"]
source: "https://www.youtube.com/watch?v=dpj_SyxjPCg"
author: "Maximilian Schwarzmüller"
---
In a recent live stream, developer Max embarked on a "vibe coding" experiment to build a browser-based, "Vampire Survivors-like" game from scratch, leveraging AI agents despite having no prior game development experience. The ambitious project utilized a robust AI-driven workflow centered around the Pi coding agent within the Herder terminal multiplexer, primarily powered by GPT-5.6-Sol for research and planning, and Grok 4.5 for implementation. After exploring various options, the team settled on Phaser 4, TypeScript, and Vite for the core technology stack, emphasizing a code-only approach without a visual game editor.

The session quickly moved from basic project setup to implementing the game's first vertical slice, featuring a bounded arena, keyboard-controlled player, and auto-firing projectiles against randomly spawning enemies. Initial challenges, such as blurry visuals, were swiftly addressed by the AI through device pixel density rendering. Notably, the agents also autonomously generated player and enemy spritesheets in a cartoon illustration style, integrating them seamlessly into the Phaser engine. By the end of the stream, the prototype boasted a functional heads-up display (HUD), a health and death system for both player and enemies, a 60-second wave timer culminating in 'You Won' or 'Game Over' screens, and a New Game restart option, showcasing rapid development in an unfamiliar domain through an iterative, agent-centric approach.
