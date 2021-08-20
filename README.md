# yandex-practicum-data-scientist-projects
Projects from [Yandex.Practicum Data Scientist course](https://practicum.yandex.ru/data-scientist/). 
 
Unfortunately, I can’t post datasets from most of the projects here because of limitations in the [Yandex.Practicum terms of use](https://yandex.ru/legal/praktikum_termsofuse/) (clause 4.1). But in some cases datasets were pulled from open sources (project 6), so you can download data and notebook and fully run it.
 
## Description of projects
### [Project 0. Fundamentals of Python and data analysis](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/00.%20Fundamentals%20of%20Python%20and%20data%20analysis)
__Music of big cities__
- Client - [Yandex.Music](https://music.yandex.ru/);
- Input data - music listening data for Moscow and St. Petersburg;
- Target - researching user preferences.

Tools used - pandas.

### [Project 1. Data preprocessing](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/01.%20Data%20preprocessing)
__Borrowers reliability research__

- Client - bank credit department;
- Input data - customers solvency statistics;
- Target - determine whether the marital status and number of children of the customer affects the fact of repayment of the loan on time.

Tools used - pandas, pymystem3.

### [Project 2. Exploratory data analysis](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/02.%20Exploratory%20data%20analysis)
__Analysis of apartment advertisements__

- Input data - [Yandex.Nedvizhimost](https://realty.yandex.ru/) service data: archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years;
- Target - determine the parameters for determining the market value of real estate.

Tools used - pandas, pymystem3.

### [Project 3. Statistical data analysis](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/03.%20Statistical%20data%20analysis)
__Definition of a prospective tariff for a telecom company__ 

- Client - federal mobile operator;
- Input data - data from 500 users: who they are, where they come from, what tariff they use, how many calls and messages each one sent in 2018;
- Target - analyze customer behavior and conclude - which tariff is better.

Tools used - pandas, NumPy, Matplotlib, SciPy.

### [Project 4. Module project 1](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/04.%20Module%20project%201)
__Computer games market research__

- Client - computer games online store;
- Input data - historical game sales data, user and expert ratings, genres and platforms (e.g. Xbox or PlayStation);
- Target - identify patterns governing the success of the game.

Tools used - pandas, NumPy, Matplotlib, seaborn, SciPy.

### [Project 5. Introduction to machine learning](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/05.%20Introduction%20to%20machine%20learning)
__Tariff recommendation__

- Client - federal mobile operator.
- Input data - data on the behavior of customers who have already switched to these tariffs (from the project 3).
- Target - build a model for the classification problem, which will choose the appropriate tariff.

Tools used - pandas, scikit-learn.

Models used - Logistic Regression, Decision Tree Classifier, Random Forest Classifier.

### [Project 15. Final project](https://github.com/Installka/yandex-practicum-data-scientist-projects/tree/main/15.%20Final%20project)
__Telecom operator customer churn prediction__

- Client - telecom operator.
- Input data - personal data of clients, information about their tariffs and contracts.
- Target - learn to predict customer churn.

Tools used - pandas, NumPy, Matplotlib, scikit-learn, CatBoost.
Models used - Logistic Regression, Decision Tree Classifier, Random Forest Classifier, CatBoost Classifier, VotingClassifier.
