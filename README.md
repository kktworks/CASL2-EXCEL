# CASL2-EXCEL
基本情報技術者試験で出題されるアセンブラ言語(CASL2)をExcel上で動かすシミュレータ。
Excelがインストールされていれば
- CASL2で書かれたプログラムの入力→文法チェック → 実行
- 実行時トレース(ON/OFF切り替え可能)
	- 次に実行する行をソース上で表示
	- GR,PR,SRやOSZフラグの内容表示
	- プログラムが参照/変更したレジスタ、フラグ、メモリ、スタックに色を付けて表示
- デバッグ
	- ブレークポイントを設定し、その行まで実行
	- 1ステップ実行
	- step in/step over

などが行えます。
 
# DEMO
 
"hoge"の魅力が直感的に伝えわるデモ動画や図解を載せる
 
# 特長
CASL2初心者が迷う

> これはメモリの内容をGRへロードしてるの？それともアドレス?

を支援。そのほか１ステップ実行しながらどのレジスタやメモリが読み書きされているのか一目瞭然です。
 
# 前提ソフト
 
* Microsoft Excel (バージョン2112で動作を確認)

# 注意点
本プログラムは以下で出題されたコードで動作の確認を行いました。

* 令和元年度 秋季午後 問12(1),(2),(3)
* 平成31年度 春季午後 問12(1)
* 平成30年度 秋季午後 問12(1)
* 平成30年度 春季午後 問12(1),(2),(3)
* 平成29年度 秋季午後 問12(1),(2),(3)
* 平成29年度 春季午後 問12(1),(2)
* 平成27年度 秋季午後 問12(1)
* 平成27年度 春季午後 問12(1),(2)
* 平成26年度 秋季午後 問12(1),(3)

# Author
* 作成者：菊田英明
* E-mail：kktworks@google.com
 
# CASL2-EXCELについて

【はじめに】
* CASL2-EXCEL（以下，本ソフトウェアという）は，上記作成者（以下，作者という）が個人のCASL2学習を支援する目的で作成したソフトウェアです。
* 本ソフトウェアは作者の権利として日本国著作権法で保護されており，本ソフトウェア及び複製の所有権は作者が保有しています。
* 本ソフトウェアは販売するものではなく，Githubからダウンロードした利用者に対して，次の使用条件に基づいてのみ使用することを許諾するものです。

【使用条件】
+ 作者は，正しくインストールされた本ソフトウェアが正しく動作することを確認していますが，本ソフトウェアのインストール及び取り扱いは，慎重に行ってください。利用者が使用する環境によっては何らかの障害を起こす可能性もあります。本ソフトウェアをインストールするハードディスクは事前にバックアップを取った上で使用してください。

+ 本ソフトウェアに関する著作権は作者に帰属します。本ソフトウェアはGithubからダウンロードすることで，非独占的に使用する権利のみを無償で得ることとします。

+ 本ソフトウェアは，本ソフトウェアをダウンロードしたコンピュータにおいて個人でCASL2を学習する目的のみの使用を許諾します。その一部あるいは全体をインターネット等ネットワークで接続されたコンピュータ等への配布，他人への譲渡，販売，複製，貸与，頒布等の上記目的以外のために使用すること，またこれらに基づいて二次的著作物を創作することは一切禁止します。

+ 作者は本ソフトウェアを無償で提供することに鑑み，本ソフトウェアの使用中に起こり得るあらゆる障害，損害，金銭的損失，その他いかなる事態に対しても，責任を一切負いません。

+ 作者はソフトウェアについて上記「注意点」で記載した以上の保証を一切行いません。利用者は自身の責任と負担のもとに使用することとします。

# サポート・問い合わせ

質問、要望、その他何かありましたら、以下のどちらかでお願いします。
* Issueを作成しAssigneeとする
* kktworks@gmail.comへメール
