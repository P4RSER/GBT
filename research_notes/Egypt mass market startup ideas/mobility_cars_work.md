# Egypt everyday pain points: getting around, owning and maintaining cars, and finding work (status as of 3 Oct 2026)

> **How this was researched, and the limits:** the session's shared web-search budget ran out after about 18 successful queries by this researcher. Every full-page fetch was blocked by the network egress proxy, including Wikipedia, Ahram Online, Egyptian Streets, Enterprise, Transport for Cairo, TechCrunch, Zawya, Wamda, Google Play and digital.gov.eg. As a result:
> - Most findings come from **search-engine result summaries**, not full-text reads. A few come from **GitHub repository metadata**, which was read directly.
> - Numbers should be read as "reported in search summaries". Confirm them before publishing.
> - When a summary pooled several sources, it was not always possible to tell which source gave which number. Those cases are flagged.
> - Many sub-questions are recorded as **Gaps**. These include ride-hailing complaints, intercity buses, parking, used-car fraud, maintenance, licensing and fines portals, insurance, job platforms and scams, small-business hiring, and CV demand.
> - Leads from background knowledge that could not be confirmed this session appear only under Gaps, marked "unverified lead".

## 1. Urban mobility in Greater Cairo and Alexandria: modal split, congestion and the information gap for informal transit

### Takeaway
The most recent modal split I could cite is old (2001 data, reported by the World Bank around 2006). It shows about 14.4m motorized trips a day in Greater Cairo, 68% of them on public or shared modes. The microbus ("shared taxi", 25%) was the largest single mode, and its share had been rising since the late 1980s. I could not verify any modal split or commute-time figure for 2024–2026.

Route and fare information for microbuses is still mostly undigitized:
- The main open dataset (Transport for Cairo / Digital Cairo GTFS) dates from 2017.
- Efforts in 2025–2026 are zero-traction hobby projects.
- Governorates re-set fares after every fuel-price round, with rises of about 10–15% per round.

