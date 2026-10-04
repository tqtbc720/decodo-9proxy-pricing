# smartproxy review: what the Decodo rebrand changed, the real price per GB, and when a cheaper pay-per-IP pack wins

If you searched for a smartproxy review, you're likely after one of two things: whether the provider you read about a year ago is still worth the money, or whether the plan and price you saw in an old review still exist. Both questions trace back to the same cause. Smartproxy is not called Smartproxy anymore.

That's not a rumour or a rebrand-in-progress. Decodo states that Smartproxy became Decodo on 22 April 2025, with the same company, the same infrastructure, the same accounts — even the same API endpoints. Any review written before that date is describing the current product under its old name, and any price quoted in it should be treated as history until you check the live pricing page.

So this article does three things: it separates what actually changed from what only changed name, it walks through the real Decodo pricing a new buyer pays, and it puts the metered per-GB model next to the other common model — paying per IP with unlimited bandwidth — which is where providers like 9Proxy sit.

## What the rebrand did and didn't change

The rename is cosmetic for the network. Old accounts, subscriptions and dashboards carried over, so if you already had a Smartproxy plan, you still have a Decodo plan. The company's own footer still reads "decodo.com (formerly smartproxy.com)" — the continuity is deliberate.

What the rebrand did damage is the paper trail. Reviews, screenshots and tutorials published before 2025 reference menus and plan names that a new signup no longer sees, and the review scores accumulated under the old brand sit on profiles the new name had to start building again. Treat the rebrand as a version boundary: behaviour described in old reviews — how rotation feels, how support responds — tends to survive a rename. Numbers do not.

One detail worth knowing if you're comparing pools: Decodo's own pages don't agree with each other. The residential product page publishes 115M+ addresses, while the location FAQ on the same site headlines 125M+ IPs across 195+ locations. Both are the company's own figures, most likely pulled at different update dates or counting different products. It's a small thing, but it tells you to treat advertised pool totals as marketing rather than a number you can compare against a competitor's.

Third-party aggregate scores are more useful. Toolradar logged a 4.6/5 average across 687 reviews tracked on G2, last checked in August 2026, and ProxyLook's comparison pages rate the same provider 4.5 stars.

## What Decodo actually sells

The catalogue is wider than the mid-market proxy average, and six products matter for a buying decision:

- **Residential proxies** — the flagship, billed per gigabyte, either pay-as-you-go or on a monthly subscription.
- **Static residential (ISP) proxies** — sold per dedicated IP or per GB of bandwidth.
- **Datacenter proxies** — also sold both per IP and per GB.
- **Mobile proxies** — billed per GB.
- **Web Scraping API** — billed per thousand requests, with the rate varying by request type (standard, JavaScript rendering, premium proxies).
- **Site Unblocker** — billed by bandwidth, and the priciest item on the list.

There's also a free tier on the AI Parser and MCP server, and a genuinely free allocation on the Web Scraping API — worth knowing if your interest is AI pipelines rather than raw IP access.

## The residential price a first-time buyer actually pays

The headline and the checkout are two different numbers. Decodo's residential page advertises "starting at just $2/GB." The $2/GB rate exists, but it sits at the 1,000 GB monthly tier. Here's the self-serve ladder:

| Plan | Effective rate | Monthly subtotal |
| --- | --- | --- |
| 3 GB | $3.75/GB | $11.25 |
| 10 GB | $3.50/GB | $35 |
| 25 GB | $3.25/GB | $81.25 |
| 50 GB | $3.00/GB | $150 |
| 100 GB | $275 | $275 |
| Pay as you go | $4.00/GB | billed per GB |

Larger commitments run to 250 GB, 500 GB and 1,000 GB, where the advertised floor lives. Two things push the invoice above the table: every listed proxy price is quoted before VAT, printed on the page as "+ VAT", and the entry-level rate is roughly 1.9x the advertised headline.

To be fair to Decodo, the $2/GB floor is a real published tier rather than a sales-call number, which is more than several competitors manage. The gap that deserves a warning is on the static residential side. ISP proxies advertise "from $0.27 per IP", but the cheapest purchasable dedicated static residential plan works out closer to $3.33 per IP — around 12x the headline figure — because the $0.27 row is a shared-list comparison entry with no purchase option attached. If static IPs are your actual requirement, reprice the whole thing before you get attached to that number.

## Trial or refund — you pick one, not both

This is the part that trips people up, because both offers are real and they're mutually exclusive.

> Decodo's 3-day trial includes 100 MB of traffic and requires a card for verification, with no upfront charge. But the trial auto-converts to your selected plan when it ends unless you cancel first — and taking the trial voids the 14-day money-back option.

The refund terms are narrow in their own right: it applies to a first self-service purchase, the request has to land inside 14 calendar days, and usage must stay under 20% of your traffic (10% on Enterprise) or 1 GB, whichever comes first. Crypto payments and enterprise plans are excluded from the described policy.

Our read is the same one FleetProxy arrived at: 100 MB comfortably proves that your proxies connect and authenticate, so take the trial if that's the question you're answering. It is not enough to prove that the IPs hold up against a hostile target, so if that's what you need to test, buy the smallest paid plan and let the refund window do the work instead.

