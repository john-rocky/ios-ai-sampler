# <div align="center">ios-ai-sampler</div>
##### <div align="center">A collection of samples for using various AI models on iOS</div>
##### <div align="center">Use the model converted from Pytorch to Core ML in Swift.</div>

<<p align="center">
<img src=https://github.com/john-rocky/ios-ai-sampler/assets/23278992/cddb76d7-289f-4e50-afbd-a71cc914de7f width=300>
</p>

# Usage
0. Choose the model you like.
1. Jump to the link to the sample page of the model you want to use.
2. Clone and open　it with Xcode.
3. If the Core ML model size is less than 100MB, a Core ML model is bundled with the sample project.
   If the Core ML model is not bundled, download it from the [Core ML Models](https://github.com/john-rocky/CoreML-Models) link and drag and drop it into your Xcode project.

# Table of contents

- [**Object Detection**](#object-detection)
  - [yolov5](#yolov5)

# Object Detection

### [yolov5-iOS](https://github.com/john-rocky/CoreML-YOLOv5)
https://github.com/john-rocky/CoreML-YOLOv5
| Core ML Model Link | Original Project | License  | 
| -------------  | ------------- |------------- |
|[YOLOv5s](https://drive.google.com/file/d/1KT-9eKO4F-LYIJVYJg7dy2LEW_hVUq0M/view?usp=sharing)|[ultralytics/yolov5](https://github.com/ultralytics/yolov5)|[GNU](https://github.com/ultralytics/yolov5/blob/master/LICENSE)|
<img width="200" alt="スクリーンショット 2021-12-27 6 34 43" src="https://user-images.githubusercontent.com/23278992/147620103-ef113d22-eb7a-4399-a9fa-58970e3896b1.PNG">

# Semantic Segmentation
https://github.com/john-rocky/CoreML-Face-Parsing
### [face-parsing](https://github.com/john-rocky/CoreML-Face-Parsing)

<img src="https://user-images.githubusercontent.com/23278992/147860040-14a7e022-5490-4e51-98cd-cd421066dd8c.png" width=400> <img src="https://user-images.githubusercontent.com/23278992/147860042-d27f37b0-227b-45ab-8d76-f6c6f2f5b3a4.png" width=400>

| Core ML Model Link | Size | Output |Original Project | License | 
| ------------- | ------------- | ------------- | ------------- | ------------- |
| [face-Parsing](https://drive.google.com/file/d/1I_cu8x0k6d1AEV_VPLyMu3Pqg3hwmo7g/view?usp=sharing) | 53.2 MB | MultiArray(1 x 512 × 512)| [zllrunning/face-parsing.PyTorch](https://github.com/zllrunning/face-parsing.PyTorch)  | [MIT](https://github.com/zllrunning/face-parsing.PyTorch/blob/master/LICENSE)|

