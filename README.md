# EDA-on-Titanic-Dataset

## About  : 
  In this project, we performed data cleaning, data preprocessing, data analysis, exploratory data analysis (EDA), statistical analysis, and data visualization on the Titanic dataset. We analyzed different features, handled missing values, studied relationships and patterns, and created various graphs to understand the data. No machine learning model was trained in this project.
  
Dataset
  The Titanic dataset contains details of passengers who travelled on the RMS Titanic.
It includes information such as Passenger ID, name, sex, age, ticket number, and passenger class.
It also contains details like fare, cabin, number of siblings/spouses, and parents/children aboard.
The dataset records whether each passenger survived or did not survive the Titanic disaster.
Overall, it can be used to analyze passenger characteristics and their relationship with survival.

  This dataset contains twelve features/columns :
  Feature	                              Meaning
  - PassengerId	               A unique identification number assigned to each passenger.
  - Survived	                 Indicates whether the passenger survived the Titanic disaster: 0 = Did not survive, 1 = Survived.
  - Pclass	                   Passenger class/ticket class: 1 = First class, 2 = Second class, 3 = Third class.
  - Name	                     Full name of the passenger.
  - Sex	                       Gender of the passenger, such as male or female.
  - Age	                       Age of the passenger in years.
  - SibSp	                     Number of siblings or spouses the passenger had aboard the Titanic.
  - Parch	                     Number of parents or children the passenger had aboard the Titanic.
  - Ticket	                   Ticket number assigned to the passenger.
  - Fare	                     Amount of money paid by the passenger for the ticket.
  - cabin                      Cabin number or cabin information assigned to the passenger.
  - Embarked                   Port where the passenger boarded the Titanic: C = Cherbourg, Q = Queenstown, S = Southampton.
  
## Tools used :
  - python
  - pandas
  - matplotlib
  - seaborn
    
## Key findings : 
  - Most passengers did not survive.
  - Female passengers had a higher survival rate than male passengers.
  - Children had better survival chances compared with many adults.
  - Passengers in higher classes had better survival rates.
  - Pclass had a noticeable relationship with survival.
  - Fare was generally higher for passengers in higher classes.
  - The dataset contains missing values, especially in Age, Cabin, and Embarked.
  - Survived is the target/outcome feature.

    Survival was strongly related to gender and passenger class, with females and higher-class passengers having better survival rates. The dataset also contained missing values, which required data cleaning and preprocessing before performing EDA and visualization.
