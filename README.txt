# AquavitTORUS
AquavitOMERと連携してテキストに対応した複数の音声合成ソフトと連携し出力を行う。


プロジェクトのタイトル
	AquavitTORUS2
	
免責事項
	いかなる理由があってもこのソフトを利用して受けた損害や被害などの保証は行いません。
	利用する場合は自己責任でお願い致します。

プロジェクトの概要説明
	テキスト文章をもとに音声ファイルを出力します。
	またテキストの表示時間なども調整できます。



必要条件
	windows10以上（だと思うよ！）

使用言語、環境、テクノロジー
	C#6.0（一部.NET Framework ）

使い方
	暫定版なので動画などを見てどのような機能なのか確認をお願い致します。


インストール方法
  ZIPから展開して好きな場所に保存してください。


  その後必要に応じて以下のことを行ってください。
  ・VOICEVOXで録音再生する場合はVOICEVOXのインストール及び起動していることが条件です。
  　https://voicevox.hiroshiba.jp/

　・A.I.VOICEで録音するためにはA.I.VOICEのインストール及び起動していることが条件です。
　　https://aivoice.jp/

  ・AquesTalkで録音再生する場合はAquesTalk10とAqKanji2Koe-A Win両方のDLLが必要です。
  　https://www.a-quest.com/download.html
		上記のサイトからAquesTalk10及びAqKanji2Koe-A Winをダウンロードして展開した後に以下の通りに保存してください。
		.\VoiceLink\AquestDLL 配下
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
	
	A.I.VOICE様
	https://aivoice.jp/

	VOICEVOX様
	https://voicevox.hiroshiba.jp/

	AquesTalk10及びAqKanji2Koe（株式会社アクエスト様）
	https://www.a-quest.com/download.html

	


	出力されるテキストに適した動画編集ソフト
	http://spring-fragrance.mints.ne.jp/aviutl/

今後の計画
	・その他の音声連携ソフトに連携可能化検討中
	