# 信件


更新日期:2016/07/15

### 1.路徑:    ../character_mail/get_msg_info.php  　　　　 
   　　　　  　

### 2. 說明

輸入角色名稱判斷不是存在此暱稱
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id |  | string | 11   |   --  |



### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc |  | string | -- |
| gems |  | string | 寶石 |
| queue |  | string | 數量|

### 5. 錯誤代碼說明

| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 140 | string |  |
| err_desc | the character does not exist  | string | 沒有此ID |



### 6.回傳格式範例
```

  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'nickname_exist' => boolean true

```







