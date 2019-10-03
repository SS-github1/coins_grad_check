# Coinsの卒業要件に達しているかをチェック！


## abst
- 2016年入学の情報科学類生の卒業を判定をします
- ジョークプログラムです．このプログラムの出力を真に受けた結果，卒業できなかったとしても責任は取れません
- 「ある単位Aを枠1と枠2のどちらにも使用できる」状況で雑に割り振っています．そのため，「卒業できません」の判定を受けても組み合わせを変えれば卒業できる場合がままあります．


## usage
- python main.py [csvファイル名] [専攻] で実行
	- csvファイル : twinsにログインして「履修タブ」 -> 「科目区分参照・変更」のページからダウンロード
	- 専攻 : ソフトウェアサイエンスは2, 情報システムは3, 知能情報メディアは4を指定
- 例えば，csvを"data.csv"で保存した知能情報メディア専攻の人は $ python main.py data.csv 4
