# Face-Recognition-Using-Deep-Learning

🔥 (Face recognition for smart attendance system using deep learning, published in 2023) implemented (FaceNet, ArcFace trained on single GPU) in Tensorflow 2.0+. This is an Documentation Implementation.🔥

Results show that RetinaFace face detection has average precision (AP) results on the WiderFace dataset of 94.20% easy, 93.24% medium, and 83.55% hard, better than MTCNN with AP values of 83.31% easy, 80.32% medium, 83.55% hard. For the combination of face recognition models, FaceNet + RetinaFace obtained as the best combinations model in recognition and speed with a Rank-1 Recognition Rate of 99.114% and recognition speed per image of 118.90 ms.

Link Paper: [CMBN Journal](https://scik.org/index.php/cmbn/article/view/7872)


## Data Preparation

Download the data from here : [Dataset](https://binusianorg-my.sharepoint.com/personal/galuh_warman_binus_ac_id/Documents/Dataset%20and%20Model%20Thesis/Face%20Data.zip?csf=1&web=1&e=OzaYFM)

Download Model FaceNet : [Model FaceNet](https://drive.google.com/drive/folders/12aMYASGCKvDdkygSv1yQq8ns03AStDO_)


After downloading do this:

- first extract the dataset file into the dataset folder then, run splitdata.ipynb to divide the dataset ratio
- both extract the faceneth5 model parallel to the .ipynb file of the combination model


###IPYNB FILES

- The first IPYNB named Complete Results 1 Model is an example of a complete model from start to finish starting from the step face detect - embedding - face recog - final result which includes training and testing
- The second IPYNB named Combination Model Evaluation Results is an ipynb which contains the speed of the combined model
