# lighthouse_pagespeed_reporter

This script runs Pagespeed insight AND Lighthouse reports across a list of URLs. These reports will be saved in a CSV under the `sitename` folder under this repo. In addition, all JSON files are stored there as well.

## Requirements
- Python 3
- Pagespeed Insights API key
  - (Refer to this link on getting started (https://developers.google.com/speed/docs/insights/v5/get-started)
- Add API key to environment variable
  - The variable name should be stored as `pagespeed`.
- Lighthouse npm installed globally
  - run `npm install -g lighthouse`

## To run:
- Clone the repo

- CD into the directory

- Update the urls.txt with each url on their own line.

### Command Usage:
`python ./py-pagespeed-reports.py`

Once this is finished, you will see a folder generated with the site name that will have the CSV's there, as well as the JSON files.
