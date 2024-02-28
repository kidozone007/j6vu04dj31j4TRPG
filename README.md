# 《一、　基本規則》

## 1.判定

每當玩家試圖進行一個有可能失敗的動作時，為了檢測玩家的人物是否成功的完成動作，玩家必須進行一次【判定】，【判定】分為三個步驟：

1. 確定你的DP：
DP即dice pool，它決定了你在此次檢定中可以投幾枚D6。
1. 確定你的加骰等級：
加骰等級分為1級～3級，共3個等級，預設為1級，也就是當值骰結果符合[加骰等級表](#加骰等級表)時，可以追加投擲1顆額外的骰子，直到你無法再獲得新的加骰為止。
1. 擲骰判定：
擲相當於你DP數值的D6。如果一枚骰子的數值為5或6，則稱這枚骰子取得了1個成功。你取得成功的骰子的總數稱為「成功數」。
1. 計算成功數：
在進行判定後，只要擲骰結果中的有效成功數大於0（一些能力可能導致你扣除有效成功數並導致無法使用附加成功），便可以依據角色的能力、狀態等提供的「附加成功」數加總後計算出最終成功數。
1. 與目標進行對比：
閥值（下稱DC）是判定時的目標數值，判定的成功數大於或等於DC時，行動成功，成功數超出DC越多，行動越成功，反之則行動失敗。

:::info
有一些判定只關注自己的成功數，成功數決定他的行動做得有多好，例如一次攻擊造成多大傷害，一次奮力跳躍能跳多高等。DC取決於判定的形式屬於競爭還是對抗。
:::

---

### 加骰等級表

| 1級 | 2級 | 3級 |
| :--------: | :--------: | :--------: |
| 每投出2個「6」| 每投出1個「6」| 每投出1個「5」或「6」|

---

### 關於DC

DC有幾種不同的來源，可能來自於固定的DC或者與他人的對抗：

* 固定DC對抗：
固定DC的對抗是指DC是一個固定的，預先設定值的判定，例如你想舉起一袋米，跳過一個坑，爬上一堵墻等。
* 與他人對抗：
與他人對抗是指DC是一個由對手進行的判定成功數的判定，例如你想在跑步比賽中勝過某個人，你試圖將別人撞出幾米遠等。
* 主動對抗：
主動對抗是指你發動的對抗效果，例如你發起的擒抱或沖撞。
* 豁免：
在對抗中，被動進行的那一方的檢定行為，稱為豁免。這也意味著，不存在任何情況下主動進行的豁免。

:::warning
因為豁免是被動的，所以「進行一次意志豁免，並將成功數增加在你的攻擊DP中。」是無法成立的，因為豁免一定是個被動行為。如上文的主動動作應該使用「意志檢定」。
:::

---

### 機運骰

偶然地，因為某些原因，導致可以投擲的D6的個數為0或更低時，你仍然能投擲2D6，只有當這2顆骰子皆投出6的時候才會獲得一個成功數，並且此次成功能夠獲得2顆加骰，但是，在這個擲骰中投出2個1的話，就會遭到一定的不利影響（由ST設定），這稱之為大失敗。

這樣的判定，稱為機運骰。機運骰雖然名為檢定，但是實際上並非檢定，其不受到任何增加檢定DP或者檢定結果的能力影響，除非該能力擁有特殊說明。並且，若機運骰的檢定中已經投出成功，則加骰中投出1也不視為大失敗，後續獲得的成功數也會以普通的方式計算。

---

### 小數的計算

沒有特殊說明的情況下，當你得到小數時要無條件捨去小數點後的值。

### 乘法與加法

沒有特殊說明的情況下，在計算能力相關的數值時(不是價錢、距離之類真實存在的數字)，能力所提供的乘法型加值無法對加法型加值生效，且乘法型加值之間的計算方法為相加後減1。

>舉例：
>當你有1個2倍效果，1個3倍效果，1個4倍效果，1個加10效果時，計算公式如下：
>**最終值 = 基礎值 * [ 2 + (3-1) + (4-1) ] + 10**

---

# 《二、　建立人物卡》

要參與無限恐怖的游戲，首先你需要創造一張屬于你的，符合游戲規則的人物卡。

一張無限恐怖的人物卡分為六個大段，分別是「概念段」，「屬性段」，「衍生屬性段」，「技能段」，「專長段」，「能力段」。下面將詳細敘述每一段中的數據及數據的意義。

## 1.概念段

人物概念定義了人物的形象，背景，性格特征等扮演要素。

| 類別 | 說明 |
| :--------: | -------- |
| 角色名 | 角色的名字。(不一定要真名。) |
| 性別 | 角色的真實性別。 |
| 年齡 | 角色的真實年齡。 |
| 身高/體重 | 角色的身高與體重。 |
| 種族/國籍 | 角色的國籍，初始種族固定為人族。 |
| 語言 | 請見《[關於語言](#關於語言)》。 |
| 外貌/特徵 | 人物的外貌特徵，初始風度值為3或以上時可以設定為帥哥/美女。 |
| 性格 | 人物的性格。 |
| 概述 | 人物之前的簡歷和背景。 |
| 起源 | 請見《[關於起源](#關於起源)》。 |

---

### 關於語言

每種語言被視為對應一種專長，在建立人物卡時，人物會獲得【智力*2】的語言點數，這些語言點數能且只能分配在語言上，每點語言點數可以獲得或提升1級語言。

:::info
1. 智力為1的人物必須將他的語言點全部分配在他所選擇的母語上。
2. 語言并非專長，不使用通常專長的購買方法。
:::

:::warning
語言（1--5）：
特殊：語言可以復數擁有，例如漢語3，德語2，英語2。
特殊：人物的母語應該至少有2級。購買或提升1級語言需要1點語言點數，或1XP。

* 1級：基本的讀寫能力，至少可以辨認出和其他語言的不同。
* 2級：較為流暢的拼寫和閱讀能力，至少可以看懂報紙上的大部分文章。
* 3級：優秀的語言運用能力，成語俚語什麼的也難不倒你。
* 4級：連方言和語系演變都爛熟於胸。在購買同語系或語族的語言時，可以減少一半消耗。
* 5級：你可以開創一種新的語言，這種語言只有你可以傳授給別人，并且主神的翻譯機制對此無效。創造語言時，除了達到5級的這門語言之外，還可以把不超過智力上附加成功數種語言融入，所融入的語言必須至少也達到3級。破譯該語言的DC為所用到的所有語言專長等級之和，加上你智力上的附加成功數。破譯時為智力+相關調整DP的檢定。相關調整為破譯者擁有的破譯目標相關語言等級之和。創造語言本身不可以作為基準語言和融入語言。若你掌握了更多的語言，可以花費額外的15XP更新創造語言的DC。
:::

---

### 關於起源

起源，又稱之為「混沌衝動」。概念上類似原始本能，也類似宿命論。指所有事物，包括生命、在其起始之時已經有其方向性（因），然後必然會向著這方向發展。這以人類而言，這方向性會產生的就是一種原始的衝動，但仍有以後天生成的人格和智慧去壓抑的可能。但由於起源是遠在「根源之渦」已經決定了的方向性，所以是萬象萬物作為核心的絕對命令，縱使世世輪迴亦不能改變。

每位PC為自己的人物設置1個起源，依據自已的起源為自己的人物設置1個「衝動」和1個「角色特性」，這是角色在個性上的特徵。

* 每部影片一次，玩家的扮演符合人物的「衝動」時，他能將意志值恢復到最大值。
* 每個場景一次，玩家的扮演符合角色特性時，他能將意志值恢復1點。

> 舉例：
>> 起源：劍
>> 衝動：作為他人的劍（正義的夥伴）而活。
>> 角色特性：無法對求救的人視而不見（因為衝動為成為正義的夥伴導致）。
>> 角色特性（另一種設定法）：性格十分的耿直（就像劍一樣）。

---

## 2.屬性段

人物屬性定義了人物先天所具備的最為基本的能力，人物屬性分為九項，它們分別是對應三大類屬性（生理屬性，心智屬性，互動屬性）的三大方面（強度，靈活，抗性）。

| 生理技能 | 心智技能 | 互動技能 |
| :-----: | :-----: | :-----: |
| 力量 | 智力 | 風度 |
| 敏捷 | 感知 | 操控 |
| 耐力 | 決心 | 沉著 |

:::info
關於屬性的詳細說明，如何提升/降低屬性等，請見《屬性詳述》子節單獨說明。
:::

---

### 建立一張新的人物卡

1. 將人物的所有屬性基本值設置為1。
2. 將3點/2點/1點的點數分別分配給生理、心智、互動三類屬性。
3. 將點數加在對應種類中的各項屬性上。
4. 將3點自由點數任意加在想要提高的屬性上。

:::info
1. 若是要將一項已經加到4的屬性提升到5，需要耗費2點點數。
2. 普通人的平均屬性是2，上限屬性是5。
:::

> 舉例：
> 1.路人甲將所有屬性基本值設置為1。
> 2.他將3點分配給了生理，將2點分配給了心智，將1點分配給了互動。
> 3.在生理上，他將力量敏捷耐力分別提升到2，花去3點，在心智上，他將智力感知分別提升到2，花去2點，在互動上，他將風度提升到2，花去1點。
> 此時他的屬性是 力2/敏2/耐2/智2/感2/決1/風2/操1/沉1
> 4.他覺得有所偏重的不太好看，將剩下的3點分別分配給決心，操縱，沉著并將它們提升到2，於是結果，他的所有屬性都是2。

---

## 3.衍生屬性段

衍生屬性通常由人物的屬性，專長等決定，衍生屬性包含以下幾種：

| 類別 | 說明 |
| :--------: | -------- |
| 體積 | 普通成年人體積為5，體型嬌小者可以設定為4，僅有特殊專長者可以設定為6。 |
| 速度 | 表示人物的速度，大小為【力量+敏捷+體積】。這是你的基礎速度，速度的變化若無特殊說明，則一般是使用基礎速度做乘法和加法運算。 |
| 移動速度 | 表示一次移動動作能移動的距離上限，依【速度】查表決定，單位為公尺。 |
| 先攻 | 用以決定戰鬥中的行動順序，大小為【敏捷+沉著】 |
| 基本防御 | 用以決定人物的防御值（AC），大小為【敏捷和感知中較低者】，并具有【敏捷和感知中較高者的附加成功】。基本防御被認為是一種防御上的閃避加值。 |
| 生命值 | 大小為【耐力+體積】 |
| 意志 | 意志力是一個可以消耗以換取收益的點數，其上限為【決心+沉著】，是一個固定值。在某些資源中，會將意志力池稱為「意志值」，它們實際上是一種東西。意志力池中的點數被稱為「意志力」，具有特殊用法。 |
| 意志豁免 | 有些場合會需要使用意志豁免，常用于抵御心靈影響或精神傷害，意志豁免使用【決心+專注+意志】進行判定。 |
| 反射豁免 | 有些場合會需要使用反射豁免，常用于回避范圍攻擊，反射豁免使用【敏捷+運動+反射】進行判定。 |
| 強韌豁免 | 有些場合會需要使用強韌豁免，常用于抵抗生理影響，強韌豁免使用【耐力+生存+強韌】進行判定。 |

---

### 關於體積

一些能力或效果會使得人物的體型發生改變，這種超自然的變化會對人物產生肉體上的影響。更大的體型讓人物更加強壯，更加堅韌，步幅更大，也更加容易被擊中，具體影響請見《衍生屬性詳述》子節單獨說明。

### 關於生命值

生命值代表了人物的生命力，受傷會讓人物的生命值降低。人物生命值的計算方法見《衍生屬性詳述》子節單獨說明。此外，臨時的耐力或體積會帶來新的生命值，但在失去這些臨時耐力或體積時，會優先移除最接近完好的生命槽。

### 關於意志力

人物的意志力代表人物憑自己的堅定意志扭轉劣勢或改變現實的能力。

* 人物在進行一個行動時，若該行動不是延長動作且只需一次判定，可以以自由動作花費1點意志力，在該行動上獲得＋3DP的表現加值（本加值可與其他同類型加值疊加），這種用法對一次行動只能使用一次。
* 人物在戰斗時可以以反射動作花費1意志力，在防御上獲得＋2表現加值，持續一輪。
* 當人物因重傷、饑渴或類似情況而失去知覺時，可以以反射動作花費1意志力，使自己保持清醒1輪（若因重傷）或3小時（若因饑渴），這種用法每個場景只能使用一次。

:::info
如果你強制自己保持清醒，當保持清醒的時間結束你會立刻暈厥，即使你已經脫離了讓你失去知覺的狀態。因此方式進入暈厥后，你需要已經脫離了讓你失去知覺的狀態，并且在一個場景后才會醒來。并且，當人物因某種原因失去知覺后使用意志保持了清醒，在這之后又因傷勢加重等原因再次觸發昏迷的條件，則人物仍然會陷入昏迷。
:::

---

## 4.技能段

人物技能定義了人物後天學習所得的做某件具體的事的能力和技巧。
與屬性一樣，它分為三大類技能，也就是生理技能，心智技能，互動技能。

| 生理技能 | 心智技能 | 互動技能 |
| :--------: | :--------: | :--------: |
| 運動 | 學識 | 洞察 |
| 射擊 | 器用 | 隱秘 |
| 武技 | 手藝 | 表達 |
| 求生 | 專注 | 社交 |

:::info
* 生理技能：
生理技能不完全是純粹的技巧，許多技巧即使沒有知識，單靠自身的素質也可以進行嘗試。
**如果生理技能為0，你仍然可以嘗試進行判定，但是會失去三個成功數。**
* 心智技能：
心智技能是純粹的知識和技巧。
**如果心智技能為0，你無法進行對應判定，視為判定結果自動失敗。**
* 互動技能：
互動技能往往是技巧與知識的結合，與生理技能相似。
**如果互動技能為0，你仍然可以嘗試進行判定，但是會失去三個成功數，其中有一部分技能，甚至是一部分技能的一部分用法，ST可以認定為0時無法判定，視為結果自動失敗，例如表達（彈奏鋼琴）。**
:::

除了技能之外，每項技能下還細分無數個「專業」，以表現以特定方式使用技能。
「專業」通常也由ST和PC協商決定，在《技能詳述》子節中，我們列出了一些常用專業。

當玩家在技能下擁有專業時，在該技能符合該專業的用法時，專業會給你帶來等同于專業等級DP的專業加值，由于所獲為DP加值，專業加值無法讓你在不進行判定的用法上獲益。

---

### 建立一張新的人物卡

1. 將人物的所有技能基本值為0。
1. 將6/5/4點的點數分別分配給生理、心智、互動三類技能。
1. 將點數加在對應種類中的各項技能上。
1. 將3點自由點數任意加在需要的技能上。

:::info
初始人物卡的技能等級上限為3，但是可以通過相應的特殊專長將上限提高到4。技能0~2時提升一點消耗1技能點，2到3時消耗2技能點。
:::

* 獲得6個專業點，這些專業點可以將任意專業提升1級（也包括了從0提升到1的情況），但專業等級不能超過所屬的技能等級。

---

## 5.專長段

專長定義了人物一些特殊能力，它會讓人物在某些行動中獲益。
(請注意，專長與前文的技能專業是不同的。)

### 建立一張新的人物卡

你獲得5個專長點數，將5個點數分配在專長上。

> 購買專長的花費為每專長等級1專長點（例如當你需要購買冥想專長時，因為其最低等級就是2級，因此需要2個專長點）。
> 
> 大部分專長須逐級購買，少部分專長無須逐級購買，這些專長會額外說明。
> 
> 若專長有多個等級，你需要為每個等級花費等級×1點專長點數。許多高級專長可能需要較高的點數來獲取，還有些專長在一開始受到一定的購買限制。
> 
> 有一部分的專長僅能在創建新的人物卡時購買，詳見《專長子節－背景專長》。
> 
> 需要注意的是，人物卡的背景/概述是與特殊身份專長相對應的。如果你選擇獲得特殊身份，這意味著你可能經受過某些系統性的學習或訓練，或者有某些異于常人的特質（指特殊身份4）；如果你選擇不獲得背景特殊身份專長，則意味著你沒有經過某些系統性的學習或訓練，如果你還在某個技能上達到3級，以3級武技舉例，意味著你在沒有任何老師的教導下無師自通/自學成才，技術媲美專業格斗家。

具體的專長請見《專長子節》。

## 6.能力段

建立新人卡時，需要和ST協商帶入影片的物品，一般來說不能攜帶對應背景無法獲得的東西。

## 7.強化人物卡的方式

在無限恐怖游戲中，強化人物有兩種方式，一種是通過在影片中完成任務獲得獎勵點數，用獎勵點數獲取兌換來增強自己，另一種是通過在影片中歷練，通過時間和經歷來磨練自己。