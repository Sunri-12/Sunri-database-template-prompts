# Sunri database template prompts
資料庫記憶總結插件_資料庫模板優化

基於Gemini模型的API串接與「資料庫·記憶總結插件」，針對数据库表格模版can貂改v5.7，進行結構化提示詞及長期記憶管理優化

核心技術
- Token優化: 將事件紀要由300–500字縮減至70–120字，單筆表格字數上限降低 76%
- 記憶管理: 調整摘要規則與重要對話紀錄條件，減少冗餘資訊
- 資料載入: 修改表格的關鍵字觸發配置，探索降低非必要上下文佔用模型注意力
- 結構化設計: 調整JSON資料表欄位、格式限制及資料更新規則

技術工具: Gemini API串接、AI長期記憶管理、提示工程、JSON、LLM上下文、Token優化

紀要表簡潔化:

<img width="1880" height="891" alt="Screenshot 2026-10-23 123322" src="https://github.com/user-attachments/assets/cb06a53c-ecd5-4e7c-935c-9b789e4a1693" />

資料庫AI提示詞設計:

<img width="1786" height="910" alt="image" src="https://github.com/user-attachments/assets/c5483dc9-1f3c-46d0-a27f-18f043512e88" />

