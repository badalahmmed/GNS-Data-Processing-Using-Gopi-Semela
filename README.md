# GNS-Data-Processing-Using-Gopi-Semela
GNS data preprocessing using Gopi Semela involves converting RINEX files, extracting dual-frequency observables, removing cycle slips, calculating satellite geometry, and deriving slant TEC. It also applies mapping functions to obtain vertical TEC for ionospheric analysis.

# CMN File Copy Script

A Windows batch script to copy all `.cmn` files from EarthScope dataset to a dedicated folder.

## Overview

This script automates the process of copying all `.cmn` files from the UNAVCO EarthScope dataset folder into a centralized subfolder for easier processing.

## Files

- `copy_cmn_files.bat` - Main batch script for copying CMN files

## Usage

1. Place the batch script in your project directory
2. Ensure the `earthscope_2022_2023_all_data` folder exists in the same directory
3. Run the script:
   ```cmd
   copy_cmn_files.bat
   ```

## What it does

- Creates `earthscope_2022_2023_all_data\All_cmn_file` directory if it doesn't exist
- Copies all `.cmn` files from the source directory to the destination
- Overwrites existing files without prompting (`/Y` flag)
- Displays confirmation message

## Requirements

- Windows OS
- `.cmn` files in the `earthscope_2022_2023_all_data` directory

## Related

For processing the copied CMN files into CSV format, see: [Convert_all_cmn_file_into_a_large_csv_file.ipynb](https://github.com/badalahmmed/GNS-Data-Processing-Using-Gopi-Semela/blob/main/Convert_all_cmn_file_into_a_large_csv_file.ipynb)

## Author

**Badal Ahmmed**  
Email: badalahmmed@gmail.com  
Date: 4 Feb 2025
