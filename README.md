# ⏱️ Advanced Exam Pacing & Analytics Tool

A powerful, web-based utility designed to help students master their exam strategy. This tool allows you to simulate exams, track your pacing per question, and gain deep insights into your performance through advanced analytics.

## ✨ Features

### 🎯 Exam Simulation
-   **Customizable Setup**: Define the number of questions, total time limit, and marking scheme (positive/negative marks).
-   **Real-Time Pacing**: View your **Required Pace** vs. **Current Pace** live during the exam.
-   **Time Bank**: See exactly how much time you have "banked" (saved) or "borrowed" (overspent) compared to the ideal schedule.
-   **Question Navigation**: Jump between questions, mark difficult ones for review, and track your progress.
-   **Pause & Resume**: Need a break? Pause the exam and resume exactly where you left off.

### 📊 Advanced Analytics
After finishing the exam, get a comprehensive performance report:
-   **Score & Accuracy**: Instant calculation of your final score and accuracy percentage.
-   **Visual Charts**:
    -   **Score Distribution**: Donut chart showing Correct vs. Incorrect vs. Unattempted.
    -   **Pacing Scatter Plot**: Visualize time spent on every question to identify outliers.
    -   **Time Bank Trajectory**: Track how your time buffer evolved throughout the exam.
-   **Strategic Insights**: AI-like insights that analyze the "Cost of Mistakes" and identify "Time Sinks" (questions where you spent too much time and still got them wrong).
-   **Detailed Results**: A sortable table showing time spent, pace deviation, and outcome for every single question.

### 💾 Persistence
-   **Auto-Save**: Your progress is automatically saved to your browser's local storage. You can close the tab and resume your exam later.

## 🚀 Usage

1.  **Open the Tool**:
    Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Edge, Safari). No installation is required.

2.  **Configure Your Exam**:
    -   **Start/End Q#**: Set the question range (e.g., 1 to 50).
    -   **Total Time**: Set the duration in minutes.
    -   **Marking Scheme**: Enter marks for correct answers (e.g., +4) and negative marks for wrong answers (e.g., 1).
    -   **Answer Key (Optional)**: Pre-load correct answers (comma-separated like `a,b,c...`) for auto-grading.

3.  **Take the Exam**:
    -   Use the **Navigator** to switch questions.
    -   Select options (A, B, C, D) or use keyboard shortcuts.
    -   Keep an eye on the **Pacing Bar** and **Time Bank**.

4.  **Grade & Analyze**:
    -   Click **Finish & Grade**.
    -   If you didn't provide an answer key initially, you can enter the correct answers now.
    -   View your **Performance Report** and explore the charts.

## 🛠️ Tech Stack

-   **HTML5 & CSS3**: Core structure and styling.
-   **Bootstrap 5.3**: Responsive design and UI components.
-   **Chart.js**: Interactive data visualization.
-   **Vanilla JavaScript**: All logic for timing, state management, and analytics.

## 📝 License

This project is open-source and available for personal and educational use.
