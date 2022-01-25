# 裝備

[AoW Ideas 計畫](https://github.com/nefarious-kitsune/aow.ideas):
*玩家一些能幫助使遊戲更有趣的修改與改進的想法。*

[English](equipment)

## Problem

遊戲必須不斷發展以保持課長玩家的興趣。 在17級英雄和10級士兵推出後，
到下一次「大升級」只是時間問題：

- 20級英雄和/或11級部隊
- 另目前最強的士兵失色的新士兵
- 另目前最強的英雄失色的新英雄

每次發生這種情況，一些開發者希望留下的老玩家都會灰心喪氣而離開。 
我們需要一種替代方法來引入品種，而不會疏遠資深玩家。

目標：

* 允許個性化的軍事風格
* 保持遊戲平衡

## Suggested Solution

* 新的遊戲物品，「盔甲」，允許玩家「個性化」他們的軍隊。
* 盔甲會同時「加強」和「削弱」玩家的軍隊，所以這不單純只是升級
* 盔甲影響速度、力量、和防禦
    - **阿爾塔斯之盾**：為軍隊裝備重型防護裝備，但拖慢軍隊速度
    - **赫拉克勒斯之刃**：為軍隊裝備強大的武器，但也會降低護甲
    - **奧德修斯之靴**：為軍隊裝備超輕裝甲以提高機動性


| 盔甲      | 加強    | 削弱  |
| --------- | ------ | ----- |
| 阿爾塔斯   | +防禦 | -速度   |
| 赫拉克勒斯 | +攻擊 | -防禦   |
| 奧德修斯   | +速度 | -攻擊  |
| 普通      | 無 | 無 |

新物品將允許最終遊戲玩家強調他們軍隊的某些方面（速度、力量或坦克），
同時也允許發展中的玩家在不失去競爭力的情況下維持自己的路線。

### 實施和玩法

- 將「英雄」頁面更改為「學院」頁面，用於存取英雄、部隊和裝備
- 裝備也是卡片。合併兩個 1 級盔甲創建一個 2 級盔甲
- 2 級盔甲比 1 級盔甲具有更高的加強/削弱。 例如：

|盔甲       | 加強    | 削弱  |
| ----------- | ----------- | ---------- |
| Lvl 1 阿爾塔斯 | +2% 防禦 | -5% 速度  |
| Lvl 2 阿爾塔斯 | +3% 防禦 | -7% 速度  |

- 玩家可能需要保持不同等級的盔甲，並找到適合自己風格的合適等級
- 在戰鬥畫面上，每個玩家的頭相片下方都會出現一個盾牌圖標。
- 點擊圖標以顯示盔甲的數據。
- 盔甲的能力是被動的，適用於所有玩家自己的單位
- 盔甲的能力對對手的軍隊沒有影響