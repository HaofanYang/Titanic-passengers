# Titanic-passengers-data-analysis
The data analysis was based on dataset of passengers on the pulley 'Titanic' that sank in 1912, further description about this dataset can be found: https://www.kaggle.com/c/titanic/data

## 1. What is the correlation between survival chance and the number of family members (e.g. spouses, parents and children)?
It seems the number of family members is not strongly correlated with the chance of survival, which is kinda surprising. Our intuition is that those have more family members would sequently have a stronger desire for survival, as they were under the obligation to take care their families.
However, this may be explained in multiple ways. For example: passengers with more family members might be older. As the result, they gave up the hope of survival and save more space for younger people. This leads us to the next question: the correlation with age and the survival chance.
![image](https://github.com/HaofanYang/Titanic-passengers/raw/master/images/q1.png)
![image](https://github.com/HaofanYang/Titanic-passengers/raw/master/images/1_2.png)
## 2. How does the probabily of survival differ with age.
The distribution pattern of survival chance wrt. age groups is not clear
The average survival chance in all age groups is 37.6% ± 12.1%
Children and infants (0 - 10 years old) had highest survival chance at 59.4%, whereas the elders (70 - 80) had lowest one.
Given some missing data points were deleted at the stage of data cleaning, the result might not be representitive.
![image](https://github.com/HaofanYang/Titanic-passengers/raw/master/images/q2.png)
## 3. Do sexuality and ticket classes influence the survival chance?
The trend in terms of sexuality is quite obivious: females passengers had significantly higher survival chance than males.
The survival chance decreases as the ticket class gets lower (i.e. passengers with 1st class ticket have highest probability of survival, followed by 2nd class).
Almost every women in with 1st and 2nd class tickets survived (survival chance: aprox. 96%), whereas only 13.5% males with 3rd class ticked survived
![image](https://github.com/HaofanYang/Titanic-passengers/raw/master/images/q3_!.png)
![image](https://github.com/HaofanYang/Titanic-passengers/raw/master/images/q3_2.png)
