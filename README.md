**A github respiratory with scripts developed for STEM-data processing as follows:**

**1-Nanocrystals segmentation and population analysis.**

A code designed to segment large ensembles of heterogeneous nanocrystals and obtain a chemical composition on individual nanocrystals. this code utilizes the segment every grain algorithm (SEG) to segment individual nanocrystals in the HAADF image, the SEG algorithm can be found here: [segment every grain algorithm](https://github.com/zsylvester/segmenteverygrain), Watershed segmentation was added for segmentartion of agglomerated nanocrystals.

Before running this script, an additional file named "sam_vit_h_4b8939.pth" must be downloaded (link is avilable in the script).


**2- EDX-Tomography dataset denoising.**

A script written specifically for the deconvolution of Cu x-ray signal that might overlap with other elements in the sample, in EDX Tomography , the EDX spectrum will suffer from intense Cu x-ray signal especcially at high tiliting angles such as +/-60<sup>o</sup>. Principal component analysis (PCA) has proven effective in removing the Cu signal from all the tilt angle datasets. 

**3- Cathodoluminescence (CL) datasets denoising.**

Cathodoluminescence data aquisition might suffer from low signal to noise ratio (SNR) as the electron dose needs to be low to avoid sample movement under the electron beam, this sample movement affect the image contrast. PCA has proven to be effective in enhancing the SNR.

**A GitHub Repository for Advanced STEM Data Processing**
This repository contains a collection of scripts developed for the processing and analysis of Scanning Transmission Electron Microscopy (STEM) data. The scripts address various aspects of STEM data analysis, including nanocrystal segmentation, population analysis, and dataset denoising. The following sections provide an overview of the key components:
**1-Nanocrystal Segmentation and Population Analysis.**

This script is designed to segment large ensembles of heterogeneous nanocrystals and determine the chemical composition of individual nanocrystals. The code utilises the Segment Every Grain (SEG) algorithm for segmenting individual nanocrystals in the High-Angle Annular Dark-Field (HAADF) image. The SEG algorithm can be accessed at: [segment every grain algorithm](https://github.com/zsylvester/segmenteverygrain). Additionally, watershed segmentation has been implemented to address the segmentation of agglomerated nanocrystals.
Prior to executing this script, users must download an auxiliary file named "sam_vit_h_4b8939.pth" (the download link is provided within the script).

**2-EDX-Tomography Dataset Denoising.**
This script has been specifically developed for the deconvolution of copper X-ray signals that may overlap with other elemental signals in the sample during Energy-Dispersive X-ray (EDX) Tomography. EDX spectra often suffer from intense copper X-ray signals, particularly at high tilting angles (e.g., ±60°). Principal Component Analysis (PCA) has demonstrated efficacy in removing the copper signal from datasets across all tilt angles.

**3-Cathodoluminescence (CL) Dataset Denoising.**

Cathodoluminescence data acquisition frequently encounters low signal-to-noise ratios (SNR) due to the necessity of using low electron doses to prevent sample movement under the electron beam, which can affect image contrast. PCA has proven effective in enhancing the SNR of CL datasets.
