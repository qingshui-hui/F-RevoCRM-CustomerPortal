# docker

## 手順

1. .env内の環境変数を設定します。
2. php/Dockerfileを必要に応じて修正します。
3. docker-compose upを実行します。
4. VSCodeのDev Containersで、立ち上げたコンテナに接続します。

## このフォルダのみクローンする

```bash
git clone --no-checkout https://github.com/qingshui-hui/F-RevoCRM-CustomerPortal.git
cd F-RevoCRM-CustomerPortal
git config core.sparsecheckout true
git sparse-checkout set /docker
git checkout
```
