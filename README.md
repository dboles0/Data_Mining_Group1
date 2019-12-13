# Data_Mining_Group1
Project based on Yelp data set

## Installing dependancies
```
plotly installation
!{sys.executable} -m pip install plotly --upgrade
!{sys.executable} -m pip install "notebook>=5.3" "ipywidgets>=7.2"

visualizing with geo data
!{sys.executable} -m pip install geopandas==0.3.0
!{sys.executable} -m pip install pyshp==1.2.10
!{sys.executable} -m pip install shapely==1.6.3
!{sys.executable} -m pip install chart_studio
!{sys.executable} -m pip install plotly-geo
!{sys.executable} -m pip install folium

installations for tree visualization
conda install python-graphviz
!{sys.executable} -m pip install pydotplus

also if you are interested in code folding to manage code you can 
add npextentions instructions at (https://github.com/ipython-contrib/jupyter_contrib_nbextensions/blob/master/README.md)

```

## Building the project 
```
after dependencies are installed runall 
```

## Unit tests
```
JSON_to_dataFrame_2 - test integrety of input file converting to dataframe
test_DataFrame_to_Json - test integrety of dataframe to input file
check_input_output - utility tool to check where problems arrise in the file
```
