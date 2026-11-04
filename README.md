# BUDI MADANI Forecaster

**Independent RON95 consumption and cost scenario calculator for Malaysia.**

A multilingual, browser-based experiment that estimates fuel consumption and illustrative expenditure from driving distance and vehicle efficiency. This is not an official government service and does not determine eligibility or retrieve live prices.

## 01 / Overview

| | |
| :--- | :--- |
| **Purpose** | Illustrative monthly RON95 consumption and expenditure |
| **Platform** | Static single-page application |
| **Languages** | English, Bahasa Melayu, Mandarin, Tamil |
| **Stack** | HTML, vanilla JavaScript, Tailwind CSS, Chart.js |
| **Data** | User inputs and fixed reference assumptions |
| **Status** | Independent, experimental |

## 02 / Method

The calculator estimates daily consumption as distance (km) divided by efficiency (km/L). It multiplies daily consumption by 30 to estimate monthly fuel use, then calculates example spending using the reference subsidy allowance. A chart compares cumulative use with that allowance.

## 03 / Policy assumptions

| Parameter | Value | Note |
| :--- | ---: | :--- |
| Basic BUDI95 allowance | 300 L/month | Restored effective 1 September 2026; eligibility applies |
| Subsidised RON95 price | RM1.99/L | Ministry of Finance figure |
| Unsubsidised reference price | RM3.87/L | Example only, **not a live quote** |
| Forecast horizon | 30 days | Constant daily travel assumption |

**Policy source:** [Ministry of Finance announcement, 31 August 2026](https://www.mof.gov.my/portal/ms/berita/siaran-media/had-kelayakan-asas-bulanan-budi-madani-dinaikkan-semula-kepada-300-liter-mulai-1-september-2026).

The application does not check your actual quota, eligibility, prior purchases, or current pump price. Always confirm official requirements and prices before using an estimate for a financial decision.

## 04 / Features

- Four-language interface with immediate language switching
- Estimated 30-day consumption and cost based on user-supplied driving assumptions
- Chart.js visualisation of cumulative use against the basic reference allowance
- Static frontend without a backend or account system

## 05 / Running locally

Download or clone the repository and open `index.html` in a modern browser. An internet connection is needed to load the Tailwind CSS, Chart.js and font resources referenced in the page.

The earlier prototype AI advisor has been removed from the public version. It used a browser-side API key placeholder and inserted untrusted chat text into HTML. A safe future integration would require a protected backend, safe rendering, and maintained policy sources.

## 06 / Limitations

This is an educational modelling tool, not a production subsidy service. It assumes a 30-day period, constant daily driving and an example market price. It does not track actual purchases or verify eligibility. The calculator does not fetch government records or a live pricing feed.

---

**Independent project. Not affiliated with or endorsed by the Ministry of Finance or the BUDI MADANI programme.**
