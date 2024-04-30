# liquibase-mongodb-demo

### 範例注意事項
- 必須加入Liquibase Extension相關依賴才可以使用NoSQL相關功能(參考1)
- 不支援自動回滾, 但可以自訂回滾流程
- Liquibase Pro 需要額外申請Key, 由於不確定付費問題與使用依賴有發生錯誤, 所以範例中並未使用(參考4)
- 部分版本Extension與Liquibase在使用MongoDB的情境下存在相容問題(參考3)

### 框架使用
- Spring Boot
- MongoDB
- Liquibase
- Liquibase Extension

### Demo範例
- Collection Create&Drop
- 欄位規則
- 資料單/多筆新增
- 回滾 (未完成)


### 參考資料來源
1. https://contribute.liquibase.com/extensions-integrations/
2. https://docs.liquibase.com/change-types/mongodb/home.html
3. https://github.com/liquibase/liquibase-mongodb/blob/main/src/test/resources/liquibase/ext/changelog.create-collection.test.xml

### 備註
1. https://docs.liquibase.com/change-types/mongodb/home.html
2. https://contribute.liquibase.com/extensions-integrations/directory/database-tutorials/mongodb/
3. https://github.com/spring-projects/spring-boot/issues/29991
4. https://docs.liquibase.com/start/tutorials/mongodb-pro/home.html
