# Financial Transparency and Access Data for 25 Leading DMV Youth Soccer Clubs: What Is Public, Where, and What Is Missing

_Research reflects 2025–26 season information. Structured data: [`data/dmv-clubs.csv`](../data/dmv-clubs.csv) and [`data/dmv-club-990s.csv`](../data/dmv-club-990s.csv)._

Nonprofit status is the best single predictor of financial transparency among the DMV's elite youth soccer clubs. Fourteen of the 25 clubs selected here have a current IRS Form 990 on ProPublica Nonprofit Explorer, with revenue, expense and named executive-pay data, while the for-profit, pro-affiliated and alliance-branded programs (D.C. United Academy, DC Power FC, The St. James FC, VA Revolution/Loudoun United, Achilles FC, Northern Virginia Alliance, Virginia Development Academy, Fairfax Virginia Union) publish little or no entity-level financial data. Fee schedules and financial-aid policies are common. Aid outcomes (how many players get aid, and how much) are rare: only Alexandria Soccer Association and DC Soccer Club (Stoddert) publish aid dollar totals, and no club publishes the share of elite-tier players on aid.

## TL;DR
- **990s are good for 14 clubs; for-profit and alliance programs are largely opaque.** ProPublica shows current (FY2024–FY2025) 990s for the big community nonprofits: Arlington ($10.89M revenue), Loudoun ($7.84M), Alexandria ($7.29M), Bethesda ($6.56M), SYC ($5.23M), Stoddert/DC Soccer Club ($4.87M) and others. At the three clubs where the split was extracted (Arlington, Bethesda, McLean), 88.8–90.7% of revenue is program-service fees, so fees drive the budget and donations are marginal (5.0–7.5%).
- **Fee schedules and aid policies are usually public, but aid outcomes are not.** Arlington publishes a tiered fee and aid grid (club fees of $2,050–$3,000, maximum aid 60%). Loudoun publishes a $65,000 family-income cutoff. SYC and VDA publish percentage or case-by-case rules. Only Alexandria and DC Soccer Club ($250,000–$350,000 per year) publish aid totals, and neither breaks them out for elite teams. Alexandria's Spring2ACTion page says "Last year ASA supported over 2,000 participants with $715,000 in financial aid support," but its other published figures differ.
- **A database is feasible but needs three layers of data.** 990 data is machine-readable and cheap to collect. Fee and aid data has to be scraped from club websites each season and is often incomplete (uniforms, travel and team fees are excluded). Data on for-profits and alliances needs state registry lookups plus direct outreach. Expect about 60–65% coverage from public sources alone.

## How the 25 Clubs Were Selected

