# Crime Data Analysis for Los Angeles Police Department (LAPD)

## Overview
This project aims to analyze crime data for the **Los Angeles Police Department (LAPD)** to help identify patterns in criminal behavior, with the goal of assisting in resource allocation to tackle crime effectively across different areas in Los Angeles. The data provided comes from the **Los Angeles Open Data** and contains various crime-related information, including crime types, locations, victim demographics, and timestamps.

## Dataset Description

The dataset is a CSV file `crimes.csv` with the following columns:

| Column         | Description |
|----------------|-------------|
| **DR_NO**      | Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits. |
| **Date Rptd**  | Date reported (MM/DD/YYYY). |
| **DATE OCC**   | Date of occurrence (MM/DD/YYYY). |
| **TIME OCC**   | Time of occurrence in 24-hour military time. |
| **AREA NAME**  | The 21 geographic areas or patrol divisions in Los Angeles. |
| **Crm Cd Desc**| Crime type description (e.g., theft, assault, etc.). |
| **Vict Age**   | Victim's age in years. |
| **Vict Sex**   | Victim's sex: F (Female), M (Male), X (Unknown). |
| **Vict Descent**| Victim's descent (e.g., Hispanic, Black, White, etc.). |
| **Weapon Desc**| Description of the weapon used (if applicable). |
| **Status Desc**| Status of the crime (e.g., open, closed). |
| **LOCATION**   | Street address of the crime. |

## Objective
The goal is to analyze this crime data to:
1. Identify patterns in crime occurrences.
2. Determine peak crime hours.
3. Investigate the areas with the most frequent night-time crimes.
4. Analyze victim demographics based on age groups.


