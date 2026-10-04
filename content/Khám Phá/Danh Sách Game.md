---
publish: true
created: 2026-09-27T10:58
modified: 2026-10-04T01:09
---

> [!quote| txt-c] The Hidden Quest
>
> ```dataviewjs
> const folder = "Games"; 
> const notes = dv.pages(`"${folder}"`) .where(note => note.publish !== false);
>
> dv.paragraph(`Hội quán đã thu thập được tổng số trò chơi (bao gồm bản mở rộng) là **${notes.length}** `);
> ```

```dataviewjs
const folder = "Games"; 
const notes = dv.pages(`"${folder}"`) .where(note => note.publish !== false);
dv.paragraph(`Hội quán đã thu thập được tổng số trò chơi (bao gồm bản mở rộng) là **${notes.length}** `);
```

```tabsdown
tab: Level 1

| Ảnh Bìa                                                                                                                                                 | Tên                                                | Người Chơi | Thời Lượng | Thể Loại                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ---------- | ---------- | ------------------------------------------------------------------- |
| ![](https://cf.geekdo-images.com/bLintO18LwPlMoA0DiC05Q__itemrep@2x/img/2lSVklnEnriOa-L1hE5tOA8-0tw=/fit-in/492x600/filters:strip_icc()/pic8954964.png) | [[Games/Gwent.md\|Gwent: The Legendary Card Game]] | 2-5        | 20 phút    | <ul><li>Cardgame</li><li>DeckBuilding</li><li>Chien_Thuat</li></ul> |


tab: Level 2

| Ảnh Bìa | Tên | Người Chơi | Thời Lượng | Thể Loại |
| ------- | --- | ---------- | ---------- | -------- |

tab: Level 3

>[!danger|ttl-c txt-c] Nhắc Nhở: Nhân viên hội quán sẽ không hướng dẫn game level 3

| Ảnh Bìa | Tên | Người Chơi | Thời Lượng | Thể Loại |
| ------- | --- | ---------- | ---------- | -------- |


```
