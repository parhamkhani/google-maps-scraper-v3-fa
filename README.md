# Google Maps Scraper v3 (FA)

 یک ابزار برای استخراج **دقیق** و **جامع اطلاعات مکان‌ها از Google Maps** است. این ابزار قادر است **جزئیات کامل هر مکان** را جمع‌آوری کند؛ **خروجی دقیقا نتیجه ریسپانس API رسمی گوگل** است و می‌تواند به عنوان **منبعی دقیق برای تحلیل داده‌های مکانی یا توسعه نرم‌افزارهای مرتبط** مورد استفاده قرار گیرد.

هدف این ریپوزیتوری، ارائه یک **نمونه از نحوه استخراج داده‌های مکان‌ها** است. در صورتی که به **داده‌های مکانی خاصی** نیاز دارید، می‌توانید با من تماس بگیرید تا **استخراج سفارشی** انجام شود، بدون آنکه **محدودیت جغرافیایی یا نوع مکان** وجود داشته باشد.


---

## 🔹 نمونه خروجی

- نمونه خروجی برای 100 رستوران در تهران در پوشه [examples](https://github.com/parhamkhani/google-maps-scraper-v3-fa/tree/main/examples) موجود است.


### یک مکان نمونه در گوگل مپ + جیسون خلاصه شده این مکان:
<div style="text-align: center; margin: 20px;">
  <img src="https://github.com/parhamkhani/google-maps-scraper-v3-fa/blob/main/Tehran_360_Restaurant.png" 
       width="600"
     style="text-align: center; margin: 20px;">
</div><br>

<details>
<summary>نمایش JSON (کلیک کنید)</summary>

<div style="max-height:400px; overflow:100px; border:1px solid #ddd; padding:10px; background:#f7f7f7; margin:10px;">
<pre>
{
    "accessibilityOptions": {
        "wheelchairAccessibleEntrance": true,
        "wheelchairAccessibleParking": true,
        "wheelchairAccessibleRestroom": true,
        "wheelchairAccessibleSeating": true
    },
    "addressComponents": [
        {
            "languageCode": "en",
            "longText": "Milad Tower",
            "shortText": "Milad Tower",
            "types": [
                "premise"
            ]
        },
        {
            "languageCode": "en-US",
            "longText": "P9VG+X6",
            "shortText": "P9VG+X6",
            "types": [
                "plus_code"
            ]
        },
        {
            "languageCode": "en",
            "longText": "Milad Tower Road",
            "shortText": "Milad Tower Rd",
            "types": [
                "route"
            ]
        },
        {
            "languageCode": "en",
            "longText": "District 2",
            "shortText": "District 2",
            "types": [
                "sublocality_level_1",
                "sublocality",
                "political"
            ]
        },
        {
            "languageCode": "en",
            "longText": "Tehran",
            "shortText": "Tehran",
            "types": [
                "locality",
                "political"
            ]
        },
        {
            "languageCode": "en",
            "longText": "Tehran",
            "shortText": "Tehran",
            "types": [
                "administrative_area_level_2",
                "political"
            ]
        },
        {
            "languageCode": "en",
            "longText": "Tehran Province",
            "shortText": "Tehran Province",
            "types": [
                "administrative_area_level_1",
                "political"
            ]
        },
        {
            "languageCode": "en",
            "longText": "Iran",
            "shortText": "IR",
            "types": [
                "country",
                "political"
            ]
        }
    ],
    "addressDescriptor": {
        "areas": [
            {
                "containment": "WITHIN",
                "displayName": {
                    "languageCode": "en",
                    "text": "District 2"
                },
                "name": "places/ChIJcV9mQ3YHjj8R8U7K-91ORwE",
                "placeId": "ChIJcV9mQ3YHjj8R8U7K-91ORwE"
            }
        ],
        "landmarks": [
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "Milad Tower"
                },
                "name": "places/ChIJA4SR1RAHjj8ReBOEZwsp9XQ",
                "placeId": "ChIJA4SR1RAHjj8ReBOEZwsp9XQ",
                "spatialRelationship": "AROUND_THE_CORNER",
                "straightLineDistanceMeters": 88.14349,
                "travelDistanceMeters": 128.47746,
                "types": [
                    "establishment",
                    "point_of_interest",
                    "tourist_attraction"
                ]
            },
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "Milad Tower International Conference Center"
                },
                "name": "places/ChIJN9vVKREHjj8RFrT3Ad7JJnE",
                "placeId": "ChIJN9vVKREHjj8RFrT3Ad7JJnE",
                "straightLineDistanceMeters": 271.27313,
                "travelDistanceMeters": 180.23926,
                "types": [
                    "establishment",
                    "point_of_interest"
                ]
            },
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "Milad Tower Squash Club | MSC"
                },
                "name": "places/ChIJn92R0lIHjj8RA0k3Kb0dvLU",
                "placeId": "ChIJn92R0lIHjj8RA0k3Kb0dvLU",
                "spatialRelationship": "AROUND_THE_CORNER",
                "straightLineDistanceMeters": 99.03527,
                "travelDistanceMeters": 223.63126,
                "types": [
                    "establishment",
                    "point_of_interest"
                ]
            },
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "Tehran fire staton.119"
                },
                "name": "places/ChIJmTYodRQHjj8RiIy_O2G92Jg",
                "placeId": "ChIJmTYodRQHjj8RiIy_O2G92Jg",
                "straightLineDistanceMeters": 331.93695,
                "travelDistanceMeters": 406.23334,
                "types": [
                    "establishment",
                    "fire_station",
                    "point_of_interest"
                ]
            },
            {
                "displayName": {
                    "languageCode": "en",
                    "text": "Milad Circus"
                },
                "name": "places/ChIJwXf3RgAHjj8RtH14-7zCuCA",
                "placeId": "ChIJwXf3RgAHjj8RtH14-7zCuCA",
                "straightLineDistanceMeters": 282.15323,
                "travelDistanceMeters": 345.38333,
                "types": [
                    "establishment",
                    "point_of_interest"
                ]
            }
        ]
    },
    "businessStatus": "OPERATIONAL",
    "containingPlaces": [
        {
            "id": "ChIJA4SR1RAHjj8ReBOEZwsp9XQ",
            "name": "places/ChIJA4SR1RAHjj8ReBOEZwsp9XQ"
        }
    ],
    "currentOpeningHours": {
        "nextCloseTime": "2025-12-07T15:30:00Z",
        "openNow": true,
        "periods": [
            {
                "close": {
                    "date": {
                        "day": 7,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 0,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "date": {
                        "day": 7,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 0,
                    "hour": 0,
                    "minute": 0,
                    "truncated": true
                }
            },
            {
                "close": {
                    "date": {
                        "day": 7,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 0,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "date": {
                        "day": 7,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 0,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 8,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 1,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "date": {
                        "day": 7,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 0,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "date": {
                        "day": 8,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 1,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "date": {
                        "day": 8,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 1,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 9,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 2,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "date": {
                        "day": 8,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 1,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "date": {
                        "day": 9,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 2,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "date": {
                        "day": 9,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 2,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 10,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 3,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "date": {
                        "day": 9,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 2,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "date": {
                        "day": 10,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 3,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "date": {
                        "day": 10,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 3,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 11,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 4,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "date": {
                        "day": 10,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 3,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "date": {
                        "day": 11,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 4,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "date": {
                        "day": 11,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 4,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 12,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 5,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "date": {
                        "day": 11,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 4,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "date": {
                        "day": 12,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 5,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "date": {
                        "day": 12,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 5,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 13,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 6,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "date": {
                        "day": 12,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 5,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "date": {
                        "day": 13,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 6,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "date": {
                        "day": 13,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 6,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "date": {
                        "day": 13,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 6,
                    "hour": 23,
                    "minute": 59,
                    "truncated": true
                },
                "open": {
                    "date": {
                        "day": 13,
                        "month": 12,
                        "year": 2025
                    },
                    "day": 6,
                    "hour": 19,
                    "minute": 30
                }
            }
        ],
        "weekdayDescriptions": [
            "Monday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Tuesday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Wednesday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Thursday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Friday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Saturday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Sunday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM"
        ]
    },
    "dineIn": true,
    "displayName": {
        "languageCode": "en",
        "text": "Tehran 360 Restaurant"
    },
    "formattedAddress": "Tehran Province, Tehran, District 2, Milad Tower Rd, P9VG+X6 Milad Tower, Iran",
    "goodForChildren": true,
    "goodForGroups": true,
    "googleMapsLinks": {
        "directionsUri": "https://www.google.com/maps/dir//''/data=!4m7!4m6!1m1!4e2!1m2!1m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e!3e0?g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
        "photosUri": "https://www.google.com/maps/place//data=!4m3!3m2!1s0x3f8e071133d8e089:0xb1cb162f80d7489e!10e5?g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
        "placeUri": "https://maps.google.com/?cid=12811357958266374302&g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
        "reviewsUri": "https://www.google.com/maps/place//data=!4m4!3m3!1s0x3f8e071133d8e089:0xb1cb162f80d7489e!9m1!1b1?g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
        "writeAReviewUri": "https://www.google.com/maps/place//data=!4m3!3m2!1s0x3f8e071133d8e089:0xb1cb162f80d7489e!12e1?g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA"
    },
    "googleMapsUri": "https://maps.google.com/?cid=12811357958266374302&g_mp=Cilnb29nbGUubWFwcy5wbGFjZXMudjEuUGxhY2VzLlNlYXJjaE5lYXJieRACGAEgAA",
    "iconBackgroundColor": "#FF9E67",
    "iconMaskBaseUri": "https://maps.gstatic.com/mapfiles/place_api/icons/v2/restaurant_pinlet",
    "id": "ChIJieDYMxEHjj8RnkjXgC8Wy7E",
    "internationalPhoneNumber": "+98 21 8862 0381",
    "liveMusic": true,
    "location": {
        "latitude": 35.7447707,
        "longitude": 51.3755592
    },
    "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E",
    "nationalPhoneNumber": "021 8862 0381",
    "parkingOptions": {
        "freeParkingLot": true,
        "paidGarageParking": true,
        "paidParkingLot": true
    },
    "paymentOptions": {
        "acceptsCashOnly": false,
        "acceptsCreditCards": true,
        "acceptsDebitCards": true
    },
    "photos": [
        {
            "authorAttributions": [
                {
                    "displayName": "Hooman",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXZfu9lCNIl44XR4H4Q3bKqzZjY8hXP8Lf5mz80yA3QMZbgEwwH5Q=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/115213653929472846461"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgID-ooeNcQ&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgID-ooeNcQ!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 3000,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHock05EkNh8Lfrv9wwqCCvuM0b4B7vXvuafgRDeGL07Uk2Uf22fbKmib3bRDdzmqSHP_skTVdmqnIYPzyjfhaBuGoMGHsgXNvMCvfRvWbEN0jSHcM0SSo5i0ZB8NqR_y6lLjADg_hIn16hj9oHgH2ZSfZyf7_e7ODNPnPD_8Wztp4hg-LTkuj2skWNXYES6Z-GvU_iZyNFGavWKSSlvpPXgcAsffgc-z7E1rV7X8wW8p0vdsjZYaKsiHBZCXqDwIHE3FiC5ybRlWIn9W8KHqUAzYjjAufc8SdteV5WN3jsecnYNdjWgacW_RKw9uZngkFeyCDBS9OGvc-Nv6vmFP2BA87qB-gIPCHgtvLMrgMrMiUl76HOtf0bMTeOmQOl4v3LmaffRF2SdoPML_QBbNkwWpqQ9-uK2BzTzLDAfkm2UZQ",
            "widthPx": 4000
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Zahra Hajihasani",
                    "photoUri": "https://lh3.googleusercontent.com/a/ACg8ocI3sZu8KL1rtNrKfLh59vMwevHl4NsVmDZMsNiocUFVL1FycWWg=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/114410852387056434518"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgIDpz_DZCQ&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgIDpz_DZCQ!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 4000,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHqe5e-rWKI7i38TxQfP42UliimJ7ztPw6ls6XxhD4X54MK3x4tDlQgePvbky5PL_r0_dl0bTdoe6CoUIQkWDK3yTvMkH8mNYaDsm4xFHP_E6qyanP_c6tnReAK7I95uz-Rb49kztK8LmudG_VZyfKnt-y8tRMFhfYc_Nq-ClQD-J0QDFWBsFzjIm2W0qZBCn3oe-X1Dc6IJyH9src05zMw30QP8KQ7ZW0ikekLgPULSKvcD5T79cI2UzK00CgqELtAxv--9WgSw4CN1xqGH01jCsET9KJmEbkQa8AaqJjoLO3IGx4xzZV_ZEEQfWN0IpFdZMUYutst7erHTPU_Bn-hZk7q3dQmH-WfAdnOEpNtHy7H6hFUUYLP_lDVkPwENs6rdguqynLG8UXe3npDjbCCP0Al2Fx_QsVcRANQczJ8Evg",
            "widthPx": 3000
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Rush Studio",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXI0cdkKh5TqTpxlLj3UgqlDA7E6F8Mde-MssH46Lvwu9BfujA=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/115242445637813505396"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIABIhAXYMS0JurhsT_AWledSD8G&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIABIhAXYMS0JurhsT_AWledSD8G!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 4000,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHrtov3nlwNo6OeSLRiG6Qz5alzYvGLht5UzwrNoTXptxrhkm4iQwDjXETRuhUPLIMcdGgFx3GvD7aa7wKRrPvmbh5yzA5tekX3UpHwJWA1cu-aZly-w8izyMJnJNPGGCrEBQQtaa1mHAZe7YJCzzB0CrKFIu4NaXYzDqZ0FUbEl3zWKogbUIuPwIDJ3AW79WIfgGSVXTzJrYMPapGlzXCa0-gHJ3j0eyY3iAye_WFedvgD0gK4HLspvnHj9HhQHNRaTa5wRmYULc2vpAh_iIxwr_VCq2CmK3OoSkmBjKLgZzGJh4mqdLJ6PSjZMwkNHpx-0HxXcbaaNhX52l3A4BeunHnnxvTbxDSw_7tVk7TZi-nYgaUWqgT0NL2Te0NC5sMEA0OZJqGrtjVBZda5TN6QfbZylFyh7aRF5PVB3dxG5UruAmB66_4NzqreurM13",
            "widthPx": 3000
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Shervin Arianfard",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjV-9oVSQj30RJgtroRXJg0Hwmcy_mdsk2wGnW37BbfZQvy8LMooqQ=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/116470574284526501290"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgICltfCrew&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgICltfCrew!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 2736,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHqyaeCaNn6Iv1swFaOfLhFA8LrKXN5asjsQYjDzYrzvidD5p9OunSOKU0ncQ00HPtSGG5NuaxAb5oCd7q4PhUyLkPpLJddShSFc1Enn9K6VQT1iG9RS7I0odWwLRM91fWzdhPnsXwra0NUvKCU7AQLQuCxtlh5zJnOxPSSCY52w0qabjk0oXxGDSgsTZ7c8i-eJF-GiRcjDDnVA9q52_okjRpgdu118twbxBRG81cEMpGxFgRfzRd7Mlp3KCg-LuEySOzZXka5sFibyWlrCrZr-O20PMMdA9lIh0VnK0RXs8C9iuu-fEVtDWWEXmEb7SCrLlL8cPCXnmAuRnjOnbN8mb9nmPe0Pbv58MvfDJwnZXtIQOiyNo9zEDL8RPVEJAXHjZXfqV_Mb-cClRejOHn4E7OpaJfQzM42xw-9FQwQ",
            "widthPx": 3648
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Erfan Yoosefian",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjVGdcaJKYmObwGQgfkR-c8D7Bgh3OMR8EicCUdNbt3fA9UKBJE=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/108378272955944977609"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgICH1ci5Qg&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgICH1ci5Qg!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 4000,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHq_FHNbRJ9HLa5_XgFFwO_9NUcZJ1pP6GXksCuromEqrJfb_iXlmdlii9iIz6PJ3-nlwC7W15I6XWsTRQWrHhFAR-kihbojdLSD4mH14_hVz_fpJaif7e46bIg1XvUR0Y1AN00B5_h-QF86u5x75iv4yFwDWTxIVRCphOxf1SMD-XpOoxxTdehvJhSyNCIvw5ZhU26kXone4LtKJRmj2B8E4JTDGvteFLrQfYIzpgTclwYICeTk689pZ_ybo5spW4t3kFVVwOx1WnX6lKIrN3d2_nDV4Qnw6YrE1w_4WHoL11Qd7bZ6QLtFyFrXtOF7iOlRfsmFNAoYoUylOefRnCb86-W-_JKbT9thaVYaXaL4yFgYCyyIF3NbUH7lw3pemr8OWHvxERh3YSc68BVad__xJgfp5PGsFOeehjZBm4eOEw",
            "widthPx": 3000
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Hamed Habiba",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXerFqMSNDNiLUXw2vB6q5k3VfCXyHbglUFPULcwXxg4AahzOwe=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/110974566486300880886"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgID1m7XDrQE&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgID1m7XDrQE!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 4032,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHrKlOFPL7-oXp7w7lxOQm-LtrOQ-_TKzKwWjGWQw_KV2rTcMSwOWK4Wm_o8d7lX2D9KNOIGrl7r2VsHXkvokPJipcyiKdVhpsBk1N_r3e7ElPLCGTIzMZ72pMd3Skk5f2X1PO0YWayX9U-rOrSboeuZf3YIo3u0Sy8YCVbQ3QGx_uk46useXRzCn4gJO3cshcqeBz7Rj187S7arJ745L3-weFCnWTCcrJ4Zs70tjICYpolSXOA3bHY9Zbhtq_kEcsfVIHToZHxQAT_U93930i2uuzc4Gl938kSfxwd57RNveKsIX0epLwtCet0i9V1XViO5TFV5mpRYCg_FgXq2K1DjA2H8jlFrsXRK4GJkmLYH2aIk4GdzssFGlV6ewn0Uihtm-uWBWRrVWdN1lp5E5Nea2C_ghjg8_z_CO37RRLbjyrHB",
            "widthPx": 3024
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Abozar Raghibdoust",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXIV1RxOhfNeBhGzwmUeybtxL_Wg9szNPKp-4ICyC03JcyFz6JF=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/101247290872101237676"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgICy2-LX9gE&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgICy2-LX9gE!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 720,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHojkafnE-8eA0rt2yu_jlcYsxOCHHt41yUXk5hwnDaMmacCQoNQHe8MLS5aGpNJIJzzLFaqtUGNBqo1_RWd6HvFYow59lY5wx3lLMzVxdB0IWdPxPAV6kNYmMd_-LDvGj4diaICsgf6l4BMOepjbf2z3tTA35crTIU2lKqQpLLF6EhZa1rYMPqFlr1YraDJi9nXzCMB-PPDqQq2IS4ffv0n9XR-DF-UDEzs06NEllPK9LaDbmKOi2qnaZeyxDz6mlUeVMNugar1Lbt2WDHbeKPlDb25dkjojsord0ADbvkhP_6AZVrN0Dw0Qt0bJN4riaEgMM3SZJj0ZkYKdm_8xxN3sS0aGsTmDjkwQlkfCMEsGpC8gezbY6zu8hstPbTTL7CFj4PfsD8Ml32xFqn7FtcyLSkVgdIt7TkhDCWTKWLLreXf",
            "widthPx": 1026
        },
        {
            "authorAttributions": [
                {
                    "displayName": "sala majidi",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjWZJdLAcsgpM13Gi_32NXx5QoUGv8dH5dj5V6sT_Bx1xaSCfAGqJA=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/102543273742354145072"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgIDWgsTMKQ&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgIDWgsTMKQ!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 1920,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHpYtLZODRRvdXUhRfmYFlECNfz7GknnkHkyx0aC6voikJ_8PR7qpgAGSbWbP8RLURBXoNqA8FAbuSaxrjMd4yqH8GSkIjbpwwAa3BowJCSSk6c3B33rTiMm9dRG0S0xhUu2mMxDfahwNOXW3Xmk429pdFlu1VcgTRY7f76g4awdH1WhYm4CnyKA3WKlJzS1Hkpnw98BOOhzpapqjvuqCmNPe63UG_rrYHsEGqMYp3idJPPBXcreqx1Xg8FrEkNi_RLUX3RiklFFzPXwQnuk7AGWnyGPqwk7XleuSIC_HxgQU4iyss5m-NhUr9nIvf3Cpko7uIBEjuINkr5k0PoQIot5dBXdDCvBGQEtXsmFmFuFFlvgyqmIStyvqK-8xar4WfDPQmyvvRp0uh0Xna0thrg1m3wXvPRL66HjXi2vBVA",
            "widthPx": 1080
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Majid Noori",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjUUH3pYtBGUdoLmuIopUR8Yu3Cj3tzEdU6U9z91aNK9PfMe14io=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/117866817599271755012"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgIDX66KHvQE&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgIDX66KHvQE!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 4800,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHqH1ggSSt0exRt5GWJ7zWglkg_NNc5QJUBlF_2wTmXAVACFxB73SsTwXq4vUssWZm9lia8fvsvww10ptE55p1k-03HA-I8YA12nttcTP9BpD5jWtVFBSlCQ5tqBDzynQE7vZgQ6RJa1RZ1-wIfG6G_FJ29-pI_zafZPEmLVE7npBXH3XF7DcNKlCtX_G2lbeWZd5GQXffGHUjA_TgWfhs2WEpg-X6zv879O_XEvLgq5iC7yAqcICZbP_iKBZfUcZ1jM2Jhdo5wgY8sV91yJ9rgtLt3j2uug6wTPTjLN-H4HHTYnvY4bOfM3KKkjpZOBAQrVi5--OX-bGzm4K30jLkErvst8t1yWQAybxkrWn7IBh_2ZA-ESmG6k8drayizzXIzwhMdeLR_qL40tuVQZog0drO1sabzNkB-waTh0GC3Rkho",
            "widthPx": 3600
        },
        {
            "authorAttributions": [
                {
                    "displayName": "Zahra Hajihasani",
                    "photoUri": "https://lh3.googleusercontent.com/a/ACg8ocI3sZu8KL1rtNrKfLh59vMwevHl4NsVmDZMsNiocUFVL1FycWWg=s100-p-k-no-mo",
                    "uri": "https://maps.google.com/maps/contrib/114410852387056434518"
                }
            ],
            "flagContentUri": "https://www.google.com/local/imagery/report/?cb_client=maps_api_places.places_api&image_key=!1e10!2sCIHM0ogKEICAgIDpz_DtQQ&hl=en-US",
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgIDpz_DtQQ!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 4000,
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/photos/AZLasHqfA2YIm3DrFPsGF5HSR4MFDScvBLFLmt0eIAHDkZvaYZr0cFXIjHCktZQOrPiQ79u2owS89XWsa2JDxbLgW52MNgVh2K1jimn8CGBjm-bscD9k4V8ChyUigjdhKjZwt90diHVYAFp32H7srKBDI4_tcpP5y7jHoZdS4H9_cjAkvLJqBgbFrzD7BqobRjrCwHuKqwBnDnBCPupl5a77B3bx9DGs6jL-k2jithJR8StGvvhkyXq94DgNLgSU7s9Nn3gyX0OxDx9aAWU20Lo1_rui7_YG-3YF47AvzdBIneym6Wb2o_ChDMg_TtWhTmV3p57LRAzqFkp4tsLBFfhMfgaO199CN-PJEVDIHTJJ-r0yONhLfW7zklU7LTLx3iI4gXQ7EFxan-bRo8OkG7TkmK7FTo6QZm_YwV4djBaomKz5KQ",
            "widthPx": 3000
        }
    ],
    "postalAddress": {
        "addressLines": [
            "Milad Tower Rd",
            "P9VG+X6 Milad Tower"
        ],
        "administrativeArea": "Tehran Province",
        "languageCode": "en-US",
        "locality": "Tehran",
        "regionCode": "IR",
        "sublocality": "District 2"
    },
    "priceRange": {
        "startPrice": {
            "currencyCode": "IRR",
            "units": "10000000"
        }
    },
    "primaryType": "restaurant",
    "primaryTypeDisplayName": {
        "languageCode": "en-US",
        "text": "Restaurant"
    },
    "rating": 3.3,
    "regularOpeningHours": {
        "nextCloseTime": "2025-12-07T15:30:00Z",
        "openNow": true,
        "periods": [
            {
                "close": {
                    "day": 0,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "day": 0,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 1,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "day": 0,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "day": 1,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "day": 1,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 2,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "day": 1,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "day": 2,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "day": 2,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 3,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "day": 2,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "day": 3,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "day": 3,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 4,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "day": 3,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "day": 4,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "day": 4,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 5,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "day": 4,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "day": 5,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "day": 5,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 6,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "day": 5,
                    "hour": 19,
                    "minute": 30
                }
            },
            {
                "close": {
                    "day": 6,
                    "hour": 19,
                    "minute": 0
                },
                "open": {
                    "day": 6,
                    "hour": 8,
                    "minute": 0
                }
            },
            {
                "close": {
                    "day": 0,
                    "hour": 0,
                    "minute": 55
                },
                "open": {
                    "day": 6,
                    "hour": 19,
                    "minute": 30
                }
            }
        ],
        "weekdayDescriptions": [
            "Monday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Tuesday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Wednesday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Thursday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Friday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Saturday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM",
            "Sunday: 8:00 AM – 7:00 PM, 7:30 PM – 12:55 AM"
        ]
    },
    "reservable": true,
    "restroom": true,
    "reviews": [
        {
            "authorAttribution": {
                "displayName": "Reza Sattarzadeh Nowbari",
                "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjWQTNM9Yrnnrdvd6cbMZJUu3jwDLkVlrdQUnPl6LmfxSKphkTY=s128-c0x00000000-cc-rp-mo-ba7",
                "uri": "https://www.google.com/maps/contrib/100615538772769699069/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=Ci9DQUlRQUNvZENodHljRjlvT2pKTFJUQlBXRVpGV0daVlYzTlNNV0V6UXpKbVIwRRAB&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2pKTFJUQlBXRVpGV0daVlYzTlNNV0V6UXpKbVIwRRAB!2m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/reviews/Ci9DQUlRQUNvZENodHljRjlvT2pKTFJUQlBXRVpGV0daVlYzTlNNV0V6UXpKbVIwRRAB",
            "originalText": {
                "languageCode": "en",
                "text": "The only good things about this restaurant is the fact that it is revolving and gives you the experience of a 360-degree view of the capital as you have your meal. For 2 million tomans per person (in November 2025), you will have access to a buffet of mainly Irania dishes. The food is meh at best, so do not expect a fine dining experience. As for the service, the staff are finely mannered and polite. As for management, there seems to be a serious flaws in organising the place. First, the titles on the food trays do not match the food presented, so it seems that they just put the titles, so that there is something there. Second, the drinks are kept in a not cool place and you are forced to use ice. And if for some reason you are not OK with ice in your drink, you are forced to have lukewarm drinks.\n\nOverall, for the overpriced entry fee, you can enjoy the atmosphere but there is no wow element with the food, or the way it is presented."
            },
            "publishTime": "2025-11-27T15:07:39.506169867Z",
            "rating": 3,
            "relativePublishTimeDescription": "a week ago",
            "text": {
                "languageCode": "en",
                "text": "The only good things about this restaurant is the fact that it is revolving and gives you the experience of a 360-degree view of the capital as you have your meal. For 2 million tomans per person (in November 2025), you will have access to a buffet of mainly Irania dishes. The food is meh at best, so do not expect a fine dining experience. As for the service, the staff are finely mannered and polite. As for management, there seems to be a serious flaws in organising the place. First, the titles on the food trays do not match the food presented, so it seems that they just put the titles, so that there is something there. Second, the drinks are kept in a not cool place and you are forced to use ice. And if for some reason you are not OK with ice in your drink, you are forced to have lukewarm drinks.\n\nOverall, for the overpriced entry fee, you can enjoy the atmosphere but there is no wow element with the food, or the way it is presented."
            }
        },
        {
            "authorAttribution": {
                "displayName": "Hamed Habiba",
                "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXerFqMSNDNiLUXw2vB6q5k3VfCXyHbglUFPULcwXxg4AahzOwe=s128-c0x00000000-cc-rp-mo-ba3",
                "uri": "https://www.google.com/maps/contrib/110974566486300880886/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=ChdDSUhNMG9nS0VJQ0FnSUQxbTdYRGpRRRAB&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChdDSUhNMG9nS0VJQ0FnSUQxbTdYRGpRRRAB!2m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/reviews/ChdDSUhNMG9nS0VJQ0FnSUQxbTdYRGpRRRAB",
            "originalText": {
                "languageCode": "en",
                "text": "The food it’s awful. The windows are not clean enough. There is no live music and there are only maybe 7-8 foods on the menu and they are all kebabs. The buffet only has soup and salad. Overall it’s better to get the ticket and just enjoy the view rather than using the restaurant."
            },
            "publishTime": "2024-01-10T10:43:58.170117Z",
            "rating": 1,
            "relativePublishTimeDescription": "a year ago",
            "text": {
                "languageCode": "en",
                "text": "The food it’s awful. The windows are not clean enough. There is no live music and there are only maybe 7-8 foods on the menu and they are all kebabs. The buffet only has soup and salad. Overall it’s better to get the ticket and just enjoy the view rather than using the restaurant."
            }
        },
        {
            "authorAttribution": {
                "displayName": "Abozar Raghibdoust",
                "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXIV1RxOhfNeBhGzwmUeybtxL_Wg9szNPKp-4ICyC03JcyFz6JF=s128-c0x00000000-cc-rp-mo-ba2",
                "uri": "https://www.google.com/maps/contrib/101247290872101237676/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=ChdDSUhNMG9nS0VJQ0FnSUN5MjZLTW13RRAB&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChdDSUhNMG9nS0VJQ0FnSUN5MjZLTW13RRAB!2m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/reviews/ChdDSUhNMG9nS0VJQ0FnSUN5MjZLTW13RRAB",
            "originalText": {
                "languageCode": "en",
                "text": "Tehran 360 restaurant is located in Milad tower. You can see tehran from sky with 273 meter height. Good views, seats near windows turn around with restaurant. For launch you have various choices, but some items were not fresh. The Broad Bean cooked rice with meat was delicious but the meat could be cooked better. Maybe the reason that the meat was not cooked well is that height the food is cooked with electricity. Good quality of service and impressive view of lovely Tehran make me to come here again."
            },
            "publishTime": "2021-03-23T11:35:35.830852Z",
            "rating": 4,
            "relativePublishTimeDescription": "4 years ago",
            "text": {
                "languageCode": "en",
                "text": "Tehran 360 restaurant is located in Milad tower. You can see tehran from sky with 273 meter height. Good views, seats near windows turn around with restaurant. For launch you have various choices, but some items were not fresh. The Broad Bean cooked rice with meat was delicious but the meat could be cooked better. Maybe the reason that the meat was not cooked well is that height the food is cooked with electricity. Good quality of service and impressive view of lovely Tehran make me to come here again."
            }
        },
        {
            "authorAttribution": {
                "displayName": "Hamid Rahimpour",
                "photoUri": "https://lh3.googleusercontent.com/a/ACg8ocJGWXmwznxfSwMXoa_s3O6TlETUFZC0J4S2d_AIiKRIr6n8ocA=s128-c0x00000000-cc-rp-mo-ba4",
                "uri": "https://www.google.com/maps/contrib/114787142984784891601/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=ChZDSUhNMG9nS0VJQ0FnSURtOEstSFF3EAE&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnSURtOEstSFF3EAE!2m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/reviews/ChZDSUhNMG9nS0VJQ0FnSURtOEstSFF3EAE",
            "originalText": {
                "languageCode": "en",
                "text": "Tehran 360 Restaurant is located in Milad tower. Watching Tehran from a height of 276 meters was an interesting and exciting experience. Inside atmosphere of restaurant was calm,\nbut\n❌The lighting and ❌interior decoration was nothing special to me.\n\n❌The lighting was poor. The lighting was not suitable for photography.\n\n❌The furniture was worn out.\n\n❌Services was poor.\n\n❌ food  quality was average but in some cases it was even surprising.\n\n❌The price was high and expensive compared to the level of service and  food quality.\n\nstaff behavior was appropriate.\n\n✔Overall not recommended❗"
            },
            "publishTime": "2022-01-17T06:10:08.455444Z",
            "rating": 2,
            "relativePublishTimeDescription": "3 years ago",
            "text": {
                "languageCode": "en",
                "text": "Tehran 360 Restaurant is located in Milad tower. Watching Tehran from a height of 276 meters was an interesting and exciting experience. Inside atmosphere of restaurant was calm,\nbut\n❌The lighting and ❌interior decoration was nothing special to me.\n\n❌The lighting was poor. The lighting was not suitable for photography.\n\n❌The furniture was worn out.\n\n❌Services was poor.\n\n❌ food  quality was average but in some cases it was even surprising.\n\n❌The price was high and expensive compared to the level of service and  food quality.\n\nstaff behavior was appropriate.\n\n✔Overall not recommended❗"
            }
        },
        {
            "authorAttribution": {
                "displayName": "Nika",
                "photoUri": "https://lh3.googleusercontent.com/a/ACg8ocLG13CjiPL6WTzQCudD4e21wwl0vmo2eHRf3m5yibB_51P4Iw=s128-c0x00000000-cc-rp-mo-ba2",
                "uri": "https://www.google.com/maps/contrib/109551821615781398669/reviews"
            },
            "flagContentUri": "https://www.google.com/local/review/rap/report?postId=ChZDSUhNMG9nS0VJQ0FnTUNBMWRiR01REAE&d=17924085&t=1",
            "googleMapsUri": "https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnTUNBMWRiR01REAE!2m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "name": "places/ChIJieDYMxEHjj8RnkjXgC8Wy7E/reviews/ChZDSUhNMG9nS0VJQ0FnTUNBMWRiR01REAE",
            "originalText": {
                "languageCode": "en",
                "text": "If you want to experience the absolute worst restaurant experience  in a country as a tourist, this is the please to go. We had extremely high expectations before coming to the restaurant at top of the beautiful Milad tower but was met with absolute disappointment. Outdated, old and cheap interior and lighting. Did not seem clean or hygienic at all. Kids and people run around like its a mcdonalds and the food is not tasteful and served in a prisonlike manner. No decorations or effort to make it an atmospheric place. The view is almost not visible due to dirty Windows. The staff make you pay on the ground floor before entering the place because they know how horrible the place is and the cost of it is unreasonably expensive. Not even dessert or bottle/cans of soda was derved. This should be one of Tehrans prides, its the opposite, absolute shame. So much potential just thrown away. Do not go here! Absolutley do not recommend it at all."
            },
            "publishTime": "2025-02-02T20:59:59.152679Z",
            "rating": 1,
            "relativePublishTimeDescription": "10 months ago",
            "text": {
                "languageCode": "en",
                "text": "If you want to experience the absolute worst restaurant experience  in a country as a tourist, this is the please to go. We had extremely high expectations before coming to the restaurant at top of the beautiful Milad tower but was met with absolute disappointment. Outdated, old and cheap interior and lighting. Did not seem clean or hygienic at all. Kids and people run around like its a mcdonalds and the food is not tasteful and served in a prisonlike manner. No decorations or effort to make it an atmospheric place. The view is almost not visible due to dirty Windows. The staff make you pay on the ground floor before entering the place because they know how horrible the place is and the cost of it is unreasonably expensive. Not even dessert or bottle/cans of soda was derved. This should be one of Tehrans prides, its the opposite, absolute shame. So much potential just thrown away. Do not go here! Absolutley do not recommend it at all."
            }
        }
    ],
    "servesBreakfast": true,
    "servesBrunch": true,
    "servesCoffee": true,
    "servesDessert": true,
    "servesDinner": true,
    "servesLunch": true,
    "shortFormattedAddress": "Tehran, District 2, Milad Tower Rd, P9VG+X6 Milad Tower",
    "takeout": true,
    "timeZone": {
        "id": "Asia/Tehran"
    },
    "types": [
        "breakfast_restaurant",
        "restaurant",
        "food",
        "point_of_interest",
        "establishment"
    ],
    "userRatingCount": 414,
    "utcOffsetMinutes": 210,
    "viewport": {
        "high": {
            "latitude": 35.7462355302915,
            "longitude": 51.376374730291495
        },
        "low": {
            "latitude": 35.7435375697085,
            "longitude": 51.373676769708496
        }
    },
    "websiteUri": "https://instagram.com/tehran360restaurant",
    "timestamp": 1765101033
}
</pre>
</div>
</details><br><br>




---


## 🔹 قابلیت‌ها و ویژگی‌ها
- استخراج تمام فیلدهای **Place Details**
- خروجی کاملاً **یکسان با API رسمی گوگل**
- بدون محدودیت جغرافیایی
- پشتیبانی از تمامی انواع مکان‌ها:
  - رستوران، داروخانه، کافه، آرایشگاه، طلافروشی، سوپرمارکت و …
- استخراج **ساعات کاری هفتگی** و وضعیت باز/بسته فعلی
- استخراج **5 نظر آخر کاربران**
- استخراج **10 عکس اصلی باکیفیت مکان**
- پشتیبانی از خروجی در فرمت‌های مختلف: JSON, CSV, Excel, SQL و …

---

## درخواست‌های داده سفارشی

علاوه بر استخراج داده‌های خام، امکان **پردازش و تبدیل سفارشی داده‌ها** بر اساس نیاز شما نیز فراهم است.

این خدمات شامل موارد زیر می‌شود:
- پاک‌سازی و بازساختاردهی داده‌های خام
- فیلتر کردن یا تجمیع ویژگی‌ها و فیلدهای مشخص
- تبدیل خروجی‌ها به هر قالب درخواستی (JSON، CSV، GeoJSON، SQL و …)

---

## 🔹 تماس با من
- **Telegram:** [t.me/parhamkhani](https://t.me/parhamkhani)  
- **Email:** parhamkhani.ir@gmail.com
