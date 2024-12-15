
# Architourism4

■サービス概要

・日本の文化財の建造物を地図上で検索できるサービスです
    ・現在の位置情報から、近くの建造物を探すことができます
    ・ログインをすると、建造物のブックマーク、口コミの投稿・いいねができるようになります


■ このサービスへの思い・作りたい理由

・私は文化財の建造物や庭園を巡る旅を趣味としており、旅の際には市町村や文化財一覧のHPをネット検索で調査していたのですが、
「もう少し簡単に調べられるアプリケーションが欲しい」と感じたのがサービス作成のきっかけでした。

また、下記のような課題を感じ、それを改善できるサービス作成をすることを決めました。
	・文化財の建造物を一元管理しているようなサービスがあるものの、登録されていない建造物もあり、完全ではなかった。
	・正確に調べる場合、市町村ごとのHPで文化財一覧を調べなくてはならず、情報に辿り着くまでに手間がかかること。
	・建築愛好家で旅に出る方が多く存在するにも関わらず(建造物関連の投稿にいいねが200~600ついていることも珍しくない)、
		簡単に調べられるアプリケーションが存在しない。
	・利用者の生の声(口コミ)は、SNSやGoogle Mapのレビューなどを見に行かないと確認できない。
	
	
■ ユーザー層について

・主に国内の建築愛好家

	理由：文化財の建造物を目的に旅をする方々は、SNS上でも非常に多く見られます。
	また、簡単に情報を調べられるアプリケーションが存在しないため、建築愛好家にとって大きな需要があると感じました。



■サービスの利用イメージ
ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。

・マップ上で文化財の建造物がわかります。地名などから周辺の場所を検索することもできます。
これにより、簡単に文化財の建造物を調べることができます。

・口コミを検索できます。他のユーザーが投稿した口コミを閲覧できます。
これにより、訪問者の生の声が手に入ります。

・建造物のブックマークを登録できます。
これにより、旅の際に訪問する予定の建造物の確認が簡単になります。

・口コミにいいねをすることができます。
これにより、気になった口コミをマイページで確認することができます。

・建造物にいいねをすることができます。
これにより、建造物への人気ランキングを確認することができます。


■ ユーザーの獲得について

・Xでの告知を私がやっていこうと考えています。



■ サービスの差別化ポイント・推しポイント


差別化ポイントは他のユーザーが投稿した口コミを閲覧できることです。
訪問者の生の声(口コミ)は、SNSやGoogle Mapのレビューなどを見に行かないと確認できませんが、
このアプリケーション上では簡単に確認することができます。

似たようなサービス
https://bunkazai-map.colour-field.jp/


サービスの推しとなるポイントは、３つあります。
1つ目がマップを利用した確認のしやすさです。地図上でピンをたて、どこにあるか分かりやすくしています。
2つ目が口コミの投稿です。利用者の生の声(口コミ)をアプリケーション上で簡単に手に入れることができます。
3つ目がいいね機能です。建造物に関していいね機能を追加しランキング形式にすることにより、
人気のある建造物が分かるようになります。


■ 機能候補

【メイン機能(ユーザー登録不要)】
(1) 場所検索：現在地を取得し、周辺施設をマップ表示
(2) 一覧検索：「建築名」「地域」での施設情報の絞り込み
(3) 口コミ検索：「建築名」「ユーザー名」「投稿内容」で口コミ検索
(4) 建築情報表示：「建築名」 / 口コミ 表示


【サブ機能(ユーザー登録必要)】
(5) ブックマーク
(6) 口コミ投稿
(7) 口コミへのいいね
(8) マイページ：プロフィール編集 / 退会機能 / 「投稿した口コミ」「いいねした口コミ」表示
(9) 建造物へのいいね機能/いいねが多い順のランキング機能

【その他】
・ログイン機能



■ 機能の実装方針予定

〇場所検索
	・Google Map API導入
	・テーブル、カラム作成
	・データ追加
	・viewで、すべての投稿内容を一つの地図上で一覧表示、マーカーをクリックすると投稿の内容が出る、地図上で詳細ページまでのリンクを表示

