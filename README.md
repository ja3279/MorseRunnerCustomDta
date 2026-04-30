# Morse Runner Custom Dta Files
Repository contains custom `.dta` files with valid US callsign data that can be used on [Morse Runner 1.68](https://www.dxatlas.com/MorseRunner/) practice. All callsigns are valid and active US callsigns that were active in [FCC Database](https://data.fcc.gov/download/pub/uls/complete/l_amat.zip). FCC Data was downloaded on April 29, 2026. 

* `first3_callsigns.dta` - contains just leading 3 characters of callsigns.
* `first4_callsigns.dta` - contains just leading 4 characters of callsigns
* `all_callsigns.dta` contains all the callsigns of all lengths.

Replace Morse Runner's `Master.dta` file with one of these files. Ensure you save and backup the original `Master.dta` file so that you can revert when needed.

Example:
```bash
mv Master.dta Master.dta.original
cp first3_callsigns.dta Master.dta
```
