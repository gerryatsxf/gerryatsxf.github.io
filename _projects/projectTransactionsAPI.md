---
layout: post
title: Planner - Scripts API
description: Script-oriented API that eases out parsing of financial data. Featuring Pandas, Numpy and BeautifulSoup
---


[Transactions API](https://github.com/gerryatsxf/transactions-api)
============

Script-oriented API that eases out parsing of financial data. Featuring Pandas, Numpy and BeautifulSoup

Featuring:

  * Swagger
  * Flask
  * Dependency injection (kink)
  * Unit testing (unittest)
  * Pandas
  * Numpy
  * BeautifulSoup
  * Docker

At the time of writing this, the [Transactions API](https://github.com/gerryatsxf/transactions-api) is able to parse .csv files downloaded from Santander MX into a usable JSON format, along with other endpoints dedicated to:
  * Serializing the transactions and assigning a pseudo-identifier value to each record
  * Conceal records in file in order to filter out new records that aren't present in the users selected [YNAB](https://ynab.com) budget

