# Time Series Forecasting Theory
[Youtube: Time Series Forecasting Theory | AR, MA, ARMA, ARIMA | Data Science](https://www.youtube.com/watch?v=Aw77aMLj9uM)
# 0 Intro to Time series data
## 0.1 Types of data
### 0.1.1 Univariate Time series:
Time sereis that consist of single observations recorded over regular time intervals.
(only one feature for each timestamp)
### 0.1.2 Cross-sectional Data
Multiple subjects (observation) at the same point of time/ during the same time period.
(multiple features ffor each timestamp)
## 0.2 Patterns emerging in time series data
- frequency
- trend
- constant
- quadratic trend
- ...

e.g. Downnward sloping/ seasonal around upward sloping
## 0.3 Componets of time-series
The pattern in a time series is sometimes classified into:
- trend, seasonal, cyclical and random components

|type|description|notes|
|-|-|-|
|Trend| A long term relatively smooth pattern that usually persists for more than one year||
|Seasonal|A pattern that appears in a regular interval wherein the frequency of occurrence is within a year or even shorter.||
|cyclical|repeated pattern that appears in a time-series but beyond a frequency of one year|business cycles that record periods of economic recession and inflation, cycles in the monetary and finacial sectors|
|random components| The component of the time-series that obtained all the pattens that 'extracted' out from the three patterns above||
## 0.4 Idea behind Univariate Time Seerires modelling
The need to use univariate modeling arises in situations where:
  
  (a) An appropriate economic theory to the relationship between series may not be available and hence one consider only the statistical relationship of the given series with its past value.
  
  (b) Sometimes even when the set of explanatory variables may be known it may not be possible to obtain the entire set of such variabbles required to estimate a regression model and one would then have to use only a single series of the dependent variable to forcast the future values

## Different Time Series Processes
|term|description|
|-|-|
|White Noise|pure random with no corelation to each other; has zero mean and a constant variance|
|Stationarity|if the marginal distribution of Y at time  t[p(Y<sub>t</sub>)] is the same as any other point in time; which means p(Y<sub>t</sub>)=p(Y<sub>t+k</sub>) no matter what 't' is|

If a series is not white noise, then we can start analyse it.

|anotation|meaning|
|-|-|
|f()|linear function: f(x<sub>1</sub>,x<sub>2</sub>) = w<sub>1</sub>x<sub>1</sub>+w<sub>2</sub>x<sub>2</sub>+c|
| e|error term|

# 1. AutoRegressive Model - AR

```
AR model is one in which Y<sub>t</sub> only depends on its own past values
```
Y<sub>t</sub> = f(Y<sub>t-1</sub>,Y<sub>t-2</sub>,Y<sub>t-3</sub>,..., e<sub>t</sub>)

Y<sub>t</sub>(p) = f(Y<sub>t-1</sub>,Y<sub>t-2</sub>,..., Y<sub>t-p</sub>,e<sub>t</sub>)

# 2. Moving Average - MA


Y<sub>t</sub> = f(e<sub>t-1</sub>,e<sub>t-2</sub>,e<sub>t-3</sub>,..., e<sub>t</sub>)

Y<sub>t</sub> = f(e<sub>t-1</sub>,e<sub>t-2</sub>,e<sub>t-3</sub>,..., e<sub>t</sub>)

# 3. AutoRegressive Moving Average Model - ARMA
A combination of both AR & MA

Y<sub>t</sub>(p,q) = f(Y<sub>t-1</sub>,Y<sub>t-2</sub>,Y<sub>t-3</sub>,..., e<sub>t</sub>) + f(e<sub>t-1</sub>,e<sub>t-2</sub>,e<sub>t-3</sub>,..., e<sub>t</sub>)


# 4. ARIMA
