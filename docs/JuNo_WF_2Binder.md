---
title: Jupyter Notebooks - Workflow to MyBinder/Voila
layout: home
nav_order: 1
parent: Jupyter Notebooks - Templates, Tutorials, and Workflows
grand_parent: Jupyter Notebooks
---

# Jupyter Notebooks - Workflow to MyBinder/Voila

The following section contains information about generating a Voila Dashboard based on a Jupyter Notebook from a GitHub repository hosted by the MyBinder service. The MyBinder service is free and can be reached at https://mybinder.org/.

**Prerequisite:** A key step in the process is to define all Python libraries required to execute the Jupyter Notebook on the MyBinder server in an `environment.yml` file. (For an example, refer to the iNUX Jupyter Notebooks on https://github.com/gw-inux/Jupyter-Notebooks).

**Running Jupyter Notebooks through the MyBinder service**: When opening https://mybinder.org/ a user form appears that collects initial information about the address of the GitHub repository where the Jupyter Notebooks (together with the `environment.yml` file) are available. Additionally, the Git ref (referring to the specific location within the GitHub repository) is required. Typically, `HEAD` points to the main/master repository.

If you click **launch** without further information, you will generate a link that opens **Jupyter Lab** on your browser. However, if this is not what you intend (e.g., you like to open a specific Jupyter Notebook as Voila Dashboard in order to minimize trouble for users), you can further tailor the process of Notebook generation to your needs.

*Generating a link to run a single Jupyter Notebook as Voila Dashboard*

Further information is required to generate a Voila Dashboard from the Jupyter Notebook. An additional link is required in the textbox **URL to open (optional)**, which is `voila/render/PATH/TO/Notebook.ipynb`. Make sure that you select **URL** beside the textbox. Next, click the **launch** button to initiate the process of generating the MyBinder link. Then copy the URL of the MyBinder-Voila Notebook for further use.

<img src="\assets\images\JuNo\JuNo001.png" alt="**Figure:** MyBinder user interface to generate a Voila dashboard based on a suitable Jupyter Notebook" style="zoom:50%;" />

Generating a link to run a single Jupyter Notebook

To generate a direct link to a Jupyter Notebook, put `notebooks/PATH/TO/Notebook.ipynb` in the **URL to open (optional)** textbox. Next, click the **launch** button to initiate the process of generating the MyBinder link, and copy the URL of the MyBinder-Notebook for further use.

<img src="\assets\images\JuNo\JuNo002.png" alt="**Figure:** MyBinder user interface to generate a Jupyter Notebook based on a suitable Jupyter Notebook" style="zoom:50%;" />

