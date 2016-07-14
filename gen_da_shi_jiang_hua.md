# 跟大師講話


更新日期:2016/07/14


### 1.路徑:api/character/talk.php 　

### 2. 說明

輸入角色ID
與對話類型(Type)請參考遊戲場景聖域裡面的部分有四個講話類型

### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| charaet_id | 1 | int | 11   |   --  |
| type | 0 | int |   |   天使  |
| type | 1 | int |   |   牧師  |
| type | 2 | int |   |   教師  |
| type | 4 | int |   |   聖誕老人   |

### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc | success | string | -- |
| character_id | 1 | string | -- |
|rand_task|每日隨機任務 |array|--"
|Daily_random_tasks_point|每日隨機積分 |array|--| 
|Daily_Take|禮包是否有被領取過 |array|--|  
|Package_1||array|禮包目前狀態|  
|Daily_Can_Get|禮包是否可以領取 |array||  
|Achive1||array|如果可以領取會顯示True|  
|Dail_Task_point|一般任務積分|array|--|  
|DailyEventID|一般任務標籤|array|--|  
|point|一般任務分數|array|--| 
|Dail_Random_props|每日隨機指定任務道具 |||  
|Specify_element| 指定隨機元素|||  
|Specify_Fragment|指定隨機製作碎片 |||  
|Integration|總積分 |||  
|Do_you_have|今天有沒有被使用過這隻API ||--|  
### 5. 錯誤代碼說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 140 | string |  |
| err_desc | character does not exist | string | 找不到此ID |
| err_code | 320 | string |  |
| err_desc | invalid type | string | 无效的类型 |





### 6.回傳格式範例
```

array (size=5)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'can not talk' (length=12)
  'success' => boolean false
  'remain_time' => int 0
  'eagle_shield' => int 6



```