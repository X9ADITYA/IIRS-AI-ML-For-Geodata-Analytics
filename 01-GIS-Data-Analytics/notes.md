# Lesson 1 — GIS Data Analytics — Detailed Notes

## 1. Overview of Geospatial Technology

Geospatial technology refers to technologies used for collecting, managing, analyzing, and visualizing information associated with locations on Earth.

The session introduced four important areas:

1. GIS / Spatial Analytics
2. GNSS & Positioning
3. Earth Observation
4. Scanning

---

# 2. GIS / Spatial Analytics

GIS stands for Geographic Information System.

GIS and spatial analytics are used to work with geographically referenced information.

GIS technologies can be implemented through:

- Desktop applications
- Web and cloud platforms
- Mobile devices and tablets

Spatial analytics focuses on analyzing information according to its geographic or spatial characteristics.

---

# 3. GNSS & Positioning

GNSS stands for Global Navigation Satellite System.

GNSS and positioning technologies are used to determine and work with geographic positions.

Applications introduced in the session include:

- Navigation
- Positioning
- Indoor positioning

---

# 4. Earth Observation

Earth Observation involves obtaining information about the Earth using observation technologies.

The session introduced:

### Satellite Remote Sensing

Satellites can collect information about Earth's surface and environment.

### UAV / Drone

Unmanned Aerial Vehicles can be used for collecting aerial geographic information.

### Aerial Survey

Aerial surveys collect information from an elevated or airborne platform.

---

# 5. Scanning Technologies

Scanning technologies introduced in the session include:

### LiDAR

Light Detection and Ranging.

LiDAR uses laser-based measurements to obtain information about objects and surfaces.

### TLS

TLS stands for Terrestrial Laser Scanning.

It is used for detailed scanning of objects and environments from terrestrial locations.

### Radar

Radar uses electromagnetic signals to detect and analyze objects and surfaces.

---

# 6. Knowledge Base for GIS

GIS is an interdisciplinary technology.

It combines knowledge from different technological and traditional disciplines.

## Computer Science / MIS

Important areas include:

- Graphics
- Visualization
- Database systems
- System administration
- Security

## Geography and Related Fields

Important areas include:

- Cartography
- Geodesy
- Photogrammetry
- Landforms
- Spatial statistics

GIS therefore represents the convergence of technological fields and traditional geographic disciplines.

---

# 7. Applications of GIS

GIS can be applied to many areas.

Examples include:

- Public administration
- Planning
- Geology
- Mineral exploration
- Forestry
- Site selection
- Marketing
- Civil engineering
- Criminal justice
- Surveying

---

# 8. Types of Data

Data can broadly be categorized as:

1. Structured
2. Semi-structured
3. Unstructured

---

# 9. Structured Data

Structured data follows a predefined structure.

It can commonly be represented using:

- Rows
- Columns
- Tables

Examples include:

- Database records
- Numerical data
- Spreadsheet data
- Ratings

Structured data is generally easier to store and process using traditional database systems.

---

# 10. Semi-structured Data

Semi-structured data does not strictly follow a tabular structure but still contains some organizational information.

Examples include:

- Emails
- Social media content organized using hashtags
- Files organized according to topics or categories

Metadata and tags can provide structure to otherwise flexible data.

---

# 11. Unstructured Data

Unstructured data does not follow a predefined tabular or relational structure.

Examples include:

- Images
- Videos
- Audio
- Speech
- Documents
- Emails
- Online reviews
- Social media content

Unstructured data often requires specialized methods and tools for processing.

---

# 12. Structured vs Unstructured Data

| Structured Data | Unstructured Data |
|---|---|
| Organized into rows and columns | Not naturally organized into rows and columns |
| Commonly stored in relational databases | Includes images, audio, video, documents, etc. |
| Numbers, dates, strings | Multimedia and free-form content |
| Easier to manage using traditional systems | More difficult to manage using traditional systems |
| Usually requires less storage | Often requires more storage |

---

# 13. Big Data

Big Data refers to datasets that are so large and complex that traditional database management systems and conventional data-processing applications may struggle to handle them.

Big Data creates challenges across the entire data lifecycle.

---

# 14. Challenges in Big Data

Important challenges include:

- Capture
- Curation
- Storage
- Search
- Sharing
- Transfer
- Analysis
- Visualization

---

# 15. Characteristics of Big Data

The five characteristics introduced in the session are:

## Volume

The amount of data.

Big Data involves very large quantities of data.

## Velocity

The speed at which data is generated and accumulated.

## Variety

The different formats and sources of data.

## Veracity

The uncertainty, inconsistencies, and reliability of data.

## Value

