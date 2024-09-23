# Predicting_The_PC_PayneLab
Methods for Predicting the protein corona using machine learning. Utilizes Nanoparticle features, interaction conditions, and protein properties calculated with biopython and NetsurfP. 

Running/Using this Code
This code is structured to be run on Google Colab (free version). The project is organized within a parent folder named after my last name ("Vijgen"), but you are free to rename this folder according to your preference.

Important: If you choose to rename the parent folder or any subdirectories, please ensure that you update the file paths in the code accordingly. This will allow the code to locate the necessary files without any issues.

For example:
If you rename the parent folder to something else, adjust all occurrences of the original folder name in the file paths throughout the code.
Make sure that any directories used in the code match the structure of your renamed folders.
By following these steps, you can ensure that the code runs smoothly in your environment.

*Instructions for Running the Code**
Upload Raw Mass Spectrometry Data:

Open the Proteomic_Data_Perseus_to_df.ipynb notebook in Google Colab.
Upload your raw mass spectrometry data (.txt files) within the notebook.
Follow the steps to convert the .txt file into a readable input format for further analysis.
Merge Relevant Data:

Open the Data_Consolidation.ipynb notebook in Google Colab.
Use this notebook to consolidate and merge all relevant data files.
Detailed instructions regarding the necessary input information can be found at the top of the Colab notebook.
Run the Prediction Models:

Depending on your analysis goal, you can choose to run one of the following notebooks:
RFC.ipynb: Use this notebook to predict categorical protein values using a Random Forest Classifier.
RFR.ipynb: Use this notebook to predict continuous protein values using a Random Forest Regressor.
Execute the notebook to generate predictions based on the processed data.
