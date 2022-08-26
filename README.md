# 🪰 FlyDAR - Fruit Fly Detection Alert Response

Try out FlyDAR here:
[🪰 FLYDAR](https://flydar.herokuapp.com/)

Demo the app it by registering and adding this sample fly-trap Unique ID: **ABC-123**

##  About Fruit Fly

Fruit flies are one of the world’s most destructive horticultural pests and pose a risk to most fruit and vegetable crops. There are two main species of fruit flies threatening Australia's $13 billion horticultural industry: the Queensland fruit fly and the Mediterranean fruit fly.

Fruit fly can infest many types of fruit and fruiting vegetables, from citrus, to stone fruit, to chilis to apples. 

## The challenge

How might we use data to communicate where fruit fly are being detected so we can notify the right growers as quickly and accurately as possible?

PIRSA checks over 7,500 fruit fly traps across the State every week and the results from this work are collected in real-time via a secure App which has been developed by PIRSA.

The data for this App is collected simultaneously by around a dozen Inspectors as they check the traps every day.

Growers need to be provided with real-time access to the results of trap checks on their properties so that they know immediately if a fruit fly has been detected but they should not be provided with the results of trap checks on other properties. It’s important that results are only provided for traps that growers are authorised to receive information for so that growers are not able to prejudice other growers as a result of a detection being made.

By making this data available to growers, they can respond quickly and eradicate the pest before it becomes established. It also provides PIRSA with a convenient means of informing growers of trap results without having to rely on less efficient processes.

Ideally, the platform could also be fit for purpose to manage emergency responses in the event of Varroa Mite, Foot and Mouth Disease or Lumpy Skin Disease in South Australia.


## FlyDAR


## User stories

As a grower, I want to know immediately if fruit fly is detected on my property, so I can eliminate fruit fly from my property.

As a PIRSA inspector, I want to notify a grower that I've detected fruit fly on their property immediately so they can take steps to prevent fruit fly spreading.

## Technologies Used

Full Stack Web App with authentication. <br/>
Front-End: _React_ <br/>
Back-End: _Django_ <br/>
Deployed on Heroku <br/>

## Wireframes

Link to come

## Unsolved problems and future planned updates

- Twilio integration for SMS notifications

## App Screenshots
![Readme](docs/RegisterFruitTrap.png) <br/>
![Readme](docs/CheckIfFound.png) <br/>
![Readme](docs/ReviewRegistered.png) <br/>

## Installation Instructions

```
python3 -m venv venv;
source venv/bin/activate;
pip install -r requirements.txt;
cd frontend && npm install && npm run build;
python ../manage.py runserver;
```
