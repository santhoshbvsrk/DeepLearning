# DEFCON Level Dataset
![enter image description here](https://www.abbreviations.com/images/18726_DEFCON.png)
![enter image description here](https://militarymortgagecenter.com/wp-content/uploads/2017/08/defcon-system.jpg)
## Content

 - Military conflict is an intense state of violence.
 
 -  In such situations, it is crucial for a nation to stay alert, cope with it, and mitigate its implications. 
   
 - A country has set up the DEFCON (Defense Readiness Condition) warning system.
   
 - This alert system is used to gauge the level of alertness of the defense forces.     
   
 - It consists of five levels of readiness for the    military forces to be prepared for the consequences of the conflict.
   
 - The DEFCON system allows the nation’s forces to be a step ahead of its rivals.
   
 - You are given a synthesized data that can be used to build a model that can accurately predict the DEFCON level raised as a result of
   the conflict. 
   
 - The data is present in a single csv file:    defcon_level.csv - Dataset consisting of approximately 10,000 data    samples.

## Data Description

|Column|Description  |
|--|--|
|Allied_Nations  |The number of nations that have joined together as allies.  |
|Diplomatic_Meetings_Set| The number of meetings with the intent to resolve the conflict that is planned. |
|Percent_Of_Forces_Mobilized| The percentage of forces mobilized.|
|Hostile_Nations| The number of enemy nations that have allied together.  |
|Active_Threats| The number of situations or threats that require immediate attention.  |
|Inactive_Threats| The number of situations or threats being monitored for activity or escalation.|
|Citizen_Fear_Index| The percentage of citizens who fear catastrophic military conflicts.|
|Closest_Threat_Distance(km)| The closest threat to the border of the country in question.  |
|Aircraft_Carriers_Responding| The number of aircraft carriers actively traveling towards a threat to neutralize it. |
|Troops_Mobilized(thousands)| The number of troops that are activated and responding to the threats being the most.|
|DEFCON_Level| A numeric scale of conflict 'seriousness' with 1 being the least serious and 5 being the most. (target variable)|
|ID| An ID to aid a checker script|

## Objective

 - This dataset is intended for multi-class classification tasks. 
 - Use this data set to train a model able to classify the different DEFCON levels based on certain conditions.
