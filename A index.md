---
title: Home
layout: default
filename: A index
--- 

![aggrecount logo](https://github.com/AggreCount/aggrecount.github.io/blob/master/AC_logo1.png?raw=true)

## An unbiased automated image analysis tool for quantification and localization of cellular aggregates

AggreCount is an automated image analysis tool written in the ImageJ macro language based on the FIJI distribution of ImageJ (version 1.52p or later).
AggreCount requires dual channel images that have at least immunohistochemical stains for aggregates and nuclei though it supports n-channel images.

<a href="https://github.com/AggreCount/AggreCount/archive/master.zip"><img src="https://github.com/AggreCount/aggrecount.github.io/blob/master/Picture1.png?raw=true" width="300"></a>

[Download FIJI](https://imagej.net/Fiji/Downloads)

### Advanced image processing
AggreCount utilizes the difference of gaussians (DoG) methodology to isolate puncta from immunohistochemical images. DoG allows for the reliable quantification of puncta even
when images have uneven background illumination, out of focus fields, or varying fluorescence intensities. AC is ready for analysis out of the box for a large variety of 
aggregate stains (inclduing ubiquitin stains) though may be modified by users to analyze numerous other punctate structures such as peroxisomes and lysosomes. 

![Image](https://github.com/AggreCount/aggrecount.github.io/blob/master/processing%20imageac.png?raw=true)

### Accelerated aggregate quantification
AggreCount is ready for batch image analysis allowing for rapid quantification of 100s of images. AC can accept any file type supported by the BioFormats image importer including proprietary image file types such as .nd2. Find all supported formats in the [BioFormats documentation](https://docs.openmicroscopy.org/bio-formats/6.5.1/supported-formats.html)
![Image](https://github.com/AggreCount/aggrecount.github.io/blob/master/aggrecell.png?raw=true)

### Easy cell segmentation
AggreCount uses the watershed-based segmentation algorithm native to FIJI allowing for segmentation of cells without the need of machine learning algorithms
and training sets. This segmentation methods allows for separation of cells even when closely packed. Users may change the 'prominence' variable that determines local maxima which defines cells using the main settings window.

![Image](https://github.com/AggreCount/aggrecount.github.io/blob/master/segmentation.png?raw=true)


### AggreCount on BioRx
The AggreCount journal article is now in preprint on BioRx. 

[AggreCount BioRx](https://www.biorxiv.org/content/10.1101/2020.07.25.221267v1)

### Developed in the Raman Lab at Tufts University
AggreCount was developed by Jacob Klickstein in the Raman Lab in 2020. Find more information on the lab, our research, and our members by visiting the lab website here

[Raman Lab](https://www.raman-lab.org/)

