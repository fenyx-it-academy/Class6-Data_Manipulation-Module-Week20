# Class6-Data_Manipulation-Module-Week20

### 1. Multi index & column:

__Data:__ https://www.kaggle.com/c/titanic

__Task:__ Create a multi-indexed dataframe

__Indexes:__
* level_0 = Sex
* level_1 = Embarked

__Columns:__
*  level_0 = Pclass
*  level_1 = Survived

__Values:__ Random

__Result:__
![alt text](img/1.png 'result')

Tip: you can use the .unique() method to get unique values. For example;
df.Survived.unique().

### 2. Pivot:

__Data:__ https://www.kaggle.com/c/titanic

__Task:__ Create pivot table by using pivot

__Index:__ Name

__Column:__ Ticket

__Values:__ Age

__Result:__
![alt text](img/2.png 'result')

__Tip__: Use iloc[:10] for the first 10 row


### 3. Stack & Unstack:

__Data:__ Task 1

__Task:__ Manipulate the table you obtained in the 1st task with the stack and unstack methods

__Result:__
![alt text](img/3.png 'result')


### 4. Melt:

__Data:__ https://www.kaggle.com/c/titanic

__Task:__ Create the table below using melt method

__Id_vars:__ 'Name' and 'Embarked'

__Value_vars:__ 'Sex' and 'Age'

__Result:__
![alt text](img/4.png 'result')

__Tip__: Use iloc[:10] for the first 10 row


### 5. Pivot Table:

__Data:__ https://www.kaggle.com/c/titanic

__Task:__ Create the following pivot tables using the pivot_table method

__Index:__ 
* A) 'Embarked'
* B) 'Embarked', 'Sex', 'Pclass'
* C) 'Embarked', 'Sex', 'Pclass'

__Values:__ 'Fare' and 'Age'

__aggfunc:__
* A) 'Fare': mean, 'Age': median
* B) 'Fare': mean, 'Age': median
* C) 'Fare': mean and np.sum, 'Age': np.median and np.std

__Result:__
![alt text](img/5-1.png 'result')
![alt text](img/5-2.png 'result') 
