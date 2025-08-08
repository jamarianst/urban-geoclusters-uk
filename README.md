# Urban GeoClusters in the UK

## 📍 Overview
This project uses KMeans clustering to analyze the geographic distribution of urban areas in Great Britain. We explore how spatial coordinates (longitude and latitude) can be used to group nearby cities and towns, and how these clusters relate to actual population centers.

The goal is to apply unsupervised learning to real-world spatial data, visualize the results, and interpret the meaning of the clusters.

---

## 🧾 Dataset
- **Name:** UrbanGB.txt (provided in CSCI 3360E)
- **Source:** Course-provided dataset listing coordinates and labels of urban locations in the UK
- **Format:** Tab-separated text file with:
  - `coords` → a string like `"longitude,latitude"`
  - `city_label` → city name or indicator

> 📌 The dataset is not included due to licensing. To run this notebook, place `urbanGB.txt` in the `/data` directory.

---

## 🔍 Methods
- Parse and split coordinates into `longitude` and `latitude`
- Scale longitude to correct for map distortion
- Use KMeans clustering to group urban areas
- Visualize clusters on a 2D plot
- Overlay actual city labels to assess how well the clusters correspond to real urban centers

---

## 📈 Sample Visualization
![Clusters of Urban Areas in GB](https://your-image-link-if-you-host-one.png)

Each cluster is color-coded, and geographic coordinates are plotted in 2D space.

---

## 🧠 Key Takeaways
- Spatial clustering with KMeans can approximate geographic groupings
- Clusters sometimes align with major urban regions (e.g., London area, Midlands)
- Longitude scaling is necessary for accurate visualization
- Good introduction to unsupervised learning on geographic data

---

## 🚀 How to Run
1. Clone this repository:
```bash
git clone https://github.com/<your-username>/urban-geoclusters-uk.git
cd urban-geoclusters-uk
