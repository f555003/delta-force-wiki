# delta-force

---
## 更新資訊
- [更新內容](./release-notes.md)

## 遊戲設定
### 1. 鍵/鼠操作優化
- **鍵位設定**: 
    - (暫無內容)
- **個人滑鼠設定**: 
    - 外部靈敏度：`1300 DPI`
    - 遊戲內靈敏度：`3`

### 2. 彈道調校專題 (`sy想睡觉了`)
> 💡 **核心邏輯**：透過調整係數，將彈道分佈從散亂的「圓圈/人字」收束為精準的「米/1字」。

#### 🎯 彈道分佈診斷
- ❌ **不合格**：彈道呈 `圓圈` 或 `人` 字型。
    - *原因：容易脫離控制。*
- ✅ **合格**：彈道呈 `米` 或 `1` 字型。
    - *原因：適合手腕聯動手臂操作。*

#### ⚙️ `建議`參數設置
- **滑鼠靈敏度**：`3`
- **垂直係數**：`1.0` ~ `1.2`
- **水平係數**：`0.7`

#### 🔬 彈道收束演算法
$$\text{垂直係數} \le \text{水平係數} \times 1.4$$

> ⚠️ **調校心得**：
> 當 $\text{垂直} > \text{水平} \times 1.4$ 時，彈道會因為垂直補償過度，導致極難控制橫向位移。

#### 🔗 參考來源
- [完美的灵敏度怎么调？全网最专业的導師來教你！](https://www.bilibili.com/video/BV1xMS9BnEE8/?t=74.6) — `sy想睡觉了`
- [三角洲控枪神术细节之无后座](https://www.bilibili.com/video/BV1S6wXzXEKz/?spm_id_from=333.1387.homepage.video_card.click&vd_source=3e6241ea6065bcf4f9a52bba4006255b) — `sy想睡觉了`
---
### 3. 特殊流派設定
- **光速開鏡流**: S8賽季因為實施了`開精開火`同鍵位，`操控拉到160ms`導致開火會快速拉槍，近乎於腰射

#### 🔗 參考來源
- [11万光速流勇士 鼠鼠必学的粑粑神枪 得吃400万！【三角洲行动】](https://www.bilibili.com/video/BV1LDQcBfEXM/?vd_source=3e6241ea6065bcf4f9a52bba4006255b) — `库特菌`

## 💡 角色人物
### 🔗 角色操作與細節 (影片連結)

* **攻擊位**
    - (暫無內容)
* **支援位**
    - (暫無內容)

* **工程位**
    - **牧羊人(老黑)**
        - **推薦主播:**
            [库特菌](https://space.bilibili.com/69307?spm_id_from=333.337.search-card.all.click)

    - **比特**
        <details>
        <summary>无人Noone</summary>

        - [全网最详细比特焚决！一期视频让你从0成为团队中的全能高手](https://www.bilibili.com/video/BV1jLD9BzEug/?vd_source=3e6241ea6065bcf4f9a52bba4006255b)
            - **重點紀錄**：03:24 應用玻璃無線延伸的特性來遠距離使用煙霧/小蜘蛛。
        </details>
    - **深藍**
        - **推薦主播:**
            [Haruka_遙](https://space.bilibili.com/15362534?spm_id_from=333.337.search-card.all.click)

        
        - **小技巧教學**
            <details>
            <summary>三角洲丢包尊者</summary>

            - [【全网首发】深蓝改键100%实现31切枪技巧，看完人人都会](https://www.bilibili.com/video/BV1nxcDz8ERd?vd_source=3e6241ea6065bcf4f9a52bba4006255bspm_id_from=333.788.player.player_end_recommend&trackid=web_related_0.router-related-2479604-d9wfs.1776223841167.507)
            </details>

            <details>
            <summary>Ghost_Wolf_L</summary>

            - [哈基盾：盾这下真牛大了](https://www.bilibili.com/video/BV1WbwKzyErh/?spm_id_from=333.337.search-card.all.click&vd_source=3e6241ea6065bcf4f9a52bba4006255b)
                - **時間戳記**：00:00 31切槍，預設切換到1號武器:1,切換到2號武器:2；把設定都改到 1，就可以實施31切槍，需求是`兩把武器` & `主武器要放在2號武器欄位`
                - **時間戳記**：00:33 一鍵防抬手，需求是`大招` & `戰術道具 1 or 2`一同綁定即可，推薦`大招` & `鉤爪`互綁。
                - **時間戳記**：00:48 一鍵開合盾(`基於一鍵防抬手設定`)，需求是`大招` & `戰術道具 1 or 2` & `空出來的武器欄位` 一同綁定即可。
                - **`額外注意事項`**：`大戰場無法使用一鍵31切槍`。
            </details>

            <details>
            <summary>隔心GX</summary>

            - [仅需按一个键的深蓝31切枪和扇贝盾教学！手残党最狂喜的一集！](https://www.bilibili.com/video/BV1wbD1BZEsQ/?vd_source=3e6241ea6065bcf4f9a52bba4006255b)
                - **時間戳記**：01:01 31切槍。
                - **細節說明**: 預設切換到1號武器:1,切換到2號武器:2；把設定都改到 1，就可以實施31切槍，需求是`兩把武器` & `主武器要放在2號武器欄位`
                - **時間戳記**：03:09 一鍵扇貝盾。
            </details>
        

* **偵查位**

---
## 三角洲行动固排干员搭配公式 (`骑士小饼`)

* **健康隊伍搭配**
    - 一號位/兼職指揮: 威龍/駭爪
    - 偵查位: 駭爪/露娜
    - 煙位: 紅狼/蜂醫/蠱/烏魯魯
    - 投擲位: 紅狼/牧羊人/烏魯魯/露娜

---
## 槍械資訊
- [改槍碼庫](./weapon_codes.md)
- [槍械賽季排行](./weapon-stats)