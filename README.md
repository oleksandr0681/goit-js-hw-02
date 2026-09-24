# goit-js-hw-02

Homework assignment #2 from the [GoIT](https://goit.global/) JavaScript course. A set of four small exercises practicing conditional logic (`if/else`, `switch`) and string methods in vanilla JavaScript.

## 📋 About

Each task is implemented as a standalone function that is called with sample inputs, logging the result to the console:

- **Task 1** — `makeTransaction(quantity, pricePerDroid, customerCredits)`: calculates an order's total price and returns a confirmation message, or an "Insufficient funds!" message if the customer can't afford it.
- **Task 2** — `formatMessage(message, maxLength)`: truncates a message to a maximum length, appending `...` if it was shortened.
- **Task 3** — `checkForSpam(message)`: case-insensitively checks whether a message contains the words "spam" or "sale".
- **Task 4** — `getShippingCost(country)`: uses a `switch` statement to look up the shipping cost for a set of supported countries, returning a "no delivery" message for unsupported ones.

## 🛠️ Tech Stack

- Vanilla JavaScript (ES modules)
- HTML5

## 📁 Project Structure

```
goit-js-hw-02-main/
├── js/
│   ├── task-1.js    # Transaction with funds check
│   ├── task-2.js    # Message truncation
│   ├── task-3.js    # Spam message detection
│   └── task-4.js    # Shipping cost lookup by country
├── .prettierrc.json   # Prettier configuration
└── index.html          # Loads all four task scripts as ES modules
```

## 🚀 Getting Started

Open `index.html` in a browser and check the browser console (DevTools) to see the logged results of each task.
