BXjaprnind パッケージ
=====================

LaTeX: 段落頭の開き括弧類の位置の自動調整

段落冒頭および強制改行後の行頭における開き括弧の位置をユーザが予め
設定した値に自動的に調整する。

### 対応環境

  * TeX フォーマット： LaTeX
  * TeX エンジン： pTeX／upTeX／LuaTeX（＋LuaTeX-ja）
  * 依存パッケージ：
      - bxtoolbox（[BXbase] バンドル）

[BXbase]: https://www.ctan.org/pkg/bxbase

### インストール

TDS 1.1 に準拠するシステムの場合、以下のようにファイルを移動する：

  - `*.sty`  →  $TEXMF/tex/latex/BXjaprnind

この後必要に応じて mktexlsr を実行する。

### ライセンス

本パッケージは MIT ライセンスの下で配布される。


bxjaprnind パッケージ ― 本体
-----------------------------

詳細は解説文書 bxjaprnind.pdf を参照。


更新履歴
--------

  * Version 0.4a 〈2021/06/18〉
      - 手違いで `dialogueparenindentamount` の定義が欠落していたような
        ので修正。
  * Version 0.4  〈2021/06/06〉
      - バグ修正。
      - `force` オプションを追加。
  * Version 0.3b 〈2017/09/12〉
      - source special 挿入への対策。
  * Version 0.3a 〈2013/05/05〉
      - 会話用の特別な鉤括弧の処理を追加した。
  * Version 0.3  〈2013/04/29〉
      - everyhook パッケージへの依存を無くした。
  * Version 0.2  〈2012/05/14〉
      - 最初の公開版。

--------------------
Takayuki YATO (aka. "ZR")  
https://github.com/zr-tex8r
