# DVD-Rental-Store-SQL

[![Makes people smile](https://forthebadge.com/images/badges/makes-people-smile.svg)](https://github.com/iamsivab)
## DVD-Rental-Store-SQL

[![Generic badge](https://img.shields.io/badge/Datascience-Beginners-Red.svg?style=for-the-badge)](https://github.com/iamsivab/DVD-Rental-Store-SQL) 
[![Generic badge](https://img.shields.io/badge/LinkedIn-Connect-blue.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iamsivab/) [![Generic badge](https://img.shields.io/badge/Python-Language-blue.svg?style=for-the-badge)](https://github.com/iamsivab/DVD-Rental-Store-SQL) [![ForTheBadge uses-git](http://ForTheBadge.com/images/badges/uses-git.svg)](https://GitHub.com/)

#### The goal of this project is to [#DataScience](https://github.com/iamsivab/DVD-Rental-Store-SQL) from the various travel insurance-related attributes.

[![GitHub repo size](https://img.shields.io/github/repo-size/iamsivab/DVD-Rental-Store-SQL.svg?logo=github&style=social)](https://github.com/iamsivab) [![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/iamsivab/DVD-Rental-Store-SQL.svg?logo=git&style=social)](https://github.com/iamsivab/)[![GitHub top language](https://img.shields.io/github/languages/top/iamsivab/DVD-Rental-Store-SQL.svg?logo=python&style=social)](https://github.com/iamsivab)

#### Few popular hashtags - 
### `#DataScience` `#Guide for Beginners` `#`
### `#patternlearning` `#BagofWords` `#textanalytics`

# Sakila DVD Rental database Analysis


## Introduction

In this project, we have queried the Sakila DVD Rental database. The Sakila Database holds information about a company that rents movie DVDs. For this project, we have queried the database to gain an understanding of the customer base, such as what the patterns in movie watching are across different customer groups, how they compare on payment earnings, and how the stores compare in their performance. For assistance in the queries, the schema for the DVD Rental database was used as given in the `dvd-rental-erd-2.pdf`.


## Local Environment Setup

Follow the steps provided below to setup the local environment with **PostgreSQL** and database

**Step 1. Downloading PostgreSQL**

First, we will need to install PostgreSQL on your local machine. The instructions below provide detailed description of the steps we need to take.

**Installing PostgreSQL for Windows:**

http://www.postgresqltutorial.com/install-postgresql/

**Installing PostgreSQL for Mac OS:**

https://www.postgresql.org/download/macosx/

**Note:** We need to write down the database superuser (postgres) password as we will need it to create the Sakila database once we have installed the PostgreSQL server.

**Step 2. Downloading Sakila database**

Once PostgreSQL server is installed, we will need to download the Movie database from this page: [PostgreSQL Sample Database](http://www.postgresqltutorial.com/postgresql-sample-database/)

Scroll down and click on the orange "Download DVD Rental Sample Database" button.

This will download a zipped file, and you will need to extract the `dvdrental.tar file`.

**Step 3. Loading database**

The next step is to load the DVD Rental database into our PostgreSQL server on our machine. We recommend using the **PgAdmin tool**. We can find the instructions to do so on the following link: [Load PostgreSQL Sample Database](http://www.postgresqltutorial.com/load-postgresql-sample-database/).

The instructions are down ⅓ on this page under the header **“Load the DVD Rental database using pgAdmin tool”** .

Now, we need to follow the instructions all the way through the header titled **"Verify the loaded sample database."**

Once we have followed the instructions through the end of **"Verify the loaded sample database."**, we have now loaded the `dvdrental` sample database into our local PostgreSQL database server.

**Step 4. Connecting back to the PostgreSQL server:**

Now, we will relaunch PgAdmin III and click on the PostgreSQL server within the Object browser and enter our superuser (postgres) password.

**Step 5. Connecting to the DVD rental database:**

Next, we will click on the plus sign next to Databases to access the DVD rental database.

**Step 6. Choose the DVD Rental database**

Choose the `dvdrental` database under Databases.

We are now linked to the DVD rental database.

**Step 7. Running Queries on your dvdrental database**

Now, we are ready to run some queries. For that, we need to click on the SQL icon with a magnifying glass

## Questions to work upon for analysis

**Question 1**

We want to understand more about the movies that families are watching. The following categories are considered family movies: Animation, Children, Classics, Comedy, Family and Music.

**Create a query that lists each movie, the film category it is classified in, and the number of times it has been rented out.**

**Question 2**

Now we need to know how the length of rental duration of these family-friendly movies compares to the duration that all movies are rented for. **Can you provide a table with the movie titles and divide them into 4 levels (first_quarter, second_quarter, third_quarter, and final_quarter) based on the quartiles (25%, 50%, 75%) of the rental duration for movies across all categories?** Make sure to also indicate the category that these family-friendly movies fall into.

**Question 3**

Finally, provide a table with the family-friendly film category, each of the quartiles, and the corresponding count of movies within each combination of film category for each corresponding rental duration category. The resulting table should have three columns:

- Category
- Rental length category
- Count

**Question 4**

We would like to know who were our top 10 paying customers, how many payments they made on a monthly basis during 2007, and what was the amount of the monthly payments. **Can you write a query to capture the customer name, month and year of payment, and total payment amount for each month by these top 10 paying customers?**







#### Steps involved in this project

[![Made with Python](https://forthebadge.com/images/badges/made-with-python.svg)](https://github.com/iamsivab/DVD-Rental-Store-SQL) [![Made with love](https://forthebadge.com/images/badges/built-with-love.svg)](https://www.linkedin.com/in/iamsivab/) [![ForTheBadge built-with-swag](http://ForTheBadge.com/images/badges/built-with-swag.svg)](https://www.linkedin.com/in/iamsivab/)

#### Explanation

### Libraries Used

![R Studio](https://img.shields.io/badge/R-dplyr-blue.svg?style=flat&logo=r&logoColor=white) 
![R Studio](https://img.shields.io/badge/R-stringr-blue.svg?style=flat&logo=r&logoColor=white)
![R Studio](https://img.shields.io/badge/R-readtext-blue.svg?style=flat&logo=r&logoColor=white) 
![R Studio](https://img.shields.io/badge/R-e1071-blue.svg?style=flat&logo=r&logoColor=white) 
![R Studio](https://img.shields.io/badge/R-mlr-blue.svg?style=flat&logo=r&logoColor=white)
![R Studio](https://img.shields.io/badge/R-caret-blue.svg?style=flat&logo=r&logoColor=white) 
![R Studio](https://img.shields.io/badge/R-randomForest-blue.svg?style=flat&logo=r&logoColor=white) 


### Installation

- Install **randomForest** using pip command: `install.packages("randomForest")`
- Install **caret** using pip command: `install.packages("caret")`
- Install **mlr** using pip command: `install.packages("mlr")`
- Install **MASS** using pip command: `install.packages("MASS")`

### How to run?

[![R Studio](https://img.shields.io/badge/R-clean_data.R.-lightgrey.svg?logo=R&style=social)](https://github.com/iamsivab/DVD-Rental-Store-SQL/tree/master/src)


### Project Reports

[![report](https://img.shields.io/static/v1.svg?label=Project&message=Report&logo=microsoft-word&style=social)](https://github.com/iamsivab/DVD-Rental-Store-SQL/blob/master/Sivasubramanian-Text%20Mining%20Report.pdf)

- [Download](https://github.com/iamsivab/DVD-Rental-Store-SQL/blob/master/Sivasubramanian-Text%20Mining%20Report.pdf) for the report.

### Useful Links

1. [Why Term Frequency is better than TF-IDF for text classification](https://www.quora.com/Why-does-TF-term-frequency-sometimes-give-better-F-scores-than-TF-IDF-does-for-text-classification)
 
### Related Work

[![Sentiment Analysis](https://img.shields.io/static/v1.svg?label=Text&message=Mining&color=lightgray&logo=linkedin&style=social&colorA=critical)](https://www.linkedin.com/in/iamsivab/) [![GitHub top language](https://img.shields.io/github/languages/top/iamsivab/DVD-Rental-Store-SQL.svg?logo=php&style=social)](https://github.com/iamsivab/)

[Text Mining Analyzer](https://github.com/iamsivab/DVD-Rental-Store-SQL) - A Detailed Report on the Analysis


### Contributing

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?logo=github)](https://github.com/iamsivab/DVD-Rental-Store-SQL/pulls) [![GitHub issues](https://img.shields.io/github/issues/iamsivab/DVD-Rental-Store-SQL?logo=github)](https://github.com/iamsivab/DVD-Rental-Store-SQL/issues) ![GitHub pull requests](https://img.shields.io/github/issues-pr/viamsivab/DVD-Rental-Store-SQL?color=blue&logo=github) 
[![GitHub commit activity](https://img.shields.io/github/commit-activity/y/iamsivab/DVD-Rental-Store-SQL?logo=github)](https://github.com/iamsivab/DVD-Rental-Store-SQL/)

- Clone [this](https://github.com/iamsivab/DVD-Rental-Store-SQL/) repository: 

```bash
git clone https://github.com/iamsivab/DVD-Rental-Store-SQL.git
```

- Check out any issue from [here](https://github.com/iamsivab/DVD-Rental-Store-SQL/issues).

- Make changes and send [Pull Request](https://github.com/iamsivab/DVD-Rental-Store-SQL/pull).
 
### Need help?

[![Facebook](https://img.shields.io/static/v1.svg?label=follow&message=@iamsivab&color=9cf&logo=facebook&style=flat&logoColor=white&colorA=informational)](https://www.facebook.com/iamsivab)  [![Instagram](https://img.shields.io/static/v1.svg?label=follow&message=@iamsivab&color=grey&logo=instagram&style=flat&logoColor=white&colorA=critical)](https://www.instagram.com/iamsivab/) [![LinkedIn](https://img.shields.io/static/v1.svg?label=connect&message=@iamsivab&color=success&logo=linkedin&style=flat&logoColor=white&colorA=blue)](https://www.linkedin.com/in/iamsivab/)

:email: Feel free to contact me @ [balasiva001@gmail.com](https://mail.google.com/mail/)

[![GMAIL](https://img.shields.io/static/v1.svg?label=send&message=balasiva001@gmail.com&color=red&logo=gmail&style=social)](https://www.github.com/iamsivab) [![Twitter Follow](https://img.shields.io/twitter/follow/iamsivab?style=social)](https://twitter.com/iamsivab)


### License

MIT &copy; [Sivasubramanian](https://github.com/iamsivab/DVD-Rental-Store-SQL/blob/master/LICENSE)

[![](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/images/0)](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/links/0)[![](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/images/1)](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/links/1)[![](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/images/2)](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/links/2)[![](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/images/3)](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/links/3)[![](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/images/4)](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/links/4)[![](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/images/5)](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/links/5)[![](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/images/6)](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/links/6)[![](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/images/7)](https://sourcerer.io/fame/iamsivab/iamsivab/DVD-Rental-Store-SQL/links/7)


[![GitHub license](https://img.shields.io/github/license/iamsivab/DVD-Rental-Store-SQL.svg?style=social&logo=github)](https://github.com/iamsivab/DVD-Rental-Store-SQL/blob/master/LICENSE) 
[![GitHub forks](https://img.shields.io/github/forks/iamsivab/DVD-Rental-Store-SQL.svg?style=social)](https://github.com/iamsivab/DVD-Rental-Store-SQL/network) [![GitHub stars](https://img.shields.io/github/stars/iamsivab/DVD-Rental-Store-SQL.svg?style=social)](https://github.com/iamsivab/DVD-Rental-Store-SQL/stargazers) [![GitHub followers](https://img.shields.io/github/followers/iamsivab.svg?label=Follow&style=social)](https://github.com/iamsivab/)
