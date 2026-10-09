# ⚡ Automated EDA: Four Tools Compared

Manual EDA takes hours. These notebooks compare four libraries that generate an exploratory report in a few lines of code, tested on Seaborn's **Titanic** and **Tips** datasets.

| Notebook | Library | Output |
|---|---|---|
| `Automated EDA using pandas profiling.ipynb` | **ydata-profiling** | Full HTML report: distributions, correlations, missing values, warnings |
| `Automated EDA using SweetViz.ipynb` | **Sweetviz** | Visual report (`SWEETVIZ_REPORT.html`), strong for comparing two datasets or a target |
| `Automated EDA Using Autoviz.ipynb` | **AutoViz** | Automatically picks and draws the most relevant charts |
| `Automated EDA using Dtale.ipynb` | **D-Tale** | Interactive, spreadsheet-like browser UI for exploring a DataFrame |

## 💡 When I'd use which
- **Quick health check** of a new dataset → ydata-profiling
- **Train vs test comparison** → Sweetviz
- **Hands-on exploration** → D-Tale

These tools speed up the first look, but they don't replace thinking about the data. I still verify key findings manually.

## 🚀 Run it
```bash
pip install ydata-profiling sweetviz autoviz dtale seaborn jupyter
jupyter notebook
```
Open the saved reports (`SWEETVIZ_REPORT.html`, `output.html`) in a browser to see example output.

---
👩‍💻 **Nidhi Mehta** · [GitHub](https://github.com/itsnidhimehta)
