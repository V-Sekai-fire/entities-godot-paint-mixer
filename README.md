# entities-godot-paint-mixer

A Godot project that mixes two paint colours the way pigments mix, through spectral reflectance, and shows the palette between them.

## What it is for

The mixer upsamples each colour to a reflectance spectrum, blends the spectra with the Kubelka-Munk model, and converts the result back to sRGB, so blue and yellow make green rather than grey. The scene lets you pick the two colours and the number of swatches.

## Run

Open `project.godot` in the Godot editor and run the main scene.

## Licence

MIT; see `LICENSE`. The mixing script also carries its upstream author's MIT notice.
