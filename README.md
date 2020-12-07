# Noise-free-C2-graph
Removal of Thermal Noise from Polarimetric Sentinel-1 SAR Data

The processing graph is related to the approach proposed in the scientific work:

[Ref] L. Mascolo, Juan Manuel Lopez-Sanchez, Shane R. Cloude, "Thermal Noise Removal from Polarimetric Sentinel-1 Data", IEEE Trans. Geosci. Remote Sens. Letters, in review

---------------------------------------------------------------------

File     : NoiseFree_C2_single_look.xml

Authors  : L. Mascolo, Juan Manuel Lopez-Sanchez, Shane R. Cloude

Creation : 09/2020

---------------------------------------------------------------------

Description : remove thermal noise from Single Look Complex (SLC) dual-polarization Interferometric Wide Swath (IW) Sentinel-1 (S1) SAR data

The .xml file has to be loaded in the Sentinel Application Platform (SNAP) software by the European Space Agency (ESA), in order to process S1 data

Input: SLC dual-polarization IW S1 data 

Output: Noise-free C2 matrix, C11, C12_imag, C12_real, C22 .img files (and associated .hdr files)

---------------------------------------------------------------------

NOTES:

     1) The .xml file available in this repository has been tested with SNAP 8, using a SLC dual-polarization VH-VV IW S1A image, collected on a sea area
     The S1 imae ID is: S1A_IW_SLC__1SDV_20180603T182052_20180603T182119_022196_0266A4_F6CB.SAFE
     
     2) Only a Region of Intesrest (ROI) has been processed, by selecting bursts 3-5, and using the Subset operator.
     
     3) In the Multilook operator, the number of range looks is set to 4, the number of azimuth looks is set to 1
     
 
 TO RUN THE PRESENT GRAPH IN SNAP:
 
     1)
 
     
     
