# About
This repo contains scripts for stock data analysis using various machine learning algorithms.

# File structure
* **Conf** folder contains configuration files for robots, stock data downloaders and algoritms.
* **Tests** folder contains unit tests.
* **Helpers** folder contains simple classes for data description.
* **StockDataDownloader** folder contains classes for downloading stock data. This data is used for back tests and strategies optimization.
* **DbDump.py** - dumps forex data from Oanda broker to configurable PostgreSQL database.
* **DbCheck.py** - checks PostgreSQL database integrity (validates datetime stamps difference)
* **FxRobot.py** - a template for forex robot with backlogs support (to be modified).
* **PatternsProcessor.py** - a class for splitting sequental price data into patterns (not used).
* **PatternsAnalyzer.py** - a tool for patterns determination and analysis (to use classifiers then).
* **Readme.md** - readme file.
