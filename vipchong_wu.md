# VIP_寵物


API編碼:2.10.6

更新日期:2016/07/05

發布版本:2.0.6
### 1.路徑:/event/Rank_power_show 　

### 2. 說明

輸入角色ID 可以拿到自己的資訊,剩下資訊是每日排行資料
### 3. 輸入參數說明


| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id  |   | string | -- | 角色ID |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |--|
| -- | -- | -- | -- | -- |
| err_code | 000 | string | -- |--|
| err_desc | souce | string |  --|--|
| character_nicknamer | -- | string |--|--|
| character_lv   |  | int | -- | 角色等級|
| character_model   |  | int | -- | 角色模組|
| character_duty   |  | int | -- | 角色duty|
| Rank_list   |  | int | -- | 排行名次|
| Rank_score   |  | int | -- | 排行分數|
| Alliance_name   |  | int | -- | 個人所屬聯盟名稱|

### 5. 錯誤代碼說明



### 6.回傳格式範例
```
```

