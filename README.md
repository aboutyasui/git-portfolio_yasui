# <仲介業者ランキング>

## サイト概要・・・材料を取り扱うメーカーと仲介業者のレビューサイト
### サイトテーマ
ユーザー（材料を購入したいが購入方法が分からない状態の人）向けのレビューサイト<br>
工事やDIYなどに必要な材料（ユーザーが欲しいと思っている材料）の情報をもとに メーカー＆仲介業者の情報を表示＆レビューできるサイトです

### テーマを選んだ理由
前職が施工管理で、仲介業者を選ぶ際に業者ごとのレビューサイトがないことに不便さを感じたため。<br>
まず工事（新築や改修など種類は様々あります）が始まる前に設計書（建物の大体の形や設備の位置等が記された図面）と施工要領書（工事を行うにあったて、守るべきルールがまとめられた書類　※例えば、高所作業は原則禁止とするや使っていい材料と悪い材料が明記されていたりする）を建築会社からもらいます。それをもとに必要な工事や材料を検討する期間が３～５か月ほどあります。（工事現場の規模によっては異なります）５か月も期間があれば余裕と感じる方がいるかもしれませんが、実際はそうではありません。使う材料を検討しつつ工事をするために必要な図面（施工図※前の工事現場では二人で約１００枚作成しました）を作成し仲介業者との値段交渉をするなど、仕事の種類や量が多いことから３～５か月の期間があっても足りないと思ってしまうものでした。また業者と交渉が成立し工事が始まったとしても、問題はあります。工事中に当初予定していた材料が使えない場面（設置場所に他設備の配管や配線、鉄骨関係などが干渉してしまい、予定していた物では工事がでできないと判断されるケースが主です。）やそもそも材料が調達できない場面（前の現場では、半導体不足によって照明器具や空調設備などが遅れたときもありました）などに当たってしまった場合、どの業者に頼めばいいのか分からない状態に陥ります。<br>
困っている中で「ユーザー目線で作られた機能」や「仕事の効率を上げるようなサイト」があれば誰でも使いたくなると私は考えました。<br>
また昨今の建築業界ではＩＴ化に力を入れている企業が増えてきています。（例えば3D図面作成用のソフト開発や測定アプリとCADソフトとの連携を取る開発など）主な理由としては、やはり仕事量から来る残業量や見えないところでのトラブルを回避するため、など様々あります。<br>
このような理由から今回のテーマを選びました。

### ターゲットユーザ
施工管理会社の社員<br>
DIYに興味がある人

### 主な利用シーン

#### 利用者が施工関係のユーザーの場合<br>
仲介業者を選ぶとき<br>
メーカーや仲介業者の情報を知りたいとき(例：過去の対応例などを投稿＆表示することで、閲覧側は業者の情報をしることができます)<br>
急遽発注しないといけなくなったとき(設計当初予定していた材料以外でないと、工事ができないと気付いたとき)<br>
業者をレビューしたいとき

#### 利用者が一般人ユーザー（趣味がDIYの人など）の場合<br>
自分がしたい工事に関係のある材料を知りたい時<br>
またそれを扱っているメーカーやお店情報を見たい時

## 設計書
機能リスト　：　https://docs.google.com/spreadsheets/d/169sUv5-aiWkSHcu4Xn1P-lk_Jo7L7kybbhsTbWX_T2o/edit?usp=sharing<br>
UI Flows　:　https://drive.google.com/file/d/1-ZXn-XeKC6RyWOoiAYNNJ4SQ90AybkCU/view?usp=sharing<br>
ワイヤーフレーム(顧客側)　:　https://drive.google.com/file/d/1w96Wzyu9xvIFbe89wLBXIEIUPt3Orn0W/view?usp=sharing <br>
ワイヤーフレーム(店側)　:　https://drive.google.com/file/d/15q7ovRD7NeVsxrp9EGf66NiXskXz25JE/view?usp=sharing <br>
ワイヤーフレーム(管理側)　:　https://drive.google.com/file/d/1ba1oOYvOab6hEtVzkfi3JbG_f7-ufSad/view?usp=sharing <br>
ER図　：　 https://drive.google.com/file/d/1JWqBujjbv7MSwixqDb08E_EENZIPUi9X/view?usp=sharing <br>
テーブル定義書　：　https://docs.google.com/spreadsheets/d/1c-WF1jaam5wLdN3UlhDs-8wC1KBm5aauUC3O0b_sddI/edit?usp=sharing<br>
アプリケーション詳細設計書　：　https://docs.google.com/spreadsheets/d/1kIPcvTtgXXwiE8PeX7FQXlyd_lh7ow-YfJ1iphynO7A/edit?usp=sharing<br>
   
## 開発環境
- OS：Linux(CentOS)
- 言語：HTML,CSS,JavaScript,Ruby,SQL
- フレームワーク：Ruby on Rails
- JSライブラリ：jQuery
- IDE：Cloud9

## 使用素材
- フリー素材の画像（いらすとや等）
