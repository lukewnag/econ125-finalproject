# econ125-finalproject
Downloading data from FRED without having to click "download" 256 times

TO RUN:
* Request an API key for FRED [here](https://fredaccount.stlouisfed.org/apikeys)
* Install Python (preferably 3.10, but any version of Python3 before 3.12 should work)
* (Recommended) Create a virtual environment: use `Ctrl-Shift-P`, then search "Python: Create Environment"
* Download all required Python libraries using `pip install numpy pandas fredapi`
* Go to `data_downloader.ipynb` and replace `INSERT KEY HERE` with the API key you obtained from FRED, then run all cells
* Go to `data_formatter.ipynb` and run all cells to obtain the Stata file
