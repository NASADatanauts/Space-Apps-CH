# NASA & ESA Open Data 

## Challenge 
Laelaeps-1 — Autonomous Threat Identification, Verification & Pursuit
(Autonomous ground robot tracking humans/objects)

Training models for person/vehicle detection, obstacle understanding, and real-time tracking.

| Data Type | Source | Link |
|----------|--------|------|
|Urban/field imagery for detection & tracking|	NASA Earthdata	|https://earthdata.nasa.gov/|
|High-resolution human activity datasets	|NASA SEDAC – Human Footprint, Population, Land Use|	https://sedac.ciesin.columbia.edu/|
|Rover navigation & autonomy datasets|	NASA JPL Robotics Datasets|	https://www-robotics.jpl.nasa.gov/datasets/|
|Object detection imagery	|NASA SpaceNet (now hosted by Maxar but still free)|	https://spacenet.ai/|
|Terrain & elevation	|NASA SRTM|	https://www2.jpl.nasa.gov/srtm/|


## C-UAS-1 — Counter Fiber-Optic Drone Detection
(Detect drones with non-RF sensors: thermal, optical, acoustic)
Thermal signatures of drones, optical detection, acoustic pattern recognition.

| Data Type | Source | Link |
|----------|--------|------|
|Thermal imagery sets (UAV, ground)	|NASA ECOSTRESS	|https://ecostress.jpl.nasa.gov/|
|Acoustic event detection datasets	|NASA Jet Propulsion Laboratory — Acoustic Data	|https://data.nasa.gov/|
|UAV identification & tracking	|ESA - Copernicus Drone/UAV datasets (Sentinel-2)	|https://dataspace.copernicus.eu/|
|High-frequency optical sequences	|NASA HICO Dataset|	https://oceancolor.gsfc.nasa.gov/data/hico/|


## C-UAS-2 — Autonomous Targeting for Low-Cost Interceptors
(Detect, classify, chase, intercept Shahed drones)
Train vision models to lock on to small flying objects in thermal/visual spectra.

| Data Type | Source | Link |
|----------|--------|------|
|High-frame-rate infrared flight targets	|NASA AAIR AI-Ready Aviation Dataset|	https://aair.cstcloud.cn/
|Aircraft & drone classification sets|	NASA Langley DAWN dataset	|https://data.nasa.gov/
|Satellite imagery of UAV objects|	ESA Sentinel-2|	https://dataspace.copernicus.eu/|
|Wind field & environment (for drone flight modeling)|	NASA MERRA-2|	https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/



## C-UAS-3 — Autonomous Drone Detection & Tracking
Detection and tracking in cluttered/urban terrain.
(Small UAV detection, trajectory estimation)

| Data Type | Source | Link |
|----------|--------|------|
|Multi-modal UAV detection datasets	|NASA UAM (Urban Air Mobility) Traffic Datasets	|https://uav.nasa.gov/data/|
|Video frames with flying drones	|IEEE UAV Datasets (NASA-funded research)	|https://www.kaggle.com/datasets/tariqsays/uav-detection|
|3D terrain and clutter maps	|NASA SRTM	|https://www2.jpl.nasa.gov/srtm/|
|Optical + IR fusion datasets	|NASA Earth Observations (NEO)	|https://neo.gsfc.nasa.gov/|





## C-UAS-4 — UAV Threat Classification & Prediction
(Classify drone types, predict intent)
Drone class identification, pattern-of-life analysis, trajectory forecasting.

| Data Type | Source | Link |
|----------|--------|------|
|Drone type classification images	|Agriculture Drone Dataset (NASA/USDA)	|https://data.nal.usda.gov/|
|Multi-modal flight data|	NASA UTM Flight Data|	https://utm.arc.nasa.gov/data.shtml|
|Airborne object classification	|NASA AERONET	|https://aeronet.gsfc.nasa.gov/|
|Flight behavior prediction inputs	|NASA OpenSky Flight Trajectories	|https://opensky-network.org/datasets/|




