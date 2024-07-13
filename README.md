# Java Quiz Application

This Java Quiz Application is a simple desktop quiz game built using Swing and AWT libraries. It presents a series of questions to the user and calculates the score based on the user's answers.

## Features

- **Multiple Choice Questions**: The quiz consists of 10 multiple-choice questions.
- **Timer**: Each question has a timer of 15 seconds.
- **50-50 Lifeline**: The lifeline disables two incorrect options, making it easier for the user to choose the correct answer.
- **Next and Submit Buttons**: Users can navigate through the questions using the "Next" button and submit their answers at the end.
- **Score Calculation**: The application calculates the final score based on the number of correct answers.

## Screenshots

![Quiz Application](icons/quiz.jpg)

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- IDE such as NetBeans, Eclipse, or IntelliJ IDEA

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/GauravThakur100/Quiz_Application-using-java.git
    ```
2. Open the project in your preferred IDE.

3. Compile and run the `Quiz.java` file.

## Code Overview

### `Quiz.java`

This file contains the main logic of the quiz application. It includes the following functionalities:

- **Initialization**: Sets up the quiz window, including the layout and design.
- **Question Management**: Stores the questions, options, and correct answers.
- **Event Handling**: Handles the actions for the "Next", "50-50 Lifeline", and "Submit" buttons.
- **Timer**: Implements a countdown timer for each question.
- **Score Calculation**: Calculates and displays the final score based on the user's answers.

### Example Question Data Structure

```java
String questions[][] = new String[10][5];
questions[0][0] = "Which is used to find and fix bugs in the Java programs.?";
questions[0][1] = "JVM";
questions[0][2] = "JDB";
questions[0][3] = "JDK";
questions[0][4] = "JRE";
```

### Example Answer Data Structure

```java
String answers[][] = new String[10][2];
answers[0][1] = "JDB";
```

## Running the Application

To run the application, execute the `main` method in the `Quiz` class:

```java
public static void main(String[] args) {
    new Quiz("User");
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- **Images**: Icons used in the application are sourced from external resources.

## Contact

For any questions or feedback, please reach out to me through my [GitHub profile](https://github.com/GauravThakur100).
