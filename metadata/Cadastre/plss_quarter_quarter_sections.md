# Title

Utah PLSS Quarter Quarter Sections GCDB

## ID

4b63af59-da17-40dd-bf40-2996c489fc4d

## Brief Summary

Cartographic representation of the smallest unit of the Public Land Survey System (PLSS), where each polygon represents 40 acres of land.

## Summary

This dataset represents the GIS Version of the Public Land Survey System. GCDB base attribute data was used to create the second division feature class.

## Description

### What is the dataset?

The second division of the PLSS is quarter, quarter-quarter, sixteenth or government lot division of the PLSS. The second and third divisions are combined into this feature class as an intentional de-normalization of the PLSS hierarchical data. The polygons in this feature class represent the smallest division that has been defined for the first division. In most cases the smallest division for the cadastral reference will be the sixteenth but in some cases sections have only been divided to the quarter. Divisions below the sixteenth may be included in this feature class, but in most implementations these smaller divisions will be parcels.

This dataset is the fourth level of a hierarchical break down of the Public Land Survey System Rectangular surveys. This data is Version 2.3 2020 of the [Utah PLSS Fabric](https://gis.utah.gov/products/sgid/cadastre/parcel-fabric/). The primary source for the data is cadastral survey records housed by the BLM supplemented with local records and geographic control coordinates from states, counties as well as other federal agencies such as the USGS and USFS. This data was orginally published on 1/3/2017.

### What is the purpose of the dataset?

This data is a useful representation of the geometry and topology of parcels contained within the PLSS, but its application is intended for mapping purposes only. The GCDB data is not a substitute for a legal land survey.

### What does the dataset represent?

The attributes assigned to PLSS polygons were taken from the BLM's Legal Land Description (LLD) data set, contained within the Legacy Rehost for the year 2000 (LR2000) automated records system. The coordinate data was produced by using control stations of known location, with varying degrees of accuracy, from various sources which include but are not limited to; U.S. Geological Survey (USGS) topological quadrangles and other sources, National Geodetic Survey (NGS) and US Coast & Geodetic Survey (USC&GS) Cooperative Base Network (CBN) control, Federal Base Network control (FBN), and Continuous Operating Reference Stations (CORS), and Global Positioning System (GPS) data, which is then analyzed and adjusted in concert with official survey data for any given geographic area.

### How was the dataset created?

The locations of Public Land Survey System (PLSS) corners, as represented in geographic coordinate pairs, were derived from a variety of source documents, which include U.S. General Land Office and BLM survey plats/notes, as well as survey data obtained from other U.S. Government agencies, private sector survey firms, and local governments.

Lots were dissolved to the section level. Survey_type: B (aliquot parts less than 40 acres) for geopolitical splits were attributed as Survey_type: A. This data is derived from the PLSS Intersected feature class of the Utah PLSS Fabric GISv2.3 2020. This layer is based on Geographic Coordinate Data Base (GCDB) coordinate data.

### How reliable and accurate is the dataset?

Cadastral publication data has two primary components, land parcel data and cadastral reference data. It is important to recognize that the publication data are not the same as the operation and maintenance or production data. The production data is structured to optimize maintenance processes, is integrated with internal agency operations and contains much more detail than the publication data.

## Credits

### Data Source

### Host

## Restrictions

This statewide dataset is maintained by UGRC in partnership with the BLM and local government. The geographic coordinates and their associated products are NOT legal land survey records. The coordinates can NOT be used as a substitute for a legal land survey. They can be used for record keeping, mapping, graphics and planning purposes only. No warranty is made by the Bureau of Land Management for use of the data for purposes not intended by BLM.

## License

## Tags

## Secondary Category

## Data Page Link

## Update

Updates were made to Quarter Quarter Sections in Utah County to add quarter-quarter sections to areas that were not broken down less than the Section level. These are labeled as SECDIVTYP = Z and SECDIVTXT = Unsurveyed Unprotracted. They were added, using information from points collected by county surveyors, that is in the data and extrapolating information from adjoining sections wherever possible. They are still areas that could not be interpreted well enough and they were left empty, beyond the section level. In the future this data will continue to be carried in this feature class but not incorporated into the official PLSS Fabric.

### Update Schedule

This dataset is updated as needed.

Updates are expected annually as horizontal control positions from published sources and global positioning system (GPS) observations are added.

Updated 12/15/2020

Updates were made to Quarter Quarter Sections in Utah County to add quarter-quarter sections to areas that were not broken down less than the Section level. These are labeled as SECDIVTYP = Z and SECDIVTXT = Unsurveyed Unprotracted. They were added using information from points collected by county surveyors, that is in the data and extrapolating information from adjoining sections wherever possible. They are still areas that could not be interpreted well enough and they were left empty, beyond the section level.

### Previous Updates

The Cadastral Publication Data Standard ([CadNSDI](https://hub.arcgis.com/maps/BLM-EGIS::blm-natl-public-plss-cadnsdi/about)) is the cadastral data component of the [NSDI](https://www.fgdc.gov/nsdi/nsdi.html). This is the publication guideline for cadastral data that is intended to provide a common format and structure and content for cadastral information that can be made available across jurisdictional boundaries.