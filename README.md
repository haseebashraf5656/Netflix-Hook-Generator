# 🍿 Netflix Hook Generator

An interactive Netflix-style tool that turns any movie or TV show name — even with typos or alternate titles like **"Money Heist"** — into an exciting, binge-worthy hook that makes you want to hit play immediately!

Built with Python, pandas, and ipywidgets in Google Colab. No machine learning training needed — just smart lookup, fuzzy matching, and fun rephrasing using real Netflix data.

## 🚀 Features

- **Fuzzy Search**: Handles typos (e.g., "Squd Game" → "Squid Game")
- **Alternate Titles Support**: "Money Heist" automatically maps to "La Casa de Papel"
- **Engaging Hooks**: Original Netflix description transformed into an addictive one-liner with genre-based flair
- **Rich Details**: Shows movie/TV show type, release year, rating, and genres
- **Beautiful Netflix-Themed UI**: Red button, dark mode card — feels like the real Netflix app!
- **Fast & Lightweight**: Runs instantly in Colab, no GPU or external APIs needed

## 📸 Screenshot
<img width="1599" height="224" alt="image" src="https://github.com/user-attachments/assets/a512ea38-c759-4dd4-8e6d-beee30c000d4" />


## 🛠️ How to Run

1. Click the **"Open in Colab"** badge above
2. Run all cells (Runtime → Run all)
3. Type any movie or show name in the search box
4. Click **"Get Hook!"** and enjoy your personalized binge pitch!

### Example Inputs & Outputs

**Input**: `Money Heist`  
**Output**:  
> Get hooked on 'La Casa de Papel': Eight thieves take hostages and lock themselves in the Royal Mint of Spain as a criminal mastermind manipulates the police to carry out his plan! An emotional rollercoaster you won't forget.

**Input**: `Squd Game` (typo)  
**Output**: Closest match found → Full exciting hook for *Squid Game*

## 📊 Dataset

Uses a cleaned version of the famous Netflix titles dataset (~8,800 movies and TV shows) with columns:
- title
- type (Movie/TV Show)
- description
- release_year
- rating
- listed_in (genres)
- and more

Duplicates handled, titles lowercased for fast lookup.

## 🧑‍💻 Tech Stack

- **Python**
- **pandas** – Data loading and lookup
- **difflib** – Fuzzy matching for typos
- **ipywidgets** – Interactive GUI in Jupyter/Colab
- **Pure Python logic** – Aliases, hook generation, styling

No external APIs | No training | Fully offline

## 🌟 Why This Project Rocks

Perfect for:
- Learning data handling with pandas
- Building interactive apps in notebooks
- Practicing clean, modular code
- Portfolio showcase (data + UI + real-world utility)

## 🤝 Contributing

Feel free to:
- Add more aliases (e.g., regional titles)
- Improve hook phrases
- Add similar movie suggestions
- Enhance the UI

Just fork, make changes, and open a PR!

## 📝 License

MIT License — free to use, modify, and share.

---

Made with ❤️ by [Your Name]  
Inspired by endless Netflix scrolling sessions.
