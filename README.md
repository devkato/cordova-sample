
## インストール

```shell
npm -g install cordova ios-sim
source ~/.zshrc
```

## cordovaコマンドについて

[Cordova Command-Line Interface](http://docs.phonegap.com/en/edge/guide_cli_index.md.html#The%20Command-Line%20Interface)

## 起動方法

### iOS

注意: tmux上から実行するとsession timeoutになるので、素のshellから叩くこと。

```shell
cordova emulate ios
```

### Android

Genymotionを利用する場合

@TODO デバッグログが全く見れないんだけど、logcatするしかないのかな

```shell
cordova run android
```

通常のAndroid Simulatorを利用する場合

```shell
cordova emulate android
```
