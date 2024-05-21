# Microscopic-Image-Recognition-for-Malaria-Detection

## Task Description
Using images from the National Library of Medicine database for Malaria-infected cells, we will train a Convolutional Neural Network Model on to identify whether they are infected or not.

## Notebook Sections
### 1. Loading, Visualising and Processing the Data
### 4. Building, Training, Testing and Evaluating a Model for this Data
### 5. Train and Evaluate the Model
### 6. Test the Model
## Background: Why is this Project Useful
* Globally in 2022, there were an estimated 249 million malaria cases and 608 000 malaria deaths in 85 countries.
* The WHO African Region carries a disproportionately high share of the global malaria burden.
* In 2022, the Region was home to 94% of malaria cases (233 million) and 95% (580,000) of malaria deaths.
* Children under 5 accounted for about 80% of all malaria deaths in the Region. Source: [WHO](https://www.who.int/news-room/fact-sheets/detail/malaria).
* Malaria infections occur when mosquito bites allow for the bacterium Plasmodium falciparum into the bood system.
* Haematological testing to diagnose malaria involve a creating a thin blooad smear on microscope slides.
 ![alt text](https://microbenotes.com/wp-content/uploads/2020/02/Thick-Blood-Smear-and-Thin-Blood-Smear.jpg)

   Image Source: Haematology in a NutShell, Microbiology Info, and DOI: 10.5336/caserep.2015-47850
### The Cell Image Database
* The database that we will be working with is from the National Library of Medicine, and can be found [here](https://lhncbc.nlm.nih.gov/LHC-research/LHC-projects/image-processing/malaria-datasheet.html).
* The microscope images have been segmented to yield images of individual cells.
* The dataset contains a total of 27,558 cell images.
* The database constains an equal amount of infected and healthy cells, labelled as 'Parasitized' and 'Uninfected', respectively.
### The Approach
* This will be a binary classification problem.

# Acknowledgements
The author would like to thank the creators of the database:
Rajaraman, S., Antani, S. K., Poostchi, M., Silamut, K., Hossain, M. A., Maude, R. J., ... & Thoma, G. R. (2018). Pre-trained convolutional neural networks as feature extractors toward improved malaria parasite detection in thin blood smear images. PeerJ, 6, e4568.
