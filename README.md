# 🏛️ AFCA Archive Dataset

**AFCA Archive Dataset - Historical year-total fish count data from 1882-1952**

**Historical year-total fish count data from Alaska Department of Fish & Game (ADF&G) monitoring stations following AFCA Location Codes Framework**

## 📊 Dataset Statistics
- **Total Files**: 71 JSON files
- **Total Locations**: 1 location with historical data
- **ID Range**: 24 (Karluk River - AFCA Sport Framework)
- **Year Range**: 1882-1952 (71 years)
- **Species**: 1 species (Sockeye Salmon)
- **Framework**: AFCA Location Codes Framework

## 🎯 About This Repository

This repository contains historical year-total fish count data from the Karluk River monitoring station, operated by the Alaska Department of Fish & Game (ADF&G). This data represents the earliest recorded fish counts in Alaska and serves as the historical foundation for the Alaska Fish Count App archive section.

**Note**: Archive dataset files use a simplified year-total format optimized for historical data, containing single annual counts rather than daily breakdowns.

### 📋 AFCA Location Codes Framework (Archive: Historical Data)

This dataset follows the official AFCA Location Codes Framework for historical data:

#### Location ID: 24 (Karluk River)
- **Location**: Karluk River, Kodiak Island, Alaska
- **Species**: Sockeye Salmon (Species ID 420)
- **Period**: 1882-1952 (71 years of historical data)
- **Data Type**: Historical escapement counts

## 📁 Repository Structure

```
afca-archive-dataset/
├── manifest.json          # Dataset manifest and metadata
├── README.md             # This documentation
├── 24/                   # Location ID 24 (Karluk River)
│   └── 420/              # Species ID 420 (Sockeye Salmon)
│       ├── 1882-karluk-river-sockeye.json
│       ├── 1883-karluk-river-sockeye.json
│       ├── 1884-karluk-river-sockeye.json
│       ├── ...
│       └── 1952-karluk-river-sockeye.json
```

### 📋 File Naming Convention

- **Format**: `YEAR-location-slug-species-slug.json`
- **Example**: `1882-karluk-river-sockeye.json`
- **Location Slug**: Lowercase, hyphenated location name
- **Species Slug**: Lowercase, hyphenated species name

## 🐟 Supported Species

| Species ID | Common Name           | Scientific Name            | Color Code    |
| ---------- | --------------------- | -------------------------- | ------------- |
| 420        | Sockeye Salmon (Red)  | _Oncorhynchus nerka_       | Red           |

## 📍 Archive Location Directory

This dataset contains **1 location** with historical fish count data from 1882-1952.

### Historical Archive Location

| Location ID | Location Name | Species Available | Year Range |
|-------------|---------------|-------------------|------------|
| 24 | [Karluk River](https://github.com/alaskafishcounts/afca-archive-dataset/tree/main/24) | [sockeye](https://github.com/alaskafishcounts/afca-archive-dataset/tree/main/24/420) | 1882-1952 |

*This table shows the single location in the archive dataset with 71 years of historical sockeye salmon data.*

## 📊 Data Format

All files follow the AFCA Archive Dataset format optimized for historical year-total data:

```json
{
  "metadata": {
    "location_id": 24,
    "location_name": "Karluk River",
    "species_id": 420,
    "species_name": "Sockeye Salmon (Red)",
    "year": 1882,
    "data_type": "historical_catch",
    "source": "Historical canning industry records (1882-1952)",
    "method": "Commercial catch data",
    "notes": "Historical data from canning industry - single annual count, no daily breakdown",
    "created": "2025-08-18T16:03:01.541282",
    "historical_period": "Pre-ADFG monitoring era",
    "sources": {
      "primary_source": {
        "type": "ADF&G Fish Counts",
        "url": "https://www.adfg.alaska.gov/sf/FishCounts/index.cfm?ADFG=main.displayResults&COUNTLOCATIONID=24&SpeciesID=420",
        "description": "Official ADF&G fish count data for Karluk River"
      },
      "secondary_sources": [
        {
          "type": "USGS Water Data",
          "url": "https://waterdata.usgs.gov/ak/nwis/uv?site_no=15295000",
          "description": "USGS hydrological data for the location"
        }
      ],
      "historical_context": {
        "data_type": "Historical escapement counts",
        "period": "Early commercial fishing era",
        "methodology": "Weir operations and commercial catch records"
      }
    },
    "source_attribution": "Alaska Department of Fish and Game (ADF&G)",
    "data_license": "Public domain - ADF&G data",
    "last_updated": "2025-01-20T00:00:00Z"
  },
  "DATA": [
    [
      "01-01",
      "00:00",
      58800,
      "Annual catch for 1882"
    ]
  ],
  "summary": {
    "total_fish": 58800,
    "data_points": 1,
    "period": "Annual",
    "historical_significance": "Pre-ADFG commercial fishing era"
  }
}
```

## 🏔️ Historical Context

The Karluk River sockeye salmon data represents the earliest systematic fish counting in Alaska, beginning in 1882. This historical data provides crucial baseline information for understanding long-term salmon population trends and environmental changes over 71 years.

### Key Historical Periods:
- **1882-1900**: Early commercial fishing era
- **1900-1920**: Transition to conservation management
- **1920-1940**: Pre-war fishing expansion
- **1940-1952**: Post-war fishing development

## 🔄 Related Datasets

- **Sport Dataset**: Current sport fishing data (2002-2025) - [alaskafishcounts/adfg-sport-dataset](https://github.com/alaskafishcounts/adfg-sport-dataset)
- **Commercial Dataset**: Commercial fishing data (1965-2025) - [alaskafishcounts/adfg-commercial-dataset](https://github.com/alaskafishcounts/adfg-commercial-dataset)
- **SASAP Dataset**: Historical escapement data (1921-2017) - [alaskafishcounts/adfg-sasap-dataset](https://github.com/alaskafishcounts/adfg-sasap-dataset)
- **Archive Dataset**: Historical data (1882-1952) - *This dataset*

## 📄 License & Attribution

This data is in the **Public Domain** and available for unrestricted use.

When using this data, please attribute:
- **Data Source**: Alaska Department of Fish & Game (ADF&G)
- **Repository**: alaskafishcounts/afca-archive-dataset
- **Application**: Alaska Fish Count App
- **Framework**: AFCA Location Codes Framework

## 📞 Contact Support

- **GitHub Issues**: Report problems via repository Issues
- **Data Source**: Alaska Department of Fish & Game
- **Repository**: alaskafishcounts/afca-archive-dataset

---

**Last Updated**: October 18, 2025  
**Version**: AFCA v1.0.1  
**Data Source**: Alaska Department of Fish & Game (ADF&G)  
**Framework**: AFCA Location Codes Framework  
**Repository**: alaskafishcounts/afca-archive-dataset
