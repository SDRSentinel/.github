<p align="center">
  <img src="https://raw.githubusercontent.com/SDRSentinel/.github/main/profile/assets/sdrsentinel.png" alt="SDRSentinel logo" width="160">
</p>

<h1 align="center">SDRSentinel</h1>

<p align="center">
  <strong>Passive RF analysis · Pulse characterization · Direction finding</strong>
</p>

<p align="center">
  <a href="https://github.com/SDRSentinel/SDRPlusPlus">Main project</a> ·
  <a href="https://github.com/SDRSentinel/SDRPlusPlus/blob/master/docs/04_kullanim_kilavuzu.md">User guide</a> ·
  <a href="https://github.com/SDRSentinel/SDRPlusPlus/blob/master/ROADMAP.md">Roadmap</a> ·
  <a href="https://github.com/SDRSentinel/SDRPlusPlus/blob/master/CONTRIBUTING.md">Contribute</a>
</p>

SDRSentinel brings together software-defined radio development and reference implementations for RF signal analysis, pulse descriptor words (PDW), coherent receivers, and direction-of-arrival estimation.

## Start here

**[SDRSentinel / SDRPlusPlus](https://github.com/SDRSentinel/SDRPlusPlus)** is the main application: an SDR++-based receiver extended with pulse analysis, KrakenSDR direction finding, and a dockable analysis workspace. The repository retains its `SDRPlusPlus` name to reflect its upstream heritage.

- **Use it:** [Installation and build instructions](https://github.com/SDRSentinel/SDRPlusPlus#building-from-source) · [User guide](https://github.com/SDRSentinel/SDRPlusPlus/blob/master/docs/04_kullanim_kilavuzu.md)
- **Explore it:** [RF tools](https://github.com/SDRSentinel/SDRPlusPlus/tree/master/misc_modules/rf_tools) · [KrakenSDR DoA](https://github.com/SDRSentinel/SDRPlusPlus/tree/master/misc_modules/kraken_doa) · [Technical documentation](https://github.com/SDRSentinel/SDRPlusPlus/tree/master/docs)
- **Help improve it:** [Report an issue](https://github.com/SDRSentinel/SDRPlusPlus/issues) · [Contribution guide](https://github.com/SDRSentinel/SDRPlusPlus/blob/master/CONTRIBUTING.md)

## Development

| Repository | Focus | Upstream |
| --- | --- | --- |
| **[SDRPlusPlus](https://github.com/SDRSentinel/SDRPlusPlus)** | Main SDRSentinel application: RF analysis, PDW extraction, and coherent direction finding. | [AlexandreRouma/SDRPlusPlus](https://github.com/AlexandreRouma/SDRPlusPlus) |
| **[GPU_SDR](https://github.com/SDRSentinel/GPU_SDR)** | GPU-accelerated USRP acquisition and resonator readout, with fork-specific Python 3, UHD 4, and CMake updates. | [nasa/GPU_SDR](https://github.com/nasa/GPU_SDR) |

## Reference implementations

These forks provide algorithm, data-format, and hardware references for experimentation. Each has its own setup requirements and maintenance history.

| Repository | Focus | Upstream |
| --- | --- | --- |
| **[gr-pdw](https://github.com/SDRSentinel/gr-pdw)** | GNU Radio pulse detection, PDW extraction, power calibration, and HDF5 logging. | [gtri/gr-pdw](https://github.com/gtri/gr-pdw) |
| **[gr-doa](https://github.com/SDRSentinel/gr-doa)** | Legacy GNU Radio direction finding with MUSIC, Root-MUSIC, and USRP X310/TwinRX examples. | [EttusResearch/gr-doa](https://github.com/EttusResearch/gr-doa) |
| **[coherent-rtlsdr](https://github.com/SDRSentinel/coherent-rtlsdr)** | Legacy 36-channel coherent RTL-SDR receiver, synchronization, and beamforming reference. | [mlaaks/coherent-rtlsdr](https://github.com/mlaaks/coherent-rtlsdr) |

## Contributing and credits

For the main application, follow the [SDRSentinel contribution guide](https://github.com/SDRSentinel/SDRPlusPlus/blob/master/CONTRIBUTING.md) and [AI contribution guidelines](https://github.com/SDRSentinel/SDRPlusPlus/blob/master/AGENTS.md). For other repositories, consult their own documentation and contribution policies.

SDRSentinel builds on the work of the SDR++ community, NASA/JPL, Georgia Tech Research Institute, Ettus Research, and the coherent-rtlsdr contributors. Upstream authorship and each repository's license remain documented in the corresponding repository.
