# 環境構築
1. jreをインストール
1. Graphvizをインストール(Windowsの場合、msiが存在する。)
1. VSCodeでPlantUMLプラグインをインストール

# PDF出力設定
1. 以下を参考に必要なファイルをダウンロードする。  
https://plantuml.com/ja/pdf  
http://beta.plantuml.net/batikAndFop.zip  
1. zipファイルを展開し、plantuml.jarと同じフォルダに配置する。

## VSCodeの拡張機能としてPlantUMLをインストールした場合のplantuml.jarの場所(Ubuntu)
ユーザーホームディレクトリ（~）内の.vscode/extensionsフォルダに移動します。  
.vscode/extensionsフォルダ内で、jebbs.plantuml-{バージョン番号}という名前のフォルダを探します。このフォルダは、PlantUML拡張機能のインストール時に自動的に作成されます。  
jebbs.plantuml-{バージョン番号}フォルダに入ると、その中にplantuml.jarファイルが見つかるはずです。  


## VSCodeの拡張機能としてPlantUMLをインストールした場合のplantuml.jarの場所(Windows)
ユーザーホームディレクトリ（通常はC:\Users\ユーザー名）に移動します。  
.vscode\extensionsフォルダに移動します。  
jebbs.plantuml-{バージョン番号}という名前のフォルダを探します。このフォルダは、PlantUML拡張機能のインストール時に自動的に作成されます。  
jebbs.plantuml-{バージョン番号}フォルダに入ると、その中にplantuml.jarファイルが見つかるはずです。  
