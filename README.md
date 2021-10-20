Note: The following information are taken from the related dataset project's websites. The sources are provided at the bottom of this readme file.

This repository contains the following three datasets:

1) NTU RGB+D and NTU RGB+D 120
2) Stanford40
3) BOLD5000

# NTU RGB+D and NTU RGB+D 120

## General Overview:

"NTU RGB+D" and NTU RGB+D 120" datasets contain 56,880 and 114,480 action samples, respectively. Both datasets include 4 different modalities of data for each sample:

+ RGB videos
+ depth map sequences
+ 3D skeletal data
+ infrared (IR) videos

Video samples have been captured by three Microsoft Kinect V2 cameras concurrently. The resolutions of RGB videos are 1920×1080, depth maps and IR videos are all in 512×424, and 3D skeletal data contains the 3D locations of 25 major body joints at each frame.

Paper: NTU RGB+D: A Large Scale Dataset for 3D Human Activity Analysis (https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Shahroudy_NTU_RGBD_A_CVPR_2016_paper.pdf)

Paper: NTU RGB+D 120: A Large-Scale Benchmark for 3D Human Activity Understanding (https://arxiv.org/pdf/1905.04757.pdf)

Github account: https://github.com/shahroudy/NTURGB-D

# Stanford40

## General Overview:

The Stanford 40 Action Dataset is a dataset for understanding human actions in still images. It contains images of humans performing 40 actions. In each image, they provide a bounding box of the person who is performing the action indicated by the filename of the image. There are 9532 images in total with 180-300 images per action class.

Paper: Human Action Recognition by Learning Bases of Action Attributes and Parts (http://vision.stanford.edu/pdf/YaoJiangKhoslaLinGuibasFei-Fei_ICCV2011.pdf)

# BOLD5000

## General Overview:

In BOLD5000, researchers have increased the stimulus set size deployed in an fMRI study of visual scene processing.

Researchers scanned 4 participants in a slow-evented related design with 4,916 unique scenes.
Data was collected over 16 sessions, 15 of which were task-related sessions, plus an additional session for acquiring high resolution anatomical scans.
In 8 of the 15 task-related sessions, a functional localizer was run in order to independently define scene-selective cortex.
In each scanning session, participants filled out a questionnaire (Daily Intake) about their daily routine, including: current status regarding food and beverage intake, sleep, exercise, ibuprofen, and comfort in the scanner. 
During BOLD scanning, physiological data (heart rate and respiration) were also acquired.

## Stimuli and Presentation Details:
The experiment includes:

1) 4,803 images presented on a single trial throughout the experiment
2) 112 images repeated four times, and one image repeated three times
3) a total of 5,254 stimuli trials.

The stimuli were drawn from three datasets:

1) 1000 images from Scene Images (with scene categories based on SUN categories)
2) 2000 images from the COCO dataset
3) 1916 images from the ImageNet dataset

Images were presented for 1 second, with 9 seconds of fixation between trials. Participants were asked to judge whether they liked, disliked, or were neutral about the image.

## Summary:

In sum, this dataset is unique in three ways: it is

1) significantly larger than existing slow-event related neural datasets by an order of magnitude
2) extremely diverse in stimuli
3) considerably overlapping with existing computer vision datasets

This large-scale dataset enables novel neural network training and novel exploration of benchmark computer vision datasets through neuroscience. Finally, the scale advantage of this dataset and the use of a slow event-related design enables, for the first time, joint computer vision and fMRI analyses that span a significant and diverse region of image space using high-performing models.

## Other Resources:
+ A complete re-release of functional data from BOLD5000 is provided here: https://figshare.com/s/bbaf45dca1b1b873ddfa
+ First release of the functional data from BOLD5000 is provided here: https://figshare.com/articles/dataset/BOLD5000/6459449
+ The Github repository of BOLD5000 dataset: https://github.com/BOLD5000-dataset/BOLD5000
+ The BOLD5000's paper on Nature: https://www.nature.com/articles/s41597-019-0052-3
+ Term of use for BOLD5000's dataset: https://bold5000-dataset.github.io/website/terms.html

### Sources: 
+ NTU RGB+D: https://rose1.ntu.edu.sg/dataset/actionRecognition/
+ Stanford40: http://vision.stanford.edu/Datasets/40actions.html
+ BOLD5000: https://bold5000-dataset.github.io/website/
