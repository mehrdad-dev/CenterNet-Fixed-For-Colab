<p align="center">
  <img src="https://raw.githubusercontent.com/mehrdad-dev/CenterNet-Fixed-For-Colab/main/images/centernet-in-colab.png" alt="CenterNet Fixed For Google Colab, mehrdad mohammadian" style="width:550px;height:100px;"/>
</p>
<div align=center> Object detection, 3D detection, and pose estimation using center point detection </div>
 
-------- 
 
## 🛠 CenterNet Fixed For Google Colab 
  
\+ 🤔  Do you want to run CenterNet pre-trained models in Colab without error 🐞 and make predictions?

\- 🤯 BAAM, yes!

\+ 😎 Read [this doc](https://mehrdad-dev.ir/CenterNet-Fixed-For-Colab/) and then download [this jupyter notebook](https://github.com/mehrdad-dev/CenterNet-Fixed-For-Colab/blob/main/CenterNet-for-colab.ipynb), to run CenterNet pre-trained models (with different backbones) on your dataset!
 

## The Official CenterNet repo
[go to the repo](https://github.com/xingyizhou/CenterNet)


## Jupyter notebook
For use CenterNet in google colab please download [this jupyter notebook](https://github.com/mehrdad-dev/CenterNet-Fixed-For-Colab/blob/main/CenterNet-for-colab.ipynb) and run it.

Note: Set your `Hardware accelerator` on GPU in colab.

 ## Options
You can use the blow options for change seeting:

**Basic settings:**

`task`: ctdet, ddd, multi_pose, exdet,  default='ctdet'

`--dataset`: coco, kitti, coco_hp, pascal, default='coco'

`--exp_id`: default='default'

`--test`: store_true

`--debug`:   default=0
 - 1: only show the final detection results
 - 2: show the network output features
 - 3: use matplot to display 
 - 4: save all visualizations to disk

`--demo`: path to image/ image folders/ video or webcam

`--load_model`: path to pretrained model

`--resume`: resume an experiment. Reloaded the optimizer parameter and set load_model to model_last.pth in the exp dir if load_model is empty


## Results

See the [results.md](./results.md) for compare the diffrent backbones results.
