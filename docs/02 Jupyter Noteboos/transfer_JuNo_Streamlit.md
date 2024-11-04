---
title: Jupyter Notebooks - Streamlit Apps
layout: home
nav_order: 2
parent: Jupyter Notebooks
has_children: true
---

# Streamlit Apps

## Overview

Streamlit Apps are an excellent and user-friendly way to make the content of Jupyter Notebooks accessible. Streamlit Apps can be easily hosted in the Internet. They provide easy and fast access to Python Scripts. Streamlit Apps are very suitable for smaller Jupyter Notebooks that should be directly accessed, e.g., during a lecture or course.

## Streamlit Library

It is required to install the Streamlit library through the comand line and pip (open the command window, type 'pip install streamlit'). Once the library is installed, you can adapt existing python code (e.g., from an Jupyter Notebook) to work with streamlit. The main steps are subsequently explained.

## Transfer a Jupyter Notebook to an Streamlit APP

The following instructions consider an exsting interactive Jupyter Notebook that uses interactive sliders.

[The Jupyter Notebook is working with interactive sliders etc.]

1) Import Streamlit in the notebook

Add in the top section of the notebook (where the required libraries are noted) streamlit
'''import streamlit as st'''

2) It is assumed that the existing Jupyter Notebook implemented the sliders by the 'interact' functionality. Interact calls a function that contains the main functionality. This function is not longer required, therefore:

2.1) remove the function header

2.2) remove the intend of the code that was originally inside the function

3) Place all parameter that are required in the code (i.e., that were in the original Jupyter Notebook defined by the sliders) before the respective calls in the Python script.

3.1) As an initial step it is sufficient to just define the parameter value.
3.2) Check that the app is working. Open the comand window in the folder of the python script, start streamlit by typing '''Streamlit run NAME_OF_APP.py'''; the app should appear in a browser window (eventually run the app)
3.3) Implement sliders and similar functions to allow users to modify the parameters in the app.

4) Deploy the app through share.streamlit.io (see there for further instructions)