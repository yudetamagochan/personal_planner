# personal_planner
パーソナルスペースを学習した経路計画

# 人のパーソナルスペースを考慮した移動ロボットの経路生成

Physical AI講座 2026 応用編1の自由課題です。

## 概要

人の移動能力、速度、協調性を考慮して、
移動ロボットの経路を生成します。

以下の人物属性を扱います。

- 通常の人
- 移動弱者
- 低速・高速
- 協調的・非協調的

## 使用手法

- 2次元グリッドマップ
- A*による教師データ生成
- PyTorch MLPによる次方向の分類
- 人の回避半径を考慮した安全フィルタ
- Matplotlibによる経路可視化

## 実行環境

- Google Colab
- Python
- NumPy
- Matplotlib
- PyTorch

## 実行方法

1. `personal_space_navigation.ipynb`を開く
2. Google Colabで開く
3. セルを上から順番に実行する
4. 学習後、経路生成とアニメーションを実行する

## Notebook

[Google Colabで開く](https://colab.research.google.com/drive/1kb2ph4hbm0bMl26AqyhHoBsdvlfX2zFN)
