# pangpang

A Codex desktop pet: a white cat with golden eyes and a pink nose.

## Install

Copy this folder to `~/.codex/pets/pangpang/`, fully quit Codex, reopen it, then select **pangpang** in Pets settings.

```bash
mkdir -p ~/.codex/pets
cp -R pet.json spritesheet.webp ~/.codex/pets/pangpang/
```

If you cloned the repo, you can copy the whole directory:

```bash
cp -R pangpang ~/.codex/pets/pangpang
```

## Behavior

- Calm idle, plus a short click / hover acknowledgement
- Left and right movement while dragging
- Focused task, waiting, review, and failure states
- 16-direction gaze tracking

## Package

Codex v2 spritesheet: 1536 x 2288, 8 x 11 cells, 192 x 208 per cell, `spriteVersionNumber: 2`.

License: MIT.
