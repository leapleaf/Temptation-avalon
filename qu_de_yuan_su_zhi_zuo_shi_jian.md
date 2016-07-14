# 取得元素製作時間




更新日期:2016/07/14

### 1.路徑:   ../character/get_collect_gem.php 　　　　 
   　　　　  　

### 2. 說明

輸入角色ID  
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| charaet_id | 1 | int | 11   |   --  |



### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc |  | string | -- |
| remaining_time |  | string | 寶石製作柱列時間 |
| gem_id |  | string | 製作寶石ID|

### 5. 錯誤代碼說明

| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 140 | string |  |
| err_desc | the character does not exist  | string | 沒有此ID |



### 6.回傳格式範例
```

{"err_code":"000","err_desc":"success","remaining_time":2000,"gem_id":100001,"queue":[{"gem_id":100001,"remaining_time":2000},{"gem_id":100001,"remaining_time":-1}]}

```





