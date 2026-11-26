# BIM Muhandis MCP — oxirgi versiya

## 1.13.0 (26.11.2026)

BIM Muhandis MCP — AI ilovalar (Claude, ChatGPT, Gemini, Microsoft Copilot, Grok, Kimi, Qwen, Meta Muse, DeepSeek, Perplexity, Cursor, Windsurf, LM Studio, Cline) uchun Revit, AutoCAD / Civil 3D, Navisworks, Tekla Structures, SketchUp, LIRA-SAPR, SCAD Office, SAP2000 / ETABS, Robot, SOLIDWORKS, Photoshop, CorelDRAW 2022–2027 va Word / Excel / PowerPoint ulagichi.

O'rnatish: ZIP'ni chiqarib oling → «BIM Muhandis MCP - O'rnatish.exe» → Claude va Revit'ni qayta oching. AI ilovalar o'zi ulanadi. To'liq o'chirish: «BIM Muhandis MCP - O'chirish.exe».

- Kod himoyasi — server (BimMuhandisMCP.exe) ichidagi matnlar va mantiq shifrlanadi (string encryption): dastur dekompilyatsiya qilinsa ham kodni o'qib, ko'chirib yoki nusxalab bo'lmaydi. Nomlar o'zgarmaydi, shuning uchun C# skriptlar (rvt_run_csharp), tool'lar va yangilanish avvalgidek ishlaydi
- Checkpoint (saqlash nuqtasi) — rvt_checkpoint_save: katta o'zgarishdan oldin model saqlanib, nusxasi «_BM_checkpoints» papkasiga qo'yiladi (oxirgi 10 ta); rvt_checkpoint_list — ro'yxat; rvt_checkpoint_open — nusxani alohida ochish (asosiy model o'zgarmaydi)
- Claude, ChatGPT va Gemini'ga endi ~160 ta tool to'g'ridan-to'g'ri ko'rinadi (oldin 80): modellash, armatura, varaq, o'lcham, spetsifikatsiya, eksport va tekshiruv tool'lari qidiruvsiz chaqiriladi
