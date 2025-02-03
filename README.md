# Accessibility analysis using Point Kernel Density Estimation (KDE) and Buffer
## Overview
This project aims to understand the distribution pattern of tourism object points ​and discover whether the location of Transjakarta Shelters in Jakarta ​(Kepulauan Seribu Regency is excluded) can reach all tourist ​destinations by employing Geographic Information System (GIS) and ​spatial data programming tools.

We determined that tourism objects considered accessible are those located within a 1 km buffer zone. This radius is based on research by Larasati et al. (2022), which defines it as the maximum distance pedestrians can travel to reach a destination. 

**Limitation:** This analysis is only based on buffer proximity analysis and does not consider the road networks.
## Data
All data collected from [Open Map Jakarta Satu Geoportal](https://jakartasatu.jakarta.go.id/portal/apps/sites/#/public) can be downloaded from the folder Data. This folder includes four data in a vector (shapefile) format: 
1. Administration Boundary of Jakarta (excluding Kepulauan Seribu Regency) (polygon);
2. Tourism Objects (point);
3. Transjakarta Shelters (point); and
4. Transjakarta Route (polyline). <br />
**Note:** Data was collected in 2023, therefore, there might be some updates in recent times that are not included in this analysis and visualization.
## Notebook
Codes in the notebook include five primary stages:
1. Read and visualize each shapefile;
2. Kernel density analysis of tourism object distribution in Jakarta;
3. Buffer analysis for Transjakarta Shelters with 1-km radius;
4. Accessibility analysis; and
5. Final map visualization. <br />
### Reference
* Larasati, A. F., Nurlaela, S., dan Susetyo, C. (2022). Analisis Keterjangkauan Fasilitas Halte pada Koridor Ruas Jalan Kota. Jurnal Penelitian Transportasi Darat, 24(1), 28–34. ​https://doi.org/10.25104/jptd.v24i1.2098.
* Pemerintah Provinsi Daerah Khusus Ibukota Jakarta. (n.d.). Open Map Jakarta Satu. https://jakartasatu.jakarta.go.id/portal/apps/sites/#/public.
### Contact
For suggestions and collaboration, kindly reach me at: [LinkedIn](https://www.linkedin.com/in/rizka-amelia-dwi-safira/) or rizkasafira20@gmail.com.
