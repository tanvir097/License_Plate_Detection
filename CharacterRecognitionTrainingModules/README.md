## Scala - Myanmar Number Plate Recognition System 

Developed by AI,NLP & Blockchain Dept., eGeneration PLC.,Bangladesh - Last Updated: 3.11.2021
	
	
## Tools and Libraries:

     -Python 3.7
	 |
     -Numpy 1.17.4
	 |
     -Matplotlib 3.2.1
	 |
     -OpenCV 4.1.0
	 |
	 -Keras 2.3.1
	 |
	 -Tensorflow 1.14.0
	 |
	 -sklearn==0.21.3


## Project Directory Tree:

	--root
		|
		--- dataset_characters [ Containas All The Character Image Data Separated by Different Folder Names ]
		|
		--- character_recognition_model_training_script.py [ Main Training Program File ]
		|
		--- environment.yml [ Exported Environmenty yml File ]
		|
		--- license_character_classes.npy [ Contains All Respective Labels ]
		|
		--- License_character_recognition.h5 [ Contains Weight Of The Layers ]
		|
		--- MobileNets_character_recognition.json [ COntains The Model Architecture ]
		| 
		--- ReadMe.md  [ Instruction File ]
		| 
		--- requirements.txt [ List of Dependency Library text file ]
	

## Environment Setup

| Type | Process |

|-----------|-------------|

| conda | • Install anaconda or miniconda on your system<br/> • Run the below command in cmd. It will create SLPD conda environment<br/> • **conda env create -f environment.yml** |

| pip | • Install anaconda or miniconda or python on your system<br/> • run the below command in cmd for anaconda or miniconda<br/> • **conda create -n SLPD python=3.7**<br/> • You can also setup core python environment<br/> • After that run the following command<br/> • **pip install -r requirements.txt** |
	
   
## Workflow

After environment setup you can follow this process from cmd<br/>

• Place the Character input images folders in the **dataset_characters** directory where each of the specific character images should be placed in different folders where the folder name should resemble the respective label of the character images.<br/>

• Run **conda activate SLPD** to activate the virtual environment<br/>

• Open **Jupiter Notebook** IDE<br/>

• Go to *CharacterRecognitionTrainingModules* directory [ ex: cd CharacterRecognitionTrainingModules ]<br/> 

• Open *character_recognition_model_training_script.ipynb* file<br/> 

• Run All Cells and wait for the training epoch to finish.<br/>

• After finishing the training collect the trained model weight [ License_character_recognition.h5 ],class [ license_character_classes.npy ],and architecture [ MobileNets_character_recognition.json ] file from the running directory of the program.<br/>









