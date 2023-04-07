# derivation-of-schroedinger-equation
derivation of schroedinger equation

以下のハミルトン-ヤコビ方程式から出発します

$$
\frac{1}{2m}\[\left(\frac{\partial W}{\partial x}\right)^2+\left(\frac{\partial W}{\partial y}\right)^2+\left(\frac{\partial W}{\partial z}\right)^2\]+V = E
$$

次の変数変換を行います

$$
W(x,y,z)=K\log\varphi(x,y,z)
$$

物理学者高林氏はボルツマンの次の式との類似性に言及しています（量子論の発展史/ちくま学芸文庫）

$$
S=k_B\log p
$$

変換を行うと、 $\varphi$ の式を得ます

$$
\frac{K^2}{2m}\left(\left(\frac{\partial \varphi}{\partial x}\right)^2+\left(\frac{\partial \varphi}{\partial y}\right)^2+\left(\frac{\partial \varphi}{\partial z}\right)^2\right)+(V-E)\varphi^2=0
$$

この両辺を積分すると

$$
\int\left[\frac{K^2}{2m}\left(\left(\frac{\partial \varphi}{\partial x}\right)^2+\left(\frac{\partial \varphi}{\partial y}\right)^2+\left(\frac{\partial \varphi}{\partial z}\right)^2\right)+(V-E)\varphi^2 \right]dxdydz=0
$$

ここでシュレディンガーは左辺の変分がゼロになると仮定します

$$
\delta \int\left(\frac{K^2}{2m}\left(\left(\frac{\partial \varphi}{\partial x}\right)^2+\left(+\frac{\partial \varphi}{\partial y}\right)^2+\left(\frac{\partial \varphi}{\partial z}\right)^2\right)+(V-E)\varphi^2\right)dxdydz=0
$$

変分を実行すると

$$
\delta \int\int\int\left(\frac{K^2}{2m}\left(\frac{\partial \varphi}{\partial x}\frac{\partial \delta\varphi}{\partial x}+\left(\frac{\partial \varphi}{\partial y}\right)^2+\left(\frac{\partial \varphi}{\partial z}\right)^2\right)+(V-E)\varphi^2\right)dxdydz=0
$$


# 参考

量子力学 / 保江 邦夫 著 https://www.nippyo.co.jp/shop/book/1761.html

Quantisierung als Eigenwertproblem - Schrödinger - 1926 - Annalen der Physik - Wiley Online Library https://onlinelibrary.wiley.com/doi/10.1002/andp.19263840404
