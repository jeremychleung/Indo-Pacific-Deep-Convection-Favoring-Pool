<!-- # Indo-Pacific Deep Convection Favoring Pool -->
Indo-Pacific Deep Convection Favoring Pool <br />
(Indo-Pacific Warm Pool defined with time-varied SST threshold)
=====
[![DOI](https://zenodo.org/badge/520879810.svg)](https://zenodo.org/badge/latestdoi/520879810) <br />
This repository contains the data of the time-varied SST threshold for deep convection (σ<sub>SST_conv</sub>) and Indo-Pacific Deep Convection Favoring Pool (DCFP).
<br /> <br />
 
<!-- 
**Overview**
-----
- This repository contains the data of the Indo-Pacific Deep Convection Favoring Pool (Indo-Pacific Warm Pool defined with time-varied SST threshold).
 <br />  
 -->


**About the time-varied SST threshold for deep convection (σ<sub>SST_conv</sub>)**
-----
- σ<sub>SST_conv</sub> is estimated by the joint frequency distribution (JFD) of SST and precipitation (P) over the Indo-Pacific Ocean, which reflects the joint probability (i.e., area of grid points) that certain values of SST and P cover.
- σ<sub>SST_conv</sub> for convection with a particular precipitation level (P0) is defined as the minimum SST where more than 80% of the area with P = P0 is observed throughout the year, assuming that a small proportion of deep convection is not only triggered purely by warm ocean surface but also induced by other atmospheric systems and dynamic factors, such as tropical waves, tropical cyclones etc. 
- Please refer to [Leung et al. (2022)](https://doi.org/ ) for more detail about the calculation procedure and the science behind it.
 <br /> 
 
 
**About the Indo-Pacific Deep Convection Favoring Pool (DCFP)**
-----
- The DCFP refers to the ocean that fulfils the SST criterion of favoring atmospheric deep convection, which shares the same concept of the traditional IPWP definition except for considering the time-varied σSST_conv.
- The DCFP area is defined as the total area of the Indo-Pacific Ocean (25°S–25°N, 40°E–220°E) enclosed by the isotherm of a time-varied SST threshold of deep convection (σ<sub>SST_conv</sub>). 
- Please refer to [Leung et al. (2022)](https://doi.org/ ) for more detail about the calculation procedure and the science behind it.
 <br /> 
 
**Files**
-----
<!--
- GMM index derived based on the ERA-Interim reanalysis
  - Location: [data/gmm_index_erai.csv](https://github.com/jeremychleung/Geopotential-based-Multivariate-MJO-Index/blob/main/data/gmm_index_erai.csv)
  - Temporal coverage: 1979–2013
-->
- σ<sub>SST_conv</sub> derived based on ERSSTv5 and GPCP
  - Description: Time-varied SST threshold (σ<sub>SST_conv</sub>) for deep convection of intensity, derived based on SST (from ERSSTv5) and precipitation (GPCP).
  - Location: [data/02-sst_threshold_ersst_gpcp.csv](https://github.com/jeremychleung/Indo-Pacific-Deep-Convection-Favoring-Pool/blob/main/data/02-sst_threshold_ersst_gpcp.csv)
  - Temporal coverage: 1979–2020
  - Rows: Year
  - Columns: Convection intensity (defined based on average monthly precipitation)
- σ<sub>SST_conv</sub> derived based on HadISST and GPCP
  - Description: Time-varied SST threshold for deep convection (σ<sub>SST_conv</sub>) derived based on SST (from HadISST) and precipitation (GPCP).
  - Location: [data/02-sst_threshold_hadisst_gpcp.csv](https://github.com/jeremychleung/Indo-Pacific-Deep-Convection-Favoring-Pool/blob/main/data/02-sst_threshold_hadisst_gpcp.csv)
  - Temporal coverage: 1979–2020
  - Rows: Year
  - Columns: Convection intensity (defined based on average monthly precipitation)
<br /> 
  

**Citation**
-----
If you use the GMM index in a publication or for any other purposes, please cite 
<!--
- Leung, J.CH., Qian, W., Zhang, P. et al. Geopotential-based Multivariate MJO Index: extending RMM-like indices to pre-satellite era. Clim Dyn (2022). https://doi.org/10.1007/s00382-022-06142-2
-->
- Leung, J.CH., Zhang, B., Gan, Q. et al. On the differential expansion speeds of Indo-Pacific warm pool and deep convection favoring pool under greenhouse warming.  npj Climate and Atmospheric Science (under Review). 
- Zenodo archive: https://doi.org/10.5281/zenodo.6977568

<br /> 

**References**
-----
<!-- - Wheeler, M.C., Hendon, H.H. An All-Season Real-Time Multivariate MJO Index: Development of an Index for Monitoring and Prediction. Mon Weather Rev 132:1917–1932 (2004). https://journals.ametsoc.org/view/journals/mwre/132/8/1520-0493_2004_132_1917_aarmmi_2.0.co_2.xml -->
- Leung, J.CH., Zhang, B., Gan, Q. et al. On the differential expansion speeds of Indo-Pacific warm pool and deep convection favoring pool under greenhouse warming.  npj Climate and Atmospheric Science (under Review). 
- Hoyos, C.D., Webster, P.J. Evolution and Modulation of Tropical Heating from the Last Glacial Maximum through the Twenty-First Century. Climate Dynamics (2012).
- Johnson, N.C., Xie, S.P. Changes in the Sea Surface Temperature Threshold for Tropical Convection. Nature Geoscience (2010).
<br /> 


**Contact**
-----
If you have any questions about the data, feel free to contact Dr. Jeremy Leung (chleung@pku.edu.cn or liangzx@gd121.cn).
<br /> 
