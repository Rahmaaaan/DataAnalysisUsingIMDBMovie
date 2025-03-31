# IMDB Movie Data Analysis

[![Open in Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)]([DataAnalysisUsingIMDB.ipynb](https://github.com/Rahmaaaan/DataAnalysisUsingIMDBMovie/blob/main/Data%20analysis%20using%20IMDB%20Movie.ipynb))
[![HTML Version](https://img.shields.io/badge/HTML-Report-blue.svg)]([DataAnalysisUsingIMDB.html](https://github.com/Rahmaaaan/DataAnalysisUsingIMDBMovie/blob/main/DataAnalysisUsingIMDB.html))

A comprehensive data analysis project exploring relationships between movie budgets, popularity, runtime, genres, and profitability using the TMDB dataset. This study utilizes Python's data analysis stack to derive insights into film industry trends.

## Files Structure

```
.
├── .gitattributes
├── .gitignore
├── DataAnalysisUsingIMDB.ipynb    # Main Jupyter Notebook
├── DataAnalysisUsingIMDB.html     # Exported HTML Report
├── LICENSE
├── readme.md
└── tmdb-movies.csv                # Primary dataset
```

## Technologies Used

- Python 3.8+
- pandas (v1.2.4+)
- numpy (v1.19.5+)
- matplotlib (v3.3.4+)
- seaborn (v0.11.1+)
- Jupyter Notebook

## Problem Statements

1. **Budget and Popularity:** Is there a relationship between a film's budget and its popularity? Does a higher budget mean higher popularity?
2. **Runtime and Popularity:** How does the runtime of a movie influence audience engagement and popularity?
3. **Popularity and Profitability:** Does higher popularity correlate with higher profits?
4. **Characteristics of Top-Grossing Movies:** What features define the top 10 revenue-generating movies?
5. **Genre Trends Over Time:** Which genres dominate popularity trends over time?

## Installation

### Prerequisites
- Python 3.8+ installed
- pip package manager
- Git (for contribution)

### Quick Start

1. Clone repository:
```bash
git clone https://github.com/Rahmaaaan/DataAnalysisUsingIMDBMovie.git
cd DataAnalysisUsingIMDBMovie
```

2. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch analysis:
```bash
jupyter notebook DataAnalysisUsingIMDB.ipynb
```

## Contribution

### How to Contribute

We welcome contributions in these areas:
- 🧹 Data cleaning improvements
- 📈 New analytical approaches
- 📊 Visualization enhancements
- 📝 Documentation updates
- 🐛 Bug fixes

### Contribution Process

1. **Fork the repository**
   ```bash
   git clone https://github.com/Rahmaaaan/DataAnalysisUsingIMDBMovie.git
   ```

2. **Create feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Test changes**
   ```bash
    jupyter nbconvert --execute         DataAnalysisUsingIMDB.ipynb
   ```
   
4. **Commit changes**
   ```bash
   git add .
   git commit -m "feat: add correlation analysis for director impact"
   ```

5. **Push changes**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create Pull Request**
   - Use conventional commit messages
   - Reference related issues
   - Include visualizations if applicable

### Coding Standards
- Follow PEP8 guidelines
- Use descriptive variable names
- Include Markdown explanations in notebooks
- Keep visualizations accessible (colorblind-friendly palettes)
- Validate results with statistical tests

## License

This website is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, feel free to reach out to us at <therahman14@gmail.com>. We're excited to hear from you and make this project even better!