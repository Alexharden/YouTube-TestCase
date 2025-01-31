# YouTube-TestCase
1. 專案名稱： YouTube 測試
2. 測試類型： 功能測試、UI 測試
3. 測試平台： Windows
4. 瀏覽器： Chrome

# Premium 帳號測試
## 一、 推薦內容測試
| 前置作業 | 測試項目 | 測試步驟 | Expected Result | Actual Result | Verify Status |
| --- | --- | --- | --- | --- | --- |
| 登入只看NBA相關影片的帳號 | 個人化推薦 | 查看首頁推薦內容 | 推薦內容與用戶觀看歷史相關(例如:NBA)| 符合預期 | Pass |
| 接續前項測試 | 觀看影片後推薦變化 | 1. 觀看5部新聞相關類型影片 <br> 2. 回到首頁查看首頁推薦內容 | 推薦內容應該根據觀看歷史更新 | 符合預期 | Pass |

| 實際結果圖片 |
| --- |
| No1. ![image](https://github.com/user-attachments/assets/121bbf6e-c3e6-459b-8d14-b0c845124d6a) |
| No2. ![image](https://github.com/user-attachments/assets/e8cdc6e2-db7a-4b3c-b33d-ddfc32ebdc7f) |



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


