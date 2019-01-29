# Notebooks and synthetic data for AI OpenScale demo with German Credit data

The notebooks and data in this repo will allow you to explore the capabilities of [IBM AI OpenScale](https://www.ibm.com/cloud/ai-openscale). There are two main notebooks to work with:
  * The [lab notebook](https://raw.githubusercontent.com/emartensibm/german-credit/master/german_credit_lab.ipynb) will allow you to train, save and deploy the German Credit Risk model, and configure AI OpenScale to monitor that deployment.
  * The [end-to-end notebook](https://raw.githubusercontent.com/emartensibm/german-credit/master/german_credit_train_and_config.ipynb) does all of the above, and additionally uses Apache Spark with Watson Studio to configure continuous learning for your model.
  
Finally, you can use the [credit feed notebook](https://raw.githubusercontent.com/emartensibm/german-credit/master/german_credit_scoring_feed.ipynb) to regularly send data to your models, allowing for a continuous feed of predictions for OpenScale to monitor.
  
Right-click on the notebook you wish to run and select **Save As...** to download the file. To import the notebook into Watson Studio:
  * Open [Watson Studio](https://dataplatform.ibm.com)
  * Click **Create a project** and select a **Standard** project
  * Give your project a name, select an existing object storage instance or create a new one, and click **Create**
  * Once your project has been created, click on the **Assets** tab, click on **Add to project** at the top of the screen, and select **NOTEBOOK**
  * On the **New Notebook** screen, select **From file**, choose the notebook file you downloaded, select the **Default Spark Python...** option, and click **Create notebook**

You may now continue following the instructions contained in the notebook.
