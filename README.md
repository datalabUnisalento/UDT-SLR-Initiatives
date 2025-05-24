#### **Duet** {#par:Duet}

The DUET project, which stands for \"Digital Twin for the Energy
Transition,\" is an initiative focused on developing digital twin
technologies to support various applications, particularly in the energy
sector. Duet can be effectively considered as an operational proof of
concept to be especially used in case of cities that lack advanced
data-driven solutions for urban purposes. A key component of this
project is the T-Cell framework, which serves as a foundational platform
for integrating various elements necessary for effective DT applications
([@raes2021duet]).

These components work together in synergy within a shared environment to
generate insights that may be used for decision-making purposes in smart
cities. By developing this dynamic correspondence among architecture,
models, and data, the state and behavior of both DT and its physical
counterpart can be monitored and kept synchronized. The integration of
individual models via APIs thus allows for the prospect of a network of
models on the cloud, usable for multiple what-if analyses regarding
traffic, air quality, and noise pollution.

#### **Fishermans Bend Digital Twins** {#par:fishermansDTI}

Fishermans Bend Digital Twins provides a multi-dimensional schema to
develop the DT corresponding to the homonymous Australian city for the
state government of Victoria ([@tzachor2022potential]). The first two
dimensions of the city of the proposed schema are the city's 3D model
and a collaborative environment for the various city actors. The main
purpose of this initiative is to collectively improve public services,
including road infrastructure and safety. Its simulation capabilities
for real-time mass transit data facilitate the prediction of tram
traffic patterns.

#### **GATE Bulgaria** {#par:gateDTI}

GATE Bulgaria platform proposes a DT development process that is based
on its semantic 3D models. The reason behind this choice lies in the
ability of these 3D models to accurately depict landscapes and urban
areas. The proposed multi-step process for developing an DT also
introduces a 3D city model that serves as the initial foundation for
implementing the Sofia city's DT
([@dimitrov20213d; @hristov2022enabling]). According to the CityGML 2.0
specifications, this 3D model is delivered at LOD 1 and allows the
integration of buildings and terrain, including address information for
modeled buildings. The integration of buildings and terrain is an
important feature, as often buildings are partially levitating or
submerged in the terrain. Lozenets corresponds to the selected district
in Sofia that was identified as the pilot area for urban modeling.
Furthermore, a web-based application has been developed that enables the
user to interact with the city model. The main functionalities offered
by this application correspond to the possibilities to focus on a single
building and to display various visual styles according to its attribute
list, including relevant overlay information and shadows.

#### **Herrenberg** {#par:HerrenbergDTI}

Herrenberg represents an UDT prototype, which was designed for the
municipality of Herrenberg, in Germany. The proposed prototype is based
on the integration of the following five main components: (1) a 3D model
of the built environment; (2) a street network model using space syntax;
(3) a simulation of urban mobility; (4) a simulation of wind flow; (5) a
set of empirical quantitative and qualitative data obtained through
volunteered geographic information. The resulting UDT has been
integrated into a software platform to enable virtual reality support
and was showcased during various public events, first of all the
\"Morgenstadt Werkstatt\" (Tomorrow's Cities Workshop) ([@Dembski2020]).

#### **New South Wales**

