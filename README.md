<br>

> This is my test repository.  
> Testing markdown

<br>

> # **見出し**

```
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6
```
表示はこのようになる。

# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6


> # **段落**
```
あいうえお
<空行>
かきくけこ
```
表示はこのようになる。

あいうえお

かきくけこ


> # **改行**

```
aaa(スペース2つ)
bbb
<br>
ccc
```
表示はこのようになる

aaa  
bbb
<br>
ccc

> # **リスト**

`-` もしくは `+`, `*`を使用し記述する。


```
- リスト1
    - りんご
        - 甘い
        - 赤い
    - ぶどう
        - 紫色
        - 丸い
    - みかん
```

- リスト1
    - りんご
        - 甘い
        - 赤い
    - ぶどう
        - 紫色
        - 丸い
    - みかん

<br>

* タブまたはスペース2つ

> # **番号付きリスト**
```
1. リスト1
    1. りんご
        1. 甘い
        1. 赤い
    1. ぶどう
        1. 紫色
        1. 丸い
    1. みかん
```
1. リスト1
    1. りんご
        1. 甘い
        1. 赤い
    1. ぶどう
        1. 紫色
        1. 丸い
    1. みかん

> # **ハイパーリンクの設定**

```
[表示文字列](URL)
```
表示例

[Google](https://www.google.com)

## リンク付き画像  
```
## リンク付き画像  
[![discord-avatar](https://cdn.discordapp.com/embed/avatars/4.png)](https://www.google.com)  
(discordのアバター画像。googleへリンクが設定されている。)
```
[![discord-avatar](https://cdn.discordapp.com/embed/avatars/4.png)](https://www.google.com)  
(discordのアバター画像。googleへリンクが設定されている。)

<br>
<br>

> # **文字列の装飾**

> ## 斜体
```
*あいうえお*  
_あいうえお_
```

*あいうえお*  
_あいうえお_

> ## 強調
```
**あいうえお**  
__あいうえお__
```
**あいうえお**  
__あいうえお__

> ## 強調 + 斜体
```
***あいうえお***  
___あいうえお___
```
***あいうえお***  
___あいうえお___

> ## 下線
```
<u>あいうえお</u>
```
<u>あいうえお</u>

> ## 打消し
```
~~あいうえお~~
```
~~あいうえお~~

> ## 下付き
```
X<sub>2</sub>
```
X<sub>2</sub>

> ## 上付き
```
X<sup>2</sup>
```
X<sup>2</sup>

> ## 文字色の指定
```
<font color="Red">テキスト</font>
```
<font color="skyblue">テキスト</font>

> ## カスタム
```
<span style="font-size:16pt; border: 1px skyblue solid; padding: 4px;">ABC</span>
```
<span style="font-size:16pt; border: 1px skyblue solid; padding: 4px;">ABC</span>

<br>
<br>

> # **引用**
```
> テキスト
>> テキスト
```
> テキスト
>> テキスト

> # **コードの挿入**
```
\```java:Example.java
int i = 0;
\```
```

```java:Example.java
int i = 0;
```

> # **インラインコード**
```
これは`インラインコード`です。
```
<br>

> # **画像**

> ## サイズを指定しない場合
```
![代替テキスト](URL "タイトル")
```
![discord-avatar.png](https://cdn.discordapp.com/embed/avatars/4.png "discord-avatar")

> ## サイズを指定する場合
```
<img width="数値" alt="代替テキスト" src="URL">
```
<img width="200" alt="discord-avatar" src="https://cdn.discordapp.com/embed/avatars/4.png">

<br>

> # **テーブル**
```
| 1 | 2 | 3 |
| :-- | :-: | --: |
| a | b | c |
| 左寄せ | 中央揃え | 右寄せ |
```
| 1 | 2 | 3 |
| :-- | :-: | --: |
| a | b | c |
| 左寄せ | 中央揃え | 右寄せ |

<br>

> # **水平線**
```
***
---
___
```

***
---
___

> # チェックボックス
```
[ ] チェックなし  
[x] チェックあり
```

[ ] チェックなし  
[x] チェックあり
