# ISTG1003-Prosjekt

## Relevant Dataset Resources
* [Further dataset information from zenodo](https://zenodo.org/records/4446043#.Y9Y9ENJBwUE)
* [Kaggle](https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities?resource=download)

### Dataset Variables
```python
int # Data entry
float realSum # Full price of accommodation for two people and two nights in EUR
str room_type # type of the acoomodation (Private room, Entire home/apt, Shared room)
bool room_shared # if room is shared with another person
bool room_private # if room is not shared with another person
float person_capacity # the maximum number of guests
bool host_is_super_host # superhost status
int multi # if the listing belongs to hosts with 2-4 offers
int biz # if the listing belongs to host with more than 4 offers
float cleanliness_raing # cleanliness rating
float guest_satisfaction_overall # overall rating of listing
int bedrooms # number of bedrooms (0 for studios)
float dist # distance from city centre in km
float metro_dist # distance from nearest metro station in km
float attr_index # attraction index of listing location
float attr_index_norm # normalised attraction index (0-100)
float rest_index # restaurant index of the listing locaiton
float attr_index_norm # normalised restaurant index (0-100)
float lng # longitude of the listing location
float lat # latitude of the listing locaiton
```

## Dependencies
Install dependencies needed for the project:
```bash
py -m pip install pandas numpy matplotlib seaborn statsmodels sklearn 
```
