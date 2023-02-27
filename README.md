# Scraper with Cloud Deployment

This project is a web scraper designed to extract data from a website and store it in a database. The scraper is deployed on AWS Elastic Beanstalk using Python and the Flask web framework.

# Getting Started
To get started with this project, you will need to set up the AWS Elastic Beanstalk environment and deploy the application. You will also need to set up the database and configure the application to connect to the database.

# Prerequisites
To deploy the scraper on AWS Elastic Beanstalk, you will need an AWS account and the AWS Command Line Interface (CLI) installed on your computer. You will also need a database, such as MySQL or PostgreSQL, set up and running.

# Installation
To install the scraper, clone the repository to your local machine:

```sh
git clone https://github.com/FahimaChowdhury/scrapper.git
```

# Next, create a virtual environment and install the dependencies:

```sh
pip install -r requirements.txt
```
# Deployment
To deploy the scraper on cloud (AWS Elastic Beanstalk), follow these steps:

- Set up an Elastic Beanstalk environment using the AWS Management Console or the AWS CLI.
- Create an Elastic Beanstalk application using the AWS Management Console or the AWS CLI.
- Deploy the application using the AWS Management Console or the AWS CLI.
- For more detailed instructions on deploying a Flask application on Elastic Beanstalk, see the official AWS documentation.

# Configuration
To configure the scraper, edit the application.py file and set the database connection details:

```sh
DB_USER = 'username'
DB_PASSWORD = 'password'
DB_HOST = 'hostname'
DB_NAME = 'database_name'
```

You can also set other configuration options, such as the URL to scrape and the time interval between scrapes.

# Running the Scraper
To run the scraper, activate the virtual environment and run the application.py file:
```sh
python application.py
```
