# **Chicago Address Search & Territory Locator**

A lightweight, single-file web application that allows users to search for addresses across multiple City of Chicago open data portals. 

## **📋 Features**

* **Multi-Dataset Search**: Simultaneously queries three major City of Chicago datasets:  
  * Building Permits  
  * City-Owned Land Inventory  
  * TIF Approved Projects  
* **Smart Contact Resolution**: Automatically parses permit data to identify and resolve key contacts (Owners, General Contractors, Architects, Plumbers, Masons).  
* **Data Export**: One-click CSV export of all search results.  
* **Address Normalization**: robust logic to handle variations in street directions and suffixes (e.g., "Ave" vs "Avenue").  
* **Zero-Build**: Runs entirely in the browser with no backend or build process required.

## **🛠️ Data Sources**

This application queries the **City of Chicago Data Portal** (Socrata API) in real-time.

| Dataset Name | API ID | Description |
| :---- | :---- | :---- |
| **Building Permits** | ydr8-5enu | Records of permits issued by the Department of Buildings. |
| **City-Owned Land** | aksk-kvfp | Inventory of land owned by the City of Chicago. |
| **TIF Projects** | mex4-ppfc | Projects funded through Tax Increment Financing. |

*Note: This tool relies on third-party APIs provided by the City of Chicago. Availability and uptime are subject to the City's data portal status.*
