# StockPredictorTerminal
 A simple stock predictor terminal w/ Tkinter GUI


This project uses a simple Linear Regression model and the Tkinter GUI to make a simple stock predictor terminal. The Quandl package is free to use for Python, but it is important to mention that if you are trying to use this program, you have to create a account to generate the API Key that allows you to get the stock information. Thanks, and happy coding! Link to website where you create the aforementioned account: https://data.nasdaq.com/login

This program taught me the fundamentals of GUIs in Python with Tkinter, and was a good way to practice using comprehensive graphical libraries like Matplotlib. It was a lot of fun to mess around and tweak things within it, and I learnt a lot!

There is one major bug regarding the API Key: while it seems to sometimes keep track of it as an environmental variable, it is extremely inconsistent. You can still access the data w/out the API key, but the amount of times daily will be extremely limited in comparison.

To run this repo, download it and open file main.ipynb. This will appear as a jupyter notebook, in which you just run all cells, found at the top bar of the notebook. If there is for some reason preloaded results, just restart the kernel and run all cells.

If you run the program, you will be asked a series of questions about your API Key, the stock you wish to view, and the number of days worth of data in the future you want to predict. If you answer all of these, you should be greeted with this frame after a short duration of load time:

<img src="/path/to/img.jpg" alt="Alt text" title="Optional title">

Things I could improve with this project are that I would like to try and use a different Python GUI, maybe something like PyQt. On top of this, I think it would be helpful for the user to have a list of available stocks from the Quandl API, which is something I am planning to implement in the future.
