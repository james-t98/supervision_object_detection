# Supervision Object Detection 🚀  

This repository contains experiments and utilities for **object detection using [Supervision](https://github.com/roboflow/supervision)**, extended to both **image** and **video** pipelines.  
The project demonstrates how modern **Vision-Language Models (VLMs)** and **Supervision annotators** can be integrated into a practical detection workflow.  

---

## 📖 Overview  

Object detection is a fundamental task in computer vision, enabling applications from video analytics to sports tracking and real-time monitoring.  
This project focuses on building modular detection pipelines that:  

- ✅ Run detection on **static images** and **video streams**  
- ✅ Integrate **Supervision** for annotation and visualization  
- ✅ Explore the role of **Vision-Language Models (VLMs)** in guiding or enhancing detection  
- ✅ Provide **notebook-based experiments** for reproducibility and easy adaptation  

---

## 🏗️ Project Components  

1. **Image Object Detection**  
   - Implemented in: [`sv_vlm_image_object_detection.ipynb`](./sv_vlm_image_object_detection.ipynb)  
   - Demonstrates applying a detection model to images and overlaying annotations.  
   - Integrates VLMs for class-labeling and contextual description.  

2. **Video Object Detection**  
   - Implemented in: [`sv_vlm_video_object_detection.ipynb`](./sv_vlm_video_object_detection.ipynb)  
   - Processes video streams frame-by-frame.  
   - Provides tracking, overlays, and optional temporal analysis.  

---

## 🛠️ Tech Stack  

- **[Supervision](https://github.com/roboflow/supervision)** for annotation & visualization  
- **Vision-Language Models (VLMs)** for context-aware detection labels  
- **OpenCV** for video I/O  
- **Jupyter Notebooks** for reproducible experiments  

---

## 📌 Key Features  

- 🔍 **Flexible detection** for both images and videos  
- 🎨 **Supervision-powered overlays** for clear bounding boxes & keypoints  
- 🤖 **VLM integration** to enrich object labels with descriptive context  
- 📈 **Notebook-first workflow** for easy prototyping and adaptation  

---

## 🔮 Future Directions  

- Real-time deployment on camera streams  
- Integration with **tracking-by-detection** for multi-object tracking  
- Evaluation across multiple detection models (YOLO, SAM, etc.)  
- Adding explainability via VLM-generated captions  

---