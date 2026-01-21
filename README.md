# UIC Campus Geographic Graph System

A C++ program that builds a geographic graph from OpenStreetMap data and computes the **shortest path between two buildings on the UIC campus** once you specify the start and end locations.

---

## Overview

The UIC Campus Geographic Graph System prompts users to input their given .osm file to use as the UIC campus. After, the users most imput the building they are starting at and the building they want to go to.

This application allows user to:
- Input their starting and ending UIC buildings on campus
- Automatically compute the shortest path using a Dijkstra's algorithm

## Features

- Parses OpenStreetMap (OSM) data
- Builds a graph from provided geographic map data
- Computes the shortest path between two campus buildings

---

##  How to Run

### Prerequisites
- C++ compiler (e.g., `g++` or `clang++`)
- WSL or other native window alternatives in order to use makefiles

### Run the Application
From the project root directory:

- Using native bash without makefile
```bash
g++ application.cpp osm.cpp dist.cpp tinyxml2.cpp -o application.exe
./application.exe
```

- Using makefile
```bash
make build
make run
