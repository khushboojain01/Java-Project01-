# Java GUI - Scientific Calculator With Currency Conversion

## Overview
This project is a **GUI-based Scientific Calculator** designed to offer multiple modes of operation:
- **Standard Mode**: Basic arithmetic operations like addition, subtraction, multiplication, and division.
- **Scientific Mode**: Advanced mathematical functions like trigonometric operations, logarithms, exponents, and more.
- **Currency Conversion Mode**: Allows users to convert between different currencies.

The project is built using **Java Swing** for the graphical user interface, providing a user-friendly and interactive design.

---

## Features
### 1. **Standard Calculator**
- Perform basic operations: addition, subtraction, multiplication, division.
- User-friendly layout for quick calculations.

### 2. **Scientific Calculator**
- Support for trigonometric functions: sin, cos, tan.
- Exponential and logarithmic functions.
- Factorial and power calculations.

### 3. **Currency Converter**
- Converts values between popular currencies.
- Uses a fixed exchange rate (can be extended to fetch live rates).

### 4. **Login System**
- A secure login interface to protect access to the calculator.
- Validates user credentials before granting access.

---

## Technologies Used
- **Java**: Core programming language for logic and functionality.
- **Java Swing**: For GUI development.
- **Java AWT**: For UI components.
- **Eclipse IDE**: Used for project development and debugging.

---

## Project Structure
```
├── login_system/       # Contains the login system functionality
│   └── loginsys.java   # Logic for the login interface
├── scicalc/            # Contains the calculator implementation
│   └── scicalc.java    # Logic for the calculator
├── java report.pdf     # Documentation and analysis of the project
├── README.md           # Project documentation
```

---

## How to Run
### Prerequisites
- Ensure you have **Java JDK 8 or later** installed on your system.
- **Eclipse IDE** installed on your machine.

### Steps
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/khushboojain01/Java-Project01.git
   ```
2. Open **Eclipse IDE** and import the project:
   - Go to `File > Import > Existing Projects into Workspace`.
   - Select the project folder.
3. Locate the `scicalc.java` or `loginsys.java` file in the `src` folder.
4. Right-click the file and select `Run As > Java Application`.
5. Follow the login prompt to access the calculator.

---

## Screenshots
![Screenshot of the application](./Frame%201.png)


---

## Future Enhancements
- Add live currency conversion using APIs.
- Improve the GUI design for a modern look and feel.
- Extend scientific functions for advanced mathematical operations.
- Add a history feature to track past calculations.

---

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to:
1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

---

## License
This project is licensed under the [MIT License](LICENSE).

---
