# Planetary Researcher

A browser-based planetary field research game about landing on procedurally generated worlds, taking instrument readings, keeping a journal, cataloging discoveries, and investigating anomalous planetary signatures.

The game is self-contained: open `index.html` in a browser and play. Saves are stored in the browser's local storage.

## Play

- Local: open `index.html`.
- GitHub Pages, once enabled/deployed: `https://jackwayne234.github.io/Planetary-Researcher-Browser-Game/`
- Itch.io upload: zip the contents of this repo, or use the prepared itch build zip.

## Features

- Procedural star systems and planets.
- Surface exploration with movement, time of day, weather, and terrain discovery.
- Scientific instruments for atmosphere, radiation, stars, solar data, magnetics, LIDAR, radar, infrared, spectroscopy, seismology, and radio.
- Player-owned journal with saved instrument readings.
- Catalog for biological discoveries.
- Anomaly discovery loop:
  - subtle proximity cues,
  - evidence collection across multiple instruments,
  - confirmed anomaly IDs,
  - map markers,
  - Fleet reporting.
- Glossary tab for instrument, HUD, anomaly, and map terminology.
- Save migration for older browser saves.

## Test Seed

Use seed:

```text
anomaly-qa-06-10
```

On planet `TrES 6361e`, useful anomaly test locations include:

- `SEI-484` at `(-7, 12)`: Seismo, Radar, LIDAR.
- `RAD-538` at `(-2, 12)`: Radio, Stars, Mag.
- `THM-775` at `(8, -3)`: IR, Spec, Radar.

## Development

This is a plain HTML/CSS/JavaScript project. There is no build step.

Recommended local check:

```bash
node --check js/*.js
```

Then open `index.html` in a browser and test a short play session.

## Release Notes

See [CHANGELOG.md](CHANGELOG.md).
