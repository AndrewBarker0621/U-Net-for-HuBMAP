# U-Net-for-HuBMAP
Human Biomolecular Mapping Project Competition
>"HuBMAP - Hacking the Kidney" is a Research Code Competition aiming at identifing glomeruli in human kidney tissue images

**Our team's final ranking in the public leaderboard was 80/1216 and the private leaderboard was 120/1216, which gave us the final *bronze* medal. Thanks to my teammates, Tim biubiu, tedin, Mroland2021 and JODY JODY!**

All codes are original, and we gave reference to the source in the reference section. This Git follows the open source rules of MIT, welcome reasonable reproduction and discussion.

For this competition, our challenge is to detect functional tissue units (FTUs) across different tissue preparation pipelines. An FTU is defined as a “three-dimensional block of cells centered around a capillary, such that each cell in this block is within diffusion distance from any other cell in the same block” (de Bono, 2013). The goal of this competition is the implementation of a successful and robust glomeruli FTU detector.

All rules and dataset can be find in the follow URL: https://www.kaggle.com/c/hubmap-kidney-segmentation/overview

This Git consists of four main files: 
+ *Inference_for_UNet_with_EfficientNet_backbone.ipynb*
+ *Main_seed_2020_size_1024_nfolds_2_trainfold_1.ipynb*
+ *Sub_efficient_sampling.ipynb*
+ *Train_efficient_sampling.ipynb*

The whole network contains U-Net structure, self-attentive mechanism and some reference to ResNet structure. The above constructions make the whole network more suitable for image segmentation and learning.
