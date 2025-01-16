This is a guided project from a PostgreSQL specialization by Dr Charles Severance from the University of Michigan.

# Elasticsearch Data Ingestion Project

This project demonstrates how to ingest and index data into Elasticsearch using Python. Specifically, it focuses on processing book texts and email data, storing them in Elasticsearch for efficient search and retrieval.

## Overview

Elasticsearch is a powerful search engine capable of full-text search, real-time analytics, and more. This project showcases the process of taking raw data—in this case, books in text format and email dumps—and indexing them into Elasticsearch. Once indexed, this data can be queried and analyzed efficiently.

## Scripts

### `elasticbook.py`

This script processes a book in `.txt` format, slices the text into paragraphs, and stores each paragraph as a separate document in Elasticsearch.

### `elasticmail.py`

This script pulls email data from the web, processes it, and stores different parts of the email (such as sender, recipient, subject, and body) as separate documents in Elasticsearch.

## Resources

- [Elasticsearch Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html)
- [Python Elasticsearch Client](https://elasticsearch-py.readthedocs.io/en/latest/)

---

By following this guide, you can successfully ingest and index book and email data into Elasticsearch, enabling efficient search and analysis capabilities for your applications. 
