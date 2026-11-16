---
id: 204
slug: baikai-inkansuu-bibun
name: 媒介変数表示・陰関数の微分
status: coming
---
# 媒介変数表示・陰関数の微分

ボールの位置は、時間tを使って x=t²、y=t³ のように表せます。このとき y を x の式に直さなくても、傾き dy/dx は求められます。xもyもtの関数なので、合成関数の微分から dy/dx = (dy/dt)/(dx/dt) となります。例題では dy/dt=3t²、dx/dt=2t なので、dy/dx=3t²/2t=3t/2 です。t=2 なら傾きは3です。

もう一つ、x²+y²=25 のように、y=(xの式)の形になっていない式があります。このようにxとyの関係を式で表したものを **陰関数** といいます。y をxの関数とみて両辺をxで微分します。y² の微分は合成関数の微分で 2y×dy/dx となるので、2x+2y×dy/dx=0 から dy/dx=-x/y です。点(3,4)での傾きは -3/4 です。

どちらも、曲線の接線を求めるときに役立ちます。

```quiz
[
 {"type":"choice","q":"x=2t、y=t² のとき dy/dx は？","choices":["t","2t","t/2"],"answer":0,"explain":"dy/dt=2t、dx/dt=2 なので dy/dx=2t/2=t です。"},
 {"type":"number","q":"x=t²+1、y=2t³ のt=2での dy/dx は？","answer":6,"tol":0,"formula":"(6*2**2)/(2*2)","explain":"dy/dx=6t²/2t=3t。t=2で6です。"},
 {"type":"number","q":"x²+y²=25 上の点(4,3)での傾きは？小数第2位まで。","answer":-1.33,"tol":0.005,"formula":"-4/3","explain":"dy/dx=-x/y なので -4/3=-1.333... 約-1.33です。"}
]
```
