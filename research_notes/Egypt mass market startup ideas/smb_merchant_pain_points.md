# Egyptian SMB & Merchant Operational Pain Points and Software Landscape (as of 3 Oct 2026)

> **Coverage note for the report writer (read first).** Tooling limits cut this research short. The web search budget for the whole session (200 calls, shared with the parallel researchers) ran out after this researcher had made 13 searches. WebFetch was blocked by the network egress proxy on every domain tried: youm7.com, amwalalghad.com, hapijournal.com, eta.gov.eg, alborsaanews.com, pioneers-solutions.com, techmoonshot.com, daftra.com, en.wikipedia.org, menabytes.com and vatupdate.com. **Every cited finding below therefore comes from search-result snippets, summaries and headlines. No full article was read.** Treat each figure as "as reported in the headline or snippet." Coverage by key question:
> - **Reasonably covered:** Q1 (SMB base) and Q3 (regulatory forcing functions).
> - **Partly covered:** Q2, but only for B2B ordering platforms and InstaPay payments.
> - **No verified findings:** Q4–Q7 (social commerce, vertical software, WhatsApp/AI and willingness to pay). These are written up as gaps, with clearly labelled leads to verify.

## 1. SMB base: number of establishments, share that is micro/small/informal, most common types

### Takeaway
CAPMAS's 6th Economic Census (reference year 2022/23, results published in late October 2025) counts about 3.86 million establishments employing 15.2 million people. Of these establishments, 54.4% are in wholesale and retail trade. About half of private establishments (50.7%, roughly 1.96 million) are informal, and these average only about two workers each. The mass market is overwhelmingly micro-retail run by the owner.

