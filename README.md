# CalculatorApp

## Overview
The **CalculatorApp** is a simple, user-friendly calculator application built using JavaFX. It follows the **Model-View-Controller (MVC)** design pattern, allowing users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The application also includes error handling for cases like division by zero.

## How to Run the Application

### Prerequisites
To run the CalculatorApp, you need the following:
- **Java Development Kit (JDK)** (version 8 or later)
- **JavaFX SDK** (if your JDK doesn't include JavaFX)
- **JavaFX-enabled IDE** (e.g., IntelliJ IDEA, Eclipse) or a command-line setup

### Steps to Run:
1. **Download the project files** or clone the repository:
   ```bash
   git clone <https://github.com/lleylawa/CalculatorApp.git>
   ```
2. **Open the project** in your preferred IDE or prepare the project files for execution in a JavaFX environment.

3. **Ensure JavaFX is configured** in your IDE. Follow these steps:
   - For **IntelliJ IDEA**, add JavaFX SDK under Project Structure -> Libraries.
   - For **Eclipse**, go to Project -> Properties -> Java Build Path -> Add External JARs to include JavaFX.
   
4. **Run the application**:
   - Open the `HelloApplication.java` file in your IDE.
   - Run the application directly from your IDE or build the project and run it via the terminal.
   
5. The calculator window should open up, allowing you to perform calculations.

## How to Use the Calculator

### Basic Operations:
- **Enter a number** by clicking on the digit buttons (0-9).
- **Choose an operation** by clicking on the operator buttons (`+`, `-`, `*`, `/`).
- **Perform the calculation** by clicking the `=` button.
- **Clear the input** by pressing the `Clear` button.

### Example Usage:
1. To add `5 + 3`:
   - Click `5`.
   - Click `+`.
   - Click `3`.
   - Click `=`, and the result will display `8`.

2. To divide `8 / 0` (edge case):
   - Click `8`.
   - Click `/`.
   - Click `0`.
   - Click `=`, and the display will show `Error` (since division by zero is undefined).

### Special Functions:
- **Clear**: Resets the display and allows you to start a new calculation.
- **Error Handling**: If you attempt to divide by zero or encounter another invalid operation, the calculator will display an error message.

## Screenshots

Here are some screenshots of the calculator in action:

### Screenshot 1: Initial UI Design
![Снимок экрана 2024-10-20 145810](https://github.com/user-attachments/assets/ea91997e-d47f-4837-bbec-cbbce64410a7)

### Screenshot 2: Performing Addition
![Снимок экрана 2024-10-20 145929](https://github.com/user-attachments/assets/b6096d24-16e1-4a1b-93ea-ab702feb09dd)
![Снимок экрана 2024-10-20 145953](https://github.com/user-attachments/assets/8d2dde31-1cb9-4381-a07a-2409aee9e7dc)
![Снимок экрана 2024-10-20 150031](https://github.com/user-attachments/assets/e79840b7-d6b3-4c21-b39e-74acae272200)

### Screenshot 3: Division by Zero Error
![Снимок экрана 2024-10-20 150506](https://github.com/user-attachments/assets/e00e1655-82d6-465d-815b-172863927918) 
![Снимок экрана 2024-10-20 150552](https://github.com/user-attachments/assets/29bd337f-3a57-4efe-882d-cc949ff7fbc3) 
![Снимок экрана 2024-10-20 150617](https://github.com/user-attachments/assets/af3261df-b744-4304-8392-f33ef7235ed2)


## Known Issues

- **Division by Zero**: The calculator correctly handles division by zero by showing an error, but does not halt the application. You can reset the calculator and start a new calculation.
- **Invalid Inputs**: If an operator is clicked before entering any number, no action is taken, and the calculator waits for valid input.
---
