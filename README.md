# Final_Project_StyleGAN
#### This experimental environment depends on libraries: torch, yacs, tqdm, numpy, torchvision

#### Reference code URL: https://github.com/huangzh13/StyleGAN.pytorch

#### Using ffhq 128x128 dataset, the dataset is available at: https://github.com/NVlabs/ffhq-dataset

#### he third-party tools used are mainly libraries needed to run the StyleGAN model, mainly pytorch, reference tutorials are: 1) https://zhuanlan.zhihu.com/p/292659179 2) https://arxiv.org/pdf/1812.04948.pdf

The purpose of my experiment is to train the StyleGAN network to get a model that can generate a specific Style image. I will give the necessary hints and the experiment will be successful if the model can generate images that satisfy the conditions. In this project I use deep learning algorithms, specifically I will use the StyleGAN network, which is divided into two parts, the Mapping Network and Synthesis Network, and the model structure is shown in the following figure:

<img width="186" alt="image" src="https://github.com/YunfanGuo/Final_Project_StyleGAN/assets/119873151/93e89818-9838-471f-9fd8-9815e63372ac">

Samples generated when the model was trained up to round 19:

<img width="232" alt="image" src="https://github.com/YunfanGuo/Final_Project_StyleGAN/assets/119873151/13a237ba-15b2-41d7-9fd5-9a93fe53496f">

Training to the current round of generated samples (terminated early because of the long time)

<img width="235" alt="image" src="https://github.com/YunfanGuo/Final_Project_StyleGAN/assets/119873151/107605cc-3527-41ec-848a-e4fada0e79f5">

This experiment had high hardware requirements and long training times. In the follow-up I moved to Google Colab to run the test, the test run time was equally long and did not improve. And problems occurred when deploying in the local environment, for example, some compatibility errors were encountered when installing the torch, which was eventually solved by searching on the web. I think there is still a lot of room for improvement in the follow-up, and how to try to collect more datasets if possible, in order to improve the generalization of the model and generate more diverse images.

Video Link: https://youtu.be/qU-3esWJSdQ
