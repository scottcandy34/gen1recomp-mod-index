Draws the overworld as a 3D voxelized diorama. Also supports experimental first-person, third-person and VR cameras.

## What it does

The flat Gen 1 map is rebuilt as a perspective 3D scene made of voxel tiles. Buildings, trees, ledges, water and characters gain real height and depth. The camera can be tilted from a gentle 15° overview all the way to free-roam first- and third-person views.

## Key features

- **Voxel diorama camera** — ladder of pitch angles (15° → 35° → 50° → 75°) plus experimental 1ST / 3RD person free-roam
- **3D battles** — fight on the map or on floating discs; optional Pokémon Stadium battle models (player supplies their own US Stadium 1.0 ROM)
- **Water** — pixel waves, sky/sun/moon reflections, optional screen-space ray-marched shoreline reflections
- **Shadows** — real cast shadows from a second sun pass (buildings, trees, people)
- **Anti-aliasing** — 2× / 4× supersampling of the diorama
- **Daytime control** — SYNC / DAY / NIGHT / DUSK / DAWN / CYCLE
- **V-CURVE** — bend the world over the horizon up to a half-sphere
- **Render distance** — FIT / WIDE / WIDER / WIDEST / OFF
- **VR** (PCVR via OpenXR) — STANDARD first-person, DIORAMA tabletop mode, and DIORAMA-MR (green-screen mixed reality)

## Stadium models

Stadium battle models are **not** included. You must supply a Pokémon Stadium (US) 1.0 ROM (md5 `ed1378bc12115f71209a77844965ba50`). The mod extracts and builds the 151 models locally; the ROM is never kept.

## Controls

Most options are also rows on the in-game OPTIONS menu. Number keys 3 / 5 / 6 / 7 / 8 / 9 and SELECT step the main ladders. Free-roam cameras use mouse / right stick to look and continuous camera-relative movement.

## Notes

- Conflicts with `ds_fp_ceiling`
- Requires `engine_internals` permission
- Redistribution of non-derivative code is restricted after v1.6.0 without permission

**Categories:** ART
**Tags:** voxel, 3d, overworld, camera, stadium, vr, diorama, graphics

Source: https://github.com/scottcandy34/DramaticShapeVoxelMod-latest
