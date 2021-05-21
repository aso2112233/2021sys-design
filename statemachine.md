```UML
@startuml
[*] --> トップページ
トップページ -> 会員登録
トップページ -left-> ログイン
トップページ --> カート
カート -> お届け先入力
お届け先入力 -> otodokesakinyuuryokunaiyoukakuninn
otodokesakinyuuryokunaiyoukakuninn -> kounyuukannryou
@enduml
```
