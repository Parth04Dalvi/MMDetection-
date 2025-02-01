# MMDetection<br>
 MMDetection is an open source object detection toolbox based on PyTorch. It is a part of the OpenMMLab project. (The main branch works with PyTorch 1.8+)

 # Main Features<br>

# Modular Design<br>

We decompose the detection framework into different components and one can easily construct a customized object detection framework by combining different modules.<br>

Support of multiple tasks out of box<br>

The toolbox directly supports multiple detection tasks such as object detection, instance segmentation, panoptic segmentation, and semi-supervised object detection.<br>

High efficiency<br>

All basic bbox and mask operations run on GPUs. The training speed is faster than or comparable to other codebases, including Detectron2, maskrcnn-benchmark and SimpleDet.<br>

State of the art<br>

The toolbox stems from the codebase developed by the MMDet team, who won COCO Detection Challenge in 2018, and we keep pushing it forward. <br>
The newly released RTMDet also obtains new state-of-the-art results on real-time instance segmentation and rotated object detection tasks and the best parameter-accuracy trade-off on object detection.<br>
