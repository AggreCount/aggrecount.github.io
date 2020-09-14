## AggreCount: an unbiased automated image analysis tool for quantification of aggregates

AggreCount is an automated image analysis tool written in the ImageJ macro language based on the FIJI distribution of ImageJ (version 1.52p or later).
AggreCount requires dual channel images that have (at a minimum) immunohistochemical stains for aggregates and nuclei though it supports n-channel images.

[Download AggreCount v1.1](https://github.com/AggreCount/AggreCount/archive/master.zip)

### Advanced image processing
AggreCount utilizes the difference of gaussians methodology to isolate puncta from immunohistochemical images. DoG allows for the reliable quantification of puncta even
when images have uneven background illumination, out of focus fields, or varying fluorescence intensities. AC is ready for analysis out of the box for a large variety of 
aggregate stains (inclduing ubiquitin stains) though may be modified by users to analyze numerous other punctate structures such as peroxisomes and lysosomes. 

![Image](https://dl.boxcloud.com/api/2.0/internal_files/718951951675/versions/764477999275/representations/jpg_paged_2048x2048/content/1.jpg?access_token=1!pQOfvYfSl9_jEdFRL1g3rP0rmPvp4FwBuRXtJm17tj-pHWdEM3NWIjKAJ2tW7dj24Me0wyOtpdcMO7DapF114tkA28e3nNPb3O3Tm1Wk5S8b2r3NEIztdbMtFHjvdxzchUuYkwQuOb8tw7Sbv3Cd7YDDO_jN-n4v_d9tC6KeBaNIk5PUiUBjcq3-bgnJh_Avvh2-z6rJDzczJI8JjvQP5gkwt9URpJ7KzuhYiQx6K3jIde39HtC8KkBthh3oDszg6PPJGz5VaWjvW3T3xcMODYcpqnp4P1LPc71O8uRBf20ah2rdNpcx7lbsqkwNcdSew3uhz7OV_diL1KyNF89mN8kFUkXFKCiRZk7yFx6O4ocvpSc5q18Tg4TM1HYs2Snd9C3LHgSRjenqoloTNMG1YPqMEt0gfJZb8-Wn83mK5DPwrED894YfGJMnlmDHLzi79wPLSMkdt6nJauGv8miOPqRJM2bo00LachRyZsBKMUVC4AqBsnCLzqLfBU_gUsoZqQV0x9jQY2b5aZmBCxicPv1KNLJPblT1ZiFFaHkrn1Vu3G1CaUU_rV2zZI_YKHlfIWOA7SKGHJM-EZR2NHM5otYG9ca-VCoCcK_tMibKz32pFSZu6wyjtM5yksHjD4NqSYZb7ORf5K7e6tAOiLvb05ayKC2ixFN1T4IW27q026vf1mI.&box_client_name=box-content-preview&box_client_version=2.49.1)

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
