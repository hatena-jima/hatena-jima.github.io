---
id: 188
slug: kahou-teiri
name: 加法定理と2倍角の公式
status: coming
---
# 加法定理と2倍角の公式

sin30°=1/2、sin45°=√2/2ですが、sin(30°+45°)=sin30°+sin45°とは計算できません。足した角の三角関数は、次の**加法定理**で求めます。
sin(α+β)=sinαcosβ+cosαsinβ
sin(α−β)=sinαcosβ−cosαsinβ
cos(α+β)=cosαcosβ−sinαsinβ
cos(α−β)=cosαcosβ+sinαsinβ

例題です。sin75°を求めます。75°=45°+30°なので、sin75°=sin45°cos30°+cos45°sin30°=(√2/2)(√3/2)+(√2/2)(1/2)=(√6+√2)/4です。

加法定理でβをαにすると、**2倍角の公式**が得られます。sin2α=2sinαcosα、cos2α=cos²α−sin²α。相互関係sin²α+cos²α=1を使えば、cos2α=2cos²α−1=1−2sin²αとも書けます。たとえばsinα=3/5、cosα=4/5のとき、sin2α=2×(3/5)×(4/5)=24/25です。次の町では、この公式を使って、sinとcosの足し算を1つのsinにまとめます。

```quiz
[
 {"type":"number","q":"cos75°の値を、cos(45°+30°)で計算して小数第2位まで求めよ。","answer":0.26,"tol":0.005,"formula":"(Math.sqrt(6)-Math.sqrt(2))/4","explain":"cos45°cos30°−sin45°sin30°=(√6−√2)/4で、約0.26です。"},
 {"type":"number","q":"sinα=3/5、cosα=4/5のとき、sin2αの値は？","answer":0.96,"tol":0.005,"formula":"2*3/5*4/5","explain":"sin2α=2sinαcosα=2×3/5×4/5=24/25=0.96です。"},
 {"type":"choice","q":"cos2αをcosαだけで表すと？","choices":["2cos²α−1","2cosα","cos²α+sin²α"],"answer":0,"explain":"cos2α=cos²α−sin²αのsin²αを1−cos²αにすると、2cos²α−1になります。"}
]
```
