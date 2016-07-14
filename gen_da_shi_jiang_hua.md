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
array (size=11)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'character_id' => int 1
  'reset_time' => int 63536
  'rand_task' => 
    array (size=2)
      0 => 
        array (size=2)
          'rand_task' => int 20001
          'Daily_random_tasks_point' => int 0
      1 => 
        array (size=2)
          'rand_task' => int 20004
          'Daily_random_tasks_point' => int 0
  'Daily_Take' => 
    array (size=13)
      'Package_1' => boolean false
      'Package_2' => boolean false
      'Package_3' => boolean false
      'Package_4' => boolean false
      'Package_5' => boolean false
      'Package_6' => boolean false
      'Package_7' => boolean false
      'Package_8' => boolean false
      'Package_9' => boolean false
      'Package_10' => boolean false
      'Package_11' => boolean false
      'Package_12' => boolean false
      'Package_13' => boolean false
  'Daily_Can_Get' => 
    array (size=13)
      'Achive1' => boolean false
      'Achive2' => boolean false
      'Achive3' => boolean false
      'Achive4' => boolean false
      'Achive5' => boolean false
      'Achive6' => boolean false
      'Achive7' => boolean false
      'Achive8' => boolean false
      'Achive9' => boolean false
      'Achive10' => boolean false
      'Achive11' => boolean false
      'Achive12' => boolean false
      'Achive13' => boolean false
  'Dail_Task_point' => 
    array (size=8)
      0 => 
        array (size=2)
          'DailyEventID' => int 10001
          'point' => int 0
      1 => 
        array (size=2)
          'DailyEventID' => int 10002
          'point' => int 0
      2 => 
        array (size=2)
          'DailyEventID' => int 10003
          'point' => int 0
      3 => 
        array (size=2)
          'DailyEventID' => int 10004
          'point' => int 0
      4 => 
        array (size=2)
          'DailyEventID' => int 10005
          'point' => int 0
      5 => 
        array (size=2)
          'DailyEventID' => int 10006
          'point' => int 0
      6 => 
        array (size=2)
          'DailyEventID' => int 10007
          'point' => int 0
      7 => 
        array (size=2)
          'DailyEventID' => int 10008
          'point' => int 0
  'Dail_Random_props' => 
    array (size=2)
      'Specify_element' => int 100011
      'Specify_Fragment' => int 100111
  'Integration' => int 0
  'Do_you_have' => boolean false





```