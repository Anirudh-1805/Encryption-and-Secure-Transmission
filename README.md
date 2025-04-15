# 🔐 Encryption and Secure Transmission

This project demonstrates a complete pipeline for image encryption, secure transmission, and evaluation using Python. It employs chaos-based encryption (Arnold’s Cat Map), logistic map key generation, and evaluates encryption quality using metrics like SSIM, MSE, PSNR, and entropy. A simulated network flow graph is also used to represent secure transmission.

## 📁 Contents

- `preprocess_image`: Load and resize the grayscale image.
- `arnolds_cat_map`: Image scrambling using chaotic transformation.
- `generate_logistic_key`: Key generation using the Logistic Map.
- `xor_encrypt_decrypt`: Performs XOR-based encryption/decryption.
- `calculate_metrics`: Computes SSIM, PSNR, MSE between images.
- `simulate_network_flow`: Simulates max-flow for secure transmission.
- `visualize_graph`: Shows network graph with flow values.
- `hash_image`: Computes SHA256 hash to verify image integrity.

## 🚀 How to Run

1. Make sure you have all dependencies installed:
   ```bash
   pip install numpy opencv-python scikit-image networkx matplotlib
