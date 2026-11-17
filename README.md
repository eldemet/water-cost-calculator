# Water Cost Calculator / Υπολογιστής Κόστους Νερού

Progressive Web App that estimates the monthly domestic water bill for a household under an increasing-block tariff.

**Live:** https://eldemet.github.io/water-cost-calculator/

## Inputs
- Number of people in the house
- Litres per person per day
- Days per month (default 30)

## Default tariff (monthly)
| Block (m³/month) | €/m³ |
|---|---|
| Fixed charge | €4.00 / month |
| 1 – 10 | 1.05 |
| 11 – 20 | 1.45 |
| 21 – 30 | 1.80 |
| 31 – 40 | 2.50 |
| 41 – 60 | 3.00 |
| 61 – 80 | 5.00 |
| > 80 | 10.00 |

Blocks are applied progressively. The tariff is editable in the app. VAT and sewerage charges are not included.

## Install
Open the live link on a phone or in Chrome/Edge and choose **Add to Home Screen / Install app**. Works offline after the first visit.
