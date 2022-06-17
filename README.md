# Sabbioneta-sidewalks

This repository contains data relating to the doctoral thesis of Daniele Treccani, PhD candidate in cycle XXXIV at the Politecnico di Milano, Department of Architecture, Built Environment and Construction Engineering. The thesis work was carried out in collaboration with the HESUTECH group of the MantovaLAB laboratory of the Politecnico di Milano, at Mantova Campus.

The data is owned by the HESUTECH Group and licensed under ODbL.

The "data" folder contains the vector file ".shp" containing the sidewalk network of the city of Sabbioneta, obtained through calculations performed during the PhD thesis.

The thesis, entitled "POINT CLOUD PROCESSING FOR PHYSICAL ACCESSIBILITY EVALUATION IN HISTORICAL URBAN ENVIRONMENTS. THE CASE OF THE UNESCO SITE OF SABBIONETA", dealt with the development of a semi-automatic procedure for the analysis of a point cloud of a historical urban environment, in order to generate a shapefile containing the network of sidewalks with the relative spatial and geometric attributes, such as width, elevation with respect to the street, longitudinal and transversal slopes, and pavement material.

The computation of the sidewalks parameters was done following a semi-automatic approach, for some attributes a limit value was set. To computed attributes exceeding the threshold, a NULL value was set. The shapefile attributes are described in the following table:

| Attribute | Type | Description | Notes |
|-----|---|---|---|
|ID|double|consecutive numbering|some numbers are missing|
|material|Qstring|material used for the paved surface of sidewalk|manually inserted, after on-site check|
|width|double|width of the sidewalk|from computation|
|TransvSlop|double|slope of the sidewalk in transverse direction respect road local direction|from computation|
|LongSlope|double|slope of the sidewalk in longitudinal direction respect road local direction|from computation|
|Zdiff|double|difference in elevation between road and sidewalk, if present|from computation|
|manual_add|int|if "1" means that the line was manually inserted| if manually inserted, the attributes are empty|
computed|if "1" means that the line was automatically inserted|if automatically inserted, the attributes were computed and stored within the line|



More information can be found in the following scientific articles:

http://ocs.editorial.upv.es/index.php/arqueologica20/arqueologica9/paper/viewFile/12088/6052

https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLIII-B4-2021/243/2021/

https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/VIII-M-1-2021/101/2021/

https://www.int-arch-photogramm-remote-sens-spatial-inf-sci.net/XLVI-2-W1-2022/497/2022/


