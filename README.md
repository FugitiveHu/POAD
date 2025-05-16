# POAD
Open-World Panoptic Anomaly Detection via Visual-Language Alignment

# **Dual-Branch Multimodal Framework**

**FC-CLIP** (Vision-Language Alignment) + **GroundingDINO** (Open-Set Object Detection)

------

## 📌 Framework Overview

This repository contains two independent yet collaborative branches:

1. **`FC-CLIP` Branch**: A CLIP-based vision-language feature alignment model for image-text retrieval, classification, etc.
2. **`GS` Branch**: An open-set object detection model supporting text-prompted detection of arbitrary categories.

------

## 🚀 Quick Start

### **1. Environment Setup**

```
# Create Python environment (recommended 3.8+)
conda create -n POAD python=3.8 -y
conda activate POAD

# Install dependencies (each branch requires separate configuration)
git clone https://github.com/fugit0316/POAD.git
```

### **2. FC-CLIP Branch**

```
cd FC-CLIP
pip install -r requirements.txt  # Install FC-CLIP dependencies
# Further steps: see FC-CLIP/README.md
```

**Core Features**:

- Image-text similarity computation
- Zero-shot classification

### **3. GroundingDINO Branch**

```
cd GroundingDINO
pip install -r requirements.txt  # Install GroundingDINO dependencies
# Further steps: see GroundingDINO/README.md
```

**Core Features**:

- Detect objects in images via text prompts (e.g., `"cat, dog"`)
- Supports custom category detection
