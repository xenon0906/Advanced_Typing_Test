# Advanced_Typing_Test

Welcome to the Typing Test Project! This project is a typing test application that measures your typing speed (in words per minute) and accuracy. The project is developed using Java and Python, with additional features like personalized reports and visualizations.

## Features

- **Typing Speed Measurement**: Calculates Words Per Minute (WPM) based on your typing speed.
- **Accuracy Calculation**: Determines the accuracy of your typed sentence compared to the reference sentence.
- **Personalized Reports**: Generates detailed reports with insights into your typing performance, including accuracy and WPM.
- **Graphical Visualization**: Provides a visual graph of typing speed over multiple attempts using Python's Matplotlib.
- **PDF Report Generation**: Automatically generates a PDF report with all the detailed results.

## Prerequisites

Before you can run this project, make sure you have the following installed on your system:

1. **Java Development Kit (JDK)**
   - You can download and install the JDK from [Oracle's official website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

2. **Python 3**
   - Download and install Python 3 from the [official Python website](https://www.python.org/downloads/).

3. **Required Python Libraries**
   - Install the necessary Python libraries using `pip`:
     ```bash
     pip install matplotlib reportlab
     ```

## Getting Started

Follow these steps to set up and run the project:

1. **Download the Project:**
   - Clone the repository or download the ZIP file from the GitHub repository.
   - If you downloaded the ZIP file, extract it to your desired location.

2. **Compile the Java Code:**
   - Open a terminal or command prompt.
   - Navigate to the directory where the project files are located.
   - Compile the Java program:
     ```bash
     javac EnhancedTypingTest.java
     ```

3. **Run the Java Program:**
   - After compiling, run the Java program:
     ```bash
     java EnhancedTypingTest
     ```

4. **Run the Python Script:**
   - The Java program will automatically invoke the Python script to generate graphs and reports. Ensure that Python is correctly set up on your system, and the required libraries are installed.

## Project Structure

- `EnhancedTypingTest.java`: The main Java program that runs the typing test.
- `record_speed.py`: Python script to record typing speed, generate graphs, and create PDF reports.
- `typing_speeds.txt`: A text file to store typing speed data for generating graphs.
- `typing_test_report.pdf`: The PDF report generated after each typing test.

## Usage

1. **Start the Typing Test:**
   - Run the Java program and follow the instructions to complete the typing test.
   - Enter your name when prompted to generate a personalized report.

2. **View the Report:**
   - After completing the test, a PDF report will be generated, providing detailed insights into your typing performance.

## Contribution

Feel free to fork this repository, contribute new features, or fix issues. Pull requests are always welcome!

## License

This project is licensed under the MIT License.

---

This README provides a clear and detailed overview of your project, instructions for setting it up, and how to run it.
