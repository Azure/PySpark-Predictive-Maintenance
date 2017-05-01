
# Predictive Maintenance using PySpark

Predictive maintenance is one of the most commonly seen machine learning use cases. With the advancement of information technology nowadays, the volume of data is growing faster than ever before. Therefore, it is useful and necessary to leverage big data analytics capabilities to efficiently transform large amount of data into business intelligence. In the past, we have published a series of learning materials including blogs, modeling guide and sample tutorials in the domain of predictive maintenance. In this tutorial, we will illustrate a detailed step-by-step process starting from raw input data all the way till model development. 


## Input Data

The input data is simulated and consists of features that are generic for most of the predictive maintenance scenarios. For a relatively quick iteration, this sample data is only about 1.3 GB but the whole PySpark framework could be easily applied to a much larger dataset. The data is hosted on a publicly accessible Azure Blob Storage container and you can download a copy by clicking the link below. In our tutorial, we imported the data directly from the blob storage. 

https://pysparksampledata.blob.core.windows.net/sampledata/sampledata.csv



## Jupyter Notebooks

There are  three Jupyter Notebooks on this GitHub repository. 

| File Name | Description |
|-----------|-------------|
| Notebook_1_DataCleansing_FeatureEngineering | Data cleansing, exploration and some parts of feature engineering. |
| Notebook_2_FeatureEngineering_RollingCompute | How to deal with large amount of rolling feature compute. This was one of the major road blocks. |
| Notebook_3_Labeling_FeatureSelection_Modeling | Over-labeling technique, feature reduction, down-sampling, modeling, hyper-parameter tuning, cross-validation. |

We formatted this tutorial as Jupyter notebooks because it is easy to show the step-by-step process this way. You can also easily compile the executable PySpark script(s) using your favorite IDE.

## Hardware Specifications

The hardware used in this tutorial is a Linux Data Science Virtue Machine with 32 cores and 448 GB memory. For more detailed information of the Data Science Virtue Machine, please visit the link below. You do not really need such powerful machine for 1.3 GB of data, so you can choose the hardware configuration that is appropriate for your specific use case. You can also download the Jupyter Notebooks and run them on any machine that has PySpark enabled. 

https://docs.microsoft.com/en-us/azure/machine-learning/machine-learning-data-science-linux-dsvm-intro


## References

1.  https://blogs.technet.microsoft.com/machinelearning/2016/04/21/predictive-maintenance-modelling-guide-in-the-cortana-intelligence-gallery/

2.  https://gallery.cortanaintelligence.com/Collection/Predictive-Maintenance-Modelling-Guide-1

3.  https://gallery.cortanaintelligence.com/Notebook/Predictive-Maintenance-Modelling-Guide-R-Notebook-1

4.  https://gallery.cortanaintelligence.com/Notebook/Predictive-Maintenance-Modelling-Guide-Python-Notebook-1

5.  https://gallery.cortanaintelligence.com/Solution/Predictive-Maintenance-10

6.  https://gallery.cortanaintelligence.com/Experiment/Predictive-Maintenance-Template-2


## Contributing and Adapting

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
