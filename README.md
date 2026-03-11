# WSET Level 3 Interactive Wine Map

An interactive study tool for the WSET Level 3 Award in Wines. Explore 96 wine regions and 150 sub-appellations across 14 countries on a single-page map dashboard.

**[Live Demo](https://yeujack.github.io/wset3_interactive_map/wine_map_dashboard.html)**

![Screenshot](https://img.shields.io/badge/regions-96-7b2d8b) ![Screenshot](https://img.shields.io/badge/sub--appellations-150-0f3460) ![Screenshot](https://img.shields.io/badge/countries-14-e8c97a)

## Features

- **Interactive world map** — Leaflet.js with clustered markers, polygon boundaries for every region and sub-appellation
- **Tasting notes & grape data** — climate, terroir, key grapes, and study notes for each region drawn from WSET L3 curriculum
- **Geographical features** — 43 annotated features including rivers, mountain ranges, wind patterns, and ocean currents with tooltips explaining their viticultural importance
- **Region search & navigation** — collapsible sidebar with search, grouped by WSET study chapters; dropdown switcher to jump between regions
- **Sub-appellation drill-down** — click any region to see its sub-zones with individual polygon boundaries, grape tags, and detailed notes
- **Wine-colored grape tags** — grapes are color-coded by wine style (red, white, rosé, sparkling, sweet)
- **Zero dependencies to install** — single self-contained HTML file, no build step required

## Regions Covered

| Country | Regions |
|---------|---------|
| France | Bordeaux, Burgundy (Chablis, Cote de Nuits, Cote de Beaune, Cote Chalonnaise, Maconnais), Beaujolais, Loire Valley, Northern Rhone, Southern Rhone, Alsace, Champagne, Languedoc-Roussillon, Provence, SW France |
| Italy | Piedmont, Veneto, Friuli-Venezia Giulia, Trentino-Alto Adige, Tuscany, Umbria, Abruzzo, Campania, Puglia, Sicily |
| Spain | Rioja, Ribera del Duero, Navarra, Rueda, Rias Baixas, Priorat, Penedes, Jerez, Catalonia |
| Germany | Mosel, Rheingau, Rheinhessen, Nahe, Pfalz, Baden, Franken |
| Portugal | Douro/Port, Vinho Verde, Dao, Bairrada, Alentejo |
| USA | Napa Valley, Sonoma, Paso Robles, Santa Barbara, Willamette Valley, Columbia Valley, Walla Walla |
| Australia | Barossa Valley, Eden Valley, Clare Valley, McLaren Vale, Coonawarra, Adelaide Hills, Hunter Valley, Margaret River, Yarra Valley, Tasmania |
| New Zealand | Marlborough, Hawke's Bay, Central Otago, Martinborough, Wairarapa, Nelson |
| South Africa | Stellenbosch, Constantia, Paarl, Franschhoek, Swartland, Walker Bay, Elgin |
| Chile | Casablanca, Maipo, Colchagua, Rapel, Aconcagua, Leyda, Bio Bio |
| Argentina | Mendoza, Uco Valley, Salta, Lujan de Cuyo, Patagonia |
| Austria | Wachau, Kremstal, Kamptal, Burgenland |
| Hungary | Tokaj |
| Greece | Naoussa, Nemea, Santorini, Cephalonia, Mantinia |

## Geographical Features

43 annotated features visible at zoom level 5+:

- **Rivers** (13) — Loire, Gironde/Garonne, Ciron, Rhone, Rhine, Mosel, Douro, Ebro, Danube, Po, Layon, Saar, Nahe
- **Mountains** (16) — Vosges, Alps, Andes, Sierra de Cantabria, Massif Central, Mt Etna, Table Mountain, Apennines, and more
- **Winds** (4) — Mistral, Cape Doctor, Van Duzer Corridor, Tramontane
- **Ocean Currents** (3) — Gulf Stream, Humboldt Current, Benguela Current
- **Special Features** (7) — Landes Pine Forest, Galets Roules, Carcassonne Gap, Gimblett Gravels, Lake Garda, San Pablo Bay, False Bay

Each feature includes a tooltip explaining its importance to local viticulture.

## Tech

Single HTML file (~2900 lines) using:
- [Leaflet.js](https://leafletjs.com/) for mapping
- [Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster) for marker clustering
- [CARTO](https://carto.com/) dark basemap tiles

No build tools, frameworks, or server required. Just open the HTML file in a browser.

## Usage

Open `wine_map_dashboard.html` in any modern browser, or visit the [live demo](https://yeujack.github.io/wset3_interactive_map/wine_map_dashboard.html).

- Click a marker or sidebar entry to view region details
- Use the dropdown in the info panel to switch between region groups
- Zoom in to see sub-appellation boundaries and geographical features
- Toggle the sidebar with the arrow button for a fuller map view

## Credits

Created by Jack Yeu, with the help of notes from Wang Haitian.

## License

MIT
