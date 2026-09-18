# Awesome-Mine-Fleet-Management

## Top Mine Fleet Management Tools Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**
*Focused on Mining Fleet Management, Mine Dispatch, Haulage Optimization, Equipment Telemetry & Autonomous Mining*
**Last updated: September 2026**

This repository tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Mine Fleet Management Systems (FMS)**. These tools monitor, dispatch, optimize, and automate mining fleets including haul trucks, loaders, excavators, drills, LHDs, light vehicles, and autonomous equipment.

**Examples** include HxGN MineOperate, Modular Mining DISPATCH, Wenco, Micromine Pitram, GroundHog, RPMGlobal FleetPlanner/FleetOptimiser, ASI Mining Mobius, Epiroc Mobilaris Mining Intelligence, Sandvik OptiMine, and Cat MineStar Fleet.

Modern mine FMS platforms typically combine **real-time equipment positioning, GPS/GNSS, dynamic truck-shovel dispatch, haul-cycle optimization, payload and production tracking, equipment health, short-interval control, fleet analytics, mine-road routing, grade/blend management, and increasingly autonomous haulage**.

**Open-source emphasis**: This section is heavily expanded with active and useful projects for building self-hosted mining fleet systems — including **mine-dispatch simulators, truck-dispatch optimization algorithms, GPS/telematics platforms, IoT gateways, MQTT infrastructure, GIS/routing engines, autonomous-driving frameworks, telemetry databases, dashboards, and mining analytics**.

> **Important distinction:** There are currently very few mature open-source projects that are direct drop-in replacements for enterprise mine FMS products such as DISPATCH, MineOperate, Wenco, Pitram, or MineStar Fleet. The open-source ecosystem is therefore best viewed as a collection of **building blocks for constructing a custom mine FMS**, rather than a single equivalent product.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or repositories.

## Table of Contents

