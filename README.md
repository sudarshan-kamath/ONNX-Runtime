# ONNX-Runtime
Experiments with the object detection using ONNX-Runtime

This repository aims to showcase the findings during my thesis work, where I was dealing with the MobileNetV2 architecture with SSDLite.
It was observed that the MobileNetV2 based SSD had lower frame rates compared to the YOLOv2, which was a bigger network, even though the size of the weights was around 19 Mb.

This got me interested into finding the answers for this behaviour, which culminated in me discovering the ONNX runtime.
