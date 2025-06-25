# 🎯 Oil Production Analysis  

This project applies spatial analytics and geostatistical modeling to improve oil well placement and production strategy. By leveraging geological survey data and kriging interpolation, we identified high-potential drilling zones to support data-driven decision-making in oil exploration.
This analysis was conducted as part of the DSO 545: Statistical Computing and Data Visualization course at the University of Southern California.

---

## 📊 Project Overview

Oil field exploration involves complex geological variables such as porosity, depth, and pressure. This project used spatial modeling and statistical computing techniques to predict porosity in unsampled locations and recommend efficient drilling zones.

We started with a cleaned dataset containing geological features across hundreds of well sites. The core steps of the project included:

- Preprocessing production and geostatistics data  
- Modeling spatial dependence using variograms  
- Applying **Ordinary Kriging** to estimate porosity across the field  
- Visualizing potential drilling zones using contour maps and 3D surface plots  
- Interpreting spatial patterns to support well planning decisions  

---

## 🎯 Objectives

- Predict porosity values in regions where no well data exists  
- Uncover spatial trends in subsurface geology  
- Recommend drilling locations that maximize production potential  
- Reduce exploration risk and improve planning with data visualization  

---

## 🧪 Techniques & Models Used

| Method              | Purpose                                                        |
|---------------------|----------------------------------------------------------------|
| Ordinary Kriging     | Interpolates porosity based on spatial correlation            |
| Variogram Modeling   | Quantifies spatial structure and influences of distance       |
| Contour Mapping      | Highlights zones of high porosity visually                    |
| Surface Plotting     | Provides 3D perspective on subsurface properties              |
| Correlation Analysis | Assesses relationships among depth, porosity, and production  |

---

## ✅ Key Insights

- Three distinct zones with high porosity were revealed through kriging interpolation  
- Porosity was positively correlated with production and negatively with depth  
- Optimal drill locations were recommended in regions with high interpolated porosity and accessible depth  
- Visualizations significantly improved interpretability and communication with non-technical stakeholders  

---

## 📂 Data Sources

- `Oil_production_data.csv`: Contains production volumes, porosity, and depth at various well sites  
- `Geostatistics_data.csv`: Cleaned and formatted dataset used for spatial modeling  

---

## 💡 Tools & Technologies

- **Python**  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Plotly** for 3D surface visualizations  
- **PyKrige** for kriging implementation  
- **Excel** for initial exploration and formatting  

---

## 📈 Business Impact

By applying spatial statistics and visualization, this project enables:

- Smarter drilling decisions based on predictive analytics  
- Cost savings through reduced reliance on trial drilling  
- Enhanced planning by visualizing geology in intuitive formats  
- A scalable workflow that can be extended to other reservoirs  

---

## 🚀 Potential Extensions

- Add seismic and satellite-derived data for co-kriging  
- Integrate economic cost models to prioritize drill zones  
- Build a web dashboard for real-time spatial insights  
- Extend analysis to include water injection and pressure maintenance planning  
