# 每日禮包內容清單


更新日期:2016/06/08

發布版本:2.0.6
### 1.路徑: ../event/Daily_Tasks_show_get.php 　

### 2. 說明

輸入角色跟ID跟禮包順序可以查詢禮包內容 ,但是前期是積分要夠
### 3. 輸入參數說明


| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id  | character_id  | int | -- | 角色ID |
| Receive_gifts_id   | 範例:10001 | int | -- | 禮包ID|

### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| exp |  | string | 領取 |
| err_code | 430 | string | 已領取 |
| err_code|431|string|未領取|



### 5. 錯誤代碼說明

### 6.回傳格式範例

{"err_code":"430","err_desc":"\u5df2\u9818\u53d6","show_Receive_gifts_id":null}

