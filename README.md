### Task: Supermarket

You are the owner of two supermarkets, one in Berlin and one in Leipzig.

To keep track of your stock, your income and your product prices you want to write a program.

To avoid duplicate code, write a Typescript-class called `Supermarket`.

The class should implement the following functionalities:

### Name of your store

- The class has a attribute called `name` that is a string representing the name of your store.

### Constructor

Write a constructor for your class.

- The constructor has the OPTION of being passed the name (as a string).
- If no name is given, a default name (i.e. `Store`) is used.

### Money

- Add a new private attribute to your class called `balance` that keeps track of your money.
- Your balance is 0 upon instantiation.
- Write a get-method for retrieving the current balance.

### Product Prices

You will need to keep track of your product prices.

- Create a new private object that has the product names as keys and their prices as values.
- The object is empty upon instantiation.

### New Product Price

- Write a class-method called `newProduct` that takes two arguments:

1. A string representing the name of the new product.
2. A number representing the price of the product.

The method adds the new key-value pair to the object of your products.

### Get Product Prices

- Write a get-method for retrieving your product prices.
- The method simply creates and returns a string, with all product-price pairs.
- Example output: 'apple: 0.5 EUR, banana: 0.2 EUR'

### Sell products

- Write a class-method called `sell` that takes two arguments:

1. A string representing the name of the sold product.
2. A number representing the quantity.

- The method retrieves the price of the product from the prices-object...
- ... multiplies it by the quantity and...
- ... adds the income to your balance.

## Using your class

Test your class by creating two new instances of Supermarket.

1. Instance 1: a store in Leipzig with the name "myLeipzig"
1. Instance 2: a store in Berlin with the name "myBerlin"

### Products in Leipzig

Add the following product-price pairs to your store in Leipzig:

- apple: 0.5
- banana: 0.2
- bread: 1.26
- milk: 1.49

### Products in Berlin

Add the following product-price pairs to your store in Berlin:

- pear: 0.5
- pineapple: 2.49
- watermelon: 3.29
- bread: 1.49

### Selling products

Sell the following products in your store in Leipzig:

- 3 apples, 5 bananas, 2 milk

Sell the following products in your store in Berlin:

- 1 watermelon, 2 bread, 3 pears

### Money?

How much money does each store have? How much money do you have in total?
