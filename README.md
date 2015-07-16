# Amazon Virtual Private CloudをCloudFormationを使用して自動構築
## template①
![http://private-gyazao-images.s3.amazonaws.com/Database.png](http://private-gyazao-images.s3.amazonaws.com/Database.png)
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

## template②
![http://private-gyazao-images.s3.amazonaws.com/Database_rds.png](http://private-gyazao-images.s3.amazonaws.com/Database_rds.png)
## 説明
以下のこのテンプレートを使用し作成出来る内容を記載
- virtual private cloud
- public subnet(ap-northeast-1a)
- public subnet(ap-northeast-1c)
- private subnet(ap-northeast-1a)
- private subnet(ap-northeast-1b)
- private subnet(ap-northeast-1c)
- internet gateway
- rds-single
- rds-multi-az
- rds parameter groups
- rds subnet groups

以上をTokyo Regionに作成
