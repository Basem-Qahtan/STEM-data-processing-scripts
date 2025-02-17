**A github repository with scripts developed for advanced STEM-data processing:**

This repository contains a collection of scripts developed for the processing and analysis of Scanning Transmission Electron Microscopy (STEM) data. The scripts address various aspects of STEM data analysis, including nanocrystal segmentation, population analysis, and dataset denoising. The following sections provide an overview of the key components:

**1-Nanocrystals segmentation and population analysis.**

A code designed to segment large ensembles of heterogeneous nanocrystals and obtain a chemical composition on individual nanocrystals. this script utilises the segment every grain algorithm (SEG) to segment individual nanocrystals in the HAADF image, the SEG algorithm can be found here: [segment every grain algorithm](https://github.com/zsylvester/segmenteverygrain), Watershed was added for segmentation of agglomerated nanocrystals.

Before running this script, an additional file named "sam_vit_h_4b8939.pth" must be downloaded (link is available in the script).


**2- EDX-Tomography dataset denoising.**

A script written specifically for the deconvolution of Cu x-ray signal that might overlap with other elements in the sample, in EDX Tomography , the EDX spectrum will suffer from intense Cu x-ray signal especially at high tilting angles such as ±60<sup>o</sup>. Principal component analysis (PCA) has proven effective in removing the Cu signal from all the tilt angle datasets. 

**3- Cathodoluminescence (CL) datasets denoising.**

Cathodoluminescence data acquisition may suffer from low signal to noise ratio (SNR) as the electron dose needs to be low to avoid sample movement under the electron beam, this sample movement affect the image contrast. PCA has proven to be effective in enhancing the SNR.
