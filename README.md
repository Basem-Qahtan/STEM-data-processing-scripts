**A github respreotory with scripts developed for STEM-data processing as follows:**

1-Nanocrystals segmentation and population analysis.

A code designed to segment large ensembles of heterogeneous nanocrystals and obtain a chemical composition on individual nanocrystals. this code utilizes the segment every grain algorithm (SEG) to segment individual nanocrystals in the HAADF image, the SEG algorithm can be found here: [segment every grain algorithm](https://github.com/zsylvester/segmenteverygrain), Watershed segmentation was added for segmentartion of agglomerated nanocrystals.

##2- EDX-Tomography dataset denoising

A script written specifically for the deconvolution of Cu x-ray signal that might overlap with other elements in the sample, in EDX Tomography , the EDX spectrum will suffer from intense Cu x-ray signal especcially at high tiliting angles such as +/-60 degrees. the Principal component analysis (PCA) has proven effective in removing the Cu signal from all the tilt angle datasets. 

##3- Cathodoluminescence (CL) datasets denoising.

Cathodoluminescence data aquisition might suffer from low signal to noise ratio (SNR) as the electron dose needs to be low to avoid sample movement under the electron beam, this sample movement affect the image contrast. PCA has proven to be effective in enhancing the SNR.
