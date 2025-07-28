# GEOSPATIAL-PROJECT

## SpaceX Launch Site Location Analysis with Folium

This project is part of a geospatial data analysis exercise using the Folium library in Python. It focuses on visualizing SpaceX launch sites and their proximity to key infrastructure like cities, highways, coastlines, and railways.

###  Objectives

* Plot all known SpaceX launch sites on an interactive Folium map.
* Color-code markers based on launch success/failure.
* Use proximity analysis to calculate distance to nearby features.
* Add markers and polylines for visualizing spatial relationships.
* Draw insights based on map analysis.

---

### Project Files

| File Name                                            | Description                                                                |
| ---------------------------------------------------- | -------------------------------------------------------------------------- |
| `lab_jupyter_launch_site_location_FINAL_COLAB.ipynb` | Final Google Colab-compatible notebook containing all code and analysis.   |
| `spacex_launch_geo.csv`                              | CSV file with SpaceX launch data including coordinates and launch success. |

---

###  Key Features

* **Launch Site Markers**: Interactive markers for all launch sites.
* **Success/Failure Icons**: Green = success, Red = failure.
* **Proximity Markers**: Nearest city, railway, highway, and coastline shown.
* **Distance Lines**: Polylines show spatial proximity from launch sites to infrastructure.
* **Interactive Map**: Built with `folium.Map()` and `folium.MarkerCluster()`.

---

### Insights Answered

* Are launch sites in close proximity to railways?
* Are launch sites near coastlines or highways?
* Are launch sites isolated from cities?
* Do launch failures correlate with location factors?

---

### Tech Stack

* **Python 3.12+**
* **Folium**
* **Pandas**
* **Geopy**
* **Google Colab** 

---

###  How to Run

1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/).
2. Ensure required libraries are installed
3. Run all cells from top to bottom.
4. Interact with the maps and explore the results.



### 🙌 Author

**Lance Midzi**
Graduate Student, Data Analytics & Visualization
Yeshiva University | 🇺🇸

---

