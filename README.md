# Triowillow 1.0 TEST
Native Java/Canvas Android 8+ Heteromino region-fencing puzzle.

Fence all white cells into edge-connected regions of exactly three cells. Regions with the same shape AND the same orientation cannot share an edge. Rotated or reflected shapes may touch when their orientations differ. X cells are blocked, outside every region. Tap between two white tiles to toggle a fence. Twelve unique 4x4 blocker boards have twelve distinct solutions; each board has four X tiles and one connected white area.

Saved trio palette and current-region counts, GG007 icon/menu/site/privacy, unlimited undo/reset. Offline, no ads, analytics, account or requested permissions. Settings and completed-puzzle marks stay on device. External studio link opens the browser.

Independent Python enumerates all 52 connected three-cell sets and exact covers. Java independently enumerates triples by coordinate connectivity, compares translated coordinate sets and side contacts, then checks every legal exact cover plus 40000 random 24-edge wall masks per board against production floodfill and normalized bit-shape signatures. One solution per board; bounds, solve, undo and replay pass. Adapter navigation, settings, privacy, fence taps, next, levels and persistence pass. Actual drawing pixels inspected, not phone screenshots. Phone runtime, performance and browser handoff QA incomplete. Signed TEST only; not final or Play published.

Current 803-entry registry, 118 recovered README/source records and exact Lassofem cumulative stage found no Heteromino match. Shares Gapwillow three-cell pieces but covers every white cell with variable regions, no circled seeds or empty-gap rule. Shares Stonefence fence input but three-cell regions and orientation-dependent neighbor exclusion replace four-cell regions and fenced-side clues. Unlike Shapechain, identical orientation is forbidden only between edge neighbors; no corner chains or rotation/reflection equivalence. Known Heteromino genre, not a global invention. Partial recovered corpus, not ALL-local. Rules https://www.janko.at/Raetsel/Naoki/Heteromino.htm .

Download signed test APK on MEGA: https://mega.co.nz/#!YBFHVYiL!_8QmS7_3lAAewAF0lpe5gaQH1darusMn6JwPWKGsRS0

APK SHA256: e82c5e02a091029942f925a8d97f0e3c3d27ae9761bb8fd4059a5a325ac628ee
Full Git source upload remains pending; source is preserved in the private archive.
