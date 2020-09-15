## AggreCount: an unbiased automated image analysis tool for quantification of aggregates

AggreCount is an automated image analysis tool written in the ImageJ macro language based on the FIJI distribution of ImageJ (version 1.52p or later).
AggreCount requires dual channel images that have (at a minimum) immunohistochemical stains for aggregates and nuclei though it supports n-channel images.

[<img src="https://github.com/AggreCount/aggrecount.github.io/blob/master/Picture1.png" width="300">](https://github.com/AggreCount/AggreCount/archive/master.zip)

### Advanced image processing
AggreCount utilizes the difference of gaussians methodology to isolate puncta from immunohistochemical images. DoG allows for the reliable quantification of puncta even
when images have uneven background illumination, out of focus fields, or varying fluorescence intensities. AC is ready for analysis out of the box for a large variety of 
aggregate stains (inclduing ubiquitin stains) though may be modified by users to analyze numerous other punctate structures such as peroxisomes and lysosomes. 

![Image](https://github.com/AggreCount/aggrecount.github.io/blob/master/image_analysis.jpg?raw=true)

### Accelerated aggregate quantification
Using an automated image analysis tool can decrease the amount of time needed for image quantification allowing for scientists to get back to the bench.

### Easy cell segmentation
AggreCount uses the native watershed-based segmentation algorithm native to FIJI allowing for segmentation of cells without the need of machine learning algorithms
and training sets. 

![Image](https://github.com/AggreCount/aggrecount.github.io/blob/master/segmentation.png?raw=true)


### AggreCount on BioRx
The AggreCount journal article is now in preprint on BioRx. 

[AggreCount BioRx](https://www.biorxiv.org/content/10.1101/2020.07.25.221267v1)

### Developed in the Raman Lab at Tufts University
AggreCount was developed by Jacob Klickstein in the Raman Lab in 2020. Find more information on the lab, our research, and our members by visiting the lab website here

[Raman Lab](https://www.raman-lab.org/)

