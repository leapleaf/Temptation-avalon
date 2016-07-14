# 選擇元素製作



# 取得角色資訊


更新日期:2016/07/14

### 1.路徑:    ../character/choose_collect_gem.php   　　　　  　

### 2. 說明

輸入角色ID  製作物品ID
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| charaet_id | 1 | int | 11   |   --  |
| item_id | 1 | 物品ID | 11   |   --  |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc |  | string | -- |
| remaining_time |  | string | 寶石製作柱列 |
| last_remaining_time |  | string | 累加時間 |

### 5. 錯誤代碼說明

| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 140 | string |  |
| err_desc | the character does not exist  | string | 沒有此ID |



### 6.回傳格式範例
```
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'remaining_time' => int 2232
  'last_remaining_time' => int 2232

```





