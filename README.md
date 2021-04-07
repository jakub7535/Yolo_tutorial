# Yolo tutorial
This is the code i used in my tutorial[yt link] of Yolo algorithm.

You can manipulate live thresholds(confidence, intersection of union) and accesories(anchor boxes, grids) using keyboard on image and see how it affects detection.

You can run detection them on videos, from camera, on images from your pc/laptop, and from most images on the web just by passing link of them.

You can comapre 4 algorithms on different input sizes(320, 416(most popular), 620, any integer multiple of 32):
- Yolov3
- Yolov3-tiny
- Yolov4
- Yolov4-tiny



# Instalation
Installing using conda(recomended)

``` bash
conda env create -f conda_instalation.yml
conda activate yolo_tutorial
python -m ipykernel install --user --name yolo_tutorial --display-name "yolo_tutorial"
```
Installing using pip

``` bash
pip install --upgrade pip opencv-python==4.5.1.48 numpy==1.19.2 jupyter
```

