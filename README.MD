# Weed Detector
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?style=flat-square)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/torch?style=flat-square)

Weeds in crops are every farmer's nightmare and removing them is a very time consuming and labor intensive job. This web app can assist farmer's in detecting weeds among acres of land with the motivation to save time and energy. 

The idea was inspired from a Youtube video (see references) and [Blue River Technology](https://bluerivertechnology.com/) is a well known organisation for implementing such technology.

## Demo
Live demo of the app hosted on streamlit:

[Weed Detector Demo](https://undisputedcoder-yolov5-app-m403pc.streamlitapp.com/)

## Installation
Install using a Python virtual environment and pip. Need to clone the yolov5 repo as well
```bash
    git clone https://github.com/ultralytics/yolov5
    cd yolov5
    pip install -qr requirements.txt
```
*Change the path of the weights in `app.py`*
## Deployment
To deploy this project run

```bash
    streamlit run app.py
```

### Trained Weights
The trained weights can be found in [releases](https://github.com/undisputedcoder/Weed-Detector/releases)

## References
- [AI & the future of Agriculture](https://www.youtube.com/watch?v=oot55bK62pk)
- [Crop and weed detection data with bouding boxes dataset](https://www.kaggle.com/datasets/ravirajsinh45/crop-and-weed-detection-data-with-bounding-boxes)