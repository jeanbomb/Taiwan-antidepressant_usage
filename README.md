# 健保資料庫統計分析專案

## 專案簡介
此專案旨在示範如何利用Python進行健保資料庫的數據撈取、整理、統計分析及結果表格製作。專案內容包括資料擷取、資料處理、統計分析和報表生成，並展示如何自動化這些流程。

## 專案結構
```
diabetes_analysis_project/
├── config/
│   ├── __init__.py
│   ├── api_config.py          # API配置
│   └── report_config.py       # 報表配置
├── src/
│   ├── __init__.py
│   ├── api_handler.py         # API請求處理
│   ├── data_sync.py           # 資料同步
│   ├── data_processing.py     # 資料處理
│   ├── data_analysis.py       # 統計分析
│   └── report_updater.py      # 報表更新
├── output/
│   ├── raw_data/              # 原始資料
│   ├── processed_data/        # 處理後資料
│   └── reports/               # 分析報告
├── logs/                      # 記錄檔
├── main.py                    # 主程式
└── requirements.txt           # 套件需求
```

## 使用方法

### 1. 安裝必要套件
請確保您已經安裝了必要的Python套件，您可以通過以下命令來安裝：
```bash
pip install -r requirements.txt
```

### 2. 配置API金鑰和參數
請在 `config/api_config.py` 中配置您的API金鑰和相關參數。

### 3. 執行主程式
您可以通過以下命令來執行主程式：
```bash
python main.py
```

## 主要功能
1. 自動化資料擷取：從健保資料庫定期撈取資料。
2. 資料處理：處理和清洗原始資料。
3. 統計分析：分析病患特徵和就醫行為。
4. 報表生成：生成詳細的分析報告和視覺化圖表。

## 注意事項
1. 確保您有適當的資料庫存取權限。
2. 定期檢查記錄檔以確保系統正常運行。
3. 備份重要資料以防止資料丟失。
4. 遵守資料保密規範，保護患者隱私。
