# Jeffery_butler_carbon_game
Users will enter their answers once a day.
The above calculations will determine how much CO2 they produced that day.
They will get a score using above calculations every day. The emissions are subtracted from a fixed value so that scores can be positive.
The score will be cumulative, giving users an incentive to input their footprint everyday and emit less CO2


SCORE MECHANISM:
Average CO2 Emission per day => 0.0021 metric tonnes (2.1kg)
Score => [ 0.025 metric tonnes (25kg) - CARBON FOOTPRINT ] / 2

CO2 Calculation:
Transport
Transport CO2 (metric tonnes)=0
[QUESTION] Do you own a car?
Yes:
[QUESTION] Is your car petrol-powered or diesel-powered?
Petrol:
[QUESTION] How many kilometres have you driven today?
Transport CO2=petrol0.000192
Diesel:
[QUESTION] How many kilometres have you driven today?
Transport CO2=diesel0.000171
No:
[NEXT QUESTION]

Holiday Travel
Holiday CO2 (metric tonnes)=0
[QUESTION] Have you flown by airplane today?
Yes:
[QUESTION] Enter the time taken to reach your destination.
Holiday CO2=time0.09
No:
[NEXT QUESTION]
Food
Food CO2 (metric tonnes)=0
[QUESTION] Do you consume meat?
Yes:
[QUESTION] How much meat (kg) did you consume today?
Food CO2+=meat0.0079
No:
[NEXT QUESTION]

[QUESTION] How much non-meat products (kg) did you consume today?
Food CO2+=nonmeat0.0015
House Consumption
House CO2 (metric tonnes)=0
[QUESTION] How much energy (kWh) did you consume in the past month?
House CO2=energy0.00037130
[QUESTION] How many members are in your household?
House CO2=members
Waste Disposal
Waste CO2 (metric tonnes)=0
[QUESTION] How much waste (kg) have you disposed today?
Waste CO2=waste0.0007members
Other Sources of CO2
Total CO2=(Transport CO2+Holiday CO2+Food CO2+House CO2+Waste CO2)1.1
__________________________________________________________________________________
