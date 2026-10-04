---
publish: true
created: 2026-10-05T00:00
modified: 2026-10-05T00:00
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
