# Mask-Detection-Dataset
Mask Detection Dataset for yolo annotated by using https://github.com/tzutalin/labelImg

This dataset is in format for training yolov3 model using darknet or any python wrapper for yolo.

it has 4000+ images of masked people on and 4000 images of non-masks.


More data will be added in future and any contribution is appriciated.

Star this repo to stay updated.

|class number | class name |
|-------------|------------|
| 0           | mask       |
|1            | nomask     |


Directory structure:
```
img/
  - image1.jpg
  - image1.txt
  - image2.jpg
  - image2.txt
  - image3.jpg
  - image3.txt
    .
    .
    .
train.txt
test.txt

```
format of annotation file
```
<object-class> <x> <y> <width> <height>
```
e.g.
```
0 0.513672 0.610879 0.246094 0.384937
0 0.567647 0.253906 0.205882 0.156250
1 0.373529 0.246094 0.158824 0.140625
```

test.txt and train.txt are randomly sampled in 10:90 ratio

format of train.txt and train.txt
```
imgs/3409.jpg
imgs/894.jpg
imgs/5249.jpg
imgs/1762.jpg
imgs/2337.jpg
imgs/2857.jpg
imgs/5004.jpg
imgs/467.jpg
```


Download zipped file : https://drive.google.com/file/d/12BAE8t-TumUcOEfJsz4ADL0bka57Dwrw/view?usp=sharing


**Credit of images :** 

  https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset
 
  http://shuoyang1213.me/WIDERFACE/
