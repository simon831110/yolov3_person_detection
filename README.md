## yolov3_preprocessing_person_detection
這個倉庫是為了[person_classifiaction_tf2.0](https://github.com/simon831110/person_classifiaction_tf2.0)所做的前處理，使用Yolo v3使得行人圖片較不受到背景所影響並過濾沒有行人的圖片。

## 建置環境
<pre>
TensorFlow >=2.0.0<br/>
opencv-python<br/>
os<br/>
</pre>

在當前資料夾下新增名為`dataset_cropped`的資料夾存放修剪後的圖片，並存在行人資料庫如下存放:
<pre>
/dataset<br />
    /dataset/0000<br />
    /dataset/0001<br />
    /dataset/0002<br />
    .<br />
    .<br />
    .<br />
</pre>
## 展示
![demo](https://github.com/simon831110/yolov3_preprocessing_person_detection/blob/main/data/cropped_and_uncropped.jpeg)