**Definition used:** A club qualifies if it is a DMV-based club (DC, Montgomery, Prince George's, Anne Arundel and Frederick counties in MD, and Northern Virginia) that meets at least one of these tests:
- holds a top-tier national platform membership in 2025–26 (MLS NEXT Homegrown/Academy/MLS NEXT 2, ECNL/ECNL Boys, Girls Academy, USL Academy/USL Youth);
- is a founding or operating parent of such a program;
- is among the region's largest community clubs by 990 revenue;
- is a DC-based pro-affiliated youth pathway.

Membership was drawn from league and club announcements, SoccerWire club pages, ClubScout guides and the MLS NEXT membership list. GotSport/PitchRank rankings were not systematically pulled, so this is a **tier-and-size** definition, not a ranking-based one. Alliances such as NVA and VDA are listed separately from their parent clubs because families pay the alliance program, but money flows through the parents' 990s.

| # | Club | Jurisdiction | Why included |
|---|---|---|---|
| 1 | D.C. United Academy | DC / Leesburg, VA | MLS club academy (MLS NEXT) |
| 2 | DC Power FC (academy contracts) | DC | USL Super League pro club signing DMV youth to academy contracts |
| 3 | DC Soccer Club (Stoddert Soccer League) | DC | Largest DC nonprofit; ECNL RL (does not offer MLS NEXT) |
| 4 | Arlington Soccer Association | Arlington, VA | ECNL Boys/Girls, MLS NEXT; largest revenue in set |
| 5 | McLean Youth Soccer | McLean, VA | MLS NEXT, Girls Academy |
| 6 | Alexandria Soccer Association | Alexandria, VA | MLS NEXT; large community club |
| 7 | Loudoun Soccer (Loudoun Youth Soccer Assn.) | Leesburg, VA | MLS NEXT 2, Girls Academy; NVA partner |
| 8 | Northern Virginia Alliance (NVA) | Loudoun/Fairfax, VA | ECNL, MLS NEXT, Girls Academy alliance |
| 9 | Great Falls Reston SC | Great Falls, VA | NVA founding partner |
| 10 | Virginia Development Academy (VDA) | Woodbridge, VA | ECNL Boys/Girls, USL Youth |
| 11 | Prince William Soccer Inc. | Woodbridge, VA | VDA founding partner |
| 12 | Fairfax Virginia Union (successor to Fairfax BRAVE) | Fairfax, VA | ECNL national club |
| 13 | Braddock Road Youth Club | Springfield, VA | FVU/BRAVE founding partner |
| 14 | Vienna Youth Soccer | Vienna, VA | FVU/BRAVE founding partner |
| 15 | Lee Mount Vernon Sports Club | Alexandria/Fairfax, VA | FVU partner |
| 16 | Springfield/South County Youth Club (SYC) | Springfield, VA | Girls Academy, GA Aspire; MLS NEXT 2 listing |
| 17 | The St. James FC | Springfield, VA / Bethesda, MD | MLS NEXT; for-profit sports complex operator |
| 18 | VA Revolution / Loudoun United FC | Leesburg, VA | MLS NEXT, Girls Academy; merged with USL Championship club |
| 19 | Bethesda Soccer Club | Bethesda/N. Potomac, MD | MLS NEXT, ECNL |
| 20 | Achilles FC (+ Achilles FC Foundation) | Silver Spring, MD | MLS NEXT charter club |
| 21 | Montgomery Soccer Inc. (Maryland Rush Montgomery) | Derwood, MD | Large Montgomery County club |
| 22 | Maryland United FC | Bowie/Annapolis, MD | USL Youth; large PG/Anne Arundel club |
| 23 | FC Frederick | Frederick, MD | Large Frederick County club |
| 24 | Virginia Valor FC | Chantilly, VA | NVA and FVU partner |
| 25 | Liverpool FC IA Maryland | Rockville, MD | National Academy League; international-brand academy |

## Summary Table

"990?" means a 990 was located on ProPublica. "Fee public?" and "Aid public?" mean a schedule or policy was found on the club's own site during this research.

| Club | Entity type / tax status | 990 available? (latest FY: revenue) | Fee schedule public? | Financial-aid info public? | Other disclosures |
|---|---|---|---|---|---|
| D.C. United Academy | Division of D.C. United (private MLS club; entity not verified) | No (for-profit) | N/A: academy stated to be fully club-funded | N/A | Pathway-to-Pro partnerships with local clubs |
| DC Power FC | Private pro club (entity not verified) | No | No youth fees (academy contracts) | N/A | Press releases on academy signings |
| DC Soccer Club / Stoddert | 501(c)(3), EIN 52-1340436 | Yes (FY Jul 2025: $4.87M) | Partial (not verified) | Yes: $250k–$350k per year awarded | Aid committee independent of coaches |
| Arlington Soccer Assn. | 501(c)(3), EIN 23-7284150 | Yes (FY Jun 2025: $10.89M) | Yes (fee grid; 2023–24 amounts) | Yes: detailed FPL-tiered policy, 60% cap | Arlington Community Foundation listing; donations page |
| McLean Youth Soccer | 501(c)(3), EIN 80-0015698 | Yes (FY Jun 2025: $3.58M) | Not verified | Not verified | Candid profile |
| Alexandria Soccer Assn. | 501(c)(3), EIN 54-0902413 | Yes (FY Jun 2025: $7.29M) | Partial (all-inclusive tuition; amounts not verified) | Yes: over $715k to 2,000+ participants | "Where Does All the Money Go?" budget explainer; financial info link; conflict-of-interest form |
| Loudoun Soccer | 501(c)(3), EIN 54-1076172 | Yes (FY May 2025: $7.84M) | Yes (2025–26 Travel Financial Policy PDF; 2026/27 fees) | Yes: $65,000 income threshold | Refund policy |
| Northern Virginia Alliance | Alliance program; own EIN not found | No (a similarly named Arlington league filer is likely unrelated) | Not verified | "Available" statement only | Affiliate agreement (RBFC GA Aspire) |
| Great Falls Reston SC | 501(c)(3), EIN 51-0226159 | Yes (FY Dec 2024: $2.77M) | Not verified | Not verified | — |
| VDA | Alliance of PWSI + Virginia Soccer Assn.; own EIN not found | No | Yes (fee structure plus 2025–26 fee table) | Yes: case-by-case, after $400 initial fee | Financial Policy PDF |
| Prince William Soccer Inc. | 501(c)(3), EIN 54-1101179 | Yes (FY Jun 2025: $4.64M) | Not verified | Not verified | — |
| Fairfax VA Union / BRAVE | Six-club alliance; own EIN not found | No | Yes (fee structure page) | Yes (program page) | Governance statement (equal shares) |
| Braddock Road YC | 501(c)(3), EIN 54-1015722 | Yes (FY Dec 2024: $3.14M) | Not verified | Not verified | Schedule L related-party transactions reported |
| Vienna Youth Soccer | 501(c)(3), EIN 54-1004923 | Yes (FY Jun 2025: $3.87M) | Not verified | Not verified | — |
| Lee Mount Vernon SC | Nonprofit (990 not checked) | Not checked | Yes (deposit and payment plan) | Yes: reduced $150 deposit; no cap on scholarships | Sibling discount |
| SYC | 501(c)(3), EIN 54-0938972 | Yes (FY Jun 2025: $5.23M) | Not verified | Yes: 30% travel scholarship; Fairfax County scholarship link | Written confidentiality procedure |
| The St. James FC | For-profit (owned by The St. James complex; entity not verified) | No | Not found | Not found (the school's aid is separate) | Chelsea FC partnership marketing |
| VA Revolution / Loudoun United | Merged with privately owned USL club; legacy 501(c)(3) EIN 84-2902851 is stale | Stale (FY2022: $16,967, 990-EZ) | Partial (RSA school tuition $19,500) | Limited ("quite limited" for the RSA school) | Merger announcements |
| Bethesda SC | 501(c)(3), EIN 52-1223186 | Yes (FY Aug 2025: $6.56M) | Not verified | Yes: policy, but no totals | Scholarship fund sources disclosed |
| Achilles FC | Club entity not verified; Foundation described as 501(c)(3) (2018) | Foundation not found on ProPublica | Not found | Stated (Foundation scholarships) | — |
| Montgomery Soccer Inc. | 501(c)(3), EIN 23-7327918 | Yes (FY Dec 2024: $4.49M) | Not verified | Not verified | Legacy "Maryland Rush Montgomery" EIN also exists |
| Maryland United FC | 501(c)(3), EIN 83-0574699 | Yes (FY Dec 2024: $3.59M) | Not verified | Not verified | 990 reports no paid officers |
| FC Frederick | 501(c)(3), EIN 61-1441486 | Yes (FY Jun 2025: $3.31M) | Not verified | Not verified | $1.09M contributions in 990 |
| Virginia Valor FC | Not verified | Not checked | Not verified | Not verified | — |
| LFC IA Maryland | Not verified (likely licensed private operator) | Not checked | Not verified | Not verified | — |

## Key Findings

### 1. Form 990 data: strong for community nonprofits, and it shows fee-dependence
The largest DMV clubs are multi-million-dollar organizations whose budgets rest almost entirely on family fees:

| Club (FY) | Revenue | Expenses | Program-service (fee) share | Contributions | Top reported compensation |
|---|---|---|---|---|---|
| Arlington (Jun 2025) | $10,890,449 | $10,551,382 | 89.7% | $815,301 (7.5%) | Mohamed Tayari, Dir. of Coaching, $177,557; ED Frank DeMarco $172,500 |
| Loudoun (May 2025) | $7,842,651 | $8,940,229 | not extracted | not extracted | Mark Ryan, CEO, $237,993 |
| Alexandria (Jun 2025) | $7,286,737 | $6,560,658 | not extracted | not extracted | Thomas Park, ED, $374,075 + $18,949 other |
| Bethesda (Aug 2025) | $6,564,798 | $6,928,501 | 88.8% | $327,987 (5.0%) | Jonathon Colton, ED, $207,262 |
| SYC (Jun 2025) | $5,229,193 | $4,884,054 | not extracted | not extracted | Dorothy Talbott, GM, $183,243 + $17,814 |
| Stoddert/DC Soccer Club (Jul 2025) | $4,870,669 | $4,858,366 | not extracted | not extracted | Gregory Andrulis, ED, $170,000 + $5,400 |
| Prince William Soccer (Jun 2025) | $4,641,062 | $4,155,749 | — | — | Quan Phan, ED, $112,997 |
| Montgomery Soccer (Dec 2024) | $4,488,877 | $6,806,926 | — | — | Gus Delgado, ED, $205,000 |
| Vienna Youth Soccer (Jun 2025) | $3,868,248 | $3,861,343 | — | — | Kevin James, ED, $177,528 |
| Maryland United FC (Dec 2024) | $3,591,749 | $3,609,607 | — | — | No paid officers listed; $1,573,869 other salaries |
| McLean (Jun 2025) | $3,579,252 | $3,656,978 | 90.7% | $234,975 (6.6%) | Louise Waxler, ED, $181,628 + $24,967 |
| FC Frederick (Jun 2025) | $3,311,564 | $1,797,648 | — | $1,094,808 | Robert Eskay, ED/VP, $128,640 |
| Braddock Road YC (Dec 2024) | $3,139,608 | $2,558,416 | — | — | Michelle Dolansky, VP, $18,000 |
| Great Falls Reston (Dec 2024) | $2,774,491 | $2,870,625 | — | — | Richard Shelton, ED, $140,000 |

What this means for equity work:
- **Fee dependence.** Where it was extracted, 88.8–90.7% of revenue comes from program fees and only 5–7.5% from contributions. Aid is therefore mostly cross-subsidized by paying families or capped by small donation pools, not funded by an endowment or public money. This structural fact explains why aid is rationed.
- **Deficits and reserves.** Several clubs ran deficits in the latest year: Loudoun by about $1.1M, Montgomery Soccer by about $2.3M, Bethesda by $363,703, McLean by $77,726. McLean holds $4.24M in net assets against a $3.66M expense base, while Bethesda holds $1.17M. Reserve depth matters for whether aid can expand. The 990 alone does not explain large one-year deficits (capital projects, facility leases or timing are all possible), so Schedules D and O should be read before drawing conclusions.
- **Compensation outliers.** Alexandria's ED pay of $374,075 is notably higher than peers ($170,000–$238,000 for top executives at clubs of similar or larger size). McLean's key-person compensation is 11.2% of expenses, against 1.6% at Arlington and 3.0% at Bethesda. These are legitimate governance data points, but role definitions differ (some clubs list coaching directors as key employees).
- **Anomalies to verify.** Maryland United FC reports no compensated officers despite $1.57M in salaries. Braddock Road reports Schedule L (related-party) transactions. Both are worth reading in the full filing.

### 2. Fee schedules: widely posted, but "total cost of play" is systematically understated
- **Arlington** publishes the most useful grid. Its 2023–24 financial-aid page lists club fees of $2,210 (U9–U12 travel), $2,050–$2,450 (U13–U19 travel tiers) and $3,000 (Academy/ECNL), plus team fees of $300–$800 collected on top. It also estimates out-of-pocket costs for cleats ($50–$200), warm-ups ($100) and backpacks ($70), and states fees exclude gas, hotels and meals. The current 2025–26 page describes the structure: a $300 non-refundable deposit, a 7-month payment plan, and a non-resident "pass-through" fee. Dollar amounts could not be extracted from that page, so the 2023–24 figures should be treated as dated.
- **VDA** itemizes what its Club, Field and Team fees cover and publishes a 2025–26 ECNL fee table. The table's amounts could not be extracted in this research. VDA explicitly warns of costs outside club fees: uniforms "Generally $400–$500," family travel, and separately billed ECNL playoff costs.
- **Loudoun** publishes a Travel Financial Policy PDF and 2026/27 fees, and markets "no hidden fees." Even so, it separates Club fees from Team fees (paid directly to the team for tournaments, coach travel and extra training) and a required uniform kit.
- **Fairfax Virginia Union** and **Lee Mount Vernon** publish fee structures: FVU prorates 25% for mid-year joiners, and LMVSC charges a $250 deposit (or $150 for aid applicants) and offers an 8-month plan and a 10% sibling discount.
- **Alexandria** says its Academy tuition is all-inclusive (coaching, league, tournaments, referees, field permits), with an $80–$90 Capelli uniform lasting about two years. This is a rare low-uniform-cost data point. The tuition amounts themselves were not verified.
- **For-profits and pro-affiliated programs** publish the least about their club teams. VA Revolution's residency school (RSA) lists $19,500 per year in tuition, with club soccer billed separately. No St. James FC team fee schedule was found.

**Implication:** No club publishes a true all-in annual cost that includes team fees, uniforms, tournament travel and lodging. A database that captures only "club fee" will understate the cost of elite play, probably substantially for teams that travel nationally, though this could not be quantified from public sources.

### 3. Financial aid: policies are public, outcomes almost never are
| Club | Published rule | Published outcome |
|---|---|---|
| Arlington | Tiered by federal poverty level: 1st priority at ≤130% FPL, then 185%, 250%, 300%; max award 60% of club fee; team fees and optional items not covered | None. The club says that "Many years, this is the only group receiving financial aid" (≤130% FPL) "given the volume of requests" |
| Loudoun | 2025–26 threshold of $65,000 gross family income (hardship considered); elite GA aid "for players identified who demonstrate talent, commitment, and need"; rec aid excludes add-on training | None |
| SYC | Travel scholarship "standard" 30% of club fees (deposit excluded); county-scholarship recipients pay 30% of the travel fee. These two statements conflict (30% off vs. paying 30%); uniform and team fees are excluded | None |
| VDA | Case-by-case; considered only after a $400 initial fee is paid | None |
| Bethesda | Limited, need-based; funded by contributions, camp and tournament proceeds; must already hold a roster spot and have paid a deposit | None |
| DC Soccer Club | Committee independent of coaches; annual reapplication; covers uniforms | **$250,000–$350,000 awarded per year** across all eight wards |
| Alexandria | Rec aid tied to ACPS free/reduced lunch; Academy aid by inquiry | **ASA's Spring2ACTion page: "Last year ASA supported over 2,000 participants with $715,000 in financial aid support."** Other ASA figures differ: its Access4All page says "In 2022, ASA provided $750,000 in scholarship support to 2,500 participants," The Zebra (June 7, 2025) reported "2,929 participants with a total of $750,000," and its 2020 budget explainer reported over $450,000 to 1,500+ kids |
| LMVSC | No cap on number of scholarships | None |
| Achilles FC Foundation | Scholarships for low-income families | None found |

Equity red flags visible in the policies themselves:
- **Deposit-before-aid rules.** VDA requires $400 and Bethesda requires a deposit before aid is considered, which screens out the lowest-income families at the front door.
- **Percentage caps with uncovered team fees.** Under Arlington's 60% cap, a maximum-aid Academy family still owed $1,670–$1,970 to the club in 2023–24, before travel.
- **Talent-conditioned aid** at the elite tier (Loudoun GA).
- **Aid excluded from add-on training**, which is often where development advantages accrue.

Alexandria's aid totals are the strongest public evidence of scale. Its roughly $715,000 is on the order of one-tenth of its FY2025 revenue, though the aid figure is calendar 2025 and the revenue fiscal year ends June 2025, so the ratio is approximate. Virginia Senate Resolution SR603 (2022 session) states that ASA offers "financial aid to one in three participants, including $675,000 worth of aid in 2021 alone," which is the only participation-rate figure found for any club in the set. DC Soccer Club's range equals about 5–7% of its FY2025 revenue. Neither separates aid for elite (ECNL/MLS NEXT) teams from recreational aid.

### 4. Annual reports, audits, budgets, board minutes
- **Alexandria** is the only club found publishing a budget explainer ("Where Does All the Money Go?", 2020), a financial-information link on its About page and a staff conflict-of-interest process.
- No club in the set was found posting audited financial statements, current budgets or board minutes. Those may exist behind member logins.
- ProPublica also hosts Single Audits for nonprofits spending $750,000 or more in federal funds. These were not checked club by club; given how little public money these clubs report, few if any are likely.

### 5. Sponsorship, grants and public-funding disclosures
- **Public-sector links are real but largely unquantified.** Arlington travel teams train on fields allocated by Arlington County Parks and Recreation and accept the county's fee-reduction form as aid documentation. SYC routes families to the Fairfax County Department of Community and Recreation Services Youth Scholarship Program. Alexandria ties rec aid to ACPS lunch eligibility and has piloted free after-school leagues at Title 1 schools. VDA pays facility fees for Long & Howison Park. Field-allocation value, which is effectively an in-kind public subsidy, is not disclosed by any club.
- **Philanthropy channels:** Arlington (Arlington Community Foundation listing, Givebutter), Alexandria (Spring2ACTion), and Bethesda (scholarship donations). FC Frederick's $1.09M in contributions is unusually large and warrants a look at Schedule B/O for its source.
- **Pro and corporate partnerships:**
  - D.C. United's "Pathway-to-Pro" program with local clubs.
  - D.C. United's minority stake in Loudoun United. According to Loudoun United FC's April 17, 2025 press release on the VA Revolution merger, "The partnership comprises Virginia Revolution, D.C. United, and Attain Sports, and will be managed by Virginia Revolution's principal owner, Jim Miller." Attain Sports & Entertainment bought controlling ownership of Loudoun United on Feb 2, 2023.
  - Arlington's partnership with Swansea City AFC.
  - The St. James's partnership with Chelsea FC.
  - Commercial sponsors are visible on club sites, such as a GoHealth banner on Arlington's fee page.

  None of these partnerships disclose dollar terms.

### 6. For-profit registrations (Maryland SDAT, Virginia SCC, DC DLCP)
These registry records could not be verified in this research. Entity names, formation dates and registered agents for D.C. United, DC Power FC, The St. James, Loudoun United/VA Revolution, Achilles FC and LFC IA Maryland should be pulled from:
- Virginia SCC's Clerk's Information System;
- Maryland SDAT's Business Entity Search;
- DC DLCP's CorpOnline.

Note the practical limit: state registries in these jurisdictions disclose entity status and agents, not finances. Registration closes the "who owns this" gap but not the "what does it cost / where does money go" gap.

## Most and Least Transparent

**Most transparent**
1. **Arlington Soccer Association:** current 990; full fee grid with aid math; FPL-based priority rules; candid admission that aid is rationed to the ≤130% FPL group.
2. **Alexandria Soccer Association:** current 990; published aid dollar and participant totals; budget explainer; conflict-of-interest process.
3. **DC Soccer Club (Stoddert):** current 990; published annual aid range; independent aid committee.
4. **Loudoun Soccer:** current 990; financial policy PDF; explicit income threshold.

**Least transparent**
1. **The St. James FC:** for-profit; no 990; no team fee schedule or aid policy found.
2. **Achilles FC:** no club financials; the Foundation was not located on ProPublica, possibly because it files only a 990-N.
3. **VA Revolution / Loudoun United:** stale nonprofit filing (FY2022, $16,967); now tied to a privately owned pro club; only school tuition is published.
4. **NVA, VDA and Fairfax Virginia Union:** fees are public for VDA and FVU, but finances are split across parent-club 990s, so program-level economics are unobservable.
5. **D.C. United Academy and DC Power FC** are opaque financially but have little direct affordability concern. The academy is stated to be fully funded, and Power FC signs players to contracts. Here the equity questions are about **who reaches them** (feeder-club costs), not their fees.

## Data Gaps and Feasibility of a Goal Equity Advisors Database

**Feasible with high confidence (Tier 1, low cost):**
- 990 financials for 14 nonprofits via ProPublica's API/XML or IRS TEOS: revenue, fee share, contributions, compensation, net assets and deficits. This is annual and fully reproducible.

**Feasible with effort (Tier 2, seasonal scraping and manual coding):**
- Fee schedules and aid rules. Expect inconsistent formats (PDFs, PlayMetrics/LeagueApps checkout-only disclosures), dated pages (Arlington's grid is 2023–24), and missing team, uniform and travel costs.
- Build a standardized "published cost floor," and separately a modeled all-in cost using club-stated add-ons (for example, VDA's $400–$500 uniforms).

**Not feasible from public sources (Tier 3, needs outreach or surveys):**
- Number and share of players on aid by tier.
- Aid dollars at the elite tier.
- Demographic and ZIP-code composition of rosters.
- Team-fee totals.
- For-profit finances.
- Value of public field allocations. This could be approached via county Parks and Recreation allocation records or FOIA requests, which is an untested but promising route.

**Recommendations**
1. Launch with a 990 panel of the 14 filers and publish standardized ratios: fee share of revenue, aid-proxy (where Schedule data allow), executive compensation per $1M of revenue, and reserve months.
2. Create a uniform "Access Disclosure" request covering aid dollars, recipients by tier, deposit rules, team-fee ranges, and whether aid covers team fees and uniforms. Send it to all 25 clubs, and score clubs on response. Non-response is itself a transparency metric.
3. Treat alliances (NVA, VDA, FVU) as the unit families experience, and request program-level P&Ls from parent clubs.
4. Pull SDAT, SCC and DLCP records for all for-profit and unverified entities before publication.
5. Prioritize policy changes the data already supports: aid without deposit requirements, aid that covers team fees and uniforms, and published annual aid outcomes on the model of Alexandria and DC Soccer Club.

## Caveats
- Several 990 figures (Loudoun, Alexandria, SYC, Stoddert, PWSI, Vienna, GFR, Braddock, Montgomery, Maryland United, FC Frederick) come from a research sub-pass of ProPublica summary pages. The underlying PDFs and XML were not opened, and the top-compensated person reflects only the first screen of listed people.
- The ProPublica record for Loudoun lists an exemption date of Nov 2024 despite filings back to 2010, which is likely an IRS master-file quirk.
- Montgomery Soccer Inc. has a separate legacy entity (Maryland Rush Montgomery Soccer Association, EIN 36-4544964) that is no longer on the IRS exempt list.
- 990s for Lee Mount Vernon, Virginia Valor, and LFC IA Maryland were not checked. Fairfax Virginia Union was not searched by its own name in ProPublica.
- The "Northern Virginia Alliance League" 990 filer (EIN 52-1284397, $81,454 revenue) is probably not the NVA elite program.
- The D.C. United "fully funded" academy statement comes from a Sept 15, 2020 SoccerWire article, echoed by MLSsoccer.com, on D.C. United's plans for its "Under-15, Under-16, and Under-17 Academy youth teams for the 2020-21 season and moving forward, with all teams being fully-funded by the club." MLSsoccer.com added that "The club had previously been one of two MLS teams to charge a fee to play for its youth academy teams." Earlier Washington City Paper reporting found that "United charges its players an annual fee—between $1,500 and $2,500, depending on the age group," and Black And Red United (Aug 2015) named the Portland Timbers as the other fee-charging MLS club.
- League memberships change yearly (for example, Fairfax BRAVE became Fairfax Virginia Union). Club selection reflects 2025–26 information as found, not a ranking.
- Third-party club directories (ClubScout, PlayClubSoccer, YouthSoccerSports) were used only for context. They are aggregators and some list outdated or conflicting data.
