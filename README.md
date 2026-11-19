# deepfake-detection-model
A machine learning project intended to detect AI-generated faces from image-level signals.

## deepfake image generation method
- Model: StyleGAN3-T, pretrained on FFHQ at 1024×1024 (NVIDIA)
- Truncation: 0.7
- Seeds: 0-2799
- Resized to 512×512 with Lanczos and saved as PNG
- The custom CUDA plugins were disabled and the plain-PyTorch versions used. The images are the same, it’s just slower.
