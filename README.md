![image](https://github.com/user-attachments/assets/314489b6-53ae-41d6-8afe-087614613d8d)

# Pet Shelter Analysis
[Project Link](https://github.com/ashleyle95/Pet-Shelter-Analysis-/blob/main/Pet_Shelter_Analysis%202.ipynb)
# Questions:
- Question number 1: What is the distribution of the types of animals in the shelter?
- Question number 2: Is there an area where more pets are found?. Find the top 5 location where pet are found
- Question number 3: What is the average number of pets found in a month in the year 2015?. Are there months where there is a higher number of animals found?
- Question number 4: What is the ratio of incoming pets vs. adopted pets
- Question number 5: What are the adoption rates for specific breeds? Find the top 5 dog breeds in the shelter (based on count) and then find the adoption percentage of each breed.
- Question number 6: About how many animals are spayed/neutered each month? This will help the shelter allocate resources and staff. Assume that all intact males and females will be spayed/neutered.
- Question number 7: How many animals in the shelter are repeats?, Which animal was returned to the shelter the most? This means the animal has been brought in more than once.
- Question number 8: What are the adoption rates for different colorings? Find the top 5 colorings in the shelter (based on count) and then find the adoption percentage of each color.
- Question number 9: What are the adoption rates for the following age groups? baby: 4 months and less, young: 5 months - 2 years, adult: 3 years - 10 years, senior: 11+
- Question number 10: If spay/neuter for a dog costs $100 and a spay/neuter for a cat costs $50, how much did the shelter spend in 2015 on these procedures?
# Dataset Dictionary
#### Acc_Intakes.csv 
- Age Upon Intake: The age of the animal when it was brought to the facility
- Animal ID: A unique identifier for each animal.
- Animal Type: The species of the animal. In both examples, this is 'Dog'.
- Breed: The breed of the animal.
- Color: The color of the animal's coat.
- Datetime: The date and time when the animal was intake.
- Datetime2: This seems to be a repeat of the intake date and time
- Found Location: The location where the animal was found before being brought to the facility.
- Intake Condition: The health or physical condition of the animal at intake.
- Intake Type: The circumstances under which the animal was brought to the facility.
- Name: The name given to the animal. 
- Sex Upon Intake: The gender and reproductive status of the animal when it arrived.

#### Acc_Outcomes.csv
- Age Upon Outcome: This is the age of the animal at the time they left the facility
- Animal ID: A unique identifier assigned to each animal.
- Animal Type: The species of the animal.
- Breed: The breed of the animal.
- Color: The color of the animal's coat.
- Date of Birth: The birth date of the animal. 
- Datetime: The date and time when the animal left the facility.
- Monthyear: This seems to be a repeat of the outcome date and time
- Name: The name of the animal
- Outcome Subtype: Additional details about the outcome.
- Outcome Type: The general category of the outcome.
- Sex Upon Outcome: The gender and reproductive status of the animal when it left the facility.
# Findings:
The analysis of the animal shelter's data provides valuable insights into the various aspects of animal intake, adoption, and care. Below are the key findings for each question:

Distribution of Animal Types:
The shelter primarily receives two types of animals: dogs and cats. Dogs make up a slightly higher proportion of the intake compared to cats.

Top 5 Locations Where Pets Are Found:
Certain areas have significantly higher numbers of animals found compared to others. The top 5 locations account for a large proportion of all intakes, indicating potential hotspots for stray or abandoned animals.

Average Number of Pets Found Per Month (2015):
On average, a consistent number of pets are found each month. However, there are specific months where the intake spikes, possibly due to seasonal trends or events.

Ratio of Incoming Pets vs. Adopted Pets:
The ratio shows that not all incoming pets are adopted. Understanding this disparity helps highlight areas where the shelter can improve its adoption strategies.

Adoption Rates for Specific Breeds:
Among the top 5 dog breeds, certain breeds have higher adoption rates than others. Popular or well-known breeds tend to be adopted more quickly, suggesting the need for targeted marketing for less popular breeds.

Number of Animals Spayed/Neutered Each Month:
A consistent number of spay/neuter procedures are performed each month. This data helps the shelter efficiently allocate resources and staff for these operations.

Repeat Animals:
Some animals are brought back to the shelter more than once, indicating potential issues with compatibility, behavioral problems, or other factors. Identifying these animals helps develop interventions to increase successful adoption rates.

Adoption Rates by Colorings:
Certain colorings are adopted more frequently than others. Understanding these trends can help shelters present animals more appealingly and potentially improve adoption rates.

Adoption Rates by Age Groups:
Adoption rates vary significantly across age groups, with puppies and kittens generally being adopted more quickly than adults or seniors. Tailored adoption campaigns for older animals could improve their chances of finding homes.

Total Cost of Spay/Neuter Procedures in 2015:
The total expenditure for spay/neuter procedures in 2015 is significant. Accurate budgeting and forecasting based on these figures can help the shelter plan for future expenses.

