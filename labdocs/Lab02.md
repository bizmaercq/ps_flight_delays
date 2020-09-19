# Working with Data

Data is the foundation on which machine learning models are built. In this lab, you'll explore *datastores* and *datasets* in Azure Machine Learning.

So now it's time to see how you can use Azure Machine Learning to manipulate data

## Before You Start

Before you start this lab, ensure that you have completed the *Create an Azure Machine Learning Workspace* and *Create a Compute Instance* tasks in [Getting Started with Azure Machine Learning](Lab01.md). Then return to this lab.

## Use the Azure Machine Learning SDK to Train and Register Models

In this task, you'll use code in a notebook to run training scripts as Azure Machine Learning experiments.

1. In [Azure Machine Learning studio](https://ml.azure.com), view the **Compute** page for your workspace; and on the **Compute Instances** tab, ensure your compute instance is running. If not, start it.
2. When the compute instance is running, click the **Jupyter** link to open the Jupyter home page in a new browser tab.
3. In the Jupyter home page, in the **Users/ps_flight_delays** folder, open the **2-Working_with_Data.ipynb** notebook. Then read the notes in the notebook, running each code cell in turn.

    > **Tip**: If you cloned the repository previously, and the notebook file is not in the **Users/mslearn-aml-labs** folder, open a new terminal in your Jupyter environment and run the following commands to refresh the lab files (overwriting any changes you have made):

    ```bash
    cd Users/ps_flight_delays
    git reset --hard HEAD
    git pull
    ```

> **Important**: When you have finished the lab, close all Jupyter tabs and **Stop** your compute instance to avoid incurring unnecessary costs.
