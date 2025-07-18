# FilteringDatasets
Datsets used for estimation of event filtering efficiency in the _High throughput event filtering: The interpolation-based DIF algorithm
hardware architecture_ paper.

The datasets have been uploaded to the Google drive as the files are too big to be stored directly on GitHub.\
https://drive.google.com/drive/folders/1pV0U2GFZuVrmySPI-VtKKd6KYd3xe0-3?usp=sharing

_Recorded_ directory contains datasets recorded with a DVS sensor.\
_V2E_AGH_ directory contains datasets generated with the [V2E](https://github.com/SensorsINI/v2e) tool.\
_Recorded_filtered_ directory contains datasts from _Recorded_ directory, but filtered with NN algorithm.\
_Recorded_noise_ directory contains noise recorded with a DVS sensor.

The datasets were used with the noise generator provided in [NoiseGeneratorCPP](https://github.com/vision-agh/NoiseGeneratorCPP) repository.

If you find the resources usefull, please cite the paper.
```
@article{Kowalczyk2025,
title = {High throughput event filtering: The interpolation-based DIF algorithm hardware architecture},
journal = {Microprocessors and Microsystems},
volume = {117},
pages = {105171},
year = {2025},
issn = {0141-9331},
doi = {https://doi.org/10.1016/j.micpro.2025.105171},
url = {https://www.sciencedirect.com/science/article/pii/S0141933125000390},
author = {Marcin Kowalczyk and Tomasz Kryjak},
keywords = {Dataset, Denoising, DVS, FPGA, High-throughput},
}
```
