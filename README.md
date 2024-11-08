# Module 1 Solution - Lunch Checker

## Overview
This module 1, **Lunch Checker**, is a simple web application built using **AngularJS (1.8.2)**. It allows users to input a list of dishes separated by commas to check whether their lunch includes too many items. The application provides instant feedback with a message that changes based on the number of items entered.

## Technologies Used
- **HTML5**
- **CSS3**
- **AngularJS (1.8.2)**
- **JavaScript**

## Usage
1. Enter a list of dishes in the input field (e.g., `apple, sandwich, chips`).
2. Click the **"Check If Too Much"** button.
3. The application will display a message:
   - **If the input is empty**: The message "Please enter data first" will appear in **red**.
   - **If 3 or fewer items are entered**: The message "Enjoy!" will be shown.
   - **If more than 3 items are entered**: The message "Too much!" will be displayed.

## Code Highlights
- **Two-Way Data Binding** with `ng-model` for real-time data reflection.
- **Event Handling** using `ng-click` to trigger the `checkLunch` function.
- **Dynamic Styling** for conditional message color changes using `ng-style`.
<img width="751" alt="0" src="https://github.com/user-attachments/assets/405ac35e-6bf8-4511-9e3d-b1b8a87e3355">
<img width="838" alt="1" src="https://github.com/user-attachments/assets/95a1f0f1-daf2-48f3-819e-15fcd07540f6">
<img width="767" alt="2" src="https://github.com/user-attachments/assets/e48ca1b7-0adb-4a4c-b961-2aa54e071a69">
<img width="765" alt="3" src="https://github.com/user-attachments/assets/c7a88204-1ba1-4e3d-b5c3-19bb1ee71160">


## Author
Created by Quang Bui.

