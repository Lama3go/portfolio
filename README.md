# Lama Almarwani | UX/UI Designer Portfolio

A single page portfolio site for Lama Almarwani, a UX/UI designer based between Al-Madinah and Vancouver. It shows mobile app screens, safety and awareness posters, illustration and packaging work, plus her background and contact details.

Built with plain HTML, CSS and JavaScript. No framework and no build step. Hosted on GitHub Pages.

## What is on the site

- **Selected Screens:** a case study for a fertility care mobile app (Problem, Process, Solution, Learned tabs).
- **The Rest Of The Work:** a filterable poster wall (Awareness, Safety campaigns, Illustration, Packaging) with a full size viewer.
- **About and Route:** her story, skills and career path.
- **Contact:** email, phone and location.

## Project structure

```
work-main/
  index.html      the whole site (HTML, CSS and JS in one file)
  README.md       this file
  images/         every project image
```

## Projects and their images

| Project | Category | Image file |
|---|---|---|
| Mobile app screens (fertility care app) | UX / UI | `fertility-care-app-screens.png` |
| Stop plastic pollution | Awareness | `stop-ocean-plastic-pollution.png` |
| They are not part of the job | Safety campaign | `harassment-awareness-poster.png` |
| Putting this up can break your back | Safety campaign | `manual-handling-safety-poster.png` |
| This will fracture you | Safety campaign | `slip-and-trip-safety-poster.png` |
| Road and site safety | Safety campaign | `road-safety-bus-stop.png` |
| Amusement park maintenance | Safety campaign | `amusement-park-maintenance-poster.png` |
| Night forest | Illustration | `night-forest-illustration.jpg` |
| The future is green | Packaging | `future-is-green-packaging.jpg` |

## How to add or change a project

1. Put the image inside the `images/` folder. Use lowercase words separated by dashes, for example `my-new-poster.png`.
2. Open `index.html` and search for `const WORKS`.
3. Copy one block and change `srcs`, `title`, `desc`, `year`, `tools` and `type`. The path must start with `images/` and match the file name exactly, including letter case.
4. If a project has more than one image, name the extra ones with `-2`, `-3`, `-4` after the cover name (`my-new-poster-2.png`) and set `count` to the total number of images.

## Publishing on GitHub Pages

1. Save the files, then open Source Control in VS Code.
2. Write a short message, press **Commit**, then **Sync Changes**.
3. Wait a minute or two, open the site and hard refresh with `Ctrl+F5`.

`index.html` must stay in the root of the repository for GitHub Pages to find it.

## Contact

lama.almarwani.11@gmail.com
