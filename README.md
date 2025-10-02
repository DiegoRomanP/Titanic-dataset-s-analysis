# Exploración inicial de datos
For the first exploration we copy and paste the data dictionary
| Variable     | Definition                                      | Key                                                                 |
|--------------|--------------------------------------------------|----------------------------------------------------------------------|
| survival     | Survival                                         | 0 = No, 1 = Yes                                                     |
| pclass       | Ticket class                                     | 1 = 1st, 2 = 2nd, 3 = 3rd                                           |
| sex          | Sex                                              |                                                                     |
| age          | Age in years                                     | Age is fractional if less than 1. If estimated, in form of xx.5     |
| sibsp        | # of siblings / spouses aboard the Titanic       | Sibling: brother, sister, stepbrother, stepsister<br>Spouse: husband, wife (mistresses and fiancés ignored) |
| parch        | # of parents / children aboard the Titanic       | Parent: mother, father<br>Child: daughter, son, stepdaughter, stepson<br>Some children travelled only with a nanny, so parch=0 for them |
| ticket       | Ticket number                                    |                                                                     |
| fare         | Passenger fare                                   |                                                                     |
| cabin        | Cabin number                                     |                                                                     |
| embarked     | Port of Embarkation                              | C = Cherbourg, Q = Queenstown, S = Southampton                      |

**Variable Notes:**

- **pclass**: A proxy for socio-economic status (SES)<br>1st = Upper, 2nd = Middle, 3rd = Lower
- **age**: Age is fractional if less than 1. If estimated, is in the form of xx.5
- **sibsp**: The dataset defines family relations as follows...<br>Sibling = brother, sister, stepbrother, stepsister<br>Spouse = husband, wife (mistresses and fiancés were ignored)
- **parch**: The dataset defines family relations as follows...<br>Parent = mother, father<br>Child = daughter, son, stepdaughter, stepson<br>Some children travelled only with a nanny, therefore parch=0 for them
### Questions:
The first question we want to answear is:
+ who have more probability of survive? it have to be for gender, class and age 
