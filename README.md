# COVID-19 Map visualization

This map visualization is about the number of confirmed/recovered/deaths cases in link with the COVID-1ç by country.

## Instalation

If you want to execute the code you need to have a notebook interface.
For windows : Install Anacounda
For Linux/MacOS : Install Jupyter

### Requirement

pandas : -pip install pandas
        
numpy : -pip install numpy

folium : -pip install folium
         -conda install folium (on Anacounda)
         
json : -pip install json

geopandas : -pip install geopandas
            -conda install folium (on Anacounda)
       
pyproj : -pip install --ignore-installed pyproj (to have the latest version)


## Usage

### Dataset

The dataset use in this little project is from : https://github.com/CSSEGISandData/COVID-19

So to easely update the map visualization you might want to clone the github repertory mentioned right above and put the Python_Test file in the 'COVID-19/csse_covid_19_data/csse_covid_19_time_series/' directories.

So that you just have to pull the last modification made on the repertory and rerun the code. 
