# Notes for book [Forecasting: Principles and Practice](https://otexts.com/fpp2/index.html)

# plots with [R-ggplot2](https://ggplot2-book.org/getting-started.html)

## Intro
This textbook is intended to provide a comprehensive introduction to forecasting methods and to present enough information about each method for readers to be able to use them sensibly. We don’t attempt to give a thorough discussion of the theoretical details behind each method, although the references at the end of each chapter will fill in many of those details.

## 1.2 Forecasting, planning and goals
|Things|Explaination|
|-|-|
|Forecasting|is about predicting the future as accurately as possible, given all of the information available, including historical data and knowledge of any future events that might impact the forecasts.|
|Goals|are what you would like to have happen. Goals should be linked to forecasts and plans, but this does not always occur. Too often, goals are set without any plan for how to achieve them, and no forecasts for whether they are realistic.|
|Planning|is a response to forecasts and goals. Planning involves determining the appropriate actions that are required to make your forecasts match your goals. Forecasting should be an integral part of the decision-making activities of management, as it can play an important role in many areas of a company. Modern organisations require short-term, medium-term and long-term forecasts, depending on the specific application.|
|Short-term forecasts|are needed for the scheduling of personnel, production and transportation. As part of the scheduling process, forecasts of demand are often also required.|
|Medium-term forecasts|are needed to determine future resource requirements, in order to purchase raw materials, hire personnel, or buy machinery and equipment.|
|Long-term forecasts|are used in strategic planning. Such decisions must take account of market opportunities, environmental factors and internal resources|


## 1.3 Determining what to forecast
In the early stages of a forecasting project, decisions need to be made about what should be forecast. For example, if forecasts are required for items in a manufacturing environment, it is necessary to ask whether forecasts are needed for:

1. every product line, or for groups of products?

2. every sales outlet, or for outlets grouped by region, or only for total sales?

3. weekly data, monthly data or annual data?

It is also necessary to consider the forecasting horizon. Will forecasts be required for one month in advance, for 6 months, or for ten years? Different types of models will be necessary, depending on what forecast horizon is most important.

How frequently are forecasts required? Forecasts that need to be produced frequently are better done using an automated system than with methods that require careful manual work.

It is worth spending time talking to the people who will use the forecasts to ensure that you understand their needs, and how the forecasts are to be used, before embarking on extensive work in producing the forecasts.

Once it has been determined what forecasts are required, it is then necessary to find or collect the data on which the forecasts will be based. The data required for forecasting may already exist. These days, a lot of data are recorded, and the forecaster’s task is often to identify where and how the required data are stored. The data may include sales records of a company, the historical demand for a product, or the unemployment rate for a geographic region. A large part of a forecaster’s time can be spent in locating and collating the available data prior to developing suitable forecasting methods.
