# Clean Haldwani & friends (v3)

Static site, no build step.

## Deploy on Vercel
Import this folder at vercel.com/new -> Framework preset "Other", no build command, output directory "./".
Or run `vercel --prod` inside the folder.

## Structure
- index.html            the page (hero = @clean_haldwani, 3D ring = the other five, list = all six)
- assets/bg.jpg         background photo
- assets/logos/         profile pictures, named by handle (.png)
- assets/previews/      profile screenshots shown when a card flips, named by handle (.jpg)
- assets/posts/         the two Clean Haldwani posts used in the hero

## Update
- New screenshot or DP: replace the file with the same name and redeploy.
- Names, tags, card colours: the `profiles` array near the bottom of index.html.
- Hero text and bio lines: the HERO section near the top of index.html.
