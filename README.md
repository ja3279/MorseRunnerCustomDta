# MorseRunner Custom Dta Files
Contains custom `.dta` files with valid US callsign data that can be used for MorseRunner practice.

* `first3_callsigns.dta` - contains just leading 3 characters of callsigns.
* `first4_callsigns.dta` - contains just leading 4 characters of callsigns
* `all_callsigns.dta` contains all the callsigns of all lengths.

Replace MorseRunner's `Master.dta` file with one of these files. Ensure you save the original `Master.dta` file so that you can revert when needed.
Example:
```
mv Master.dta Master.dta.original
mv first3_callsigns.dta Master.dta
```
