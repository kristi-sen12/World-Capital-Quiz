# World-Capital-Quiz
 A fun web-based quiz application that tests your knowledge of world capitals. The application randomly displays a country, and the user has to enter its capital city. The score increases for every correct answer, and the game ends when an incorrect answer is submitted.

## Features

-  Randomly selects a country from the PostgreSQL database
-  Checks the user's answer (case-insensitive)
-  Displays the current score
-  Ends the game on the first incorrect answer
-  Restart option to play again
-  Simple and responsive user interface using EJS and CSS

## Tech Stack

- **Node.js**
- **Express.js**
- **PostgreSQL**
- **EJS**
- **HTML5**
- **CSS3**
- **Body Parser**
- **dotenv**

## 📁 Project Structure

```
World-Capital-Quiz/
│
├── public/
│   └── styles/
│       └── main.css
│
├── views/
│   └── index.ejs
│
├── index.js
├── package.json
├── package-lock.json
├── capitals.csv
├── .env
├── .gitignore
└── README.md
```

# How to play?
1. A country name is displayed.
2. Type its capital city.
3. Click **Submit**.
4. Correct answers increase your score.
5. A wrong answer ends the game.
6. Click **Restart** to play again.

## 📷 Screenshots
# Home page
<img width="959" height="442" alt="Screenshot 2026-07-02 003700" src="https://github.com/user-attachments/assets/6de80be7-c775-4291-baf6-963f44b43b72" />

# Game Over
<img width="955" height="443" alt="Screenshot 2026-07-02 003820" src="https://github.com/user-attachments/assets/72ca71e5-231b-4aa3-969c-35b7065cd9ba" />

# Restart for a new game
<img width="957" height="440" alt="Screenshot 2026-07-02 003832" src="https://github.com/user-attachments/assets/780ff030-39dc-41fb-a4d0-8e07bf762b09" />

## Future Improvements

- Add multiple difficulty levels
- Track the highest score
- Add a timer for each question
- User authentication
- Leaderboard
- More countries and capitals





