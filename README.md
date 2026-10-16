# The Room Remembers

**Chapter I — The House Notices (v0.3)**

A quiet, original architectural puzzle game for desktop browsers and mobile devices. Your previous attempts can leave echoes that interact with the environment.

## Play

https://sashank-810.github.io/the-room-remembers/

- Move with **WASD** or the **arrow keys**, or use the touch controls.
- Press **R** or **REWIND** to preserve a memory of your last attempt.
- Use **ROOMS** to revisit unlocked rooms.
- The circular reset button clears the current room and its remembered attempts.
- The game intentionally does not display solutions.

## Chapter I — Five rooms

01. **AFTERIMAGE**
02. **STRINGS ATTACHED**
03. **BAD HABITS**
04. **THE PERFECT EXIT**
05. **DÉJÀ WHO?**

This update introduces a deceptive-exit puzzle and multiple remembered echoes, while retaining the first three rooms.

**Progress migration:** Returning v0.2 players who had reached Room 03 can enter Room 04 without replaying the introduction. New players start with Room 01. Progress saves locally in your browser; clearing the site's storage resets progress.

## Development

The prototype is self-contained in `index.html` (HTML, CSS, Canvas and vanilla JavaScript). GitHub Pages serves it directly from `main`; no build or Codex usage is required to publish it.

Puzzle behavior is deterministic and designer-authored in this release. It does **not** currently use reinforcement learning; offline-trained adaptive room behavior is a future experiment once the core puzzles have been thoroughly playtested.

Preserve the quiet architectural aesthetic, accessible controls, and fair puzzle rules.
