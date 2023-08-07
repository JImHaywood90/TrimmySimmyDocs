# TrimmySimmy Documentation

## Overview

TrimmySimmy is a web-based application designed to generate and manage quizzes. With a collection of exam data, users can take quizzes and receive immediate feedback on their performance.

## Code Structure

### JavaScript

#### generateExam.js

This script is central to the exam generation process. Key functionalities include:
- Fetching exam data from the server using AJAX.
- Displaying questions to the user.
- Shuffling questions for a varied experience.
- Handling user interactions during the exam.

#### quiz.js

This script manages the quiz experience. Key features are:
- Initializing the quiz with questions.
- Handling user's answers and interactions.
- Calculating and displaying the user's score.
- Providing feedback based on user's answers.

### CSS

- **ExamGeneratorStyles.css**: Styles specific to the exam generation interface.
- **styles.css**: General styles for the application.

### JSON

These files contain the data for various exams:
- AZ-104.json
- MS-900.json
- PL-400.json
- PL-600.json

### PHP

- **get-exam.php**: Fetches a specific exam's data.
- **list-exams.php**: Lists all available exams.
- **upload-exam.php**: Handles the uploading of new exam data.

### HTML

#### QJ.html (Questy Jenny!)

This HTML file serves as the main interface for generating and reviewing exams. It includes:
- A step-by-step wizard for creating and reviewing exams.
- Multiple sections for adding different types of questions (e.g., Single Answer, Multiple Answer, Drag and Drop).
- A review section to view and edit added questions.
- A final section to view the resulting JSON and upload the exam.

## Usage

### Creating a Multiple Answer Question

1. Click on the "Add New Question" button.
2. Select "Multiple Answer" as the question type.
3. Enter the question text in the provided textarea.
4. Add answer options by clicking on the "Add Option" button.
5. Select the correct answer by checking the corresponding checkbox.
6. Provide an explanation for the correct answer (optional).
7. Click on the "Save Question" button to save the question.

### Creating a Drag and Drop Question

1. Click on the "Add New Question" button.
2. Choose "Drag and Drop" as the question type.
3. Enter the question text in the given textbox.
4. Specify the number of available options using the number input.
5. Click on the "Generate Options" button to generate the required number of option inputs.
6. Fill in the available options.
7. Arrange the correct order of options by clicking on them in the correct sequence.
8. Provide an explanation for the question (optional).
9. Click on the "Save and Add More" button to save the question and continue adding more questions of the same type, or click on the "Save and Close" button to save and exit.

### Creating a Sortable List Question

1. Click on the "Add New Question" button.
2. Choose "Sortable List" as the question type.
3. Enter the question text in the provided textarea.
4. Add the options in the correct order by clicking on the "Add Option" button.
5. Provide an explanation for the correct order (optional).
6. Click on the "Save and Add More" button to save the question and continue adding more questions of the same type, or click on the "Save and Close" button to save and exit.

### Creating a Single Answer Question

1. Click on the "Add New Question" button.
2. Select "Single Answer" as the question type.
3. Enter the question text in the provided textarea.
4. Add answer options by clicking on the "Add Option" button.
5. Select the correct answer using the radio button.
6. Provide an explanation for the correct answer (optional).
7. Click on the "Save and Add More" button to save the question and continue adding more questions of the same type, or click on the "Save and Close" button to save and exit.

### Creating a Dropdown Question

1. Click on the "Add New Question" button.
2. Choose "Dropdown" as the question type.
3. Enter the question text in the provided textarea.
4. Add dropdown options by clicking on the "Add Dropdown Option" button.
5. Specify the correct answer from the dropdown list.
6. Provide an explanation for the correct answer (optional).
7. Click on the "Save and Add More" button to save the question and continue adding more questions of the same type, or click on the "Save and Close" button to save and exit.

### Reviewing Questions

1. Access the "Review Questions" tab.
2. Browse through the list of questions in the table.
3. Use the search bar to find specific questions.
4. Apply filters to narrow down the question list.
5. Edit or delete questions using the context menu or buttons in the table.
6. Click on the pagination buttons to navigate through multiple pages of questions.

### Customizing the Question Generator

1. Modify the question types available by editing the HTML template and JavaScript functions.
2. Customize the appearance and layout by updating the CSS styles.
3. Integrate additional libraries or plugins to extend the functionality.
4. Add features such as exporting questions to different formats (e.g., CSV, JSON).

Feel free to explore the various functionalities of the Question Generator and adapt it to your specific needs. The application is designed to be flexible and easily customizable to suit different use cases.
