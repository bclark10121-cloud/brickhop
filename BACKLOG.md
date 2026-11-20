# Brickhop: backlog

Updated 2026-11-20. BC decides the order.

## Done

- 0.5.1 Kit movement (2026-11-20): run, jump and fall now come from the shared kit block K1 (kit 1.19.0), with the 0.5.0 numbers as this game's tuning. Same feel: a bot run through 1-1 matched 0.5.0 on every step. No 60 frame cap (kit 1.17.1).
- 0.5.0 Floating stick and jump feel (2026-11-20): a touch stick that appears under the thumb on the left half replaces the left, right and Down buttons. Movement fixes from a three-agent review: a camera with no smoothing or swing, corner correction, hidden blocks push the hero down, jump height blends from walk to run, foes drawn smoothly, the landing pose lines up, shake only on a hit. Jump retune: a crisp release, no float at the top, a heavier fall, stomp bounces work like a jump, air speed kept. Full screen by default in the browser (kit 1.17.0). TOUCH and LAND checks added.
- 0.4.2 Higher jumps at 120 frames a second (2026-11-19): the game steps 120 times a second, gravity eases through the top of the jump, jumps go about 4.5 blocks high (5.3 with a running start), a frame rate readout in Tester tools. First game on the new standard G6.20.
- 0.4.1 Smooth jumps (2026-11-19): fixed the skipped frame at the top of the jump. The hero is drawn between physics steps, so 90 and 120 Hz phones no longer stutter. Letting go of jump slows the climb smoothly instead of stopping it in one step. One air pose through the top of the jump. FEEL check added.
- 0.4.0 Foes and sounds (2026-11-19): the teal pill bug (stomp it into a ball, kick the ball into other foes) and the hopping spring frog, Kenney sounds for jump, coins, stomps, bumps, hurt, pipe and flag, spinning toy coins and a star coin from Gemini.
- 0.3.0 Look and sound (2026-11-19): toy render blocks, pipes and ground from a Gemini block sheet, the wind-up beetle walker (walk and squashed frames), a toy meadow background that scrolls slower than the level, "Pixelland" on the start screen and "Carefree" in play, the name Brickhop kept and the title font Lilita One on the start screen, game page and Game Shelf.
- 0.2.0 The hero (2026-11-19): BC's Goggles hero from Gemini and Meshy, rigged with Idle, Run, Jump and Hit motions, rendered side-on into an 17-frame sprite sheet. Idle, run, jump, fall and hit poses in play. The hero bounces on the start screen too.
- 0.1.0 Gray box (2026-11-19, not shipped yet): 1-1 Toybox Meadow as level data, run and jump with coyote time, jump buffer and variable height, coin blocks, a Sprout block, bricks, a hidden block, coins, three star coins, walkers to stomp, a checkpoint, a secret room through a down pipe, the flag with a best time. Soft fail: hits and falls cost coins. Breezy, Standard and Classic. Run Hold, Toggle or Always. Touch buttons. New start screen scene.

## Now

1. BC's check of 0.5.1 on his phone: the floating stick, the jump and landings, the camera. 0.5.1 should feel the same as 0.5.0.
2. BC picks the next release from the ideas below.

## Asked for by BC, not built yet


## Ideas to choose from (BC picks by number)

1. More foes: a shell foe that slides, a hopping foe, a piranha-style pipe plant (all original).
2. Coins dropped by a hit bounce out and can be picked back up.
3. Score and best (G4.17, kit `score.gd`): due at a coming release per the studio rollout table.
4. Level 1-2 to 1-4 and a castle level, once BC says the jumping feels right (G4.13).
5. LDtk level editor for levels (studio backlog).

## Later

None.

## Not planned (they break the pillars)

- Lives and game over (soft fail, BC 2026-11-19).

## Decisions from BC

- 2026-11-20, 12:23 PM: "work on the kit sprint first before any new games", then 12:33 PM: "go with your suggestion first" (move Brickhop onto K1). 0.5.1.
- 2026-11-20, 9:03 AM: "There still are problems jumping ... landing in different spots and skipping a frame" and "change the touch controls so there isnt a left/right and a joystick that is free floating". Then picked "Add retune now" and "Ship v0.5.0 now". 0.5.0.
- 2026-11-19, 10:24 PM: "jumping still skips a beat and the character need to jump higher, my device is 120 fps" and "that needs to be a standard to support up to 120 fps". 0.4.2 and G6.20.
- 2026-11-19, 10:16 PM: "jumping itself is good, but it seems to skip a frame at the top of the jump". Fixed in 0.4.1.
- 2026-11-19, 10:00 PM: "Continue to the next release": foes, sounds and coin art as 0.4.0.
- 2026-11-19, 9:47 PM: "go with your suggestions all 3 in 1 release": toy render art, Patch.gg music, keep the name Brickhop and pick the title font (Lilita One).
- 2026-11-19, 9:24 PM: hero C, Goggles. 9:09 PM: the main character comes through Gemini and Meshy before the MVP.
- 2026-11-19, 8:53 PM: start building N21 now (no plan step first), soft fail, clean toy render art.

