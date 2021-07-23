# Assignment 
## Task 1

Given an integer x, return true if x is palindrome integer.

An integer is a palindrome when it reads the same backward as forward. For example, 121 is palindrome while 123 is not.


### Example 1:

    Input: x = 121

    Output: true

### Example 2:

    Input: x = -121

    Output: false

Explanation: From left to right, it reads -121. From right to left, it becomes 121-. Therefore it is not a palindrome.

### Example 3:

    Input: x = 10

    Output: false

Explanation: Reads 01 from right to left. Therefore it is not a palindrome.

### Example 4:

    Input: x = -101

    Output: false

 

Constraints:

    -231 <= x <= 231 - 1
    
## Task 2

You are given an array prices where prices[i] is the price of a given stock on the ith day.

Find the maximum profit you can achieve. You may complete as many transactions as you like (i.e., buy one and sell one share of the stock multiple times).

Note: You may not engage in multiple transactions simultaneously (i.e., you must sell the stock before you buy again).

 

### Example 1:

    Input: prices = [7,1,5,3,6,4]
    Output: 7

Explanation: Buy on day 2 (price = 1) and sell on day 3 (price = 5), profit = 5-1 = 4.
Then buy on day 4 (price = 3) and sell on day 5 (price = 6), profit = 6-3 = 3.

### Example 2:

    Input: prices = [1,2,3,4,5]
    Output: 4

Explanation: Buy on day 1 (price = 1) and sell on day 5 (price = 5), profit = 5-1 = 4.
Note that you cannot buy on day 1, buy on day 2 and sell them later, as you are engaging multiple transactions at the same time. You must sell before buying again.

### Example 3:

    Input: prices = [7,6,4,3,1]
    Output: 0

Explanation: In this case, no transaction is done, i.e., max profit = 0.

 

Constraints:

    1 <= prices.length <= 3 * 104
    0 <= prices[i] <= 104

## Task 3

You are building Website of a book shop which deals with selling and renting books. You can develop multiple pages for this project.

1. New book can be created, their information can be edited, and they can be deleted. It should be store name, ISBN, and price details etc.
2. When an order is placed, you should **email the user a receipt**. You can integrate with the sandbox of [Mailgun.com](https://www.mailgun.com/) for this. _Note:_ Every Mailgun account comes with a sandbox email account domain (whatever@sandbox123.mailgun.org) that you can send from by default. So, there's no need to setup any DNS for your domain for this task. [Read more here](https://documentation.mailgun.com/en/latest/faqs.html#how-do-i-pick-a-domain-name-for-my-mailgun-account).
3. Design a page for the report of all orders.
4. Validation on all the form values.
5. Image upload of every book.
6. No need to design the backend for this project. You can use firebase or any other backend free services.
7. Any design library can be used on this project.

(You can use stackoverflow or any other info website for this project)

