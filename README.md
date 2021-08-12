# NBeats_Routing_Opt

The objective of this project is to predict the next transmission through a router or switch in a network.

## Data Collection
The data is collected and cleaned by me. A router in Telia network is observed for 24 hours and an univariate dataset is created. 

### sunday_csv.csv is the values of the selected router observed on a sunday. Similarly, wednesday_csv.csv is the values of the same router observed on a monday.

## Model Prepperation

Model is a dual stacked ResNet that observes the trend and seasonality of the data to predict the next coming values.

### To read more about the project, visit https://siddardhakaja.web.app/assets/doc/thesis.pdf
