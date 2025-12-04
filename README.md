# RecordGo Rentacar Scraper
>This scraper gathers live rental car prices and availability from the RecordGo Rent a Car website. It automates the search process, letting you compare costs, track seasonal trends, and analyze vehicle categories without manually browsing the site. If you're researching rental markets or planning a trip, this tool delivers clean, ready-to-use pricing data.

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>RecordGo Rentacar Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The RecordGo Rentacar Scraper extracts structured rental options based on your pickup and dropoff locations, dates, and times. It’s designed for travelers, analysts, and teams working on travel-tech applications who need real-time pricing and availability data across multiple RecordGo locations.

### What It Helps You Do
- Compare rental rates across dates, cities, or airports.  
- Capture vehicle availability and categories in real time.  
- Automate large-scale pricing research without repetitive manual checks.  
- Export clean datasets for travel dashboards or market models.

---
## Features
| Feature | Description |
|---------|-------------|
| Location-Based Search | Pulls pricing and car options for selected pickup and dropoff locations. |
| Real-Time Pricing | Returns current rental prices for specified dates and times. |
| Vehicle Details Extraction | Collects transmission, seats, doors, luggage space, fuel type, and category. |
| Structured Output | Provides JSON, CSV, or Excel-ready data formats. |
| Automated Scraping | Eliminates manual data collection across multiple date ranges. |
| Proxy Support | Optionally uses proxy rotation for more stable runs. |
| Flexible Limits | Allows max-results customization for focused queries. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| carName | Name or model of the rental car. |
| category | Vehicle classification (e.g., economy, SUV). |
| transmission | Manual or automatic transmission type. |
| seats | Number of seats available. |
| doors | Number of doors. |
| luggage | Luggage capacity rating. |
| fuelType | Fuel type supported by the vehicle. |
| priceDaily | Daily rental price. |
| priceTotal | Total rental cost for the full duration. |
| currency | Currency of the displayed price. |
| imageUrl | Link to the vehicle image. |
| features | List of vehicle features or amenities. |
| pickupLocation | Selected pickup location. |
| dropoffLocation | Selected dropoff location. |
| pickupDate | Retrieval date. |
| dropoffDate | Return date. |
| duration | Rental duration in days or hours. |
| timestamp | Time when the data was scraped. |

---
## Example Output
    
    [
      {
        "carName": "Ford Fiesta",
        "category": "Economy",
        "transmission": "Manual",
        "seats": 5,
        "doors": 4,
        "luggage": "2 small bags",
        "fuelType": "Petrol",
        "priceDaily": 22.5,
        "priceTotal": 90.0,
        "currency": "EUR",
        "imageUrl": "https://recordgo.com/images/fiesta.jpg",
        "features": ["Air Conditioning", "ABS", "Bluetooth"],
        "pickupLocation": "Madrid Airport",
        "dropoffLocation": "Madrid Airport",
        "pickupDate": "2024-06-15",
        "dropoffDate": "2024-06-19",
        "duration": "4 days",
        "timestamp": "2024-05-01T10:14:55Z"
      }
    ]

---
## Directory Structure Tree
    
    RecordGo Rentacar Scraper/
    ├── src/
    │   ├── main.js
    │   ├── scraper/
    │   │   ├── search_runner.js
    │   │   ├── results_parser.js
    │   │   └── proxy_handler.js
    │   ├── utils/
    │   │   ├── date_formatter.js
    │   │   └── output_normalizer.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Travelers** compare rental prices across multiple airports and dates to find the best deal.  
- **Travel-tech developers** feed real-time rental data into booking engines or comparison tools.  
- **Market researchers** analyze seasonal pricing patterns and fleet availability.  
- **Agencies** automate reporting on rental car trends for business forecasting.  
- **Pricing analysts** monitor fluctuations in daily or weekly rental rates.

---
## FAQs

**Does it support different pickup and dropoff locations?**  
Yes, you can specify unique locations for each.

**Is proxy support included?**  
Yes, optional proxy settings improve stability, especially for high-volume scraping.

**What data formats does it support?**  
You can export results as JSON, CSV, or Excel.

**Does it show real-time prices?**  
Yes, all pricing and availability data reflect the live results at scraping time.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Extracts live rental options in seconds per search session, depending on site load.

**Reliability Metric:**  
Maintains a success rate above 95% with proper proxy configuration and stable selectors.

**Efficiency Metric:**  
Optimized parsing enables smooth operation even when scraping multiple date ranges.

**Quality Metric:**  
Produces complete and consistent rental data, including pricing, features, and duration calculations.

---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>

