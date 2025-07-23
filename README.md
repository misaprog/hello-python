# Python入門 - Spamの例（Kaggle練習）

This is a basic practice from the Kaggle Python course.  
We assign a value to a variable and use it to repeat a string.

これはKaggleの「Python入門」で学んだ最初の練習です。  
変数の代入、条件分岐、文字列の繰り返し（*演算子）を体験しています。



---

## 🔢 コード全文

```python
spam_amount = 0
print(spam_amount)

# Ordering Spam, egg, Spam, Spam, bacon and Spam (4 more servings of Spam)
spam_amount = spam_amount + 4

if spam_amount > 0:
    print("But I don't want ANY spam!")

viking_song = "Spam " * spam_amount
print(viking_song)
```

---

## 🔍 各行の解説

---

### ✅ `spam_amount = 0`

* \*\*変数の代入（初期化）\*\*です。
* `spam_amount`（スパムの量）という変数に `0` を代入しています。
* まだスパムは注文していない状態。

---

### ✅ `print(spam_amount)`

* 今のスパムの量（＝0）を画面に表示します。
* 出力結果：`0`

---

### ✅ `spam_amount = spam_amount + 4`

* スパムを**4つ追加注文**します。
* `spam_amount` は `0 + 4` となり、結果は `4` に更新されます。
* これは変数の「更新（再代入）」です。

---

### ✅ `if spam_amount > 0:`

* \*\*条件分岐（if文）\*\*です。
* もしスパムの量が0より多ければ（＝注文してたら）…

```python
    print("But I don't want ANY spam!")
```

* 上の行が実行され、「スパムはいらないのに！」というセリフが出力されます。
* 出力結果：`But I don't want ANY spam!`

---

### ✅ `viking_song = "Spam " * spam_amount`

* 文字列 `"Spam "` を **4回繰り返す** という意味です（`spam_amount = 4` のため）。
* Pythonでは、**文字列 × 数字 → 繰り返し文字列** になります。

例：

```python
"Spam " * 4  →  "Spam Spam Spam Spam "
```

* `viking_song` という変数にこの文字列を代入しています。

---

### ✅ `print(viking_song)`

* 最後にスパムだらけの歌（`Spam Spam Spam Spam `）を出力します。

---

## ✅ 出力のまとめ（実行結果）

```text
0
But I don't want ANY spam!
Spam Spam Spam Spam 
```

---

## 📝 これは何のための問題？

* Pythonの**基本スキル**を一度に学べるようになっています：

| スキル      | 使われている箇所                        |
| -------- | ------------------------------- |
| 変数の代入    | `spam_amount = 0`               |
| 変数の更新    | `spam_amount = spam_amount + 4` |
| 条件分岐     | `if spam_amount > 0:`           |
| 文字列の繰り返し | `"Spam " * spam_amount`         |
| 出力       | `print(...)`                    |

---

## 🧠 補足知識：「Monty Python」の“スパム”とは？

* 「モンティ・パイソン」はイギリスの伝説的コメディグループ。
* 有名なコントで、**どの料理にもスパム（缶詰肉）が入っていて困っている客の話**があります。
* Pythonという言語名は、彼らにちなんで名付けられました。

---

## ✅ まとめ

このコードは、Pythonの基本を楽しく学ぶための「練習問題＋ジョークネタ」です。

