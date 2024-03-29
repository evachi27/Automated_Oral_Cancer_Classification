# Automated Classification of Oral Cancer Lesions: Vision Transformer vs Radiomics.
## Description
This repository accompanies the article entitled "Automated Classification of Oral Cancer Lesions: Vision Transformer vs Radiomics.". The project focuses on classifying cancerous oral lesions by comparing vision transformer (ViT) methods with a fully automated radiological approach. This involves the use of object detection and segmentation algorithms to effectively classifie oral lesions in cancer and control cases.

## Associated article
This paper is available at SSRN https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4772606 .

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

## Contributors
This project was developed by:
   - Yolanda Vives Gilabert
   - Joan Vila Francés
   - José V. Bagan
   - Eva Chilet Martos
     
We appreciate the collaboration and support of all the team members throughout the development process.

## References
If you found this code useful, please cite our paper:

'''
Chilet-Martos, Eva and Vila-Francés, Joan and Bagan, Jose V. and Vives-Gilabert, Yolanda, Automated Classification of Oral Cancer Lesions: Vision Transformers vs Radiomics. Available at SSRN: https://ssrn.com/abstract=4772606 or http://dx.doi.org/10.2139/ssrn.4772606
'''

