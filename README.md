# 盡可能簡單明瞭(但不如計畫)的新手MTGA完整指南

> As Short As Possible (Not As Short As Planned) Unabridged Beginner’s Guide to MTG Arena

## 著作權聲明

本指南由[/u/localghost](https://www.reddit.com/user/localghost)撰寫(編寫)，[原文](https://sites.google.com/view/asap-bg-to-mtga/home?authuser=0)經作者本人同意翻譯。此翻譯版本由bachelorwhc製作，未經授權請勿任意轉載，由於個人外語能力有限，如有錯誤或建議歡迎來信[bachelor.whc@gmail.com](mailto:bachelor.whc@gmail.com)。

## 免責聲明

這份指南假設你知道什麼是紙牌集換遊戲，並對魔法風雲會有基本的認識。如果你需要了解或複習，可以先看看附錄A，如果你想把MTG玩得更好則看看官方的[Level One專欄](https://magic.wizards.com/en/articles/archive/level-one/level-one-full-course-2015-10-05)或附錄C。

本指南已假定玩家知道什麼是卡牌遊戲，對魔法風雲會已有基本的認知。若玩家需要了解或溫習，請先參閱附錄A。若想把MTG玩得更好請參閱官方的[Level One專欄](https://magic.wizards.com/en/articles/archive/level-one/level-one-full-course-2015-10-05)或附錄C。

## 翻譯說明

- 雖然魔法風雲會(MTG)有繁體中文與簡體中文版，但本翻譯是服務MTGA玩家。故縱使系列名稱已有官方中文名稱，但本翻譯仍以原文表記方便玩家對照遊戲介面。除此之外與遊戲介面、文字相關的內容將視情況保留原文(除非未來威世智加入中文語系)

- 為求便捷，稀有度表記Common為鐵牌、Uncommon為銀牌，Rare為稀有、Mythic為秘稀

- 部份原稱過長且縮寫在英語圈極常使用的用詞不翻，以便日後玩家搜尋資料或理解。例如：ICR(Individual Card Rewards)

- 部份英文名稱縮寫的用詞不翻，以便日後玩家搜尋資料或理解。例如：ICR(Individual Card Rewards)

- mana官方翻譯為「魔法力」，本翻譯大部分簡稱為法力。tap land正式翻譯應作「橫置地牌」，本翻譯則採一般中文玩家簡稱轉地
->不予評論 個人覺得這句不是很必要 要加的話不要打大部分 官方翻譯跟正式翻譯請選一個打 或是這樣  tap land在此指南採中文玩家簡稱的轉地 (之類的)

- 系列(set)跟環境的差別：新手可能會納悶什麼是系列什麼是環境，在以前MTG同一故事背景──也就是環境可能會發售二到三個系列，第一個發售的系列會定調該環境的風格與機制，第二個以後發售的系列稱為擴充系列，在限制賽中通常會與第一個系列組合遊玩以讓機制運作起來。在近期威世智決定不再發售擴充系列，日後每個系列都能獨立運作；環境賽(只能使用二到三個系列的牌張)也就被系列賽取代。因此目前**環境**大多指賽制整體牌池，例如標準賽制中包含的所有系列稱為標準環境，方便討論在該賽制內遊玩可利用的機制與遊戲速度、牌張強度。

- 未來發展<br/>本指南作者[/u/localghost](https://www.reddit.com/user/localghost)更新相當頻繁，對較晚加入的新手來說是情報較為正確亦對應當前版本。在徵求翻譯權時，作者希望中文語系的玩家未來能看到的不光是單純的翻譯版本，而是由中文玩家共同經營更新的創作。<br/>敝人著實感動也受啟發，在初版翻譯結束後，應當交由玩家們基於本指南共同編輯創作，營造更活躍友善的遊戲境。

//文章越短越好 不用加過多贅詞

## 我適合這款遊戲嗎？猶豫不決的你應該知道的事

- Arena是一款**真正**的MTG遊戲，但他聚焦在標準賽制與Ixalan以後的核心與擴充系列。Arena的永恆賽制稱為Historic，以增加歷來的系列為特色

- Arena是一款**真正**的MTG遊戲，他聚焦在標準賽制與Ixalan以後的核心與擴充系列。Arena的永恆賽制稱為Historic，特色為增加以往的系列來遊玩。

- Arena只有單挑。不排除未來增加其他遊戲模式或過去系列與其他永恆賽制的可能性，而什麼時候實現看來遙遙無期。先驅賽制的牌池正逐漸地補足，但補完的計畫仍未明瞭

- Arena只有單挑。未來不排除會增加其他遊戲模式或其他賽制的可能。先驅賽制的牌池正逐漸補足，但補完的時程仍未明瞭。
//賽制跟過去系列應該算同一個系統(?


- Arena是一款免費遊戲，自然也存在一般免費遊戲的經濟模式。你不需要一開始就湊齊所有的卡片，想要湊齊所有卡片不是需要消耗時間就是花費金錢(或兩者皆需)

- Arena是一款免費遊戲，也存在一般免費遊戲有的經濟模式。玩家不需要一開始就湊齊所有卡片，想湊齊卡片需要消耗時間或花費金錢。
//這裡的大意應該是不用課金也能玩吧，大部分有在課金的中文玩家應該都知道這種道理，不用打的這麼文謅謅，這邊應該有更好的打法，例如說這遊戲不用課金也能遊玩，只是要迅速收集卡片就要課金之類的

- Arena不是Pay-to-Win(譯註：付費者勝)，而是花錢讓遊戲進度加快。一個每日遊玩的免費玩家根據賽場環境需要一到兩個月不等的時間組出一套競技套牌
                                                                         無課

- 輪抽可以是玩家參與(但與不同組別對決)也可以是bot參與(與玩家對決)
            玩家對戰                       NPC對戰或電腦對戰


- Arena的卡片是無法與玩家交易的，你無法兌換成虛擬或現實貨幣。交易帳戶是違反使用條款的

- Arena的卡片禁止玩家之間的交易，也禁止兌換成虛擬或現實貨幣。擁有交易帳號會違反使用條約。

- Arena中同等稀有度的獲取成本是相同的。這意味著實體牌中"經濟"套牌在Arena裡不見得比較便宜，那些有趣狂野的組合技套牌也有可能跟競技套牌一樣難組

- 總而言之，MTGA可以是免費(或說比實體便宜不少)遊玩MTG的平台，也是官方長期經營和推廣標準賽制、電競的遊戲

//總之，MTGA是免費遊玩MTG的平台，也是官方長期經營和推廣的標準賽制、電競的遊戲


- Windows平台的Arena可透過Wizards of the Coast或Epic Games Store下載。MacOS版本從2020年6月起只能由Epic Game Store安裝。行動裝置(版)預計於2020年底以前上線，在那之前可以使用Steam Link作為替代方案



## Contents

Preface. Brief answers on the hottest questions people ask when (re)starting
What to do first? — How to get cards? — What to spend on? — What is Standard? — and more

1. [開始玩Arena](1.md)

2. [賽制與活動、模式簡介](2.md)

3. [進行對決](3.md)

4. [獲得卡片](4.md)

5. [組一副更好的套牌 \[進階\]](5.md)

6. [深潛 \[進階\]](6.md)

Appendix A. Introduction to MTG
Overview — Card types — Combat — Stack — New sets and rotation — Sideboard

Appendix B. Some common slang
Color combinations — Mechanics and effects — Dual-color lands — Various

Appendix C. Third-party tools, learning materials, and other resources
Collection trackers and overlays — Understanding Magic — Getting better at Limited — Tools to build your own deck

Appendix D. Major MTG Arena changes timeline
