---
toc: true
---

## ロケットエンジン

CORE ではロケットエンジンとしてハイブリッドエンジンを使用しています．

ロケットは主に固体エンジンと液体エンジンに分けられますが，ハイブリッドエンジンはその中間で酸化剤に液体又は気体，燃料に固体を使用するものです． 日本国内で多く使用されている燃料としては樹脂（シャンプー容器や自動車の車内装備などに使用されるような一般的なもの）や WAX（ロウソクのようなもの）があります．

また，酸化剤として液体酸素や気体酸素，亜酸化窒素(N2O)などがあります．これらは，単体では比較的安全なため管理がしやすいことから学生団体に多く使用されています．

多くの学生団体はカナダの Cesaroni Technology 社が販売する HyperTEK を使用しています．HyperTEK はそのエンジン性能によって I 型～ M 型に種類分けされているため用途に応じた使い分けが容易です．

近年では独自開発エンジンプロジェクトが進行中です．本プロジェクトは，2015 年の初代 K 型エンジン"CAMELLIA"から始まり，2020 年の酸化剤旋回流方式を採用した L 型エンジン"LIATRIS"まで，トライアンドエラーを重ねながら，多くの種類のエンジン開発に成功してきました．2020 年 10 月には弊団体初となる L 型相当のエンジン"LIATRIS.musica"の燃焼試験に成功しました．新たなエンジン開発にも取り組んでいるなど，独自開発エンジンプロジェクトはさらなる発展を続けています．

## バルブシステム

CORE では、自作ハイブリッドロケットエンジンの開発と並行して、酸化剤供給を制御するバルブシステムの高度化にも継続的に取り組んできました。

エンジンプロジェクト自体は 2013 年頃に構想が始まり、約 4 年間の研究開発を経て、2017 年 2 月の"CAMELLIA"で初の燃焼試験に成功。その後も "LARKSPUR X"（2018）、"LARKSPUR XP"（2019）と改良を重ね、能代宇宙イベントでは大型化した"LIATRIS.musica"（2020–2022）といった後継機の開発を続けてきました。

こうしたエンジン技術の発展と歩調を合わせ、バルブシステムの開発も進行しました。
2020 年に本格的なバルブ機構の独自開発を開始し、改良を重ねた結果、2022 年には FM モデル（フライトモデル）バルブシステムを用いた燃焼試験に成功。
この成果をもとに、2023 年の能代宇宙イベントでは、酸化剤供給に独自バルブシステムを採用した"LIATRIS.pasley"を搭載したロケットの打上げに成功しています。

さらに 2024 年には"LIATRIS.musica"、2025 年には自作 M 型エンジン"MIGRAILA.illis"の打上げにも成功し、バルブ技術とエンジン技術の両面で開発力を強化してきました。

現在は、従来方式を超える新方式バルブシステムを採用した次世代エンジンの開発を進めており、さらなる性能向上と高い信頼性の両立を目指しています。

## 電装・計器

ロケットの電気的動作を制御する機構です．

ロケットを減速落下させる為に分離機構を動作する．
どのように飛翔したのか把握する．
それらを正確に分析し実行するにはこのロケットの脳と言うべき共通計器が大切となります．

共通計器には主にマイクロコンピュータ，加速度・ジャイロセンサ，温度気圧高度センサ，GPS 受信機，無線通信機器，マイクロ SD カードなど使用します．
CORE では頂上付近で分離機構を作動させる適切な時を見計らうために離床からの時間と高度を分析し実行しています．
また加速度センサやフライトピンを使用し，発射判定をさせて地上で分離機構が動作させないようにしています．

飛翔状態の把握は飛翔中のセンサーの分析をマイクロ SD カードに保存し、ロケット回収後パソコンで読み込み、打ち上げメンバーの目で解析，反省を行います．

近年では，今まで既製品を用いていたハイブリッドロケットの打上用コントローラの自作化，ロケットの飛翔状態を計算・予測するシミュレータの製作も進めており，電装班が作業を行っています．

## 開放機構

開放機構は，ロケットが頂上付近でパラシュートを開き減速落下するための機構です．

CORE ではパラシュート開傘のためにロケットを開く方法として，
縦開放と横開放の２種類が主に用いられています．

