<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

<img src="https://raw.githubusercontent.com/rkassila/Medical_AImaging/master/aimaging/interface/images/title_image.png" alt="Medical AImaging" width="1280" align="right">

# Medical AImaging

_A Deep Learning based solution for MR & CT diseases detection._

</header>

## Project

*Medical AIMaging is our Le Wagon bootcamp project*

The tool can detect 36 diseases in 5 organs. It has been trained on Rad Image Net dataset.

## プロジェクト概要

深層学習モデルを使用した、MR及びCTの画像から5つの臓器の36種類の疾患を検出できる、ウェブアプリ開発プロジェクトです。このプロジェクトでは、以下の技術を用いました：

* **臓器検出モデルのトレーニング、バイナリ分類モデル、疾患分類モデルのトレーニング:** 畳み込みニューラルネットワークを用いて、高精度な臓器検出モデルをトレーニングしました。
* **GradCAMの使用:** 疾患のより分かりやすい画像を返すためにGradCAMを使用しました。
* **APIの構築:** FastAPIを使用して、疾患検出結果を提供するAPIを構築しました。
* **クラウドインフラの利用:** Google Cloud Platform (GCP) を使用して、モデルのデプロイメントおよびスケーラビリティを実現しました。
* **コンテナ技術の利用:** Dockerを用いて、開発環境の統一とデプロイメントの効率化を図りました。
* **ユーザーインターフェイスの作成:** Streamlitを使用して、ユーザーが直感的に利用できるインターフェイスを作成しました。
* **チームでのプロジェクト:** 4人のメンバーと共に、10日間でこのプロジェクトを完了しました。


### What's next?

We will try to work on an improved version. This first one having been only done in 10 days.


<footer>
</footer>
