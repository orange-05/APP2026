# 📓 APP2026 — Data Cleaning with Pandas

> A focused Jupyter notebook that demonstrates **identifying and dropping missing values** in a real-world-style dataset (`selling.csv`), with a complete, well-commented walkthrough.

![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter)
![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Cleaning-150458?style=for-the-badge&logo=pandas)

---

## 📂 What's in this repo

| File | Purpose |
|---|---|
| `Identify and Dropping Missing Values.ipynb` | The full assignment — 7 sections covering null detection, dropping strategies, and verification |
| `selling.csv` | The dataset used in the notebook (real-estate / classifieds-style rows with mixed nulls) |
| `choose.txt` | A reference list of open-source desktop apps (Firefox, LibreOffice, VS Code, …) used as class material |

---

## 🧭 What the notebook covers

1. **Load** `selling.csv` with pandas
2. **Inspect** — shape, dtypes, head, info
3. **Quantify** missing values per column
4. **Visualize** missingness patterns
5. **Drop strategies** — rows vs columns, threshold-based
6. **Verify** — confirm no nulls remain
7. **Reflect** — when to drop, when to fill

The notebook is heavily commented so it doubles as a learning artifact, not just a one-off answer.

---

## 🚀 How to run

### Option A — Jupyter

```bash
git clone https://github.com/orange-05/APP2026.git
cd APP2026
pip install jupyter pandas
jupyter notebook "Identify and Dropping Missing Values.ipynb"
```

### Option B — VS Code

Open the `.ipynb` file in VS Code with the **Jupyter** extension installed and run cells inline.

### Option C — Google Colab

1. Upload the notebook to [colab.research.google.com](https://colab.research.google.com)
2. Also upload `selling.csv` to the Colab session
3. Run all cells

---

## 📦 Requirements

```text
pandas
jupyter
```

(NumPy is pulled in automatically with pandas; `seaborn` / `matplotlib` are optional for the visualization cells.)

---

## 📄 License

Released for educational use. See the notebook's header for the original assignment attribution.
