EN | [日本語](readme.md)

# Standard Data Model
This repository manages the **Standard Data Model** for the area data coordination platform.

## Overview

This repository serves to store and manage the **Area Data Standard Data Model** designed to facilitate data sharing and interoperability across regions.

Even when dealing with identical types of data—such as "public facilities," "events," or "medical institutions"—the difficulty in comparing, reusing, and sharing data increases significantly when field names and value representations vary between organizations or sectors. This data model aims to standardize frequently reused regional datasets into reusable units, ensuring both data interoperability (interoperability) and service application portability.

## Target Domains

The repository contains standard data models for the following domains:

| Domain | Data Model |
|--------|------------|
| Public Services | Public facilities / Demographic data by age group / Firewater facilities |
| Resident Services | Users / Community points / Local currency / Public Wi-Fi access points / Public restrooms / Vacant property databases / Childcare support facilities |
| Tourism and Regional Revitalization | Events / Human mobility data / Tourist facilities / Cultural properties |
| Health and Medical Services | AED locations / Medical institutions / Long-term care service facilities |
| Transportation and Mobility | Public transportation operation information / Boarding/alighting data / Parking facilities / Bicycle parking spaces / Shared bicycle docking stations |
| Education | Schools |

## Prerequisites

- For coordinate reference systems, latitude and longitude should primarily use **JGD 2011/(B,L) (Japan Geodetic Datum 2011)**.
- Fields marked as "Required" must not be deleted even if they aren't being used (additional missing fields may be added).
- Fields labeled "Value Required" indicate whether data entry is mandatory or optional (allowing NULL values).
- When multiple data types are listed in a field, select the appropriate type based on your intended use.
- Handling of personal data must comply with the Personal Information Protection Act and other relevant laws and guidelines.

## Related Documents

- [Government Interoperability Framework (GIF)](https://www.digital.go.jp/policies/data_strategy_government_interoperability_framework)
- [COMmmmONS (Commons)](https://www.mlit.go.jp/commmmons/) (Public transportation sector)
- [Ministry of Education, Culture, Sports, Science and Technology Education Data Standards](https://www.mext.go.jp/a_menu/other/data_00001.htm) (Education sector)

## License

This repository is released under the [PDL](https://www.digital.go.jp/resources/open_data/public_data_license_v1.0) license.

## Change Log

| Version | Last Modified Date |
|----------|--------------------|
| Initial | September 4, 2026 |
