### マテリアル デザインのガイドライン（日本語版）を読んで振り返り

#### 2017/10/12
#### iwaisako.y
---
### material_design.pdf

---
### マテリアルの動き
<br>
### ユーザーによる操作は、通常は Z 軸に沿った動きとして表現します。
[動画](http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B6Okdz75tqQsQW1HYnpicTVySG8/whatismaterial-materialprop-movementmaterial-Material_Response_xhdpi_003.mp4)


---
### motion.pdf

---
### マテリアルの動き方
<br>
### モバイル端末では、大きなアニメーションの継続時間は 300～400 ms、小さなアニメーションでは 150～200 ms になります。

---
### マテリアルの動き方
<br>
### 要素がビューに遷移するとき、要素とその周りの要素は、互いの関係を示すような動きになっています。

[動画1](http://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B14F_FSUCc01TFFreDdlSVp3dGc/Aware_01_Choreo-v2.mp4)　[動画2](http://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B14F_FSUCc01RFdjQWE4ZXBseWM/Aware_02_MoveAway-v2.mp4)

---
### 優れた遷移の特徴
<br>
### 遷移はわかりやすく、シンプルで、まとまりのあるものにします。一度に多くの動きを取り入れないでください。

[適切](http://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B14F_FSUCc01NDkzU2FaYlFHMXM/GoodTransition_ClearDo-v3.mp4)　[不適切](http://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B14F_FSUCc01VzRvLWJDTEE4WXM/GoodTransition_ClearDont-v3.mp4)


---
### モーションの意義
<br>
### 適切の動画のように、遷移中、ユーザーは次のビューへと導かれます。サーフェスは階層がわかるように変形しています。読み込みは背後で行われているため、遅れをあまり感じさせません。

[適切](http://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B14F_FSUCc01Um1wdzhBR1ZuYVE/ImplicationsDo-v2.mp4)　[不適切](http://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B14F_FSUCc01anJjQkt4QS1GRzQ/ImplicationsDont-v2.mp4)


---
### モーションの意義
<br>

### 適切の動画のように、遷移中、ユーザーは次のビューへと導かれます。サーフェスは階層がわかるように変形しています。読み込みは背後で行われているため、遅れをあまり感じさせません。

[適切](http://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B14F_FSUCc01Um1wdzhBR1ZuYVE/ImplicationsDo-v2.mp4)　[不適切](http://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B14F_FSUCc01anJjQkt4QS1GRzQ/ImplicationsDont-v2.mp4)

---
### 継続時間とイージング
<br>

### アニメーションの継続時間が400msを超えると遅いと思われる可能性がある。距離や端末の大きさにより継続時間は変わる。

[参考URL](https://qiita.com/takahirom/items/61976bdebe2c18dfce82)


---
### コレオグラフィ（振付？）
<br>
### レイアウトを意識する。遷移中にまだ読み込まれていない要素のためのスペースを確保しておき、要素が完全に読み込まれたら、その場所にスムーズに表示します。

[動画](http://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B14F_FSUCc01TGhVWlZaam5CNVU/Continuity_06_LayoutAwareDo_v2.mp4

)

