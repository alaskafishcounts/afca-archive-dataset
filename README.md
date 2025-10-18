# 🏛️ AFCA Archive Dataset

**Historical year-total fish count data from Alaska's earliest commercial fishing era (1882-1952)**

This repository contains the foundational historical fish count data for the Alaska Fish Count App (AFCA), representing the earliest systematic fish counting records in Alaska. The data spans 71 years of commercial fishing operations and provides crucial baseline information for understanding long-term salmon population trends and environmental changes.

## 📊 Dataset Overview

- **Total Files**: 71 JSON files
- **Time Period**: 1882-1952 (71 years)
- **Data Type**: Historical year-total catch records
- **Source**: National Archives Record Group 022
- **Format**: Simplified JSON optimized for historical data
- **Framework**: AFCA Location Codes Framework

## 🗂️ Repository Structure

```
afca-archive-dataset/
├── README.md                    # This overview file
├── manifest.json                # Dataset index and metadata
├── location-info/               # Location-specific documentation
│   └── karluk-river/           # Karluk River location info
│       ├── README.md           # Location-specific README
│       └── historical-context.md # Detailed historical information
└── 24/                         # Location 24: Karluk River
    └── 420/                    # Species 420: Sockeye Salmon
        ├── 1882-karluk-river-sockeye.json
        ├── 1883-karluk-river-sockeye.json
        └── ... (71 files total)
```

## 🎯 Current Locations

| Location ID | Location Name | Species | Years Available | Data Files |
|-------------|---------------|---------|-----------------|------------|
| 24 | [Karluk River](location-info/karluk-river/) | [sockeye](24/420/) | 1882-1952 | 71 files |

*This table shows the single location currently in the archive dataset with 71 years of historical sockeye salmon data.*

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
    "created": "2025-08-18T16:03:01.541282",
    "historical_period": "Pre-ADFG monitoring era",
    "sources": {
      "primary_source": {
        "type": "National Archives Record Group 022",
        "url": "https://catalog.archives.gov/id/312419233?objectPage=9",
        "description": "Catch of Karluk River Red Salmon from beginning of the canning industry in 1882 to 1952",
        "image_url": "https://s3.amazonaws.com/NARAprodstorage/lz/seattle/rg-022/95115924/Batch0003/95115924-073/95115924-073-011/95115924-073-011-0002.jpg"
      },
      "historical_context": {
        "data_type": "Historical escapement counts",
        "period": "Early commercial fishing era",
        "methodology": "Weir operations and commercial catch records"
      }
    },
    "source_attribution": "National Archives Record Group 022",
    "data_license": "Public domain - National Archives data",
    "last_updated": "2025-10-18T08:00:00Z"
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

## 🏔️ Historical Significance

This dataset represents the earliest systematic fish counting in Alaska, beginning in 1882. The data comes directly from the National Archives Record Group 022 document titled "Catch of Karluk River Red Salmon from beginning of the canning industry in 1882 to 1952" and provides crucial baseline information for understanding long-term salmon population trends and environmental changes over 71 years.

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

## 🔄 Related Datasets

- **Sport Dataset**: Current sport fishing data (2002-2025) - [alaskafishcounts/adfg-sport-dataset](https://github.com/alaskafishcounts/adfg-sport-dataset)
- **Commercial Dataset**: Commercial fishing data (1965-2025) - [alaskafishcounts/adfg-commercial-dataset](https://github.com/alaskafishcounts/adfg-commercial-dataset)
- **SASAP Dataset**: Historical research data (1921-2017) - [alaskafishcounts/adfg-sasap-dataset](https://github.com/alaskafishcounts/adfg-sasap-dataset)

## 📋 Usage

This dataset is designed for:
- **Historical Analysis**: Long-term population trend analysis
- **Research**: Academic and scientific research on salmon populations
- **Conservation**: Baseline data for conservation planning
- **Education**: Historical context for fisheries management

## 🔗 Integration

The AFCA Archive Dataset integrates with the Alaska Fish Count App:
- **Archive Page**: Historical data visualization
- **Location Pages**: Individual monitoring station data
- **Research Tools**: Long-term trend analysis capabilities

## 📄 License

This dataset is released under **Public Domain** - National Archives data. All data originates from publicly available National Archives records and is free for use in research, education, and conservation efforts.

## 🤝 Contributing

This dataset is maintained as part of the Alaska Fish Count App project. For questions or contributions, please refer to the main AFCA repository.

---

**Alaska Fish Count App v1.0.1** - Historical Archive Dataset  
*Preserving Alaska's fishing heritage through data*