([@diakite2022liveable]) []{#par:nswDTI label="par:nswDTI"} The New
South Wales project aims to develop an UDT demonstrator that integrates
existing data using a standardized 3D format. CityGML was adopted as a
standard for generating the 3D city representation and enabling BIM
visualization by integrating BIM and Geographic Information Systems
(GIS) technologies. This demonstrator embeds analytics, such as sun
exposure and tree coverage, to assess livability within a 3D city
modeling framework. Common urban features such as buildings, roads,
railways, vegetation, and water bodies are also supported. In addition,
this project supports DTs development through a set of open-source tools
to improve accessibility and repeatability, beyond allowing the
integration of IoT sensors into the city model. The project provides to
store city features in a 3D City Database (3DCityDB) and supports the 3D
upgrading of urban features commonly available as 2D data. Several use
cases are illustrated and discussed in the project. Finally, the
integration of the hydrodynamic city model with the 3D DT is used as
input for analytics and visualizations.

#### **Digital Twin-Enabled System Resilience**

([@alva2022digital]) []{#par:dt_enabled_sys_resilienceDTI
label="par:dt_enabled_sys_resilienceDTI"} This project focuses on the
development of an UDT through a web map application for a district-scale
university campus. Two case studies were developed to validate the
project. The first relates to the simulation of the pandemic impact on
the specific environment. This simulation was performed by changing both
the occupancy rates and the average cooling loads in the target
buildings during the lockdown period. A second case study concerns the
simulation of climate change scenarios. The resulting UDT provides a
dashboard that includes various data visualizations. These
visualizations include the 3D model of the university campus, real-time
data collected by the deployed sensors, results of the energy demand
simulation performed by the City Energy Analyst (CEA) tool, and
occupancy rates of buildings detected using WiFi data. Another work for
the same project focuses on formulating a resilience assessment metric
to measure the robustness of buildings to possible disruptions, which
can be beneficial for facilities management and planning applications.
Finally, the project highlights the benefits of using the DT approach to
support decarbonizing initiatives for cities.

#### **Rotterdam 3D** {#par:rotterdamDTI}

The project provides a three-dimensional city model of Rotterdam that
although does not contain any semantic information. In this regard, the
proposed city model adopts a CityGML-compliant method that is intended
to solve this absence, thereby rendering these models useful for a wide
variety of spatial analyses ([@rook2016towards]). As a result, it
becomes possible to recognize, distinguish, and organize various spatial
features, such as walls, terrain, roofs, and building ground, in order
to generate a semantically rich three-dimensional city model.

#### **VarCity (ETH)** {#par:varcityDTI}

VarCity is an initiative of the Computer Vision Laboratory at ETH Zurich
that investigates the modeling of dynamic and semantic cities from
images[^1]. The project combines dynamic layers (such as traffic flows
and events) with semantic layers to generate and comprehend entire
cities. The goal is to populate static 3D city models with dynamic
content and generate the corresponding city-scale motion and activity
models, based on the usage of special events and traffic flow data.
Beyond analyzing images of actual cities, the project can be used to
construct semantic and parameterized models, which include information
such as vegetation, building height, traffic sign shadow, and building
count.

#### **Virtual Singapore**

[^2] []{#par:virtual_singaporeDTI label="par:virtual_singaporeDTI"} The
goal of the Virtual Singapore project is to deploy a 3D digital
platform. This platform allows users from different sectors to develop
software tools for test-bedding concepts and services, decision-making
strategies, and their corresponding planning as well. As a result, new
challenges for Singapore can be faced thanks to the technological
advances provided by research in the field, fostered by the usage of the
applications developed for the purposes of this project. A case study
has been presented in the past where the Virtual Singapore 3D city model
was used to develop an integrated simulation platform for both the
climate assessment and the district energy demand
([@ignatius2019virtualSingapore]).

#### **West Cambridge Digital Twin**

([@WestCambridgeDTbrazauskas2022cdbb]) []{#par:west_cambridgeDTI
label="par:west_cambridgeDTI"} The collection and analysis of real-time
sensor data represents the key aspect of the architectural framework
developed within this initiative. To reduce the latency of information
streams, real-time data is pushed from asynchronous sensor events,
either simple or complex, and properly displayed on end-user web pages.
All data entities, including sensor readings, types, and building
objects, are represented using JSON-LD structures, allowing and
facilitating effective management of the relations between the same
structures.

[^1]: <https://www.varcity.ethz.ch/>

[^2]: [www.nrf.gov.sg/programmes/virtual-singapore](www.nrf.gov.sg/programmes/virtual-singapore){.uri}
