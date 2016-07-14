# 取得角色資訊


更新日期:2016/07/14

### 1.路徑:  ../character/get_character.php 　 　　 　  　

### 2. 說明

輸入角色ID 、暱稱、戰鬥值(職業)、角色模組
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| charaet_id | 1 | int | 11   |   --  |

### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc | success | string | -- |
| nickname |  | string | 暱稱 |
| model |  | string | 特殊玩家 |
| duty |  | string | 職業 |
| exp |  | string | 經驗值 |
| lv |  | string | 等級 |
| power |  | string | 戰力 |
| position |  | string | 領導 |
| alliance_name |  | string | 聯盟名稱 |
| alliance_short_name |  | string | 聯盟短名稱 |
| alliance_join_receive |  | string | 聯盟捐獻 |
| alliance_create_receive |  | string | 創立聯盟 |
| received_signin_reward_today |  | string | 累積領取簽到日期 |
| receive_newbie_gift |  | string | 新手獎勵 |
| action_point |  | string | 行動值 |
| action_total_point |  | string | 總共行動值 |
| mounts_id |  | string | 寵物ID |
| vip_pet_time |  | string | 寵物時間 |
| gem_num |  | string | 元素製作數量 |
| goldleaf |  | string | 金幣 |
| stage_no |  | string | 關卡名稱 |
| signin_day |  | string | 簽到天數 |
| eagle_shield |  | string | 應級盾牌 |
| belief |  | string | 信仰 |
| belief_type |  | string | 信仰type |
| theology |  | string | 神學 |
| theology_type |  | string | 神學type |
| gem_remain_time |  | string | 元素製作時間 |
| pet_exist |  | string | 目前卡牌 |
| pet_id |  | string | 卡牌ID |
| pet_lv |  | string | 卡牌等級 |
| pet_hp |  | string | 卡牌血量 |
| pet_atk |  | string | 卡牌攻擊力 |
| pet_def |  | string | 卡牌防禦力 |
| pet_act_skill_id1 |  | string | 卡牌攻擊技能1 |
| pet_act_skill_id2 |  | string | 卡牌攻擊技能2 |
| pet_act_skill_id3 |  | string | 卡牌攻擊技能3 |
| pets_atk |  | string | 卡牌總攻擊 |
| pets_def |  | string | 卡牌總防禦 |
| normal_fight_win_times |  | string | 戰鬥勝利次數 |
| normal_fight_lose_times |  | string | 戰鬥失敗次數 |
| boss_fight_win_times |  | string | 王戰鬥勝利次數 |
| boss_fight_lose_times |  | string | 王戰鬥失敗次數 |
| boss_fight_damage |  | string | 王的總傷害 |
| pvpWin |  | string | pvp贏 |
| pvpLose |  | string | pvp輸 |
| skill_item_type1 |  | string | 技能裝備1 |
| skill_item_type2 |  | string | 技能裝備2 |
| skill_item_type3 |  | string | 技能裝備3 |
| skill_item_type4 |  | string | 技能裝備4 |
| skill_item_type5 |  | string | 技能裝備5 |
| newbie_status |  | string | 新手狀態 |
| action_point_countdown |  | string | 行動值倒數計時 |
| bfAddEquipValue |  | string | 虔誠增加值 |
| bfItemAddRate |  | string | 虔誠增家數量與bfAddEquipValue 來取得角色虔誠值 |
| protector_status |  | string | 保護狀態 ,請參考角色table |
| santa_stage_id |  | string | 聖誕老人關卡ID |

### 5. 錯誤代碼說明



### 6.回傳格式範例
```
array (size=61)
  'err_code' => string '000' (length=3)
  'err_desc' => string 'success' (length=7)
  'nickname' => string '唐' (length=3)
  'model' => int 1
  'duty' => int 1
  'exp' => int 24319
  'lv' => int 70
  'vip_lv' => int 4
  'power' => int 125341
  'position' => int 6
  'alliance_name' => string 'goddamn' (length=7)
  'alliance_short_name' => string 'ABD' (length=3)
  'alliance_join_receive' => boolean true
  'alliance_create_receive' => boolean false
  'received_signin_reward_today' => boolean true
  'receive_newbie_gift' => boolean true
  'action_point' => int 150
  'action_total_point' => int 150
  'mounts_id' => string '' (length=0)
  'vip_pet_time' => int 0
  'gem_num' => int 3
  'goldleaf' => int 1441000
  'stage_no' => int 1600703
  'signin_day' => int 1
  'eagle_shield' => int 6
  'belief' => int 609
  'belief_type' => int 5
  'theology' => int 202
  'theology_type' => int 5
  'gem_remain_time' => int 0
  'pet_exist' => boolean true
  'pet_id' => int 100101
  'pet_lv' => int 10
  'pet_hp' => int 720
  'pet_atk' => int 455
  'pet_def' => int 528
  'pet_act_skill_id1' => int 10000103
  'pet_act_skill_id2' => int 10000301
  'pet_act_skill_id3' => int 10002205
  'pets_atk' => int 122426
  'pets_def' => int 141551
  'normal_fight_win_times' => int 194
  'normal_fight_lose_times' => int 1
  'boss_fight_win_times' => int 0
  'boss_fight_lose_times' => int 2
  'boss_fight_damage' => int 40828052
  'pvpWin' => int 2
  'pvpLose' => int 2
  'skill_item_type1' => int 4409
  'skill_item_type2' => int 4144
  'skill_item_type3' => int 4114
  'skill_item_type4' => int 4092
  'skill_item_type5' => int 4034
  'newbie_status' => int 4
  'action_point_countdown' => int 120
  'bfAddEquipValue' => int 0
  'bfItemAddRate' => int 0
  'thAddEquipValue' => int 0
  'thItemAddRate' => int 0
  'protector_status' => int -1
  'santa_stage_id' => int 0

```
