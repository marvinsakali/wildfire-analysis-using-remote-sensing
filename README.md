# Burnt Area Severity Assessment and Vegetation Dynamics Monitoring in Mt. Kenya Using Satellite Imagery and Google Earth Engine
## Abstract
In the recent years, wirlddires have frequently and increasingly posed a significant threat to the forest ecosystem. In Kenya, Mt. Kenya’s forest a UNESCO World Heritage Site and one of Africa’s most important water towers, a critical ecosystem for biodiversity and water catchment, has experienced several wildfires over recent years. On the 10th, March 2019 is on of the most recent wildfire accorance on the region which have led to significant ecological and socio-economic impacts in the region, including biodiversity loss, changes in soil properties, and threats to water resources. 

### The main objectives of this study are:

To detect and map the extent of burnt areas in Mt. Kenya using satellite imagery in Google Earth Engine.
To assess burn severity by applying the Normalized Burn Ratio (NBR) and other relevant indices.
To analyze post-fire vegetation changes satellite data.

This study will provide essential insights into the impact of wildfires on Mt. Kenya’s ecosystem, offering data-driven solutions for restoration efforts. The findings will aid policymakers and forest managers in making informed decisions on fire mitigation, forest rehabilitation, and sustainable land use practices.

## Methodology
### Data
This study utilized Landsat 8 satelite imagery for the analysis. Landsat 8 was launched by NASA and the U.S. Geological Survey (USGS) on February 11, 2013, as part of the ongoing Landsat program, which has provided continuous Earth observation data since 1972. This satellite orbits in a sun-synchronous pattern, allowing it to revisit the same location every 16 days. Landsat 8's primary purpose is to monitor Earth's land and coastal regions, providing crucial data for a wide range of environmental and scientific studies, including land use, ecosystem health, and climate change analysis.
Images before the fire and immediately after the fire were loaded in the Google Earth Engine enviroment and visualized

### Image Processing
Landsat 8 being an optical remote sensing data, it is highly affected by clouds, their associated clouds and snow. This tends to often obscure the Earth's surface, leading to inaccuracies in analyses. To overcome all this a cloud and snow mask was performed to remove the cloud covered pixels in the image.Landsat 8 provides cloud masking capabilities through the Quality Assessment (QA) band, which includes flags for different types of clouds (e.g., cirrus clouds) and cloud shadows.
### Burnt Area Detection
The Normalized Burn Ratio (NBR) will be used to identify burnt areas:
The Normalized Burn Ratio (NBR) is an index designed to highlight burnt areas in large fire zones.  Healthy vegetation shows a very high reflectance in the NIR, and low reflectance in the SWIR portion of the spectrum he opposite of what is seen in burnt areas
       
        NBR = NIR−SWIR/NIR+SWIR
![FireShot Capture 019 - Normalized Burn Ratio (NBR) - UN-SPIDER Knowledge Portal - un-spider org (1)](https://github.com/user-attachments/assets/003ddb0b-7eff-4ed5-af19-216125c5f112)

### Burn Severity
The difference between the pre-fire and post-fire NBR obtained from the images is used to calculate the delta NBR (dNBR or ∆NBR), which then can be used to estimate the burn severity. A higher value of dNBR indicates more severe damage, while areas with negative dNBR values may indicate regrowth following a fire. The formula used to calculate dNBR is illustrated below:
      
       dNBR=NBRpre-fire−NBRpost-fire
​
![FireShot Capture 020 - Normalized Burn Ratio (NBR) - UN-SPIDER Knowledge Portal - un-spider org](https://github.com/user-attachments/assets/c234d95b-1745-4d64-a6f4-749251f55f28)
 Keeley, J. E. (2009). Fire intensity, fire severity and burn severity: A brief review and suggested usage. International Journal of Wildland Fire, 18(1), 116–126
 ### Vegetation Damage
 NDVI was calculate and change in NDVI visualized. This was used to determine the amount of vegetation damage caused by the fire.
## Results

## Conclusion
The study successfully maps and assesses the burnt areas in Mt. Kenya using satellite imagery. Burn severity varies significantly across the region, influencing post-fire vegetation recovery. The use of remote sensing tools like Google Earth Engine proves effective in wildfire monitoring and can be a vital resource for forest management.
​
