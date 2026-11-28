# BIM Muhandis MCP — oxirgi versiya

## 1.15.3 (28.11.2026)

BIM Muhandis MCP — AI ilovalar (Claude, ChatGPT, Gemini, Microsoft Copilot, Grok, Kimi, Qwen, Meta Muse, DeepSeek, Perplexity, Cursor, Windsurf, LM Studio, Cline) uchun Revit, AutoCAD / Civil 3D, Navisworks, Tekla Structures, SketchUp, LIRA-SAPR, SCAD Office, SAP2000 / ETABS, Robot, SOLIDWORKS, Photoshop, CorelDRAW 2022–2027 va Word / Excel / PowerPoint ulagichi.

O'rnatish: ZIP'ni chiqarib oling → «BIM Muhandis MCP - O'rnatish.exe» → Claude va Revit'ni qayta oching. AI ilovalar o'zi ulanadi. To'liq o'chirish: «BIM Muhandis MCP - O'chirish.exe».

- SOLIDWORKS → Revit ko'prigi (bridge_sw_to_revit): faol detal/yig'ma Revit'ga aniq geometriya bilan (qattiq jism, kategoriya va joylashuv tanlanadi; hajmlar avtomatik solishtiriladi — SOLIDWORKS 2026 + Revit 2024 da farq 0,02 %)
- SOLIDWORKS spetsifikatsiyasi / kesish ro'yxati Excel va Word'ga (office_sw_vedomost, sw_vedomost — GOST 2.106 ustunlari)
- sw_section_properties (kesim yuzasi, inersiya momentlari)
- sw_self_test — modulni o'z-o'zini sinash (11 qadam, kutilgan hajmlar bilan)
- dialog kuzatuvchisi: SOLIDWORKS'da oyna ochilib qolsa, 10 daqiqa kutmasdan oyna matni va tugmalari bilan xabar beradi
- SAT eksportida ACIS versiyasi (sat_version)
- LIRA: lira_build_frame sxemasi endi hisobga tayyor — plita tugunlari tartibi tuzatildi (ilgari «некорректная геометрия» berardi), plita bikrligi va beton zichligi to'g'ri yoziladi (o'z og'irligi qo'yiladi); lira_analyze hisob bayonnomasidagi xatolarni ko'rsatadi
