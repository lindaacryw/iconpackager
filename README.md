# IconPackager

IconPackager is a Python program that allows users to download and apply sets of icons to personalize the Windows desktop interface. This tool simplifies the process of changing desktop icons by automating the download and application steps.

## Features

- Download icon packs from a specified URL.
- Extract downloaded icon packs.
- Apply icons to the Windows desktop interface (future implementation).

## Requirements

- Python 3.x
- `requests` library
- `shutil` and `zipfile` libraries (standard Python libraries)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/iconpackager.git
   cd iconpackager
   ```

2. Install the required Python packages:

   ```bash
   pip install requests
   ```

## Usage

1. Run the IconPackager script with the URL of the icon pack you want to download:

   ```bash
   python icon_packager.py
   ```

2. Replace the `url` variable in the script with the actual URL of the icon pack you want to download.

## Notes

- The `apply_icons` function is a placeholder and needs to be implemented with system-specific functionality to apply icons to the Windows desktop interface.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.