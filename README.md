# TSF 2024 (Home Optimization of Sterilization Economically - HOSE)

Authors: Daisy Li, Kelly Wang

Home Optimization of Sterilization Economically (HOSE) is a project that intends to find the most economical way to sterilize household objects with materials available at home. This repository contains the Jupyter Notebook used to analyze the data with Python Pandas and Scikit-learn, and the Arduino sketch that drives the prototype.

The Data Processing folder contains the Jupyter notebook and related CSVs, while the Prototype folder contains the Arduino sketch and the early prototype script, which is in Python.

The Data Processing Jupyter Notebook processes the data that we have collected during experimentation with hot water and bacterial colony areas, and fits it to a linear regression model. Using the linear regression model, we can predict the amount of bacteria that will grow on a petri dish after holding it under boiling water for any amount of time. The Prototype is an Arduino device that can detect the amount of time an object is held under boiling water, and using our linear regression model, display  the object's "percentage sterilized" on an LCD screen.

You can see a demonstration of the prototype device at this link: https://youtu.be/hDZ--jbLrL8

Note: wither-rose is erynidye's (Daisy Li's) old account. All contributions are under that name.
