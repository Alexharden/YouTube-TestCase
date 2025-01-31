# YouTube-TestCase
1. 專案名稱： YouTube 測試
2. 測試類型： 功能測試、UI 測試
3. 測試平台： Windows
4. 瀏覽器： Chrome

# 測試計畫
著重於普通使用者會使用到的功能進行測試 <br> 
以Premium帳號為主測試，額外挑選出未登入及一般帳號有區別的功能，進行另外的單獨測試。

# Premium 帳號測試
## 一、 推薦內容測試
| 前置作業 | 測試項目 | 測試步驟 | 預期結果 | 實際結果 | 驗證狀態 |
| --- | --- | --- | --- | --- | --- |
| 登入只看NBA相關影片的帳號 | 個人化推薦 | 查看首頁推薦內容 | 推薦內容與用戶觀看歷史相關(例如:NBA)| 符合預期 | Pass |
| 接續前項測試 | 觀看影片後推薦變化 | 1. 觀看5部新聞相關類型影片 <br> 2. 回到首頁查看首頁推薦內容 | 推薦內容應該根據觀看歷史更新 | 符合預期 | Pass |

| 實際結果圖片 |
| --- |
| No1. ![image](https://github.com/user-attachments/assets/121bbf6e-c3e6-459b-8d14-b0c845124d6a) |
| No2. ![image](https://github.com/user-attachments/assets/e8cdc6e2-db7a-4b3c-b33d-ddfc32ebdc7f) |

## 二、 搜尋功能測試
| 前置作業 | 測試項目 | 測試步驟 | 預期結果 | 實際結果 | 驗證狀態 |
| --- | --- | --- | --- | --- | --- |
| 登入帳號 | 基本搜尋 | 在搜尋框輸入關鍵字並點擊搜尋 | 返回相關搜尋結果(例如:NBA)| 符合預期 | Pass |
| 登入帳號 | 輸入拼錯關鍵字處理 | 搜尋錯別字 (例如:trumo) | 仍能返回相關結果或建議修正(例如:trump)| 符合預期 | Pass |

| 實際結果圖片 |
| --- |
| No1. ![image](https://github.com/user-attachments/assets/0a5c707f-e163-4e10-9bb2-9da7215ff8be) |
| No2. ![image](https://github.com/user-attachments/assets/915e5490-261a-4ebb-ad87-d3f0926722be) |

## 三、 確認首頁 Premium 功能
| 前置作業 | 測試項目 | 測試步驟 | 預期結果 | 實際結果 | 驗證狀態 |
| --- | --- | --- | --- | --- | --- |
| 登入帳號 | Premium Logo| 查看左上角Logo  | 應該顯示為Premium | 符合預期 | Pass |
| 登入帳號 | 下載影片 | 1. 挑選任意影片 <br> 2.點擊 More operations按鈕 <br> 3.點擊下載 | 1. 出現正在下載提示 <br> 2. 出現在下載清單中| 符合預期 | Pass |
| 登入帳號 | 確認首頁廣告 | 在首頁中滾動尋找廣告 | 不應該出現任何廣告 | 符合預期 | Pass |

| 實際結果圖片 |
| --- |
| No1. ![image](https://github.com/user-attachments/assets/0d2cbce7-6e88-442a-874e-bec20decc1dd) |
| No2. ![image](https://github.com/user-attachments/assets/6a2814c1-89d6-4029-ba1c-eeeebdb53817) |
| No3. ![image](https://github.com/user-attachments/assets/6ab46d18-b9ab-4bbc-82a9-72f6e524f2c2) |

## 四、 觀看影片
| 前置作業 | 測試項目 | 測試步驟 | 預期結果 | 實際結果 | 驗證狀態 |
| --- | --- | --- | --- | --- | --- |
| 登入帳號 | 觀看影片內的廣告顯示 | 點擊任意一部影片  | 不應該出現任何廣告 | 符合預期 | Pass |
| 登入帳號 | 查看右側推薦影片區塊的廣告 | 點擊任意一部影片  | 在右側推薦影片最上方不應該顯示廣告 | 符合預期 | Pass |


| 實際結果圖片 |
| --- |
|No1. ![image](https://github.com/user-attachments/assets/3da839ea-62f3-48c2-a163-a4bbefd9a12d) |
|No2. ![image](https://github.com/user-attachments/assets/38c6580b-fbe5-4ff9-a978-2a7f3e2136cb) |


# 一般帳號/未登入帳號 測試
## 一、 推薦內容測試
| 前置作業 | 測試項目 | 測試步驟 | Expected Result | Actual Result | Verify Status |
| --- | --- | --- | --- | --- | --- |
| 開啟無痕頁面 | 未登入用戶的推薦 | 查看首頁推薦內容 | 1. 沒有推薦內容 <br> 2. 出現輸入搜尋字詞的提示訊息| 符合預期 | Pass |
| 接續前項測試 | 觀看影片後推薦變化 | 1. 搜尋任意關鍵詞並查看影片 <br> 2. 回到首頁查看首頁推薦內容 | 應出現推薦影片 | 符合預期 | Pass |

| 實際結果圖片 |
| --- |
| No1. ![image](https://github.com/user-attachments/assets/4e8ca7a0-3636-4aef-8dcd-56fd582832f8) |
| No2. ![image](https://github.com/user-attachments/assets/7f3333a5-7b41-4064-93fa-92bdad47b456) |

# 二、 確認首頁 非 Premium 功能
| 前置作業 | 測試項目 | 測試步驟 | Expected Result | Actual Result | Verify Status |
| --- | --- | --- | --- | --- | --- |
| 登入帳號/未登入 | YouTube Logo| 查看左上角Logo  | 應該顯示為YouTube | 符合預期 | Pass |
| 登入帳號 | 下載影片 | 1. 挑選任意影片 <br> 2.點擊 More operations按鈕 <br> 3.點擊下載 | 應出現需要訂閱的提示訊息| 符合預期 | Pass |
| 登入帳號/未登入 | 確認首頁廣告 | 在首頁中滾動尋找廣告 | 第一則影片的位置應該要出現廣告 | 符合預期 | Pass |



| 實際結果圖片 |
| --- |
| No1. ![image](https://github.com/user-attachments/assets/42f6b261-7e9b-40e1-a25b-cf879dc4d908) |
| No2. ![image](https://github.com/user-attachments/assets/aff6142a-2494-4940-aa1f-023907df0867) |
| No3. ![image](https://github.com/user-attachments/assets/33e9358f-4f19-493d-9894-0a8d67eb9ea6) |



## 四、 觀看影片
| 前置作業 | 測試項目 | 測試步驟 | 預期結果 | 實際結果 | 驗證狀態 |
| --- | --- | --- | --- | --- | --- |
| 登入帳號/未登入 | 觀看影片內的廣告顯示 | 點擊任意一部影片  | 應該在影片開頭顯示廣告或影片播放到中途出現廣告 | 符合預期 | Pass |
| 登入帳號/未登入 | 查看右側推薦影片區塊的廣告 | 點擊任意一部影片  | 應該在右側推薦影片最上方顯示廣告 | 符合預期 | Pass |

| 實際結果圖片 |
| --- |
|No1. ![image](https://github.com/user-attachments/assets/2b0bfc79-503f-46f3-a01d-13760b504520) |
|No2. ![image](https://github.com/user-attachments/assets/a1e23c2f-d054-436b-917e-7ee3631db16a) |




