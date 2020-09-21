
# Demographic Data Analyzer

In this project, we analyze demographic data using Pandas. The dataset of demographic data was extracted from the 1994 Census database. Here is the head of the data looks like:

|      |  age | workclass        | fnlwgt | education | education-num | marital-status     | occupation        | relationship  | race  | sex    | capital-gain | capital-loss | hours-per-week | native-country | salary |
| ---: | ---: | :--------------- | -----: | :-------- | ------------: | :----------------- | :---------------- | :------------ | :---- | :----- | -----------: | -----------: | -------------: | :------------- | :----- |
|    0 |   39 | State-gov        |  77516 | Bachelors |            13 | Never-married      | Adm-clerical      | Not-in-family | White | Male   |         2174 |            0 |             40 | United-States  | <=50K  |
|    1 |   50 | Self-emp-not-inc |  83311 | Bachelors |            13 | Married-civ-spouse | Exec-managerial   | Husband       | White | Male   |            0 |            0 |             13 | United-States  | <=50K  |
|    2 |   38 | Private          | 215646 | HS-grad   |             9 | Divorced           | Handlers-cleaners | Not-in-family | White | Male   |            0 |            0 |             40 | United-States  | <=50K  |
|    3 |   53 | Private          | 234721 | 11th      |             7 | Married-civ-spouse | Handlers-cleaners | Husband       | Black | Male   |            0 |            0 |             40 | United-States  | <=50K  |
|    4 |   28 | Private          | 338409 | Bachelors |            13 | Married-civ-spouse | Prof-specialty    | Wife          | Black | Female |            0 |            0 |             40 | Cuba           | <=50K  |


We use Pandas to answer the following questions:
- How many people of each race are represented in this dataset? (`race` column)
- What is the average age of men?
- What is the percentage of people who have a Bachelor's degree?
- What percentage of people with advanced education (`Bachelors`, `Masters`, or `Doctorate`) make more than 50K?
- What percentage of people without advanced education make more than 50K?
- What is the minimum number of hours a person works per week?
- What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?
- What country has the highest percentage of people that earn >50K and what is that percentage?
- Identify the most popular occupation for those who earn >50K in India. 


Unit tests are written under `test_module.py`.

### To Run this Repository:
- `git clone https://github.com/McSnipe97/demographic-data-analyzer.git && cd demographic-data-analyzer-master`
- `python3 -m poetry install`
- `python3 main.py`

### Development

For development, you can use `main.py` to test your functions. Run `python main.py` in terminal.

### Testing 

I've imported the tests from `test_module.py` to `main.py` for convenience. The tests will run automatically whenever `main.py` is executed.

### Dataset Source

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

