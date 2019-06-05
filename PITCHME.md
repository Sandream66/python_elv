<!-- 自己紹介 -->
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/p_elv.jpeg" width=200%>
+++
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide2.jpeg" width=85%>
+++
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide3.jpeg" width=85%>
+++
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide4.jpeg" width=85%>
+++
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide5.jpeg" width=85%>
+++
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide6.jpeg" width=85%>
+++
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide7.jpeg" width=85%>
+++
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide8.jpeg" width=85%>
+++
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide9.jpeg" width=85%>
+++
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide10.jpeg" width=85%>
<!-- 自己紹介 -->
---

<!-- Pythonの話 -->
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/slide11.jpeg" width=85%>
+++

### Pythonって何が出来るの？

+++

### 出来ることモロモロ
<font color="orange" size="5" face="Comic Sans MS">
機械学習を使った人工知能の開発<br>
自動データ処理や分析などの業務効率化<br>
スクレイピングによるWEB上の画像データ・テキストデータの自動収集<br>
WEBサービス・WEBアプリケーション制作<br>
スマホアプリ（Android） デスクトップアプリ制作<br>
フィンテック・ブロックチェーン技術の開発<br>
</font><br>

+++

### Pythonスキルを生かせる仕事とは？

+++

### こんなお仕事
人工知能（AI）エンジニア<br>
WEBアプリケーションエンジニア<br>
データサイエンティスト<br>
etc...<br>
+++

### 何故Pythonがいいの？

+++
<font color="orange" size="8" face="Comic Sans MS">
それは、私も今模索中。<br>
でも・・
</font>

+++
<font color="orange" size="8" face="Comic Sans MS">
間違いなく<br>
初心者にも優しい言語だと思います！
</font>
<!-- Pythonの話 -->

---
# Pythonの基礎
+++
### Pythonはオブジェクト指向の  
### プログラミング言語です。
+++

### オブジェクト指向とは？  

<font size="4">オブジェクト指向は、クラスを基準としたプログラムを設計する方法論の1つ</font>  
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/object1.jpg" width="700">

+++
#### クラスとメソッドと関数で構成されています。  

<font size="4">
  クラスの変数を属性。動作をメソッド。動作だけを記載した関数で構成されています。  
  １つ１つのデータ型も全てオブジェクトです。  
  今日のところは、オブジェクトとはこういう感じとだけ覚えて帰ってください。  
  この話は、様々な人が様々な意見を持っているようです。  
  その話は第3回で改めお話します。
</font>
+++

### 変数

+++
#### 変数とは何でも入る箱です。

<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/hensu1.jpg" width="400">  

```
# 文字も入る
a = "疲れてきた？大丈夫？"

# 数値も入る
b = 123

# そのほか色々入れられます。 
```

+++

### ターミナル・コマンドプロンプト 
### を立ち上げてみましょう

+++

##### ターミナル・コマンドプロンプト
<details><summary>Macの方  </summary>
<font size="6" color="red">［アプリケーション］→［ユーティリティ］→［ターミナル］を選択しましょう。</font>  </details>  
<details><summary>Windowsの方  </summary>
<font size="6" color="red">［スタート］→［Windowsシステムツール］→［コマンドプロンプト］を選択しましょう。  </font></details>  

+++

##### ターミナル・コマンドプロンプト
##### でPythonを起動しよう。  

<details><summary>Macの方  </summary>
<font size="6" color="red">Python3 と入力しエンター</font>  </details>  
<details><summary>Windowsの方  </summary>
<font size="6" color="red">Pythonと入力しエンター</font></details>

+++
<font size="6">こんな感じになっていればOK  
  ＊Pythonあとの数字とかは違っていても大丈夫です</font>  
<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/python1.jpg" width="700">

+++
##### 数値や文字などの演算子


<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/python2.jpg" width="700">  
実際に使ってみましょう。


+++

### 文字列も計算してくれます

<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/python3.jpg" width="700">  



---
# 型の話

+++

