# study-applescript
applescriptを色々やってみる用のrepo

### 拡張機能導入と.applescriptファイル文字化け解消
- applescript用の拡張機能を入れる
```
https://marketplace.visualstudio.com/items?itemName=idleberg.applescript
```
- `command+,`でvscodeのpreferenceを開く
- settings.jsonと入力してsettings.jsonで編集をクリック
- jsonファイルに下記を追加

```
"[applescript]": {
  "files.encoding": "utf8"
}
```

### アプリケーション化の仕方
- アプリケーション化したい`.applescript`ファイルを開く
- Shift+comman+Pでvscodeのcommand-paletteを開く
- `applescript`を入力すると、`Compile Application`が表示されるのでクリックするとアプリケーションにコンパイルされる

### 参考
https://qiita.com/seiya1121/items/656fd596570f9e8276bc