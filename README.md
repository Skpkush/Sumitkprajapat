<div align="center">

# `sumit=#` Sumit Kumar Prajapat — Portfolio

**Data Analyst · BI Developer · PL-300 Certified**

A single-page portfolio built around a **terminal / SQL editor** aesthetic.
No framework, no build step — one hand-written `index.html`.

<a href="https://skpkush.github.io/Sumitkprajapat/"><img src="https://img.shields.io/badge/▶_Live_site-skpkush.github.io/Sumitkprajapat-15803D?style=for-the-badge&labelColor=18181B"/></a>

<a href="Sumit_Prajapat_Data_Analyst.pdf"><img src="https://img.shields.io/badge/Resume-PDF-E4E4E7?style=flat-square&labelColor=18181B&logo=adobeacrobatreader&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/sumit-k-prajapat/"><img src="https://img.shields.io/badge/LinkedIn-connect-E4E4E7?style=flat-square&labelColor=18181B&logo=linkedin&logoColor=white"/></a>
<a href="mailto:sumitkprajapat29@gmail.com"><img src="https://img.shields.io/badge/Email-sumitkprajapat29@gmail.com-E4E4E7?style=flat-square&labelColor=18181B&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/Skpkush"><img src="https://img.shields.io/badge/GitHub-Skpkush-E4E4E7?style=flat-square&labelColor=18181B&logo=github&logoColor=white"/></a>

</div>

---

## ★ Latest build — Grocery Retail Analytics

<a href="https://github.com/Skpkush/grocery-retail-analytics"><img src="https://raw.githubusercontent.com/Skpkush/grocery-retail-analytics/main/docs/images/powerbi_1_executive_overview.png" width="100%" alt="Grocery Retail Analytics — Power BI Executive Overview"/></a>

> **Does a grocer's promotional spend actually change behaviour?**
> 1.46M real transactions · 2,469 households · a full year of dunnhumby *The Complete Journey* data.

| 1.46M | 50.6% | 102 + 6 | 58 / 58 |
| :---: | :---: | :---: | :---: |
| transactions modelled in dbt | coupon redemptions going to shoppers already buying | dbt data tests + unit tests, run in CI | Power BI values reconciled to SQL |

dbt project on DuckDB (28 models, staging → intermediate → marts, incremental fact tables) → 13 SQL analyses → difference-in-differences with placebo tests → 5-page Power BI report (45 DAX measures) + Streamlit app. `dbt build` runs on every push.

[`→ repo`](https://github.com/Skpkush/grocery-retail-analytics) &nbsp;·&nbsp; [`🟢 live app`](https://grocery-retail-analytics-gej2xcqxwhwypm7lvjhher.streamlit.app/)

---

## What's on the site

| section | what it does |
| :--- | :--- |
| `psql hero` | an animated SQL query that "returns" the intro row |
| `projects.sql` | tab filters rewrite a live `SELECT … WHERE … ORDER BY` query, plus a psql result-set of headline metrics |
| `journey.git` | career history rendered as `git log` commits |
| `⌘K` palette | `Ctrl+K` / `⌘K` jumps between sections and runs actions (resume, email, live apps) |
| theme | light / dark toggle, scroll-reveal animations, ATS-friendly resume download |

### Featured projects

<table>
  <tr>
    <td width="50%" valign="top"><a href="https://github.com/Skpkush/grocery-retail-analytics"><img src="https://raw.githubusercontent.com/Skpkush/grocery-retail-analytics/main/docs/images/powerbi_1_executive_overview.png" width="100%" alt="Grocery Retail Analytics"/></a><br/><b><a href="https://github.com/Skpkush/grocery-retail-analytics">Grocery Retail Analytics</a></b><br/><sub>dbt · 1.46M transactions → <b>50.6% of coupons go to habitual buyers</b></sub></td>
    <td width="50%" valign="top"><a href="https://github.com/Skpkush/Healthcare-Insurance-Claims-Analytics"><img src="https://raw.githubusercontent.com/Skpkush/Healthcare-Insurance-Claims-Analytics/v2-real-data/dashboard/Executive%20command%20center.png" width="100%" alt="Healthcare Provider Fraud Detection"/></a><br/><b><a href="https://github.com/Skpkush/Healthcare-Insurance-Claims-Analytics">Healthcare Provider Fraud Detection</a></b><br/><sub>558K claims → <b>226× fraud concentration</b> · 90.1% recall</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://github.com/Skpkush/mf-analytics-platform"><img src="https://raw.githubusercontent.com/Skpkush/mf-analytics-platform/main/docs/screenshots/page1_executive.png" width="100%" alt="Mutual Fund Analytics Platform"/></a><br/><b><a href="https://github.com/Skpkush/mf-analytics-platform">Mutual Fund Analytics Platform</a></b><br/><sub><b>14,384 schemes</b> · 51 AMCs · Prophet NAV forecasts</sub></td>
    <td width="50%" valign="top"><a href="https://github.com/Skpkush/Olist-E-Commerce-Analytics-Dashboard"><img src="https://raw.githubusercontent.com/Skpkush/Olist-E-Commerce-Analytics-Dashboard/main/Images/page1_sales_intelligence.png" width="100%" alt="Olist E-Commerce Analytics"/></a><br/><b><a href="https://github.com/Skpkush/Olist-E-Commerce-Analytics-Dashboard">Olist E-Commerce Analytics</a></b><br/><sub>112,650 rows → <b>~97% one-time buyers</b> · 40+ DAX</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><a href="https://github.com/Skpkush/Customer-Segmentation"><img src="https://raw.githubusercontent.com/Skpkush/Customer-Segmentation/main/images/rfm_segments.png" width="100%" alt="Customer Segmentation"/></a><br/><b><a href="https://github.com/Skpkush/Customer-Segmentation">Customer Segmentation</a></b><br/><sub>RFM + K-Means · <b>Silhouette 0.52</b> · live app</sub></td>
    <td width="50%" valign="top"><a href="https://www.queryscratch.com/"><img src="assets/queryscratch.png" width="100%" alt="QueryScratch"/></a><br/><b><a href="https://www.queryscratch.com/">QueryScratch</a></b><br/><sub><b>500 SQL challenges</b> · in-browser sandbox</sub></td>
  </tr>
</table>

---

## Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

Fonts: Inter + JetBrains Mono (Google Fonts). Hosted free on GitHub Pages.

## Run locally

It's a static site — open `index.html` in a browser, or serve it:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
index.html                        # the entire site (HTML + CSS + JS)
Sumit_Prajapat_Data_Analyst.pdf   # downloadable resume
assets/queryscratch.png           # project screenshot
```

<div align="center">

<sub><code>sumit=# COMMIT;</code> — open to Data Analyst · BI Developer · Power BI Developer roles</sub>

</div>
