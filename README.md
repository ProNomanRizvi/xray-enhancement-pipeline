# X-Ray Enhancement Pipeline

A computer vision pipeline for medical X-ray image enhancement and bone structure detection.

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

## Output

- `highlighted_bones_output.png` — X-ray with detected bone edges highlighted in cyan
- `final_comparison.png` — Side-by-side comparison of all pipeline stages