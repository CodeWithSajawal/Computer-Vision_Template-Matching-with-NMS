# Computer-Vision_Template-Matching-with-NMS
This project enhances a template matching implementation by integrating Non-Maximum Suppression (NMS) to improve object localization in computer vision tasks.
# Computer-Vision_Template-Matching-with-NMS

This project implements **template matching** enhanced with **Non-Maximum Suppression (NMS)** to achieve more accurate and robust object localization in images.  
Instead of returning many overlapping detections for the same object, NMS filters and keeps only the **most confident** bounding boxes.

---

## 📌 Key Features

- 🔍 **Template Matching** using OpenCV  
- 📉 **Confidence Score Map** (match result heatmap)  
- 📦 **Bounding Box Generation** from thresholded matches  
- 🧹 **Non-Maximum Suppression (NMS)** to remove redundant overlapping boxes  
- 🖼️ **Visualization Utilities** to draw boxes on the original image  
- 🧪 Easy to extend for multiple templates or video frames

---

## 🧰 Tech Stack

- **Language:** Python 3.x  
- **Libraries:**
  - [OpenCV](https://opencv.org/) (`opencv-python`)
  - `numpy`
  - (Optional) `matplotlib` for visualization

---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   Computer-Vision_Template-Matching-with-NMS/
│
├─ src/
│  ├─ template_matching.py      # Template matching logic
│  ├─ nms.py                    # Non-Maximum Suppression implementation
│  ├─ utils.py                  # Helper functions (drawing boxes, IO, etc.)
│  └─ main.py                   # Entry point / demo script
│
├─ data/
│  ├─ images/                   # Input images
│  └─ templates/                # Template images
│
├─ output/
│  └─ results/                  # Result images with bounding boxes
│
├─ requirements.txt
└─ README.md

   git clone https://github.com/your-username/Computer-Vision_Template-Matching-with-NMS.git
   cd Computer-Vision_Template-Matching-with-NMS
