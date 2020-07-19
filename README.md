# average-invest

An app to compare the significance of dollar cost averaging on a particular timeframe (day vs week vs month).

## Stack

- React

## About

This project evolved out of my curiousity with dollar cost averaging. Obviously it is a good idea to invest continuously in order to achieve the average return for a particular stock. However I could not find comparisons of the actual recommended timeframe for investing. Was it better to invest once a month or every Tuesday? Was there an advantage to a particular day of the week? As it turns out there really isnt much difference among weekdays or even months. If you are frequent enough, say even just quarterly with buys and you hold the stock for several years the difference between the timing of your buys is often negligible. This app uses a public API to gather all historical US stock data.    

## Challenges

- Cleaning and formatting the historical stock data
- Handling holidays and days when the stock market was closed.
- Making an equal comparison between motnhs, weeks, quarters, years.
  

## Future Features

- Adding a date range slider, so that a user can choose the number of years invested and when
- Adding a graph of the performance over selected time period
- Adding a benchmark stock to this performance graph
- Adding other foreign stock exchanges
