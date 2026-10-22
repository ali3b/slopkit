# slopkit

The game kit of the Sloponator: everything a game (or the small, free language model writing it) needs on top of
licensed **Synty Studios** assets.

- **Runtimes:** Phaser 3 (2D) and three.js (3D) libraries for loading content packs, input, audio, saves, cameras.
- **Components:** every catalogued Synty asset as a ready-to-use thing: `world.spawn('soldier_us_rifle')` gives a
  working, animated, colliding character.
- **Templates and examples:** games that already run, with marked regions to change.
- **Scene scripts:** describe a scene, get a video of the characters playing it out, or a cutscene in a game.
- **For weak models:** one-task recipes, errors that say how to fix them, `kit check` (PASS/FAIL with
  screenshots) and `kit help-me`, which sends a request to a stronger model that answers it and fixes the docs.

Assets come from the pipeline, [ali3b/sloponator](https://github.com/ali3b/sloponator) (`slop build`). The kit
depends on it only through its manifest formats, so a game never contains pipeline code. The plan and the review
that led here: [sloponator/docs/PLAN.md](https://github.com/ali3b/sloponator/blob/master/docs/PLAN.md).

## Progress

| Phase | What | Status |
|---|---|---|
| P5 | Runtimes: core, Phaser, three.js; components | — |
| P5b | Scene scripts and video | — |
| P6 | Agent layer: `kit` CLI, MCP, templates, examples, docs | — |
| P7 | Help loop and evals (baseline: sloponator spike 2) | — |
| P8 | Migration proof: Monty and Off Road | — |

## Licence

Code and docs: MIT. **Synty assets are not included** and are never committed; rendered content packs stay in
local, git-ignored stores.
