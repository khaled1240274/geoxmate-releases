# geoxmate-releases
GeoXMate software releases packages
# GeoXMate

**GeoXMate** is a Windows desktop application for subsurface geoscience: wells and logs, seismic interpretation, structural and property modelling, volumetrics and machine learning, all in one project.

Website: https://geoxmate-website.khaled-salehhtc.workers.dev/

## Download

Get the latest installer from **[Releases](../../releases/latest)**.

Each release includes:
- `GeoXMate_Setup_<version>.exe`: the GeoXMate installer
- `SHA256SUMS.txt`: checksums for verifying your download

## What's inside

- **Data management:** wells, deviation surveys, LAS / DLIS / Excel logs, well tops, maps and seismic cubes
- **Well correlation:** assisted picking, sub-zones and zone QC
- **Seismic interpretation:** horizons, faults, attributes, 3D views, ML horizon tracking and seismic event classes
- **Fault prediction:** supervised and unsupervised
- **Geomodelling:** structural models, upscaling, seismic resampling, property modelling, and volumes with Monte Carlo uncertainty
- **Machine learning:** data exploration, QC and cleaning, algorithm comparison, feature selection, tuning, evaluation and log prediction, with PDF reports
- **GeoXMate Assistant (add-on):** an offline AI assistant that answers questions about the software and your own project, running entirely on your PC

## System requirements

- Windows 10 or 11, 64-bit
- 8 GB RAM minimum (16 GB recommended for large seismic and the Assistant)
- About 1.5 GB free disk space (the Assistant add-on needs about 2.7 GB more)

## Installation

1. Download `GeoXMate_Setup_<version>.exe` from the latest release.
2. Optional: verify it. In PowerShell run `Get-FileHash .\GeoXMate_Setup_<version>.exe -Algorithm SHA256` and check the hash matches `SHA256SUMS.txt`.
3. Run the installer and follow the steps.
4. Start GeoXMate and enter your licence when prompted.

## Licensing

GeoXMate is commercial software. A licence is required; some modules and add-ons are licensed separately. Contact us through the website for licences and trials.

## Support

Use the contact details on the website. Please include your GeoXMate version (shown in the title bar) and a screenshot of any error.

---
© 2026 Khaled Saleh. All rights reserved.
