## MY BRAIN 🧠 🧟

MRI scans of my brain acquired across three scanning sessions at different institutions.

GIFs were made using [gif_your_nifti](https://github.com/miykael/gif_your_nifti) written by [Michael Notter](https://miykael.github.io/).

---

### Session 1 — Centre for Integrative Neuroscience and Neurodynamics (CINN), University of Reading

**Scanner:** 3T Siemens Prisma  
**Location:** [Centre for Integrative Neuroscience and Neurodynamics (CINN)](https://research.reading.ac.uk/cinn/), University of Reading, UK  
**Operators:** Dr Brendan Williams and Dr Shan Shen  
**Context:** Pilot scanning session

| Scan | Folder | Type | Description |
|------|--------|------|-------------|
| MPRAGE | `2023_reading/mprage/` | T1-weighted anatomical | Standard magnetisation-prepared rapid gradient echo structural scan |
| White-matter nulled T1 | `2023_reading/wmn-mprage/` | T1-weighted anatomical | Inversion recovery scan with inversion time chosen to null white matter signal |

---

### Session 2 — Centre for Human Brain Health (CHBH), University of Birmingham

**Scanner:** 3T Siemens Prisma (serial no. 166100, syngo MR E11)  
**Location:** [Centre for Human Brain Health (CHBH)](https://www.birmingham.ac.uk/research/centre-for-human-brain-health), Pritchatts Road, University of Birmingham, Birmingham, UK (B15 2RA)  
**Date:** 11 March 2026  
**Operators:** Veronika Wendler and Dr Nina Salman  
**Coil:** 32-channel head coil (Head_32)  
**Context:** MRI Training session

| Scan | Folder | Type | Sequence | Orientation | Resolution | TR / TE | Flip Angle | Description |
|------|--------|------|----------|-------------|------------|---------|------------|-------------|
| `localiser_32ch_1` | `11032026_birmingham/localiser/` | Localiser / Scout | 3D Gradient Echo (`*fl3d1_ns`) | Sagittal | 3.15 ms / 1.37 ms | 8° | 160×160, 1.6 mm slice | Standard localiser used to confirm head position and plan subsequent acquisitions |
| `noT1_petra_tra_FA_1_deg_5` | `11032026_birmingham/petra/` | Ultra-short echo time (UTE) | PETRA — Pointwise Encoding Time Reduction with Radial Acquisition (`*Petra3d1`) | Transverse (~Cor −3.6°, Sag +1.3°) | 3.61 ms / 0.07 ms | 1° | 320×320, 0.75 mm isotropic | 3D radial UTE acquisition with an ultra-short echo time (TE = 0.07 ms) and very low flip angle (1°), minimising T1 weighting ("noT1"). PETRA is used to image tissues with extremely short T2* relaxation times that are invisible to conventional MRI sequences |

---

### Session 3 — Centre for Human Brain Health (CHBH), University of Birmingham

**Scanner:** 3T Siemens Prisma (serial no. 166100, syngo MR E11)  
**Location:** [Centre for Human Brain Health (CHBH)](https://www.birmingham.ac.uk/research/centre-for-human-brain-health), Pritchatts Road, University of Birmingham, Birmingham, UK (B15 2RA)  
**Date:** 13 April 2026  
**Operators:** Veronika Wendler and Dr Martin Wilson  
**Coil:** 32-channel head coil (Head_32)  
**Context:** MRI Training session

| Scan | Folder | Type | Sequence | Orientation | Resolution | TR / TE | Inversion Time | Flip Angle | Description |
|------|--------|------|----------|-------------|------------|---------|----------------|------------|-------------|
| `localiser_32ch_1` | `13042026_birmingham/localiser/` | Localiser / Scout | 3D Gradient Echo (`*fl3d1_ns`) | Sagittal | 160×160, 1.6 mm slice | 3.15 ms / 1.37 ms | — | 8° | Standard localiser used to confirm head position and plan subsequent acquisitions |
| `T1_vol_MPR_v1_5` | `13042026_birmingham/t1-mprage/` | T1-weighted anatomical | MPRAGE (`*tfl3d1_16ns`) | Sagittal (~Cor −4.7°, Tra −0.2°) | 256×256, 1.0 mm isotropic | 2000 ms / 2.03 ms | 880 ms | 8° | Standard magnetisation-prepared rapid gradient echo structural scan |
