# cwtex-q-fonts 專案說明文件

## 歷史與著作權

cwTeX 字型最初是由 Tsong-Min Wu 及 Tsong-Huey Wu 於 1999 至 2004 年間製作並以 GNU GENERAL PUBLIC LICENSE Version 2 or latter 發佈。在 2005 至 2007 年間，Edward G.J. Lee 對該字型進行過整理。本專案 cwtex-q-fonts 自 2008 年起由 Chen-Pan Liao 開始運作。

於 2014 年，Tsong-Min Wu、Tsong-Huey Wu、Edward G.J. Lee 及 Chen-Pan Liao 四人同意將漢字及中文常用標點符號之字符另外獨立並以 SIL Open Font License (Version 1.1) 授出，以利與其他 OFL 授權之字體整合。

本專案所含之所有字型及其所有版本允許嵌入 PS、PDF 及其他相類的檔案中而不因此影響文件或文件格式本身所使用的授權（許可證）。

## 目的

前人所發佈之 cwTeX 字型仍有許多不完美之處，例如字符的寬度或位置不統一。本計劃的主要目的是修正 cwTeX 字型，願能使字型達更高水準。

## 字體一覽表

目前 cwtex-q-fonts 共有五種字體，兩種授權方式，共分成十個字型檔案，請見下表。

### GPLV2+

| 字體種類 | 字型檔名 | 字型全名 | 授權方式 |
| ---------| -------- | -------- | -------- |
| 中明體   | cwTeXQMing-Medium     | cwTeX Q Ming Medium      | GNU GENERAL PUBLIC LICENSE Version 2 or latter |
| 中楷體   | cwTeXQKai-Mediu m     | cwTeX Q Kai Medium       | GNU GENERAL PUBLIC LICENSE Version 2 or latter |
| 中圓體   | cwTeXQYuan-Medium     | cwTeX Q Yuan Medium      | GNU GENERAL PUBLIC LICENSE Version 2 or latter |
| 中仿宋體 | cwTeXQFangsong-Medium | cwTeX Q Fangsong Medium  | GNU GENERAL PUBLIC LICENSE Version 2 or latter |
| 粗黑體   | cwTeXQHei-Bold        | cwTeX Q Hei Bold         | GNU GENERAL PUBLIC LICENSE Version 2 or latter |

### OFL

| 字體種類 | 字型檔名 | 字型全名 | 授權方式 |
| ---------| -------- | -------- | -------- |
| 中明體（自 0.3 版）   | cwTeXQMingZH-Medium     | cwTeX Q MingZH Medium      | SIL Open Font License (Version 1.1) |
| 中楷體（自 0.3 版）   | cwTeXQKaiZH-Mediu m     | cwTeX Q KaiZH Medium       | SIL Open Font License (Version 1.1) |
| 中圓體（自 0.3 版）   | cwTeXQYuanZH-Medium     | cwTeX Q YuanZH Medium      | SIL Open Font License (Version 1.1) |
| 中仿宋體（自 0.3 版） | cwTeXQFangsongZH-Medium | cwTeX Q FangsongZH Medium  | SIL Open Font License (Version 1.1) |
| 粗黑體（自 0.3 版）   | cwTeXQHeiZH-Bold        | cwTeX Q HeiZH Bold         | SIL Open Font License (Version 1.1) |

備註：此授權之字體僅包含漢字部份與中文常用標點符號。

## 修正方針
五個字體皆由 cwTeX Type 1 字型（簡稱為 cwt1）Version 1.1（見 [cwt1 1.1 釋出網頁](http://blog.bs2.to/post/EdwardLee/8355)）以 [FontForge](http://fontforge.sourceforge.net/) 組合而成。相較於 cwt1，已針對五種字體的中文常用標點符號做了調整，皆以
  * 貼近基線；
  * 左, 右括號或引號分別向右、左集中；以及
  * 將漢字與符號之字寬統一
為方針所進行。


## 下載
  *  [自 Google drive 直接下載](https://drive.google.com/folderview?id=0B0E2FRIvjDDobXhySmlKTkVLVUE&usp=sharing)

## 原始碼
  * [Version 0.1](https://github.com/l10n-tw/cwtex-q-fonts/tree/v0.1)
  * [Version 0.2](https://github.com/l10n-tw/cwtex-q-fonts/tree/v0.2)
  * [Version 0.2-1](https://github.com/l10n-tw/cwtex-q-fonts/tree/v0.2-1)
  * [Version 0.3](https://github.com/l10n-tw/cwtex-q-fonts/tree/v0.3)
  * [Version 0.4](https://github.com/l10n-tw/cwtex-q-fonts/tree/v0.4)

## 沿革

### Version 0.1

  * May 12, 2011 釋出。
  * 中文常用標點符號貼近基線的修正。
  * 中文常用括號貼近基線的修正。

### Version 0.2

  * Feb 25, 2012 釋出。
  * 將黑體字與圓體字之大小與位置大規模重新安排，以利與其它 cwtex-q-fonts 字體的字高與大小較為一致。
  * 明體字極少數字符修正。

### Version 0.2-1
  * Mar 10, 2014 釋出。 
  * 修正 cwTeX Q Yuan Medium 之字符「低」（感謝 [pswo10680 @ Google Code 的回報](http://code.google.com/p/cwtex-q-fonts/issues/detail?id=2)）。

### Version 0.3

  * Jul. 10, 2014 釋出。
  * 在 SVN 中不再更新 TTF 字型檔；TTF 字型檔取得方法請見「下載」一節內容。
  * 將所有漢字及中文常用符號（U+3000—301E、U+4E00—9FFF、U+F900—FAFF 及 U+FE30—FFFF）複製至新字型檔並以 SIL Open Font License (Version 1.1) 授權釋出。
  * 明確加入「本專案所含之所有字型及其所有版本允許嵌入 PS、PDF 及其他相類的檔案中而不因此影響文件或文件格式本身所使用的授權（許可證）」之例外宣告。


### Version 0.4

  * Mar. 13, 2015 釋出。
  * 調整黑體字之中文標點符號，包括圓角改成方角，使字體風格更一致。
  * 從 Google Code 轉移至 GitHub。
