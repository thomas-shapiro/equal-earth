# Equal Earth

A sphere divided into 195 segments of equal area, one for each country of the world: the 193 member states of the United Nations and its 2 non-member observer states.

Fun fact: If scaled to the size of the Earth, each segment would cover 2.62 million km².

**Live page:** https://thomas-shapiro.github.io/equal-earth/

## How it is made

The segments come from a 195-faced Catalan-like polyhedron projected onto the sphere.
https://github.com/thomas-shapiro/catalan-like-solid-generator
https://github.com/thomas-shapiro/catalan-like-solid-viewer
The vertices were then adjusted so that every segment covers exactly 1/195 of the sphere. Countries are assigned to segments so that neighboring segments correspond to neighboring countries on Earth, which was impossible for some countries that either have too many neighbors or too few neighbors. In those cases, approximate mapping was used.

## Files

- `index.html` – the viewer (three.js, loaded from a CDN)
- `data/globe.json` – segment geometry and country assignment
- `textures/` – flag textures

## License

MIT © 2026 Thomas Shapiro. You may use, copy, modify and distribute this work, provided the copyright notice is kept. Flag images are adapted from [flag-icons](https://github.com/lipis/flag-icons) (MIT); see `LICENSE`.
