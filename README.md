### Functional interfaces with lambda expressions Pre-work

Expected time required: 15 min

In this scenario, you are processing a list of orders to determine which orders contain only one item so that item
picking and packaging can be done without human intervention. You have a list of orders, each order is a list of items. 
You must remove any orders that contain more than one item. `List` contains a method `removeIf` that accepts a 
`Predicate` interface as an argument. Implement the `checkOrders` method of `ShippingHelper` using a lambda expression 
for the input argument for `removeIf`.

1. Implement the `checkOrders` method of `ShippingHelper`. Use `List`'s `removeIf` method to check if orders contain 
only one item. Pass an inline lambda expression to `removeIf` that implements the `Predicate` functional interface. The 
method `removeIf` will remove the item from the `List` if the condition evaluates to `true`. Therefore, the lambda 
expression should return `true` if the order has more than one item.

HINTS:
* [Error: Conditional logic can be removed](./hints/hint-01.md)
