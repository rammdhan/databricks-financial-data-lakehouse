# Databricks Financial Data Lakehouse

**End-to-End Data Engineering Project** for transforming raw SEC financial filings into **AI-ready data** using the **Databricks Lakehouse Platform (Free Edition)**.

---

## Overview

This project demonstrates how a **Data Engineer** can build a **streaming data pipeline** that ingests, transforms, and prepares financial reports from the U.S. Securities and Exchange Commission (SEC) into a structured, queryable, and AI-ready dataset.
The final output is a **Lakehouse architecture** that supports **Retrieval-Augmented Generation (RAG)** use cases — enabling AI chatbots or analytical models to access structured financial knowledge efficiently.

---

## Objectives

- Build a **streaming ingestion pipeline** for JSON-based SEC filings  
- Transform and normalize raw financial data (Balance Sheet, Income Statement, Cash Flow)  
- Convert structured data into **textual documents** suitable for AI models  
- Generate **vector embeddings** and assemble a **Databricks Vector Search Index**

---

## Flow
<p align="center">
  <img width="651" height="401" alt="sec-finance drawio" src="https://github.com/user-attachments/assets/66b9cdbf-1aba-46c9-b7ab-9716b06873f1" />
</p>

---

## Datasets
SEC Financial Reports: https://www.kaggle.com/datasets/pranjalverma08/sec-edgar-annual-financial-filings-2021
