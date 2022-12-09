# IC50 prediction model for individual drug
- This is the code repository for IC50 prediction model for individual drug

# Usage
- Jupyter notebook files of python coding for each setting are stored in Model_generation
- All the dataset and pre-defined models of each scenarios can be downloaded from [here (IC50_individual_drug/Datasets, IC50_individual_drug/Models)](https://mega.nz/folder/SXhXTKYK#T1skByytOWobMHa7Hv3j6A)
- You should download each dataset and change the path in each code (path for dataset, model_output_folder, result_output_folder, etc)
- Please set and check the file path (workdir) where dataset and training-test set split file located and for model and output file in each code.

# Code description
- *.ipynb : the jupyter notebook files (python 3) to construct prediction model and show validation result
- *.h5, *.json : these files are constructed model architecture and model weight from AI-method (CNN and ResNet)
- *.pkl : these files are constructed model from ML-method (linearSVR, random forest, XGBoost, etc)

# Computer specification
- All models were constructed under the computer specification below.
- Windows 10
- Python 3
- Keras 2.3.0
- tensorflow-gpu 1.14.0
- Geforce GTX 1080 Ti 11GB and Titan RTX 24GB
- RAM 64GB

# Contact
### If you have any questions, please contact below.
- Mr. Aron Park (parkar13@gmail.com)
- Prof. Seungyoon Nam (nams@gachon.ac.kr)
