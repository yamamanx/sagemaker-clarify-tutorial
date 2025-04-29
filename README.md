# SageMaker Clarify チュートリアル

このリポジトリは、Amazon SageMaker Clarify を使用して機械学習モデルの公平性と説明可能性を評価するためのチュートリアル資料を提供します。

## 概要

SageMaker Clarify は、機械学習モデルのバイアス検出と説明可能性を提供するツールです。このチュートリアルでは、以下の内容を学ぶことができます：

- 機械学習モデルのトレーニング
- バイアス検出と評価
- モデルの説明可能性の分析

## ファイル構成

- `ClarifyDemo.ipynb`: メインのチュートリアルノートブック
- `xgboost_train.py`: XGBoostモデルのトレーニングスクリプト
- `clarify_bias_output.pdf`: バイアス分析の出力結果
- `clarify_explainability_output.pdf`: 説明可能性分析の出力結果

## 使用方法

1. SageMaker ノートブックインスタンスまたは SageMaker Studio で `ClarifyDemo.ipynb` を開きます
2. ノートブックの手順に従って、モデルのトレーニングとClarifyによる分析を実行します

## 前提条件

- AWS アカウント
- SageMaker へのアクセス権限
- 基本的な Python と機械学習の知識

## 参考リソース

- [Amazon SageMaker Clarify ドキュメント](https://docs.aws.amazon.com/sagemaker/latest/dg/clarify-fairness-and-explainability.html)
- [XGBoost ドキュメント](https://xgboost.readthedocs.io/)
