# Data Pipeline with Azure

This project is a complete data pipeline using different Azure services. Although the origins of the data are not available anymore, you can review all the source data located into a branch called data_sources.

Lets have a little review of the ETL process and Azure servvices involve:

- Extraction:
  - The main data source is a Blob storage configured in an Storage Account that allows Hierarchical Namespace complemented by Data Lake Storage Gen2 endpoint.
  - There is also a HTTP data extraction module that allows us to extract data from a public endpoint.
- Transform:
  - For transformation we use Data Flow. It allows us to make basic transformation to our data assets. Also, it is easy to set up and integrate to our data pipelines. In my opinion, it is a good tool but I feel more control over transformation process when I write my own code.
- Load:
  - The best way to store data after a pipeline process is finished is in a Data Lake. In this case we use the same Blob Storage service that we create for the Extraction phase. However, it is important to have in mind that the data in this case is part of an staging process. Is better if there is some extra steps that upload the data into a Database.

If you are interesting to learn more about programming with Python and backend development please check my notes:

- [Algorithms](https://drive.google.com/file/d/1e72w53UL7udKEjXqQ3TDJ7lvyY1VqcqF/view)
- [POO with Python](https://drive.google.com/file/d/1pud53b66uLaWs0rKYCsoqygSnXZqtWLy/view)
- [Django](https://drive.google.com/file/d/1-NrgiLMRyXBIjHABq759OGGmGZL9QtWH/view)
- [FastAPI](https://drive.google.com/file/d/1e72w53UL7udKEjXqQ3TDJ7lvyY1VqcqF/view)
- [Databases](https://drive.google.com/file/d/10MDw_llXH3bQwYK7jlJo7ahotsHSM6hX/view)
- [SQL](https://drive.google.com/file/d/1DHNKuA1FnyRUByQTc_3gONyJ4C0gO1_8/view)

To see other learning projects and notes please follow this [link](https://imdiego.dev/projects/projects/notes).
To see more about my please visit [my webpage](https://imdiego.dev/).
