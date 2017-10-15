# Markdownサンプル集

## ページ内リンク
* [テーブル](#table)
* [色づけ](#color)


***
## イメージ
![img](.\img\1.jpg)  
```
![img](.\img\1.jpg)  
```
- サイズ指定する場合  
	<img src=".\img\1.jpg" width="100px">
	```
	<img src=".\img\1.jpg" width="100px">
	```

## リンク  
[W3C]( http://www.w3.org/)
```
[W3C]( http://www.w3.org/)
```

<a name="table"></a>
## テーブル
| Left align | Right align | Center align |
|:-|-:|:-:|
|Apple|Banana|Peach|
|Cars|Ships|Planes|


```
|Left align|Right align|Center align|
|:-|-:|:-:|
|Apple|Banana|Peach|
|Cars|Ships|Planes|
```
## コメントアウト
<!--
こめんと
-->
```
<!--
こめんと
-->
```
<a name="color"></a>
## 色づけ
- <Font color="red">あかいろ</font>
	```
	<Font color="red">あかいろ</font>
	```

## コードの挿入
- 例）`<relation/>`要素
	```
	例）`<relation/>`要素
	```
- 本Markdownのソースファイルを参照。
	```html:sample.html
	<relation effectiveCrId="1826" effectiveDateTime="9999-12-31T00:00:00.000+09:00" updateNo="1">
	  <objectType>WORK_PRODUCT</objectType>
	</relation>
	```