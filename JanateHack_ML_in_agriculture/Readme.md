## Problem overview
The Toxic Pesticides
Though, many of us don't appreciate much, but a farmer's job is real test of endurance and determination.
Once the seeds are sown, he works days and nights to make sure that he cultivates a good harvest at the 
end of season. A good harvest is ensured by several factors such as availability of water, soil fertility, 
protecting crops from rodents, timely use of pesticides & other useful chemicals and nature. 
While a lot of these factors are difficult to control for, the amount and frequency of pesticides is 
something the farmer can control.

Pesticides are also special, because while they protect the crop with the right dosage. 
But, if you add more than required, they may spoil the entire harvest. 
A high level of pesticide can deem the crop dead / unsuitable for consumption among many outcomes. 
This data is based on crops harvested by various farmers at the end of harvest season. 
To simplify the problem, you can assume that all other factors like variations in farming techniques 
have been controlled for.

You need to determine the outcome of the harvest season, i.e. whether the crop would be healthy (alive),
damaged by pesticides or damaged by other reasons.

## Data Description :

* **ID**	UniqueID
* **Estimated_Insects_Count**	Estimated insects count per square meter
* **Crop_Type**	Category of Crop(0,1)
* **Soil_Type**	Category of Soil (0,1)
* **Pesticide_Use_Category**	Type of pesticides uses (1- Never, 2-Previously Used, 3-Currently Using)
* **Number_Doses_Week**	Number of doses per week
* **Number_Weeks_Used**	Number of weeks used
* **Number_Weeks_Quit**	Number of weeks quit
* **Season**	Season Category (1,2,3)
* **Crop_Damage**	Crop Damage Category (0=alive, 1=Damage due to other causes, 2=Damage due to Pesticides)

## Evaluation Metric
The evaluation metric for this hackathon is Accuracy Score.



## Public and Private split
The public leaderboard is based on 30% of test data, while final rank would be decided on remaining 70% of test data (which is private leaderboard)

 

## Guidelines for Final Submission
Please ensure that your final submission includes the following:

Solution file containing the predicted category for crop damage
Code file for reproducing the submission, note that it is mandatory to submit your code for a valid final submission