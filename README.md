# WSB Shiny
Demo shiny application for visualizing WSB.

An up to date version is avalible at: []()

Not updated frequently and does not contain all code and data. 

# How to prep data

To shrink the size of the repo some of the data will need to be updated or created, to do so:

1. Run `Dev/update_WSB_scrape.py`. This will update the `Data/raw-historical/2021_raw_wsb_dd_submissions.csv`
2. Run `Dev/merge_raws.r`. This will combine the historical data into a singular CSV which can be cleaned
3. Run `Dev/NLP_extract.R`. This does the feature mining (sentiment, mentioned stocks, award counts).

# Running the Shiny App

After completing the above steps, click run app in `WSB-viz/app.R`

# Notes

This was a project with [Taylor Blair](https://github.com/Goodernews) and [Jiarong Li](https://github.com/jialicatherine) in [Kelly McConville's](https://github.com/mcconvil) Data Science 241 class at Reed College.

If there is an issue please file an issue and I will patch it as soon as possible.
