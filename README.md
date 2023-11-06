# CFn-APIGateway-DynamoDB
![ddb-crud](https://github.com/Koshi-46/CFn-APIGateway-DynamoDB/assets/55370161/9176263d-5f86-4389-965e-877e7373e097)

## 使い方
### 項目の作成または更新
curl -X "PUT" -H "Content-Type: application/json" -d "{\"id\": \"123\", \"price\": 12345, \"name\": \"myitem\"}" https://********.execute-api.{region}.amazonaws.com/items

### すべての項目を取得する
curl https://********.execute-api.{region}.amazonaws.com/items

### 1つの項目を取得する
curl https://********.execute-api.{region}.amazonaws.com/items/{id}

### 項目を削除する
curl -X "DELETE" curl https://********.execute-api.{region}.amazonaws.com/items/{id}
