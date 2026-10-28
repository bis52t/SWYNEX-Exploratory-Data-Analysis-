# SWYNEX-Exploratory-Data-Analysis-


**Dataset:** Cleaned Titanic dataset (Task 1) | **Tools:** Python, pandas, matplotlib

## Key statistics
- 891 passengers, overall survival rate: __%
- Average age: __, median fare: __, max fare: __
- Fare outliers: __ passengers; zero-fare passengers: __

## Insights
1. **Sex was the strongest factor.** Women survived at __% vs men at __% (chart 1).
2. **Class mattered.** 1st class survival was __% vs __% in 3rd class (chart 2).
3. **Children had better odds.** Child survival was __%, higher than other age groups (chart 3).
4. **Family size has a sweet spot.** Small families (2-4) survived more than solo travellers and large families (chart 4).
5. **Fare tracks class.** Higher fares sit with 1st class and correlate positively with survival (charts 7, 8).
6. **Port of embarkation.** Cherbourg passengers survived more, likely because more of them travelled 1st class (chart 5).

## Anomalies
- Fares are heavily right-skewed, with a few very high outliers (max __).
- __ passengers have a fare of 0.
- __% of ages were imputed in Task 1, so age analysis uses known ages only.

## Charts
![sex](charts/1_survival_by_sex.png)
![class](charts/2_survival_by_class.png)
(add the rest the same way)

## Limitations
Correlation is not causation, and the data covers only 891 passengers.

## How to run
pip install pandas matplotlib && python eda.py
