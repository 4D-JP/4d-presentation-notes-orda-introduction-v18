# 4d-presentation-notes-orda-introduction-v18

### ORDA（Object Relational Data Access）とは？

* **バックエンド**（データベース）と**フロントエンド**（デスクトップ/Web/モバイル）を融合する次世代のアプリケーション開発手法
* 全面的に**オブジェクト指向プログラミング**を使用
* バージョン: **v17**以降

### ORDAのメリットは？

* コンパイルモードで**スレッドセーフ**
* モダンなプログラミング言語（JavaScriptに類似） - クラス・オブジェクト・フォーミュラ（関数ポインター）・バリアント型
  * ソースコードのモジュール化・類型化・整理を促進
  * メンテナンス・デバッグ・リファクタリングが容易
  * 他言語システムとの**連携**が容易（JSON/HTTP/REST）
* 今後の新機能追加は原則的にORDAが対象  
* 従来ランゲージとの併用が可能

### ORDAのデメリットは？

* 新言語の習得（モダンなプログラミング言語に慣れていない場合）

### ORDAを習得するために

ORDAでは，データベース・テーブル・カレントレコード・カレントセレクションといった従来の概念をすべてオブジェクトの**クラス**をみなします。レコードの検索・並び替え・読み書きといった処理は，すべて**オブジェクト記法**で記述します。ORDAを始める前に，まずオブジェクト型・オブジェクト記法（**コレクション型**を含む）の扱いに慣れておくと良いでしょう。オブジェクト指向プログラミングの長所を最大限に引き出すためには，**フォーミュラ**についても知っておく必要があります。

* [オブジェクト型](https://doc.4d.com/4Dv18/4D/18/Structure-of-4D-language-objects.300-4505646.ja.html)（v14）
* [オブジェクト記法/コレクション型](https://doc.4d.com/4Dv18/4D/18/Using-object-notation.300-4505639.ja.html)（v17）
* [データストア/ORDA](https://doc.4d.com/4Dv18/4D/18/Datastores.300-4575757.ja.html) (v17)
* [フォーミュラ](https://doc.4d.com/4Dv18/4D/18/Formula.301-4505749.ja.html) (v18)

---

* [Open datastore()](https://doc.4d.com/4Dv18/4D/18/Open-datastore.301-4675616.ja.html)

### サンプルデータベース

#### [v18](https://4d-jp.github.io/hdi/#v18)

* **[ORDA: リモートデータストアー (サンプルアプリケーション)](https://github.com/4D-JP/HDI/releases/download/18/TIP_Remote_Datastore.zip)** リモートデータストアーのサンプルアプリケーションです。ローカルデータベースでは直近のデータだけを保存し、過去データはすべて外部データベースにて管理します。サンプルには、ローカルデータベース (TIP_Remote_Datastore_Client) とリモートデータベース (TIP_Remote_Datastore_Server) が含まれています。

* **[ORDA: リモートデータストア](https://github.com/4D-JP/HDI/releases/download/18/HDI_Remote_Datastore.zip)** 新しく追加された Open datastore コマンドを使って、RESTリソースとして公開されている外部の 4D データベースをリモートデータストアの形で取得し、操作することができます。
