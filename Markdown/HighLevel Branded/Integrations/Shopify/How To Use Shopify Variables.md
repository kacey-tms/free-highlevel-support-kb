**Date Updated:** 2021-12-04T20:32:45.000Z

| **Shopify Variable Details**              | **Shopify Variable format**          | **Data Sample**                                     | **Abandoned Checkout Trigger** | **Order Placed Trigger** |     |
| ----------------------------------------- | ------------------------------------ | --------------------------------------------------- | ------------------------------ | ------------------------ | --- |
| **Order Info**                            |                                      |                                                     |                                |                          |     |
| Order id                                  | {{[order.id](http://order.id/)}}     | 1900968798308                                       | YES                            | YES                      |     |
| Order number                              | {{order.number}}                     | 1044                                                | \-                             | YES                      |     |
| Order status URL                          | {{order.order\_status\_url}}         | link to order                                       | \-                             | YES                      |     |
| Abandoned checkout URL                    | {{order.abandoned\_checkout\_url}}   | link to abandoned checkout                          | YES                            | \-                       |     |
| Created at                                | {{order.created\_at}}                | 2021-10-21T11:47:12+05:30                           | YES                            | YES                      |     |
| Created on                                | {{order.created\_on}}                | default format 10-20-2021                           | YES                            | YES                      |     |
| Currency                                  | {{order.currency}}                   | $                                                   | YES                            | YES                      |     |
| Currency code                             | {{order.currency\_code}}             | USD                                                 | YES                            | YES                      |     |
| |                                         |                                      |                                                     |                                |                          |     |
| **Customer Info**                         |                                      |                                                     |                                |                          |     |
| First Name                                | {{order customer.first\_name}}       | John                                                | YES                            | YES                      |     |
| Last Name                                 | {{order.customer.last\_name}}        | Carter                                              | YES                            | YES                      |     |
| Email                                     | {{order.customer.email}}             | [johncarter@gmail.com](mailto:johncarter@gmail.com) | YES                            | YES                      |     |
| Phone                                     | {{order.customer.phone}}             | 18989898989                                         | YES                            | YES                      |     |
| |                                         |                                      |                                                     |                                |                          |     |
| **Order Value**                           |                                      |                                                     |                                |                          |     |
| Total Cart Price                          | {{order.total\_cart\_price}}         | 99.00                                               | \-                             | YES                      |     |
| Discount Code                             | {{order.discount\_code}}             | TESTDISC20                                          | \-                             | YES                      |     |
| Total Discount Value                      | {{order.total\_discounts}}           | 11.99                                               | \-                             | YES                      |     |
| Order has discount?                       | {{order.has\_discount}}              | true/false                                          | \-                             | YES                      |     |
| Subtotal Price                            | {{order.subtotal\_price}}            | 88.99                                               | \-                             | YES                      |     |
| Total Shipping Price                      | {{order.total\_shipping\_price}}     | 14.49                                               | \-                             | YES                      |     |
| Total Price                               | {{order.total\_price}}               | 102.99                                              | \-                             | YES                      |     |
| |                                         |                                      |                                                     |                                |                          |     |
| **Customer Billing Address**              |                                      |                                                     |                                |                          |     |
| Contact Name                              | {{order.billing\_address.name}}      | John Carter                                         | \-                             | YES                      |     |
| Address Company                           | {{order.billing\_address.company}}   | Marvel Inc.                                         | \-                             | YES                      |     |
| Address 1                                 | {{order.billing\_address.address1}}  | 890                                                 | \-                             | YES                      |     |
| Address 2                                 | {{order.billing\_address.address2}}  | Fifth Avenue, Manhattan                             | \-                             | YES                      |     |
| Province                                  | {{order.billing\_address.province}}  | New York City                                       | \-                             | YES                      |     |
| Zip                                       | {{order.billing\_address.zip}}       | 10128                                               | \-                             | YES                      |     |
| Country                                   | {{order.billing\_address.country}}   | United States                                       | \-                             | YES                      |     |
| |                                         |                                      |                                                     |                                |                          |     |
| **Customer Shipping Address**             |                                      |                                                     |                                |                          |     |
| Contact Name                              | {{order.shipping\_address.name}}     | John Carter                                         | \-                             | YES                      |     |
| Address Company                           | {{order.shipping\_address.company}}  | Marvel Inc.                                         | \-                             | YES                      |     |
| Address 1                                 | {{order.shipping\_address.address1}} | 890                                                 | \-                             | YES                      |     |
| Address 2                                 | {{order.shipping\_address.address2}} | Fifth Avenue, Manhattan                             | \-                             | YES                      |     |
| Province                                  | {{order.shipping\_address.province}} | New York City                                       | \-                             | YES                      |     |
| Zip                                       | {{order.shipping\_address.zip}}      | 10128                                               | \-                             | YES                      |     |
| Country                                   | {{order.shipping\_address.country}}  | United States                                       | \-                             | YES                      |     |
| Order requires shipping?                  | {{order.requires\_shipping}}         | true/false                                          | \-                             | YES                      |     |
| |                                         |                                      |                                                     |                                |                          |     |
| |                                         |                                      |                                                     |                                |                          |     |
| |                                         |                                      |                                                     |                                |                          |     |
| |                                         |                                      |                                                     |                                |                          |     |
| **Advanced Variables**                    |                                      |                                                     |                                |                          |     |
| Order/Abandoned cart items(\*Coming Soon) | {{#each Order line\_items as \| item | }}                                                  |                                | YES                      | YES |
| | item.id                                 |                                      |                                                     |                                |                          |     |
| | item.image                              |                                      |                                                     |                                |                          |     |
| | item.title                              |                                      |                                                     |                                |                          |     |
| | item.quantity                           |                                      |                                                     |                                |                          |     |
| | item.price                              |                                      |                                                     |                                |                          |     |
| | item.line\_price                        |                                      |                                                     |                                |                          |     |
| | {{/each}}                               |                                      |                                                     |                                |                          |     |
| |                                         |                                      |                                                     |                                |                          |     |
| Order Tax Details(\*Coming Soon)          | {{#each Order tax\_lines as \| tax   | }}                                                  |                                | \-                       | YES |
| | tax.title                               |                                      |                                                     |                                |                          |     |
| | tax.rate                                |                                      |                                                     |                                |                          |     |
| | tax.price                               |                                      |                                                     |                                |                          |     |
| | {{/each}}                               |                                      |                                                     |                                |                          |     |
| |                                         |                                      |                                                     |                                |                          |     |
| |                                         |                                      |                                                     |                                |                          |     |
| |                                         |                                      |                                                     |                                |                          |     |

  