ロケットを開く動力源としては主にばねや塩化ビニルシートの弾性力を利用します．
その弾性力によって開くロケットの扉のロックにはサーボモーターを使用します．
電装，計器が適切な時を見計らいサーボモーターを動作させることで頂上付近で開放扉が開き，
パラシュートが開傘します．

## 機体

ロケットの胴体部は持ち運びや組み立てが容易なように，モジュール式構造を主に用いています．

胴体素材には，GFRP（ガラス繊維強化プラスティック）や CFRP（カーボン繊維強化プラスティック）を主に使用します．
これらの素材は軽量で丈夫なことに加え，加工が容易という特徴があります．

またモジュール同士の接合をするカプラという部品にはアルミ合金，
ロケットの頭頂部であるノーズコーンは 3D プリンターで製作した物を使用しています．

## 過去のロケット

{{< load-photoswipe >}}

<details>

<summary><font size="5">2007年 8月 能代宇宙イベント</font></summary>

#### さざんか

{{< gallery >}}
{{<figure link="/img/gallery/body-sazanka.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2008年 8月 能代宇宙イベント</font></summary>

#### \[名称不明]

{{< gallery >}}
{{<figure link="/img/gallery/body-2008-08.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2009年 8月 能代宇宙イベント</font></summary>

#### ウルトラマン

{{< gallery >}}
{{<figure link="/img/gallery/body-2009-09-noshiro-ult.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2010年 8月 能代宇宙イベント</font></summary>

{{< gallery >}}
{{<figure link="/img/gallery/body-2010-noshiro-unnamed.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2011年 8月 能代宇宙イベント</font></summary>

{{< gallery >}}
{{<figure link="/img/gallery/body-redbull-01.jpg" thumb="-thumb" caption="機体①">}}
{{<figure link="/img/gallery/body-redbull-02.jpg" thumb="-thumb" caption="機体②">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2012年 3月 伊豆大島共同打上実験</font></summary>

#### トマトーク

{{< gallery >}}
{{<figure link="/img/gallery/people-toma.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

#### T-ロケット

{{< gallery >}}
{{<figure link="/img/gallery/body-T-rocket.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2012年 8月 能代宇宙イベント</font></summary>

#### キョロ(kyolo)

{{< gallery >}}
{{<figure link="/img/gallery/body-2013-noshiro-kyolo.jpg" thumb="-thumb" caption="機体">}}
{{<figure link="/img/gallery/body-kyolo.jpg" thumb="-thumb" caption="フェアリング">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2012年 11月 伊豆大島共同打上実験</font></summary>

#### GXP(Gold Experience)

{{< gallery >}}
{{<figure link="/img/gallery/body-GXP-01.jpg" thumb="-thumb" caption="機体①">}}
{{<figure link="/img/gallery/body-GXP-02.jpg" thumb="-thumb" caption="機体②">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2013年 3月 伊豆大島共同打上実験</font></summary>

#### SSP(スケスケパラダイス)

{{< gallery >}}
{{<figure link="/img/gallery/body-SSP.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2013年 8月 能代宇宙イベント</font></summary>

#### ミランダ

{{< gallery >}}
{{<figure link="/img/gallery/body-miranda.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2014年 3月 伊豆大島共同打上実験</font></summary>

#### ジョルジョナポリターノ

{{< gallery >}}
{{<figure link="/img/gallery/body-2014-oshima-jo.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2014年 8月 能代宇宙イベント</font></summary>

#### FreshG

{{< gallery >}}
{{<figure link="/img/gallery/body-flashg.png" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

#### VOLVOX

{{< gallery >}}
{{<figure link="/img/gallery/body-2014-noshiro-volvox.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2014年 11月 伊豆大島共同打上実験</font></summary>

#### VALTURE

{{< gallery >}}
{{<figure link="/img/gallery/body-2014-11-oshima-valture.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2015年 3月 伊豆大島共同打上実験</font></summary>

#### Helix 翼

{{< gallery >}}
{{<figure link="/img/gallery/body-helix_tsubasa.png" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

#### Vertex

{{< gallery >}}
{{<figure link="/img/gallery/body-vertex.png" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

#### Crazy thunder road

{{< gallery >}}
{{<figure link="/img/gallery/body-2015-03-oshima-crazy.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2015年 8月 能代宇宙イベント</font></summary>

#### CYCLOPS

{{< gallery >}}
{{<figure link="/img/gallery/body-cyclops.png" thumb="-thumb" caption="機体">}}
{{<figure link="/img/gallery/poster-2015-08-noshiro.jpg" thumb="-thumb" caption="ポスター">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2015年 11月 伊豆大島共同打上実験</font></summary>

#### Swift

{{< gallery >}}
{{<figure link="/img/gallery/body-swift.png" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2016年 3月 伊豆大島共同打上実験</font></summary>

#### SwiftX

{{< gallery >}}
{{<figure link="/img/gallery/body-swiftχ.png" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

#### すずな・すずしろ

- 機体名：すずしろ

  {{< gallery >}}
  {{<figure link="/img/gallery/logo-suzunasuzushiro.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-suzushiro.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2016年 8月 能代宇宙イベント</font></summary>

{{< gallery >}}
{{<figure link="/img/gallery/poster-2016-08-noshiro.jpg" thumb="-thumb" caption="ポスター">}}
{{< /gallery >}}

#### 電信柱

- 機体名：幸区小倉 1 丁目 7
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2016-08-noshiro-denshin.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-denshinbashira.png" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

#### Eyens

- 機体名：Eyens
  {{< gallery >}}
  {{<figure link="/img/gallery/body-eyens.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2016年 11月 伊豆大島共同打上実験</font></summary>

#### 古代飛翔体ンポロンポロ

{{< gallery >}}
{{<figure link="/img/gallery/poster-2016-11-oshima.jpg" thumb="-thumb" caption="ポスター">}}
{{<figure link="/img/gallery/body-nporo.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2017年 3月 伊豆大島共同打上実験</font></summary>

#### ムササビ

{{< gallery >}}
{{<figure link="/img/gallery/body-musasabi.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

#### チーム・ヌペリオル

- 機体名：Phase-IV

  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2017-03-oshima.jpg" thumb="-thumb" caption="機体ロゴ">}}
  {{<figure link="/img/gallery/body-phase-iv.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2017年 8月 能代宇宙イベント</font></summary>

#### ウラノメトリア

- 機体名：空飛ぶカメレオン

  {{< gallery >}}
  {{<figure link="/img/gallery/body-flykamereon.png" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

#### SEA CHICKEN

{{< gallery >}}
{{<figure link="/img/gallery/logo-2017-08-noshiro-sea-chicken.png" thumb="-thumb" caption="ミッションロゴ">}}
{{<figure link="/img/gallery/body-seachicken.jpg" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2017年 11月 伊豆大島共同打上実験</font></summary>

#### 17 式陸上高高度実証機(L チキ)

{{< gallery >}}
{{<figure link="/img/gallery/logo-Lchicken.jpg" thumb="-thumb" caption="ロゴ">}}
{{<figure link="/img/gallery/body-Lchiki.png" thumb="-thumb" caption="機体">}}
{{< /gallery >}}

</details>

<details>

<summary><font size="5">2018年 3月 伊豆大島共同打上実験</font></summary>

#### Team F.C.

- 機体名：FamilyChicken

  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2018-03-oshima-familychicken.png" thumb="-thumb" caption="機体ロゴ">}}
  {{<figure link="/img/gallery/body-familychicken.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

#### Team SkyLARK

{{<figure link="/img/gallery/logo-2018-03-oshima-vase.png" thumb="-thumb" caption="ミッションロゴ">}}

- 機体名：VASE

  {{< gallery >}}
  {{<figure link="/img/gallery/body-vase.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2018年 8月 能代宇宙イベント</font></summary>

#### CORE'S キッチン

- 機体名：きりたんぽ
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2018-08-noshiro-cores-kitchen.png" thumb="-thumb" caption="機体ロゴ">}}
  {{<figure link="/img/gallery/body-kiritanpo.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

#### Explore SEA

- 機体名：しらさぎ
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2018-08-noshiro-exploresea.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-shirasagi.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2019年 3月 伊豆大島共同打上実験</font></summary>

#### PATHFINDER

- 機体名：pf
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2019-03-oshima-pathfinder.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-pathfinder.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

#### 技術部誘導飛翔体開発課

- 機体名：⁽⁽ଘ( ˊᵕˋ )ଓ⁾⁾（ぐんぐにぃる）
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2019-03-tech.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-tech.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2019年 8月 能代宇宙イベント</font></summary>

#### ASAHI

- 機体名：Citrus
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2019-08-noshiro-asahi.jpg" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-asahi.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

#### Gemini QUEST

- 機体名：Ptarmigan
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2019-08-noshiro-gemini.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-geminiquest.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2019年 11月 伊豆大島共同打上実験</font></summary>

#### Stream Conductor

- 機体名：あまつかぜ
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-streamconductor.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-amatsukaze.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2020年 3月 伊豆大島共同打上実験</font></summary>

#### どんぶらこ

- 機体名：桃太郎
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2020-03-donburako.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-donburako.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

#### CRYSTAL PALACE

- 機体名：Piglet
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2020-03-oshima-crystal.jpg" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-Piglet.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2020年 11月 能代宇宙イベント</font></summary>

#### ミソラ工房

- 機体名：ひばり
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-2020-08-noshiro-misora.jpg" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-hibari.jpg" thumb="-thumb" caption="機体">}}
  {{<figure link="/img/gallery/poster-2020-11-noshiro.png" thumb="-thumb" caption="ポスター">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2021年 3月 御宿共同打上実験</font></summary>

#### Duo

{{<figure link="/img/gallery/logo-duo.jpg" thumb="-thumb" caption="ミッションロゴ">}}

- 機体名：ひばり 1
  {{< gallery >}}
  {{<figure link="/img/gallery/body_hibari1.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}
- 機体名：ひばり 2
  {{< gallery >}}
  {{<figure link="/img/gallery/body-hibari2.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2021年 11月 能代宇宙イベント</font></summary>

#### Duo

{{<figure link="/img/gallery/logo-duo.jpg" thumb="-thumb" caption="ミッションロゴ">}}

- 機体名：ひばり 2
  {{< gallery >}}
  {{<figure link="/img/gallery/body-hibari2-noshiro.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2022年 3月 伊豆大島共同打上実験</font></summary>

#### 新入生プロジェクト

- 機体名：CANVAS
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-CANVAS.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-CANVAS.png" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2022年 8月 能代宇宙イベント</font></summary>

#### Project-e

- 機体名：CORE #バルブ #ロケット #能代 #海打ち #高高度 #ロケッティア #点火点越しの私の世界 #ロケット好きと繋がりたい #CAN #リーフィング #rocket_hunter_jp #ババヘラ #自作エンジン #縦開放 #ロケットら部 #大学生 #きりたんぽ #fusion360 #OpenRocket #CFD #若気の至り #インカレ #3D プリンタ
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-pro-e.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-pro-e.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2022年 11月 伊豆大島共同打上実験</font></summary>

#### Violet

- 機体名：Violet
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-violet.jpg" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-violet.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2023年 3月 伊豆大島共同打上実験</font></summary>

#### はっぱ

- 機体名：れたす
  {{< gallery >}}
  {{<figure link="/img/gallery/body-lettuce.png" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

- 機体名：きゃべつ
  {{< gallery >}}
  {{<figure link="/img/gallery/body-cabbage.png" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2023年 8月 能代宇宙イベント</font></summary>

#### 萵苣

- 機体名：萵苣
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-chisha.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-chisha.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2023年 11月 伊豆大島共同打上実験</font></summary>

#### ダヴィンチ

- 機体名：Artist
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-artist.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-artist.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2024年 3月 伊豆大島共同打上実験</font></summary>

#### クロッフル

- 機体名：クロワッサン
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-croffle.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/body-croissant.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2024年 8月 能代宇宙イベント</font></summary>

#### 山岳

- 機体名：剣岳
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-turugidake.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/rocket-turugidake.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2024年 12月 伊豆大島共同打上実験</font></summary>

#### Citrus-ORangE

- 機体名：Orange Range
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-orange.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/rocket-orange.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>

<details>

<summary><font size="5">2025年 3月 伊豆大島共同打上実験</font></summary>

#### ゆき巳だいふく

- 機体名：だいふく
  {{< gallery >}}
  {{<figure link="/img/gallery/logo-yukimi.png" thumb="-thumb" caption="ミッションロゴ">}}
  {{<figure link="/img/gallery/rocket-yukimi.jpg" thumb="-thumb" caption="機体">}}
  {{< /gallery >}}

</details>
