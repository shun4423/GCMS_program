# Gaschromatography_program
このプログラムはGCMS QP2010SE（島津製作所）で分析し、GCMSsolutionで出力したデータを前提にしています。

This program is based on the data analyzed by GCMS QP2010SE (Shimadzu Corporation) and output by GCMS solution.



# DEMO
想定しているファイルとして、サンプルデータを付けていますので、一度ご確認ください。

Sample data is attached as an assumed file, so please check it once.

# Features
１.もっとも高いSIから５〜６こ残し、あとは削除します。これを各ピークで行います。

1. Leave 5 to 6 from the highest SI and delete the rest. Do this at each peak.

２.IFERROR関数を入力し、面積を書き込みます。

2. Enter the IFERROR function and write the area.

3.各ファイルを一つに並べます。

3. Arrange each file in one.

４.できるだけ近いRTタイムを並列させます。

Parallel RT times as close as possible.



# Requirement
anacondaを前提にしています。

It is premised on anaconda version 1.7.2(Python 3.8.5).

VOCをデスクトップに置き、VOC内に「0.textから変換済み」、「1.絞り込み済み」、「2.まとめ」というフォルダーを作成してください。

Place the VOC on the desktop and create folders called "0.Converted _file", "1.filtered", and "2.summary" inside the VOC.

# Setting
基本的にはパス名と取得したいピーク数を入力するだけです。

Basically, You should change the path name and the number of peaks you want to get.

# Note


# Author

* 伏見駿亮(Fushimi Shunsuke)
* Kyoto University
* f.shunsuke0402@gmail.com

