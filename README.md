# 2020cp_COVID_19_chest_X_Ray_detection

### Groups
* < Lai Yen-Ru, 賴彥儒, 105701027 >
* < Lin Yu-Han, 林煜翰, 105701037 >
* < Huang Chen-Tang, 黃乾塘, 105701004 >
* < 黃郁軒, 106703049 >

### Abstract 

Since the vaccine of COVID-19 is still under development, we can’t let our guards down in the mean time. However, one huge obstacle we are facing now is the shortage of COVID-19 testing kits. Moreover, it takes hours, even weeks, to receive the results. This is where deep convolution neural network comes into mind. With more and more COVID-19 patients contributing their chest X-ray images to open source radiology organizations all over the world including: Radiopaedia, SIRM, Eurorad etc., we can utilize these data to build a CNN model identifying the COVID-19 patients.

### Objective 

Creating a CNN model that can distinguish between normal peoples chest X-ray, people with general pneumonias chest X-ray and COVID-19 patients’ chest X-ray.

### Datasets

* Kaggle : Chest X-Ray Images (Pneumonia)
(https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
This is a Kaggle dataset that contains normal and general pneumonia chest X-ray images. 

* COVID chest X-ray Dataset
(https://github.com/ieee8023/covid-chestxray-dataset)
This is a GitHub dataset that contains hundreds of COVID-19 patients chest X-ray images. 
    * The sources of this dataset are :
        1. Radiopaedia ( https://radiopaedia.org/ ) : 
            A wiki-based international collaborative radiology educational web resource.
        2. SIRM ( https://www.sirm.org/en/ ) : The Italian radiology organization. 
        3. Eurorad ( https://www.eurorad.org/ ): The European radiology organization.

### code

* Methods :
    * VGG, ResNet, CheXNet
* Perform evaluation:
    * Cross-validation

### results

![Alt text](fdacc.png?raw=true)
