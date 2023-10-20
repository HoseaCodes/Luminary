# How Does an Online Payment Platform Like Stripe Work?

Stripe is a payment services provider. It enables merchants to accept credit and debit card payments in over 135 currencies. How exactly does this happen?

Stripe follows these steps to process a payment:

1. First, the client specifies his card details.
1. This card data is then sent to the Stripe payment gateway.
1. Stripe, in turn, sends this data to the bank, which will process the transaction.
1. The transaction is then transferred to the bank through a credit card network such as Mastercard or Visa.
1. The bank then approves or rejects the transfer.
1. Finally, the client receives a message about the success or failure of the transaction.


## How do payment gateways work?

Payment gateways and processors function as intermediaries between businesses and customers, ensuring each transaction is carried out securely and promptly. The process typically includes several steps, starting from the customer making a payment for goods or services and ending with the business receiving the payment.

Payment gateways have several important responsibilities during the transaction process, including:

- Encryption

    When a customer places an order, the gateway encrypts the payment information before sending it to the business’s web server. From there, the gateway sends the transaction data to the payment processor used by the business’s acquiring bank.

- Authorization requests
  
    The payment processor sends the transaction data to a card network, which routes it to the bank that issued the customer’s card to authorize or decline the transaction.

- Filling the order
  
    The processor then forwards an authorization related to the business and customer to the payment gateway. Once the gateway obtains this response, it transmits it to the business’s website (or whatever interface processed the payment) to complete the payment process. If the transaction is approved, the business can then fulfill the order.

- Settlement

    At the end of the day, the business sends a batch of all approved authorizations to its acquiring bank for settlement. The bank deposits the total of the approved funds into the business’s nominated account. This could be a daily, weekly, or other agreed-upon schedule.

By providing a secure pathway between the customer, the business, and the payment processor, payment gateways ensure smooth, secure, and quick online transactions. Payment gateways also employ various security measures, such as SSL encryption and fraud prevention tools, to protect sensitive data such as credit card numbers and other personal information.

## How do payment processors work?

The terms “payment processor” and “payment gateway” are sometimes used interchangeably, but they represent two distinct stages in the payment cycle. Here’s a more detailed explanation of how each one works:

### Payment processor

A payment processor is a company that works with a business to handle the processing of transactions for acquiring banks. When a customer pays for a product or service with a credit or debit card, the payment processor immediately performs several tasks:

- Authorization
  
    It verifies the details of the credit card (such as whether the card has expired or not) and checks if the customer has enough credit to cover the purchase.

- Transaction processing
  
    After authorization, the payment processor will then process the transaction. This involves transferring the customer’s information and the transaction information to the bank that issued the credit card.

- Payment

    Once the transaction has been processed, the payment processor will then transfer the funds from the customer’s account to the business’s account.

### Payment gateway

A payment gateway is a service that authorizes credit card payments for online and offline businesses. It’s the equivalent of a physical point-of-sale terminal in a store or restaurant. It transfers information between the payment portal—such as a website or mobile app—and the payment processor or acquiring bank.

Here’s a simplified overview of how a payment gateway works:

- Encryption

    When a customer orders a product from an online business, the payment gateway securely encrypts the credit card details and sends this information to the business’s server.

- Authorization request

    The business then forwards this information to its payment processor, which, in turn, sends it to the customer’s credit card issuer for authorization.

- Filling the order

    The credit card issuer sends a response back to the payment processor. The response includes information about whether the transaction was approved or declined. If the transaction was approved, the business can fulfill the customer’s order.

- Settlement

    At the end of the day, the business sends the day’s approved authorizations in a batch to its acquiring bank for settlement. The bank deposits the total of the approved funds into the business’s regular business bank account.

For both payment processors and payment gateways, the main objectives are to securely handle sensitive credit card information, ensure the customer has enough credit to cover the purchase, and move funds from the customer’s account to the business’s account. They each play important roles in ecommerce transactions, enabling businesses to sell products online and customers to easily and confidently make purchases.




## References

- [Softermil](https://www.softermii.com/blog/how-to-create-an-online-payment-platform-like-stripe)

- [Stripe Create Your Own](https://stripe.com/resources/more/how-to-create-your-own-payment-gateway)