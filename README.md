# Blood cell classification
Binary blood cells classification: infected or not infected.

# Installation
## Manually
- conda create -n bloodCells python=3.7
- conda install tensorflow-gpu=1.14.0
- conda install keras=2.3.1
- conda install pillow
- conda install matplotlib
- conda install scikit-learn
- conda install jupyterlab

# Required folder structure
```
data
├── training
│   ├── features
│   │   ├─00000.jpg
│   │   ├─00001.jpg
│	│   └─...
│	└── labels.csv	
└── inference
    ├── features
    │   ├─20000.jpg
    │   ├─20001.jpg
 	│   └─...
 	└── prediction.csv <- model generates this file
```