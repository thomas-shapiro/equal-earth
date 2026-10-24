# Equal Earth

A sphere divided into 195 segments of equal area, one for each country of the world: the 193 member states of the United Nations and its two non-member observer states, the Holy See and the State of Palestine.

Scaled to the size of the Earth, each segment would cover about 2.62 million km².

**Live page:** https://thomas-shapiro.github.io/equal-earth/

## How it is made

The segments come from a 195-faced Catalan-like polyhedron projected onto the sphere. The vertices were then adjusted so that every segment covers exactly 1/195 of the sphere. Countries are assigned to segments so that neighbouring segments are, as far as possible, neighbouring countries on Earth.

Each flag is framed for its own segment so that all of its stripes and emblems remain visible. Basic colours (red, blue, green, yellow and so on) are shared across all flags.

## Files

- `index.html` – the viewer (three.js, loaded from a CDN)
- `data/globe.json` – segment geometry and country assignment
- `textures/` – flag textures

## License

MIT © 2026 Thomas Shapiro. You may use, copy, modify and distribute this work, provided the copyright notice is kept. Flag images are adapted from [flag-icons](https://github.com/lipis/flag-icons) (MIT); see `LICENSE`.
