# 01 · Raw Dataset

The original files. **Do not edit them**; save every change into `02_Cleaned_Dataset/`.

| File | Rows | One row = | Use it for |
|---|---|---|---|
| `city_day.csv` | 6,279 | city × day | **Main file.** 10 cities, 1 Jan 2015 – 31 Dec 2016 |
| `station_day.csv` | 17,182 | station × day | Station-level drill-down (29 stations) |
| `stations.csv` | 29 | station | Lookup: StationId → name, city, state, status |
| `delhi_hour.csv` | 17,543 | hour (Delhi only) | Hour-of-day patterns and the Diwali-night spike |

Columns in the readings files: `City` or `StationId`, `Date` (or `Datetime`), 12 pollutants (`PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene`), `AQI`, `AQI_Bucket`.

All four files fit in one Google Sheets workbook as four tabs (File → Import → Upload → *Insert new sheet(s)*).
