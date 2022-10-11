**作業:** 工作分解結構清單列出了 11 項任務，每項任務都有編號、說明、需時，以及前置任務。
其中，某些依存任務可以擁有一個或多個前置任務。

請以 **(1)PERT/CPM圖** 和 **(2)甘特圖** 以及 **(3)關鍵路徑** 來表示這些任務。<br>
你必須進行兩個步驟：
1. 顯示任務及任務模式。
2. 輸入開始及結束時間。

---

| 任務 | 說明         | 需時(天) | 前置任務 |
| ---- | ------------ | -------- | -------- |
| 1    | 研擬計畫     | 1        | -        |
| 2    | 任務分配     | 4        | 1        |
| 3    | 取得硬體     | 17       | 1        |
| 4    | 程式開發     | 70       | 2        |
| 5    | 安裝軟體     | 10       | 3        |
| 6    | 程式測試     | 30       | 4        |
| 7    | 撰寫使用手冊 | 25       | 5        |
| 8    | 轉換檔案     | 20       | 5        |
| 9    | 系統測試     | 25       | 6        |
| 10   | 使用者訓練   | 20       | 7,8      |
| 11   | 使用者測試   | 25       | 9,10     |

---
**PERT**

![![來源]([https://hackmd.io/D5ZuKSUIQIOSJreZ-K5Mew](https://hackmd.io/@elvMnT8FRe-QPcC1RlqxgA/Chein623
))](https://user-images.githubusercontent.com/79584249/195106994-76619a09-ae12-4c1a-86bd-561263ee5dc0.jpg)

---
**甘特圖**
```mermaid
gantt
    title 甘特圖
    
    section 研擬計畫
    1       :a1, 2022-10-01, 1d
   
    section 任務分配
    4       :a2, after a1  , 4d
    
    section 取得硬體
    17      :a3, after a1 , 17d
    
    section 程式開發
    70      :a4, after a2  , 70d
    
    section 安裝硬體
    10      :a5, after a3  , 10d
    
    section 程式測試
    30      :a6, after a4  , 30d
    
    section 撰寫使用手冊
    25      :a7, after a5  , 25d
    
    section 轉換檔案
    20      :a8, after a5  , 20d
    
    section 系統測試
    25      :a9, after a6  , 25d
    
    section 使用者訓練
    20      :a10, after a7  , 20d
    
    section 使用者測試
    25      :a11, after a9  , 25d
```
---
**關鍵路徑**  
![![來源]([https://hackmd.io/D5ZuKSUIQIOSJreZ-K5Mew](https://hackmd.io/@elvMnT8FRe-QPcC1RlqxgA/Chein623
))](https://user-images.githubusercontent.com/79584249/195108356-618f1d73-0b5a-4e6b-b376-9dd517102e16.jpg)
