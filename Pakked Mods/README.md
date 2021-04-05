
# Glassworks
Build pak of a collection of glass shapes.

Requires Hydronix ModLoader and Hydronix Store.

Caveats and known issues:

- [ ] Unable to highlight-outline glass objects (possible limitation of game itself, according to Max)
- [ ] Glass material, especially its transparent and refractive properties, may cause deleterious framelag at high vis counts
- [X] AVERTED: **CRITICAL** Store items compiled with Hydronix store in mind, are not accessible to non-Hydronix users (requires Hydronix Store or MacGregor Emporium)
- [X] AVERTED: **URGENT** Store hook removes Simple Chair from store (Move to ModLoader in anticipation of move to UMH)
- [x] FIXED: **URGENT** Attempting to place glass buildables in non-placeable open world areas results in being unable to exit placement mode
- [X] FIXED: Simple Collision Hull incorrectly shaped (Affects certain physics interactions)
- [x] FIXED: Build gridguides not showing up (repaired under scrutiny of new template)

# Restrictor Pipe
Adds a restrictor pipe to the Bridgepour pipe store which reduces water pressure all the way down to 1%.

Requires HydroUMH

Known issues:

- [X] FIXED: UV texturing is bad in pipe's waist, resulting in a flat matte coloration
- [x] FIXED: Restrictor Pipes not saving in the savefile


# --REMOVED-- MacGregor Emporium
At this time, this is a simple break-out of Hydronix Store code from the Hydronix Core.

All credit still due to Team Hydronix

Caveats and known issues:

- [x] FIXED: **URGENT** Castle walls and second floor are not being spawned in
