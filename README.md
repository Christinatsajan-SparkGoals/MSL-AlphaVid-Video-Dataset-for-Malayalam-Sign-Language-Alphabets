# MSL-AlphaVid-Video-Dataset
MSL-AlphaVid is the first video-based Malayalam Sign Language (MSL) alphabet dataset with 15 classes and 72 videos each, recorded from six signers under varied conditions. It supports 3D CNN and Transformer models, advancing video-based MSL recognition and accessibility for the Malayalam Deaf community.

# 📘 MSL-AlphaVid Dataset Details

## 1. Introduction

The **Malayalam Sign Language (MSL)** alphabet was standardized in **September 2021**, marking a major step toward linguistic inclusion for Kerala’s Deaf community. However, publicly available datasets remain scarce, with most being **image-based** and lacking temporal motion information crucial for real-world sign recognition.

To address this gap, we introduce **MSL-AlphaVid**, the **first video-based dataset** for MSL alphabet recognition. The dataset comprises **15 classes**, each containing **72 video instances**, recorded from **six different signers** under **varied backgrounds and lighting conditions** to ensure diversity and robustness.  

This variation enhances the dataset’s ability to support model training and evaluation for real-world scenarios. MSL-AlphaVid serves as a **benchmark dataset** for sign language research, enabling the development of **3D CNN** and **Transformer-based** models for video-based recognition. By providing a structured, high-quality dataset, MSL-AlphaVid aims to promote deep learning research and accessibility for Malayalam-speaking Deaf communities.

---

## 2. Dataset Composition

- **Total Classes:** 15 (Malayalam alphabet letters)  
- **Videos per Class:** 72  
- **Total Videos:** 1,080  
- **Signers:** 6 individuals  
- **Average Duration:** 2–4 seconds per video  
- **Resolution:** 1920 × 1080 (Full HD)  
- **Frame Rate:** 30 FPS  
- **Format:** `.mp4`  
- **Environment:** Varied lighting and backgrounds  

Each folder represents a specific Malayalam alphabet sign, containing 72 instances of that gesture performed by different signers.


---

## 3. Tools Used for Dataset Creation

To record the dataset, a combination of **software tools** and **devices** was employed:

- **OBS Studio** – Open-source screen recording and streaming tool used for stable indoor recordings with webcams.  
- **Mobile Cameras** – Used for flexible, natural lighting and variable camera angles.  

This hybrid setup enabled both **controlled** and **semi-controlled** environments, contributing to the dataset’s **visual diversity** and **authenticity**.

All videos were standardized with consistent file naming conventions indicating the **class label**, **signer ID**, and **instance number**. Each clip was reviewed to ensure gesture correctness, clarity, and accurate labeling. Ambiguous or noisy samples were re-recorded or removed, resulting in a **clean and balanced dataset**.

The dataset is ideal for:
- 3D CNNs  
- Spatio-Temporal Transformers  
- Pose estimation and gesture segmentation  
- Continuous sign language recognition experiments

---

## 4. Challenges During Dataset Creation

Building MSL-AlphaVid presented several challenges:

- **Signer Coordination:** Maintaining consistency across six signers while preserving natural variations.  
- **Lighting & Background:** Recording in diverse lighting led to issues like shadows and overexposure.  
- **Device Variation:** Using both webcams and mobile cameras caused differences in frame rate and angle, requiring careful standardization.  
- **Environmental Noise:** Maintaining quiet, distraction-free environments during recording was difficult.  
- **Technical Issues:** Occasional camera glitches, framing errors, and background noise required re-shooting certain samples.

Despite these difficulties, the dataset achieved strong consistency and clarity across all classes.

---

## 5. Limitations

While MSL-AlphaVid significantly advances MSL research, it still has some limitations:

1. **Partial Alphabet Coverage:** Currently includes 15 alphabet classes, not the full MSL vocabulary.  
2. **Limited Signer Pool:** Six signers offer diversity but may not capture full variation across the community.  
3. **Isolated Gestures Only:** The dataset focuses on single alphabet gestures, not continuous signing sequences.  
4. **Controlled Environments:** Most recordings are indoors with limited real-world background complexity.

Future extensions will focus on:
- Expanding signer diversity  
- Incorporating continuous sign streams  
- Capturing in outdoor or dynamic environments  
- Increasing gesture variety and dataset scale  

---

## 6. Conclusion

The **MSL-AlphaVid** video dataset represents a **foundational step** in advancing Malayalam Sign Language recognition. By providing **high-quality, well-structured, and diverse** video data, it bridges the gap between isolated gesture datasets and real-time recognition systems.  
This dataset contributes to the broader field of **regional sign language processing** and supports the development of **inclusive AI-driven communication technologies** for the Malayalam-speaking Deaf community.

---

## 7. Special Thanks 💐

The success of the MSL-AlphaVid dataset would not have been possible without the dedication and collaboration of the six volunteer signers who contributed their time and effort to record high-quality gesture videos.

**Signers:**  
- Sandhra Merin Sabu  
- Ashwathi C  
- Christina Thankam Sajan
- Dr. Hephzibha S Mathew
- Arya Anilkumar  
- Helanmary M Sunny  

Your contributions were vital in bringing this dataset to life and promoting inclusivity in regional sign language research. Thank you for being an integral part of this initiative.

---

*Author:* **Christina Thankam Sajan**  
*Guided by*: **Dr. Anju Pratap**
*Institution:* Saintgits College of Engineering, Kottayam, Kerala, India  
*Year:* 2025  

