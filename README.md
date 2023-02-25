# pointnet_inspection

PointNetを使用して点群データの分類を行う。
正常な球体、大きさの異なる球体、凹みのある球体、その他に分類する

※精度が悪いので別のモデル、法線や体積など特徴量を追加することを今後検討


用途
・外観検査
→ 写真では判別できない凹みや傷などを検出（暗い場所でも検出可）
→機械学習によってさまざまな検査に応用可能
→ 大きさ、体積を計算可能
![image](https://user-images.githubusercontent.com/93971055/221352463-7e3216af-38c0-4bb3-88ba-a7aef296dc5d.png)



# 処理の概要

・点群の学習データを作成
・PointNetを定義し、学習
・テストデータで検証



# Requirement

Pytorch

open3d

hdbscan

k3d

pyransac


