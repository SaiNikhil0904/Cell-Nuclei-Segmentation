# Cell Nuclei Segmentation

## Project Overview
Welcome to the Cell Nuclei Segmentation project! Our mission is to revolutionize biomedical research by automating nucleus detection, a fundamental step in understanding cellular dynamics and advancing drug discovery. By leveraging the powerful UNet architecture, our project accelerates the identification of cell nuclei, reducing the time required for critical biomedical analysis.

## Purpose
Biomedical research, particularly in diseases like lung cancer, heart disease, Alzheimer's, and diabetes, often involves time-consuming manual analysis. Our project addresses this challenge by automating nucleus detection, a critical step in understanding cellular dynamics. The primary purpose is to accelerate the research process, leading to faster discoveries and advancements in drug development.

## Project Impact
Beyond individual diseases, our project offers a transformative tool for biomedical researchers. By expediting nucleus detection, we streamline drug testing processes, potentially compressing the timeline for drug development. The project aims to contribute to advancements in understanding diseases and facilitating the development of novel treatments.

## Key Features
- **UNet Architecture:** We employ the potent UNet architecture for precise cell nucleus segmentation, known for its success in semantic segmentation tasks.
- **Dataset:** Trained on the diverse dataset from the [2018 Data Science Bowl competition](https://www.kaggle.com/datasets/84613660e1f97d3b23a89deb1ae6199a0c795ec1f31e2934527a7f7aad7d8c37), our model is robust and adaptable to various experimental conditions.
- **Pre-Processing:** Our approach includes boundary extraction and region filling for enhanced accuracy in cell nucleus segmentation.
- **Model Architecture:** The UNet model consists of 35 Conv2D layers, providing a sophisticated neural network for image segmentation.

## Requirements

To run this project, ensure you have the following Python libraries installed:
- pandas, numpy, matplotlib, Keras, scikit-learn, tensorflow.

You can install the required libraries using the following command:

```bash
pip install pandas numpy matplotlib keras scikit-learn tensorflow
```
- Google Colab/Jupiter Notebook

## Team
- Aayush Dubey
- Anish Borkar
- Godavarthi Sai Nikhil

## Mentor
We express our sincere gratitude to **Dr. Devanjali Relan**, who provided invaluable supervision during this project. 

## Explore the Work
Feel free to delve into our codebase, datasets, and model architecture. Your engagement and feedback are invaluable as we continue refining and expanding our project.

## Output Images
Sample output image combining original, ground truth/mask, and generated images:

![0e4c2e2780de7ec4312f0efcd86b07c3738d21df30bb4643659962b4da5505a3](https://github.com/SaiNikhil0904/Cell-Nuclei-Segmentation/assets/98106917/2d86c4c1-5b43-4324-a565-31f8a1f3c8a3)


1. **Original Image:** The original microscopy image.
2. **Ground Truth/Mask:** The annotated ground truth or mask indicating the actual cell nuclei positions.
3. **Generated Image:** The output of our segmentation model, highlighting the detected cell nuclei.

## Contact Us
For inquiries, collaboration opportunities, or further information, please feel free to reach out to:

- **Email:** [nikhilgodavarthi9@gmail.com](mailto:nikhilgodavarthi9@gmail.com)

Thank you for joining us on this transformative journey in biomedical research!
