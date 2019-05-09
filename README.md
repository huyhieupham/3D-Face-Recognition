# 3D Face Datasets

This repository contains a list of 3D face datasets. Each has a short description, year published and download url. Note that, the first 10 datasets (e.g. ) are most often used as training and validation data for deep learning-based 3D face recognition approaches. To the best of my knowledge, the LS3DFace (https://arxiv.org/pdf/1711.05942.pdf) is the largest 3D face dataset to date, which contains 1,853 identities with 31,860 scans. This is in fact a merged dataset from the most challenging public datasets (FRGCv2, BU3-DFE, Bosphorus, Texes FRD, BU4DFE, CASIA, UMB DB, 3D-TEC, and ND-2006). 

<p align="center"> 
<img src="https://github.com/huyhieupham/3D-Face-Recognition/blob/master/figures/3d_face_data.png" width="550" height="300">
</p>
<p align="center"> 
</p>
<p align="center"> 
   Figure 1: Details of some important datasets for 3D facial analysis tasks.
  </p>

## 1. FRGC v2 Dataset

**Original paper**: P. Phillips, P. Flynn, T. Scruggs, K. Bowyer, et al. "Overview of the face recognition grand challenge". In IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2005.

**Description**: The FRGC v2 is a large-scale 3D face recognition benchmark dataset with 446 identities and 4007 scans. The data consists of 3D scans and high resolution still imagery taken under controlled and uncontrolled conditions.

**Year of release**: 2005

**Download URL:** https://cvrl.nd.edu/media/django-summernote/2018-09-19/c7654649-5277-4d8c-b069-483d8ffa3039.pdf

## 2. BU-3DFE Database (Binghamton University 3D Facial Expression)

**Original paper**: L. Yin, X. Wei, Y. Sun, J. Wang, and M. J. Rosato. "A 3D facial expression database for facial behavior research" - In 7th International Conference on Automatic Face and Gesture Recognition (FGR06), pages 211–216. IEEE, 2006. 

**Description**: This dataset includes 100 subjects (56% female, 44% male), ranging age from 18 years to 70 years old, with a variety of ethnic/racial ancestries, including White, Black, East-Asian, Middle-east Asian, Indian, and Hispanic Latino for 2500 facial expression models.  Each subject made 6 expressions (e.g. happiness, disgust, fear and so on) with four levels of intensity from low to high and a neutral expression. 

**Year of release**: 2006

**Download URL:** http://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html

## 3. Bosphorus 

**Original paper**: A. Savran, N. Alyuz, H. Dibeklio ¨ glu, O. C¸ eliktutan, ˘ B. Gokberk, B. Sankur, and L. Akarun. "Bosphorus database for 3D face analysis" - In European Workshop on Biometrics and Identity Management, pages 47–56. Springer, 2008.

**Description**: The Bosphorus database contains 4,666 3D facial scans over 105 subjects with rich expression variations, poses, occlusions. The 2,902 scans contain expression variations from 105 subjects. In the experiment, 105 first neutral scans from each identity are used as a gallery set and 2797 non-neutral scans are used as a probe set.

**Year of release**: 2008

**Download URL:** http://bosphorus.ee.boun.edu.tr/default.aspx

## 4. Texas 3D Face Recognition Database (Texas 3DFRD) 

**Original paper**: S. Gupta, M. K. Markey, A. C. Bovik, "Anthropometric 3D Face Recognition", International Journal of Computer Vision, 2010, Volume 90, 3:331-349. 

**Description**: The Texas 3D Face Recognition database (Texas 3DFRD) is a collection of 1149 pairs of facial color and range images of 105 adult human subjects. These images were acquired using a stereo imaging system manufactured by 3Q Technologies (Atlanta, GA) at a very high spatial resolution of 0.32 mm along the x, y, and z dimensions. During each acquisition, the color and range images were captured simultaneously and thus the two are perfectly registered to each other.

**Year of release**: 2010

**Download URL:** http://live.ece.utexas.edu/research/texas3dfr/


## 5. CASIA 3D Face Database

**Reference**: "CASIA-3D FaceV1, http://biometrics.idealtest.org/"

**Description**:  This is a 3D face database consisting of 4624 scans of 123 persons using the non-contact 3D digitizer called Minolta Vivid 910 with the combined variations of expressions under illumination and poses under expressions.

**Year of release**: 2004

**Download URL:** http://biometrics.idealtest.org/dbDetailForUser.do?id=8

## 6. 3D-TEC 

**Original paper**: V. Vijayan, K. W. Bowyer, P. J. Flynn, D. Huang, L. Chen, M. Hansen, O. Ocegueda, S. K. Shah, and I. A. Kakadiaris.
"Twins 3D face recognition challenge". International Joint Conference on Biometrics (IJCB), 2011 , pages 1–7. IEEE, 2011.

**Description**: The 3D-TEC database contains 107 pairs (total 214 subjects) of twins and expressions of neutral and smiling scan are captured for each subject. Since twins are visually similar to each other, it is harder to identify a probe where the corresponding twin of the probe is in a gallery set. 

**Year of release**: 2011

**Download URL:** https://cvrl.nd.edu/projects/data/


## 7. ND-2006 

**Original paper**: T. C. Faltemier, K. W. Bowyer, and P. J. Flynn. Using a multi-instance enrollment representation to improve 3d face
recognition. In Biometrics: Theory, Applications, and Systems, 2007. BTAS 2007. First IEEE International Conference
on, pages 1–6. IEEE, 2007.

**Description**:  The ND-2006 3D face dataset contains 13,450 scans of 888 subjects. This is the large 3D face dataset that contains a substantial amount of varied facial expression (Neutral, Happiness, Sadness, Surprise, Disgust, and Other). A total of 888 distinct persons, with as many as 63 images per subject, are available in this dataset.

**Year of release**: 2007

**Download URL:** https://cvrl.nd.edu/media/django-summernote/2018-09-19/9e4d703f-f262-4e04-8731-e4833f525340.pdf

## 8. LS3D-W 

**Original paper**: Bulat, Adrian, and Georgios Tzimiropoulos. "How far are we from solving the 2D & 3D face alignment problem?(and a dataset of 230,000 3d facial landmarks)." Proceedings of the IEEE International Conference on Computer Vision, 2017.

**Description**: The LS3D-W is the largest and most challenging 3D facial landmark dataset to date (~230,000 images), obtained from unifying almost all existing datasets.

**Year of release**: 2017

**Download URL:** https://www.adrianbulat.com/face-alignment


## 9. DMCSv1 Database 

**Original paper**: W. Sankowski, P.S. Nowak, P. Krotewicz, "Multimodal Biometric Database DMCSv1 of 3D Face and Hand Scans" - In the 22nd International Conference on Mixed Design of Integrated Circuits & Systems, pp. 93-97, June 2015.

**Description**: The DMCSv1 database is a multimodal biometric database. The database contains 3D face and hand scans. The number of individuals:	35. Total number of face scans: 1050.

**Year of release**: 2015

**Download URL:**  http://biometrics.dmcs.pl/en/databases/dmcsv1

## 10. COMPACT Database Biometric Dataset of Face Images Acquired in Uncontrolled Indoor Environment 

**Original paper**: M. Włodarczyk, D. Kacperski, W. Sankowski, K. Grabowski, "COMPACT: Biometric Dataset of Face Images Acquired in Uncontrolled Indoor Enviroment", 2017

**Description**: The COMPACT dataset was collected in an indoor laboratory environment. It aims at fostering the development of biometric recognition systems that work indoors and in unconstrained conditions. Number of subjects:	108. Number of registration images:	12312. 

**Year of release**: 2017

**Download URL:** http://biometrics.dmcs.pl/en/databases/compact


## 11. The University of Milano Bicocca 3D face database  (UMB-DB database)

**Original paper**:  A. Colombo, C. Cusano, and R. Schettini, “B-DB: A Database of Partially Occluded 3D Faces,” in in Proc. ICCV 2011 Workshops, pp. 2113-2119, 2011.

**Description**: The University of Milano Bicocca 3D face database is a collection of multimodal (3D + 2D colour images) facial acquisitions. It has been acquired with a particular focus on facial occlusions, i.e.scarves, hats, hands, eyeglasses and other types of occlusion wich can occur in real-world scenarios. Database contents 143 subjects, (98 male, 45 female; a pair of male twins and a baby included); 1473 total acquisitions (3D + colour 2D).

**Year of release**: 2011

**Download URL:** http://www.ivl.disco.unimib.it/minisites/umbdb//


## 12. 3D Mask Attack Dataset 

**Original paper**: Erdogmus, Nesli, and Sébastien Marcel. "Spoofing in 2d face recognition with 3d masks and anti-spoofing with kinect." 2013 IEEE Sixth International Conference on Biometrics: Theory, Applications and Systems (BTAS). IEEE, 2013.

**Description**: It currently contains 76500 frames of 17 persons, recorded using Kinect for both real-access and spoofing attacks. Each frame consists of a depth image (640x480 pixels – 1x11 bits), the corresponding RGB image (640x480 pixels – 3x8 bits), manually annotated eye positions (with respect to the RGB image).

**Year of release**: 2013

**Download URL:** https://www.idiap.ch/dataset/3dmad

## 13. EURECOM Kinect 3D Face Dataset 

**Original paper**: Rui Min, Neslihan Kose, Jean-Luc Dugelay, "KinectFaceDB: A Kinect Database for Face Recognition," Systems, Man, and Cybernetics: Systems, IEEE Transactions on , vol.44, no.11, pp.1534--1548, 2014.

**Description**: A database of images of different facial expressions in different lighting and occlusion conditions to serve various research purposes. The Dataset consists of the multimodal facial images of 52 people (14 females, 38 males) obtained by Kinect

**Year of release**: 2014

**Download URL:** http://rgb-d.eurecom.fr/ 


## 14. FaceWarehouse: a 3D Facial Expression Database for Visual Computing 

**Original paper**: Cao Chen, Yanlin Weng, Shun Zhou, Yiying Tong, Kun Zhou: "FaceWarehouse: a 3D Facial Expression Database for Visual Computing", IEEE Transactions on Visualization and Computer Graphics, 20(3): 413-425, 2014

**Description**: This is a RGB-D Facial Expression Database of 150 individuals aged 7-80 from various ethnic backgrounds. For each person, the RGB-D data of her different expressions, including the neutral expression and 19 other expressions such as mouth-opening, smile, kiss, etc was captured. For every RGBD raw data record, a set of facial feature points on the color image such as eye corners, mouth contour and the nose tip are automatically localized, and manually adjusted if better accuracy is required.

**Year of release**: 2014

**Download URL:** http://kunzhou.net/zjugaps/facewarehouse/


## 15. University of York 3D Face Database 

**Original paper**: N/A.

**Description**: The database currently consists of over 5000 3D face models of approximately 350 people (15 models each). There are ten facial surfaces of 97 different people were captured, under the conditions. During capture, no effort was made to control the lighting conditions. In order to capture facial surfaces at various head orientations, the subjects are asked to face towards reference points positioned roughly at 45 degrees to the left, right, above and below the camera, but no effort was made to enforce a precise angle of orientation. 

**Year of release**: N/A.

**Download URL:** http://www-users.cs.york.ac.uk/~nep/research/3Dface/tomh/3DFaceDatabase.html

## 16. Biwi 3D Audiovisual Corpus of Affective Communication 

**Original paper**: G. Fanelli, T. Weise, J. Gall, L. Van Gool, "Real Time Head Pose Estimation from Consumer Depth Cameras", 33rd Annual Symposium of the German Association for Pattern Recognition (DAGM'11).

**Description**: This dataset comprises a total of 1109 sentences uttered by 14 native English speakers (6 males and 8 females). A real time 3D scanner and a professional microphone were used to capture the facial movements and the speech of the speakers. The dense dynamic face scans were acquired at 25 frames per second and the RMS error in the 3D reconstruction is about 0.5 mm. Each sentence was recorded twice: First, the speaker read the sentence from text, with a neutral expression. Then, the speaker watched a clip extracted from a feature film where the sentence is acted by professional actors and the context is highly emotional. After rating the emotions induced by the video, the speaker repeated the sentence.

**Year of release**: 2010

**Download URL:** http://www.vision.ee.ethz.ch/datasets/b3dac2.en.html

## 17. Biwi Kinect Head Pose Database 

**Original paper**: Fanelli, Gabriele, et al. "Random forests for real time 3d face analysis." International Journal of Computer Vision 101.3 (2013): 437-458.

**Description**: The dataset contains over 15K images of 20 people (6 females and 14 males - 4 people were recorded twice). For each frame, a depth image, the corresponding rgb image (both 640x480 pixels), and the annotation is provided. The head pose range covers about +-75 degrees yaw and +-60 degrees pitch. Ground truth is provided in the form of the 3D location of the head and its rotation.

**Year of release**: 2013

**Download URL:** https://data.vision.ee.ethz.ch/cvl/gfanelli/head_pose/head_forest.html#


## 18. ETH Face Pose Range Image Data Set 

**Original paper**: Breitenstein, Michael D., et al. "Real-time face pose estimation from single range images." 2008 IEEE Conference on Computer Vision and Pattern Recognition. IEEE, 2008.

**Description**: The dataset consisting of 10,545 range images from 26 people (male and female). Each person freely turned her head while the scanner captured range images at 28 fps. In the beginning, each person looks straight into the camera before moving the head. The resulting range images have a resolution of 640x480 pixels, and a face typically consists of about 150x200 depth values. The head pose range covers about +-90 degrees yaw and +- 45 degrees pitch rotation. Roll rotation is not included in this data set. In the image above, a few example input frames are visible (depth information is shown as green color values), and in the image below, a typical camera trajectory is visualized.

**Year of release**: 2008

**Download URL:** https://www.vision.ee.ethz.ch/datasets/headposeCVPR08/


## 19. Spacetime Faces Database 

**Original paper**: Zhang, Li, et al. "Spacetime faces: High-resolution capture for~ modeling and animation." Data-Driven 3D Facial Animation. Springer, London, 2008. 248-276.


**Description**: Video sequences to high resolution, editable, dynamically controllable face models. The capture system employs synchronized video cameras and structured light projectors to record videos of a moving face from multiple viewpoints. 

**Year of release**: 2008

**Download URL:** http://grail.cs.washington.edu/projects/stfaces/

## 20. Human face

**Original paper**: A. M. Bronstein, M. M. Bronstein, R. Kimmel, "Calculus of non-rigid surfaces for geometry and texture manipulation", IEEE Trans. Visualization and Computer Graphics, Vol 13/5, pp. 902-913, September-October 2007.

**Description**: An animated three-dimensional face dataset showing different facial expressions, acquired using a real-time range camera. The acquisition speed is approximately 3 frames/sec. The database contains 15 expressions of the same face, represented as a textured shape. Each object contains approximately 2000 vertices. 

**Year of release**: 2007

**Download URL:** http://tosca.cs.technion.ac.il/book/resources_data.html (Please scroll to bottom of page)


