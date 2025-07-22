# Open Source Medallion Architecture with Spark & Delta Lake

This project is a learning playground to implement the **Medallion Architecture** (Bronze → Silver → Gold layers) using **Apache Spark**, **Delta Lake**, and **Docker** for local development.

---

## Project Overview

The Medallion Architecture organizes data pipelines into three layers:

- **Bronze:** Raw ingested data, as close to the source as possible.
- **Silver:** Cleaned, filtered, and enriched data.
- **Gold:** Curated, aggregated data ready for analytics and reporting.

This project demonstrates how to build these layers locally with open-source tools, giving you hands-on experience with Spark processing, Delta Lake tables, and containerized environments.

---

## Why This Project?

- Gain practical experience with Spark and Delta Lake without relying on managed cloud platforms.
- Understand how a Medallion pipeline works step-by-step.
- Learn how Docker simplifies managing complex environments and dependencies.
- Build a reusable template for your future data engineering projects.

---

## Features

- Local Spark cluster running in Docker
- Delta Lake for ACID-compliant data storage and versioning
- PySpark scripts for data transformation between layers
- Jupyter notebooks for interactive exploration and development
- Clear folder structure reflecting the Medallion layers

---

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/) installed and running
- Basic knowledge of Python and PySpark
- Familiarity with command line / terminal

---
