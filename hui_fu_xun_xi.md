
# 接收信件獎勵



更新日期:2016/07/15

### 1.路徑: ../character_mail/receive_msg_reward.php  　   　　　　 
   　　　　  　

### 2. 說明

輸入角色ID 跟 信件ID
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id |  | string | 11   |   --  |
| character_mail_id |  | int | 11   |   --  |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc |  | string | -- |
| item_id |  | int | 道具ID |
| num |  | int | 數量|
| goldleaf |  | int | 金幣|

### 5. 錯誤代碼說明
```
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 111 | string |  |
| err_desc | can not find the mail  | string | 沒有此ID |
  ```

### 6.回傳格式範例
```
array (size=6)

array (size=5)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'reward_items' => 
    array (size=2)
      0 => 
        array (size=2)
          'item_id' => int 100175
          'num' => int 1000
      1 => 
        array (size=2)
          'item_id' => int 300001
          'num' => int 1
  'cardlist' => 
    array (size=0)
      empty
  'goldleaf' => int 0

```











