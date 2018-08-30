# MLECapstone

INTRO
-----
My Machine learning engineer capstone project

The project proposal can be found in Capstone Project Proposal.docx

My final writw up can be found in the pdf Capstone Project.pdf

DATA
----
Raw image data for the project can be downloaded from the ISIC archive at www.isic-archive.com

Unfortunatly because it has taken 6 months to complete my project due to having to put it on hold to take on child care for 5 months, the gallery on the site has been updated and it is no longer possible to filter images that are tagged for the 2017 ISIC challenge. 

The serialized preprocessed images take up approximately 2Gb space and can be provided if required.

Software requirements
---------------------
Software requirements to create an environment to run the code can be found in /requirements. Please use   the correct file for your os.

Code
-----
The code for the project is split between the 4 notebooks:

* Capstone_wrangling_and_Xception.ipynb - this details intial loading of data and wrangling into a usable format + the training of the Xception initial and fine tuned classifier

* Capstone_inception.ipynb - this details the training and fine tuning of a InceptionV3 based classifier

* Capstone_resNet.ipynb - this details the training of a ResNet50 based classifier

* Capstone_ensemble.ipynb - this details the wrangling of data from the output of each of the CNN classifiers and training of ensembles, plus the creation of a ROC curve to access the performance of classifiers

