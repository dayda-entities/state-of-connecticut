---
title: Salt Water Limit
created: '2020-12-04T18:55:31.010518'
modified: '2020-12-04T18:55:31.010526'
state: active
type: dataset
tags:
  - Connecticut Coast
  - Ct
  - Ctdeep
  - Data
  - Deep
  - Hydrography
  - Limit
  - Long Island Sound
  - Open
  - Open Data
  - Rivers
  - Salt
  - Salt Water Extent
  - Salt Water Limit
  - Streams
  - Water
groups:
  - Local Government
csv_url: >-
  https://ct-deep-gis-open-data-website-ctdeep.hub.arcgis.com/datasets/cf96fdfbd01b42bca3b8350c35c29169_0.csv?outSR=%7B%22latestWkid%22%3A2234%2C%22wkid%22%3A102656%7D
json_url: >-
  https://services1.arcgis.com/FjPcSmEFuDYlIdKC/arcgis/rest/services/Salt_Water_Limit/FeatureServer/0
layout: post

---
Salt Water Limit is a 1:24000-scale, line feature-based layer that depicts the approximate salt water limits of watercourses and embayments in coastal Connecticut. It is important to note that the exact demarcation of the salt-water extent is often not accurate. As stated in the report known as Source 1 in this metadata ("The Boundary Between Freshwater and Saltwater in Connecticut"): "Any definition and demarcation of the boundary between saltwater and freshwater is, of necessity, an approximation. The boundary is transitory and, at times, vague. Within a given body of water, it may vary from day to day, season to season, and year to year, according to such predictable and unpredictable factors as tidal magnitude, rate of evaporation, climatological and meteorological factors, estuarine circulation patterns, and the degree of vertical salinity stratification. An exact delimitation of the upstream limits of saltwater would be a difficult task and one that is probably not necessary for the purposes of coastal management in Connecticut. However, since the primary goal of Connecticut's Coastal Area Management Program is to provide for the balanced, coordinated management of coastal resources, the coastal waters of the state must be clearly and uniformly defined as required in federal and state legislation."
The source data for this layer (a compilation of reports and maps) varied in cartographic scale and age but features were digitized onto standard 1:24,000 scale US Geological Survey (USGS) topographic quadrangle maps. Because of this, the layer does not represent conditions at any particular point in time, nor does every waterbody have an associated salt water extent. This data layer has been updated in 2005 to include more robust attribute information, but no further updates are planned.
Attribute information is comprised of an AV_LEGEND attribute that identifies the feature as the salt water extent ("Salt Limit"), eight "DATASRC[1-8]" attributes that contain a boolean (0,1) value identifying whether or not that particular source was used, a NOTES attribute for additional data source descriptions, a QUADNUMBER attribute and a QUAD_NAME attribute.
