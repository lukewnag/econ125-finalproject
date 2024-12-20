# econ125-finalproject
Downloading data from FRED without having to click "download" 256 times

TO RUN:
* Request an API key for FRED [here](https://fredaccount.stlouisfed.org/apikeys)
* Place the code in a new Google Colab notebook, OR
* Install Python (preferably 3.10, but any version of Python3 before 3.12 should work)
* (Recommended) Create a virtual environment: if you are using Visual Studio Code, use `Ctrl-Shift-P`, then search "Python: Create Environment"
  * Does not matter if you are using Google Colab
* Download all required Python libraries using `pip install numpy pandas fredapi` (insert `%` in front of it and place this in the first cell if using Google Colab)
* Go to `data_downloader.ipynb` and replace `INSERT KEY HERE` with the API key you obtained from FRED, then run all cells
  * If having trouble with previous steps, I have provided all the downloaded data in the repository
* Go to `data_formatter.ipynb` and run all cells to obtain the Stata file
  * If having trouble with Python, I have uploaded the Stata file as well as `econproject.dta`
