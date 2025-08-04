# 🌍 Global Riverine N₂O Emissions Processor

This project provides an R-based processing pipeline to analyze nitrous oxide (N₂O) emissions from global riverine systems using raster datasets. It leverages data from the [CMS: Global Riverine N₂O Emissions, 1900–2016](https://daac.ornl.gov/CMS/guides/Global_Riverine_N2O_Emissions.html) dataset.

---

## 📁 Project Structure

```text
📦 Global-Riverine-N2O-Emissions-Processor
├── N2O-N_Emission_Compile_All.R
│   └─ Main driver script: orchestrates data loading, filtering, plotting, and final outputs.
│
├── N2O-N_Emission_Specific_Type_Calc_n_Plot.R
│   └─ Called by main script to handle raster operations per emission category and stream order.
│
├── N2O_N_Emission.cfg
│   └─ Configuration file to define parameters (years, thresholds, paths, OS).
│
├── Slider_Year_Range_Filter.R
│   └─ Interactive year-range selector used in the main script.
│
└── /output/
    └─ Raster outputs (GeoTIFF, PNG) and cumulative summaries

```

### 🧭 Processing Workflow

![Slide 1 - Workflow](figures/slide_02.png)

### 📈 Raster summation methods

![Slide 2 - Emissions Comparison](figures/slide_03.png)

### 📈 Visual comparison both methods

![Slide 3 - Emissions Comparison](figures/slide_09.png)

### 📈 Visual summation 2 categoris emissions method 1

![Slide 4 - Emissions Comparison](figures/slide_11.png)

### ![📂 See all slides →](figures/)