### よく利用される型  
<font size="6">
int型：整数  
float型：小数点  
str型：文字列  
bool型：真偽値  
list型：リスト  
tuple型：タプル  
dict型：辞書  
</font>

+++
### int型：整数  
<font size="4">
Pythonの整数型には値の範囲がなく、システムのメモリ容量が許す限り、  
どんな大きな値の整数オブジェクトでも作成できます。  

文字列や浮動小数点数などをint型オブジェクトで整数に変換できます。  </font>

```
int("2") 
int(2.123)
```  

<font size="4">この２つは整数の２となります。</font>

+++
### float型：小数点  
<font size="4">
浮動小数点数の計算をする場合、小数点数を計算するときや丸めるときに誤差が発生する場合があります。  
このような問題を防ぐため、Pythonでは十進数の計算をするためのdecimalモジュールが用意されています。</font>  

```
x = 0.1
y = 0.2

print(x + y)
>>>0.30000000000000004
```

<font size="4">float型同士の計算では微妙なずれが生じます。</font>　　

```
from decimal import Decimal
 
x = Decimal("0.1")
y = Decimal("0.2")
 
print(x + y)
>>>0.3
```
+++
### str型：文字列
<font size="4">
文字列オブジェクトは、str型のオブジェクトです。  
数値や浮動小数点数などを文字列に変換する場合は、  
str型を呼び出して変換します。
</font>

```
print(str(1) + str(0.1) + str(1+0.1))
>>> 1 + 0.1 = 1.1
```

<font size="5">文字数を調べる組込関数</font>  

```
len("Hello")
>>>5
```
  
<font size="5">小文字に変換するメソッド</font>　　
```
"A Ａ".lower()
>>>'a a'
```
+++
### bool型：真偽値  

