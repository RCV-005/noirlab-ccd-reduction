# NOIRLab CCD Data Reduction

This project explores the basic reduction of archival CCD observations
obtained from the NSF NOIRLab Astro Data Archive.

## Dataset

- Observatory: Cerro Tololo Inter-American Observatory (CTIO)
- Telescope: CTIO 0.9 m
- Instrument: CFCCD / CCD Imager
- Detector: Tek2K_3
- Science target: 158P
- Filter: r
- Observation night: 2018-04-18
- Science exposure: 60 s

## Calibration data

- 10 bias/zero frames
- 5 R-band dome flats
- No dark frames were available for the selected observing night.

## Workflow

The planned reduction workflow is:

1. Inspect raw FITS data and metadata.
2. Overscan correction and trimming.
3. Create a master bias.
4. Create a normalized master flat.
5. Calibrate the science image.
6. Inspect and analyze the reduced image.

Raw FITS files are not included in this repository.