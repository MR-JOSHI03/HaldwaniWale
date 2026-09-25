# Haldwani, on your feed

Static site. No build step.

## Deploy on Vercel
- Drag-and-drop: vercel.com/new -> import this folder, Framework preset "Other", no build command, output directory "./".
- CLI: `npm i -g vercel` then run `vercel --prod` inside this folder.

## Edit
- Profiles, bios, colours: the `profiles` array near the bottom of `index.html`.
- Logos: put images in `assets/` (e.g. `assets/haldwaniwale.png`) and set `logo:"assets/haldwaniwale.png"` for that profile.
- Background photo: replace `assets/haldwani-bg.jpg` (keep the same name).
