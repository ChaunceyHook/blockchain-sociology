# 無大台

討論區塊鏈，離不開「去中心化」。一直認為這個 decentralization 的翻譯很差勁，幸好香港有個地道而且傳神得多的翻譯 —— 無大台。

### ‌無大台 有共識

‌每個人都說 decentralization，但每個人說的都不太一樣，它被詮釋成各種意思，引起各種誤會。把區塊鏈的 decentralization 解釋得最清楚的要算以太坊創辦人[ Vitalik Buterin](https://en.wikipedia.org/wiki/Vitalik_Buterin)，他 2017 年的《[The Meaning of Decentralization](https://medium.com/@VitalikButerin/the-meaning-of-decentralization-a0c92b76a274)》1，把 decentralization 解拆成架構、管治、邏輯三個維度分析，第一個可理解為多點，其次是分權，第三是得出不同結論。比如說，傳統企業設有一個總部、一個總裁、一個方向，所以三個維度都屬中心化，傳統企業是徹底的中心化管理方針。

‌又比方說 Facebook 網站，伺服器分布在世界各地以便當地用家快速讀取，但所有伺服器都聽命於中央，而數據保持一致，所以是多點但不分權，得出一致結論，這就是分佈式管理（distributed），也是最經常跟區塊鏈的去中心化概念混淆。分佈式管理可避免因單點故障（single point of failure）拖垮整套系統，但無助於系統性敗壞，比如 Facebook 總部指令出錯，伺服器即使遍布全球，都會一起出錯。很多人會有錯覺，誤以為分布愈廣就愈去中心，但系統的去中心程度是多點與分權程度的乘積，當後者為零，前者無論多大，乘積依然是零。如果數學無助你明白，不妨這樣理解，行政長官由 1,200 人委員會選出，但假如這些人全部聽命於一個權力中心，就算增加到 12,000 人都沒有區別；反而，一般陪審團只有幾個人，但只要產生過程真正隨機，已經相當去中心。

‌傳統智慧告訴我們，一群各有自由意志，散落在不同地點的人，自然會有各種想法與行動。但假如所謂「去中心化」指的是架構、管治、邏輯三方面都去中心，那無疑是一盤散沙，沒有討論的意義。區塊鏈之所以帶來革命性改變，正是因為能在多點和分權管理下，得到中心化的邏輯。這裏「中心化的邏輯」也是極爛的翻譯，因為中文有個簡單清晰的詞——共識。

‌無大台一詞源於香港的公民抗爭，對此不但港人十分重視，甚至國際社會都嘖嘖稱奇。無大台的重點不單是散落各區或是沒人領軍，更是背後的潛台詞：有共識——即使沒有總台，遍地開花，抗爭運動的訴求依然取得共識。

### ‌齊上齊落

‌既要無大台又要有共識，依賴的是 protocol，在技術的語境一般翻譯成協議，廣義則可理解為取得共識的機制。不單是數位世界裏伺服器之間需要傳輸協議才能溝通，物理世界中人類共處依賴的也是一層又一層共識機制，比如語言就是其中之一，沒有共同語言，雞同鴨講。共識機制內化到生活每個層面，我們不一定覺察，解拆開來可以這樣理解，《基本法》是基礎、其上有普通法、衡平法、條例、附屬立法和習慣法等，再往上還有約定俗成的道德律、公德、禮貌等。基礎是個相對的概念，如《基本法》下還有《中華人民共和國憲法》，更基礎的還有國際法，更更基礎的還有民主自由這些普世價值。中文常以「機器是死的而人是活的」來表揚處事靈活，套用在共識機制卻是，機器會牢牢依循既定的共識機制，一層一層永不逾越，物理世界中卻往往有人輸打贏要，任意詮釋社會共識，依仗權力及武力，胡作非為。‌

計算機科學史上，1982 年提出的拜占庭容錯機制（Byzantine Fault Tolerance，BFT）要處理的難題，以一句解釋，正是無大台共識機制。有關論文以拜占庭帝國軍隊作為類比，假設來自四方的幾個小隊需要攻入一座城堡，要成功，必須「齊上齊落」，要攻一起進，[要退一齊走](https://thestandnews.com/politics/%E4%BD%94%E9%A0%98%E7%AB%8B%E6%B3%95%E6%9C%83-%E5%A0%85%E6%8C%81-%E4%B8%80%E9%BD%8A%E8%B5%B0-%E6%95%B8%E5%8D%81%E7%A4%BA%E5%A8%81%E8%80%85%E5%86%92%E6%B8%85%E5%A0%B4%E6%AD%BB%E7%B7%9A-%E9%87%8D%E8%BF%94%E6%9C%83%E8%AD%B0%E5%BB%B3%E5%8B%B8%E9%9B%A2%E7%95%99%E5%AE%88%E8%80%85/)，一個都不能少。當時沒有電郵沒有手機，將領間只靠騎兵帶訊息，不但有延時，更可能中途被截殺，更甚者，被混入「鬼」。BFT 要解決的，就是在信任基礎的缺乏下取得共識，共同進退。

‌在區塊鏈的領域，BFT 有各種實現方式，最廣泛使用的是比特幣和以太坊的工作證明（[Proof of Work](https://en.wikipedia.org/wiki/Proof_of_work)），原理可以粗疏地理解為，眾人分別紀錄一段時間的內容並寫成區塊，然後解決一條數學難題，第一位完成的對眾人高喊：「我計算好久終於找到答案了，請按我的區塊，不信的話你來試試」，其他人於是同意使用該區塊；即使有人在相近時間提出另一區塊，只要跟隨者不超過一半，總體還是會按著共識，一個一個區塊走下去。比特幣工作證明的數學難題本身沒有意義，答案極難求得但容易核實，只能透過不斷試錯（trial and error）直至找出，因而浪費的算力，是比特幣需要消耗大量電力的原因。

‌為解決耗電及效率等問題，以太坊正改向權益證明（[Proof of Stake](https://en.wikipedia.org/wiki/Proof_of_stake)）發展，而沒有歷史包袱的新區塊鏈如 Cosmos、Facebook Libra 等，大都直接使用這種新機制。以讚賞幣區塊鏈（LikeCoin chain）的權益證明為例，新區塊的提案者質押讚賞幣作為背書，假如紀錄過去五秒內容更新的新區塊得到三分之二以上投票確認，符合拜占庭容錯機制，則採納為最新區塊，形成共識，否則提案者會損失部分讚賞幣，並由其他人重新提出新區塊。

### Proof of Love

‌回到無大台一詞的原有語境，反對《逃犯條例》修訂草案運動所演繹的，跟區塊鏈的運作如出一轍，整場運動沒有中央統領，各區連綿不斷、橫跨整個光譜的抗爭行動由不同年齡階層、信仰、背景的素人提出，一浪接一浪；不可能也不需要每一項行動都為所有人認可，但總體依然立足於有如憲法，奠基於《[金鐘宣言](https://www.inmediahk.net/node/1065302)》的五大訴求。‌

類似於解決數學難題和質押資產，抗爭者以行動證明對香港的愛和公義的執著，押上前途甚至安全，抑制了其他人另起爐灶的衝動，讓整體始終保持共識。反對《逃犯條例》修訂草案的無大台抗爭在全球前所未有，難以找到相關研究，我遂把這套共識機制稱為愛的證明，Proof of Love。

