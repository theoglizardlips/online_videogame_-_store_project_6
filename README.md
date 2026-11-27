# Online Videogame Store "ICE": Sales and Ratings EDA — Marketing Shortlist for 2017
Exploratory data analysis of historical video game sales, platform lifecycles, critic vs. user ratings, and ESRB classifications through 2016 to identify the best titles for 2017 marketing campaigns.

## Project Overview
The goal of this project is to analyze, contextualize, and discern possible patterns that identify what drives video game commercial success. Doing so allows us to distill an actionable shortlist of titles for 2017 marketing campaigns through the following steps:
- **Platform Lifecycles:** Identifying which gaming platforms are declining or actively growing heading into 2017.
- **Ratings and Commercial Impact:** Comparing how user scores and critic scores affect global sales, as well as the role of ESRB age ratings.
- **Statistical Hypothesis Testing:** Testing if average user ratings differ significantly across key platforms (e.g., PC vs. Xbox One) and genres (e.g., Sports vs. Action).

## Key Takeaways
- **Work in Progress:** Originally written in Portuguese, this project was initially translated via an offline NMT engine. I am currently refining the text to ensure natural localization, accurate terminology, and clearer, more cohesive reasoning.
- The **ESBR rating** matters a lot more for market range and reach than initially expected. Not that I ever believed an age rating would stop all parents from buying specific games for their kids, but it does stop some.
- We discuss how different age ratings set different **marketing trends** and what the **20-year effect** can do to a customer.

*This section will be updated once the translation has been completed.*

## Libraries
- **Language:** Python 3.9+
- **Data Manipulation and Analysis:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Statistical Testing:** `scipy.stats`
- **Environment:** Jupyter Notebook

## Repository Structure
```
text
├── notebook/
│   ├── English/
│   │   └── Project 5_en.ipynb
│   └── Portuguese/
│       └── Project 5.ipynb
├── .gitattributes
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

## License & Data Attribution
- **Code & Analysis:** Licensed under the MIT License.
- **Dataset:** The underlying historical video game dataset was provided as part of the TripleTen Data Analysis program and is omitted from this repository to respect course material boundaries.
