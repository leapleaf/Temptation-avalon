# VIP_pet


API編碼:2.10.6

更新日期:2016/07/05

發布版本:2.0.6
### 1.路徑:../event/VIP_pet.php 　　

### 2. 說明
輸入角色ID MountsID判斷目前要裝備哪一個 , MountsName 空值為不更改名稱 ,輸入值可以更名
### 3. 輸入參數說明


| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id  |   | int | -- | 角色ID |
| MountsID  |   | string | -- | 寵物ID |
| MountsName  |   | string | -- |寵物名稱 |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| 000  |   | int | -- |  |
| souce  |   |string  | -- | 回傳成功 |
| My_pet  |   | string | -- |寵物ID |
| My_pet_nam  |   | string | -- |寵物名稱 |
### 5. 錯誤代碼說明



### 6.回傳格式範例
```
{"err_code":"000","err_desc":"success","My_pet":"MountsID10001","My_pet_nam":"949141"}
```

