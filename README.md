# FER-SN-FER2013
## Usage
**Step 1. Install libraries**
```
conda env create -f environment.yml
```
**Step 2. Download fer2013 CSV file**
```
https://www.kaggle.com/competitions/challenges-in-representation-learning-facial-expression-recognition-challenge/data
```
**Step 3. Download pre-trained models from this link**
```
https://www.dropbox.com/sh/xaxnzhzuyacmuf8/AADR7qY-QHv1vfRTGOOwi5Yea?dl=0
```
**Step 4. Set the correct paths in the following files**
```
Evaluation.ipynb
train.py
data/fer2013.py
```
**To train the model from scratch, run the following**
```
python train.py network=vgg name=my_vgg
```
**For evaluation open the following jupyter notebook**
```
Evaluation.ipynb
```
