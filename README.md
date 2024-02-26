# Hand Washing Anaylzer 

## Overview:
This project utilizes two datasets:
* [Kaggle](https://www.kaggle.com/datasets/realtimear/hand-wash-dataset/data)
* [Pauls Stradins Clinical University Hospita](https://zenodo.org/records/4537209)

These datasets contain videos of correct hand washing practices (by the WHO). They will imported into MediaPipe to output location points (x,y,z) of landmarks on the hands in the video. There are 20 landmarks which are the joints on ones hand. 

After all the location points are recognized we will use the labeled datasets to train a model in PyTorch which will be able to analyze how well someone completed each movement.

All movements:   
"1: Hand washing movement — Palm to palm   
2: Hand washing movement — Palm over dorsum, fingers interlaced   
3: Hand washing movement — Palm to palm, fingers interlaced   
4: Hand washing movement — Backs of fingers to opposing palm, fingers interlocked   
5: Hand washing movement — Rotational rubbing of the thumb   
6: Hand washing movement — Fingertips to palm   
7: Turning off the faucet with a paper towel   
0: Other hand washing movement"   




