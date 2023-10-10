# market-economy
this is minecraft mod

- Write an economy mod for MC
- Macro-control system that supports the global economy of the server
- Appreciation and depreciation of the market economy within the server
- Control data can be configured
## General principles of currency issuance
- The total issued currency is called xenon currency, and the default issuance is the total number of server registrations * 1000
- Individuals whose total assets exceed 80% of the total issuance of xenon can apply for the issuance of personal currency
- The value of personal currency appreciates and depreciates at a rate of 10% of xenon currency. 
- For example: if the total issuance is 10,000 and an individual issuance is 10,000
- then the value of the currency is 1,000/1,000*100%
- If an individual issuance is 11,000, then the currency value is 1,000/ 1100*100% currency devaluation.

## The default is the total market economic regulation proportion table, as follows
|         item          |                               value                               |   |   |
|:---------------------:|:-----------------------------------------------------------------:|:---:|:---:|
| Wheat and other items | (monetary aggregate-xenon currency circulation)/100*initial price |   |   |
