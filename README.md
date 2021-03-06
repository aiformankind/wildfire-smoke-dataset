# Open Wildfire Smoke Datasets

The goal is to curate wildfire smoke datasets to enable open sharing and ease of access of datasets for developing vision based wildfire detection models. Easy access and open sharing of datasets will facilitate and accelerate the research efforts in solving wildfire crisis.

#### HPWREN Cameras

[AI For Mankind](https://aiformankind.org/) downloaded the public domain HPWREN Cameras images and annotated these images with bounding boxes for object detection.

1. [Bounding Box Annotated Wildfire Smoke Dataset (Pascal VOC annotation format) Version 1.0](https://drive.google.com/file/d/1sEB77bfp2yMkgsSW9703vwDHol_cK6D5/view?usp=sharing) for smoke detection. Thank you our founder [Wei Shung Chung](https://www.linkedin.com/in/wei-shung-chung-01326a7/) in creating this first set of bounding boxes. In total, 744 bounding box annotated images are created.

2. [Bounding Box Annotated Wildfire Smoke Dataset (Pascal VOC annotation format) Version 2.0](https://drive.google.com/drive/folders/1IKXN2-hxTrEQsIIKOxiUAuLgoxubA9Wq?usp=sharing) This is the latest annotated images we created with the help of **our volunteers**. It has 2192 annotated images.

**Please give credits to AI For Mankind and HPWREN when using these bounding box annotated smoke datasets. The bounding box annotated smoke datasets are licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).** 

Note: [Learn more about HPWREN](http://hpwren.ucsd.edu/)

#### Donate to Support Us
[Donate](https://donorbox.org/support-the-evaluation-and-deployment-of-wildfire-smoke-detector) to support our efforts. Your donation is tax deductible. AI For Mankind is a registered 503(c)(3) nonprofit organization.

For classification, you can checkout this dataset [Wildfire Smoke vs No Smoke datasets](https://tinyurl.com/roo8tas). We separated the images into smoke and no smoke categories for anyone who is interested in building a smoke classifier.


We created a few promising wildfire smoke detection models using the version 1.0 of bounding box annotated wildfire smoke images (744 images). Learn more about our [wildfire smoke detection research](https://aiformankind.org/wildfire-smoke-detection-research/).

#### Clouds Dataset
Clouds/fog have similar visual appearance as wildfire smoke. Detection model might confuse cloud/fog with smoke. We share the following cloud dataset we curated from HPWREN cameras. 

1. [Cloud dataset](https://drive.google.com/file/d/1mUgVvnctpdZ8VZgihIDMoeUgkhsx1iAH/view?usp=sharing)

#### Submit your Model
We welcome you to train new wildfire detection model and submit your model to us for benchmarking/evaluation. If your model beat our benchmark, we will deploy your model to production for further evaluation.

One of our production models is the winning model from last year wildfire detection hackathon 2.0.

#### Detection Results
AI For Mankind's wildfire smoke detector aka "The Super Duper" built using this annotated dataset shows very promising results.

Checkout our <a href="https://youtube.com/playlist?list=PLB-XesK9mcaCCvSbogU9SFBlp1LEAjgT2">detections for fire season 2020</a>

1. For 2020-02-05 fire captured by HPWREN camera hp-w-mobo-c, our detector detected the smoke *13 minutes* after fire ignition.

    <br/>
    <a href="https://youtu.be/CcbXdcMEQvs"><img src="images/smoke_detector_in_action_13mins_detected.png" width="500" ></a>
    <br clear="right"/>

 2. For 2020-03-06 fire captured by HPWREN camera mlo-n-mobo-c, our detector detected the smoke *3 minutes* after fire ignition. See video below.

    <br/>
    <a href="https://youtu.be/X_QvjA1-Nb4"><img src="images/smoke_detector_in_action_3mins_detected.png" width="500" ></a>

    <br clear="right"/>

    <br/>
    
 3. For 2019-10-06 fire captured by HPWREN camera pi-s-mobo-c, our detector detected the smoke *3 minutes* after fire ignition. See video below.

    <br/>
    <a href="https://youtu.be/e9T_8coM20M"><img src="images/smoke_detector_in_action_3mins_detected_20191006.png" width="500" ></a>

    <br clear="right"/>

    <br/>
    
 4. For 2019-10-06 fire captured by HPWREN camera lp-s-mobo-c, our detector detected the smoke *10 minutes* after fire ignition. See video below.

    <br/>
    <a href="https://youtu.be/XVvZVnxHv4A"><img src="images/smoke_detector_in_action_10mins_detected_20191006.png" width="500"></a>

    <br clear="right"/>

    <br/>   
 
 5. For 2020-05-21 fire captured by HPWREN camera VEGMGMT ml-w-mobo-c, our detector detected the smoke *16 minutes* after fire ignition.

    <br/>

    <img src="images/20200521_VEGMGMT_ml-w-mobo-c_1590081617_+00960_smoke_detected.png" alt="Wildfire Smoke Detector in Action" width="450"/>
    <br clear="right"/>


You can checkout more results below:

   - [20191006: Detected smoke ~6 mins after fire ignition (HPWREN ml w mobo c)](https://youtu.be/wt1sQyRjoCI)
   - [20191006: Detected smoke ~7 mins after fire ignition (HPWREN lp n mobo c)](https://youtu.be/dViR_XGQ8Oo)
   - [20191006: Detected smoke ~10 mins after fire ignition (HPWREN lp s mobo c)](https://youtu.be/XVvZVnxHv4A)
   - [20191006: Detected smoke ~3 mins after fire ignition (HPWREN pi s mobo c)](https://youtu.be/e9T_8coM20M)
   - [20191007: Detected smoke ~10 mins after fire ignition (HPWREN sm s mobo c)](https://youtu.be/LqAxrY-Xa4w)
   - [20200206: Detected smoke ~4 mins after fire ignition (HPWREN ml s mobo c)](https://youtu.be/Y3tal1-nk1Y)
   - [20200306: Detected smoke ~3 mins after fire ignition (HPWREN mlo n mobo c)](https://youtu.be/X_QvjA1-Nb4)
   - [20200205: Detected smoke ~13 mins after fire ignition (HPWREN hp w mobo c)](https://youtu.be/CcbXdcMEQvs)
   - [20200615: Detected smoke ~4 mins after fire ignition (HPWREN rm e mobo c)](https://youtu.be/uPSkxGjUqRk)
   
See our wildfire smoke detector in action: https://www.youtube.com/playlist?list=PLB-XesK9mcaCCvSbogU9SFBlp1LEAjgT2   

#### Become Volunteer 
AI For Mankind's volunteers will continue to annotate these HPWREN images and make them available here. Please feel free to reach out to us ai.for.mankind@gmail.com if you would like to volunteer your time to help with labeling. Learn more about AI For Mankind [here](https://www.meetup.com/AI-for-Mankind/)

#### Other Smoke Images
1. [Center for Wildfire Research of University of Split, Croatia](http://wildfire.fesb.hr/index.php?option=com_content&view=article&id=49&Itemid=54)

#### Papers
* [Wildfire smoke detection based on local extremal region segmentation and surveillance](https://www.sciencedirect.com/science/article/pii/S0379711216301059)
* [Wildfire Smoke Detection Using SpatioTemporal Bag-of-Features of Smoke](https://www.cse.unr.edu/~bebis/CS479/PaperPresentations/SmokeDetectionBoFs.pdf)
* [A wireless sensor network for early forest fire detection and monitoring as a decision factor in the context of a complex integrated emergency response system](https://ieeexplore.ieee.org/document/8052688)
* [Wildfire Smoke Detection using Convolutional Neural Networks](https://www.inf.fu-berlin.de/inst/ag-ki/rojas_home/documents/Betreute_Arbeiten/Master-Hohberg.pdf)


#### Join Our Slack Channel
- [AI For Mankind Slack Channel](https://tinyurl.com/vch2z68)

#### Join Our Meetup Group
- [Join AI For Mankind Meetup Group](https://www.meetup.com/AI-for-Mankind/) to receive event announcement.

#### AI For Mankind's Youtube Channel
- [Presentations](https://www.youtube.com/channel/UCyosmgDqG3jfZ4_aYsN94Lw)


#### Donate to Support Us
[Donate](https://donorbox.org/support-the-evaluation-and-deployment-of-wildfire-smoke-detector) to support our efforts. Your donation is tax deductible. 