<font size="4">
ブール型（bool又はboolean）はプログラミング言語でよく使われる真偽値のことです。  
True(真）とFalse（偽）の二種類が用意されています。
</font>

```
bool1 = True  
if bool1 == True:  
    print ("処理を実行")  
```
<font size="4">のように、if文などの判断に使われる事が多いです。  
if文についての詳細は後半で説明します。</font>

+++
### list型：リスト  

```
li1 = ["A","B","c",1,2,3,["cc","dd"]]  
```
<font size="4">このように[ ]でくくったデータの集合体をリストと言います。  
リストには箱番号がついています。箱と箱は , で区切ります。</font>

<img src="https://raw.githubusercontent.com/Sandream66/python_elv/master/path/to/list1.jpg" width="700">  

<font size="4">部屋番号は0から始まります。各部屋の情報を取り出したい時は以下のように書きます。</font>  
```
# リストの0番目を取り出したい
print (li1[0])

>>> A
```

+++
### tuple型：タプル  
```
li1 = ("A","B","c",1,2,3,["cc","dd"])
```
<font size="4">このように( )でくくったデータの集合体をタプルと言います。  
リストと同じように箱番号が0からついています。 箱と箱は , で区切ります。 
リストと異なるのは、更新が出来ないという事です。</font>
```
# リストの場合
li1 = ["A","B","c",1,2,3,["cc","dd"]]  
li1[0] = "Change"
print li1
>>> ["Change","B","c",1,2,3,["cc","dd"]] 

# タプルで同じ事をやると・・
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'tuple' object does not support item assignment
```
+++
### dict型：辞書  
```
d1 = {"apple": "りんご","B": 2,"C": 3}
```
<font size="4">このように{ } でくくって　Key： Value で記載された集合体を辞書と言います。  
英語辞書をイメージしてください。appleというKeyを調べると、りんごというvalueが確認できます。  
Keyを使って、Valueを確認したいときは以下のように使います。  </font>
```
print (d1["apple"])
>>> りんご
```
+++

![コーヒータイム](path/to/coffe.jpg)
---
# ファイルを使って実行しよう 
+++

### ファイルを使って実行しよう  
<font size="4">ここまではターミナルもしくはコマンドプロンプトを使ってPythonとたわむれてきました。  
ここからは一度書いたプログラムを繰り返し実行できる方法をご紹介します。  
プログラムはテキストエディターを使って記載し、そのファイルを実行する事でプログラムを動かす事が出来ます。
ターミナルやコマンドプロンプトは一回書いて、閉じたら終わり。それではアプリなど作れないので・・  
適切なテキストエディタを利用します。  
かつ、プログラミングを書くのに適したエディタが無料で色々あります。  
色々試して自分の使いやすいものを探すと良いでしょう。
私はAtomもしくはKomodoEditを使う事が多いです。  
[Atomインストール](https://atom.io)</font>
+++
![インストール手順](path/to/atom.jpg)

+++
### ファイルを保存する場所を用意する  
<font size="4">今日は単純にデスクトップにフォルダをつくって、そこにファイルを入れてきましょう。  
ターミナルもしくはコマンドプロンプトに戻りましょう。</font>

```
>>>|
```
<font size="4">先ほど使ったままにしている方はおそらく↑のようになっていると思います。  
  なっている方は exit() と入力してpythonの環境から抜けましょう。  
  *なっていない方は無視してください。  </font>
+++
### デスクトップにフォルダを作ります。  
<font size="4">ターミナルやコマンドプロンプトは、デフォルトでは基本ご自身のパソコンの  
ホームディレクトリと呼ばれる場所にいます。  
せっかくなのでコマンドでプログラマーっぽく、作りましょう。</font>  

```
cd Desktop
```

<font size="4">デスクトップに移動します。</font>  

```
mkdir elvpython
```

<font size="4">デスクトップにelvpythonというディレクトリ（フォルダのことです）を作成します。</font>
+++
### テキストエディタにコードを書いてみよう  

<font size="4">先ほどインストールしたAtomもしくはお好きなテキストエディタを開きます。</font>

```
print ("Hello World")
```
<font size="4">と書いて、先ほど作ったディレクトリに test.py という名前で保存しましょう。</font>

+++
### 実行  
<font size="4">コマンドプロンプトもしくはターミナルに戻りましょう。  </font>
<details><summary>Macの方  </summary>
<font size="6" color="red">`python3 test.py`  </font></details>  
<details><summary>Windowsの方  </summary>
<font size="6" color="red">`python test.py`  </font></details>  
 <font size="4">と入力してエンターキーを押下！！  </font>

```
Hello World
```

<font size="4">と出たら、成功です！！　おめでとうございます！！</font>
+++
# if文  
+++
### if文は条件分岐です  
<font size="4">ifという言葉の通り、「もし〜だったら」を想定して書きます。  
余談ですが・・こんな記事が海外で人気になったそうです。    
ある妻がプログラマの夫に「買い物にいって牛乳を1つ買ってきてちょうだい。  
卵があったら6つお願い」と言った。  
夫はしばらくして、牛乳を6パック買ってきた。  
妻は聞いた「なんで牛乳を6パックも買ってきたのよ！」  
夫いわく「だって、卵があったから……」</font>

+++
### どういうことかわかりますか？  

![ミルクと卵](path/to/milkegg.png)

+++
### これをPythonで書くなら・・  

```
if egg in store:
    milk_buy(6)
else:
    milk_buy(1)
```

<font size="4">こんな感じですかね・・</font>

+++
### Pythonのif文  

<font size="4">条件が１つの場合それ以外は何もしない</font>

```
if 条件を記載します:
    条件を満たしたときはここに記載の実行内容を実行
```

<font size="4">条件が複数ある場合</font>

```
if 最初の条件を記載します:
    最初の条件を満たした時に実行したい内容を記載
elif 最初の条件を満たさなかったものの中から次の条件を記載します。
    二個目の条件を満たした時に実行したい内容を記載
else:
    全ての条件を満たさなかった場合に記載
```

<font size="4">必ず条件指定の下はインデントを下げます（タブ4つ分)  
インデントが下がっている間がその条件の有効範囲となります。</font>

### 比較演算子  


![比較演算子](path/to/hikaku.jpg)
