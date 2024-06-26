# Setup a Development Environment
If you want to commit changes to the repo, we recommend you use the current versions of application software unless a newer version enables new features. Software should work with newer versions of these dependencies.

## Software dependencies:

- Python >= 3.8 (3.9 recommended)

Install the below packages from NIPM

- Measurement Link (2024 Q1 or higher)
- NI-DCPower (2023 Q4 or higher)
- NI-Scope (2023 Q4 or higher) (note: required for ripple)

Install the below packages using pip:

- ni-measurementlink-service
- ni-measurementlink-generator
- nidcpower
- niscope

Refer to [this](https://www.ni.com/docs/en-US/bundle/measurementlink/page/python-measurement-dependencies.html) document for python measurement dependencies.

## Tested with:
- Instrument Studio 2024 Q1
- TestStand 2022 Q4
- Semiconductor Device Control Add-On 2023 Q4

## Building NIPM packages
To build NIPM packages for the measurement plugin, refer to [this](build-plugin.md) document.
