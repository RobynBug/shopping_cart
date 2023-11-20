Shopping cart with add, remove, and payment features.
* ADD feature
  * Feature allows the user to add to the cart and increase the quantity of each item.
* Remove feature
  * Feature allows the user to decrease the quantity of items in the cart or remove the item entirely.
* Payment feature
  * Feature allows user to render payment.
    * Conditional statement checks for sufficient payment.
    * If the condition is met:
      * A message is returned
      * Change amount is returned if applicable
      * Cart is emptied
    * If condition is not met:
      * A message is returned regarding insufficient funds
      * Remaining amount is returned
      * Any additional amount received will be added to original amount until full amount is received 
