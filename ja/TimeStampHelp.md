---
title: 項目の時間スタンプ
---

# 項目の時間スタンプ

この機能は、**オプション→設定→一般**で入切したり設定したりすることができます。

JabRefでは、データベースに項目が加えられた日付を、フィールドに自動的に入れるようにすることができます。

## 整形

時間スタンプの整形は、日付の各部分の位置を示す指示文字を含む文字列を用いて指定します。

以下は、使用できる指示文字の一部です(括弧中の部分は2005年9月14日水曜日午後5時45分の場合の表示例を示します)。

-   **yy**: 西暦 (05)
-   **yyyy**: 西暦 (2005)
-   **MM**: 月 (09)
-   **dd**: 日 (14)
-   **HH**: 時 (17)
-   **mm**: 分 (45)

これらの指示子は区切り文字や空白とともに使用することができます。以下に例を挙げます。

-   **yyyy/MM/dd** は **2005/09/14** となります。
-   **yy.MM.dd** は **05.09.14** となります。
-   **yyyy/MM/dd HH:mm** は **2005/09/14 17:45** となります。