The useful information that can be extracted from the data.

---

# 16. Representing Geographic Features

Geographic features can be described using two important types of information:

## Spatial Data

Spatial data describes:

> Where?

It represents the location or geographic position of a feature.

Examples:

- Location of a road
- Location of a river
- Location of a building

## Attribute Data

Attribute data describes characteristics associated with a location.

It answers questions such as:

- What?
- How much?
- When?

Example:

For a particular road:

Spatial data:
- Geographic location of the road

Attribute data:
- Road name
- Road type
- Length
- Construction information

---

# 17. GIS Layers

Geographic features can be grouped into layers according to similar characteristics.

Examples:

- Hydrography
- Elevation
- Water lines
- Sewer lines
- Sales information

Each layer represents a particular category or theme of geographic information.

---

# 18. Vector Data Model

The vector data model represents geographic features using geometric objects.

The three basic vector geometries are:

### Point

Represents a specific location.

Example:

- School
- Hospital
- Weather station

### Line

Represents linear geographic features.

Example:

- Road
- River
- Pipeline

### Polygon

Represents an enclosed geographic area.

Example:

- District
- Lake
- Forest area

---

# 19. Raster Data Model

The raster data model represents geographic information as a grid.

The grid is made up of cells or pixels.

Raster data is commonly used for:

- Satellite imagery
- Elevation
- Temperature
- Continuous geographic surfaces

---

# 20. Data Properties in GIS

The session highlighted four important properties.

## Projection

Projection determines how geographic coordinates on Earth's curved surface are represented on a flat map.

## Scale

Scale represents the relationship between map distance and actual ground distance.

## Accuracy

Accuracy indicates how close the recorded or represented value is to the true value.

## Resolution

Resolution indicates the level of detail represented by the data.

For raster data, spatial resolution is commonly associated with pixel size.

---

# 21. Relational Database Management System

The session introduced the use of a relational Database Management System (DBMS) as part of incorporating geographic information into computer application systems.

A relational DBMS organizes information using tables and relationships between data.

---

# 22. Primary and Secondary Data

## Primary Data

Primary data is collected directly for a specific purpose.

Examples:

- Surveys
- Questionnaires
- Direct observations
- Field measurements

### Important Quiz Point

If asked:

**Which of the following is an example of a primary data collection method?**

Answer:

**Surveys and questionnaires.**

---

## Secondary Data

Secondary data is data that already exists and is obtained from previously collected or published sources.

Examples:

- Government census reports
- Published research articles
- Company annual reports

---

# 23. Data Cleaning

Data cleaning is the process of identifying and handling problems in datasets before analysis.

Examples of data-quality problems include:

- Missing values
- Duplicate records
- Inconsistent values
- Incorrect formats
- Invalid records

Clean data improves the reliability of subsequent analysis.

---

# 24. Data Analytics

Data analytics involves examining data to obtain useful information and insights.

In geospatial analytics, the geographic component of the data can be used to identify:

- Spatial patterns
- Relationships
- Trends
- Geographic distributions

---

# 25. Exploratory Data Analysis

Exploratory Data Analysis (EDA) is used to understand data before deeper analysis or modeling.

EDA can help identify:

- Patterns
- Trends
- Relationships
- Unusual observations
- Data-quality problems
- Distributions

Visualization is an important part of EDA.

---

# 26. Geo-processing

Geoprocessing involves performing operations on geographic data.

It can be used to:

- Transform geographic data
- Analyze geographic data
- Create derived information
- Combine or manipulate geographic layers

Geoprocessing is an important capability of GIS.

---

# 27. Data Visualization

Data visualization represents information graphically.

Visualization makes it easier to:

- Understand patterns
- Identify trends
- Compare values
- Communicate results

For geospatial information, maps are an important form of visualization.

---

# 28. AI/ML for Spatial Data Analysis

The session provided an overview of AI/ML for spatial data analysis.

AI and ML can be applied to geographic datasets to support tasks such as:

- Classification
- Prediction
- Pattern recognition
- Automated analysis
- Spatial data interpretation

This provides the foundation for the AI/ML topics covered in later lessons.

---

# 29. Lesson Summary

The first lesson establishes the foundation for the entire course.

The main progression is:

Geospatial Technology
        ↓
GIS
        ↓
Geospatial Data
        ↓
Data Collection
        ↓
Data Cleaning
        ↓
Data Analytics
        ↓
Exploratory Data Analysis
        ↓
Geo-processing
        ↓
Visualization
        ↓
AI/ML for Spatial Data Analysis

Understanding these concepts is important before moving into image processing, machine learning, deep learning, and generative AI for geospatial applications.