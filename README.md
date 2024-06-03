# Interactive Photo Gallery

## Overview
This project involves building an interactive photo gallery based on provided Figma designs. It assesses skills in HTML, CSS, and JavaScript, as well as problem-solving abilities. The project also includes two coding challenges to test logical thinking and coding aptitude.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Coding Challenges](#coding-challenges)
  - [Array Manipulation](#coding-challenge-1-array-manipulation)
  - [String Transformation](#coding-challenge-2-string-transformation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- **Responsive Design:** Adapts seamlessly to different screen sizes and devices.
- **Figma Design Accuracy:** Matches the provided Figma designs, including layout, spacing, typography, and visual styles.
- **Hover Interaction:** Displays additional details when hovering over a photo.
- **Cross-browser Compatibility:** Ensures consistent performance across modern web browsers (Chrome, Firefox, Safari, and Edge).
- **Clean Code:** Follows best practices and coding conventions for HTML, CSS, and JavaScript.

## Technologies Used
- HTML
- CSS
- JavaScript

## Setup and Installation
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/muhozajohn/COA-TASKFORCE-TAKE-HOME-CHALLENGE.git
   cd COA-TASKFORCE-TAKE-HOME-CHALLENGE
   ```

2. **Open the Project:**
   Open the project in your preferred code editor (e.g., VS Code).

3. **View in Browser:**
   Open `index.html` in your web browser to view the interactive photo gallery.

## Usage
- **Navigate the Gallery:** Hover over the images to see additional details.
- **Responsive Design:** Resize the browser window to see how the gallery adapts to different screen sizes.

## Coding Challenges

### Coding Challenge 1: Array Manipulation
**Problem Statement:**
Given an array of integers and a target sum, determine if there exists a contiguous subarray within the array that sums up to the target. Return `true` if such a subarray exists, otherwise return `false`.

**Example:**
```javascript
Input: arr = [4, 2, 7, 1, 9, 5], target = 14
Output: true
Explanation: The subarray [7, 1, 9] sums up to 14, which is equal to the target.
```

**Solution:**
The solution is implemented in `challenges/coding-challenge/arrayMap.js`.

### Coding Challenge 2: String Transformation
**Problem Statement:**
Given a string, transform it based on the following rules:
- If the length of the string is divisible by 3, reverse the entire string.
- If the length of the string is divisible by 5, replace each character with its ASCII code.
- If the length of the string is divisible by both 3 and 5, perform both operations in the specified order.

**Example:**
```javascript
Input: "Hello World"
Output: "87 111 114 108 100 32 111 108 108 101 72"
Explanation: The length of the string is 11, which is divisible by both 3 and 5. First, the string is reversed, becoming "dlroW olleH". Then, each character is replaced by its ASCII code, resulting in "87 111 114 108 100 32 111 108 108 101 72".
```

**Solution:**
The solution is implemented in `challenges/coding-challenge/stringTransform.js`.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or feedback, please contact:
- **Name:** John Muhoza
- **Email:** muhozajohn4@gmail.com
- **GitHub:** [muhozajohn](https://github.com/muhozajohn)

This README provides clear and concise information about the project, including setup instructions, usage details, and solutions to the coding challenges.
