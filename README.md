# Flight Delays : Analysis and Prediction of flight delays

Data science project about flight delays.

The data came from  [the U.S. Department of Transportation](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236) and we use the 2016 data and the data available for 2017 at that time.

## Data fields names and descriptions :
- `YEAR` — Year
- `QUARTER` — Quarter (1-4)
- `MONTH` — Month
- `DAY_OF_MONTH` — Day of Month
- `DAY_OF_WEEK` — Day of Week
- `FL_DATE`— Flight Date (yyyy-mm-dd)
- `UNIQUE_CARRIER` — Unique Carrier Code. (`HA`:	Hawaiian Airlines Inc., `AS`:	Alaska Airlines Inc., `DL`:	Delta Air Lines Inc., `OO`:	SkyWest Airlines Inc., `UA`:	United Air Lines Inc., `EV`:	ExpressJet Airlines Inc., `WN`:	Southwest Airlines Co., `AA`:	American Airlines Inc., `VX`:	Virgin America, `F9`:	Frontier Airlines Inc., `B6`:	JetBlue Airways, `NK`:	Spirit Air Lines.)
- `ORIGIN`— Origin Airport
- `ORIGIN_CITY_NAME` — Origin Airport, City Name
- `DEST` — Destination Airport
- `DEST_CITY_NAME` — Destination Airport, City Name
- `CRS_DEP_TIME` — CRS Departure Time (local time: hhmm)
- `DEP_TIME` — Actual Departure Time (local time: hhmm)
- `DEP_DEL15` — Departure Delay Indicator, 15 Minutes or More (1=Yes)
- `CRS_ARR_TIME` — CRS Arrival Time (local time: hhmm)
- `ARR_TIME` — Actual Arrival Time (local time: hhmm)
- `ARR_DEL15` — Arrival Delay Indicator, 15 Minutes or More (1=Yes)
- `FLIGHTS` — Number of Flights
- `DISTANCE` — Distance between airports (miles)
- `DISTANCE_GROUP` — Distance Intervals, every 250 Miles, for Flight Segment