* [SaaS/Hosted Platforms](#saashosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)
* [Mining Dispatch & Simulation Projects](#mining-dispatch--simulation-projects)
* [Fleet Tracking & Telematics](#fleet-tracking--telematics)
* [IoT & Industrial Data Infrastructure](#iot--industrial-data-infrastructure)
* [GIS, Routing & Mine Road Optimization](#gis-routing--mine-road-optimization)
* [Autonomous Mining & Robotics](#autonomous-mining--robotics)
* [Telemetry Databases & Analytics](#telemetry-databases--analytics)
* [Recommended Open-Source Mine FMS Architecture](#recommended-open-source-mine-fms-architecture)
* [Commercial → Open-Source Mapping](#commercial--open-source-mapping)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

* **[Hexagon HxGN MineOperate](https://hexagon.com/solutions/mine-fleet-management)**
  Mine fleet management ecosystem for optimizing haulage, blending, fleet utilization, operational workflows, and situational awareness across mining operations.

* **[Modular Mining DISPATCH](https://www.komatsu.com/en-us/technology/smart-mining/loading-and-haulage/dispatch)**
  Komatsu's foundational fleet management system providing real-time visibility and control of loading and hauling, dynamic truck assignments, haulage tracking, fueling, blending, and mine-plan execution.

* **[Wenco Mining Systems](https://www.wencomine.com/our-solutions/mining-fleet-management)**
  Mining fleet management platform for trucks, excavators, shovels, and auxiliary equipment with real-time production monitoring, dispatching, equipment assignment, and operational dashboards.

* **[Wenco Dynamic Dispatch](https://www.wencomine.com/our-solutions/dispatching)**
  Dynamic dispatching system that assigns trucks to loading and dumping locations while considering production, blending, fueling, activity, and operational constraints.

* **[Micromine Pitram](https://www.micromine.com/pitram/)**
  Underground and surface mining fleet and production management system supporting mobile data collection, dispatch, equipment tracking, production events, telemetry, reporting, and operational control.

* **[GroundHog Fleet Management System](https://www.groundhogapps.com/open-pit-mining-fleet-management-system/)**
  Surface mine FMS for monitoring and optimizing shovels, excavators, haul trucks, graders, water trucks, and other equipment, with dynamic dispatch and production control.

* **[GroundHog Underground FMS](https://www.groundhogapps.com/underground-fms/)**
  Underground fleet management and activity-sequencing platform supporting real-time resource allocation, shift planning, equipment utilization, and dynamic rescheduling.

* **[RPMGlobal FleetPlanner](https://rpmglobal.com/product/fleetplanner/)**
  Cloud-based mining haulage planning and fleet optimization platform using 3D visualization and travel-time calculations to optimize truck and loader allocations.

* **[RPMGlobal XECUTE / FleetOptimiser](https://help.rpmglobal.com/fleetoptimiser/latest/en/Content/GettingStarted.htm)**
  Web-based mining haulage optimization and execution environment for modeling, analyzing, and optimizing fleet operations.

* **[ASI Mining Mobius](https://asimining.com/mobius.html)**
  OEM-agnostic command-and-control platform for autonomous mining fleets, including haulage, drilling, blasting, teleoperation, and tracking of manned vehicles.

* **[Epiroc Mobilaris Mining Intelligence](https://www.epiroc.com/en-us/customer-stories/2023/optimizing-flows)**
  Mining intelligence and situational-awareness platform providing real-time location and operational visibility for underground equipment and personnel.

* **[Sandvik OptiMine](https://www.rocktechnology.sandvik/en/products/automine-and-optimine/optimine/)**
  Digital mining platform supporting equipment monitoring, production analytics, process optimization, and connected mining operations.

* **[Cat MineStar Fleet](https://www.cat.com/en_US/by-industry/mining/surface-mining/surface-technology/fleet.html)**
  Integrated fleet monitoring and management system providing real-time visibility into cycle time, payload, material movement, equipment assignment, fueling, and production performance.

* **[Cat MineStar](https://www.cat.com/en_US/by-industry/mining/minestar-solutions.html)**
  Broader connected mining technology ecosystem spanning fleet management, autonomy, equipment health, machine control, and operational intelligence.

* **[Hexagon MineOperate Asset Health](https://hexagon.com/products/hexagon-asset-health)**
  Equipment-health monitoring and analytics platform integrated with mine fleet operations for identifying abnormal conditions, equipment trends, alarms, and performance issues.

* **[Komatsu Modular Ecosystem](https://www.komatsu.com/en-us/technology/smart-mining/modular)**
  Connected mine-management ecosystem combining mine operations, machine technologies, analytics, and applications around the Modular DISPATCH platform.

* **[Komatsu DISPATCH Roadways](https://www.komatsu.com/en-us/technology/smart-mining/modular)**
  Haul-road optimization application designed to use real-time road information for routing, congestion management, ETA improvement, and cycle-time optimization.

* **[Komatsu DISPATCH Replenish](https://www.komatsu.com/en-us/technology/smart-mining/modular)**
  Fueling and charging optimization application that uses equipment location, fuel levels, burn rates, and station availability to reduce queues and downtime.

* **[Komatsu DISPATCH Adapt](https://www.komatsu.com/en-us/technology/smart-mining/modular)**
  AI-assisted fleet optimization application designed to dynamically adjust truck assignments and material flow as mine conditions change.

## Open-Source GitHub Projects

> The following projects are **not all complete mine FMS products**. They are categorized according to their usefulness in constructing an open-source mining fleet-management platform.

### Mining Dispatch & Simulation Projects

* **[OpenMines](https://github.com/370025263/openmines)**
  Open-pit mine traffic simulation environment for evaluating truck-dispatch algorithms, including configurable mine scenarios, truck fleets, dispatch policies, visualization, and reinforcement-learning support.

* **[OpenMines 2026 Fork](https://github.com/Zlinhai64/openmines_2026)**
  Active fork of OpenMines providing a Python-based environment for mining truck dispatch simulation and algorithm experimentation.

* **[Vivania](https://github.com/Yairama/vivania)**
  Open-pit mining Fleet Management System simulator modeling hauling/loading cycles, queueing, traffic, destination assignment, and reinforcement-learning optimization.

* **[CAOS_MINEHAUL](https://github.com/fsantibanezleal/CAOS_MINEHAUL)**
  Open-source deterministic discrete-event mine-haulage simulator covering open-pit and underground operations, constrained road networks, truck cycles, traffic effects, dispatch policies, and mine-planning scenarios.

* **[GA-TA Truck Dispatching](https://github.com/wesleycox/GA-TA-Truck-Dispatching)**
  Open-source implementation of a genetic-algorithm approach to truck dispatching in mining operations.

* **[Google OR-Tools](https://github.com/google/or-tools)**
  Open-source operations-research toolkit supporting vehicle-routing, constraint programming, linear programming, and optimization algorithms that can be adapted for truck-shovel dispatch and haulage allocation.

* **[PyVRP](https://github.com/PyVRP/PyVRP)**
  Open-source vehicle-routing optimization framework useful for experimenting with fleet assignment and routing problems.

* **[NetworkX](https://github.com/networkx/networkx)**
  Python graph-analysis library useful for mine-road graphs, shortest paths, network analysis, and custom dispatch algorithms.

### Additional Mining Optimization Building Blocks

* **[SciPy](https://github.com/scipy/scipy)**
  Scientific-computing library useful for optimization, statistics, numerical modeling, and mining production analytics.

* **[NumPy](https://github.com/numpy/numpy)**
  Numerical computing foundation for simulation, telemetry analysis, optimization, and machine-learning pipelines.

* **[Pyomo](https://github.com/Pyomo/pyomo)**
  Open-source optimization modeling framework suitable for mathematical mine-fleet allocation and production-planning models.

* **[COIN-OR](https://github.com/coin-or)**
  Collection of open-source optimization projects covering linear, mixed-integer, and nonlinear optimization.

### Fleet Tracking & Telematics

* **[Traccar](https://github.com/traccar/traccar)**
  Open-source GPS tracking server supporting a large range of tracking devices and protocols. Useful for tracking mining trucks, light vehicles, service vehicles, and mobile equipment.

* **[Traccar Web](https://github.com/traccar/traccar-web)**
  Web interface for real-time vehicle tracking, maps, fleet status, and telemetry visualization.

* **[OpenRemote](https://github.com/openremote/openremote)**
  Open-source IoT and asset-management platform supporting device management, telemetry, rules, automation, dashboards, and geofencing.

* **[KUKSA.val](https://github.com/eclipse-kuksa/kuksa.val)**
  Open-source automotive/vehicle-data platform implementing standardized vehicle data models and interfaces that can be adapted to machine telemetry architectures.

* **[COVESA Vehicle Signal Specification](https://github.com/COVESA/vehicle_signal_specification)**
  Open vehicle-data model useful as a reference for standardizing equipment telemetry and machine signals.

* **[OpenGTS](https://github.com/open-gts)**
  Open-source GPS tracking ecosystem that can be adapted for vehicle and asset tracking.

* **[OwnTracks](https://github.com/owntracks/recorder)**
  Open-source location tracking ecosystem useful for lightweight location-data collection and experimentation.

### IoT & Industrial Data Infrastructure

* **[ThingsBoard](https://github.com/thingsboard/thingsboard)**
  Open-source IoT platform for telemetry ingestion, device management, rule processing, dashboards, alarms, and asset monitoring.

* **[Eclipse Mosquitto](https://github.com/eclipse-mosquitto/mosquitto)**
  Lightweight MQTT broker suitable for real-time mine-site telemetry from trucks, loaders, sensors, gateways, and edge devices.

* **[EMQX](https://github.com/emqx/emqx)**
  MQTT-based messaging platform for high-volume IoT telemetry and distributed equipment communication.

* **[Node-RED](https://github.com/node-red/node-red)**
  Flow-based programming environment useful for connecting machine telemetry, MQTT, APIs, databases, alerts, and dashboards.

* **[Eclipse Kura](https://github.com/eclipse-kura/kura)**
  IoT edge-computing framework suitable for rugged mine-site gateways and industrial data collection.

* **[Eclipse 4diac](https://github.com/eclipse-4diac/4diac-ide)**
  Open-source industrial automation framework that can be integrated into equipment-control and industrial-data architectures.

* **[OpenPLC](https://github.com/thiagoralves/OpenPLC_v3)**
  Open-source PLC runtime useful for experimental industrial-control and equipment-integration environments.

### GIS, Routing & Mine Road Optimization

* **[QGIS](https://github.com/qgis/QGIS)**
  Leading open-source GIS platform useful for mine maps, haul-road networks, pit boundaries, equipment locations, terrain models, and spatial analysis.

* **[PostGIS](https://github.com/postgis/postgis)**
  PostgreSQL spatial extension for storing and querying mine geometry, haul roads, equipment locations, geofences, and operational geography.

* **[pgRouting](https://github.com/pgRouting/pgrouting)**
  Routing extension for PostgreSQL/PostGIS supporting shortest paths and network-analysis algorithms that can be adapted to mine haul-road networks.

* **[OSRM](https://github.com/Project-OSRM/osrm-backend)**
  High-performance routing engine useful for route calculation and travel-time estimation over custom mine-road networks.

* **[GraphHopper](https://github.com/graphhopper/graphhopper)**
  Open-source routing engine with vehicle-routing capabilities and customizable road profiles.

* **[OpenStreetMap](https://github.com/openstreetmap/openstreetmap-website)**
  Open geographic-data ecosystem that can provide mapping infrastructure, although actual mine-site road data generally needs to be supplied separately.

* **[OpenDroneMap](https://github.com/OpenDroneMap/ODM)**
  Open-source photogrammetry platform useful for generating mine-site maps, orthophotos, point clouds, and terrain information from drone imagery.

### Autonomous Mining & Robotics

* **[ROS 2](https://github.com/ros2/ros2)**
  Open-source robotics middleware providing communication, lifecycle management, sensors, navigation, and integration components for autonomous mining research.

* **[Autoware](https://github.com/autowarefoundation/autoware)**
  Open-source autonomous-driving software stack covering perception, localization, planning, and control. Useful as a research foundation for autonomous mining vehicles.

* **[Nav2](https://github.com/ros-navigation/navigation2)**
  ROS 2 navigation framework supporting localization, path planning, obstacle avoidance, and autonomous navigation.

* **[OpenRMF](https://github.com/open-rmf/rmf)**
  Open-source fleet-management framework for coordinating autonomous robots and vehicles. Although developed for general robotics rather than mining, its multi-fleet coordination concepts can be adapted for mining research.

* **[Open-RMF Traffic Editor](https://github.com/open-rmf/rmf_traffic_editor)**
  Tooling for modeling maps, lanes, traffic dependencies, and multi-vehicle navigation environments.

* **[PX4 Autopilot](https://github.com/PX4/PX4-Autopilot)**
  Open-source autopilot platform useful for autonomous aerial mapping, surveying, and robotics research around mining operations.

* **[MAVLink](https://github.com/mavlink/mavlink)**
  Open protocol and messaging ecosystem useful for autonomous vehicle and drone telemetry.

### Telemetry Databases & Analytics

* **[PostgreSQL](https://github.com/postgres/postgres)**
  Strong open-source transactional database for equipment, production, dispatch, shift, assignment, and mine-management data.

* **[TimescaleDB](https://github.com/timescale/timescaledb)**
  PostgreSQL-based time-series database particularly useful for high-frequency equipment telemetry.

* **[InfluxDB](https://github.com/influxdata/influxdb)**
  Time-series database suitable for machine telemetry, engine parameters, GPS data, fuel consumption, and sensor streams.

* **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**
  High-performance analytical database suitable for large-scale fleet telemetry and historical production analysis.

* **[DuckDB](https://github.com/duckdb/duckdb)**
  Embedded analytical database useful for local analysis of haul-cycle, equipment, and production datasets.

* **[Apache Kafka](https://github.com/apache/kafka)**
  Distributed event-streaming platform suitable for real-time equipment events and mine-production pipelines.

* **[Apache Pulsar](https://github.com/apache/pulsar)**
  Distributed messaging and event-streaming platform for large-scale telemetry architectures.

* **[NATS](https://github.com/nats-io/nats-server)**
  Lightweight messaging system suitable for low-latency machine and fleet events.

* **[MinIO](https://github.com/minio/minio)**
  S3-compatible object storage useful for storing telemetry archives, drone imagery, machine logs, datasets, and mine maps.

### Dashboards & Operational Intelligence

* **[Grafana](https://github.com/grafana/grafana)**
  Open-source observability and visualization platform suitable for fleet dashboards, equipment telemetry, cycle-time trends, production KPIs, and alarms.

* **[Apache Superset](https://github.com/apache/superset)**
  Open-source BI platform for fleet performance, production analytics, haul-cycle analysis, and management reporting.

* **[Metabase](https://github.com/metabase/metabase)**
  Easy-to-deploy open-source BI platform suitable for mine operations dashboards and fleet reports.

* **[Apache ECharts](https://github.com/apache/echarts)**
  Visualization library useful for building custom mine-control dashboards and fleet analytics applications.

### AI & Machine Learning

* **[PyTorch](https://github.com/pytorch/pytorch)**
  Open-source machine-learning framework suitable for predictive maintenance, cycle-time prediction, dispatch optimization, and computer vision.

* **[scikit-learn](https://github.com/scikit-learn/scikit-learn)**
  Machine-learning toolkit useful for equipment failure prediction, cycle-time modeling, anomaly detection, and production forecasting.

* **[XGBoost](https://github.com/dmlc/xgboost)**
  Gradient-boosting framework useful for predicting equipment downtime, cycle duration, fuel consumption, and production performance.

* **[Ollama](https://github.com/ollama/ollama)**
  Local LLM runtime useful for building private AI assistants over mine operational data and documentation.

* **[vLLM](https://github.com/vllm-project/vllm)**
  High-performance open-source inference engine useful for self-hosted AI services.

* **[Hugging Face Transformers](https://github.com/huggingface/transformers)**
  Open-source AI framework useful for NLP, document analysis, predictive workflows, and mining operations assistants.

## Additional Strong Open-Source Options

* **[OpenMines](https://github.com/370025263/openmines)** for truck-dispatch simulation and algorithm research.
* **[CAOS_MINEHAUL](https://github.com/fsantibanezleal/CAOS_MINEHAUL)** for deterministic mine-haulage simulation.
* **[Vivania](https://github.com/Yairama/vivania)** for reinforcement-learning-based FMS experimentation.
* **[GA-TA Truck Dispatching](https://github.com/wesleycox/GA-TA-Truck-Dispatching)** for genetic-algorithm dispatch research.
* **[Google OR-Tools](https://github.com/google/or-tools)** for truck-shovel allocation and optimization.
* **[Traccar](https://github.com/traccar/traccar)** for GPS fleet tracking.
* **[ThingsBoard](https://github.com/thingsboard/thingsboard)** for equipment telemetry and IoT management.
* **[Eclipse Mosquitto](https://github.com/eclipse-mosquitto/mosquitto)** for MQTT-based machine communication.
* **[QGIS](https://github.com/qgis/QGIS)** for mine GIS and haul-road mapping.
* **[PostGIS](https://github.com/postgis/postgis)** for spatial mine-data management.
* **[pgRouting](https://github.com/pgRouting/pgrouting)** for custom mine-road routing.
* **[OSRM](https://github.com/Project-OSRM/osrm-backend)** for route and travel-time calculations.
* **[OpenDroneMap](https://github.com/OpenDroneMap/ODM)** for drone-based mine mapping.
* **[ROS 2](https://github.com/ros2/ros2)** and **[Autoware](https://github.com/autowarefoundation/autoware)** for autonomous-vehicle research.
* **[Grafana](https://github.com/grafana/grafana)** for real-time operational dashboards.
* **[TimescaleDB](https://github.com/timescale/timescaledb)** and **[InfluxDB](https://github.com/influxdata/influxdb)** for telemetry storage.
* **[Apache Kafka](https://github.com/apache/kafka)** for high-volume equipment-event streaming.

**Frameworks for building custom systems**: Combine **Traccar + ThingsBoard + MQTT + PostgreSQL/PostGIS + TimescaleDB + QGIS + OR-Tools + Grafana** to create a self-hosted mine fleet-management platform. Add **OpenMines/CAOS_MINEHAUL** for dispatch simulation and **ROS 2/Autoware** when autonomous vehicle research is required.

## Recommended Open-Source Mine FMS Architecture

```text
┌─────────────────────────────────────────────────────────────────┐
│                     MINE FLEET / EQUIPMENT                      │
│                                                                 │
│  Haul Trucks │ Shovels │ Excavators │ LHDs │ Drills │ LV/Service│
└──────────────────────────────┬──────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────┐
│                    EDGE / TELEMATICS LAYER                      │
│                                                                 │
│ CAN / J1939 │ GPS/GNSS │ Sensors │ RFID │ PLC │ Edge Gateway   │
└──────────────────────────────┬──────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────┐
│                 COMMUNICATION / EVENT LAYER                     │
│                                                                 │
│ MQTT / Mosquitto │ EMQX │ Kafka │ NATS │ Node-RED              │
└──────────────────────────────┬──────────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────────┐
│                  TELEMETRY / FMS DATA PLATFORM                  │
│                                                                 │
│ ThingsBoard │ Traccar │ KUKSA │ PostgreSQL │ TimescaleDB       │
└──────────────────────────────┬──────────────────────────────────┘
                               │
                 ┌─────────────┼─────────────┐
                 ▼             ▼             ▼
        ┌─────────────┐ ┌─────────────┐ ┌──────────────┐
        │ Mine GIS    │ │ Dispatch    │ │ Analytics    │
        │ QGIS        │ │ OR-Tools    │ │ Grafana      │
        │ PostGIS     │ │ PyVRP       │ │ Superset     │
        │ pgRouting   │ │ Custom FMS  │ │ Metabase     │
        └──────┬──────┘ └──────┬──────┘ └──────┬───────┘
               │               │               │
               └───────────────┼───────────────┘
                               ▼
                 ┌─────────────────────────┐
                 │   OPERATIONS CONTROL     │
                 │                         │
                 │ Dispatch │ SIC │ KPI    │
                 │ Shift Plan │ Alerts     │
                 └─────────────────────────┘
```

## Commercial → Open-Source Mapping

| Commercial Platform             | Open-Source Building-Block Strategy                                |
| ------------------------------- | ------------------------------------------------------------------ |
| **HxGN MineOperate**            | ThingsBoard + Traccar + QGIS/PostGIS + OR-Tools + Grafana          |
| **Modular Mining DISPATCH**     | OpenMines + OR-Tools + PostGIS + custom dispatch engine            |
| **Wenco**                       | Traccar + ThingsBoard + OR-Tools + QGIS + TimescaleDB              |
| **Micromine Pitram**            | ERP/data layer + ThingsBoard + PostgreSQL + custom mining workflow |
| **GroundHog FMS**               | ThingsBoard + Traccar + OR-Tools + PostGIS + Grafana               |
| **RPMGlobal FleetPlanner**      | OR-Tools/PyVRP + QGIS + PostGIS + simulation engine                |
| **ASI Mining Mobius**           | ROS 2 + Autoware + OpenRMF + custom autonomous supervisory layer   |
| **Epiroc Mobilaris**            | Traccar + QGIS/PostGIS + ThingsBoard + Grafana                     |
| **Sandvik OptiMine**            | ThingsBoard + TimescaleDB + Grafana + ML stack                     |
| **Cat MineStar Fleet**          | ThingsBoard + Traccar + OR-Tools + TimescaleDB + Grafana           |
| **MineStar autonomous systems** | ROS 2 + Autoware + OpenRMF + custom vehicle-control layer          |

> These mappings are **architectural equivalents, not drop-in replacements**. Enterprise mine FMS products integrate proprietary machine interfaces, mining workflows, hardware, optimization algorithms, safety systems, and site-specific implementations that generally require substantial engineering to reproduce.

## Open-Source Fleet Management Capability Matrix

| Capability                 | OpenMines | Traccar | ThingsBoard | OR-Tools | QGIS/PostGIS | ROS 2 | Grafana |
| -------------------------- | --------: | ------: | ----------: | -------: | -----------: | ----: | ------: |
| GPS Tracking               |        ⚠️ |       ✅ |           ✅ |        ❌ |            ✅ |     ✅ |       ✅ |
| Equipment Telemetry        |        ⚠️ |       ✅ |           ✅ |        ❌ |           ⚠️ |     ✅ |       ✅ |
| Mine Mapping               |        ⚠️ |      ⚠️ |          ⚠️ |        ❌ |            ✅ |     ✅ |       ✅ |
| Truck Dispatch             |         ✅ |       ❌ |          ⚠️ |        ✅ |           ⚠️ |    ⚠️ |       ❌ |
| Truck-Shovel Allocation    |         ✅ |       ❌ |          ⚠️ |        ✅ |           ⚠️ |    ⚠️ |       ❌ |
| Route Optimization         |        ⚠️ |      ⚠️ |           ❌ |        ✅ |            ✅ |     ✅ |       ❌ |
| Haul-Cycle Simulation      |         ✅ |       ❌ |           ❌ |       ⚠️ |            ❌ |    ⚠️ |       ❌ |
| Real-Time Dashboards       |        ⚠️ |       ✅ |           ✅ |        ❌ |           ⚠️ |    ⚠️ |       ✅ |
| IoT Device Management      |         ❌ |      ⚠️ |           ✅ |        ❌ |            ❌ |    ⚠️ |       ❌ |
| Machine Learning           |        ⚠️ |       ❌ |          ⚠️ |       ⚠️ |            ❌ |     ✅ |       ❌ |
| Autonomous Navigation      |         ❌ |       ❌ |           ❌ |        ❌ |           ⚠️ |     ✅ |       ❌ |
| Multi-Vehicle Coordination |        ⚠️ |       ❌ |          ⚠️ |       ⚠️ |           ⚠️ |     ✅ |       ❌ |
| Production Analytics       |        ⚠️ |      ⚠️ |           ✅ |       ⚠️ |           ⚠️ |    ⚠️ |       ✅ |
| Self-Hosted                |         ✅ |       ✅ |           ✅ |        ✅ |            ✅ |     ✅ |       ✅ |

> `⚠️` indicates that the capability requires customization, integration, or another component.

## Best Open-Source Combinations

### Open-Pit Truck Dispatch

```text
OpenMines
   +
OR-Tools
   +
QGIS / PostGIS
   +
TimescaleDB
   +
Grafana
```

Useful for:

* Truck-shovel assignment research
* Dispatch optimization
* Haul-cycle simulation
* Mine-road modeling
* Production optimization

### Real-Time Fleet Tracking

```text
Traccar
   +
MQTT / Mosquitto
   +
ThingsBoard
   +
PostgreSQL / TimescaleDB
   +
Grafana
```

Useful for:

* GPS tracking
* Fleet location
* Equipment status
* Geofencing
* Telemetry
* Alerts
* Historical analysis

### Advanced Mining FMS

```text
Equipment
   ↓
CAN/J1939 + GPS
   ↓
Edge Gateway
   ↓
MQTT / Kafka
   ↓
ThingsBoard
   ↓
PostgreSQL + TimescaleDB
   ↓
PostGIS / QGIS
   ↓
OR-Tools / PyVRP
   ↓
Dispatch Engine
   ↓
Grafana / Superset
```

### Autonomous Mining Research

```text
ROS 2
   +
Autoware
   +
OpenRMF
   +
QGIS / PostGIS
   +
Simulation Environment
   +
Telemetry Platform
```

This is appropriate primarily for **research, simulation, prototyping, and autonomous-vehicle development**, rather than immediate deployment as a safety-critical mine autonomy system.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: project name, official/repository link, 1–2 sentence description, and whether it is SaaS, hosted, open-source, simulation, or a building block.
4. For open-source projects, include the actual GitHub repository whenever available.
5. Do not describe a generic IoT, GIS, or robotics project as a complete mine FMS unless it actually provides that functionality.
6. Mention important licensing or maturity limitations where relevant.
7. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

* This is a **community-curated** list — not exhaustive and not an endorsement.
* Enterprise mining FMS platforms may combine proprietary software, onboard hardware, machine interfaces, mine-specific optimization algorithms, communications infrastructure, and operational services.
* Most open-source projects listed here are **building blocks, simulators, optimization libraries, telemetry platforms, GIS systems, or robotics frameworks**, rather than complete replacements for commercial mine FMS products.
* Mining fleet management and autonomous equipment are **safety- and production-critical** systems. Uncertified software must not be used for primary autonomous machine control, collision avoidance, functional safety, or mission-critical mine dispatch without appropriate engineering validation, certification, redundancy, and regulatory compliance.
* CAN/J1939, GPS/GNSS, industrial-network, autonomous-driving, and machine-control integrations should be validated against the specific equipment and mine environment.
* Always consult OEM documentation, mining-technology specialists, functional-safety professionals, and applicable mining regulations before deploying software in an operational mine.

---

**Made for mining companies, mine managers, dispatchers, fleet engineers, mining-technology teams, researchers, and open-source developers.**
Let's make mine fleet management more **open, interoperable, data-driven, optimized, and automation-ready**.

