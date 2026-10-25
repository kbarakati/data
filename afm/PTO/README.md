
# PTO — AFM/PFM Dataset

## Material Information

- **Material:** PTO-based ferroelectric sample
- **Characterization:** Atomic Force Microscopy (AFM), Piezoresponse Force Microscopy (PFM), and Force Spectroscopy

## Material Description

Lead titanate (PbTiO₃, PTO) is a ferroelectric perovskite oxide grown on a potassium tantalate (KTaO₃, KTO) substrate. It exhibits spontaneous electric polarization and strong electromechanical coupling. Its ferroelectric domain structures and nonlinear electromechanical responses can be investigated using spatially resolved Piezoresponse Force Microscopy (PFM) and spectroscopy.


## Data Attribution

- **Operator:** Kamyar Barakati
- **Research group:** AE-SPM | The University of Tennessee, Knoxville
- **Data source:** Professor Hiroshi Funakubo Lab, Institute of Science Technology, Japan


## Dataset Description

This dataset contains spatially resolved AFM/PFM imaging and force spectroscopy measurements for investigating ferroelectric domain structures, local electromechanical behavior, and nonlinear response.


## Image Inventory

| Image | Filename | PFM Mode | Angle | Domain Sensitivity | Scan Size | Channels |
|---|---|---|---|---|---|---|
| 01 | PTKTO_map_0000.ibw | PFM Mapping | In-plane/Out-of-plane | Electromechanical response | 5 × 5 µm² | Height, Amplitude1, Amplitude2, Phase1, Phase2, Frequency |
| 01 | PTKTO_map_0000.ibw | PFM Mapping | In-plane/Out-of-plane | Electromechanical response | 20 × 20 µm² | Height, Amplitude1, Amplitude2, Phase1, Phase2, Frequency |
| 03 | ForceMap00.h5 | Force Spectroscopy | N/A | Nonlinear electromechanical response | 5 × 5 µm² (64 × 64 grid) | Force spectroscopy curves |


## Notes

- Original experimental files are provided without modification.
- The IBW file contains multiple imaging channels.
- The HDF5 force map contains spatially distributed spectroscopy measurements.
- Measurement units and experimental metadata should be checked before quantitative analysis.
