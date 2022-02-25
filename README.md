Tests:

Describe: Pizza()

Test 1: "It should return a pizza object with two properties for toppings and size"
Code: const pizzaOrder = new Pizza(["anchovies", "pepperoni"], "medium");
Expected Output: Pizza { topping: ["anchovies", "pepperoni"], size: "medium"}

------------------

Describe: price()

Test 2: "It should return the orderTotal according to the pizza1 object size value"
Code: pizza1.price("small");
Expected Output: 5

------------------

Describe: price()

Test 3: "It should return the orderTotal according to the pizza1 object size and topping value"
Code: pizza1.price("anchovie", "small");
Expected Output: 6

-----------------