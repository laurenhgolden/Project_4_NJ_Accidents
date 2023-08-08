# Project 4

Rutgers Data Sciences Bootcamp, (8 August 2023)

- [Anika Dinger](https://github.com/adinger1)
- [Lauren Golden](https://github.com/laurenhgolden)
- [Justine Owsik](https://github.com/jowsik)
- [MJ Teng](https://github.com/jowsik)

New Jersey has the second highest population density in the United States, behind the District of Columbia. And with this high population density comes lots of traffic and congestion on roadways. Despite being ranked highly for safe drivers, accidents are very common. We are also curious as to which factors impact accident severity most. Through this project, we built a Random Forest machine learning model to predict the severity of the accident, and determine the most significant features that impact these accidents.

## Questions:
- What factors contribute most to the severity of a car accident's impact on traffic?

## Analysis Goals:
- Identify the most important features of the dataset
    - Environmental factors (weather conditions, temperature, humidity, etc)
    - Traffic controllers (stop signs, traffic signals, roundabouts)

- Determine accident severity accuracy through machine learning 


## Conclusion:
- The most significant features that affect an accident's severity and impact on traffic were Year (likely due to the pandemic), Distance, and Weather Conditions (primarily Fair, Overcast or Clear).

## Data Sources

- [US Accidents (2016 - 2023) via Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents?resource=download)- 
- [Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.](https://afdc.energy.gov/data/10304)


## Built With

- Python with Pandas
- Jupyter Notebook
- Matplotlib
- Scikit-Learn
- Imbalanced-Learn

## Installation

In order to correctly run our code, ensure you have installed the libraries noted above to correctly run the Jupyter notebooks. In order to run the code, start by running the NJ_Data_Preprocessing, and then run the Random_Forest_Model code. If you would like to view the original CSV with the US data, you can look on the kaggle, as it is uploaded with our gitignore.

## Tools and Sources

- Python with Pandas
- Jupyter Notebook
- Matplotlib
- Scikit-Learn
- Imbalanced-Learn
- GitHub
- Tableau (see visualizations here: https://public.tableau.com/views/SeverityofNewJerseyCarAccidents/NewJerseyMap?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
