---
title: Building Xenotheric — a Metroid-inspired project in Godot 4
date: 2025-12-13 12:00:00 +0000
categories: projects
tags: godot metroidvania gamedev devlog
---

I’ve started a Metroid-inspired side-scroller called **Xenotheric**, built with Godot 4. Here’s a quick overview of what I’m aiming for and how I’m approaching the work.

## What I’m building

- Exploration-first platformer with interconnected rooms and soft backtracking.
- Snappy movement: tight jump arcs, fast ledge grabs, and responsive air control.
- Combat that rewards positioning over button-mashing.
- Light progression: upgrades that change traversal (think dash, morph/slide, mobility perks).

## Project state

- Core systems live in the [repo](https://github.com/qrzn23/xenotheric). The current focus is on movement feel, collision stability, and camera framing that stays readable during fast traversal.
- Level blockout uses simple test rooms so iteration stays quick while mechanics bake.
- CI/build scripts target Godot 4; the goal is reproducible exports once content ramps up.

## Near-term roadmap

1) Movement polish: refine jump buffering, coyote time, and slope/edge handling.  
2) Camera: finalize deadzone/framing rules so combat and traversal both stay readable.  
3) Combat loop: enemy protos with simple tells, stagger rules, and hit-stop tuning.  
4) Upgrades: first traversal upgrade (dash/slide) with gated test rooms.  
5) Tools: quick room loader and hot-reload-friendly debug overlay for metrics (speed, jump height).

## Longer-term beats

- Biome shaping and tileset pass once traversal and camera rules are locked.
- Audio pass for movement, hits, and ambience.
- Export pipeline for desktop first; stretch goal for handheld-friendly builds.

If you want to watch progress or try out builds as they land, the repo is the place to follow along. Feedback on movement feel and readability is especially welcome.
