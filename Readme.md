<h1 style="color: green;">CHSB Metrics API docs.</h1>

The data required for the page can be fetched from the following api root:
```
https://chsb.my-test-domain.website/
```
The data required for the chsb chart can be fetched from the following api ends:
```
/chsb-price-month
```
E.g. Request:
```
GET https://chsb.my-test-domain.website/chsb-price-month
```
E.g. Response: 
```
[
    {
        "price": 0.00935,
        "time": "2019-06-16T00:00:00.000Z"
    },
    {
        "price": 0.008741,
        "time": "2019-06-17T00:00:00.000Z"
    },
    {
        "price": 0.008509,
        "time": "2019-06-18T00:00:00.000Z"
    }
]
```

The rest of the data can be found at the following api end:
```
/chsb-metrics
```
E.g. Request:
```
GET https://chsb.my-test-domain.website/chsb-metrics
```
E.g. Response: 
```
{
    "chsbCirculatingSupplyTokens": 227885076,
    "chsbStackedTokens": 139665000,
    "chsbStackedPercentage": 19.83,
    "chsbYieldPledgedTokens": 331754774,
    "chsbInYieldPercentage": 47.11,
    "chsbBurnedTokens": 4898917.07,
    "totalSupplyBurnedPercentage": 0.6956675457607038
}
```
