# Noise-free-C2-graph
Removal of Thermal Noise form Single Look Complex (SLC) dual-polarization Interferometric Wide Swath (IW) Sentinel-1 (S1) SAR data using the Sentinel Application Platform (SNAP) software, provided by the European Space Agency (ESA)

The processing graph allows implementing the approach proposed in the scientific work:

[Ref] L. Mascolo, Juan Manuel Lopez-Sanchez, Shane R. Cloude, "Thermal Noise Removal from Polarimetric Sentinel-1 Data", IEEE Geoscience and Remote Sensing Letters, in print.

---------------------------------------------------------------------

File     : NoiseFree_C2_single_look.xml

Input: SLC dual-polarization IW S1 data 

Output: Noise-free C2 matrix, C11, C12_imag, C12_real, C22 .img files (and associated .hdr files)

Authors  : L. Mascolo, Juan Manuel Lopez-Sanchez, Shane R. Cloude

Creation : 09/2020

---------------------------------------------------------------------

NOTES:

     1) The processing graph available in this repository has been tested in SNAP 8, using a SLC dual-polarization VH-VV IW S1A image, collected on a sea area
     The ID of the image is: S1A_IW_SLC__1SDV_20180603T182052_20180603T182119_022196_0266A4_F6CB.SAFE
     
     2) Only a Region of Intesrest (ROI) has been processed, by selecting sub-swath IW1 and bursts 3-5, and using the Subset operator
     
     3) In the Multilook operator, the number of range looks is set to 4, the number of azimuth looks is set to 1
    
 BEFORE RUNNING THE PROCESSING GRAPH IN SNAP
 
 - MANDATORY CHANGES
 
 According to the image (or the set of images) to be processed, the user must change:
 
      1) The sub-swath and the bursts in the TOPSAR-Split operator, by selecting the sub-swath and the the bursts of interest
     
      2) The geographical coordinates of the ROI's polygon in the Subset operator, by updating the new coordinates relevant to ROI of interest
  
  - OPTIONAL CHANGES
  
  According to the user needs, the following changes can be applied:
  
      1) The Subset operator can be removed from the graph
     
      2) The number of range and azimuth looks in the Multilook oprator can be changed

  
  
 
     
 
     
     
