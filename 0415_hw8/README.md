## 0415_hw8 AI Agents：職涯成長導師 + 超會寫 LinkedIn 的貼文助理
**原始任務：** 輸入在職場上遇到的低潮，生成一段具啟發性的LinkIn貼文。

#### ✅ CoT 改寫版本流程：
1. **第一階段（思考階段）**：請 LLM 思考五種『為什麼這是一次成長契機』的理由
2. **第二階段（產文階段）**：從這五個理由中挑出最有啟發性的一個，寫成LinkIn貼文

### prompt設定
system_planner = "你是一位資深職涯教練，擅長幫助人們從職涯低潮中看到成長機會。
請針對使用者分享的挫折，思考五種『為什麼這是一次成長契機』的理由，列出條列式清單。
請用台灣習慣的中文回應，可以用第一人稱思考。"
system_writer = "你是一位專業的 LinkedIn 小編，擅長用積極、真誠、有啟發性的語氣撰寫職涯貼文。
請根據一個特別有啟發性的理由，寫出一段 LinkedIn 風格的第一人稱貼文。
開頭要有一點個人故事，中間加入一個反思點，結尾呼應成長，並用 #成長思維 #職涯路上 等 Hashtag。"

### Gradio展示
<img width="748" alt="0415_hw8_1" src="https://github.com/user-attachments/assets/4f0e983a-1253-4207-b14d-4fc45a277ed6" />
<img width="748" alt="0415_hw8_2" src="https://github.com/user-attachments/assets/ac177eb4-3977-4d52-8c29-1a8d6bf780c8" />
