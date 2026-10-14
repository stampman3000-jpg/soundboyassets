# Soundboy

Soundboy is a Raspberry Pi groovebox: a small instrument for making music, built around a Pi, an OLED screen, physical controls, and its own sound engine. The project mixes hardware, the on-screen interface, sequencing, and DSP.

This repository is the public documentation site. The instrument software is not in here.

## Live site

[https://stampman3000-jpg.github.io/soundboyassets/](https://stampman3000-jpg.github.io/soundboyassets/)

- [Home](https://stampman3000-jpg.github.io/soundboyassets/)
- [Architecture](https://stampman3000-jpg.github.io/soundboyassets/architecture)
- [Hardware](https://stampman3000-jpg.github.io/soundboyassets/hardware)
- [DSP](https://stampman3000-jpg.github.io/soundboyassets/dsp)
- [UI](https://stampman3000-jpg.github.io/soundboyassets/UI)
- [Roadmap](https://stampman3000-jpg.github.io/soundboyassets/roadmap)

The UI link uses a capital `UI`, same as the file `UI.md`. A lowercase `/ui` address does not work.

## Preview locally

GitHub Pages builds these Markdown files with Jekyll and the Minima theme. To preview the same way on your machine, install Ruby and Bundler, then from this folder:

```bash
bundle init
bundle add github-pages
bundle exec jekyll serve
```

Open [http://127.0.0.1:4000/](http://127.0.0.1:4000/).

Do not commit the `Gemfile` or `Gemfile.lock` that those commands create. Pages is set up to build the Markdown already in the repo, from the root of `main`.
