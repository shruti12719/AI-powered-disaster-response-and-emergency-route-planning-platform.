# 🚀 Route Resilience AI

Route Resilience AI is an AI-powered disaster management and emergency route planning platform developed for the ISRO BAH Hackathon PS4.

The platform converts satellite imagery into an intelligent transportation network by extracting roads, repairing disconnected road topology, constructing a routable graph, identifying critical infrastructure, simulating disaster events, and generating alternate emergency routes for rescue operations.

Unlike traditional road extraction systems that stop after segmentation, Route Resilience AI transforms extracted roads into actionable decision intelligence for emergency responders.

## ✨ Features

### 🛰️ Satellite Image Processing
- Upload satellite imagery
- Road extraction using Deep Learning (U-Net / DeepLab / SegFormer)
- Occlusion handling
- Morphological refinement
- Skeletonization

### 🛣️ Intelligent Road Graph Generation
- Road network construction
- Automatic topology repair
- Gap bridging
- Graph optimization
- Connected component analysis

### 📊 Network Analytics
- Betweenness Centrality
- Critical Road Identification
- Critical Junction Detection
- Network Resilience Index
- Connectivity Analysis

### 🚨 Disaster Simulation
Supports realistic disaster scenarios including:
- 🌊 Urban Flood
- 🌉 Bridge Failure
- 🚧 Major Road Accident
- ⛰️ Landslide

### 🚑 Emergency Route Planning
- Search locations by name
  - Hospitals
  - Police Stations
  - Fire Stations
  - Relief Camps
  - Airports
  - Roads and Localities

The platform automatically:
- Converts place names into coordinates
- Snaps locations to the nearest road network
- Computes the shortest normal route
- Simulates road blockages
- Generates resilient alternate routes
- Estimates travel delay

### 🗺️ Interactive GIS Dashboard
- Google Maps-like interface (using supported map tiles)
- Satellite basemap
- Road overlays
- Emergency route visualization
- Critical node highlighting
- Blocked road visualization
- Interactive markers

### 📈 Decision Support Dashboard
- Road Extraction Quality
- Network Connectivity
- Disaster Impact
- Route Delay
- Recovery Index
- AI-generated Emergency Summary

### 📄 Reporting
- Download Road Masks
- Export Road Graph
- PDF Emergency Report
- Disaster Analysis Report

## 🧠 Technology Stack

### Artificial Intelligence
- Python
- PyTorch
- Segmentation Models PyTorch
- U-Net
- DeepLabV3+
- SegFormer

### Computer Vision
- OpenCV
- scikit-image
- Morphological Processing
- Skeletonization

### Graph Analytics
- NetworkX
- Dijkstra Algorithm
- Betweenness Centrality
- Connected Components
- Graph Healing

### GIS & Mapping
- Folium
- OpenStreetMap
- Nominatim Geocoder
- Leaflet

### Dashboard
- Streamlit
- Pandas
- NumPy

## 🎯 Workflow

```text
Satellite Image
        │
        ▼
Road Extraction
        │
        ▼
Road Mask Refinement
        │
        ▼
Skeletonization
        │
        ▼
Road Graph Generation
        │
        ▼
Topology Repair
        │
        ▼
Critical Infrastructure Detection
        │
        ▼
Disaster Simulation
        │
        ▼
Emergency Route Planning
        │
        ▼
Interactive GIS Dashboard
        │
        ▼
Decision Support Report
```

## 🌍 Applications
- Disaster Response
- Flood Management
- Earthquake Recovery
- Emergency Medical Services
- Fire & Rescue Operations
- Urban Infrastructure Planning
- Smart Cities
- Military Logistics
- Humanitarian Relief Operations
