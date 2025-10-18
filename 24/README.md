# 🐟 Location 24: Karluk River

**Historical fish count data for Karluk River, Kodiak Island, Alaska (1882-1952)**

This directory contains historical fish count data for the Karluk River, representing the earliest systematic fish counting in Alaska. The data spans 71 years from 1882 to 1952 and provides crucial baseline information for understanding long-term salmon population trends.

## 📊 Location Overview

- **Location ID**: 24
- **Location Name**: Karluk River
- **Region**: Kodiak Island, Alaska
- **Coordinates**: 57.4°N, 154.1°W
- **Data Period**: 1882-1952 (71 years)
- **Data Type**: Historical year-total catch records
- **Primary Species**: Sockeye Salmon (Oncorhynchus nerka)

## 🐟 Species Available

| Species ID | Common Name | Scientific Name | Years Available | Total Files |
|------------|-------------|-----------------|-----------------|-------------|
| 420 | Sockeye Salmon (Red) | _Oncorhynchus nerka_ | 1882-1952 | 71 files |

## 📁 Directory Structure

```
24/
└── 420/                    # Species 420: Sockeye Salmon
    ├── 1882-karluk-river-sockeye.json
    ├── 1883-karluk-river-sockeye.json
    ├── 1884-karluk-river-sockeye.json
    ├── ...
    ├── 1951-karluk-river-sockeye.json
    └── 1952-karluk-river-sockeye.json
```

## 📈 Data Statistics

### Overall Statistics (1882-1952)
- **Total Years**: 71 years
- **Total Fish Counted**: ~50 million fish
- **Average Annual Catch**: ~700,000 fish
- **Peak Year**: 1901 (3,985,177 fish)
- **Lowest Year**: 1947 (110,236 fish)

### Decade Averages
- **1880s**: ~1.2 million fish/year
- **1890s**: ~1.8 million fish/year
- **1900s**: ~1.5 million fish/year
- **1910s**: ~1.1 million fish/year
- **1920s**: ~1.0 million fish/year
- **1930s**: ~600,000 fish/year
- **1940s**: ~300,000 fish/year
- **1950s**: ~200,000 fish/year (1950-1952 only)

## 🏔️ Historical Context

The Karluk River sockeye salmon data represents the earliest systematic fish counting in Alaska, beginning in 1882. This historical data comes directly from the National Archives Record Group 022 document titled "Catch of Karluk River Red Salmon from beginning of the canning industry in 1882 to 1952" and provides crucial baseline information for understanding long-term salmon population trends and environmental changes over 71 years.

### Primary Source Document:
- **Document**: National Archives Record Group 022
- **Title**: "Catch of Karluk River Red Salmon from beginning of the canning industry in 1882 to 1952"
- **Archive URL**: [https://catalog.archives.gov/id/312419233?objectPage=9](https://catalog.archives.gov/id/312419233?objectPage=9)
- **Image**: [Direct document image](https://s3.amazonaws.com/NARAprodstorage/lz/seattle/rg-022/95115924/Batch0003/95115924-073/95115924-073-011/95115924-073-011-0002.jpg)

### Key Historical Periods:
- **1882-1900**: Early commercial fishing era (peak catch: 3,985,177 in 1901)
- **1900-1920**: Transition to conservation management (peak catch: 2,343,104 in 1916)
- **1920-1940**: Pre-war fishing expansion (peak catch: 2,386,335 in 1926)
- **1940-1952**: Post-war fishing development (declining catches: 218,791 in 1952)

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
    "source": "National Archives Record Group 022 - Catch of Karluk River Red Salmon from beginning of the canning industry in 1882 to 1952",
    "method": "Commercial catch data from canning industry records",
    "notes": "Historical data from National Archives - single annual count per year, no daily breakdown",
    "sources": {
      "primary_source": {
        "type": "National Archives Record Group 022",
        "url": "https://catalog.archives.gov/id/312419233?objectPage=9",
        "description": "Catch of Karluk River Red Salmon from beginning of the canning industry in 1882 to 1952",
        "image_url": "https://s3.amazonaws.com/NARAprodstorage/lz/seattle/rg-022/95115924/Batch0003/95115924-073/95115924-073-011/95115924-073-011-0002.jpg"
      }
    },
    "source_attribution": "National Archives Record Group 022",
    "data_license": "Public domain - National Archives data"
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

## 🔗 Related Documentation

- **Location Info**: [location-info/karluk-river/README.md](../location-info/karluk-river/README.md)
- **Historical Context**: [location-info/karluk-river/historical-context.md](../location-info/karluk-river/historical-context.md)
- **Main Repository**: [README.md](../README.md)
- **Manifest**: [manifest.json](../manifest.json)

## 📄 License & Attribution

This data is in the **Public Domain** and available for unrestricted use.

When using this data, please attribute:
- **Data Source**: National Archives Record Group 022
- **Repository**: alaskafishcounts/afca-archive-dataset
- **Application**: Alaska Fish Count App
- **Location**: Karluk River, Kodiak Island, Alaska

## 📞 Contact & Support

- **GitHub Issues**: Report problems via repository Issues
- **Data Source**: National Archives Record Group 022
- **Repository**: alaskafishcounts/afca-archive-dataset
- **Location Documentation**: [location-info/karluk-river/](../location-info/karluk-river/)

---

**Last Updated**: October 18, 2025  
**Version**: AFCA v1.0.1  
**Data Source**: National Archives Record Group 022  
**Location**: Karluk River, Kodiak Island, Alaska  
**Repository**: alaskafishcounts/afca-archive-dataset
