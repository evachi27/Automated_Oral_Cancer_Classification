# Automated Classification of Oral Cancer Lesions: Vision Transformer vs Radiomics.
## Description
This repository accompanies the article entitled "Automated Classification of Oral Cancer Lesions: Vision Transformer vs Radiomics.". The project focuses on classifying cancerous oral lesions by comparing vision transformer (ViT) methods with a fully automated radiological approach. This involves the use of object detection and segmentation algorithms to effectively classifie oral lesions in cancer and control cases.

## Content of the repository
### Notebooks
The logical and functional order of the project is as follows:

1. **Reorganization and preprocesing (`reestructuracion.ipynb`):**
   - This file will allow us to obtain the directories with anonymized images, separated for each set and augmented. 
   - It will also generate the annotation files needed for later deep learning models. 
   Explained in more detail in the ipynb.

2. **Detection (`deteccion.ipynb`):**
   - Prediction of bounding boxes associated with the injury region using DERT, a transformer-based detection model

3. **Segmentation (`segmentacion.ipynb`):**
   - Prediction of associated masks injuries using SAM, segmentation model based on transformers.

4. **Classification with ViT Models(`clasificacion_vit.ipynb`):**
   - Use of Vision Transformer (ViT) for classification and it's analysis
   - Extraction of attention maps to obtain masks.

5. **Classification by Radiomics (`clasificacion_radiomica.ipynb`):**
   - Application of radiomic techniques for classification.

### Database
This repository does not include the database used due to its character and usage restrictions. More information can be found in the associated article.

