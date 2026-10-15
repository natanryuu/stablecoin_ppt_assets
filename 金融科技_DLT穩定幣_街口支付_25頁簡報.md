# 從 DLT 到穩定幣：區塊鏈如何改變全球支付與金融服務？

**MIS989 金融科技｜國立中山大學｜40 分鐘｜3 位組員**

---

## 第 1 頁｜封面

# 從 DLT 到穩定幣
### 區塊鏈如何改變全球支付與金融服務？

Distributed Ledger Technology & Stablecoins in Modern Finance

MIS989 金融科技｜國立中山大學

---

## 第 2 頁｜研究背景：為什麼金融機構開始關注穩定幣？

- 傳統跨境支付可能涉及多家銀行、清算安排及不同國家的金融制度。
- 區塊鏈提供跨地區運作的數位資產記錄與移轉網路。
- 穩定幣結合法幣價值錨定與鏈上轉移的特性，擴大支付與結算的可能性。
- Visa 已在美國推出 USDC 機構結算服務，顯示穩定幣開始融入既有金融基礎設施。

**資料來源：** [Visa（2025）](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21951.html)｜[BIS（2025）](https://www.bis.org/publ/arpdf/ar2025e.pdf)

---

## 第 3 頁｜核心問題與報告架構

**核心問題：** 既然傳統銀行已能電子轉帳，為什麼金融機構仍開始導入穩定幣？

1. **技術與產品：** DLT 如何支援穩定幣發行、流通及贖回？
2. **實際應用：** Visa 如何將 USDC 導入機構結算？街口支付如何看待台灣的穩定幣應用？
3. **金融影響：** 穩定幣帶來哪些商業價值、風險與監管課題？

---

## 第 4 頁｜DLT 與穩定幣的關係

![DLT 到穩定幣技術架構](stablecoin_ppt_assets/01_dlt_stablecoin.png)

- **DLT：** 讓多方共同維護、驗證交易紀錄。
- **區塊鏈：** DLT 的一種實現方式。
- **穩定幣：** 可在區塊鏈上發行、持有及移轉的價值穩定型數位資產。
- **金融服務：** 將穩定幣應用於支付、跨境資金移轉及結算。
- 穩定幣的價值穩定來自儲備與贖回等經濟制度，不是區塊鏈技術本身。

**資料來源：** 課程教材《Distributed Ledger Technology》P.6–13｜[BIS（2025）](https://www.bis.org/publ/arpdf/ar2025e.pdf)

---

## 第 5 頁｜穩定幣的三種主要模式

| 類型 | 維持價值的方式 | 代表案例 |
|---|---|---|
| 法幣儲備支持型 | 由現金、短期流動性資產等支持發行與贖回 | USDC、USDT、PYUSD |
| 加密資產抵押型 | 以加密資產抵押並搭配風險管理機制 | DAI |
| 演算法型 | 透過市場誘因與代幣供需調整價格 | 已崩潰的 TerraUSD（UST） |

**本報告焦點：法幣儲備支持型穩定幣。**

**資料來源：** [BIS（2025）](https://www.bis.org/publ/arpdf/ar2025e.pdf)

---

## 第 6 頁｜市場代表產品：USDT 與 USDC

| 面向 | USDT | USDC |
|---|---|---|
| 發行體系 | Tether | Circle |
| 錨定貨幣 | 美元 | 美元 |
| 代表場景 | 加密資產交易、跨平台資金移轉 | 機構支付、鏈上金融與結算 |
| 關鍵分析 | 儲備組成與市場流通 | 儲備透明、贖回與機構金融整合 |

**核心觀察：** 同樣錨定美元，不代表儲備、贖回資格及監理安排完全相同。

**資料來源：** [Tether Transparency](https://tether.to/en/transparency/)｜[Circle USDC](https://www.circle.com/usdc)

---

## 第 7 頁｜USDC 如何發行、流通與贖回？

![USDC 發行與贖回流程](stablecoin_ppt_assets/02_usdc_lifecycle.png)

1. 合格機構將美元交付發行商。
2. 發行商透過智能合約鑄造相應 USDC。
3. USDC 在支援的區塊鏈及服務平台上移轉。
4. 符合資格的機構申請贖回；相應 USDC 銷毀並依規定取得美元。

**補充：** Circle Mint 不直接提供一般個人使用；個人通常透過交易所或其他服務取得、出售 USDC。

**資料來源：** [Circle 發行與贖回說明](https://help.circle.com/support/en/tokenizing-and-redeeming-usdc?id=kb_article_view&sysparm_article=KB0010781)｜[Circle USDC](https://www.circle.com/usdc)

---

## 第 8 頁｜USDC 為何能接近 1 美元？

- **儲備支持：** Circle 表示 USDC 由高流動性現金與現金等價資產支持。
- **贖回安排：** 符合條件的客戶可按規定向發行商辦理 1:1 美元贖回。
- **市場套利：** 在一定條件下，參與者的買賣、發行與贖回有助降低偏離錨定價格的幅度。
- **資訊揭露：** Circle 公布儲備資訊，並提供第三方確信報告。

**重要區別：** 1:1 贖回安排不代表二級市場價格永遠固定在 1 美元。

**資料來源：** [Circle Transparency](https://www.circle.com/transparency)｜[Circle USDC Terms](https://www.circle.com/legal/usdc-terms)

---

## 第 9 頁｜穩定幣發行商的商業模式

**從穩定幣流通到儲備收益：**

- 合格客戶提供美元，發行商鑄造對應穩定幣。
- 發行商依產品與監管規範持有相應儲備，例如現金、短期美國國債。
- 部分儲備資產可能產生利息收益。
- 發行商需要支付儲備管理、法遵、營運及分銷等成本。
- 利率變動、穩定幣流通量、合作平台費用會影響商業模式。

**分析結論：** 穩定幣不只是交易媒介，也形成資金、儲備管理與支付服務的新商業鏈。

**資料來源：** [Circle Transparency](https://www.circle.com/transparency)｜[Circle USDC Terms](https://www.circle.com/legal/usdc-terms)

---

## 第 10 頁｜傳統跨境支付的痛點

- **流程：** 部分跨境轉帳需透過代理行與不同清算系統。
- **成本：** 除匯款費外，可能存在匯差、中轉行費用及收款費用。
- **時間：** 銀行營業時間、時區、當地支付基礎設施可能影響完成時間。
- **資金管理：** 金融機構需處理跨幣別流動性及對帳。
- **但傳統支付持續進步：** SWIFT gpi 等方案已改善付款追蹤與到帳速度。

**資料來源：** [FSB 跨境支付路線圖](https://www.fsb.org/work-of-the-fsb/financial-innovation-and-structural-change/cross-border-payments/)｜[SWIFT gpi](https://www.swift.com/our-solutions/swift-gpi)

---

## 第 11 頁｜傳統匯款 vs. 穩定幣資金移轉

### 傳統跨境支付
![傳統跨境支付示意](stablecoin_ppt_assets/03_transfer_comparison.png)

### 穩定幣跨境資金移轉
![穩定幣資金移轉示意](stablecoin_ppt_assets/04_stablecoin_transfer.png)

**關鍵差異：** 穩定幣可以簡化部分資產轉移流程；但法幣出入金、身份驗證、合規與當地付款安排仍不可忽略。

**資料來源：** [BIS（2025）](https://www.bis.org/publ/arpdf/ar2025e.pdf)｜[FSB Cross-border Payments](https://www.fsb.org/work-of-the-fsb/financial-innovation-and-structural-change/cross-border-payments/)

---

## 第 12 頁｜穩定幣支付一定更快、更便宜嗎？

| 比較項目 | 傳統銀行匯款 | 穩定幣支付 |
|---|---|---|
| 資金移轉 | 銀行與清算系統 | 區塊鏈轉帳及服務平台 |
| 服務時間 | 受支付系統和營業安排影響 | 公鏈通常全天候運作 |
| 成本項目 | 匯款費、匯差、中轉費等 | 鏈上費用、平台費、出入金與兌換費 |
| 完成判定 | 收款行實際入帳 | 鏈上完成不等於法幣已入帳 |
| 風險 | 作業延誤、銀行及交易對手等風險 | 發行商、託管、私鑰、兌換與鏈上操作風險 |

**結論：** 需以完整「付款至收款」流程衡量成本和效率，不能只看鏈上轉帳速度。

**資料來源：** [BIS（2025）](https://www.bis.org/publ/arpdf/ar2025e.pdf)｜[FSB 跨境支付](https://www.fsb.org/work-of-the-fsb/financial-innovation-and-structural-change/cross-border-payments/)

---

## 第 13 頁｜實際案例一：Visa USDC 結算

- **發布日期：** 2025 年 12 月 16 日。
- **應用內容：** Visa 在美國推出 USDC 結算服務，供合作的發卡及收單機構使用。
- **首批參與者：** Cross River Bank、Lead Bank。
- **鏈上網路：** Solana。
- **核心特色：** 讓部分機構資金結算透過穩定幣進行，而非要求消費者改變刷卡方式。

**案例重點：穩定幣首先改變的是金融機構之間的後端結算流程。**

**資料來源：** [Visa 官方新聞稿（2025/12/16）](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21951.html)

---

## 第 14 頁｜Visa 案例：結算流程如何改變？

![Visa USDC 結算流程](stablecoin_ppt_assets/05_visa_settlement.png)

- 消費者照常以 Visa 卡片付款。
- Visa 仍提供原有支付網路與交易服務。
- 參與機構可在指定結算安排中使用 USDC。
- USDC 在區塊鏈上移轉，增加結算資產移動的選項。

**關鍵觀察：** 支付前端維持熟悉的使用體驗，後端則導入新的結算基礎設施。

**資料來源：** [Visa 官方新聞稿（2025/12/16）](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21951.html)

---

## 第 15 頁｜Visa 採用 USDC 的實際效益

- **每週七天：** Visa 公告表示 USDC 結算支援一週七天的資金移轉。
- **假日彈性：** 有利於處理週末、假日結算安排。
- **提高選擇性：** 傳統法幣結算外，新增鏈上穩定幣結算通道。
- **規模指標：** 2025 年 12 月，Visa 公告穩定幣結算量已達 **超過 35 億美元年化規模**。

**分析：** Visa 的做法是將鏈上結算嵌入既有支付網路，而不是替代整套卡片支付系統。

**資料來源：** [Visa 官方新聞稿（2025/12/16）](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21951.html)

---

## 第 16 頁｜穩定幣會取代銀行嗎？

**可能被重塑的環節**

- 跨境資金轉移與部分結算作業。
- 金融機構的流動性管理與支付通道。
- 部分企業支付及平台型金融服務。

**銀行仍具有關鍵角色**

- 法幣出入金、存款、授信與信用創造。
- 金融監理、身份驗證及反洗錢作業。
- 客戶資產保管、糾紛處理及實體經濟金融服務。

**小組判斷：** 穩定幣比較可能先重塑支付結算的部分環節，而非全面取代銀行體系。

**資料來源：** [BIS（2025）](https://www.bis.org/publ/arpdf/ar2025e.pdf)｜[Visa（2025）](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21951.html)

---

## 第 17 頁｜穩定幣的風險：金融承諾與技術風險

![穩定幣風險分層](stablecoin_ppt_assets/06_risk_layers.png)

- **價格脫鉤：** 市場價格可能暫時偏離錨定貨幣。
- **儲備與贖回：** 資產流動性、發行商信用及大量贖回需求可能產生壓力。
- **鏈上安全：** 私鑰遺失、智能合約漏洞、誤轉帳可能造成資產損失。
- **監管與跨境合規：** 涉及身分驗證、反洗錢、資金流向及跨境制度差異。

**核心區別：** 交易紀錄可驗證，不等於穩定幣的市價、贖回及資產安全獲得保證。

**資料來源：** [BIS Annual Economic Report 2025，Chapter III](https://www.bis.org/publ/arpdf/ar2025e3.htm)

---

## 第 18 頁｜街口支付觀點：穩定幣最重要的應用在哪裡？

- 街口支付董事長梅驊認為，消費者重視的是付款的**確定感、便利性與信任感**。
- **台灣境內支付：** 穩定幣主要可能改善資金移轉效率，屬於既有系統的優化。
- **跨境支付：** 幣別轉換、海外付款費用與資金清算等需求更加明確。
- 新臺幣或美元穩定幣是否適用，應從實際使用情境與需求出發。

**案例定位：** 街口支付提出的是產業觀點與潛在發展方向，並非宣布已上線穩定幣支付。

**資料來源：** [XREX《Web3 大西進》專訪街口支付董事長梅驊（2026/10/14）](https://xrex.io/tw/zh/blog/web3-podcast/jkopay-mei-hua-stablecoin-payments/)

---

## 第 19 頁｜街口支付 × 日本 PayPay：跨境電子支付實例

- 街口支付與日本 PayPay 合作，讓台灣使用者在日本合作商店進行跨境付款。
- 依專訪說明，消費者於付款當下即可得知換算後的新臺幣金額。
- 外幣清算及銀行作業由支付業者與銀行在後端處理。
- 此服務展示支付業者如何整合使用介面、外匯換算與跨境清算。

**重要事實：街口 × PayPay 目前所討論的合作是跨境電子支付，不是已採用穩定幣的結算案例。**

**資料來源：** [XREX：街口支付跨境支付訪談（2026）](https://xrex.io/tw/zh/blog/web3-podcast/jkopay-mei-hua-stablecoin-payments/)

---

## 第 20 頁｜從跨境電子支付到穩定幣：可能改變什麼？

| 比較面向 | 街口 × PayPay 現有跨境支付 | 潛在穩定幣跨境支付模式 |
|---|---|---|
| 使用者體驗 | 掃碼付款，顯示新臺幣金額 | 可整合於既有 App，使用者未必直接接觸鏈上資產 |
| 後端資金流 | 由支付機構與銀行處理外幣清算 | 部分機構間資金轉移可能使用穩定幣 |
| 主要能力 | 電支與國際支付合作、銀行清算 | 鏈上轉移、儲備與贖回、法幣出入金整合 |
| 尚須處理 | 匯率、資金清算、法規遵循 | 同樣須處理匯率、監管、兌換及資安問題 |

**分析：** 穩定幣不一定改變消費者的付款動作，可能首先改變支付服務背後的資金移轉方式。

**資料來源：** [XREX 街口支付專訪](https://xrex.io/tw/zh/blog/web3-podcast/jkopay-mei-hua-stablecoin-payments/)｜[Visa USDC Settlement（2025）](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21951.html)

---

## 第 21 頁｜台灣支付業者導入穩定幣的機會與挑戰

**三項既有優勢**

1. **使用場景：** 已建立商家受理網路與付款流程。
2. **會員基礎：** 熟悉使用者身分驗證及日常付款需求。
3. **監理與資金管理：** 電子支付機構具既有法遵、信託與消費者保障流程。

**導入仍須解決**

- 與穩定幣發行人、虛擬資產服務商及銀行的合作分工。
- 鏈上與鏈下資金對帳、穩定幣兌換、交易監控與反洗錢要求。
- 消費者對價格、退款、詐騙及資產保障的理解與信任。

**資料來源：** [XREX 專訪（2026）](https://xrex.io/tw/zh/blog/web3-podcast/jkopay-mei-hua-stablecoin-payments/)｜[金管會《虛擬資產服務法》](https://law.fsc.gov.tw/LawContent.aspx?id=GL004301)

---

## 第 22 頁｜美國監管：GENIUS Act

- **立法：** 美國《GENIUS Act》於 2025 年 7 月 18 日簽署成法。
- **核心目的：** 建立支付型穩定幣的聯邦層級監管架構。
- **主要規範方向：** 發行人資格、儲備資產、贖回、資訊揭露與監督。
- **金融意義：** 穩定幣逐步從加密市場產品，進入受專門規範的支付金融制度。

**資料來源：** [美國 GENIUS Act 法律原文](https://www.govinfo.gov/content/pkg/PLAW-119publ27/html/PLAW-119publ27.htm)

---

## 第 23 頁｜國際監管比較：美國、歐盟、台灣

| 地區 | 主要制度 | 監管重點 |
|---|---|---|
| 美國 | GENIUS Act（2025 年簽署） | 支付型穩定幣發行資格、儲備、贖回、監督 |
| 歐盟 | MiCA（穩定幣相關規定自 2024 年適用） | 資產參考代幣、電子貨幣代幣、發行人許可等 |
| 台灣 | 《虛擬資產服務法》（2026 年 7 月公布） | 穩定幣發行許可、準備資產、贖回與監理要求 |

**台灣施行狀態：** 法規資料庫註明部分或全部條文尚未施行，不應把「公布」等同「全面上路」。

**資料來源：** [美國法律原文](https://www.govinfo.gov/content/pkg/PLAW-119publ27/html/PLAW-119publ27.htm)｜[歐盟 MiCA](https://finance.ec.europa.eu/digital-finance/digital-finance-legislation/markets-crypto-assets-regulation-mica_en)｜[台灣金管會法規](https://law.fsc.gov.tw/LawContent.aspx?id=GL004301)

---

## 第 24 頁｜BIS：穩定幣能否成為貨幣制度核心？

**國際清算銀行（BIS）的三項評估標準**

1. **Singleness — 貨幣一致性：** 不同支付媒介應維持可靠的一致價值。
2. **Elasticity — 彈性：** 金融體系須適當回應資金與流動性需求。
3. **Integrity — 完整性：** 金融制度需防止非法金融活動並維持可信度。

**BIS 觀點：** 穩定幣具有技術創新價值，但在上述制度條件存在限制，不宜作為未來貨幣制度的主要支柱。

**資料來源：** [BIS Annual Economic Report 2025，第 III 章](https://www.bis.org/publ/arpdf/ar2025e.pdf)

---

## 第 25 頁｜結論：穩定幣是取代者，還是補充者？

1. **技術面：** DLT 為穩定幣提供共享交易紀錄與鏈上資產移轉能力；價值穩定則依賴儲備、贖回及市場機制。
2. **國際應用：** Visa 已將 USDC 納入金融機構的後端結算，顯示穩定幣可與既有金融支付網路整合。
3. **台灣市場：** 街口支付案例顯示，跨境支付有明確需求；穩定幣應用仍須搭配支付場景、使用者信任與金融監管。
4. **未來方向：** 穩定幣較可能先補充部分支付及結算流程，而非全面取代銀行、電子支付機構與法幣體系。

**核心結論：** 真正的金融科技創新，不只是把交易放到區塊鏈，而是讓資金流動更有效率、可信任且符合監管要求。

**資料來源：** [Visa（2025）](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21951.html)｜[XREX 街口支付專訪（2026）](https://xrex.io/tw/zh/blog/web3-podcast/jkopay-mei-hua-stablecoin-payments/)｜[BIS（2025）](https://www.bis.org/publ/arpdf/ar2025e3.htm)

---

## 參考文獻

- Yang, Y.-C. 《MIS989 Fintech: Distributed Ledger Technology》課程教材，P.6–32。
- Visa. (2025-12-16). [Visa Launches Stablecoin Settlement in the United States](https://usa.visa.com/about-visa/newsroom/press-releases.releaseId.21951.html).
- Circle. [USDC](https://www.circle.com/usdc); [Transparency](https://www.circle.com/transparency).
- Tether. [Transparency](https://tether.to/en/transparency/).
- Bank for International Settlements. (2025). [Annual Economic Report 2025, Chapter III](https://www.bis.org/publ/arpdf/ar2025e3.htm).
- XREX. (2026-10-14). [穩定幣子法最快 2027 年上路！街口支付董事長梅驊：支付業者有支付應用場景與信任優勢](https://xrex.io/tw/zh/blog/web3-podcast/jkopay-mei-hua-stablecoin-payments/).
- U.S. Government Publishing Office. (2025). [GENIUS Act, Public Law 119-27](https://www.govinfo.gov/content/pkg/PLAW-119publ27/html/PLAW-119publ27.htm).
- European Commission. [Digital finance / MiCA](https://finance.ec.europa.eu/news/digital-finance-2024-12-19_en).
- 金融監督管理委員會。（2026）。[虛擬資產服務法](https://law.fsc.gov.tw/LawContent.aspx?id=GL004301)。
