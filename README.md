Introduction:

The Titanic dataset is widely used for learning data analysis and machine learning concepts. It contains passenger details such as age, gender, class, fare, and survival status.
The objective of this analysis is to explore patterns affecting passenger survival.Python Pandas is used to clean, analyze, and extract insights from the dataset.

Dataset Overview:

The dataset includes information about passengers aboard the Titanic ship.Key features include PassengerId, Age, Sex, Pclass, Fare, Embarked, and Survived.
The target variable is Survived (0 = No, 1 = Yes).The dataset contains missing values in columns like Age and Embarked that require preprocessing.

Methodology:

The dataset was imported using Pandas and inspected using head(), info(), and describe().Missing values were handled using fillna() and dropna() techniques.
Data was filtered, sorted, grouped, and reshaped for meaningful analysis.Statistical calculations and aggregations were performed using groupby() and pivot tables.

Statistical Analysis:

Survival rate was calculated based on gender, passenger class, and embarkation point.Average age of survivors and non-survivors was compared.
Fare distribution was analyzed to identify highest and lowest ticket prices.Filtering and sorting helped identify high-risk and high-survival passenger groups.

Conclusion:

Female passengers had a significantly higher survival rate than males.Passengers in higher classes (Pclass 1) were more likely to survive.Ticket fare and passenger age showed
noticeable influence on survival patterns.Pandas proved effective for data cleaning, transformation, and exploratory analysis.
