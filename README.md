# Frankfurt VPS: what €3.49–€15.90 a month actually buys, which tier fits your workload, and the costs the plan tables hide

A Frankfurt VPS costs roughly €3.49 to €5.49 a month from hosts that publish euro prices, or $3.89 to $3.99 from hosts that bill in dollars, and that entry tier is usually one vCPU, 1 GB of RAM and 15–25 GB of disk. That runs a static site, a small API, a WireGuard endpoint or a bot that has to stay online. A database that matters, Windows, or a handful of concurrent services pushes you into the €8–€16 band.

Prices here come from the hosts' own pages. Wolkra and EDIS Global were checked on 30 and 28 October 2026, EDBB's figures come from a page dated 14 November 2025 and are labelled as such, and OliveVPS and Arct Cloud publish no page date, so their numbers are described as page figures rather than current ones. JustHost's plan list carries no date either; what follows is what its English VPS page displays.

> **Short answer.** For a single small site or API in Frankfurt, the cheapest tier is enough. You do not need 4 GB of RAM for a brochure site. The lowest monthly figure in this round of checking is JustHost's Sirius plan: 1 vCPU, 1 GB RAM, 20 GB NVMe, unmetered traffic on a 300 Mbit fair-share port, at $2.81 a month, or $2.25 a month if you prepay 12 months. It is IPv6-only, and JustHost sells from one global configurator rather than city pages, so confirm Frankfurt in the location selector before paying. 👉 [Check JustHost's current VPS plan list and prices](https://justhost.asia/en/vps?ref=196392)

## What JustHost actually sells, plan by plan

JustHost runs a configurator: you choose a plan, a storage type (HDD, SSD or NVMe) and a location. Its English VPS page lists two separate lines, and the split matters more than any single spec.

### IPv6-only plans

| Plan | vCPU · RAM · Disk | Port | Price (USD) | Order |
| --- | --- | --- | --- | --- |
| Sirius | 1 · 1 GB · 20 GB NVMe | 300 Mbit | $2.81/mo · $2.25/mo on 12-month prepay | [Order Sirius](https://justhost.asia/en/vps?ref=196392) |
| Arcturus | 1 · 2 GB · 30 GB NVMe | 300 Mbit | $4.01/mo · $3.21/mo prepaid | [Order Arcturus](https://justhost.asia/en/vps?ref=196392) |
| Vega | 2 · 4 GB · 80 GB NVMe | 500 Mbit | $7.79/mo · $6.23/mo prepaid | [Order Vega](https://justhost.asia/en/vps?ref=196392) |
| Yildun | 4 · 8 GB · 200 GB NVMe | 750 Mbit | $16.20/mo · $12.96/mo prepaid | [Order Yildun](https://justhost.asia/en/vps?ref=196392) |
| Betelgeuse | 6 · 12 GB · 400 GB NVMe | 750 Mbit | $26.40/mo · $21.12/mo prepaid | [Order Betelgeuse](https://justhost.asia/en/vps?ref=196392) |
| Altair | 8 · 24 GB · 600 GB NVMe | 750 Mbit | $47.40/mo · $37.92/mo prepaid | [Order Altair](https://justhost.asia/en/vps?ref=196392) |

### IPv4 + IPv6 plans

| Plan | vCPU · RAM · Disk | Price (USD) | Order |
| --- | --- | --- | --- |
| HDD VPS Start | 1 · 512 MB · 5 GB HDD | $3.25/mo · $2.60/mo prepaid | [Order HDD Start](https://justhost.asia/en/vps?ref=196392) |
| SSD VPS Start+ | 1 · 512 MB · 5 GB SSD | $3.90/mo · $3.12/mo prepaid | [Order SSD Start+](https://justhost.asia/en/vps?ref=196392) |
| NVMe VPS Start++ | 1 · 512 MB · 5 GB NVMe | $4.22/mo · $3.38/mo prepaid | [Order NVMe Start++](https://justhost.asia/en/vps?ref=196392) |
| HDD VPS Standard | 2 · 2 GB · 25 GB HDD | $11.00/mo · $8.80/mo prepaid | [Order HDD Standard](https://justhost.asia/en/vps?ref=196392) |
| SSD VPS Standard+ | 2 · 2 GB · 25 GB SSD | $13.20/mo · $10.56/mo prepaid | [Order SSD Standard+](https://justhost.asia/en/vps?ref=196392) |
| NVMe VPS Standard++ | 2 · 2 GB · 25 GB NVMe | $14.30/mo · $11.44/mo prepaid | [Order NVMe Standard++](https://justhost.asia/en/vps?ref=196392) |
| HDD VPS Super | 4 · 4 GB · 50 GB HDD | $22.00/mo · $17.60/mo prepaid | [Order HDD Super](https://justhost.asia/en/vps?ref=196392) |
| SSD VPS Super+ | 4 · 4 GB · 50 GB SSD | $26.40/mo · $21.12/mo prepaid | [Order SSD Super+](https://justhost.asia/en/vps?ref=196392) |
| NVMe VPS Super++ | 4 · 4 GB · 50 GB NVMe | $28.60/mo · $22.88/mo prepaid | [Order NVMe Super++](https://justhost.asia/en/vps?ref=196392) |

Two things in that pair of tables decide whether JustHost is cheap or not.

The famous $2.25 is an IPv6-only plan. The company's own marketing says all plans include IPv4/IPv6, but the plan list separates the two lines, and the plan names on the site end in `_ipv6`. If your site needs an address the IPv4 internet can reach without a gateway, you are on the second table, where the cheapest option is 512 MB of RAM and a 5 GB disk. The next IPv4+IPv6 step with usable memory is 2 vCPU / 2 GB / 25 GB at $11.00 a month, or $8.80 prepaid.

That gap is worth pricing against the alternatives. $8.80 prepaid buys 2 vCPU and 2 GB here. Wolkra charges €4.99 a month for 1 vCPU / 2 GB / 30 GB plus €0.89 for a primary IPv4. OliveVPS charges $7.99 a month for 1 vCPU / 2 GB / 60 GB with a static IPv4 included. On the IPv6 side JustHost wins on price; on the IPv4 side it does not. 👉 [Open JustHost's IPv4 and IPv6 plan list side by side](https://justhost.asia/en/vps?ref=196392)

## Frankfurt entry prices across the hosts that publish them

| Host and facility | Entry plan | Price as published | What to watch |
| --- | --- | --- | --- |
| Wolkra, fra1 | 1 vCPU · 1 GB · 15 GB, unmetered | €3.49/mo, hourly €0.0056 capped at the monthly price | IPv4 is €0.89/mo extra; page dated 30 Oct 2026 |
| EDIS Global, Equinix FR5 | 1 vCPU · 1 GB · 15 GB · 1 TB | €4.99/mo | Priced excl. VAT; extra IPv4 €5/mo; page dated 28 Oct 2026 |
| OliveVPS, Interxion FRA8 | 1 vCPU · 1 GB · 25 GB NVMe · 1 TB | $3.99/mo | Starter is Linux-only; static IPv4 and /64 IPv6 included |
| EDBB, Frankfurt | 1 core · 1 GB · 20 GB SSD · 1 TB | €5.49/mo | Excl. VAT; figures from a page dated 14 Nov 2025 |
| Arct Cloud, Frankfurt | Entry from $3.89/mo | $3.89/mo | No full plan table published; Windows needs 2+ vCPU |

Read the entry prices as a floor, not a quote. A €4.99 plan that excludes VAT and charges €5 for an extra IPv4 is not competing with a $7.99 plan that includes both.

## The four line items that move the bill

**IPv4.** Wolkra includes IPv6 and sells a primary IPv4 for €0.89 a month. EDIS charges €5 a month per additional IPv4, up to 10. OliveVPS includes a static IPv4 and a routed /64. JustHost splits its catalogue instead. On a two-year horizon an IPv4 surcharge of €5 a month is €120, which is more than the server.

**Backups.** Wolkra prices daily backups at 20% of the server price with seven restore points. On a €3.49 plan that is €0.70 a month; on a €24.99 plan it is €5. A fixed-price backup add-on from another host can be cheaper at the top end and more expensive at the bottom. Ask which model you are buying.

**Overage and add-ons.** OliveVPS bills traffic beyond the plan at $0.005/GB. EDIS sells +1 vCPU at €10 a month and storage boosts from €3.60 a month, with a 500 GB total disk ceiling and 8 vCPU / 24 GB RAM expansion caps.

**VAT.** EDIS prints "Excl. VAT" next to the €4.99, and EDBB states its prices exclude VAT. Wolkra, OliveVPS, Arct Cloud and JustHost do not say either way on the pages checked. A German consumer price can be a fifth higher than the headline.

## Hourly billing changes what a test costs

Wolkra bills from a prepaid balance by the started hour and caps the total at the monthly price. The arithmetic checks out: the 2 vCPU / 4 GB plan is €0.0144 an hour, which would be about €10.50 over 730 hours, but the cap holds it at €8.99.

For short work that is the cheapest way to buy a Frankfurt server anywhere in this comparison. Three hours on the smallest plan is about two cents. A week of benchmarking a latency-sensitive app costs under a euro. Monthly-only hosts charge the full month whether you use three hours or three weeks of it.

The catch is that hourly billing rewards deleting the server. If you keep it, you converge on the monthly price anyway, so there is no long-run saving, only a lower cost of experimenting.

## What the network numbers do and don't tell you

Frankfurt matters because DE-CIX is there. OliveVPS publishes round-trip figures from its Frankfurt region of 1–3 ms locally, about 16 ms to London, 240 ms to Tokyo and 300 ms to Sydney. If your users are in DACH or the Benelux, a Frankfurt box keeps the European leg short.

The big throughput numbers on vendor pages are a different measurement. EDIS reports 16,699.51 Mbps down and 9,398.20 Mbps up with 0.48 ms idle latency, and EDBB reports 18,716.09 Mbps down and 16,407.04 Mbps up with 0.76 ms, both run with Speedtest CLI on 21 September 2026 and 14 November 2025 respectively. Both pages state plainly that these are tests from the host platform to a same-city Speedtest server and not a guarantee of what a single VPS will push. Treat them as evidence that the uplink is not oversubscribed at 1 Gbit, nothing more.

One more caution: the German network paragraphs on EDIS and EDBB, listing Arelion, Lumen, Cogent, Zayo, Hurricane Electric, GTT, Sparkle, Verizon, Deutsche Telekom, Vodafone and NTT in near-identical wording, read like the same copy. Do not count them as two independent confirmations of the same peering claims.

JustHost's "unmetered" traffic deserves the same scepticism. Its own page explains the 300 Mbit port as fair-share and equates it to 93+ TB a month. Unmetered means no per-gigabyte bill, not a reserved 93 TB.

## Windows, upgrades and refunds: the rules you only find after paying

Windows needs at least 2 vCPU at Arct Cloud, and deployment takes 2–4 minutes against under 30 seconds for Linux. OliveVPS restricts its $3.99 Starter plan to Linux and puts Windows on the $7.99 Pro and $15.99 Premium tiers, which include the licensing surcharge. EDBB labels all three Starter plans "Linux recommended · Windows not recommended". A $3.99 Windows VPS does not exist at any of these hosts.

Upgrades are not always one click. EDIS requires a full shutdown and restart for RAM, vCPU and storage changes, and after a storage upgrade you expand the partition and filesystem yourself. OliveVPS handles an upgrade with a single reboot of 60–90 seconds but requires a backup and rebuild to go down a tier. Buying one size too large and shrinking later is more work than starting small.

Refunds: OliveVPS offers 7 days, no questions, with no free trial. Arct Cloud has no free tier. JustHost's published refund policy is written in general terms. It describes deductions for costs already incurred, refunds through the original payment channel, and a written calculation with each deduction itemised, but it does not state a simple "X-day money-back" window.

## JustHost's track record, and who should avoid prepaying

JustHost's own company description says 45 server locations worldwide with NVMe storage, unlimited traffic, free SSL, DDoS protection, root access and 24/7 support. Reviews on Trustpilot's page for the brand, dated August 2025, include complaints about oversold nodes and unusable locations, slow support responses, a VPS blocked after an abuse report with the customer unable to start or image it afterwards, and a prepaid 36-month plan blocked about six weeks in. Some reviewers also credit the company for actively monitoring for malware callbacks, which is what triggered at least one of those blocks.

The practical read: the 20% annual discount on Sirius is $0.56 a month, about $6.72 a year. That is what you are paid for handing over 12 months in advance. If a blocked node or a billing dispute would hurt, pay monthly at $2.81 and keep the exit open. If you are running something disposable, take the discount. 👉 [Compare JustHost's monthly and prepaid prices before choosing a term](https://justhost.asia/en/vps?ref=196392)

## Which plan to pick

**One static site, a redirect, a WireGuard endpoint, a Telegram bot.** The 1 vCPU / 1 GB tier is the right size. JustHost's Sirius at $2.81 monthly or $2.25 prepaid is the cheapest here if IPv6-only works for you; if you need IPv4, OliveVPS Starter at $3.99 or Wolkra at €3.49 plus €0.89 for IPv4 are the honest comparisons.

**A small app with a database, Redis, or a queue worker.** 2 vCPU / 4 GB. Wolkra's €8.99 plan is the cleanest buy because the IPv4 surcharge is small and hourly billing means a failed migration costs cents. JustHost's Vega at $7.79 is cheaper per month but IPv6-only.

**Windows, RDP, MT4/MT5, a trading terminal.** Budget for 2 vCPU minimum. OliveVPS Pro at $7.99 includes the licence surcharge; EDIS covers Windows Server 2019 through 2025 and Windows 10/11 if you need a specific image.

**A two-hour latency test, nothing more.** Use a host that bills hourly and delete the server.

Three things to confirm in the order flow before any card details go in: whether the price includes VAT, whether an IPv4 address is part of the plan or a paid extra, and what the refund window actually says in the agreement rather than on the sales page. If Frankfurt specifically is the requirement, watch the location selector rather than the plan name, because JustHost prices one global catalogue and the city is chosen during configuration.

👉 [Start with JustHost's VPS plan list and confirm Frankfurt at checkout](https://justhost.asia/?ref=196392)
