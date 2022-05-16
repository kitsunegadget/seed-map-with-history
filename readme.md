# Random Seed of History on Biome Finder

Biome Finder のランダムシードボタンに、履歴ボタンを追加する拡張機能です。
おまけでブックマーク機能も付いています。

---

## ランダムボタンの履歴機能

通常のブラウザの戻る・進むボタンのように扱えます。
よって、Next側の履歴がある状態でランダムボタンを押してシードを生成すると、先の履歴は削除されます。

拡張機能を削除しない限り、履歴は保持されます。

履歴を削除したい場合は、削除ボタンを押します。

履歴が存在し、ページを離れても同じシードページに戻る場合は、履歴をその場所から再開できます。

どの入力にも関わらず、最後に見たシードから再開されるのは Biome Finder 側の仕様です。この場合、最初に読み込まれる履歴に無いシードは新たに履歴に保存しません。
クッキーが無いためにハッシュが存在しない場合も同様です。
このとき前の履歴が残っている場合は、最後の位置から1つ進んでいますが、ボタンでシードを追加すると最初のページのシードは消去されます。

それぞれのボタンを長押しすると、リストを表示できます。

今のところ、**ランダムボタンから生成されたシードしか履歴に保存しません。**
仕様上、入力数値の変更が確定されるとページハッシュが変更されて、意図しない多くの履歴を生成してしまうためです。おそらく Biome Finder が通常のブラウザ履歴を遷移せずに上書きしているのは、そのためと考えています。

ランダムシード以外を残したい場合は、代わりに下記のブックマーク機能を使うことができます。

## ブックマーク機能
  
ブックマーク機能は、表示しているシードを☆ボタンでブックマークします。
表示したシードで★になっていればブックマークに入っています。
削除したい場合は、同じシードを表示してから、★ボタンを再度押すことで消去することができます。こちらも拡張機能を削除しない限り、データは残ります。

ボタン長押しでリストを表示します。
いつでもお気に入りシードをすぐに選択できるでしょう！

ブックマークリストからシードを選択すると、現在の位置から新しいページとして履歴に残ります。
前述と同じく履歴に次ページがある場合、それらは削除されます。
