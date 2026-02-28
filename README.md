# Codedex_2026_February_Dataset_Challenge_Efficiency_vs_Fantasy
This project analyzes how Dungeons &amp; Dragons classes scale from level 1 to 20 using real player data. By examining HP growth, stat progression, and a custom Power Index, it compares long-term efficiency with class popularity through a data-driven approach.

For this study, I used a dataset created by Joakim Arvidsson (2 years ago, Kaggle.com), coming from a mobile D&D game. All data belongs to them. 

The dataset includes 7,946 characters, each with race, class, and various stats. We focus on single-class characters, which account for 7,475 (94%) of all characters, to ensure a clean comparison of growth potential. I cleaned the dataset in Python (NumPy and Plotly), removed irrelevant columns, and excluded multi-class characters to focus purely on class-specific growth.

My python file: "dndcategories.ipynb", 2026.02.25.
My full analize work: "EfficiencyvsFantasy.pdf", 2026.02.27.

Source: Data: Joakim Arvidsson, updated 2 years ago, downloaded: 2026.02.25. 
https://www.kaggle.com/datasets/joebeachcapital/dungeons-and-dragons-characters > "dnd_chars_unique.tsv"
