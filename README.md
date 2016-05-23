# 人工智慧自動克漏字填空

痞客邦為華文區最大原生內容創作平台，擁有眾多閱讀者及大量的優質文章。許多的網友會在此平台上尋找生活娛樂的相關資訊，例如旅遊景點、化妝品牌及美食甜點，故如何從文章當中萃取出相關的人事時地物為相當重要的技術。  
  
比賽題目為選擇題形式的克漏字填空。題目來源為各大部落客的熱門文章，我們在這些文章中挑出特定語句，並將語句中的特定詞彙挖空，產生克漏字的問題。

例如：  
>明太祖朱元璋是明朝的開國皇帝。朱元璋出身平民，幼時貧窮，曾為地主放牛。公元1344年，入皇覺寺，25歲時參加郭子興領導的紅巾軍反抗蒙元政權。先後擊敗了陳友諒、張士誠等其他起義軍，統一南方，後北伐滅元，建立大一統的皇朝，國號「大明」。廟號太祖，諡高皇帝。因年號洪武也俗稱朱洪武或洪武帝。

透過解析以上的文章，參賽者可能會拿到下面這樣的題目：  

```
明太祖︽⊙＿⊙︽是明朝的開國皇帝。  
a. 朱元璋
b. 朱頭皮
c. 朱茵
```  
又或是  

```
明太祖︽⊙＿⊙︽是明朝的開國皇帝。  
a. 洪武帝
b. 朱頭皮
c. 朱茵
```

## 資料集
參賽者將獲得完整的**原始本文**與**範例題目**兩個資料集作為訓練資料。在這裡我們先公布部分範例，於參賽者報名成功後將開放完整資料的下載連結。

* **原始本文集**：來自痞客邦站內分類為流行、旅遊的熱門文章，同時也是本次比賽題目的出處。但我們也要提醒大家，**問題的答案未必都與原始文章如出一轍，當答案不存在於原始文章的時候，我們希望參賽者選出最接近的答案**。就像上面的例子一樣。
* **範例題目**：我們從原始本文集之中整理出來的題目集合，部分範例與資料格式請看[這裡](https://www.pixnet.net/)。事實上，參賽者也可以不看原始本文集，單純透過解析範例題目，利用語義分析等方法找出問題與答案之中的規則來回答問題。

因為知道每一位參賽者都追求更高的答對率，追求完美，所以原始文本集與範例題目我們一起給你。

## 比賽方式
各隊必需實作 Slack Bot 作為回答比賽題目的 AI 機器人，接下來各隊的 Bot 會被邀請至擂台頻道，擂台主Bot 會提問題目，再由各隊Bot 回答計算結果，並由大會程式來即時統計分數

* Slack Channel Link
* Slack Integratioin Sample Code
* Slack Integration Library
 * https://github.com/slackhq/python-slackclient
 * https://github.com/os/slacker

## 如何加入 pixnethackathon2016 channel 



## 評分方式

### 演算法推薦結果(80%)
* 準確率
* 回應速度
 
### 簡報分數(20%)
