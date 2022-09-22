{% docs payment_method %}

one of the following values:

| status         | definition                                       |
|----------------|--------------------------------------------------|
| credit_card    | Order placed, not yet shipped                    |
| gift_card      | Order has been shipped, not yet been delivered   |
| coupon         | Order has been received by customers             |
| bank_transfer  | Customer indicated they want to return this item |
|                | 
{% enddocs %}



{% docs payment_status %}

one of the following values:
| status         | definition                                       |
|----------------|--------------------------------------------------|
| success        | Payment transaction successful                   |
| fail           | Payment transaction failed                       |

{% enddocs %}