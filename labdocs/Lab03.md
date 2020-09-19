# Training and Registering Models

Machine Learning is primarily about training models that you can use to provide predictive services to applications; so now it's time to see how you can use Azure Machine Learning experiments to run training scripts, and how to register the resulting trained models.

## Before You Start

Before you start this lab, ensure that you have completed the *Create an Azure Machine Learning Workspace* and *Create a Compute Instance* tasks in [Getting Started with Azure Machine Learning](Lab01.md). Then return to this lab.

## Use the Azure Machine Learning SDK to Train and Register Models

In this task, you'll use code in a notebook to run training scripts as Azure Machine Learning experiments.

1. In [Azure Machine Learning studio](https://ml.azure.com), view the **Compute** page for your workspace; and on the **Compute Instances** tab, ensure your compute instance is running. If not, start it.
2. When the compute instance is running, click the **Jupyter** link to open the Jupyter home page in a new browser tab.
3. In the Jupyter home page, in the **Users/ps_flight_delays** folder, open the **3-Build&Register_the_Model.ipynb** notebook. Then read the notes in the notebook, running each code cell in turn.

    > **Tip**: If you cloned the repository previously, and the notebook file is not in the **Users/ps_flight_delays** folder, open a new terminal in your Jupyter environment and run the following commands to refresh the lab files (overwriting any changes you have made):

    ```bash
    cd Users/ps_flight_delays
    git reset --hard HEAD
    git pull
    ```

> **Important**: When you have finished the lab, close all Jupyter tabs and **Stop** your compute instance to avoid incurring unnecessary costs.
