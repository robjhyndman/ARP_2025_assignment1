# Assignment1

A supermarket has `p` checkouts and customers must choose one, forming a queue if it is already occupied. Customers always choose the shortest queue. The time between each new customer arriving at the checkouts has an exponential distribution with mean $\mu$ minutes. The time it takes for a checkout operator to process a customer has an independent exponential distribution with mean $\lambda$ minutes.

Write an R function to simulate the supermarket queues at each checkout, taking the arguments `mu`, `lambda`, `p` and `n`, and returning the total number of customers waiting to be served, `n` minutes after the supermarket opens. The argument `p` should have default value 3, while `n` should have default value `720` (the number of minutes in a 12 hour day). The other arguments should have no default values. Your function should be named `remaining_customers`.

Your code should be as efficient as possible. Arguments should be checked for range and class.
