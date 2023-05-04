# Optimize CLIP model for inference with OpenVINO™ Toolkit
This tutorial shows how to optimize the models from OpenCLIP library for inference using the OpenVINO™ Toolkit.
The Optimization consists from two steps:
* Export image and text encoder models into OpenVINO format. See details in the `openvino_export.ipynb`.
* Apply post-training 8-bit quantization to exccelerate inference. See details in the `openvino_quantization.ipynb`.

## Prerequisites
```
pip install -r requirements_openvino.txt
```