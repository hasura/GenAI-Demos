# Prototype fast on your GenAI Apps

## Introduction
Hasura empowers you to rapidly create high-quality data APIs for production purposes. As data sources continue to evolve Hasura evolves as well, providing you with the capability to construct secure data APIs over versatile data stores, including vectorized data.

As part of Hasura's evolution, we're introducing [Hasura Notebook](), a tool designed to facilitate the swift prototyping of cutting-edge GenAI applications.

## Getting started with GenAI applications on Hasura
First step is to make sure you have Hasura CLI installed. If not get started with [Hasura CLI documentation]().

Use the Hasura CLI to start a new remote Hasura Notebook with templated projects of your choice using below commmand.

> command comes here 

## Project Template
Each branch starting with `project` is a project template. 

| Project Name| Details| Tech Stack | Link|
|---|---|---|--|
Smart Product Search | Smart search API.<br><br>User can not only search for product but also get answers to questions to help narrow the search effort.<br><br>Example:<br>What are the most durable products and why?<br>How is ProductX better than ProductY?| * Hasura Notebook<br>* Weaviate<br>* Hasura<br>* OpenAI| [Copy link](https://github.com/hasura/GenAI-Demos/tree/project/smart_product_search)|
|SRE assistant| Chatbot can help Site Reliability Engineers investigate issues quickly.<br><br>SREs can request questions on issue tickets to chatbot. Required context is fetched from ClickHouse telemetry tables and passed with prompt to OpenAI model to provide answers.<br><br>Example:<br>Run analysis on incident 2 and identify root cause of the issue.<br>Was there CPU outage on incident 5?| * Hasura Notebook<br>* ClickHouse<br>* Hasura<br>* OpenAI|[Copy link](https://github.com/hasura/GenAI-Demos/tree/project/clickhouse_sre_assistant)|


## Getting started with your own project
You can start Hasura Notebook with your own project as well. Private repos are not supported at the moment, so please make sure your repository is Public.
Only code within `server.ipynb` can be converted to endpoints.