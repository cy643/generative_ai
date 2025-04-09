## 0408_hw7 實作RAG系統。
蒐集arxiv上與自動駕駛相關的一百筆文獻標題與摘要做自動駕駛問答RAG系統

### 收集資料集並轉換成向量(chatGPT生成蒐集腳本)
<img width="335" alt="0408_hw7_dataset" src="https://github.com/user-attachments/assets/a14d7bd6-7a02-4def-9990-349bf210b4c7" />  

### 從google drive下載向量資料集
https://drive.google.com/uc?export=download&id=1e23zrST2JmdavrUXPSHdWJVw1m3j8kw_

### prompt設定
system_prompt = "你是一個自動駕駛知識問答系統，請根據學生的提問來回答。請簡潔、清楚並且準確地回答，並且使用自然流暢的語言回應。"  
prompt_template = """  
學生問題：{question}  
回覆內容：{retrieved_chunks}  
請根據自動駕駛文獻資料庫內容來回答學生的問題。確保回答簡潔且準確，並使用自然語言表達。  
"""  

### Gradio展示
<img width="635" alt="0408_hw7_1" src="https://github.com/user-attachments/assets/3298bc28-40f5-43bd-9367-3cb92bdf96eb" />  
<img width="640" alt="0408_hw7_2" src="https://github.com/user-attachments/assets/46f4b0de-da6f-45c6-80f4-2344efab5b01" />  
