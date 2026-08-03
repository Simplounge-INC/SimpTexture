# TEMPORARY Mineclub assets — REMOVE BEFORE RELEASE

Used with permission from the Mineclub administration for development only.
Condition: must be removed/replaced before public release.

Files (prefixed tmp_mc_ in the standard texture folders):
- assets/clubtopia/textures/titles/tmp_mc_ttt_banner.png  (from tabletop/banner.png, bottom banner)
- assets/clubtopia/textures/block/tmp_mc_ttt_{tile,x,o}_{tl,tr,bl,br}.png  (from tabletop/pieces.png)

Referenced by:
- assets/clubtopia/models/block/ttt_*.json  (repoint to clubtopia:block/ttt_* placeholders on removal)
- assets/minecraft/font/default.json        (provider for  — remove on removal)

Original placeholder tiles still exist at assets/clubtopia/textures/block/ttt_*.png —
reverting the model JSONs restores them instantly.
- assets/clubtopia/textures/block/tmp_mc_c4_{empty,red,yellow}.png  (from tabletop/pieces.png)
