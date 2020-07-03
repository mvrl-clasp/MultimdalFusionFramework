# Visual-Linguistic Semantic Alignment
The Visual-linguisitc semantic alignment (VLSA) framework and the visualization tool were developed by a group of researchers associated with the [Multidisciplinary Vision Research Lab](http://mvrl.cis.rit.edu/) and [Computational Linguistics and Speech Processing Lab](https://www.rit.edu/clasp/) at Rochester Institute of Technology.

![Raw data](https://raw.githubusercontent.com/mvrl-clasp/MultimodalFusionFramework/master/thesis_snagFig19.png)

There are four folders in the downloaded folder. A Readme file accompanies these folders and details out all the steps required to execute the framework excluding data collection. 

#### 1. VLSACode:

This folder consists of all the software code to run the framework. There are two main bash files that can be used to execute the entire framework. The bash files call other sub programs that are mostly in Python and a few in MATLAB. Please note Python 2.7 was used to code the scripts and necessary changes would have to be made to migrate them to Python 3. 

This folder comes with the BerkeleyAligner and BerkeleyParser with the English grammer database. 

#### 2. VLSAData:

This folder consists of example files for data that is required for each step up to the step before applying the Berkeley aligner. The Readme exaplins in detail what data is need at which step. It also has a folder for the reference alignments (ground truth) that can be obtained using the RegionLabeler software provided n this website [SNAG](https://mvrl-clasp.github.io/SNAG/).

#### 3. VLSAUnits:

#### 4. ALignmentPlotter: 

For ease, the Alignment Plotter is included in the VLSA framework folder. For more details on this folder see below.

# Alignment Plotter: Annotation visualizer
This folder contains the Alignment Plotter, which is a MATLAB program to visualize the annotations. The program needs two output files that are generated from the VLSA Framework or the appropriate data in the format as the files generated by the framework. For more information, please refer to the README.txt within the folder. 

# Downloads  

[VLSAFramework](https://drive.google.com/drive/folders/1QbrnSsqh78mERLyUjHp1OtG8BZau6_z7)

[AlignmentPlotter](https://drive.google.com/drive/folders/1nnB3LPdQIQ7j0U9G6uLKm1uhVKk8iaJ3)

# License
[VLSAFrameworkLicenses.pdf](https://drive.google.com/file/d/1Anj-cPYv62vISyvKC1vva55aHXi6ssRN/view?usp=sharing)

[AlignmentPlotterLicense.pdf](https://drive.google.com/file/d/1vWHmmqu736zNrex2I33sRNZdLhNVv2YS/view?usp=sharing)

# Citation and Contact
Please cite our paper when you use this framework or parts of it:

Vaidyanathan, P., Prud’hommeaux, E., Alm, C. O., & Pelz, J. B. (2020). Computational framework for fusing eye movements
and spoken narratives for image annotation. Journal of Vision, 00(0):06788, 1–28.

@article{Vaidyanathan2020Computational,
  title={Computational framework for fusing eye movements and spoken narratives for image annotation},
  author={Vaidyanathan, P., Prud’hommeaux, E., Alm, C. O., & Pelz, J. B.},
  journal={Journal of Vision},
  volume={00(0)},
  number={06788},
  pages={1--28},
  year={2020},
  publisher={Association for Research in Vision and Ophthalmology}
}

For any questions about this dataset or software please contact Preethi Vaidyanathan at pxv1621@rit.edu.
 
