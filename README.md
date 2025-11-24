# Fujifilm LUTs Converted to XMP Profiles
This repository contains Adobe Camera Raw (.xmp) preset files converted from the official Fujifilm camera Look Up Tables (LUTs) available on the Fujifilm-X website. These profiles can be imported into Adobe Lightroom Classic, Lightroom CC, and Lightroom Mobile for use as creative profiles.
### Description
Fujifilm provides official 3D LUTs as .cube files for video color grading. This project aims to make these unique film simulations accessible to still photographers using Adobe software by converting them to the .xmp format, which is the standard for Lightroom presets and profiles.
The profiles allow users to apply classic Fujifilm looks (like Classic Chrome, Astia, Provia, etc.) to their RAW or JPEG photos directly within Lightroom, offering greater flexibility and creative control.
Contents
The repository structure should look like this:
/
├── README.md           # This file
├── LICENSE             # Project license (e.g., MIT, if you choose one)
└── XMP_Profiles/
    ├── CC.xmp (convert from Flog2)
    |-- FLOG2C-CC.xmp (convert from Flog2c)
    └── ... (other converted profiles)
## Installation (Importing into Lightroom)
The .xmp files can be imported into all modern versions of Adobe Lightroom. The specific steps vary slightly depending on the platform.
### For Lightroom Classic (Desktop)
Download and Unzip: Download or clone this repository and unzip the files to a convenient location on your computer.
Open Lightroom: Open Adobe Lightroom Classic.
Navigate to Presets: Go to the Develop module.
Import Presets: In the Presets panel on the left, click the + icon at the top of the panel and select Import Presets.
Select Files: Navigate to the XMP_Profiles folder you unzipped and select the .xmp files you want to import (or the whole folder).
Confirm: The new profiles will appear in the User Presets or a new dedicated group within the Presets panel.
### For Lightroom CC (Desktop)
Download and Unzip: Download the repository and unzip the files.
Open Lightroom CC: Launch the Lightroom CC desktop application.
Navigate to Presets: Click on the Presets icon (usually two overlapping circles) at the bottom or on the right panel.
Import Presets: Click the three-dot menu (...) at the top-right of the Presets panel and select Import Presets.
Select Files: Select the .xmp files from the unzipped folder.
Sync: The imported presets will automatically sync to your Lightroom Mobile apps via the Creative Cloud.
### For Lightroom Mobile (iOS/Android)
The easiest way is to import them via the desktop application as described above, and let them sync.
Alternatively, you can import the .zip file directly on your mobile device:
Download on Mobile: Download the .zip file of this repository directly to your phone's storage or cloud service.
Open Lightroom Mobile: Open the app and select any photo to enter the editing screen.
Navigate to Presets: Scroll the bottom menu to the right and tap Presets.
Import Presets: Ensure you are in the Yours tab, tap the three-dot menu (...) at the top-right of the screen, and select Import Presets.
Select Zip File: Navigate to the downloaded .zip file and select it. Lightroom Mobile can import the entire zip file at once.
## Usage
Once imported, the profiles can be applied to your images:
Open an image in the Develop (Classic) or Edit (CC) module.
Locate the Presets panel.
Browse and apply the Fujifilm XMP profiles to achieve the desired look.
Note: These are color profiles, designed to mimic specific color science, not just basic adjustments. They work best on RAW files but are compatible with all image types.
## Source
The original .cube files were downloaded from the official Fujifilm-X Support LUT Download Page.


