# Multi-Screen Dataset

## Welcome to the BC-KU Multi-Screen Dataset

Welcome to Brightcove-Kingston University Multi-Screen Dataset. The dataset provides subjective ratings obtained for various HEVC encoded video sequences of multiple resolution-bitrate pairs viewed on three different devices: Mobile, Tablet and TV.

## Abstract
In modern-era video streaming systems, videos are streamed and displayed on a wide range of devices. Such devices vary from large-screen UHD and HDTVs to medium-screen Desktop PCs and Laptops to smaller-screen devices such as mobile phones and tablets. It is well known that a video is perceived differently when displayed on different devices. The viewing experience for a particular video on smaller screen devices such as smartphones and tablets, which have high pixel density, will be different with respect to the case where the same video is played on a large screen device such as a TV or PC monitor. Being able to model such relative differences in perception effectively can help in the design of better quality metrics and in the design of more efficient and optimized encoding profiles, leading to lower storage, encoding, and transmission costs.

However, to the best of our knowledge, public datasets providing subjective scores for the same content when viewed on multiple devices with different screen sizes do not exist, thus limiting a proper evaluation of the existing quality metrics for such multi-screen video streaming applications. This paper addresses this research gap by presenting a new, open-source dataset consisting of subjective ratings for various encoded video sequences of different resolutions and bitrates (quality) when viewed on three devices of varying screen sizes: TV, Tablet, and Mobile. Along with the subjective scores, an evaluation of some of the most famous and commonly used open-source objective quality metrics is also presented. It is observed that the performance of the metrics varies a lot across different device types, with the recently standardized ITU-T P.1204.3 Model, on average, outperforming their full-reference counterparts. The dataset consisting of the videos, along with their subjective and objective scores, is available freely on Github

## Dataset Description

The dataset files are available in the google drive folder [here](https://drive.google.com/drive/folders/1SZT_s2E1zvZ_DQabpED4H3ZDlB0ef4qQ?usp=sharing)

The dataset consists of following files:

1. `source_sequences`: The 1080p source sequences used to generate the encoded (test) video sequences

2. `test_sequences`: consists of the 27 test sequences which were used in the subjective test

3. `Results.xlsx`: An Excel file containing the Mean Opinion Scores for the test sequences for all three videos. In addition, objective metric scores and their correlation with MOS in terms of PLCC and SROCC scores is also provided. The results file also contain information about the test sequences resolution and bitrates. 

All plots and results reported in the paper along with a few additional results are also available for the interested readers.

## Citation

We are making BC-KU Multi-Screen Dataset available to the research community free of charge. If you use this database in your research, we kindly ask that you to cite our papers listed below:

Nabajeet Barman, Yuriy Reznik and Maria G Martini. 2023. A Subjective Dataset for Multi-Screen Video Streaming Applications}. In Proceedings of the 15th International Conference on Quality of Multimedia Experience (QoMEX'23). IEEE, submitted.

## Authors

- Nabajeet Barman, Brightcove UK Ltd, London, United Kingdom (nbarman@brightcove.com, nabajeetbarman4@gmail.com)
- Yuriy Reznik, Brightcove Inc, Seattle, USA  (yreznik@brightcove.com)
- Maria Martini, Kingston University, London, United Kingdom (m.martini@kingston.ac.uk)

## Copyright

Copyright (c) 2022 Kingston University, London and Brightcove UK Ltd 
All rights reserved. 
It has to be noted that the recordings may contain copyrighted work which can only be used in compliance with fair use.
Permission is hereby granted, without written agreement and without license or royalty fees, to use, copy, modify, and distribute this database (the videos, the results and the source files) and its documentation for any purpose, provided that the copyright notice in its entirety appear in all copies of this database, and the original source of this database, Kingston University, London and Brightcove UK Ltd, is acknowledged in any publication that reports research using this database.

IN NO EVENT SHALL THE KINGSTON UNIVERSITY AND BRIGHTCOVE UK LTD BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE USE OF THIS DATABASE AND ITS DOCUMENTATION, EVEN IF THE KINGSTON UNIVERSITY, LONDON AND BRIGHTCOVE UK LTD HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. 

THE KINGSTON UNIVERSITY AND BRIGHTCOVE UK LTD SPECIFICALLY DISCLAIM ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THE DATABASE PROVIDED HEREUNDER IS ON AN "AS IS" BASIS, AND THE KINGSTON UNIVERSITY, LONDON AND BRIGHTCOVE UK LTD HAS NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.
