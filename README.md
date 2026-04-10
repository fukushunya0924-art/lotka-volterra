# Numerical Analysis of 4-Species Lotka-Volterra System

## Overview
4種のロトカ・ヴォルテラ方程式におけるシミュレーション、および相図の描画を行うプロジェクトです。

## Mathematical Model
$$\frac{dx_i}{dt} = x_i \left( r_i + \sum_{j=1}^{4} a_{ij} x_j \right)$$

## Methods
- **Integration**: 4th-order Runge-Kutta method(LLE) and Odeint(Time-series Plot　and Trajectory)
- **LLE Derivation**: QR Decomposition / Benettin Algorithm
- **Environment**: Python (NumPy, SciPy, Matplotlib)



## Usage
1. 依存ライブラリのインストール: `pip install -r requirements.txt`
2. シミュレーションの実行: `python main.py`
