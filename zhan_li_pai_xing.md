# 戰力排行

API編碼:2.10.5

更新日期:2016/06/22

發布版本:2.0.6
### 1.路徑:/event/Rank_power_show 　

### 2. 說明

輸入角色ID 可以拿到自己的資訊,剩下資訊是每日排行資料
### 3. 輸入參數說明


| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id  |   | string | -- | 角色ID |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |--|
| -- | -- | -- | -- | -- |
| err_code | 000 | string | -- |--|
| err_desc | souce | string |  --|--|
| character_nicknamer | -- | string |--|--|
| character_lv   |  | int | -- | 角色等級|
| character_model   |  | int | -- | 角色模組|
| character_duty   |  | int | -- | 角色duty|
| Rank_list   |  | int | -- | 排行名次|
| Rank_score   |  | int | -- | 排行分數|
| Alliance_name   |  | int | -- | 個人所屬聯盟名稱|

### 5. 錯誤代碼說明



### 6.回傳格式範例
```
array (size=1)
  0 => 
    array (size=7)
      'character_nickname' => string '唐' (length=3)
      'character_lv' => int 90
      'character_model' => int 3
      'character_duty' => int 1
      'Rank_list' => int 1
      'Rank_score' => int 86472
      'Alliance_name' => string 'ABD' (length=3)
#### var_dump_fortest end ####

#### var_dump_fortest start ####
array (size=63)
  0 => 
    array (size=7)
      'character_nickname' => string '唐' (length=3)
      'character_lv' => int 90
      'character_model' => int 3
      'character_duty' => int 1
      'Rank_list' => int 1
      'Rank_score' => int 86472
      'Alliance_name' => string 'ABD' (length=3)
  1 => 
    array (size=7)
      'character_nickname' => string 'ra' (length=2)
      'character_lv' => int 100
      'character_model' => int 1
      'character_duty' => int 2
      'Rank_list' => int 2
      'Rank_score' => int 84401
      'Alliance_name' => string '' (length=0)
  2 => 
    array (size=7)
      'character_nickname' => string 'QQ30號' (length=7)
      'character_lv' => int 68
      'character_model' => int 0
      'character_duty' => int 2
      'Rank_list' => int 3
      'Rank_score' => int 82507
      'Alliance_name' => string 'TS4' (length=3)
  3 => 
    array (size=7)
      'character_nickname' => string 'A1133' (length=5)
      'character_lv' => int 60
      'character_model' => int 4
      'character_duty' => int 1
      'Rank_list' => int 4
      'Rank_score' => int 80428
      'Alliance_name' => string 'XXX' (length=3)
  4 => 
    array (size=7)
      'character_nickname' => string 'QQ33' (length=4)
      'character_lv' => int 33
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 5
      'Rank_score' => int 80319
      'Alliance_name' => string 'qqq' (length=3)
  5 => 
    array (size=7)
      'character_nickname' => string 'QAQ' (length=3)
      'character_lv' => int 10
      'character_model' => int 6
      'character_duty' => int 2
      'Rank_list' => int 6
      'Rank_score' => int 62142
      'Alliance_name' => string 'QAQ' (length=3)
  6 => 
    array (size=7)
      'character_nickname' => string 'yee' (length=3)
      'character_lv' => int 51
      'character_model' => int 1
      'character_duty' => int 3
      'Rank_list' => int 7
      'Rank_score' => int 57109
      'Alliance_name' => string 'QAQ' (length=3)
  7 => 
    array (size=7)
      'character_nickname' => string 'clliu_' (length=6)
      'character_lv' => int 16
      'character_model' => int 6
      'character_duty' => int 3
      'Rank_list' => int 8
      'Rank_score' => int 39188
      'Alliance_name' => string 'QAQ' (length=3)
  8 => 
    array (size=7)
      'character_nickname' => string '吃飯了' (length=9)
      'character_lv' => int 100
      'character_model' => int 6
      'character_duty' => int 1
      'Rank_list' => int 9
      'Rank_score' => int 26376
      'Alliance_name' => string 'qqq' (length=3)
  9 => 
    array (size=7)
      'character_nickname' => string 'wwqqq' (length=5)
      'character_lv' => int 8
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 10
      'Rank_score' => int 22940
      'Alliance_name' => string 'AAA' (length=3)
  10 => 
    array (size=7)
      'character_nickname' => string 'ryz' (length=3)
      'character_lv' => int 5
      'character_model' => int 4
      'character_duty' => int 3
      'Rank_list' => int 11
      'Rank_score' => int 22486
      'Alliance_name' => string '' (length=0)
  11 => 
    array (size=7)
      'character_nickname' => string 'a0428' (length=5)
      'character_lv' => int 3
      'character_model' => int 0
      'character_duty' => int 3
      'Rank_list' => int 12
      'Rank_score' => int 21394
      'Alliance_name' => string '' (length=0)
  12 => 
    array (size=7)
      'character_nickname' => string 'A7744' (length=5)
      'character_lv' => int 2
      'character_model' => int 2
      'character_duty' => int 1
      'Rank_list' => int 13
      'Rank_score' => int 18239
      'Alliance_name' => string '' (length=0)
  13 => 
    array (size=7)
      'character_nickname' => string '心情' (length=6)
      'character_lv' => int 3
      'character_model' => int 6
      'character_duty' => int 3
      'Rank_list' => int 14
      'Rank_score' => int 13939
      'Alliance_name' => string '' (length=0)
  14 => 
    array (size=7)
      'character_nickname' => string 's0602' (length=5)
      'character_lv' => int 22
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 15
      'Rank_score' => int 12064
      'Alliance_name' => string '' (length=0)
  15 => 
    array (size=7)
      'character_nickname' => string 'QQ31' (length=4)
      'character_lv' => int 7
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 16
      'Rank_score' => int 11837
      'Alliance_name' => string '' (length=0)
  16 => 
    array (size=7)
      'character_nickname' => string 'A6644' (length=5)
      'character_lv' => int 7
      'character_model' => int 1
      'character_duty' => int 1
      'Rank_list' => int 17
      'Rank_score' => int 11837
      'Alliance_name' => string '' (length=0)
  17 => 
    array (size=7)
      'character_nickname' => string 'REWR' (length=4)
      'character_lv' => int 7
      'character_model' => int 6
      'character_duty' => int 2
      'Rank_list' => int 18
      'Rank_score' => int 11805
      'Alliance_name' => string '' (length=0)
  18 => 
    array (size=7)
      'character_nickname' => string 'gg no2' (length=6)
      'character_lv' => int 12
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 19
      'Rank_score' => int 10654
      'Alliance_name' => string 'QAQ' (length=3)
  19 => 
    array (size=7)
      'character_nickname' => string 'QQ32' (length=4)
      'character_lv' => int 6
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 20
      'Rank_score' => int 9204
      'Alliance_name' => string '' (length=0)
  20 => 
    array (size=7)
      'character_nickname' => string 'A5566' (length=5)
      'character_lv' => int 22
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 21
      'Rank_score' => int 8073
      'Alliance_name' => string '' (length=0)
  21 => 
    array (size=7)
      'character_nickname' => string 'SS0607' (length=6)
      'character_lv' => int 4
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 22
      'Rank_score' => int 7875
      'Alliance_name' => string '' (length=0)
  22 => 
    array (size=7)
      'character_nickname' => string 'KTC' (length=3)
      'character_lv' => int 2
      'character_model' => int 6
      'character_duty' => int 1
      'Rank_list' => int 23
      'Rank_score' => int 6555
      'Alliance_name' => string '' (length=0)
  23 => 
    array (size=7)
      'character_nickname' => string 'QQ21號' (length=7)
      'character_lv' => int 100
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 24
      'Rank_score' => int 5729
      'Alliance_name' => string '' (length=0)
  24 => 
    array (size=7)
      'character_nickname' => string 'A2233' (length=5)
      'character_lv' => int 2
      'character_model' => int 2
      'character_duty' => int 1
      'Rank_list' => int 25
      'Rank_score' => int 5253
      'Alliance_name' => string '' (length=0)
  25 => 
    array (size=7)
      'character_nickname' => string 'SSS0604' (length=7)
      'character_lv' => int 2
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 26
      'Rank_score' => int 5253
      'Alliance_name' => string '' (length=0)
  26 => 
    array (size=7)
      'character_nickname' => string 'A4422' (length=5)
      'character_lv' => int 3
      'character_model' => int 2
      'character_duty' => int 1
      'Rank_list' => int 27
      'Rank_score' => int 3955
      'Alliance_name' => string '' (length=0)
  27 => 
    array (size=7)
      'character_nickname' => string 'qqqwe' (length=5)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 28
      'Rank_score' => int 3949
      'Alliance_name' => string '' (length=0)
  28 => 
    array (size=7)
      'character_nickname' => string 'S0607' (length=5)
      'character_lv' => int 1
      'character_model' => int 4
      'character_duty' => int 1
      'Rank_list' => int 29
      'Rank_score' => int 3946
      'Alliance_name' => string 'QAQ' (length=3)
  29 => 
    array (size=7)
      'character_nickname' => string 'S0614' (length=5)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 30
      'Rank_score' => int 3946
      'Alliance_name' => string '' (length=0)
  30 => 
    array (size=7)
      'character_nickname' => string 'SS0614' (length=6)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 31
      'Rank_score' => int 3946
      'Alliance_name' => string '' (length=0)
  31 => 
    array (size=7)
      'character_nickname' => string 'A1122' (length=5)
      'character_lv' => int 26
      'character_model' => int 1
      'character_duty' => int 3
      'Rank_list' => int 32
      'Rank_score' => int 3844
      'Alliance_name' => string 'a12' (length=3)
  32 => 
    array (size=7)
      'character_nickname' => string '心很累' (length=9)
      'character_lv' => int 2
      'character_model' => int 1
      'character_duty' => int 1
      'Rank_list' => int 33
      'Rank_score' => int 3769
      'Alliance_name' => string '' (length=0)
  33 => 
    array (size=7)
      'character_nickname' => string 'qwwqeqwe' (length=8)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 34
      'Rank_score' => int 3764
      'Alliance_name' => string '' (length=0)
  34 => 
    array (size=7)
      'character_nickname' => string 'weqe' (length=4)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 35
      'Rank_score' => int 3764
      'Alliance_name' => string '' (length=0)
  35 => 
    array (size=7)
      'character_nickname' => string 'hithere' (length=7)
      'character_lv' => int 1
      'character_model' => int 2
      'character_duty' => int 1
      'Rank_list' => int 36
      'Rank_score' => int 3764
      'Alliance_name' => string '' (length=0)
  36 => 
    array (size=7)
      'character_nickname' => string '遠洋' (length=6)
      'character_lv' => int 1
      'character_model' => int 1
      'character_duty' => int 3
      'Rank_list' => int 37
      'Rank_score' => int 3760
      'Alliance_name' => string '' (length=0)
  37 => 
    array (size=7)
      'character_nickname' => string 'QQQQQQQQQQQQ' (length=12)
      'character_lv' => int 2
      'character_model' => int 3
      'character_duty' => int 1
      'Rank_list' => int 38
      'Rank_score' => int 2650
      'Alliance_name' => string 'QAQ' (length=3)
  38 => 
    array (size=7)
      'character_nickname' => string 'Test0615' (length=8)
      'character_lv' => int 2
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 39
      'Rank_score' => int 2650
      'Alliance_name' => string '' (length=0)
  39 => 
    array (size=7)
      'character_nickname' => string 'A5522' (length=5)
      'character_lv' => int 2
      'character_model' => int 6
      'character_duty' => int 1
      'Rank_list' => int 40
      'Rank_score' => int 2650
      'Alliance_name' => string '' (length=0)
  40 => 
    array (size=7)
      'character_nickname' => string 'bbc' (length=3)
      'character_lv' => int 1
      'character_model' => int 1
      'character_duty' => int 1
      'Rank_list' => int 41
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  41 => 
    array (size=7)
      'character_nickname' => string 'qwewqed' (length=7)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 42
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  42 => 
    array (size=7)
      'character_nickname' => string '塔里木盆地' (length=15)
      'character_lv' => int 1
      'character_model' => int 4
      'character_duty' => int 1
      'Rank_list' => int 43
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  43 => 
    array (size=7)
      'character_nickname' => string 'swww' (length=4)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 44
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  44 => 
    array (size=7)
      'character_nickname' => string 'Test00' (length=6)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 45
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  45 => 
    array (size=7)
      'character_nickname' => string 'A7788' (length=5)
      'character_lv' => int 20
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 46
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  46 => 
    array (size=7)
      'character_nickname' => string 'd01' (length=3)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 47
      'Rank_score' => int 2647
      'Alliance_name' => string 'qqq' (length=3)
  47 => 
    array (size=7)
      'character_nickname' => string 'lollllll' (length=8)
      'character_lv' => int 1
      'character_model' => int 5
      'character_duty' => int 1
      'Rank_list' => int 48
      'Rank_score' => int 2647
      'Alliance_name' => string 'QAQ' (length=3)
  48 => 
    array (size=7)
      'character_nickname' => string 'hpbdgqaaa' (length=9)
      'character_lv' => int 1
      'character_model' => int 1
      'character_duty' => int 1
      'Rank_list' => int 49
      'Rank_score' => int 2647
      'Alliance_name' => string 'QAQ' (length=3)
  49 => 
    array (size=7)
      'character_nickname' => string 'A4455' (length=5)
      'character_lv' => int 1
      'character_model' => int 3
      'character_duty' => int 1
      'Rank_list' => int 50
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  50 => 
    array (size=7)
      'character_nickname' => string 'vffdxf' (length=6)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 51
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  51 => 
    array (size=7)
      'character_nickname' => string 'SS0604' (length=6)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 52
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  52 => 
    array (size=7)
      'character_nickname' => string 'S0606' (length=5)
      'character_lv' => int 1
      'character_model' => int 5
      'character_duty' => int 1
      'Rank_list' => int 53
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  53 => 
    array (size=7)
      'character_nickname' => string 'aa0607' (length=6)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 54
      'Rank_score' => int 2647
      'Alliance_name' => string '' (length=0)
  54 => 
    array (size=7)
      'character_nickname' => string 'A5123' (length=5)
      'character_lv' => int 1
      'character_model' => int 3
      'character_duty' => int 2
      'Rank_list' => int 55
      'Rank_score' => int 2645
      'Alliance_name' => string '' (length=0)
  55 => 
    array (size=7)
      'character_nickname' => string 'qwewqeqwe' (length=9)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 56
      'Rank_score' => int 1347
      'Alliance_name' => string '' (length=0)
  56 => 
    array (size=7)
      'character_nickname' => string '21' (length=2)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 57
      'Rank_score' => int 1347
      'Alliance_name' => string '' (length=0)
  57 => 
    array (size=7)
      'character_nickname' => string '123333' (length=6)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 58
      'Rank_score' => int 1347
      'Alliance_name' => string '' (length=0)
  58 => 
    array (size=7)
      'character_nickname' => string 'weq1234' (length=7)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 59
      'Rank_score' => int 1347
      'Alliance_name' => string '' (length=0)
  59 => 
    array (size=7)
      'character_nickname' => string 'Twrewrw' (length=7)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 60
      'Rank_score' => int 1347
      'Alliance_name' => string '' (length=0)
  60 => 
    array (size=7)
      'character_nickname' => string 'A7733' (length=5)
      'character_lv' => int 1
      'character_model' => int 1
      'character_duty' => int 1
      'Rank_list' => int 61
      'Rank_score' => int 1347
      'Alliance_name' => string '' (length=0)
  61 => 
    array (size=7)
      'character_nickname' => string 's0604' (length=5)
      'character_lv' => int 1
      'character_model' => int 6
      'character_duty' => int 1
      'Rank_list' => int 62
      'Rank_score' => int 1347
      'Alliance_name' => string '' (length=0)
  62 => 
    array (size=7)
      'character_nickname' => string 'A9955' (length=5)
      'character_lv' => int 1
      'character_model' => int 0
      'character_duty' => int 1
      'Rank_list' => int 63
      'Rank_score' => int 1347
      'Alliance_name' => string '' (length=0)
```
