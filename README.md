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

     1)
