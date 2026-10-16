# Codex brief — The Room Remembers

Work from `index.html` and `README.md`. Preserve the existing Room 01 mechanics and palette. Port them to **Godot 4** using small reusable scenes: `Player`, `Echo`, `PressurePlate`, `Door`, `Room`, and `AttemptMemory`.

Requirements:
- Deterministic physics, frame-rate-independent movement and robust mobile touch input.
- Save previous attempt as a timestamped trajectory; replay an echo on rewind. Echo must hold its final position.
- Trigger plates from player or echo, with a gate that responds deterministically.
- No puzzle-answer signs or pop-up instructions inside levels.
- A room graph to add new architectural spaces without revisiting the base movement architecture.
- A level verification harness: initial state, memory state, solver path, valid reachable exit, no deadlocks.
- Keep learning or adaptation OFF initially. Expose a `RoomDirector` with a small, declared list of designer-validated variations; train policies offline only after playtesting.
- Export Android first, but retain desktop/browser prototyping.

### Test checklist
- Door must not be reachable without using the echo.
- Rewind creates exactly one replayable echo of the prior run.
- An echo at the switch opens the gate long enough for player to cross.
- A direct run into a closed gate does not allow tunneling.
- Clear-memory resets the entire puzzle.
- Phone portrait / landscape renders with safe camera tracking.