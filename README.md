# Overview
This package was designed to help developers detect Credit/Debit card type🏦💳.

# Installation
```
yarn add card-detector-js
```

# Usage
Import and call the card detection function while passing the card number in string format as an argument.
```js
const detectCardType = require('card-detector-js')
let cardType = detectCardType(card_number)
```
```
console.log(cardType)
>>> visa
```
This function will return the card type as a **string** if the card numbers are complete and valid, else it will return **undefined**.
This function uses regular expression to detect a wide variety of card type e.g *"mastercard", "visa", "amex", "discover", "unionpay", "jcb", e.t.c*.



#### Remarks
Thank you for using card-detector-js, if this package has helped you, you can give it a star⭐️ on github. Should you encounter any difficulty, you can open a github issue on this repo https://github.com/i-wizard/card-detector-js.