## C-UAS-5 — Non-Kinetic Neutralization
(Soft-kill: nets, spoofing, airflow)
Modeling soft-kill effects such as airflow-based diversion or spoofing.

| Data Type | Source | Link |
|----------|--------|------|
Turbulence & airflow simulation datasets	NASA Turbulence Modeling Resource (TMR)	https://turbmodels.larc.nasa.gov/
|GPS & GNSS spoofing simulation data	|ESA GNSS-SDR Datasets	|https://gnss-sdr.org/docs/|
 datasets/
|UAV aerodynamics data	|NASA Aeronautics Research Data Repository (ARDR)|	https://data.nasa.gov/browse?category=Aeronautics|




## EW-1 — EW Defense Against FPV Drones

(RF detection, jamming, passive sensors)
Passive RF detection, classification, jamming modeling.

| Data Type | Source | Link |
|----------|--------|------|
|Electromagnetic spectrum data	|NASA Spectrum Management SMDB	|https://spectrum.nasa.gov/|
|RF signature datasets	|GNU Radio / ESA Signal Datasets	|https://opendata.europeandspaceagency.org/|
|Comms interference modeling	|NASA SCaN Testbed Data	|https://www.nasa.gov/directorates/heo/scan/|


## EW-2 — Rapidly Deployable Mesh Network

(Mobile mesh, multi-hop, interference-resistant)
Routing algorithms, interference prediction, node failure scenarios.

| Data Type | Source | Link |
|----------|--------|------|
|Delay-tolerant networking datasets	|NASA DTN Research Testbed	|https://www.nasa.gov/content/|
|Satellite-free mesh data|	ESA OPS-SAT Experiments	|https://opssat1.esoc.esa.int/|
|RF interference maps|	NASA NEDIS / SEVAN	|https://data.nasa.gov/|

| Purpose | Best Tool | Link |
|----------|--------|------|
|Realistic RF + battlefield mesh|	EMANE	|https://www.nrl.navy.mil/itd/ncs/products/emane
|Academic simulations	|ns-3|	https://www.nsnam.org/|
|Quick prototype	|Docker mesh|	https://www.docker.com/|
|Mobile UAS/UAV mesh	|Mininet-WiFi	|https://github.com/intrig-unicamp/mininet-wifi
|Cross-country mesh with no physical radio	|ZeroTier / Tailscale	|https://www.zerotier.com/, https://tailscale.com/|
|Beginner-friendly|	GNS3	|https://www.gns3.com/|



## EW-3 — Passive Detection of Uncooperative Radios
Signal fingerprinting, TDOA / AoA localization, burst analysis.
(SIGINT, passive localization)

| Data Type | Source | Link |
|----------|--------|------|
|RF emitter classification sets	|ESA SDR Testwave Datasets	|https://opendata.europeandspaceagency.org/|
|Spectrum maps	|NASA electromagnetic data|	https://spectrum.nasa.gov/|
|Satellite SIGINT recordings (public domain)|	GRSS Datasets (NASA-affiliated)|	https://ieee-dataport.org/|


## IFF-1 — Friend/Foe Ground Classification From Air
(Identify people & vehicles from airborne sensors)
Recognizing people, vehicles, uniforms, patterns via multispectral + RGB.

| Data Type | Source | Link |
|----------|--------|------|
|High-res aerial imagery	|NASA NAIP Aerial Imagery	|https://www.fsa.usda.gov/programs-and-services/aerial-photography/imagery-programs/naip-imagery/|
|Vehicle/person detection datasets|	NASA SpaceNet / xView	|https://xviewdataset.org/|
|Multispectral detection	|ESA Sentinel-2|	https://dataspace.copernicus.eu/|



## Mar-1 — Maritime Infrastructure Monitoring & Threat Detection
(Undersea cables, pipelines, subsea threats)
AI-based submarine threat classification, pipeline anomaly detection, AIS spoofing.

