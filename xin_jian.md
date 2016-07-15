# 信件


更新日期:2016/07/15

### 1.路徑:    ../character_mail/get_msg_info.php  　　　　 
   　　　　  　

### 2. 說明

輸入角色ID跟type判斷信件未讀取數量 ,type為信件分類 請參考 character_mail table
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id |  | string | 11   |   --  |
| type |  | int | 11   |   --  |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc |  | string | -- |
| unread_amount |  | int | 信件未讀取數量 |
| queue |  | string | 數量|

### 5. 錯誤代碼說明



### 6.回傳格式範例
```

array (size=3)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'unread_amount' => int 0

```







