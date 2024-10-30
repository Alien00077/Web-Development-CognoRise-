# Web-Development_CognoRise

# BMI Calculator

A sleek, interactive **Body Mass Index (BMI) Calculator** built with **HTML**, **CSS**, and **JavaScript**. This web-based tool makes it easy for users to calculate their BMI based on weight and height inputs, providing quick feedback on their BMI category.

---

## Table of Contents

- [Live Demo](#live-demo)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [BMI Categories](#bmi-categories)
- [Contributing](#contributing)
- [License](#license)

---

## Live Demo

To see the BMI Calculator in action, [click here](https://yourusername.github.io/BMI_Calculator/) or download the file and run it locally on your machine.

---

## Features

- **Simple, Intuitive UI**: User-friendly design that adapts beautifully to both mobile and desktop screens.
- **Instant BMI Calculation**: Computes BMI using the latest BMI formula based on weight and height input.
- **Clear Result Display**: Shows both your BMI score and the BMI category you fall into (e.g., Normal weight, Overweight).
- **Error Handling**: Provides clear feedback if invalid input values are entered.

---

## Technologies

- **HTML** for structuring the page layout.
- **CSS** for styling, including responsive adjustments for mobile.
- **JavaScript** for calculation logic and error handling.

---

## Getting Started

To get the BMI Calculator up and running on your local machine, follow these simple steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/BMI_Calculator.git



## BMI Categories

The BMI categories used in this application are as follows:

| Category       | BMI Range            |
|----------------|----------------------|
| Underweight    | Less than 18.5       |
| Normal weight  | 18.5 - 24.9          |
| Overweight     | 25 - 29.9            |
| Obese          | 30 and above         |

## Contributing

We welcome contributions! To improve this project:

1. **Fork the Repository**.
2. **Create a New Branch** for your feature.
3. **Make Your Changes** and commit them.
4. **Open a Pull Request** for review.

Feel free to suggest enhancements, report issues, or submit pull requests!


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

# Online Quiz App

A web-based quiz application that allows users to answer multiple-choice questions and receive immediate feedback. This app tracks the user's score and displays the final result upon completion.

## Features

- Multiple-choice questions with immediate feedback.
- Color-coded results (green for correct answers, red for incorrect).
- Displays the user’s final score at the end of the quiz.

## How to Use

### 1. Open the Application
Open `Online_QuizApp.html` in any modern web browser to start the quiz.

### 2. Answer Questions
- Each question is displayed with multiple answer options.
- Click on an answer to select it; the app will immediately show if the answer was correct or incorrect.

### 3. Move to the Next Question
After selecting an answer, click the "Next" button to proceed to the following question.

### 4. View Final Score
Once all questions have been answered, the app will display your final score out of the total number of questions.

## Contributing

We welcome contributions to improve the Online Quiz App. Here’s how you can help:

1. **Fork the Repository.**
2. **Create a New Branch** for your feature.
3. **Make Your Changes** and commit them.
4. **Open a Pull Request** for review.

Feel free to suggest new features, report bugs, or submit improvements!


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

# Travel Booking System

A web-based travel booking system that allows users to book trips by specifying a destination and a travel date. Booked trips are displayed in a list, providing a simple and effective way to track upcoming travel plans.

## Features

- Allows users to enter a travel destination and select a travel date.
- Displays each booking as a list item with destination and date details.
- Automatically resets the form after each booking.

## How to Use

1. **Open the Application**  
   Open `Travel_Booking_System.html` in any modern web browser.

2. **Make a Booking**  
   - Enter the **Destination** in the provided text field.
   - Select the **Date** for your trip.
   - Click **Book Now** to add the booking to the list.

3. **View Booked Trips**  
   Each booking will be displayed below the form in a list format, showing the destination and travel date.

## File Structure

- `Travel_Booking_System.html`: The main HTML file for the application.
- `booking.css`: Contains styling for the application (if present).
- `booking.js`: JavaScript file managing form interactions and bookings.

## Contributing

We welcome contributions to improve the Travel Booking System. Here’s how you can contribute:

1. **Fork the Repository.**
2. **Create a New Branch** for your feature.
3. **Make Your Changes** and commit them.
4. **Open a Pull Request** for review.

Feel free to suggest new features, report bugs, or enhance existing functionality!


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
# Currency Converter

A web-based currency converter application that allows users to convert an entered amount from one currency to another using real-time exchange rates.

## Features

- Allows users to input an amount and select "from" and "to" currencies.
- Uses real-time exchange rates to calculate and display the converted amount.
- Includes a default currency selection for convenience (`USD` to `INR`).

## How to Use

1. **Open the Application**  
   Open `Currency_Converter.html` in any modern web browser.

2. **Enter Amount**  
   Enter the amount you want to convert.

3. **Select Currencies**  
   - Choose the currency you’re converting **from** and **to** from the dropdowns.
   - The application will automatically load available currencies from an external exchange rate API.

4. **Convert Currency**  
   - Click **Convert** to see the result. The converted amount will be displayed below the button.

## Dependencies

This application uses the [ExchangeRate-API](https://www.exchangerate-api.com) to retrieve real-time currency exchange rates.

## File Structure

- `Currency_Converter.html`: The main HTML file for the application, including embedded styles and JavaScript for functionality.

## Contributing

We welcome contributions to improve the Currency Converter. Here’s how you can help:

1. **Fork the Repository.**
2. **Create a New Branch** for your feature.
3. **Make Your Changes** and commit them.
4. **Open a Pull Request** for review.

Feel free to suggest new features, report bugs, or enhance existing functionality!



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
# To-Do List Web App

A simple, responsive To-Do List application built with HTML, CSS, and JavaScript. This app allows users to add tasks to a list and delete them when completed.

## Features

- **Add Tasks**: Enter a new task in the input field and click "Add Task" to include it in the list.
- **Delete Tasks**: Remove a task by clicking the "Delete" button next to it.
- **Responsive Design**: Clean and centered layout that adapts well to different screen sizes.

## Demo

![To-Do List Screenshot](screenshot.png)

## Technologies Used

- **HTML**: Structure of the app.
- **CSS**: Styling for layout, color, and hover effects.
- **JavaScript**: Functionality for adding and deleting tasks.

## Code Overview

### HTML

The HTML file creates a container with an input field, an "Add Task" button, and an empty list to hold tasks.

### CSS

Custom CSS styles are applied to:
- Center the container.
- Style buttons, input fields, and task list items.
- Add hover effects on buttons.

### JavaScript

A single `addTask()` function:
- Adds a new task to the list if the input field is not empty.
- Creates a "Delete" button next to each task to remove it when clicked.

## How to Use

1. Clone the repository.
2. Open `index.html` in a web browser.
3. Add tasks by typing into the input field and clicking "Add Task".
4. Delete tasks by clicking the "Delete" button next to each task.

---


