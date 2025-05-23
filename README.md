

**🖼️ Image Compression using JPEG and Wavelet-Based Techniques | Python & Digital Signal Processing**
This project implements and compares two powerful image compression techniques—JPEG (DCT-based) and Wavelet-based Compression—using Python and Digital Signal Processing (DSP) principles. It aims to reduce image size while preserving perceptual quality, demonstrating how modern compression algorithms balance fidelity and efficiency.

**🔍 Key Features**
JPEG Compression using Discrete Cosine Transform (DCT)
Wavelet-Based Compression using Discrete Wavelet Transform (DWT)
Image reconstruction and quality evaluation (PSNR, MSE, Compression Ratio)
Side-by-side visualization of original vs. compressed images
Modular and easy-to-understand Python implementation

**🛠️ Tech Stack**
Python (NumPy, OpenCV, PyWavelets, Matplotlib)
Digital Signal Processing (DSP) concepts applied for transform coding
Image Quality Metrics: PSNR, MSE, Compression Ratio

**⚙️ Algorithms Implemented**

**JPEG Compression:**
Convert to YCrCb color space
Block-wise DCT transformation (8×8)
Quantization and entropy coding

**Wavelet Compression:**
Multi-level DWT decomposition (Haar, Daubechies)
Thresholding and coefficient quantization
Image reconstruction from compressed coefficients

**🚀 How to Run**
Clone the repository
Install dependencies via requirements.txt
Run jpeg_compression.py for DCT-based compression
Run wavelet_compression.py for wavelet-based compression
Explore comparison.ipynb to visualize and compare results

**📊 Results**
Significant reduction in image size with high visual quality retention
Wavelet compression shows better performance at lower bitrates
Quantitative analysis using PSNR and compression ratio plots

**📌 Applications**

Image storage and transmission optimization
Multimedia systems and digital photography
Real-time video and image streaming systems
