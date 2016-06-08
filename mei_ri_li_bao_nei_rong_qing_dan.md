# 每日禮包內容清單

API編碼:2.10.3

更新日期:2016/06/08

發布版本:2.0.6
### 1.路徑: ../event/Daily_Tasks_show_get.php 　

### 2. 說明

輸入角色跟ID跟禮包順序可以查詢禮包內容
### 3. 輸入參數說明


| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id  | character_id  | int | -- | 角色ID |
| Receive_gifts_id   | 範例:10001 | int | -- | 禮包ID|

### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| exp |  | int | 經驗值 |
| property |  | string | 道具 |
| quantity |  | int | 數量 |
| err_code | 430 | string | 已領取 |
| err_code | 430 | string | 已領取 |
| err_code|431|string|未領取|
| Daily_Take| | bool | 有沒有領過 |
| Daily_Can_Get| | bool | 可不可以領取 | 



### 5. 錯誤代碼說明

### 6.回傳格式範例


```
array (size=4)
  'Daily_Take' => boolean false
  'Daily_Can_Get' => boolean false
  'exp' => int '100' (length=3)
  0 => 
    array (size=2)
      'property' => string '100009' (length=6)
      'quantity' => int 1
{"Daily_Take":false,"Daily_Can_Get":false,"exp":"100","0":{"property":"100009","quantity":1}}
``````
