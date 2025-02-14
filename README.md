# JustGrade

JustGrade is a simple web application designed to help educators and developers upload a student's file and an assignment/rubric file, and use AI to grade the student’s submission based on the rubric. The application displays the grading result and feedback generated by AI. The design is clean and responsive, powered by React and styled with CSS.

## Features

- Upload a student's file and an assignment/rubric file.
- Display the selected file names and contents directly on the page.
- Submit both files for grading via the AI, and get a grade and feedback.
- Responsive layout with a navigation bar and styled components.
- Display the grading results and feedback from AI in a user-friendly format.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/JustGrade.git
   cd JustGrade
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to:

   ```bash
   http://localhost:3000
   ```

## File Structure

```
JustGrade/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
├── public/
├── styles/
│   ├── globals.css
├── package.json
└── README.md
```

## Usage

1. **Upload the student's file** using the **"Select File"** button.
2. **Upload the assignment/rubric file** using the **"Assignment/Rubric"** button.
3. **Click the "Submit" button** to send both files to the AI for grading.
4. View the grading results, including the **grade** and **feedback**, displayed on the page below the submit button.

## Technologies Used

- **Next.js**: Framework for React-based applications.
- **React**: Frontend library for building UI components.
- **CSS**: Styling for the application.
- **FileReader API**: For reading and displaying file contents.
- **OpenAI API**: For generating grades and feedback based on the uploaded rubric and student file.

## Future Enhancements

- Add functionality to export grading results as a CSV file.
- Implement authentication and user accounts for secure grading tools.
- Improve the grading model with more refined AI-based evaluation.

## Contributing

Feel free to fork this repository and contribute to the project by submitting pull requests. For major changes, please open an issue to discuss the proposed changes.
