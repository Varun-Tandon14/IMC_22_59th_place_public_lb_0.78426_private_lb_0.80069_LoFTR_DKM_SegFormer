# IMC_22_59th_place_public_lb_0.78426_private_lb_0.80069_LoFTR_DKM_SegFormer

### Background
This work was done as part of Image matching challenge 2022 (IMC 22) which was held on Kaggle by Google. 
Although this challenge is not new but this was the first time that challenge was held on Kaggle. 
The competition is part of [Image Matching: Local Features & Beyond
CVPR 2022 Workshop.](https://image-matching-workshop.github.io/)
[Competition Overview.](https://www.kaggle.com/competitions/image-matching-challenge-2022/overview) 


### Problem Statement
In this challenge the participants were asked to solve the Wide Baseline Stereo problem (WxBS) specifically for urban scenes.
Basically the problem was poised such as given two images (of the same scene) we had to essentially calculate the Fundamental matrix 
describing the projective geometry between the two images.
For more information about the problem visit this [page](https://www.kaggle.com/competitions/image-matching-challenge-2022/overview/problem-definition).

## Data
The train data that was given was part of Phototourism which contained images of different monuments around the world. 
The poses for each scene were reconstructed via [Structure-from-Motion](https://en.wikipedia.org/wiki/Structure_from_motion), and are only accurate up to a scaling factor. 
The final test had about 10000 pairs of images of urban scenes.
Additionally from the test set the organizers provided three set of images. 
The domain gap between train and test set was the reason that many teams didn't finetune their models on the training set.
Some teams which did so experienced a decline in performance. 
As per my knowledge, the organizers will realise the test set after the Image Matching: Local Features & Beyond
CVPR 2022 Workshop.

#### Download the IMC 22 dataset
Due to large size of the dataset, the readers are requested to download the dataset from this [page.](https://www.kaggle.com/competitions/image-matching-challenge-2022/data)
Please note at the time of writing this is only place the data is avaliable and you will have to register for the competition on kaggle to view and download the data. As
said earlier the data maybe realised after tghe workshop.

## How to run
1. Please make sure to place the notebook and all the dependencies (including the dataset) in the same folder.
2. Install all the dependencies.
3. The reader now have to change the path in the notebook to point to their local folder. (i.e. from kaggle/* to 'local path')

## Side note- Am I the best?
Most definitely not. This was my first kaggle competition and my first CV competition. I encourage the readers
to go to this [page](https://www.kaggle.com/competitions/image-matching-challenge-2022/discussion?sort=published) and explore discussions about the competition. It is here that you will learn the most. I certainly did. ;) 

# All done. Enjoy the code
