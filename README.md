# plantuml-vscode
vscode で PlantUML をリアルタイムプレビュー。

## 動作環境
```
$ sw_vers
ProductName:    Mac OS X
ProductVersion: 10.14.6
BuildVersion:   18G87
```
```
$ docker --version
Docker version 19.03.1, build 74b1e89
```
```
$ docker-compose --version
docker-compose version 1.24.1, build 4667896b
```
```
$ code -v
1.41.1
```

## セットアップ
- vscode の extensions タブで `@recommended` で検索。
- workspace recommendations の拡張をインストール。
- PlantUML server コンテナを起動。
```
$ docker-compose up
```

## 使い方
### プレビュー
- `Option + D`

### 画像出力
- `Shift + ⌘ + P` でコマンドパレットを開く。
- `PlantUML: Export Current Diagrams` を選択。
- `png`, `svg` など任意の形式を選択。
