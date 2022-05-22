# Monster Hunter Series Gallary
ボタンを押すと歴代のモンスターハンターシリーズが表示されるアプリです。

各作品のパッケージ画像とともに作品名・発売日・売上本数が表示されます。

# 工夫したところ
今後作品が増えても良いようにしたところ。具体的にはボタンの数を作品数の分だけ用意するのではなく、電卓のように任意の数を入力できるようにして、対象範囲外の番号にはエラーメッセージを出すようにしました。

# 苦戦したところ
clearボタンを押したあとにシリーズの情報を消すところ。既にある変数を関数の中で再定義してしまったために発生したバグでした。変数のスコープの重要性を思い知りました。

HTMLにJavaScriptが反映されなかったところ。JS初心者なので、scriptタグを入れてないとか入れる場所（順番）が違うとかで数時間は溶かしました。。。

# 改善したいところ
スライダーの向きが全部同じなところ。現在の番号より大きい数字なら左→右、小さいなら右→左に画像が流れるようにしたい。(2022/5/22修正済)

レスポンシブ対応。スマホだといい感じでもPCだと画像が大きすぎる。(2022/5/22修正済)

prevボタンとnextボタンの実装。毎回clearボタンを押すのが煩雑なので、連番の画像をみたい場合はprevとnextを押せば参照できるようにしたい。

# URL
以下のURLから見ることができます。
https://amnis333.github.io/Monster-Hunter-Series-Gallary/
