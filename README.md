# X-Ray Enhancement Pipeline

Takes a raw chest X-ray and runs it through a four-stage computer vision pipeline —
contrast enhancement, edge detection, and bone boundary overlay — entirely in Python.

## Pipeline Stages

1. Upload and load X-ray image (grayscale)
2. Pixel intensity analysis and histogram
3. CLAHE contrast enhancement
4. Canny edge detection
5. Bone highlighting with cyan overlay
6. Final comparison — all stages

## Tech Stack

- Python 3
- OpenCV
- scikit-image (CLAHE)
- Pillow
- NumPy
- Matplotlib

## Platform

Designed for Google Colab. Run directly in browser — no local setup required.

## Usage

1. Open `xray_enhancement_pipeline.ipynb` in Google Colab
2. Run cells sequentially
3. Upload your X-ray image when prompted
4. Download output files at the end

## Sample Output

The pipeline produces a side-by-side comparison of all four stages:

| Stage | Description |
|---|---|
| Original | Raw grayscale X-ray |
| CLAHE Enhanced | Local contrast improved |
| Canny Edges | Bone boundaries detected |
| Bone Overlay | Edges highlighted in cyan |