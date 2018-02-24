# Project 5: Brevet time calculator with Ajax and MongoDB
---------------------------------------------
Author: Yanhua Luo

Contact: yanhual@uoregon.edu

## Introduction
Simple list of controle times from project 4 stored in MongoDB database.
The "Submit" button would insert the entered control times into the database
The "Display" button would display the entries from the database

## Requirement/Installation
- Docker
- Python3

run command:
docker-compose build
docker-compsoe up


## Error Handle
- input negative control time would result in an "Invalid date" in both Open and Close section
- input empty control time would resulted in open an empty page.