### Cited Findings
- Total establishments rose from 3.743 million in the 2017/18 census to 3.858 million in 2022/23 (+3.1%). These are the results of the 6th Economic Census, a count CAPMAS runs every five years — [Youm7, 26 Nov 2025](https://www.youm7.com/story/2025/11/26/%D8%A7%D9%84%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%89-%D8%A7%D9%84%D8%B3%D8%A7%D8%AF%D8%B3-%D8%AE%D8%B1%D9%8A%D8%B7%D8%A9-%D8%AC%D8%AF%D9%8A%D8%AF%D8%A9-%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF-%D9%8A%D8%AA%D8%BA%D9%8A%D8%B1-3-9-%D9%85%D9%84%D9%8A%D9%88%D9%86/7212299)
  - Headlines round this to "3.9 million establishments, 15.2 million workers" — [Parlmany](https://www.parlmany.com/News/2/588690/%D8%AE%D8%B1%D9%8A%D8%B7%D8%A9-%D8%AC%D8%AF%D9%8A%D8%AF%D8%A9-%D9%84%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF-%D8%A7%D9%84%D9%85%D8%B5%D8%B1%D9%8A-%D9%86%D8%AA%D8%A7%D8%A6%D8%AC-%D8%A7%D9%84%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%8A-%D8%A7%D9%84%D8%B3%D8%A7%D8%AF%D8%B3-%D8%AA%D9%83%D8%B4%D9%81-%D9%85%D9%84%D8%A7%D9%85%D8%AD); [Hapi Journal, 27 Oct 2025](https://hapijournal.com/2025/10/27/%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%B9%D8%A7%D9%85-2022-2023-3-9-%D9%85%D9%84%D9%8A%D9%88%D9%86-%D9%85%D9%86%D8%B4%D8%A3%D8%A9-%D8%AA%D8%B9%D9%85%D9%84-%D8%A8%D9%85%D8%B5%D8%B1-%D8%AA%D8%B4%D8%BA/); [El Balad](https://www.elbalad.news/6745597)
  - Some outlets round down to "3.8 million" and say the informal sector shrank — [Amwal Al Ghad, 27 Oct 2025](https://amwalalghad.com/2025/10/27/%D8%A7%D9%84%D8%A5%D8%AD%D8%B5%D8%A7%D8%A1-%D9%86%D9%85%D9%88-%D8%B9%D8%AF%D8%AF-%D8%A7%D9%84%D9%85%D9%86%D8%B4%D8%A2%D8%AA-%D8%A7%D9%84%D8%B9%D8%A7%D9%85%D9%84%D8%A9-%D8%A8%D8%A7%D9%84%D8%A7%D9%82/); [Akhbar El Yom](https://akhbarelyom.com/news/newdetails/4741200/1/%D8%A7%D9%84%D8%A5%D8%AD%D8%B5%D8%A7%D8%A1-38-%D9%85%D9%84%D9%8A%D9%88%D9%86-%D8%B9%D8%AF%D8%AF-%D8%A7%D9%84%D9%85%D9%86%D8%B4%D8%A2%D8%AA-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%8A%D8%A9-)
- The census counts 15.2 million workers and EGP 744 billion in total annual wages — [Al Mal](https://almalnews.com/2081918/%D9%88%D9%81%D9%82-%D9%86%D8%AA%D8%A7%D8%A6%D8%AC-%D8%A7%D9%84%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%8A-%D8%A7%D9%84%D8%B3%D8%A7%D8%AF%D8%B3-%C2%AB%D8%A7%D9%84%D8%A5%D8%AD%D8%B5%D8%A7%D8%A1%C2%BB-15/)
- Activity mix, as a share of establishments: wholesale and retail trade 54.4%, "other activities" 27.4%, manufacturing 13.4% — [Youm7, 26 Nov 2025](https://www.youm7.com/story/2025/11/26/%D8%A7%D9%84%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%89-%D8%A7%D9%84%D8%B3%D8%A7%D8%AF%D8%B3-%D8%AE%D8%B1%D9%8A%D8%B7%D8%A9-%D8%AC%D8%AF%D9%8A%D8%AF%D8%A9-%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF-%D9%8A%D8%AA%D8%BA%D9%8A%D8%B1-3-9-%D9%85%D9%84%D9%8A%D9%88%D9%86/7212299)
  - These three shares add up to 95.2%. The snippet does not say what the other 4.8% is.
- Wholesale and retail trade establishments paid an average wage of EGP 3,805 in 2022/23. Mada Masr reads the census as showing establishments and workers concentrated in low-wage sectors — [Mada Masr, 27 Oct 2025](https://www.madamasr.com/2025/10/27/news/%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF/%D8%A8%D9%8A%D8%A7%D9%86%D8%A7%D8%AA-%D8%A7%D9%84%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%8A-%D8%AA%D9%83%D8%B4%D9%81-%D8%AA%D9%8E%D8%B1%D9%83%D9%8F%D8%B2/)
  - The snippet does not say whether this is a monthly figure.
- Formality: of about 3.9 million private establishments, 49.3% are formal and 50.7% are informal — [Youm7](https://www.youm7.com/story/2025/11/26/%D8%A7%D9%84%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%89-%D8%A7%D9%84%D8%B3%D8%A7%D8%AF%D8%B3-%D8%AE%D8%B1%D9%8A%D8%B7%D8%A9-%D8%AC%D8%AF%D9%8A%D8%AF%D8%A9-%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF-%D9%8A%D8%AA%D8%BA%D9%8A%D8%B1-3-9-%D9%85%D9%84%D9%8A%D9%88%D9%86/7212299); [Parlmany](https://www.parlmany.com/News/2/588690/%D8%AE%D8%B1%D9%8A%D8%B7%D8%A9-%D8%AC%D8%AF%D9%8A%D8%AF%D8%A9-%D9%84%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF-%D8%A7%D9%84%D9%85%D8%B5%D8%B1%D9%8A-%D9%86%D8%AA%D8%A7%D8%A6%D8%AC-%D8%A7%D9%84%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%8A-%D8%A7%D9%84%D8%B3%D8%A7%D8%AF%D8%B3-%D8%AA%D9%83%D8%B4%D9%81-%D9%85%D9%84%D8%A7%D9%85%D8%AD)
- Informal private establishments fell to about 1.955 million in 2022/23 — [Al Dostor](https://www.dostor.org/5281562)
  - Hapi Journal's headline gives "2 million informal private establishments employing 3.9 million people" — [Hapi Journal](https://hapijournal.com/2025/10/27/%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-2022-2023-2-%D9%85%D9%84%D9%8A%D9%88%D9%86-%D9%85%D9%86%D8%B4%D8%A3%D8%A9-%D9%85%D9%86-%D8%A7%D9%84%D9%82%D8%B7%D8%A7%D8%B9-%D8%A7%D9%84%D8%AE%D8%A7%D8%B5-%D8%BA%D9%8A/)
- Informal-sector employment rose from 2.8 million in 2012/13 to 3.9 million in 2022/23 — [Youm7, 24 May 2026](https://www.youm7.com/story/2026/5/24/%D8%B9%D8%AF%D8%AF-%D8%A7%D9%84%D8%B9%D8%A7%D9%85%D9%84%D9%8A%D9%86-%D8%A8%D8%A7%D9%84%D9%82%D8%B7%D8%A7%D8%B9-%D8%BA%D9%8A%D8%B1-%D8%A7%D9%84%D8%B1%D8%B3%D9%85%D9%89-%D8%A7%D8%B1%D8%AA%D9%81%D8%B9-%D9%85%D9%86-2-8-%D8%B9%D8%A7%D9%85/7427108)
- Informal-sector output is headlined as rising "to EGP 582bn from 17/18 to 22/23" — [Youm7, 24 May 2026](https://www.youm7.com/story/2026/5/24/%D8%A5%D9%86%D8%AA%D8%A7%D8%AC-%D8%A7%D9%84%D9%82%D8%B7%D8%A7%D8%B9-%D8%BA%D9%8A%D8%B1-%D8%A7%D9%84%D8%B1%D8%B3%D9%85%D9%8A-%D9%81%D9%8A-%D9%85%D8%B5%D8%B1-%D9%8A%D8%B1%D8%AA%D9%81%D8%B9-%D9%84%D9%80582-%D9%85%D9%84%D9%8A%D8%A7%D8%B1-%D8%AC%D9%86%D9%8A%D9%87/7427231)
  - The headline does not make clear whether EGP 582bn is the 2022/23 level or the increase.
- Youm7's census feature headline makes these points — [Youm7](https://www.youm7.com/story/2025/11/26/%D8%A7%D9%84%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%89-%D8%A7%D9%84%D8%B3%D8%A7%D8%AF%D8%B3-%D8%AE%D8%B1%D9%8A%D8%B7%D8%A9-%D8%AC%D8%AF%D9%8A%D8%AF%D8%A9-%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF-%D9%8A%D8%AA%D8%BA%D9%8A%D8%B1-3-9-%D9%85%D9%84%D9%8A%D9%88%D9%86/7212299):
  - Services and construction are expanding.
  - "Half of activity is in the shadows."
  - Small projects are the growth engine.
  - Cairo has the most establishments; Sinai is growing fastest.
- Arabi21 reports that 32% of Egyptian establishments operate below capacity — [Arabi21](https://arabi21.com/story/1726955/32-%D9%81%D9%8A-%D8%A7%D9%84%D9%85%D8%A7%D8%A6%D8%A9-%D9%85%D9%86-%D8%A7%D9%84%D9%85%D9%86%D8%B4%D8%A2%D8%AA-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%8A%D8%A9-%D8%A7%D9%84%D9%85%D8%B5%D8%B1%D9%8A%D8%A9-%D9%84%D8%A7-%D8%AA%D8%B9%D9%85%D9%84-%D8%A8%D8%B7%D8%A7%D9%82%D8%AA%D9%87%D8%A7)
  - Use with caution: the same snippet gives an inconsistent reference date ("mid-2020").
- One Egyptian outlet criticizes the 2022/23 census method, saying it has "methodological gaps that threaten data credibility" when judged against international standards — [Al Alam Al Youm](https://alalamelyoum.co/254848/)
- MSMEDA (the Micro, Small and Medium Enterprise Development Agency) says it has financed more than 493,000 projects with EGP 22.7 billion, creating more than 1 million jobs. The figures were reported in Nov 2025; the period appears to start in 2022 — [Youm7, 22 Nov 2025](https://www.youm7.com/story/2025/11/22/%D8%AC%D9%87%D8%A7%D8%B2-%D8%AA%D9%86%D9%85%D9%8A%D8%A9-%D8%A7%D9%84%D9%85%D8%B4%D8%B1%D9%88%D8%B9%D8%A7%D8%AA-%D8%B6%D8%AE-22-7-%D9%85%D9%84%D9%8A%D8%A7%D8%B1-%D8%AC%D9%86%D9%8A%D9%87-%D9%84%D8%AA%D9%85%D9%88%D9%8A%D9%84-493/7206350); [Al-Ahram](https://gate.ahram.org.eg/daily/News/205415/5/1000084/%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF/%D8%AC%D9%87%D8%A7%D8%B2-%D8%AA%D9%86%D9%85%D9%8A%D8%A9-%D8%A7%D9%84%D9%85%D8%B4%D8%B1%D9%88%D8%B9%D8%A7%D8%AA--%D8%A3%D9%84%D9%81-%D9%85%D8%B4%D8%B1%D9%88%D8%B9-%D8%A8%D8%AA%D9%85%D9%88%D9%8A%D9%84--%D9%85%D9%84%D9%8A%D8%A7%D8%B1%D8%AC%D9%86%D9%8A%D9%87-.aspx)
  - Young people and women received 47% of the financing.
  - The same search results also gave project loans of EGP 33.2bn for 1.4 million projects and more than 2 million jobs. Which page this came from, and the period it covers, are unclear.
- MSMEDA financed 24,000 small and micro projects for women (Jul 2025) — [Youm7, 5 Jul 2025](https://www.youm7.com/story/2025/7/5/%D8%AC%D9%87%D8%A7%D8%B2-%D8%AA%D9%86%D9%85%D9%8A%D8%A9-%D8%A7%D9%84%D9%85%D8%B4%D8%B1%D9%88%D8%B9%D8%A7%D8%AA-%D8%AA%D9%85%D9%88%D9%8A%D9%84-24-%D8%A3%D9%84%D9%81-%D9%85%D8%B4%D8%B1%D9%88%D8%B9-%D8%B5%D8%BA%D9%8A%D8%B1-%D9%88%D9%85%D8%AA%D9%86%D8%A7%D9%87%D9%8A-%D8%A7%D9%84%D8%B5%D8%BA%D8%B1/7044738)

### Inferences
- Wholesale and retail trade comes to roughly **2.1 million establishments** (54.4% × 3.858M). Groceries and kiosks, clothing shops and phone shops fall in this bucket, which makes it the largest uniform target segment. Manufacturing is about 0.52M, and "other activities" (likely including services such as salons, repair and cafés) about 1.06M.
- Informal establishments average about **2.0 workers** each (3.9M workers ÷ 1.955M establishments). Across all establishments the average is about 3.9 (15.2M ÷ 3.858M). Mass-market products must therefore work for an owner with one helper: phone-first, in Arabic, with almost no setup.
- The average trade wage of EGP 3,805 (2022/23) points to very small software budgets per shop. Pricing likely has to be very low, or the product has to be paid for indirectly through payments, supplier credit or compliance. This is an inference; no willingness-to-pay data was found.
- The number of informal establishments fell slightly while informal employment kept growing. Formalization is happening, but slowly. Tax incentives (Q3) are the main lever pulling businesses into the formal system, where software becomes necessary.

### Gaps
- No breakdown by size class (1–4 workers, 5–9 workers, and so on) was obtained. Nor were counts by detailed activity: groceries, pharmacies, cafés and restaurants, salons, garages, clinics, tutoring centers, gyms. The CAPMAS publication tables could not be reached because fetch is blocked.
- The definitions in MSME Law 152/2020, and any 2025 revisions, were not verified. *Lead to verify (background knowledge, unverified):* micro = annual turnover under EGP 1M; small = EGP 1–50M; medium = EGP 50–200M.
- Social-media sellers and home-based businesses are not establishments in the census, and no count of them was found.
- No source was obtained for vertical counts. One example: a figure of "80k+ pharmacies" circulates but was not verified.

## 2. Daily operations: credit ledgers, bookkeeping, inventory, supplier ordering (B2B), cash/payments, working capital, staff/payroll

### Takeaway
Only two strands produced verified data: B2B ordering and payments.
- **B2B ordering:** FMCG B2B marketplaces have consolidated. MaxAB-Wasoko bought Fatura in May 2025, and Cartona has disclosed no new funding since 2024. The surviving players are turning to retailer credit as their profit engine.
- **Payments:** InstaPay handled US$53bn of transfers in 2024, added QR codes in June 2024 and introduced fees in April 2025.

Credit-ledger apps (كشكول الشكك, informal shop credit books), bookkeeping, inventory and expiry tracking, staffing and payroll could not be researched.

### Cited Findings
**B2B ordering platforms**
- MaxAB (Egypt) and Wasoko (Kenya) completed their merger in 2024 — [MENAbytes](https://www.menabytes.com/maxab-wasoko-complete-merger/)
  - A startup directory reports the combined company's valuation at US$526m. This was not confirmed by a primary source — [AU Startups](https://au-startups.com/startups/maxab-wasoko)
  - It operates in Egypt, Morocco, Kenya, Rwanda and Tanzania — [Tech In Africa](https://www.techinafrica.com/maxab-wasoko-bets-on-fintech-over-e-commerce-in-push-for-profitable-growth-across-africa/)
- In May 2025, MaxAB-Wasoko acquired Fatura, an Egyptian B2B e-marketplace. Fatura's network of more than 626 wholesalers served 25,000 FMCG retailers in 16 cities — [ImpactAlpha](https://impactalpha.com/maxab-wasoko-acquires-fatura-to-serve-informal-retailers-in-egypt/); [Techpoint Africa](https://techpoint.africa/news/maxab-wasoko-acquires-fatura/); [Enterprise](https://enterpriseam.com/egypt/issues/maxab-wasoko-acquires-fatura/)
- MaxAB-Wasoko's fintech arm in Egypt turns over more than US$180m a year and grew by more than 100% in the prior year. The company is "betting on fintech over e-commerce" to reach profitable growth — [Tech In Africa](https://www.techinafrica.com/maxab-wasoko-bets-on-fintech-over-e-commerce-in-push-for-profitable-growth-across-africa/)
  - The article date was not captured; it is likely from 2025.
- A Feb 2026 commentary is headlined "Wasoko-MaxAB Is Quietly Purging Its Founder DNA — And Betting Everything on Fintech." Only the headline was seen; it suggests leadership turnover — [Techmoonshot, 24 Feb 2026](https://techmoonshot.com/2026/02/24/wasoko-maxab-is-quietly-purging-its-founder-dna-and-betting-everything-on-fintech/)
- Cartona: based in Giza, founded 2019 — [Tracxn](https://tracxn.com/d/companies/cartona/__TbkVAbuFULIzvHWsqxXErHlzt8azc05kK-H4zpU1isc)
  - It has raised US$22.1m in total over four rounds from 11 investors. The latest disclosed round was US$2.5m of debt on 30 Jul 2024. No 2025–26 rounds were found — [Tracxn](https://tracxn.com/d/companies/cartona/__TbkVAbuFULIzvHWsqxXErHlzt8azc05kK-H4zpU1isc)
  - Its US$12m Series A was led by Silicon Badia — [WAYA](https://waya.media/cartona-egypts-b2b-e-commerce-platform-raises-12m-in-a-series-a-round/)
  - It then raised a US$8.1m Series A extension: US$5.6m equity plus US$2.5m debt from Camel Ventures and GlobalCorp, with the debt earmarked for retailers' working capital — [Gulf Business](https://gulfbusiness.com/egypt-based-b2b-platform-cartona-raises-8-1m/); [Tech In Africa](https://www.techinafrica.com/egyptian-b2b-e-commerce-platform-cartona-raises-8-1-million-in-extended-series-a-funding/)
  - Cartona serves more than 188,000 retailers in 17 Egyptian cities (as of 2024). It works in FMCG and HORECA (hotels, restaurants, cafés) and plans to expand into other MENA markets — [Gulf Business](https://gulfbusiness.com/egypt-based-b2b-platform-cartona-raises-8-1m/)

**Payments (InstaPay)**
- InstaPay's annual transaction value reached US$53bn in 2024 — [Egyptian Streets, 4 Jan 2026](https://egyptianstreets.com/2026/01/04/inside-egypts-instapay-economy-how-instant-payments-are-changing-access-for-a-new-generation/)
- QR-code payments arrived in June 2024, initially for person-to-person transfers, with point-of-sale (merchant) payments to follow — [Egyptian Streets](https://egyptianstreets.com/2026/01/04/inside-egypts-instapay-economy-how-instant-payments-are-changing-access-for-a-new-generation/); [Egypt Today](https://www.egypttoday.com/Article/3/132704/CBE-enhances-InstaPay-with-QR-Code-feature-for-Instant-Payments)
- In April 2025, after three years of free transfers, InstaPay began charging 0.1% per transfer, with a minimum of EGP 0.50 and a maximum of EGP 20 — [Egyptian Streets](https://egyptianstreets.com/2026/01/04/inside-egypts-instapay-economy-how-instant-payments-are-changing-access-for-a-new-generation/)
- "85 percent of Egyptian SMEs now accept digital payments" — [Egyptian Streets](https://egyptianstreets.com/2026/01/04/inside-egypts-instapay-economy-how-instant-payments-are-changing-access-for-a-new-generation/)
  - The original source was not identified. The claim sits poorly with a base in which 50.7% of establishments are informal. Treat it as unverified, and probably as covering formal SMEs only.
- The Central Bank of Egypt (CBE) has published InstaPay user numbers, but the figure was not captured — [Egypt Independent](https://www.egyptindependent.com/cbe-reveals-number-of-instapay-users-volume-of-egyptian-transactions/)

### Inferences
- **B2B is consolidating.** FMCG ordering for kiosks and groceries now centers on one large player (MaxAB-Wasoko plus Fatura) and Cartona. Competing head-on in marketplace logistics takes a lot of capital and does not suit a small team. The money these incumbents are chasing is retailer working capital (buy-now-pay-later and stock financing): MaxAB-Wasoko's fintech turnover is above US$180m, and Cartona raised debt specifically for retailer credit.
- **Positioning:** a software startup could become the retailer's day-to-day system of record (sales, credit ledger, stock) and feed that data to distributors and lenders as a partner, rather than competing with them.
- **Payment reconciliation:** InstaPay's person-to-person QR codes and new fees suggest many micro-merchants receive money into personal accounts. Confirming payments and matching transfers to sales or debts is therefore a plausible pain point. This is a hypothesis; no source documenting it was obtained.

### Gaps
- **Customer credit ledgers (كشكول الشكك / البيع بالآجل, shop credit books and credit sales):** no data on how common they are, typical balances, collection problems or default rates. No Egyptian ledger apps were identified. *To research:* Google Play Egypt listings and reviews for debt-book ("دفتر الديون") apps; whether Fawry, Paymob or MaxAB-Wasoko offer digital ledgers.
- **Bookkeeping, inventory and expiry tracking** (pharmacies, groceries): no findings.
- **Payment acceptance:** pricing and traction not obtained for Fawry, Paymob, Geidea, Kashier, PaySky, Aman, Masary, Bee or Momkn, nor for Vodafone Cash and the other telecom wallets or the Meeza national card. Merchant fees, SoftPOS (phone-as-terminal) availability and the 2026 status of InstaPay merchant QR are unverified.
- **Merchant lending:** Fawry's microfinance arm, Valu, Contact, Sympl, Souhoola and Khazna were not checked.
- **Other B2B players:** status unverified. *Lead (background knowledge, unverified):* Capiter reportedly collapsed in 2023 amid fraud allegations.
- **Staffing, payroll and social insurance:** not researched. *Leads to verify (background knowledge, unverified):* new Labour Law No. 14 of 2025 (reportedly in force from September 2025); private-sector minimum wage of EGP 7,000 from March 2025; Social Insurance Law 148/2019 contribution rates and the annual minimum and maximum insurable wage.

## 3. Regulatory forcing functions: e-invoice and B2C e-receipt mandates, the simplified tax regime, e-payment acceptance

### Takeaway
**E-receipt mandate.** The Egyptian Tax Authority (ETA) is rolling out the B2C e-receipt (الإيصال الإلكتروني) list by list, under a nine-phase deployment strategy. Two recent waves:
- From 15 Mar 2025: health, personal-care and telecom businesses in Greater Cairo and Alexandria.
- From 15 Sep 2025: further taxpayers listed under Decision 281/2025.

Failing to comply carries fines of EGP 20,000–100,000 under the Unified Tax Procedures Law. Receipt volumes quadrupled, from 400M by April 2024 to 1.6bn by September 2025.

**Simplified regime.** Law 6/2025 covers businesses with turnover up to EGP 20M and taxes turnover at 0.4–1.5%. It had 107k joiners by August 2025 and about 120k later. The state offers these joiners POS support and concessional finance. The result is a fast-growing segment of newly formal micro-businesses that need simple, compliant POS and bookkeeping.

### Cited Findings
**E-receipt (B2C)**
- The ETA adopted a nine-phase strategy for deploying the e-receipt system, phased by taxpayer segment. This comes from a search snippet whose source is one of these two pages — [ETA](https://www.eta.gov.eg/ar/news/mnzwmt-alaysal-alalktrwny-18); [Youm7 timeline explainer, May 2022](https://www.youm7.com/story/2022/5/27/%D9%83%D9%84-%D9%85%D8%A7-%D8%AA%D8%B1%D9%8A%D8%AF-%D9%85%D8%B9%D8%B1%D9%81%D8%AA%D9%87-%D8%B9%D9%86-%D8%A7%D9%84%D8%AC%D8%AF%D9%88%D9%84-%D8%A7%D9%84%D8%B2%D9%85%D9%86%D9%89-%D9%84%D8%AA%D8%B7%D8%A8%D9%8A%D9%82-%D8%A7%D9%84%D8%A5%D9%8A%D8%B5%D8%A7%D9%84-%D8%A7%D9%84%D8%A5%D9%84%D9%83%D8%AA%D8%B1%D9%88%D9%86%D9%89/5778285)
- The ETA states that e-receipt phases are separate from, and unrelated to, e-invoice phases — [ETA](https://www.eta.gov.eg/ar/news/mrahl-alzam-almmwlyn-walmklfyn-bmnzwmt-alaysal-alalktrwny-lys-lha-laqt-bmrahl-alzam-almmwlyn)
- Taxpayers listed in sub-phase 5 of main phase 4 had to issue e-receipts from 15 Jul 2024 — [ETA](https://eta.gov.eg/en/node/796). Sub-phase 4 of main phase 4 was announced earlier — [Income Tax portal](https://www.incometax.gov.eg/ar/news/almmwlyn-walmklfyn-almlzmyn-balmrhlt-alrabt-mn-almrhlt-alryysyt-alrabt-lmnzwmt-alaysal)
- Phase 7, sub-phase 1 became mandatory on 15 Mar 2025 for the health and personal-care and telecom sectors in Greater Cairo and Alexandria — [Maspero, 13 Mar 2025](https://www.maspero.eg/economy/2025/03/13/848952/%D8%A7%D9%84%D8%B6%D8%B1%D8%A7%D8%A6%D8%A8-%D8%A8%D8%AF%D8%A1-%D8%A7%D9%84%D8%A5%D9%84%D8%B2%D8%A7%D9%85-%D8%A8%D8%A7%D9%84%D9%85%D8%B1%D8%AD%D9%84%D8%A9-%D8%A7%D9%84%D8%B3%D8%A7%D8%A8%D8%B9%D8%A9-%D9%85%D9%86-%D9%85%D9%86%D8%B8%D9%88%D9%85%D8%A9-%D8%A7%D9%84%D8%A5%D9%8A%D8%B5%D8%A7%D9%84-%D8%A7%D9%84%D8%A5%D9%84%D9%83%D8%AA%D8%B1%D9%88%D9%86%D9%8A-15%D9%85%D8%A7%D8%B1%D8%B3); [Al Dostor](https://www.dostor.org/4998308)
- In January 2025, KPMG reported a new list of taxpayers required to issue B2C e-receipts — [KPMG TaxNewsFlash, Jan 2025](https://kpmg.com/us/en/taxnewsflash/news/2025/01/tnf-egypt-taxpayers-required-comply-mandate-electronic-receipts-b2c-transactions.html)
- **Decision 281/2025**, effective 15 Sep 2025. Taxpayers it lists must meet the ETA's technical operating requirements for issuing e-receipts. They must also register on the portal of the ETA's incentive program, "فاتورتك – حمايتك وجايزتك" ("Your invoice – your protection and your prize"). ETA hotline: 16395 — [Al-Ain](https://al-ain.com/article/egyptian-taxes-new-phase-electronic-receipt); [ETA](https://eta.gov.eg/ar/news/qrarat-jdydt-khast-bmnzwmt-alaysal-alalktrwny-walty-tlzm-almmwlyn-walmklfyn-alward-asmayhm)
  - VATupdate calls the 15 Sep 2025 batch "the eighth sub-phase of the second stage." It says covered taxpayers had to connect their POS devices or ERP systems to the ETA by that date — [VATupdate, 9 Aug 2025](https://www.vatupdate.com/2025/08/09/egypt-expands-e-receipt-mandate-for-b2c-transactions-starting-september-2025/)
  - Phase numbering differs between sources.
- Earlier undated headlines: "ETA issues decision on two new phases of the e-receipt system" — [Al Masdar](https://www.almasdar.com/137106); "details of applying phase 5" — [El Watan](https://www.elwatannews.com/news/details/7453821)
- Volumes: 400 million e-receipts had been submitted by the end of April 2024 — [Youm7, 30 Apr 2024](https://www.youm7.com/story/2024/4/30/%D9%85%D8%B5%D9%84%D8%AD%D8%A9-%D8%A7%D9%84%D8%B6%D8%B1%D8%A7%D8%A6%D8%A8-400%D9%85%D9%84%D9%8A%D9%88%D9%86-%D8%A5%D9%8A%D8%B5%D8%A7%D9%84-%D8%AA%D9%85-%D8%A5%D8%B1%D8%B3%D8%A7%D9%84%D9%87%D8%A7-%D8%B9%D9%84%D9%89-%D9%85%D9%86%D8%B8%D9%88%D9%85%D8%A9-%D8%A7%D9%84%D8%A5%D9%8A%D8%B5%D8%A7%D9%84-%D8%A7%D9%84%D8%A5%D9%84%D9%83%D8%AA%D8%B1%D9%88%D9%86%D9%89/6560612). By September 2025, 1.6 billion e-invoices and 1.6 billion e-receipts had been issued — [Al Borsa, 3 Sep 2025](https://www.alborsaanews.com/2025/09/03/1912754)
- The ETA presents the e-receipt as guaranteeing consumers' right to exchange and return goods, and the e-invoice as legal evidence that protects traders — [ETA](https://www.eta.gov.eg/ar/news/alaysal-alalktrwny-ydmn-hq-almsthlk-fy-altbdyl-walastrja-walfatwrt-alalktrwnyt-snd-qanwny)
  - The ETA also lowered the minimum invoice value at which the buyer's national ID must be recorded. The new threshold was not captured — [ETA](https://www.eta.gov.eg/ar/news/tkhfyd-alhd-aladny-lqymt-alfatwrt-alalktrwnyt-allazm-ladarj-byanat-alrqm-alqwmy-llmshtry)
- **Penalties:**
  - Failing to join the e-invoice system carries a fine of EGP 20,000–100,000 under the Unified Tax Procedures Law — [Youm7, 9 Oct 2022](https://www.youm7.com/story/2022/10/9/%D8%A7%D9%84%D8%B6%D8%B1%D8%A7%D8%A6%D8%A8-%D8%BA%D8%B1%D8%A7%D9%85%D8%A9-%D9%84%D8%A7-%D8%AA%D9%82%D9%84-%D8%B9%D9%86-20-%D8%A3%D9%84%D9%81-%D8%AC%D9%86%D9%8A%D9%87-%D8%B9%D9%82%D9%88%D8%A8%D8%A9-%D8%B9%D8%AF%D9%85/5934463)
  - The ETA says that not issuing e-invoices or e-receipts breaches that law and triggers its penalties. Reports describe it as tax evasion — [Youm7, 5 Jun 2024](https://www.youm7.com/story/2024/6/5/%D8%A7%D9%84%D8%B6%D8%B1%D8%A7%D8%A6%D8%A8-%D8%B9%D8%AF%D9%85-%D8%A5%D8%B5%D8%AF%D8%A7%D8%B1-%D8%A7%D9%84%D9%81%D9%88%D8%A7%D8%AA%D9%8A%D8%B1-%D8%A7%D9%84%D8%A5%D9%84%D9%83%D8%AA%D8%B1%D9%88%D9%86%D9%8A%D8%A9-%D9%85%D8%AE%D8%A7%D9%84%D9%81-%D9%84%D8%A3%D8%AD%D9%83%D8%A7%D9%85-%D9%82%D8%A7%D9%86%D9%88%D9%86-%D8%A7%D9%84%D8%A5%D8%AC%D8%B1%D8%A7%D8%A1%D8%A7%D8%AA-%D8%A7%D9%84%D8%B6%D8%B1%D9%8A%D8%A8%D9%8A%D8%A9/6599602); [Linkitsys](https://linkitsys.com/ar/%D8%B9%D9%82%D9%88%D8%A8%D8%A9-%D8%A7%D9%84%D9%81%D8%A7%D8%AA%D9%88%D8%B1%D8%A9-%D8%A7%D9%84%D8%A7%D9%84%D9%83%D8%AA%D8%B1%D9%88%D9%86%D9%8A%D8%A9/)
- **Unverified vendor claims** (not confirmed against ETA decisions; may be wrong) — [Flick Network](https://www.flick.network/en-eg/egypt-b2c-e-receipt-mandate); [DataValue](https://datavalue.solutions/egypt-e-invoicing-eta-2026-sme-guide/); [Orchida](https://orchidatax.com/countries-compliance/egypt-e-invoicing-compliance/). Vendor compliance guides in English assert that:
  - e-receipts must be sent to the ETA within 72 hours and carry a QR code on the printed receipt;
  - "a 2026 mandate" lowers the revenue threshold to EGP 250k, with a compliance deadline of 31 Mar 2026;
  - from 2026 a three-tier penalty system for late submission applies, which at its most severe can suspend invoice issuance.
- **Vendor ecosystem:** many local vendors publish 2026 e-receipt guides, a sign of competition for compliance sales — [Pioneers Solutions](https://pioneers-solutions.com/blog-electronic-invoice-receipt); [Cash For Sales](https://cash-forsales.com/ar/%D8%AF%D9%84%D9%8A%D9%84-%D8%B4%D8%A7%D9%85%D9%84-%D9%84%D9%85%D9%86%D8%B8%D9%88%D9%85%D8%A9-%D8%A7%D9%84%D8%A5%D9%8A%D8%B5%D8%A7%D9%84-%D8%A7%D9%84%D8%A5%D9%84%D9%83%D8%AA%D8%B1%D9%88%D9%86%D9%8A/); [iSales](https://www.isalesms.com/ar/%D8%AF%D9%84%D9%8A%D9%84-%D8%B4%D8%A7%D9%85%D9%84-%D9%84%D9%85%D9%86%D8%B8%D9%88%D9%85%D8%A9-%D8%A7%D9%84%D8%A5%D9%8A%D8%B5%D8%A7%D9%84-%D8%A7%D9%84%D8%A5%D9%84%D9%83%D8%AA%D8%B1%D9%88%D9%86%D9%8A/); [Daftra blog](https://www.daftra.com/blog/%D8%A7%D9%84%D9%81%D9%88%D8%A7%D8%AA%D9%8A%D8%B1/%D8%A7%D9%84%D8%A5%D9%8A%D8%B5%D8%A7%D9%84-%D8%A7%D9%84%D8%A5%D9%84%D9%83%D8%AA%D8%B1%D9%88%D9%86%D9%8A/); [Egyptian tax blog, Feb 2026](https://egptiantax.blogspot.com/2026/02/Electronic%20invoice%20and%20receipt.html)
  - International e-invoicing vendors cover Egypt too — [ClearTax](https://www.cleartax.com/eg/en/e-invoicing-egypt); [Avalara](https://www.avalara.com/us/en/vatlive/country-guides/africa-and-middle-east/egypt-vat/egyptian-e-invoicing.html); [Thomson Reuters/Pagero](https://europe.thomsonreuters.com/compliance/regulatory-updates/egypt); [2B-CS](https://www.2b-cs.com/blog/2b-1/e-invoicing-egypt-compliance-guide-39)
- **Open-source code for ETA integration exists, but on a small scale.** A GitHub repository search found three projects:
  - a .NET bridge between ERP/POS systems and the ETA e-invoicing platform (13 stars; last updated June 2026) — [GitHub: Egyptian-eInvoicing](https://github.com/mohamedelareeg/Egyptian-eInvoicing)
  - a Java signer for ETA e-invoices — [GitHub: eta-einvoice-signer](https://github.com/mostafaism1/eta-einvoice-signer)
  - a Python SDK for the ETA created in September 2026 — [GitHub: egypt-compliance](https://github.com/Infinite-Care-soultions/egypt-compliance)
  - Searches for open-source e-receipt (as opposed to e-invoice) projects returned nothing.

**Simplified tax regime (Law 6/2025)**
- Law 6/2025 offers a package of tax facilities to micro, small and medium businesses with annual turnover of up to EGP 20M. It covers businesses already registered and informal businesses that want to regularize — [Mondaq](https://www.mondaq.com/tax-authorities/1789906/%D8%A7%D9%84%D8%AA%D9%8A%D8%B3%D9%8A%D8%B1%D8%A7%D8%AA-%D8%A7%D9%84%D8%B6%D8%B1%D9%8A%D8%A8%D9%8A%D8%A9-%D8%A7%D9%84%D8%AC%D8%AF%D9%8A%D8%AF%D8%A9-%D9%81%D9%8A-%D8%A7%D9%84%D9%82%D8%A7%D9%86%D9%88%D9%86-%D8%B1%D9%82%D9%85-6-%D9%84%D8%B3%D9%86%D8%A9-2025-%D9%84%D9%84%D9%85%D8%B4%D8%B1%D9%88%D8%B9%D8%A7%D8%AA-%D8%A7%D9%84%D8%B5%D8%BA%D9%8A%D8%B1%D8%A9); [ETA](https://eta.gov.eg/ar/news/alnzam-aldryby-almbst-wfqa-llqanwn-rqm-6-lsnt-2025-frst-daymt-ldm-almnshat-alsghyrt-wthqyq)
  - It belongs to a first facilitation package made up of Laws 5, 6 and 7 of 2025 — [Allied for Legal & Tax Advice](https://alliedforlegalandtaxadvice.com/%D8%B4%D8%B1%D8%AD-%D9%85%D8%A8%D8%B3%D8%B7-%D9%84%D9%82%D8%A7%D9%86%D9%88%D9%86-%D8%B1%D9%82%D9%85-5-%D8%8C-6-%D8%8C-7-%D9%84%D8%B3%D9%86%D8%A9-2025-%D9%81%D9%8A-%D8%B4%D8%A3%D9%86-%D8%A8%D8%B9/)
- Tax is charged on turnover at graduated rates: 0.4% for turnover under EGP 500k, rising to 1.5% for turnover just under EGP 20M — [Mondaq](https://www.mondaq.com/tax-authorities/1789906/%D8%A7%D9%84%D8%AA%D9%8A%D8%B3%D9%8A%D8%B1%D8%A7%D8%AA-%D8%A7%D9%84%D8%B6%D8%B1%D9%8A%D8%A8%D9%8A%D8%A9-%D8%A7%D9%84%D8%AC%D8%AF%D9%8A%D8%AF%D8%A9-%D9%81%D9%8A-%D8%A7%D9%84%D9%82%D8%A7%D9%86%D9%88%D9%86-%D8%B1%D9%82%D9%85-6-%D9%84%D8%B3%D9%86%D8%A9-2025-%D9%84%D9%84%D9%85%D8%B4%D8%B1%D9%88%D8%B9%D8%A7%D8%AA-%D8%A7%D9%84%D8%B5%D8%BA%D9%8A%D8%B1%D8%A9); [ETA](https://eta.gov.eg/ar/news/alnzam-aldryby-almbst-wfqa-llqanwn-rqm-6-lsnt-2025-frst-daymt-ldm-almnshat-alsghyrt-wthqyq)
  - Joiners get five years without a tax audit and are exempt from capital-gains and dividend taxes, among other exemptions.
- 107,326 taxpayers had joined by 31 Aug 2025, according to ETA head Rasha Abdel Aal — [Hapi Journal, 31 Aug 2025](https://hapijournal.com/2025/08/31/%D8%B1%D8%B4%D8%A7-%D8%B9%D8%A8%D8%AF-%D8%A7%D9%84%D8%B9%D8%A7%D9%84-%D8%A7%D9%86%D8%B6%D9%85%D8%A7%D9%85-%D8%A3%D9%83%D8%AB%D8%B1-%D9%85%D9%86-107-%D8%A2%D9%84%D8%A7%D9%81-%D9%85%D9%85%D9%88%D9%84/); [Pioneers Misr](https://pioneersmisr.com/149106/)
  - The Finance Minister later cited 120,000 voluntary joiners. His headline also mentions EGP 80bn in additional tax, which may refer to the facilitation packages overall. Date not captured — [Misr Elaan](https://misrelaan.com/article/107437/%D9%88%D8%B2%D9%8A%D8%B1-%D8%A7%D9%84%D9%85%D8%A7%D9%84%D9%8A%D8%A9-120-%D8%A3%D9%84%D9%81-%D9%85%D9%85%D9%88%D9%84-%D9%8A%D9%86%D8%B6%D9%85%D9%88%D9%86-%D8%B7%D9%88%D8%A7%D8%B9%D9%8A%D8%A9)
  - The ETA said the number of joiners "exceeded expectations" — [Al Mohasben](https://almohasben.com/%D8%A7%D9%84%D8%B6%D8%B1%D8%A7%D8%A6%D8%A8-%D8%A3%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D9%85%D9%86%D8%B6%D9%85%D9%8A%D9%86-%D9%84%D9%84%D9%86%D8%B8%D8%A7%D9%85-%D8%A7%D9%84%D9%85%D9%8F%D8%A8%D8%B3/)
- The Ministry of Finance offers concessional financing to the first 100,000 customers who join the simplified regime — [El Watan](https://www.elwatannews.com/news/details/8250699)
- The ETA promises "comprehensive, unlimited support" to taxpayers under EGP 20M in the simplified regime, including point-of-sale devices and technical consultations. Whether the devices are free or subsidized was not confirmed — [ETA](https://www.eta.gov.eg/ar/news/dmana-shamlana-wbla-hdwd-lshrakayna-almmwlynalmklfyn)
- 2026 follow-ups (headlines only):
  - ETA conditions for using the simplified accounting system (8 Mar 2026) — [Youm7](https://www.youm7.com/story/2026/3/8/%D9%85%D8%B5%D9%84%D8%AD%D8%A9-%D8%A7%D9%84%D8%B6%D8%B1%D8%A7%D8%A6%D8%A8-%D8%AA%D8%B9%D9%84%D9%86-%D8%B4%D8%B1%D9%88%D8%B7-%D8%A7%D9%84%D8%A7%D8%B3%D8%AA%D9%81%D8%A7%D8%AF%D8%A9-%D9%85%D9%86-%D9%86%D8%B8%D8%A7%D9%85-%D8%A7%D9%84%D9%85%D8%AD%D8%A7%D8%B3%D8%A8%D8%A9-%D8%A7%D9%84%D9%85%D8%A8%D8%B3%D8%B7/7332324)
  - Tax facilities for commercial activities under EGP 20M (20 Apr 2026) — [FintechGate](https://fintechgate.net/2026/04/20/%D9%85%D8%B5%D9%84%D8%AD%D8%A9-%D8%A7%D9%84%D8%B6%D8%B1%D8%A7%D8%A6%D8%A8-%D8%A7%D9%84%D9%85%D8%B5%D8%B1%D9%8A%D8%A9-%D8%AA%D8%B3%D9%87%D9%8A%D9%84%D8%A7%D8%AA-%D8%B6%D8%B1%D9%8A%D8%A8%D9%8A%D8%A9/)
  - The Finance Minister says the tax procedures law includes "flexibility and simplification" (23 Jun 2026), which suggests amendments in 2026 — [Youm7](https://www.youm7.com/story/2026/6/23/%D9%88%D8%B2%D9%8A%D8%B1-%D8%A7%D9%84%D9%85%D8%A7%D9%84%D9%8A%D8%A9-%D9%82%D8%A7%D9%86%D9%88%D9%86-%D8%A7%D9%84%D8%A5%D8%AC%D8%B1%D8%A7%D8%A1%D8%A7%D8%AA-%D8%A7%D9%84%D8%B6%D8%B1%D9%8A%D8%A8%D9%8A%D8%A9-%D9%8A%D8%AA%D8%B6%D9%85%D9%86-%D9%85%D8%B1%D9%88%D9%86%D8%A9-%D9%88%D8%AA%D8%A8%D8%B3%D9%8A%D8%B7/7458417)
  - New details on the second facilitation package — [Al Dostor](https://www.dostor.org/5496595)
  - The season for filing 2025 tax returns opened on 1 Jan 2026 — [Maspero](https://www.maspero.eg/economy/2026/01/03/917895/%D8%A7%D9%84%D8%B6%D8%B1%D8%A7%D8%A6%D8%A8-%D8%A8%D8%AF%D8%A1-%D9%85%D9%88%D8%B3%D9%85-%D8%A7%D9%84%D8%A5%D9%82%D8%B1%D8%A7%D8%B1%D8%A7%D8%AA-%D8%B9%D9%86-%D8%B9%D8%A7%D9%85-2025-%D9%81%D9%8A-%D8%A7%D9%84%D8%A3%D9%88%D9%84-%D9%85%D9%86-%D9%8A%D9%86%D8%A7%D9%8A%D8%B1-2026)

### Inferences
- **The e-receipt is a real forcing function for formal B2C businesses.** It becomes mandatory once a business is named on an ETA list. It carries fines of EGP 20k–100k and is described as tax evasion when ignored. It also requires connecting a POS or ERP system to the ETA.
- **Demand arrives in waves.** The rollout goes sector by sector and region by region (for example health, personal care and telecom in Cairo and Alexandria in March 2025), so buyers appear after each new list. A startup could time its sales pushes to these lists.
- **Volume growth confirms fast onboarding.** E-receipts rose from 400M to 1.6bn in about 17 months (April 2024 to September 2025).
- **Most of the mass market has not been reached yet.** About 120k joined the simplified regime, against roughly 1.9M formal private establishments (49.3% of about 3.9M), or about 6%, plus about 1.96M informal establishments. The ETA's count of taxpayers registered for e-receipts was not found, but most micro-shops are almost certainly not issuing e-receipts yet.
- **The value is in software on top of compliance.** State POS support for simplified-regime joiners may commoditize basic e-receipt issuance. The opening for a startup is the layer above it: inventory, credit ledger, payment reconciliation, and tracking turnover for the 0.4–1.5% tax. Under a turnover tax, accurate sales records directly determine the tax bill, so the system that records sales is also the compliance system.
- **Building is feasible but harder for e-receipts.** Open-source e-invoice integration code exists, but nothing for e-receipts turned up. Any ETA qualification or certification of solutions (not verified) would be both a barrier to entry and a moat.

### Gaps
- The full list of e-receipt phases, sectors and dates for 2025–2026; which phase applies as of October 2026; and how many taxpayers are registered for e-receipts. (The ETA site was blocked.)
- Whether taxpayers in the simplified regime must issue e-receipts, and from when.
- Whether the vendor claims are true: the EGP 250k threshold, the 31 Mar 2026 deadline, the three-tier penalties and the 72-hour rule.
- The list of ETA-certified or qualified e-receipt solution providers and their prices (subscription, per POS, hardware). Not obtained.
- Mandates to accept electronic payment were not researched: Law 18/2019 on non-cash payment and its executive regulations, any requirement that merchants offer POS or e-payment, and Ministry of Supply decisions.
- What the second facilitation package contains, and whether it has been enacted. Only headlines were found.

## 4. Social commerce sellers (Facebook, Instagram, TikTok, WhatsApp): numbers, pain points, existing tools, gaps

### Takeaway
No verified findings. The shared search budget ran out before this question could be researched.

### Cited Findings
- None obtained this session.

### Inferences
- None can be supported by sources from this session.

### Gaps
- Everything on this question remains unresearched:
  - the number of social sellers;
  - the cash-on-delivery share, refusal rates (customers refusing COD parcels at the door) and return rates;
  - fake orders;
  - courier coverage and pricing (Bosta, Mylerz, J&T Express, Aramex, Egypt Post and others);
  - store builders. *Leads to verify (background knowledge, unverified):* ExpandCart, Wuilt and EasyOrders (Egyptian), Shopify, YouCan, Zid, Salla;
  - social-commerce and dropshipping platforms. *Lead:* Taager;
  - tools for capturing orders from chats and reconciling payments.
- Suggested queries for a follow-up: "نسبة المرتجع الدفع عند الاستلام" (COD return rate), "Bosta pricing 2026", "Taager 2025 funding", "بيع أونلاين فيسبوك مرتجعات" (online selling on Facebook, returns).

## 5. Vertical software (clinics, pharmacies, restaurants, salons, gyms, tutoring centers, real-estate brokers, workshops)

### Takeaway
Not researched because of tool limits. The only data point found is tangential: Daftra markets ETA e-receipt compliance content.

### Cited Findings
- Daftra, a cloud accounting/ERP vendor active in Egypt, publishes guides on "how to work with the e-receipt in 2025." This shows it uses ETA compliance as a selling point — [Daftra blog](https://www.daftra.com/blog/%D8%A7%D9%84%D9%81%D9%88%D8%A7%D8%AA%D9%8A%D8%B1/%D8%A7%D9%84%D8%A5%D9%8A%D8%B5%D8%A7%D9%84-%D8%A7%D9%84%D8%A5%D9%84%D9%83%D8%AA%D8%B1%D9%88%D9%86%D9%8A/)

### Inferences
- Phase 7 (March 2025) explicitly covered health and personal-care businesses in Cairo and Alexandria (see Q3). Clinics, pharmacies and salons there are therefore probably among the newest buyers of POS that can issue e-receipts. This is an inference from the phase scope; no adoption data was found.

### Gaps
- Unresearched: EGP prices, adoption and user complaints for Foodics and local restaurant POS; Odoo partners; clinic software (*lead:* Vezeeta's clinic tools); pharmacy systems; salon tools (*lead:* Fresha); and software for gyms, tutoring centers and brokers.

## 6. Demand for WhatsApp Business automation and Egyptian-Arabic chatbots/AI assistants

### Takeaway
No verified findings.

### Cited Findings
- None obtained this session.

### Inferences
- None can be supported by sources from this session.

### Gaps
- Unresearched: how merchants use WhatsApp; WhatsApp Business Platform pricing (*lead, background knowledge, unverified:* Meta moved to per-message pricing on 1 Jul 2025); local chatbot and voice-AI players (*leads:* WideBot, Intella, Tactful) and their pricing and traction; any evidence of demand or willingness to pay.

## 7. Willingness to pay, churn, what merchants pay for, effective sales channels

### Takeaway
No direct data on SaaS price points, churn or channel economics was obtained. Indirect signals say the money is in three things: compliance (the e-receipt mandate and its fines), getting paid (payments) and credit (B2B distributors' fintech arms). Government programs (ETA POS support, concessional finance for simplified-regime joiners) are a large channel and also a competitor.

### Cited Findings
- Distributors earn from retailers through credit. MaxAB-Wasoko's Egyptian fintech arm turns over more than US$180m a year and grew by more than 100% — [Tech In Africa](https://www.techinafrica.com/maxab-wasoko-bets-on-fintech-over-e-commerce-in-push-for-profitable-growth-across-africa/)
- Cartona raised US$2.5m of debt specifically to fund retailers' working capital — [Gulf Business](https://gulfbusiness.com/egypt-based-b2b-platform-cartona-raises-8-1m/)
- The ETA offers POS devices and technical support to simplified-regime taxpayers — [ETA](https://www.eta.gov.eg/ar/news/dmana-shamlana-wbla-hdwd-lshrakayna-almmwlynalmklfyn). The Ministry of Finance offers concessional financing to the first 100k joiners — [El Watan](https://www.elwatannews.com/news/details/8250699)
- Non-compliance with e-invoicing and e-receipts costs EGP 20,000–100,000 in fines — [Youm7, 9 Oct 2022](https://www.youm7.com/story/2022/10/9/%D8%A7%D9%84%D8%B6%D8%B1%D8%A7%D8%A6%D8%A8-%D8%BA%D8%B1%D8%A7%D9%85%D8%A9-%D9%84%D8%A7-%D8%AA%D9%82%D9%84-%D8%B9%D9%86-20-%D8%A3%D9%84%D9%81-%D8%AC%D9%86%D9%8A%D9%87-%D8%B9%D9%82%D9%88%D8%A8%D8%A9-%D8%B9%D8%AF%D9%85/5934463)
- The average wage in wholesale and retail trade establishments was EGP 3,805 in 2022/23 — [Mada Masr](https://www.madamasr.com/2025/10/27/news/%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF/%D8%A8%D9%8A%D8%A7%D9%86%D8%A7%D8%AA-%D8%A7%D9%84%D8%AA%D8%B9%D8%AF%D8%A7%D8%AF-%D8%A7%D9%84%D8%A7%D9%82%D8%AA%D8%B5%D8%A7%D8%AF%D9%8A-%D8%AA%D9%83%D8%B4%D9%81-%D8%AA%D9%8E%D8%B1%D9%83%D9%8F%D8%B2/)
- InstaPay transfers now cost 0.1% (EGP 0.50 minimum, EGP 20 maximum) since April 2025. Payment cost has become something merchants notice — [Egyptian Streets](https://egyptianstreets.com/2026/01/04/inside-egypts-instapay-economy-how-instant-payments-are-changing-access-for-a-new-generation/)

### Inferences
- **Price against the fine.** The fines (EGP 20k–100k) are large relative to micro-merchant economics, so a compliance product can be priced as insurance against them. That works only for businesses already on an ETA list or newly registered in the simplified regime.
- **Free entry, paid elsewhere.** Informal micro-shops with about two workers and low wages are unlikely to pay meaningful subscriptions. A free or cheap entry product that earns from payments, lending referrals or supplier partnerships fits better. This is an inference; no WTP or churn data was found.
- **Candidate channels:** B2B distributors already reach 188k+ retailers (Cartona) and tens of thousands more (Fatura/MaxAB-Wasoko). The ETA and Ministry of Finance onboarding programs reach about 120k simplified-regime joiners. Payment companies are a third route. Bundling through them is more plausible than direct sales alone, but it has not been verified.

### Gaps
- Actual prices for Daftra, Foodics, Odoo partners, POS bundles from Fawry, Paymob and Geidea, e-receipt providers, store builders and WhatsApp tools.
- Churn benchmarks for Egyptian SMB SaaS.
- Field-sales cost per merchant, and evidence of which channels work (bank, telecom or payment-company bundles; distributors).
- None of this was researched because the search budget was exhausted and fetching was blocked.
