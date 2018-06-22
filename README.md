# Machine Learning Engineer Nanodegree
## Capstone Project


### Project Description

Much recent interest has been garnered in the application of AI in healthcare, particularly in the diagnosis of diseases. Lung conditions, a category that includes both communicable and non-infectious diseases have remained the second leading cause of death globally in the last 15 years, just after heart disease, according to the World Health Organization.

Despite the critical need for early screening and detection, it is estimated that two-thirds of countries do not have sufficient access to basic radiology services, such as a simple x-ray or ultrasounds. Additionally, a lack of access to well-trained radiologists could delay diagnosis and the prevention and identification of deadly lung diseases. 

As the culmination of the Machine Learning Engineer Nanodegree, my capstone project addresses the need for software that can 1) distinguish between normal and abnormal x-ray images, and 2) perform “diagnosis”, which in the case of radiological evidence usually entails implicating several possible pulmonary conditions of roughly equal probability. 


### Install

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [PyTorch](https://pytorch.org/)

Please note that Jupiter Notebook [Jupyter Notebook](http://ipython.org/notebook.html) is needed.

To install Python, you can install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. However, the Python 3.x installer should be selected and not the Python 2.7 installer.

### Code

The main code for this project will be located in the `Udacity_Capstone_Project.ipynb` notebook file. Additional supporting code for visualizing the necessary graphs will be found in `visuals.py`. Finally, the "Report.html" file contains a snapshot of the main code in the jupyter notebook with all code cells executed. A detailed write-up of the project overview, evaluation metrics, methodology, data exploration, and analysis will be included in `Final Capstone Project.pdf`. 

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Udacity_Capstone_Project.ipynb
```  
or
```bash
jupyter notebook Udacity_Capstone_Project.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

This dataset is a modified version of the original dataset, which consists of 5,232 chest X-ray images taken from 5,856 pediatric patients, 1 to 5 years old, from the Gaungzhou Women’s and Children’s Hospital. Academic physicians have classified 3,883 of these as depicting pneumonia, within which 2,538 bacterial and 1,345 viral pneumonia cases, and 1,349 images as normal. The dataset is publicly available and was used in a published study. The images are of varying sizes and are grayscale. The

The original dataset can be found on the [NIH site via Box](https://nihcc.app.box.com/v/ChestXray-NIHCC).

