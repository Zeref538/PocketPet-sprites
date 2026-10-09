# Twelve-frame care artwork

Eight loops: idle, eating, happy, playing, studying, sleeping, washing, and drinking. Each has twelve distinct transparent PNG frames at 192 by 192. Use the files in `frames/` in numeric order at 12 frames per second.

Frames share one scale per action, centered horizontally with the same ground baseline. The PNGs replace whole sequences; they are not extra frames to mix between the old six-frame poses. GIF previews use 80 milliseconds per frame for inspection, approximately 12.5 frames per second.

Original sheets are preserved in `sheets/`. Cuts follow transparent gaps because the sheet spacing was not perfectly even. Very faint alpha outside the sprites was removed. Contact sheets show the final cuts. `checks.json` records frame counts, unique pixel hashes, transparency, and source-cell edge contacts.

Two playing cells report alpha at a cut edge. Their complete pup and ball were visually checked in the contact sheet. The set needs animation review in the target game; extra frames alone do not guarantee smooth motion.

All eight sequences were imported into PocketPet Care, and the seven care actions were observed in its Windows build. Real integration screenshots are in `../previews/phone-game-*.png`.
