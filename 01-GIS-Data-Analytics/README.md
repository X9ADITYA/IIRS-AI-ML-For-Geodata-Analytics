# Lesson 1 — GIS Data Analytics

This folder contains notes, interview questions, quiz questions, and examples from **Lesson 1: GIS Data Analytics** of the **IIRS–ISRO AI/ML for Geodata Analytics** course.

## 📚 Topics Covered

- Overview of Geospatial Technology
- Spatial Data Models
- Data Collection Methods
- Data Cleaning
- Data Analytics
- Exploratory Data Analysis (EDA)
- Concepts of Geo-processing
- Data Visualization Tools
- Overview of AI/ML for Spatial Data Analysis

## 🌍 Geospatial Technology

Geospatial technology deals with technologies used to collect, manage, analyze, visualize, and interpret information related to locations on Earth.

The major areas introduced in the session include:

- GIS / Spatial Analytics
- GNSS & Positioning
- Earth Observation
- Scanning Technologies

### Major Components

#### GIS / Spatial Analytics

Used for:

- Desktop GIS
- Web and Cloud GIS
- Mobile and Tablet-based GIS
- Spatial data analysis

#### GNSS & Positioning

Used for:

- Navigation
- Positioning
- Indoor positioning

#### Earth Observation

Includes:

- Satellite Remote Sensing
- UAV / Drone-based observation
- Aerial Survey

#### Scanning

Includes:

- LiDAR
- TLS (Terrestrial Laser Scanning)
- Radar

---

## 🗺️ GIS

GIS (Geographic Information System) is a system used to work with geographically referenced information.

GIS combines concepts from multiple fields, including:

- Computer Science
- Management Information Systems
- Geography
- Cartography
- Geodesy
- Photogrammetry
- Landform studies
- Spatial statistics

GIS has applications in areas such as:

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

## 📊 Types of Data

Three broad categories of data were introduced:

### 1. Structured Data

Data organized in a predefined structure, commonly represented using rows and columns.

Examples:

- Database records
- Numerical data
- Spreadsheet data
- Ratings

### 2. Semi-structured Data

Data that does not follow a strict tabular structure but contains organizational information such as tags or metadata.

Examples:

- Emails
- Social media content organized using hashtags
- Files organized using folders or categories

### 3. Unstructured Data

Data that does not follow a clearly defined tabular or relational structure.

Examples:

- Images
- Videos
- Audio
- Documents
- Emails
- Online reviews
- Social media content

---

## 🔄 Structured vs Unstructured Data

### Structured Data

- Can be represented using rows and columns
- Commonly stored in relational databases
- Usually contains numbers, dates, and strings
- Easier to manage using traditional database systems
- Generally requires less storage than equivalent unstructured data

### Unstructured Data

- Cannot naturally be represented using traditional rows and columns
- Includes images, audio, video, documents, emails, and other content
- Generally requires more complex processing and management
- Often requires specialized tools for analysis

---

## 📦 Big Data

Big Data refers to datasets that are very large and complex, making them difficult to process using traditional database management systems or conventional data-processing applications.

### Challenges of Big Data

Major challenges include:

- Data capture
- Data curation
- Data storage
- Data search
- Data sharing
- Data transfer
- Data analysis
- Data visualization

---

## 🔢 Characteristics of Big Data

The session introduced five major characteristics:

### Volume

The huge amount of data being generated and stored.

### Velocity

The speed at which data is generated, accumulated, and processed.

### Variety

The presence of different types and formats of data from different sources.

### Veracity

The inconsistencies, uncertainty, and reliability issues associated with data.

### Value

The useful information and insights that can be extracted from data.

---

## 🌐 Representing Geographic Features

Geographical features can be described using two major types of data:

### Spatial Data

Spatial data describes **where** something is located.

Examples:

- Location of a road
- Location of a river
- Location of a building
- Location of a city

### Attribute Data

Attribute data describes the characteristics associated with a particular location.

It can describe:

- What
- How much
- When
- Other characteristics of the geographic feature

### Example

For a city:

**Spatial Data:**
- Geographic coordinates of the city

**Attribute Data:**
- Population
- Area
- Name
- Population density

---

## 🗂️ GIS Layers

Geographic information can be organized into layers based on similar characteristics.

Examples of layers include:

- Hydrography
- Elevation
- Water lines
- Sewer lines
- Sales-related geographic information

Each layer represents a particular type or theme of geographic information.

---

## 🧭 GIS Data Models

Two major digital data models were introduced:

### Vector Data Model

Vector data represents geographic features using geometric objects such as:

- Points
- Lines
- Polygons

Examples:

- Point → location of a school
- Line → road or river
- Polygon → district or lake boundary

### Raster Data Model

Raster data represents geographic information as a grid of cells or pixels.

It is commonly used for continuous geographic phenomena and imagery.

Examples:

- Satellite imagery
- Elevation data
- Temperature surfaces

---

## 📐 Important GIS Data Properties

The session highlighted several important properties of geographic data:

### Projection

Defines how the curved surface of the Earth is represented on a flat map.

### Scale

Represents the relationship between distances on a map and corresponding distances on the ground.

### Accuracy

Describes how close a measurement or representation is to the true value.

### Resolution

Describes the level of detail represented by the data.

---

## 🧹 Data Cleaning

Data cleaning involves identifying and handling issues in datasets before analysis.

It helps improve the quality and usability of data.

Typical issues can include:

- Missing values
- Inconsistent values
- Duplicate records
- Incorrect formats
- Invalid data

---

## 📈 Data Analytics

Data analytics involves examining and processing data to obtain useful information and insights.

In geospatial applications, analytics can be used to identify spatial patterns, relationships, and trends.

---

## 🔎 Exploratory Data Analysis

Exploratory Data Analysis (EDA) is used to understand a dataset before applying more advanced analysis or modeling.

EDA can involve:

- Examining data distributions
- Identifying patterns
- Detecting unusual values
- Understanding relationships between variables
- Visualizing data

---

## ⚙️ Geo-processing

Geoprocessing refers to operations performed on geographic data to create, transform, analyze, or derive new geographic information.

It is an important part of GIS-based analysis.

---

## 📊 Data Visualization

Data visualization involves representing data graphically so that patterns, relationships, trends, and other information can be understood more easily.

Visualization is particularly important in geospatial analytics because geographic information can be represented through maps and other visual forms.

---

## 🤖 AI/ML for Spatial Data Analysis

The session also introduced the application of Artificial Intelligence and Machine Learning to spatial data analysis.

AI/ML can be used to analyze large and complex geospatial datasets and support tasks such as:

- Pattern identification
- Classification
- Prediction
- Spatial analysis
- Automated interpretation

This topic connects the fundamentals of GIS and geospatial data with later AI/ML lessons in the course.

---

## 🎯 Key Takeaways

After completing this lesson, you should understand:

1. What geospatial technology is.
2. The major components of geospatial technology.
3. What GIS is and where it is used.
4. The difference between spatial and attribute data.
5. Structured, semi-structured, and unstructured data.
6. The concept and characteristics of Big Data.
7. How geographic features are represented in GIS.
8. Vector and raster data models.
9. The importance of projection, scale, accuracy, and resolution.
10. The role of data cleaning, analytics, EDA, geoprocessing, and visualization.
11. Why AI/ML is relevant to spatial data analysis.

---

## 📁 Folder Contents

- `README.md` — Lesson overview
- `Notes.md` — Detailed learning notes
- `Interview-Questions.md` — Interview preparation
- `Quiz-Questions.md` — Quiz and revision questions
- `Examples/` — Practical examples and code