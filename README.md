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


## Cite our Papers in your work(bib formate)

@article{Mostofa2025,
	title = {Impact of space weather on ionospheric dynamics in Bangladesh: Insights from 2022–2023 TEC analysis},
	volume = {49},
	ISSN = {0378-8121},
	url = {http://dx.doi.org/10.3329/jbas.v49i1.80229},
	DOI = {10.3329/jbas.v49i1.80229},
	number = {1},
	journal = {Journal of Bangladesh Academy of Sciences},
	publisher = {Bangladesh Academy of Sciences},
	author = {Mostofa,  Sadia and Ahmmed,  Mohammad Badal and Hasan,  Mohammad Mahdi and Some,  Jagobandhu and Sharif,  Muhammad},
	year = {2025},
	month = jun,
	pages = {103–111}
}

@inproceedings{Mostofa2022,
	title = {A GPS TEC-based Ionospheric-M Index over Malaysia},
	url = {http://dx.doi.org/10.1109/SCOReD57082.2022.9973947},
	DOI = {10.1109/scored57082.2022.9973947},
	booktitle = {2022 IEEE 20th Student Conference on Research and Development (SCOReD)},
	publisher = {IEEE},
	author = {Mostofa,  Sadia and Abdullah,  Mardina and Islam,  Mohammad Tariqul and Bahari,  Siti Aminah and Ahmmed,  Mohammad Badal},
	year = {2022},
	month = nov,
	pages = {185–189}
}

@inproceedings{Mostofa2022a,
	title = {Variations of total electron content during quiet and disturbed geomagnetic conditions over Malaysia},
	url = {http://dx.doi.org/10.1109/ISTT56288.2022.9966546},
	DOI = {10.1109/istt56288.2022.9966546},
	booktitle = {2022 IEEE 6th International Symposium on Telecommunication Technologies (ISTT)},
	publisher = {IEEE},
	author = {Mostofa,  Sadia and Abdullah,  Mardina and Islam,  Mohammad Tariqul and Bahari,  Siti Aminah and Ahmmed,  Mohammad Badal},
	year = {2022},
	month = nov,
	pages = {97–101}
}

@article{Mostofa2023,
	title = {Analysis of the Regional Ionospheric Disturbance Index During Geomagnetic Storm in 2012},
	volume = {11},
	ISSN = {2169-3536},
	url = {http://dx.doi.org/10.1109/ACCESS.2023.3311257},
	DOI = {10.1109/access.2023.3311257},
	journal = {IEEE Access},
	publisher = {Institute of Electrical and Electronics Engineers (IEEE)},
	author = {Mostofa,  Sadia and Abdullah,  Mardina and Bahari,  Siti Aminah and Islam,  Mohammad Tariqul},
	year = {2023},
	pages = {94742–94752}
}


## Author

**Badal Ahmmed**  
Email: badalahmmed@gmail.com  
Date: 4 Feb 2025
