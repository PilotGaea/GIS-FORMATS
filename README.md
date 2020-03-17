# 高程格式
1. **HDR**+GRD : 中華民國內政部研發的高程，用美國國家標準資訊 (ASCII)碼記
錄，製成數值地形模型檔(.grd)，最後賦予檔頭資料(*.hdr)。
  + 資料集
    + [新版臺灣本島20公尺網格DTM資料](https://data.moi.gov.tw/MoiOD/Data/DataDetail.aspx?oid=8600CF99-A6EF-4335-947D-D26C9992EDD1)
  + 支援軟體
    + PilotGaea TransferData 開啟 *.GRD
  + Remarks
     + 台灣說的**HDR**大致上都是此格式
     + 舊版HDR28行，新版HDR26行，格式如附檔
1. **FLT**+HDR : Floating Point Raster File (.flt) include a binary floating-point file (.flt) and an ASCII header file (.hdr).
  + 資料集
    + [Ontario Ministry of Natural Resources DEM version 3](https://library.carleton.ca/find/gis/geospatial-data/provincial-digital-elevation-model-version-3)
    + [USGS National Elevation Dataset](https://lta.cr.usgs.gov/NED)
  + 支援軟體
    + Global Mapper
    + ArcGIS
    + QGIS : 
+ **GRD** : Grid (.grd) files contain integers that give the height of each cell in the grid, generally arranged from west to east and north to south. Like shapefiles, grid files generally include several file components such as .grd, .gri, and .vrt files.
  + 資料集
    + [DIVA-GIS](http://www.diva-gis.org/)
  + 支援軟體
    + Global Mapper
    + ArcGIS
    + QGIS

# 參考資料

1. [99 年度莫拉克颱風災區基本地形圖修測工作-工作總報告書](https://www.nlsc.gov.tw/uploadfile/5942500.pdf])
1. [Digital Elevation Model (DEM) Formats](https://library.carleton.ca/help/dem-formats)
