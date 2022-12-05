# Mini-Project: Using APIs to Retrieve Data

For this mini project, we will focus on equities data from the Frankfurt Stock Exhange (FSE), which is available for free. We'll try and analyze the stock prices of a company called Carl Zeiss Meditec, which manufactures tools for eye examinations, as well as medical lasers for laser eye surgery: https://www.zeiss.com/meditec/int/home.html. The company is listed under the stock ticker AFX_X.

We pull some data from https://data.nasdaq.com/ .


While there is a dedicated Python package for connecting to the Nasdaq API, the aim of this project is to demonstrate the use of the requests package, which can be easily downloaded using pip or conda. You can find the documentation for the package here: http://docs.python-requests.org/en/master/ .

Finally, apart from the requests package, we do not use any third party Python packages, such as pandas, and instead focus on what's available in the Python Standard Library (the collections module might come in handy: https://pymotw.com/3/collections/). Also, since we won't have access to DataFrames, we use Python's native data structures - preferably dictionaries, though some questions can also be answered using lists. We can read more on these data structures here: https://docs.python.org/3/tutorial/datastructures.html ..