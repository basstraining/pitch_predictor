# Pitch Predictor Model
![Alt text](images/floro_slider.gif)
## Intro & Business Context
We are starting a sports analytics modeling company, and the first model we have created is an MLB pitch predictor, which will predict the type of pitch that will be thrown next during an at-bat. Our company believes in the growing influence of technology and data in sports decision-making, with AI at the forefront, and that emerging companies like ours will be able to compete in a market without dominant players in the private sector. We are beginning with a baseball model because of the tabular and static nature of the sport, with the goal of expanding our predictive-modeling capabilities to other sports as we continue to gain a foothold in the industry.
## Data Understanding


We scraped data from [baseballsavant](https://baseballsavant.mlb.com/), a website that collects MLB data from MLB.com's Statcast database, using Pybaseball, a python package that scrapes baseball data. This gave us a dataset of all the pitches thrown in the 2023 MLB season.


We scraped data from [baseballsavant](https://baseballsavant.mlb.com/), a website that collects MLB data from MLB's Statcast database, using [Pybaseball](https://github.com/basstraining/pitch_predictor/tree/main/notebooks/pybaseball), a python package that scrapes baseball data. This gave us a dataset of all the pitches thrown in the 2023 MLB season.

## Data Cleaning and Preproccesing

## Modeling & Evaluation

## Data Cleaning and Preproccessing
## Modeling & Evalution

## Conclusion & Next Steps
## Contributing 
If you would like to contribute to the project please fork the repository. You should activate your python env with `conda` or `venv` using  >= python3.8 and install the python package `pybaseball` with `pip`

#### On Linux/Mac/Windows
```
pip install pybaseball
```





































## Repo Structure 
```
├── data
├── images
├── notebooks
│   ├── 
│   ├── 
├── .gitignore
├── LICENSE
├── README.md
├── binary_class_training_eval_final.ipynb
```
