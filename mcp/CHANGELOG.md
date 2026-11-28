# BIM Muhandis MCP — oxirgi versiya

## 1.15.0 (28.11.2026)

BIM Muhandis MCP — AI ilovalar (Claude, ChatGPT, Gemini, Microsoft Copilot, Grok, Kimi, Qwen, Meta Muse, DeepSeek, Perplexity, Cursor, Windsurf, LM Studio, Cline) uchun Revit, AutoCAD / Civil 3D, Navisworks, Tekla Structures, SketchUp, LIRA-SAPR, SCAD Office, SAP2000 / ETABS, Robot, SOLIDWORKS, Photoshop, CorelDRAW 2022–2027 va Word / Excel / PowerPoint ulagichi.

O'rnatish: ZIP'ni chiqarib oling → «BIM Muhandis MCP - O'rnatish.exe» → Claude va Revit'ni qayta oching. AI ilovalar o'zi ulanadi. To'liq o'chirish: «BIM Muhandis MCP - O'chirish.exe».

- SOLIDWORKS 2022–2026 — to'liq modul: 7 ta o'rniga 140+ tool (sw_*). Eskiz bitta chaqiruvda (chiziq, aylana, yoy, to'rtburchak, ko'pburchak, paz, spline; o'lcham va bog'lanishlar), elementlar (ekstruziya, kesish, aylantirish, sweep, loft, fillet, faska, qobiq, uklon, qovurg'a, teshik/zenkovka/rezba, spiral), yordamchi tekislik/o'q/nuqta, chiziqli/aylanma/eskiz bo'yicha massiv, ko'zgu, ko'p jismli amallar
- yig'ma: komponent qo'shish va joylashtirish, sopryajeniyalar (coincident, concentric, distance, angle, parallel, tangent, lock, symmetric, width, gear), komponent massivi, kesishish tekshiruvi, portlatilgan ko'rinish, tarkib (BOM)
- 2D chizma: modeldan GOST bo'yicha ko'rinishlar (birinchi burchak proyeksiyasi, masshtab GOST 2.302 qatoridan avtomatik), kesim, detal ko'rinishi, o'lchamlar, markaz belgilari, yozuv, tarkib jadvali va pozitsiyalar, varaqlar va formatlar
- eksport/import: PDF (barcha varaqlar), DWG/DXF (1:1, qatlamlar bilan; listovoy metall yoymasi), STEP, IGES, Parasolid, ACIS, STL, 3MF, IFC, eDrawings, 3D PDF; papkani ommaviy konvertatsiya; Pack and Go
- parametrlar: konfiguratsiyalar jadvali (sw_config_values), tenglamalar va global o'zgaruvchilar, o'lchamni nomi bo'yicha o'zgartirish
- listovoy metall (asos, yoyish) va payvand konstruksiyalar (profildan karkas, profillar kutubxonasi, kesish ro'yxati)
- tekshiruv: har o'zgarishdan keyin avtomatik hajm, massa, gabarit va xatolar; sw_verify (kutilgan qiymatlar bilan solishtirish), sw_snapshot / sw_compare, sw_measure, sw_check_geometry
- tezlik: sw_batch (ko'p amal bitta chaqiruvda), SOLIDWORKS ichidagi ulagich (add-in) — «BIM Muhandis» lenta yorlig'i va paneli (MCP: ON/OFF, Jurnal, Saqlash nuqtasi); ulagichsiz ham barcha tool'lar COM orqali ishlaydi
- sw_run_csharp — SOLIDWORKS API bo'yicha erkin C# kodi (cheklovsiz); sw_checkpoint_save — saqlash nuqtalari
- yuz/qirra havolalari tilga bog'liq emas («face:+z», «plane:front», «edge@x,y,z»)
- SOLIDWORKS 2026 SP5 da jonli sinalgan: har bir bo'lim (eskiz, elementlar, yig'ma, chizma, eksport, listovoy metall, payvand) ochiq dasturda tekshirildi; chizma A4 (GOST 2.301 — kitob) va A3…A0 da GOST ramka-shtampi bilan avtomatik, izometriya bo'sh chorakka sig'diriladi
- sw_run_csharp — to'liq tiplangan API (o'rnatilgan SOLIDWORKS'ning o'z kutubxonalari, Simulation ham), sw_api_help — metod va enum imzolari ma'lumotnomasi
- LIRA-SAPR 2024+ bilan TO'G'RIDAN-TO'G'RI ulanish (COM API): lira_app, lira_doc (yangi / ochish / matnli sxemani darhol import — qo'lda «Файл → Импорт» kerak emas), lira_table_read / lira_table_write (tugunlar, elementlar, tayanchlar, bikrliklar va boshqa 30 ta kiritish jadvali — xatolar qator/ustun bilan), lira_select, lira_dead_weight, lira_analyze (hisobni boshlaydi, tugashini kutadi, natija CSV jadvallarini beradi), lira_command, lira_call
- AutoCAD: bo'sh chizmada chegaralar to'g'ri ko'rsatiladi
