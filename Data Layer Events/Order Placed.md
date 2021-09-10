# Order Placed

### 

## Javascript Code
```js
window.dataLayer222 = window.dataLayer222 || [];
dataLayer222.push({
  "event": "Order Placed",
    "coupon": "<coupon>",
    "currency": "<currency>",
    "items": [
        {
            "item_brand": "<item_brand>"
        }
    ],
    "value": "<value>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|coupon|string|Order-level coupon code used for a purchase.|summer\_fun|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|item_brand|string|Item brand|Gucci|||||||
|value|number|The monetary value of the event.	|7.77, 239.55, 659|||||||



