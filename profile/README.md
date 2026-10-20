<p align="center">
  <a href="https://geolith.app"><img src="https://github.com/geolith.png" width="96" alt="geolith"></a>
</p>

<h3 align="center">Planet-scale geocoding, tiles and routing from static files</h3>

<p align="center">
  OpenStreetMap + Overture Maps, built on one machine, served from object storage at the edge.<br>
  No database. No server farm.
</p>

---

**What we build**

- **`.glx`** — a single-file geocoding index. Search, autocomplete, reverse geocoding and place outlines, answered with HTTP range reads from a Worker, a browser tab or a laptop. Try it: [glx.geolith.app](https://glx.geolith.app)
- **search** — a Pelias-compatible geocoding API served from one `.glx` file. [Docs and benchmarks](https://docs.search.geolith.app)
- **geolith** — the build engine: OpenStreetMap + Overture → vector tiles (PMTiles / MLT), routing files and `.glx` indexes. [geolith.app](https://geolith.app)

**Benchmarks** are measured on the same data and the same machine as Nominatim, Photon and Pelias, all in Docker, with the harness published: [docs.search.geolith.app/benchmarks/engines](https://docs.search.geolith.app/benchmarks/engines/).

**Contact:** [contact@geolith.app](mailto:contact@geolith.app) · security reports: [security@geolith.app](mailto:security@geolith.app)

<sub>Map data © OpenStreetMap contributors (ODbL) and Overture Maps Foundation.</sub>
