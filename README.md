# algo

[Newman](https://www.npmjs.com/package/newman) interacts with the [tradeking API](https://developers.tradeking.com/) to

  - get market data

  - make trades.
  
Behind Newman, there is also an analyzer program. The analyzer takes the market data coming in from tradeking via Newman and produces buy or sell actions, and uses Newman to send those actions to the tradking API.
