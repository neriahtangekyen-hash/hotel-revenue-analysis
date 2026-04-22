# hotel-revenue-analysis
## Hotel Revenue Analysis — City Hotel (2015–2017)

### Overview
Exploratory revenue analysis of a European city hotel using the Hotel 
Booking Demand dataset (Antonio et al., 2019). Calculates core hospitality 
KPIs and applies yield analysis to identify revenue optimisation opportunities.

### KPIs Calculated
- RevPAR (Revenue Per Available Room)
- ADR (Average Daily Rate) by market segment
- Occupancy Rate (approximated via booking count / estimated capacity)

### Key Findings
1. **OTA dependency risk:** Online TA accounts for 60.9% of revenue at 
   an ADR of ~€110, while Direct bookings achieve ~€125 ADR at only 11.5% 
   share — suggesting significant net revenue upside from shifting volume 
   to direct channels (estimated 15–20% commission saving on migrated bookings).

2. **RevPAR trend:** City Hotel RevPAR grew from ~€10 in mid-2015 to ~€35 
   by mid-2017, with clear seasonality peaks in mid-year months consistent 
   with summer demand patterns.

3. **Pricing not demand-linked:** The yield curve shows a positive but 
   weak occupancy-ADR relationship (wide scatter around trend line), 
   suggesting rates are not being dynamically adjusted to occupancy levels — 
   a yield management gap.

### Methodology Note
Occupancy rate is approximated using daily booking count divided by 
estimated hotel capacity (300 rooms for City Hotel). This likely 
underestimates true occupancy. Dataset covers non-cancelled bookings only 
(~73,000 of 119,000 total rows; ~37% cancellation rate excluded).

### Data Source
Antonio, N., de Almeida, A., & Nunes, L. (2019). Hotel booking demand datasets. 
Data in Brief, 22, 41-49.
