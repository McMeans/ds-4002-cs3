# Distracted Driver Case Study

This project classifies 10 breeds of dogs and cats using deep learning and transfer learning. It uses the Distracted Driving Dataset and applies a fine-tuned ResNet-50 model for high-accuracy breed identification.

## Context

Before beginning, please read review the following files:
- [`CS3Hook.pdf`](https://github.com/McMeans/ds-4002-cs3/blob/main/CS3Hook.pdf): One-page overview of the project
- [`CS3Rubric.pdf`](https://github.com/McMeans/ds-4002-cs3/CS3Rubric.pdf): Submission guidelines and evaluation rubric


## Remaining Documentation

### `/supplements` folder
Contains references contextualizing the project motivation:
- [`ML_Techniques_Distracted_Driving.pdf`](https://github.com/McMeans/ds-4002-cs3/blob/main/supplements/ML_Techniques_Distracted_Driving.pdf): Academic article covering ML in Distracted Driving 
- [`NHTSA_Distracted_Driving.pdf`](https://github.com/McMeans/ds-4002-cs3/blob/main/supplements/NHTSA_Distracted_Driving.pdf): Beginner-friendly article covering the dangers and stastics regardign Distracted Driving

### `scripts` folder
- [`code.ipynb`](https://github.com/McMeans/ds-4002-cs3/blob/main/scripts/code.ipynb): Notebook for data processing, model training, and evaluation

### Data
- [`data.zip`](https://github.com/McMeans/ds-4002-cs3/blob/main/data.zip): Zipped dataset utilized by the notebook


## Producing Results

The notebook should be compatible both locally (VS Code or other IDE of choice) and for Google Colab. 

**On your Local Machine/IDE**
- Clone the repository in the file destination of your choice
    - `git clone https://github.com/McMeans/ds-4002-cs3.git`
- Navigate to `scripts/code.ipynb` and run all cells
    - All data is processed inside this file. You may prematurely unzip the data file if you choose, but it is not required.
    - Edit the `EPOCHS` variable as desired to change model strength. Please be aware this will take time as you increase the value.

**Google Colab**
- Navigate to Google Colab and choose 'Open Notebook'
- On the GitHub tab, paste the repository URL
- Select `scripts/code.ipynb` and run all cells
   - All data is processed inside this file. You may prematurely unzip the data file if you choose, but it is not required.
    - Edit the `EPOCHS` variable as desired to change model strength. Please be aware this will take time as you increase the value.