# Content Creator Guide: Virtual Labs PWA

## Introduction
This document is intended for the virtual lab developers who are creating experiments for the virtual labs and want to display their experiments on the PWA. This document details the process for including your interactive experiments within Virtual Labs Progressive Web App (PWA). By integrating your experiments, you'll be making them accessible to a wider audience and fostering a more engaging learning experience. These experiments are presented in the form of cards, offering basic information and a clickable link to access the main experiment page. 

## Audience
This guide is intended for educators and developers who have developed interactive experiments and wish to make them available through our Virtual Labs PWA platform.

## Motivation

The PWA platform offers several advantages for showcasing the Virtual Labs experiments. It provides:
**Enhanced user experience:** The PWA offers a smooth and responsive interface optimized for mobile devices.
**Wider reach:** By integrating your experiments into the PWA, you'll expose them to a broader user base.

## Prerequisites 

To add an experiment, the following conditions must be met:

* The experiment must be hosted on the Virtual Labs central website.
* It should be fully responsive and functioning correctly.


## How to add your experiment to the PWA?

To include your experiment in the PWA, please fill the following details in the "Your Institute" tab of the Google Sheet. 

Google Sheet Link: [PWA-Onboarding-Sheet](https://docs.google.com/spreadsheets/d/1ohrWAzEYdiDQTBM52AUhup2nZB3JRVsm2dG2n9-FHh0/edit?usp=sharing)

<b>S No | <b> Fill the Serial Number of the entry
:--|:--|
<b> Experiment URL | <b> Fill your hosted experiment url
<b> Image of the experiment| <b> Fill the public link to the image in the experiment repository
<b> Description| <b> Fill the description of the experiment in 10- 20 words
<b> Tags| <b> Fill the tags of the experiment as a omma-separated list

**A. Experiment URL**

Please provide the web address (URL) of the experiment you want to include in the PWA.  This needs to the 

**B. Image of the experiment**

To select an appropriate image that aligns with the experiment's description or aim, please adhere to the following guidelines:

1. Ensure that the chosen image does not violate any copyright laws. It should either be freely available for download, have a public domain license, or be licensed under Creative Commons for non-commercial use (CC-BY-NC).
You can explore the following online sources as examples:
 - [Category:Images - Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Images)
 - [Pngtree](https://pngtree.com/)
 - [Pixabay](https://pixabay.com/)
 - [Unsplash](https://unsplash.com/)
If you have access, you can also utilize DALL-E for generating the required images.

2. Adhere the the following specifications for the image

 - Resolution : greater than or equal to 640 X 480 
 - Dimensions : Approximately 4 X 3 image 
 - File size: should not exceed 50 KB
 - Image should be coloured.
 - Example image: [Data Clustering](https://github.com/virtual-labs/exp-mst-based-iiith/blob/main/experiment-image.jpg)
3. Double check the license agreement terms for any image you upload.
4. Name the image as experiment-image.png/jpg.
5. Commit the image to the main branch of the experiment's GitHub repository and share the public link to the image in the designated spreadsheet column. [Example Link](https://github.com/virtual-labs/exp-mst-based-iiith/tree/main).

 **C. Description**

To provide a concise description for each experiment, kindly write a brief summary in the designated sheet itself under the column titled "Description." The description should ideally be between **10 to 20 words** in length. You may refer to online sources such as ChatGPT for assistance in crafting the descriptions.

**D. Tags**

Refer the experiment name, aim, theory and online sources and list relevant tags. Enter the tags as a comma separated list in the Tags column in the sheet. list out at least 5 tags for each  experiment. The tags must be comma separated. Each tag can  have space separated words, or have hyphens “-”. Use of any  other characters are not permitted. The tags should be strictly relevant  to the experiment. Do not include the experiment name, lab name, institute name and discipline name as tags.

## Conclusion
By following the steps outlined in this guide and filling out the experiment information sheet, you'll be well on your way to sharing your valuable experiments with a wider audience and enriching the learning experience within the Virtual Labs PWA. If you have any questions, please don't hesitate to contact us @ ravi.kiran@vlabs.ac.in. 
