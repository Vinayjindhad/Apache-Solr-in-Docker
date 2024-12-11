# Apache-Solr-in-Docker


# Introduction

This project focuses on deploying Apache Solr, a powerful open-source search platform, within a Docker container and running it on a local host. By leveraging containerization technology, we can create an isolated and reproducible environment for deploying and experimenting with Solr. Docker simplifies the setup by bundling Solr and its dependencies into a lightweight container, showcasing the efficiency of managing open-source applications in a controlled manner.

# About Apache Solr

Apache Solr, part of the Apache Lucene project, is an open-source search platform widely recognized for its scalability, flexibility, and speed. It is used for full-text search, faceted search, real-time indexing, and analytics, making it a preferred choice for applications requiring advanced search capabilities.

# Key Features:

Open Source: Solr’s source code is publicly available, fostering innovation and collaboration.
Scalability: Designed to handle large datasets with distributed indexing and replication.
Rich Query Features: Supports powerful querying, including faceted search, spell checking, and result grouping.
Extensibility: Customizable through plugins and APIs to adapt to various use cases.
Cross-Platform: Compatible with Windows, Linux, and macOS, ensuring wide accessibility.
Steps to Setup and Run Apache Solr

# Step 1: Pulling the Docker Image

The first step is to download the Docker image for Apache Solr. This command fetches the official Solr image from Docker Hub:

**docker pull solr**

# Step 2: Create and Run a Docker Container

After downloading the image, instantiate a Docker container to run Apache Solr. The command binds port 8983 on the host machine to the Solr container, making it accessible locally:

**docker run -p 8983:8983 -t solr**

# Step 3: Accessing Apache Solr

Once the container starts successfully, Apache Solr can be accessed in a web browser by navigating to:

**http://localhost:8983**
This will open the Solr Admin interface, where you can manage cores, query data, and configure Solr settings.

# VIDEO



https://github.com/user-attachments/assets/75187152-17cd-413b-b2c2-80fca105261f

