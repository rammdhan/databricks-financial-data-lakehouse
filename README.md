# Databricks Financial Data Lakehouse

**End-to-End Data Engineering Project** for transforming raw SEC 10-K filings into **AI-ready knowledge documents** using the **Databricks Lakehouse Platform**.

---

## Overview

This project demonstrates how a **Data Engineer** can build a **streaming data pipeline** that ingests, transforms, and prepares descriptive SEC 10-K filings into a structured, searchable, and AI-ready dataset.
The final output is to create a **Lakehouse architecture** that supports **Retrieval-Augmented Generation (RAG)** use cases — enabling AI applications or chatbots to retrieve factual, context-rich financial knowledge directly from company filings.

---

## Objectives

- **Ingest** descriptive SEC filings (JSON format) using **Databricks Auto Loader** and Volumes 
- **Normalize** and **clean narrative** sections (Item_1, Item_1A, Item_7, etc.) in the Silver Layer
- Assemble **AI-ready documents** in the Gold Layer
- **Embed** and **index** those documents in a **Databricks Vector Search Endpoint** for RAG and chatbot retrieval

---

## Flow
<p align="center">
  <img width="651" height="401" alt="sec-finance drawio" src="https://github.com/user-attachments/assets/66b9cdbf-1aba-46c9-b7ab-9716b06873f1" />
</p>

---

## Tech Stack

- Databricks Lakehouse Platform (Free Edition)
- Delta Lake
- Auto Loader (cloudFiles)
- Unity Catalog & Volumes
- Vector Search & Embeddings
- PySpark / Databricks Notebooks

---

## Datasets
Source: https://www.kaggle.com/datasets/pranjalverma08/sec-edgar-annual-financial-filings-2021
