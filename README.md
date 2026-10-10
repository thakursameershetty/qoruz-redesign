# Qoruz Creator Profile Redesign

A redesign of the Qoruz creator profile page (Alia Bhatt), made for the Junior UX Designer assignment.

- `index.html`: landing page with the note, the Figma link and previews, served at `/`
- `qoruz-redesign.html`: the redesigned page, served at `/redesign`
- `qoruz-original.html`: a recreation of the original page for comparison, served at `/original`

The pages are standalone: images and scripts are inlined, so there is no build step. To add the Figma link, set `FIGMA_URL` near the bottom of `index.html`.

## Deploy

Import the repo in Vercel with the **Other** framework preset and no build command. `vercel.json` handles routing.
