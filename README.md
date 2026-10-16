# The Room Remembers

A quiet, top-down architectural puzzle game about rooms that remember your previous attempts.

**Current version:** Chapter I — five introductory rooms + **UNFINISHED BUSINESS** (Room 06), an optional advanced challenge.

**Play:** https://sashank-810.github.io/the-room-remembers/

## Controls

- Desktop: WASD or arrow keys to move; R to rewind.
- Mobile: on-screen movement buttons and REWIND.
- ROOMS opens the level selector for unlocked rooms.
- Restart (top-right arrow) clears the current room's memory.

## What's new in v0.4

- Room 06: **UNFINISHED BUSINESS**, featuring finite-duration echoes and interactions triggered by the *sequence* of events.
- The first five rooms remain available and mechanically unchanged.
- Progress is stored locally in the browser. Previous v0.3 save data is carried forward.
- Room 06 reports the number of attempts and active play time on completion.
- No text-based solution hints.

## Development

This is a static HTML + JavaScript prototype, hosted by GitHub Pages from the `main` branch. No Node build, external server, login or Codex subscription is required to play it.

For new game mechanics, we prioritize fair discoverability, meaningful memory interactions, fast retries, and deterministic puzzle solutions. Reinforcement learning remains a future research direction, not part of this build.

## QA notes

The browser prototype was tested in Chromium on desktop and an iPhone-sized viewport. Scripted tests cover the intended Room 06 solution, blocked shortcuts, and regression checks for Rooms 01–05. The actual difficulty needs validation by human playtesting.