### Cited Findings
**Modal split (old baseline)**
- Greater Cairo in 2001:
  - 14.40 million motorized trips a day.
  - 68% on transit modes: 25% shared taxi (microbus), 21% bus and minibus, 14% metro, 8% ordinary taxi.
  - 32% on private modes.
  - Sources: [World Bank – Greater Cairo: A Proposed Urban Transport Strategy](https://openknowledge.worldbank.org/entities/publication/8c1c745c-def0-5633-bd52-65ad4e1782fa/full); [World Bank – Urban Transport Strategy Review: The Case of Cairo](https://openknowledge.worldbank.org/entities/publication/254c8325-5d08-5493-8c9c-6e18fee2f4c5/full). See also the [JICA report](https://openjicareport.jica.go.jp/pdf/11709938_03.pdf). The World Bank documents are c. 2006.
- Since the late 1980s, the microbus share of daily trips has kept rising, along with metro trips, while public-bus travel declined. Cairo's transport policy led to "a considerable expansion of private microbus lines" — [World Bank Urban Transport Strategy Review](https://openknowledge.worldbank.org/entities/publication/254c8325-5d08-5493-8c9c-6e18fee2f4c5/full).
- Buses and microbuses together carry "more than two thirds" of trips in Cairo's transport system — [TfC R&D blog: Comparing public transit modes in Egypt](https://rnd.transportforcairo.com/blog/comparing-public-transit-modes-egypt). The page could not be read and its date is unknown; the attribution comes from a search summary.

**Who maps informal transit**
- Transport for Cairo (TfC):
  - Started as a grassroots effort to map Greater Cairo's public transport network.
  - Is now a strategic advisory practice in urban mobility that builds passenger information systems (transit maps, wayfinding).
  - Has mapped 5 African metropolitan areas.
  - States that "most African commuters rely on paratransit provided by driver-entrepreneurs".
  - Builds "RouteLab" digital tools for collecting data in data-poor environments.
  - Sources: [TfC 2025 Q1 Passenger Information Portfolio (uploaded Jul 2025)](https://transportforcairo.com/wp-content/uploads/2025/07/2025Q1_TfC-Passenger-Information-Portfolio.pdf); [La Fabrique des Mobilités wiki](https://wiki.lafabriquedesmobilites.fr/wiki/Transport_for_Cairo_(TfC)); [Egyptian Streets, May 2021](https://egyptianstreets.com/2021/05/23/transport-for-cairo-the-startup-mapping-movement-in-egypt-and-across-africa/); [Happy Cities blog](https://happycities.com/blog/cairo-transport-advocates-create-a-grassroots-transit-map-2).
- Alexandria: TfC and WRI produced a "Digital Transport for Africa" (DT4A) report on Alexandria (Sep 2023) — [WRI–TfC DT4A Alexandria final report](https://transportforcairo.com/wp-content/uploads/2023/09/WRI-TfC-DT4A_Alex_FinalReport_V2-1.pdf). Earlier: [TfC Passenger Information Systems portfolio Q1 2022](https://transportforcairo.com/wp-content/uploads/2022/08/TfC-Maps-Passenger-Information-Systems-Practice-Portfolio-Q1-2022.pdf).

**Open data (read directly from GitHub metadata)**
- TfC publishes two datasets:
  - A Cairo Metro GTFS, "Data Release for Open Data Day Cairo 2016"; repo created Feb 2016 — [transportforcairo/Metro-GTFS](https://github.com/transportforcairo/Metro-GTFS).
  - "GIS & GTFS Transit data for the GCR, produced by the Digital Cairo project" (2017 vintage; repo created Aug 2018) — [transportforcairo/Transit---GCR-Digital-Cairo-2017-](https://github.com/transportforcairo/Transit---GCR-Digital-Cairo-2017-).
- Independent projects on informal transit, 2025–2026. All have 0 GitHub stars, so they are prototypes:
  - "cairo-bus-map" (created 6 Aug 2026): an interactive map of formal buses, paratransit ("microbus/tomnaya/minibus") and metro, built "from Transport for Cairo GTFS + OpenStreetMap" — [repo](https://github.com/Miqell24/cairo-bus-map).
  - "d-nerve" (created Nov 2025): a FastAPI/PostGIS backend "for Cairo's informal microbus network", with route discovery and ETA prediction — [repo](https://github.com/d-nerve-cairo/d-nerve-backend).
  - "Aroh-Ezay" (Arabic for "how do I get there", created Jan 2026): an "AI-powered Cairo transit guide" that answers microbus and metro route questions in Egyptian Arabic using Gemini and Llama 3 — [repo](https://github.com/AhmedHesham202/Aroh-Ezay-App).
  - Port Said bus/minibus GTFS (Dec 2025) — [repo](https://github.com/youssefelzedy/PortSaid-Transit-GTFS).
  - A Cairo transport optimization student project (May 2025) — [repo](https://github.com/Salahmohameds/Cairo-Transportation-Optimization-System).

**Fares and fare changes**
- After each decision by the fuel-pricing committee, governorates announce new fares for microbus, "service" and collective transport.
  - Rises run 10–15% nationwide.
  - Alexandria set +15% for diesel vehicles and up to +10% for petrol vehicles. This was in the round that took 92-octane from EGP 17.25 to 19.25 (October 2025).
  - Sources: [Masrawy](https://www.masrawy.com/news/news_regions/details/2025/4/11/2768913); [El Balad](https://www.elbalad.news/6540101); [Al Bawaba News](https://www.albawabhnews.com/4979121). The search summary pooled these, so I can't tell which source gave each number.
- Coverage of fare revisions recurs with each fuel round. Masrawy items on fare changes are dated 25 Jul 2024 and 11 Apr 2025 — [Masrawy, Jul 2024](https://www.masrawy.com/news/news_egypt/details/2024/7/25/2616966); [Masrawy, Apr 2025](https://www.masrawy.com/news/news_regions/details/2025/4/11/2768913).
- A Parlmany feature is titled "أجرة مواصلات مصر.. اسأل قبل ما تركب" ("Egypt transport fares: ask before you ride") — [Parlmany](https://www.parlmany.com/News/7/136629/أجرة-مواصلات-مصر-اسأل-قبل-ما-تركب). Publication date unclear.

**Regional concentration**
- Cairo governorate alone held 2.8m of Egypt's 11.05m licensed vehicles at end-2025, about 25% — [Banker.news](https://banker.news/134859); [Erem Business](https://www.erembusiness.com/cars/0ooi2a0).

### Inferences
- **The microbus is probably still the backbone.**
  - In 2001, 25% of 14.4m trips meant about 3.6m microbus trips a day.
  - The share was rising and policy favoured private microbus lines (World Bank), so microbuses very likely remain the largest single mode.
  - Population growth implies today's absolute numbers are materially higher. No current figure was verified.
- **The information gap is structural.**
  - The most complete open paratransit dataset is about 9 years old (2017).
  - It predates the BRT (2025), the monorail (2026), metro extensions and the growth of new cities.
  - Three independent microbus-routing projects appeared within 10 months (Nov 2025–Aug 2026). That signals a felt need, but no consumer product has traction.
- **Fares are volatile data.**
  - Fare revisions are documented after the Jul 2024, Apr 2025 and Oct 2025 fuel rounds: the dated Masrawy coverage matches the fuel-hike dates, and the Oct 2025 round is described in the search summary.
  - The Mar 2026 fuel hike very likely triggered a fourth round, but that is inferred, not verified.
  - Any routing product needs a cheap way to keep fares current, such as crowdsourced fare reports, rather than static tables.
- **Business model signal.** TfC's model is consulting for governments and development partners, plus printed or digital maps. This suggests passenger information in Egypt has been funded by institutions rather than by consumers.

### Gaps
- No 2024–2026 modal split for Greater Cairo or Alexandria.
- No current shares for ride-hailing or tuk-tuks.
- No verified average commute time or congestion index (e.g., TomTom). Search budget was exhausted before these queries.
- A World Bank congestion-cost estimate is often quoted (about 3.6% of GDP, 2014 study). **Unverified lead**, not confirmed this session.
- Tuk-tuk fleet size (licensed vs unlicensed) and governorate rules: not found.
- Whether Google Maps or Moovit show Cairo or Alexandria microbus routes in 2026: not verified.
- Current microbus fare levels by governorate and line: not captured.
- The contents of TfC's 2025 portfolio and the DT4A Alexandria report (route counts, mode shares) could not be read.

## 2. New mass transit (metro, monorail, LRT, BRT) and intercity rail: what opened, how people get information, how they pay

### Takeaway
Greater Cairo added two new formal modes in about 10 months:
- **Ring Road BRT:** fully operational 3 Jul 2025.
- **East Nile monorail:** passenger service from 6 May 2026.

Early monorail ridership is far below its target. An AFP ride in late May 2026 found 30–50 people across four cars, against an official target of 500–600k a day once the West Nile line opens (expected 2027). Monorail fares are distance-based and relatively high (EGP 20–80).

Egyptian National Railways (ENR) intercity rail now sells through 7 channels, including an app with e-payment, but limits booking to 15 days ahead and 4 tickets a day. I could not verify the current metro fare table, ridership, or whether payment is integrated across modes.

### Cited Findings
**Monorail**
- East Nile line inaugurated 20 Mar 2026; passenger service began 6 May 2026 — [Wikipedia: Cairo Monorail](https://en.wikipedia.org/wiki/Cairo_Monorail); [Al-Ahram Weekly: "Monorail opens to the public"](https://english.ahram.org.eg/NewsContent/50/1201/567832/AlAhram-Weekly/Egypt/Monorail-opens-to-the-public-.aspx).
- The National ran a story headlined as an inauguration on 7 Aug 2026 — [The National](https://www.thenationalnews.com/news/mena/2026/08/07/cairo-monorail-inaugurated-first-africa/). Content not read; it may describe a later formal ceremony.
- Fares, announced May 2026:
  - Up to 5 stations EGP 20; 10 stations EGP 40; 15 stations EGP 55; full line EGP 80.
  - 50% discount for people over 60 and people with disabilities, so the maximum is EGP 40 for them.
  - Source: [Egyptian Streets, 9 May 2026](https://egyptianstreets.com/2026/05/09/egypt-announced-monorail-ticket-prices/).
- Ridership:
  - Officials cite 500,000–600,000 riders a day once the West Nile line (Giza–6th of October City) comes online "next year".
  - A ride on a Thursday afternoon found "between 30 and 50 people across the train's four cars".
  - Source: [Malay Mail / AFP, 28 May 2026](https://www.malaymail.com/amp/news/life/2026/05/28/cairos-new-monorail-glides-above-a-city-struggling-below/221568).

**Ring Road BRT**
- Trial operations began 3 Jun 2025; fully operational 3 Jul 2025.
- Phase 1 runs 35 km from the Alexandria Agricultural Road to the Police Academy, with 14 stations and 100 air-conditioned electric buses.
- Three phases will total 48 stations.
- Sources: [Wikipedia: Cairo BRT](https://en.wikipedia.org/wiki/Cairo_Bus_Rapid_Transit); [Egyptian Streets, 25 May 2025](https://egyptianstreets.com/2025/05/25/cairos-new-bus-rapid-transit-system-a-leap-towards-sustainable-urban-mobility/); [Cairo Governorate BRT page](https://cairo.gov.eg/en/governorate-services/transportation-services/bus-rapid-transit/); [Egyptian Streets, 18 Apr 2025 (driver training)](https://egyptianstreets.com/2025/04/18/transport-ministry-begins-training-for-brt-bus-drivers-ahead-of-launch-on-cairo-ring-road); [Enterprise explainer](https://enterpriseam.com/egypt/hardhats/cairos-ring-road-isnt-just-getting-wider-its-getting-a-brt-lane-heres-why-thats-a-great-idea/).
- No BRT ridership figures were found for 2025–2026. The search summary explicitly reported none.

**Intercity rail (ENR)**
- ENR sells through 7 booking channels:
  - station ticket windows
  - the official website
  - the "Egyptian National Railways" mobile app
  - agents of e-payment collection companies
  - the 1661 voice line
  - city booking offices
  - self-service machines in major stations
- Customers can pay by bank card or e-payment and keep the e-ticket on their phone.
- Booking opens 15 days before departure, with a maximum of 4 tickets a day.
- Sources: [Al Bawaba News](https://www.albawabhnews.com/4857016); [El Balad](https://www.elbalad.news/6899339); [Akhbar El Yom – Eid al-Fitr 2026 train booking methods](https://m.akhbarelyom.com/news/NewDetails/4790907/1/تعرف-على-طرق-حجز-تذاكر-قطارات-عيد-الفطر-).
- An Akhbar El Yom headline reads "مش بيرضوا يحجزوا روسي.. ركاب القطارات يش[…]", roughly "They won't book [us on the] Russian [coaches]… train passengers complain" — [Akhbar El Yom](https://akhbarelyom.com/news/newdetails/3236002/1/-مش-بيرضوا-يحجزوا-روسي--ركاب-القطارات-يش). Date and details not read.

### Inferences
- **The monorail's demand problem is likely about access and price, not capacity.** Very low early loads against a 500–600k/day target suggest people do not know how to reach stations, cannot get from station to final destination easily, or find EGP 20–80 high next to informal options. The AFP headline frames it as gliding "above a city struggling below". This is suggestive, not proof of cause.
- **Re-learning routes is a recurring pain.** BRT (2025), monorail (2026) and the planned West Nile monorail (2027) each force commuters to re-learn routes and transfers. Information products that combine formal and informal legs would have a recurring trigger.
- **Payment is probably fragmented.** I found no evidence of a unified card or app across metro, monorail, BRT, LRT, ENR and microbus (cash). This is inferred from the lack of evidence, not verified. If true, it is a friction for multimodal commuters and a partnership opening for wallets and fintechs.
- **Intermediated booking.** ENR's channel list includes agents, a voice line and city offices. This shows a large share of travellers still rely on assisted booking, a coping behaviour that suggests digital booking is not easy for everyone.

### Gaps
- **Current metro fare table.** A search summary gave zone fares of EGP 5/7/10 for Line 3 and subscriptions from EGP 310 a month. These look like older (pre-2024) values. A 2026 Dostor headline, "سعر تذكرة المترو بعد الزيادة الجديدة" ("metro ticket price after the new increase"), suggests a newer rise — [Dostor](https://www.dostor.org/5483591); [Dostor – subscriptions](https://www.dostor.org/5485162). Treat the fare table as unverified.
- Not verified: metro daily ridership; status of Line 3 completion and Lines 4 and 6; LRT (10th of Ramadan) ridership; Alexandria projects (Abu Qir metro, Raml tram).
- Not verified: whether metro, monorail or BRT accept contactless bank cards, QR codes or Meeza.
- Not verified: ENR app downloads, ratings and specific complaints.

## 3. Ride-hailing, intercity buses and parking

### Takeaway
- **inDrive** (riders bid their own price) was Egypt's most-downloaded ride-hailing app in 2024. It has added courier (2025) and city-to-city products in Egypt.
- **Swvl** survived by pivoting to enterprises and governments. In Aug 2026 it raised $13m from investors led by Coefficient LP (backed by the Sawiris family) to expand in the US.
- **Women's safety** with Uber drivers has been the main public controversy, around 2024. Egypt's 2018 ride-hailing law centres on licensing and data retention.

Intercity bus operators (Go Bus, Blue Bus and others), Uber/Careem/DiDi status, price complaints after the Mar 2026 fuel hike, and parking could not be researched this session.

### Cited Findings
**inDrive**
- inDrive was the leading ride-hailing app by downloads in Egypt's travel category in 2024 — [Business Wire, 6 Feb 2025](https://www.businesswire.com/news/home/20250206210021/en). It led the travel category in several markets including Egypt — [Autocar PH, 2025](https://autocar.com.ph/indrive-is-the-4th-most-in-demand-travel-app-in-2025/).
- inDrive launched courier delivery in Egypt in 2025, and its "City to City" intercity rides operate in Egypt — [inDrive article (Wikipedia mirror, Mar 2026 snapshot)](https://wiki.krisyotam.com/content/wikipedia_en_all_nopic_2026-03/InDrive); [HandWiki: inDrive](https://handwiki.org/wiki/Company:InDrive). The search summary did not say which of these sources gave this fact.
- inDrive's MENA business (led by Egypt and Saudi Arabia) reportedly grew users by more than 50% a year, with about 120m trips and an estimated $220m regional revenue in FY2025 — [Canvas Business Model](https://canvasbusinessmodel.com/products/indrive-bcg-matrix). This is a **low-reliability aggregator; treat as unverified.**
- Globally, inDrive was the second most-downloaded ride-hailing app for the fourth year running in 2025, with more than 400m downloads — [Himalayan Times](https://thehimalayantimes.com/business/indrive-retains-no-2-global-ride-hailing-app-rank-for-fourth-year).

**Swvl**
- In Aug 2026 Swvl announced a $13m private placement (PIPE) "priced at the market under Nasdaq rules".
  - It was led by Coefficient LP, a US firm backed by the Sawiris family, which invested $10m and became Swvl's largest institutional shareholder.
  - The stated aim is to "anchor its next phase of growth and US expansion".
  - Sources: [Wamda, Aug 2026](https://www.wamda.com/2026/08/swvl-secures-13-million-investment-led-sawiris-backed-coefficient); [press release via Finviz](https://finviz.com/news/385165/swvl-announces-13-million-strategic-investment-round-priced-at-the-market-under-nasdaq-rules-led-by-the-sawiris-family-and-coefficient-lp-to-anchor-its-next-phase-of-growth-and-us-expansion).
- Swvl remains Nasdaq-listed; its share price was $1.39 on 3 Aug 2026 — [PitchBook](https://pitchbook.com/profiles/company/183318-31).
- Swvl has about 596 employees, is positioned as a mobility-solutions provider for enterprises and governments, and earns most of its revenue in Egypt — [StartupHub.ai profile](https://www.startuphub.ai/startups/swvl.md). **Low-reliability profile.**

**Regulation and safety**
- Egypt's 2018 ride-hailing law set operating licences and fees, and requires companies to store user data for 180 days and hand it to security authorities on request — [Arab News](https://www.arabnews.com/node/1298436/amp); [Gulf News](https://gulfnews.com/business/egypt-approves-law-to-govern-popular-ride-hailing-apps-1.2217966).
- Ride-hailing apps became popular with women because of widespread sexual harassment, including by some taxi drivers — [KUNC/NPR, Mar 2016](https://www.kunc.org/2016-03-28/amid-ride-booking-rivalries-many-cairo-women-turn-to-uber-for-safe-passage).
- "A recent streak of violence against women by Uber drivers sparked nationwide controversy." Uber's MENA head of public policy met MPs "in May" to ask for access to drivers' criminal records — [Egyptian Streets](https://egyptianstreets.com/?p=91310); [Egyptian Streets](https://egyptianstreets.com/?p=92469). Likely 2024; dates not read.

### Inferences
- **Riders are price-sensitive.** inDrive's lead in downloads suggests riders value negotiating fares. The pressure has grown: 92-octane rose about 29% in roughly 5 months (Oct 2025–Mar 2026; see section 4), which squeezes both drivers and riders. Expect more haggling, cancellations and "outside-the-app" deals.
- **Consumer bus-pooling is hard to monetize.** Swvl's pivot from consumer bus-pooling to enterprise and government transport, and its new US focus, suggest this. Enterprise staff transport has budgets. That is relevant for any startup weighing B2C vs B2B mobility.
- **Safety is a lasting decision factor for women.** Safety features (verified drivers, trip-sharing, women-driver options) are a differentiator, but they need regulator and platform cooperation. Willingness to pay is unknown.

### Gaps
- Uber, Careem and DiDi: current Egypt operations, market shares, driver and rider numbers, and fare changes after the Mar 2026 fuel hike. Not verified.
- **Unverified lead:** the 2024 Habiba El-Shamaa case, a woman who died after jumping from an Uber, followed by a driver conviction. Not confirmed this session.
- Intercity bus operators (Go Bus, Blue Bus, Super Jet, West & Mid Delta, Upper Egypt Bus): booking channels, app traction, prices and complaints. Not researched (budget).
- Parking: informal "سايس" attendants, any parking law and its enforcement, smart meters or apps in Cairo and Alexandria. Not researched. **Unverified lead:** a 2020 law regulating parking attendants.

## 4. Car ownership, new-car prices and overprice, and fuel

### Takeaway
- **Fleet:** Egypt had 11.05m licensed vehicles at end-2025 (+6.1% on the year), including about 5.7m private cars. Cairo accounts for 2.8m vehicles.
- **New-car sales:** 173.8k units in 2025 (+69.9%), recovering from a very weak 2024 (implied about 102k). Imports outgrew local assembly.
- **Overprice** (the dealer premium above list price) faded around mid-2025 but returned on some 2026 models, at EGP 20–40k.
- **Fuel** is the sharpest running-cost shock. 92-octane went from EGP 17.25 to 22.25 a litre between Oct 2025 and 10 Mar 2026, a 29% rise, as the pound crossed 52 per US dollar.

### Cited Findings
**Fleet**
- Licensed vehicles: 9.95m at end-2023 → 10.41m at end-2024 (+4.7%) → 11.05m at end-2025 (+6.1%). Cairo governorate leads with 2.8m (2025) — [Banker.news](https://www.banker.news/101452); [Banker.news](https://banker.news/134859); [Erem Business](https://www.erembusiness.com/cars/0ooi2a0); [Al Arabiya, 18 Apr 2024 ("10 million licensed vehicles")](https://www.alarabiya.net/aswaq/cars/2024/04/18/10-%D9%85%D9%84%D8%A7%D9%8A%D9%8A%D9%86-%D9%85%D8%B1%D9%83%D8%A8%D8%A9-%D8%B9%D9%84%D9%89-%D9%85%D8%B1%D8%AE%D8%B5%D8%A9-%D8%B9%D9%84%D9%89-%D8%A7%D9%84%D8%B7%D8%B1%D9%82-%D8%A7%D9%84%D9%85%D8%B5%D8%B1%D9%8A%D8%A9).
- About 5.7m licensed private cars in 2025 — [Ken Research, Egypt Used Car Market 2026–2032 (search summary)](https://www.kenresearch.com/industry-reports/egypt-used-car-market.md). Which source in the summary gave this number is uncertain.

**New-car sales (AMIC data)**
- Jan–Jul 2025: 90,100 vehicles, up 83% from 49,230 a year earlier. That was 69,790 passenger cars, 5,560 buses and 14,750 trucks — [Business Today Egypt](https://www.businesstodayegypt.com/amp/1/6678/Egypt’s-car-sales-surge-83-in-first-seven-months-of); [Egyptian Streets, 1 Sep 2025](https://egyptianstreets.com/2025/09/01/egypts-car-sales-jump-83-in-first-seven-months-of-2025).
- Full year 2025: 173.8k units (+69.9%). Passenger cars +64.4%, buses +53.6%, trucks +108.4%. Imports outpaced locally assembled vehicles — [Enterprise, 5 Feb 2026](https://enterpriseam.com/egypt/2026/02/05/auto-sales-were-up-69-9-in-2025-but-imports-outpaced-locally-assembled-vehicles-at-an-increased-rate/).

**Overprice (الأوفر برايس)**
- Overprice fell noticeably in mid-2025 as the dollar stabilized and supply improved.
- For 2026 models, the Chevrolet Optra carries EGP 20–40k overprice and the Hyundai Accent RB EGP 20k. One headline reads "سيارات تعود إلى الأوفر برايس رغم هبوط الأسعار.. احذر من شرائها" ("Cars return to overprice despite falling prices… beware of buying them").
- Sources: [AboutMsr](https://aboutmsr.com/سيارات-تعود-إلى-الأوفر-برايس-رغم-هبوط/); [Akhbar El Yom – "2026 models: will they bring relief?"](https://m.akhbarelyom.com/news/NewDetails/4652113/1/%D8%B7%D8%B1%D8%A7%D8%B2%D8%A7%D8%AA-%D8%B3%D9%8A%D8%A7%D8%B1%D8%A7%D8%AA-2026-%D9%87%D9%84-%D8%AA%D8%AD%D9%82%D9%82-%D8%A7%D9%84%D8%A7%D9%86%D9%81%D8%B1%D8%A7%D8%AC%D8%A9-%D8%A7%D9%84%D9%85).

**Fuel**
- October 2025 increases, per litre:
  - 95-octane: EGP 19 → 21
  - 92-octane: EGP 17.25 → 19.25
  - 80-octane: EGP 15.75 → 17.75
  - diesel: EGP 15.50 → 17.50
  - Sources (pooled in the fare search summary): [Masrawy](https://www.masrawy.com/news/news_regions/details/2025/4/11/2768913); [El Balad](https://www.elbalad.news/6540101). The 92-octane change is confirmed by [Egyptian Streets, 10 Mar 2026](https://egyptianstreets.com/2026/03/10/egypt-raises-fuel-prices-by-egp-3-per-litre/).
- 10 March 2026: several fuel products rose by EGP 3 a litre, taking 92-octane to EGP 22.25 (about $0.43).
  - Reasons given: geopolitical tensions, higher import, production and shipping costs.
  - The pound had just crossed EGP 52 per dollar.
  - Source: [Egyptian Streets, 10 Mar 2026](https://egyptianstreets.com/2026/03/10/egypt-raises-fuel-prices-by-egp-3-per-litre/).
- The Prime Minister promised no more petrol price changes for 6 months — [CairoScene](https://cairoscene.com/buzz/prime-minister-assures-no-more-changes-in-petrol-prices-for-6-months). Date not confirmed. If the pledge followed the March 2026 hike, the freeze would have ended around September 2026.

### Inferences
- **Ownership rate.**
  - 5.7m private cars implies roughly 52–53 private cars per 1,000 people.
  - 11.05m vehicles of all types implies about 100 per 1,000.
  - Both figures assume a population of about 107–109m, which was not verified this session.
  - Car-related services therefore reach a large but mostly middle-class minority. Microbus and public-transport services reach the majority.
- **Fleet growth.** 2024 sales implied by the 2025 growth rate were about 102k units (173.8k ÷ 1.699). The fleet still grew by about 640k vehicles in 2025 (10.41m → 11.05m), far more than new sales. Possible explanations are motorcycles, tuk-tuks, re-licensing or other categories not covered by AMIC. This was not verified.
- **Fuel cost example (illustrative assumption).** A commuter driving 1,000 km a month at 8 L/100 km uses about 80 L. That costs about EGP 1,380 at EGP 17.25 and EGP 1,780 at EGP 22.25, so about EGP 400 a month more (+29%) within roughly five months. The pressure is larger for taxi, ride-hailing and microbus drivers, who pass it on through fare rounds.
- **Price opacity.** FX swings (EGP 52+) and the return of overprice on popular models mean buyers struggle to know a "fair" price. That points to price-tracking, dealer-quote comparison and alert tools. The fact that buyers pay EGP 20–40k premiums for quick delivery shows they will pay for certainty and speed.

### Gaps
- Official cars-per-1,000 figure and the share of households owning a car: not found.
- Fleet breakdown by type (private, taxi, microbus, truck, motorcycle, tuk-tuk) for 2025: not captured. The Parlmany article "سيارة كل دقيقة.. 10.4 مليون مركبة" ("a car every minute… 10.4 million vehicles") could not be fetched.
- Car price changes after the pound weakened past 52/USD in Mar 2026: not verified.
- Any fuel-price decision after March 2026 (for example in Sep/Oct 2026): not verified.
- CNG conversion volumes, EV adoption and car-loan rates: not found.

## 5. Used cars, inspection and fraud, maintenance, licensing and fines, insurance — and existing apps

### Takeaway
The used-car market is large and mostly informal:
- Estimates are about 750k used-car sales a year versus about 250k new, roughly a $14bn market and more than 2,000 sales a day. These figures are of uncertain vintage, possibly 2022.
- About 71% of activity in 2024 was unorganized sellers.

Platforms are consolidating and getting capital:
- Dubizzle acquired Hatla2ee in Feb 2025.
- Sylndr raised $12.6m in 2022 and a later $15.7m round, betting on inspection and financing.

I could not quantify fraud (odometer rollback, hidden accidents, unpaid fines or instalments), maintenance and spare-parts pain, licensing renewal and fines pain, or insurance, because of tool limits.

### Cited Findings
- Market estimates: roughly $14bn, more than 2,000 used cars sold daily, and about 250,000 new vs about 750,000 used cars sold a year — [TechCrunch (search summary)](https://techcrunch.com/?p=2323007); [Ken Research](https://www.kenresearch.com/industry-reports/egypt-used-car-market.md). The TechCrunch item is probably 2022 coverage of Sylndr's first raise, so these figures may be 2022-vintage.
- Unorganized sellers made up 71.33% of used-car market activity in 2024. Organized formats are growing faster, helped by inspection, warranties, financing and digital valuation — [Ken Research](https://www.kenresearch.com/industry-reports/egypt-used-car-market.md). This is a paid-report summary with unknown method.
- Used-car classifieds include Hatla2ee, Contact Cars and OLX (now Dubizzle) — [TechCrunch (search summary)](https://techcrunch.com/?p=2323007).
- Hatla2ee (Cairo; CB Insights lists founding year 2016) was acquired by Dubizzle Group in February 2025 — [CB Insights](https://www.cbinsights.com/company/hatla2eecom); [CB Insights: Hatla2ee vs Sylndr](https://www.cbinsights.com/compare/hatla2eecom-vs-sylndr).
- Sylndr (founded 2022, Cairo) buys and sells used cars and offers financing. It raised $12.6m in May 2022 — [The National, 23 May 2022](https://thenational-the-national-prod.cdn.arcpublishing.com/business/2022/05/23/sylndr-raises-126m-to-disrupt-egypts-online-used-car-market); [Global Fleet](https://www.globalfleet.com/en/node/777741). It later raised $15.7m — [WeeTracker](https://weetracker.com/tag/egypt-used-car-marketplace/) (date not read).
- On GitHub, there is no public tooling for looking up Egyptian traffic fines. The only Egypt "traffic violations" repos are computer-vision student projects for plate and violation detection — [Smart-safe-road (Mar 2026)](https://github.com/tasneem123khliel/Smart-safe-road); [Autonomous_Vehicles (Aug 2025)](https://github.com/Mohamed-Rag/Autonomous_Vehicles). This is a weak signal that fines and licence data are not openly accessible.

### Inferences
- **The trust deficit is the core used-car pain, and it can be monetized.**
  - About 750k sales a year means about 1.5m buyer and seller parties a year.
  - About 71% of trades are informal.
  - VC funding (Sylndr) and strategic buying (Dubizzle–Hatla2ee) suggest investors expect payment for listings, inspection, warranties and financing.
  - Openings for a small team:
    - An independent mobile pre-purchase inspection marketplace, earning commission per inspection.
    - A "car passport" or history report built from service records, fines status and licence status, paid per report and also sold to platforms and banks.
    - A paperwork concierge for ownership transfer and power of attorney.
  - All of these depend on access to Ministry of Interior traffic data or on building a crowdsourced service-record database.
- **Licensing and fines are a high-frequency admin burden.** With 11.05m licensed vehicles, if the average vehicle renews every 1–3 years, that is about 3.7–11m renewal events a year. This is an inferred range; actual validity periods were not verified. A "track my fines and licence expiry, then renew for me" service fits the target model well: automatic tracking like the bank-SMS spending app, plus physical delivery like the ID-photo service.
- **Maintenance.** 5.7m private cars plus commercial fleets need regular servicing. Trust in mechanics and spare parts is a classic informal-market problem, but I found no 2024–2026 data this session, so it should be treated as hypothesis.

### Gaps
- Prevalence of odometer rollback, hidden accident history, cars with unpaid instalments or liens, and unpaid fines passed to buyers: no data found. Arabic queries ("عداد مضروب", "فحص السيارات المستعملة") could not be run.
- Inspection centres (prices, capacity) and the inspection products of Sylndr and ContactCars: traction not verified. Sylndr's 2026 status not verified.
- Maintenance: share of counterfeit parts, workshop pricing, and apps for car service or parts with their traction. Not found.
- Licensing renewal: the Digital Egypt portal flow, technical-inspection queues, home delivery of licences. Not verified (digital.gov.eg blocked).
- Traffic fines: online lookup and payment, automated cameras and radars, any 2025–2026 changes to the traffic law. Not verified. **Unverified lead:** fines must be settled before a licence can be renewed.
- Insurance: compulsory third-party vs comprehensive penetration, Financial Regulatory Authority (FRA) motor premiums, insurtech players. Not found.
- App traction (downloads, ratings, reviews) for Hatla2ee, ContactCars, Sylndr and Dubizzle Motors: Google Play blocked.

## 6. Work: unemployment and informality, how jobs are found, scams, freelancers, small employers, CV skills

### Takeaway
Headline unemployment hit a record low of 5.8% in Q2 2026, but the figure hides much:
- **Informality:** about 60% of the employed work informally (18.7m informal workers in Q1 2024).
- **Women:** female unemployment is 14.4%, against 3.4% for men.
- **Cities:** urban unemployment is rising, at 8.8% in Q2 2026 versus 8.4% in Q1.

Hiring channels for blue-collar and entry-level work (Forasna, Wuzzuf, Facebook groups, word of mouth), job scams, small-employer hiring pains and CV/interview demand could not be researched. The freelancer payout and tax details I found come from a low-reliability source.

### Cited Findings
**Unemployment**
- Quarterly rates: Q4 2025 6.2%; Q1 2026 6.0%; Q2 2026 5.8%, a record low — [Ahram Online (Q4 2025)](https://english.ahram.org.eg/NewsContent/1/2/562427/Egypt/Society/Egypt%E2%80%99s-unemployment-rate-falls-to--in-Q--CAPMAS.aspx); [Egypt Today (Q1 2026)](https://egypttoday.com/Article/1/147185/Unemployment-rate-in-Egypt-declines-to-6-in-Q1-2026); [Ahram Online (Q2 2026)](https://english.ahram.org.eg/News/574172.aspx); [Trading Economics](https://tradingeconomics.com/egypt/unemployment-rate/news/575466).
- The labour force rose 1.7% to 35.412m in Q1 2026 — [Zawya](https://www.zawya.com/en/economy/north-africa/egypts-unemployment-rate-down-to-6-in-q1-2026-capmas-saq03z6k).
- Q2 2026 detail: men 3.4%, women 14.4%; urban 8.8%, up from 8.4% in Q1 — [Ahram Online](https://english.ahram.org.eg/News/574172.aspx); [Arab Finance](https://arabfinance.com/en/news/newdetails/egypt-unemployment-rate-in-q2-2026).
- Annual 2025 unemployment was 6.3% — [ME Observer, 30 Apr 2026](https://meobserver.news/economy/2026/04/30/egypt-jobs-unemployment-falls-to-6-3-in-2025-as-labour-force-expands/).

**Informality**
- "Irregular workers compose 60% of employed Egyptians" (CAPMAS).
  - Q1 2024: workforce of 31.1m, 29.2m employed, of whom 18.7m worked in the informal sector.
  - Informal work is concentrated in agriculture, fishing, construction, mining and transport.
  - Formal public-sector employment is declining.
  - Source: [Cairo Governorate news, 2024](https://www.cairo.gov.eg/en/news/news-eng/2024/edd26a9969d44378be5c315c024dc05d).
- Further analysis exists but could not be read: [Ahram Online – "Looking beyond the unemployment rate" (2026)](https://english.ahram.org.eg/News/574869.aspx); [ERF – Assaad & Mahmoud, Egypt Labor Market Panel Survey (ELMPS) 2024 paper](https://erf.org.eg/app/uploads/2024/11/1732788693_150_1127410_assaadmahmoud_elmps2024.pdf).

**Freelancers and remote workers**
- One guide reports:
  - PayPal charges 3.9% + $0.30 per transaction; Payoneer charges a 3% receiving fee and $1.50 per ATM withdrawal.
  - Payoneer is widely used by Egyptian freelancers on Upwork and Fiverr; receiving into PayPal within Egypt is "limited".
  - Freelancers earning above EGP 60,000 a year must register with the Tax Authority, and annual filing is due 31 March.
  - In late 2025 Egypt clarified VAT-free treatment for remote tech-talent exports.
  - Source: [Jobbers.io 2026 guide](https://www.jobbers.io/egypt-freelancers-cairo-tech-hub-complete-registration-guide-2026/).
  - **Low reliability:** the same page says 1 USD ≈ EGP 30.90 in Jan 2026, contradicted by the pound crossing EGP 52/USD by Mar 2026 ([Egyptian Streets](https://egyptianstreets.com/2026/03/10/egypt-raises-fuel-prices-by-egp-3-per-litre/)).
- International payroll firms and fintechs publish guides on paying Egyptian contractors. This signals a meaningful cross-border contractor market: [Deel](https://www.deel.com/blog/how-to-pay-independent-contractors-in-north-africa-and-middle-east/); [Rippling](https://www-j.rippling.com/blog/how-to-pay-contractors-in-egypt); [Omnivoo – "paying Egyptian contractors from a US company"](https://www.omnivoo.com/blog/paying-egyptian-contractors-from-us-company); [Zenind – opening PayPal in Egypt, 2026 guide](https://www.zenind.com/help/post/how-to-open-a-paypal-account-in-egypt-2026-step-by-step-guide-for-individuals-and-businesses).

### Inferences
- **Size of the unemployed and informal pools.** About 2.05m people are unemployed (35.41m × 5.8%; Q2 labour force not verified). Informal workers number about 18–21m (60% of about 30m+ employed). These are the mass markets for job-matching tools: work-history, references and verified-employer tools for informal workers, and entry-level matching for urban youth.
- **Labour-force jump may be methodological.** The Q1 2024 workforce (31.1m) and Q1 2026 labour force (35.4m) differ by 14% in two years. That may reflect a CAPMAS methodology or definition change, so compare trend figures with care.
- **Urban job seekers are a pocket of rising pain.** Rising urban unemployment (8.4% → 8.8%) while the national rate falls suggests this. It is the segment most reachable by app-based products.
- **Women's unemployment is a mass, under-served segment.** At 14.4% (about 4× men's), it links to the mobility safety concerns in section 3 (inferred link). Remote, near-home or safe-commute job matching is a plausible wedge.
- **Freelancer FX demand.** A weaker pound (EGP 52+/USD) makes earning in dollars more attractive. Payout fees of about 3%, PayPal limits and tax-registration confusion point to demand for compliant invoicing, tax filing and FX-payout comparison tools. The size of the freelancer population is unknown.

### Gaps
- Forasna, Wuzzuf and other platforms: user and employer counts, blue-collar share, pricing, 2026 status. Not found.
- How blue-collar jobs are found (word of mouth, Facebook or WhatsApp groups, café "brokers") and their shares: not found. The ELMPS paper could not be read.
- Job scams (upfront "fees", fake overseas jobs, Telegram "task" scams): no data found.
- Small-employer hiring pains (time to hire, staff turnover, verification): not found.
- Demand and prices for CV writing and interview coaching: not found.
- Number of Egyptian freelancers and remote workers, rules on receiving foreign currency (CBE, InstaPay, Payoneer withdrawals), the simplified tax regime for small businesses and freelancers: not verified.
- **Unverified lead:** a new Labour Law reportedly enacted in 2025, which would change contract, termination and social-insurance obligations for small employers. Confirm before use.

## 7. Pain-point scorecard: scale, frequency, money and time cost, workaround, existing solutions, willingness to pay, software opportunity

### Takeaway
On the evidence gathered, five problems each touch millions of people and have a credible software angle:
1. Finding routes and fares on informal transit.
2. Car admin and running costs: fines, licence renewal, fuel.
3. Trust in used-car purchases.
4. Job matching for informal and entry-level workers, including women.
5. Freelancer payouts and tax.

In every case, paying channels look more credible than consumer subscriptions:
- business and government contracts
- data licensing
- commissions
- per-transaction service fees

Willingness-to-pay evidence is thin and mostly indirect.

### Cited Findings
Scale anchors, all cited above:
- Greater Cairo motorized trips: 14.4m a day in 2001, 25% by microbus — [World Bank](https://openknowledge.worldbank.org/entities/publication/8c1c745c-def0-5633-bd52-65ad4e1782fa/full).
- Licensed vehicles: 11.05m (end-2025), Cairo 2.8m — [Banker.news](https://banker.news/134859).
- Private cars: about 5.7m (2025) — [Ken Research](https://www.kenresearch.com/industry-reports/egypt-used-car-market.md).
- Used-car sales: about 750k a year (vintage uncertain) — [TechCrunch summary](https://techcrunch.com/?p=2323007).
- New vehicles sold in 2025: 173.8k — [Enterprise](https://enterpriseam.com/egypt/2026/02/05/auto-sales-were-up-69-9-in-2025-but-imports-outpaced-locally-assembled-vehicles-at-an-increased-rate/).
- 92-octane: EGP 17.25 → 22.25 (Oct 2025 → Mar 2026) — [Egyptian Streets](https://egyptianstreets.com/2026/03/10/egypt-raises-fuel-prices-by-egp-3-per-litre/).
- Labour force 35.4m; unemployment 5.8%; female unemployment 14.4% — [Zawya](https://www.zawya.com/en/economy/north-africa/egypts-unemployment-rate-down-to-6-in-q1-2026-capmas-saq03z6k); [Ahram Online](https://english.ahram.org.eg/News/574172.aspx).
- Informal workers: 18.7m (Q1 2024) — [Cairo Governorate](https://www.cairo.gov.eg/en/news/news-eng/2024/edd26a9969d44378be5c315c024dc05d).
- Willingness-to-pay and investment signals:
  - Overprice of EGP 20–40k paid on some 2026 models — [AboutMsr](https://aboutmsr.com/سيارات-تعود-إلى-الأوفر-برايس-رغم-هبوط/).
  - Sylndr's $12.6m (2022) and $15.7m rounds — [The National](https://thenational-the-national-prod.cdn.arcpublishing.com/business/2022/05/23/sylndr-raises-126m-to-disrupt-egypts-online-used-car-market); [WeeTracker](https://weetracker.com/tag/egypt-used-car-marketplace/).
  - Dubizzle's acquisition of Hatla2ee (Feb 2025) — [CB Insights](https://www.cbinsights.com/company/hatla2eecom).
  - Swvl's $13m raise and pivot to enterprises and governments — [Wamda](https://www.wamda.com/2026/08/swvl-secures-13-million-investment-led-sawiris-backed-coefficient).
  - About 3% payout fees accepted by freelancers (low reliability) — [Jobbers.io](https://www.jobbers.io/egypt-freelancers-cairo-tech-hub-complete-registration-guide-2026/).

### Inferences
Each profile below is a synthesis. Estimates are labelled inferred.

**P1. Finding routes and fares on microbus and informal transit** (Greater Cairo first; Alexandria and secondary cities have even less data)
- **Scale:** about 3.6m microbus trips a day in Greater Cairo in 2001; today likely several million riders a day (inferred).
- **Frequency:** daily for commuters, and acute for trips outside the usual routine, for newcomers and students, and after network or fare changes. Three fare rounds are documented (Jul 2024, Apr 2025, Oct 2025). A fourth after the Mar 2026 fuel hike is inferred.
- **Cost:**
  - Time lost asking, waiting and taking wrong vehicles.
  - Overcharging risk.
  - Not quantified (gap).
- **Workaround:**
  - Asking drivers, conductors and other passengers.
  - Habit and word of mouth.
  - TfC's printed maps.
- **Existing solutions and weaknesses:**
  - TfC: maps and consulting for government and development partners; its open GTFS data dates from 2017.
  - Three 2025–26 hobby apps with no traction.
  - Google Maps coverage of microbuses unverified.
- **Willingness to pay:** weak for consumers (inferred). Institutional demand is shown by TfC's funded portfolio.
- **Opportunity:** an Egyptian-Arabic, voice- or WhatsApp-first "أروح إزاي؟" ("how do I get there?") assistant that combines formal and informal legs, with crowdsourced fare and route updates. Possible revenue:
  - hyper-local ads
  - passenger-information contracts with governorates and transit operators
  - data licensing to delivery, logistics and map companies
  - employer commuter-benefit packages
- **Risk:** the cost of keeping data current, and limited consumer willingness to pay.

**P2. Getting started on new transit (monorail, BRT, metro extensions, 2027 West Nile monorail)**
- **Scale:** the monorail targets 500–600k riders a day (actual loads very low in May 2026). The BRT has 14 stations and 100 buses.
- **Workaround:** asking around and sticking with familiar microbuses (inferred).
- **Opportunity:**
  - Station-access and feeder-route guidance plus fare calculators.
  - Contracts with operators and the ministry.
  - Employer shuttles and commuter plans for workers in new cities (Swvl-style enterprise demand).

**P3. Car admin: fines, licence renewal, technical inspection, ownership transfer**
- **Scale:** 11.05m vehicles; about 3.7–11m renewal events a year (inferred range).
- **Workaround:** queues and middlemen; inferred and unverified this session.
- **Existing solutions:** government portals (unverified); no public API (weak GitHub signal).
- **Opportunity:**
  - Fines and licence-expiry tracking with alerts.
  - Paid renewal concierge with doorstep pickup and delivery.
  - Fleet subscriptions for taxi, microbus and company fleets.
  - Referral income from insurers and workshops.
- **Key risk:** access to Ministry of Interior data.

**P4. Running costs (fuel, maintenance)**
- **Scale:** about 5.7m private cars, plus taxi, ride-hailing and microbus drivers.
- **Cost:** fuel up 29% in about 5 months; illustratively about EGP 400 a month more for 1,000 km a month.
- **Opportunity:**
  - A car-expense tracker (fuel and service logged from SMS, receipts or photos), modelled on the bank-SMS spending app.
  - Maintenance reminders and price benchmarks.
  - Revenue from workshop and parts commissions, insurance referrals and fleet subscriptions.

**P5. Trust in used-car purchases**
- **Scale:** about 750k sales a year, about 1.5m parties; about 71% informal.
- **Existing solutions:** Hatla2ee (Dubizzle), ContactCars, Dubizzle and Sylndr (managed sales with financing).
- **Gaps in existing solutions:** independent inspection and vehicle-history checks at scale (inferred).
- **Opportunity:** mobile inspection marketplace, history reports, escrow and paperwork concierge. Charge buyers per inspection or report, and sell to platforms and lenders.

**P6. New-car price opacity and overprice**
- **Scale:** 173.8k new vehicles in 2025; overprice of EGP 20–40k on some models.
- **Opportunity:** price tracker, dealer-quote comparison and delivery-time transparency. Revenue from dealer and bank lead generation.

**P7. Informal and entry-level job matching, scams, women's employment**
- **Scale:** 18.7m informal workers, about 2m unemployed, female unemployment 14.4%.
- **Workaround:** word of mouth and social media groups; inferred, not verified this session.
- **Opportunity:**
  - WhatsApp- or voice-first job matching with employer verification, to fight scams.
  - Employers pay per post or per hire.
  - Small-business "hire in 48 hours" packages.
  - Arabic AI CV and interview coaching, paid per use.
- Willingness to pay is unverified.

**P8. Freelancer payouts, FX and tax**
- **Scale:** unknown.
- **Cost:** about 3% in fees (low reliability).
- **Opportunity:** invoicing, tax registration and filing, and payout-route comparison, sold by subscription, plus referral fees from banks and fintechs.

### Gaps
- Direct willingness-to-pay data was not found for any segment: prices paid to middlemen, inspection fees, CV services, app subscriptions.
- App-store traction for incumbents was not available.
- Revenue benchmarks for comparable Egyptian apps were not found.

## Latent and predicted pain points

### Takeaway
Beyond the documented problems, the strongest **latent** pains are everyday frictions people treat as normal:
- asking strangers which microbus to take, and arguing about fares and change
- paying middlemen for car paperwork
- discovering fines only when renewing a licence
- buying used cars on blind trust
- finding work through personal networks

Recent changes will create **new** pains:
- 92-octane fuel up 29% in about 5 months
- new BRT and monorail lines, with a second monorail line due in 2027
- a weaker pound (EGP 52+/USD)
- urban unemployment rising while the national rate falls

Most items below are labelled **inferred**. Their reach estimates rest on the cited anchors in sections 1–7.

### Cited Findings
Evidence base for the items below; details and sources are in earlier sections:
- About 3.6m microbus trips a day in Greater Cairo in 2001 (25% of 14.4m) — [World Bank](https://openknowledge.worldbank.org/entities/publication/8c1c745c-def0-5633-bd52-65ad4e1782fa/full).
- The main open paratransit data dates from 2017 — [TfC GitHub](https://github.com/transportforcairo/Transit---GCR-Digital-Cairo-2017-). Hobby microbus-routing projects appeared Nov 2025–Aug 2026 — [Aroh-Ezay](https://github.com/AhmedHesham202/Aroh-Ezay-App); [d-nerve](https://github.com/d-nerve-cairo/d-nerve-backend); [cairo-bus-map](https://github.com/Miqell24/cairo-bus-map).
- Fare rounds of 10–15% after fuel hikes — [Masrawy](https://www.masrawy.com/news/news_regions/details/2025/4/11/2768913). A feature titled "ask before you ride" — [Parlmany](https://www.parlmany.com/News/7/136629/أجرة-مواصلات-مصر-اسأل-قبل-ما-تركب).
- 92-octane at EGP 22.25 (10 Mar 2026), up from 17.25 before Oct 2025; pound past 52/USD — [Egyptian Streets](https://egyptianstreets.com/2026/03/10/egypt-raises-fuel-prices-by-egp-3-per-litre/).
- Monorail loads of 30–50 per four-car train against a 500–600k/day target; West Nile line (Giza–6th of October) due "next year" — [Malay Mail/AFP](https://www.malaymail.com/amp/news/life/2026/05/28/cairos-new-monorail-glides-above-a-city-struggling-below/221568).
- ENR booking limited to 15 days ahead and 4 tickets a day, with agents, a voice line and city offices as channels — [Al Bawaba News](https://www.albawabhnews.com/4857016).
- Controversy over violence against women by Uber drivers — [Egyptian Streets](https://egyptianstreets.com/?p=91310).
- 11.05m licensed vehicles — [Banker.news](https://banker.news/134859). About 750k used-car sales a year and about 71% informal trading — [TechCrunch summary](https://techcrunch.com/?p=2323007); [Ken Research](https://www.kenresearch.com/industry-reports/egypt-used-car-market.md).
- Overprice returning on 2026 models — [AboutMsr](https://aboutmsr.com/سيارات-تعود-إلى-الأوفر-برايس-رغم-هبوط/).
- 18.7m informal workers — [Cairo Governorate](https://www.cairo.gov.eg/en/news/news-eng/2024/edd26a9969d44378be5c315c024dc05d). Female unemployment 14.4%; urban unemployment 8.8%, up from 8.4% — [Ahram Online](https://english.ahram.org.eg/News/574172.aspx).

### Inferences
Each item gives a label, the reasoning and evidence, and a rough reach estimate.

**Mobility**

**L1. "Which microbus, from where, and how much?"**
- **Label:** documented problem; the coping behaviour is inferred.
- **Reasoning:**
  - Without signs, timetables or current data, riders rely on asking drivers, conductors and other passengers. That is normal for regulars but costly for newcomers, students, job seekers travelling to interviews, people who moved to new cities, and anyone on a trip outside their routine.
  - TfC's whole origin, a 2017 dataset that is still the main open source, and a cluster of 2025–26 prototype apps all point to an unmet information need.
- **Reach:** several million riders a day in Greater Cairo (2001 baseline: 3.6m microbus trips a day). Alexandria and other governorates have even less data (Port Said's only GTFS is a Dec 2025 hobby repo).
- **Frequency:** acute weekly for many people, and spiking after each fuel or fare round and each network change.

**L2. Fare confusion and disputes after each fuel round**
- **Label:** fare changes are documented; disputes, rounding up and arguments over small change ("الفكة") are inferred.
- **Reasoning:**
  - Each fuel round triggers governorate-by-governorate fare tables with rises of 10–15%.
  - Riders rarely see the official table, so drivers' rounding and line-by-line differences go unchecked.
  - "Ask before you ride" coverage shows fares are not transparent.
- **Reach:** all microbus and "service" riders nationwide, so millions a day.
- **Frequency:** three documented fare rounds (Jul 2024, Apr 2025, Oct 2025) plus a Mar 2026 fuel hike that presumably triggered a fourth. That is about one round every 5–7 months, and the weeks of confusion after each are inferred.

**L3. Getting to and from the new transit lines**
- **Label:** low ridership is documented; the causes are inferred.
- **Reasoning:**
  - Monorail and BRT stations sit on highways and ring roads.
  - Without feeder information, safe walking access or integrated fares, people stay on microbuses.
  - Early monorail loads are a tiny fraction of the target.
- **Reach:** the corridor users the target implies, hundreds of thousands a day once the network is complete. In 2027 this becomes a new pain for Giza, 6th of October and Sheikh Zayed commuters when the West Nile line opens (predicted).

**L4. Re-learning commutes after moving to new cities and new administrative districts**
- **Label:** inferred and predicted.
- **Reasoning:**
  - Housing and government jobs are shifting to new cities (New Cairo, 6th of October, the New Administrative Capital).
  - Commuters face long trips on corridors where informal routes are still forming, so no reliable map exists.
  - Employers may run staff buses, which is the opening Swvl pivoted toward.
  - The scale of the government-employee move to the New Administrative Capital was **not verified** this session.
- **Reach:** likely hundreds of thousands of commuters (unverified).

**L5. Many tickets and cash for one journey**
- **Label:** inferred.
- **Reasoning:**
  - A multimodal trip, such as microbus → metro → monorail or BRT, appears to need separate payment media plus cash for microbuses.
  - I found no evidence of a unified card or app.
  - The hidden cost is time spent at ticket windows and the need to carry exact change.
- **Reach:** multimodal commuters in Greater Cairo, likely in the millions. This needs checking.

**L6. Ride-hailing price volatility and bargaining fatigue**
- **Label:** inferred.
- **Reasoning:**
  - The bid model (inDrive leads downloads) pushes negotiation onto riders.
  - Fuel up 29% in about 5 months pushes drivers to counter-bid, cancel or ask for off-app cash.
  - Riders absorb uncertainty about both price and arrival time.
- **Reach:** ride-hailing users in big cities, likely millions. User counts were not verified.

**L7. Women's commute safety as a hidden tax on mobility and work**
- **Label:** safety concerns are documented; the effects on employment are inferred.
- **Reasoning:**
  - Women choose ride-hailing to avoid harassment, then faced driver-violence scandals.
  - Safety costs time and money, through pricier modes and avoided routes or hours.
  - It likely narrows the set of jobs women can take, consistent with female unemployment of 14.4% vs 3.4% for men.
- **Reach:** millions of women commuters, plus female job seekers (female unemployment 14.4%).

**L8. Holiday train-ticket crunch and dependence on agents**
- **Label:** booking rules and channels are documented; the peak crunch and resale are inferred.
- **Reasoning:**
  - A 15-day window, a 4-tickets-a-day cap, and peak demand around Eid concentrate booking stress.
  - Assisted channels (agents, the 1661 line, city offices) show many people need help.
  - Families travelling together hit the 4-ticket cap.
- **Reach:** millions of trips at each Eid peak (no figure verified).

**Cars**

**L9. Fines discovered only at renewal, and fines passed to used-car buyers**
- **Label:** inferred. The rule that fines must be cleared before renewal is an unverified lead.
- **Reasoning:**
  - Without proactive alerts, owners discover accumulated fines when they renew.
  - Buyers of used cars may inherit liabilities.
  - Wider automated enforcement (cameras and radars; roll-out not verified) would make surprise fines more frequent.
- **Reach:** up to 11.05m vehicles' owners. The problem recurs at every renewal and every used-car sale (about 750k a year).

**L10. The renewal and inspection runaround, and paying a middleman ("معقّب")**
- **Label:** inferred.
- **Reasoning:**
  - Licensing involves inspection, fee and fine settlement, and paperwork.
  - The common workaround of paying someone to "finish it" signals both pain and willingness to pay.
  - This mirrors the ID-photo-with-delivery model.
- **Reach:** about 3.7–11m renewal events a year (inferred range), plus driving-licence renewals.

**L11. Buying a used car on blind trust**
- **Label:** inferred. Fraud prevalence was not measured.
- **Reasoning:**
  - About 71% informal trading means most buyers have no warranty, history or independent inspection.
  - The workaround is bringing a mechanic friend or buying through relatives.
  - The fact that organized players sell inspection, warranties and financing implies the gap exists.
- **Reach:** about 1.5m buyer and seller parties a year.

**L12. Running-cost squeeze and "should I still drive?" decisions**
- **Label:** the price shock is documented; behavioural responses are inferred.
- **Reasoning:**
  - 92-octane went from EGP 17.25 to 22.25 in about 5 months.
  - Car owners have no easy way to see cost per km or per trip, or to compare driving with transit, carpooling or CNG.
  - Drivers of taxis, ride-hailing cars and microbuses see their margins compressed.
- **Reach:** about 5.7m private-car owners, plus hundreds of thousands of commercial drivers (count not verified).

**L13. Not knowing a fair car price in a weak-pound market**
- **Label:** overprice is documented; the information gap is inferred.
- **Reasoning:**
  - List prices move with FX (EGP 52+/USD), and overprice reappears on popular models.
  - Buyers and sellers of used cars benchmark against shifting new-car prices.
  - Many over- or under-price as a result.
- **Reach:** about 170–250k new-car buyers and about 750k used-car transactions a year.

**L14. Trusting mechanics and spare parts**
- **Label:** inferred, with no data found this session.
- **Reasoning:**
  - Without price benchmarks or a way to verify parts, owners rely on one "trusted" mechanic or on brand-owner Facebook groups.
  - Switching costs are high and overcharging is invisible.
- **Reach:** about 5.7m private cars plus commercial fleets.

**Work**

**L15. Finding informal work through networks, with no portable track record**
- **Label:** inferred.
- **Reasoning:**
  - 18.7m informal workers have no contracts, so they rely on referrals and brokers.
  - They cannot show verified experience or references.
  - Employers cannot verify workers either, which feeds scams in both directions.
- **Reach:** about 18–21m informal workers, plus small employers.

**L16. Commute cost and time shrinking the job-search radius**
- **Label:** inferred.
- **Reasoning:**
  - Repeated 10–15% fare rounds and long commutes from new cities raise the effective cost of distant jobs.
  - Rising urban unemployment (8.4% → 8.8%) alongside falling national unemployment is consistent with city job seekers facing frictions.
  - Hyper-local job matching that shows commute time and cost could reduce failed hires.
- **Reach:** about 2m unemployed plus low-wage workers.

**L17. Entry-level candidates who can't present themselves**
- **Label:** inferred; demand for CV and interview help was not verified.
- **Reasoning:**
  - Urban youth and graduate unemployment pockets, together with formal employers screening digitally, suggest gaps in CVs and interview skills.
  - Consumer willingness to pay is unknown.
- **Reach:** hundreds of thousands of entry-level job seekers a year (unverified).

**L18. Freelancers' FX, payout and tax uncertainty**
- **Label:** partly documented, from a low-reliability source; mostly inferred.
- **Reasoning:**
  - The pound past 52/USD increases the incentive to earn in dollars.
  - Payout routes cost about 3%, PayPal receiving is limited, and tax-registration rules and thresholds are confusing.
  - Freelancers likely under-register or overpay.
- **Reach:** unknown; the number of freelancers is a gap.

**L19. New labour rules creating compliance confusion for small employers and workers (predicted)**
- **Label:** inferred. The law's existence and contents were **not verified**.
- **Reasoning:** if a 2025 Labour Law is in force, small employers will need contract and termination templates and social-insurance compliance help, and workers will need to understand their rights.
- **Reach:** potentially millions of small-business workers, if confirmed.

### Gaps
- None of the inferred items could be checked against complaint data (Reddit r/Egypt and r/cairo, Google Play reviews, Facebook groups) because fetching was blocked and search was exhausted.
- Ordered by importance for validation, the reach estimates that most need checking are:
  1. Current microbus ridership and an up-to-date modal split.
  2. Licence validity periods and annual renewal volumes.
  3. Prevalence of used-car fraud.
  4. Ride-hailing user counts.
  5. Number of freelancers.
  6. Scale of the New Administrative Capital relocation.
  7. Status of the 2025 Labour Law.
  8. Rollout of automated traffic enforcement.
