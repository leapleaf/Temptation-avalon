# VIP

API編碼:2.10.4

更新日期:2016/06/17

發布版本:2.0.7
### 1.路徑:api/event/VIP_show

### 2. 說明

VIP功能
### 3. 輸入參數說明


| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| charaet_id | 1 | int | 11   |   --  |


### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc | success | string | -- |
| character_id | 1 | int | -- |
|vip_lv|VIP等級 |int|--"
|vip_pay|VIP付款金額 |int|--| 
|Vipinform|VIP資訊 |array|以下都是靜態表資料|  
|VipID||int||  
|VipLv| |int||  
|Prepaid||int||  
|GetGold||int|--|  
|Mount||int|--|  
|point||int|--| 
|ExpBuff| |int||  
|GemSpeepBuff| |int||  
|GemNumBuff| |int||  
|StaminaBuff| |int||  
|PetAtkBuff| |int|--|  
|PetDefBuff| |int|--|  
|PetHpBuff| |int|--|  
|LvLimit| |int|--|  

### 5. 錯誤代碼說明




### 6.回傳格式範例
```
array (size=6)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'character_id' => int 1134
  'vip_lv' => int 8
  'vip_pay' => int 50240
  'VipID' => 
    array (size=10)
      0 => 
        array (size=13)
          'VipID' => int 1001
          'VipLv' => int 1
          'Prepaid' => int 120
          'GetGold' => int 300
          'Mount' => int 0
          'ExpBuff' => float 0.05
          'GemSpeepBuff' => float 0
          'GemNumBuff' => float 0
          'StaminaBuff' => int 10
          'PetAtkBuff' => int 0
          'PetDefBuff' => int 0
          'PetHpBuff' => int 0
          'LvLimit' => int 1
      1 => 
        array (size=13)
          'VipID' => int 1002
          'VipLv' => int 2
          'Prepaid' => int 500
          'GetGold' => int 1000
          'Mount' => int 3
          'ExpBuff' => float 0.1
          'GemSpeepBuff' => float 0.03
          'GemNumBuff' => float 0
          'StaminaBuff' => int 20
          'PetAtkBuff' => int 30
          'PetDefBuff' => int 30
          'PetHpBuff' => int 30
          'LvLimit' => int 1
      2 => 
        array (size=13)
          'VipID' => int 1003
          'VipLv' => int 3
          'Prepaid' => int 1500
          'GetGold' => int 1500
          'Mount' => int 7
          'ExpBuff' => float 0.2
          'GemSpeepBuff' => float 0.05
          'GemNumBuff' => int 2
          'StaminaBuff' => int 30
          'PetAtkBuff' => int 50
          'PetDefBuff' => int 50
          'PetHpBuff' => int 100
          'LvLimit' => int 1
      3 => 
        array (size=13)
          'VipID' => int 1004
          'VipLv' => int 4
          'Prepaid' => int 4000
          'GetGold' => int 2000
          'Mount' => int 14
          'ExpBuff' => float 0.3
          'GemSpeepBuff' => float 0.07
          'GemNumBuff' => float 2
          'StaminaBuff' => int 50
          'PetAtkBuff' => int 100
          'PetDefBuff' => int 100
          'PetHpBuff' => int 250
          'LvLimit' => int 1
      4 => 
        array (size=13)
          'VipID' => int 1005
          'VipLv' => int 5
          'Prepaid' => int 10000
          'GetGold' => int 3000
          'Mount' => int 30
          'ExpBuff' => float 0.4
          'GemSpeepBuff' => float 0.09
          'GemNumBuff' => float 2
          'StaminaBuff' => int 70
          'PetAtkBuff' => int 150
          'PetDefBuff' => int 150
          'PetHpBuff' => int 300
          'LvLimit' => int 1
      5 => 
        array (size=13)
          'VipID' => int 1006
          'VipLv' => int 6
          'Prepaid' => int 15000
          'GetGold' => int 4000
          'Mount' => int 60
          'ExpBuff' => float 0.5
          'GemSpeepBuff' => float 0.15
          'GemNumBuff' => float 3
          'StaminaBuff' => int 100
          'PetAtkBuff' => int 150
          'PetDefBuff' => int 150
          'PetHpBuff' => int 350
          'LvLimit' => int 30
      6 => 
        array (size=13)
          'VipID' => int 1007
          'VipLv' => int 7
          'Prepaid' => int 30000
          'GetGold' => int 5000
          'Mount' => int 36500
          'ExpBuff' => float 0.6
          'GemSpeepBuff' => float 0.2
          'GemNumBuff' => float 3
          'StaminaBuff' => int 150
          'PetAtkBuff' => int 200
          'PetDefBuff' => int 200
          'PetHpBuff' => int 400
          'LvLimit' => int 35
      7 => 
        array (size=13)
          'VipID' => int 1008
          'VipLv' => int 8
          'Prepaid' => int 50000
          'GetGold' => int 10000
          'Mount' => int 36500
          'ExpBuff' => float 0.7
          'GemSpeepBuff' => float 0.25
          'GemNumBuff' => float 4
          'StaminaBuff' => int 200
          'PetAtkBuff' => int 200
          'PetDefBuff' => int 200
          'PetHpBuff' => int 500
          'LvLimit' => int 40
      8 => 
        array (size=13)
          'VipID' => int 1009
          'VipLv' => int 9
          'Prepaid' => int 120000
          'GetGold' => int 20000
          'Mount' => int 36500
          'ExpBuff' => float 0.8
          'GemSpeepBuff' => float 0.3
          'GemNumBuff' => float 4
          'StaminaBuff' => int 250
          'PetAtkBuff' => int 250
          'PetDefBuff' => int 250
          'PetHpBuff' => int 600
          'LvLimit' => int 45
      9 => 
        array (size=13)
          'VipID' => int 1010
          'VipLv' => int 10
          'Prepaid' => int 240000
          'GetGold' => int 30000
          'Mount' => int 36500
          'ExpBuff' => float 1
          'GemSpeepBuff' => float 0.35
          'GemNumBuff' => float 5
          'StaminaBuff' => int 300
          'PetAtkBuff' => int 300
          'PetDefBuff' => int 300
          'PetHpBuff' => int 800
          'LvLimit' => int 50

```
