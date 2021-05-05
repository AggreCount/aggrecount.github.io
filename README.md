![aggrecount logo](https://github.com/AggreCount/aggrecount.github.io/blob/master/AC_logo1.png?raw=true)

## An unbiased automated image analysis tool for quantification and localization of cellular aggregates

AggreCount is an automated image analysis tool written in the ImageJ macro language based on the FIJI distribution of ImageJ (version 1.52p or later).
AggreCount requires dual channel images that have at least immunohistochemical stains for aggregates and nuclei though it supports n-channel images.

<a href="https://github.com/AggreCount/AggreCount/raw/036048df7b131d118d80022108b8a7ebada3b809/AggreCount_download/AggreCount%20v1_13.ijm"><img src="https://github.com/AggreCount/aggrecount.github.io/blob/master/Picture1.png?raw=true" width="300"></a>

(right click -> "Save link as...")

[Quick start guide](https://github.com/AggreCount/AggreCount/raw/036048df7b131d118d80022108b8a7ebada3b809/AggreCount_download/documentation/Quick%20start%20guide.txt)

[Full instructions](https://github.com/AggreCount/AggreCount/raw/036048df7b131d118d80022108b8a7ebada3b809/AggreCount_download/documentation/AggreCount%20Instructions.txt)

[Download FIJI](https://imagej.net/Fiji/Downloads)

## 1.13 patch notes
- Added new thresholding method combining segmentation and thresholding
    Select this method from the main menu drop down menu "Thresholding_new"
- Fixed cell thresholding, allowing user to select the option without "Boolean error"


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
The AggreCount journal article is now published in the Journal of Biological Chemistry. 

[AggreCount paper](https://doi.org/10.1074/jbc.RA120.015398)

### Developed in the Raman Lab at Tufts University
AggreCount was developed by Jacob Klickstein in the Raman Lab in 2020. 

This work was supported by NIH grant R01GM127557 to Malavika Raman Ph.D.

Find more information on the lab, our research, and our members by visiting the lab website here
[Raman Lab](https://www.raman-lab.org/)

## Previous patch notes
### 1.11
- Fixed indexing error when an aggregate ROI happens to lie between two cell ROIs
- Added "Largest perinuclear aggregate size" to dataset_cells for post-hoc aggresome analysis
- Changed DoG blur to scale with image scale
- Changed final gaussian blur of aggregates to scale with image scale
- Added a gamma process step to enhance bright puncta

### 1.12 
- Added support for multi-channel stacks using duplicate function
- Added additional instructions in setup prompts for clarity
- Added "dataset_description" save file with explanations for each data field
- Fixed error when there is a folder name < 4 characters in the analysis folder
- Added "help" button to main dialog window that directs to BioRx preprint of the AggreCount article
- Switched "Make binary" function in cell body thresholding to the "minimal" auto threshold function
- Added gamma processing step to cell body thresholding to enhance cell body detection
