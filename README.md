# LiteRadio

Worldwide radio web app with an interactive map, station search, country and genre filters, a live player, HLS support, and browser-local favourites.

## Run locally

Download the code and run `python3 -m http.server 8000` in this folder. Open http://localhost:8000. No API keys or build step required.

## Publish

GitHub Settings → Pages → Deploy from a branch → main → / (root). This private repository requires a plan supporting private GitHub Pages. Changing visibility is your choice.

## Dependencies

Radio Browser directory, Leaflet 1.9.4, OpenStreetMap map tiles, hls.js 1.6.13. Internet access is required. Streams come directly from broadcasters. Only HTTPS stations are requested; stream availability, redirects, formats and geographic restrictions can prevent playback. Favourites stay in the same browser. This app is independent of Radio Garden.

## Validation

JavaScript syntax check passed. Automated browser testing could not run because the browser executable is absent from this environment. Real audio, live API and map loading need verification in your browser.
