# Numerical Analysis of 4-Species Lotka-Volterra System

## Overview
4種のロトカ・ヴォルテラ方程式におけるシミュレーション、および相図の描画を行うプロジェクトです。

## Mathematical Model

The model consists of two prey species ($x_1, x_2$) and two predator species ($y_1, y_2$):

$$
\begin{aligned}
\frac{dx_1}{dt} &= r_{x_1}x_1 - \lambda_{11}x_1y_1 - \lambda_{12}x_1y_2 \\
\frac{dy_1}{dt} &= -r_{y_1}y_1 + c_1\lambda_{11}x_1y_1 + d_1\lambda_{21}x_2y_1 \\
\frac{dx_2}{dt} &= r_{x_2}x_2 - \lambda_{21}x_2y_1 - \lambda_{22}x_2y_2 \\
\frac{dy_2}{dt} &= -r_{y_2}y_2 + c_2\lambda_{12}x_1y_2 + d_2\lambda_{22}x_2y_2
\end{aligned}
$$
## Methods
- **Integration**: Odeint(Time-series Plot and Trajectory)
- **Environment**: Python (NumPy, SciPy, Matplotlib)


