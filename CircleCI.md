### そもそもCI/CDとはなんなのか

CI:Continuous Intergration / 継続的インテグレーション
CD:Continuous Deployment / 継続的デプロイ

CIでビルドとテストを実行、CDでデプロイ

#### Saas型

サービスの使用量に応じて or サブスク型で料金を支払う

#### オンプレミス型

ライセンスの購入費用やメンテナンス費用が発生

### CircleCIでできること

**ビルド**

ソースコードから実行可能なアプリケーションを構築
Dockerイメージのプル、依存パッケージのインストール、コンパイルなど

**テスト**

テストコードを実行して動作確認、Rubocopでリントチェックなど

**デプロイ**

ビルドしてテストが通ったものをリリース

![image](https://user-images.githubusercontent.com/58359284/109410054-d21ed700-79da-11eb-8946-d340d44a7a72.png)

https://codezine.jp/article/detail/11208
