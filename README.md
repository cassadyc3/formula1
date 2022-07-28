# formula1
This repository includes both scripts for a group and personal project for Formula 1 using PySpark.

The script "Group D MDA Formula 1 Final.ipynb" is from a Group Project for my Master's Degree. In this notebook there is both Tweet Analysis and Machine Learning Predictions. The tweets were imported using Nifi and the #formula1. Our predictions combined datasets of drivers, constructors, qualifications, race outcomes, and tracks to predict the number of points drivers will earn by the end of a season.

The second script "F1_personal" is a continuation of the previous problem. The initial idea was to rank each driver at the end of a race based on the track, constructor, and qualifying position, but I realized that this approach would be a multi-class classification problem. Thus, I decided to change courses to predict the number of points a driver would earn given a specific race, location, and qualifying position. The output gives results but the code, data, and approach need work.
