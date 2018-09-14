# Astrosat Tech Talk Series - 07/09/2018
NOTE: was rescheduled to 14/09/2018

## Description
As part of the Astorsat internal Tech Talk series, the notebook here was presented to describe the challenges, limitations, and options available when automatically processing Landsat 8 (and optical satellite images in general) for display in user interpretable and friendly manner.

## Setup
The code was written in a Python 3.7 virtualenv, but may work in early versions of Python 3.
It is recommended to setup a Python 3.7 environment therefore.

From in the environment, requirements can be installed with:
```
pip install -r requirements.txt
```

To view and edit the notebook:
```
jupyter notebook Tech_Talk_20180907.ipynb
```

To run the presentation in the browser:
```
jupyter nbconvert Tech_Talk_20180907.ipynb --to slides --post serve
```