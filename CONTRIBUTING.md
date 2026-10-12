# 🤝 Contributing to the Macau Chess Open Games Archive

First off, thank you for helping preserve Macau's chess history! As a player-maintained project, this archive relies on the local community to stay accurate, complete, and reliable. 

Whether you are a participant wanting to submit your own games, or a volunteer helping correct notation typos, here is how you can contribute.

---

## 📸 1. Submitting Game Photos or Scoresheets
If you are currently playing in the tournament and want to ensure your games are archived safely:
1. Take a clear, high-resolution photo of your physical scoresheet right after your round ends.
2. Ensure both players' names, the board number, the round number, and the final result are clearly visible.
3. Send the photos directly to the repository maintainer (**wintercat-126**) or upload them via a GitHub Issue.

---

## ⌨️ 2. Submitting Game PGN Data
If you have already typed out your game moves into a chess engine (like Lichess or chess.com), you can submit the raw PGN data.

### Standard PGN Header Format
Please ensure your PGN submissions include these standard tournament headers:
```pgn
[Event "Macau Open 2026"]
[Site "Cotai Bowling Centre, Macau"]
[Date "2026.??.??"]
[Round "X"]
[White "Name"]
[Black "Name"]
[Result "1-0"]
[Termination "Black Won by checkmate"]
[TimeControl "5400+30"]
[Board "18"]
```

### How to add your PGN to the Archive:
* **Option A:** Open a **New Issue** on this repository, label it "Game Submission: Round X", and paste your raw PGN text directly into the description box.
* **Option B:** Fork this repository, navigate to the specific round file (e.g., `Games and Information/Round 1/R1.pgn`), paste your game data at the bottom of the file, and submit a **Pull Request**.

---

## 📝 3. Reporting Notation Errors or Missing Games
If you review an archived game and notice a typo in a player's name, an incorrect tournament result, or a broken move sequence:
1. Go to the **Issues** tab at the top of this repository page.
2. Click **New Issue**.
3. Describe the problem clearly (e.g., *"Round 3, Board 5: White's 24th move should be Bxe4 instead of Bxe5"*).

---

## ⚖️ Community Code of Conduct
* **Accuracy First:** Please double-check move inputs against official scoresheets before submitting.
* **Respectful Collaboration:** We are all local chess players working together to build something great for ourselves. Keep all discussions in Issues and Pull Requests friendly and constructive.
