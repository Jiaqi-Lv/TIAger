# TIAger Algorithm

This repository contains the code for the TIAger team's algorithm that was submitted as an entry to the [TIGER](https://tiger.grand-challenge.org/) challenge.
The associated paper for this code can be found [here](https://arxiv.org/abs/2206.11943)

Currently this repository takes H&E-stained whole slide images (WSIs) from breast cancer as input and outputs a predicted TILs score for the slide.
This is done by first segmenting the tumour-stroma areas. Following this, the pipeline will generate a bulk tumor segmentation and detect TILs within the stroma of the tumour bulk. Finally, it will determine the proportion of this area that is TILs in order to geenrate a TILs score between 0 and 100.
<!-- ![alt text](./pipeline.png) -->

# Authors

This code is made by Adam Shephard and Mostafa Jahanifar, as part of the TIA Centre, University of Warwick, Coventry, UK. It is based on the code developed by the TIGER challenge organisers.