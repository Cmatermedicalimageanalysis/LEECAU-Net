# **LEECAU-Net: A Latent Entropy-quantized and Efficient Channel Attention-aided U-Net Model for Microscopic Medical Image Segmentation**

This is the official GitHub repository corresponding to the research paper entitled **LEECAU-Net: A Latent Entropy-quantized and Efficient Channel Attention-aided U-Net Model for Microscopic Medical Image Segmentation**.

The research work has been accepted at the **2024 International Conference on Progress in Informatics and Computing (PIC-2024)**. It has been awarded the **Best Paper** at the conference held from **20th to 22nd December 2024 in China**, sponsored by the IEEE Beijing Section, and co-organized by the Shanghai University of Finance and Economics, Shanghai University, and Shanghai Computer Society (SCS).

---

## **Abstract**

Microscopic medical image segmentation is essential for detailed cellular-level analysis in computational pathology, offering insights into disease mechanisms. However, this task is particularly challenging due to the high similarity between different cellular classes and variability within each class, especially in densely packed or overlapping cell regions.

To this end, we present **LEECAU-Net** (Latent Entropy-quantized and Efficient Channel Attention-aided U-Net), a U-Net-based model designed to improve segmentation accuracy through a dual-attention mechanism. Built on an Inceptionv4 backbone, LEECAU-Net’s encoder integrates **Latent Entropy-quantized Channel Attention (LECA)** and **Efficient Channel Attention (ECA)** modules. The ECA module enhances the network’s ability to focus on essential channel dependencies, while LECA leverages entropy quantification to prioritize channels rich in information, leading to better differentiation between similar structures.

We have tested LEECAU-Net on three challenging publicly available datasets: **Triple Negative Breast Cancer (TNBC)**, **Multi-organ Nuclei Segmentation (MoNuSeg)**, and **Cervical Nucleus Segmentation (CNS)**. Across these datasets, our model achieves higher performance metrics than numerous state-of-the-art approaches reported in the literature. The improved results underscore the effectiveness of LEECAU-Net’s architecture in handling the complexity of microscopic medical images, making it a valuable tool for advancing automated cellular analysis in biomedical research.

The attachment below shows the detailed architecture of the proposed methodology.

![LEECAU-Net Architecture](https://github.com/user-attachments/assets/72c14849-daa1-4b4a-9722-2a65b312c149)


## **Authors**

- [Sanchita Das](https://www.linkedin.com/in/sanchita-das-8734611b1)  
- [Gouranga Maity](https://www.linkedin.com/in/gouranga-maity-ba3869131)  
- [Diptarka Mandal](https://www.linkedin.com/in/diptarkamlds)  
- [Dmitrii Kaplun](https://www.linkedin.com/in/dmitrii-kaplun-7971b085)  
- [Alexander Voznesensky](https://www.linkedin.com/in/a-voznesensky)  
- [Ram Sarkar](https://www.linkedin.com/in/ram-sarkar-51414a230)


## **Citation**

Please do cite our paper in case you find it useful for your research.

```bibtex
@inproceedings{das2024leecau,
  title={LEECAU-Net: A Latent Entropy-Quantized and Efficient Channel Attention-Aided U-Net Model for Microscopic Medical Image Segmentation},
  author={Das, Sanchita and Maity, Gouranga and Mandal, Diptarka and Kaplun, Dmitrii and Voznesensky, Alexander and Sarkar, Ram},
  booktitle={2024 IEEE International Conference on Progress in Informatics and Computing (PIC)},
  pages={259--267},
  year={2024},
  organization={IEEE}
}

## **DOI**

🔗 [https://doi.org/10.1109/PIC62406.2024.10892671](https://doi.org/10.1109/PIC62406.2024.10892671)
