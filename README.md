# DBT and BigQuery Introductory Project

This project serves as an introductory exploration of **DBT (Data Build Tool)** and **BigQuery**. It is designed to help users understand the basics of data transformation and analytics using these powerful tools.

## Introduction

DBT is a command-line tool that enables data analysts and engineers to transform data in their warehouse more effectively. BigQuery is a fully-managed, serverless data warehouse that allows for super-fast SQL queries using the processing power of Google's infrastructure.

## Installation

To get started with this project, ensure you have the following installed:

- [DBT](https://docs.getdbt.com/docs/installation)
- [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/dbt-bigquery-intro.git
cd dbt-bigquery-intro
```

## Usage

1. Set up your DBT profile in `~/.dbt/profiles.yml` to connect to your BigQuery project.
2. Run the following command to execute the models:

```bash
dbt run
```

3. You can also test the models with:

```bash
dbt test
```

## Acknowledgments

- [DBT Documentation](https://docs.getdbt.com/docs/introduction)
- [BigQuery Documentation](https://cloud.google.com/bigquery/docs)
- Yusuf Ganiyu

Feel free to explore and modify the models as you learn more about DBT and BigQuery!
