---
id: 201
slug: sankaku-bibun
name: 三角関数の導関数
status: coming
---
# 三角関数の導関数

ぶらんこの揺れや波の形は、sin xやcos xで表せます。その変化の速さを知るには、微分が必要です。出発点になるのは、xをラジアンで測るとき、xが0に近づくと sin x/x が1に近づくという事実です。つまり lim(x→0) sin x/x = 1 です。xが小さいと sin x はほぼ x に等しい、ということです。

これと加法定理を使うと、(sin x)' = cos x、(cos x)' = -sin x が導けます。式がこんなに簡単なのは、角をラジアンで測るからです。度で測ると、きれいな式になりません。

例題。y=x sin x を積の微分で求めます。(x)'sin x + x(sin x)' = sin x + x cos x です。また、lim(x→0) sin 2x/x は、sin 2x/(2x)×2 と見て、1×2=2 と求まります。次の町では、これらの結果を使って、いろいろな関数の積分を求めます。

```quiz
[
 {"type":"choice","q":"(cos x)' はどれ？","choices":["sin x","-sin x","-cos x"],"answer":1,"explain":"cos xを微分すると -sin x になります。"},
 {"type":"number","q":"lim(x→0) sin 3x / x の値は？","answer":3,"tol":0,"formula":"1*3","explain":"sin 3x/(3x)×3 と見て、1×3=3 です。"},
 {"type":"number","q":"y=x cos x のx=0での微分係数は？","answer":1,"tol":0,"formula":"Math.cos(0)-0*Math.sin(0)","explain":"y'=cos x - x sin x。x=0で 1-0=1 です。"}
]
```
