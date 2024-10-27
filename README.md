# iOS Token List App - Take-Home Exercise

## Overview

The goal of this project is to build an **iOS app** that retrieves and displays a list of tokens. This exercise will assess your knowledge of **iOS development, networking, and UI design**. The provided API will serve as the data source for the tokens. You should use **Swift** with either **UIKit** or **SwiftUI**, depending on your preference. Feel free to incorporate **third-party libraries** to demonstrate familiarity with modern development tools.

---

## Objective

Fetch the list of tokens from the following endpoint:  
[https://spot-labs.github.io/ios-interview-api/data.json](https://spot-labs.github.io/ios-interview-api/data.json)

Display the data in a scrollable list, showing the following properties for each token:
- **Name**  
- **Symbol**  
- **Price** (formatted to two decimal places)  
- **Logo Image** (from `logoURI`)

---

## Features and Requirements

### 1. Networking:
- Fetch token data from the provided API.  
- Handle errors gracefully (e.g., display alerts or retry options).

### 2. User Interface:
- Display tokens using a **UITableView** or **SwiftUI List**.  
- Use an appropriate layout for easy readability.  
- Load token logos efficiently (e.g., lazy loading with caching using **SDWebImage** or similar).

### 3. Architecture:
- Choose an architecture you're comfortable with (e.g., **MVC**, **MVVM**).  
- Ensure the code is modular, well-organized, and maintainable.

### 4. Third-Party Libraries:
- You are free to use libraries for networking and image handling
