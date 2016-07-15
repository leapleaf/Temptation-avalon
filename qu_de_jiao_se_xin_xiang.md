
# 取得角色信箱



更新日期:2016/07/15

### 1.路徑: ../character_mail/get_msg_inbox.php   　   　　　　 
   　　　　  　

### 2. 說明

輸入角色ID 跟 信件類型  收信者暱稱 信件主旨 信件內容
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id |  | string | 11   |   --  |
| type |  | int | 11   |   --  |
| receiver_name |  | string | 11   |   --  |
| subject |  | string | 11   |   --  |
| content |  | string | 11   |   --  |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc |  | string | -- |
| canSendMsg |  | int | 道具ID |


### 5. 錯誤代碼說明
```

  ```

### 6.回傳格式範例
```
array (size=3)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'canSendMsg' => boolean true

```















