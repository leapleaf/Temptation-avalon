# 戰力排行

API編碼:2.10.2

更新日期:2016/06/08

發布版本:2.0.6
### 1.路徑:/event/Daily_Touch_renter.php 　

### 2. 說明

輸入角色跟ID跟禮包順序可以領取禮包
### 3. 輸入參數說明


| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id  | character_id  | int | -- | 角色ID |
| Receive_gifts_id   | 範例:10001 | int | -- | 禮包ID|

### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 429 | string | 領取 |
| err_code | 430 | string | 已領取 |
|err_code|431|string|積分不夠,不能領取|

### 5. 錯誤代碼說明



### 6.回傳格式範例
```
array (size=3)
  'err_code' => string '429' (length=3)
  'err_desc' => string '領取' (length=6)
  'show_Receive_gifts_id' => null
{"err_code":"430","err_desc":"\u5df2\u9818\u53d6","show_Receive_gifts_id":null}
```
