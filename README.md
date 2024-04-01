
# Deep Insights into Gastrointestinal Health

Explore our repository to discover the latest research in gastrointestinal health and AI. We're using advanced technology to improve how we detect and treat digestive diseases. Our repository contains a special model we've created using deep learning. It helps make diagnosing gastrointestinal conditions more accurate and reliable. We've also collected datasets and developed smart techniques to handle data imbalances. By using explainable AI methods, we're making our models easier to understand. Whether you're a researcher, doctor, or just interested in AI, our repository has plenty of resources to help advance gastrointestinal health research.

## Installation

 By following these simple steps, you'll be equipped to delve into the depths of digestive health and harness the power of deep learning to revolutionize disease detection and treatment.

**Step 1: Clone the Repository**
To get started, clone our repository to your local machine using the following command: 

git clone git@github.com:fahad-git/deep-insights-into-gi-health.git

**Step 2: Navigate to the Repository Directory**
Once the repository is cloned, navigate to the directory containing the repository on your local machine using the cd command:

cd deep-insights-into-gi-health


**Step 3: Install Dependencies**
With the repository directory as your current working directory, install all the required dependencies by running the following command:

pip install -r requirements.txt

**Step 4: Verify Installation**
After executing the installation command, verify that all dependencies were successfully installed without any errors. You can do this by checking for any error messages displayed in the terminal.

## Usage
**Data Augmentation**
1. Open the "Data Augmentation.ipynb" notebook located in the repository.

2. Modify the directory path within the notebook to point to your dataset.

3. Execute the code within the notebook to perform data augmentation.

### Downloading Pre-trained Model Weights

You can download the pre-trained model weights from the following link:

[Download Model Weights](https://drive.google.com/file/d/1w1cfpsDNhwZXAAggbLGqbdGQRDi-ECKa/view?usp=drive_link)

After downloading, place the weights in the appropriate directory as instructed in the model training notebooks.

**DenseNet-121 Model Training**
1. Open the "DenseNet-121.ipynb" notebook located in the repository.

2. Follow the instructions within the notebook to train the DenseNet-121 model.

**Proposed Model**
1. Open the "DenseNet + Greedy Soup.ipynb" notebook located in the repository.

2. Pass appropriate model paths and dataset path as required.

3. Execute the notebook to run the proposed model.

**Explainability**
1. Open the "SHAP Visualization.ipynb" and "GradCAM Visualization.ipynb" notebooks located in the repository.

2. Follow the instructions within the notebooks to visualize SHAP and GradCAM explanations respectively.

**Testing and Validation**
1. Utilize the "Test.py" and "Validate.py" module files located in the repository for testing and validating the models respectively.

2. Additionally, the "mics.py" module file contains code for generating results.

## License

MIT License

Copyright (c) 2024 Muhammad Fahad

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Acknowledgments

We would like to express our sincere appreciation to the following individuals for their valuable contributions and support in the development of this project:

**Noor E Mobeen:** Conceptualization, methodology, data collection, original draft preparation, writing, review, and editing. 
**Ali Shariq Imran:** Review and editing, supervision. 
**Sher Muhammad Daudpota:** Review and editing. 
**Zenun Kastrati:** Review and editing. 
**Faouzi Alaya Cheikh:** Review and editing. 
**Mohib Ullah:** Review and editing, supervision.
**Subhan Ali:** Suggesting dataset

We would also like to thank the open-source community and the creators of the libraries, frameworks, and tools that have made this project possible.
