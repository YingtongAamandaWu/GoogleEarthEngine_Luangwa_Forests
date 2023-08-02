# Using Google Earth Engine to evaluate annual forest loss in Luangwa Forests
**Quick summary: ** This is a Python-based analysis of the Hassen Forest Global Watch Data using Google Earth Engine. The goal is to access annual forest loss within the carbon project area.  

**Data source:**

Hansen, M. C., P. V. Potapov, R. Moore, M. Hancher, S. A. Turubanova, A. Tyukavina, D. Thau, S. V. Stehman, S. J. Goetz, T. R. Loveland, A. Kommareddy, A. Egorov, L. Chini, C. O. Justice, and J. R. G. Townshend. 2013. "High-Resolution Global Maps of 21st-Century Forest Cover Change." Science 342 (15 November): 850-53. 10.1126/science.1244693 Data available online at: https://glad.earthengine.app/view/global-forest-change.
See link https://developers.google.com/earth-engine/datasets/catalog/UMD_hansen_global_forest_change_2022_v1_10

**Background:**

The Luangwa Valley is known for its rich biodiversity and critical ecological significance, making it essential to understand and monitor the extent of deforestation and forest degradation in the region. This project leverages the power of Google Earth Engine for extracting valuable insights on forest cover variations over time. The repository serves as a hub for python code, data sources, documentation, and visualizations. 

**Installation Required:**  Python3, Jupyter Notebook Required Python packages: numpy, pandas, scipy.stats, statsmodels.stats.api, matplotlib, matplotlib.pyplot

**Main Findings:**

(1) A higher number of forest canopy loss from 2001 to 2022 within reference area than the project area:

**Figure 1:** Forest canopy loss from 2001 to 2022 in and around the Luangwa community forests project (LCFP) area. The LCFP project area is highlighted in green polygons, and the reference area is highlighted in orange polygons. Red pixels indicate forest loss since 2001 using the data from Hansen Global Forest Change v1.10 (2000-2022) (Hansen et al., 2013). The background aerial image is a composite image of bands 5, 4, and 3 from Landsat-7, where healthy vegetation is bright green and soils are mauve; dark blue indicates water bodies. 

![Screenshot 2023-08-02 140024](https://github.com/YingtongAamandaWu/GoogleEarthEngine_Luangwa_Forests/assets/80353259/d31a7a0c-6078-47c6-aaf9-2eb0a5e39b3b)

(2) A much faster increase in forest canopy loss from 2001 to 2002 within the reference area than project area:

**Figure 2:** Forest canopy loss from 2001 to 2022 within the reference area (orange line) and within the project area (green line), respectively. 
![Figure2](https://github.com/YingtongAamandaWu/GoogleEarthEngine_Luangwa_Forests/assets/80353259/fcf7289b-dfd2-4551-be54-54aff9823320)

