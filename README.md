# BIOL 215 Island Biogeography Lab

An interactive teaching app for a second-year ecology lab at the University of Victoria. Students map real islands on satellite imagery, measure their area and isolation, fit the species–area relationship (S = cA^z) for plants and birds, test what else explains species richness, predict species loss from habitat loss, and edit and run the R code behind every result.

**Open the app:** https://drlyndonduff.github.io/island-biogeography-lab/

The app is written in R (Shiny) and runs entirely in the web browser with [Shinylive](https://posit-dev.github.io/r-shinylive/) and webR, so nothing needs to be installed and no server is needed. It works on computers and tablets. The first load downloads R into the browser and takes about 20–60 seconds.

## Data and credits

- **Hakai Institute 100 Islands Project** (CC BY 4.0). Plants: doi:10.21966/CZ48-D388; Obrist et al. 2022, *Ecology and Evolution* 12: e9270. Birds: doi:10.21966/10tk-4956; Obrist et al. 2020, *Proceedings of the Royal Society B* 287: 20200108.
- **Galápagos plants:** Johnson & Raven 1973, *Science* 179: 893–895, via the `faraway` R package. Island coordinates © OpenStreetMap contributors (ODbL); the Gardner islet near Española is approximate.
- **Maps:** Esri World Imagery; © OpenStreetMap contributors. Map and measuring tools: Leaflet and leaflet-measure.

This repository contains only the exported website. The app's source (`app.R`) is included in `app.json`.
