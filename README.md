# 🛠️ Ninja Store XML Processor

This repository contains a script to clean and process the distributor's `productList.xml` for Ninja Store automation.

### ✅ Features

- Updates product **availability** based on category rules:
  - `NS` → Available
  - `Action` → Available from 10 to 30 days
  - `Special` or `Ninja Stock` → untouched (manual override)
  
- Calculates **final selling price** based on the client’s formula:
