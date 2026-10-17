# Command Pop! — Linux Learning Arcade

A small, mobile-friendly Linux command learning game inspired by a dream about an arcade marble shooter.


## Versions and themes

**Current: v0.4** — Switch between an airy pale-blue **Light mode** and deep-blue **Dark mode** with the button at the top of the game. Your choice is remembered in this browser (if browser storage is available); blue/green/purple command balls and full-color command pictograms are unchanged.

- [Play the current version](https://kalintech.github.io/command-pop/)
- [v0.4 preserved playable checkpoint](https://kalintech.github.io/command-pop/versions/v0.4/)
- [v0.3 original playable checkpoint](https://kalintech.github.io/command-pop/versions/v0.3/)
- [v0.3 archive branch](https://github.com/KaliNtech/command-pop/tree/archive/v0.3)

Both versions retain their own HTML source and notes inside [versions/](versions/), with Git commit history preserved.

## Play

The game is a single HTML page (`index.html`) that runs in a modern browser. No login, installation, backend, or external assets required.

- **Learn mode:** See an icon, a plain-language description, and the Linux command. Type the command to pop the matching bubble.
- **Recall mode:** Use the icon as a memory cue and retrieve the command. An answer option is available.
- **Command families:** Blue for navigation; green for file operations; purple for search and networking. Icons retain their individual colors.
- **Progress:** Score, streak, accuracy, and a short round of 12 bubbles.

## Starter commands

`pwd`, `ls`, `cd`, `mkdir`, `cat`, `cp`, `mv`, `rm`, `grep`, `ip addr`, `ping`.

The application **simulates answers**; it does **not** run a Linux shell, modify files, or change network settings. Sample commands and descriptions are educational shorthand, not a replacement for command manuals.

## Project direction

The next steps are to test the illustrations as memory aids, record commands encountered during real training, and refine the game's learning mechanics. Future possible games include a simulated terminal and network configuration challenges. These are ideas, not features of this version.

## Provenance

- **v0.1** — First playable prototype: picture-driven command bubbles and score.
- **v0.2** — Learn mode now displays the command directly.
- **v0.3** — Eleven command icons updated to use a consistent blue/green/purple category system with multi-color pictograms.

Design and development explored through human–AI collaboration. This is an early prototype, not a finished product.