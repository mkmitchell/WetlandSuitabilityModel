# WetlandSuitabilityModel
Wetland suitability model used by Ducks Unlimited.

Originally written by Stacey Shankle, Dawn Browne, and Jerry Holden Jr. around 2005.
Updated by Mike Mitchell in 2017

<b>Abstract</b><br>
The Mississippi Alluvial Valley (MAV), encompassing nearly 26 million acres, boasts high species richness yet is one of the nation’s most ecologically degraded landscapes.  Historically supporting the most expansive continuous bottomland hardwood forest ecosystem in North America, the MAV experienced profound modifications during the 20th century, from the clearing of approximately 80% of historic forest cover to widespread hydrologic engineering for flood control.  Currently, the MAV is undergoing substantial reforestation, driven by falling agricultural commodity prices, Farm Bill initiatives, and a collaborative effort of federal, state, and non-governmental entities.  <br>
Ducks Unlimited, Inc. (DU), as one of the primary delivery agents of the USDA Natural Resource Conservation Service’s Wetland Reserve Program in the MAV, has constructed a reforestation priority model for identifying optimal sites for restoration of forested wetlands in the region.  The model harnesses the functionality of ERDAS Imagine’s Expert Classifier to construct a logical decision tree that considers weighted confidence values in pixel classification, thereby permitting more sophisticated analysis than afforded by traditional modeling methods.  The output of the restoration priority model represents the culmination of three years of data development projects by DU with assistance from regional conservation partners.  The model facilitates intelligent analysis of multiple, regional datasets critical to determining site suitability in the MAV, including: a Soil Moisture Index (DU), Natural Flood Frequency (DU), a 1973-2001 Forest Loss dataset (DU), Sinks/Depressional Areas (DU derived from USGS National Elevation Dataset (NED)), and graduated stream buffers by stream order (DU derived from USGS/USEPA National Hydrography Dataset).  The output of the restoration priority model will assist with directing the future reforestation efforts of multiple parties to the most appropriate locations throughout the MAV. 
<br>
<br>
<b>Parameters</b><br>
Flood frequency - Yvonne Allen's GCPO Flood frequency<br>
Soil moisture - SSURGO wetland suitability<br>
Sinks - DEM calculation<br>
Stream buffers - NHD streams buffered<br>
Forest change - NLCD comparison<br>
