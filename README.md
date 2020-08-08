# owAutoBootツール
### 前提条件
画面のサイズが1920*1080であること、pythonのPyAutoGUIがインストールされていること

### 設定手順
1.ブリザードアプリをタスクバーに追加

![キャプチャ](https://user-images.githubusercontent.com/55028393/64477793-b4ecbc00-d1da-11e9-815a-03512b6cfd2d.PNG)



2.タスクスケジューラ追加設定

- [ ] 基本タスクの作成
- [ ] 名前をテキトーにかく
- [ ] トリガーは「コンピュータの起動時」を選択
- [ ] 操作は「プログラムの開始」を選択
- [ ] プログラム/スクリプトはpython.exeの格納場所、引数の追加(オプション)はowAutoBoot.py、開始(オプション)はowAutoBoot.pyの格納場所をそれぞれ指定
![キャプチャ1](https://user-images.githubusercontent.com/55028393/64478055-9936e500-d1dd-11e9-8235-0c34f3945244.PNG)

遅延時間などは良い感じにテキトーに
