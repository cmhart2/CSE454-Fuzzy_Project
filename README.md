Fuzzy Inference Engine
==


About
---

This project utilizes a fuzzy inference engine in order to make the decisions for a robot which must navigate from a starting point to a destination point.

Getting Started
----

Open the directory in MATLAB R2021b. Run the file `fuzzy_project_cmhart2.mlx`. Upon running, you should see a small prompt pop up. Enter the robot's starting X and Y-coordinates which can range from 0 to 100, then click "OK". Another prompt should pop up, in which you should enter the robot's destination X and Y-coordinates and click "OK" to continue.

At this point, a new window will open in the MATLAB Fuzzy Logic Designer. This is the Rule Viewer for this project\'s fuzzy membership functions. In the rule viewer, you are able to set the two input values, distance and phi, by dragging and clicking the vertical red bar. Upon doing so, you should notice the output variables, linear_velocity and angular_velocity changing based on the input values.

Requirements
----

[MATLAB version R2021b](https://www.mathworks.com/products/new_products/latest_features.html)
[MATLAB Fuzzy Logic Designer](https://www.mathworks.com/help/fuzzy/fuzzylogicdesigner-app.html#:~:text=The%20Fuzzy%20Logic%20Designer%20app%20lets%20you%20design%20and%20test,remove%20input%20and%20output%20variables.)
