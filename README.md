

# Stockify

Command to run project:- 
(Open the project dir where manage.py file is located and type in terminal:- python manage.py runserver)
1.	Top Gainers & Losers data is fetched from the ‘nsetools’.
2.	Searching any stock of  NSE with ticker
a.	Raw data is fetched from ‘nsetools’
b.	Candlestick live data is fetched from ‘yahoofinance’
3.	Watchlist data is fetched from ’nsepy’
4.	Monthly Performance of any stock of NSE is hosted on ‘streamlit’.
-	Code file is located in heatmap/monthlyperformance dir
-	To run the monthly performance file as localhost
Run this command on terminal dir
(streamlit run APPNAME.py)
-	If any hosted app of ‘streamlit’ don’t work try to run using command and file or you can host it on your account

(same for heatmap of ‘NIFTY’)
5.	Live News is fetched from ‘iexapi’
6.	Learn trading module is totally reading purpose
7.	Contact page is connected with database ‘sqlite’
8.	Database of project:-
a.	Create an admin account:-
i.	In terminal python manage.py createsuperuser
ii.	Set your details
iii.	In browser http://127.0.0.1:8000/admin
9.	After any changes in database 
a.	python manage.py makemigrations
b.	python manage.py migrate


10.	Run prediction
You have to run LSTM & LR both prediction on terminal first then open that in webapp.

LSTM run commands:-
1.	Open new terminal in vs
2.	 cd prediction
3.	 cd LSMT
4.	 streamlit run app.py
Now open webapp and from navbar open lsmt prediction page
Same procedure for running LR prediction
First run LSTM then LR



