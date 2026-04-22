
# City Hotel — Revenue Performance & Strategy Memo
**Dataset:** Hotel Booking Demand (Antonio et al., 2019) | 2015–2017  
**Scope:** City Hotel, non-cancelled bookings (n = 73,419)  
**Prepared by:** Tan Gek Yen

---

## 1. Performance Summary

City Hotel recorded a RevPAR range of €4.90 to €33.06 across the 
2015–2017 period, with clear mid-year seasonality peaks visible in 
July–August each year. Average daily rate (ADR) across all segments 
stands at €108.27, with occupancy averaging 19.2% under the current 
methodology (see limitations).

The hotel generates revenue across seven market segments, with Online 
TA and Offline TA/TO collectively accounting for approximately 79% of 
total revenue.

---

## 2. Key Issues Identified

**Issue 1: OTA over-dependence with material net revenue cost**

Online TA is the dominant channel at 60.9% revenue share (24,098 
bookings) and an ADR of €118.23. Direct bookings, however, command 
the highest ADR at €121.87 — a €3.64 gap per booking, while 
contributing only 11.5% of revenue (4,935 bookings).

The financial impact is larger than the ADR gap suggests. OTA 
commissions typically run 15–20% of booking value. At 15% commission 
on the average OTA ADR of €118.23, the net ADR per OTA booking is 
approximately €100.50 — versus €121.87 for a direct booking with 
near-zero acquisition cost. This represents a €21.37 net revenue gap 
per booking. Across 24,098 OTA bookings, shifting even 10% to direct 
would recover approximately €51,000 in net revenue annually.

**Issue 2: Pricing not dynamically adjusted to demand**

The yield curve (Occupancy Rate vs ADR) shows a positive but 
low-gradient relationship with high variance around the trend line. 
This indicates ADR is not being meaningfully adjusted in response to 
occupancy levels — rates appear largely static regardless of demand 
signals. A well-functioning yield management strategy would show a 
steeper positive relationship, with ADR rising as occupancy approaches 
capacity constraints.

**Issue 3: Corporate segment underleveraged**

Corporate bookings account for only 2.5% of revenue despite typically 
offering stable, predictable demand and lower acquisition costs than 
OTA channels. Underdevelopment of the corporate segment increases 
revenue volatility and OTA dependency.

---

## 3. Strategic Recommendations

**Recommendation 1: Direct channel shift**  
Target a 10% migration of OTA volume to direct bookings through rate 
parity enforcement, loyalty programme incentives, and best-rate 
guarantees on the hotel's own booking engine. Estimated net revenue 
uplift: ~€51,000 per year based on current booking volumes.

**Recommendation 2: Demand-based rate restrictions**  
Implement ADR floor restrictions during projected high-occupancy 
periods (Q3, consistent with observed RevPAR peaks). Close discounted 
and promotional rates when forward occupancy exceeds 70%, preventing 
ADR dilution during peak demand windows.

**Recommendation 3: Corporate account development**  
Prioritise outreach to corporate accounts in the hotel's catchment 
area to diversify revenue mix. A 5 percentage point increase in 
corporate revenue share — from 2.5% to 7.5% — would reduce OTA 
dependency and improve net revenue per booking given lower acquisition 
costs.

---

## 4. Limitations

- **Occupancy approximation:** Occupancy rate is estimated using daily 
  booking count divided by assumed hotel capacity (300 rooms). The 
  dataset does not include actual rooms-available figures. This 
  methodology likely underestimates true occupancy, which explains the 
  low average of 19.2%. RevPAR figures should be interpreted as 
  directional rather than absolute.
- **Geography:** Dataset covers a Portuguese city hotel. ADR figures 
  are in EUR and market dynamics may differ from target markets such 
  as Tokyo.
- **Cancellations excluded:** 37% of raw bookings were cancelled and 
  excluded from this analysis. Cancellation pattern analysis (e.g., 
  by channel or lead time) could yield additional revenue strategy 
  insights.
- **No cost data:** Analysis focuses on gross revenue. Net revenue 
  estimates for OTA commission impact use industry-standard assumptions 
  (15–20%) and should be validated against actual contract terms.