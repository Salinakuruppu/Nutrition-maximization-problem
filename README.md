Introduction
As university students, we always attempt to consume whatever worth for our budget. We have another question once we reach that stage. Are the foods we eat healthy? 
The University of Ruhuna has an answer for this problem. They introduced a canteen in the style of a buffet. We can choose from a variety of dishes and curries for breakfast/lunch. Each curry dish has a different cost. As a result, we can select and purchase the curries that we like. Let's talk about the meals and curries, and how much of each can we get for lunch.
We can use operation research to address these issues as aspiring mathematicians. Realistic circumstances need taking into account several objectives on one side and various sorts of information while making decisions

Methodology
A mathematical method and linear programming variant is called goal programming. Goal programming is a method that can be used to solve problems involving multiple conflicting goals. Its objective function is made up of non-homogeneous units of measurement and only includes deviational variables (d⁻, d⁺) that are complementary to one another.
The priorities of the decision-making objectives are often ranked.  In the ranking of the qualified assigned values, objectives with similar propriety may be weighted differently. Goal programming therefore aims to reduce the total sum of deviational variables.
There are two different kinds of constraints in the goal programming problem. There are both hard and soft constraints. The initial function with a set of priorities and goals, including positive and negative deviational variables, is just the goal constraint.
Typically, we use
                         d⁺ = over achievement 
                        d⁻ = under achievement

problem
We talked about the areas of this subject we are prepared to cover earlier in the introduction section.
We decide on a canteen that is close to the University of Ruhuna. Here, we examine a lunch meal for a single adult (20–25 years old). Let's look at this issue's solution.
This is the menu card for the university canteen.

Menu Card Of Food Stole :

01.	 White rice                    one dish (250g)                             50/=
02.	 Dal Curry                     one dish (50g)                              25/=
03.	 Kankung Curry                 one dish (50g)                               25/=
04.	 Brinjal Curry                 one dish (50g)                               25/=
05.	 Carrot Curry                  one dish (50g)                               25/=
06.	 Beans Curry                   one dish (50g)                               25/=
07.	 Sweet Potato Curry            one dish (50g)                               25/=
08.	 Beats Curry                   one dish (50g)                               25/=
09.	 Steamed Fish Curry            one dish (50g)                                25/=
10.	 Chicken Curry                 one dish (50g)                                25/=            
You can choose one white rice dish and maximum four curries ( can’t select both of Steamed fish curry and Chicken curry, only one curry ) and maximum three dishes per every curry.


Recall that we have a choice. 
• Only one serving of white rice (x0=1)
• A maximum of four curries (we can only choose one of the two: steamed fish curry or chicken curry).
I hope you can manage your finances and gain some insight into the menu. Our first goal is to purchase a high-quality, economical lunchbox.
Let's examine the nutritional content of these curries. For our issue, we place a high priority on protein, carbohydrates, fat, calcium, potassium, sugar, and calories.

Healthy Male Person Age (20  - 25)
![image](https://github.com/user-attachments/assets/ff75b266-7e5b-48b6-81cc-f42023b01e82)
Assumptions
01)	We assume age between 20 – 25 male person need 32g of Protein, 103.33g of Carbohydrates, 23.33g of Fat , 0.33g of Calcium, 1.27g of Potassium, 30g of sugar, 833.33 of Calories.
02)	50g of curry dishes should be ordered and maximum three dishes. 
03)	We assume should be have more than 30 marks preferences for any kind of four curries

Customers can put marks for curries according their interesting for curries (you can put 0 - 10)
01)	Dal Curry                         -   ……………….
02)	Kankung Curry                     -   ………………..
03)	Brinjal Curry                     -   ………………..
04)	Carrot Curry                      -   ………………..
05)	Beans Curry                       -   ………………..
06)	Sweet Potato Curry                -   ………………..
07)	Beets Curry                       -   ………………….
08)	Streamed Fish Curry               -   ………………….
09)	Chicken Curry                     -   ………………….

Variables      
•	X₁= number of dal dishes
•	X₂= number of kankung dishes
•	X₃= number of brinjal dishes
•	X₄= number of carrot dishes
•	X₅= number of beans dishes
•	X₆= number of sweet potato dishes
•	X₇= number of beet dishes
•	X₈= number of steamed fish dishes
•	X₉= number of chicken dishes

•	k₁= priority number for dal curry
•	k₂= priority number for kankung curry
•	k₃= priority number for brinjal curry
•	k₄= priority number for carrot curry
•	k₅= priority number for beans curry
•	k₆= priority number for sweet potato curry
•	k₇= priority number for beet curry
•	k₈= priority number for steamed fish curry
•	k₉= priority number for chicken curry

•	y₁  -  y₉  = decision variables (0 or 1)
Object
Minimize the budget
 Min(z) = 25 (X₁ +X₂ +X₃ +X₄ +X₅ +X₆ + X₇ + X₈+ X₉) 
 Constraints
Decision of the preferred dishes
y₁ +y₂ +y₃ +y₄ +y₅ +y₆ + y₇ + y₈+ y₉ = 4
Yᵢ  >= 0 (i = 0 to 1)
Preference of the non vegetarians and vegetarians
y₈  +  y₉  <= 1
Xᵢ  >= 0 (i =  1 to 9 )

Goal
Protein
4.195 X₁ +1.995 X₂ +0.395 X₃ +0.37 X₄ +0.91 X₅ +0.96 X₆ +1.37 X₇ +10.97 X₈ +15.5 X₉  >=  25.35

Carbohydrates
9.365 X₁ +2.565 X₂ +4.155 X₃ +3.995 X₄ +3.805 X₅ +9.9.5 X₆ +8.14 X₇ +0.165 X₈ +0 X₉ >= 33.58

  Fat
3.335 X₁ +0.25 X₂+1.925 X₃ +1.24 X₄ +1.55 X₅ +1.62 X₆ +1.915 X₇ +6.88 X₈ +1.785 X₉  >= 22.63 
 Calcium
0.009 X₁ +0 X₂ +0.003 X₃ +0 X₄ +0 X₅ +0.0185 X₆ +0 X₇ +0.0065 X₈ +0.0075 X₉  >= 0.31
 Potassium
0.1715 X₁ +0.1505 X₂+0.0585 X₃ +0.1135 X₄ +0.07 X₅ +0.2265 X₆ +0.2485 X₇ +0.157 X₈ +0.128X₉ >= 1.18 
 Sugar
0.84 X₁+0.255 X₂ +1.51 X₃ +1.665 X₄ +0.74 X₅ +4.02 X₆ +6.47 X₇ +0.04 X₈ +0 X₉ >= 29.88 
 Calories
82.5 X₁ +16 X₂ +32.5 X₃ +27 X₄ +29.5 X₅ +56.5 X₆ +51 X₇ +63 X₈ +190 X₉  >=  510.83 
 
Conclusion
            We can use this method for eat nutritional lunch packet with lowest price.  Some time this method is not practical because day to day busy schedules most of university students like to get their lunch packet easy and quickly but concern about nutritious and price. 
•	According to this our code, maximize the customers preferences but should be maximize the nutrition, if this is not satisfy, there is no feasible solution.
•	We use integer linear programming then every out puts are integers then some time cant find feasible solutions between variable limit.
•	When we analyze our canteen menu couldn’t eat low budget nutritional lunch packet  without chicken or fish dishes, we cant find feasible solution for that.   

Applying for Practical situation :
But every university students, lectures and staff members are not healthy persons, couldn’t eaten only preferences should be checked nutrition of foods and also need to check price. This method we think more useful for this.



