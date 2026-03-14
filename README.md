# Examine-the-History-of-Lego-Sets

📌 Project Overview

LEGO is one of the most recognizable toy brands in the world, known for its innovative building sets, movies, video games, and collaborations with popular franchises. One of the most significant developments in LEGO’s history was the introduction of licensed themes, beginning with Star Wars.

This project explores the impact of licensed LEGO sets by analyzing historical LEGO set data. Using Python and data analysis techniques, we investigate how licensed themes—particularly Star Wars—have contributed to LEGO’s product success.

⸻

📊 Objectives

The goal of this project is to analyze LEGO datasets and answer the following key questions:
	1.	What percentage of all licensed LEGO sets released were Star Wars themed?
The result is stored in a variable called:

the_force

	2.	In which year was the highest number of Star Wars LEGO sets released?
The result is stored in a variable called:

new_era


⸻

📂 Dataset

Two datasets are used in this project.

1️⃣ lego_sets.csv

Contains information about individual LEGO sets.

Column	Description
set_num	Unique identifier for each LEGO set
name	Name of the LEGO set
year	Year the set was released
num_parts	Number of pieces in the set
theme_name	Sub-theme name
parent_theme	Parent theme the set belongs to

⚠️ set_num is critical for identifying valid sets.

⸻

2️⃣ parent_themes.csv

Contains information about LEGO parent themes.

Column	Description
id	Unique identifier for each theme
name	Parent theme name
is_licensed	Boolean indicating whether the theme is licensed


⸻

🔎 Analysis Process

The project follows these main steps:
	1.	Data Cleaning
	•	Removed rows with missing set_num values.
	2.	Data Merging
	•	Joined the LEGO sets dataset with the parent themes dataset to identify licensed themes.
	3.	Filtering Licensed Sets
	•	Extracted only licensed themes to analyze collaborations.
	4.	Star Wars Analysis
	•	Calculated the percentage of licensed sets that belong to the Star Wars theme.
	•	Identified the year with the most Star Wars LEGO sets released.

⸻

📈 Key Results
	•	Percentage of licensed sets that are Star Wars:
the_force = 51
	•	Year with the most Star Wars sets released:
new_era = 2017

These results highlight the major influence of the Star Wars partnership, which has played a significant role in LEGO’s product strategy since its introduction.

⸻

📚 Data Source

The datasets used in this project are provided by the Rebrickable LEGO Database, which contains comprehensive historical LEGO set data.

⸻

📜 License

This project is for educational and data analysis purposes.

If you can't view the code click here:
https://nbviewer.org/github/Vincenzocariel/Examine-the-History-of-Lego-Sets/blob/main/notebook.ipynb
