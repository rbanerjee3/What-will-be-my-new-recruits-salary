# What will be my new recruit's salary?

The goal of this project is to build a model that would help predict salaries for a particular job/role based on known salary data. This dataset was scrapped from one of the job boards and is a quite simplified version of the real world job market.

The project is designed as such that with just a few tweaks it can also be used to implement a much more complex dataset. As we know how the data is growing at a rapid rate, thus to make it scalable, the model has been integrated with AWS to pull the data from cloud. The entire process has been automated starting from pulling the data from cloud, implementing the model to saving the results and displaying the key factors affecting the salary prediction which can be used by business for decision making.

## Technologies/Libraries used:
* AWS RedShift
* Pandas
* NumPy
* Psycopg2
* Seaborn
* Matplotlib
* Scikit-learn
* Lightgbm

## Models implemented:
* Ridge Regression
* Linear Regression
* Light Gradient Boosting
