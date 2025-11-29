# NASA & ESA Open Data — Mapped to Each Challenge

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
Useful NASA/ESA Open Datasets
Data Type	Source	Link
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
 delay-tolerant-networking
|Satellite-free mesh data|	ESA OPS-SAT Experiments	|https://opssat1.esoc.esa.int/|
|RF interference maps|	NASA NEDIS / SEVAN	|https://data.nasa.gov/|



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


