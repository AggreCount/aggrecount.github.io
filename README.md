## AggreCount: an unbiased automated image analysis tool for quantification of aggregates

AggreCount is an automated image analysis tool written in the ImageJ macro language based on the FIJI distribution of ImageJ (version 1.52p or later).
AggreCount requires dual channel images that have (at a minimum) immunohistochemical stains for aggregates and nuclei though it supports n-channel images.

[Download AggreCount v1.1](https://github.com/AggreCount/AggreCount/archive/master.zip)

### Advanced image processing
AggreCount utilizes the difference of gaussians methodology to isolate puncta from immunohistochemical images. DoG allows for the reliable quantification of puncta even
when images have uneven background illumination, out of focus fields, or varying fluorescence intensities. AC is ready for analysis out of the box for a large variety of 
aggregate stains (inclduing ubiquitin stains) though may be modified by users to analyze numerous other punctate structures such as peroxisomes and lysosomes. 

![Image](https://dl.boxcloud.com/api/2.0/internal_files/718955413509/versions/764481830709/representations/jpg_paged_2048x2048/content/1.jpg?access_token=1!FTnJvPl6D6budueWGljbWIxj942CQ7asdDOQhWAqHksluH_nSnq6X-pOZom214Uz1h-K7h3bA-fR9NnlMr8R0ajYDp8xPQDDoZZHfx-SJV33k-UCVH2DUbvxThnLGjfD0Zkaf8goBhQQY88pfLt5Dd56rbzDaoidvxeeVWBNfqLYhtnrvC3dZyNTN-3B9lK-v7Svzj9NlqsSfqjPHq9EpehzWFQ6aACsccKwFmMmewWHS8zfI3hmLaqVCl0yUxtl4Y4kbnTKaZv10k7AvgxE3QF_irrg5H1-XWlJCpIQno7VsEJUyoHmETbja5U11Z35CIKk1jUJ9l8fwimZKVdLz-Yy53z8NHBaC-L_HEkpFk5_6DtX0vfFEOAtjL1b0-c6jE5GvQZhuEb48kbB7xHF9V2QnVnZfcXEv3epB4NeSkRov2IlML6bleww_1_t1M6q8zEc7x3GHu0mt-wYOZtMk7blTbXNGqnshiAXbJb9fDyVXz0nggWeRisnkthX2hHuXLBgDV9rsYjJFk8NWViGRIGIyPTR6FuEFTqGp3uiDHw1h5_Es7A7PCSZ1ZByYq9jNrZEBuKRFZ9QMaR28QfcNhyXy7E9vYQWYGL1_fFaiB-o-mJ3Csmy0LHH-eBntoUiIcG8jLOkDN7Dy3ipURRf-xkCVHpf-DvzcYMCyYi7sy6DGVs.&box_client_name=box-content-preview&box_client_version=2.49.1)

### Accelerated aggregate quantification
Using an automated image analysis tool can decrease the amount of time needed for image quantification allowing for scientists to get back to the bench.

### Easy cell segmentation
AggreCount uses the native watershed-based segmentation algorithm native to FIJI allowing for segmentation of cells without the need of machine learning algorithms
and training sets. 


### MarkUP

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AggreCount/aggrecount.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
