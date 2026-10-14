# Agents

This is the public documentation site for Soundboy, a Raspberry Pi groovebox. Edit docs only. The instrument software is not in this repo.

## Site structure

Pages are Markdown files in the repo root:

| File | Live page |
| --- | --- |
| `index.md` | [/](https://stampman3000-jpg.github.io/soundboyassets/) |
| `architecture.md` | [/architecture](https://stampman3000-jpg.github.io/soundboyassets/architecture) |
| `hardware.md` | [/hardware](https://stampman3000-jpg.github.io/soundboyassets/hardware) |
| `dsp.md` | [/dsp](https://stampman3000-jpg.github.io/soundboyassets/dsp) |
| `UI.md` | [/UI](https://stampman3000-jpg.github.io/soundboyassets/UI) |
| `roadmap.md` | [/roadmap](https://stampman3000-jpg.github.io/soundboyassets/roadmap) |

`_config.yml` sets the Minima theme, the site title, and the short description. Images live in `assets/photos/`. `README.md` and `AGENTS.md` are excluded from the Jekyll build so they do not become extra pages.

`UI.md` is capitalised on purpose. The live URL is case-sensitive: `/UI` works, `/ui` does not. Do not rename that file.

## How Pages builds it

GitHub Pages uses its legacy Jekyll build. The source is the root of `main`. A push to `main` runs GitHub's `pages-build-deployment` workflow and publishes [https://stampman3000-jpg.github.io/soundboyassets/](https://stampman3000-jpg.github.io/soundboyassets/).

There is no `Gemfile` and no workflow file in the repo. Leave it that way unless someone asks. A committed `Gemfile` would change how Pages builds the site.

## Conventions

- One topic per root Markdown file. Keep the writing plain and short, in the same voice as the existing pages.
- Link between pages with relative links, the way `index.md` already does.
- Put new images in `assets/photos/` and link to them with relative paths.
- Leave the page files and photos alone unless the task is to change them.

## Rules

This repo is public.

- Do not add a home address, a personal email address, or private files.
- Make commits as `Stampman3000 <stampman3000@gmail.com>`.
- Do not rewrite history. No force-push, no rebasing commits that are already on the remote, and no amending a commit that has been pushed.
