Arithmetic Flash Cards
======================

A clean, modern, and responsive web-based flash card application designed to help users practice basic arithmetic skills. The app is built with vanilla HTML, CSS, and JavaScript, and is contained within a single `index.html` file for simplicity and portability.

✨ Features
----------

-   **Customizable Sessions:** Users can select specific numbers (0-12) and operations (addition, subtraction, multiplication, division) to create a tailored practice session.

-   **Interactive Flash Cards:** A clean, flippable card interface displays a problem on the front and the answer on the back.

-   **Smart Deck Generation:** The app generates a unique set of problems based on user selections, ensuring no duplicates. Incorrectly answered cards are shuffled back into the deck for reinforcement.

-   **Progress Tracking:** A visual progress bar and percentage complete indicator show how far the user is in the current session.

-   **Detailed Statistics:** The app tracks key metrics like total cards, remaining cards, attempts, correct/incorrect answers, and overall accuracy.

-   **Persistent Settings:** The user's selected numbers and operations are saved in local storage, making it easy to start a new session with the same preferences.

-   **Light & Dark Modes:** Includes a theme switcher with options for light, dark, or system-default themes to suit user preference.

-   **Responsive Design:** The layout is fully responsive and works seamlessly on desktops, tablets, and mobile devices.

-   **Confetti Celebration:** A fun confetti animation celebrates the successful completion of a session.

🚀 How to Use
-------------

1.  **Open the `index.html` file** in any modern web browser.

2.  **Select Numbers:** Click on the numbers you want to include in your problems. You must select at least two.

3.  **Select Operations:** Choose one or more arithmetic operations (+, -, ×, ÷).

4.  **Start Session:** Click the "New Session" button to generate the deck and begin.

5.  **Practice:**

    -   View the problem on the card.

    -   Click the "Check" button to flip the card and see the answer.

    -   Mark your answer as correct (✓) or incorrect (✗).

6.  **Complete the session** and see your final accuracy score.

🛠️ Technologies Used
---------------------

-   **HTML5:** For the structure and content of the application.

-   **CSS3:** For all styling, including the card animations, responsive layout, and theme variables.

-   **Vanilla JavaScript (ES6+):** For all application logic, including deck generation, state management, and DOM manipulation.

-   **Canvas-Confetti:** A lightweight library used for the end-of-session celebration effect.

📂 File Structure
-----------------

The entire application is self-contained in a single file for maximum simplicity:

-   `index.html`: Contains the HTML structure, CSS styles, and JavaScript logic.
