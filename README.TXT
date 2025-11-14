# 🏠 Airbnb London Data Visualization Platform

A modern, interactive JavaFX application for exploring and analyzing 50,000+ Airbnb listings across London's 33 boroughs. Features dynamic map visualization, real-time filtering, geospatial analytics, and comprehensive statistical dashboards built with Java and JavaFX.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technical Specifications](#technical-specifications)
- [Algorithm Implementation](#algorithm-implementation)
- [Testing](#testing)
- [Skills Demonstrated](#skills-demonstrated)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎯 Overview

The Airbnb London Data Visualization Platform is a comprehensive desktop application that transforms raw CSV data containing 50,000+ property listings into an intuitive, interactive map-based interface. Built as part of a software engineering team project, this application demonstrates advanced GUI development, algorithm implementation, and data processing capabilities.

**Project Highlights:**
- 📊 Processes and visualizes 50,000+ Airbnb listings
- 🗺️ Interactive map with 33 clickable London boroughs
- 🔍 Real-time filtering and sorting capabilities
- 📈 Dynamic statistical analysis dashboard
- 📍 Geospatial distance calculations using Haversine formula
- ⚡ Sub-second response time for complex operations

**Technologies Used:**
- Java 11
- JavaFX 17
- OpenCSV 4.1
- JUnit 5

---

## ✨ Features

### 🗺️ Interactive Map Visualization
- **Dynamic Color Coding**: Borough regions automatically colored based on listing density using custom pixel manipulation algorithms
- **Clickable Regions**: All 33 London boroughs are interactive with event handlers
- **Real-time Visual Updates**: Instant color adjustments when price filters change
- **Responsive Design**: Map scales appropriately for different screen sizes

### 🔍 Advanced Filtering & Sorting
- **Price Range Filter**: Set minimum and maximum price thresholds with dropdown menus
- **Multi-Criteria Sorting**: Sort by price, reviews, host name, or minimum nights
- **Ascending/Descending Toggle**: Single-click order reversal
- **Custom Merge Sort Algorithm**: O(n log n) implementation for efficient data organization

### 📊 Statistical Analysis Dashboard
- **8 Dynamic Metrics**: 
  - Average reviews per property
  - Total available properties
  - Number of entire homes/apartments
  - Most expensive borough
  - Host with most listings
  - Crime rate ranking
  - Tourist attractions
  - Population density
- **Rotating Display**: Navigate through statistics with arrow buttons
- **Borough-Specific Data**: Statistics update automatically when borough is selected

### 📍 Geospatial Calculations
- **Haversine Formula**: Accurate great-circle distance calculations
- **Distance to High Streets**: Calculate proximity from any property to borough centers
- **Coordinate Processing**: Latitude/longitude handling for all 33 boroughs

### 🎨 User Interface
- **Professional Design**: Custom CSS styling with polished aesthetics
- **Popup Windows**: Modal dialogs for detailed property information
- **Smooth Navigation**: Intuitive panel switching with previous/next buttons
- **Welcome Screen**: Engaging landing page with London imagery

---

## 🎬 Demo

### Application Workflow

1. **Launch Screen**
   - Welcome page displays London cityscape
   - Price range selectors (disabled until range selected)

2. **Price Selection**
   - Choose from: £10, £20, £50, £100, £500, £1000, £5000, £10000
   - Validation ensures minimum < maximum
   - Navigation buttons activate upon valid selection

3. **Interactive Map**
   - Click any of 33 boroughs
   - View color-coded listing density
   - Hover tooltips show borough names

4. **Listings View**
   - Filtered properties display in scrollable list
   - Sort by multiple criteria
   - Click individual listings for details

5. **Statistics Panel**
   - Four rotating stat boxes
   - Arrow navigation to cycle metrics
   - Updates based on selected borough

### Sample Use Case
