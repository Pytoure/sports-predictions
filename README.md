# sports-predictions
This project predicts football match results using a weighted scoring algorithm in C. It evaluates recent form, head-to-head history, league standings, home/away performance, and halftime scores to reduce betting risks and enhance bettors’ statistical analysis.
📂 Project Structure
bash
Copy
Edit
📁 FootballPrediction
 ├── prediction.c   # Main source code
 └── README.md      # Project documentation
💻 Requirements
C compiler (e.g., GCC)

Basic terminal/command prompt knowledge

🚀 How to Run
Compile the program

bash
Copy
Edit
gcc prediction.c -o prediction
Run the program

bash
Copy
Edit
./prediction
Follow the prompts to enter team names, recent results, league position, etc.

📝 Example Output
markdown
Copy
Edit
+=+ CHAMPIONNATS +=+
1. Premier League
2. La Liga
3. Bundesliga
4. Serie A
5. Ligue 1
Faites votre choix : 1
Premier League, bon choix !
Veuillez entrer l'équipe à domicile : Arsenal
Veuillez entrer l'équipe extérieure : Chelsea
...

=== SCORE FINAL ===
Arsenal : 58 points
Chelsea : 42 points
💡 Position : Victoire probable de Arsenal
📌 Future Improvements
Add more leagues and teams

Automate data collection from online football statistics

Integrate machine learning for more accurate predictions

Create a graphical user interface (GUI)


