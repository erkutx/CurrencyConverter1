
# Project Title:CurrencyConverter

The app converts input currency to the all desired currency values.
 Currency data delivered are sourced from financial data providers and banks, including the European Central Bank.

## API Reference
The API comes with multiple endpoints, each serving a different use case. Endpoint functionalities include getting the latest exchange rate data for all or a specific set of currencies, converting amounts from one currency to another, retrieving Time-Series data for one or multiple currencies 
and querying the API for daily fluctuation data.
#### Get all items

```http
  GET /api/items
```
var requestURL = 'https://api.exchangerate.host/latest';
var request = new XMLHttpRequest();
request.open('GET', requestURL);
request.responseType = 'json';
request.send();

request.onload = function() {
  var response = request.response;
  console.log(response);
}



## Authors

- [@erkutcetiner](https://www.github.com/erkutx)
## Package Alamofire

Chainable Request / Response Methods
 Swift Concurrency Support Back to iOS 13, macOS 10.15, tvOS 13, and watchOS 6.
 Combine Support
 URL / JSON Parameter Encoding
 Upload File / Data / Stream / MultipartFormData
 Download File using Request or Resume Data
 Authentication with URLCredential
 HTTP Response Validation
 Upload and Download Progress Closures with Progress
 cURL Command Output
 Dynamically Adapt and Retry Requests
 TLS Certificate and Public Key Pinning
 Network Reachability
 Comprehensive Unit and Integration Test Coverage
 
