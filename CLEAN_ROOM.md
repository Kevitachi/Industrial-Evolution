# Clean-room rules

This mod must be publishable. It takes *gameplay ideas* from IndustrialCraft 2 (ideas, mechanics and
balance numbers are not protected), never its *expression* (code, assets, text, data files).

## Never copy into this repo

- Code from the IC2 jar, the decompiled 1.12 source, or the private 1.21 port (`IC2_Repository`),
  including by retyping or translating it, and including the `ic2.api` package.
- IC2 textures, models, sounds, GUI layouts (`guidef/*.xml`), lang text or recipe files.
- The names "IndustrialCraft", "IC2" or the `ic2` namespace.

## Allowed

- Mechanics described in plain words in [DESIGN.md](DESIGN.md) ("a battery box stores 40 000 units and
  outputs 32 per tick"), written from gameplay knowledge, not from source code.
- Vanilla Minecraft / NeoForge APIs and patterns from their docs and examples.
- Our own names: items, blocks and the energy unit get their own names here.

## Workflow

1. Describe a feature's behaviour in DESIGN.md first.
2. Implement it from that description only, against the NeoForge API.
3. Give it original assets and text.
