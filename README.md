# flask_20230506
20230506開始，產業人才投資計畫，python大數據資料探勘實務班

[老師github主頁](https://github.com/roberthsu2003/)

[老師本案課程github](https://github.com/roberthsu2003/__112_python_flask__)

[上課時連結](https://meet.google.com/ghs-xzys-oaj)

# github 常用指令
1. 強制上傳：git push -f

# 使用的延伸模組跟套件
[套件]
1. requests
2. pandas
3. openpyxl -> 存成.xls和.csv檔案 (to_excel/to_csv)
4. streamlit -> 互動式網頁展現表格/資料 (streamlit run 檔案名.py)

[延伸模組]
1. Excel Viewer -> 可預覽excel表格資料

# desktop需安裝
1. python
2. github desktop
3. vscode

# 指令
1. 互動式網頁指令(於CMD/vscode terminal使用)：streamlit run 檔案名.py
2. 程式環境
   (1) 儲存目前幻境的套件版本(於vscode terminal使用)：pip freeze > requirements.txt
   (2) 取消註解 devcontainer.json 中的 postCreateCommand，以便之後在新環境開啟本codespace，就會自動安裝套件
