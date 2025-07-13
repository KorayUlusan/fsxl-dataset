# Flickr-Suits-XL Dataset (FSXL)

![License CC](https://img.shields.io/badge/license-CC--BY--NC--SA%204.0-green.svg?style=plastic)
![Format JPG](https://img.shields.io/badge/format-JPG-green.svg?style=plastic)
![Images 1208](https://img.shields.io/badge/images-1208-green.svg?style=plastic)

![Teaser image](./fsxl-teaser.png)

The **Flickr-Suits-XL (FSXL)** dataset contains **1208 high-quality images** of people wearing suits, collected from Flickr under permissive licenses. 

The dataset was curated by crawling Flickr for over **5687 images** and filtering down using face detection (via **MTCNN**), alignment, and cropping steps to center the face horizontally and place it at approximately **1/3 from the top vertically**. This ensures consistency with resolutions used in [SDXL](https://arxiv.org/abs/2307.01952) models.

> 📌 **Note**: There is a noticeable **gender imbalance** in FSXL, with **male subjects being the majority**.

---

## Metadata

More information for each image is available in the file: [fsxl-metadata.json](fsxl-metadata.json)

Example entry:
```json
[
    {
        "image_name": "20716603320.jpg",
        "photo_url": "https://www.flickr.com/photos/35591378@N03/20716603320",
        "photo_title": "P040915PS-0974",
        "author": "Obama White House Archived",
        "country": "",
        "license": "United States Government Work",
        "license_url": "http://www.usa.gov/copyright.shtml",
        "date_uploaded": "2015-08-26",
        "date_crawled": "2024-07-19"
    }
]
```



## Image Resolutions


The image resolutions align with the SDXL training specifications (~1MP):


![Image Resolutions](./fsxl-image-resolutions.png)


## BibTeX

```bib
@inproceedings{Ulusan2025SynData4CV,  
  author        = {Ulusan, Koray and Kiefer, Benjamin},
  title         = {{Generating Synthetic Data via Augmentations for Improved Facial Resemblance in DreamBooth and InstantID}},
  booktitle     = {Proceedings of the CVPR 2025 Workshop on Synthetic Data for Computer Vision (SynData4CV)},
  year          = {2025},
  month         = {May},
  url           = {https://openreview.net/forum?id=2o0RxrcV23},
  note          = {Accepted to the CVPR 2025 SynData4CV Workshop},
  eprint        = {2505.03557},
  archiveprefix = {arXiv},
  primaryclass  = {cs.CV},
  doi           = {10.48550/arXiv.2505.03557}
}
```

## Licenses

The individual images were published in Flickr by their respective authors under either [Creative Commons BY 2.0](https://creativecommons.org/licenses/by/2.0/), [Creative Commons BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/), [Public Domain Mark 1.0](https://creativecommons.org/publicdomain/mark/1.0/), [Public Domain CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/), or [U.S. Government Works](http://www.usa.gov/copyright.shtml) license. All of these licenses allow **free use, redistribution, and adaptation for non-commercial purposes**. However, some of them require giving **appropriate credit** to the original author, as well as **indicating any changes** that were made to the images. The license and original author of each image are indicated in the metadata.

* [https://creativecommons.org/licenses/by/2.0/](https://creativecommons.org/licenses/by/2.0/)
* [https://creativecommons.org/licenses/by-nc/2.0/](https://creativecommons.org/licenses/by-nc/2.0/)
* [https://creativecommons.org/publicdomain/mark/1.0/](https://creativecommons.org/publicdomain/mark/1.0/)
* [https://creativecommons.org/publicdomain/zero/1.0/](https://creativecommons.org/publicdomain/zero/1.0/)
* [http://www.usa.gov/copyright.shtml](http://www.usa.gov/copyright.shtml)

The dataset itself is made available under [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). You can **use, redistribute, and adapt it for non-commercial purposes**, as long as you (a) **indicate any changes** that you've made, and (b) distribute any derivative works **under the same license**.

* [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This decision was made because [Creative Commons CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/) restricts the commercial use.
