# Google Maps Scraper v3 (FA)

 یک ابزار برای استخراج **دقیق** و **جامع اطلاعات مکان‌ها از Google Maps** است. این ابزار قادر است **جزئیات کامل هر مکان** را جمع‌آوری کند؛ شامل **نام، نوع، آدرس دقیق، موقعیت جغرافیایی، شماره تماس بین‌المللی و محلی، ساعات کاری، امتیاز کاربران، ویژگی‌های خدماتی** و سایر مشخصات مرتبط. **خروجی تولید شده توسط این ابزار کاملاً مطابق با API رسمی گوگل** است و می‌تواند به عنوان **منبعی دقیق برای تحلیل داده‌های مکانی یا توسعه نرم‌افزارهای مرتبط** مورد استفاده قرار گیرد.

هدف این ریپوزیتوری، **نشان دادن توانایی‌های این ابزار** و ارائه یک **نمونه از نحوه استخراج داده‌های مکان‌ها** است. در صورتی که به **داده‌های مکانی خاصی** نیاز دارید، می‌توانید با من تماس بگیرید تا **استخراج سفارشی** انجام شود، بدون آنکه **محدودیت جغرافیایی یا نوع مکان** وجود داشته باشد.


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
    "id": "ChIJieDYMxEHjj8RnkjXgC8Wy7E",
    "name": "Tehran 360 Restaurant",
    "primaryType": "restaurant",
    "primaryTypeDisplayName": "Restaurant",
    "types": [
        "breakfast_restaurant",
        "restaurant",
        "food",
        "point_of_interest",
        "establishment"
    ],
    "formattedAddress": "Tehran Province, Tehran, District 2, Milad Tower Rd, P9VG+X6 Milad Tower, Iran",
    "location": {
        "latitude": 35.7447707,
        "longitude": 51.3755592
    },
    "googleMapsUri": "https://maps.google.com/?cid=12811357958266374302",
    "websiteUri": "https://instagram.com/tehran360restaurant",
    "internationalPhoneNumber": "+98 21 8862 0381",
    "nationalPhoneNumber": "021 8862 0381",
    "rating": 3.3,
    "userRatingCount": 414,
    "priceRange": {
        "startPrice": {
            "currencyCode": "IRR",
            "units": "10000000"
        }
    },
    "currentOpeningHours": {
        "openNow": true,
        "nextCloseTime": "2025-12-07T15:30:00Z",
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
    "features": {
        "dineIn": true,
        "takeout": true,
        "reservable": true,
        "servesBreakfast": true,
        "servesBrunch": true,
        "servesLunch": true,
        "servesDinner": true,
        "servesDessert": true,
        "servesCoffee": true,
        "liveMusic": true,
        "restroom": true,
        "goodForChildren": true,
        "goodForGroups": true
    },
    "accessibility": {
        "wheelchairAccessibleEntrance": true,
        "wheelchairAccessibleParking": true,
        "wheelchairAccessibleRestroom": true,
        "wheelchairAccessibleSeating": true
    },
    "parkingOptions": {
        "freeParkingLot": true,
        "paidParkingLot": true,
        "paidGarageParking": true
    },
    "paymentOptions": {
        "acceptsCreditCards": true,
        "acceptsDebitCards": true,
        "acceptsCashOnly": false
    },
    "photos": [
        {
            "authorAttributions": [
                {
                    "displayName": "Hooman",
                    "photoUri": "https://lh3.googleusercontent.com/a-/ALV-UjXZfu9lCNIl44XR4H4Q3bKqzZjY8hXP8Lf5mz80yA3QMZbgEwwH5Q=s100-p-k-no-mo"
                }
            ],
            "googleMapsUri": "https://www.google.com/maps/place//data=!3m4!1e2!3m2!1sCIHM0ogKEICAgID-ooeNcQ!2e10!4m2!3m1!1s0x3f8e071133d8e089:0xb1cb162f80d7489e",
            "heightPx": 3000,
            "widthPx": 4000
        }
        // ... سایر عکس‌ها به طور خلاصه
    ],
    "reviews": [
        {
            "authorAttribution": {
                "displayName": "Reza Sattarzadeh Nowbari"
            },
            "rating": 3,
            "text": "The only good things about this restaurant is the fact that it is revolving and gives you the experience of a 360-degree view...",
            "relativePublishTimeDescription": "a week ago"
        }
        // ... سایر نظرات به طور خلاصه
    ],
    "addressDetails": {
        "postalAddress": {
            "addressLines": [
                "Milad Tower Rd",
                "P9VG+X6 Milad Tower"
            ],
            "locality": "Tehran",
            "administrativeArea": "Tehran Province",
            "regionCode": "IR",
            "sublocality": "District 2"
        },
        "addressComponents": [
            {
                "longText": "Milad Tower",
                "types": [
                    "premise"
                ]
            },
            {
                "longText": "Milad Tower Road",
                "types": [
                    "route"
                ]
            },
            {
                "longText": "District 2",
                "types": [
                    "sublocality_level_1",
                    "sublocality",
                    "political"
                ]
            }
            // ... سایر اجزا
        ]
    },
    "nearbyLandmarks": [
        {
            "displayName": "Milad Tower",
            "straightLineDistanceMeters": 88.14349,
            "travelDistanceMeters": 128.47746,
            "spatialRelationship": "AROUND_THE_CORNER"
        },
        {
            "displayName": "Milad Tower International Conference Center",
            "straightLineDistanceMeters": 271.27313,
            "travelDistanceMeters": 180.23926
        }
        // ... سایر نقاط نزدیک
    ],
    "containingPlaces": [
        {
            "id": "ChIJA4SR1RAHjj8ReBOEZwsp9XQ",
            "name": "places/ChIJA4SR1RAHjj8ReBOEZwsp9XQ"
        }
    ],
    "timestamp": 1765012432,
    "businessStatus": "OPERATIONAL",
    "iconBackgroundColor": "#FF9E67",
    "iconMaskBaseUri": "https://maps.gstatic.com/mapfiles/place_api/icons/v2/restaurant_pinlet",
    "viewport": {
        "high": {
            "latitude": 35.7462355302915,
            "longitude": 51.376374730291495
        },
        "low": {
            "latitude": 35.7435375697085,
            "longitude": 51.373676769708496
        }
    }
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

## 🧬 ساختار فیلدهای JSON خروجی


```
id
name
displayName
├── languageCode
└── text

formattedAddress
addressComponents
├── languageCode
├── longText
├── shortText
└── types

addressDescriptor
├── areas
│   ├── containment
│   ├── displayName
│   │   ├── languageCode
│   │   └── text
│   ├── name
│   └── placeId
└── landmarks
    ├── displayName
    │   ├── languageCode
    │   └── text
    ├── name
    ├── placeId
    ├── spatialRelationship
    ├── straightLineDistanceMeters
    ├── travelDistanceMeters
    └── types

location
├── latitude
└── longitude

googleMapsUri
googleMapsLinks
├── directionsUri
├── photosUri
├── placeUri
├── reviewsUri
└── writeAReviewUri

businessStatus

currentOpeningHours
├── nextOpenTime
├── openNow
├── periods
│   ├── close
│   │   ├── date
│   │   │   ├── day
│   │   │   ├── month
│   │   │   └── year
│   │   ├── day
│   │   ├── hour
│   │   └── minute
│   └── open
│       ├── date
│       │   ├── day
│       │   ├── month
│       │   └── year
│       ├── day
│       ├── hour
│       └── minute
└── weekdayDescriptions

internationalPhoneNumber
nationalPhoneNumber

paymentOptions
├── acceptsCashOnly
└── acceptsDebitCards

dineIn
liveMusic

iconMaskBaseUri
iconBackgroundColor

photos
├── authorAttributions
│   ├── displayName
│   ├── photoUri
│   └── uri
├── flagContentUri
├── googleMapsUri
├── heightPx
├── name
└── widthPx
```





---

## 🔹 تماس با من
- **Telegram:** [t.me/parhamkhani](https://t.me/parhamkhani)  
- **Email:** parhamkhani.ir@gmail.com
