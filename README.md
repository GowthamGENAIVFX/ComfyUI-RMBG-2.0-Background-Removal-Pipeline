# ComfyUI RMBG-2.0 Background Removal Pipeline

A production-oriented ComfyUI workflow designed for automatic background removal using RMBG-2.0.

This workflow demonstrates AI-powered foreground extraction and alpha mask generation for creating clean transparent PNG assets suitable for e-commerce, product photography, dataset preparation, compositing, and digital content creation.

---

## Project Overview

Background removal is a common production task across:

* E-commerce
* Product Photography
* Marketing
* VFX
* Dataset Preparation
* Asset Libraries

Traditional background removal requires manual masking and rotoscoping.

This workflow automates the process using RMBG-2.0.

---

## Architecture Diagram

![Architecture Diagram](images/Architecture_diagram.png)

---

## Workflow Graph

![Workflow](images/BG_removal_Workflow_01.png)
![Workflow](images/BG_removal_Workflow__bottle_02.png)
![Workflow](images/BG_removal_Workflow_seq_01.png)

---

## Sample Outputs

### Input Product

![Input](images/Input_01.png)
![Input](images/Input_02.png)
![Input](images/Input_03.png)
![Input](images/Input_04.png)
![Input](images/Input_05.png)
![Input](images/Input_06.png)
![Input](images/Input_game_items.png)



### Final Transparent PNG

![Final](images/output_01.png)
![Final](images/output_02.png)
![Final](images/output_03.png)
![Final](images/output_04.png)
![Final](images/output_05.png)
![Final](images/output_06.png)
![Final](images/output_07.png)
![Final](images/Bottle_full.png)
![Final](images/Bottle_cropped.png)
![Final](images/crown.png)
![Final](images/crown_cropped.png)

---

## Workflow Structure

Load Image

↓

RMBG-2.0 Segmentation

↓

Alpha Mask Generation

↓

Background Removal

↓

PNG Export

---

## Technical Stack

| Category           | Technology |
| ------------------ | ---------- |
| Workflow Engine    | ComfyUI    |
| Segmentation Model | RMBG-2.0   |
| Image Processing   | OpenCV     |
| Programming        | Python     |
| Export Format      | PNG Alpha  |
| Version Control    | Git        |

---

## Documentation

| Document                                            | Description                                 |
| --------------------------------------------------- | ------------------------------------------- |
| 📘 [Node Explanations](docs/node-explanations.md)   | Detailed explanation of workflow nodes      |
| 📗 [Optimization Notes](docs/optimization-notes.md) | Workflow testing and optimization decisions |

---

## Applications

* Product Photography
* E-Commerce
* Marketing Assets
* Dataset Creation
* Asset Libraries
* VFX Compositing
* Digital Advertising

---

## Learning Objectives

* Background Removal
* Alpha Mask Generation
* Semantic Segmentation
* Asset Preparation
* Production Automation

---

## Future Improvements

* Batch Processing
* SAM3 Integration
* Automatic Asset Cropping
* Multi-Object Segmentation
* Dataset Automation

---

## Author

Gowtham Subramanian

Generative AI Workflow Designer | Technical Artist | Senior Digital Compositor
