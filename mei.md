# 每日簽到


更新日期:2016/07/14

### 1.路徑: ../character/signin_reward.php 　  　

### 2. 說明

輸入角色ID ,進行簽到
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| charaet_id | 1 | int | 11   |   --  |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc | success | string | -- |
| success | 1 | bool | 成功與否 |
| goldleaf | 1 | bool | 獲取金幣 |
| reward_items | 1 |  | 道具禮包 |
| item_id | 1 | int | -- |
| num | 1 | int | -- |
### 5. 錯誤代碼說明







### 6.回傳格式範例
```
array (size=5)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'success' => boolean true
  'goldleaf' => int 0
  'reward_items' => 
    array (size=1)
      0 => 
        array (size=2)
          'item_id' => int 100001
          'num' => int 1



```
