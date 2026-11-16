---
id: 183
slug: taisuu
name: 対数と常用対数
status: coming
---
# 対数と常用対数

2を何乗すると8になるでしょう。2³=8なので答えは3です。この「何乗するか」を表す言葉が**対数**で、log₂8=3と書きます。一般に、aを1でない正の数として、a^p=Mのとき、p=log_a Mです。aを底、Mを真数といいます。たとえばlog₁₀1000=3、log₃9=2、log₅1=0です。

対数には次の性質があります。log_a(MN)=log_a M+log_a N、log_a(M/N)=log_a M−log_a N、log_a(M^k)=k×log_a M。例題として、log₂8+log₂4=3+2=5です。これはlog₂(8×4)=log₂32=5と一致します。かけ算が足し算に変わるのが、対数の便利なところです。

底を10にした対数log₁₀Mを**常用対数**といいます。log₁₀10=1、log₁₀100=2のように、10の累乗なら整数になります。大きな数や小さな数の大きさを、10の何乗くらいかで比べるときに役立ちます。次の町では、この対数を使って関数を作り、そのグラフを調べます。

```quiz
[
 {"type":"number","q":"log₃81の値は？","answer":4,"tol":0.001,"formula":"Math.log(81)/Math.log(3)","explain":"3⁴=81なので、log₃81=4です。"},
 {"type":"number","q":"log₁₀50+log₁₀2の値は？","answer":2,"tol":0.001,"formula":"Math.log10(50)+Math.log10(2)","explain":"log₁₀(50×2)=log₁₀100=2です。"},
 {"type":"choice","q":"log₅1の値は？","choices":["0","1","5"],"answer":0,"explain":"5⁰=1なので、log₅1=0です。"}
]
```
