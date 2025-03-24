# 0311_hw4
建立自己的benchmarks
### 請解釋雙目視差計算的基本原理，並提供 Python 實作範例。
#### 1. ChatGPT-4o的回答與範例程式結果
![reply from ChatGPT](https://github.com/user-attachments/assets/2f69d285-81e2-4ef0-9c71-6e59d6f6e381)  
![result form ChatGPT](https://github.com/user-attachments/assets/c223d8ff-b47f-45c0-b9d9-a06ccb6cf0e3)  
 
#### 2. Google Gimini 2.0的回答與範例程式結果
![reply from Gimini](https://github.com/user-attachments/assets/19adc099-2d56-4165-9193-053630e9a40f)
![result form Gimini](https://github.com/user-attachments/assets/26f67c8b-b3d4-4bb2-ad6c-ef5803292371)

#### 生成結果比較
1. ChatGPT敘述雙目視差匹配流程與常用評估方法，但Gimini主要在解釋雙目視差的概念。可能因為我常常詢問ChatGPT相關的問題，ChatGPT預設使用者具備一定知識進行說明;Gimini預設使用者完全不理解何謂雙目視差，因此選擇更口語的說明方式。

2. 兩個LLM都選用cv2.StereoBM_create這個工具進行視差匹配，但ChatGPT的參數設定(numDisparities=64, blockSize=14)相較Gimini的設定(numDisparities=16, blockSize=15)在視覺上更精準。

