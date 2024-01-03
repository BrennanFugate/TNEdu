# TNEdu
Executive Summary 
The American Education System fails to fit with the lustrous reputation many Americans tout of the country as a whole. My goal is to find the best of our districts and dig deeper into why they are the best we have to offer. I plan to focus on public schools, as the, well, private nature of private schools makes transparent data difficult to find. I know that budget must play a large part of the gaps between regions but I want to use specifically only officially posted data so I'm going to used the "Proposed Budgets" of states as I believe they show where the States' intents lie, they are functionally the idealized version of how the state should be ran as penned by the governing body. I want to highlight the effects of a teacher's pay on the state's performance. In a sentence, I want to create a series of investigative dashboards that give context focusing down into my home state of Tennessee. Using the greater context I hope to be able to essentially take notes from other parts of the country and apply it to Tennesee in hopes of lifting TN's historically dour educational performance. 


Motivation
I was raised by the Tennesee school system, and from my experience I would have never thought we were so low compared to the rest of the country, and honestly that's the problem. Misinformation is a virus in our world of unmediated internet access, and it's easy to fall into pits of ignorance if you were never armed with the right defenses. Every year, the list of my family members, young and old, falling into the flat earth, holocaust denialism, or other pseudoscientific/conspiratorial communities grows. I can only think that if they had had a academic background or were taught a historical perspective of such misinformation then things may be different and honestly, family gatherings would be exponentially less awkward.   

Data Question(s)
Are there common threads of education success for the whole country?
Is teacher pay indicative of student performance?
Do poorer areas perform worse?
How has the US performed on the international stage?
Can I find something generally overlooked when it comes to education?

Minimum Viable Product. (MVP)
1. A Tableau presentation that gives an overview of education in the US as a whole, drilling down in to Tennessee 
2. Provide international context to show the US's performance over time. 
3. Provide key characteristics of the US's 4 main regions that relate to education. 
4. Come up with at least 2 recommendations for areas that could be preventing Tennessee from doing well academically. 

Schedule (through 1/4/2023)
1.	Get the Data (12/01/2023)
2.	Clean & Explore the Data (12/4/2023 -12/08/2023)
3.	Create Presentation of your Analysis (12/20/2023)
4.	Internal demos (1/2/2024)
5.	Demo Day (1/04/2024)

Data Sources
https://www.census.gov/programs-surveys/geography/guidance/geo-areas/urban-rural.html

https://nces.ed.gov/programs/digest/d18/tables/dt18_226.60.asp

https://www.tn.gov/content/dam/tn/finance/budget/documents/2019BudgetDocumentVol1.pdf

https://budget.digital.mass.gov/bb/gaa/fy2018/

https://educationdata.org/public-education-spending-statistics#:~:text=In%20the%20United%20States%2C%20education,below%20the%20international%20standard%2015.00%25.

https://www.oecd.org/pisa/publications/pisa-2018-results.htm

Known Issues and Challenges
- There will be almost no CSVs, only the Census website is generous with data types. 
- There are many ways to posture a state's budget, its difficult to find a single billion dollar figure that will be able to explain the entirety of an education system. 
- Education topics go beyond the classroom, so many critical lifestyle events happen at home that don't get put onto spreadsheets. I'm gonna need to find a way to make broad categories that aren't neccesarily school related to prove some points (Essentially, use the predicted livable income per state)
- The COVID-19 Pandemic shook up education as we previously understood it. I'll have to decide whether to use pre or post COVID stats. 
- There are no great ways to score students on an international level as every country has a different cirriculum. 
- Honestly, the biggest challenge with this project was finding the angle I wanted to go with it. Education spurs the rest of the country in every direction, there's so much data that could be used to tell any story. Due to my inherent indecisiveness: I will be spending hours agonizing about which data to even use, then what it's saying, then if it's a big enough factor to actually be used in my project. 


Running the Project 
File Structure should be as follows
WITHIN the Project Folder
"agreggate data"
Aggregate data is from the initial data search, I put anything and everything that could relate to the topic in this folder just to have as many options as possible. 
"art"
PNGs, JPEGS, etc used in the Tableau Presentation
"notebooks"
Python Notebooks originally used before I realized Tableau was doing all of the work for me. 
"used data"
Cleaned Data actually used in the final project. 


Used Data 
"ACT_Scores_by_State" 
Already clean from 'https://nces.ed.gov/programs/digest/d18/tables/dt18_226.60.asp', just needed to clear cell merging from the "State" column, then save to a CSV. 

"best-states-for-teachers-2023"
Already clean from 'https://worldpopulationreview.com/state-rankings/best-states-for-teachers'Just needed to sort the states alphabetically in Excel.

"BUDGET PORTION"
TN budget pulled from 'https://www.tn.gov/finance/fa/fa-budget-information.html'
MA Budget pulled from 'https://budget.digital.mass.gov/bb/gaa/fy2018/'

"Property Values by State"
Data Pulled from: https://www.bankrate.com/real-estate/median-home-price/#median-price-by-state


"Transportation Budget Comparisons"
TN Transportation Budget pulled from:
MA Transpotation Budget pulled from: 'https://www.doe.mass.edu/finance/transportation/default.html' fy2018