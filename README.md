
-----

# Which Feminist Are You?

### A Personality Quiz Web Application

This project is a fun, interactive personality quiz built with vanilla HTML, CSS, and JavaScript. Users answer a series of questions to discover which influential feminist icon best matches their personality. The application features a dynamic quiz flow, local storage for saving results, and a live leaderboard to showcase the most popular results and player participation.

-----

### Features

  * **Interactive Quiz Flow:** A series of questions with multiple-choice answers guide the user through the quiz.
  * **Dynamic Scoring:** The quiz logic uses a simple scoring system to determine the user's result based on their choices.
  * **Persistent Leaderboard:** The application uses `localStorage` to save and display results, creating a leaderboard that persists across sessions. It shows the number of people who got each result and lists the names of participants.
  * **Responsive Design:** The interface is built with basic CSS to be clean, visually appealing, and usable on different screen sizes.

-----

### How It Works

The entire application is contained within a single `index.html` file.

  * **HTML Structure:** The HTML provides the basic layout for the landing page, quiz questions, and results screen.
  * **CSS Styling:** The `<style>` tag contains all the CSS to make the quiz visually appealing.
  * **JavaScript Logic:** The `<script>` tag handles all the application logic, including:
      * Storing quiz questions and possible results in a `quizData` array and a `resultMap` object.
      * Managing the quiz state (current question, user scores).
      * Rendering questions and handling user clicks.
      * Calculating the final result by finding the character with the highest score.
      * Interacting with the browser's `localStorage` to save and retrieve leaderboard data.
      * Dynamically updating the leaderboard to show total plays and a breakdown of results.

-----

### Getting Started

To run this project locally, simply clone the repository and open the `index.html` file in your web browser.

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
# Then, open index.html in your favorite browser
```

No server or additional dependencies are required, making it easy to deploy and share.

-----

### Future Enhancements

This project could be expanded with several improvements:

  * **External Files:** Separate the HTML, CSS, and JavaScript into individual files for better organization and maintainability.
  * **Backend Integration:** Implement a simple backend (e.g., using Node.js, Python/Flask) to store leaderboard data more securely in a database instead of `localStorage`.
  * **Expanded Content:** Add more questions and feminist icons to make the quiz more diverse and comprehensive.
  * **Better UI/UX:** Use a modern CSS framework like Bootstrap or Tailwind CSS for a more polished look and feel.
  * **Code Refactoring:** Refactor the JavaScript code to be more modular and object-oriented, following best practices for larger applications.

-----

### License

This project is licensed under the MIT License.
