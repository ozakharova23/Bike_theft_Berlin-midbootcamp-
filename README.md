 #**Project name**

##**Berlin Bike Theft Analysis**

###**Table of Contents**
####General Info
####Dataset
####Technology stack




###Dataset
The dataset is available in a csv file link.

The data set contains information on bike thefts in Berlin from 01/01/2021 to 01/06/2023.

All data is available on the official government website:
https://daten.berlin.de/datensaetze/fahrraddiebstahl-berlin

The GeoJSON files for mapping are avaliable under:
https://daten.odis-berlin.de/index.html


1) Dataset contains the following information

ANGELEGT_AM – Date of recording = date of recording for each offence

TATZEIT_ANFANG_DATUM – Date of the offence = start date of the offence

TATZEIT_ANFANG_STUNDE – Stealing hour – hour when crime happen

TATZEIT_ENDE_DATUM – Report stealing date = date when crime was report to police

TATZEIT_ENDE_STUNDE – Report stealing hour = hour when crime was report to police

LOR – Berlin code area = 8 or less digit number for Berlin area identification

SCHADENSHOEHE = Bike value (€)

VERSUCH = Attempt

Ja = Sucessfull atempt
Nein – unsucessfull attemt 
Unknown

ART_DES_FAHRRADS – Bike type
Damenfahrad - female bike
Herrenfahrad - male bike
Lastenfahrad - cargo bike

DELIKT – Crime type

Fahrraddiebstahl = Thieft
Keller- und Bodeneinbruch = Break-in

ERFASSUNGSGRUND = Crime reason four category:

Sonstiger schwerer Diebstahl von Fahrrädern = Aggravated theft
Einfacher Diebstahl von Fahrrädern = Theft
Sonstiger schwerer Diebstahl in/aus Keller/Boden von Fahrrädern = Aggravated theft from basement/floor
Einfacher Diebstahl aus Keller/Boden von Fahrrädern" = Theft from basement/floor
Aggrevated theft = theft with break-in, theft with robbery (aggressor has to use force against person or property)

### LOR dataset

Berlin code area = LOR number

Administrative district = Berlin administrative district name

District – Berlin district name

Quarter – Berlin quater name

Street name – Berlin street name


### Tableau  visualisations and presentations are available under

https://public.tableau.com/app/profile/olga.zakharova/viz/MidbootcampProject_16862708519450/Mid-bootcamp

###Technology stack
Computing platform
Jupyter Notebook
Packages for data pre-processing
Numpy
Pandas
Scikit-learn
Data visualisation library
Matplotlib
Seaborn
Tableau