## The catch with metered bandwidth

Everything above is a per-gigabyte model, and per-gigabyte models have a specific failure mode: unused allowance disappears at renewal. If your workload is spiky — a burst of scraping this month, quiet the next — you're paying for volume on the calendar rather than on the work. Decodo's pay-as-you-go option at $4/GB removes the expiry problem but strips out the volume discount at the same time.

That's the honest trade-off. If your jobs run steadily and you can predict monthly gigabytes, metered is fine. If you can't predict them, the billing unit itself is the thing to change rather than the provider.

## The other model: pay per IP, unlimited bandwidth

9Proxy is a residential network with 20M+ IPs across 90+ countries and a published uptime claim of 99.95%, and structurally it does something different. It sells two usage models side by side:

**Residential by IPs.** You buy a fixed number of residential IPs and pay per IP, not per gigabyte. Bandwidth on an active IP is unlimited. Unused IPs never expire and sit in your balance until forwarded, but an activated IP stays online for a few hours up to roughly 24 hours, because the underlying pool is genuinely residential. If an IP drops, Auto Refresh replaces it, or Auto Rotation swaps on a schedule. This model requires the desktop app for local port forwarding.

**Residential by GB.** You pay per gigabyte, generate unlimited proxy endpoints, choose rotating or sticky sessions, and authenticate with username/password or IP whitelisting. Nothing to install — it runs from the dashboard. Bandwidth carries 180-day validity, and every endpoint is countable rather than allocated.

For a workload where bandwidth is hard to predict but IP count is easy to count, that first model is a genuinely different deal from anything metered: it converts a variable bill into a fixed one.

