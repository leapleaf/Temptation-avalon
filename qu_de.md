# 取得跟大師講話


更新日期:2016/07/14

### 1.路徑:./character/get_talk.php  　

### 2. 說明

輸入角色ID ,查詢目前哪個講話已經對過話
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| charaet_id | 1 | int | 11   |   --  |
| charaet_id | 1 | int | 11   |   --  |
| charaet_id | 1 | int | 11   |   --  |

### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc | success | string | -- |
| can_angel_talk | 1 | bool | -- |
| can_pastor_talk | 1 | bool | -- |
| can_teacher_talk | 1 | bool | -- |
| can_santaclaus_talk | 1 | bool | -- |

### 5. 錯誤代碼說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 140 | string |  |
| err_desc | character does not exist | string | 找不到此ID |






### 6.回傳格式範例
```


{"err_code":"000","err_desc":"success","can_angel_talk":true,"can_pastor_talk":true,"can_teacher_talk":false,"can_santaclaus_talk":true}



```
