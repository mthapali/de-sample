# data-science-on-gcp


### Updates to book
The pace of change in cloud computing is incredible, so it's not surprising that there are topics that were not covered in the book, but which are important. These articles update the book in the sections stated:

| Where it goes | Link to article | Key update |
|---|---|---|
| Addition to Ch 5 | [How to train and predict regression and classification ML models using only SQL — using BigQuery ML](https://towardsdatascience.com/how-to-train-and-predict-regression-and-classification-ml-models-using-only-sql-using-bigquery-ml-f219b180b947) | You can start experimenting with Machine Learning models much earlier, in the data exploration phase itself. |
| Replace last section of Ch 2 | [Scheduling data ingest using Cloud Functions and Cloud Scheduler](https://towardsdatascience.com/scheduling-data-ingest-using-cloud-functions-and-cloud-scheduler-b24c8b0ec0a5) | A better way to do periodic data ingest: instead of using AppEngine Cron, use Cloud Scheduler to launch a Cloud Function. |
| Update Ch 9 | [How to deploy Jupyter notebooks as components of a Kubeflow ML pipeline](https://towardsdatascience.com/how-to-deploy-jupyter-notebooks-as-components-of-a-kubeflow-ml-pipeline-part-2-b1df77f4e5b3) | Developing a TensorFlow model in a notebook is now best done using the Keras API, in Eager mode. You can even quickly run the notebook routinely using Kubeflow pipelines, while you extract the pieces out into containerized components for production. |
# de-sample
