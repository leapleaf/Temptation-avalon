# 戰力排行

API編碼:2.10.5

更新日期:2016/06/22

發布版本:2.0.6
### 1.路徑:/event/Rank_power_show 　

### 2. 說明

輸入角色ID 可以拿到自己的資訊,剩下資訊是每日排行資料
### 3. 輸入參數說明


| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id  |   | string | -- | 角色ID |
| character_lv   |  | int | -- | 角色等級|
| character_model   |  | int | -- | 角色模組|
| character_duty   |  | int | -- | 角色duty|
| Rank_list   |  | int | -- | 等級|
| Rank_score   |  | int | -- | 等級|
| Alliance_name   |  | int | -- | 等級|

### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc | souce | string |  --|


### 5. 錯誤代碼說明



### 6.回傳格式範例
```
array (size=3)
  'err_code' => string '429' (length=3)
  'err_desc' => string '領取' (length=6)
  'show_Receive_gifts_id' => null
{"err_code":"430","err_desc":"\u5df2\u9818\u53d6","show_Receive_gifts_id":null}
```
