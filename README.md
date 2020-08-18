# 【崩壞3rd】詞綴收益計算
## 適用對象
物理輸出角色  
>**tips:**  
>元素傷害不會爆擊，所以元素角色不考慮會心跟爆擊傷害詞綴  

回復能量或其他功能型詞綴請依自己需求來選擇  

## 說明
- 女武神等級：默認80等，非80可自行更改  
- 攻擊、會心：就是基本屬性上的數值(包含舊詞綴)  
- 爆擊率、爆擊傷害：包含隊長技能、被動技能、武器、聖痕、勳章、隊友輔助、神之鍵等 (點`加總小幫手`可以輔助計算)  
- 最終爆擊率：會心轉換的爆擊率跟爆擊率加成的總和  
- ![詞綴](https://tsuna01t.github.io/honkai-impact-affix/img/VEL03.png)：詞綴  
- 新詞綴期望提升：依爆擊期望計算相比舊詞綴的提升

## 攻擊型詞綴一覽
|最高數值| 
|----|
|機械角色裝備時提升23點攻擊力|
|生物角色裝備時提升23點攻擊力|
|異能角色裝備時提升23點攻擊力|
|量子角色裝備時提升23點攻擊力|
|雙槍、騎槍角色裝備時提升23點攻擊力|
|太刀、十字架角色裝備時提升23點攻擊力|
|重砲、鐮刀角色裝備時提升23點攻擊力|
|大劍、拳套角色裝備時提升23點攻擊力|
|提升19點攻擊力|
|提升13點會心|
|提升5.6%爆擊傷害|

## 會心轉換爆擊率公式
                    會心
    爆擊率 = ───────────────────
              女武神等級*5 + 75
