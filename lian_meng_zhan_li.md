# 聯盟競技場排行


API編碼:2.10.8

更新日期:2016/07/13

發布版本:2.0.7

### 1.路徑:rank/Show_card_rank.php 
### 2. 說明
### 3. 輸入參數說明





### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | int |  |
| err_desc | success | int | -- |
| Alliance_short_name |  | string | 聯盟短名稱|
| Alliance_long_name |  | string | 聯盟名稱 |
| Rank_score |  | int | 競技場分數 |
| Rank_list |  | int | 排名 |
| nickname |  | string | 聯盟盟主 |

### 5. 錯誤代碼說明




### 6.回傳格式範例
```
array (size=4)
  0 => 
    array (size=5)
      'Alliance_short_name' => string 'QAQ' (length=3)
      'Alliance_long_name' => string 'QAQQ' (length=4)
      'Rank_score' => int 1410
      'Rank_list' => int 1
      'nickname' => string '' (length=0)
  1 => 
    array (size=5)
      'Alliance_short_name' => string 'GGG' (length=3)
      'Alliance_long_name' => string 'GGGGG' (length=5)
      'Rank_score' => int 660
      'Rank_list' => int 2
      'nickname' => string '' (length=0)
  2 => 
    array (size=5)
      'Alliance_short_name' => string 'qqq' (length=3)
      'Alliance_long_name' => string 'qqqq' (length=4)
      'Rank_score' => int 520
      'Rank_list' => int 3
      'nickname' => string '' (length=0)
  3 => 
    array (size=5)
      'Alliance_short_name' => string 'XXX' (length=3)
      'Alliance_long_name' => string 'XXXX' (length=4)
      'Rank_score' => int 340
      'Rank_list' => int 4
      'nickname' => string '' (length=0)

```





