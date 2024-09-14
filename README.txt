
# Project Notebook Execution Guide

This project contains a series of Jupyter notebooks that are executed using Main.ipynb sequentially depending on the 'Run' value specified for each notebook in Main.xlsx. The file structure and sequence must be maintained as described below. 

## Code files Structure:
- pre_processing.ipynb
- pre_processing_evaluation_data.ipynb
- training_evaluation_without_personality.ipynb
- training_evaluation_personality.ipynb
- creation_of_model.ipynb
- Prototype_model.ipynb
- webscrapping.ipynb

## Execution Instructions:

1. Running the Main Function with All Codes:
   If you are executing the main function that calls all notebooks, only the Main.ipynb, Main.xlsx, Input folder, chromedriver is required. The main function will sequentially run the notebooks based on their 'Run' status.

2. Randomly running Notebook other than pre_processing.ipynb:
   If you wish to randomly run any file other than pre_processing.ipynb, file structure as shown in the gitlab is needed to ensure proper functioning, as dependencies between notebooks exist.

Please ensure the file structure remains as shown in the gitlab for smooth execution of the notebooks.

Additionally, a zip file named backup_files.zip is maintained to download the whole file structure with codes, input and outputs
