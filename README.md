# deep-learning-challenge
Deep Learning Challenge

This challenge attempts to help a nonprofit foundation, Alphebet Soup, by creating a tool to help select applicants for funding with the best chance of success in their ventures. Creating various models and optimizing along the way, my goal is to get a model that has above a 75 percent accuracy rating. 

Results
Preprocessing:
•	Target variable in this case is the success or failure of the applicant, or IS_SUCCESSFUL
•	Dropped unnecessary ID variables in EIN and NAME
•	Featured variables include:
o	APPLICATION_TYPE—Alphabet Soup application type
o	AFFILIATION—Affiliated sector of industry
o	CLASSIFICATION—Government organization classification
o	USE_CASE—Use case for funding
o	ORGANIZATION—Organization type
o	STATUS—Active status
o	INCOME_AMT—Income classification
o	SPECIAL_CONSIDERATIONS—Special considerations for application
o	ASK_AMT—Funding amount requested


Compiling, Training, and Evaluation

•	All of my models used two hidden layers and one outer layer 
•	All of my models used relu for the hidden layers and sigmoid for the outer
•	Model 1 had 80,60,1 for the neurons
•	Model 2 had 100,70,1
•	Model 3 had 100,80,1
•	Model 4 had 90,60,1

I kept the models similar because I started very close to the target accuracy. Despite this, I did not reach the target goal of 75 percent.  All models were around 72.5 percent. I felt like playing with the neurons would get me over the target line, but I was unable to find a suitable combination. 


Summary:
The overall results of the model are ok but not optimal. If one model must be chosen, I would recommend the first model because it has the highest accuracy, albeit by a small margin. 

https://git.bootcampcontent.com/Michigan-State-University/MSU-VIRT-DATA-PT-06-2023-U-LOLC/-/tree/main
