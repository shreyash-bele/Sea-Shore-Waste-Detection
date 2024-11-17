# Sea Shore Waste Detection Using Image Processing

This project implements a pipeline for detecting waste along seashores using various image processing techniques, including K-means clustering, contour detection, texture analysis, and color segmentation. The implementation uses OpenCV, NumPy, and other libraries for image analysis and visualization.

---

## Features

1. **Segmentation using K-means Clustering**:
   - Segments the image into multiple clusters.
   - Binary masks are created for each segment to classify objects based on their properties.

2. **Morphological Operations**:
   - Refines binary masks using erosion and dilation to remove noise.

3. **Object Detection with Contours**:
   - Identifies and filters objects based on size, shape, and color.
   - Highlights detected waste areas with bounding boxes.

4. **Gabor Filter for Texture Analysis**:
   - Extracts texture features for corrosion or waste material detection.
   - Analyzes patterns for identifying specific waste features.

5. **Color Segmentation (HSV)**:
   - Uses hue, saturation, and value channels to mask specific colors.
   - Filters regions of interest based on transparency and color properties.

6. **Circle Detection with Hough Transform**:
   - Detects circular objects like bottles or cans within the image.

7. **Local Binary Patterns (LBP)**:
   - Captures texture details for additional feature analysis.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/sea-shore-waste-detection.git
   cd sea-shore-waste-detection
