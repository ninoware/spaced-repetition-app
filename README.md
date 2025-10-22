# Spaced Repetition Quiz App

A minimal, local-first web application for exam preparation using the SM-2 spaced repetition algorithm. This was generated with Claude 4.5 as a learning project.

## Features

- **Smart Scheduling**: Uses the SM-2 algorithm to automatically schedule questions based on your performance
- **Progress Tracking**: Visual indicators showing your last 5 attempts for each question
- **Question Library**: Manage all your questions with sorting, editing, and deletion capabilities
- **Statistics Dashboard**: Track success rates, identify weak areas, and monitor overall progress
- **Local Storage**: All data saved automatically in your browser
- **Portable**: Export/import your questions and progress as JSON files
- **Minimal Design**: Clean black and white interface with color used only for feedback

## How to Use

### Getting Started
1. Open the app in your browser
2. Click "Library" and then "Add Question"
3. Enter your question, 4 answer options, and select the correct answer
4. Start quizzing by clicking "Quiz"

### Taking Quizzes
- Questions you haven't answered appear first
- Questions you struggle with appear more frequently
- Green border shows the correct answer if you're wrong
- Progress icons show your last 5 attempts (✓ = correct, ✗ = incorrect, ○ = not attempted)

### Managing Questions
- **Library View**: See all your questions with statistics
- **Edit**: Modify question text, answers, or the correct answer
- **Delete**: Remove questions you no longer need
- **Sort**: Click column headers to sort by success rate or number of attempts

### Exporting/Importing Data
- Click the download icon to export your data as a JSON file
- Click the upload icon to import previously exported data
- Use this to transfer your progress between computers

## Technical Details

- **No installation required**: Single HTML file that runs entirely in your browser
- **No server needed**: All data stored locally using localStorage
- **Framework**: Built with React 18
- **Styling**: Tailwind CSS
- **Algorithm**: SM-2 spaced repetition for optimal learning

## The SM-2 Algorithm

This app uses the SuperMemo 2 (SM-2) algorithm, which:
- Calculates optimal review intervals based on how well you know each question
- Increases intervals for questions you answer correctly
- Resets intervals for questions you get wrong
- Adjusts difficulty ratings based on your performance

## Local Development

Simply open `index.html` in any modern web browser. No build process or dependencies required.

## Data Privacy

All your data stays on your computer. Nothing is sent to any server. Your questions and progress are stored in your browser's localStorage.

## Browser Compatibility

Works in all modern browsers:
- Chrome (recommended)
- Firefox
- Safari

## Tips for Best Results

1. **Be consistent**: Review questions regularly for best retention
2. **Add questions gradually**: Build your question bank over time as you study
3. **Review weak areas**: Check the "Focus Areas" section to see which topics need more attention
4. **Export regularly**: Back up your data by exporting the JSON file

## License

Free to use and modify for personal use.

---

Created for exam preparation using evidence-based learning techniques.
