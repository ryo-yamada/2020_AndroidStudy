## パッケージ構成

- presentation
    - View, ViewModel、widget、adapter等
- data
    - repository
    - api
    - db
- domain
    - model

## クラス図


## DBテーブル

|カラム名|属性|備考|
|:--|:--|:--|
|id|varchar|PK|
|json|varchar|-|
|register_time|datetime|-|

## 利用ライブラリ
### AAC
- navigation
- coroutine

### DB
- room

### httpクライアント
- retrofit

### Jsonパース
- kotshi

### DI
- dagger hilt

### 画像
- Glide

### 日付
- ThreeTenABP