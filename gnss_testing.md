# Practical testing various configurations of the new ARF GNSS System against one of our existing units
**N. Tripcevich**, *Date: March 2020*
## New GNSS: [EMLID Reach RS2 Survey Kit](hhttps://arf.berkeley.edu/equipment/inventory/field/gps/emlid-reach-rs2-gnss-survey-kit)
## Existing GNSS: [Trimble Geo 6000](https://arf.berkeley.edu/equipment/field/gps/trimble-geoxh-6000-gps)

*Testing various configurations including:*
1. WAAS SBAS correction only
2. NTRIP Correction against [California CRTN Network](http://sopac.ucsd.edu/crtn.shtml) using the mountpoint in downtown Berkeley  SRB1_RTCM3
3. NTRIP Correction against [CSDS CSVSN Network](https://www.csdsinc.com/gps-network-services/)
4. RTK Correction against nearby Base (EMLID Only).

### Results
| Configuration   | solution status | lateral rms | sample count | distance to base | Base Satellites |
|-----------------|-----------------|-------------|--------------|------------------|-----------------|
| RS2 No WAAS     | Single          | 0.2869      | 431          |                  |                 |
| RS2 CRTN        | FIX             | 0.0037      | 114          | 896 m            |                 |
| RS2 CSVSN test1 | FIX             | 0.0067      | 375          | 
| RS2 CSVSN test2 | FIX             | 0.0055      | 239          |


Thousands of GNSS Real-time Reference Base Stations are available publicly online that can be used with our GNSS units using NTRIP provided that the device is on the internet. You will need either cellular broadband (create a hotspot with your cell phone) or a satellite internet connection hotspot.
A map showing the UNAVCO stations can be viewed online
https://www.unavco.org/instrumentation/networks/status/all/realtime

For example the UNAVCO Realtime station in Berkeley is called P224
https://www.unavco.org/instrumentation/networks/status/nota/overview/P224

Instructions for configurations (request email for login/passwd, etc) are here
https://www.unavco.org/data/gps-gnss/real-time/real-time-use-instructions.html

search EMLID forums for issues. Use Raw


