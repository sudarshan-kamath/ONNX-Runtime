# ONNX-Runtime
## Experiments with the object detection using ONNX-Runtime

This repository aims to showcase the findings during my thesis work, where I was dealing with the MobileNetV2 architecture with SSDLite.
It was observed that the MobileNetV2 based SSD had lower frame rates compared to the YOLOv2, which was a bigger network, even though the size of the weights was around 19 Mb.

This got me interested into finding the answers for this behaviour, which culminated in me discovering that ONNX runtime exists. The aim was to run inference in other framework by converting the original weights that was present in PyTorch format. ONNX allows to convert the weights by acting as an intermediate format, but it was cool that ONNX runtime was also being provided, with various target hardware configurations.

## Results
The most important section! The observations for the ONNX Runtime are very interesting, which made me use it in the first place.
Publishing the results of my inference speeds for ONNX and PyTorch for comparison here.
