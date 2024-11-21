# Prompt Engineer 作業題目

## 作業內容

請使用 **LangChain** 套件完成以下作業，並實作提供的方法 `generate_node(question)`。

---

### 作業1

1. 問題：`2024年台灣10月紀念日有哪些?`
2. 方法：實作 `generate_node(question)`，用於回答上述問題。
3. 輸出格式需為 JSON，範例如下：
    ```json
    {
        "Result": [
            {
                "日期": "2024-10-10",
                "名稱": "國慶日"
            }
        ]
    }
    ```

---

### 作業2

1. 問題：`2024年台灣10月紀念日有哪些?`
2. 方法：使用 Function Calling 查詢指定的API，實作 `generate_node(question)`，用於回答上述問題。
3. 輸出格式需為 JSON，


### 注意事項
- 必須使用 **LangChain** 套件完成方法實作。
- 確保輸出的格式與範例一致。
