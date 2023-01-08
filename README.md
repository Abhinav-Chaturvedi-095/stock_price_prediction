# stock_price_prediction
Stacked LSTM

explanation
1.collection of data
2. preprcess the data -> test train split

for time series split will be continuous because it next value depends on previous
ex: 120,130,125,140,134,150,160,190,154

train=>120,130,125,140,134,150
test=>160,190,154


timesteps =3(how many previous days to consider for next)

	x_train		y_train
f1	f2	f3	o/p
120	130	125	140
130	125	140	134...so on


similarly test
then comparison

in our computation=> time steps=100

3. creating stacked LSTM(because we need more accuracy & deep learning {multi Lstm) is required) 
for lstm we need 3d matrix[samples, time steps, features]
4.predict the test data and plot the output 
	green colour->test data prredict
5.predict the future 30 days

reference: krish naik
other keywords explanation
verbose=>
epoch=>
batch_size=>
