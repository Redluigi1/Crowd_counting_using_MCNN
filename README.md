
---

# MCNN Crowd Counting

This project implements the **Multi-Column Convolutional Neural Network (MCNN)** for crowd counting, as proposed in the research paper *"Single-Image Crowd Counting via Multi-Column Convolutional Neural Network"* — [IEEE Xplore PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780439).

##  Overview

The MCNN model addresses the challenge of varying crowd densities and perspective distortions in images. It uses **three parallel CNN branches** with different receptive fields to capture features at multiple scales. The outputs are combined to generate a **density map**, which is used to estimate the crowd count.

##  Model Details

* **Architecture:** Three-column CNN with varying kernel sizes.
* **Loss Function:** Mean Squared Error (MSE).
* **Optimizer:** Adam.
* **Evaluation Metrics:** MAE – 200.60, MSE – 349.70, Relative Error – 31%.

##  Dataset

The model is trained and evaluated on the **ShanghaiTech dataset** for crowd counting.

##  Reference

Zhang, Y., Zhou, D., Chen, S., Gao, S., & Ma, Y. (2016).
*Single-Image Crowd Counting via Multi-Column Convolutional Neural Network*.
IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016.

---


