# 回復API

# 取得角色訊息-後台使用




更新日期:2016/07/15

### 1.路徑:    ../character_mail/get_duplex_message.php   　　　　 
   　　　　  　

### 2. 說明

輸入角色ID 跟
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
| head_id |  | int | 數量ID |
| tail_id |  | string | 抬頭ID|
 page_size |  | string | 頁數|
### 5. 錯誤代碼說明
```
array (size=2)
  'err_code' => string '151' (length=3)
  'err_desc' => string 'the mail does not exist' (length=23)
  ```

### 6.回傳格式範例
```

array (size=3)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'head_id' => int 0
  'tail_id' => 
  'head_content' => 
  'tail_content' => 

```







