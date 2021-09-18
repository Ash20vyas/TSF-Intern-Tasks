<h1 align="center">Task 2 : Stock Market Prediction using Numerical and Textual Analysis</h1>

<h2>Problem Statement</h2>

 ● Create a hybrid model for stock price/performance prediction using numerical analysis of historical stock prices, and sentimental analysis of news headlines.
 
<div id="about_dataset">
    <h2>About the dataset</h2>
    The news dataset <b>Times of India News Headlines</b> is a persistent historical archive of noteable events in the Indian subcontinent from start-2001 to end-2020, recorded in realtime by the journalists of India. It contains approximately 3.4 million events published by Times of India.
    <br>
    <br>
    Times Group as a news agency, reaches out a very wide audience across Asia and drawfs every other agency in the quantity of english articles published per day. The data can be accessed at <a href="https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DPQMQH">Times of India News Headlines</a>.
    <br>
    <br>
    Due to the heavy daily volume over multiple years, this data offers a deep insight into Indian society, its priorities, events, issues and talking points and how they have unfolded over time. It is possible to chop this dataset into a smaller piece for a more focused analysis, based on one or more facets.
    <br>
    <br>
    Since our Textual Analysis dataset containing news from Times of India News Headlines is from 2nd January 2001 to 31st December 2020. 
    So we will only work with stock price from 2nd January 2001 to 31st December 2020. 
    <br>
    <br>
    We will be using <b>yfinance</b> to extract the stock data of <b>BSE SENSEX</b> from <b>02/01/2001</b> to <b>31/12/2020</b>. The <b>BSE SENSEX</b> is a free-float market-weighted stock market index of 30 well-established and financially sound companies listed on the Bombay Stock Exchange.
</div>
 
<h2>Libraries Used</h2>
 <ul>
   <li>warnings</li>
   <li>math</li>
   <li>pandas</li>
   <li>numpy</li>
   <li>yfinance</li>
   <li>nltk</li>
   <li>SentimentIntensityAnalyzer <i>from</i> nltk.sentiment.vader</li>
   <li>matplotlib.pyplot</li>
   <li>MinMaxScaler <i>from</i> sklearn.preprocessing</li>
   <li>Sequential <i>from</i> keras.models</li>
   <li>Dense, LSTM, Dropout, Dense, Activation <i>from</i> keras.layers</li>
   <li>metrics <i>from</i> sklearn</li>
</ul>

<h2>Stock Price Prediction</h2>
<p align="center">
<img src="https://github.com/Ash20vyas/TSF-Intern-Tasks/blob/main/%232%20-%20Stock%20Market%20Prediction%20using%20Numerical%20and%20Textual%20Analysis/Stock%20Price%20Prediction.jpg">
  </p>
