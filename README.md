# azure_sample

# 環境設定(mac)

### cliを入れる

```
brew update
brew install azure-cli
```

### loginする

```
az login
```

urlが現れるので認証。    

参考    
https://docs.microsoft.com/ja-jp/cli/azure/authenticate-azure-cli?view=azure-cli-latest    

認証されるとaccount listに入る    

```
az account list
```

### コンテナリポジトリ

azure管理画面からContainerで検索してコンテナリポジトリを作成する。    


### docker login

docker loginでloginできる    

```
sudo docker login hogehoge.azurecr.io
```





# 参考

https://qiita.com/shinyay/items/803ec1ee4d5bfee1b39f
