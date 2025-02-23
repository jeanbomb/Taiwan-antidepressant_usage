# 抗憂鬱藥物使用資料分析與自動化 / Antidepressant Usage Data Analysis and Automation

這個專案從台灣健保資料庫的 API 下載並處理抗憂鬱藥物使用數據。它會進行數據清理、統計分析，並定期自動更新結果。所有分析結果會儲存為 Excel 和 CSV 文件。

This project downloads and processes antidepressant usage data from the Taiwan National Health Insurance (NHI) API. It performs data cleaning, statistical analysis, and automatically updates the results periodically. All analysis results are saved as Excel and CSV files.

## 使用技術 / Technologies Used

- **Python**: 用於開發整體專案。 / Python was used for overall project development.
- **pandas**: 用於數據處理和分析。 / pandas was used for data manipulation and analysis.
- **requests**: 用於從 API 下載數據。 / requests was used to fetch data from the API.
- **schedule**: 用於設置定期任務，實現自動更新。 / schedule was used to set up periodic tasks for automatic updates.

## 主要功能 / Main Features

- 從 API 或 CSV 讀取數據。 / Fetch data from API or read from CSV.
- 計算年齡、性別和地區的統計數據。 / Calculate statistics by age, gender, and region.
- 自動化定期更新數據。 / Automate periodic data updates.
- 儲存統計數據為 Excel 和 CSV 文件。 / Save the statistical data as Excel and CSV files.

