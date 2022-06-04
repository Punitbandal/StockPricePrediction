# StockPricePrediction

<h1>ALGORITHM AND METHODOLOGIES</h1>

**1.NATURAL LANGUAGE PROCESSING**

Natural language processing (NLP) refers to the branch of computer science—and more specifically,<br/> the branch of artificial intelligence or AI—concerned with giving computers the ability to understand text and spoken words in much the same way human beings can.<br/>
**NLP tasks**
- Speech recognition<br/>
- Part of speech tagging
- Sentiment analysis

![image](https://user-images.githubusercontent.com/65059328/172019784-99d79113-66f4-4dd4-b1b1-9c4d2c1bedd0.png)

**2. NAIVE BAYES ALGORITHM**

- Naive bayes classifiers are a family of simple “probabilistic classifiers”.
- Naive Bayes classifier uses applied mathematics to classify data. 
- Naive Bayes classifier algorithms make use of Bayes theorem  
- Challenges in tongue processing frequently involve speech recognition, tongue understanding, and tongue generation.

**3. ARIMA FROM STATS MODEL**

- Autoregressive integrated moving average (ARIMA) models predict future values based on past values.
- ‘AR’ helps in determining the change since last time, ‘MA’ smoothens the trend in data, <br/>and ‘I’ removes the non-stationary form of series.
- Widely used in technical analysis to forecast future security prices.
- Autoregressive models implicitly assume that the future will resemble the past.

**Autoregressive(AR or p):**
Stating the relationship of a variable with its own lagged values ,<br/> autoregressive order represents the number of lagged values that are connected to the current value of the variable.

![image](https://user-images.githubusercontent.com/65059328/172019873-d658eddb-369b-49cd-94e9-e2eb7e0e41e6.png)

Where yt is the current value, yt−1 is the lagged value of variable y, e defines the error term,  is constant or drift, and p determines the number of period lag.

**Integrated(Differencing):**

Integration of the variable state the degree of differencing required for converting the **non-stationary form of the time series into the stationary one by removing the effect of seasonality or irregular events**.

**Moving average (MA or q)**
Being the representative of the **relationship between the observations and the residual error**, the size of the moving average represents the status of dependency.<br/>

![image](https://user-images.githubusercontent.com/65059328/172019950-3d7365bd-00bb-459b-aba7-6440a315e8ee.png)
<br/>

Where, yt is the current value, e is the residual term, q is the number of moving average, and is the constant term.


**APPLICATIONS**

- Stock market prediction aims to determine the future movement of the
       stock value of a financial exchange. The accurate prediction of share price
       movement will lead to more profit investors can make.<br/>
- The accurate prediction of share price movement will lead to more profit
       investors can make.<br/>
- Users can identify the patterns in the market, assess the investment risks,
        and analyze the sentiments of the people.<br/>
- With the help of sentiment analysis, users can check sentiments among the
        public about the Company.<br/>

