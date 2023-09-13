# ETL Implementation: An Introductory Database Design Project

## Introduction
This project showcases fundamental skills in the domains of data sourcing, cleaning, and relational database design. We extracted datasets from various sources, cleaned and transformed the data, and structured it into a relational database, which is visually represented by an Entity-Relationship Diagram (ERD).

## Table of Contents
- [Dataset Information](#dataset-information)
- [Database Design Development](#database-design-development)
- [Importing Data into Postgres](#importing-data-into-postgres)
- [Primary Keys and Foreign Keys](#primary-keys-and-foreign-keys)
- [ERD](#erd)
- [Questions](#questions)
- [Key Insights from Analysis](#key-insights-from-analysis)
- [Queries](#queries)

## Dataset Information
- **Source:** IMDB Dataset (Dated: 29/3/2023)
- **Tables included:** 
  - Title.akas
  - Title.basics
  - Name.basics
  - Title.episode
  - Title.ratings

## Database Design Development
The datasets were meticulously examined to ascertain the relationships among the tables. Following this examination, we formulated an initial design for the database. This design strategy involved decisions regarding the introduction of new tables in subsequent stages, inclusive of fact and dimension tables.

## Importing Data into Postgres
A robust database structure was created using Postgres. In this setup, tables were clearly defined, followed by data import procedures.

## Primary Keys and Foreign Keys
During the table creation phase, we assigned primary and foreign keys. These keys were meticulously referenced to their respective tables to ensure data integrity and relationships.

## ERD (Entity Relationship Diagram)
For a holistic and visual representation of table relations, an ERD was crafted using Postgres.

## Questions
Throughout this project, we delved into various analytical questions, such as:

- What's the average rating and total votes across different categories?
- How many titles made their appearance in the most recent year?
- What are the specific breakdowns when considering titles across each category?

## Key Insights from Analysis
A few pivotal insights derived from the analysis include:

- A majority inclination towards movies in the 2022 dataset.
- The leading genres were Drama, Documentary, and Comedy.
- We observed certain inconsistencies in the duration data representation, particularly for TV mini-series.

For a comprehensive understanding and further data break-down, please navigate to the Insights segment of the project documentation.

## Queries
We have incorporated a rich set of SQL queries, tailor-made to draw insights from the dataset. These queries encompass areas like understanding average ratings, identifying dominant genres, exploring regional data variations, among others.
