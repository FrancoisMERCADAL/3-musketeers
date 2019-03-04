![alt text](https://www.gannett-cdn.com/-mm-/3b8b0abcb585d9841e5193c3d072eed1e5ce62bc/c=0-30-580-356/local/-/media/2018/02/24/USATODAY/usatsports/large-pile-of-hundred-dollar-bills-cash-money-savings-rich_large.jpg?width=3200&height=1680&fit=crop)


# cash
### The cash library is a tool to convert currencies to other ones

# Install modules
Go to the cash folder and type :
```sh
npm install
```

# How to use the app :
enter the command :
``javascript
node index.js "value" "start currency" "convert currency 1" "convert currency 2" ... "convert currency N"
```

if you just enter :
  ``javascript
  node index.js
  ```
  the program will convert 1 USDollar to EURO, Yen and Pound

  ``sh
  node index.js "value"
  ```
  the program willconvert the value from USDollar to EURO, Yen and Pound

  ``javascript
  node index.js "value" "start currency"
  ```
  the program will convert the value from the start currency to basic currencies (USDollar, Euro, Yen and Pound)

  ``javascript
  node index.js "start currency" "convert currency 1" "convert currency 2" ... "convert currency N"
  ```
  the program will convert 1 amount from the start currency to the defined currencies

  ``javascript
  node index.js "value" "start currency" "convert currency 1" "convert currency 2" ... "convert currency N"
  ```
  the program will convert the value from the start currency to the defined currencies

# Error messages you can get
``javascript
‼ The "a currency name" currency not found
```
you typed a wrong currency name

``javascript
"Internal server error"
```
A problem occured

``javascript
Please check your internet connection!"
```
you have a problem with your Internet connection

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/watch?v=eD2ZGW1NGJo)
