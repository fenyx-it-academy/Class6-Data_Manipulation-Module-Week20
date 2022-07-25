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
<img width="524" alt="1" src="https://user-images.githubusercontent.com/48917695/180757815-38cd6a33-449c-4e1a-92fe-2d9c00ed7078.png">


Tip: you can use the .unique() method to get unique values. For example;
df.Survived.unique().

### 2. Pivot:

__Data:__ https://www.kaggle.com/c/titanic

__Task:__ Create pivot table by using pivot

__Index:__ Name

__Column:__ Ticket

__Values:__ Age

__Result:__


__Tip__: Use iloc[:10] for the first 10 row
<img width="659" alt="2" src="https://user-images.githubusercontent.com/48917695/180757861-1cbd1ebf-a39c-4b4e-a1a3-22b404056737.png">


### 3. Stack & Unstack:

__Data:__ Task 1

__Task:__ Manipulate the table you obtained in the 1st task with the stack and unstack methods

__Result:__
<img width="469" alt="3" src="https://user-images.githubusercontent.com/48917695/180757895-4735aede-e88e-4960-97a7-8f39f143b7fd.png">



### 4. Melt:

__Data:__ https://www.kaggle.com/c/titanic

__Task:__ Create the table below using melt method

__Id_vars:__ 'Name' and 'Embarked'

__Value_vars:__ 'Sex' and 'Age'

__Result:__
<img width="469" alt="4" src="https://user-images.githubusercontent.com/48917695/180757922-f62d9638-da51-48ab-babe-b505697b0830.png">


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
 <img width="566" alt="5-1" src="https://user-images.githubusercontent.com/48917695/180757993-60a74fce-7052-44cc-ae16-77b5a0c28c7a.png">
<img width="473" alt="5-2" src="https://user-images.githubusercontent.com/48917695/180758006-29f9590a-737f-4195-ba97-a95ea74a1189.png">

