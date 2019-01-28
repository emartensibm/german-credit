# Notebooks and synthetic data for AI OpenScale demo with German Credit data

The notebooks and data in this repo will allow you to explore the capabilities of [IBM AI OpenScale](https://www.ibm.com/cloud/ai-openscale). There are two main notebooks to work with:
  * The [lab notebook](https://raw.githubusercontent.com/emartensibm/german-credit/master/german_credit_lab.ipynb) will allow you to train, save and deploy the German Credit Risk model, and configure AI OpenScale to monitor that deployment.
  * The [end-to-end notebook](https://raw.githubusercontent.com/emartensibm/german-credit/master/german_credit_train_and_config.ipynb) does all of the above, and additionally uses Apache Spark with Watson Studio to configure continuous learning for your model.
  
Finally, you can use the [credit feed notebook](https://raw.githubusercontent.com/emartensibm/german-credit/master/german_credit_scoring_feed.ipynb) to regularly send data to your models, allowing for a continuous feed of predictions for OpenScale to monitor.
  
Right-click on a notebook like and select **Save As..** to download the file. All notebooks should be run in a [Watson Studio](https://dataplatform.ibm.com) project, using the **Python 3.5 with Spark** runtime environment.
