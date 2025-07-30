# Unity.MG
# 霛清義莊AKA小心地板很滑 更新日誌

## [1.0.7] - 2025-07-30 (中文)

### 提醒

* 請務必備份你的世界存檔、Xaero 的資料夾，以及 options.txt 檔案，以防萬一！

### 更新內容

* 感謝 councilfarciminis2，新增了一個靈感來自《流亡黯道 PoE 試煉》的大型方尖碑競技場。
* 新增了大量食物的食用支援及與 Mine and Slash 的兼容性（包括 Cuisine Delight 模組）。感謝 Helester 和 councilfarciminis2！
* 將夜巫（Night Lich）與黑曜石石靈（Obsidilith）的生成位置由 The Otherside 改為 The End。
* 大幅降低老鼠與骷髏僕人的生成率。
* 豐收任務（Bountiful）的經驗獎勵提升了 50%。

### 修正內容

* 修正 Awful Ghast 錯誤地掉落 Nether Keeper 戰利品的問題。
* 修正在地圖中未獲得傳送器道具（teleporter item）問題，除非為 OP 身分。
* 修正「暴擊施放旋風斬（Cyclone on Crit）」真的會從怪物身上施放的問題。

### 模組更新

* 更新 EnhancedAI、FTB Library。

## [1.0.6] - 2025-07-24

### 提醒

* 請務必備份你的世界存檔、Xaero 的資料夾，以及 options.txt 檔案，以防萬一！

### 更新內容

* 新增一個可使用道具，在地圖中可將你與最近的盟友傳送至 Boss 傳送方塊。此道具在離開地圖維度時會被移除。感謝 DubleDice！
* 組隊額外經驗獎勵由 20% 提升至 50%。兩人組隊時，原本為 120% 經驗除以 2 = 60%，現在為 150% 除以 2 = 75%。
* 增加許多天生具有異常狀態機率的技能觸發率，特別是多段攻擊類型。
* Glacial Phoenix 的每個冰塊傷害區域減少約 33%。
* Ice Comet 傷害下調約 5%。
* Frost Nova 的心型粒子特效數量降低。
* Phase Dive 魔力消耗下降。
* Fury 圖示稍作修改，與 Combo Extender 做出區別。
* 傷口效果（Wounds effect）現在給予 +15% 流血觸發機率，並降低 10% 流血抗性，不再是 -50% 自身治療效果（怪物本身不太會治療）。
* 獵人藥水（Hunter's Potion）不再需要使用遠程武器。
* 獵人藥水冷卻時間由 45 秒降至 20 秒。
* 惡靈（Vexes）現在總是以普通稀有度生成。
* 將「地獄守護者（Defenders of the Nether）」任務拆分為兩個任務，各對應一個 Boss，並新增結構示意圖（感謝 Kythulu！）。
* Act I 新增介紹小鬼盔甲修飾（Kobold Armor Trims）任務。
* Act II 新增介紹 Netherite 升級與殘餘堡壘（Remnant Bastion）的主線任務。
* 石英現在能提供更多採礦經驗。
* 關閉 Supplementaries Flower Box 的簡易模式，現在可放置多個高花於單一區塊中。
* 預設關閉 Xaero 地圖中的花朵顯示功能。
* Garnet 與 Amber 方塊的強度權重略為調整降低。
* 現在無法再獲得腐化樹苗與腐化史萊姆球。Garbush 種子可透過 Amber 與 Garnet 方塊取得。
* 移除 Bonwiltia，並將 Dyespria 種子掉落更換為 Dyescrapia，Dyescrapia + Acidripia 種子掉落位置由 Amber 改為 Garnet 方塊。
* 根據上述更動，全面重製 Sniffer Flowers 任務線。
* 新增轉換合成配方，將各種鵝卵石/沙子變回原版鵝卵石/沙子。感謝 Sainguin！
* 因為漏洞問題，停用 Red String Container 與 Tiny Planets。
* 現在可以透過特殊配方合成普通與長滿苔蘚的傳送石（Waystones）。
* 傳送石的製作成本大幅降低。
* 懸賞憑證（Bounty Slip）獎勵翻倍。
* 削弱地圖分解獲得資源的輸出。
* Kami 點心（Kami Treat）製作成本下降。
* 移除 MNS 功能中心中的「所有盟友（ALL ALLIES）」選項，因其效果與預期不符並造成大量混淆。
* 更新 MCA 守衛清單，現在他們會攻擊 Born in Chaos 的怪物。感謝 Kuktar！
* 官方伺服器現在每日會重置地圖/Harvest/Obelisk 維度，感謝 Poe！

### 修正內容

