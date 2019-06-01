# Overview

This project implements log analysis of a newspaper site. Data is provided as a SQL database. It uses python to connect PostgreSQL to excute SQL queries for data analysis and prints results on console.

# Dependencies

- Virtual Machine
- Vagrant
- PostgreSQL database with log data
- Python

Above dependencies are provided as project prerequisites.

# Code Design

Project has one python source file `main.py`, It contains three functions, each for one problem statement of the project.

 - show_popular_articles
 - show_popular_authors
 - show_days_with_errors

Each of this function takes database connection object as input and prints desired output on console. These functions are invoked in sequence by main entrypoint code.

Sample output is provideed in `output.txt`

# Run

```bash
$ python main.py
```





