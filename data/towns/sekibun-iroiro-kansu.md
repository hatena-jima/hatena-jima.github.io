---
id: 206
slug: sekibun-iroiro-kansu
name: いろいろな関数の積分
status: coming
---
# いろいろな関数の積分

積分は、微分の逆の計算です。三角関数・指数関数・対数関数の導関数を知っていれば、その逆をたどって積分の公式が作れます。(sin x)'=cos x だから ∫cos x dx = sin x + C、(cos x)'=-sin x だから ∫sin x dx = -cos x + C です。（Cは積分定数）

(eˣ)'=eˣ なので ∫eˣ dx = eˣ + C。また (log x)'=1/x（x>0）から、分数関数 1/x の積分は、x が負の場合も含めて ∫(1/x) dx = log|x| + C となります。

例題。∫₀^π sin x dx = [-cos x] を0からπまで = -cos π -(-cos 0) = 1+1 = 2 です。これは sin x のグラフと x軸で囲まれた山の面積を表します。

微分の公式を逆に読むだけで、積分の道具が増えます。次の町では、形が複雑な式を置き換えや積の微分を使って積分する、置換積分法と部分積分法に進みます。

```quiz
[
 {"type":"choice","q":"∫sin x dx はどれ？","choices":["cos x + C","-cos x + C","-sin x + C"],"answer":1,"explain":"(-cos x)'=sin x なので -cos x + C です。"},
 {"type":"number","q":"∫₀¹ eˣ dx の値は？小数第2位まで。","answer":1.72,"tol":0.005,"formula":"Math.E-1","explain":"[eˣ]を0から1まで = e-1 =1.718... 約1.72です。"},
 {"type":"number","q":"1からe²までの (1/x) の積分の値は？","answer":2,"tol":0,"formula":"Math.log(Math.E**2)-Math.log(1)","explain":"[log x]を1からe²まで = log e² - log 1 = 2 です。"}
]
```
