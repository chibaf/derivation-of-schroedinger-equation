# derivation-of-schroedinger-equation
derivation of schroedinger equation

以下のハミルトン-ヤコビ方程式から出発します

$$
\frac{1}{2m}\left\{\left(\frac{\partial W}{\partial x}\right)^2+\left(\frac{\partial W}{\partial y}\right)^2+\left(\frac{\partial W}{\partial z}\right)^2\right\}+V = E
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
\frac{k^2}{2m}\left(\left(\frac{\partial \varphi}{\partial x}\right)^2+\left(\frac{\partial \varphi}{\partial y}\right)^2+\left(\frac{\partial \varphi}{\partial z}\right)^2\right)+(V-E)\varphi^2=0
$$

この両辺を積分すると

$$
\int\left[\frac{k^2}{2m}\left(\left(\frac{\partial \varphi}{\partial x}\right)^2+\left(\frac{\partial \varphi}{\partial y}\right)^2+\left(\frac{\partial \varphi}{\partial z}\right)^2\right)+(V-E)\varphi^2 \right]dxdydz=0
$$

ここでシュレディンガーは左辺の変分がゼロになると仮定します

$$
\delta \int\int\int\left(\frac{k^2}{2m}\left(\left(\frac{\partial \varphi}{\partial x}\right)^2+\left(\frac{\partial \varphi}{\partial y}\right)^2+\left(\frac{\partial \varphi}{\partial z}\right)^2\right)+(V-E)\varphi^2\right)dxdydz=0
$$
