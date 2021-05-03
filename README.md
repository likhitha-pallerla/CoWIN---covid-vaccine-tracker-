# CoWIN---covid-vaccine-tracker-
This python code is used to check the available slots fpr Covid-19 vaccination centers from CoWIN API in India

## Users can follow the below steps to use this tracker:

- state_ids can be found using curl -X GET "https://cdn-api.co-vin.in/api/v2/admin/location/states" -H  "accept: application/json" -H  "Accept-Language: hi_IN"
or open https://cdn-api.co-vin.in/api/v2/admin/location/states in browser

- district_ids can be found using curl -X GET "https://cdn-api.co-vin.in/api/v2/admin/location/districts/12" -H  "accept: application/json" -H  "Accept-Language: hi_IN"
or open https://cdn-api.co-vin.in/api/v2/admin/location/districts/32 in browser, replace 12 with your state_id.

- user can use online complier to use this feature: https://www.programiz.com/python-programming/online-compiler/
