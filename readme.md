# Simple Atlas

```bash
yarn install
yarn run hello-world
```

This is a slightly modified recreation of Mike Bostock's [World Atlas TopoJSON](https://github.com/topojson/world-atlas/blob/master/.gitignore). It will generate a TopoJSON map of the world, with the English name of each country as its ID.

His repo will give you the 1:110m scale version, the 1:50m scale version, and corresponding TSV files with additional data for each country. This only gives the 1:110m scale version. In place of the ISO N3 number as the ID, I use the English name.

The file will be generated in the a directory named `dist`. The downloaded data from Natural Earth will be in the `map-data` directory.
