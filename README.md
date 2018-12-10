# seek-fraud-box

A box came from TC SHENZHEN Hackathon 2018. This box is contributed by [Emil](https://github.com/emil-balashov).

## Introduction

The Ontofraud team (Emil Balashov, Ruslan Dautov and Vlad Sergeev) has built the web-service to check and prevent fraudulent transactions based on Ontology blockchain technology. The web service provides the tool to make the transactions as Trusted, OK, New, Suspicious and Fraudulent. Although, the main functionality is deep search algorithm which analyzes a graph of transactions based on Pandas and Networkx.

## Getting started

- init python virtual environment.
- install needed packages `pip install -r requirements.txt`.
- install PostgreSQL and create a DB `onto`, it should be avialble by URL: `postgres://localhost:5432/onto'`.
- run `./manage.py migrate`.
- run `./manage.py collectstatic`.
- Then run the server `./manage.py runserver`.