[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.on004624-blue)](https://doi.org/10.82901/nemar.on004624)

An Ecosystem of Technology and Protocols for Adaptive Neuromodulation Research in Humans

This study aims to develop an ecosystem for the purpose of neurmodulation using the Cortec BCI device and BCI2000 software.

Contact: For questions regarding this dataset, please contact
mivalt.filip@mayo.edu or Miller.Kai@mayo.edu

Funding: NIH U01NS128612

## Electrode locations (19 Oct 2026; revised 22 Oct 2026)

sub-c03 has an electrodes.tsv but, in the deposit, no coordsystem.json. This branch adds one that declares `Other` / `mm` and states its limitation in `iEEGCoordinateSystemDescription`: no c03-specific source states the frame (sub-c02 and sub-c04 declare ACPC; c03 may use the same frame, but that is not confirmed), no image or surface is associated (no `IntendedFor`), and `mm` is inferred from the spread of the positions, which is physically plausible only in millimetres. No coordinate value changed. The MEF channel labels of c03 do not equal the electrodes.tsv contact names, so positions do not attach to channels in mne_bids or EEGDash; this file is metadata only. This dataset mirrors OpenNeuro; the same change belongs upstream.
