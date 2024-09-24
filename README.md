# Machine-Learning-models-for-Stage-Discharge-Rating-Curve-Prediction-across-CONUS
Anupal Baruah, Reihaneh Zarrabi, J. Michael Johnson, Sagy Cohen

The increasing occurrence of flood events, amidst rapidly changing environments, highlight the need for greater hydrological data availability at to facilitate robust decision-making strategies. Hydrological rating curves, which translate fluvial water height/stage to streamflow or vice versa, play a pivotal role in various applications, including flood inundation modeling, catchment hydrology, and studies related to river geomorphology. Power law equations have been found to be an appropriate proxy for the nonlinear relationship between flow discharge and water level in natural systems. Hydrological rating curves are commonly used and reported in river gauging locations, in which stage monitoring and discharge measurements are available. This study aims to develop a heirarchical data-driven approach to estiamte the power-law rating curve parameters (α, β) across the river network of the CONtiguous United States (CONUS). The development of this model is motivated by our interest in exploring a unifying solution to better link rating curve parameters with channel shape, catchment properties, and hydro-climatological characteristics. These, in turn, can be applied to operational hydrological forecasting frameworks, such as the NOAA Office of Water Prediction Next Generation Water Resource Modeling framework (NextGen), to enhance model parameterization and inputs (e.g. the NextGen Hydrofabric) to improve river routing and flood inundation mapping effors. In this study, we used the HYDRoacoustic dataset in support of the Surface Water Oceanographic Topography satellite mission (HYDRoSWOT), National Hydrography datasets (NHDPlus version2.1), and STREAM-CATCHMENT (STREAMCAT) datasets to develop a suite of models for predicting α and β. The first tier of models in our hierarchical setup fociuses on input parameters that are limited to gauged locations and thus, while offering better accuracy, have limited application. The second-tier models offer a good compromise between accuracy and applicability across the CONUS. Four empirical models, namely Multivariate regression, eXtreme Gradient boosting (XGBoost), Random Forest regression, Support vector regression, are compared. The results show that XGBoost yielded the strongest model for α with an R2 of 0.67 for the first tier and 0.55 for the second-tier models. For β, R2 is found as 0.74 for the first tier and 0.70 for the second-tier models. The results show satisfactory performance in river reaches with mean annual discharge greater than 5 m3/s. The minimum Euclidian distance index was calculated to quantify the similarity between the model-derived and observed rating curves at thirty USGS gauge stations. We also compared the stage from the predicted rating curves with the observed stage and found a good agreement. The spatial distribution of the predicted α and β parameters across CONUS are explored. We analyzed the topography and hydro climatological influence on rating curves throughout CONUS and observed that α and β are more sensitive to elevation, aridity index, and rainfall patterns.
<p align="center">
  <div style="display: inline-block; text-align: center;">
    <img src="https://github.com/user-attachments/assets/18330e3b-0b75-45dd-8240-7ba9bf8d7994" width="250" alt="USGS Rating Curve Stations Across CONUS">
    <p><b>Figure 1: USGS Rating Curve Stations Across CONUS</b></p>
  </div>
  <div style="display: inline-block; text-align: center;">
    <img src="https://github.com/user-attachments/assets/d5d41354-ee65-4350-8233-9d24aee619c7" width="250" alt="Predicted Rating Curve Coefficient">
    <p><b>Figure 2: Predicted Rating Curve Coefficient</b></p>
  </div>
  <div style="display: inline-block; text-align: center;">
    <img src="https://github.com/user-attachments/assets/c9cf6386-f5dd-47d6-99a2-1b88670d0220" width="250" alt="Predicted Rating Curve Exponent">
    <p><b>Figure 3: Predicted Rating Curve Exponent</b></p>
  </div>
</p>

                                                                         









