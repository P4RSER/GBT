# Validation round B: paperwork, cars and housing

> Source: separate Claude Code research session session_018Ei1vy1Wr5zosykKmZQhdr, finished 2026-10-03. Produced in a validation round with its own web-search allowance; page fetches may have been blocked, so many facts come from search-result summaries. The content below is that session's final notes, unedited.

# Validation round: candidate ideas B1–B5 (Egypt), as of 2026-10-03

**Method.** I ran 5 parallel research passes, about 33–35 WebSearch calls each (~170 total), in English and Arabic. The proxy blocked WebFetch for Google Play, the App Store and most news and company sites. So **everything below comes from search-result snippets, and there are no Google Play download counts for any player.** [UNVERIFIED] marks claims from background knowledge or the researcher's own estimates. Some Egyptian news sites show the date the page was loaded rather than the date it was published, so I did not use those dates.

| # | Idea | Score | One-line reason |
|---|---|---|---|
| B1 | Paperwork navigator + vault + concierge | **2.5/5** | Real pain, but the state is taking over simple errands; what remains is heavy on operations and needs a lawyer or a power of attorney (توكيل) |
| B2 | Car paperwork + used-car history check | **2/5** | The state is taking over renewals and fines; the data a history check needs (odometer, accidents) is not accessible |
| B3 | Building / occupants'-union (اتحاد الشاغلين) management for ordinary buildings | **3/5** | Large, monthly, legally required, and nobody serves ordinary buildings; no evidence yet that people will pay |
| B4 | Verified home-services marketplace | **2/5** | Tried for 12+ years without anyone scaling; little revenue per job, and customers bypass the platform |
| B5 | Broker-free rentals + lease tools + old-rent help | **2.5/5** | The broker fee is a real pain, but the old-rent and alternative-housing angle is weak; a two-sided marketplace against funded portals |

---

## B1. Government paperwork navigator + document vault + "digital معقب" concierge

