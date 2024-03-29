<!--
**icapetti/icapetti** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Welcome!
### Here is something about me

### Data Engineering projects
#### Crawlers
- [News Crawler - a Scrapy spider that crawls news and run in a Docker Container](https://github.com/icapetti/news-crawler)
<br>Extract textual data relating to news. The output of this crawler is particularly useful for researches with NLP, Computational Linguistics and Analytical intelligence with grouped texts. 
  - Runs on a Docker container
  - The items crawled from the website are saved as jsonlines, compressed with gzip and send to a bucket on AWS.

- [ANP Crawler - a Scrapy spider that crawls fuel prices](https://github.com/icapetti/anp-crawler)
<br>This crawler extracts data from ANP research on fuels and has two quality layers implemented: 
  - There is a Pipeline for data standardization, validate if the data are in the defined structure and typing, monitor the crawler statistics, such as minimum amount of extracted items, unwanted http status, errors, etc.
  - Alerts to a Slack channel if one or more monitors failed
  - All this process run in a EC2 instance on AWS and Circle CI is used to manage the deploy process from Github to the EC2 instance
    
  The extracted data is saved in a gzip-compressed jsonlines file and sent to an AWS S3 bucket.

### Courses in progress or completed
- #### [Advanced SQL: MySQL Data Analysis & Business Intelligence](https://github.com/icapetti/advanced-mysql-for-analysis-and-bi)
Here I built an environment to practice the sql exercices proposed by the course, with docker compose to setup the Mysql Instance (the course database) and the Metabase instance (so I can run the queries over the Mysql database and build some analysis with charts and dashboards).
- #### [100 days of code: complete Python bootcamp!](https://github.com/icapetti/100-days-of-code-python-bootcamp)

### Various
- [Smart River - System for monitoring the level of rivers](https://github.com/icapetti/tcc_arduino)
<br>My college graduation capstone project: an android app for monitoring the level of rivers. 
The data is collected by sensors that communicate with a central through LoRa wireless technology, present on an Arduino MKR board. 
The central, an ESP8266 board, consolidates the data and sends it to the database via Wi-Fi, which is finally accessed by the android application.

