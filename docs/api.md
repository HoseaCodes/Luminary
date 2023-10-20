## APIs for payment service 
We use the RESTful API design convention for the payment service.

### POST /v1/payments

This endpoint executes a payment event. As mentioned above, a single payment event may contain multiple payment orders. The request parameters are listed below:

| Field | Description | Type |
| --- | --- | --- |
| buyer_info | The info of the buyer | object |
| checkout_id | A global unique ID for this checkout | string |
| credit_card_info | This could be encrypted credit card info or a payment token. The value is PSP-specific | object |
| payment_orders | A list of the payment orders | list |


The payment_orders look like this:


| Field  | Description  | Type   |
|------------------|----------------------------------------------------------------------------------------|--------|
| seller_account  | Which seller will receive the money | string |
| amount| The transaction amount for the order  | string |
| currency | The currency for the order | string |
| payment_order_id   | A globally unique ID for this payment | string   |