👉 [Check the current 9Proxy price list and set up an account](https://bit.ly/9-Proxy)

## The full 9Proxy price list

### Residential by IPs — unlimited bandwidth per active IP

9Proxy raised its IP pricing recently; the 100-IP pack moved from $20 to $24. These are the tiers published after that adjustment.

| Package | Price per IP | Total | What it's for |
| --- | --- | --- | --- |
| 100 IPs | $0.24 | $24 | Proof of concept, small one-off jobs |
| 500 IPs | $0.144 | $72 | Solo operators, light scraping, multi-account work |
| 1,000 + 500 bonus IPs | $0.084 | $126 | Small teams with steady workloads |
| 2,500 IPs | ~$0.070 | ~$175 | Several verticals running at once |
| 5,000 IPs | ~$0.060 | ~$300 | Agencies, mid-scale SEO and price monitoring |
| 15,000 IPs | ~$0.040 | ~$600 | Regional teams, heavier automation |
| 25,000 IPs | ~$0.030 | ~$750 | Resellers, automation labs |
| 50,000 IPs | ~$0.025 | ~$1,250 | High-volume reseller operations |
| 100,000 IPs | $0.023 | $2,300 | Industrial-scale collection |
| 200,000 IPs | ~$0.021 | ~$4,140 | Platform-level operations |
| 500,000 IPs | $0.018 | $8,625 | The published floor |

The five largest rows and the three smallest were confirmed in Geekflare's 2026 review of the network after the price change. The mid-tier figures between 2,500 and 50,000 IPs come from the last full ladder published before that adjustment, which is why they carry a "~" — if your order lands in that range, confirm the live total at checkout rather than trusting this table.

|  |  |  |
| --- | --- | --- |
| [Get the 100-IP pack](https://bit.ly/9-Proxy) | [Get the 5,000-IP pack](https://bit.ly/9-Proxy) | [Get the 100,000-IP pack](https://bit.ly/9-Proxy) |

### Residential by GB — 180-day validity

| Package | Price per GB | Total | Validity |
| --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 days |
| 50 GB + 5 GB bonus | $2.10 | $105 | 180 days |
| 100 GB | $1.50 | $150 | 180 days |
| 200 GB | $1.00 | $200 | 180 days |
| 1,000 GB | $0.80 | $800 | 180 days |
| 2,000 GB | $0.75 | $1,500 | 180 days |

### Enterprise bandwidth — no expiry

| Package | Price per GB | Total | Validity |
| --- | --- | --- | --- |
| 3,000 GB | $0.72 | $2,160 | Never expires |
| 6,000 GB | $0.70 | $4,200 | Never expires |
| 10,000 GB | $0.68 | $6,800 | Never expires |

Enterprise also bundles team mode — one owner plus up to five members — with per-member traffic limits, activity logs, no-expiry bandwidth sharing inside the team, and unlimited Share Code creation. Share Codes are how you hand proxies to someone else; the minimum is 5 proxies or 1 GB per code, and a code from a regular package inherits that package's remaining validity, while an Enterprise code runs 180 days from redemption.

👉 [Compare the GB packs and Enterprise tiers](https://bit.ly/9-Proxy)

### Bundles — IPs and bandwidth in one purchase

| Bundle | Contents | Price | Best for |
| --- | --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 | Client pilots, single projects |
| Popular | 1,500 IPs + 50 GB | $180 | Agencies juggling a few active clients |
| Pro | 5,000 IPs + 500 GB | $720 | Shops that want one all-in pack |

Bundle traffic keeps the standard 180-day validity, which matters if a project stalls for a month.

## Decodo vs 9Proxy at a glance

|  | Decodo (formerly Smartproxy) | 9Proxy |
| --- | --- | --- |
| Billing unit | per GB, metered | per IP (unlimited bandwidth) or per GB |
| Commitment | monthly subscription or PAYG | one-off top-up, no renewal date |
| Entry price | $11.25 for 3 GB ($3.75/GB) | $24 for 100 IPs, or $15 for 5 GB |
| Unused balance | allowance expires at renewal | unused IPs never expire; GB valid 180 days (unlimited on Enterprise) |
| Free trial | 3 days / 100 MB, card required, auto-converts | limited trials for new users, subject to availability |
| Targeting | country, state, city, ZIP, ASN | country, state, city, ZIP, ISP |
| Published pool | 115M+–125M+ IPs, 195+ locations | 20M+ IPs, 90+ countries |
| Beyond residential | mobile, ISP, datacenter, scraping API, Site Unblocker, AI Parser, MCP server | residential only, IP and GB models, bundles |
| Team features | enterprise tier with account management | Enterprise: 1 owner + 5 members, logs, share codes |
| Payments | card-based checkout | card, crypto (USDT, BTC, ETH, LTC, DOGE), Alipay, Apple Pay, Google Pay, wallet |

Two of those rows decide most purchases. If you need datacenter IPs, an unblocking API or ASN-level targeting, Decodo is the only one of the two that sells them. If your bill is being driven by unpredictable bandwidth on long sessions, the pay-per-IP model is the shape that fixes it.

## Which one fits your job

- **Steady scraping with predictable volume** — Decodo's metered ladder is transparent enough to budget against, and the volume discount is real.
- **Long-running sessions where traffic is hard to forecast** — 9Proxy's IP packs cap the cost at the number of IPs you buy, with unlimited bandwidth on each active one.
- **Sites with heavy anti-bot defences** — Decodo's Site Unblocker and fingerprint handling do work that plain proxies can't, and it's priced per successful retrieval.
- **Multi-account and antidetect workflows** — both work, but 9Proxy's IP model exists specifically for stable per-profile session identity, and unused IPs don't burn off at month end.
- **Rare geographies or city-level precision at scale** — Decodo's larger pool and ASN filtering have the edge; 90+ countries is enough for common markets, not for every market.
- **Paying in crypto** — 9Proxy accepts it directly. Note that Decodo's published refund conditions exclude crypto payments, so you lose your exit on that route.

## Before you check out

Four things worth a minute of your time:

1. **Confirm the rate at your volume, not the banner rate.** Both providers advertise floors that only exist at the top of the ladder.
2. **Add VAT if you're an EU buyer on Decodo.** Every listed proxy price there is quoted before tax.
3. **Check the expiry rule on whatever you buy.** IP balances that never expire and bandwidth that's valid 180 days are worth more than a marginally cheaper rate that evaporates in 30.
4. **Check how the trial converts.** Decodo's trial converts to a paid plan on its own unless you cancel, and taking it forfeits the refund window.

## FAQ

**Is Smartproxy still available?**
Not under that name. Smartproxy became Decodo in April 2025 — same company, same network, same accounts and subscriptions. Search results still surface the old name because years of reviews and tutorials point at it.

**Do old Smartproxy reviews still apply?**
Partly. Anything about how the product behaves is usually still true. Anything about plan names, prices, caps and trial terms has to be re-verified on the current site.

**Is 9Proxy cheaper?**
Depends on the unit. Per IP, 9Proxy's published rate falls to $0.018/IP at 500,000 IPs and starts at $0.24/IP for 100, with unlimited bandwidth on each active IP. Against a metered provider, that's cheaper whenever your workload pushes a lot of traffic through few sessions, and more expensive whenever you need a huge rotating pool without stable identity.

**Does 9Proxy have a free trial?**
Trials exist for new users but are limited and subject to availability, so don't plan around one. The smallest paid pack is a low-cost way to test the pool and the port-forwarding app before scaling.

**Can I run both?**
Plenty of teams do — a metered provider for rotation-heavy jobs and a pay-per-IP provider for sessions that need to stay put. The billing models measure different things, so it isn't really double paying.

👉 [Start with a small 9Proxy pack and check the pool yourself](https://bit.ly/9-Proxy)

## The short version

Decodo is Smartproxy with a new name, a wider catalogue than its reputation suggests, and a pricing page where the headline and the checkout differ by roughly a factor of two. Its trial and refund are mutually exclusive, and its metered model punishes uneven usage. 9Proxy is the cheaper structure when your cost is driven by bandwidth you can't forecast, because you buy IPs and the traffic on them is unlimited — with the trade-off that its published pool is a fifth the size and it doesn't sell datacenter or unblocking products at all.

Pick by billing unit first, provider second. That's the decision that shows up on the invoice.
