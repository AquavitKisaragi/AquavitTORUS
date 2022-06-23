# AquavitTORUS
AquavitOMERと連携してテキストに対応した音声データの出力を行う。

現在のところ、以下の2種類の音声合成ソフトのみ対応
VOICEVOX様　https://voicevox.hiroshiba.jp/
　インストール及びサーバが起動していることが音声合成の条件です。
AquesTalk様　https://www.a-quest.com/index.html
　各種DLLを配置していることが音声再生の条件です。


プロジェクトのタイトル
	AquavitTORUS
	
免責事項
	いかなる理由があってもこのソフトを利用して受けた損害や被害などの保証は行いません。
	利用する場合は自己責任でお願い致します。

プロジェクトの概要説明
	テキスト文章をもとに音声ファイルを出力します。
	またテキストの表示時間なども調整できます。



必要条件
	windows10以上（だと思うよ！）

使用言語、環境、テクノロジー
	C#（一部Python）

使い方
	暫定版なので動画などを見てどのような機能なのか確認をお願い致します。


インストール方法
  ZIPから展開して好きな場所に保存してください。


  その後必要に応じて以下のことを行ってください。
  ・VOICEVOXで録音再生する場合はVOICEVOXのインストール及び起動していることが条件です。
  　https://voicevox.hiroshiba.jp/


  ・AquesTalkで録音再生する場合はAquesTalk10とAqKanji2Koe-A Win両方のDLLが必要です。
  　https://www.a-quest.com/download.html
		上記のサイトからAquesTalk10及びAqKanji2Koe-A Winをダウンロードして展開した後に以下の通りに保存してください。
		本体のフォルダ直下
  　	-AquesTalk.dll　	#ダウンロードしたファイルのaqtk10_win_110\aqtk10_win\lib64　配下
		-AquesTalk.lib　	#ダウンロードしたファイルのaqtk10_win_110\aqtk10_win\lib64　配下

		-aq_dic				#aqk2k_win_412\aqk2k_win\配下（フォルダごと置く）
		-AqKanji2Koe.dll	#\aqk2k_win_412\aqk2k_win\lib64　配下
		-AqKanji2Koe.lib	#\aqk2k_win_412\aqk2k_win\lib64　配下
		-AqUsrDic.dll		#\aqk2k_win_412\aqk2k_win\lib64　配下
		-AqUsrDic.lib		#\aqk2k_win_412\aqk2k_win\lib64　配下

ライセンス情報
	アクアビット・キサラギ
	Twitter（@TMarunoko）
	

	録音及び再生に必要なソフトウェア
	AquesTalk10及びAqKanji2Koe（株式会社アクエスト様）
	https://www.a-quest.com/download.html

	VOICEVOX様
	https://voicevox.hiroshiba.jp/

	出力されるテキストに適した動画編集ソフト
	http://spring-fragrance.mints.ne.jp/aviutl/

今後の計画
	・株式会社アクエスト様のライセンスキーの登録方法の検討（ライセンス流出の被害をなくせるか検討中）
	