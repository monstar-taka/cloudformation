# Amazon Virtual Private CloudをCloudFormationを使用して自動構築
## 構成イメージ図
![https://s3.amazonaws.com/private-gyazao-images/Database.png](https://s3.amazonaws.com/private-gyazao-images/Database.png)
## 説明
以下のこのテンプレートを使用し作成出来る内容を記載
- virtual private cloud
- public subnet(ap-northeast-1a)
- public subnet(ap-northeast-1c)
- private subnet(ap-northeast-1a)
- private subnet(ap-northeast-1c)
- internet gateway
- 開発用Web Security Group
- 開発用DB Security Group
- ステージング用Web Security Group
- ステージング用DB Security Group
- 本番用Web Security Group
- 本番用DB Security Group

以上をTokyo Regionに作成