| Data Type | Source | Link |
|----------|--------|------|
|SAR for ship detection	|ESA Sentinel-1 SAR|	https://dataspace.copernicus.eu/|
|Maritime vessel tracking	|ESA AIS Data (Open)	|https://marinetraffic.com/free-data|
|Sea-floor mapping	|NASA SWOT Ocean Topography Mission	|https://swot.jpl.nasa.gov/|
|Underwater anomaly signals|	ESA CryoSat & GOCE Gravity Data|	https://earth.esa.int/eogateway/missions|

###  Ocean Traffic & Maritime Monitoring Resources

| Resource Type | Name / Platform | Link | Notes |
|---------------|----------------|------|-------|
| AIS Data | MarineTraffic Free Data | [Link](https://www.marinetraffic.com/en/ais-data) | Real-time vessel positions, global coverage |
| AIS Data | AISHub | [Link](https://www.aishub.net/) | Aggregates AIS feeds from global contributors |
| AIS Data | ExactEarth | [Link](https://www.exactearth.com/) | Satellite AIS data, some free datasets |
| ESA / Copernicus | Copernicus Marine Environment Monitoring Service (CMEMS) | [Link](https://marine.copernicus.eu/) | Ocean currents, sea state, vessel environment |
| ESA / Copernicus | Sentinel-1 SAR Imagery | [Link](https://sentinel.esa.int/web/sentinel/missions/sentinel-1) | Detects ships and vessels even in cloudy conditions |
| ESA / Copernicus | Sentinel-2 Optical Imagery | [Link](https://sentinel.esa.int/web/sentinel/missions/sentinel-2) | Coastal monitoring, port activity |
| NOAA / US Gov | NOAA ERDDAP | [Link](https://coastwatch.pfeg.noaa.gov/erddap/index.html) | Real-time oceanographic observations |
| NOAA / US Gov | NOAA CoastWatch / VMS | [Link](https://coastwatch.noaa.gov/) | Vessel Monitoring System data for fisheries |
| NOAA / US Gov | National Geospatial-Intelligence Agency (NGA) | [Link](https://www.nga.mil/) | Maritime charts & ship routes |
| Open / Research | OpenShipMap / OpenAIS | [Link](https://openshipmap.org/) | Community-driven AIS and port data |
| Open / Research | Global Fishing Watch | [Link](https://globalfishingwatch.org/) | Vessel tracking with focus on fishing activities |
| Open / Research | Kaggle Maritime Datasets | [Link](https://www.kaggle.com/datasets?search=maritime+AIS) | Historical AIS, vessel tracking, port activity |
| Satellite / Remote Sensing | NASA SWOT | [Link](https://swot.jpl.nasa.gov/) | Ocean currents, sea surface height, coastal monitoring |
| Satellite / Remote Sensing | Copernicus Sentinel-3 | [Link](https://sentinel.esa.int/web/sentinel/missions/sentinel-3) | Sea surface temperature, color, ship detection potential |
| Satellite / Remote Sensing | ESA CryoSat & GOCE | [Link](https://earth.esa.int/eogateway/missions) | Underwater topography & gravitational anomalies |
| Tools / Software | OpenSeaMap | [Link](https://www.openseamap.org/) | Open-source maritime charts |
| Tools / Software | PyAIS / Python AIS Tools | [Link](https://github.com/Megaputer/pyais) | Parse AIS streams, build analytics |
| Tools / Software | MarineTraffic API | [Link](https://www.marinetraffic.com/en/ais-api-services) | Programmatic vessel tracking |
| Weather & Wind | NOAA Global Forecast System (GFS) | [Link](https://www.ncdc.noaa.gov/data-access/model-data/model-datasets/global-forcast-system-gfs) | Global weather & wind forecasts |
| Weather & Wind | OpenWeatherMap Marine API | [Link](https://openweathermap.org/api/marine) | Marine weather & wind conditions, API-based |
| Weather & Wind | Copernicus Marine Wind Data | [Link](https://marine.copernicus.eu/) | Ocean wind fields and forecast |
| Weather & Wind | ECMWF Ocean & Wind Datasets | [Link](https://www.ecmwf.int/en/forecasts/datasets) | High-resolution ocean & atmospheric wind data |




