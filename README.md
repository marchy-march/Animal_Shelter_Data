## **Interactive Map of Austin Animal Center Data** 
This EDA project aims to map out the data provided by Austin Animal Center in order to visualize the rescue locations, animal type and intake condition. Although this project serves mainly as a way to practice and implement new tools for me, I would like for it to be a tool to better understand why so many domestic pets end up for adoption. The map can be used to analyze if the intake condition (i.e 'Normal', 'Injured', 'Sick', 'Nursing', 'Aged', 'Other', 'Feral', 'Medical', 'Pregnant', 'Behavior') and/or intake type (i.e 'Stray', 'Public Assist', 'Wildlife', 'Owner Surrender', 'Abandoned', 'Euthanasia Request') could be influenced by or related to the found location. This could potentially be used to develop solutions taylored to the community and to better understand how to help pet owners and pets before a rescue is needed.

The end result of this project is a map of Houston, Texas with color coded data points that represent each animal (cat, dog, bird or other), where it was found and what type of intake took place (i.e 'Stray', 'Public Assist', 'Wildlife', 'Owner Surrender', 'Abandoned', 'Euthanasia Request'). 
It was done entirely in Jupyter Notebook using Pandas, Bokeh, Geopy and Google Maps. 

Data obtained from: Austin Animal Center via Daoud, J. (2021). Animal Shelter Analytics. Kaggle. https://www.kaggle.com/datasets/jackdaoud/animal-shelter-analytics

#**Do you want to run this project or make a similar one? Here is everything you need to download:**
from dotenv import load_dotenv
* pandas
* bokeh 
  - from bokeh.io import output_notebook, show
  - from bokeh.plotting import gmap, figure
  - from bokeh.models import GMapOptions, ColumnDataSource, CategoricalColorMapper, Legend
  - from bokeh.transform import factor_cmap, factor_mark
  - from bokeh.palettes import Bokeh8
* geopy
  - from geopy.geocoders import GoogleV3, Nominatim
  - geopy.distance
* googlemaps

#**Want to read more about this project?**
Check out my [medium article](https://medium.com/@marciapedrozajv/austin-animal-shelter-data-interactive-map-of-intakes-from-2013-to-2020-e2ecb8f18e18) about it!  
