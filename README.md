This Python code creates a quiz-style game titled "Jogo das Três Pistas," where two teams compete to answer questions based on a series of progressively easier clues.

# Key Components of the Code:
Questions and Answers:

- A predefined list of questions (perguntas) includes a main term (correct answer) and three progressively easier hints. These hints are shown one by one if the team does not guess correctly.
Scoring System:

- Correct answers earn points based on how many hints were revealed before answering. The fewer hints used, the higher the points awarded, with up to 30 points for a first-try answer.
Team and Audience Interactions:

- Teams alternate in answering questions. If they fail after all hints are shown, the audience has a chance to answer and gain points.
- 
## Gameplay Loop:

The game runs in a loop, presenting a question to a team, showing hints, and collecting responses. Once a team or the audience reaches 100 points, the game ends.
Interface and Controls:

The os.system('cls' if os.name=='nt' else 'clear') command clears the console screen between turns to make the experience cleaner for players.
In summary, this code simulates a trivia game with a focus on speed and accuracy, encouraging players to guess with minimal clues to maximize their score.
