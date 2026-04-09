# 🌍 ALIVE Hourly Data Access Tutorial

**An empirical benchmark for near real-time surface–atmosphere carbon dioxide and energy fluxes**

This repository provides a step-by-step tutorial for accessing and working with **ALIVE Hourly data** using modern cloud-native data formats like **Zarr**.

---

## 📌 Overview

This project demonstrates how to:

* Access ALIVE hourly datasets
* Work with cloud-hosted scientific data
* Use **Zarr** for efficient large-scale data handling
* Analyze carbon, water, and energy fluxes

The dataset includes:

* **Carbon fluxes**: NEE, GPP, RECO
* **Water flux**: Latent Heat (LE)
* **Energy fluxes** and related environmental variables

---

## 🌱 Background

Understanding ecosystem processes at **sub-daily (hourly) resolution** is critical because:

* Environmental conditions (light, temperature, moisture) change rapidly
* Carbon and energy exchanges respond dynamically
* Traditional datasets often lack temporal resolution

The ALIVE dataset bridges this gap using near real-time satellite observations.

---

## 🛰️ Data Sources

The data is derived from:

* **GOES-R satellites (Geostationary Operational Environmental Satellites)**
* **Advanced Baseline Imager (ABI)**
* Ground validation from:

  * AmeriFlux towers
  * NEON sites

---

## 📦 Technologies Used

* **Python**
* **NumPy** – numerical computing
* **Pandas** – data manipulation
* **Xarray** – labeled multi-dimensional arrays
* **Zarr** – cloud-native storage format
* **fsspec** – filesystem interface for cloud storage

---

## ⚡ Why Zarr?

Zarr enables:

* Chunked and compressed storage
* Parallel data access
* Efficient cloud-based workflows
* Scalability for large datasets

Perfect for Earth science and remote sensing applications.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/alive-hourly-data-tutorial.git
cd alive-hourly-data-tutorial
```

### 2. Install Dependencies

```bash
pip install numpy pandas xarray zarr fsspec
```

### 3. Run the Notebook

Open the notebook:

```bash
jupyter notebook
```

Then run:

```
LESSON_TO_ACCESS_ALIVE_V3_PUBLIC_DATA_SHARE.ipynb
```

---

## 📊 What You'll Learn

* How to open remote Zarr datasets
* How to explore multi-dimensional environmental data
* How to visualize time-series flux data
* How to handle large datasets efficiently

---

## 📁 Repository Structure

```
├── LESSON_TO_ACCESS_ALIVE_V3_PUBLIC_DATA_SHARE.ipynb
├── README.md
└── assets/ (optional images or figures)
```

---

## 🤝 Contributing

Contributions are welcome! You can:

* Improve documentation
* Add visualizations
* Extend analysis workflows

---

## 📜 License

This project is open-source. Add your preferred license here (e.g., MIT, Apache 2.0).

---

## 📖 Citation

If you use this dataset or workflow, please cite:

**Ranjbar et al. – ALIVE Hourly Dataset**

(Add full citation when available)

---

## 💡 Acknowledgments

* ALIVE project contributors
* Earth observation and remote sensing community
* Open-source Python ecosystem

---

## 📬 Contact

For questions or collaboration:

* Open an issue
* Reach out via GitHub or sadegh.ranjbar@yale.edu
