# ARTEX 與南韓金融業入侵事件：導讀

本篇導讀整理 CrowdStrike 2026-10-07 發布的分析，說明攻擊者如何用 agentic 滲透測試工具 ARTEX 與多個 LLM 對南韓金融機構展開入侵，並對照《京鄉新聞》的報導，補上受害與時間線，最後把可用的偵測與防禦思路列出（標明為本文判斷）。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 導讀網頁（Mermaid 需連網載入） |
| `artex-south-korea-finance.md` | 正式導讀 Markdown |
| `images/` | 7 組圖片，各有 16:9 與 `-mobile` 9:16 版，由 AI 生成 |

查證帳本、流程紀錄與驗收截圖只在作者本機保存，未公開。

## 原始資料

- 文章：CrowdStrike，Unknown Threat Actor Uses AI-Driven ARTEX to Target South Korean Finance，2026-10-07。https://www.crowdstrike.com/en-us/blog/unknown-threat-actor-uses-artex-to-target-south-korean-finance/
- 新聞：Kim Sang-Beom，The Korean financial sector was breached by a two-month-old Chinese AI，《京鄉新聞》，2026-10-04。https://www.khan.co.kr/en/article/202610042320007
- 補充：Korea Times 解析（2026-10-07）、RuntimeWire 彙整（2026-10-06）、Arirang News 影片（2026-10-08）。
- 逐字稿：不適用。

## 注意

- CrowdStrike 原文列有疑似攻擊者的個人資料，原文自述無法確定關聯，本導讀不轉載。
- 偵測與防禦建議是本文判斷，CrowdStrike 原文沒有。

## 狀態

已發布（2026-10-10）：https://lushinshang.github.io/artex-south-korea-finance/
