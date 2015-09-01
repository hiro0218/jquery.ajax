jquery.ajax
====
jQueryのAjax関連の機能だけ使えるようにしたもの。

## 説明
jQueryのカスタムビルドを利用して、ajax以外のモジュールを削除している。

利用できるのは以下のみ。
* ajax
* ajax/xhr
* ajax/script
* ajax/jsonp


### 実行するタスク

		grunt custom:-css,-deprecated,-dimensions,-effects,-event,-event/alias,-offset,-wrap,-core/ready,-deferred,-exports/global,-exports/amd,-sizzle compare_size
