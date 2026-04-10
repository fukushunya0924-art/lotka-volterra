# Numerical Analysis of 4-Species Lotka-Volterra System

## Overview
4種のロトカ・ヴォルテラ方程式におけるカオス的ダイナミクスのシミュレーション、および最大リアプノフ指数（LLE）の導出を行うプロジェクトです。

## Mathematical Model
$$\frac{dx_i}{dt} = x_i \left( r_i + \sum_{j=1}^{4} a_{ij} x_j \right)$$

## Methods
- **Integration**: 4th-order Runge-Kutta method
- **LLE Derivation**: QR Decomposition / Benettin Algorithm
- **Environment**: Python (NumPy, SciPy, Matplotlib)

## Results
### Phase Portraits
(ここに相図の画像を配置： `![Phase Portrait](./results/phase_portrait.png)`)

### Maximum Lyapunov Exponent (LLE)
- Calculated LLE: $\lambda_{max} = 0.XXX$ (Positive value indicates chaos)
- Convergence Plot:
(ここに収束グラフを配置)

## Usage
1. 依存ライブラリのインストール: `pip install -r requirements.txt`
2. シミュレーションの実行: `python main.py`
