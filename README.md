# 🏛️ AFCA Archive Dataset

**AFCA Archive Dataset - Historical fish count data from 1882-1952**

**Historical fish count data from Alaska Department of Fish & Game (ADF&G) monitoring stations following AFCA Location Codes Framework**

## 📊 Dataset Statistics
- **Total Files**: 71 JSON files
- **Total Locations**: 1 location with historical data
- **ID Range**: 24 (Karluk River - AFCA Sport Framework)
- **Year Range**: 1882-1952 (71 years)
- **Species**: 1 species (Sockeye Salmon)
- **Framework**: AFCA Location Codes Framework

## 🎯 About This Repository

This repository contains historical fish count data from the Karluk River monitoring station, operated by the Alaska Department of Fish & Game (ADF&G). This data represents the earliest recorded fish counts in Alaska and serves as the historical foundation for the Alaska Fish Count App archive section.

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

All files follow the ADFG standard format with consistent column structure:

```json
{
  "COLUMNS": [
     "YEAR",
    "COUNTDATE",
    "FISHCOUNT",
    "SPECIESID",
    "COUNTLOCATIONID",
    "COUNTLOCATION",
    "SPECIES"
  ],
  "DATA": [
    [
      1882,
      "July, 15 1882 00:00:00",
      15000,
      420,
      24,
      "Karluk River",
      "Sockeye"
    ]
  ],
  "metadata": {
    "location_id": 24,
    "location_name": "Karluk River",
    "species_id": 420,
    "species_name": "Sockeye Salmon",
    "year": 1882,
    "last_updated": "2025-10-18T08:00:00Z",
    "data_source": "ADF&G Historical Archive"
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
