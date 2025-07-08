# ⚽ EverythingBundesliga

> When Bayern gets knocked out of the Club World Cup and Musiala gets injured, there's only one thing to do:  
> open a Jupyter notebook and let the healing begin. 💻📉⚽

**EverythingBundesliga** is a machine learning and data analysis playground focused on the beautiful game.  
This repo is where tactics meet tech – from building expected goals (xG) models to breaking down Bundesliga table drama like a football-obsessed data scientist.

---

## 📁 What's in the Squad?

| Folder | Role |
|--------|------|
| `data/` | All the raw and cleaned data – from Bundesliga stats to open shot data |
| `notebooks/` | Tactical command center – contains all experiments and visual explorations |
| `visuals/` | Shot maps, heatmaps, and more football-themed data art |

---

## 🔍 Core Projects

### 📈 Expected Goals (xG) Model  
*Based on open shot-level data (not Bundesliga-specific)*  
- Inspired by the McKay Johns tutorial and expanded with custom ideas
- Predicts the probability of a shot resulting in a goal using logistic regression
- Key features: shot distance, angle, location
- Visuals: shot maps + xG overlays for different positions

🧠 Notebook: `notebooks/xg_model_experiment.ipynb`

---

### 🇩🇪 Bundesliga 2024/25 Final Table Analysis  
*Team-level analysis based on final standings and performance metrics*  
- Broke down final league table: points, GD, form, and streaks
- Evaluated home vs away form and late-season momentum
- Identified overachievers and underperformers
- Includes visualizations for league progression and team stats

📊 Notebook: `notebooks/bundesliga_2025_table_analysis.ipynb`

---

## 🛠️ Tools of the Trade

- 🐍 Python 3.x  
- 📊 `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`  
- 🤖 `scikit-learn`, `xgboost`  
- 🌐 `BeautifulSoup`, `requests` for scraping  
- 🧠 Jupyter Notebooks (aka the tactical whiteboard)

---

## 🚧 Next Steps (aka What’s Cooking)

### 🧠 Build a Custom xG Model (for real this time)
- Move beyond the tutorial and create a personalized xG pipeline
- Engineer deeper features:
  - Shot angle (cosine math coming in clutch)
  - Goalkeeper distance
  - Assist type (key pass? cross? through ball?)
  - Body part used
- Try different models: Logistic Regression, Random Forest, XGBoost
- Evaluate with ROC curves, calibration, and Brier score

---

### 🧬 Discover Different Types of Players
- Cluster players by playstyle (attacker types, defenders, creators)
- Use PCA + KMeans to find player archetypes
- Label clusters like:
  - The Poacher  
  - The Playmaker  
  - The Pressing Demon  
  - The Chaos Merchant™
- Result = data-driven scouting reports

---

### 🎯 Create a Goal Map
- Visualize where all goals were scored on the pitch
- Filter by:
  - Player
  - Team
  - Match period (early game, late drama, etc.)
- Use heatmaps, scatter plots, and maybe animations (if we’re feeling spicy)
- Optional: compare goal zones vs shot zones

---

## 🙌 Contributions & Collabs

Have a cool dataset? A spicier way to calculate xG? Just wanna rant about why Bayern München struggle in big games?

Pull requests are welcome! Fork it, clone it, or start an Issue to suggest improvements, analysis ideas, or visuals.

> _Football never stops. And neither does this repo._

---

