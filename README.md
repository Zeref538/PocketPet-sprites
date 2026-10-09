# PocketPet sprites

Artwork for [PocketPet](https://github.com/Zeref538/PocketPet) and [PocketPet Care](https://github.com/Zeref538/PocketPet-Care), kept separate from Unity projects for easier downloads.

`pup-smooth/frames/` contains a new care set: idle, eating, happy, playing, studying, sleeping, washing, and drinking. Each has twelve separate transparent 192-by-192 frames. Original `pup/` artwork is preserved. Contact sheets, source sheets, and GIF previews are under `pup-smooth/`.

`ui/phone-actions/` contains eight matching button shapes with different colors and action pups. `props/phone-care/` contains the study table, bed, and food bowl. `previews/` contains layout concepts and actual game captures.

For the lab, use the compact [care artwork download](https://github.com/Zeref538/PocketPet-sprites/releases/tag/v1.1.0). It contains only the 96 new frame PNGs, eight buttons, three props, and frame instructions. Files named `previews/phone-game-*.png` are actual Windows game captures; the other preview files are design concepts.

`ui/status-bars/` contains separate transparent frames and fills for hunger, happiness, energy, and cleanliness. These are prepared images for later use, not implemented gameplay.

`props/care/` contains six additional transparent props for future use: food bowl, water bowl, soap, grooming brush, toy ball, and pet bed. These are prepared artwork; they are not implemented in the game. The six PNGs total 435,945 bytes.

- `hamster/`: 33 frames, 212x187
- `otter/`: 64 frames, 185x142
- `wolf/`: 48 frames, 202x187
- `pup/`: 48 frames, 294x149
- `bunny/`: 32 frames, 137x107
- `ui/`: 44 UI pieces: buttons (and pressed versions), icons, square and round buttons, bars, speech bubble

Each frame is named `<animation>_<frame>.png`. Animations: idle, happy, sad, crying, eating, playing, studying, sleeping.

## Download

Mac Terminal:

```bash
cd ~/Desktop
git clone --depth 1 https://github.com/Zeref538/PocketPet-sprites.git
```

Or open the repo on GitHub, click the green **Code** button, then **Download ZIP**.

To get new frames later: `cd ~/Desktop/PocketPet-sprites && git pull`
