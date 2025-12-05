# ImageProcessingPlayground
A collection of super simple and beginner-friendly image processing examples using OpenCV and Matplotlib in Python. Perfect for learning, teaching, or quick experiments!

# SimpleImageProcessing

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

A growing collection of **very simple, clean, and well-commented** image processing scripts using OpenCV + NumPy + Matplotlib.

Ideal for:
- Beginners learning computer vision
- University assignments
- Quick prototyping & experiments

## Examples Included

| Script                     | What it does                                      |
|---------------------------|----------------------------------------------------|
| `red_channel_boost.py`    | Increases red channel by 50 and shows before/after |
| `green_blue_swap.py`      | Swaps green and blue channels                      |
| `grayscale.py`            | Converts image to grayscale (3 methods)            |
| `brightness_contrast.py` | Adjusts brightness & contrast                      |
| `negative.py`             | Creates negative image                             |
| `histogram_equalization.py` | Simple histogram equalization                   |
| `blur_examples.py`        | Gaussian, Median, and Bilateral blur               |
| `edge_detection.py`       | Canny edge detection (simple)                      |


## How to Run

```bash
# 1. Clone the repo
git clone https://github.com/your-username/SimpleImageProcessing.git
cd SimpleImageProcessing

# 2. (Recommended) Create virtual environment
python -m venv venv
source venv/bin/activate    # Linux/Mac
# or
venv\Scripts\activate       # Windows

# 3. Install requirements
pip install opencv-python numpy matplotlib

# 4. Run any example
python red_channel_boost.py
