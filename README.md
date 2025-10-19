# Region Filling and Object Removal by Inpainting

This project implements the **Exemplar-Based Image Inpainting** algorithm proposed by Criminisi et al. (2004) for region filling and object removal in digital images. The work was completed as part of an **Image Processing coursework** project. Please refer to this [report](https://github.com/sing1174/Inpainting_large_object_removal/blob/main/Object_removal_by_inpainting_Manpreet_Singh.pdf) for an overview of the project.

---

## Overview

The algorithm removes unwanted objects from images and reconstructs the background by combining the strengths of texture synthesis and inpainting. It prioritizes filling based on structural continuity and texture similarity to achieve visually coherent results.

**Key features:**
- Propagates linear structures (isophotes) into missing regions  
- Uses exemplar-based patch synthesis for realistic texture filling  
- Computes patch priorities using confidence and data terms  
- Handles large missing areas efficiently

---

## How to Run

Modify the image and mask paths in the notebook if using custom data.
All the functions used are present in the Inpainting_code.ipynb file. The images and masks used are all present in main folder for ease of access. You can simply run the .ipynb file to check the results.

Reference
Criminisi, A., Pérez, P., & Toyama, K. (2004). Region Filling and Object Removal by Exemplar-Based Image Inpainting.
IEEE Transactions on Image Processing, 13(9), 1200–1212.
DOI: 10.1109/TIP.2004.833105