* 修正在「應該衝浪（Should Surfing）」模式中無法互動的按鈕問題。相機現在也會正確地與玩家脫離，除非手上持有武器或可投擲物品。
* 修正物理轉元素的混沌/腐化屬性沒有正確實裝的問題。
* 修正 Awful Ghast 偶爾不掉落物品的問題。
* 移除設定選單中的遺留按鈕。
* 解除 ChatPlus 的偷看鍵（peek key）綁定，因為存在衝突。
* 移除 Sewer2 地圖中的錯誤指令方塊。
* 修正 Mansion 地圖中怪物卡住的問題。
* 移動 Aztec 地圖中導致怪物生成在牆內的 Harvest 生成器。
* 修正魔像的內建法術觸發機率未運作問題。
* 修正 Daw 與 Bri 符文在 Blue Skies 維度中無掉落問題。
* Ferrous Wroughtnaut 任務現在應更容易完成。
* Caught in the Web 任務現在應更容易完成。
* 修正 Hemorrhager 圖示缺失。
* 修正 80-99 等級的飾品配方出現空氣的問題。
* 修正 Windfury 符文語 Cyclone 被敵人施放的問題。
* 修正 Cabbage Wrapped Elder Guardian 沒有食物屬性的問題。
* 停用某些導致問題的 MCA 自訂內容。
* 修正 Night Lich 塔未生成的錯誤。
* 修正部分 Unique 掉落未遵守最小等級限制的問題。
* 修正 Phase Dive 有擊退效果（應無擊退）的問題。
* 修正 Campaign 商店與獎勵中吸血寶石（Leech gems）名稱錯誤。
* 從 Blessed Aim 移除 Offensive 標籤（不該有）。
* 對 Obsidilith 競技場進行修改，應能改善部分生成問題。
* 嘗試減少天賦樹（Talent Tree）延遲。
* 修正自然地牢 Uber 競技場的怪物生成。
* 移除錯誤的磨刀石裝備製作配方。
* 修正 Harvest 活動任務描述錯誤。
* 修正雷霆魔像（Lightning Golem）會施放 Frost Nova 的問題。
* 修正某些向量運算仍在 KB 關閉時生效的問題。

### 模組更新

* 更新 Crafting Tweaks、Default Options、Dungeon Realms、EnhancedAI、EntityJS、FancyMenu、GeckoLib、Inventory Essentials、MCA、Mine and Slash、More Sniffer Flowers、Remnant Bosses、RoE Weapons、Sophisticated Backpacks、Xaero's。
* 新增 EMI Ores。
* 新增 Dimensional Threading。

## [1.0.2] - 2025-05-26

### 更新
- 增加了一系列可選符文獎勵作為戰役任務獎勵。
- 全面降低了擊殺任務所需的擊殺數，約 25-30%。
- 增加了寶箱中符文的機率，目前約為 15%，高於先前的 10%。
- 地圖預設包大小增加了約 33%。
- 方尖碑怪物刷新率大幅提升（增加了一倍以上）。
- 方尖碑獎勵現在包含更高的符文獲得幾率，以及更高的高級符文獲得幾率。這是遊戲早期獲取高級符文的少數來源之一。
- 大幅提升預言幣的掉落率。
- 預言獎勵已重製。低稀有度物品的出現頻率降低，價格也降低了。現在，你在任何等級都能遇到傳奇及更高稀有度的物品，而不再僅限於高等級地圖。傳奇稀有度獎勵現在從20級開始出現，神話稀有度獎勵從40級開始出現，而不是60級以上。
- 獨特物品掉落率翻倍。
- 新增地圖預言詛咒，可降低玩家所受的疾病傷害。
- 地圖詞綴原本賦予怪物額外元素傷害，現已改迴轉換。不過，它們現在也會獲得該元素的額外傷害。
- 地圖詞綴對非預言元素的抗性懲罰翻倍。
- 收割怪物的生成數量減少 25%。
- 重製遺物。地圖上可添加的遺物數量已減少，但詞綴已大幅增強以彌補此缺陷。您可以擁有 1 個「收穫」遺物、1 個「遠古方尖碑」遺物以及 3 個「礦井與砍擊」遺物。
- 地下城領域遺物已併入基礎「礦井與砍擊」遺物。
- 新增了一個可增加地圖中預言幾率的遺物。
- 整理了部分遺物和屬性的在地化資訊。

### 修復
- 修復了不可破壞的煤炭問題。
- 修正了部分收割模式的刷新問題。
- 修復了砂岩Boss房間陷阱問題。
- 修正了部分缺少的靈魂修改器在地化問題。
- 嘗試修復深淵Uber房間的問題。
- 修正了藍天Boss有時不會掉落戰利品包的問題。

### 模組更新
- 更新了AmbientSounds、EntityLootDrops、Euphoria Patches、JEI、InsaneLib、NirvanaLib和Sophisticated模組。

  
## [1.0.1] - 2025-05/09
### 修改 (測試階段)
- 刪除 投影設備
  
  
## [1.0.0] - 2025-05/08
### 新增 (測試階段)
- 塔羅牌！。
- 東方女僕(右鍵可下載自訂音效及資源)及更多功能。 
- 更豐富生態系(雪地有企鵝)！。
- 等價交換。
- 英翻中模組 (部分有支援)。
- 投影設備 (支援youtube)。
- 測試階段 ！テストフェーズ！。  
  
  
## [0.9.3b] - 2025-05/04
### 更新
- 筆記！如果您在加入地圖維度時遇到問題，則需要執行“/dungeon_realm wipe_world_data”，關閉伺服器，然後刪除 dungeon_realm 的維度資料夾。
- 新武器類型：苦無！這些基本上是每 2 秒可以發射一枚彈頭的匕首。
- 現在您可以透過滑鼠中鍵點擊查看其他玩家的構建或分享您自己的構建！
- 早期添加了解釋古代方尖碑的任務。
- 更新了地圖的任務說明。
- 無限附魔不再適用於非基本箭。
- 出血遊戲改變者不再造成固定的致命一擊。
- 感染遊戲改變者現在造成的疾病傷害增加 15%，而不是 20%。
- 地圖陰影中的實體不再會掉落其預設戰利品。他們仍然會掉落硬幣以及挖掘和砍殺戰利品。
- 減少地圖怪物密度以抵消怪物生成半徑的修復。
- 增加了天賦樹的搜尋關鍵字。
- 在箱子中添加了「快速掠奪」按鈕，可讓您將物品移動到主包中。
