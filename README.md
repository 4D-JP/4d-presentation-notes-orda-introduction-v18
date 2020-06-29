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
* 今後の言語拡張は原則的にORDA/オブジェクト指向プログラミングが対象
  * [ZIPアーカイブ](https://doc.4d.com/4Dv18/4D/18/About-ZIP-Archives.300-4679649.ja.html)
  * [メール](https://doc.4d.com/4Dv18/4D/18/Mail.302-4504492.ja.html)
  * [ファイルシステム](https://doc.4d.com/4Dv18/4D/18/File-and-folder-object-pathnames.300-4506091.ja.html)
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

### 教材

v16以降の新機能は，ドキュメントに加え，プロダクトオーナー\*によるブログ記事およびサンプルデータベースで習得することができます。

\* 仕様の策定に携わり，制作進行を監修する開発チームのメンバー

#### オブジェクト型

* **[New Object](https://github.com/4D-JP/HDI/releases/download/16r3/HDI_NewObject.zip)** オブジェクトを初期化するための新コマンドNew objectが追加されました。従来のコードと新コマンドを使ったコードを比較します。

* **[オブジェクトとピクチャー属性](https://github.com/4D-JP/HDI/releases/download/16r4/HDI_PictureObjectAttribute.zip)** オブジェクトの属性値にピクチャーを設定できるようになりました。

#### オブジェクト記法/コレクション型

* [オブジェクト記法](https://github.com/4D-JP/HDI/releases/download/16r4/HDI_ObjectNotationDatasource.zip)
* [コレクション](https://github.com/4D-JP/HDI/releases/download/16r4/HDI_UseCollections.zip)
* [コレクションの操作](https://github.com/4D-JP/HDI/releases/download/16r6/HDI_Collection_Members.zip)
* [コレクションのクエリ](https://github.com/4D-JP/HDI/releases/download/16r6/HDI_Collection_Query.zip)
* [新しい For each…End for each ループ](https://github.com/4D-JP/HDI/releases/download/17/HDI_ForEach.zip)

#### データストア/ORDA

* [ORDA: エンティティの新規作成・更新・削除](https://github.com/4D-JP/HDI/releases/download/17/HDI_ORDA_CRUD.zip)
* [ORDA: クエリ](https://github.com/4D-JP/HDI/releases/download/17/HDI_ORDA_Query.zip)
* [ORDA: エンティティセレクションとカレントセレクションの相互変換](https://github.com/4D-JP/HDI/releases/download/17/HDI_ORDA_Current_Selection_Bridge.zip)
* [ORDA: エンティティとオブジェクトの相互変換](https://github.com/4D-JP/HDI/releases/download/17/HDI_ORDA_Objects_And_Collections.zip)
* [ORDA: 悲観的(ペシミスティック)ロック](https://github.com/4D-JP/HDI/releases/download/17/HDI_ORDA_Pessimistic_Lock.zip)
* [ORDA: 楽観的(オプティミスティック)ロック](https://github.com/4D-JP/HDI/releases/download/17/HDI_ORDA_Optimistic_Lock.zip)
* [ORDA: エンティティとエンティティセレクションの操作](https://github.com/4D-JP/HDI/releases/download/17/HDI_ORDA_Handling_Entities.zip)
* [ORDA: エンティティセレクションの論理演算](https://github.com/4D-JP/HDI/releases/download/17/HDI_ORDA_Logical_Operators.zip)
* [ORDA: エンティティセレクションの統計情報](https://github.com/4D-JP/HDI/releases/download/17/HDI_ORDA_Statistics.zip)

#### データストア/ORDA

* [ORDA: フォーミュラを使った並べ替え](https://github.com/4D-JP/HDI/releases/download/17r6/HDI_Order_ByFormula.zip)
* [ORDA: フォーミュラを使ったクエリ](https://github.com/4D-JP/HDI/releases/download/17r6/HDI_Query_ByFormula.zip)
* [ORDA: 新機能を活用した汎用コード](https://github.com/4D-JP/HDI/releases/download/17r5/ORDA_Dynamic_Code.zip)
* [ORDA: 動的なストラクチャー情報の取得](https://github.com/4D-JP/HDI/releases/download/17r5/HDI_Database_Info.zip)
* [ORDA: 属性パスのプレースホルダーを使ったクエリ](https://github.com/4D-JP/HDI/releases/download/17r5/HDI_PlaceHolders_AttributePaths.zip)
* [ORDA: 値の命名プレースホルダーを使ったクエリ](https://github.com/4D-JP/HDI/releases/download/17r5/HDI_PlaceHolders_Values.zip)

#### フォーミュラ 

* **[メソッドのオブジェクト化](https://github.com/4D-JP/HDI/releases/download/17r3/HDI_NewFormula.zip)** New formulaコマンドを使って，メソッドをオブジェクト化することができます。オブジェクト化されたメソッドは引数として受け渡すことができます。

#### リモートデータストア

* **[ORDA: リモートデータストア (サンプルアプリケーション)](https://github.com/4D-JP/HDI/releases/download/18/TIP_Remote_Datastore.zip)** リモートデータストアーのサンプルアプリケーションです。ローカルデータベースでは直近のデータだけを保存し，過去データはすべて外部データベースにて管理します。サンプルには，ローカルデータベース (TIP_Remote_Datastore_Client) とリモートデータベース (TIP_Remote_Datastore_Server) が含まれています。

* **[ORDA: リモートデータストア](https://github.com/4D-JP/HDI/releases/download/18/HDI_Remote_Datastore.zip)** 新しく追加された Open datastore コマンドを使って，RESTリソースとして公開されている外部の 4D データベースをリモートデータストアの形で取得し，操作することができます。
