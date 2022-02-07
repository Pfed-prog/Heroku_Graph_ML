# Heroku_Graph_ML

Deployed Using Heroku at https://dspyt.herokuapp.com/

We are accessing Uniswap V3 GraphQL at https://thegraph.com/hosted-service/subgraph/uniswap/uniswap-v3?selected=playground to obtain historical data for the chosen token. The Default token is Uniswap.

Next we model the time-series data to predict token price for the N number of timestamps. Default is 15 periods.

## Model

![](https://media.discordapp.net/attachments/920662756779253840/921062122685882368/unknown.png)

![ARIMA General Case](https://user-images.githubusercontent.com/66903336/146431211-f9d1b500-0296-4911-8236-f0fea763f170.png)

We have Used Arima(1,1,0) model since it has maths foundation and differences the data to make it stationary.

In particular properties of AR(1) are as following:
![image](https://user-images.githubusercontent.com/66903336/146432161-72e33d28-88a7-4c9a-b64b-9f02761ca690.png)

We are also using the app to create a larger app for the Uniswap bounty. The app output ![image](https://user-images.githubusercontent.com/66903336/146433297-49d145bc-7aef-4c79-8349-1b2db0b2352a.png)


## Further References

[DSPYT: Time series data – An easy introduction](https://dspyt.com/time-series-data-an-easy-introduction/)