### 1. Scale
- **Life events per year**
  - Deaths: **610k in 2024**, up from 583k in 2023, so about 1,670 a day (CAPMAS figure in a snippet: https://amwalalghad.com/pifc). I could not confirm the exact article. Each death starts a chain: death certificate, inheritance determination (إعلام وراثة), pension, banks.
  - Births: **1.968M in 2024**, down from 2.045M; the first year under 2M since 2007 (https://www.parlmany.com/News/2/567662/, 2025).
  - Marriages: **936,739 contracts in 2024** (−2.5%). Divorces: 273,892 (+3.1%) (https://www.dostor.org/5325318, 30 Nov 2025).
- **Pensioners:** about **11.5M** beneficiaries at the National Organization for Social Insurance (NOSI, الهيئة القومية للتأمين الاجتماعي) (https://www.masrawy.com/news/news_economy/details/2025/11/9/2887285/, Nov 2025).
- **Egyptians abroad:** **11.08M** (Foreign Ministry estimate for 2022, https://m.akhbarelyom.com/news/newdetails/4526221/). I could not verify the commonly quoted "14M".
  - Remittances were $36.5B in FY24/25 and **$47.3B in FY25/26** (https://almalnews.com/2131609/, 2026).
- **Egypt Post:** 3.65M government transactions at post offices from launch to May 2025, across about 4,700 offices (https://amwalalghad.com/gxvn, 2025).

### 2. Existing solutions
- **Govcoo / Les Concierges Egypt**
  - Handles IDs, passports, birth certificates and other documents, with pickup and delivery. Claims 200k clients in Greater Cairo since 2013.
  - Prices were **EGP 110–750 per document**, tiered by speed from 24h to 15 days (https://scoopempire.com/get-your-governmental-papers-renewed-with-this-new-site/; an old article, about 2018 [UNVERIFIED date]).
  - **Sells through banks under its partners' brands.** It is inside Banque du Caire's "Tharwa" wealth package, covering birth, death, marriage and divorce certificates, family records and authentication, in Greater Cairo and Alexandria (https://www.bankygate.com/68137). It is probably also in Banque Misr's VIP concierge (https://banquemisr.com/ar-EG/Pages/BMVIP/Concierge-content-section).
  - No funding, app or 2025–26 news found.
- **Baseta:** a paperwork-runner service around 2014 (IDs, passports, marriage and death certificates) with about 200k Facebook likes. Press raised "legality concerns" about acting for people without a personal authorization (https://www.albawaba.com/business/egypt-legal-documents-603475). No current activity found.
- **Engizni (Enkzni):** "government services without queues", aimed at elderly and disabled people (https://gust.com/companies/engizni-startup-2). No traction data.
- **The state, which is the main competitor:**
  - Digital Egypt had 10.7M users and more than 25M transactions and queries in 2025 (https://almalnews.com/2092144/).
  - **Civil-status documents online with Egypt Post delivery:** a birth certificate costs about EGP 65 plus EGP 15–20 delivery and takes 2–4 days (https://www.dostor.org/5262958, 2025).
  - **National ID delivered home:** EGP 50 (15 days), 125 (3 days) or 175 (24h) (https://www.dostor.org/5261716, 2025).
  - **Death and inheritance certificate (إشهاد وفاة ووراثة):** family prosecution now issues it online with postal delivery at the same fee as in person, but you log in through a lawyer's account (https://www.maspero.eg/egypt/2025/02/18/843906/; https://www.masrawy.com/ 2026/4/14/2972185).
  - **Notarization Authority app «أرغب في عمل توكيل»** handles booking and fees for powers of attorney. A general specific-purpose power of attorney (توكيل عام مخصص) costs about EGP 30 in service fees (https://gate.ahram.org.eg/News/5646412.aspx; https://gate.ahram.org.eg/News/5287073.aspx).
  - Egypt Post offers about 20 government services (https://www.elwatannews.com/news/details/4998553).
  - **Consular services going digital (Aug 2026):**
    - Phase 1 is pending; birth certificates for Egyptians abroad take 3–5 days.
    - Authentication offices went from 15 to about 40 (https://egyptianstreets.com/2026/08/05/good-news-for-egyptians-abroad-consular-services-go-digital/; https://www.dailynewsegypt.com/2026/09/26/).
    - Criminal-record certificates are available online from abroad (https://english.ahram.org.eg/News/571910.aspx).
- **Informal expediters (معقب):** I found no published price lists. One lawyer guide puts the fee for an inheritance determination (إعلام وراثة) at about **EGP 1,000** (asesor.legal, 2025).
- **Digital Egypt app rating and reviews:** not retrievable, because Play was blocked.

### 3. Gap
- **Single documents are now a commodity.** The state delivers to the door for EGP 15–175, so a concierge has a thin margin on them.
- **Journeys that cross several agencies are the real gap.** No one coordinates them. The clearest case is a death:
  1. Death certificate.
  2. Inheritance determination (إعلام وراثة), filed with family court or prosecution. A court bailiff (محضر) must notify the heirs (https://www.elwatannews.com/news/details/6262891).
  3. Central Bank inquiry for the deceased's accounts. It needs the إعلام وراثة, IDs and a power of attorney that explicitly allows revealing the accounts (https://www.bankygate.com/18394).
  4. Releasing the money from each bank.
  5. NOSI survivor pension: Form 109, ID and a bank approval (masrawy, Nov 2025, above).
  6. Then the car, real estate, phone lines and so on [UNVERIFIED].
- **NOSI's new digital system (live 24 Feb 2026) caused slowdowns** and halted document issuance and some payments (https://aawsat.com/node/5265416; https://www.dostor.org/5520047, 2026). This is fresh evidence of pain.
- **Diaspora:** a power of attorney from abroad still requires appearing in person at a consulate (https://almalnews.com/1774090/). Nobody offers an end-to-end, tracked "we act on your power of attorney in Egypt" service.
- **People left out of digital services** (elderly, low-literacy, no e-payment): the evidence is indirect only (2.1M Cabinet complaints, NOSI's 2026 failures). I found no survey.

### 4. Willingness to pay and monetization
- **Price anchors:**
  - Concierge: EGP 110–750 per document (old Govcoo pricing).
  - The state's express premium: EGP 125–175.
  - Lawyer for an inheritance determination: about EGP 1,000.
  - Government fees themselves: EGP 30–65.
- **Who pays:**
  - Urban middle and upper class. Bank wealth packages already bundle a concierge, which shows a bank channel works.
  - Diaspora, paying in hard currency.
  - Bereaved families, who pay once but at a high level.
- **Prices to test [UNVERIFIED estimates]:**
  - A "death bundle" at EGP 3–8k.
  - Diaspora tasks at $30–100 each.
  - The document vault as a free hook, since people are unlikely to pay for it alone.
- **Business channels:** banks (which already pay Les Concierges), insurers, funeral services, and expat-focused fintech and remittance apps.

### 5. Regulatory constraints
- **Acting for a client needs a notarized power of attorney (توكيل),** from the Notarization Authority, or from a consulate if the client is abroad. Some documents are released only to first-degree relatives or to someone holding an official power of attorney. This adds friction for every new customer.
- **Inheritance filings run through lawyers.** Court representation requires bar registration [UNVERIFIED: Advocacy Law 17/1983], so you must partner with or employ lawyers.
- **Banks** need the heirs in person, or a power of attorney that names the account-disclosure power.
- **Document vault:** Personal Data Protection Law 151/2020 applies to stored IDs and death records [UNVERIFIED: status of its executive regulations and licensing].
- **Expediting offices (تخليص معاملات):** I found no licence category for them.

### 6. Feasibility (2–4 people)
- **MVP:**
  1. A WhatsApp-first checklist navigator for about 10 life events, starting with "a death in the family" and "I live abroad".
  2. Done-for-you service through 5–10 vetted runners and lawyers in Cairo and Giza.
  3. Status tracking.
  4. An encrypted vault.
- **Data:** the Digital Egypt catalogue, the Notarization Authority's fee lists, NOSI pages, and fee guides published by news sites.
- **Operations:** runner quality and bribery risk, liability for original documents, court timelines, collecting payment. Unit economics are driven by labour and time spent in queues.
- **Risks:**
  - Each customer needs the service rarely.
  - Customers must trust you with original documents and powers of attorney.
  - Lawyers control key steps.
  - The government keeps closing gaps.
  - Govcoo has a 13-year head start with banks.

### 7. Verdict: 2.5/5
The pain is real and national in scale: about 610k deaths, 937k marriages and 1.97M births a year, 11.5M pensioners and 11M+ Egyptians abroad. But Digital Egypt and Egypt Post have turned frequent, simple errands into a commodity. What is left is a service business heavy on operations and gated by powers of attorney and lawyers, and it has stayed niche for over a decade. It is not mass-market software.

- **Best way in:** an "after a death" navigator plus concierge for the diaspora and the urban middle class.
  - Sell it as a bundle, through banks, insurers and remittance apps.
  - Use a free checklist as SEO and the top of the funnel.
- **Red flags:**
  - The incumbent's 200k clients never became a scaled venture.
  - Legal grey zone for runners.
  - Data liability for the vault.
  - The state keeps replacing these services.
  - Reaching customers at the moment of bereavement is hard.

---

## B2. Car paperwork concierge + used-car history check

### 1. Scale
- **New registrations in 2025:** 538,385 vehicles, of which 204,695 private cars and 297,143 motorcycles (https://eg.hatla2ee.com/news/200959/, Jan 2026).
- **Used-car market:**
  - Volume is "over 1M units/yr" (https://www.kenresearch.com/industry-reports/egypt-used-car-market.md, 2026; method unclear).
  - Value was $7.53B in 2025 (https://www.mordorintelligence.com/industry-reports/egypt-used-car-market).
  - I found no official count of ownership transfers.
- **Renewal:**
  - Owners choose a licence term; new private cars are inspected after 3 years, then yearly.
  - A full renewal costs about **EGP 4,000–6,000+ for 3 years**, excluding fines. Annual tax is EGP 225–3,000 depending on engine size, or 2.5% of value above 2,030cc (https://www.dostor.org/5517900; https://www.dostor.org/5524466, 2026).
  - Estimate [UNVERIFIED]: 5.7M private cars renewing every 1–3 years gives about 2–4M renewals a year.

### 2. Existing solutions
**Government (free or cheap, and improving fast):**
- **Online renewal with home delivery** through the Interior Ministry traffic portal and Digital Egypt.
  - Only for a private car or motorcycle of 2,030cc or less, with no sales ban (حظر بيع), an electronic sticker, and all taxes and fines paid (https://www.dostor.org/5260115, 2025).
- **Fines:**
  - Checking fines by plate on the Public Prosecution portal (ppo.gov.eg/tr) is free.
  - Contesting a fine costs **EGP 100** up front (https://amwalalghad.com/a2ta).
  - You can pay by card or through Aman, Masary, Sadad or Egypt Post (https://www.dostor.org/5296171, 2025).
- **Fawry:** pays fines for about **EGP 30**; it delivers a fines certificate in about 4 working days, valid for 14 days (https://www.contactcars.com/ar/media/articles/b217e86dbcf5).
- **Mobile traffic units** come to your door for about EGP 400 (hotline 15558; Cairo Governorate, 2022; https://akhbarelyom.com/news/newdetails/4411476/1/).
- **Self-service kiosks** renew a car licence in about 60 seconds (national ID + OTP, fines paid on the spot) at City Stars and Cairo Festival City malls (https://eg.hatla2ee.com/news/201288/, 2026).
- **Vehicle data certificate (شهادة بيانات):** shows owner, chassis, engine and expiry; issued online (https://www.contactcars.com/ar/media/articles/97aab45c004b).
- **Loan liens:** the Central Bank ended paper handling, and banks now lift sales bans electronically (https://almalnews.com/1010933/).

**Private:**
- **Sylndr**
  - Raised a **$15.7M Series A in May 2025** (https://www.wamda.com/2025/05/sylndr-closes-15-7-million-series-a-drive-automotive-innovation-egypt).
  - Sylndr Plus covers inspection, maintenance and ownership transfer. Its dealer marketplace, "Al-Ajans", handles inspection, transfer and payment (https://waya.media/sylndr-closes-15-7m-in-funding-to-help-egyptians-buy-sell-finance-and-service-used-cars/).
  - Prices not found.
- **Dubizzle/Hatla2ee and ContactCars:** listings plus guides.
  - Dubizzle's services section lists third-party pre-purchase inspectors at about **EGP 500** per inspection (https://www.dubizzle.com.eg/services/car-services/; unverified snippet).
  - No branded history report found.
- **Car-care apps:**
  - FriendyM: car management with planned concierge tiers; raised $2M in Jan 2024 (https://techpoint.africa/2024/01/15/egypts-friendym-funding-scale-nationwide/). Status in 2025–26 unknown.
  - 3atlana: seed round in 2022 (https://www.wamda.com/en/2022/09/egyptian-car-service-app-3atlana-closes-seed-round).
- **No carVertical- or Carfax-style history check exists in Egypt.**
- **Informal runners (مندوب/معقب):** prices not found [UNVERIFIED].

### 3. Gap
- **Renewal concierge: the gap is shrinking.** What is still painful:
  - cars that don't qualify for online renewal (over 2,030cc, a lien, no sticker, inspection due)
  - people who aren't digital
  - fleets and small businesses
  - households with several cars
  - contesting wrong fines
- **Fines monitoring:** you have to check yourself, and radar fines pile up silently (https://www.masrawy.com/news/news_cases/details/2026/4/27/2978850/, Apr 2026).
  - **Fake traffic-fine SMS scams** prompted a government warning (https://amwalalghad.com/2026/01/17/, Jan 2026). So any third-party fine alert will look like a scam.
- **History check: the real gap.**
  - Many cars are sold on a sale power of attorney (توكيل بيع) instead of a registered transfer. Fines and accidents stay on the original owner, and the holder can resell the car more than once (https://www.contactcars.com/ar/media/articles/733de54cec14; https://www.egy-car.com/car-sale-authorization).
  - Stolen cars with forged chassis numbers keep appearing in the news (https://eg.hatla2ee.com/news/50393/).
  - No Egyptian data on odometer fraud; EU estimates are 5–12% (https://www.almuraba.net/?p=885296).

### 4. Willingness to pay and monetization
- **Price anchors:** Fawry fee EGP 30; mobile unit about EGP 400; inspection about EGP 500; the renewal itself EGP 4–6k.
- **Models [assumptions]:**
  - a history or "papers" report at EGP 150–300
  - an inspection-plus-papers bundle at EGP 800–1,500
  - selling to businesses: dealers, platforms, lenders (Valu, Contact), insurers and fleets, paying per lookup or per transfer
- **Renewal concierge:** people will likely pay a few hundred EGP at most [UNVERIFIED].

### 5. Regulatory constraints
- **Data access:** the Interior Ministry, Public Prosecution and traffic units own the data, and I found **no public API**. Scraping or automating citizen accounts (national ID + OTP) carries legal and terms-of-service risk.
- **Traffic law amendments:**
  - **Approved by the cabinet in Dec 2025:**
    - speed and lane fines rise from a maximum of EGP 2,000 to **EGP 2,000–10,000**, doubled for repeat offences
    - fines for unsecured loads and debris of EGP 5,000–15,000
    - unlicensed vehicles pay the full year's tax plus a one-third surcharge
    - Sources: https://alarabiya.net/arab-and-world/egypt/2025/12/26/; https://gate.ahram.org.eg/News/5378994.aspx
  - **Still unclear:** in Aug 2026 traffic departments were "awaiting" a new law with a 12-point licence system (https://www.parlmany.com/News/7/207389/), so **whether it has been enacted is unclear**.
- **Lien registry:** the Financial Regulatory Authority (FRA) relaunched its movable-collateral registry (Law 115/2015) with e-finance on 9 Feb 2026 (fra.gov.eg news). Whether third parties can search it, and the fees, are unknown.
- **Sales and powers of attorney:** handled by the Real Estate Registry (الشهر العقاري), which offers 22 services on Digital Egypt (https://www.youm7.com/story/2026/4/6/7361399).

### 6. Feasibility (2–4 people)
- **MVP:**
  - A WhatsApp-first service: the user sends plate and ID, you check fines by hand, remind before expiry, and book or run the renewal.
  - A **"pre-purchase pack" at about EGP 1,000:** data certificate, fines certificate, sales-ban check and a partner mechanic's inspection.
- **Data limits:** only official certificates are reliable. **Odometer and accident history have no accessible source.** Getting them needs partnerships with insurers and authorized service centres, which is a long sales cycle.
- **Risks:**
  - The state keeps digitizing.
  - No data moat.
  - Scam perception.
  - Sylndr or Dubizzle could bundle inspection and transfer for free.

### 7. Verdict: 2/5
The state is turning renewals and fines into a commodity: online renewal with delivery, EGP 30 Fawry payments, kiosks and mobile units. A history check addresses real pain (power-of-attorney sales, liens, stolen cars, odometer tampering). But the data that would make it defensible is out of reach, and what *is* reachable, buyers can get themselves.

- **Best way in:** "papers + verification" for used-car deals, sold to dealers, small showrooms and Dubizzle buyers and sellers.
  - Convert power-of-attorney sales into registered transfers, pull the certificates and ban checks, and send a partner inspector.
  - Build your own mileage and inspection dataset from each job.
  - Secondary: fine and renewal alerts for fleets and small businesses.
- **Red flags:** no official API; well-funded incumbents; regulation in flux; scam-driven distrust.

---

## B3. Building / occupants'-union (اتحاد الشاغلين) management for ordinary apartment buildings

### 1. Scale
- **Buildings and units (CAPMAS 2017 census):**
  - **16.18M buildings, of which 13.5M residential.**
  - 43.2M units, of which 12.8M are vacant.
  - Sources: https://invest-gate.me/news/egypts-capmas-reveals-latest-population-housing-census/; https://egyptindependent.com/total-number-vacant-housing-units-egypt-12-8-mn-capmas/
- **75.7% of households live in apartments**, versus 12.3% in houses (2017 census microdata sample: https://erfdataportal.com/index.php/catalog/248/variable/V2360). The urban share is about 43% (2017).
- **Every building with 5 or more units must legally form an occupants' union**, whatever its age (https://unitify.com/blog/unions-of-occupants-egypt-new-cities-maintenance-fees; https://www.elbalad.news/5134032).
- **I found no count of registered unions.** An Akhbar El-Yom column titled "مأساة اتحادات الشاغلين" ("the tragedy of occupants' unions") suggests most exist only on paper (https://m.akhbarelyom.com/news/newdetails/4808370/1/).
- **Estimate [UNVERIFIED]:** a few million urban buildings with several units, more than 10M apartment households, and fees collected every month.

### 2. Existing solutions
**Compound-focused (sold to developers and compound managers):**
- **Lyve (formerly iCommunity)**
  - Founded 2016; raised a $600K Series A from Algebra Ventures.
  - 50+ compounds and about 40K units, including Palm Hills, La Vista, MNHD and Katameya Heights.
  - Offers fee reminders, a services marketplace and gate access.
  - Still active (TAMEER's AZAD compound). No 2025–26 funding news.
  - Sources: https://startupbahrain.com/blog/icommunity-the-community-management-platform-raises-600k-in-series-a-funding-from-algebra-ventures; https://egyptinnovate.com/en/news/icommunity-is-now-lyve-a-new-facelift-simplifying-life-in-compounds; https://invest-gate.me/features/tameer-provides-topnotch-features-to-its-azad-residents/
- **Milango:** six-figure seed round led by A15 in Oct 2020; payments and gate access. Current status unknown (https://wamda.com/2020/10/milango-raises-seed-investment).
- **Unitify:** billing, collections, gate access and a resident app for compound managers in Egypt, Saudi Arabia and the UAE (https://unitify.com/egypt).
- **Developers' own apps:** Horizon Egypt, Misrrea (https://invest-gate.me/news/misr-real-estate-asset-management-company-launches-integrated-services-through-misrrea-mobile-application/).

**For ordinary buildings (small and scattered):**
- **3amaraPlus:** free, iPhone only. The building supervisor adds residents, bills, expenses and maintenance dates. No usage data (https://apps.apple.com/gb/app/3amaraplus/id6599847846).
- **A job post on the freelance site Mostaql for an "owners' union" (اتحاد الملاك) app:** shows demand, not a product. Features asked for (https://mostaql.com/project/140254):
  - an expense ledger with each resident's balance
  - chat that includes the doorman, and a monthly doorman rating
  - booking a carpenter, plumber or electrician
- **Excel templates for union accounts** sold on Khamsat (https://khamsat.com/business/erp/1766271).

**Regional comparables:**
- **Saudi Arabia, Mullak (run by the real-estate authority REGA):** 17,000 approved associations, 160K+ members and 74K+ transactions by mid-2025, with **3,600 new associations in H1 2025**. This is government-led formalization (https://rega.gov.sa/en/media-center/news/rega-owners-associations-record-185-growth-in-the-first-half-of-2025/, Aug 2025).
- **Dubai, Mollak (run by the regulator RERA):** service charges must go into a regulated escrow account; 1,500+ buildings (https://www.engelvoelkers.com/ae/en/resources/mollak-system-dubai).
- **India:**
  - **MyGate charges ₹15–25 per flat per month and NoBrokerHood about ₹25** (https://codingclave.com/guides/society-management-app-development-cost-india-2026).
  - MyGate is now pushing to earn from community services (https://the-ken.com/story/gate-secured-mygate-now-wants-to-monetise-community/).

### 3. Gap
Funded Egyptian players sell only to compounds. Ordinary city buildings, with 5–40 units run by a volunteer treasurer over WhatsApp and a notebook, have nothing beyond tiny apps and Excel sheets.

Known pain points:
- residents who don't pay
- treasurers who don't show the accounts
- disputes over the doorman's pay
- neglected elevators

The legal penalty for not paying is weak: **EGP 10–100 per month** (https://www.elbalad.news/5796336; youm7, 2021).

### 4. Willingness to pay and monetization
- **Fee levels:** I found no sourced EGP figures for building fees, doorman salaries or elevator contracts. Guess: EGP 100–500 per apartment per month in middle-class Cairo [UNVERIFIED]. **This needs checking in the field.**
- **How fees are split by law:** in proportion to each unit's share of the land, with shops and offices paying double (unitify blog, above).
- **Payment costs:**
  - **Paymob charges 2.75% + EGP 3** per transaction (https://paymob.com/en/pricing). On a EGP 300 fee that is about 3.7%, which is heavy, so prefer InstaPay or wallets.
  - Fawry's merchant rate was not found.
- **Ways to make money:**
  - free for residents
  - a small fee per apartment (the Indian price is roughly EGP 9–15 [UNVERIFIED conversion])
  - a convenience fee on digital payments
  - **a services marketplace (elevator maintenance contracts, repairs, cleaning), probably the main revenue**
  - an upgrade to professional building management
- **Who adopts:** the treasurer or union head adopts the tool; residents resist new fees.

### 5. Regulatory constraints
- **Law 119/2008 (the unified building law), Book 4, Chapter 1, articles 69–89:**
  - A union is required for any building with 5 or more units.
  - It is responsible for shared areas, elevators, guarding and cleaning.
  - It can earn income from advertising and mobile phone towers on the building (youm7, Oct 2023).
  - An earlier draft added administrative seizure of the unit for repeat non-payers (https://almalnews.com/624265/; date unclear).
- **Elevators:**
  - The owner must have a contract with a licensed elevator company for maintenance and certification.
  - Repeated accidents are blamed on weak oversight, and MPs are demanding enforcement (https://akhbarelyom.com/news/newdetails/4792651/1/).
  - A child died in an elevator in El-Salam, Cairo, in Oct 2025 (https://misrconnect.com/en/news/mobile-phones-and-accessories-stores/child-dies-in-el-salam-elevator).
- **2026 reform:**
  - On **3 Aug 2026** Housing Minister Randa El-Menshawy reviewed **draft building-law amendments that reorganize occupants' unions** and tighten government oversight. She ordered final drafts; the text is not public.
  - Sources: https://www.masrawy.com/news/realestate-news/details/2026/8/3/3027283/; https://gate.ahram.org.eg/News/5882037.aspx; https://almalnews.com/2127746/
  - Masrawy also reported "urgent alerts to governorates" on occupants' unions on 11 May 2026 (https://www.masrawy.com/news/news_egypt/details/2026/5/11/2986367/; not opened).
- **Holding money:** holding residents' funds may require a Central Bank licence. Collect through Paymob, Fawry or InstaPay and never pool funds yourself.
- **Registration:** unions register on paper at the local district office (الحي) [UNVERIFIED].

### 6. Feasibility (2–4 people)
- **MVP (about 3–4 months):** an Arabic Android app plus a WhatsApp bot with:
  - a ledger with receipt photos
  - each apartment's dues, reminders and a who-paid board
  - payment links
  - maintenance tickets
  - notices and general-assembly votes
  - an elevator contract and inspection tracker
  - a monthly PDF statement
- **Data:** no outside data needed; users create it.
- **Hard work:**
  - Signing up treasurers one building at a time, possibly through doormen and landlords.
  - Matching cash payments to the ledger.
  - Vetting service vendors.
- **Risks:**
  - low willingness to pay
  - a cash culture
  - treasurers who don't want transparency
  - WhatsApp plus Excel being "good enough"
  - payment fees eating small dues
  - losing the building when the treasurer changes
  - a government platform like Mullak, which could be a threat or a channel

### 7. Verdict: 3/5 (the strongest of the five)
**For:**
- The pain is real and monthly: collecting dues, disputes over the accounts, elevator safety.
- The base is huge: about 76% of households live in apartments, and a union is legally required for 5+ units.
- Funded players ignore ordinary buildings.
- **The 2026 amendments could force formalization, as Mullak did in Saudi Arabia.** Software is the product itself here, as with the founder's reference examples, and operations are light.

**Against:** no evidence of willingness to pay, and selling is building by building.

- **Best way in:** a free "digital treasurer" for buildings of 10–40 units with an elevator in Cairo, Giza and Alexandria (ledger, receipts, who-paid board, WhatsApp reminders).
  - Make money from elevator maintenance contracts with compliance reminders, a vendor marketplace, and a small paid tier.
  - Then offer registration and compliance once the amendments are published.
- **Red flags:**
  - Most unions aren't registered.
  - The reform text is unknown.
  - Funded players chose compounds, which hints that ordinary buildings are hard to make money from.

---

## B4. Verified home-services marketplace

### 1. Scale
- **Households:** about **25.8M** (CAPMAS 2025 estimate): 55.4% rural, 44.6% urban (https://www.erembusiness.com/economy/ragpcww, 2025).
- **AC ownership:**
  - **17.7% of households had an AC in 2019/20**, up from about 3% in 2006 (HIECS survey: https://www.erfdataportal.com/index.php/catalog/254/variable/V1490). It is likely higher now [UNVERIFIED].
  - A 1.5HP split unit cost EGP 22–34k in 2025 (https://al-ain.com/article/1-5-hp-air-conditioners-prices-egypt-2025).
- **Informal workforce:** 10–12M (Ministry of Labor: https://www.dostor.org/5282728). No count of plumbers or electricians.
- **How often households need repairs:** no data; guess 2–4 jobs a year plus seasonal AC service [UNVERIFIED].

### 2. Existing solutions
- **FilKhedma (2014)**
  - **Funding:** about **$1.2–1.25M over 4–5 rounds** (KiAngel, Algebra, Glint, Cairo Angels) (https://www.cbinsights.com/company/filkhedma/financials).
  - **Acquired 100% by South Africa's SweepSouth in Dec 2021**, when it had about 2,000 providers in 3 cities and "tens of thousands" of customers (https://www.wamda.com/en/2021/12/sweepsouth-fully-acquires-filkhedma).
  - SweepSouth closed Nigeria and Kenya in Nov 2022 but kept Egypt (https://techcabal.com/?p=105646).
  - **Last seen in Aug 2024**, operating in Cairo, Alexandria and the North Coast (https://enterpriseam.com/egypt/2024/08/30/leave-home-maintenance-to-the-pros/).
    - Vetting: written tests, in-person assessment and a criminal check.
    - Chalet cleaning costs EGP 600; deep cleaning starts at EGP 1,730.
  - iOS rating **3.4 from 256 ratings** (https://apps.apple.com/app/id1473742608).
  - No 2025–26 news, visit fee or take rate found.
- **Fixawy (Alexandria, 2016)**
  - On-demand craftsmen, plus a "Video Order" remote-repair service with Bosch.
  - Covers Greater Cairo, Alexandria, Tanta, Damanhur and the North Coast.
  - **Prices start at EGP 75 and average EGP 250** per visit or repair (https://www.dailynewsegypt.com/?p=727734, Aug 2024).
  - No funding or 2025–26 news.
- **Smaller players:**
  - Taskty (2012): about $140K raised (https://www.cbinsights.com/company/taskty).
  - AnaMehani (2018): about $350K (https://gust.com/companies/ANAMEHANI).
  - Sal7lyy: Upper Egypt, seed-funded.
  - **Osta:** appliance repair with fixed prices and a **3-month warranty**, which is exactly this pitch (https://gust.com/companies/osta0).
  - Many small apps, plus repeated Mostaql requests to build "a platform linking customers with technicians" (https://mostaql.com/project/1146976).
- **Super-apps:** no sign that Careem, Talabat or Halan offer home repair in Egypt.
- **Regional comparables:**
  - **Urban Company (India):**
    - IPO Sep 2025, listing 57% above the issue price (https://www.5paisa.com/news/urban-company-ipo-listing).
    - **Takes 20–35% commission** (https://inc42.com/?p=571319).
    - Core consumer business made a 5.6% operating margin (as a share of transaction value) in Q3 FY26 (https://www.storyboard18.com/amp/brand-marketing/urban-company-cuts-losses-65-qoq-in-q3-fy26-top-service-partners-earn-over-rs-51000-a-month-88208.htm).
  - **Justlife (UAE):** 15M bookings and a Careem partnership (https://fastcompanyme.com/?p=97121).
  - **Saudi Arabia:** Nabeeh got Ibtikar Fund investment in Jan 2025 (https://www.wamda.com/en/2025/01/ibtikar-fund-backs-nabeeh-undisclosed-investment). Others: Munjz, B8ak.

### 3. Why previous players stalled
- **Customers bypass the platform:** after a good first job, customer and technician deal directly (https://techcrunch.com/2015/07/31/why-homejoy-failed-and-the-future-of-the-on-demand-economy).
- **Low frequency:** one job doesn't pay back the cost of acquiring the customer.
- **Little capital in Egypt:** the best-funded player raised about $1.25M over 7 years and was sold.
- **Low job values:** about EGP 250 a job.
- **Drift to other categories:** FilKhedma shifted toward cleaning and beauty, which people book more often [inference].
- **Trust complaints** (overcharging, no-shows) are widely assumed, but I found no survey data [UNVERIFIED].

### 4. Willingness to pay and monetization
- **Price points:** Fixawy averages about EGP 250 a job; AC installation about EGP 1,000 in individual classified ads (https://eg.opensooq.com/ar/search/281917728, 2025).
- **The platform keeps very little:** at a 20% cut, about **EGP 50 (~$1) a job**.
- **Who pays reliably:** probably compounds, property managers, landlords, insurers and appliance retailers rather than households [UNVERIFIED].

### 5. Regulatory constraints
- **VAT:** 14% on services, with registration required above EGP 500k turnover (https://www.mondaq.com/tax-authorities/1683656/tax-compliance-for-digital-services-and-e-commerce-in-egypt).
- **Guarantees:** offering a guarantee on informal labour likely makes you liable under Consumer Protection Law 181/2018 [UNVERIFIED].
- **Payments:** cash dominates [UNVERIFIED].
- **Licensing:** no specific licence found for home-services platforms.

### 6. Feasibility (2–4 people)
- **MVP:**
  - One district, 2–3 categories (AC, plumbing, appliances).
  - A fixed price list, booking over WhatsApp, a deposit up front, and a 30–90 day free-redo guarantee.
  - 20–50 vetted technicians.
- **This is mostly an operations business:** dispatch, quality checks, disputes, spare-parts pricing, no-shows.
- **Risks:**
  - customers bypassing the platform
  - high customer acquisition cost
  - spare-parts markups undercutting fixed prices
  - technicians leaving at the summer AC peak

### 7. Verdict: 2/5
Six players have tried vetting, fixed prices or warranties since 2012, and none scaled. The economics don't work: jobs are infrequent, worth about EGP 250, and leave about $1 for the platform. Urban Company shows the model can work, but only with a decade of capital and frequently booked cleaning and beauty services.

- **Better ways in:**
  - (a) Maintenance for businesses: compounds, property managers and short-let hosts, on recurring contracts.
  - (b) An AC-only yearly subscription sold through AC retailers.
  - (c) A booking, receipts and reviews tool for independent technicians.
- **Red flags:**
  - many dormant copycats
  - no recent funding in this space in Egypt
  - heavy operations
  - liability from guarantees
  - seasonality

---

## B5. Broker-free rentals + lease and rent-collection tools + old-rent help

### 1. Scale
- **Law 164/2025:** ratified 4 Aug 2025 and **in force from 5 Aug 2025** (https://cairoscene.com/Buzz/President-El-Sisi-Approves-Amendments-to-Old-Rental-Law). So residential old-rent contracts end around **Aug 2032** and non-residential ones around Aug 2030.
- **Rent increases:**
  - Premium zones (متميزة): **20x, minimum EGP 1,000**.
  - Middle zones (متوسطة): **10x, minimum EGP 400**.
  - Economic zones (اقتصادية): **10x, minimum EGP 250**.
  - **Then +15% every year** (https://www.masrawy.com/news/news_egypt/details/2025/12/1/2900041/, Dec 2025; https://egyptindependent.com/egypts-government-issues-new-decision-regarding-the-old-rent-law/).
- **Zone committees:**
  - Their mandate was extended to early Feb 2026.
  - Cairo's results: 37% economic, 31% middle, 18% premium (https://www.egypttelegraph.com/article/215715).
  - Giza's results were published Aug 2026 (https://www.parlmany.com/News/2/590223/).
- **Affected households (2017 census):**
  - **1,642,870 old-rent households, about 6.13M people.**
  - 82% live in Cairo (41%), Giza (18.7%), Alexandria (12.9%) and Qalyubia (9%).
  - 3.19M old-rent units, of which 1.869M residential (https://m.akhbarelyom.com/news/newdetails/4620744/1/).
  - Note: round 1's "~1.8M households" likely mixes households with residential units.
- **Whole rental market:**
  - **3.3M renting households in 2017, about 1.5M of them on new rent** (https://marsadomran.info/en/2018/02/1410/). No newer split.
  - Rents in Cairo/Giza rose up to 120% per brokers (masrawy, Feb 2024).
  - Expat-skewed rents in early 2026: 1BR about EGP 35k a month (https://www.expatfocus.com/egypt/guide/egypt-property-rental-prices).
  - Mass-market rents for 2026: not found.

### 2. Existing solutions
- **The state's alternative-housing scheme:**
  - **How it works:**
    - Applications go through **Digital Egypt** with the national ID: upload the lease, track status, appeal online (https://www.egypttelegraph.com/210495).
    - Run by the Social Housing Fund.
  - **Uptake is low:**
    - 58k applications in the first 2.5 months; Asharq Al-Awsat's headline was "alternative housing doesn't tempt tenants" (https://aawsat.com/node/5225356).
    - About **102k by Jul 2026** (99.8k residential).
  - **Deadline extended to 12 Oct 2026** (https://al-ain.com/article/application-deadline-extended-alternative-units).
  - **Eligibility and terms:**
    - The applicant or spouse owns no other suitable unit and actually lives in the unit.
    - Priority goes by age, then income.
    - Payment by rent, rent-to-own, mortgage or cash (https://www.egypttelegraph.com/article/248785).
  - **About 102k applications against 1.64M households is roughly 6%.**
- **Egypt Real Estate Platform (منصة مصر العقارية, realestate.gov.eg):** a state portal backed by a shared listings database. It is adding 10 services, including search across sales and rentals (https://almalnews.com/2100915/). It could compete on verified listings.
- **Nawy:**
  - **Raised $75M in May 2025** ($52M equity, $23M debt).
  - GMV $1.4B in 2024, profitable.
  - Focuses on sales, not rentals (https://egyptianstreets.com/2025/05/13/nawy-raises-75-million-to-expand-proptech-vision-across-mena/).
- **Aqarmap:**
  - Claims 200k+ listings and 2M users; paid for by broker and developer subscriptions.
  - Its Saudi revenue now exceeds Egypt's (Jun 2025).
  - iOS rating 3.9 from 318 reviews (https://apps.apple.com/app/id642633889).
- **Property Finder EG:**
  - The parent took $525M from Permira/Blackstone plus $250M in Ares debt.
  - It signed a protocol with GOEIC (which runs the broker registry) to train and license brokers (https://www.arabfinance.com/en/news/newdetails/goeic-and-property-finder-egypt-sign-protocol-to-qualify-real-estate-brokers-for-licensing).
  - Broker-centric.
- **Dubizzle (ex-OLX) and Bayut EG:** classifieds where owners and brokers mix.
- **Small rental startups (all small; no download numbers):**
  - Roomz.rent: co-living; pre-seed Jun 2025; more than $100k of contracts in 5 months (https://www.wamda.com/en/2025/06/roomzrent-raises-pre-seed-round-led-qora71).
  - RentUp: six-figure pre-seed.
  - BirdNest: furnishing and rental management.
  - Boyot: rent collection (https://startuplist.africa/startup/boyot).
- **Complaints about fake listings or brokers posing as owners:** I found no Egypt-specific press on these [UNVERIFIED anecdotal].

### 3. Gap
- **Every portal is paid for by brokers;** none verifies owners or is free for the tenant.
- **Nobody digitizes the new-rent lifecycle:** the contract, proof of payment, annual increases, and evidence when the lease ends.
- **Law 165/2025** lets a landlord get an eviction order from the summary judge when a new-rent lease expires, and a tenant's lawsuit does not suspend it (https://dspace.id.com.eg/handle/123456789/3804). This makes clean, dated contracts valuable and should make owners more willing to let.
- **Old-rent payment disputes:**
  - If the landlord refuses the new rent, the tenant must send a bailiff's offer notice (إنذار عرض) and deposit the money at the court.
  - Failing to pay the increase counts as non-payment (https://www.dostor.org/5480714; https://www.elwatannews.com/news/details/8255705).
  - Digital receipts and dispute guidance are an unmet need.
- **Navigating the alternative-housing scheme is low value:** the portal is free, few apply, and the window closes 12 Oct 2026.

### 4. Willingness to pay and monetization
- **Broker fees today:** usually **one month's rent from the landlord AND one from the tenant**, sometimes half from one side. Sales commission is 1.5–2.5% (https://aqarmap.com.eg/ar/advice/?p=25458).
- **What a move costs the tenant:** on an EGP 8–15k rent, about EGP 8–15k in broker fees [UNVERIFIED band].
- **Ways to make money:**
  - a flat "verified deal" fee from the tenant of 25–50% of one month's rent
  - landlord software at EGP 50–150 per unit per month [UNVERIFIED]
  - paid listing boosts
  - deposit escrow
- **Comparable pricing:** none public for Boyot or RentUp.

### 5. Regulatory constraints
- **Brokerage licensing:** brokerage is regulated under Law 21/2022 plus an end-2025 decree, with registration due by Jul 2026 (https://www.propertyfinder.eg/blog/?p=27106). **A platform that takes a matching fee may itself need a GOEIC broker licence.**
- **Leases:** a lease can be notarized at the Real Estate Registry (https://gate.ahram.org.eg/News/5025116.aspx). I found **no mandatory electronic lease registry**. The "Ejar" results are Saudi.
- **Tax:** about 3M rented units are coming under real-estate tax (https://www.dostor.org/5510440), so landlords avoid paper trails. Income tax on rent [UNVERIFIED].
- **Short-term rentals** need a Ministry of Tourism holiday-home licence under Decree 209/2025 (https://www.tamimi.com/our-knowledge/publications/eyes-on-2026/articles/egypts-holiday-homes-regime-an-investment-opportunity-for-hotel-operators-and-property-owners/).
- **Constitutional challenges to Law 164:**
  - Three cases are filed at the Supreme Constitutional Court (cases 34, 37 and 38 of judicial year 47), targeting Articles 2 and 7. The court's commissioners heard them on 9 Aug 2026 (https://www.youm7.com/7489546).
  - **No ruling yet.** One unconfirmed headline claims the 7-year eviction clause was cancelled; it contradicts the Arabic press.
  - If Article 2 falls, the wave of displaced tenants shrinks.

### 6. Feasibility (2–4 people)
- **MVP:**
  - owner-verified listings (ID, plus a utility bill or contract matched to the unit, plus a video visit)
  - a lease generator following Law 4/1996 and Law 165/2025
  - a rent ledger and reminders with InstaPay or Fawry links
  - an old-rent calculator (zone, minimum rent, 15% raise, end date)
- **Operations:** verification, attracting landlords (supply), and keeping brokers out.
- **Risks:**
  - a two-sided cold start
  - brokers posing as owners
  - portals adding an "owner only" filter
  - the state portal entering rentals
  - landlords avoiding tax
  - the court ruling

### 7. Verdict: 2.5/5
Broker friction of about two months' rent per move, 3M+ renting households and Law 165/2025 all make documented, broker-free renting valuable. But the old-rent angle is weak:
- only about 6% of affected households applied for alternative housing
- the window closes 12 Oct 2026
- forced moves peak around 2032 and may be changed by the court

A broker-free marketplace means heavy operations against funded, broker-paid portals.

- **Best way in:** a free landlord tool for small new-rent landlords in Cairo and Giza (lease, rent ledger, receipts, raise and expiry alerts). Add verified owner-direct listings on top of that base later. Use the old-rent calculator as SEO, not as the product.
- **Red flags:** GOEIC licence if you take commissions; landlords avoiding tax; the state portal.

---

## Cross-cutting findings
1. **The government is the biggest competitor in B1 and B2, and it is moving fast.** Recent examples:
   - Digital Egypt plus Egypt Post delivery (EGP 15–175)
   - online death and inheritance certificates
   - car-renewal kiosks and mobile units
   - the consular digital platform (Aug 2026)
   - the state real-estate portal

   Ideas that sell a single government errand are losing their value. Ideas that use the state's rails (delivery, InstaPay, Digital Egypt) as inputs hold up better.
2. **Ideas closest to the founder's reference examples (software-first, light on operations, everyday) rank highest: B3,** then the landlord-tools wedge of B5. B1, B2 and B4 turn into service or operations businesses: runners, lawyers, inspectors, technicians.
3. **Regulatory tailwinds can drive adoption:**
   - B3: the Aug 2026 draft amendments on occupants' unions, and Saudi Mullak's growth after formalization (3,600 new associations in H1 2025).
   - B5: Law 165/2025 summary eviction rewards documented leases.
   - B2: higher traffic fines, if enacted.
4. **Payments:** card fees (Paymob 2.75% + EGP 3) are heavy on small recurring payments, so build on InstaPay or wallets. Never hold customer funds, to avoid needing a Central Bank licence.
5. **Selling through partners appears in every idea:**
   - banks already pay a concierge (B1)
   - dealers and lenders (B2)
   - elevator and maintenance vendors (B3)
   - compounds and property managers (B4)
   - landlords (B5)

   For low-frequency consumer needs, a business channel is usually the realistic route.
6. **No Egyptian player in any of the five spaces has raised significant venture money,** except adjacent giants: Sylndr ($15.7M), Nawy ($75M) and Property Finder. Several earlier startups (FilKhedma, Baseta, Milango, Taskty) stalled. This is a warning about consumer willingness to pay at Egyptian price points.
7. **WhatsApp-first MVPs fit all five** and are how a 2–4 person team should test demand before building apps.

## Gaps
- **No Google Play download counts or ratings** for any app, including Digital Egypt, because Play was blocked. Worth checking by hand.
- **B1:** informal expediter (معقب) price lists; Govcoo's current pricing and revenue; a 2025–26 diaspora count; a survey on people left out of digital services.
- **B2:** whether the traffic-law amendments and the points system are enacted; annual ownership transfers and the share of sales done by power of attorney; whether third parties can search the FRA lien registry; odometer and theft statistics; Sylndr and inspection-centre prices.
- **B3 (the most important gap, since B3 ranks highest):** actual EGP building fees, doorman salaries and elevator-contract prices; the number of registered unions; the text of the Aug 2026 draft amendments. **A field check of 20–30 Cairo buildings (treasurer interviews) is the cheapest next step.**
- **B4:** whether FilKhedma, Fixawy and Osta are active in 2025–26 and their take rates; current EGP prices for common repairs; AC ownership after 2020.
- **B5:** mass-market rents for 2026; the number of GOEIC-registered brokers and any commission cap; applicant numbers after Jul 2026; the constitutional court ruling.
- **General:** all of this rests on search snippets and was not read in full. Dates on some Arabic news pages were unreliable.
