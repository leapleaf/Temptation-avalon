
# 取得角色訊息-後台使用



更新日期:2016/07/15

### 1.路徑: ../character_mail/send_duplex_message.php 　   　　　　 
   　　　　  　

### 2. 說明

輸入角色ID 跟 收信者暱稱 跟內容 
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id |  | string | 11   |   --  |
| mail_id |  | int | 11   |   --  |
| content |  | string | 11   |   --  |

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
| err_code | 112 | string |  |
| err_desc | the receiver does not exist  | string | 沒有此ID |
  ```

### 6.回傳格式範例
```
array (size=6)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'canSendMsg' => boolean true
  'model' => int 1
  'duty' => int 1
  'mail_id' => int 110102

```









