# A-B-testing

![CH](https://user-images.githubusercontent.com/61593994/169151199-971049a9-552d-43cb-bf2b-368f2d04465a.PNG)

About
SmartAd is a mobile first advertiser agency. It designs intuitive touch-enabled advertising. It provides brands with an automated advertising experience via machine learning and creative excellence. As a Machine learning engineer in SmartAd, the task was to design a reliable hypothesis testing algorithm for the BIO service and to determine whether a recent advertising campaign resulted in a significant lift in brand awareness.

Objectives
An advertising company is running an online ad for a client with the intention of increasing brand awareness. The advertiser company earns money by charging the client based on user engagements with the ad it designed and serves via different platforms. To increase its market competitiveness, the advertising company provides a further service that quantifies the increase in brand awareness as a result of the ads it shows to online users. The main objective of this project is to test if the ads that the advertising company runs resulted in a significant lift in brand awareness.

Repository overview
Structure of the repository:

    ├── models  (contains trained model)
    ├── assets  (contains assets)
    ├── data    (contains data of smart ad)
    ├── scripts (contains the main script)	
    │   ├── logger.py (logger for the project)
    overview)
    │   ├── plot.py (handles plots)
    ├── notebooks	
    │   ├── overview.ipynb (overview of the project)
    │   ├── classical.ipynb (Classical AB testing)
    │   ├── sequential.ipynb (Sequential AB testing)
    ├── tests 
    │   ├── test_preprocess.py (test for the the AB testing script)
    ├── README.md (contains the project description)
    ├── requirements.txt (contains the required packages)
    ├── setup.py (contains the setup of the project)
    └── .dvc (contains the dvc configuration)
    

Hypothesis
H0: The ads that the advertising company runs did not result in a significant lift in brand awareness.
H1: The ads that the advertising company runs resulted in a significant lift in brand awareness.

Results
The test is significant at the p-value of 0.25.

Conclusion
The ads that the advertising company runs did not result in a significant lift in brand awareness.

Contrbutors
Ken Wakura
Rehmet Yeshanew
Samuel Alene
Yididiya Samuel
