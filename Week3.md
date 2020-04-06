# CourseraExercise
For this project, I considered the headquarters building of the company that I work at. It is in San Francisco Bay Area and we own 4 floors of a 15 floor building. We are a tech company and hence everyone has their own laptops as well as separate monitors screens. Bay area is very spread out with not the most efficient transportation and also the city(SF) is very expensive to live in. Hence since nothing is in walking distance, people at work use a combination of driving in and public transport to get to work each day. 

For this exercise I calculated the GHG using Electricity used and Commuting Carbon Footprints. Though I have added a note about waste generated, I have not used it in my model. We also get a lot of food and snacks at work and I have not considered the carbon logistical footprint for each of them since it would make my model very complex.

[Link to Model](https://docs.google.com/spreadsheets/d/10P9gyPU335r3j7zznuPlGkKokKAAMfv8KeWa85De0Xs/edit?usp=sharing)

Total Waste Generated for 400 Employees :
558 Tons Per Year

Assumptions For Electricity : 					
1. People use it for longer than 12 hours (Some people come in early and some people come in late)			
2. Number of Working Days in a year = 200					
3. Not Counting Standby Time of Any Electronics					
4. Assuming Incadescent Lights					
5. Not Adding any food related emissions					
					

Model At Current State: 
![alt text](https://github.com/jheeld/CourseraExercise/blob/master/Screen%20Shot%202020-04-05%20at%206.35.18%20PM.png)


For electricity GHG, I have considered number of people, floors, laptops, monitors, lights, coffee, fridge and other applicances for the model.

As we can see from the model, the highest contributor for electricity GHG is not laptops itself but monitor displays which is essential for most programming jobs. These are also very less energy effecient, at the same time employees are encouraged to have multiple screens. They are contributing to 45% of the kHW. The best way to reduce it will be to use energy effecient and cap the number of monitors allocated to each employee. Its good to have but not necessary. Next big contributor is light. That is easy to divide by 1/3 by switching to LEDs. 

Assumptions for Commuting Model :
1. To Accounting For Public Transit the effects of shared usage we half the values. It should actually be lower.
2. Taken a random end point which is potentially average emissions
3. Not Accounted for Multi Modal Way of Transport to reduce model complexity

Model At Current State: 
![alt text](https://github.com/jheeld/CourseraExercise/blob/master/Screen%20Shot%202020-04-05%20at%206.37.29%20PM.png)

As explained at the start due to various reasons, commuting is a major GHG emissions producer. But since my workplace has pretty flexible timings and has carbon conscious employees, a wide chunk of people do use public transportation. The major number missing from my analysis is driving by private vehicle to a public transit stop which I know does add up significantly. Even with all the public transit, almost 1/4 can be assumed to drive in. That adds up significantly since on an average that distance is 30-40 miles one way(with traffic it adds even more GHG). Employees should be given incentive to work from home, take public transit or even bike to work.

References:
