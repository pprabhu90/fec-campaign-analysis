
# 2016 California Presidential Primary Campaign Contributions

This project explores political donation trends from California during the 2016 U.S. presidential primaries using real Federal Election Commission (FEC) data. It was completed as part of Week 12–13 of the **UC Berkeley MIDS DATASCI 200: Introduction to Data Science Programming** course.

## 📊 Objectives
- Analyze real-world campaign finance data using `pandas`
- Visualize donation distributions with `matplotlib`
- Investigate patterns in candidate support and donor occupations

## 🔍 Dataset
The dataset used (`2016_ca_primary_cleaned.csv`) contains cleaned FEC data on campaign contributions from California during the 2016 presidential primary season. It is **not included** in the repo to avoid uploading large data files. You can download it [here](https://drive.google.com/file/d/1ftdw7L9Z6WQJ6i0SXj030PA7ObsXfPsg/view?usp=sharing) and place it in a local directory outside the repository.

## 🧮 Analysis Topics
- Histograms of contribution amounts (full range & zoomed-in)
- Daily fundraising time series for Hillary Clinton and Bernie Sanders
- Total vs. average donations by candidate
- Donor occupation analysis for each candidate

## 📁 Files
- `fec_campaign_analysis.py` — Main analysis script
- `README.md` — Project overview and instructions

## ▶️ How to Run
1. Download the CSV file from the link above.
2. Save it outside your repo, for example:
   ```
   /Users/<your-username>/Downloads/2016_ca_primary_cleaned.csv
   ```
3. Update the file path in `fec_campaign_analysis.py` if needed.
4. Run the script:
   ```bash
   python fec_campaign_analysis.py
   ```

## ✍️ Author
Praj Prabhu – [GitHub Profile](https://github.com/pprabhu90)
