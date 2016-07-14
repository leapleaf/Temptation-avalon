# 設定角色職業與模組


更新日期:2016/07/14

### 1.路徑:  ../character/set_character.php 　　 　  　

### 2. 說明

輸入角色ID 、暱稱、戰鬥值(職業)、角色模組
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| charaet_id | 1 | int | 11   |   --  |
| nickname | 1 | int | 11   |   --  |
| duty | 1 | int | 11   |   --  |
| model | 1 | int | 11   |   --  |

### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc | success | string | -- |
| remain_goldleaf |  | string | 扣除金幣 |
### 5. 錯誤代碼說明



### 6.回傳格式範例
```
array (size=3)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'remain_goldleaf' => int 1441000

```
