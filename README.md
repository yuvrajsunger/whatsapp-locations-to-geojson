# whatsapp-locations-to-geojson
Converts locations shared in whatsapp chat into a single geojson file.

The ojective of writing this code for me is to keep track of attendance (location based) of field surveyors working in a project my team is heading.

For attendance, we have a whatsapp group where 25 field surveyors are supposed to share their current location, when they start in morning and when they leave. This is so that, we can monitor whether they are spending enough time on field or not.

But as analyzing this within whatsapp group, even for once in a while, is a cumbersome, I wrote this code to convert the "extracted whatsapp chat" into a single geojson file with all locations shared over weeks/days.

The resulting geojson file has locations shared as point features in it, with surveyors mobile number (unique ID), date time stamp of time of sharing, lat, lng and location link shared as its attributes.This geojson then can be very easily analyzed and visualized in QGIS using its temporal feature (images are attached).

![15_02_21_10](https://user-images.githubusercontent.com/52693754/117569043-38159200-b0e1-11eb-9b74-ecc79592fe15.PNG)
![15_02_21_18](https://user-images.githubusercontent.com/52693754/117569048-3f3ca000-b0e1-11eb-9dce-859a7d7b8c90.PNG)
