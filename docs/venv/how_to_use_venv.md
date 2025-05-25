## Python仮想環境の有効化/無効化

### 仮想環境の有効化（アクティベーション，activation）
**Mac，Linuxの場合**
```
source myenv/bin/activate
```

**Windows PowerShellの場合**
```
myenv\Scripts\activate
```

有効化 (activate) されると、プロンプトに仮想環境の名前が表示されます。


### 仮想環境の無効化（deactivation）
仮想環境を終了し、元のユーザー環境に戻るには、次のコマンドを実行します。
```
deactivate
```


### ライブラリの保存
```
pip freeze > requirements.txt
```