---
id: 208
slug: bubun-sekibun
name: 部分積分法
status: coming
---
# 部分積分法

x eˣ のように、二つの違う種類の関数の積は、置き換えでは解けないことがあります。そんなときは、積の微分の公式 (fg)' = f'g + fg' を逆に使います。両辺を積分して移項すると、∫f g' dx = f g - ∫f' g dx となります。これが **部分積分法** です。

使い方は、積の片方を微分する側 f に、もう片方を積分する側 g' に決めることです。決め方の目安は、微分すると簡単になる方を f にすることです。

例題 ∫x eˣ dx。f=x、g'=eˣ とすると f'=1、g=eˣ なので、x eˣ - ∫eˣ dx = x eˣ - eˣ + C = (x-1)eˣ + C です。逆に f=eˣ にすると、かえってxの次数が上がって難しくなります。

定積分では、f g の部分に範囲の値を入れるのを忘れないようにします。積分の道具として、これで置き換えと並ぶ武器がそろいました。

```quiz
[
 {"type":"number","q":"∫₀² x eˣ dx の値は？小数第1位まで。","answer":8.4,"tol":0.05,"formula":"Math.E**2+1","explain":"[(x-1)eˣ]を0から2まで = e² - (-1) = e²+1 =8.39... 約8.4です。"},
 {"type":"number","q":"∫₀^π x cos x dx の値は？","answer":-2,"tol":0.001,"formula":"(0*Math.sin(Math.PI)+Math.cos(Math.PI))-(0+Math.cos(0))","explain":"f=x、g'=cos x とすると、x sin x - ∫sin x dx = x sin x + cos x。πと0を入れて -1-1=-2 です。"},
 {"type":"choice","q":"∫x sin x dx はどれ？","choices":["-x cos x + sin x + C","x cos x - sin x + C","-x cos x - sin x + C"],"answer":0,"explain":"f=x、g'=sin x。-x cos x - ∫(-cos x)dx = -x cos x + sin x + C です。"}
]
```
