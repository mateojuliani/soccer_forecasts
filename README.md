# soccer_forecasts
WIP - Workflow for scraping data and making forecasts for future international soccer games


## Folders

### intl_soccer_workflow
1. 01_scrape_historical_data - scrape historical games from elorating. TWe will use this data to create and train our models
2. 01_scrape_future_games - scrape upcoming games from elorating. We will perform inference on this table to forecast future games
3. 02_clean_data - cleans data from 01_scrape_historical_data, adds extra columns, and transforms format to make it friendly for training
4. 03_create_models - creates/trains 3 models based on historical data
5. 04_inference - uses models from 03_create_models and data scraped from 01_scrape_future_games to forecast win / draw / loss probabilities of upcoming international soccer games

### Data
Contains scraped data from elorating, old nate silver forecasts, and other misc data sources pulled from different websites

### Functions
Notebook containing helper functions for intl_soccer_workflow

### Models
Folder containing models created in 03_create_models




