# Big Data
'''  
│
├── Postlab 1
│ └── Lab5_Spark_II.ipynb
│
├── Postlab 2
│ └── Post_lab2.ipynb
│
└── project
└── hdfs-spark
├── hdfs-conf
├── notebook
├── spark-conf
├── .env.spark
├── Dockerfile
├── commands.txt
├── docker-compose.yaml
└── entrypoint.sh
'''  

## Description
This repository is a comprehensive collection of labs, postlabs, and a full project environment designed for practical learning and development in Big Data processing using **Apache Spark** and **Hadoop Distributed File System (HDFS)**.

**Postlab 1 & 2:**  
  These folders contain Jupyter notebooks (`Lab5_Spark_II.ipynb` and `Post_lab2.ipynb`) which provide hands-on exercises and examples to deepen your understanding of Spark’s core concepts, including data transformations, actions, Spark SQL, and performance optimization techniques.

**Project (`hdfs-spark`):**  
  This folder hosts a full-scale project setup to simulate a big data environment. It includes:
  - **HDFS configuration files (`hdfs-conf`)** to set up and customize your Hadoop file system.
  - **Spark configuration files (`spark-conf`)** for tuning Spark cluster parameters.
  - **Docker-related files** (`Dockerfile`, `docker-compose.yaml`, `.env.spark`, `entrypoint.sh`) that automate deployment of a containerized Spark and HDFS cluster, enabling you to quickly spin up a local big data environment for development and testing.
  - **Notebooks (`notebook`)** that complement the project with Spark workflows and data processing examples.
  - **`commands.txt`** listing frequently used commands for interacting with the environment, container management, and troubleshooting.

This setup enables a realistic simulation of distributed data processing pipelines on a local machine, facilitating both learning and experimentation without the need for a full cluster setup.

## Usage

### Running Postlabs

1. Navigate to the `Postlab 1` or `Postlab 2` directory.
2. Open the Jupyter notebooks (`Lab5_Spark_II.ipynb` or `Post_lab2.ipynb`) using JupyterLab or Jupyter Notebook.
3. Follow the instructions within the notebooks to perform Spark data processing exercises, explore Spark APIs, and analyze sample datasets.



