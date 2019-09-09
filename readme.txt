Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°
Brief description for files in this directory
Witten by Dr. Hisashi SATO* on 9 September 2019

This folder contains data files those are emplyed by the anaysis in the Sato and Ise (submitted). Some related materials of the analysis are also available in this folder.

* Institute of Arctic Climate and Environment Research (IACE),
Japan Agency for Marine-Earth Science and Technology (JAMSTEC),
Yokohama, Japan
hsatoscb@gmail.com
Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°Å°

_____________________________________________

1. Folder "1.VCDs"
It contains Visualized Climate Environments (VCEs) for training and testing the Deep-Neural-Network model. Names of subfolders corresponds climate data set. Each subfolder contains 2 or 4 tar.zip files. Decomposing each tar.zip file results in 15 subfoloders "01" to "15", those correspond vegetation code of the ISLSCP2. Individual VCE shows climatic condition of each half degree grid cell. According to the ISLSCP2 data, VCEs are classified by their their potential vegetation type of the grid.

Following are the vegetation code. I should note that these numbers were different from figures in the paper.
   01: Tropical Evergreen Forest/Woodland
   02: Tropical Deciduous Forest/Woodland
   03: Temperate Broadleaf Evergreen Forest/ Woodland
   04: Temperate Needleleaf Evergreen Forest/Woodland
   05: Temperate Deciduous Forest/Woodland
   06: Boreal Evergreen Forest/Woodland
   07: Boreal Deciduous Forest/Woodland
   08: Evergreen/Deciduous Mixed Forest
   09: Savanna
   10: Grassland/Steppe
   11: Dense Shrubland
   12: Open Shrubland
   13: Tundra
   14: Desert
   15: Polar Desert/Rock/Ice

Naming rule for VCEs of 10 years average climate is following:
Latitude number + "_" + Longitude number + ".png"

Naming rule for VCEs of each year climate is following:
Latitude number + "_" + Longitude number + "_" + Year of climate + ".png"

Here, latitude number ranges 001 to 360, starting from north-latitude-90 to southward at half degree interval. The longitude number ranges 001 to 720, starting from west-longitude-180 to eastward at half degree interval. 

The "CRU" subfolder contains following files
   CRU_EachYear_AnnualMean.tar.gz
   VCEs of annual mean climate (for each year from 1971 to 1980)
   
   CRU_EachYear_MonthlyMean.tar.gz
   VCEs of monthly mean climate (for each year from 1971 to 1980)
   
   CRU_AnnualMean.tar.gz
   VCEs of annual mean climate (averaged over years of 1971 to 1980)
   
   CRU_MonthlyMean.tar.gz
   VCEs of monthly mean climate (averaged over years of 1971 to 1980)

The "NcepNcar" subfolder contains following files
   NCEP_AnnualMean.tar.gz
   VCEs of annual mean climate (averaged over years of 1971 to 1980)
   
   NCEP_MonthlyMean.tar.gz
   VCEs of monthly mean climate (averaged over years of 1971 to 1980)

The "HadGEM2" subfolder contains following files
   HadGEM2_Hist_AnnualMean.tar.gz
   VCEs of annual mean climate (averaged over years of 1971 to 1980)
   
   HadGEM2_Hist_MonthlyMean.tar.gz
   VCEs of monthly mean climate (averaged over years of 1971 to 1980)
   
   HadGEM2_RCP26_MonthlyMean.tar.gz
   VCEs of monthly mean climate which is forecasted under RCP 2.6 (averaged over years of 2091 to 2100)
   
   HadGEM2_RCP85_MonthlyMean.tar.gz
   VCEs of monthly mean climate which is forecasted under RCP 8.5  (averaged over years of 2091 to 2100)

The "Miroc" subfolder contains following files
   Miroc_Hist_AnnualMean.tar.gz
   VCEs of annual mean climate (averaged over years of 1971 to 1980)
   
   Miroc_Hist_MonthlyMean.tar.gz
   VCEs of monthly mean climate (averaged over years of 1971 to 1980)
   
   Miroc_RCP26_MonthlyMean.tar.gz
   VCEs of monthly mean climate which is forecasted under RCP 2.6 (averaged over years of 2091 to 2100)
   
   Miroc_RCP85_MonthlyMean.tar.gz
   VCEs of monthly mean climate which is forecasted under RCP 8.5  (averaged over years of 2091 to 2100)

On the top of this subfolder, there is PicList.zip, which is a compressed file of PicList.txt. This text file is required for classify VCEs with the trained model.

_____________________________________________

2. Folder "2.Result"
It contains copies of image classifications results of the Digits screen. Structures of subfolder and files names correspond to those of the "VCEs" folder.

_____________________________________________

3. Folder "3.LearningCurves"
It contains screen capture of Digits output, showing learning curve of CRU climate data. This folder contains 2 files: one is trained with annual mean VCEs, and another is trained with monthly mean VCEs.
_____________________________________________

4. Folder "4.ConfusionMatrices"
Due to the limitation of space, the extended data only contains training accuracies. So, confusion matrces for each climate data is here.

_____________________________________________

5. Folder "5.FigureMaterials" 
It contains data and codes (in R) for drawing the figures in the manuscript"

