{% docs payment_method %}
   	
One of the following values: 

| method            | definition            |
|-------------------|-----------------------|
| credit_card       | credic card payment   |
| coupon            | coupon payment        |
| bank_transfer     | bank transfer payment |
| gift_card pending | gift card payment     |

{% enddocs %}

{% docs payment_status %}
   	
One of the following values: 

| status            | definition            |
|-------------------|-----------------------|
| success           | payment succeeded     |
| fail              | payment failed        |

{% enddocs %}

{% docs order_status %}
	
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| placed         | Order placed, not yet shipped                    |
| shipped        | Order has been shipped, not yet been delivered   |
| completed      | Order has been received by customers             |
| return pending | Customer indicated they want to return this item |
| returned       | Item has been returned                           |

{% enddocs %}