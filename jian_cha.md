
# 檢查_訊息讀取(不確定用不用到)



更新日期:2016/07/15

### 1.路徑: ../character_mail/set_msg_read.php  　   　　　　 
   　　　　  　

### 2. 說明

輸入mail_ID來對應 
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| mail_id |  | int | 11   |   --  |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc |  | string | -- |
| canSendMsg |  | int | 數量ID |
| model |  | int | 抬頭ID|
| duty |  | int | 抬頭ID|
| mail_id |  | int | 抬頭ID|
### 5. 錯誤代碼說明
```
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 111 | string |  |
| err_desc | the mail does not exist  | string | 沒有此ID |
  ```

### 6.回傳格式範例
```
array (size=2)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)

```











