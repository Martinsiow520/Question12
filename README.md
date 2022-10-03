# Question12
Describle the video segmentation 

Segmentation is applied during video recognition using the YOLACT method. The training weights used by YOLACT are yolact resnet50 54 800000.pth and applied to the COCO 2017 dataset. With Google Colaboratory, this process is very fast, averaging 27.1 frames per second. In the video, the subject is segmented and the appropriate labels can be seen, but the limitation of segmentation is pointed out that it cannot be continuously visible.

Question 1

YOLACT adopts the method of instance segmentation, which makes people's detection and segmentation of individuals clearer, but the detection methods of DeepSORT and FairMOT are easier to detect people, but the view of the video is cluttered.

Question 2

By using video-based action recognition, YOLACT has more potential and is better developed in the architecture to be used for this in real time. But YOLACT needs to focus on the hardware capabilities required by CUDA and PyTorch platform. With the use of higher requirements at the hardware level, YOLACT becomes faster compared to other instance segmentation.
