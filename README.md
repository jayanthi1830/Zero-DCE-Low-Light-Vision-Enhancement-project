

#  Zero-DCE: Low Light Vision Enhancement

This project implements the **Zero-DCE (Zero-Reference Deep Curve Estimation)** model for enhancing images captured in **low-light conditions**, using deep learning. The model learns image-specific enhancement curves without the need for paired training data.

---

## 🔍 Problem Statement

Low-light images suffer from poor visibility, low contrast, and noise — making it difficult for human viewing and downstream computer vision tasks. The goal of this project is to apply a deep learning model (Zero-DCE) to enhance such images **without any reference image**.

---

## 🧠 What is Zero-DCE?

**Zero-DCE (CVPR 2020)** is a lightweight deep curve estimation model that:
- Does **not require paired datasets** (i.e., no need for original and enhanced image pairs)
- Learns **image enhancement curves** using a CNN
- Optimizes for exposure, contrast, color consistency, and spatial smoothness

📄 Paper: [Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement](https://openaccess.thecvf.com/content_CVPR_2020/papers/Guo_Zero-Reference_Deep_Curve_Estimation_for_Low-Light_Image_Enhancement_CVPR_2020_paper.pdf)

---

## 🛠️ Tools & Technologies Used

| Tool/Library      | Purpose                        |
|-------------------|-------------------------------|
| Python            | Core programming language     |
| TensorFlow / Keras| Deep learning framework       |
| OpenCV            | Image loading & preprocessing |
| NumPy             | Numerical operations          |
| Matplotlib        | Visualization of results      |

---

## References

Guo et al. “Zero-Reference Deep Curve Estimation for Low-Light Image Enhancement” – CVPR 2020

Original GitHub repo: https://github.com/Li-Chongyi/Zero-DCE


