## Overview
The **Nashville-Residential-Parcel-Transaction-Price-2000-2022** dataset provides information on residential parcel transactions in Nashville, Tennessee, spanning the years **2000 through 2022**.  

It contains parcel-level transaction records including sale prices, property characteristics, location details, and assessed values. 

---
## File Information
- **File name:** `nashville_housing_data.csv` 
- **Coverage:** Davidson County (Nashville), Tennessee  
- **Time span:** January 2000 – September 2022  
- **Unit of observation:** Individual residential property transaction  

---

## Variables
| Variable        | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| `SalePrice`     | Sale price of the property (USD).                                           |
| `SaleDate`      | Date of the recorded sale (YYYY-MM-DD).                                     |
| `Acres`         | Lot size in acres.                                                          |
| `LUDesc`        | Land use description (e.g., single-family, condo, duplex).                  |
| `FinishArea`    | Finished area of the property (square feet).                                |
| `PropDate`      | Date when the property record was created or updated (YYYY-MM-DD).          |
| `PropZip`       | ZIP code of the property.                                                   |
| `CensusTract`   | Census tract identifier (for demographic linkage).                          |
| `CouncilDistrict` | Nashville Metro Council district number.                                  |
| `PropAddr`      | Street address of the property.                                             |
| `PropCity`      | City where the property is located (typically Nashville).                   |
| `PropState`     | State abbreviation of property location (TN).                               |
| `OwnCity`       | Owner’s mailing city.                                                       |
| `OwnState`      | Owner’s mailing state.                                                      |
| `OwnCountry`    | Owner’s mailing country.                                                    |
| `OwnZip`        | Owner’s mailing ZIP code.                                                   |
| `LandAppr`      | Appraised land value (USD).                                                 |
| `ImprAppr`      | Appraised improvement (building) value (USD).                               |
| `TotlAppr`      | Total appraised value (land + improvements) (USD).                          |
| `LandAssd`      | Assessed land value for taxation (USD).                                     |
| `ImprAssd`      | Assessed improvement value for taxation (USD).                              |
| `TotlAssd`      | Total assessed value (land + improvements) for taxation (USD).              |

---

## Notes
- **Currency:** All monetary values are in **nominal USD** (not inflation-adjusted).  
- **SaleDate vs. PropDate:** `SaleDate` refers to the transaction date; `PropDate` may reflect administrative record entry or update.  
- **Coverage limitations:** The dataset includes **residential parcels only**; commercial and industrial properties are excluded.  
- **Missing values:** Some variables (e.g., `FinishArea`, `Acres`) may be missing if not reported.  

---
