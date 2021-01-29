
# TestCase-OutLine


# 1. AIアプリに適した解像度・ビットレート・fps
<details open>
    <summary>解像度検証</summary>

* 対象カメラの最大解像度を超えていないか。
* エンジン処理が対応できる解像度であるか。

</details>

<details open>
    <summary>ビットレート</summary>

* ネットワーク回線や、機器にかかる負荷がオバーしていないか。
</details>

<details open>
    <summary>fps</summary>

* エンジンが対応できるfpsの設定か。

</details>

# 2. アプリ性能
## ・ 精度・照度
<details open>
    <summary>照度(Lux)</summary>

* エンジンが許容精度で認識できている照度が設定されているか。

</details>

<details open>
    <summary>検出精度 (%)</summary>

|  ピクセル  |  精度  |
| ---- | ---- |
|  16～38px  |  85%  |
|  38～  px  |  91%  |
* 上記条件での精度が出しているか。
 

</details>

# 3. カメラ設置条件
## ・ カメラ設置位置
<details open>
    <summary>取付角度・高度</summary>

* エンジンが許容精度で認識できている限界値範囲「最小値+α,最大値-α」（α:誤差）に設定されていること
* 例：角度(俯角 30度~45度)&高度(2.5m ~ 6.0m)
</details>


## ・ 推奨カメラ画角
<details open>
    <summary>垂直画角・水平画角</summary>


* エンジンが許容精度で認識できている限界値範囲「最小値+α,最大値-α」（α:誤差）に設定されていること
* 垂直画角:30度(80度未満)
* 水平画角:50度(110度未満)
* webカメラ大体50－150度
</details>


## ・ 検出対象のサイズ
<details open>
    <summary>推奨</summary>

* W384 x H216 px

</details>

<details open>
    <summary>最小</summary>

* W70 x H70 px

</details>

## ・ カメラから検出対象までの距離
<details open>
    <summary>距離</summary>

* 

</details>

# 4. 基準解像度
<details open>
    <summary>線やポリゴン描画時の基準解像度</summary>

* 1280 x 720(16:9)

</details>


