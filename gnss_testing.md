# Practical testing various configurations of the new ARF GNSS System against one of our existing units
**N. Tripcevich**, *Date: March 2020*
## New GNSS: [EMLID Reach RS2 Survey Kit](hhttps://arf.berkeley.edu/equipment/inventory/field/gps/emlid-reach-rs2-gnss-survey-kit)
## Existing GNSS: [Trimble Geo 6000](https://arf.berkeley.edu/equipment/field/gps/trimble-geoxh-6000-gps)

*Testing various configurations including:*
1. WAAS SBAS correction only
2. NTRIP Correction against [California CRTN Network](http://sopac.ucsd.edu/crtn.shtml)
3. NTRIP Correction against [CSDS CSVSN Network](https://www.csdsinc.com/gps-network-services/)
4. RTK Correction against nearby Base (EMLID Only).

### Results
| Configuration   | solution status | lateral rms | sample count |
|-----------------|-----------------|-------------|--------------|
| RS2 WAAS        | SINGLE          | 0.2869      | 431          |
| RS2 CRTN        | FIX             | 0.0037      | 114          |
| RS2 CSVSN test1 | FIX             | 0.0067      | 375          |
| RS2 CSVSN test2 | FIX             | 0.0055      | 239          |
