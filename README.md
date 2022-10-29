# Flydubai

flydubai Dataset
Problem Statement: Increase the revenue by increasing ancillary sell.

Data :
flydubai Sep_Oct 21 # Base file 1
flyDubai Nov21_Dec21 # Base file 2
flydubai Jan22_Feb22 # Base file 3
flydubai SSR Sep21_Feb22 # Ancillary data file

About Dataset :
The flydubai dataset is provided from the flydubai official CRM System. The dataset is in the form of csv files, Where 3 base files contains all the bookings from 
September 2021 to February 2022 and one Ancillary data file contains the only ancillary buying Bookings (Anc bookings are present in base booking data). The unique
identifier in the dataset is PNR Number. One Unique booking have one qnique PNR. In dataset total 8 unique Ancillary types.

The Basic Understanding of the dataset is :
1. Bookings are Distinct PNR count
2. Passengers: If the same person travels from DXB-BOM, and then returns BOM-DXB it is counted as 2 passengers
3. Journey : journey is the combination of origin destinations (If one pnr have two combinations of OD then Counted as 2 Journeys.)

The Column in the Base Dataset are :
year(departure_dt)	
month(departure_dt)	
from_airport	
to_airport	
confirmation_num	
person_org_id	
res_book_dt_lcl_key	
departure_dt	
journey_type	
pax_type_cde	
rev	
booking

The Column in the Ancillary Dataset are :
pnr	
leg_departure_date	
od_flight_no	
leg_flight_no	
from_od	
to_od	
from_leg	
to_leg	
ssr_code	
ssr_booked_date	
ssr_booked_time	
ssr_booked_time_utc	
ssr_booked_channel	
ssr_paid_revenue	
fare_brand_id	
booking_channel_id	
res_seg_status	
ptc_id	
charge_status	
Fare Brand 

flydubai dataset column Details :
1. pnr :
Passenger Name Record is the unique no. for each booking.
Valid
Mismatched

2. year(departure_dt) : Departure Year
Valid
Mismatched
Max
Min

3. month(departure_dt) : Departure Month
Valid
Mismatched
Max
Min

4. from_airport : Origin City
Valid
Mismatched

5. to_airport	: Destination City
Valid
Mismatched

6. confirmation_num	: Passenger Name Record is the unique no. for each booking (PNR)
Valid
Mismatched

7. person_org_id : Unique identifier for the customer
Valid
Mismatched

8. res_book_dt_lcl_key : At what date flight is booked
Valid
Mismatched
Max
Min

9. departure_dt	: Departure Date
Valid
Mismatched
Max
Min

10. journey_type	: Journey Type
Total Unique : OW : One Way
               RT : Return
               
11. pax_type_cde	: Passenger Type
Total Unique : ADT : Adult
               CHD : Child
               INF : Infant

12. rev	: Total Revenue

13. booking : No. of passengers

14. ssr_code	: Ancillary Type
Total Unique :

15.
