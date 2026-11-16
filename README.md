# portfolio

Personal site — [milwil-2.github.io](https://milwil-2.github.io)

- `/` is `public/index.html`: one self-contained page, the bio round a triangle you can throw, spin and
  drop, with mini golf behind "play". Astro copies it to the site's root as it is.
- `/projects/` is the Astro page `src/pages/projects.astro`: dark, monospace, minimal. Lists projects
  with links to GitHub and live demos where available.

## dev

```sh
npm install
npm run dev      # localhost:4321: the triangle at /, projects at /projects/
npm run build    # output to dist/
```

## adding projects

Edit `src/data/projects.ts`. Include a `live` URL for hosted projects to get the live badge.

Deploys automatically to GitHub Pages on push to `main`.
