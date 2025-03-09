# OpenCV Object Detection with YOLO 🚀

## 📌 Description
This project uses **OpenCV** and **YOLOv3** to perform real-time object detection on images and videos. It leverages deep learning models to accurately detect multiple objects within an image.

## ✅ Features
- ✔ Detects multiple objects in an image
- ✔ Uses **YOLO deep learning model** for fast and accurate detection
- ✔ Works with both images and real-time webcam feed

## 🔧 Installation
To set up the project, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Adityadoijad/OpenCV-Object-Detection.git
   cd OpenCV-Object-Detection
   ```

2. **Install Dependencies:**
   ```bash
   pip install opencv-python numpy
   ```

3. **Download YOLO Model Files:**
   - [`yolov3.cfg`](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
   - [`coco.names`](https://github.com/pjreddie/darknet/blob/master/data/coco.names)
   - [`yolov3.weights`](https://github.com/patrick013/Object-Detection---Yolov3/blob/master/model/yolov3.weights)
     
4. **Run the Object Detection Script:**
   ```bash
   python script.py
   ```

## 🛠️ Usage
### Run Object Detection on an Image
1. Place your test image (e.g., `test.jpg`) in the project directory.
2. Run the following command:
   ```bash
   python script.py --image test.jpg
   ```
3. The script will process the image and display detected objects with bounding boxes.

### Run Object Detection on a Video
1. Place your test video (e.g., `test.mp4`) in the project directory.
2. Run the following command:
   ```bash
   python script.py --video test.mp4
   ```
3. The script will process the video frame-by-frame and show detected objects.

### Run Object Detection Using Webcam
1. Connect your webcam (if not already available).
2. Run the following command:
   ```bash
   python script.py --video 0
   ```
3. The `0` represents the default webcam. Change it to `1` or `2` if using an external camera.

### Adjusting Confidence and Threshold
If you want to fine-tune the detection results, modify the `CONFIDENCE_THRESHOLD` and `NMS_THRESHOLD` values in the script.


## 🚀 Future Improvements
- ✅ Implement YOLOv4 for better accuracy
- ✅ Improve real-time detection speed
- ✅ Add a GUI interface for easier usage

## 👤 Author
**Aditya Doijad**  
🔗 GitHub: [Adityadoijad](https://github.com/Adityadoijad)  
🔗 LinkedIn: [Aditya Doijad](https://www.linkedin.com/in/adityadoijad)

---
Feel free to contribute or suggest improvements! 🚀

