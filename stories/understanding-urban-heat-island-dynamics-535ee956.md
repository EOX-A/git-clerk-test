# Urban Heat Islands: Monitoring Extreme Temperatures from Space <!--{ as="img" mode="hero" src="https://workspace-ui-public.gtif-at-sc.hub-otc.eox.at/api/public/share/public-4wazei3y-02/UHTM_Wien/iStock-1173256779.jpg" }-->
#### Rising temperatures and dense impervious surfaces create microclimatic heat hotspots across metropolitan areas, threatening public health and urban ecosystems. Photo via [ESA / GTIF Austria](https://gtif-austria.github.io/public-narratives/urban-heat-trend-monitor.md).

## Understanding Urban Heat Islands & Available Earth Observation Resources
Cities across Europe and the globe face mounting climate risks due to the **Urban Heat Island (UHI)** effect. Dense infrastructure composed of concrete and asphalt absorbs solar radiation during the day and re-radiates thermal energy at night, resulting in city centers experiencing temperatures up to 10°C higher than surrounding rural landscapes ([European Commission JRC](https://publications.jrc.ec.europa.eu/repository/handle/JRC137891)). This severe thermal stress disproportionately affects vulnerable communities and strains municipal energy grids.

### Official Dashboard Narratives
Two official dashboard narratives provide in-depth scientific case studies and methodology on urban heat:
1. [Urban Heat Trend Monitor](https://gtif-austria.github.io/public-narratives/urban-heat-trend-monitor.md) (*GTIF Austria*): Developed by [OHB Digital Connect](https://ohb-dc.de/en/earth-observation-solutions/) under the [ESA Green Transition Information Factory (GTIF)](https://gtif.esa.int), this narrative demonstrates how downscaling coarse 1 km thermal data from Copernicus Sentinel-3 using Sentinel-2 optical indices (NDVI, NDBI) and superpixel segmentation provides district-level temperature trend modeling.
2. [Using Earth Observation to Track Urban Indicators: Biodiversity, Heat Islands, Flood Risk, and More](https://esa-eodashboards.github.io/RACE-narratives/IDEAS.md) (*ESA RACE Dashboard*): Created under the ESA IDEAS project with [Murmuration](https://murmuration-sas.com/) and [SISTEMA](https://www.sistema.at), this narrative examines the multidimensional [Health Oriented Urban Heat and air Pollution Indicator (HOUHPI)](https://race.esa.int/?indicator=IND1_1) combining satellite thermal observations, air pollution, demographic vulnerability, and healthcare accessibility.

### Catalog Dataset vs. Official Narratives
To distinguish between the catalog resources and the official case study narratives:
- **Catalog Dataset / Indicator**: The curated catalog provides the [Europe 2m Temperature & Climatology](https://services.sentinel-hub.com/) dataset (`europe-temperature-climatology`), delivering pan-European near-surface air temperatures and anomalies derived from meteorological observation networks and regional climate scenarios.
- **Official Narratives**: The narratives linked above deliver tailored local analytics, such as the TsHARP thermal downscaling pipeline in Vienna from GTIF and interactive indicator assessments from RACE.

## Europe 2m Air Temperature & Climatology Overview <!--{ as="eox-map" zoom=4 center=[15.0,50.0] projection="EPSG:3857" layers='[{"type":"Tile","properties":{"id":"terrain-light","title":"Terrain Light"},"source":{"type":"WMTSCapabilities","url":"https://tiles.maps.eox.at/wmts/1.0.0/WMTSCapabilities.xml","layer":"terrain-light_3857","attributions":"<a href=\"https://maps.eox.at\" target=\"_blank\">\u00a9 Terrain Light by EOX IT Services GmbH</a>, \u00a9 <a href=\"https://www.openstreetmap.org/copyright\" target=\"_blank\">OpenStreetMap</a>","crossOrigin":"anonymous"}},{"type":"Tile","properties":{"id":"climate-temperature","title":"Europe 2m Temperature & Climatology"},"source":{"type":"TileWMS","url":"https://services.sentinel-hub.com/ogc/wms/0635c213-17a1-48ee-aef7-9d1731695a54","params":{"LAYERS":"AWS_VIS_2MTEMPERATURE","TILED":true,"TRANSPARENT":true},"crossOrigin":"anonymous","attributions":"<a href=\"https://eox.at\" target=\"_blank\">Data Source</a>"}}]' }-->

## Data Sources & Methodological Outlook
### Data Sources & Attribution
- **Regional Temperature Catalog Layer**: [Europe 2m Temperature & Climatology](https://services.sentinel-hub.com/) via Sentinel Hub WMS services.
- **Official Case Studies & Research**:
  - [GTIF Austria Urban Heat Trend Monitor](https://gtif-austria.github.io/public-narratives/urban-heat-trend-monitor.md) by OHB Digital Connect & [ESA GTIF](https://gtif.esa.int).
  - [ESA RACE Dashboard Urban Indicators (IDEAS)](https://esa-eodashboards.github.io/RACE-narratives/IDEAS.md) by Murmuration, SISTEMA, and [ESA Future-EO](https://www.esa.int).
  - European Commission Joint Research Centre: [Urban Heat Island Study](https://publications.jrc.ec.europa.eu/repository/handle/JRC137891).

### Image Credits
- Cover photograph: Courtesy of [GTIF Austria](https://gtif-austria.github.io/public-narratives/urban-heat-trend-monitor.md) / iStock.

*This story is an AI-generated draft. Verify scientific data and satellite visualizations independently.*