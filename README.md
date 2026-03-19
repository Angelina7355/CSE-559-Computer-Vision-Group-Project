# Bird’s Eye View (BEV) System

## Overview
This project implements a mock-up Bird’s Eye View (BEV) system that generates a top-down visualization of a scene from multiple images. The system combines image stitching, geometric transformations, and object detection to create an informative overhead map.

---

## Features
- Image stitching to combine multiple viewpoints  
- Object detection (e.g., cars, pedestrians) using a pre-trained model
- Transformation to approximate a top-down (BEV) perspective  
- Visualization of detected objects on the BEV map  

---

## Project Structure
- `panoramic_stitching.ipynb` – Image stitching and BEV transformation  
- `object_detection.ipynb` – Object detection on input images  
- `visualization_mapping.ipynb` – Mapping detections to BEV and visualization  
