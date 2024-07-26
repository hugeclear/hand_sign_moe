# hand_sing_moe

# Sign Language Detection Project: MoE Approach

## 1. Project Overview

This project focuses on sign language detection using a Mixture of Experts (MoE) model. Our approach addresses two subtasks:

1. Gesture recognition
2. Handsign (fingerspelling) recognition

## 2. Rationale

### 2.1 Adoption of MoE
After consultation with our supervisor, we determined that using MoE to handle both gesture and handsign recognition tasks could lead to more effective sign language detection.

### 2.2 Video Classification Model
To capture the dynamic nature of sign language, we will implement a video classification model capable of effectively processing time-series data.

### 2.3 Task Clarification
By treating gestures (movements representing words or phrases) and handsigns (fingerspelling) as separate tasks, we believe each expert can specialize in their respective characteristics.

## 3. Implementation Plan

### 3.1 Framework
- PyTorch

### 3.2 Model Configuration
- **Backbone:** 3D CNN for video classification
- **MoE Layer:** Multiple experts specialized in gesture recognition and handsign recognition
- **Gating Network:** Selects appropriate experts based on input

### 3.3 Training Environment
- Lab GPUs (NVIDIA A100 80GB × 2)

## 4. Next Steps

1. Construction of a dataset including both gestures and handsigns
2. Detailed design of the model architecture incorporating MoE
3. Implementation in PyTorch and commencement of initial experiments

## 5. Contributing

[Contributing guidelines to be added]

## 6. License

[License information to be added]

## 7. Contact

[Contact information to be added]
