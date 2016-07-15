
# 取得角色訊息-後台使用



更新日期:2016/07/15

### 1.路徑: ../character_mail/reply_duplex_message.php 　   　　　　 
   　　　　  　

### 2. 說明

輸入角色ID 跟
### 3. 輸入參數說明

| 參數 | 意義 | 型別 | 長度限制 | 說明 |
| -- | -- | -- | -- | -- | -- |
| character_id |  | string | 11   |   --  |
| mail_id |  | int | 11   |   --  |
| content |  | string | 11   |   --  |

### 4. 回傳參數說明
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 000 | string |  |
| err_desc |  | string | -- |
| head_id |  | int | 數量ID |
| tail_id |  | string | 抬頭ID|
 page_size |  | string | 頁數|
### 5. 錯誤代碼說明
```
| 參數 | 意義 | 型別 | 說明 |
| -- | -- | -- | -- | -- |
| err_code | 151 | string |  |
| err_desc | the character does not exist  | string | 沒有此ID |
  ```

### 6.回傳格式範例
```

array (size=3)
{"err_code":"902","err_desc":"ExceptionID:10823\ncode:23000,\nFile:\/var\/www\/html\/Temptation\/test\/lib\/idiorm\/idiorm.php,\nLine:434,\nMessage:SQLSTATE[23000]: Integrity constraint violation: 1452 Cannot add or update a child row: a foreign key constraint fails (`temptation`.`character_mail`, CONSTRAINT `character_mail_ibfk_2` FOREIGN KEY (`receiver_id`) REFERENCES `character` (`id`) ON DELETE CASCADE),\nTraceAsString:#0 \/var\/www\/html\/Temptation\/test\/lib\/idiorm\/idiorm.php(434): PDOStatement->execute()\n#1 \/var\/www\/html\/Temptation\/test\/lib\/idiorm\/idiorm.php(2010): ORM::_execute('INSERT INTO `ch...', Array, 'default')\n#2 \/var\/www\/html\/Temptation\/test\/api\/common\/common_function.php(571): ORM->save()\n#3 \/var\/www\/html\/Temptation\/test\/api\/common\/common_function.php(799): send_mail(Array, '1134', '0', '', '', 6, 0, '', '36', '0')\n#4 \/var\/www\/html\/Temptation\/test\/api\/character_mail\/reply_duplex_message.php(61): reply_duplex_message(Array, '109412', '')\n#5 \/var\/www\/html\/Temptation\/test\/api\/tool\/test_ajax.php(7): require_once('\/var\/www\/html\/T...')\n#6 {main}"}

```







