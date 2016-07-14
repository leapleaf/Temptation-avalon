# 獲取元素


更新日期:2016/07/14

### 1.路徑:    ../character/collect_gem.php 　　　　 
   　　　　  　

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
| gems |  | string | 寶石 |
| queue |  | string | 數量|

### 5. 錯誤代碼說明

| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 140 | string |  |
| err_desc | the character does not exist  | string | 沒有此ID |



### 6.回傳格式範例
```

{"err_code":"000","err_desc":"success","gems":[],"queue":[]}

```






