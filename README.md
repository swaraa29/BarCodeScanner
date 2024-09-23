# Multiple Bar Code Scanner

This project is a **Multiple Bar Code Scanner** that decodes barcodes from a live camera feed using various image processing techniques. The scanner is optimized for real-time performance, making it efficient for a wide range of applications.

## Key Features
- **Real-time barcode scanning** from a live camera feed.
- Utilizes **multiple image processing techniques** including:
  - Low Pass Filtering
  - High Pass Filtering
  - Grayscale Conversion
  - Original Image Comparison
- These techniques enhance the scanner’s efficiency in decoding barcodes in challenging environments, ensuring robust performance in real-time applications.
  
## Applications
- Inventory management systems
- Point-of-sale terminals
- Warehouse automation
- Asset tracking
- Retail and logistics

## Technologies Used
- **OpenCV** for image processing and video capture.
- **Python** for implementation and logic handling.
- **NumPy** for efficient mathematical operations.

## How it Works
1. The live camera feed is captured using OpenCV.
2. Each frame undergoes multiple image processing techniques:
   - **Low Pass Filtering** to reduce noise.
   - **High Pass Filtering** to enhance edges and fine details.
   - **Grayscale Conversion** for simplified processing.
   - **Original Image** is also analyzed to compare and improve barcode detection accuracy.
3. The processed images are analyzed to detect and decode barcodes in real-time.
   
## Getting Started
### Prerequisites
- Python 3.x
- OpenCV library
- NumPy library

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/multiple-bar-code-scanner.git
   cd multiple-bar-code-scanner
